##CN-ZH机器翻译中文,请参照en下原文理解(谷歌CDN修改已改为中国内使用)
<div id="readme" class="readme boxed-group clearfix announce instapaper_body md">
    <h3>
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M2 5h4v1H2v-1z m0 3h4v-1H2v1z m0 2h4v-1H2v1z m11-5H9v1h4v-1z m0 2H9v1h4v-1z m0 2H9v1h4v-1z m2-6v9c0 0.55-0.45 1-1 1H8.5l-1 1-1-1H1c-0.55 0-1-0.45-1-1V3c0-0.55 0.45-1 1-1h5.5l1 1 1-1h5.5c0.55 0 1 0.45 1 1z m-8 0.5l-0.5-0.5H1v9h6V3.5z m7-0.5H8.5l-0.5 0.5v8.5h6V3z"></path></svg><trans data-src="
      README.md
    " data-dst="readme.md">readme.md</trans></h3>

      <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-material-design-for-angularjs-apps-" class="anchor" href="#material-design-for-angularjs-apps-" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Material Design for AngularJS Apps " data-dst="AngularJS应用材料设计">AngularJS应用材料设计</trans><a href="https://travis-ci.org/angular/material"><img src="https://camo.githubusercontent.com/1eb3f848588892593f6aaab7f7c8241fb3a0bf2a/68747470733a2f2f7472617669732d63692e6f72672f616e67756c61722f6d6174657269616c2e737667" alt="Build Status" data-canonical-src="https://travis-ci.org/angular/material.svg" style="max-width:100%;"></a></h1>

<p><a href="https://www.google.com/design/spec/material-design/"><trans data-src="Material Design" data-dst="材料设计">材料设计</trans></a><trans data-src=" is a specification for a
unified system of visual, motion, and interaction design that adapts across different devices. Our
goal is to deliver a lean, lightweight set of AngularJS-native UI elements that implement the
material design specification for use in Angular single-page applications (SPAs)." data-dst="是一个
统一系统的视觉、动作规范,交互设计,适应不同的设备.我们的目标是提供一个
精益,AngularJS原生UI元素实现用于角单页应用
材料设计规范组轻(温泉).">是一个
统一系统的视觉、动作规范,交互设计,适应不同的设备.我们的目标是提供一个
精益,AngularJS原生UI元素实现用于角单页应用
材料设计规范组轻(温泉).</trans></p>

<p><a href="https://cloud.githubusercontent.com/assets/210413/5077572/30dfc2f0-6e6a-11e4-9723-07c918128f4f.png" target="_blank"><img src="https://cloud.githubusercontent.com/assets/210413/5077572/30dfc2f0-6e6a-11e4-9723-07c918128f4f.png" alt="venn diagram" style="max-width:100%;"></a></p>

<p><trans data-src="For developers using AngularJS, Angular Material is the reference implementation of Google's Material Design Specification. This project implements version 1.x of Angular Material and includes a rich set of reusable, well-tested, and accessible UI components." data-dst="开发者使用AngularJS,角材料是谷歌的材料设计规范的参考实现.本项目实现了版本1.x角材料和包含一组丰富的可复用,测试,和访问的UI组件.">开发者使用AngularJS,角材料是谷歌的材料设计规范的参考实现.本项目实现了版本1.x角材料和包含一组丰富的可复用,测试,和访问的UI组件.</trans></p>

<p><trans data-src="Quick Links:" data-dst="快速链接">快速链接</trans></p>

<ul>
<li> <a href="#demos"><trans data-src="API &amp; Demos" data-dst="API和演示">API和演示</trans></a></li>
<li> <a href="#contributing"><trans data-src="Contributing" data-dst="贡献">贡献</trans></a></li>
<li> <a href="#building"><trans data-src="Building" data-dst="建筑">建筑</trans></a></li>
<li> <a href="#installing"><trans data-src="Installing" data-dst="安装">安装</trans></a></li>
</ul>

<p><trans data-src="Please note that using Angular Material requires the use of " data-dst="请注意,使用角材料需要使用">请注意,使用角材料需要使用</trans><strong><trans data-src="Angular 1.3.x" data-dst="角1.3.x">角1.3.x</trans></strong><trans data-src=" or higher. Angular
Material is targeted for all browsers with versions n-1; where n is the current browser version." data-dst="或更高.角
材料是针对所有浏览器版本n-1；n是当前浏览器的版本.">或更高.角
材料是针对所有浏览器版本n-1；n是当前浏览器的版本.</trans></p>

<h2><a id="user-content--online-documentation-and-demos" class="anchor" href="#-online-documentation-and-demos" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><a name="user-content-demos"></a><trans data-src=" Online Documentation (and Demos)" data-dst="在线文档(和演示)">在线文档(和演示)</trans></h2>

