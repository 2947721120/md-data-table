##CN  此为机器翻译中文,请参照EN下理解
<article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-material-design-data-table" class="anchor" href="#material-design-data-table" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Material Design Data Table" data-dst="材料设计数据表">材料设计数据表</trans></h1>

<p><trans data-src="This module is an effort to implement Material Design data tables in " data-dst="该模块是一个努力实现材料设计数据表">该模块是一个努力实现材料设计数据表</trans><a href="https://material.angularjs.org/latest/#/"><trans data-src="Angular Material" data-dst="角材">角材</trans></a><trans data-src=". Data tables are used to present raw data sets and usually appear in desktop enterprise applications. Data tables are particularly useful for visualizing and manipulating large data sets." data-dst="。数据表是用来呈现原始数据集，通常出现在桌面应用的企业。数据表的可视化和操纵大型数据集特别有用。" style="background: transparent;">。数据表是用来呈现原始数据集，通常出现在桌面应用的企业。数据表的可视化和操纵大型数据集特别有用。</trans></p>

<p><trans data-src="Specification for Material Design data tables can be found " data-dst="材料设计数据表规范可以发现">材料设计数据表规范可以发现</trans><a href="http://www.google.com/design/spec/components/data-tables.html"><trans data-src="here" data-dst="在这里">在这里</trans></a><trans data-src="." data-dst="。">。</trans></p>

<ul>
<li><a href="#license"><trans data-src="License" data-dst="许可证">许可证</trans></a></li>
<li><a href="#demo"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><a href="#installation"><trans data-src="Installation" data-dst="安装">安装</trans></a></li>
<li><a href="#usage"><trans data-src="Usage" data-dst="使用">使用</trans></a></li>
<li><a href="/2947721120/md-data-table/blob/master/CHANGELOG.md"><trans data-src="Change Log" data-dst="更改日志">更改日志</trans></a></li>
<li><a href="#api-documentation"><trans data-src="API Documentation" data-dst="API文档">API文档</trans></a></li>
<li><a href="#contributing"><trans data-src="Contributing" data-dst="贡献">贡献</trans></a></li>
</ul>

<h2><a id="user-content-license" class="anchor" href="#license" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="License" data-dst="许可证">许可证</trans></h2>

<p><trans data-src="This software is provided free of charge and without restriction under the " data-dst="这个软件是免费提供的，没有约束的">这个软件是免费提供的，没有约束的</trans><a href="/2947721120/md-data-table/blob/master/LICENSE.md"><trans data-src="MIT License" data-dst="MIT许可证">MIT许可证</trans></a></p>

<h2><a id="user-content-demo" class="anchor" href="#demo" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Demo" data-dst="演示">演示</trans></h2>

<p><trans data-src="A live " data-dst="一个活" style="background: transparent;">一个活</trans><a href="http://danielnagy.me/md-data-table"><trans data-src="demo" data-dst="演示">演示</trans></a><trans data-src="." data-dst="。">。</trans></p>

<p><trans data-src="A fork-able " data-dst="叉能">叉能</trans><a href="http://codepen.io/anon/pen/BjvLVJ?editors=1010"><trans data-src="Codepen" data-dst="CodePen">CodePen</trans></a><trans data-src=". Please use this to reproduce any issues you may be experiencing." data-dst="。请使用此复制您可能遇到的任何问题。">。请使用此复制您可能遇到的任何问题。</trans></p>

<h2><a id="user-content-installation" class="anchor" href="#installation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Installation" data-dst="安装">安装</trans></h2>

<h4><a id="user-content-using-bower" class="anchor" href="#using-bower" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Using Bower" data-dst="利用凉亭">利用凉亭</trans></h4>

<p><trans data-src="This package is installable through the Bower package manager." data-dst="这个包是安装包管理器通过凉亭。">这个包是安装包管理器通过凉亭。</trans></p>

<pre><code><trans data-src="bower install angular-material-data-table --save
" data-dst="鲍尔安装角材料数据表-保存" style="background: transparent;">鲍尔安装角材料数据表-保存</trans></code></pre>

<p><trans data-src="In your " data-dst="在你的">在你的</trans><code><trans data-src="index.html" data-dst="index.html"><trans data-src="index.html" data-dst="index.html">index.html</trans></trans></code><trans data-src=" file, include the data table module and style sheet." data-dst="文件，包括数据表模块和样式表。">文件，包括数据表模块和样式表。</trans></p>

<div class="highlight highlight-text-html-basic"><pre><span class="pl-c"><trans data-src="<!-- style sheet -->" data-dst="<！——样式表——>">&lt;！——样式表——&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="link" data-dst="链接">链接</trans></span> <span class="pl-e"><trans data-src="href" data-dst="href"><trans data-src="href" data-dst="href">href</trans></trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="bower_components/angular-material-data-table/dist/md-data-table.min.css" data-dst="bower_components /角材料数据表/距离/ md-data-table.min.css">bower_components /角材料数据表/距离/ md-data-table.min.css</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="rel" data-dst="REL">REL</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="stylesheet" data-dst="样式表">样式表</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="type" data-dst="类型">类型</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="text/css" data-dst="文本/ CSS">文本/ CSS</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>/&gt;
<span class="pl-c"><trans data-src="<!-- module -->" data-dst="<！模块">&lt;！模块</trans></span>
&lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="type" data-dst="类型">类型</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="text/javascript" data-dst="文字/ JavaScript">文字/ JavaScript</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="bower_components/angular-material-data-table/dist/md-data-table.min.js" data-dst="bower_components /角材料数据表/距离/ md-data-table.min.js">bower_components /角材料数据表/距离/ md-data-table.min.js</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</pre></div>

<p><trans data-src="Include the " data-dst="包括">包括</trans><code><trans data-src="md.data.table" data-dst="md.data.table"><trans data-src="md.data.table" data-dst="md.data.table">md.data.table</trans></trans></code><trans data-src=" module as a dependency in your application." data-dst="模块在您的应用程序依赖。">模块在您的应用程序依赖。</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="myApp" data-dst="MyApp">MyApp</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", [" data-dst="，[">，[</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="ngMaterial" data-dst="ngmaterial">ngmaterial</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", " data-dst="，">，</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="md.data.table" data-dst="md.data.table">md.data.table</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src="]);" data-dst="]）；">]）；</trans></pre></div>

<h4><a id="user-content-using-npm-and-browserify-or-jspm" class="anchor" href="#using-npm-and-browserify-or-jspm" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Using npm and Browserify (or JSPM)" data-dst="使用NPM和browserify（或jspm）">使用NPM和browserify（或jspm）</trans></h4>

<p><trans data-src="In addition, this package may be installed using npm." data-dst="此外，该软件包可以安装使用NPM。">此外，该软件包可以安装使用NPM。</trans></p>

<pre><code><trans data-src="npm install angular-material-data-table --save
" data-dst="NPM安装角材料数据表保存">NPM安装角材料数据表保存</trans></code></pre>

<p><trans data-src="You may use Browserify to inject this module into your application." data-dst="你可以使用在你的应用browserify注入这个模块。">你可以使用在你的应用browserify注入这个模块。</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="myApp" data-dst="MyApp">MyApp</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", [" data-dst="，[">，[</trans><span class="pl-c1"><trans data-src="require" data-dst="要求">要求</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="angular-material-data-table" data-dst="角材料数据表">角材料数据表</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=")]);" data-dst="）]）；">）]）；</trans></pre></div>

<h2><a id="user-content-usage" class="anchor" href="#usage" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Usage" data-dst="使用">使用</trans></h2>

<p><strong><trans data-src="Example Controller" data-dst="例如控制器">例如控制器</trans></strong></p>

<div class="highlight highlight-source-js"><pre><span class="pl-c"><trans data-src="// Assume we have a $nutrition service that provides an API for communicating with the server" data-dst="/ /假设我们有一个为营养服务，提供了一个API，用于与服务器通信">/ /假设我们有一个为营养服务，提供了一个API，用于与服务器通信</trans></span>

<span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="demoApp" data-dst="DemoApp">DemoApp</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=")." data-dst="）。">）。</trans><span class="pl-en"><trans data-src="controller" data-dst="控制器">控制器</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="sampleController" data-dst="samplecontroller">samplecontroller</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", [" data-dst="，[">，[</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="$nutrition" data-dst="为营养">为营养</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", " data-dst="，">，</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", " data-dst="，">，</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="$nutrition" data-dst="为营养">为营养</trans></span><trans data-src=", " data-dst="，">，</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src=") {
  " data-dst="）{">）{</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="use strict" data-dst="用严格的">用严格的</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=";

  " data-dst="；">；</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-c1"><trans data-src="selected" data-dst="挑选">挑选</trans></span> <span class="pl-k">=</span><trans data-src=" [];

  " data-dst="[ ]；">[ ]；</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="query" data-dst="查询">查询</trans></span> <span class="pl-k">=</span><trans data-src=" {
    order" data-dst="{ 
秩序">{ 
秩序</trans><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="name" data-dst="姓名">姓名</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=",
    limit" data-dst="
限制，">
限制，</trans><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-c1"><trans data-src="5" data-dst="五">五</trans></span><trans data-src=",
    page" data-dst="，
">，
</trans><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-c1"><trans data-src="1" data-dst="一">一</trans></span><trans data-src="
  };

  " data-dst="}；">}；</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span> <span class="pl-en"><trans data-src="success" data-dst="成功">成功</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-smi"><trans data-src="desserts" data-dst="甜点">甜点</trans></span><trans data-src=") {
    " data-dst="）{">）{</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="desserts" data-dst="甜点">甜点</trans></span> <span class="pl-k">=</span><trans data-src=" desserts;
  }

  " data-dst="
甜点；">
甜点；</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="getDesserts" data-dst="getdesserts">getdesserts</trans></span> <span class="pl-k">=</span> <span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" () {
    " data-dst="（）{">（）{</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="promise" data-dst="承诺">承诺</trans></span> <span class="pl-k">=</span> <span class="pl-smi"><trans data-src="$nutrition" data-dst="为营养">为营养</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="desserts" data-dst="甜点">甜点</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="get" data-dst="得到">得到</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="query" data-dst="查询">查询</trans></span><trans data-src=", success)." data-dst="，成功）。">，成功）。</trans><span class="pl-smi"><trans data-src="$promise" data-dst="美元的承诺">美元的承诺</trans></span><trans data-src=";
  };

}]);" data-dst="；
 }；
 
 } ]；">；
 }；
 
 } ]；</trans></pre></div>

<p><strong><trans data-src="Example Template" data-dst="实例模板">实例模板</trans></strong></p>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-toolbar" data-dst="工具栏">工具栏</trans></span> <span class="pl-e"><trans data-src="class" data-dst="类">类</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="md-table-toolbar md-default" data-dst="MD MD默认表工具栏">MD MD默认表工具栏</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
  &lt;<span class="pl-ent"><trans data-src="div" data-dst="DIV">DIV</trans></span> <span class="pl-e"><trans data-src="class" data-dst="类">类</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="md-toolbar-tools" data-dst="MD工具栏工具">MD工具栏工具</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="span" data-dst="跨度">跨度</trans></span>&gt;Nutrition&lt;/<span class="pl-ent"><trans data-src="span" data-dst="跨度">跨度</trans></span>&gt;
  &lt;/<span class="pl-ent"><trans data-src="div" data-dst="DIV">DIV</trans></span>&gt;
&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-toolbar" data-dst="工具栏">工具栏</trans></span>&gt;

