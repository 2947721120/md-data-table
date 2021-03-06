## Change Log

#### Version 0.10.3
###### April 1, 2016

**Bug Fixes**

* The pagination directive will now display `0 - 0 of 0` if the total is zero.

#### Version 0.10.2
###### March 30, 2016

**Bug Fixes**

* Fixes bug where the select all checkbox would not be added to subsequent tables.

#### Version 0.10.1
###### March 27, 2016

**New Features**

* Pagination elements may now be disabled with the `ng-disabled` attribute.

**Bug Fixes & Improvements**

* When the total changes, the pagination directive will check if the current page is greater than the total number of pages. If it is greater, the page will be set to the last available page.

#### Version 0.10.0
###### March 27, 2016

**Breaking Changes**

* Multiple selection must now be enabled with the `multiple` attribute.

  ```html
  <table md-table md-row-select multiple ng-model="selected">
  ```

* Unique identifiers must now be a property of the item.

  ```html
    <!-- use item.id as the unique identifier -->
    <tr md-row md-select="item" md-select-id="id" md-auto-select ng-repeat="item in items">
  ```
  
* Some folks do not want the pagination limit options to be enabled. To compensate, the pagination limit options must now be enabled with the `mdLimitOptions` attribute. The `mdLimitOptions` attribute is a replacement of the `mdOptions` attribute and the default limit options have been removed.

  ```html
    <md-table-pagination md-limit-options="[5, 10, 15]">
  ```

**New Features**

* Single item selection is now possible and enabled by default. Be aware that the `ngModel` attribute must still be an array; for now.

* The pagination limit options are now disabled be default.

* The pagination page selector is now virtualized to improve performance.

**Bug Fixes & Improvements**

* Preselected items will now be displayed by the UI. Keep in mind that if preselected items are not strictly equal to items in the table you will need to use the `mdSelectId` attribute.

* Changes to the pagination label will now take effect without needing to reload the page.

* Pagination and reorder callbacks are now deferred until the next digest cycle using Angular Material's `$mdUtil.nextTick` function to allow 2-way data binding to complete and to avoid confusion. This means your local scope variables will have the same value as the parameters passed to the `md-on-reorder` and `md-on-paginate` callbacks.