<div>
  <a href="https://cloud.githubusercontent.com/assets/11819543/10056006/4aee3b68-6207-11e5-8497-a0656f85902a.PNG" target="_blank"><img src="https://cloud.githubusercontent.com/assets/11819543/10056006/4aee3b68-6207-11e5-8497-a0656f85902a.PNG" alt="Angular Material docs website" style="max-width:100%;"></a>
</div>

<ul>
<li><trans data-src="Visit " data-dst="访问">访问</trans><a href="https://material.angularjs.org/"><trans data-src="Material.AngularJS.org" data-dst="material.angularjs.org">material.angularjs.org</trans></a><trans data-src=" online to review the API, see the
components in action with live Demos, and study the Layout system." data-dst="在线评论的API,看到在行动
构件的现场演示,并研究其布局系统." style="background: transparent;">在线评论的API,看到在行动
构件的现场演示,并研究其布局系统.</trans></li>
<li><trans data-src="Or you can build the documentation and demos locally; see
" data-dst="或者你可以建立文档和演示局部；看">或者你可以建立文档和演示局部；看</trans><a href="https://github.com/angular/material/tree/master/docs/README.md"><trans data-src="Build Docs &amp; Demos" data-dst="文档和演示.">文档和演示.</trans></a><trans data-src=" for details." data-dst="详情.">详情.</trans></li>
</ul>

<h2><a id="user-content--our-release-processes" class="anchor" href="#-our-release-processes" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><a name="user-content-releasing"></a><trans data-src=" Our Release Processes" data-dst="我们的释放过程" style="background: transparent;">我们的释放过程</trans></h2>

<p><trans data-src="Angular Material has revised/improved its build processes. To preserve stability with applications currently using Angular Material, we will have three (3) types of releases:" data-dst="角材料已修订/改进制造流程.与应用程序正在使用角材料保持稳定,我们将有三(3)类型的版本:" style="background: transparent;">角材料已修订/改进制造流程.与应用程序正在使用角材料保持稳定,我们将有三(3)类型的版本:</trans></p>

<ul>
<li> <code><trans data-src="major" data-dst="大">大</trans></code><trans data-src=" :  this type of release will be the Angular 2.x efforts maintained in a separate repository called " data-dst=":这种类型的发布将角2.在一个单独的库称为X的努力维持">:这种类型的发布将角2.在一个单独的库称为X的努力维持</trans><a href="https://github.com/angular/material2"><trans data-src="Material2" data-dst="材质2">材质2</trans></a><trans data-src=". This type of release will not be used within Angular Material 1.x." data-dst=".这种类型的释放不会在角材料1用".">.这种类型的释放不会在角材料1用".</trans></li>
<li> <code><trans data-src="minor" data-dst="小">小</trans></code><trans data-src=":  aka " data-dst=":又名">:又名</trans><code><trans data-src="master" data-dst="硕士">硕士</trans></code><trans data-src=" contains patch release changes AND breaking changes and new features" data-dst="包含补丁的变化和断裂的变化和新的特点">包含补丁的变化和断裂的变化和新的特点</trans></li>
<li> <code><trans data-src="patch" data-dst="补丁">补丁</trans></code><trans data-src=":  non-breaking changes (no API, CSS, UX changes that will cause breaks in existing ngMaterial applications)" data-dst=":非断变化(没有API,CSS,UX的变化,将导致现有的ngmaterial应用断裂)">:非断变化(没有API,CSS,UX的变化,将导致现有的ngmaterial应用断裂)</trans></li>
</ul>

<h5><a id="user-content-patch-releases" class="anchor" href="#patch-releases" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Patch Releases" data-dst="补丁发布">补丁发布</trans></h5>

<p><trans data-src="The patch builds (1.0.4, 1.0.5, 1.0.6) are prepared based on commits in the " data-dst="建立(1.0.4补丁,1.0.5,1.0.6)是基于有准备的">建立(1.0.4补丁,1.0.5,1.0.6)是基于有准备的</trans><code><trans data-src="patch" data-dst="补丁">补丁</trans></code><trans data-src=" branch; which contains only non-breaking changes (eg bug fix, some API additions, minimal non-breaking CSS changes ).  We will be building " data-dst="分；只含有非重大更改(如bug修复,一些API的增加,最小的非破CSS的变化).我们将建设">分；只含有非重大更改(如bug修复,一些API的增加,最小的非破CSS的变化).我们将建设</trans><code><trans data-src="patch" data-dst="补丁">补丁</trans></code><trans data-src=" releases every week." data-dst="释放每一周.">释放每一周.</trans></p>