<span class="pl-c"><trans data-src="<!-- exact table from live demo -->" data-dst="<！——精确表从现场演示——>">&lt;！——精确表从现场演示——&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-container" data-dst="表容器">表容器</trans></span>&gt;
  &lt;<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span> <span class="pl-e"><trans data-src="md-table" data-dst="MD表">MD表</trans></span> <span class="pl-e"><trans data-src="md-row-select" data-dst="MD行选择">MD行选择</trans></span> <span class="pl-e"><trans data-src="multiple" data-dst="多">多</trans></span> <span class="pl-e"><trans data-src="ng-model" data-dst="NG型">NG型</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="selected" data-dst="挑选">挑选</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-progress" data-dst="医学的进步">医学的进步</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="promise" data-dst="承诺">承诺</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="thead" data-dst="螺纹">螺纹</trans></span> <span class="pl-e"><trans data-src="md-head" data-dst="的MD -好的">的MD -好的</trans></span> <span class="pl-e"><trans data-src="md-order" data-dst="MD命令">MD命令</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="query.order" data-dst="query.order">query.order</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-on-reorder" data-dst="MD -排序">MD -排序</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="getDesserts" data-dst="getdesserts">getdesserts</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
      &lt;<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span> <span class="pl-e"><trans data-src="md-row" data-dst="的MD -行">的MD -行</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-order-by" data-dst="MD命令">MD命令</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="nameToLower" data-dst="nametolower">nametolower</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;<span class="pl-ent"><trans data-src="span" data-dst="跨度">跨度</trans></span>&gt;Dessert (100g serving)&lt;/<span class="pl-ent"><trans data-src="span" data-dst="跨度">跨度</trans></span>&gt;&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span> <span class="pl-e"><trans data-src="md-order-by" data-dst="MD命令">MD命令</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="calories.value" data-dst="calories.value">calories.value</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;<span class="pl-ent"><trans data-src="span" data-dst="跨度">跨度</trans></span>&gt;Calories&lt;/<span class="pl-ent"><trans data-src="span" data-dst="跨度">跨度</trans></span>&gt;&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span>&gt;Fat (g)&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span>&gt;Carbs (g)&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span>&gt;Protein (g)&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span>&gt;Sodium (mg)&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span>&gt;Calcium (%)&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span>&gt;Iron (%)&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
      &lt;/<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span>&gt;
    &lt;/<span class="pl-ent"><trans data-src="thead" data-dst="螺纹">螺纹</trans></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="tbody" data-dst="TBODY">TBODY</trans></span> <span class="pl-e"><trans data-src="md-body" data-dst="MD的身体">MD的身体</trans></span>&gt;
      &lt;<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span> <span class="pl-e"><trans data-src="md-row" data-dst="的MD -行">的MD -行</trans></span> <span class="pl-e"><trans data-src="md-select" data-dst="MD选择">MD选择</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="dessert" data-dst="甜点">甜点</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-select-id" data-dst="MD id">MD id</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="name" data-dst="姓名">姓名</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-auto-select" data-dst="MD自动选择">MD自动选择</trans></span> <span class="pl-e"><trans data-src="ng-repeat" data-dst="NG的重复">NG的重复</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="dessert in desserts.data" data-dst="在desserts.data甜点">在desserts.data甜点</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.name}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.calories.value}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.fat.value | number: 1}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.carbs.value}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.protein.value | number: 1}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.sodium.value}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.calcium.value}}{{dessert.calcium.unit}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
        &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.iron.value}}{{dessert.iron.unit}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
      &lt;/<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span>&gt;
    &lt;/<span class="pl-ent"><trans data-src="tbody" data-dst="TBODY">TBODY</trans></span>&gt;
  &lt;/<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span>&gt;
&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-container" data-dst="表容器">表容器</trans></span>&gt;

&lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span> <span class="pl-e"><trans data-src="md-limit" data-dst="MD极限">MD极限</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="query.limit" data-dst="query.limit">query.limit</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-limit-options" data-dst="MD的限制选项">MD的限制选项</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="[5, 10, 15]" data-dst="[ 5，10，15 ]">[ 5，10，15 ]</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-page" data-dst="MD">MD</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="query.page" data-dst="query.page">query.page</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-total" data-dst="MD总">MD总</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="{{desserts.count}}" data-dst="desserts.count { }">desserts.count { }</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-on-paginate" data-dst="MD的页码">MD的页码</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="getDesserts" data-dst="getdesserts">getdesserts</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-page-select" data-dst="MD页面选择">MD页面选择</trans></span>&gt;&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span>&gt;
</pre></div>

<h2><a id="user-content-api-documentation" class="anchor" href="#api-documentation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="API Documentation" data-dst="API文档">API文档</trans></h2>

<p><strong><trans data-src="v0.10.x" data-dst="v0.10 X。">v0.10 X。</trans></strong></p>

<ul>
<li><a href="#column-sorting"><trans data-src="Column Sorting" data-dst="列排序">列排序</trans></a></li>
<li><a href="#edit-dialogs"><trans data-src="Edit Dialogs" data-dst="编辑对话框">编辑对话框</trans></a></li>
<li><a href="#inline-menus"><trans data-src="Inline Menus" data-dst="内置菜单">内置菜单</trans></a></li>
<li><a href="#numeric-columns"><trans data-src="Numeric Columns" data-dst="数字列">数字列</trans></a></li>
<li><a href="#pagination"><trans data-src="Pagination" data-dst="分页">分页</trans></a></li>
<li><a href="#row-selection"><trans data-src="Row Selection" data-dst="行选择">行选择</trans></a></li>
<li><a href="#table-progress"><trans data-src="Table Progress" data-dst="表的进展">表的进展</trans></a></li>
<li><a href="#table-toolbars"><trans data-src="Table Toolbars" data-dst="表格工具栏">表格工具栏</trans></a></li>
</ul>

<p><strong><trans data-src="Earlier Versions" data-dst="早期的版本">早期的版本</trans></strong></p>

<ul>
<li><a href="https://github.com/daniel-nagy/md-data-table/tree/v0.9.x#api-documentation"><trans data-src="0.9.x" data-dst="0.9.x"><trans data-src="0.9.x" data-dst="0.9.x">0.9.x</trans></trans></a></li>
<li><a href="https://github.com/daniel-nagy/md-data-table/tree/legacy#api-documentation">&lt;=0.8.14</a></li>
</ul>

<blockquote>
<p><trans data-src="Tables are sorted alphabetically by their first column.
I will be " data-dst="表是按字母顺序排列的第一列。
我会">表是按字母顺序排列的第一列。
我会</trans><strong><trans data-src="camelCasing" data-dst="camelcasing">camelcasing</trans></strong><trans data-src=" attributes in tables (otherwise the cells would wrap and be difficult to read) but don't forget to " data-dst="属性表（否则细胞会包裹和难以阅读）但不要忘记">属性表（否则细胞会包裹和难以阅读）但不要忘记</trans><strong><trans data-src="snake-case" data-dst="蛇案">蛇案</trans></strong><trans data-src=" them in your template." data-dst="他们在你的模板。">他们在你的模板。</trans></p>
</blockquote>

<h3><a id="user-content-column-sorting" class="anchor" href="#column-sorting" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Column Sorting" data-dst="列排序">列排序</trans></h3>

<table><thead>
<tr>
<th align="left"><trans data-src="Attribute" data-dst="属性">属性</trans></th>
<th align="left"><trans data-src="Element" data-dst="元素">元素</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="mdDesc" data-dst="mddesc">mddesc</trans></code></td>
<td align="left"><code><trans data-src="mdColumn" data-dst="mdcolumn">mdcolumn</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="If present, the column will sort descending first. The default is to sort ascending first." data-dst="如果存在，将第一列降序排序。默认为升序排序第一。">如果存在，将第一列降序排序。默认为升序排序第一。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdOnReorder" data-dst="mdonreorder">mdonreorder</trans></code></td>
<td align="left"><code><trans data-src="mdHead" data-dst="mdhead">mdhead</trans></code></td>
<td align="left"><code><trans data-src="function" data-dst="功能">功能</trans></code></td>
<td align="left"><trans data-src="A callback function for when the order changes. The callback will receive the new order." data-dst="回调函数的顺序变化时。回调将获得新的订单。">回调函数的顺序变化时。回调将获得新的订单。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdOrder" data-dst="mdorder">mdorder</trans></code></td>
<td align="left"><code><trans data-src="mdHead" data-dst="mdhead">mdhead</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><trans data-src="A variable to bind the sort order to." data-dst="变量绑定的排序顺序。">变量绑定的排序顺序。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdOrderBy" data-dst="mdorderby">mdorderby</trans></code></td>
<td align="left"><code><trans data-src="mdColumn" data-dst="mdcolumn">mdcolumn</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><trans data-src="The value to bind to the sort order." data-dst="绑定到排序的值。">绑定到排序的值。</trans></td>
</tr>
</tbody></table>

<p><trans data-src="When the user clicks the " data-dst="当在用户点击">当在用户点击</trans><code><trans data-src="md-column" data-dst="MD柱">MD柱</trans></code><trans data-src=" element, the value of the " data-dst="元，值了">元，值了</trans><code><trans data-src="md-order-by" data-dst="MD命令">MD命令</trans></code><trans data-src=" attribute will be bound to the variable provided to the " data-dst="属性将提供给变量">属性将提供给变量</trans><code><trans data-src="md-order" data-dst="MD命令">MD命令</trans></code><trans data-src=" attribute on the " data-dst="属性上">属性上</trans><code><trans data-src="md-head" data-dst="的MD -好的">的MD -好的</trans></code><trans data-src=" element. If the column is already sorted by that value, a minus sign " data-dst="元素如果列已经被价值排序，减号">元素如果列已经被价值排序，减号</trans><code><trans data-src="-" data-dst="—"><trans data-src="—" data-dst="—">—</trans></trans></code><trans data-src=" will be prefixed to the value. For most query languages, this is the universal symbol to sort descending." data-dst="将值的前缀。对于大多数的查询语言，这是降序的通用符号。">将值的前缀。对于大多数的查询语言，这是降序的通用符号。</trans></p>

<p><trans data-src="The variable can be used to send a query to the server or as the " data-dst="变量可以用来查询发送到服务器或为">变量可以用来查询发送到服务器或为</trans><code><trans data-src="orderBy" data-dst="OrderBy">OrderBy</trans></code><trans data-src=" property of an " data-dst="的财产">的财产</trans><code><trans data-src="ng-repeat" data-dst="NG的重复">NG的重复</trans></code><trans data-src=" expression." data-dst="表达。">表达。</trans></p>

<p><strong><trans data-src="Example Using ngRepeat" data-dst="以ngrepeat">以ngrepeat</trans></strong></p>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-container" data-dst="表容器">表容器</trans></span>&gt;
  &lt;<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span> <span class="pl-e"><trans data-src="md-table" data-dst="MD表">MD表</trans></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="thead" data-dst="螺纹">螺纹</trans></span> <span class="pl-e"><trans data-src="md-head" data-dst="的MD -好的">的MD -好的</trans></span> <span class="pl-e"><trans data-src="md-order" data-dst="MD命令">MD命令</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="myOrder" data-dst="我的命令">我的命令</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
      <span class="pl-c"><trans data-src="<!-- when the user clicks this cell, the myOrder variable will get the value 'nameToLower' -->" data-dst="<！当用户点击该单元格，myOrder变量将有价值的nametolower -->">&lt;！当用户点击该单元格，myOrder变量将有价值的nametolower --&gt;</trans></span>
      &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-order-by" data-dst="MD命令">MD命令</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="nameToLower" data-dst="nametolower">nametolower</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;Dessert (100g serving)&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
      <span class="pl-c"><trans data-src="<!-- the variable myOrder will not be changed when this cell is clicked -->" data-dst="<！——变我的命令将不会改变，当细胞被点击-->">&lt;！——变我的命令将不会改变，当细胞被点击--&gt;</trans></span>
      &lt;<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span> <span class="pl-e"><trans data-src="md-column" data-dst="MD柱">MD柱</trans></span> <span class="pl-e"><trans data-src="md-numeric" data-dst="MD值">MD值</trans></span>&gt;Calories&lt;/<span class="pl-ent"><trans data-src="th" data-dst="TH">TH</trans></span>&gt;
    &lt;/<span class="pl-ent"><trans data-src="thead" data-dst="螺纹">螺纹</trans></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="tbody" data-dst="TBODY">TBODY</trans></span> <span class="pl-e"><trans data-src="md-body" data-dst="MD的身体">MD的身体</trans></span>&gt;
      <span class="pl-c"><trans data-src="<!-- we can let ng-repeat sort the columns for us -->" data-dst="<！我们可以让NG重复排序我们栏目-->">&lt;！我们可以让NG重复排序我们栏目--&gt;</trans></span>
      &lt;<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span> <span class="pl-e"><trans data-src="ng-repeat" data-dst="NG的重复">NG的重复</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="dessert in desserts | orderBy: myOrder" data-dst="在甜点| OrderBy甜点：我的命令">在甜点| OrderBy甜点：我的命令</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span>&gt;
    &lt;/<span class="pl-ent"><trans data-src="tbody" data-dst="TBODY">TBODY</trans></span>&gt;
  &lt;/<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span>&gt;
&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-container" data-dst="表容器">表容器</trans></span>&gt;</pre></div>

<h3><a id="user-content-edit-dialogs" class="anchor" href="#edit-dialogs" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Edit Dialogs" data-dst="编辑对话框">编辑对话框</trans></h3>

<p><trans data-src="Tables may require basic text editing. This module includes a service for displaying edit dialogs to modify text or anything else really. The service provides presets for both small and large edit dialogs designed for manipulating text. It also has full support for creating custom dialogs so you can be as creative as you want to be." data-dst="表可能需要基本的文本编辑。该模块包括服务显示编辑对话框来修改文本或其他任何东西真的。服务提供小型和大型的编辑设计操作文本对话框预置。它还具有用于创建自定义对话框，你可以做你想做的创意充分的支持。">表可能需要基本的文本编辑。该模块包括服务显示编辑对话框来修改文本或其他任何东西真的。服务提供小型和大型的编辑设计操作文本对话框预置。它还具有用于创建自定义对话框，你可以做你想做的创意充分的支持。</trans></p>

<p><trans data-src="Unlike Angular Material dialogs, the preset methods will open the dialog." data-dst="不像角材料对话框，设定方法将打开对话框。">不像角材料对话框，设定方法将打开对话框。</trans></p>

<p><strong><trans data-src="Restrictions" data-dst="限制">限制</trans></strong></p>

<ul>
<li><trans data-src="The dialog will always receive a new isolated scope." data-dst="对话总是会收到一个新的分离范围。">对话总是会收到一个新的分离范围。</trans></li>
<li><trans data-src="You must provide a " data-dst="你必须提供一个">你必须提供一个</trans><code><trans data-src="targetEvent" data-dst="targetevent">targetevent</trans></code><trans data-src=" and the event target must be a table cell." data-dst="而事件的目标必须是一个单元格。">而事件的目标必须是一个单元格。</trans></li>
</ul>

<p><strong><trans data-src="Example" data-dst="例子">例子</trans></strong></p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="editComment" data-dst="editcomment">editcomment</trans></span> <span class="pl-k">=</span> <span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-c1"><trans data-src="event" data-dst="事件">事件</trans></span><trans data-src=", " data-dst="，">，</trans><span class="pl-smi"><trans data-src="dessert" data-dst="甜点">甜点</trans></span><trans data-src=") {
  " data-dst="）{">）{</trans><span class="pl-c"><trans data-src="// if auto selection is enabled you will want to stop the event" data-dst="//如果启用自动选择你将要停止活动">//如果启用自动选择你将要停止活动</trans></span>
  <span class="pl-c"><trans data-src="// from propagating and selecting the row" data-dst="/ /传播和选择行">/ /传播和选择行</trans></span>
  <span class="pl-c1"><trans data-src="event" data-dst="事件">事件</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="stopPropagation" data-dst="里面">里面</trans></span><trans data-src="();

  " data-dst="（）；">（）；</trans><span class="pl-c"><trans data-src="/* " data-dst="/ *">/ *</trans></span>
<span class="pl-c"><trans data-src="   * messages is commented out because there is a bug currently" data-dst="*消息是说因为有一个bug，目前">*消息是说因为有一个bug，目前</trans></span>
<span class="pl-c"><trans data-src="   * with ngRepeat and ngMessages were the messages are always" data-dst="* ngrepeat和ngmessages的消息总是">* ngrepeat和ngmessages的消息总是</trans></span>
<span class="pl-c"><trans data-src="   * displayed even if the error property on the ngModelController" data-dst="*即使在ngmodelcontroller错误属性显示">*即使在ngmodelcontroller错误属性显示</trans></span>
<span class="pl-c"><trans data-src="   * is not set, I've included it anyway so you get the idea" data-dst="*不定，我已经包括了所以你懂的">*不定，我已经包括了所以你懂的</trans></span>
<span class="pl-c"><trans data-src="   */" data-dst="* /">* /</trans></span>

  <span class="pl-k"><trans data-src="var" data-dst="VaR">VaR</trans></span><trans data-src=" promise " data-dst="承诺">承诺</trans><span class="pl-k">=</span> <span class="pl-smi"><trans data-src="$mdEditDialog" data-dst="mdeditdialog美元">mdeditdialog美元</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-c1"><trans data-src="small" data-dst="小">小</trans></span><trans data-src="({
    " data-dst="（{">（{</trans><span class="pl-c"><trans data-src="// messages: {" data-dst="/ /信息：{">/ /信息：{</trans></span>
    <span class="pl-c"><trans data-src="//   test: 'I don\'t like tests!'" data-dst="/ /测试：“我不喜欢考试！”">/ /测试：“我不喜欢考试！”</trans></span>
    <span class="pl-c"><trans data-src="// }," data-dst="/ }，">/ }，</trans></span><trans data-src="
    modelValue" data-dst="模型">模型</trans><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-smi"><trans data-src="dessert" data-dst="甜点">甜点</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="comment" data-dst="评论">评论</trans></span><trans data-src=",
    placeholder" data-dst="，
">，
</trans><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="Add a comment" data-dst="添加评论">添加评论</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=",
    " data-dst="，">，</trans><span class="pl-en"><trans data-src="save" data-dst="保存"><trans data-src="保存" data-dst="保存">保存</trans></trans></span><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="input" data-dst="输入">输入</trans></span><trans data-src=") {
      " data-dst="）{">）{</trans><span class="pl-smi"><trans data-src="dessert" data-dst="甜点">甜点</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="comment" data-dst="评论">评论</trans></span> <span class="pl-k">=</span> <span class="pl-smi"><trans data-src="input" data-dst="输入">输入</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="$modelValue" data-dst="元模型">元模型</trans></span><trans data-src=";
    },
    targetEvent" data-dst="
 }，
 targetevent；">
 }，
 targetevent；</trans><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-c1"><trans data-src="event" data-dst="事件">事件</trans></span><trans data-src=",
    validators" data-dst="validators，
">validators，
</trans><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span><trans data-src=" {
      " data-dst="{">{</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="md-maxlength" data-dst="MD最大长度">MD最大长度</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><span class="pl-k"><trans data-src=":" data-dst="：">：</trans></span> <span class="pl-c1"><trans data-src="30" data-dst="三十">三十</trans></span><trans data-src="
    }
  });

  " data-dst="
 }）}；">
 }）}；</trans><span class="pl-smi"><trans data-src="promise" data-dst="承诺">承诺</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="then" data-dst="然后">然后</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" (" data-dst="（">（</trans><span class="pl-smi"><trans data-src="ctrl" data-dst="Ctrl">Ctrl</trans></span><trans data-src=") {
    " data-dst="）{">）{</trans><span class="pl-k"><trans data-src="var" data-dst="VaR">VaR</trans></span><trans data-src=" input " data-dst="输入">输入</trans><span class="pl-k">=</span> <span class="pl-smi"><trans data-src="ctrl" data-dst="Ctrl">Ctrl</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="getInput" data-dst="getinput">getinput</trans></span><trans data-src="();

    " data-dst="（）；">（）；</trans><span class="pl-smi"><trans data-src="input" data-dst="输入">输入</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="$viewChangeListeners" data-dst="viewchangelisteners美元">viewchangelisteners美元</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-c1"><trans data-src="push" data-dst="推">推</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" () {
      " data-dst="（）{">（）{</trans><span class="pl-smi"><trans data-src="input" data-dst="输入">输入</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="$setValidity" data-dst="setvalidity美元">setvalidity美元</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="test" data-dst="测试">测试</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", " data-dst="，">，</trans><span class="pl-smi"><trans data-src="input" data-dst="输入">输入</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="$modelValue" data-dst="元模型">元模型</trans></span> <span class="pl-k">!==</span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="test" data-dst="测试">测试</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=");
    });
  });
});" data-dst="
）；}）；}）；}）
 
