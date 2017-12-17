





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-1c2c316b7a17f15536c6a26ed744654fc228a24658a7ae395cdcbf8329c8406b.css" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-a83d0dd1d52f7ad052dfbc843bfb6d4f76108df4328e23a5f4d9350124a3952b.css" media="all" rel="stylesheet" />
  
  
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/site-44b6bba3881278f33c221b6526379b55fbd098af3e553f54e81cab4c9a517c8e.css" media="all" rel="stylesheet" />
  

  <meta name="viewport" content="width=device-width">
  
  <title>dockerfile/README.md at master · mritd/dockerfile · GitHub</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars1.githubusercontent.com/u/13043245?s=400&amp;v=4" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="mritd/dockerfile" property="og:title" /><meta content="https://github.com/mritd/dockerfile" property="og:url" /><meta content="dockerfile - 一些常用的 docker 镜像" property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="3A25:2BF59:5B3682A:886EEA4:5A369804" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="3A25:2BF59:5B3682A:886EEA4:5A369804" name="octolytics-dimension-request_id" /><meta content="sea" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged Out">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="YzIyODVlY2Y3NjcyOTI0NGVlNGZkYWExZTBhZDUyZTEwOTlmNWFhYzdhM2NkMDNiMTNmMDhmZGNlMTU1MDc2ZXx7InJlbW90ZV9hZGRyZXNzIjoiMTgwLjE1NS40OS44MSIsInJlcXVlc3RfaWQiOiIzQTI1OjJCRjU5OjVCMzY4MkE6ODg2RUVBNDo1QTM2OTgwNCIsInRpbWVzdGFtcCI6MTUxMzUyNzMwMCwiaG9zdCI6ImdpdGh1Yi5jb20ifQ==">


  <meta name="html-safe-nonce" content="aabbc907caad09bedb9b320adf8fbad1f24e36ce">

  <meta http-equiv="x-pjax-version" content="b80347226b79d13e9e3518db050dffbe">
  

      <link href="https://github.com/mritd/dockerfile/commits/master.atom" rel="alternate" title="Recent Commits to dockerfile:master" type="application/atom+xml">

  <meta name="description" content="dockerfile - 一些常用的 docker 镜像">
  <meta name="go-import" content="github.com/mritd/dockerfile git https://github.com/mritd/dockerfile.git">

  <meta content="13043245" name="octolytics-dimension-user_id" /><meta content="mritd" name="octolytics-dimension-user_login" /><meta content="66067220" name="octolytics-dimension-repository_id" /><meta content="mritd/dockerfile" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="66067220" name="octolytics-dimension-repository_network_root_id" /><meta content="mritd/dockerfile" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/mritd/dockerfile/blob/master/shadowsocks/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



  </head>

  <body class="logged-out env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    
      



        <header class="Header header-logged-out  position-relative f4 py-3" role="banner">
  <div class="container-lg d-flex px-3">
    <div class="d-flex flex-justify-between flex-items-center">
      <a class="header-logo-invertocat my-0" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
        <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
      </a>

    </div>

    <div class="HeaderMenu HeaderMenu--bright d-flex flex-justify-between flex-auto">
        <nav class="mt-0">
          <ul class="d-flex list-style-none">
              <li class="ml-2">
                <a href="/features" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:features" data-selected-links="/features /features/project-management /features/code-review /features/project-management /features/integrations /features">
                  Features
</a>              </li>
              <li class="ml-4">
                <a href="/business" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:business" data-selected-links="/business /business/security /business/customers /business">
                  Business
</a>              </li>

              <li class="ml-4">
                <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                  Explore
</a>              </li>

              <li class="ml-4">
                    <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:marketplace" data-selected-links=" /marketplace">
                      Marketplace
</a>              </li>
              <li class="ml-4">
                <a href="/pricing" class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:pricing" data-selected-links="/pricing /pricing/developer /pricing/team /pricing/business-hosted /pricing/business-enterprise /pricing">
                  Pricing
</a>              </li>
          </ul>
        </nav>

      <div class="d-flex">
          <div class="d-lg-flex flex-items-center mr-3">
            <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/mritd/dockerfile/search" class="js-site-search-form" data-scoped-search-url="/mritd/dockerfile/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/mritd/dockerfile/blob/master/shadowsocks/README.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

          </div>

        <span class="d-inline-block">
            <div class="HeaderNavlink px-0 py-2 m-0">
              <a class="text-bold text-white no-underline" href="/login?return_to=%2Fmritd%2Fdockerfile%2Fblob%2Fmaster%2Fshadowsocks%2FREADME.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
                <span class="text-gray">or</span>
                <a class="text-bold text-white no-underline" href="/join?source=header-repo" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
            </div>
        </span>
      </div>
    </div>
  </div>