<h5><a id="user-content-minor-releases" class="anchor" href="#minor-releases" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Minor Releases" data-dst="次要版本">次要版本</trans></h5>

<p><trans data-src="The minor build (1.1.0, 1.2.0, 1.3.0,...) are prepared based on commits in the " data-dst="未建立(1.1.0,1.2.0,1.3.0,…)是基于有准备的">未建立(1.1.0,1.2.0,1.3.0,…)是基于有准备的</trans><code><trans data-src="master" data-dst="硕士">硕士</trans></code><trans data-src=" branch; which will remain the daily development branch AND will be the source for the " data-dst="分；这将保持日常的开发分支,将为源">分；这将保持日常的开发分支,将为源</trans><code><trans data-src="minor" data-dst="小">小</trans></code><trans data-src=" releases." data-dst="发布">发布</trans></p>

<p><trans data-src="Our formal release of " data-dst="我们的正式发布">我们的正式发布</trans><code><trans data-src="minor" data-dst="小">小</trans></code><trans data-src=" builds is much less frequent; probably 1x /Quarter. Developers can easily obtain the latest, full change-set from bower or npm using references to " data-dst="建立更频繁；可能1X /季度.开发人员可以很容易地获得最新的、充满变化的设置从凉亭或NPM使用参考">建立更频繁；可能1X /季度.开发人员可以很容易地获得最新的、充满变化的设置从凉亭或NPM使用参考</trans><code><trans data-src="@master" data-dst="@主">@主</trans></code><trans data-src="." data-dst=".">.</trans></p>

<h5><a id="user-content-changelog" class="anchor" href="#changelog" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Changelog" data-dst="更新日志">更新日志</trans></h5>

<p><trans data-src="The Changelog may contain releases for " data-dst="日志可能包含发布">日志可能包含发布</trans><code><trans data-src="patch" data-dst="补丁">补丁</trans></code><trans data-src=" or " data-dst="或">或</trans><code><trans data-src="minor" data-dst="小">小</trans></code><trans data-src=". If you do not see a fix listed in the Changelog but the issue has been resolved or the PR merged, then those changes will be " data-dst=".如果你没有看到一个固定在修改上市但问题已经得到解决或PR合并,然后将这些变化">.如果你没有看到一个固定在修改上市但问题已经得到解决或PR合并,然后将这些变化</trans><code><trans data-src="master" data-dst="硕士">硕士</trans></code><trans data-src=" available in the next " data-dst="在下一个可用的">在下一个可用的</trans><em><trans data-src="minor" data-dst="小">小</trans></em><trans data-src=" release." data-dst="发布">发布</trans></p>

<blockquote>
<p><trans data-src="for the purposes of Angular Material 1.x, you " data-dst="用于角材料1 X,你的目的.">用于角材料1 X,你的目的.</trans><em><trans data-src="could" data-dst="能">能</trans></em><trans data-src=" think of the patch releases as being " data-dst="认为这个补丁发布为">认为这个补丁发布为</trans><em><trans data-src="minor" data-dst="小">小</trans></em><trans data-src=" changes and the 'minor' releases as being " data-dst="变化和较小的版本是">变化和较小的版本是</trans><em><trans data-src="major" data-dst="大">大</trans></em><trans data-src=" changes." data-dst="变化.">变化.</trans></p>
</blockquote>

<h2><a id="user-content--contributing" class="anchor" href="#-contributing" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><a name="user-content-contributing"></a><trans data-src=" Contributing" data-dst="贡献">贡献</trans></h2>

<p><trans data-src="Developers interested in contributing should read the following guidelines:" data-dst="感兴趣的开发者贡献应该阅读下面的指南:">感兴趣的开发者贡献应该阅读下面的指南:</trans></p>

<ul>
<li><a href="/2947721120/material-1/blob/master/CONTRIBUTING.md#submit"><trans data-src="Issue Guidelines" data-dst="问题指南">问题指南</trans></a></li>
<li><a href="/2947721120/material-1/blob/master/CONTRIBUTING.md"><trans data-src="Contributing Guidelines" data-dst="提供指引">提供指引</trans></a></li>
<li><a href="/2947721120/material-1/blob/master/docs/guides/CODING.md"><trans data-src="Coding Guidelines" data-dst="编码指南">编码指南</trans></a></li>
<li><a href="/2947721120/material-1/blob/master/CHANGELOG.md"><trans data-src="ChangeLog" data-dst="更新日志">更新日志</trans></a></li>
</ul>