；">
）；}）；}）；}）
 
；</trans></pre></div>

<h4><a id="user-content-small-edit-dialogs" class="anchor" href="#small-edit-dialogs" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Small Edit Dialogs" data-dst="小编辑对话框">小编辑对话框</trans></h4>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="$mdEditDialog" data-dst="mdeditdialog美元">mdeditdialog美元</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-c1"><trans data-src="small" data-dst="小">小</trans></span><trans data-src="(options);" data-dst="（可选）；">（可选）；</trans></pre></div>

<table><thead>
<tr>
<th align="left"><trans data-src="Parameter" data-dst="参数">参数</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><trans data-src="options" data-dst="选项">选项</trans></td>
<td align="left"><trans data-src="object" data-dst="目标">目标</trans></td>
<td align="left"><trans data-src="Small preset options." data-dst="小的预设选项。">小的预设选项。</trans></td>
</tr>
</tbody></table>

<table><thead>
<tr>
<th align="left"><trans data-src="Property" data-dst="财产">财产</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Default" data-dst="默认">默认</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="clickOutsideToClose" data-dst="clickoutsidetoclose">clickoutsidetoclose</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="The user can dismiss the dialog by clicking anywhere else on the page." data-dst="用户可以关闭该对话框点击任何页面上的。">用户可以关闭该对话框点击任何页面上的。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="disableScroll" data-dst="disablescroll">disablescroll</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="Prevent user scroll while the dialog is open." data-dst="防止用户滚动对话框而。">防止用户滚动对话框而。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="escToClose" data-dst="esctoclose">esctoclose</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="The user can dismiss the dialog by clicking the esc key." data-dst="用户可以关闭该对话框点击ESC键。">用户可以关闭该对话框点击ESC键。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="focusOnOpen" data-dst="focusonopen">focusonopen</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="Will search the template for an " data-dst="将搜索模板的一个">将搜索模板的一个</trans><code><trans data-src="md-autofocus" data-dst="MD自动对焦">MD自动对焦</trans></code><trans data-src=" element." data-dst="元素">元素</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="messages" data-dst="消息">消息</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Error messages to display corresponding to errors on the " data-dst="在相应的错误显示错误信息">在相应的错误显示错误信息</trans><code><trans data-src="ngModelController" data-dst="ngmodelcontroller">ngmodelcontroller</trans></code><trans data-src="." data-dst="。">。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="modelValue" data-dst="模型">模型</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="The initial value of the input element." data-dst="输入元素的初始值。">输入元素的初始值。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="placeholder" data-dst="占位符">占位符</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Placeholder text for input element." data-dst="输入元素的占位符文本。">输入元素的占位符文本。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="save" data-dst="保存"><trans data-src="保存" data-dst="保存">保存</trans></trans></code></td>
<td align="left"><code><trans data-src="function" data-dst="功能">功能</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="A callback function for when the use clicks the save button. The callback will receive the " data-dst="一个回调函数时，使用点击保存按钮。回调将获得">一个回调函数时，使用点击保存按钮。回调将获得</trans><a href="https://docs.angularjs.org/api/ng/type/ngModel.NgModelController"><trans data-src="ngModelController" data-dst="ngmodelcontroller">ngmodelcontroller</trans></a><trans data-src=". The dialog will close unless the callback returns a rejected promise." data-dst="。对话框将关闭，除非回调函数返回一个拒绝承诺。">。对话框将关闭，除非回调函数返回一个拒绝承诺。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="targetEvent" data-dst="targetevent">targetevent</trans></code></td>
<td align="left"><code><trans data-src="event" data-dst="事件">事件</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="The event object. This must be provided and it must be from a table cell." data-dst="事件对象。这是必须提供的，它必须从一个单元格。">事件对象。这是必须提供的，它必须从一个单元格。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="type" data-dst="类型">类型</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="" text""="" data-dst="“文本”">“文本”</trans></code></td>
<td align="left"><trans data-src="The value of the " data-dst="的价值">的价值</trans><code><trans data-src="type" data-dst="类型">类型</trans></code><trans data-src=" attribute on the " data-dst="属性上">属性上</trans><code><trans data-src="input" data-dst="输入">输入</trans></code><trans data-src=" element." data-dst="元素">元素</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="validators" data-dst="验证器">验证器</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Optional attributes to be placed on the input element." data-dst="可选的属性被放置在输入元件。">可选的属性被放置在输入元件。</trans></td>
</tr>
</tbody></table>

<p><trans data-src="The " data-dst="这个">这个</trans><code><trans data-src="small" data-dst="小">小</trans></code><trans data-src=" method will return a " data-dst="方法将返回一个">方法将返回一个</trans><code><trans data-src="promise" data-dst="承诺">承诺</trans></code><trans data-src=" that will resolve with the controller instance. The controller has two public methods, " data-dst="这将解决与控制器实例。该控制器有两个公共方法，">这将解决与控制器实例。该控制器有两个公共方法，</trans><code><trans data-src="dismiss" data-dst="辞退">辞退</trans></code><trans data-src=" which will close the dialog without saving and " data-dst="这将关闭对话框而不保存，">这将关闭对话框而不保存，</trans><code><trans data-src="getInput" data-dst="getinput">getinput</trans></code><trans data-src=" which will return the " data-dst="这将返回">这将返回</trans><code><trans data-src="ngModelController" data-dst="ngmodelcontroller">ngmodelcontroller</trans></code><trans data-src="." data-dst="。">。</trans></p>

<h4><a id="user-content-large-edit-dialogs" class="anchor" href="#large-edit-dialogs" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Large Edit Dialogs" data-dst="大编辑对话框">大编辑对话框</trans></h4>

<p><trans data-src="Large edit dialogs are functionally identical to small edit dialogs but have a few additional options." data-dst="大编辑对话框的小编辑对话框但有一些额外的选项功能相同。">大编辑对话框的小编辑对话框但有一些额外的选项功能相同。</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="$mdEditDialog" data-dst="mdeditdialog美元">mdeditdialog美元</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="large" data-dst="大号">大号</trans></span><trans data-src="(options);" data-dst="（可选）；">（可选）；</trans></pre></div>

<table><thead>
<tr>
<th align="left"><trans data-src="Parameter" data-dst="参数">参数</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><trans data-src="options" data-dst="选项">选项</trans></td>
<td align="left"><trans data-src="object" data-dst="目标">目标</trans></td>
<td align="left"><trans data-src="Large preset options." data-dst="大的预设选项。">大的预设选项。</trans></td>
</tr>
</tbody></table>