</header>


  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      





  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav ">
    <div class="repohead-details-container clearfix container ">

      <ul class="pagehead-actions">
  <li>
      <a href="/login?return_to=%2Fmritd%2Fdockerfile"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
  </a>
  <a class="social-count" href="/mritd/dockerfile/watchers"
     aria-label="21 users are watching this repository">
    21
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fmritd%2Fdockerfile"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
    Star
  </a>

    <a class="social-count js-social-count" href="/mritd/dockerfile/stargazers"
      aria-label="474 users starred this repository">
      474
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fmritd%2Fdockerfile"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
      </a>

    <a href="/mritd/dockerfile/network" class="social-count"
       aria-label="154 users forked this repository">
      154
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/mritd" class="url fn" rel="author">mritd</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/mritd/dockerfile" data-pjax="#js-repo-pjax-container">dockerfile</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/mritd/dockerfile" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /mritd/dockerfile" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/mritd/dockerfile/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /mritd/dockerfile/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/mritd/dockerfile/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /mritd/dockerfile/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/mritd/dockerfile/projects" class="js-selected-navigation-item reponav-item" data-hotkey="g b" data-selected-links="repo_projects new_repo_project repo_project /mritd/dockerfile/projects">
      <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>


  <a href="/mritd/dockerfile/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /mritd/dockerfile/pulse">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    
  <a href="/mritd/dockerfile/blob/9dfba652aed6905f0af47120fdeda07b271e20fc/shadowsocks/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:89b4007e84cd163997249ef7aa059c1d -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/mritd/dockerfile/blob/master/shadowsocks/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/mritd/dockerfile/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/mritd/dockerfile"><span>dockerfile</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a href="/mritd/dockerfile/tree/master/shadowsocks"><span>shadowsocks</span></a></span><span class="separator">/</span><strong class="final-path">README.md</strong>
    </div>
  </div>


  <include-fragment class="commit-tease" src="/mritd/dockerfile/contributors/master/shadowsocks/README.md">
    <div>
      Fetching contributors&hellip;
    </div>

    <div class="commit-tease-contributors">
      <img alt="" class="loader-loading float-left" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" />
      <span class="loader-error">Cannot retrieve contributors at this time</span>
    </div>
</include-fragment>

  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/mritd/dockerfile/raw/master/shadowsocks/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/mritd/dockerfile/blame/master/shadowsocks/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/mritd/dockerfile/commits/master/shadowsocks/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>


        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
        </button>
  </div>

  <div class="file-info">
      214 lines (122 sloc)
      <span class="file-info-divider"></span>
    7.13 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h2><a href="#shadowsocks" aria-hidden="true" class="anchor" id="user-content-shadowsocks"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>shadowsocks</h2>