<blockquote>
<p><trans data-src="Please do " data-dst="请你">请你</trans><strong><trans data-src="not" data-dst="不">不</trans></strong><trans data-src=" ask general questions in an issue. Issues are only to report bugs, request
  enhancements, or request new features. For general questions and discussions, use the
  " data-dst="在一个问题问的一般问题.问题只报告错误,请求
增强,或要求新的特点.对于一般的问题和讨论,使用">在一个问题问的一般问题.问题只报告错误,请求
增强,或要求新的特点.对于一般的问题和讨论,使用</trans><a href="https://groups.google.com/forum/#!forum/ngmaterial"><trans data-src="Angular Material Forum" data-dst="角材料论坛">角材料论坛</trans></a><trans data-src="." data-dst=".">.</trans></p>
</blockquote>

<p><trans data-src="It is important to note that for each release, the " data-dst="需要注意的是,每个释放的重要,">需要注意的是,每个释放的重要,</trans><a href="/2947721120/material-1/blob/master/CHANGELOG.md"><trans data-src="ChangeLog" data-dst="更新日志">更新日志</trans></a><trans data-src=" is a resource that will
itemize all:" data-dst="是一种资源,将
列出所有:">是一种资源,将
列出所有:</trans></p>

<ul>
<li><trans data-src="Bug Fixes" data-dst="漏洞修补">漏洞修补</trans></li>
<li><trans data-src="New Features" data-dst="新功能">新功能</trans></li>
<li><trans data-src="Breaking Changes" data-dst="断变化">断变化</trans></li>
</ul>

<h2><a id="user-content--building" class="anchor" href="#-building" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><a name="user-content-building"></a><trans data-src=" Building" data-dst="建筑">建筑</trans></h2>

<p><trans data-src="Developers can easily build Angular Material using NPM and gulp." data-dst="开发人员可以很容易地建立角材料使用NPM和吞咽.">开发人员可以很容易地建立角材料使用NPM和吞咽.</trans></p>

<ul>
<li><a href="/2947721120/material-1/blob/master/docs/guides/BUILD.md"><trans data-src="Builds - Under the Hood" data-dst="引擎盖下的构建">引擎盖下的构建</trans></a></li>
</ul>

<p><trans data-src="First install or update your local project's " data-dst="第一次安装或更新你的本地项目">第一次安装或更新你的本地项目</trans><strong><trans data-src="npm" data-dst="新公共管理">新公共管理</trans></strong><trans data-src=" tools:" data-dst="工具">工具</trans></p>

<div class="highlight highlight-source-shell"><pre><span class="pl-c"><trans data-src="# First install all the NPM tools:" data-dst="#先安装所有新工具:">#先安装所有新工具:</trans></span><trans data-src="
npm install

" data-dst="NPM安装">NPM安装</trans><span class="pl-c"><trans data-src="# Or update" data-dst="#或更新">#或更新</trans></span><trans data-src="
npm update" data-dst="新公共管理的更新">新公共管理的更新</trans></pre></div>

<p><trans data-src="Then run the " data-dst="然后运行">然后运行</trans><strong><trans data-src="gulp" data-dst="大口">大口</trans></strong><trans data-src=" tasks:" data-dst="任务:">任务:</trans></p>

<div class="highlight highlight-source-shell"><pre><span class="pl-c"><trans data-src="# To build `angular-material.js/.css` and `Theme` files in the `/dist` directory" data-dst="#建立`角材料.JS、CSS和`主题.` `文件在` /距离`目录">#建立`角材料.JS、CSS和`主题.` `文件在` /距离`目录</trans></span><trans data-src="
gulp build

" data-dst="口建立">口建立</trans><span class="pl-c"><trans data-src="# To build the Angular Material Docs and Demos in `/dist/docs` directory" data-dst="#建立角材料文档和演示` /距离/文档`目录">#建立角材料文档和演示` /距离/文档`目录</trans></span><trans data-src="
gulp docs" data-dst="大口的文档">大口的文档</trans></pre></div>

<p><trans data-src="For more details on how the build process works and additional commands (available for testing and
debugging) developers should read the " data-dst="对于如何建立过程和附加命令的更多细节(可用于测试和调试
)开发商应该读">对于如何建立过程和附加命令的更多细节(可用于测试和调试
)开发商应该读</trans><a href="/2947721120/material-1/blob/master/docs/guides/BUILD.md"><trans data-src="Build Instructions" data-dst="版本说明">版本说明</trans></a><trans data-src="." data-dst=".">.</trans></p>

<h2><a id="user-content--installing-build-distribution-files" class="anchor" href="#-installing-build-distribution-files" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><a name="user-content-installing"></a><trans data-src=" Installing Build (Distribution Files)" data-dst="安装建设(配置文件)">安装建设(配置文件)</trans></h2>