<table><thead>
<tr>
<th align="left"><trans data-src="Property" data-dst="财产">财产</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Default" data-dst="默认">默认</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="cancel" data-dst="取消"><trans data-src="取消" data-dst="取消">取消</trans></trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="" cancel""="" data-dst="“取消”">“取消”</trans></code></td>
<td align="left"><trans data-src="Text to dismiss the dialog without saving." data-dst="文本以关闭对话框而不保存。">文本以关闭对话框而不保存。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="clickOutsideToClose" data-dst="clickoutsidetoclose">clickoutsidetoclose</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="The user can dismiss the dialog by clicking anywhere else on the page." data-dst="用户可以关闭该对话框点击任何页面上的。">用户可以关闭该对话框点击任何页面上的。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="disableScroll" data-dst="disablescroll">disablescroll</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="Prevent user scroll while the dialog is open." data-dst="防止用户滚动对话框而。">防止用户滚动对话框而。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="escToClose" data-dst="esctoclose">esctoclose</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="The user can dismiss the dialog by clicking the esc key." data-dst="用户可以关闭该对话框点击ESC键。">用户可以关闭该对话框点击ESC键。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="focusOnOpen" data-dst="focusonopen">focusonopen</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="Will search the template for an " data-dst="将搜索模板的一个">将搜索模板的一个</trans><code><trans data-src="md-autofocus" data-dst="MD自动对焦">MD自动对焦</trans></code><trans data-src=" element." data-dst="元素">元素</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="messages" data-dst="消息">消息</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Error messages to display corresponding to errors on the " data-dst="在相应的错误显示错误信息">在相应的错误显示错误信息</trans><code><trans data-src="ngModelController" data-dst="ngmodelcontroller">ngmodelcontroller</trans></code><trans data-src="." data-dst="。">。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="modelValue" data-dst="模型">模型</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="The initial value of the input element." data-dst="输入元素的初始值。">输入元素的初始值。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="ok" data-dst="好 啊">好 啊</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="" save""="" data-dst="“拯救”">“拯救”</trans></code></td>
<td align="left"><trans data-src="Text to submit and dismiss the dialog." data-dst="文本提交并关闭对话框。">文本提交并关闭对话框。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="placeholder" data-dst="占位符">占位符</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Placeholder text for input element." data-dst="输入元素的占位符文本。">输入元素的占位符文本。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="save" data-dst="保存"><trans data-src="保存" data-dst="保存">保存</trans></trans></code></td>
<td align="left"><code><trans data-src="function" data-dst="功能">功能</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="A callback function for when the use clicks the save button. The callback will receive the " data-dst="一个回调函数时，使用点击保存按钮。回调将获得">一个回调函数时，使用点击保存按钮。回调将获得</trans><code><trans data-src="ngModelController" data-dst="ngmodelcontroller">ngmodelcontroller</trans></code><trans data-src=". The dialog will close unless the callback returns a rejected promise." data-dst="。对话框将关闭，除非回调函数返回一个拒绝承诺。">。对话框将关闭，除非回调函数返回一个拒绝承诺。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="targetEvent" data-dst="targetevent">targetevent</trans></code></td>
<td align="left"><code><trans data-src="event" data-dst="事件">事件</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="The event object. This must be provided and it must be from a table cell." data-dst="事件对象。这是必须提供的，它必须从一个单元格。">事件对象。这是必须提供的，它必须从一个单元格。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="title" data-dst="头衔">头衔</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="" edit""="" data-dst="“编辑”">“编辑”</trans></code></td>
<td align="left"><trans data-src="Dialog title text." data-dst="对话框标题文本。">对话框标题文本。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="type" data-dst="类型">类型</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="" text""="" data-dst="“文本”">“文本”</trans></code></td>
<td align="left"><trans data-src="The value of the " data-dst="的价值">的价值</trans><code><trans data-src="type" data-dst="类型">类型</trans></code><trans data-src=" attribute on the " data-dst="属性上">属性上</trans><code><trans data-src="input" data-dst="输入">输入</trans></code><trans data-src=" element." data-dst="元素">元素</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="validators" data-dst="验证器">验证器</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Optional attributes to be placed on the input element." data-dst="可选的属性被放置在输入元件。">可选的属性被放置在输入元件。</trans></td>
</tr>
</tbody></table>

<p><trans data-src="The " data-dst="这个">这个</trans><code><trans data-src="large" data-dst="大号">大号</trans></code><trans data-src=" method will return a " data-dst="方法将返回一个">方法将返回一个</trans><code><trans data-src="promise" data-dst="承诺">承诺</trans></code><trans data-src=" that will resolve with the controller instance. The controller has two public methods, " data-dst="这将解决与控制器实例。该控制器有两个公共方法，">这将解决与控制器实例。该控制器有两个公共方法，</trans><code><trans data-src="dismiss" data-dst="辞退">辞退</trans></code><trans data-src=" which will close the dialog without saving and " data-dst="这将关闭对话框而不保存，">这将关闭对话框而不保存，</trans><code><trans data-src="getInput" data-dst="getinput">getinput</trans></code><trans data-src=" which will return the " data-dst="这将返回">这将返回</trans><code><trans data-src="ngModelController" data-dst="ngmodelcontroller">ngmodelcontroller</trans></code><trans data-src="." data-dst="。">。</trans></p>

<h4><a id="user-content-roll-your-own" class="anchor" href="#roll-your-own" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Roll Your Own" data-dst="滚你自己">滚你自己</trans></h4>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="$mdEditDialog" data-dst="mdeditdialog美元">mdeditdialog美元</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="show" data-dst="商展">商展</trans></span><trans data-src="(options);" data-dst="（可选）；">（可选）；</trans></pre></div>

<table><thead>
<tr>
<th align="left"><trans data-src="Parameter" data-dst="参数">参数</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><trans data-src="options" data-dst="选项">选项</trans></td>
<td align="left"><trans data-src="object" data-dst="目标">目标</trans></td>
<td align="left"><trans data-src="Dialog options." data-dst="对话框选项。">对话框选项。</trans></td>
</tr>
</tbody></table>

<table><thead>
<tr>
<th align="left"><trans data-src="Property" data-dst="财产">财产</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Default" data-dst="默认">默认</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="bindToController" data-dst="bindtocontroller">bindtocontroller</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="false" data-dst="假">假</trans></code></td>
<td align="left"><trans data-src="If true, properties on the provided scope object will be bound to the controller" data-dst="如果是真的，在规定范围的对象将被绑定到控制器的性能">如果是真的，在规定范围的对象将被绑定到控制器的性能</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="clickOutsideToClose" data-dst="clickoutsidetoclose">clickoutsidetoclose</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="The user can dismiss the dialog by clicking anywhere else on the page." data-dst="用户可以关闭该对话框点击任何页面上的。">用户可以关闭该对话框点击任何页面上的。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="controller" data-dst="控制器">控制器</trans></code></td>
<td align="left"><code><trans data-src="function" data-dst="功能">功能</trans></code> <code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Either a constructor function or a string register with the " data-dst="任何一个构造函数或一个字符串登记的">任何一个构造函数或一个字符串登记的</trans><code><trans data-src="$controller" data-dst="元控制器">元控制器</trans></code><trans data-src=" service. The controller will be automatically injected with " data-dst="服务该控制器将自动注射">服务该控制器将自动注射</trans><code><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></code><trans data-src=" and " data-dst="和">和</trans><code><trans data-src="$element" data-dst="$元">$元</trans></code><trans data-src=". Remember to annotate your controller if you will be minifying your code." data-dst="。记得给你的控制器，如果你会削减你的代码。">。记得给你的控制器，如果你会削减你的代码。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="controllerAs" data-dst="控制器">控制器</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="An alias to publish your controller on the scope." data-dst="发布您的控制范围的别名。">发布您的控制范围的别名。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="disableScroll" data-dst="disablescroll">disablescroll</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="Prevent user scroll while the dialog is open." data-dst="防止用户滚动对话框而。">防止用户滚动对话框而。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="escToClose" data-dst="esctoclose">esctoclose</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="The user can dismiss the dialog by clicking the esc key." data-dst="用户可以关闭该对话框点击ESC键。">用户可以关闭该对话框点击ESC键。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="focusOnOpen" data-dst="focusonopen">focusonopen</trans></code></td>
<td align="left"><code><trans data-src="bool" data-dst="布尔">布尔</trans></code></td>
<td align="left"><code><trans data-src="true" data-dst="真正的">真正的</trans></code></td>
<td align="left"><trans data-src="Will search the template for an " data-dst="将搜索模板的一个">将搜索模板的一个</trans><code><trans data-src="md-autofocus" data-dst="MD自动对焦">MD自动对焦</trans></code><trans data-src=" element." data-dst="元素">元素</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="locals" data-dst="当地人">当地人</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Optional dependancies to be injected into your controller. It is not necessary to inject registered services, the " data-dst="可选的依赖被注入到你的控制器。这是没有必要注入注册服务的">可选的依赖被注入到你的控制器。这是没有必要注入注册服务的</trans><code><trans data-src="$injector" data-dst="喷油器元">喷油器元</trans></code><trans data-src=" will provide them for you." data-dst="将为您提供。">将为您提供。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="resolve" data-dst="解决">解决</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Similar to locals but waits for promises to be resolved. Once the promises resolve, their return value will be injected into the controller and the dialog will open." data-dst="类似于当地人却承诺要解决等。一旦承诺的决心，他们的返回值将被注入控制器和对话框将打开。">类似于当地人却承诺要解决等。一旦承诺的决心，他们的返回值将被注入控制器和对话框将打开。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="scope" data-dst="范围">范围</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="Properties to bind to the new isolated scope." data-dst="属性绑定到新的分离范围。">属性绑定到新的分离范围。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="targetEvent" data-dst="targetevent">targetevent</trans></code></td>
<td align="left"><code><trans data-src="event" data-dst="事件">事件</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="The event object. This must be provided and it must be from a table cell." data-dst="事件对象。这是必须提供的，它必须从一个单元格。">事件对象。这是必须提供的，它必须从一个单元格。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="template" data-dst="模板">模板</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="The template for your dialog." data-dst="你的对话框模板。">你的对话框模板。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="templateUrl" data-dst="templateurl">templateurl</trans></code></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><code><trans data-src="null" data-dst="空">空</trans></code></td>
<td align="left"><trans data-src="A URL to fetch your template from." data-dst="一个URL抓取你的模板。">一个URL抓取你的模板。</trans></td>
</tr>
</tbody></table>

<p><trans data-src="The " data-dst="这个">这个</trans><code><trans data-src="show" data-dst="商展">商展</trans></code><trans data-src=" method will return a " data-dst="方法将返回一个">方法将返回一个</trans><code><trans data-src="promise" data-dst="承诺">承诺</trans></code><trans data-src=" that will resolve with the controller instance." data-dst="这将解决与控制器实例。">这将解决与控制器实例。</trans></p>

<p><trans data-src="Table cells have a " data-dst="表细胞有">表细胞有</trans><code><trans data-src="md-placeholder" data-dst="MD的占位符">MD的占位符</trans></code><trans data-src=" CSS class that you can use for placeholder text." data-dst="CSS类，你可以使用占位符文本。">CSS类，你可以使用占位符文本。</trans></p>

<p><strong><trans data-src="Example: A Table Cell That Opens An Edit Dialog" data-dst="例如：一个打开编辑对话框表格单元格">例如：一个打开编辑对话框表格单元格</trans></strong></p>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span> <span class="pl-e"><trans data-src="ng-click" data-dst="点击.">点击.</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="editComment($event, dessert)" data-dst="editcomment（$事件，甜点）">editcomment（$事件，甜点）</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="ng-class" data-dst="NG类">NG类</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="{'md-placeholder': !dessert.comment}" data-dst="（placeholder：MD！dessert.comment }">（placeholder：MD！dessert.comment }</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
  {{dessert.comment || 'Add a comment'}}
&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;</pre></div>

<h3><a id="user-content-inline-menus" class="anchor" href="#inline-menus" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Inline Menus" data-dst="内置菜单">内置菜单</trans></h3>

<p><trans data-src="Table cells support inline menus. To use an inline menu, place an " data-dst="表格单元格支持内嵌菜单。使用内联的菜单，地点">表格单元格支持内嵌菜单。使用内联的菜单，地点</trans><code><trans data-src="md-select" data-dst="MD选择">MD选择</trans></code><trans data-src=" element inside an " data-dst="元素内">元素内</trans><code><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></code><trans data-src=" element." data-dst="元素">元素</trans></p>

<p><strong><trans data-src="Example" data-dst="例子">例子</trans></strong></p>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;
  &lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-select" data-dst="选择">选择</trans></span> <span class="pl-e"><trans data-src="ng-model" data-dst="NG型">NG型</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="dessert.type" data-dst="dessert.type">dessert.type</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="placeholder" data-dst="占位符">占位符</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="Other" data-dst="其他">其他</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-option" data-dst="选项">选项</trans></span> <span class="pl-e"><trans data-src="ng-value" data-dst="商业价值">商业价值</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="type" data-dst="类型">类型</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="ng-repeat" data-dst="NG的重复">NG的重复</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="type in getTypes()" data-dst="在gettypes（型）">在gettypes（型）</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;{{type}}&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-option" data-dst="选项">选项</trans></span>&gt;
  &lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-select" data-dst="选择">选择</trans></span>&gt;
&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;</pre></div>

<p><trans data-src="Clicking anywhere in the cell will activate the menu. In addition, if you have automatic row selection enabled the row will not be selected when the cell is clicked." data-dst="单击单元格的任何地方都会激活菜单。此外，如果您选择启用自动排排不会被选中当细胞被点击。">单击单元格的任何地方都会激活菜单。此外，如果您选择启用自动排排不会被选中当细胞被点击。</trans></p>

<h3><a id="user-content-numeric-columns" class="anchor" href="#numeric-columns" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Numeric Columns" data-dst="数字列">数字列</trans></h3>

<p><trans data-src="Numeric columns align to the right of table cells." data-dst="数字列对齐表格单元格的右。">数字列对齐表格单元格的右。</trans></p>