<p><a href="https://microbadger.com/images/mritd/shadowsocks" title="Get your own image badge on microbadger.com" rel="nofollow"><img src="https://camo.githubusercontent.com/266cc7f60902163062767da4002a5f6877ec6193/68747470733a2f2f696d616765732e6d6963726f6261646765722e636f6d2f6261646765732f696d6167652f6d726974642f736861646f77736f636b732e737667" alt="" data-canonical-src="https://images.microbadger.com/badges/image/mritd/shadowsocks.svg" style="max-width:100%;"></a> <a href="https://microbadger.com/images/mritd/shadowsocks" title="Get your own version badge on microbadger.com" rel="nofollow"><img src="https://camo.githubusercontent.com/828bfd7ab30a8dc827c46e8aba2e1dc1fd46103d/68747470733a2f2f696d616765732e6d6963726f6261646765722e636f6d2f6261646765732f76657273696f6e2f6d726974642f736861646f77736f636b732e737667" alt="" data-canonical-src="https://images.microbadger.com/badges/version/mritd/shadowsocks.svg" style="max-width:100%;"></a></p>
<ul>
<li><strong>shadowsocks-libev 版本: 3.1.1</strong></li>
<li><strong>kcptun 版本: 20171113</strong></li>
</ul>
<h3><a href="#打开姿势" aria-hidden="true" class="anchor" id="user-content-打开姿势"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>打开姿势</h3>
<div class="highlight highlight-source-shell"><pre>docker run -dt --name ss -p 6443:6443 mritd/shadowsocks -s <span class="pl-s"><span class="pl-pds">"</span>-s 0.0.0.0 -p 6443 -m aes-256-cfb -k test123 --fast-open<span class="pl-pds">"</span></span></pre></div>
<h3><a href="#支持选项" aria-hidden="true" class="anchor" id="user-content-支持选项"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>支持选项</h3>
<ul>
<li><code>-m</code> : 指定 shadowsocks 命令，默认为 <code>ss-server</code></li>
<li><code>-s</code> : shadowsocks-libev 参数字符串</li>
<li><code>-x</code> : 开启 kcptun 支持</li>
<li><code>-e</code> : 指定 kcptun 命令，默认为 <code>kcpserver</code></li>
<li><code>-k</code> : kcptun 参数字符串</li>
</ul>
<h3><a href="#选项描述" aria-hidden="true" class="anchor" id="user-content-选项描述"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>选项描述</h3>
<ul>
<li><code>-m</code> : 参数后指定一个 shadowsocks 命令，如 ss-local，不写默认为 ss-server；该参数用于 shadowsocks 在客户端和服务端工作模式间切换，可选项如下: <code>ss-local</code>、<code>ss-manager</code>、<code>ss-nat</code>、<code>ss-redir</code>、<code>ss-server</code>、<code>ss-tunnel</code></li>
<li><code>-s</code> : 参数后指定一个 shadowsocks-libev 的参数字符串，所有参数将被拼接到 <code>ss-server</code> 后</li>
<li><code>-x</code> : 指定该参数后才会开启 kcptun 支持，否则将默认禁用 kcptun</li>
<li><code>-e</code> : 参数后指定一个 kcptun 命令，如 kcpclient，不写默认为 kcpserver；该参数用于 kcptun 在客户端和服务端工作模式间切换，可选项如下: <code>kcpserver</code>、<code>kcpclient</code></li>
<li><code>-k</code> : 参数后指定一个 kcptun 的参数字符串，所有参数将被拼接到 <code>kcptun</code> 后</li>
</ul>
<h3><a href="#命令示例" aria-hidden="true" class="anchor" id="user-content-命令示例"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>命令示例</h3>
<p><strong>Server 端</strong></p>
<div class="highlight highlight-source-shell"><pre>docker run -dt --name ssserver -p 6443:6443 -p 6500:6500/udp mritd/shadowsocks -m <span class="pl-s"><span class="pl-pds">"</span>ss-server<span class="pl-pds">"</span></span> -s <span class="pl-s"><span class="pl-pds">"</span>-s 0.0.0.0 -p 6443 -m aes-256-cfb -k test123 --fast-open<span class="pl-pds">"</span></span> -x -e <span class="pl-s"><span class="pl-pds">"</span>kcpserver<span class="pl-pds">"</span></span> -k <span class="pl-s"><span class="pl-pds">"</span>-t 127.0.0.1:6443 -l :6500 -mode fast2<span class="pl-pds">"</span></span></pre></div>
<p><strong>以上命令相当于执行了</strong></p>
<div class="highlight highlight-source-shell"><pre>ss-server -s 0.0.0.0 -p 6443 -m aes-256-cfb -k test123 --fast-open
kcpserver -t 127.0.0.1:6443 -l :6500 -mode fast2</pre></div>
<p><strong>Client 端</strong></p>
<div class="highlight highlight-source-shell"><pre>docker run -dt --name ssclient -p 1080:1080 mritd/shadowsocks -m <span class="pl-s"><span class="pl-pds">"</span>ss-local<span class="pl-pds">"</span></span> -s <span class="pl-s"><span class="pl-pds">"</span>-s 127.0.0.1 -p 6500 -b 0.0.0.0 -l 1080 -m aes-256-cfb -k test123 --fast-open<span class="pl-pds">"</span></span> -x -e <span class="pl-s"><span class="pl-pds">"</span>kcpclient<span class="pl-pds">"</span></span> -k <span class="pl-s"><span class="pl-pds">"</span>-r SSSERVER_IP:6500 -l :6500 -mode fast2<span class="pl-pds">"</span></span></pre></div>
<p><strong>以上命令相当于执行了</strong></p>
<div class="highlight highlight-source-shell"><pre>ss-local -s 127.0.0.1 -p 6500 -b 0.0.0.0 -l 1080 -m aes-256-cfb -k test123 --fast-open 
kcpclient -r SSSERVER_IP:6500 -l :6500 -mode fast2</pre></div>
<p><strong>关于 shadowsocks-libev 和 kcptun 都支持哪些参数请自行查阅官方文档，本镜像只做一个拼接</strong></p>
<p><strong>注意：kcptun 映射端口为 udp 模式(<code>6500:6500/udp</code>)，不写默认 tcp；shadowsocks 请监听 0.0.0.0</strong></p>
<h3><a href="#环境变量支持" aria-hidden="true" class="anchor" id="user-content-环境变量支持"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>环境变量支持</h3>
<table>
<thead>
<tr>
<th>环境变量</th>
<th>作用</th>
<th>取值</th>
</tr>
</thead>
<tbody>
<tr>
<td>SS_MODULE</td>
<td>shadowsocks 启动命令</td>
<td><code>ss-local</code>、<code>ss-manager</code>、<code>ss-nat</code>、<code>ss-redir</code>、<code>ss-server</code>、<code>ss-tunnel</code></td>
</tr>
<tr>
<td>SS_CONFIG</td>
<td>shadowsocks-libev 参数字符串</td>
<td>所有字符串内内容应当为 shadowsocks-libev 支持的选项参数</td>
</tr>
<tr>
<td>KCP_FLAG</td>
<td>是否开启 kcptun 支持</td>
<td>可选参数为 true 和 false，默认为 fasle 禁用 kcptun</td>
</tr>
<tr>
<td>KCP_MODULE</td>
<td>kcptun 启动命令</td>
<td><code>kcpserver</code>、<code>kcpclient</code></td>
</tr>
<tr>
<td>KCP_CONFIG</td>
<td>kcptun 参数字符串</td>
<td>所有字符串内内容应当为 kcptun 支持的选项参数</td>
</tr></tbody></table>
<p>使用时可指定环境变量，如下</p>
<div class="highlight highlight-source-shell"><pre>docker run -dt --name ss -p 6443:6443 -p 6500:6500/udp -e SS_CONFIG=<span class="pl-s"><span class="pl-pds">"</span>-s 0.0.0.0 -p 6443 -m aes-256-cfb -k test123 --fast-open<span class="pl-pds">"</span></span> -e KCP_MODULE=<span class="pl-s"><span class="pl-pds">"</span>kcpserver<span class="pl-pds">"</span></span> -e KCP_CONFIG=<span class="pl-s"><span class="pl-pds">"</span>-t 127.0.0.1:6443 -l :6500 -mode fast2<span class="pl-pds">"</span></span> -e KCP_FLAG=<span class="pl-s"><span class="pl-pds">"</span>true<span class="pl-pds">"</span></span> mritd/shadowsocks</pre></div>
<h3><a href="#容器平台说明" aria-hidden="true" class="anchor" id="user-content-容器平台说明"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>容器平台说明</h3>
<p><strong>各大免费容器平台都已经对代理工具做了对应封锁，一是为了某些不可描述的原因，二是为了防止被利用称为 DDOS 工具等；基于种种原因，公共免费容器平台问题将不予回复</strong></p>
<h3><a href="#更新日志" aria-hidden="true" class="anchor" id="user-content-更新日志"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>更新日志</h3>
<ul>
<li>2016-10-12 基于 shadowsocks 2.9.0 版本</li>
</ul>
<p>基于 shadowsocks 2.9.0 版本打包 docker image</p>
<ul>
<li>2016-10-13 增加 kcptun 支持</li>
</ul>
<p>增加 kcptun 的支持，使用 <code>-x</code> 可关闭</p>
<ul>
<li>2016-10-14 增加 环境变量支持</li>
</ul>
<p>增加 默认读取环境变量策略，可通过环境变量指定 shadowsocks 相关设置</p>
<ul>
<li>2016-11-01 升级 kcptun，增加 kcptun 自定义配置选项(-c 或 环境变量)</li>
</ul>
<p>增加了 <code>-c</code> 参数和环境变量 <code>KCPTUN_CONFIG</code>，用于在不挂载文件的情况下重写 kcptun 的配置</p>
<ul>
<li>2016-11-07 chacha20 加密支持</li>
</ul>
<p>增加了 libsodium 库,用于支持 chacha20 加密算法(感谢 Lihang Chen 提出),删除了 wget 进一步精简镜像体积</p>
<ul>
<li>2016-11-30 更新 kcptun 版本</li>
</ul>
<p>更新 kcptun 版本到 20161118，修正样例命令中 kcptun 端口号使用 tcp 问题(应使用 udp)，感谢 Zheart 提出</p>
<ul>
<li>2016-12-19 更新 kcptun 到 20161202</li>
</ul>
<p>更新 kcptun 版本到 20161202，完善 README 中 kcptun 说明</p>
<ul>
<li>2016-12-30 更新 kcptun 到 20161222</li>
</ul>
<p>更新 kcptun 版本到 20161222，更新基础镜像 alpine 到 3.5</p>
<ul>
<li>2017-01-20 升级 kcptun 到 20170117</li>
</ul>
<p>更新 kcptun 到 20170117，kcptun 新版本 ack 结构中更准确的RTT估算，锁优化，更平滑的rtt计算jitter，
建议更新；同时 20170120 处于 Pre-release 暂不更新；<strong>最近比较忙，可能 kcptun 配置已经有更新，具体
请参考 kcptun 官网及 <a href="https://github.com/xtaci/kcptun">Github</a></strong></p>
<ul>
<li>2017-01-25 升级 kcptun 到 20171222</li>
</ul>
<p>更新 kcptun 到 2017...... 别的我忘了......</p>
<ul>
<li>2017-02-08 升级 kcptun 到 20170120</li>
</ul>
<p>更新 kcptun 到 20170120，<strong>下个版本准备切换到 shadowsocks-libev 3.0，目前 3.0 还未正式发布，观望中!</strong></p>
<ul>
<li>2017-02-25 切换到 shadowsocks-libev</li>
</ul>
<p>切换到 shadowsocks-libev 3.0 版本，同时更新 kcptun 和参数设定</p>
<ul>
<li>2017-03-07 升级 kcptun 到 20170303</li>
</ul>
<p>更新 kcptun 到 20170303</p>
<ul>
<li>2017-03-09 升级 kcptun 到 20170308</li>
</ul>
<p>更新 kcptun 到 20170308</p>
<ul>
<li>2017-03-17 升级 kcptun 和 shadowsocks-libev</li>
</ul>
<p>升级 shadowsocks-libev 到 3.0.4 版本，支持 <code>TCP Fast Open in ss-redir</code>、<code>TOS/DESCP in ss-redir</code> 和细化 MPTCP；升级 kcptun 到 315 打假版本 <code>(:</code></p>
<ul>
<li>2017-03-21 增加多命令支持</li>
</ul>
<p>新增 <code>-m</code> 参数用于指定使用那个 shadowsocks 命令，如果作为客户端使用 <code>-m ss-local</code>,
不写的情况下默认为服务端命令，即 <code>ss-server</code></p>
<ul>
<li>2017-03-22 Bug 修复</li>
</ul>
<p>修复增加 <code>-m</code> 参数后 SS_CONFIG 变量为空导致启动失败问题</p>
<ul>
<li>2017-03-27 例行升级</li>
</ul>
<p>升级 shadowsocks-libev 到 3.0.5、kcptun 到 20170322；kcptun 该版本主要做了 CPU 优化</p>
<ul>
<li>2017-04-01 例行升级</li>
</ul>
<p>升级 kcptun 到 20170329</p>
<ul>
<li>2017-04-27 例行升级</li>
</ul>
<p>升级 shadoscoks-libev 到 3.0.6</p>
<ul>
<li>2017-05-31 例行升级</li>
</ul>
<p>升级 kcptun 到 20150525</p>
<ul>
<li>2017-06-28 例行升级</li>
</ul>
<p>升级 shadowsocks 到 3.0.7</p>
<ul>
<li>2017-07-28 例行升级</li>
</ul>
<p>升级 shadowsocks 到 3.0.8</p>
<ul>
<li>2017-08-09 obfs 支持</li>
</ul>
<p>添加对 simple-obfs 支持</p>
<ul>
<li>2017-08-23 kcptun client 支持</li>
</ul>
<p>增加镜像对 kcptun client 支持</p>
<ul>
<li>2017-11-38 例行升级</li>
</ul>
<p>升级 shadowsocks-libev 到 3.1.0，升级 kcptun 到 20170904</p>
<ul>
<li>2017-10-10 升级 kcptun</li>
</ul>
<p>升级 kcptun 到 20170930</p>
<ul>
<li>2017-11-2 update kcptun</li>
</ul>
<p>升级 kcptun 到 20171021</p>
<ul>
<li>2017-11-19 update kcptun</li>
</ul>
<p>升级 kcptun 到 20171113</p>
<ul>
<li>2017-11-22 Fix a security issue in ss-manager. (CVE-2017-15924)</li>
</ul>
<p>Fix a security issue in ss-manager. (CVE-2017-15924)</p>
<ul>
<li>2017-12-11 update base image</li>
</ul>
<p>update base image</p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2017 <span title="0.15529s from unicorn-3188691881-d923v">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/compat-e42a8bf9c380758734e39851db04de7cbeeb2f3860efbd481c96ac12c25a6ecb.js"></script>
    <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-12c0496716f4944b157a59cd9ebaf3c423f2875228732f1111242f80d5ce22af.js"></script>
    
    <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-78af6b531922b2245258bf0655886b1cd4094224dc3f912fa8778a597b14f8df.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