<h4><a id="user-content-bower" class="anchor" href="#bower" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Bower" data-dst="鲍尔">鲍尔</trans></h4>

<p><trans data-src="For developers not interested in building the Angular Material library... use " data-dst="开发商在楼角材料库不感兴趣…使用">开发商在楼角材料库不感兴趣…使用</trans><strong><trans data-src="bower" data-dst="鲍尔">鲍尔</trans></strong><trans data-src=" to install
and use the Angular Material distribution files." data-dst="安装和使用
角材料分发文件.">安装和使用
角材料分发文件.</trans></p>

<p><trans data-src="Change to your project's root directory." data-dst="改变你的项目的根目录.">改变你的项目的根目录.</trans></p>

<div class="highlight highlight-source-shell"><pre><span class="pl-c"><trans data-src="# To get the latest stable version, use Bower from the command line." data-dst="#获取最新的稳定版本,从命令行使用的凉亭.">#获取最新的稳定版本,从命令行使用的凉亭.</trans></span><trans data-src="
bower install angular-material

" data-dst="鲍尔安装角材料">鲍尔安装角材料</trans><span class="pl-c"><trans data-src="# To get the most recent, latest committed-to-master version use:" data-dst="#获得最新,最新版本致力于掌握使用:">#获得最新,最新版本致力于掌握使用:</trans></span><trans data-src="
bower install angular-material#master" data-dst="鲍尔安装角材料#大师">鲍尔安装角材料#大师</trans></pre></div>

<p><trans data-src="Visit " data-dst="访问">访问</trans><a href="https://github.com/angular/bower-material/blob/master/README.md"><trans data-src="Bower-Material" data-dst="鲍尔材料">鲍尔材料</trans></a><trans data-src=" for more
details on how to install and use the Angular Material distribution files within your own local
project." data-dst="更多的
详细介绍如何安装自己的地方
项目内使用角材料分发文件.">更多的
详细介绍如何安装自己的地方
项目内使用角材料分发文件.</trans></p>

<h4><a id="user-content-cdn" class="anchor" href="#cdn" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="CDN" data-dst="CDN">CDN</trans></h4>

<p><trans data-src="CDN versions of Angular Material are now available at
" data-dst="角材料CDN版本现在是可利用的在">角材料CDN版本现在是可利用的在</trans><a href="https://developers.google.com/speed/libraries/#angular-material"><trans data-src="Google Hosted Libraries" data-dst="谷歌主办的图书馆">谷歌主办的图书馆</trans></a><trans data-src="." data-dst=".">.</trans></p>

<p><trans data-src="With the Google CDN, you will not need to download local copies of the distribution files. Instead
simply reference the CDN urls to easily use those remote library files. This is especially useful
when using online tools such as " data-dst="与谷歌的CDN,你将不需要下载配置文件的本地副本.而不是简单的参考
 CDN网址容易使用那些远程库文件.这是特别有用的
使用在线工具等">与谷歌的CDN,你将不需要下载配置文件的本地副本.而不是简单的参考
 CDN网址容易使用那些远程库文件.这是特别有用的
使用在线工具等</trans><a href="http://codepen.io/"><trans data-src="CodePen" data-dst="CodePen"><trans data-src="CodePen" data-dst="CodePen">CodePen</trans></trans></a><trans data-src=", " data-dst=",">,</trans><a href="http://plnkr.co/"><trans data-src="Plunkr" data-dst="plunkr">plunkr</trans></a><trans data-src=", or
" data-dst=",或">,或</trans><a href="http://jsfiddle.net/"><trans data-src="JSFiddle" data-dst="JSFiddle"><trans data-src="JSFiddle" data-dst="JSFiddle">JSFiddle</trans></trans></a><trans data-src="." data-dst=".">.</trans></p>