<table><thead>
<tr>
<th align="left"><trans data-src="Attribute" data-dst="属性">属性</trans></th>
<th align="left"><trans data-src="Element" data-dst="元素">元素</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="mdNumeric" data-dst="mdnumeric">mdnumeric</trans></code></td>
<td align="left"><code><trans data-src="mdColumn" data-dst="mdcolumn">mdcolumn</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="If the expression is " data-dst="如果表达式">如果表达式</trans><code><trans data-src="null" data-dst="空">空</trans></code><trans data-src=" or evaluates to " data-dst="或评价">或评价</trans><code><trans data-src="true" data-dst="真正的">真正的</trans></code><trans data-src=" then all the cells in that column will be right aligned" data-dst="然后在该列的所有单元格将右对齐">然后在该列的所有单元格将右对齐</trans></td>
</tr>
</tbody></table>

<p><trans data-src="You may use Angular's " data-dst="你可以使用角的">你可以使用角的</trans><a href="https://docs.angularjs.org/api/ng/filter/number"><trans data-src="number" data-dst="数">数</trans></a><trans data-src=" filter on a cell to set the decimal precision." data-dst="在细胞过滤器设置小数精度。">在细胞过滤器设置小数精度。</trans></p>

<div class="highlight highlight-text-html-basic"><pre><span class="pl-c"><trans data-src="<!-- 2 decimal places -->" data-dst="<！2位小数-->">&lt;！2位小数--&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;{{dessert.protein.value | number: 2}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;</pre></div>

<blockquote>
<p><trans data-src="If you are using " data-dst="如果你使用的是">如果你使用的是</trans><code><trans data-src="colspan" data-dst="合并单元格">合并单元格</trans></code><trans data-src=" you may need to manual correct the alignment and padding of cells. You can override the cell's style with a custom CSS class." data-dst="你可能需要手动正确对齐和填充细胞。你可以用一个自定义的CSS类中重写该细胞的风格。">你可能需要手动正确对齐和填充细胞。你可以用一个自定义的CSS类中重写该细胞的风格。</trans></p>
</blockquote>

<h3><a id="user-content-pagination" class="anchor" href="#pagination" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Pagination" data-dst="分页">分页</trans></h3>

<table><thead>
<tr>
<th align="left"><trans data-src="Attribute" data-dst="属性">属性</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="mdBoundaryLinks" data-dst="mdboundarylinks">mdboundarylinks</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="Displays first and last page navigation links" data-dst="显示的第一个和最后一个页面的导航链接">显示的第一个和最后一个页面的导航链接</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdLabel" data-dst="mdlabel">mdlabel</trans></code></td>
<td align="left"><code><trans data-src="object" data-dst="目标">目标</trans></code></td>
<td align="left"><trans data-src="Change the pagination label (See more below)." data-dst="pagination change the label（see below黑莓）。">pagination change the label（see below黑莓）。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdLimit" data-dst="mdlimit">mdlimit</trans></code></td>
<td align="left"><code><trans data-src="integer" data-dst="整数">整数</trans></code></td>
<td align="left"><trans data-src="A row limit." data-dst="连续涨停。">连续涨停。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdLimitOptions" data-dst="mdlimitoptions">mdlimitoptions</trans></code></td>
<td align="left"><code><trans data-src="array" data-dst="阵列">阵列</trans></code></td>
<td align="left"><trans data-src="Row limit options." data-dst="行限制选项。">行限制选项。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdOnPaginate" data-dst="mdonpaginate">mdonpaginate</trans></code></td>
<td align="left"><code><trans data-src="function" data-dst="功能">功能</trans></code></td>
<td align="left"><trans data-src="A callback function for when the page or limit changes. The page is passed as the first argument and the limit is passed as the second argument." data-dst="一个回调函数，当页面或限制的变化。网页作为第一个参数和极限参数传递给第二。">一个回调函数，当页面或限制的变化。网页作为第一个参数和极限参数传递给第二。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdPage" data-dst="mdpage">mdpage</trans></code></td>
<td align="left"><code><trans data-src="integer" data-dst="整数">整数</trans></code></td>
<td align="left"><trans data-src="Page number. Pages are not zero indexed. The directive assumes the first page is one." data-dst="页号。不为零的索引页。该指令的第一页是一个假设。">页号。不为零的索引页。该指令的第一页是一个假设。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdPageSelect" data-dst="mdpageselect">mdpageselect</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="Display a select dropdown for the page number" data-dst="显示页码选择下拉">显示页码选择下拉</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdTotal" data-dst="mdtotal">mdtotal</trans></code></td>
<td align="left"><code><trans data-src="integer" data-dst="整数">整数</trans></code></td>
<td align="left"><trans data-src="Total number of items." data-dst="项目总数。">项目总数。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="ngDisabled" data-dst="ngdisabled">ngdisabled</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="Disable pagination elements." data-dst="禁用分页元素。">禁用分页元素。</trans></td>
</tr>
</tbody></table>

<p><trans data-src="The " data-dst="这个">这个</trans><code><trans data-src="md-label" data-dst="的MD -拉班">的MD -拉班</trans></code><trans data-src=" attribute has the following properties." data-dst="属性具有以下特性。">属性具有以下特性。</trans></p>

<table><thead>
<tr>
<th align="left"><trans data-src="Property" data-dst="财产">财产</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Default" data-dst="默认">默认</trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><trans data-src="of" data-dst="对">对</trans></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><trans data-src="'of' (e.g. x - y of z)" data-dst="' '（如X Y Z）">' '（如X Y Z）</trans></td>
</tr>
<tr>
<td align="left"><trans data-src="page" data-dst="网页">网页</trans></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><trans data-src="'Page:'" data-dst="“网页”">“网页”</trans></td>
</tr>
<tr>
<td align="left"><trans data-src="rowsPerPage" data-dst="rowsperpage">rowsperpage</trans></td>
<td align="left"><code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><trans data-src="'Rows per page:'" data-dst="“行数”页面：">“行数”页面：</trans></td>
</tr>
</tbody></table>

<p><strong><trans data-src="Example: Changing The Pagination Label" data-dst="例如：改变分页标签">例如：改变分页标签</trans></strong></p>

<div class="highlight highlight-text-html-basic"><pre><span class="pl-c"><trans data-src="<!-- how to change the pagination label -->" data-dst="<！——如何改变分页标签-->">&lt;！——如何改变分页标签--&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span> <span class="pl-e"><trans data-src="md-label" data-dst="的MD -拉班">的MD -拉班</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="{page: 'Página:', rowsPerPage: 'Filas por página:', of: 'de'}" data-dst="页：：{“页面”，“页rowsperpage：行：“：”、“}">页：：{“页面”，“页rowsperpage：行：“：”、“}</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span>&gt;

<span class="pl-c"><trans data-src="<!-- or if the label is defined on the scope -->" data-dst="<！或者如果标签是在范围定义——>">&lt;！或者如果标签是在范围定义——&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span> <span class="pl-e"><trans data-src="md-label" data-dst="的MD -拉班">的MD -拉班</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="{{label}}" data-dst="{ {标签} }">{ {标签} }</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span>&gt;</pre></div>

<blockquote>
<p><trans data-src="I used Google translate so if the translations are wrong please fix them and make a pull request." data-dst="我用谷歌翻译，如果翻译错了请修理，使拉请求。">我用谷歌翻译，如果翻译错了请修理，使拉请求。</trans></p>
</blockquote>

<p><strong><trans data-src="Example: Client Side Pagination Using ngRepeat" data-dst="例如：客户端分页使用ngrepeat">例如：客户端分页使用ngrepeat</trans></strong></p>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span> <span class="pl-e"><trans data-src="md-row" data-dst="的MD -行">的MD -行</trans></span> <span class="pl-e"><trans data-src="ng-repeat" data-dst="NG的重复">NG的重复</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="item in array | orderBy: myOrder | limitTo: myLimit: (myPage - 1) * myLimit" data-dst="在阵列| OrderBy项目：我的命令|限制：mylimit：（中国- 1）* mylimit">在阵列| OrderBy项目：我的命令|限制：mylimit：（中国- 1）* mylimit</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;

<span class="pl-c"><trans data-src="<!-- and your pagination element will look something like... -->" data-dst="<！和你的分页元素看起来就像…-->">&lt;！和你的分页元素看起来就像…--&gt;</trans></span>
&lt;<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span> <span class="pl-e"><trans data-src="md-limit" data-dst="MD极限">MD极限</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="myLimit" data-dst="mylimit">mylimit</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-page" data-dst="MD">MD</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="myPage" data-dst="天气">天气</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-total" data-dst="MD总">MD总</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="{{array.length}}" data-dst="{ {数组长度} }。">{ {数组长度} }。</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="md" data-dst="MD">MD</trans></span><span class="pl-e"><trans data-src="-table-pagination" data-dst="表的分页">表的分页</trans></span>&gt;</pre></div>

<p><strong><trans data-src="My Pagination Isn't Working?!" data-dst="我的分页不工作？！">我的分页不工作？！</trans></strong></p>

<ul>
<li><trans data-src="Make sure you pass " data-dst="确保你通过">确保你通过</trans><code><trans data-src="md-page" data-dst="MD">MD</trans></code><trans data-src=", " data-dst="，">，</trans><code><trans data-src="md-limit" data-dst="MD极限">MD极限</trans></code><trans data-src=", and " data-dst="，和">，和</trans><code><trans data-src="md-total" data-dst="MD总">MD总</trans></code><trans data-src=" to the directive and that they are finite numbers." data-dst="的指令，他们是有限的数。">的指令，他们是有限的数。</trans></li>
<li><trans data-src="Pages are not zero indexed. The directive will assume pages start at one. If your query language expects pages to be zero indexed then just subtract one before making the query." data-dst="不为零的索引页。该指令将页面在一开始的。如果你希望网页查询语言是零索引就减去一个之前的查询。">不为零的索引页。该指令将页面在一开始的。如果你希望网页查询语言是零索引就减去一个之前的查询。</trans></li>
</ul>

<h3><a id="user-content-row-selection" class="anchor" href="#row-selection" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Row Selection" data-dst="行选择">行选择</trans></h3>

<table><thead>
<tr>
<th align="left"><trans data-src="Attribute" data-dst="属性">属性</trans></th>
<th align="left"><trans data-src="Element" data-dst="元素">元素</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="mdAutoSelect" data-dst="mdautoselect">mdautoselect</trans></code></td>
<td align="left"><code><trans data-src="mdRow" data-dst="mdrow">mdrow</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="Select a row by clicking anywhere in the row." data-dst="通过单击行的任何地方选择一行。">通过单击行的任何地方选择一行。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdOnDeselect" data-dst="mdondeselect">mdondeselect</trans></code></td>
<td align="left"><code><trans data-src="mdRow" data-dst="mdrow">mdrow</trans></code></td>
<td align="left"><code><trans data-src="function" data-dst="功能">功能</trans></code></td>
<td align="left"><trans data-src="A callback function for when an item is deselected. The item will be passed as an argument to the callback." data-dst="一个回调函数，当一个项目被取消。该项目将被作为参数传给回调函数。">一个回调函数，当一个项目被取消。该项目将被作为参数传给回调函数。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdOnSelect" data-dst="mdonselect">mdonselect</trans></code></td>
<td align="left"><code><trans data-src="mdRow" data-dst="mdrow">mdrow</trans></code></td>
<td align="left"><code><trans data-src="function" data-dst="功能">功能</trans></code></td>
<td align="left"><trans data-src="A callback function for when an item is selected. The item will be passed as an argument to the callback." data-dst="一个回调函数，当选择一个项目。该项目将被作为参数传给回调函数。">一个回调函数，当选择一个项目。该项目将被作为参数传给回调函数。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdRowSelect" data-dst="mdrowselect">mdrowselect</trans></code></td>
<td align="left"><code><trans data-src="mdTable" data-dst="mdtable">mdtable</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="Enable row selection." data-dst="使行选择。">使行选择。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdSelect" data-dst="mdselect">mdselect</trans></code></td>
<td align="left"><code><trans data-src="mdRow" data-dst="mdrow">mdrow</trans></code></td>
<td align="left"><code><trans data-src="any" data-dst="任何">任何</trans></code></td>
<td align="left"><trans data-src="The item to be selected." data-dst="该项目被选中。">该项目被选中。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="mdSelectId" data-dst="mdselectid">mdselectid</trans></code></td>
<td align="left"><code><trans data-src="mdRow" data-dst="mdrow">mdrow</trans></code></td>
<td align="left"><code><trans data-src="number" data-dst="数">数</trans></code> <code><trans data-src="string" data-dst="字符串">字符串</trans></code></td>
<td align="left"><trans data-src="A unique identifier for the selected item. The identifier must be a property of the item." data-dst="选择项目的唯一标识符。标识符必须是该项的属性。">选择项目的唯一标识符。标识符必须是该项的属性。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="multiple" data-dst="多">多</trans></code></td>
<td align="left"><code><trans data-src="mdTable" data-dst="mdtable">mdtable</trans></code></td>
<td align="left"><code><trans data-src="[expression]" data-dst="[表达]">[表达]</trans></code></td>
<td align="left"><trans data-src="Allow multiple selection. When enabled a master toggle will be prepended to the last row of table header." data-dst="允许多个选择。当启用主切换将被添加到表头的最后一排。">允许多个选择。当启用主切换将被添加到表头的最后一排。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="ngDisabled" data-dst="ngdisabled">ngdisabled</trans></code></td>
<td align="left"><code><trans data-src="mdRow" data-dst="mdrow">mdrow</trans></code></td>
<td align="left"><code><trans data-src="expression" data-dst="表达">表达</trans></code></td>
<td align="left"><trans data-src="Conditionally disable row selection." data-dst="有条件地禁止行选择。">有条件地禁止行选择。</trans></td>
</tr>
<tr>
<td align="left"><code><trans data-src="ngModel" data-dst="ngmodel">ngmodel</trans></code></td>
<td align="left"><code><trans data-src="mdTable" data-dst="mdtable">mdtable</trans></code></td>
<td align="left"><code><trans data-src="array" data-dst="阵列">阵列</trans></code></td>
<td align="left"><trans data-src="A variable to bind selected items to." data-dst="变量绑定选定的项目。">变量绑定选定的项目。</trans></td>
</tr>
</tbody></table>

<p><trans data-src="By default selected items will persist. Equality between items is determined using the " data-dst="默认情况下，选定的项目将持续。平等之间的项目是确定的">默认情况下，选定的项目将持续。平等之间的项目是确定的</trans><code>===</code><trans data-src=" operator. In cases where items may not be strictly equal, you must provide a unique identifier for the item." data-dst="算子。在项目的情况下，可能不是严格相等的，必须提供该项目的唯一标识符。">算子。在项目的情况下，可能不是严格相等的，必须提供该项目的唯一标识符。</trans></p>

<p><trans data-src="You may manually add or remove items from the model but be aware that select and deselect callbacks will not be triggered. When operating in single select mode, the deselect callback will not be triggered when a user selects another item. It will be trigger, however, if the user directly deselects the item. In multi-select mode, the master toggle will trigger select and deselect callbacks for all items selected or deselected respectfully." data-dst="你可以手动添加或删除项目从模型，但要注意选择和取消选择回调将不会触发。在单一的选择模式下运行时，取消回调不会被触发，当用户选择一个项目。它将被触发，但是，如果用户直接将项目。多选择模式，主开关触发选择和取消选择回调选择或取消选择尊重所有项目。">你可以手动添加或删除项目从模型，但要注意选择和取消选择回调将不会触发。在单一的选择模式下运行时，取消回调不会被触发，当用户选择一个项目。它将被触发，但是，如果用户直接将项目。多选择模式，主开关触发选择和取消选择回调选择或取消选择尊重所有项目。</trans></p>

<p><strong><trans data-src="Example: Row Selection From The Live Demo." data-dst="例如：从现场演示行选择。">例如：从现场演示行选择。</trans></strong></p>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span> <span class="pl-e"><trans data-src="md-row" data-dst="的MD -行">的MD -行</trans></span> <span class="pl-e"><trans data-src="md-select" data-dst="MD选择">MD选择</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="dessert" data-dst="甜点">甜点</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-select-id" data-dst="MD id">MD id</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="name" data-dst="姓名">姓名</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span> <span class="pl-e"><trans data-src="md-auto-select" data-dst="MD自动选择">MD自动选择</trans></span> <span class="pl-e"><trans data-src="ng-repeat" data-dst="NG的重复">NG的重复</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="dessert in desserts.data" data-dst="在desserts.data甜点">在desserts.data甜点</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;</pre></div>

<p><strong><trans data-src="Example: Clearing Selected Items On Pagination" data-dst="例如：清除分页选定项目">例如：清除分页选定项目</trans></strong></p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="onPaginate" data-dst="onpaginate">onpaginate</trans></span> <span class="pl-k">=</span> <span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" () {
  " data-dst="（）{">（）{</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-c1"><trans data-src="selected" data-dst="挑选">挑选</trans></span> <span class="pl-k">=</span><trans data-src=" [];
}" data-dst="[ ]；
">[ ]；
</trans></pre></div>

<h3><a id="user-content-table-progress" class="anchor" href="#table-progress" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Table Progress" data-dst="表的进展">表的进展</trans></h3>

<table><thead>
<tr>
<th align="left"><trans data-src="Attribute" data-dst="属性">属性</trans></th>
<th align="left"><trans data-src="Target" data-dst="目标">目标</trans></th>
<th align="left"><trans data-src="Type" data-dst="类型">类型</trans></th>
<th align="left"><trans data-src="Description" data-dst="描述"><trans data-src="描述" data-dst="描述">描述</trans></trans></th>
</tr>
</thead><tbody>
<tr>
<td align="left"><code><trans data-src="mdProgress" data-dst="mdprogress">mdprogress</trans></code></td>
<td align="left"><code><trans data-src="mdTable" data-dst="mdtable">mdtable</trans></code></td>
<td align="left"><code><trans data-src="promise" data-dst="承诺">承诺</trans></code> <code><trans data-src="promise<Array>" data-dst="> < Promise阵列">&gt; &lt; Promise阵列</trans></code></td>
<td align="left"><trans data-src="The table will display a loading indicator until all promises are resolved or rejected." data-dst="该表将显示一个加载指示器，直到所有的承诺都得到解决或拒绝。">该表将显示一个加载指示器，直到所有的承诺都得到解决或拒绝。</trans></td>
</tr>
</tbody></table>

<p><trans data-src="The table module can display a loading indicator for you whenever asynchronous code is executing. It accepts a promise or an array of promises. If another promise is received before the previous promise is resolved or rejected it will be placed in a queue." data-dst="表模块可以显示一个加载指示器，你当异步执行代码。它接受一个承诺或一系列承诺。如果另一个承诺是在以前的承诺是解决或拒绝它将被放置在一个队列中接收。">表模块可以显示一个加载指示器，你当异步执行代码。它接受一个承诺或一系列承诺。如果另一个承诺是在以前的承诺是解决或拒绝它将被放置在一个队列中接收。</trans></p>

<p><trans data-src="Because I spent almost an hour debugging this I thought I would share with you. I'm not sure why this is the case but if you put the deferred object on the scope and try to pass the promise to the directive from that, the queue mechanism will not work properly." data-dst="因为我花了近一个小时的调试这个我以为我会与你分享。我不知道为什么会这样，但如果你把延迟对象的范围，试图通过从指令队列机制的承诺，将无法正常工作。">因为我花了近一个小时的调试这个我以为我会与你分享。我不知道为什么会这样，但如果你把延迟对象的范围，试图通过从指令队列机制的承诺，将无法正常工作。</trans></p>

<p><strong><trans data-src="This Will Not Work" data-dst="这将不工作">这将不工作</trans></strong></p>

<div class="highlight highlight-source-js"><pre><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" () {
  " data-dst="（）{">（）{</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="deferred" data-dst="递延">递延</trans></span> <span class="pl-k">=</span> <span class="pl-smi"><trans data-src="$q" data-dst="q元">q元</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-c1"><trans data-src="defer" data-dst="推迟">推迟</trans></span><trans data-src="();
  " data-dst="（）；">（）；</trans><span class="pl-c"><trans data-src="// ..." data-dst="/ /…">/ /…</trans></span>
  <span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="deferred" data-dst="递延">递延</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="resolve" data-dst="解决">解决</trans></span><trans data-src="();
}" data-dst="（）；
">（）；
</trans></pre></div>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span> <span class="pl-e"><trans data-src="md-table" data-dst="MD表">MD表</trans></span> <span class="pl-e"><trans data-src="md-progress" data-dst="医学的进步">医学的进步</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="deferred.promise" data-dst="deferred.promise">deferred.promise</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span>&gt;</pre></div>

<p><strong><trans data-src="This Will Work" data-dst="这将工作">这将工作</trans></strong></p>

<div class="highlight highlight-source-js"><pre><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" () {
  " data-dst="（）{">（）{</trans><span class="pl-k"><trans data-src="var" data-dst="VaR">VaR</trans></span><trans data-src=" deferred " data-dst="递延">递延</trans><span class="pl-k">=</span> <span class="pl-smi"><trans data-src="$q" data-dst="q元">q元</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-c1"><trans data-src="defer" data-dst="推迟">推迟</trans></span><trans data-src="();
  " data-dst="（）；">（）；</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="promise" data-dst="承诺">承诺</trans></span> <span class="pl-k">=</span> <span class="pl-smi"><trans data-src="deferred" data-dst="递延">递延</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="promise" data-dst="承诺">承诺</trans></span><trans data-src=";
  " data-dst="；">；</trans><span class="pl-c"><trans data-src="// ..." data-dst="/ /…">/ /…</trans></span>
  <span class="pl-smi"><trans data-src="deferred" data-dst="递延">递延</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="resolve" data-dst="解决">解决</trans></span><trans data-src="();
}" data-dst="（）；
">（）；
</trans></pre></div>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span> <span class="pl-e"><trans data-src="md-table" data-dst="MD表">MD表</trans></span> <span class="pl-e"><trans data-src="md-progress" data-dst="医学的进步">医学的进步</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="promise" data-dst="承诺">承诺</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="table" data-dst="表">表</trans></span>&gt;</pre></div>

<p><trans data-src="In addition, if you are dealing with something that returns a promise directly (not a deferred object) you don't need to worry about it." data-dst="此外，如果你正在处理一些回报承诺直接（不延期对象）你不需要担心。">此外，如果你正在处理一些回报承诺直接（不延期对象）你不需要担心。</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" () {
  " data-dst="（）{">（）{</trans><span class="pl-smi"><trans data-src="$scope" data-dst="美元的范围">美元的范围</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-smi"><trans data-src="promise" data-dst="承诺">承诺</trans></span> <span class="pl-k">=</span> <span class="pl-en"><trans data-src="$timeout" data-dst="$超时">$超时</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-k"><trans data-src="function" data-dst="功能">功能</trans></span><trans data-src=" () {
    " data-dst="（）{">（）{</trans><span class="pl-c"><trans data-src="// ..." data-dst="/ /…">/ /…</trans></span><trans data-src="
  }, " data-dst="}，">}，</trans><span class="pl-c1"><trans data-src="2000" data-dst="二千">二千</trans></span><trans data-src=");
}" data-dst="
）；">
）；</trans></pre></div>