<div class="highlight highlight-text-html-basic"><pre>  &lt;<span class="pl-ent"><trans data-src="head" data-dst="头部">头部</trans></span>&gt;

    <span class="pl-c"><trans data-src="<!-- Angular Material CSS now available via Google CDN; version 0.11.2 used here -->" data-dst="<！CSS角材料现在可以通过谷歌的CDN版本0.11.2这里-->">&lt;！CSS角材料现在可以通过谷歌的CDN版本0.11.2这里--&gt;</trans></span>
    &lt;<span class="pl-ent"><trans data-src="link" data-dst="链接">链接</trans></span> <span class="pl-e"><trans data-src="rel" data-dst="REL">REL</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="stylesheet" data-dst="样式表">样式表</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span> <span class="pl-e"><trans data-src="href" data-dst="href"><trans data-src="href" data-dst="href">href</trans></trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.css" data-dst="https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.css">https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.css</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;

  &lt;/<span class="pl-ent"><trans data-src="head" data-dst="头部">头部</trans></span>&gt;
  &lt;<span class="pl-ent"><trans data-src="body" data-dst="身体">身体</trans></span>&gt;

    <span class="pl-c"><trans data-src="<!-- Angular Material Dependencies -->" data-dst="<！角材料依赖-->">&lt;！角材料依赖--&gt;</trans></span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular.min.js" data-dst="http://angularjs ajax.c2cmalls.com Ajax/7/angular.min.js LIBS">http://angularjs ajax.c2cmalls.com Ajax/7/angular.min.js LIBS</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-animate.min.js" data-dst="ajax.c2cmalls.com https:///Ajax技术的angularjs 1.3.15 /angular-animate.min.js">ajax.c2cmalls.com https:///Ajax技术的angularjs 1.3.15 /angular-animate.min.js</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-aria.min.js" data-dst="http://angularjs ajax.c2cmalls.com Ajax/7/angular-aria.min.js LIBS">http://angularjs ajax.c2cmalls.com Ajax/7/angular-aria.min.js LIBS</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>


    <span class="pl-c"><trans data-src="<!-- Angular Material Javascript now available via Google CDN; version 0.11.2 used here -->" data-dst="<！角材料JavaScript现在可以通过谷歌的CDN版本0.11.2这里-->">&lt;！角材料JavaScript现在可以通过谷歌的CDN版本0.11.2这里--&gt;</trans></span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.js" data-dst="https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.js">https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.js</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>
  &lt;/<span class="pl-ent"><trans data-src="body" data-dst="身体">身体</trans></span>&gt;</pre></div>

<blockquote>
<p><trans data-src="Note that the above sample references the 0.10.0 CDN release. Your version will change based on the latest stable release version." data-dst="注意,上面的示例引用0.10.0 CDN释放.你的版本将基于最新的稳定版本的变化.">注意,上面的示例引用0.10.0 CDN释放.你的版本将基于最新的稳定版本的变化.</trans></p>
</blockquote>

<p><trans data-src="Developers seeking the latest, most-current build versions can use " data-dst="开发商寻求最新,最当前版本可以使用">开发商寻求最新,最当前版本可以使用</trans><a href="//gitcdn.link"><trans data-src="GitCDN.link" data-dst="gitcdn.link">gitcdn.link</trans></a><trans data-src=" to
pull directly from the distribution GitHub
" data-dst="对
拉直接从分布GitHub">对
拉直接从分布GitHub</trans><a href="https://github.com/angular/bower-material"><trans data-src="Bower-Material" data-dst="鲍尔材料">鲍尔材料</trans></a><trans data-src=" repository:" data-dst="知识库:">知识库:</trans></p>

<div class="highlight highlight-text-html-basic"><pre>  &lt;<span class="pl-ent"><trans data-src="head" data-dst="头部">头部</trans></span>&gt;

    <span class="pl-c"><trans data-src="<!-- Angular Material CSS using GitCDN to load directly from `bower-material/master` -->" data-dst="<！用gitcdn负载直接从`凉亭材料/硕士`角材料CSS -->">&lt;！用gitcdn负载直接从`凉亭材料/硕士`角材料CSS --&gt;</trans></span>
    &lt;<span class="pl-ent"><trans data-src="link" data-dst="链接">链接</trans></span> <span class="pl-e"><trans data-src="rel" data-dst="REL">REL</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="stylesheet" data-dst="样式表">样式表</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span> <span class="pl-e"><trans data-src="href" data-dst="href"><trans data-src="href" data-dst="href">href</trans></trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://gitcdn.link/repo/angular/bower-material/master/angular-material.css" data-dst="https://gitcdn.link/repo/angular/bower-material/master/angular-material.css">https://gitcdn.link/repo/angular/bower-material/master/angular-material.css</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;

  &lt;/<span class="pl-ent"><trans data-src="head" data-dst="头部">头部</trans></span>&gt;
  &lt;<span class="pl-ent"><trans data-src="body" data-dst="身体">身体</trans></span>&gt;

    <span class="pl-c"><trans data-src="<!-- Angular Material Dependencies -->" data-dst="<！角材料依赖-->">&lt;！角材料依赖--&gt;</trans></span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular.js" data-dst="http://angularjs ajax.c2cmalls.com Ajax/7/angular.js LIBS">http://angularjs ajax.c2cmalls.com Ajax/7/angular.js LIBS</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-animate.js" data-dst="http://的Ajax库ajax.c2cmalls.com angularjs angular-animate.js 1.3.15 //">http://的Ajax库ajax.c2cmalls.com angularjs angular-animate.js 1.3.15 //</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-aria.js" data-dst="http://angularjs ajax.c2cmalls.com Ajax/7/angular-aria.js LIBS">http://angularjs ajax.c2cmalls.com Ajax/7/angular-aria.js LIBS</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>

    <span class="pl-c"><trans data-src="<!-- Angular Material Javascript using GitCDN to load directly from `bower-material/master` -->" data-dst="<！用gitcdn负载直接从`凉亭材料/硕士`角材料JavaScript -->">&lt;！用gitcdn负载直接从`凉亭材料/硕士`角材料JavaScript --&gt;</trans></span>
<span class="pl-s1">    &lt;<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span> <span class="pl-e"><trans data-src="src" data-dst="SRC">SRC</trans></span>=<span class="pl-s"><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span><trans data-src="https://gitcdn.link/repo/angular/bower-material/master/angular-material.js" data-dst="https://gitcdn.link/repo/angular/bower-material/master/angular-material.js">https://gitcdn.link/repo/angular/bower-material/master/angular-material.js</trans><span class="pl-pds"><trans data-src="" "="" data-dst=""">"</trans></span></span>&gt;&lt;/<span class="pl-ent"><trans data-src="script" data-dst="脚本">脚本</trans></span>&gt;</span>

  &lt;/<span class="pl-ent"><trans data-src="body" data-dst="身体">身体</trans></span>&gt;</pre></div>

<p><trans data-src="Once you have all the necessary assets installed, add " data-dst="一旦你有了所有必要的资产设置,添加">一旦你有了所有必要的资产设置,添加</trans><code><trans data-src="ngMaterial" data-dst="ngmaterial">ngmaterial</trans></code><trans data-src=" as a dependency for your app:" data-dst="为您的应用程序依赖:">为您的应用程序依赖:</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst=".">.</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="(">(</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="myApp" data-dst="MyApp">MyApp</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src=", [" data-dst=",[">,[</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span><trans data-src="ngMaterial" data-dst="ngmaterial">ngmaterial</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="'">'</trans></trans></span></span><trans data-src="]);" data-dst="])；">])；</trans></pre></div>
</article>
  </div>
##EN
# Material Design for AngularJS Apps [![Build Status](https://travis-ci.org/angular/material.svg)](https://travis-ci.org/angular/material)

[Material Design](https://www.google.com/design/spec/material-design/) is a specification for a
unified system of visual, motion, and interaction design that adapts across different devices. Our
goal is to deliver a lean, lightweight set of AngularJS-native UI elements that implement the
material design specification for use in Angular single-page applications (SPAs).

![venn diagram](https://cloud.githubusercontent.com/assets/210413/5077572/30dfc2f0-6e6a-11e4-9723-07c918128f4f.png)

For developers using AngularJS, Angular Material is the reference implementation of Google's Material Design Specification. This project implements version 1.x of Angular Material and includes a rich set of reusable, well-tested, and accessible UI components.

Quick Links:

*  [API & Demos](#demos)
*  [Contributing](#contributing)
*  [Building](#building)
*  [Installing](#installing)


Please note that using Angular Material requires the use of **Angular 1.3.x** or higher. Angular
Material is targeted for all browsers with versions n-1; where n is the current browser version.

## <a name="demos"></a> Online Documentation (and Demos)

<div style="border: 1px solid #ccc">
  <img src="https://cloud.githubusercontent.com/assets/11819543/10056006/4aee3b68-6207-11e5-8497-a0656f85902a.PNG" alt="Angular Material docs website" style="display:block;">
</div>

- Visit [Material.AngularJS.org](https://material.angularjs.org/) online to review the API, see the
  components in action with live Demos, and study the Layout system.
- Or you can build the documentation and demos locally; see
  [Build Docs & Demos](https://github.com/angular/material/tree/master/docs/README.md) for details.


## <a name="releasing"></a> Our Release Processes

Angular Material has revised/improved its build processes. To preserve stability with applications currently using Angular Material, we will have three (3) types of releases:

*  `major` :  this type of release will be the Angular 2.x efforts maintained in a separate repository called [Material2](https://github.com/angular/material2). This type of release will not be used within Angular Material 1.x.
*  `minor`:  aka `master` contains patch release changes AND breaking changes and new features
*  `patch`:  non-breaking changes (no API, CSS, UX changes that will cause breaks in existing ngMaterial applications)

##### Patch Releases

The patch builds (1.0.4, 1.0.5, 1.0.6) are prepared based on commits in the `patch` branch; which contains only non-breaking changes (eg bug fix, some API additions, minimal non-breaking CSS changes ).  We will be building `patch` releases every week.

##### Minor Releases

The minor build (1.1.0, 1.2.0, 1.3.0,...) are prepared based on commits in the `master` branch; which will remain the daily development branch AND will be the source for the `minor` releases.

Our formal release of `minor` builds is much less frequent; probably 1x / Quarter. Developers can easily obtain the latest, full change-set from bower or npm using references to `@master`.

##### Changelog

The Changelog may contain releases for `patch` or `minor`. If you do not see a fix listed in the Changelog but the issue has been resolved or the PR merged, then those changes will be `master` available in the next *minor* release.

> for the purposes of Angular Material 1.x, you *could* think of the patch releases as being *minor* changes and the 'minor' releases as being *major* changes.


## <a name="contributing"></a> Contributing

Developers interested in contributing should read the following guidelines:

- [Issue Guidelines](CONTRIBUTING.md#submit)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Coding Guidelines](docs/guides/CODING.md)
- [ChangeLog](CHANGELOG.md)

> Please do **not** ask general questions in an issue. Issues are only to report bugs, request
  enhancements, or request new features. For general questions and discussions, use the
  [Angular Material Forum](https://groups.google.com/forum/#!forum/ngmaterial).

It is important to note that for each release, the [ChangeLog](CHANGELOG.md) is a resource that will
itemize all:

- Bug Fixes
- New Features
- Breaking Changes

## <a name="building"></a> Building

Developers can easily build Angular Material using NPM and gulp.

* [Builds - Under the Hood](docs/guides/BUILD.md)

First install or update your local project's **npm** tools:

```bash
# First install all the NPM tools:
npm install

# Or update
npm update
```

Then run the **gulp** tasks:

```bash
# To build `angular-material.js/.css` and `Theme` files in the `/dist` directory
gulp build

# To build the Angular Material Docs and Demos in `/dist/docs` directory
gulp docs
```

For more details on how the build process works and additional commands (available for testing and
debugging) developers should read the [Build Instructions](docs/guides/BUILD.md).

## <a name="installing"></a> Installing Build (Distribution Files)

#### Bower

For developers not interested in building the Angular Material library... use **bower** to install
and use the Angular Material distribution files.

Change to your project's root directory.

```bash
# To get the latest stable version, use Bower from the command line.
bower install angular-material

# To get the most recent, latest committed-to-master version use:
bower install angular-material#master
```

Visit [Bower-Material](https://github.com/angular/bower-material/blob/master/README.md) for more
details on how to install and use the Angular Material distribution files within your own local
project.

#### CDN

CDN versions of Angular Material are now available at
[Google Hosted Libraries](https://developers.google.com/speed/libraries/#angular-material).

With the Google CDN, you will not need to download local copies of the distribution files. Instead
simply reference the CDN urls to easily use those remote library files. This is especially useful
when using online tools such as [CodePen](http://codepen.io/), [Plunkr](http://plnkr.co/), or
[JSFiddle](http://jsfiddle.net/).

```html
  <head>

    <!-- Angular Material CSS now available via Google CDN; version 0.11.2 used here -->
    <link rel="stylesheet" href="https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.css">

  </head>
  <body>

    <!-- Angular Material Dependencies -->
    <script src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular.min.js"></script>
    <script src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-animate.min.js"></script>
    <script src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-aria.min.js"></script>


    <!-- Angular Material Javascript now available via Google CDN; version 0.11.2 used here -->
    <script src="https://ajax.c2cmalls.com/ajax/libs/angular_material/0.11.2/angular-material.min.js"></script>
  </body>
```

> Note that the above sample references the 0.10.0 CDN release. Your version will change based on the latest stable release version.

Developers seeking the latest, most-current build versions can use [GitCDN.link](//gitcdn.link) to
pull directly from the distribution GitHub
[Bower-Material](https://github.com/angular/bower-material) repository:

```html
  <head>

    <!-- Angular Material CSS using GitCDN to load directly from `bower-material/master` -->
    <link rel="stylesheet" href="https://gitcdn.link/repo/angular/bower-material/master/angular-material.css">

  </head>
  <body>

    <!-- Angular Material Dependencies -->
    <script src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular.js"></script>
    <script src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-animate.js"></script>
    <script src="https://ajax.c2cmalls.com/ajax/libs/angularjs/1.3.15/angular-aria.js"></script>

    <!-- Angular Material Javascript using GitCDN to load directly from `bower-material/master` -->
    <script src="https://gitcdn.link/repo/angular/bower-material/master/angular-material.js"></script>

  </body>
```

Once you have all the necessary assets installed, add `ngMaterial` as a dependency for your app:

```javascript
angular.module('myApp', ['ngMaterial']);
```