<h3><a id="user-content-table-toolbars" class="anchor" href="#table-toolbars" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Table Toolbars" data-dst="表格工具栏">表格工具栏</trans></h3>

<p><trans data-src="Tables may be embedded within cards that offer navigation and data manipulation tools available at the top and bottom. You can use the " data-dst="表格可以嵌入在卡提供的导航数据处理工具在顶部和底部可。你可以使用">表格可以嵌入在卡提供的导航数据处理工具在顶部和底部可。你可以使用</trans><code><trans data-src="md-table-toolbar" data-dst="MD表工具栏">MD表工具栏</trans></code><trans data-src=" and " data-dst="和">和</trans><code><trans data-src="md-default" data-dst="MD默认">MD默认</trans></code><trans data-src=" class on a " data-dst="班上">班上</trans><code><trans data-src="md-toolbar" data-dst="MD工具栏">MD工具栏</trans></code><trans data-src=" element for a plain white toolbar." data-dst="一个纯白色的工具栏元。">一个纯白色的工具栏元。</trans></p>

<p><trans data-src="If you need to display information relative to a particular column in the table you may use use a " data-dst="如果你需要显示的信息相对特定列的表中你可以使用">如果你需要显示的信息相对特定列的表中你可以使用</trans><code><trans data-src="<md-foot>" data-dst="＜MD足>">＜MD足&gt;</trans></code><trans data-src=" element. For example, say you had a " data-dst="元素比如说你有一个">元素比如说你有一个</trans><code><trans data-src="calories.total" data-dst="calories.total"><trans data-src="calories.total" data-dst="calories.total">calories.total</trans></trans></code><trans data-src=" property that summed the total number of calories and you wanted to display that information directly beneath the Calories column." data-dst="属性归纳总热量和你想要显示的信息直接在卡柱。">属性归纳总热量和你想要显示的信息直接在卡柱。</trans></p>

<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent"><trans data-src="tfoot" data-dst="设计表尾样式">设计表尾样式</trans></span> <span class="pl-e"><trans data-src="md-foot" data-dst="MD的脚">MD的脚</trans></span>&gt;
  &lt;<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span> <span class="pl-e"><trans data-src="md-row" data-dst="的MD -行">的MD -行</trans></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span>&gt;&lt;<span class="pl-ent"><trans data-src="strong" data-dst="强">强</trans></span>&gt;Total: &lt;/<span class="pl-ent"><trans data-src="strong" data-dst="强">强</trans></span>&gt;{{calories.total}}&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
    &lt;<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span> <span class="pl-e"><trans data-src="md-cell" data-dst="MD细胞">MD细胞</trans></span> <span class="pl-e"><trans data-src="colspan" data-dst="合并单元格">合并单元格</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span><trans data-src="6" data-dst="六">六</trans><span class="pl-pds"><trans data-src="" "="" data-dst="“">“</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="td" data-dst="TD">TD</trans></span>&gt;
  &lt;/<span class="pl-ent"><trans data-src="tr" data-dst="TR">TR</trans></span>&gt;
&lt;/<span class="pl-ent"><trans data-src="tfoot" data-dst="设计表尾样式">设计表尾样式</trans></span>&gt;</pre></div>

<p><trans data-src="Observe that Calories is the second column in the table. Therefore, we need to offset the first column with an empty cell. If you need to offset many columns you can use " data-dst="观察到的热量表中列第二。因此，我们需要一个空单元格偏移的第一列。如果你需要弥补很多列可以使用">观察到的热量表中列第二。因此，我们需要一个空单元格偏移的第一列。如果你需要弥补很多列可以使用</trans><code>&lt;td colspan="${n}"&gt;&lt;/td&gt;</code><trans data-src=" where " data-dst="在哪儿">在哪儿</trans><code><trans data-src="n" data-dst="n"><trans data-src="n" data-dst="n">n</trans></trans></code><trans data-src=" is the number of columns to offset." data-dst="是偏移的列数。">是偏移的列数。</trans></p>

<blockquote>
<p><trans data-src="You may need to manually correct the the text alignment and cell padding if you use " data-dst="你可以使用需要手动修正文本的对齐方式、单元格填充">你可以使用需要手动修正文本的对齐方式、单元格填充</trans><code><trans data-src="colspan" data-dst="合并单元格">合并单元格</trans></code><trans data-src="." data-dst="。">。</trans></p>
</blockquote>

<h2><a id="user-content-contributing" class="anchor" href="#contributing" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Contributing" data-dst="贡献">贡献</trans></h2>

<p><strong><trans data-src="Requires" data-dst="要求">要求</trans></strong></p>

<ul>
<li><trans data-src="node" data-dst="结">结</trans></li>
<li><trans data-src="grunt-cli" data-dst="咕噜CLI">咕噜CLI</trans></li>
</ul>

<p><trans data-src="This repository contains a demo application for developing features. As you make changes the application will live reload itself." data-dst="这个库包含了开发的功能演示应用。当你更改应用程序将加载本身的生活。">这个库包含了开发的功能演示应用。当你更改应用程序将加载本身的生活。</trans></p>

<p><strong><trans data-src="Update" data-dst="更新">更新</trans></strong></p>

<p><trans data-src="I noticed the nutrition app was an inconvenience for people trying to run the app locally and contribute. I have updated the demo application to remove the dependency for the nutrition app. This is also a good example of how you can take advantage of " data-dst="我注意到营养的应用程序是人们试图运行应用局部有不便。我已经更新了演示应用程序删除应用程序依赖的营养。这也是一个很好的例子，你可以利用">我注意到营养的应用程序是人们试图运行应用局部有不便。我已经更新了演示应用程序删除应用程序依赖的营养。这也是一个很好的例子，你可以利用</trans><code><trans data-src="ngRepeat" data-dst="ngrepeat">ngrepeat</trans></code><trans data-src=" to easily achieve client side sorting and pagination." data-dst="轻松实现客户端排序和分页。">轻松实现客户端排序和分页。</trans></p>

<h5><a id="user-content-running-the-app-locally" class="anchor" href="#running-the-app-locally" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Running the App Locally" data-dst="在运行应用程序的本地">在运行应用程序的本地</trans></h5>

<p><trans data-src="Clone this repository to your local machine." data-dst="克隆这个库到你的本地机器。">克隆这个库到你的本地机器。</trans></p>

<pre><code><trans data-src="git clone https://github.com/daniel-nagy/md-data-table.git
cd md-data-table
" data-dst="git clone https: / / GitHub。COM /丹尼尔纳吉/ MD数据表。Git 
 CD MD数据表">git clone https: / / GitHub。COM /丹尼尔纳吉/ MD数据表。Git 
 CD MD数据表</trans></code></pre>

<p><trans data-src="Create a new branch for the issue you are working on." data-dst="创造你的工作问题的一个新的分支。">创造你的工作问题的一个新的分支。</trans></p>

<pre><code><trans data-src="git checkout -b my-issue
" data-dst="git checkout -我的问题">git checkout -我的问题</trans></code></pre>

<p><trans data-src="Install the package dependencies." data-dst="安装软件包的依赖关系。">安装软件包的依赖关系。</trans></p>

<pre><code><trans data-src="npm install
bower install
" data-dst="新安装
凉亭安装">新安装
凉亭安装</trans></code></pre>

<p><trans data-src="Run the application and visit " data-dst="运行和访问中的应用">运行和访问中的应用</trans><code><trans data-src="127.0.0.1:8000" data-dst="127.0.0.1:8000"><trans data-src="127.0.0.1:8000" data-dst="127.0.0.1:8000">127.0.0.1:8000</trans></trans></code><trans data-src=" in the browser." data-dst="在浏览器。">在浏览器。</trans></p>

<pre><code><trans data-src="grunt
" data-dst="咕噜">咕噜</trans></code></pre>

<p><trans data-src="Make your modifications and update the build." data-dst="修改和更新建设。">修改和更新建设。</trans></p>

<pre><code><trans data-src="grunt build
" data-dst="繁重的建设">繁重的建设</trans></code></pre>

<p><trans data-src="Create a pull request!" data-dst="创建请求的请求！">创建请求的请求！</trans></p>
</article>
##EN
# Material Design Data Table

This module is an effort to implement Material Design data tables in [Angular Material](https://material.angularjs.org/latest/#/). Data tables are used to present raw data sets and usually appear in desktop enterprise applications. Data tables are particularly useful for visualizing and manipulating large data sets.

Specification for Material Design data tables can be found [here](http://www.google.com/design/spec/components/data-tables.html).

* [License](#license)
* [Demo](#demo)
* [Installation](#installation)
* [Usage](#usage)
* [Change Log](CHANGELOG.md)
* [API Documentation](#api-documentation)
* [Contributing] (#contributing)

## License

This software is provided free of charge and without restriction under the [MIT License](LICENSE.md)

## Demo

A live [demo](http://danielnagy.me/md-data-table).

A fork-able [Codepen](http://codepen.io/anon/pen/BjvLVJ?editors=1010). Please use this to reproduce any issues you may be experiencing.

## Installation

#### Using Bower

This package is installable through the Bower package manager.

```
bower install angular-material-data-table --save
```

In your `index.html` file, include the data table module and style sheet.

```html
<!-- style sheet -->
<link href="bower_components/angular-material-data-table/dist/md-data-table.min.css" rel="stylesheet" type="text/css"/>
<!-- module -->
<script type="text/javascript" src="bower_components/angular-material-data-table/dist/md-data-table.min.js"></script>
```

Include the `md.data.table` module as a dependency in your application.

```javascript
angular.module('myApp', ['ngMaterial', 'md.data.table']);
```

#### Using npm and Browserify (or JSPM)

In addition, this package may be installed using npm.

```
npm install angular-material-data-table --save
```

You may use Browserify to inject this module into your application.

```javascript
angular.module('myApp', [require('angular-material-data-table')]);
```

## Usage

**Example Controller**

```javascript

// Assume we have a $nutrition service that provides an API for communicating with the server

angular.module('demoApp').controller('sampleController', ['$nutrition', '$scope', function ($nutrition, $scope) {
  'use strict';
  
  $scope.selected = [];
  
  $scope.query = {
    order: 'name',
    limit: 5,
    page: 1
  };
  
  function success(desserts) {
    $scope.desserts = desserts;
  }
  
  $scope.getDesserts = function () {
    $scope.promise = $nutrition.desserts.get($scope.query, success).$promise;
  };

}]);
```

**Example Template**

```html
<md-toolbar class="md-table-toolbar md-default">
  <div class="md-toolbar-tools">
    <span>Nutrition</span>
  </div>
</md-toolbar>

<!-- exact table from live demo -->
<md-table-container>
  <table md-table md-row-select multiple ng-model="selected" md-progress="promise">
    <thead md-head md-order="query.order" md-on-reorder="getDesserts">
      <tr md-row>
        <th md-column md-order-by="nameToLower"><span>Dessert (100g serving)</span></th>
        <th md-column md-numeric md-order-by="calories.value"><span>Calories</span></th>
        <th md-column md-numeric>Fat (g)</th>
        <th md-column md-numeric>Carbs (g)</th>
        <th md-column md-numeric>Protein (g)</th>
        <th md-column md-numeric>Sodium (mg)</th>
        <th md-column md-numeric>Calcium (%)</th>
        <th md-column md-numeric>Iron (%)</th>
      </tr>
    </thead>
    <tbody md-body>
      <tr md-row md-select="dessert" md-select-id="name" md-auto-select ng-repeat="dessert in desserts.data">
        <td md-cell>{{dessert.name}}</td>
        <td md-cell>{{dessert.calories.value}}</td>
        <td md-cell>{{dessert.fat.value | number: 1}}</td>
        <td md-cell>{{dessert.carbs.value}}</td>
        <td md-cell>{{dessert.protein.value | number: 1}}</td>
        <td md-cell>{{dessert.sodium.value}}</td>
        <td md-cell>{{dessert.calcium.value}}{{dessert.calcium.unit}}</td>
        <td md-cell>{{dessert.iron.value}}{{dessert.iron.unit}}</td>
      </tr>
    </tbody>
  </table>
</md-table-container>

<md-table-pagination md-limit="query.limit" md-limit-options="[5, 10, 15]" md-page="query.page" md-total="{{desserts.count}}" md-on-paginate="getDesserts" md-page-select></md-table-pagination>

```

## API Documentation

**v0.10.x**

* [Column Sorting](#column-sorting)
* [Edit Dialogs](#edit-dialogs)
* [Inline Menus](#inline-menus)
* [Numeric Columns](#numeric-columns)
* [Pagination](#pagination)
* [Row Selection](#row-selection)
* [Table Progress] (#table-progress)
* [Table Toolbars](#table-toolbars)

**Earlier Versions**

* [0.9.x](https://github.com/daniel-nagy/md-data-table/tree/v0.9.x#api-documentation)
* [<=0.8.14](https://github.com/daniel-nagy/md-data-table/tree/legacy#api-documentation)

> Tables are sorted alphabetically by their first column.
> I will be **camelCasing** attributes in tables (otherwise the cells would wrap and be difficult to read) but don't forget to **snake-case** them in your template.

### Column Sorting

| Attribute      | Element    | Type           | Description |
| :------------- | :--------- | :------------- | :---------- |
| `mdDesc`       | `mdColumn` | `[expression]` | If present, the column will sort descending first. The default is to sort ascending first. |
| `mdOnReorder`  | `mdHead`   | `function`     | A callback function for when the order changes. The callback will receive the new order. |
| `mdOrder`      | `mdHead`   | `string`       | A variable to bind the sort order to. |
| `mdOrderBy`    | `mdColumn` | `string`       | The value to bind to the sort order. |

When the user clicks the `md-column` element, the value of the `md-order-by` attribute will be bound to the variable provided to the `md-order` attribute on the `md-head` element. If the column is already sorted by that value, a minus sign `-` will be prefixed to the value. For most query languages, this is the universal symbol to sort descending.

The variable can be used to send a query to the server or as the `orderBy` property of an `ng-repeat` expression.

**Example Using ngRepeat**

```html
<md-table-container>
  <table md-table>
    <thead md-head md-order="myOrder">
      <!-- when the user clicks this cell, the myOrder variable will get the value 'nameToLower' -->
      <th md-column md-order-by="nameToLower">Dessert (100g serving)</th>
      <!-- the variable myOrder will not be changed when this cell is clicked -->
      <th md-column md-numeric>Calories</th>
    </thead>
    <tbody md-body>
      <!-- we can let ng-repeat sort the columns for us -->
      <tr ng-repeat="dessert in desserts | orderBy: myOrder"></tr>
    </tbody>
  </table>
</md-table-container>
```

### Edit Dialogs

Tables may require basic text editing. This module includes a service for displaying edit dialogs to modify text or anything else really. The service provides presets for both small and large edit dialogs designed for manipulating text. It also has full support for creating custom dialogs so you can be as creative as you want to be.

Unlike Angular Material dialogs, the preset methods will open the dialog.

**Restrictions**

* The dialog will always receive a new isolated scope.
* You must provide a `targetEvent` and the event target must be a table cell.

**Example**

```javascript
$scope.editComment = function (event, dessert) {
  // if auto selection is enabled you will want to stop the event
  // from propagating and selecting the row
  event.stopPropagation();
  
  /* 
   * messages is commented out because there is a bug currently
   * with ngRepeat and ngMessages were the messages are always
   * displayed even if the error property on the ngModelController
   * is not set, I've included it anyway so you get the idea
   */
   
  var promise = $mdEditDialog.small({
    // messages: {
    //   test: 'I don\'t like tests!'
    // },
    modelValue: dessert.comment,
    placeholder: 'Add a comment',
    save: function (input) {
      dessert.comment = input.$modelValue;
    },
    targetEvent: event,
    validators: {
      'md-maxlength': 30
    }
  });

  promise.then(function (ctrl) {
    var input = ctrl.getInput();

    input.$viewChangeListeners.push(function () {
      input.$setValidity('test', input.$modelValue !== 'test');
    });
  });
});
```

#### Small Edit Dialogs

```javascript
$mdEditDialog.small(options);
```

| Parameter | Type   | Description |
| :-------- | :----- | :---------- |
| options   | object | Small preset options. |

| Property              | Type       | Default  | Description |
| :-------------------- | :--------- | :------- | :---------- |
| `clickOutsideToClose` | `bool`     | `true`   | The user can dismiss the dialog by clicking anywhere else on the page. |
| `disableScroll`       | `bool`     | `true`   | Prevent user scroll while the dialog is open. |
| `escToClose`          | `bool`     | `true`   | The user can dismiss the dialog by clicking the esc key. |
| `focusOnOpen`         | `bool`     | `true`   | Will search the template for an `md-autofocus` element. |
| `messages`            | `object`   | `null`   | Error messages to display corresponding to errors on the `ngModelController`. |
| `modelValue`          | `string`   | `null`   | The initial value of the input element. |
| `placeholder`         | `string`   | `null`   | Placeholder text for input element. |
| `save`                | `function` | `null`   | A callback function for when the use clicks the save button. The callback will receive the [ngModelController](https://docs.angularjs.org/api/ng/type/ngModel.NgModelController). The dialog will close unless the callback returns a rejected promise. |
| `targetEvent`         | `event`    | `null`   | The event object. This must be provided and it must be from a table cell. |
| `type`                | `string`   | `"text"` | The value of the `type` attribute on the `input` element. |
| `validators`          | `object`   | `null`   | Optional attributes to be placed on the input element. |

The `small` method will return a `promise` that will resolve with the controller instance. The controller has two public methods, `dismiss` which will close the dialog without saving and `getInput` which will return the `ngModelController`.

#### Large Edit Dialogs

Large edit dialogs are functionally identical to small edit dialogs but have a few additional options.

```javascript
$mdEditDialog.large(options);
```
| Parameter | Type   | Description |
| :-------- | :----- | :---------- |
| options   | object | Large preset options. |

| Property              | Type       | Default    | Description |
| :-------------------- | :--------- | :--------- | :---------- |
| `cancel`              | `string`   | `"Cancel"` | Text to dismiss the dialog without saving. |
| `clickOutsideToClose` | `bool`     | `true`     | The user can dismiss the dialog by clicking anywhere else on the page. |
| `disableScroll`       | `bool`     | `true`     | Prevent user scroll while the dialog is open. |
| `escToClose`          | `bool`     | `true`     | The user can dismiss the dialog by clicking the esc key. |
| `focusOnOpen`         | `bool`     | `true`     | Will search the template for an `md-autofocus` element. |
| `messages`            | `object`   | `null`     | Error messages to display corresponding to errors on the `ngModelController`. |
| `modelValue`          | `string`   | `null`     | The initial value of the input element. |
| `ok`                  | `string`   | `"Save"`   | Text to submit and dismiss the dialog. |
| `placeholder`         | `string`   | `null`     | Placeholder text for input element. |
| `save`                | `function` | `null`     | A callback function for when the use clicks the save button. The callback will receive the `ngModelController`. The dialog will close unless the callback returns a rejected promise. |
| `targetEvent`         | `event`    | `null`     | The event object. This must be provided and it must be from a table cell. |
| `title`               | `string`   | `"Edit"`   | Dialog title text. |
| `type`                | `string`   | `"text"`   | The value of the `type` attribute on the `input` element. |
| `validators`          | `object`   | `null`     | Optional attributes to be placed on the input element. |

The `large` method will return a `promise` that will resolve with the controller instance. The controller has two public methods, `dismiss` which will close the dialog without saving and `getInput` which will return the `ngModelController`.

#### Roll Your Own

```javascript
$mdEditDialog.show(options);
```

| Parameter | Type   | Description |
| :-------- | :----- | :---------- |
| options   | object | Dialog options. |

| Property              | Type                | Default | Description |
| :-------------------- | :------------------ | :------ | :---------- |
| `bindToController`    | `bool`              | `false` | If true, properties on the provided scope object will be bound to the controller |
| `clickOutsideToClose` | `bool`              | `true`  | The user can dismiss the dialog by clicking anywhere else on the page. |
| `controller`          | `function` `string` | `null`  | Either a constructor function or a string register with the `$controller` service. The controller will be automatically injected with `$scope` and `$element`. Remember to annotate your controller if you will be minifying your code. |
| `controllerAs`        | `string`            | `null`  | An alias to publish your controller on the scope. |
| `disableScroll`       | `bool`              | `true`  | Prevent user scroll while the dialog is open. |
| `escToClose`          | `bool`              | `true`  | The user can dismiss the dialog by clicking the esc key. |
| `focusOnOpen`         | `bool`              | `true`  | Will search the template for an `md-autofocus` element. |
| `locals`              | `object`            | `null`  | Optional dependancies to be injected into your controller. It is not necessary to inject registered services, the `$injector` will provide them for you. |
| `resolve`             | `object`            | `null`  | Similar to locals but waits for promises to be resolved. Once the promises resolve, their return value will be injected into the controller and the dialog will open. |
| `scope`               | `object`            | `null`  | Properties to bind to the new isolated scope. |
| `targetEvent`         | `event`             | `null`  | The event object. This must be provided and it must be from a table cell. |
| `template`            | `string`            | `null`  | The template for your dialog. |
| `templateUrl`         | `string`            | `null`  | A URL to fetch your template from. |

The `show` method will return a `promise` that will resolve with the controller instance.

Table cells have a `md-placeholder` CSS class that you can use for placeholder text.

**Example: A Table Cell That Opens An Edit Dialog**

```html
<td md-cell ng-click="editComment($event, dessert)" ng-class="{'md-placeholder': !dessert.comment}">
  {{dessert.comment || 'Add a comment'}}
</td>
```

### Inline Menus

Table cells support inline menus. To use an inline menu, place an `md-select` element inside an `md-cell` element.

**Example**

```html
<td md-cell>
  <md-select ng-model="dessert.type" placeholder="Other">
    <md-option ng-value="type" ng-repeat="type in getTypes()">{{type}}</md-option>
  </md-select>
</td>
```

Clicking anywhere in the cell will activate the menu. In addition, if you have automatic row selection enabled the row will not be selected when the cell is clicked.

### Numeric Columns

Numeric columns align to the right of table cells.

| Attribute   | Element    | Type           | Description |
| :---------  | :--------- | :------------- | :---------- |
| `mdNumeric` | `mdColumn` | `[expression]` | If the expression is `null` or evaluates to `true` then all the cells in that column will be right aligned |

You may use Angular's [number](https://docs.angularjs.org/api/ng/filter/number) filter on a cell to set the decimal precision.

```html
<!-- 2 decimal places -->
<td md-cell>{{dessert.protein.value | number: 2}}</td>
```

> If you are using `colspan` you may need to manual correct the alignment and padding of cells. You can override the cell's style with a custom CSS class.

### Pagination

| Attribute           | Type         | Description |
| :---------------- | :------------- | :---------- |
| `mdBoundaryLinks` | `[expression]` | Displays first and last page navigation links |
| `mdLabel`         | `object`       | Change the pagination label (See more below). |
| `mdLimit`         | `integer`      | A row limit. |
| `mdLimitOptions`  | `array`        | Row limit options. |
| `mdOnPaginate`    | `function`     | A callback function for when the page or limit changes. The page is passed as the first argument and the limit is passed as the second argument.    |
| `mdPage`          | `integer`      | Page number. Pages are not zero indexed. The directive assumes the first page is one. |
| `mdPageSelect`    | `[expression]` | Display a select dropdown for the page number |
| `mdTotal`         | `integer`      | Total number of items. |
| `ngDisabled`      | `[expression]` | Disable pagination elements. |

The `md-label` attribute has the following properties.

| Property    | Type     | Default |
| :---------- | :------- | :------ |
| of          | `string` | 'of' (e.g. x - y of z) |
| page        | `string` | 'Page:'   |
| rowsPerPage | `string` | 'Rows per page:' |

**Example: Changing The Pagination Label**

```html
<!-- how to change the pagination label -->
<md-table-pagination md-label="{page: 'Página:', rowsPerPage: 'Filas por página:', of: 'de'}"></md-table-pagination>

<!-- or if the label is defined on the scope -->
<md-table-pagination md-label="{{label}}"></md-table-pagination>
```

> I used Google translate so if the translations are wrong please fix them and make a pull request.

**Example: Client Side Pagination Using ngRepeat**

```html
<tr md-row ng-repeat="item in array | orderBy: myOrder | limitTo: myLimit: (myPage - 1) * myLimit">

<!-- and your pagination element will look something like... -->
<md-table-pagination md-limit="myLimit" md-page="myPage" md-total="{{array.length}}"></md-table-pagination>
```

**My Pagination Isn't Working?!**

* Make sure you pass `md-page`, `md-limit`, and `md-total` to the directive and that they are finite numbers.
* Pages are not zero indexed. The directive will assume pages start at one. If your query language expects pages to be zero indexed then just subtract one before making the query.

### Row Selection

| Attribute      | Element   | Type              | Description |
| :------------- | :-------- | :---------------- | :---------- |
| `mdAutoSelect` | `mdRow`   | `[expression]`    | Select a row by clicking anywhere in the row. |
| `mdOnDeselect` | `mdRow`   | `function`        | A callback function for when an item is deselected. The item will be passed as an argument to the callback. |
| `mdOnSelect`   | `mdRow`   | `function`        | A callback function for when an item is selected. The item will be passed as an argument to the callback. |
| `mdRowSelect`  | `mdTable` | `[expression]`    | Enable row selection. |
| `mdSelect`     | `mdRow`   | `any`             | The item to be selected. |
| `mdSelectId`   | `mdRow`   | `number` `string` | A unique identifier for the selected item. The identifier must be a property of the item. |
| `multiple`     | `mdTable` | `[expression]`    | Allow multiple selection. When enabled a master toggle will be prepended to the last row of table header. |
| `ngDisabled`   | `mdRow`   | `expression`      | Conditionally disable row selection. |
| `ngModel`      | `mdTable` | `array`           | A variable to bind selected items to. |

By default selected items will persist. Equality between items is determined using the `===` operator. In cases where items may not be strictly equal, you must provide a unique identifier for the item.

You may manually add or remove items from the model but be aware that select and deselect callbacks will not be triggered. When operating in single select mode, the deselect callback will not be triggered when a user selects another item. It will be trigger, however, if the user directly deselects the item. In multi-select mode, the master toggle will trigger select and deselect callbacks for all items selected or deselected respectfully.

**Example: Row Selection From The Live Demo.**

```html
<tr md-row md-select="dessert" md-select-id="name" md-auto-select ng-repeat="dessert in desserts.data">
```

**Example: Clearing Selected Items On Pagination**

```javascript
$scope.onPaginate = function () {
  $scope.selected = [];
}
```

### Table Progress

| Attribute    | Target    | Type                       | Description |
| :----------- | :-------- | :------------------------- | :---------- |
| `mdProgress` | `mdTable` | `promise` `promise<Array>` | The table will display a loading indicator until all promises are resolved or rejected. |

The table module can display a loading indicator for you whenever asynchronous code is executing. It accepts a promise or an array of promises. If another promise is received before the previous promise is resolved or rejected it will be placed in a queue.

Because I spent almost an hour debugging this I thought I would share with you. I'm not sure why this is the case but if you put the deferred object on the scope and try to pass the promise to the directive from that, the queue mechanism will not work properly.

**This Will Not Work**

```javascript
function () {
  $scope.deferred = $q.defer();
  // ...
  $scope.deferred.resolve();
}
```

```html
<table md-table md-progress="deferred.promise"></table>
```

**This Will Work**

```javascript
function () {
  var deferred = $q.defer();
  $scope.promise = deferred.promise;
  // ...
  deferred.resolve();
}
```

```html
<table md-table md-progress="promise"></table>
```

In addition, if you are dealing with something that returns a promise directly (not a deferred object) you don't need to worry about it.

```javascript
function () {
  $scope.promise = $timeout(function () {
    // ...
  }, 2000);
}
```

### Table Toolbars

Tables may be embedded within cards that offer navigation and data manipulation tools available at the top and bottom. You can use the `md-table-toolbar` and `md-default` class on a `md-toolbar` element for a plain white toolbar.

If you need to display information relative to a particular column in the table you may use use a `<md-foot>` element. For example, say you had a `calories.total` property that summed the total number of calories and you wanted to display that information directly beneath the Calories column.

```html
<tfoot md-foot>
  <tr md-row>
    <td md-cell></td>
    <td md-cell><strong>Total: </strong>{{calories.total}}</td>
    <td md-cell colspan="6"></td>
  </tr>
</tfoot>
```

Observe that Calories is the second column in the table. Therefore, we need to offset the first column with an empty cell. If you need to offset many columns you can use `<td colspan="${n}"></td>` where `n` is the number of columns to offset.

> You may need to manually correct the the text alignment and cell padding if you use `colspan`.

## Contributing

**Requires**

* node
* grunt-cli

This repository contains a demo application for developing features. As you make changes the application will live reload itself.

**Update**

I noticed the nutrition app was an inconvenience for people trying to run the app locally and contribute. I have updated the demo application to remove the dependency for the nutrition app. This is also a good example of how you can take advantage of `ngRepeat` to easily achieve client side sorting and pagination.

##### Running the App Locally

Clone this repository to your local machine.

```
git clone https://github.com/daniel-nagy/md-data-table.git
cd md-data-table
```

Create a new branch for the issue you are working on.

```
git checkout -b my-issue
```

Install the package dependencies.

```
npm install
bower install
```

Run the application and visit `127.0.0.1:8000` in the browser.

```
grunt
```

Make your modifications and update the build.

```
grunt build
```

Create a pull request!
