

<!-- add a comment line -->



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-7mtunHqp/Bw0ND9akjJME8XCh0WPm3HAXOSeX7skL0qGAhpdfzkQvYcujYcwNPTpWKeKMFUGZGtvnEkcczFgwQ==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-9b5314213e37056ed87b0418056c4f2c.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-BvnICKFjIvT69o61dyYllXtaOnGVb7Ifj5c3lk3wj7tkjat2ICuN+XRwyk8tqP3dj7IFhEQzxDdxSHaJ3xj3Mw==" rel="stylesheet" href="https://github.githubassets.com/assets/github-ff986874cf7e28cbcd5d448cdca7245d.css" />
    
  

  <meta name="viewport" content="width=device-width">
  
  <title>react-fundamental/README.md at master · haochuan/react-fundamental</title>
    <meta name="description" content="My react/redux training course reading material. Contribute to haochuan/react-fundamental development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars3.githubusercontent.com/u/2744803?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="haochuan/react-fundamental" /><meta name="twitter:description" content="My react/redux training course reading material. Contribute to haochuan/react-fundamental development by creating an account on GitHub." />
    <meta property="og:image" content="https://avatars3.githubusercontent.com/u/2744803?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="haochuan/react-fundamental" /><meta property="og:url" content="https://github.com/haochuan/react-fundamental" /><meta property="og:description" content="My react/redux training course reading material. Contribute to haochuan/react-fundamental development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDc5NjcxMzIyOjE0Yzg4MjBkMjhiMTkyYjM1ZTgzMzcxZjg3Mjg0YjFhMzc3ZWUzMDMxYjg5YmE0ZmYwOTczMGRjMTQzYzQwMmQ=--dd0cb042a7aaf46a034a4bad9e18bf47cd2c7f75">
  <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="request-id" content="100C:4612:227548E:236DB12:5DF9B6B6" data-pjax-transient>



  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

    <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="100C:4612:227548E:236DB12:5DF9B6B6" /><meta name="octolytics-dimension-region_edge" content="sea" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="3077373713019514018" /><meta name="octolytics-actor-id" content="34950423" /><meta name="octolytics-actor-login" content="KangYuan1233" /><meta name="octolytics-actor-hash" content="8bb1464615610abddffab322ef5c46159eb2651c6fd38be027ee1252214dd060" />

<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="c6be96534449cf26b1f77610cef1bbfc">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="KangYuan1233">

      <meta name="expected-hostname" content="github.com">

      <meta name="js-proxy-site-detection-payload" content="ODgwNTQxMDk3OTc4Mzc4MzYwZDY5ODIyM2QwZjY1NTI1NGJlNjc0M2FjYzY0YWI0NThjMjlhY2M4NDMxNTk3OHx7InJlbW90ZV9hZGRyZXNzIjoiNjcuMTg4Ljk1LjIwIiwicmVxdWVzdF9pZCI6IjEwMEM6NDYxMjoyMjc1NDhFOjIzNkRCMTI6NURGOUI2QjYiLCJ0aW1lc3RhbXAiOjE1NzY2NDYzMzQsImhvc3QiOiJnaXRodWIuY29tIn0=">

    <meta name="enabled-features" content="MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES,GHE_CLOUD_TRIAL">

    <meta name="html-safe-nonce" content="ace940e13e036ca6cf116134ed60d28084529ab5">

  <meta http-equiv="x-pjax-version" content="d5141f7b276c57bd75d3181dedc78b08">
  

      <link href="https://github.com/haochuan/react-fundamental/commits/master.atom" rel="alternate" title="Recent Commits to react-fundamental:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/haochuan/react-fundamental git https://github.com/haochuan/react-fundamental.git">

  <meta name="octolytics-dimension-user_id" content="2744803" /><meta name="octolytics-dimension-user_login" content="haochuan" /><meta name="octolytics-dimension-repository_id" content="85127348" /><meta name="octolytics-dimension-repository_nwo" content="haochuan/react-fundamental" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="85127348" /><meta name="octolytics-dimension-repository_network_root_nwo" content="haochuan/react-fundamental" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



  <meta name="webauthn-auth-enabled" content="true">

  <meta name="webauthn-registration-enabled" content="true">

  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <span class="Progress progress-pjax-loader position-fixed width-full js-pjax-loader-bar">
      <span class="progress-pjax-loader-bar top-0 left-0" style="width: 0%;"></span>
    </span>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="85127348" data-scoped-search-url="/haochuan/react-fundamental/search" data-unscoped-search-url="/search" action="/haochuan/react-fundamental/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=xx4mI28voENIwQ4dev22As9QZ5aUFlaqvgi7VPdfeXbKl5Yn6jNzy7Ol94e/Ty9NcWgwDBw5qggYFGuj8AxDmg=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      

    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>


    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" href="https://github.com/KangYuan1233">
      <img class="avatar" height="20" width="20" alt="@KangYuan1233" src="https://avatars2.githubusercontent.com/u/34950423?s=60&amp;v=4" />
      KangYuan1233
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="A6mhsSh6ENDlrAOquJqx1ATp5BG4PpabnbKW8H4wpoXcHdw/lmET/GLGslNds17jhdShMn0co9491lw5o7jtCw==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
    <a class="Header-link" href="/haochuan">haochuan</a>
    /
    <a class="Header-link" href="/haochuan/react-fundamental">react-fundamental</a>

</div>
    </div>


    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-sw js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:34950423" href="/notifications">
        <span class="mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>


  <div role="none" class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="haochuan/react-fundamental">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/haochuan/react-fundamental/issues/new" data-ga-click="Header, create new issue" data-skip-pjax>
      New issue
    </a>


  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
  <details class="details-overlay details-reset js-feature-preview-indicator-container" data-feature-preview-indicator-src="/users/KangYuan1233/feature_preview/indicator_check.json">

  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img alt="@KangYuan1233" class="avatar" src="https://avatars1.githubusercontent.com/u/34950423?s=40&amp;v=4" height="20" width="20">
      <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/KangYuan1233" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">KangYuan1233</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit "
      role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:2744803,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:34950423,&quot;client_id&quot;:&quot;716506902.1571237026&quot;,&quot;originating_request_id&quot;:&quot;100C:4612:227548E:236DB12:5DF9B6B6&quot;,&quot;originating_url&quot;:&quot;https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend&quot;}}" data-hydro-click-hmac="332d2caf2504e37736359b71149cdf98e16fc94e4b6a46f0d9517797034c38bd">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
              <span class="text-gray ml-2">Set status</span>
          </div>
        </div>
      </div>
    </summary>
    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="w+BsWoGDnWQdvl9/8tZGIgein22YjX5kIGty+czxQxlRXZkiE29DwHZ91Kk2pcVl3Jcsb00mzgPNYbEx7N2Tpw==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value=""
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2019-12-17T21:48:54-08:00">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2019-12-17T22:18:54-08:00">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2019-12-18T01:18:54-08:00">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2019-12-17T23:59:59-08:00">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2019-12-22T23:59:59-08:00">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/KangYuan1233" data-ga-click="Header, go to profile, text:your profile">Your profile</a>

    <a role="menuitem" class="dropdown-item" href="/KangYuan1233?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/KangYuan1233?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/KangYuan1233?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>





    <div role="none" class="dropdown-divider"></div>
      
<div id="feature-enrollment-toggle" class="hide-sm hide-md feature-preview-details position-relative">
  <button
    type="button"
    class="dropdown-item btn-link"
    role="menuitem"
    data-feature-preview-trigger-url="/users/KangYuan1233/feature_previews"
    data-feature-preview-close-details="{&quot;event_type&quot;:&quot;feature_preview.clicks.close_modal&quot;,&quot;payload&quot;:{&quot;client_id&quot;:&quot;716506902.1571237026&quot;,&quot;originating_request_id&quot;:&quot;100C:4612:227548E:236DB12:5DF9B6B6&quot;,&quot;originating_url&quot;:&quot;https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend&quot;,&quot;user_id&quot;:34950423}}"
    data-feature-preview-close-hmac="8e484162fb6f5dfa0ce2cb46da5122b2e56159933a680eb0dece5641eec83d7c"
    data-hydro-click="{&quot;event_type&quot;:&quot;feature_preview.clicks.open_modal&quot;,&quot;payload&quot;:{&quot;link_location&quot;:&quot;user_dropdown&quot;,&quot;client_id&quot;:&quot;716506902.1571237026&quot;,&quot;originating_request_id&quot;:&quot;100C:4612:227548E:236DB12:5DF9B6B6&quot;,&quot;originating_url&quot;:&quot;https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend&quot;,&quot;user_id&quot;:34950423}}"
    data-hydro-click-hmac="cad386f271a71d3f2fd5fe318923f2c3e88f7f1ca5f0dcdafd239c0ad4e4be26"
  >
    Feature preview
  </button>
    <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
</div>

    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="95MGPEztFLzHPHN/muOKw1l3DJIBqqIBZNg6JHjs/owoJ3uy8vYXkEBWwoZ/ymX02EpJscSIl0TEvPDtpWS1Ag==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
      <input type="text" name="required_field_39c2" hidden="hidden" class="form-control" />
<input type="hidden" name="timestamp" value="1576646334072" class="form-control" />
<input type="hidden" name="timestamp_secret" value="205ded030e8cef31caa7658f8e84671b07e9a9b04eccc7e7cf33bbeed6cb595c" class="form-control" />

</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      


  










  <div class=" pagehead repohead readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="F05LJCvT9SprVABZ92cQIlrASEvzFKoUkMN1YQpVEorJA0Q7bqv5rDgFAnNyH21aLBTY3PU3Iw1zXlU2cQfQVQ==" />      <input type="hidden" name="repository_id" value="85127348">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:85127348,&quot;client_id&quot;:&quot;716506902.1571237026&quot;,&quot;originating_request_id&quot;:&quot;100C:4612:227548E:236DB12:5DF9B6B6&quot;,&quot;originating_url&quot;:&quot;https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend&quot;,&quot;user_id&quot;:34950423}}" data-hydro-click-hmac="58930d5cceac0624bfb03358928f13b4c50f42d99c1d5c475ca8c25a611881b3" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/haochuan/react-fundamental/watchers"
          aria-label="2 users are watching this repository">
          2
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <form class="starred js-social-form" action="/haochuan/react-fundamental/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="BAj+eiq51zX60wExrwX18QlVmTbyBBmlZ8rNlYHYhQDJ7XI+tiwvjvJJCsIakE4XO8XglN3Bc8CiiFWdLBM1oA==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar haochuan/react-fundamental" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:85127348,&quot;client_id&quot;:&quot;716506902.1571237026&quot;,&quot;originating_request_id&quot;:&quot;100C:4612:227548E:236DB12:5DF9B6B6&quot;,&quot;originating_url&quot;:&quot;https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend&quot;,&quot;user_id&quot;:34950423}}" data-hydro-click-hmac="d3035af3a12cd6596ad8b7f6c324276c79263854969b1ca38a6ff27acf438b80" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg aria-label="star" height="16" class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" role="img"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>

        Unstar
</button>        <a class="social-count js-social-count" href="/haochuan/react-fundamental/stargazers"
           aria-label="2 users starred this repository">
           2
        </a>
</form>
    <form class="unstarred js-social-form" action="/haochuan/react-fundamental/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="yNEMJ+TnwvE7Qf/7SmAEXAl8uT1FsUwo6e8Rxiw0T/YBX2rSzDkG+1Wo1nnalgueEZ+Vs5sI6hR44MCQQ3NcxA==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star haochuan/react-fundamental" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:85127348,&quot;client_id&quot;:&quot;716506902.1571237026&quot;,&quot;originating_request_id&quot;:&quot;100C:4612:227548E:236DB12:5DF9B6B6&quot;,&quot;originating_url&quot;:&quot;https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend&quot;,&quot;user_id&quot;:34950423}}" data-hydro-click-hmac="31d5600916cd275c16af9d0bceb9df39ee174ee63bcb6cf16a4a7d9c5e27c0e5" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg aria-label="star" height="16" class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" role="img"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>

        Star
</button>        <a class="social-count js-social-count" href="/haochuan/react-fundamental/stargazers"
           aria-label="2 users starred this repository">
          2
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="btn-with-count" action="/haochuan/react-fundamental/fork" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="lg31Bgm2sGv2AlN8ongtUHH4e41BjCaiaO+th5E3xtfBqLz5Ny9fpmPFPwYIh4e0CWHd0P+lsCJp26ZTwQ9AZA==" />
            <button class="btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:85127348,&quot;client_id&quot;:&quot;716506902.1571237026&quot;,&quot;originating_request_id&quot;:&quot;100C:4612:227548E:236DB12:5DF9B6B6&quot;,&quot;originating_url&quot;:&quot;https://github.com/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend&quot;,&quot;user_id&quot;:34950423}}" data-hydro-click-hmac="526ee614306bee8ccd04e60e04fb7162dfa7b8222392a4bfd5ee92da93bd7cb5" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" type="submit" title="Fork your own copy of haochuan/react-fundamental to your account" aria-label="Fork your own copy of haochuan/react-fundamental to your account">              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
</button></form>
    <a href="/haochuan/react-fundamental/network/members" class="social-count"
       aria-label="10 users forked this repository">
      10
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/users/haochuan/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/haochuan">haochuan</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/haochuan/react-fundamental">react-fundamental</a></strong>
  

</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /haochuan/react-fundamental" href="/haochuan/react-fundamental">
      <div class="d-inline"><svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg></div>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /haochuan/react-fundamental/issues" href="/haochuan/react-fundamental/issues">
        <div class="d-inline"><svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 011.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg></div>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" data-skip-pjax="true" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /haochuan/react-fundamental/pulls" href="/haochuan/react-fundamental/pulls">
      <div class="d-inline"><svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0010 15a1.993 1.993 0 001-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 00-1 3.72v6.56A1.993 1.993 0 002 15a1.993 1.993 0 001-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg></div>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement" class="position-relative float-left">
      <a data-hotkey="g w" data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="repo_actions /haochuan/react-fundamental/actions" href="/haochuan/react-fundamental/actions">
        <div class="d-inline"><svg class="octicon octicon-play" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8A7 7 0 110 8a7 7 0 0114 0zm-8.223 3.482l4.599-3.066a.5.5 0 000-.832L5.777 4.518A.5.5 0 005 4.934v6.132a.5.5 0 00.777.416z"/></svg></div>
        Actions
</a>
    </span>

    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /haochuan/react-fundamental/projects" href="/haochuan/react-fundamental/projects">
      <div class="d-inline"><svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg></div>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /haochuan/react-fundamental/wiki" href="/haochuan/react-fundamental/wiki">
      <div class="d-inline"><svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg></div>
      Wiki
</a>
    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /haochuan/react-fundamental/security/advisories" href="/haochuan/react-fundamental/security/advisories">
      <div class="d-inline"><svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg></div>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /haochuan/react-fundamental/pulse" href="/haochuan/react-fundamental/pulse">
      <div class="d-inline"><svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg></div>
      Insights
</a>

</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /haochuan/react-fundamental" href="/haochuan/react-fundamental">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /haochuan/react-fundamental/issues" href="/haochuan/react-fundamental/issues">
          <span itemprop="name">Issues</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="2">
</a>      </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /haochuan/react-fundamental/pulls" href="/haochuan/react-fundamental/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="3">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /haochuan/react-fundamental/projects" href="/haochuan/react-fundamental/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="4">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /haochuan/react-fundamental/wiki" href="/haochuan/react-fundamental/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /haochuan/react-fundamental/security/advisories" href="/haochuan/react-fundamental/security/advisories">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="6">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /haochuan/react-fundamental/pulse" href="/haochuan/react-fundamental/pulse">
        Pulse
</a>
      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="community /haochuan/react-fundamental/community" href="/haochuan/react-fundamental/community">
          Community
</a>      </span>

  </nav>
</div>


  </div>
<div class="container-lg clearfix new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/haochuan/react-fundamental/blob/e33563ce9189b81a1aeae22c9ea91e4bff518c5b/examples/connect-with-express/frontend/README.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:59576457c911b2f3038f867c3b596f35 -->
      

    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
  </summary>

  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="/haochuan/react-fundamental/refs/master/examples/connect-with-express/frontend/README.md?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/haochuan/react-fundamental/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="examples/connect-with-express/frontend/README.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/haochuan/react-fundamental"><span>react-fundamental</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/haochuan/react-fundamental/tree/master/examples"><span>examples</span></a></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/haochuan/react-fundamental/tree/master/examples/connect-with-express"><span>connect-with-express</span></a></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/haochuan/react-fundamental/tree/master/examples/connect-with-express/frontend"><span>frontend</span></a></span><span class="separator">/</span><strong class="final-path">README.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/haochuan/react-fundamental/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="examples/connect-with-express/frontend/README.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>

    



    <include-fragment src="/haochuan/react-fundamental/contributors/master/examples/connect-with-express/frontend/README.md" class="Box Box--condensed commit-loader">
      <div class="Box-body bg-blue-light f6">
        Fetching contributors&hellip;
      </div>

      <div class="Box-body d-flex flex-items-center" >
          <img alt="" class="loader-loading mr-2" src="https://github.githubassets.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" height="16" />
        <span class="text-red h6 loader-error">Cannot retrieve contributors at this time</span>
      </div>
</include-fragment>




    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">
  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">

      2444 lines (1689 sloc)
      <span class="file-info-divider"></span>
    117 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/haochuan/react-fundamental/raw/master/examples/connect-with-express/frontend/README.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/haochuan/react-fundamental/blame/master/examples/connect-with-express/frontend/README.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/haochuan/react-fundamental/commits/master/examples/connect-with-express/frontend/README.md">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="https://desktop.github.com"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/haochuan/react-fundamental/edit/master/examples/connect-with-express/frontend/README.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="zBervhywnI3EwV2LtZlxzAOjiVqYmWRGPygs0MQm8ZRRB15DfvcEy23P8ePe8r2xXRtGN0cSZro7pgbIx4W0bA==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 011.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/haochuan/react-fundamental/delete/master/examples/connect-with-express/frontend/README.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="DIor7VWHYnlimBkqoSdeL6g+Drym9R+Or5Dy5Rxfz5t0Vzw/V5Acr9rWMowg+GQ3grLxgp355ON3QVSXYRCq2A==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and delete the file" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><p>This project was bootstrapped with <a href="https://github.com/facebookincubator/create-react-app">Create React App</a>.</p>
<p>Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide <a href="https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md">here</a>.</p>
<h2><a id="user-content-table-of-contents" class="anchor" aria-hidden="true" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Table of Contents</h2>
<ul>
<li><a href="#updating-to-new-releases">Updating to New Releases</a></li>
<li><a href="#sending-feedback">Sending Feedback</a></li>
<li><a href="#folder-structure">Folder Structure</a></li>
<li><a href="#available-scripts">Available Scripts</a>
<ul>
<li><a href="#npm-start">npm start</a></li>
<li><a href="#npm-test">npm test</a></li>
<li><a href="#npm-run-build">npm run build</a></li>
<li><a href="#npm-run-eject">npm run eject</a></li>
</ul>
</li>
<li><a href="#supported-browsers">Supported Browsers</a></li>
<li><a href="#supported-language-features-and-polyfills">Supported Language Features and Polyfills</a></li>
<li><a href="#syntax-highlighting-in-the-editor">Syntax Highlighting in the Editor</a></li>
<li><a href="#displaying-lint-output-in-the-editor">Displaying Lint Output in the Editor</a></li>
<li><a href="#debugging-in-the-editor">Debugging in the Editor</a></li>
<li><a href="#formatting-code-automatically">Formatting Code Automatically</a></li>
<li><a href="#changing-the-page-title">Changing the Page <code>&lt;title&gt;</code></a></li>
<li><a href="#installing-a-dependency">Installing a Dependency</a></li>
<li><a href="#importing-a-component">Importing a Component</a></li>
<li><a href="#code-splitting">Code Splitting</a></li>
<li><a href="#adding-a-stylesheet">Adding a Stylesheet</a></li>
<li><a href="#post-processing-css">Post-Processing CSS</a></li>
<li><a href="#adding-a-css-preprocessor-sass-less-etc">Adding a CSS Preprocessor (Sass, Less etc.)</a></li>
<li><a href="#adding-images-fonts-and-files">Adding Images, Fonts, and Files</a></li>
<li><a href="#using-the-public-folder">Using the <code>public</code> Folder</a>
<ul>
<li><a href="#changing-the-html">Changing the HTML</a></li>
<li><a href="#adding-assets-outside-of-the-module-system">Adding Assets Outside of the Module System</a></li>
<li><a href="#when-to-use-the-public-folder">When to Use the <code>public</code> Folder</a></li>
</ul>
</li>
<li><a href="#using-global-variables">Using Global Variables</a></li>
<li><a href="#adding-bootstrap">Adding Bootstrap</a>
<ul>
<li><a href="#using-a-custom-theme">Using a Custom Theme</a></li>
</ul>
</li>
<li><a href="#adding-flow">Adding Flow</a></li>
<li><a href="#adding-a-router">Adding a Router</a></li>
<li><a href="#adding-custom-environment-variables">Adding Custom Environment Variables</a>
<ul>
<li><a href="#referencing-environment-variables-in-the-html">Referencing Environment Variables in the HTML</a></li>
<li><a href="#adding-temporary-environment-variables-in-your-shell">Adding Temporary Environment Variables In Your Shell</a></li>
<li><a href="#adding-development-environment-variables-in-env">Adding Development Environment Variables In <code>.env</code></a></li>
</ul>
</li>
<li><a href="#can-i-use-decorators">Can I Use Decorators?</a></li>
<li><a href="#fetching-data-with-ajax-requests">Fetching Data with AJAX Requests</a></li>
<li><a href="#integrating-with-an-api-backend">Integrating with an API Backend</a>
<ul>
<li><a href="#node">Node</a></li>
<li><a href="#ruby-on-rails">Ruby on Rails</a></li>
</ul>
</li>
<li><a href="#proxying-api-requests-in-development">Proxying API Requests in Development</a>
<ul>
<li><a href="#invalid-host-header-errors-after-configuring-proxy">"Invalid Host Header" Errors After Configuring Proxy</a></li>
<li><a href="#configuring-the-proxy-manually">Configuring the Proxy Manually</a></li>
<li><a href="#configuring-a-websocket-proxy">Configuring a WebSocket Proxy</a></li>
</ul>
</li>
<li><a href="#using-https-in-development">Using HTTPS in Development</a></li>
<li><a href="#generating-dynamic-meta-tags-on-the-server">Generating Dynamic <code>&lt;meta&gt;</code> Tags on the Server</a></li>
<li><a href="#pre-rendering-into-static-html-files">Pre-Rendering into Static HTML Files</a></li>
<li><a href="#injecting-data-from-the-server-into-the-page">Injecting Data from the Server into the Page</a></li>
<li><a href="#running-tests">Running Tests</a>
<ul>
<li><a href="#filename-conventions">Filename Conventions</a></li>
<li><a href="#command-line-interface">Command Line Interface</a></li>
<li><a href="#version-control-integration">Version Control Integration</a></li>
<li><a href="#writing-tests">Writing Tests</a></li>
<li><a href="#testing-components">Testing Components</a></li>
<li><a href="#using-third-party-assertion-libraries">Using Third Party Assertion Libraries</a></li>
<li><a href="#initializing-test-environment">Initializing Test Environment</a></li>
<li><a href="#focusing-and-excluding-tests">Focusing and Excluding Tests</a></li>
<li><a href="#coverage-reporting">Coverage Reporting</a></li>
<li><a href="#continuous-integration">Continuous Integration</a></li>
<li><a href="#disabling-jsdom">Disabling jsdom</a></li>
<li><a href="#snapshot-testing">Snapshot Testing</a></li>
<li><a href="#editor-integration">Editor Integration</a></li>
</ul>
</li>
<li><a href="#debugging-tests">Debugging Tests</a>
<ul>
<li><a href="#debugging-tests-in-chrome">Debugging Tests in Chrome</a></li>
<li><a href="#debugging-tests-in-visual-studio-code">Debugging Tests in Visual Studio Code</a></li>
</ul>
</li>
<li><a href="#developing-components-in-isolation">Developing Components in Isolation</a>
<ul>
<li><a href="#getting-started-with-storybook">Getting Started with Storybook</a></li>
<li><a href="#getting-started-with-styleguidist">Getting Started with Styleguidist</a></li>
</ul>
</li>
<li><a href="#publishing-components-to-npm">Publishing Components to npm</a></li>
<li><a href="#making-a-progressive-web-app">Making a Progressive Web App</a>
<ul>
<li><a href="#opting-out-of-caching">Opting Out of Caching</a></li>
<li><a href="#offline-first-considerations">Offline-First Considerations</a></li>
<li><a href="#progressive-web-app-metadata">Progressive Web App Metadata</a></li>
</ul>
</li>
<li><a href="#analyzing-the-bundle-size">Analyzing the Bundle Size</a></li>
<li><a href="#deployment">Deployment</a>
<ul>
<li><a href="#static-server">Static Server</a></li>
<li><a href="#other-solutions">Other Solutions</a></li>
<li><a href="#serving-apps-with-client-side-routing">Serving Apps with Client-Side Routing</a></li>
<li><a href="#building-for-relative-paths">Building for Relative Paths</a></li>
<li><a href="#azure">Azure</a></li>
<li><a href="#firebase">Firebase</a></li>
<li><a href="#github-pages">GitHub Pages</a></li>
<li><a href="#heroku">Heroku</a></li>
<li><a href="#netlify">Netlify</a></li>
<li><a href="#now">Now</a></li>
<li><a href="#s3-and-cloudfront">S3 and CloudFront</a></li>
<li><a href="#surge">Surge</a></li>
</ul>
</li>
<li><a href="#advanced-configuration">Advanced Configuration</a></li>
<li><a href="#troubleshooting">Troubleshooting</a>
<ul>
<li><a href="#npm-start-doesnt-detect-changes"><code>npm start</code> doesn’t detect changes</a></li>
<li><a href="#npm-test-hangs-on-macos-sierra"><code>npm test</code> hangs on macOS Sierra</a></li>
<li><a href="#npm-run-build-exits-too-early"><code>npm run build</code> exits too early</a></li>
<li><a href="#npm-run-build-fails-on-heroku"><code>npm run build</code> fails on Heroku</a></li>
<li><a href="#npm-run-build-fails-to-minify"><code>npm run build</code> fails to minify</a></li>
<li><a href="#momentjs-locales-are-missing">Moment.js locales are missing</a></li>
</ul>
</li>
<li><a href="#alternatives-to-ejecting">Alternatives to Ejecting</a></li>
<li><a href="#something-missing">Something Missing?</a></li>
</ul>
<h2><a id="user-content-updating-to-new-releases" class="anchor" aria-hidden="true" href="#updating-to-new-releases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Updating to New Releases</h2>
<p>Create React App is divided into two packages:</p>
<ul>
<li><code>create-react-app</code> is a global command-line utility that you use to create new projects.</li>
<li><code>react-scripts</code> is a development dependency in the generated projects (including this one).</li>
</ul>
<p>You almost never need to update <code>create-react-app</code> itself: it delegates all the setup to <code>react-scripts</code>.</p>
<p>When you run <code>create-react-app</code>, it always creates the project with the latest version of <code>react-scripts</code> so you’ll get all the new features and improvements in newly created apps automatically.</p>
<p>To update an existing project to a new version of <code>react-scripts</code>, <a href="https://github.com/facebookincubator/create-react-app/blob/master/CHANGELOG.md">open the changelog</a>, find the version you’re currently on (check <code>package.json</code> in this folder if you’re not sure), and apply the migration instructions for the newer versions.</p>
<p>In most cases bumping the <code>react-scripts</code> version in <code>package.json</code> and running <code>npm install</code> in this folder should be enough, but it’s good to consult the <a href="https://github.com/facebookincubator/create-react-app/blob/master/CHANGELOG.md">changelog</a> for potential breaking changes.</p>
<p>We commit to keeping the breaking changes minimal so you can upgrade <code>react-scripts</code> painlessly.</p>
<h2><a id="user-content-sending-feedback" class="anchor" aria-hidden="true" href="#sending-feedback"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Sending Feedback</h2>
<p>We are always open to <a href="https://github.com/facebookincubator/create-react-app/issues">your feedback</a>.</p>
<h2><a id="user-content-folder-structure" class="anchor" aria-hidden="true" href="#folder-structure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Folder Structure</h2>
<p>After creation, your project should look like this:</p>
<pre><code>my-app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
  src/
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
</code></pre>
<p>For the project to build, <strong>these files must exist with exact filenames</strong>:</p>
<ul>
<li><code>public/index.html</code> is the page template;</li>
<li><code>src/index.js</code> is the JavaScript entry point.</li>
</ul>
<p>You can delete or rename the other files.</p>
<p>You may create subdirectories inside <code>src</code>. For faster rebuilds, only files inside <code>src</code> are processed by Webpack.<br>
You need to <strong>put any JS and CSS files inside <code>src</code></strong>, otherwise Webpack won’t see them.</p>
<p>Only files inside <code>public</code> can be used from <code>public/index.html</code>.<br>
Read instructions below for using assets from JavaScript and HTML.</p>
<p>You can, however, create more top-level directories.<br>
They will not be included in the production build so you can use them for things like documentation.</p>
<h2><a id="user-content-available-scripts" class="anchor" aria-hidden="true" href="#available-scripts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Available Scripts</h2>
<p>In the project directory, you can run:</p>
<h3><a id="user-content-npm-start" class="anchor" aria-hidden="true" href="#npm-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm start</code></h3>
<p>Runs the app in the development mode.<br>
Open <a href="http://localhost:3000" rel="nofollow">http://localhost:3000</a> to view it in the browser.</p>
<p>The page will reload if you make edits.<br>
You will also see any lint errors in the console.</p>
<h3><a id="user-content-npm-test" class="anchor" aria-hidden="true" href="#npm-test"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm test</code></h3>
<p>Launches the test runner in the interactive watch mode.<br>
See the section about <a href="#running-tests">running tests</a> for more information.</p>
<h3><a id="user-content-npm-run-build" class="anchor" aria-hidden="true" href="#npm-run-build"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm run build</code></h3>
<p>Builds the app for production to the <code>build</code> folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.</p>
<p>The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!</p>
<p>See the section about <a href="#deployment">deployment</a> for more information.</p>
<h3><a id="user-content-npm-run-eject" class="anchor" aria-hidden="true" href="#npm-run-eject"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm run eject</code></h3>
<p><strong>Note: this is a one-way operation. Once you <code>eject</code>, you can’t go back!</strong></p>
<p>If you aren’t satisfied with the build tool and configuration choices, you can <code>eject</code> at any time. This command will remove the single build dependency from your project.</p>
<p>Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except <code>eject</code> will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.</p>
<p>You don’t have to ever use <code>eject</code>. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.</p>
<h2><a id="user-content-supported-browsers" class="anchor" aria-hidden="true" href="#supported-browsers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Supported Browsers</h2>
<p>By default, the generated project uses the latest version of React.</p>
<p>You can refer <a href="https://reactjs.org/docs/react-dom.html#browser-support" rel="nofollow">to the React documentation</a> for more information about supported browsers.</p>
<h2><a id="user-content-supported-language-features-and-polyfills" class="anchor" aria-hidden="true" href="#supported-language-features-and-polyfills"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Supported Language Features and Polyfills</h2>
<p>This project supports a superset of the latest JavaScript standard.<br>
In addition to <a href="https://github.com/lukehoban/es6features">ES6</a> syntax features, it also supports:</p>
<ul>
<li><a href="https://github.com/rwaldron/exponentiation-operator">Exponentiation Operator</a> (ES2016).</li>
<li><a href="https://github.com/tc39/ecmascript-asyncawait">Async/await</a> (ES2017).</li>
<li><a href="https://github.com/sebmarkbage/ecmascript-rest-spread">Object Rest/Spread Properties</a> (stage 3 proposal).</li>
<li><a href="https://github.com/tc39/proposal-dynamic-import">Dynamic import()</a> (stage 3 proposal)</li>
<li><a href="https://github.com/tc39/proposal-class-public-fields">Class Fields and Static Properties</a> (part of stage 3 proposal).</li>
<li><a href="https://facebook.github.io/react/docs/introducing-jsx.html" rel="nofollow">JSX</a> and <a href="https://flowtype.org/" rel="nofollow">Flow</a> syntax.</li>
</ul>
<p>Learn more about <a href="https://babeljs.io/docs/plugins/#presets-stage-x-experimental-presets-" rel="nofollow">different proposal stages</a>.</p>
<p>While we recommend using experimental proposals with some caution, Facebook heavily uses these features in the product code, so we intend to provide <a href="https://medium.com/@cpojer/effective-javascript-codemods-5a6686bb46fb" rel="nofollow">codemods</a> if any of these proposals change in the future.</p>
<p>Note that <strong>the project only includes a few ES6 <a href="https://en.wikipedia.org/wiki/Polyfill" rel="nofollow">polyfills</a></strong>:</p>
<ul>
<li><a href="https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Object/assign" rel="nofollow"><code>Object.assign()</code></a> via <a href="https://github.com/sindresorhus/object-assign"><code>object-assign</code></a>.</li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise" rel="nofollow"><code>Promise</code></a> via <a href="https://github.com/then/promise"><code>promise</code></a>.</li>
<li><a href="https://developer.mozilla.org/en/docs/Web/API/Fetch_API" rel="nofollow"><code>fetch()</code></a> via <a href="https://github.com/github/fetch"><code>whatwg-fetch</code></a>.</li>
</ul>
<p>If you use any other ES6+ features that need <strong>runtime support</strong> (such as <code>Array.from()</code> or <code>Symbol</code>), make sure you are including the appropriate polyfills manually, or that the browsers you are targeting already support them.</p>
<p>Also note that using some newer syntax features like <code>for...of</code> or <code>[...nonArrayValue]</code> causes Babel to emit code that depends on ES6 runtime features and might not work without a polyfill. When in doubt, use <a href="https://babeljs.io/repl/" rel="nofollow">Babel REPL</a> to see what any specific syntax compiles down to.</p>
<h2><a id="user-content-syntax-highlighting-in-the-editor" class="anchor" aria-hidden="true" href="#syntax-highlighting-in-the-editor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Syntax Highlighting in the Editor</h2>
<p>To configure the syntax highlighting in your favorite text editor, head to the <a href="https://babeljs.io/docs/editors" rel="nofollow">relevant Babel documentation page</a> and follow the instructions. Some of the most popular editors are covered.</p>
<h2><a id="user-content-displaying-lint-output-in-the-editor" class="anchor" aria-hidden="true" href="#displaying-lint-output-in-the-editor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Displaying Lint Output in the Editor</h2>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.2.0</code> and higher.<br>
It also only works with npm 3 or higher.</p>
</blockquote>
<p>Some editors, including Sublime Text, Atom, and Visual Studio Code, provide plugins for ESLint.</p>
<p>They are not required for linting. You should see the linter output right in your terminal as well as the browser console. However, if you prefer the lint results to appear right in your editor, there are some extra steps you can do.</p>
<p>You would need to install an ESLint plugin for your editor first. Then, add a file called <code>.eslintrc</code> to the project root:</p>
<div class="highlight highlight-source-js"><pre>{
  <span class="pl-s"><span class="pl-pds">"</span>extends<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>react-app<span class="pl-pds">"</span></span>
}</pre></div>
<p>Now your editor should report the linting warnings.</p>
<p>Note that even if you edit your <code>.eslintrc</code> file further, these changes will <strong>only affect the editor integration</strong>. They won’t affect the terminal and in-browser lint output. This is because Create React App intentionally provides a minimal set of rules that find common mistakes.</p>
<p>If you want to enforce a coding style for your project, consider using <a href="https://github.com/jlongster/prettier">Prettier</a> instead of ESLint style rules.</p>
<h2><a id="user-content-debugging-in-the-editor" class="anchor" aria-hidden="true" href="#debugging-in-the-editor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Debugging in the Editor</h2>
<p><strong>This feature is currently only supported by <a href="https://code.visualstudio.com" rel="nofollow">Visual Studio Code</a> and <a href="https://www.jetbrains.com/webstorm/" rel="nofollow">WebStorm</a>.</strong></p>
<p>Visual Studio Code and WebStorm support debugging out of the box with Create React App. This enables you as a developer to write and debug your React code without leaving the editor, and most importantly it enables you to have a continuous development workflow, where context switching is minimal, as you don’t have to switch between tools.</p>
<h3><a id="user-content-visual-studio-code" class="anchor" aria-hidden="true" href="#visual-studio-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Visual Studio Code</h3>
<p>You would need to have the latest version of <a href="https://code.visualstudio.com" rel="nofollow">VS Code</a> and VS Code <a href="https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome" rel="nofollow">Chrome Debugger Extension</a> installed.</p>
<p>Then add the block below to your <code>launch.json</code> file and put it inside the <code>.vscode</code> folder in your app’s root directory.</p>
<div class="highlight highlight-source-json"><pre>{
  <span class="pl-s"><span class="pl-pds">"</span>version<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>0.2.0<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>configurations<span class="pl-pds">"</span></span>: [{
    <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Chrome<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>chrome<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>request<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>launch<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>http://localhost:3000<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>webRoot<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>${workspaceRoot}/src<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>sourceMapPathOverrides<span class="pl-pds">"</span></span>: {
      <span class="pl-s"><span class="pl-pds">"</span>webpack:///src/*<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>${webRoot}/*<span class="pl-pds">"</span></span>
    }
  }]
}</pre></div>
<blockquote>
<p>Note: the URL may be different if you've made adjustments via the <a href="#advanced-configuration">HOST or PORT environment variables</a>.</p>
</blockquote>
<p>Start your app by running <code>npm start</code>, and start debugging in VS Code by pressing <code>F5</code> or by clicking the green debug icon. You can now write code, set breakpoints, make changes to the code, and debug your newly modified code—all from your editor.</p>
<p>Having problems with VS Code Debugging? Please see their <a href="https://github.com/Microsoft/vscode-chrome-debug/blob/master/README.md#troubleshooting">troubleshooting guide</a>.</p>
<h3><a id="user-content-webstorm" class="anchor" aria-hidden="true" href="#webstorm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>WebStorm</h3>
<p>You would need to have <a href="https://www.jetbrains.com/webstorm/" rel="nofollow">WebStorm</a> and <a href="https://chrome.google.com/webstore/detail/jetbrains-ide-support/hmhgeddbohgjknpmjagkdomcpobmllji" rel="nofollow">JetBrains IDE Support</a> Chrome extension installed.</p>
<p>In the WebStorm menu <code>Run</code> select <code>Edit Configurations...</code>. Then click <code>+</code> and select <code>JavaScript Debug</code>. Paste <code>http://localhost:3000</code> into the URL field and save the configuration.</p>
<blockquote>
<p>Note: the URL may be different if you've made adjustments via the <a href="#advanced-configuration">HOST or PORT environment variables</a>.</p>
</blockquote>
<p>Start your app by running <code>npm start</code>, then press <code>^D</code> on macOS or <code>F9</code> on Windows and Linux or click the green debug icon to start debugging in WebStorm.</p>
<p>The same way you can debug your application in IntelliJ IDEA Ultimate, PhpStorm, PyCharm Pro, and RubyMine.</p>
<h2><a id="user-content-formatting-code-automatically" class="anchor" aria-hidden="true" href="#formatting-code-automatically"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Formatting Code Automatically</h2>
<p>Prettier is an opinionated code formatter with support for JavaScript, CSS and JSON. With Prettier you can format the code you write automatically to ensure a code style within your project. See the <a href="https://github.com/prettier/prettier">Prettier's GitHub page</a> for more information, and look at this <a href="https://prettier.github.io/prettier/" rel="nofollow">page to see it in action</a>.</p>
<p>To format our code whenever we make a commit in git, we need to install the following dependencies:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save husky lint-staged prettier</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add husky lint-staged prettier</pre></div>
<ul>
<li><code>husky</code> makes it easy to use githooks as if they are npm scripts.</li>
<li><code>lint-staged</code> allows us to run scripts on staged files in git. See this <a href="https://medium.com/@okonetchnikov/make-linting-great-again-f3890e1ad6b8" rel="nofollow">blog post about lint-staged to learn more about it</a>.</li>
<li><code>prettier</code> is the JavaScript formatter we will run before commits.</li>
</ul>
<p>Now we can make sure every file is formatted correctly by adding a few lines to the <code>package.json</code> in the project root.</p>
<p>Add the following line to <code>scripts</code> section:</p>
<div class="highlight highlight-source-diff"><pre>  "scripts": {
<span class="pl-mi1"><span class="pl-mi1">+</span>   "precommit": "lint-staged",</span>
    "start": "react-scripts start",
    "build": "react-scripts build",</pre></div>
<p>Next we add a 'lint-staged' field to the <code>package.json</code>, for example:</p>
<div class="highlight highlight-source-diff"><pre>  "dependencies": {
    // ...
  },
<span class="pl-mi1"><span class="pl-mi1">+</span> "lint-staged": {</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>   "src/**/*.{js,jsx,json,css}": [</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>     "prettier --single-quote --write",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>     "git add"</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>   ]</span>
<span class="pl-mi1"><span class="pl-mi1">+</span> },</span>
  "scripts": {</pre></div>
<p>Now, whenever you make a commit, Prettier will format the changed files automatically. You can also run <code>./node_modules/.bin/prettier --single-quote --write "src/**/*.{js,jsx,json,css}"</code> to format your entire project for the first time.</p>
<p>Next you might want to integrate Prettier in your favorite editor. Read the section on <a href="https://prettier.io/docs/en/editors.html" rel="nofollow">Editor Integration</a> on the Prettier GitHub page.</p>
<h2><a id="user-content-changing-the-page-title" class="anchor" aria-hidden="true" href="#changing-the-page-title"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Changing the Page <code>&lt;title&gt;</code></h2>
<p>You can find the source HTML file in the <code>public</code> folder of the generated project. You may edit the <code>&lt;title&gt;</code> tag in it to change the title from “React App” to anything else.</p>
<p>Note that normally you wouldn’t edit files in the <code>public</code> folder very often. For example, <a href="#adding-a-stylesheet">adding a stylesheet</a> is done without touching the HTML.</p>
<p>If you need to dynamically update the page title based on the content, you can use the browser <a href="https://developer.mozilla.org/en-US/docs/Web/API/Document/title" rel="nofollow"><code>document.title</code></a> API. For more complex scenarios when you want to change the title from React components, you can use <a href="https://github.com/nfl/react-helmet">React Helmet</a>, a third party library.</p>
<p>If you use a custom server for your app in production and want to modify the title before it gets sent to the browser, you can follow advice in <a href="#generating-dynamic-meta-tags-on-the-server">this section</a>. Alternatively, you can pre-build each page as a static HTML file which then loads the JavaScript bundle, which is covered <a href="#pre-rendering-into-static-html-files">here</a>.</p>
<h2><a id="user-content-installing-a-dependency" class="anchor" aria-hidden="true" href="#installing-a-dependency"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Installing a Dependency</h2>
<p>The generated project includes React and ReactDOM as dependencies. It also includes a set of scripts used by Create React App as a development dependency. You may install other dependencies (for example, React Router) with <code>npm</code>:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save react-router</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add react-router</pre></div>
<p>This works for any library, not just <code>react-router</code>.</p>
<h2><a id="user-content-importing-a-component" class="anchor" aria-hidden="true" href="#importing-a-component"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Importing a Component</h2>
<p>This project setup supports ES6 modules thanks to Babel.<br>
While you can still use <code>require()</code> and <code>module.exports</code>, we encourage you to use <a href="http://exploringjs.com/es6/ch_modules.html" rel="nofollow"><code>import</code> and <code>export</code></a> instead.</p>
<p>For example:</p>
<h3><a id="user-content-buttonjs" class="anchor" aria-hidden="true" href="#buttonjs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>Button.js</code></h3>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span>, { <span class="pl-smi">Component</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;

<span class="pl-k">class</span> <span class="pl-en">Button</span> <span class="pl-k">extends</span> <span class="pl-e">Component</span> {
  <span class="pl-en">render</span>() {
    <span class="pl-c"><span class="pl-c">//</span> ...</span>
  }
}

<span class="pl-k">export</span> <span class="pl-c1">default</span> <span class="pl-smi">Button</span>; <span class="pl-c"><span class="pl-c">//</span> Don’t forget to use export default!</span></pre></div>
<h3><a id="user-content-dangerbuttonjs" class="anchor" aria-hidden="true" href="#dangerbuttonjs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>DangerButton.js</code></h3>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span>, { <span class="pl-smi">Component</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-smi">Button</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>./Button<span class="pl-pds">'</span></span>; <span class="pl-c"><span class="pl-c">//</span> Import a component from another file</span>

<span class="pl-k">class</span> <span class="pl-en">DangerButton</span> <span class="pl-k">extends</span> <span class="pl-e">Component</span> {
  <span class="pl-en">render</span>() {
    <span class="pl-k">return</span> <span class="pl-k">&lt;</span>Button color<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>red<span class="pl-pds">"</span></span> <span class="pl-k">/</span><span class="pl-k">&gt;</span>;
  }
}

<span class="pl-k">export</span> <span class="pl-c1">default</span> <span class="pl-smi">DangerButton</span>;</pre></div>
<p>Be aware of the <a href="http://stackoverflow.com/questions/36795819/react-native-es-6-when-should-i-use-curly-braces-for-import/36796281#36796281" rel="nofollow">difference between default and named exports</a>. It is a common source of mistakes.</p>
<p>We suggest that you stick to using default imports and exports when a module only exports a single thing (for example, a component). That’s what you get when you use <code>export default Button</code> and <code>import Button from './Button'</code>.</p>
<p>Named exports are useful for utility modules that export several functions. A module may have at most one default export and as many named exports as you like.</p>
<p>Learn more about ES6 modules:</p>
<ul>
<li><a href="http://stackoverflow.com/questions/36795819/react-native-es-6-when-should-i-use-curly-braces-for-import/36796281#36796281" rel="nofollow">When to use the curly braces?</a></li>
<li><a href="http://exploringjs.com/es6/ch_modules.html" rel="nofollow">Exploring ES6: Modules</a></li>
<li><a href="https://leanpub.com/understandinges6/read#leanpub-auto-encapsulating-code-with-modules" rel="nofollow">Understanding ES6: Modules</a></li>
</ul>
<h2><a id="user-content-code-splitting" class="anchor" aria-hidden="true" href="#code-splitting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Code Splitting</h2>
<p>Instead of downloading the entire app before users can use it, code splitting allows you to split your code into small chunks which you can then load on demand.</p>
<p>This project setup supports code splitting via <a href="http://2ality.com/2017/01/import-operator.html#loading-code-on-demand" rel="nofollow">dynamic <code>import()</code></a>. Its <a href="https://github.com/tc39/proposal-dynamic-import">proposal</a> is in stage 3. The <code>import()</code> function-like form takes the module name as an argument and returns a <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise" rel="nofollow"><code>Promise</code></a> which always resolves to the namespace object of the module.</p>
<p>Here is an example:</p>
<h3><a id="user-content-moduleajs" class="anchor" aria-hidden="true" href="#moduleajs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>moduleA.js</code></h3>
<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-c1">moduleA</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Hello<span class="pl-pds">'</span></span>;

<span class="pl-k">export</span> { <span class="pl-smi">moduleA</span> };</pre></div>
<h3><a id="user-content-appjs" class="anchor" aria-hidden="true" href="#appjs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>App.js</code></h3>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span>, { <span class="pl-smi">Component</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;

<span class="pl-k">class</span> <span class="pl-en">App</span> <span class="pl-k">extends</span> <span class="pl-e">Component</span> {
  <span class="pl-en">handleClick</span> <span class="pl-k">=</span> () <span class="pl-k">=&gt;</span> {
    <span class="pl-k">import</span>(<span class="pl-s"><span class="pl-pds">'</span>./moduleA<span class="pl-pds">'</span></span>)
      .<span class="pl-c1">then</span>(({ moduleA }) <span class="pl-k">=&gt;</span> {
        <span class="pl-c"><span class="pl-c">//</span> Use moduleA</span>
      })
      .<span class="pl-c1">catch</span>(<span class="pl-smi">err</span> <span class="pl-k">=&gt;</span> {
        <span class="pl-c"><span class="pl-c">//</span> Handle failure</span>
      });
  };

  <span class="pl-en">render</span>() {
    <span class="pl-k">return</span> (
      <span class="pl-k">&lt;</span>div<span class="pl-k">&gt;</span>
        <span class="pl-k">&lt;</span>button onClick<span class="pl-k">=</span>{<span class="pl-c1">this</span>.<span class="pl-smi">handleClick</span>}<span class="pl-k">&gt;</span>Load<span class="pl-k">&lt;</span><span class="pl-k">/</span>button<span class="pl-k">&gt;</span>
      <span class="pl-k">&lt;</span><span class="pl-k">/</span>div<span class="pl-k">&gt;</span>
    );
  }
}

<span class="pl-k">export</span> <span class="pl-c1">default</span> <span class="pl-smi">App</span>;</pre></div>
<p>This will make <code>moduleA.js</code> and all its unique dependencies as a separate chunk that only loads after the user clicks the 'Load' button.</p>
<p>You can also use it with <code>async</code> / <code>await</code> syntax if you prefer it.</p>
<h3><a id="user-content-with-react-router" class="anchor" aria-hidden="true" href="#with-react-router"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>With React Router</h3>
<p>If you are using React Router check out <a href="http://serverless-stack.com/chapters/code-splitting-in-create-react-app.html" rel="nofollow">this tutorial</a> on how to use code splitting with it. You can find the companion GitHub repository <a href="https://github.com/AnomalyInnovations/serverless-stack-demo-client/tree/code-splitting-in-create-react-app">here</a>.</p>
<p>Also check out the <a href="https://reactjs.org/docs/code-splitting.html" rel="nofollow">Code Splitting</a> section in React documentation.</p>
<h2><a id="user-content-adding-a-stylesheet" class="anchor" aria-hidden="true" href="#adding-a-stylesheet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding a Stylesheet</h2>
<p>This project setup uses <a href="https://webpack.js.org/" rel="nofollow">Webpack</a> for handling all assets. Webpack offers a custom way of “extending” the concept of <code>import</code> beyond JavaScript. To express that a JavaScript file depends on a CSS file, you need to <strong>import the CSS from the JavaScript file</strong>:</p>
<h3><a id="user-content-buttoncss" class="anchor" aria-hidden="true" href="#buttoncss"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>Button.css</code></h3>
<div class="highlight highlight-source-css"><pre><span class="pl-e">.Button</span> {
  <span class="pl-c1"><span class="pl-c1">padding</span></span>: <span class="pl-c1">20<span class="pl-k">px</span></span>;
}</pre></div>
<h3><a id="user-content-buttonjs-1" class="anchor" aria-hidden="true" href="#buttonjs-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>Button.js</code></h3>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span>, { <span class="pl-smi">Component</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-s"><span class="pl-pds">'</span>./Button.css<span class="pl-pds">'</span></span>; <span class="pl-c"><span class="pl-c">//</span> Tell Webpack that Button.js uses these styles</span>

<span class="pl-k">class</span> <span class="pl-en">Button</span> <span class="pl-k">extends</span> <span class="pl-e">Component</span> {
  <span class="pl-en">render</span>() {
    <span class="pl-c"><span class="pl-c">//</span> You can use them as regular CSS styles</span>
    <span class="pl-k">return</span> <span class="pl-k">&lt;</span>div className<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Button<span class="pl-pds">"</span></span> <span class="pl-k">/</span><span class="pl-k">&gt;</span>;
  }
}</pre></div>
<p><strong>This is not required for React</strong> but many people find this feature convenient. You can read about the benefits of this approach <a href="https://medium.com/seek-ui-engineering/block-element-modifying-your-javascript-components-d7f99fcab52b" rel="nofollow">here</a>. However you should be aware that this makes your code less portable to other build tools and environments than Webpack.</p>
<p>In development, expressing dependencies this way allows your styles to be reloaded on the fly as you edit them. In production, all CSS files will be concatenated into a single minified <code>.css</code> file in the build output.</p>
<p>If you are concerned about using Webpack-specific semantics, you can put all your CSS right into <code>src/index.css</code>. It would still be imported from <code>src/index.js</code>, but you could always remove that import if you later migrate to a different build tool.</p>
<h2><a id="user-content-post-processing-css" class="anchor" aria-hidden="true" href="#post-processing-css"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Post-Processing CSS</h2>
<p>This project setup minifies your CSS and adds vendor prefixes to it automatically through <a href="https://github.com/postcss/autoprefixer">Autoprefixer</a> so you don’t need to worry about it.</p>
<p>For example, this:</p>
<div class="highlight highlight-source-css"><pre><span class="pl-e">.App</span> {
  <span class="pl-c1"><span class="pl-c1">display</span></span>: <span class="pl-c1">flex</span>;
  <span class="pl-c1"><span class="pl-c1">flex-direction</span></span>: <span class="pl-c1">row</span>;
  <span class="pl-c1"><span class="pl-c1">align-items</span></span>: <span class="pl-c1">center</span>;
}</pre></div>
<p>becomes this:</p>
<div class="highlight highlight-source-css"><pre><span class="pl-e">.App</span> {
  <span class="pl-c1"><span class="pl-c1">display</span></span>: <span class="pl-c1">-webkit-box</span>;
  <span class="pl-c1"><span class="pl-c1">display</span></span>: <span class="pl-c1">-ms-flexbox</span>;
  <span class="pl-c1"><span class="pl-c1">display</span></span>: <span class="pl-c1">flex</span>;
  <span class="pl-c1"><span class="pl-c1">-webkit-box-orient</span></span>: <span class="pl-c1">horizontal</span>;
  <span class="pl-c1"><span class="pl-c1">-webkit-box-direction</span></span>: <span class="pl-c1">normal</span>;
      <span class="pl-c1"><span class="pl-c1">-ms-flex-direction</span></span>: <span class="pl-c1">row</span>;
          <span class="pl-c1"><span class="pl-c1">flex-direction</span></span>: <span class="pl-c1">row</span>;
  <span class="pl-c1"><span class="pl-c1">-webkit-box-align</span></span>: <span class="pl-c1">center</span>;
      <span class="pl-c1"><span class="pl-c1">-ms-flex-align</span></span>: <span class="pl-c1">center</span>;
          <span class="pl-c1"><span class="pl-c1">align-items</span></span>: <span class="pl-c1">center</span>;
}</pre></div>
<p>If you need to disable autoprefixing for some reason, <a href="https://github.com/postcss/autoprefixer#disabling">follow this section</a>.</p>
<h2><a id="user-content-adding-a-css-preprocessor-sass-less-etc" class="anchor" aria-hidden="true" href="#adding-a-css-preprocessor-sass-less-etc"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding a CSS Preprocessor (Sass, Less etc.)</h2>
<p>Generally, we recommend that you don’t reuse the same CSS classes across different components. For example, instead of using a <code>.Button</code> CSS class in <code>&lt;AcceptButton&gt;</code> and <code>&lt;RejectButton&gt;</code> components, we recommend creating a <code>&lt;Button&gt;</code> component with its own <code>.Button</code> styles, that both <code>&lt;AcceptButton&gt;</code> and <code>&lt;RejectButton&gt;</code> can render (but <a href="https://facebook.github.io/react/docs/composition-vs-inheritance.html" rel="nofollow">not inherit</a>).</p>
<p>Following this rule often makes CSS preprocessors less useful, as features like mixins and nesting are replaced by component composition. You can, however, integrate a CSS preprocessor if you find it valuable. In this walkthrough, we will be using Sass, but you can also use Less, or another alternative.</p>
<p>First, let’s install the command-line interface for Sass:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save node-sass-chokidar</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add node-sass-chokidar</pre></div>
<p>Then in <code>package.json</code>, add the following lines to <code>scripts</code>:</p>
<div class="highlight highlight-source-diff"><pre>   "scripts": {
<span class="pl-mi1"><span class="pl-mi1">+</span>    "build-css": "node-sass-chokidar src/ -o src/",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>    "watch-css": "npm run build-css &amp;&amp; node-sass-chokidar src/ -o src/ --watch --recursive",</span>
     "start": "react-scripts start",
     "build": "react-scripts build",
     "test": "react-scripts test --env=jsdom",</pre></div>
<blockquote>
<p>Note: To use a different preprocessor, replace <code>build-css</code> and <code>watch-css</code> commands according to your preprocessor’s documentation.</p>
</blockquote>
<p>Now you can rename <code>src/App.css</code> to <code>src/App.scss</code> and run <code>npm run watch-css</code>. The watcher will find every Sass file in <code>src</code> subdirectories, and create a corresponding CSS file next to it, in our case overwriting <code>src/App.css</code>. Since <code>src/App.js</code> still imports <code>src/App.css</code>, the styles become a part of your application. You can now edit <code>src/App.scss</code>, and <code>src/App.css</code> will be regenerated.</p>
<p>To share variables between Sass files, you can use Sass imports. For example, <code>src/App.scss</code> and other component style files could include <code>@import "./shared.scss";</code> with variable definitions.</p>
<p>To enable importing files without using relative paths, you can add the  <code>--include-path</code> option to the command in <code>package.json</code>.</p>
<pre><code>"build-css": "node-sass-chokidar --include-path ./src --include-path ./node_modules src/ -o src/",
"watch-css": "npm run build-css &amp;&amp; node-sass-chokidar --include-path ./src --include-path ./node_modules src/ -o src/ --watch --recursive",
</code></pre>
<p>This will allow you to do imports like</p>
<div class="highlight highlight-source-css-scss"><pre><span class="pl-k">@import</span> <span class="pl-s"><span class="pl-pds">'</span>styles/_colors.scss<span class="pl-pds">'</span></span>; <span class="pl-c"><span class="pl-c">//</span> assuming a styles directory under src/</span>
<span class="pl-k">@import</span> <span class="pl-s"><span class="pl-pds">'</span>nprogress/nprogress<span class="pl-pds">'</span></span>; <span class="pl-c"><span class="pl-c">//</span> importing a css file from the nprogress node module</span></pre></div>
<p>At this point you might want to remove all CSS files from the source control, and add <code>src/**/*.css</code> to your <code>.gitignore</code> file. It is generally a good practice to keep the build products outside of the source control.</p>
<p>As a final step, you may find it convenient to run <code>watch-css</code> automatically with <code>npm start</code>, and run <code>build-css</code> as a part of <code>npm run build</code>. You can use the <code>&amp;&amp;</code> operator to execute two scripts sequentially. However, there is no cross-platform way to run two scripts in parallel, so we will install a package for this:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save npm-run-all</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add npm-run-all</pre></div>
<p>Then we can change <code>start</code> and <code>build</code> scripts to include the CSS preprocessor commands:</p>
<div class="highlight highlight-source-diff"><pre>   "scripts": {
     "build-css": "node-sass-chokidar src/ -o src/",
     "watch-css": "npm run build-css &amp;&amp; node-sass-chokidar src/ -o src/ --watch --recursive",
<span class="pl-md"><span class="pl-md">-</span>    "start": "react-scripts start",</span>
<span class="pl-md"><span class="pl-md">-</span>    "build": "react-scripts build",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>    "start-js": "react-scripts start",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>    "start": "npm-run-all -p watch-css start-js",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>    "build-js": "react-scripts build",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>    "build": "npm-run-all build-css build-js",</span>
     "test": "react-scripts test --env=jsdom",
     "eject": "react-scripts eject"
   }</pre></div>
<p>Now running <code>npm start</code> and <code>npm run build</code> also builds Sass files.</p>
<p><strong>Why <code>node-sass-chokidar</code>?</strong></p>
<p><code>node-sass</code> has been reported as having the following issues:</p>
<ul>
<li>
<p><code>node-sass --watch</code> has been reported to have <em>performance issues</em> in certain conditions when used in a virtual machine or with docker.</p>
</li>
<li>
<p>Infinite styles compiling <a href="https://github.com/facebookincubator/create-react-app/issues/1939">#1939</a></p>
</li>
<li>
<p><code>node-sass</code> has been reported as having issues with detecting new files in a directory <a href="https://github.com/sass/node-sass/issues/1891">#1891</a></p>
</li>
</ul>
<p><code>node-sass-chokidar</code> is used here as it addresses these issues.</p>
<h2><a id="user-content-adding-images-fonts-and-files" class="anchor" aria-hidden="true" href="#adding-images-fonts-and-files"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Images, Fonts, and Files</h2>
<p>With Webpack, using static assets like images and fonts works similarly to CSS.</p>
<p>You can <strong><code>import</code> a file right in a JavaScript module</strong>. This tells Webpack to include that file in the bundle. Unlike CSS imports, importing a file gives you a string value. This value is the final path you can reference in your code, e.g. as the <code>src</code> attribute of an image or the <code>href</code> of a link to a PDF.</p>
<p>To reduce the number of requests to the server, importing images that are less than 10,000 bytes returns a <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Data_URIs" rel="nofollow">data URI</a> instead of a path. This applies to the following file extensions: bmp, gif, jpg, jpeg, and png. SVG files are excluded due to <a href="https://github.com/facebookincubator/create-react-app/issues/1153">#1153</a>.</p>
<p>Here is an example:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-smi">logo</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>./logo.png<span class="pl-pds">'</span></span>; <span class="pl-c"><span class="pl-c">//</span> Tell Webpack this JS file uses this image</span>

<span class="pl-en">console</span>.<span class="pl-c1">log</span>(logo); <span class="pl-c"><span class="pl-c">//</span> /logo.84287d09.png</span>

<span class="pl-k">function</span> <span class="pl-en">Header</span>() {
  <span class="pl-c"><span class="pl-c">//</span> Import result is the URL of your image</span>
  <span class="pl-k">return</span> <span class="pl-k">&lt;</span>img src<span class="pl-k">=</span>{logo} alt<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Logo<span class="pl-pds">"</span></span> <span class="pl-k">/</span><span class="pl-k">&gt;</span>;
}

<span class="pl-k">export</span> <span class="pl-c1">default</span> <span class="pl-smi">Header</span>;</pre></div>
<p>This ensures that when the project is built, Webpack will correctly move the images into the build folder, and provide us with correct paths.</p>
<p>This works in CSS too:</p>
<div class="highlight highlight-source-css"><pre><span class="pl-e">.Logo</span> {
  <span class="pl-c1"><span class="pl-c1">background-image</span></span>: <span class="pl-c1">url</span>(<span class="pl-v">./logo.png</span>);
}</pre></div>
<p>Webpack finds all relative module references in CSS (they start with <code>./</code>) and replaces them with the final paths from the compiled bundle. If you make a typo or accidentally delete an important file, you will see a compilation error, just like when you import a non-existent JavaScript module. The final filenames in the compiled bundle are generated by Webpack from content hashes. If the file content changes in the future, Webpack will give it a different name in production so you don’t need to worry about long-term caching of assets.</p>
<p>Please be advised that this is also a custom feature of Webpack.</p>
<p><strong>It is not required for React</strong> but many people enjoy it (and React Native uses a similar mechanism for images).<br>
An alternative way of handling static assets is described in the next section.</p>
<h2><a id="user-content-using-the-public-folder" class="anchor" aria-hidden="true" href="#using-the-public-folder"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Using the <code>public</code> Folder</h2>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.5.0</code> and higher.</p>
</blockquote>
<h3><a id="user-content-changing-the-html" class="anchor" aria-hidden="true" href="#changing-the-html"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Changing the HTML</h3>
<p>The <code>public</code> folder contains the HTML file so you can tweak it, for example, to <a href="#changing-the-page-title">set the page title</a>.
The <code>&lt;script&gt;</code> tag with the compiled code will be added to it automatically during the build process.</p>
<h3><a id="user-content-adding-assets-outside-of-the-module-system" class="anchor" aria-hidden="true" href="#adding-assets-outside-of-the-module-system"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Assets Outside of the Module System</h3>
<p>You can also add other assets to the <code>public</code> folder.</p>
<p>Note that we normally encourage you to <code>import</code> assets in JavaScript files instead.
For example, see the sections on <a href="#adding-a-stylesheet">adding a stylesheet</a> and <a href="#adding-images-fonts-and-files">adding images and fonts</a>.
This mechanism provides a number of benefits:</p>
<ul>
<li>Scripts and stylesheets get minified and bundled together to avoid extra network requests.</li>
<li>Missing files cause compilation errors instead of 404 errors for your users.</li>
<li>Result filenames include content hashes so you don’t need to worry about browsers caching their old versions.</li>
</ul>
<p>However there is an <strong>escape hatch</strong> that you can use to add an asset outside of the module system.</p>
<p>If you put a file into the <code>public</code> folder, it will <strong>not</strong> be processed by Webpack. Instead it will be copied into the build folder untouched.   To reference assets in the <code>public</code> folder, you need to use a special variable called <code>PUBLIC_URL</code>.</p>
<p>Inside <code>index.html</code>, you can use it like this:</p>
<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent">link</span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>shortcut icon<span class="pl-pds">"</span></span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>%PUBLIC_URL%/favicon.ico<span class="pl-pds">"</span></span>&gt;</pre></div>
<p>Only files inside the <code>public</code> folder will be accessible by <code>%PUBLIC_URL%</code> prefix. If you need to use a file from <code>src</code> or <code>node_modules</code>, you’ll have to copy it there to explicitly specify your intention to make this file a part of the build.</p>
<p>When you run <code>npm run build</code>, Create React App will substitute <code>%PUBLIC_URL%</code> with a correct absolute path so your project works even if you use client-side routing or host it at a non-root URL.</p>
<p>In JavaScript code, you can use <code>process.env.PUBLIC_URL</code> for similar purposes:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">render</span>() {
  <span class="pl-c"><span class="pl-c">//</span> Note: this is an escape hatch and should be used sparingly!</span>
  <span class="pl-c"><span class="pl-c">//</span> Normally we recommend using `import` for getting asset URLs</span>
  <span class="pl-c"><span class="pl-c">//</span> as described in “Adding Images and Fonts” above this section.</span>
  <span class="pl-k">return</span> <span class="pl-k">&lt;</span>img src<span class="pl-k">=</span>{<span class="pl-c1">process</span>.<span class="pl-smi">env</span>.<span class="pl-c1">PUBLIC_URL</span> <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>/img/logo.png<span class="pl-pds">'</span></span>} <span class="pl-k">/</span><span class="pl-k">&gt;</span>;
}</pre></div>
<p>Keep in mind the downsides of this approach:</p>
<ul>
<li>None of the files in <code>public</code> folder get post-processed or minified.</li>
<li>Missing files will not be called at compilation time, and will cause 404 errors for your users.</li>
<li>Result filenames won’t include content hashes so you’ll need to add query arguments or rename them every time they change.</li>
</ul>
<h3><a id="user-content-when-to-use-the-public-folder" class="anchor" aria-hidden="true" href="#when-to-use-the-public-folder"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>When to Use the <code>public</code> Folder</h3>
<p>Normally we recommend importing <a href="#adding-a-stylesheet">stylesheets</a>, <a href="#adding-images-fonts-and-files">images, and fonts</a> from JavaScript.
The <code>public</code> folder is useful as a workaround for a number of less common cases:</p>
<ul>
<li>You need a file with a specific name in the build output, such as <a href="https://developer.mozilla.org/en-US/docs/Web/Manifest" rel="nofollow"><code>manifest.webmanifest</code></a>.</li>
<li>You have thousands of images and need to dynamically reference their paths.</li>
<li>You want to include a small script like <a href="http://github.hubspot.com/pace/docs/welcome/" rel="nofollow"><code>pace.js</code></a> outside of the bundled code.</li>
<li>Some library may be incompatible with Webpack and you have no other option but to include it as a <code>&lt;script&gt;</code> tag.</li>
</ul>
<p>Note that if you add a <code>&lt;script&gt;</code> that declares global variables, you also need to read the next section on using them.</p>
<h2><a id="user-content-using-global-variables" class="anchor" aria-hidden="true" href="#using-global-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Using Global Variables</h2>
<p>When you include a script in the HTML file that defines global variables and try to use one of these variables in the code, the linter will complain because it cannot see the definition of the variable.</p>
<p>You can avoid this by reading the global variable explicitly from the <code>window</code> object, for example:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-c1">$</span> <span class="pl-k">=</span> <span class="pl-c1">window</span>.<span class="pl-smi">$</span>;</pre></div>
<p>This makes it obvious you are using a global variable intentionally rather than because of a typo.</p>
<p>Alternatively, you can force the linter to ignore any line by adding <code>// eslint-disable-line</code> after it.</p>
<h2><a id="user-content-adding-bootstrap" class="anchor" aria-hidden="true" href="#adding-bootstrap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Bootstrap</h2>
<p>You don’t have to use <a href="https://react-bootstrap.github.io" rel="nofollow">React Bootstrap</a> together with React but it is a popular library for integrating Bootstrap with React apps. If you need it, you can integrate it with Create React App by following these steps:</p>
<p>Install React Bootstrap and Bootstrap from npm. React Bootstrap does not include Bootstrap CSS so this needs to be installed as well:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save react-bootstrap bootstrap@3</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add react-bootstrap bootstrap@3</pre></div>
<p>Import Bootstrap CSS and optionally Bootstrap theme CSS in the beginning of your <code>src/index.js</code> file:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-s"><span class="pl-pds">'</span>bootstrap/dist/css/bootstrap.css<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-s"><span class="pl-pds">'</span>bootstrap/dist/css/bootstrap-theme.css<span class="pl-pds">'</span></span>;
<span class="pl-c"><span class="pl-c">//</span> Put any other imports below so that CSS from your</span>
<span class="pl-c"><span class="pl-c">//</span> components takes precedence over default styles.</span></pre></div>
<p>Import required React Bootstrap components within <code>src/App.js</code> file or your custom component files:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> { <span class="pl-smi">Navbar</span>, <span class="pl-smi">Jumbotron</span>, <span class="pl-smi">Button</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react-bootstrap<span class="pl-pds">'</span></span>;</pre></div>
<p>Now you are ready to use the imported React Bootstrap components within your component hierarchy defined in the render method. Here is an example <a href="https://gist.githubusercontent.com/gaearon/85d8c067f6af1e56277c82d19fd4da7b/raw/6158dd991b67284e9fc8d70b9d973efe87659d72/App.js" rel="nofollow"><code>App.js</code></a> redone using React Bootstrap.</p>
<h3><a id="user-content-using-a-custom-theme" class="anchor" aria-hidden="true" href="#using-a-custom-theme"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Using a Custom Theme</h3>
<p>Sometimes you might need to tweak the visual styles of Bootstrap (or equivalent package).<br>
We suggest the following approach:</p>
<ul>
<li>Create a new package that depends on the package you wish to customize, e.g. Bootstrap.</li>
<li>Add the necessary build steps to tweak the theme, and publish your package on npm.</li>
<li>Install your own theme npm package as a dependency of your app.</li>
</ul>
<p>Here is an example of adding a <a href="https://medium.com/@tacomanator/customizing-create-react-app-aa9ffb88165" rel="nofollow">customized Bootstrap</a> that follows these steps.</p>
<h2><a id="user-content-adding-flow" class="anchor" aria-hidden="true" href="#adding-flow"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Flow</h2>
<p>Flow is a static type checker that helps you write code with fewer bugs. Check out this <a href="https://medium.com/@preethikasireddy/why-use-static-types-in-javascript-part-1-8382da1e0adb" rel="nofollow">introduction to using static types in JavaScript</a> if you are new to this concept.</p>
<p>Recent versions of <a href="http://flowtype.org/" rel="nofollow">Flow</a> work with Create React App projects out of the box.</p>
<p>To add Flow to a Create React App project, follow these steps:</p>
<ol>
<li>Run <code>npm install --save flow-bin</code> (or <code>yarn add flow-bin</code>).</li>
<li>Add <code>"flow": "flow"</code> to the <code>scripts</code> section of your <code>package.json</code>.</li>
<li>Run <code>npm run flow init</code> (or <code>yarn flow init</code>) to create a <a href="https://flowtype.org/docs/advanced-configuration.html" rel="nofollow"><code>.flowconfig</code> file</a> in the root directory.</li>
<li>Add <code>// @flow</code> to any files you want to type check (for example, to <code>src/App.js</code>).</li>
</ol>
<p>Now you can run <code>npm run flow</code> (or <code>yarn flow</code>) to check the files for type errors.
You can optionally use an IDE like <a href="https://nuclide.io/docs/languages/flow/" rel="nofollow">Nuclide</a> for a better integrated experience.
In the future we plan to integrate it into Create React App even more closely.</p>
<p>To learn more about Flow, check out <a href="https://flowtype.org/" rel="nofollow">its documentation</a>.</p>
<h2><a id="user-content-adding-a-router" class="anchor" aria-hidden="true" href="#adding-a-router"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding a Router</h2>
<p>Create React App doesn't prescribe a specific routing solution, but <a href="https://reacttraining.com/react-router/" rel="nofollow">React Router</a> is the most popular one.</p>
<p>To add it, run:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save react-router-dom</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add react-router-dom</pre></div>
<p>To try it, delete all the code in <code>src/App.js</code> and replace it with any of the examples on its website. The <a href="https://reacttraining.com/react-router/web/example/basic" rel="nofollow">Basic Example</a> is a good place to get started.</p>
<p>Note that <a href="#serving-apps-with-client-side-routing">you may need to configure your production server to support client-side routing</a> before deploying your app.</p>
<h2><a id="user-content-adding-custom-environment-variables" class="anchor" aria-hidden="true" href="#adding-custom-environment-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Custom Environment Variables</h2>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.2.3</code> and higher.</p>
</blockquote>
<p>Your project can consume variables declared in your environment as if they were declared locally in your JS files. By
default you will have <code>NODE_ENV</code> defined for you, and any other environment variables starting with
<code>REACT_APP_</code>.</p>
<p><strong>The environment variables are embedded during the build time</strong>. Since Create React App produces a static HTML/CSS/JS bundle, it can’t possibly read them at runtime. To read them at runtime, you would need to load HTML into memory on the server and replace placeholders in runtime, just like <a href="#injecting-data-from-the-server-into-the-page">described here</a>. Alternatively you can rebuild the app on the server anytime you change them.</p>
<blockquote>
<p>Note: You must create custom environment variables beginning with <code>REACT_APP_</code>. Any other variables except <code>NODE_ENV</code> will be ignored to avoid accidentally <a href="https://github.com/facebookincubator/create-react-app/issues/865#issuecomment-252199527">exposing a private key on the machine that could have the same name</a>. Changing any environment variables will require you to restart the development server if it is running.</p>
</blockquote>
<p>These environment variables will be defined for you on <code>process.env</code>. For example, having an environment
variable named <code>REACT_APP_SECRET_CODE</code> will be exposed in your JS as <code>process.env.REACT_APP_SECRET_CODE</code>.</p>
<p>There is also a special built-in environment variable called <code>NODE_ENV</code>. You can read it from <code>process.env.NODE_ENV</code>. When you run <code>npm start</code>, it is always equal to <code>'development'</code>, when you run <code>npm test</code> it is always equal to <code>'test'</code>, and when you run <code>npm run build</code> to make a production bundle, it is always equal to <code>'production'</code>. <strong>You cannot override <code>NODE_ENV</code> manually.</strong> This prevents developers from accidentally deploying a slow development build to production.</p>
<p>These environment variables can be useful for displaying information conditionally based on where the project is
deployed or consuming sensitive data that lives outside of version control.</p>
<p>First, you need to have environment variables defined. For example, let’s say you wanted to consume a secret defined
in the environment inside a <code>&lt;form&gt;</code>:</p>
<div class="highlight highlight-source-js-jsx"><pre><span class="pl-s"><span class="pl-en">render</span></span>() {
  <span class="pl-k">return</span> (
    &lt;<span class="pl-ent">div</span>&gt;
      &lt;<span class="pl-ent">small</span>&gt;You are running this application in &lt;<span class="pl-ent">b</span>&gt;<span class="pl-pse">{</span><span class="pl-c1">process</span><span class="pl-k">.</span><span class="pl-c1">env</span><span class="pl-k">.</span><span class="pl-c1">NODE_ENV</span><span class="pl-pse">}</span>&lt;/<span class="pl-ent">b</span>&gt; mode.&lt;/<span class="pl-ent">small</span>&gt;
      &lt;<span class="pl-ent">form</span>&gt;
        &lt;<span class="pl-ent">input</span> <span class="pl-e">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>hidden<span class="pl-pds">"</span></span> <span class="pl-e">defaultValue</span><span class="pl-k">=</span><span class="pl-pse">{</span><span class="pl-c1">process</span><span class="pl-k">.</span><span class="pl-c1">env</span><span class="pl-k">.</span><span class="pl-c1">REACT_APP_SECRET_CODE</span><span class="pl-pse">}</span> /&gt;
      &lt;/<span class="pl-ent">form</span>&gt;
    &lt;/<span class="pl-ent">div</span>&gt;
  );
}</pre></div>
<p>During the build, <code>process.env.REACT_APP_SECRET_CODE</code> will be replaced with the current value of the <code>REACT_APP_SECRET_CODE</code> environment variable. Remember that the <code>NODE_ENV</code> variable will be set for you automatically.</p>
<p>When you load the app in the browser and inspect the <code>&lt;input&gt;</code>, you will see its value set to <code>abcdef</code>, and the bold text will show the environment provided when using <code>npm start</code>:</p>
<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent">div</span>&gt;
  &lt;<span class="pl-ent">small</span>&gt;You are running this application in &lt;<span class="pl-ent">b</span>&gt;development&lt;/<span class="pl-ent">b</span>&gt; mode.&lt;/<span class="pl-ent">small</span>&gt;
  &lt;<span class="pl-ent">form</span>&gt;
    &lt;<span class="pl-ent">input</span> <span class="pl-e">type</span>=<span class="pl-s"><span class="pl-pds">"</span>hidden<span class="pl-pds">"</span></span> <span class="pl-e">value</span>=<span class="pl-s"><span class="pl-pds">"</span>abcdef<span class="pl-pds">"</span></span> /&gt;
  &lt;/<span class="pl-ent">form</span>&gt;
&lt;/<span class="pl-ent">div</span>&gt;</pre></div>
<p>The above form is looking for a variable called <code>REACT_APP_SECRET_CODE</code> from the environment. In order to consume this
value, we need to have it defined in the environment. This can be done using two ways: either in your shell or in
a <code>.env</code> file. Both of these ways are described in the next few sections.</p>
<p>Having access to the <code>NODE_ENV</code> is also useful for performing actions conditionally:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">if</span> (<span class="pl-c1">process</span>.<span class="pl-smi">env</span>.<span class="pl-c1">NODE_ENV</span> <span class="pl-k">!==</span> <span class="pl-s"><span class="pl-pds">'</span>production<span class="pl-pds">'</span></span>) {
  <span class="pl-smi">analytics</span>.<span class="pl-en">disable</span>();
}</pre></div>
<p>When you compile the app with <code>npm run build</code>, the minification step will strip out this condition, and the resulting bundle will be smaller.</p>
<h3><a id="user-content-referencing-environment-variables-in-the-html" class="anchor" aria-hidden="true" href="#referencing-environment-variables-in-the-html"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Referencing Environment Variables in the HTML</h3>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.9.0</code> and higher.</p>
</blockquote>
<p>You can also access the environment variables starting with <code>REACT_APP_</code> in the <code>public/index.html</code>. For example:</p>
<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent">title</span>&gt;%REACT_APP_WEBSITE_NAME%&lt;/<span class="pl-ent">title</span>&gt;</pre></div>
<p>Note that the caveats from the above section apply:</p>
<ul>
<li>Apart from a few built-in variables (<code>NODE_ENV</code> and <code>PUBLIC_URL</code>), variable names must start with <code>REACT_APP_</code> to work.</li>
<li>The environment variables are injected at build time. If you need to inject them at runtime, <a href="#generating-dynamic-meta-tags-on-the-server">follow this approach instead</a>.</li>
</ul>
<h3><a id="user-content-adding-temporary-environment-variables-in-your-shell" class="anchor" aria-hidden="true" href="#adding-temporary-environment-variables-in-your-shell"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Temporary Environment Variables In Your Shell</h3>
<p>Defining environment variables can vary between OSes. It’s also important to know that this manner is temporary for the
life of the shell session.</p>
<h4><a id="user-content-windows-cmdexe" class="anchor" aria-hidden="true" href="#windows-cmdexe"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows (cmd.exe)</h4>
<div class="highlight highlight-source-batchfile"><pre><span class="pl-k">set</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">REACT_APP_SECRET_CODE</span><span class="pl-k">=</span>abcdef<span class="pl-pds">"</span></span> <span class="pl-k">&amp;&amp;</span> npm <span class="pl-k">start</span></pre></div>
<p>(Note: Quotes around the variable assignment are required to avoid a trailing whitespace.)</p>
<h4><a id="user-content-windows-powershell" class="anchor" aria-hidden="true" href="#windows-powershell"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows (Powershell)</h4>
<div class="highlight highlight-source-powershell"><pre>(<span class="pl-smi">$<span class="pl-c1">env:</span>REACT_APP_SECRET_CODE</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>abcdef<span class="pl-pds">"</span></span>) <span class="pl-k">-and</span> (npm start)</pre></div>
<h4><a id="user-content-linux-macos-bash" class="anchor" aria-hidden="true" href="#linux-macos-bash"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Linux, macOS (Bash)</h4>
<div class="highlight highlight-source-shell"><pre>REACT_APP_SECRET_CODE=abcdef npm start</pre></div>
<h3><a id="user-content-adding-development-environment-variables-in-env" class="anchor" aria-hidden="true" href="#adding-development-environment-variables-in-env"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Adding Development Environment Variables In <code>.env</code></h3>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.5.0</code> and higher.</p>
</blockquote>
<p>To define permanent environment variables, create a file called <code>.env</code> in the root of your project:</p>
<pre><code>REACT_APP_SECRET_CODE=abcdef
</code></pre>
<blockquote>
<p>Note: You must create custom environment variables beginning with <code>REACT_APP_</code>. Any other variables except <code>NODE_ENV</code> will be ignored to avoid <a href="https://github.com/facebookincubator/create-react-app/issues/865#issuecomment-252199527">accidentally exposing a private key on the machine that could have the same name</a>. Changing any environment variables will require you to restart the development server if it is running.</p>
</blockquote>
<p><code>.env</code> files <strong>should be</strong> checked into source control (with the exclusion of <code>.env*.local</code>).</p>
<h4><a id="user-content-what-other-env-files-can-be-used" class="anchor" aria-hidden="true" href="#what-other-env-files-can-be-used"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>What other <code>.env</code> files can be used?</h4>
<blockquote>
<p>Note: this feature is <strong>available with <code>react-scripts@1.0.0</code> and higher</strong>.</p>
</blockquote>
<ul>
<li><code>.env</code>: Default.</li>
<li><code>.env.local</code>: Local overrides. <strong>This file is loaded for all environments except test.</strong></li>
<li><code>.env.development</code>, <code>.env.test</code>, <code>.env.production</code>: Environment-specific settings.</li>
<li><code>.env.development.local</code>, <code>.env.test.local</code>, <code>.env.production.local</code>: Local overrides of environment-specific settings.</li>
</ul>
<p>Files on the left have more priority than files on the right:</p>
<ul>
<li><code>npm start</code>: <code>.env.development.local</code>, <code>.env.development</code>, <code>.env.local</code>, <code>.env</code></li>
<li><code>npm run build</code>: <code>.env.production.local</code>, <code>.env.production</code>, <code>.env.local</code>, <code>.env</code></li>
<li><code>npm test</code>: <code>.env.test.local</code>, <code>.env.test</code>, <code>.env</code> (note <code>.env.local</code> is missing)</li>
</ul>
<p>These variables will act as the defaults if the machine does not explicitly set them.<br>
Please refer to the <a href="https://github.com/motdotla/dotenv">dotenv documentation</a> for more details.</p>
<blockquote>
<p>Note: If you are defining environment variables for development, your CI and/or hosting platform will most likely need
these defined as well. Consult their documentation how to do this. For example, see the documentation for <a href="https://docs.travis-ci.com/user/environment-variables/" rel="nofollow">Travis CI</a> or <a href="https://devcenter.heroku.com/articles/config-vars" rel="nofollow">Heroku</a>.</p>
</blockquote>
<h4><a id="user-content-expanding-environment-variables-in-env" class="anchor" aria-hidden="true" href="#expanding-environment-variables-in-env"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Expanding Environment Variables In <code>.env</code></h4>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@1.1.0</code> and higher.</p>
</blockquote>
<p>Expand variables already on your machine for use in your <code>.env</code> file (using <a href="https://github.com/motdotla/dotenv-expand">dotenv-expand</a>).</p>
<p>For example, to get the environment variable <code>npm_package_version</code>:</p>
<pre><code>REACT_APP_VERSION=$npm_package_version
# also works:
# REACT_APP_VERSION=${npm_package_version}
</code></pre>
<p>Or expand variables local to the current <code>.env</code> file:</p>
<pre><code>DOMAIN=www.example.com
REACT_APP_FOO=$DOMAIN/foo
REACT_APP_BAR=$DOMAIN/bar
</code></pre>
<h2><a id="user-content-can-i-use-decorators" class="anchor" aria-hidden="true" href="#can-i-use-decorators"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Can I Use Decorators?</h2>
<p>Many popular libraries use <a href="https://medium.com/google-developers/exploring-es7-decorators-76ecb65fb841" rel="nofollow">decorators</a> in their documentation.<br>
Create React App doesn’t support decorator syntax at the moment because:</p>
<ul>
<li>It is an experimental proposal and is subject to change.</li>
<li>The current specification version is not officially supported by Babel.</li>
<li>If the specification changes, we won’t be able to write a codemod because we don’t use them internally at Facebook.</li>
</ul>
<p>However in many cases you can rewrite decorator-based code without decorators just as fine.<br>
Please refer to these two threads for reference:</p>
<ul>
<li><a href="https://github.com/facebookincubator/create-react-app/issues/214">#214</a></li>
<li><a href="https://github.com/facebookincubator/create-react-app/issues/411">#411</a></li>
</ul>
<p>Create React App will add decorator support when the specification advances to a stable stage.</p>
<h2><a id="user-content-fetching-data-with-ajax-requests" class="anchor" aria-hidden="true" href="#fetching-data-with-ajax-requests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Fetching Data with AJAX Requests</h2>
<p>React doesn't prescribe a specific approach to data fetching, but people commonly use either a library like <a href="https://github.com/axios/axios">axios</a> or the <a href="https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API" rel="nofollow"><code>fetch()</code> API</a> provided by the browser. Conveniently, Create React App includes a polyfill for <code>fetch()</code> so you can use it without worrying about the browser support.</p>
<p>The global <code>fetch</code> function allows to easily makes AJAX requests. It takes in a URL as an input and returns a <code>Promise</code> that resolves to a <code>Response</code> object. You can find more information about <code>fetch</code> <a href="https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch" rel="nofollow">here</a>.</p>
<p>This project also includes a <a href="https://github.com/then/promise">Promise polyfill</a> which provides a full implementation of Promises/A+. A Promise represents the eventual result of an asynchronous operation, you can find more information about Promises <a href="https://www.promisejs.org/" rel="nofollow">here</a> and <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise" rel="nofollow">here</a>. Both axios and <code>fetch()</code> use Promises under the hood. You can also use the <a href="https://davidwalsh.name/async-await" rel="nofollow"><code>async / await</code></a> syntax to reduce the callback nesting.</p>
<p>You can learn more about making AJAX requests from React components in <a href="https://reactjs.org/docs/faq-ajax.html" rel="nofollow">the FAQ entry on the React website</a>.</p>
<h2><a id="user-content-integrating-with-an-api-backend" class="anchor" aria-hidden="true" href="#integrating-with-an-api-backend"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Integrating with an API Backend</h2>
<p>These tutorials will help you to integrate your app with an API backend running on another port,
using <code>fetch()</code> to access it.</p>
<h3><a id="user-content-node" class="anchor" aria-hidden="true" href="#node"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Node</h3>
<p>Check out <a href="https://www.fullstackreact.com/articles/using-create-react-app-with-a-server/" rel="nofollow">this tutorial</a>.
You can find the companion GitHub repository <a href="https://github.com/fullstackreact/food-lookup-demo">here</a>.</p>
<h3><a id="user-content-ruby-on-rails" class="anchor" aria-hidden="true" href="#ruby-on-rails"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Ruby on Rails</h3>
<p>Check out <a href="https://www.fullstackreact.com/articles/how-to-get-create-react-app-to-work-with-your-rails-api/" rel="nofollow">this tutorial</a>.
You can find the companion GitHub repository <a href="https://github.com/fullstackreact/food-lookup-demo-rails">here</a>.</p>
<h2><a id="user-content-proxying-api-requests-in-development" class="anchor" aria-hidden="true" href="#proxying-api-requests-in-development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Proxying API Requests in Development</h2>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.2.3</code> and higher.</p>
</blockquote>
<p>People often serve the front-end React app from the same host and port as their backend implementation.<br>
For example, a production setup might look like this after the app is deployed:</p>
<pre><code>/             - static server returns index.html with React app
/todos        - static server returns index.html with React app
/api/todos    - server handles any /api/* requests using the backend implementation
</code></pre>
<p>Such setup is <strong>not</strong> required. However, if you <strong>do</strong> have a setup like this, it is convenient to write requests like <code>fetch('/api/todos')</code> without worrying about redirecting them to another host or port during development.</p>
<p>To tell the development server to proxy any unknown requests to your API server in development, add a <code>proxy</code> field to your <code>package.json</code>, for example:</p>
<div class="highlight highlight-source-js"><pre>  <span class="pl-s"><span class="pl-pds">"</span>proxy<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>http://localhost:4000<span class="pl-pds">"</span></span>,</pre></div>
<p>This way, when you <code>fetch('/api/todos')</code> in development, the development server will recognize that it’s not a static asset, and will proxy your request to <code>http://localhost:4000/api/todos</code> as a fallback. The development server will <strong>only</strong> attempt to send requests without <code>text/html</code> in its <code>Accept</code> header to the proxy.</p>
<p>Conveniently, this avoids <a href="http://stackoverflow.com/questions/21854516/understanding-ajax-cors-and-security-considerations" rel="nofollow">CORS issues</a> and error messages like this in development:</p>
<pre><code>Fetch API cannot load http://localhost:4000/api/todos. No 'Access-Control-Allow-Origin' header is present on the requested resource. Origin 'http://localhost:3000' is therefore not allowed access. If an opaque response serves your needs, set the request's mode to 'no-cors' to fetch the resource with CORS disabled.
</code></pre>
<p>Keep in mind that <code>proxy</code> only has effect in development (with <code>npm start</code>), and it is up to you to ensure that URLs like <code>/api/todos</code> point to the right thing in production. You don’t have to use the <code>/api</code> prefix. Any unrecognized request without a <code>text/html</code> accept header will be redirected to the specified <code>proxy</code>.</p>
<p>The <code>proxy</code> option supports HTTP, HTTPS and WebSocket connections.<br>
If the <code>proxy</code> option is <strong>not</strong> flexible enough for you, alternatively you can:</p>
<ul>
<li><a href="#configuring-the-proxy-manually">Configure the proxy yourself</a></li>
<li>Enable CORS on your server (<a href="http://enable-cors.org/server_expressjs.html" rel="nofollow">here’s how to do it for Express</a>).</li>
<li>Use <a href="#adding-custom-environment-variables">environment variables</a> to inject the right server host and port into your app.</li>
</ul>
<h3><a id="user-content-invalid-host-header-errors-after-configuring-proxy" class="anchor" aria-hidden="true" href="#invalid-host-header-errors-after-configuring-proxy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>"Invalid Host Header" Errors After Configuring Proxy</h3>
<p>When you enable the <code>proxy</code> option, you opt into a more strict set of host checks. This is necessary because leaving the backend open to remote hosts makes your computer vulnerable to DNS rebinding attacks. The issue is explained in <a href="https://medium.com/webpack/webpack-dev-server-middleware-security-issues-1489d950874a" rel="nofollow">this article</a> and <a href="https://github.com/webpack/webpack-dev-server/issues/887">this issue</a>.</p>
<p>This shouldn’t affect you when developing on <code>localhost</code>, but if you develop remotely like <a href="https://github.com/facebookincubator/create-react-app/issues/2271">described here</a>, you will see this error in the browser after enabling the <code>proxy</code> option:</p>
<blockquote>
<p>Invalid Host header</p>
</blockquote>
<p>To work around it, you can specify your public development host in a file called <code>.env.development</code> in the root of your project:</p>
<pre><code>HOST=mypublicdevhost.com
</code></pre>
<p>If you restart the development server now and load the app from the specified host, it should work.</p>
<p>If you are still having issues or if you’re using a more exotic environment like a cloud editor, you can bypass the host check completely by adding a line to <code>.env.development.local</code>. <strong>Note that this is dangerous and exposes your machine to remote code execution from malicious websites:</strong></p>
<pre><code># NOTE: THIS IS DANGEROUS!
# It exposes your machine to attacks from the websites you visit.
DANGEROUSLY_DISABLE_HOST_CHECK=true
</code></pre>
<p>We don’t recommend this approach.</p>
<h3><a id="user-content-configuring-the-proxy-manually" class="anchor" aria-hidden="true" href="#configuring-the-proxy-manually"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Configuring the Proxy Manually</h3>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@1.0.0</code> and higher.</p>
</blockquote>
<p>If the <code>proxy</code> option is <strong>not</strong> flexible enough for you, you can specify an object in the following form (in <code>package.json</code>).<br>
You may also specify any configuration value <a href="https://github.com/chimurai/http-proxy-middleware#options"><code>http-proxy-middleware</code></a> or <a href="https://github.com/nodejitsu/node-http-proxy#options"><code>http-proxy</code></a> supports.</p>
<div class="highlight highlight-source-js"><pre>{
  <span class="pl-c"><span class="pl-c">//</span> ...</span>
  <span class="pl-s"><span class="pl-pds">"</span>proxy<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
    <span class="pl-s"><span class="pl-pds">"</span>/api<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
      <span class="pl-s"><span class="pl-pds">"</span>target<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>&lt;url&gt;<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>ws<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-c1">true</span>
      <span class="pl-c"><span class="pl-c">//</span> ...</span>
    }
  }
  <span class="pl-c"><span class="pl-c">//</span> ...</span>
}</pre></div>
<p>All requests matching this path will be proxies, no exceptions. This includes requests for <code>text/html</code>, which the standard <code>proxy</code> option does not proxy.</p>
<p>If you need to specify multiple proxies, you may do so by specifying additional entries.
Matches are regular expressions, so that you can use a regexp to match multiple paths.</p>
<div class="highlight highlight-source-js"><pre>{
  <span class="pl-c"><span class="pl-c">//</span> ...</span>
  <span class="pl-s"><span class="pl-pds">"</span>proxy<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
    <span class="pl-c"><span class="pl-c">//</span> Matches any request starting with /api</span>
    <span class="pl-s"><span class="pl-pds">"</span>/api<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
      <span class="pl-s"><span class="pl-pds">"</span>target<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>&lt;url_1&gt;<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>ws<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-c1">true</span>
      <span class="pl-c"><span class="pl-c">//</span> ...</span>
    },
    <span class="pl-c"><span class="pl-c">//</span> Matches any request starting with /foo</span>
    <span class="pl-s"><span class="pl-pds">"</span>/foo<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
      <span class="pl-s"><span class="pl-pds">"</span>target<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>&lt;url_2&gt;<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>ssl<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-c1">true</span>,
      <span class="pl-s"><span class="pl-pds">"</span>pathRewrite<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
        <span class="pl-s"><span class="pl-pds">"</span>^/foo<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>/foo/beta<span class="pl-pds">"</span></span>
      }
      <span class="pl-c"><span class="pl-c">//</span> ...</span>
    },
    <span class="pl-c"><span class="pl-c">//</span> Matches /bar/abc.html but not /bar/sub/def.html</span>
    <span class="pl-s"><span class="pl-pds">"</span>/bar/[^/]*[.]html<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
      <span class="pl-s"><span class="pl-pds">"</span>target<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>&lt;url_3&gt;<span class="pl-pds">"</span></span>,
      <span class="pl-c"><span class="pl-c">//</span> ...</span>
    },
    <span class="pl-c"><span class="pl-c">//</span> Matches /baz/abc.html and /baz/sub/def.html</span>
    <span class="pl-s"><span class="pl-pds">"</span>/baz/.*/.*[.]html<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
      <span class="pl-s"><span class="pl-pds">"</span>target<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>&lt;url_4&gt;<span class="pl-pds">"</span></span>
      <span class="pl-c"><span class="pl-c">//</span> ...</span>
    }
  }
  <span class="pl-c"><span class="pl-c">//</span> ...</span>
}</pre></div>
<h3><a id="user-content-configuring-a-websocket-proxy" class="anchor" aria-hidden="true" href="#configuring-a-websocket-proxy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Configuring a WebSocket Proxy</h3>
<p>When setting up a WebSocket proxy, there are a some extra considerations to be aware of.</p>
<p>If you’re using a WebSocket engine like <a href="https://socket.io/" rel="nofollow">Socket.io</a>, you must have a Socket.io server running that you can use as the proxy target. Socket.io will not work with a standard WebSocket server. Specifically, don't expect Socket.io to work with <a href="http://websocket.org/echo.html" rel="nofollow">the websocket.org echo test</a>.</p>
<p>There’s some good documentation available for <a href="https://socket.io/docs/" rel="nofollow">setting up a Socket.io server</a>.</p>
<p>Standard WebSockets <strong>will</strong> work with a standard WebSocket server as well as the websocket.org echo test. You can use libraries like <a href="https://github.com/websockets/ws">ws</a> for the server, with <a href="https://developer.mozilla.org/en-US/docs/Web/API/WebSocket" rel="nofollow">native WebSockets in the browser</a>.</p>
<p>Either way, you can proxy WebSocket requests manually in <code>package.json</code>:</p>
<div class="highlight highlight-source-js"><pre>{
  <span class="pl-c"><span class="pl-c">//</span> ...</span>
  <span class="pl-s"><span class="pl-pds">"</span>proxy<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
    <span class="pl-s"><span class="pl-pds">"</span>/socket<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
      <span class="pl-c"><span class="pl-c">//</span> Your compatible WebSocket server</span>
      <span class="pl-s"><span class="pl-pds">"</span>target<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>ws://&lt;socket_url&gt;<span class="pl-pds">"</span></span>,
      <span class="pl-c"><span class="pl-c">//</span> Tell http-proxy-middleware that this is a WebSocket proxy.</span>
      <span class="pl-c"><span class="pl-c">//</span> Also allows you to proxy WebSocket requests without an additional HTTP request</span>
      <span class="pl-c"><span class="pl-c">//</span> https://github.com/chimurai/http-proxy-middleware#external-websocket-upgrade</span>
      <span class="pl-s"><span class="pl-pds">"</span>ws<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-c1">true</span>
      <span class="pl-c"><span class="pl-c">//</span> ...</span>
    }
  }
  <span class="pl-c"><span class="pl-c">//</span> ...</span>
}</pre></div>
<h2><a id="user-content-using-https-in-development" class="anchor" aria-hidden="true" href="#using-https-in-development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Using HTTPS in Development</h2>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.4.0</code> and higher.</p>
</blockquote>
<p>You may require the dev server to serve pages over HTTPS. One particular case where this could be useful is when using <a href="#proxying-api-requests-in-development">the "proxy" feature</a> to proxy requests to an API server when that API server is itself serving HTTPS.</p>
<p>To do this, set the <code>HTTPS</code> environment variable to <code>true</code>, then start the dev server as usual with <code>npm start</code>:</p>
<h4><a id="user-content-windows-cmdexe-1" class="anchor" aria-hidden="true" href="#windows-cmdexe-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows (cmd.exe)</h4>
<div class="highlight highlight-source-batchfile"><pre><span class="pl-k">set</span> <span class="pl-smi">HTTPS</span><span class="pl-k">=</span>true<span class="pl-k">&amp;&amp;</span>npm <span class="pl-k">start</span></pre></div>
<h4><a id="user-content-windows-powershell-1" class="anchor" aria-hidden="true" href="#windows-powershell-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows (Powershell)</h4>
<div class="highlight highlight-source-powershell"><pre>(<span class="pl-smi">$<span class="pl-c1">env:</span>HTTPS</span> <span class="pl-k">=</span> <span class="pl-c1">$true</span>) <span class="pl-k">-and</span> (npm start)</pre></div>
<p>(Note: the lack of whitespace is intentional.)</p>
<h4><a id="user-content-linux-macos-bash-1" class="anchor" aria-hidden="true" href="#linux-macos-bash-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Linux, macOS (Bash)</h4>
<div class="highlight highlight-source-shell"><pre>HTTPS=true npm start</pre></div>
<p>Note that the server will use a self-signed certificate, so your web browser will almost definitely display a warning upon accessing the page.</p>
<h2><a id="user-content-generating-dynamic-meta-tags-on-the-server" class="anchor" aria-hidden="true" href="#generating-dynamic-meta-tags-on-the-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Generating Dynamic <code>&lt;meta&gt;</code> Tags on the Server</h2>
<p>Since Create React App doesn’t support server rendering, you might be wondering how to make <code>&lt;meta&gt;</code> tags dynamic and reflect the current URL. To solve this, we recommend to add placeholders into the HTML, like this:</p>
<div class="highlight highlight-text-html-basic"><pre>&lt;!doctype html&gt;
&lt;<span class="pl-ent">html</span> <span class="pl-e">lang</span>=<span class="pl-s"><span class="pl-pds">"</span>en<span class="pl-pds">"</span></span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    &lt;<span class="pl-ent">meta</span> <span class="pl-e">property</span>=<span class="pl-s"><span class="pl-pds">"</span>og:title<span class="pl-pds">"</span></span> <span class="pl-e">content</span>=<span class="pl-s"><span class="pl-pds">"</span>__OG_TITLE__<span class="pl-pds">"</span></span>&gt;
    &lt;<span class="pl-ent">meta</span> <span class="pl-e">property</span>=<span class="pl-s"><span class="pl-pds">"</span>og:description<span class="pl-pds">"</span></span> <span class="pl-e">content</span>=<span class="pl-s"><span class="pl-pds">"</span>__OG_DESCRIPTION__<span class="pl-pds">"</span></span>&gt;</pre></div>
<p>Then, on the server, regardless of the backend you use, you can read <code>index.html</code> into memory and replace <code>__OG_TITLE__</code>, <code>__OG_DESCRIPTION__</code>, and any other placeholders with values depending on the current URL. Just make sure to sanitize and escape the interpolated values so that they are safe to embed into HTML!</p>
<p>If you use a Node server, you can even share the route matching logic between the client and the server. However duplicating it also works fine in simple cases.</p>
<h2><a id="user-content-pre-rendering-into-static-html-files" class="anchor" aria-hidden="true" href="#pre-rendering-into-static-html-files"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Pre-Rendering into Static HTML Files</h2>
<p>If you’re hosting your <code>build</code> with a static hosting provider you can use <a href="https://www.npmjs.com/package/react-snapshot" rel="nofollow">react-snapshot</a> or <a href="https://github.com/stereobooster/react-snap">react-snap</a> to generate HTML pages for each route, or relative link, in your application. These pages will then seamlessly become active, or “hydrated”, when the JavaScript bundle has loaded.</p>
<p>There are also opportunities to use this outside of static hosting, to take the pressure off the server when generating and caching routes.</p>
<p>The primary benefit of pre-rendering is that you get the core content of each page <em>with</em> the HTML payload—regardless of whether or not your JavaScript bundle successfully downloads. It also increases the likelihood that each route of your application will be picked up by search engines.</p>
<p>You can read more about <a href="https://medium.com/superhighfives/an-almost-static-stack-6df0a2791319" rel="nofollow">zero-configuration pre-rendering (also called snapshotting) here</a>.</p>
<h2><a id="user-content-injecting-data-from-the-server-into-the-page" class="anchor" aria-hidden="true" href="#injecting-data-from-the-server-into-the-page"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Injecting Data from the Server into the Page</h2>
<p>Similarly to the previous section, you can leave some placeholders in the HTML that inject global variables, for example:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">&lt;</span><span class="pl-k">!</span>doctype html<span class="pl-k">&gt;</span>
<span class="pl-k">&lt;</span>html lang<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>en<span class="pl-pds">"</span></span><span class="pl-k">&gt;</span>
  <span class="pl-k">&lt;</span>head<span class="pl-k">&gt;</span>
    <span class="pl-k">&lt;</span>script<span class="pl-k">&gt;</span>
      <span class="pl-c1">window</span>.<span class="pl-c1">SERVER_DATA</span> <span class="pl-k">=</span> <span class="pl-c1">__SERVER_DATA__</span>;
    <span class="pl-k">&lt;</span><span class="pl-k">/</span>script<span class="pl-k">&gt;</span></pre></div>
<p>Then, on the server, you can replace <code>__SERVER_DATA__</code> with a JSON of real data right before sending the response. The client code can then read <code>window.SERVER_DATA</code> to use it. <strong>Make sure to <a href="https://medium.com/node-security/the-most-common-xss-vulnerability-in-react-js-applications-2bdffbcc1fa0" rel="nofollow">sanitize the JSON before sending it to the client</a> as it makes your app vulnerable to XSS attacks.</strong></p>
<h2><a id="user-content-running-tests" class="anchor" aria-hidden="true" href="#running-tests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Running Tests</h2>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.3.0</code> and higher.<br>
<a href="https://github.com/facebookincubator/create-react-app/blob/master/CHANGELOG.md#migrating-from-023-to-030">Read the migration guide to learn how to enable it in older projects!</a></p>
</blockquote>
<p>Create React App uses <a href="https://facebook.github.io/jest/" rel="nofollow">Jest</a> as its test runner. To prepare for this integration, we did a <a href="https://facebook.github.io/jest/blog/2016/09/01/jest-15.html" rel="nofollow">major revamp</a> of Jest so if you heard bad things about it years ago, give it another try.</p>
<p>Jest is a Node-based runner. This means that the tests always run in a Node environment and not in a real browser. This lets us enable fast iteration speed and prevent flakiness.</p>
<p>While Jest provides browser globals such as <code>window</code> thanks to <a href="https://github.com/tmpvar/jsdom">jsdom</a>, they are only approximations of the real browser behavior. Jest is intended to be used for unit tests of your logic and your components rather than the DOM quirks.</p>
<p>We recommend that you use a separate tool for browser end-to-end tests if you need them. They are beyond the scope of Create React App.</p>
<h3><a id="user-content-filename-conventions" class="anchor" aria-hidden="true" href="#filename-conventions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Filename Conventions</h3>
<p>Jest will look for test files with any of the following popular naming conventions:</p>
<ul>
<li>Files with <code>.js</code> suffix in <code>__tests__</code> folders.</li>
<li>Files with <code>.test.js</code> suffix.</li>
<li>Files with <code>.spec.js</code> suffix.</li>
</ul>
<p>The <code>.test.js</code> / <code>.spec.js</code> files (or the <code>__tests__</code> folders) can be located at any depth under the <code>src</code> top level folder.</p>
<p>We recommend to put the test files (or <code>__tests__</code> folders) next to the code they are testing so that relative imports appear shorter. For example, if <code>App.test.js</code> and <code>App.js</code> are in the same folder, the test just needs to <code>import App from './App'</code> instead of a long relative path. Colocation also helps find tests more quickly in larger projects.</p>
<h3><a id="user-content-command-line-interface" class="anchor" aria-hidden="true" href="#command-line-interface"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Command Line Interface</h3>
<p>When you run <code>npm test</code>, Jest will launch in the watch mode. Every time you save a file, it will re-run the tests, just like <code>npm start</code> recompiles the code.</p>
<p>The watcher includes an interactive command-line interface with the ability to run all tests, or focus on a search pattern. It is designed this way so that you can keep it open and enjoy fast re-runs. You can learn the commands from the “Watch Usage” note that the watcher prints after every run:</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/e17b470bdfc383db6ea4b32c4257d04af6e1e749/687474703a2f2f66616365626f6f6b2e6769746875622e696f2f6a6573742f696d672f626c6f672f31352d77617463682e676966"><img src="https://camo.githubusercontent.com/e17b470bdfc383db6ea4b32c4257d04af6e1e749/687474703a2f2f66616365626f6f6b2e6769746875622e696f2f6a6573742f696d672f626c6f672f31352d77617463682e676966" alt="Jest watch mode" data-canonical-src="http://facebook.github.io/jest/img/blog/15-watch.gif" style="max-width:100%;"></a></p>
<h3><a id="user-content-version-control-integration" class="anchor" aria-hidden="true" href="#version-control-integration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Version Control Integration</h3>
<p>By default, when you run <code>npm test</code>, Jest will only run the tests related to files changed since the last commit. This is an optimization designed to make your tests run fast regardless of how many tests you have. However it assumes that you don’t often commit the code that doesn’t pass the tests.</p>
<p>Jest will always explicitly mention that it only ran tests related to the files changed since the last commit. You can also press <code>a</code> in the watch mode to force Jest to run all tests.</p>
<p>Jest will always run all tests on a <a href="#continuous-integration">continuous integration</a> server or if the project is not inside a Git or Mercurial repository.</p>
<h3><a id="user-content-writing-tests" class="anchor" aria-hidden="true" href="#writing-tests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Writing Tests</h3>
<p>To create tests, add <code>it()</code> (or <code>test()</code>) blocks with the name of the test and its code. You may optionally wrap them in <code>describe()</code> blocks for logical grouping but this is neither required nor recommended.</p>
<p>Jest provides a built-in <code>expect()</code> global function for making assertions. A basic test could look like this:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">sum</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>./sum<span class="pl-pds">'</span></span>;

<span class="pl-en">it</span>(<span class="pl-s"><span class="pl-pds">'</span>sums numbers<span class="pl-pds">'</span></span>, () <span class="pl-k">=&gt;</span> {
  <span class="pl-en">expect</span>(<span class="pl-en">sum</span>(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>)).<span class="pl-en">toEqual</span>(<span class="pl-c1">3</span>);
  <span class="pl-en">expect</span>(<span class="pl-en">sum</span>(<span class="pl-c1">2</span>, <span class="pl-c1">2</span>)).<span class="pl-en">toEqual</span>(<span class="pl-c1">4</span>);
});</pre></div>
<p>All <code>expect()</code> matchers supported by Jest are <a href="https://facebook.github.io/jest/docs/en/expect.html#content" rel="nofollow">extensively documented here</a>.<br>
You can also use <a href="https://facebook.github.io/jest/docs/en/expect.html#tohavebeencalled" rel="nofollow"><code>jest.fn()</code> and <code>expect(fn).toBeCalled()</code></a> to create “spies” or mock functions.</p>
<h3><a id="user-content-testing-components" class="anchor" aria-hidden="true" href="#testing-components"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Testing Components</h3>
<p>There is a broad spectrum of component testing techniques. They range from a “smoke test” verifying that a component renders without throwing, to shallow rendering and testing some of the output, to full rendering and testing component lifecycle and state changes.</p>
<p>Different projects choose different testing tradeoffs based on how often components change, and how much logic they contain. If you haven’t decided on a testing strategy yet, we recommend that you start with creating simple smoke tests for your components:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-smi">ReactDOM</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react-dom<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-smi">App</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>./App<span class="pl-pds">'</span></span>;

<span class="pl-en">it</span>(<span class="pl-s"><span class="pl-pds">'</span>renders without crashing<span class="pl-pds">'</span></span>, () <span class="pl-k">=&gt;</span> {
  <span class="pl-k">const</span> <span class="pl-c1">div</span> <span class="pl-k">=</span> <span class="pl-c1">document</span>.<span class="pl-c1">createElement</span>(<span class="pl-s"><span class="pl-pds">'</span>div<span class="pl-pds">'</span></span>);
  <span class="pl-smi">ReactDOM</span>.<span class="pl-en">render</span>(<span class="pl-k">&lt;</span>App <span class="pl-k">/</span><span class="pl-k">&gt;</span>, div);
});</pre></div>
<p>This test mounts a component and makes sure that it didn’t throw during rendering. Tests like this provide a lot of value with very little effort so they are great as a starting point, and this is the test you will find in <code>src/App.test.js</code>.</p>
<p>When you encounter bugs caused by changing components, you will gain a deeper insight into which parts of them are worth testing in your application. This might be a good time to introduce more specific tests asserting specific expected output or behavior.</p>
<p>If you’d like to test components in isolation from the child components they render, we recommend using <a href="http://airbnb.io/enzyme/docs/api/shallow.html" rel="nofollow"><code>shallow()</code> rendering API</a> from <a href="http://airbnb.io/enzyme/" rel="nofollow">Enzyme</a>. To install it, run:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save enzyme enzyme-adapter-react-16 react-test-renderer</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add enzyme enzyme-adapter-react-16 react-test-renderer</pre></div>
<p>As of Enzyme 3, you will need to install Enzyme along with an Adapter corresponding to the version of React you are using. (The examples above use the adapter for React 16.)</p>
<p>The adapter will also need to be configured in your <a href="#initializing-test-environment">global setup file</a>:</p>
<h4><a id="user-content-srcsetuptestsjs" class="anchor" aria-hidden="true" href="#srcsetuptestsjs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>src/setupTests.js</code></h4>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> { <span class="pl-smi">configure</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>enzyme<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-smi">Adapter</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>enzyme-adapter-react-16<span class="pl-pds">'</span></span>;

<span class="pl-en">configure</span>({ adapter<span class="pl-k">:</span> <span class="pl-k">new</span> <span class="pl-en">Adapter</span>() });</pre></div>
<blockquote>
<p>Note: Keep in mind that if you decide to "eject" before creating <code>src/setupTests.js</code>, the resulting <code>package.json</code> file won't contain any reference to it. <a href="#initializing-test-environment">Read here</a> to learn how to add this after ejecting.</p>
</blockquote>
<p>Now you can write a smoke test with it:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> { <span class="pl-smi">shallow</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>enzyme<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-smi">App</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>./App<span class="pl-pds">'</span></span>;

<span class="pl-en">it</span>(<span class="pl-s"><span class="pl-pds">'</span>renders without crashing<span class="pl-pds">'</span></span>, () <span class="pl-k">=&gt;</span> {
  <span class="pl-en">shallow</span>(<span class="pl-k">&lt;</span>App <span class="pl-k">/</span><span class="pl-k">&gt;</span>);
});</pre></div>
<p>Unlike the previous smoke test using <code>ReactDOM.render()</code>, this test only renders <code>&lt;App&gt;</code> and doesn’t go deeper. For example, even if <code>&lt;App&gt;</code> itself renders a <code>&lt;Button&gt;</code> that throws, this test will pass. Shallow rendering is great for isolated unit tests, but you may still want to create some full rendering tests to ensure the components integrate correctly. Enzyme supports <a href="http://airbnb.io/enzyme/docs/api/mount.html" rel="nofollow">full rendering with <code>mount()</code></a>, and you can also use it for testing state changes and component lifecycle.</p>
<p>You can read the <a href="http://airbnb.io/enzyme/" rel="nofollow">Enzyme documentation</a> for more testing techniques. Enzyme documentation uses Chai and Sinon for assertions but you don’t have to use them because Jest provides built-in <code>expect()</code> and <code>jest.fn()</code> for spies.</p>
<p>Here is an example from Enzyme documentation that asserts specific output, rewritten to use Jest matchers:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">React</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>react<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> { <span class="pl-smi">shallow</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>enzyme<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-smi">App</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>./App<span class="pl-pds">'</span></span>;

<span class="pl-en">it</span>(<span class="pl-s"><span class="pl-pds">'</span>renders welcome message<span class="pl-pds">'</span></span>, () <span class="pl-k">=&gt;</span> {
  <span class="pl-k">const</span> <span class="pl-c1">wrapper</span> <span class="pl-k">=</span> <span class="pl-en">shallow</span>(<span class="pl-k">&lt;</span>App <span class="pl-k">/</span><span class="pl-k">&gt;</span>);
  <span class="pl-k">const</span> <span class="pl-c1">welcome</span> <span class="pl-k">=</span> <span class="pl-k">&lt;</span>h2<span class="pl-k">&gt;</span>Welcome to React<span class="pl-k">&lt;</span><span class="pl-k">/</span>h2<span class="pl-k">&gt;</span>;
  <span class="pl-c"><span class="pl-c">//</span> expect(wrapper.contains(welcome)).to.equal(true);</span>
  <span class="pl-en">expect</span>(<span class="pl-smi">wrapper</span>.<span class="pl-c1">contains</span>(welcome)).<span class="pl-en">toEqual</span>(<span class="pl-c1">true</span>);
});</pre></div>
<p>All Jest matchers are <a href="http://facebook.github.io/jest/docs/en/expect.html" rel="nofollow">extensively documented here</a>.<br>
Nevertheless you can use a third-party assertion library like <a href="http://chaijs.com/" rel="nofollow">Chai</a> if you want to, as described below.</p>
<p>Additionally, you might find <a href="https://github.com/blainekasten/enzyme-matchers">jest-enzyme</a> helpful to simplify your tests with readable matchers. The above <code>contains</code> code can be written more simply with jest-enzyme.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">expect</span>(wrapper).<span class="pl-en">toContainReact</span>(welcome)</pre></div>
<p>To enable this, install <code>jest-enzyme</code>:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save jest-enzyme</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add jest-enzyme</pre></div>
<p>Import it in <a href="#initializing-test-environment"><code>src/setupTests.js</code></a> to make its matchers available in every test:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-s"><span class="pl-pds">'</span>jest-enzyme<span class="pl-pds">'</span></span>;</pre></div>
<h3><a id="user-content-using-third-party-assertion-libraries" class="anchor" aria-hidden="true" href="#using-third-party-assertion-libraries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Using Third Party Assertion Libraries</h3>
<p>We recommend that you use <code>expect()</code> for assertions and <code>jest.fn()</code> for spies. If you are having issues with them please <a href="https://github.com/facebook/jest/issues/new">file those against Jest</a>, and we’ll fix them. We intend to keep making them better for React, supporting, for example, <a href="https://github.com/facebook/jest/pull/1566">pretty-printing React elements as JSX</a>.</p>
<p>However, if you are used to other libraries, such as <a href="http://chaijs.com/" rel="nofollow">Chai</a> and <a href="http://sinonjs.org/" rel="nofollow">Sinon</a>, or if you have existing code using them that you’d like to port over, you can import them normally like this:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">sinon</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>sinon<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> { <span class="pl-smi">expect</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>chai<span class="pl-pds">'</span></span>;</pre></div>
<p>and then use them in your tests like you normally do.</p>
<h3><a id="user-content-initializing-test-environment" class="anchor" aria-hidden="true" href="#initializing-test-environment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Initializing Test Environment</h3>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.4.0</code> and higher.</p>
</blockquote>
<p>If your app uses a browser API that you need to mock in your tests or if you just need a global setup before running your tests, add a <code>src/setupTests.js</code> to your project. It will be automatically executed before running your tests.</p>
<p>For example:</p>
<h4><a id="user-content-srcsetuptestsjs-1" class="anchor" aria-hidden="true" href="#srcsetuptestsjs-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>src/setupTests.js</code></h4>
<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-c1">localStorageMock</span> <span class="pl-k">=</span> {
  getItem<span class="pl-k">:</span> <span class="pl-smi">jest</span>.<span class="pl-en">fn</span>(),
  setItem<span class="pl-k">:</span> <span class="pl-smi">jest</span>.<span class="pl-en">fn</span>(),
  clear<span class="pl-k">:</span> <span class="pl-smi">jest</span>.<span class="pl-en">fn</span>()
};
<span class="pl-c1">global</span>.<span class="pl-smi">localStorage</span> <span class="pl-k">=</span> localStorageMock</pre></div>
<blockquote>
<p>Note: Keep in mind that if you decide to "eject" before creating <code>src/setupTests.js</code>, the resulting <code>package.json</code> file won't contain any reference to it, so you should manually create the property <code>setupTestFrameworkScriptFile</code> in the configuration for Jest, something like the following:</p>
</blockquote>
<blockquote>
<div class="highlight highlight-source-js"><pre><span class="pl-s"><span class="pl-pds">"</span>jest<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
  <span class="pl-c"><span class="pl-c">//</span> ...</span>
  <span class="pl-s"><span class="pl-pds">"</span>setupTestFrameworkScriptFile<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>&lt;rootDir&gt;/src/setupTests.js<span class="pl-pds">"</span></span>
 }</pre></div>
</blockquote>
<h3><a id="user-content-focusing-and-excluding-tests" class="anchor" aria-hidden="true" href="#focusing-and-excluding-tests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Focusing and Excluding Tests</h3>
<p>You can replace <code>it()</code> with <code>xit()</code> to temporarily exclude a test from being executed.<br>
Similarly, <code>fit()</code> lets you focus on a specific test without running any other tests.</p>
<h3><a id="user-content-coverage-reporting" class="anchor" aria-hidden="true" href="#coverage-reporting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Coverage Reporting</h3>
<p>Jest has an integrated coverage reporter that works well with ES6 and requires no configuration.<br>
Run <code>npm test -- --coverage</code> (note extra <code>--</code> in the middle) to include a coverage report like this:</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/bd0bbda8e44ea747e4c199d0e212d40563ad2fcb/687474703a2f2f692e696d6775722e636f6d2f356246686e54532e706e67"><img src="https://camo.githubusercontent.com/bd0bbda8e44ea747e4c199d0e212d40563ad2fcb/687474703a2f2f692e696d6775722e636f6d2f356246686e54532e706e67" alt="coverage report" data-canonical-src="http://i.imgur.com/5bFhnTS.png" style="max-width:100%;"></a></p>
<p>Note that tests run much slower with coverage so it is recommended to run it separately from your normal workflow.</p>
<h4><a id="user-content-configuration" class="anchor" aria-hidden="true" href="#configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Configuration</h4>
<p>The default Jest coverage configuration can be overriden by adding any of the following supported keys to a Jest config in your package.json.</p>
<p>Supported overrides:</p>
<ul>
<li><a href="https://facebook.github.io/jest/docs/en/configuration.html#collectcoveragefrom-array" rel="nofollow"><code>collectCoverageFrom</code></a></li>
<li><a href="https://facebook.github.io/jest/docs/en/configuration.html#coveragereporters-array-string" rel="nofollow"><code>coverageReporters</code></a></li>
<li><a href="https://facebook.github.io/jest/docs/en/configuration.html#coveragethreshold-object" rel="nofollow"><code>coverageThreshold</code></a></li>
<li><a href="https://facebook.github.io/jest/docs/en/configuration.html#snapshotserializers-array-string" rel="nofollow"><code>snapshotSerializers</code></a></li>
</ul>
<p>Example package.json:</p>
<div class="highlight highlight-source-json"><pre>{
  <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>your-package<span class="pl-pds">"</span></span>,
  <span class="pl-s"><span class="pl-pds">"</span>jest<span class="pl-pds">"</span></span>: {
    <span class="pl-s"><span class="pl-pds">"</span>collectCoverageFrom<span class="pl-pds">"</span></span> : [
      <span class="pl-s"><span class="pl-pds">"</span>src/**/*.{js,jsx}<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>!&lt;rootDir&gt;/node_modules/<span class="pl-pds">"</span></span>,
      <span class="pl-s"><span class="pl-pds">"</span>!&lt;rootDir&gt;/path/to/dir/<span class="pl-pds">"</span></span>
    ],
    <span class="pl-s"><span class="pl-pds">"</span>coverageThreshold<span class="pl-pds">"</span></span>: {
      <span class="pl-s"><span class="pl-pds">"</span>global<span class="pl-pds">"</span></span>: {
        <span class="pl-s"><span class="pl-pds">"</span>branches<span class="pl-pds">"</span></span>: <span class="pl-c1">90</span>,
        <span class="pl-s"><span class="pl-pds">"</span>functions<span class="pl-pds">"</span></span>: <span class="pl-c1">90</span>,
        <span class="pl-s"><span class="pl-pds">"</span>lines<span class="pl-pds">"</span></span>: <span class="pl-c1">90</span>,
        <span class="pl-s"><span class="pl-pds">"</span>statements<span class="pl-pds">"</span></span>: <span class="pl-c1">90</span>
      }
    },
    <span class="pl-s"><span class="pl-pds">"</span>coverageReporters<span class="pl-pds">"</span></span>: [<span class="pl-s"><span class="pl-pds">"</span>text<span class="pl-pds">"</span></span>],
    <span class="pl-s"><span class="pl-pds">"</span>snapshotSerializers<span class="pl-pds">"</span></span>: [<span class="pl-s"><span class="pl-pds">"</span>my-serializer-module<span class="pl-pds">"</span></span>]
  }
}</pre></div>
<h3><a id="user-content-continuous-integration" class="anchor" aria-hidden="true" href="#continuous-integration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Continuous Integration</h3>
<p>By default <code>npm test</code> runs the watcher with interactive CLI. However, you can force it to run tests once and finish the process by setting an environment variable called <code>CI</code>.</p>
<p>When creating a build of your application with <code>npm run build</code> linter warnings are not checked by default. Like <code>npm test</code>, you can force the build to perform a linter warning check by setting the environment variable <code>CI</code>. If any warnings are encountered then the build fails.</p>
<p>Popular CI servers already set the environment variable <code>CI</code> by default but you can do this yourself too:</p>
<h3><a id="user-content-on-ci-servers" class="anchor" aria-hidden="true" href="#on-ci-servers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>On CI servers</h3>
<h4><a id="user-content-travis-ci" class="anchor" aria-hidden="true" href="#travis-ci"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Travis CI</h4>
<ol>
<li>Following the <a href="https://docs.travis-ci.com/user/getting-started/" rel="nofollow">Travis Getting started</a> guide for syncing your GitHub repository with Travis.  You may need to initialize some settings manually in your <a href="https://travis-ci.org/profile" rel="nofollow">profile</a> page.</li>
<li>Add a <code>.travis.yml</code> file to your git repository.</li>
</ol>
<pre><code>language: node_js
node_js:
  - 6
cache:
  directories:
    - node_modules
script:
  - npm run build
  - npm test
</code></pre>
<ol>
<li>Trigger your first build with a git push.</li>
<li><a href="https://docs.travis-ci.com/user/customizing-the-build/" rel="nofollow">Customize your Travis CI Build</a> if needed.</li>
</ol>
<h4><a id="user-content-circleci" class="anchor" aria-hidden="true" href="#circleci"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>CircleCI</h4>
<p>Follow <a href="https://medium.com/@knowbody/circleci-and-zeits-now-sh-c9b7eebcd3c1" rel="nofollow">this article</a> to set up CircleCI with a Create React App project.</p>
<h3><a id="user-content-on-your-own-environment" class="anchor" aria-hidden="true" href="#on-your-own-environment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>On your own environment</h3>
<h5><a id="user-content-windows-cmdexe-2" class="anchor" aria-hidden="true" href="#windows-cmdexe-2"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows (cmd.exe)</h5>
<div class="highlight highlight-source-batchfile"><pre><span class="pl-k">set</span> <span class="pl-smi">CI</span><span class="pl-k">=</span>true<span class="pl-k">&amp;&amp;</span>npm test</pre></div>
<div class="highlight highlight-source-batchfile"><pre><span class="pl-k">set</span> <span class="pl-smi">CI</span><span class="pl-k">=</span>true<span class="pl-k">&amp;&amp;</span>npm run build</pre></div>
<p>(Note: the lack of whitespace is intentional.)</p>
<h5><a id="user-content-windows-powershell-2" class="anchor" aria-hidden="true" href="#windows-powershell-2"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows (Powershell)</h5>
<div class="highlight highlight-source-powershell"><pre>(<span class="pl-smi">$<span class="pl-c1">env:</span>CI</span> <span class="pl-k">=</span> <span class="pl-c1">$true</span>) <span class="pl-k">-and</span> (npm test)</pre></div>
<div class="highlight highlight-source-powershell"><pre>(<span class="pl-smi">$<span class="pl-c1">env:</span>CI</span> <span class="pl-k">=</span> <span class="pl-c1">$true</span>) <span class="pl-k">-and</span> (npm run build)</pre></div>
<h5><a id="user-content-linux-macos-bash-2" class="anchor" aria-hidden="true" href="#linux-macos-bash-2"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Linux, macOS (Bash)</h5>
<div class="highlight highlight-source-shell"><pre>CI=true npm <span class="pl-c1">test</span></pre></div>
<div class="highlight highlight-source-shell"><pre>CI=true npm run build</pre></div>
<p>The test command will force Jest to run tests once instead of launching the watcher.</p>
<blockquote>
<p>If you find yourself doing this often in development, please <a href="https://github.com/facebookincubator/create-react-app/issues/new">file an issue</a> to tell us about your use case because we want to make watcher the best experience and are open to changing how it works to accommodate more workflows.</p>
</blockquote>
<p>The build command will check for linter warnings and fail if any are found.</p>
<h3><a id="user-content-disabling-jsdom" class="anchor" aria-hidden="true" href="#disabling-jsdom"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Disabling jsdom</h3>
<p>By default, the <code>package.json</code> of the generated project looks like this:</p>
<div class="highlight highlight-source-js"><pre>  <span class="pl-s"><span class="pl-pds">"</span>scripts<span class="pl-pds">"</span></span><span class="pl-k">:</span> {
    <span class="pl-s"><span class="pl-pds">"</span>start<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>react-scripts start<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>build<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>react-scripts build<span class="pl-pds">"</span></span>,
    <span class="pl-s"><span class="pl-pds">"</span>test<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>react-scripts test --env=jsdom<span class="pl-pds">"</span></span></pre></div>
<p>If you know that none of your tests depend on <a href="https://github.com/tmpvar/jsdom">jsdom</a>, you can safely remove <code>--env=jsdom</code>, and your tests will run faster:</p>
<div class="highlight highlight-source-diff"><pre>  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
<span class="pl-md"><span class="pl-md">-</span>   "test": "react-scripts test --env=jsdom"</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>   "test": "react-scripts test"</span></pre></div>
<p>To help you make up your mind, here is a list of APIs that <strong>need jsdom</strong>:</p>
<ul>
<li>Any browser globals like <code>window</code> and <code>document</code></li>
<li><a href="https://facebook.github.io/react/docs/top-level-api.html#reactdom.render" rel="nofollow"><code>ReactDOM.render()</code></a></li>
<li><a href="https://facebook.github.io/react/docs/test-utils.html#renderintodocument" rel="nofollow"><code>TestUtils.renderIntoDocument()</code></a> (<a href="https://github.com/facebook/react/blob/34761cf9a252964abfaab6faf74d473ad95d1f21/src/test/ReactTestUtils.js#L83-L91">a shortcut</a> for the above)</li>
<li><a href="http://airbnb.io/enzyme/docs/api/mount.html" rel="nofollow"><code>mount()</code></a> in <a href="http://airbnb.io/enzyme/index.html" rel="nofollow">Enzyme</a></li>
</ul>
<p>In contrast, <strong>jsdom is not needed</strong> for the following APIs:</p>
<ul>
<li><a href="https://facebook.github.io/react/docs/test-utils.html#shallow-rendering" rel="nofollow"><code>TestUtils.createRenderer()</code></a> (shallow rendering)</li>
<li><a href="http://airbnb.io/enzyme/docs/api/shallow.html" rel="nofollow"><code>shallow()</code></a> in <a href="http://airbnb.io/enzyme/index.html" rel="nofollow">Enzyme</a></li>
</ul>
<p>Finally, jsdom is also not needed for <a href="http://facebook.github.io/jest/blog/2016/07/27/jest-14.html" rel="nofollow">snapshot testing</a>.</p>
<h3><a id="user-content-snapshot-testing" class="anchor" aria-hidden="true" href="#snapshot-testing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Snapshot Testing</h3>
<p>Snapshot testing is a feature of Jest that automatically generates text snapshots of your components and saves them on the disk so if the UI output changes, you get notified without manually writing any assertions on the component output. <a href="http://facebook.github.io/jest/blog/2016/07/27/jest-14.html" rel="nofollow">Read more about snapshot testing.</a></p>
<h3><a id="user-content-editor-integration" class="anchor" aria-hidden="true" href="#editor-integration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Editor Integration</h3>
<p>If you use <a href="https://code.visualstudio.com" rel="nofollow">Visual Studio Code</a>, there is a <a href="https://github.com/orta/vscode-jest">Jest extension</a> which works with Create React App out of the box. This provides a lot of IDE-like features while using a text editor: showing the status of a test run with potential fail messages inline, starting and stopping the watcher automatically, and offering one-click snapshot updates.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://cloud.githubusercontent.com/assets/49038/20795349/a032308a-b7c8-11e6-9b34-7eeac781003f.png"><img src="https://cloud.githubusercontent.com/assets/49038/20795349/a032308a-b7c8-11e6-9b34-7eeac781003f.png" alt="VS Code Jest Preview" style="max-width:100%;"></a></p>
<h2><a id="user-content-debugging-tests" class="anchor" aria-hidden="true" href="#debugging-tests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Debugging Tests</h2>
<p>There are various ways to setup a debugger for your Jest tests. We cover debugging in Chrome and <a href="https://code.visualstudio.com/" rel="nofollow">Visual Studio Code</a>.</p>
<blockquote>
<p>Note: debugging tests requires Node 8 or higher.</p>
</blockquote>
<h3><a id="user-content-debugging-tests-in-chrome" class="anchor" aria-hidden="true" href="#debugging-tests-in-chrome"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Debugging Tests in Chrome</h3>
<p>Add the following to the <code>scripts</code> section in your project's <code>package.json</code></p>
<div class="highlight highlight-source-json"><pre><span class="pl-s"><span class="pl-pds">"</span>scripts<span class="pl-pds">"</span></span>: {
    <span class="pl-s"><span class="pl-pds">"</span>test:debug<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>react-scripts --inspect-brk test --runInBand --env=jsdom<span class="pl-pds">"</span></span>
  }</pre></div>
<p>Place <code>debugger;</code> statements in any test and run:</p>
<div class="highlight highlight-source-shell"><pre>$ npm run test:debug</pre></div>
<p>This will start running your Jest tests, but pause before executing to allow a debugger to attach to the process.</p>
<p>Open the following in Chrome</p>
<pre><code>about:inspect
</code></pre>
<p>After opening that link, the Chrome Developer Tools will be displayed. Select <code>inspect</code> on your process and a breakpoint will be set at the first line of the react script (this is done simply to give you time to open the developer tools and to prevent Jest from executing before you have time to do so). Click the button that looks like a "play" button in the upper right hand side of the screen to continue execution. When Jest executes the test that contains the debugger statement, execution will pause and you can examine the current scope and call stack.</p>
<blockquote>
<p>Note: the --runInBand cli option makes sure Jest runs test in the same process rather than spawning processes for individual tests. Normally Jest parallelizes test runs across processes but it is hard to debug many processes at the same time.</p>
</blockquote>
<h3><a id="user-content-debugging-tests-in-visual-studio-code" class="anchor" aria-hidden="true" href="#debugging-tests-in-visual-studio-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Debugging Tests in Visual Studio Code</h3>
<p>Debugging Jest tests is supported out of the box for <a href="https://code.visualstudio.com" rel="nofollow">Visual Studio Code</a>.</p>
<p>Use the following <a href="https://code.visualstudio.com/docs/editor/debugging#_launch-configurations" rel="nofollow"><code>launch.json</code></a> configuration file:</p>
<pre><code>{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "Debug CRA Tests",
      "type": "node",
      "request": "launch",
      "runtimeExecutable": "${workspaceRoot}/node_modules/.bin/react-scripts",      
      "args": [
        "test",
        "--runInBand",
        "--no-cache",
        "--env=jsdom"
      ],
      "cwd": "${workspaceRoot}",
      "protocol": "inspector",
      "console": "integratedTerminal",
      "internalConsoleOptions": "neverOpen"
    }
  ]
}
</code></pre>
<h2><a id="user-content-developing-components-in-isolation" class="anchor" aria-hidden="true" href="#developing-components-in-isolation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Developing Components in Isolation</h2>
<p>Usually, in an app, you have a lot of UI components, and each of them has many different states.
For an example, a simple button component could have following states:</p>
<ul>
<li>In a regular state, with a text label.</li>
<li>In the disabled mode.</li>
<li>In a loading state.</li>
</ul>
<p>Usually, it’s hard to see these states without running a sample app or some examples.</p>
<p>Create React App doesn’t include any tools for this by default, but you can easily add <a href="https://storybook.js.org" rel="nofollow">Storybook for React</a> (<a href="https://github.com/storybooks/storybook">source</a>) or <a href="https://react-styleguidist.js.org/" rel="nofollow">React Styleguidist</a> (<a href="https://github.com/styleguidist/react-styleguidist">source</a>) to your project. <strong>These are third-party tools that let you develop components and see all their states in isolation from your app</strong>.</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/afa6a5df98c90ddb6b23b0fe6fba6b75c96f42b7/687474703a2f2f692e696d6775722e636f6d2f374349415770422e676966"><img src="https://camo.githubusercontent.com/afa6a5df98c90ddb6b23b0fe6fba6b75c96f42b7/687474703a2f2f692e696d6775722e636f6d2f374349415770422e676966" alt="Storybook for React Demo" data-canonical-src="http://i.imgur.com/7CIAWpB.gif" style="max-width:100%;"></a></p>
<p>You can also deploy your Storybook or style guide as a static app. This way, everyone in your team can view and review different states of UI components without starting a backend server or creating an account in your app.</p>
<h3><a id="user-content-getting-started-with-storybook" class="anchor" aria-hidden="true" href="#getting-started-with-storybook"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting Started with Storybook</h3>
<p>Storybook is a development environment for React UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.</p>
<p>First, install the following npm package globally:</p>
<div class="highlight highlight-source-shell"><pre>npm install -g @storybook/cli</pre></div>
<p>Then, run the following command inside your app’s directory:</p>
<div class="highlight highlight-source-shell"><pre>getstorybook</pre></div>
<p>After that, follow the instructions on the screen.</p>
<p>Learn more about React Storybook:</p>
<ul>
<li>Screencast: <a href="https://egghead.io/lessons/react-getting-started-with-react-storybook" rel="nofollow">Getting Started with React Storybook</a></li>
<li><a href="https://github.com/storybooks/storybook">GitHub Repo</a></li>
<li><a href="https://storybook.js.org/basics/introduction/" rel="nofollow">Documentation</a></li>
<li><a href="https://github.com/storybooks/storybook/tree/master/addons/storyshots">Snapshot Testing UI</a> with Storybook + addon/storyshot</li>
</ul>
<h3><a id="user-content-getting-started-with-styleguidist" class="anchor" aria-hidden="true" href="#getting-started-with-styleguidist"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting Started with Styleguidist</h3>
<p>Styleguidist combines a style guide, where all your components are presented on a single page with their props documentation and usage examples, with an environment for developing components in isolation, similar to Storybook. In Styleguidist you write examples in Markdown, where each code snippet is rendered as a live editable playground.</p>
<p>First, install Styleguidist:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save react-styleguidist</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add react-styleguidist</pre></div>
<p>Then, add these scripts to your <code>package.json</code>:</p>
<div class="highlight highlight-source-diff"><pre>   "scripts": {
<span class="pl-mi1"><span class="pl-mi1">+</span>    "styleguide": "styleguidist server",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>    "styleguide:build": "styleguidist build",</span>
     "start": "react-scripts start",</pre></div>
<p>Then, run the following command inside your app’s directory:</p>
<div class="highlight highlight-source-shell"><pre>npm run styleguide</pre></div>
<p>After that, follow the instructions on the screen.</p>
<p>Learn more about React Styleguidist:</p>
<ul>
<li><a href="https://github.com/styleguidist/react-styleguidist">GitHub Repo</a></li>
<li><a href="https://react-styleguidist.js.org/docs/getting-started.html" rel="nofollow">Documentation</a></li>
</ul>
<h2><a id="user-content-publishing-components-to-npm" class="anchor" aria-hidden="true" href="#publishing-components-to-npm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Publishing Components to npm</h2>
<p>Create React App doesn't provide any built-in functionality to publish a component to npm. If you're ready to extract a component from your project so other people can use it, we recommend moving it to a separate directory outside of your project and then using a tool like <a href="https://github.com/insin/nwb#react-components-and-libraries">nwb</a> to prepare it for publishing.</p>
<h2><a id="user-content-making-a-progressive-web-app" class="anchor" aria-hidden="true" href="#making-a-progressive-web-app"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Making a Progressive Web App</h2>
<p>By default, the production build is a fully functional, offline-first
<a href="https://developers.google.com/web/progressive-web-apps/" rel="nofollow">Progressive Web App</a>.</p>
<p>Progressive Web Apps are faster and more reliable than traditional web pages, and provide an engaging mobile experience:</p>
<ul>
<li>All static site assets are cached so that your page loads fast on subsequent visits, regardless of network connectivity (such as 2G or 3G). Updates are downloaded in the background.</li>
<li>Your app will work regardless of network state, even if offline. This means your users will be able to use your app at 10,000 feet and on the subway.</li>
<li>On mobile devices, your app can be added directly to the user's home screen, app icon and all. You can also re-engage users using web <strong>push notifications</strong>. This eliminates the need for the app store.</li>
</ul>
<p>The <a href="https://github.com/goldhand/sw-precache-webpack-plugin"><code>sw-precache-webpack-plugin</code></a>
is integrated into production configuration,
and it will take care of generating a service worker file that will automatically
precache all of your local assets and keep them up to date as you deploy updates.
The service worker will use a <a href="https://developers.google.com/web/fundamentals/instant-and-offline/offline-cookbook/#cache-falling-back-to-network" rel="nofollow">cache-first strategy</a>
for handling all requests for local assets, including the initial HTML, ensuring
that your web app is reliably fast, even on a slow or unreliable network.</p>
<h3><a id="user-content-opting-out-of-caching" class="anchor" aria-hidden="true" href="#opting-out-of-caching"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Opting Out of Caching</h3>
<p>If you would prefer not to enable service workers prior to your initial
production deployment, then remove the call to <code>registerServiceWorker()</code>
from <a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/src/index.js"><code>src/index.js</code></a>.</p>
<p>If you had previously enabled service workers in your production deployment and
have decided that you would like to disable them for all your existing users,
you can swap out the call to <code>registerServiceWorker()</code> in
<a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/src/index.js"><code>src/index.js</code></a> first by modifying the service worker import:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> { <span class="pl-smi">unregister</span> } <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>./registerServiceWorker<span class="pl-pds">'</span></span>;</pre></div>
<p>and then call <code>unregister()</code> instead.
After the user visits a page that has <code>unregister()</code>,
the service worker will be uninstalled. Note that depending on how <code>/service-worker.js</code> is served,
it may take up to 24 hours for the cache to be invalidated.</p>
<h3><a id="user-content-offline-first-considerations" class="anchor" aria-hidden="true" href="#offline-first-considerations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Offline-First Considerations</h3>
<ol>
<li>
<p>Service workers <a href="https://developers.google.com/web/fundamentals/getting-started/primers/service-workers#you_need_https" rel="nofollow">require HTTPS</a>,
although to facilitate local testing, that policy
<a href="http://stackoverflow.com/questions/34160509/options-for-testing-service-workers-via-http/34161385#34161385" rel="nofollow">does not apply to <code>localhost</code></a>.
If your production web server does not support HTTPS, then the service worker
registration will fail, but the rest of your web app will remain functional.</p>
</li>
<li>
<p>Service workers are <a href="https://jakearchibald.github.io/isserviceworkerready/" rel="nofollow">not currently supported</a>
in all web browsers. Service worker registration <a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/src/registerServiceWorker.js">won't be attempted</a>
on browsers that lack support.</p>
</li>
<li>
<p>The service worker is only enabled in the <a href="#deployment">production environment</a>,
e.g. the output of <code>npm run build</code>. It's recommended that you do not enable an
offline-first service worker in a development environment, as it can lead to
frustration when previously cached assets are used and do not include the latest
changes you've made locally.</p>
</li>
<li>
<p>If you <em>need</em> to test your offline-first service worker locally, build
the application (using <code>npm run build</code>) and run a simple http server from your
build directory. After running the build script, <code>create-react-app</code> will give
instructions for one way to test your production build locally and the <a href="#deployment">deployment instructions</a> have
instructions for using other methods. <em>Be sure to always use an
incognito window to avoid complications with your browser cache.</em></p>
</li>
<li>
<p>If possible, configure your production environment to serve the generated
<code>service-worker.js</code> <a href="http://stackoverflow.com/questions/38843970/service-worker-javascript-update-frequency-every-24-hours" rel="nofollow">with HTTP caching disabled</a>.
If that's not possible—<a href="#github-pages">GitHub Pages</a>, for instance, does not
allow you to change the default 10 minute HTTP cache lifetime—then be aware
that if you visit your production site, and then revisit again before
<code>service-worker.js</code> has expired from your HTTP cache, you'll continue to get
the previously cached assets from the service worker. If you have an immediate
need to view your updated production deployment, performing a shift-refresh
will temporarily disable the service worker and retrieve all assets from the
network.</p>
</li>
<li>
<p>Users aren't always familiar with offline-first web apps. It can be useful to
<a href="https://developers.google.com/web/fundamentals/instant-and-offline/offline-ux#inform_the_user_when_the_app_is_ready_for_offline_consumption" rel="nofollow">let the user know</a>
when the service worker has finished populating your caches (showing a "This web
app works offline!" message) and also let them know when the service worker has
fetched the latest updates that will be available the next time they load the
page (showing a "New content is available; please refresh." message). Showing
this messages is currently left as an exercise to the developer, but as a
starting point, you can make use of the logic included in <a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/src/registerServiceWorker.js"><code>src/registerServiceWorker.js</code></a>, which
demonstrates which service worker lifecycle events to listen for to detect each
scenario, and which as a default, just logs appropriate messages to the
JavaScript console.</p>
</li>
<li>
<p>By default, the generated service worker file will not intercept or cache any
cross-origin traffic, like HTTP <a href="#integrating-with-an-api-backend">API requests</a>,
images, or embeds loaded from a different domain. If you would like to use a
runtime caching strategy for those requests, you can <a href="#npm-run-eject"><code>eject</code></a>
and then configure the
<a href="https://github.com/GoogleChrome/sw-precache#runtimecaching-arrayobject"><code>runtimeCaching</code></a>
option in the <code>SWPrecacheWebpackPlugin</code> section of
<a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/config/webpack.config.prod.js"><code>webpack.config.prod.js</code></a>.</p>
</li>
</ol>
<h3><a id="user-content-progressive-web-app-metadata" class="anchor" aria-hidden="true" href="#progressive-web-app-metadata"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Progressive Web App Metadata</h3>
<p>The default configuration includes a web app manifest located at
<a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/public/manifest.json"><code>public/manifest.json</code></a>, that you can customize with
details specific to your web application.</p>
<p>When a user adds a web app to their homescreen using Chrome or Firefox on
Android, the metadata in <a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/public/manifest.json"><code>manifest.json</code></a> determines what
icons, names, and branding colors to use when the web app is displayed.
<a href="https://developers.google.com/web/fundamentals/engage-and-retain/web-app-manifest/" rel="nofollow">The Web App Manifest guide</a>
provides more context about what each field means, and how your customizations
will affect your users' experience.</p>
<h2><a id="user-content-analyzing-the-bundle-size" class="anchor" aria-hidden="true" href="#analyzing-the-bundle-size"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Analyzing the Bundle Size</h2>
<p><a href="https://www.npmjs.com/package/source-map-explorer" rel="nofollow">Source map explorer</a> analyzes
JavaScript bundles using the source maps. This helps you understand where code
bloat is coming from.</p>
<p>To add Source map explorer to a Create React App project, follow these steps:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save source-map-explorer</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add source-map-explorer</pre></div>
<p>Then in <code>package.json</code>, add the following line to <code>scripts</code>:</p>
<div class="highlight highlight-source-diff"><pre>   "scripts": {
<span class="pl-mi1"><span class="pl-mi1">+</span>    "analyze": "source-map-explorer build/static/js/main.*",</span>
     "start": "react-scripts start",
     "build": "react-scripts build",
     "test": "react-scripts test --env=jsdom",</pre></div>
<p>Then to analyze the bundle run the production build then run the analyze
script.</p>
<pre><code>npm run build
npm run analyze
</code></pre>
<h2><a id="user-content-deployment" class="anchor" aria-hidden="true" href="#deployment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Deployment</h2>
<p><code>npm run build</code> creates a <code>build</code> directory with a production build of your app. Set up your favorite HTTP server so that a visitor to your site is served <code>index.html</code>, and requests to static paths like <code>/static/js/main.&lt;hash&gt;.js</code> are served with the contents of the <code>/static/js/main.&lt;hash&gt;.js</code> file.</p>
<h3><a id="user-content-static-server" class="anchor" aria-hidden="true" href="#static-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Static Server</h3>
<p>For environments using <a href="https://nodejs.org/" rel="nofollow">Node</a>, the easiest way to handle this would be to install <a href="https://github.com/zeit/serve">serve</a> and let it handle the rest:</p>
<div class="highlight highlight-source-shell"><pre>npm install -g serve
serve -s build</pre></div>
<p>The last command shown above will serve your static site on the port <strong>5000</strong>. Like many of <a href="https://github.com/zeit/serve">serve</a>’s internal settings, the port can be adjusted using the <code>-p</code> or <code>--port</code> flags.</p>
<p>Run this command to get a full list of the options available:</p>
<div class="highlight highlight-source-shell"><pre>serve -h</pre></div>
<h3><a id="user-content-other-solutions" class="anchor" aria-hidden="true" href="#other-solutions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Other Solutions</h3>
<p>You don’t necessarily need a static server in order to run a Create React App project in production. It works just as fine integrated into an existing dynamic one.</p>
<p>Here’s a programmatic example using <a href="https://nodejs.org/" rel="nofollow">Node</a> and <a href="http://expressjs.com/" rel="nofollow">Express</a>:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-c1">express</span> <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>express<span class="pl-pds">'</span></span>);
<span class="pl-k">const</span> <span class="pl-c1">path</span> <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>path<span class="pl-pds">'</span></span>);
<span class="pl-k">const</span> <span class="pl-c1">app</span> <span class="pl-k">=</span> <span class="pl-en">express</span>();

<span class="pl-smi">app</span>.<span class="pl-en">use</span>(<span class="pl-smi">express</span>.<span class="pl-en">static</span>(<span class="pl-smi">path</span>.<span class="pl-c1">join</span>(<span class="pl-c1">__dirname</span>, <span class="pl-s"><span class="pl-pds">'</span>build<span class="pl-pds">'</span></span>)));

<span class="pl-smi">app</span>.<span class="pl-c1">get</span>(<span class="pl-s"><span class="pl-pds">'</span>/<span class="pl-pds">'</span></span>, <span class="pl-k">function</span> (<span class="pl-smi">req</span>, <span class="pl-smi">res</span>) {
  <span class="pl-smi">res</span>.<span class="pl-en">sendFile</span>(<span class="pl-smi">path</span>.<span class="pl-c1">join</span>(<span class="pl-c1">__dirname</span>, <span class="pl-s"><span class="pl-pds">'</span>build<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>index.html<span class="pl-pds">'</span></span>));
});

<span class="pl-smi">app</span>.<span class="pl-en">listen</span>(<span class="pl-c1">9000</span>);</pre></div>
<p>The choice of your server software isn’t important either. Since Create React App is completely platform-agnostic, there’s no need to explicitly use Node.</p>
<p>The <code>build</code> folder with static assets is the only output produced by Create React App.</p>
<p>However this is not quite enough if you use client-side routing. Read the next section if you want to support URLs like <code>/todos/42</code> in your single-page app.</p>
<h3><a id="user-content-serving-apps-with-client-side-routing" class="anchor" aria-hidden="true" href="#serving-apps-with-client-side-routing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Serving Apps with Client-Side Routing</h3>
<p>If you use routers that use the HTML5 <a href="https://developer.mozilla.org/en-US/docs/Web/API/History_API#Adding_and_modifying_history_entries" rel="nofollow"><code>pushState</code> history API</a> under the hood (for example, <a href="https://github.com/ReactTraining/react-router">React Router</a> with <code>browserHistory</code>), many static file servers will fail. For example, if you used React Router with a route for <code>/todos/42</code>, the development server will respond to <code>localhost:3000/todos/42</code> properly, but an Express serving a production build as above will not.</p>
<p>This is because when there is a fresh page load for a <code>/todos/42</code>, the server looks for the file <code>build/todos/42</code> and does not find it. The server needs to be configured to respond to a request to <code>/todos/42</code> by serving <code>index.html</code>. For example, we can amend our Express example above to serve <code>index.html</code> for any unknown paths:</p>
<div class="highlight highlight-source-diff"><pre> app.use(express.static(path.join(__dirname, 'build')));

<span class="pl-md"><span class="pl-md">-</span>app.get('/', function (req, res) {</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>app.get('/*', function (req, res) {</span>
   res.sendFile(path.join(__dirname, 'build', 'index.html'));
 });</pre></div>
<p>If you’re using <a href="https://httpd.apache.org/" rel="nofollow">Apache HTTP Server</a>, you need to create a <code>.htaccess</code> file in the <code>public</code> folder that looks like this:</p>
<pre><code>    Options -MultiViews
    RewriteEngine On
    RewriteCond %{REQUEST_FILENAME} !-f
    RewriteRule ^ index.html [QSA,L]
</code></pre>
<p>It will get copied to the <code>build</code> folder when you run <code>npm run build</code>.</p>
<p>If you’re using <a href="http://tomcat.apache.org/" rel="nofollow">Apache Tomcat</a>, you need to follow <a href="https://stackoverflow.com/a/41249464/4878474" rel="nofollow">this Stack Overflow answer</a>.</p>
<p>Now requests to <code>/todos/42</code> will be handled correctly both in development and in production.</p>
<p>On a production build, and in a browser that supports <a href="https://developers.google.com/web/fundamentals/getting-started/primers/service-workers" rel="nofollow">service workers</a>,
the service worker will automatically handle all navigation requests, like for
<code>/todos/42</code>, by serving the cached copy of your <code>index.html</code>. This
service worker navigation routing can be configured or disabled by
<a href="#npm-run-eject"><code>eject</code>ing</a> and then modifying the
<a href="https://github.com/GoogleChrome/sw-precache#navigatefallback-string"><code>navigateFallback</code></a>
and <a href="https://github.com/GoogleChrome/sw-precache#navigatefallbackwhitelist-arrayregexp"><code>navigateFallbackWhitelist</code></a>
options of the <code>SWPreachePlugin</code> <a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/config/webpack.config.prod.js">configuration</a>.</p>
<p>When users install your app to the homescreen of their device the default configuration will make a shortcut to <code>/index.html</code>. This may not work for client-side routers which expect the app to be served from <code>/</code>. Edit the web app manifest at <a href="/haochuan/react-fundamental/blob/master/examples/connect-with-express/frontend/public/manifest.json"><code>public/manifest.json</code></a> and change <code>start_url</code> to match the required URL scheme, for example:</p>
<div class="highlight highlight-source-js"><pre>  <span class="pl-s"><span class="pl-pds">"</span>start_url<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>.<span class="pl-pds">"</span></span>,</pre></div>
<h3><a id="user-content-building-for-relative-paths" class="anchor" aria-hidden="true" href="#building-for-relative-paths"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Building for Relative Paths</h3>
<p>By default, Create React App produces a build assuming your app is hosted at the server root.<br>
To override this, specify the <code>homepage</code> in your <code>package.json</code>, for example:</p>
<div class="highlight highlight-source-js"><pre>  <span class="pl-s"><span class="pl-pds">"</span>homepage<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>http://mywebsite.com/relativepath<span class="pl-pds">"</span></span>,</pre></div>
<p>This will let Create React App correctly infer the root path to use in the generated HTML file.</p>
<p><strong>Note</strong>: If you are using <code>react-router@^4</code>, you can root <code>&lt;Link&gt;</code>s using the <code>basename</code> prop on any <code>&lt;Router&gt;</code>.<br>
More information <a href="https://reacttraining.com/react-router/web/api/BrowserRouter/basename-string" rel="nofollow">here</a>.<br>
<br>
For example:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">&lt;</span>BrowserRouter basename<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>/calendar<span class="pl-pds">"</span></span><span class="pl-k">/</span><span class="pl-k">&gt;</span>
<span class="pl-k">&lt;</span>Link to<span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>/today<span class="pl-pds">"</span></span><span class="pl-k">/</span><span class="pl-k">&gt;</span> <span class="pl-c"><span class="pl-c">//</span> renders &lt;a href="/calendar/today"&gt;</span></pre></div>
<h4><a id="user-content-serving-the-same-build-from-different-paths" class="anchor" aria-hidden="true" href="#serving-the-same-build-from-different-paths"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Serving the Same Build from Different Paths</h4>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.9.0</code> and higher.</p>
</blockquote>
<p>If you are not using the HTML5 <code>pushState</code> history API or not using client-side routing at all, it is unnecessary to specify the URL from which your app will be served. Instead, you can put this in your <code>package.json</code>:</p>
<div class="highlight highlight-source-js"><pre>  <span class="pl-s"><span class="pl-pds">"</span>homepage<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>.<span class="pl-pds">"</span></span>,</pre></div>
<p>This will make sure that all the asset paths are relative to <code>index.html</code>. You will then be able to move your app from <code>http://mywebsite.com</code> to <code>http://mywebsite.com/relativepath</code> or even <code>http://mywebsite.com/relative/path</code> without having to rebuild it.</p>
<h3><a id="user-content-azure" class="anchor" aria-hidden="true" href="#azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://azure.microsoft.com/" rel="nofollow">Azure</a></h3>
<p>See <a href="https://medium.com/@to_pe/deploying-create-react-app-on-microsoft-azure-c0f6686a4321" rel="nofollow">this</a> blog post on how to deploy your React app to Microsoft Azure.</p>
<p>See <a href="https://medium.com/@strid/host-create-react-app-on-azure-986bc40d5bf2#.pycfnafbg" rel="nofollow">this</a> blog post or <a href="https://github.com/ulrikaugustsson/azure-appservice-static">this</a> repo for a way to use automatic deployment to Azure App Service.</p>
<h3><a id="user-content-firebase" class="anchor" aria-hidden="true" href="#firebase"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://firebase.google.com/" rel="nofollow">Firebase</a></h3>
<p>Install the Firebase CLI if you haven’t already by running <code>npm install -g firebase-tools</code>. Sign up for a <a href="https://console.firebase.google.com/" rel="nofollow">Firebase account</a> and create a new project. Run <code>firebase login</code> and login with your previous created Firebase account.</p>
<p>Then run the <code>firebase init</code> command from your project’s root. You need to choose the <strong>Hosting: Configure and deploy Firebase Hosting sites</strong> and choose the Firebase project you created in the previous step. You will need to agree with <code>database.rules.json</code> being created, choose <code>build</code> as the public directory, and also agree to <strong>Configure as a single-page app</strong> by replying with <code>y</code>.</p>
<div class="highlight highlight-source-shell"><pre>    === Project Setup

    First, let<span class="pl-s"><span class="pl-pds">'</span>s associate this project directory with a Firebase project.</span>
<span class="pl-s">    You can create multiple project aliases by running firebase use --add,</span>
<span class="pl-s">    but for now we<span class="pl-pds">'</span></span>ll just <span class="pl-c1">set</span> up a default project.

    <span class="pl-k">?</span> What Firebase project <span class="pl-k">do</span> you want to associate as default<span class="pl-k">?</span> Example app (example-app-fd690)

    === Database Setup

    Firebase Realtime Database Rules allow you to define how your data should be
    structured and when your data can be <span class="pl-c1">read</span> from and written to.

    <span class="pl-k">?</span> What file should be used <span class="pl-k">for</span> Database Rules<span class="pl-k">?</span> database.rules.json
    ✔  Database Rules <span class="pl-k">for</span> example-app-fd690 have been downloaded to database.rules.json.
    Future modifications to database.rules.json will update Database Rules when you run
    firebase deploy.

    === Hosting Setup

    Your public directory is the folder (relative to your project directory) that
    will contain Hosting assets to uploaded with firebase deploy. If you
    have a build process <span class="pl-k">for</span> your assets, use your build<span class="pl-s"><span class="pl-pds">'</span>s output directory.</span>
<span class="pl-s"></span>
<span class="pl-s">    ? What do you want to use as your public directory? build</span>
<span class="pl-s">    ? Configure as a single-page app (rewrite all urls to /index.html)? Yes</span>
<span class="pl-s">    ✔  Wrote build/index.html</span>
<span class="pl-s"></span>
<span class="pl-s">    i  Writing configuration info to firebase.json...</span>
<span class="pl-s">    i  Writing project information to .firebaserc...</span>
<span class="pl-s"></span>
<span class="pl-s">    ✔  Firebase initialization complete!</span></pre></div>
<p>IMPORTANT: you need to set proper HTTP caching headers for <code>service-worker.js</code> file in <code>firebase.json</code> file or you will not be able to see changes after first deployment (<a href="https://github.com/facebookincubator/create-react-app/issues/2440">issue #2440</a>). It should be added inside <code>"hosting"</code> key like next:</p>
<pre><code>{
  "hosting": {
    ...
    "headers": [
      {"source": "/service-worker.js", "headers": [{"key": "Cache-Control", "value": "no-cache"}]}
    ]
    ...
</code></pre>
<p>Now, after you create a production build with <code>npm run build</code>, you can deploy it by running <code>firebase deploy</code>.</p>
<div class="highlight highlight-source-shell"><pre>    === Deploying to <span class="pl-s"><span class="pl-pds">'</span>example-app-fd690<span class="pl-pds">'</span></span>...

    i  deploying database, hosting
    ✔  database: rules ready to deploy.
    i  hosting: preparing build directory <span class="pl-k">for</span> upload...
    Uploading: [<span class="pl-k">==============================</span>          ] 75%✔  hosting: build folder uploaded successfully
    ✔  hosting: 8 files uploaded successfully
    i  starting release process (may take several minutes)...

    ✔  Deploy complete<span class="pl-k">!</span>

    Project Console: https://console.firebase.google.com/project/example-app-fd690/overview
    Hosting URL: https://example-app-fd690.firebaseapp.com</pre></div>
<p>For more information see <a href="https://firebase.google.com/docs/web/setup" rel="nofollow">Add Firebase to your JavaScript Project</a>.</p>
<h3><a id="user-content-github-pages" class="anchor" aria-hidden="true" href="#github-pages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://pages.github.com/">GitHub Pages</a></h3>
<blockquote>
<p>Note: this feature is available with <code>react-scripts@0.2.0</code> and higher.</p>
</blockquote>
<h4><a id="user-content-step-1-add-homepage-to-packagejson" class="anchor" aria-hidden="true" href="#step-1-add-homepage-to-packagejson"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 1: Add <code>homepage</code> to <code>package.json</code></h4>
<p><strong>The step below is important!</strong><br>
<strong>If you skip it, your app will not deploy correctly.</strong></p>
<p>Open your <code>package.json</code> and add a <code>homepage</code> field for your project:</p>
<div class="highlight highlight-source-json"><pre>  <span class="pl-s"><span class="pl-pds">"</span>homepage<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://myusername.github.io/my-app<span class="pl-pds">"</span></span>,</pre></div>
<p>or for a GitHub user page:</p>
<div class="highlight highlight-source-json"><pre>  <span class="pl-s"><span class="pl-pds">"</span>homepage<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://myusername.github.io<span class="pl-pds">"</span></span>,</pre></div>
<p>Create React App uses the <code>homepage</code> field to determine the root URL in the built HTML file.</p>
<h4><a id="user-content-step-2-install-gh-pages-and-add-deploy-to-scripts-in-packagejson" class="anchor" aria-hidden="true" href="#step-2-install-gh-pages-and-add-deploy-to-scripts-in-packagejson"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 2: Install <code>gh-pages</code> and add <code>deploy</code> to <code>scripts</code> in <code>package.json</code></h4>
<p>Now, whenever you run <code>npm run build</code>, you will see a cheat sheet with instructions on how to deploy to GitHub Pages.</p>
<p>To publish it at <a href="https://myusername.github.io/my-app" rel="nofollow">https://myusername.github.io/my-app</a>, run:</p>
<div class="highlight highlight-source-shell"><pre>npm install --save gh-pages</pre></div>
<p>Alternatively you may use <code>yarn</code>:</p>
<div class="highlight highlight-source-shell"><pre>yarn add gh-pages</pre></div>
<p>Add the following scripts in your <code>package.json</code>:</p>
<div class="highlight highlight-source-diff"><pre>  "scripts": {
<span class="pl-mi1"><span class="pl-mi1">+</span>   "predeploy": "npm run build",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>   "deploy": "gh-pages -d build",</span>
    "start": "react-scripts start",
    "build": "react-scripts build",</pre></div>
<p>The <code>predeploy</code> script will run automatically before <code>deploy</code> is run.</p>
<p>If you are deploying to a GitHub user page instead of a project page you'll need to make two
additional modifications:</p>
<ol>
<li>First, change your repository's source branch to be any branch other than <strong>master</strong>.</li>
<li>Additionally, tweak your <code>package.json</code> scripts to push deployments to <strong>master</strong>:</li>
</ol>
<div class="highlight highlight-source-diff"><pre>  "scripts": {
    "predeploy": "npm run build",
<span class="pl-md"><span class="pl-md">-</span>   "deploy": "gh-pages -d build",</span>
<span class="pl-mi1"><span class="pl-mi1">+</span>   "deploy": "gh-pages -b master -d build",</span></pre></div>
<h4><a id="user-content-step-3-deploy-the-site-by-running-npm-run-deploy" class="anchor" aria-hidden="true" href="#step-3-deploy-the-site-by-running-npm-run-deploy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 3: Deploy the site by running <code>npm run deploy</code></h4>
<p>Then run:</p>
<div class="highlight highlight-source-shell"><pre>npm run deploy</pre></div>
<h4><a id="user-content-step-4-ensure-your-projects-settings-use-gh-pages" class="anchor" aria-hidden="true" href="#step-4-ensure-your-projects-settings-use-gh-pages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 4: Ensure your project’s settings use <code>gh-pages</code></h4>
<p>Finally, make sure <strong>GitHub Pages</strong> option in your GitHub project settings is set to use the <code>gh-pages</code> branch:</p>
<p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/22aef6d3f95d8cfe08317f11b161eb9e8c1a6a65/687474703a2f2f692e696d6775722e636f6d2f48556a4572396c2e706e67"><img src="https://camo.githubusercontent.com/22aef6d3f95d8cfe08317f11b161eb9e8c1a6a65/687474703a2f2f692e696d6775722e636f6d2f48556a4572396c2e706e67" width="500" alt="gh-pages branch setting" data-canonical-src="http://i.imgur.com/HUjEr9l.png" style="max-width:100%;"></a></p>
<h4><a id="user-content-step-5-optionally-configure-the-domain" class="anchor" aria-hidden="true" href="#step-5-optionally-configure-the-domain"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 5: Optionally, configure the domain</h4>
<p>You can configure a custom domain with GitHub Pages by adding a <code>CNAME</code> file to the <code>public/</code> folder.</p>
<h4><a id="user-content-notes-on-client-side-routing" class="anchor" aria-hidden="true" href="#notes-on-client-side-routing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Notes on client-side routing</h4>
<p>GitHub Pages doesn’t support routers that use the HTML5 <code>pushState</code> history API under the hood (for example, React Router using <code>browserHistory</code>). This is because when there is a fresh page load for a url like <code>http://user.github.io/todomvc/todos/42</code>, where <code>/todos/42</code> is a frontend route, the GitHub Pages server returns 404 because it knows nothing of <code>/todos/42</code>. If you want to add a router to a project hosted on GitHub Pages, here are a couple of solutions:</p>
<ul>
<li>You could switch from using HTML5 history API to routing with hashes. If you use React Router, you can switch to <code>hashHistory</code> for this effect, but the URL will be longer and more verbose (for example, <code>http://user.github.io/todomvc/#/todos/42?_k=yknaj</code>). <a href="https://reacttraining.com/react-router/web/api/Router" rel="nofollow">Read more</a> about different history implementations in React Router.</li>
<li>Alternatively, you can use a trick to teach GitHub Pages to handle 404 by redirecting to your <code>index.html</code> page with a special redirect parameter. You would need to add a <code>404.html</code> file with the redirection code to the <code>build</code> folder before deploying your project, and you’ll need to add code handling the redirect parameter to <code>index.html</code>. You can find a detailed explanation of this technique <a href="https://github.com/rafrex/spa-github-pages">in this guide</a>.</li>
</ul>
<h4><a id="user-content-troubleshooting" class="anchor" aria-hidden="true" href="#troubleshooting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Troubleshooting</h4>
<h5><a id="user-content-devtty-no-such-a-device-or-address" class="anchor" aria-hidden="true" href="#devtty-no-such-a-device-or-address"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>"/dev/tty: No such a device or address"</h5>
<p>If, when deploying, you get <code>/dev/tty: No such a device or address</code> or a similar error, try the follwing:</p>
<ol>
<li>Create a new <a href="https://github.com/settings/tokens">Personal Access Token</a></li>
<li><code>git remote set-url origin https://&lt;user&gt;:&lt;token&gt;@github.com/&lt;user&gt;/&lt;repo&gt;</code> .</li>
<li>Try <code>npm run deploy again</code></li>
</ol>
<h3><a id="user-content-heroku" class="anchor" aria-hidden="true" href="#heroku"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://www.heroku.com/" rel="nofollow">Heroku</a></h3>
<p>Use the <a href="https://github.com/mars/create-react-app-buildpack">Heroku Buildpack for Create React App</a>.<br>
You can find instructions in <a href="https://blog.heroku.com/deploying-react-with-zero-configuration" rel="nofollow">Deploying React with Zero Configuration</a>.</p>
<h4><a id="user-content-resolving-heroku-deployment-errors" class="anchor" aria-hidden="true" href="#resolving-heroku-deployment-errors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Resolving Heroku Deployment Errors</h4>
<p>Sometimes <code>npm run build</code> works locally but fails during deploy via Heroku. Following are the most common cases.</p>
<h5><a id="user-content-module-not-found-error-cannot-resolve-file-or-directory" class="anchor" aria-hidden="true" href="#module-not-found-error-cannot-resolve-file-or-directory"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>"Module not found: Error: Cannot resolve 'file' or 'directory'"</h5>
<p>If you get something like this:</p>
<pre><code>remote: Failed to create a production build. Reason:
remote: Module not found: Error: Cannot resolve 'file' or 'directory'
MyDirectory in /tmp/build_1234/src
</code></pre>
<p>It means you need to ensure that the lettercase of the file or directory you <code>import</code> matches the one you see on your filesystem or on GitHub.</p>
<p>This is important because Linux (the operating system used by Heroku) is case sensitive. So <code>MyDirectory</code> and <code>mydirectory</code> are two distinct directories and thus, even though the project builds locally, the difference in case breaks the <code>import</code> statements on Heroku remotes.</p>
<h5><a id="user-content-could-not-find-a-required-file" class="anchor" aria-hidden="true" href="#could-not-find-a-required-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>"Could not find a required file."</h5>
<p>If you exclude or ignore necessary files from the package you will see a error similar this one:</p>
<pre><code>remote: Could not find a required file.
remote:   Name: `index.html`
remote:   Searched in: /tmp/build_a2875fc163b209225122d68916f1d4df/public
remote:
remote: npm ERR! Linux 3.13.0-105-generic
remote: npm ERR! argv "/tmp/build_a2875fc163b209225122d68916f1d4df/.heroku/node/bin/node" "/tmp/build_a2875fc163b209225122d68916f1d4df/.heroku/node/bin/npm" "run" "build"
</code></pre>
<p>In this case, ensure that the file is there with the proper lettercase and that’s not ignored on your local <code>.gitignore</code> or <code>~/.gitignore_global</code>.</p>
<h3><a id="user-content-netlify" class="anchor" aria-hidden="true" href="#netlify"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://www.netlify.com/" rel="nofollow">Netlify</a></h3>
<p><strong>To do a manual deploy to Netlify’s CDN:</strong></p>
<div class="highlight highlight-source-shell"><pre>npm install netlify-cli -g
netlify deploy</pre></div>
<p>Choose <code>build</code> as the path to deploy.</p>
<p><strong>To setup continuous delivery:</strong></p>
<p>With this setup Netlify will build and deploy when you push to git or open a pull request:</p>
<ol>
<li><a href="https://app.netlify.com/signup" rel="nofollow">Start a new netlify project</a></li>
<li>Pick your Git hosting service and select your repository</li>
<li>Set <code>yarn build</code> as the build command and <code>build</code> as the publish directory</li>
<li>Click <code>Deploy site</code></li>
</ol>
<p><strong>Support for client-side routing:</strong></p>
<p>To support <code>pushState</code>, make sure to create a <code>public/_redirects</code> file with the following rewrite rules:</p>
<pre><code>/*  /index.html  200
</code></pre>
<p>When you build the project, Create React App will place the <code>public</code> folder contents into the build output.</p>
<h3><a id="user-content-now" class="anchor" aria-hidden="true" href="#now"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://zeit.co/now" rel="nofollow">Now</a></h3>
<p>Now offers a zero-configuration single-command deployment. You can use <code>now</code> to deploy your app for free.</p>
<ol>
<li>
<p>Install the <code>now</code> command-line tool either via the recommended <a href="https://zeit.co/download" rel="nofollow">desktop tool</a> or via node with <code>npm install -g now</code>.</p>
</li>
<li>
<p>Build your app by running <code>npm run build</code>.</p>
</li>
<li>
<p>Move into the build directory by running <code>cd build</code>.</p>
</li>
<li>
<p>Run <code>now --name your-project-name</code> from within the build directory. You will see a <strong>now.sh</strong> URL in your output like this:</p>
<pre><code>&gt; Ready! https://your-project-name-tpspyhtdtk.now.sh (copied to clipboard)
</code></pre>
<p>Paste that URL into your browser when the build is complete, and you will see your deployed app.</p>
</li>
</ol>
<p>Details are available in <a href="https://zeit.co/blog/unlimited-static" rel="nofollow">this article.</a></p>
<h3><a id="user-content-s3-and-cloudfront" class="anchor" aria-hidden="true" href="#s3-and-cloudfront"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://aws.amazon.com/s3" rel="nofollow">S3</a> and <a href="https://aws.amazon.com/cloudfront/" rel="nofollow">CloudFront</a></h3>
<p>See this <a href="https://medium.com/@omgwtfmarc/deploying-create-react-app-to-s3-or-cloudfront-48dae4ce0af" rel="nofollow">blog post</a> on how to deploy your React app to Amazon Web Services S3 and CloudFront.</p>
<h3><a id="user-content-surge" class="anchor" aria-hidden="true" href="#surge"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="https://surge.sh/" rel="nofollow">Surge</a></h3>
<p>Install the Surge CLI if you haven’t already by running <code>npm install -g surge</code>. Run the <code>surge</code> command and log in you or create a new account.</p>
<p>When asked about the project path, make sure to specify the <code>build</code> folder, for example:</p>
<div class="highlight highlight-source-shell"><pre>       project path: /path/to/project/build</pre></div>
<p>Note that in order to support routers that use HTML5 <code>pushState</code> API, you may want to rename the <code>index.html</code> in your build folder to <code>200.html</code> before deploying to Surge. This <a href="https://surge.sh/help/adding-a-200-page-for-client-side-routing" rel="nofollow">ensures that every URL falls back to that file</a>.</p>
<h2><a id="user-content-advanced-configuration" class="anchor" aria-hidden="true" href="#advanced-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Advanced Configuration</h2>
<p>You can adjust various development and production settings by setting environment variables in your shell or with <a href="#adding-development-environment-variables-in-env">.env</a>.</p>
<table>
<thead>
<tr>
<th align="left">Variable</th>
<th align="center">Development</th>
<th align="center">Production</th>
<th align="left">Usage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BROWSER</td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="left">By default, Create React App will open the default system browser, favoring Chrome on macOS. Specify a <a href="https://github.com/sindresorhus/opn#app">browser</a> to override this behavior, or set it to <code>none</code> to disable it completely. If you need to customize the way the browser is launched, you can specify a node script instead. Any arguments passed to <code>npm start</code> will also be passed to this script, and the url where your app is served will be the last argument. Your script's file name must have the <code>.js</code> extension.</td>
</tr>
<tr>
<td align="left">HOST</td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="left">By default, the development web server binds to <code>localhost</code>. You may use this variable to specify a different host.</td>
</tr>
<tr>
<td align="left">PORT</td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="left">By default, the development web server will attempt to listen on port 3000 or prompt you to attempt the next available port. You may use this variable to specify a different port.</td>
</tr>
<tr>
<td align="left">HTTPS</td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="left">When set to <code>true</code>, Create React App will run the development server in <code>https</code> mode.</td>
</tr>
<tr>
<td align="left">PUBLIC_URL</td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="left">Create React App assumes your application is hosted at the serving web server's root or a subpath as specified in <a href="#building-for-relative-paths"><code>package.json</code> (<code>homepage</code>)</a>. Normally, Create React App ignores the hostname. You may use this variable to force assets to be referenced verbatim to the url you provide (hostname included). This may be particularly useful when using a CDN to host your application.</td>
</tr>
<tr>
<td align="left">CI</td>
<td align="center"><g-emoji class="g-emoji" alias="large_orange_diamond" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f536.png">🔶</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="left">When set to <code>true</code>, Create React App treats warnings as failures in the build. It also makes the test runner non-watching. Most CIs set this flag by default.</td>
</tr>
<tr>
<td align="left">REACT_EDITOR</td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="left">When an app crashes in development, you will see an error overlay with clickable stack trace. When you click on it, Create React App will try to determine the editor you are using based on currently running processes, and open the relevant source file. You can <a href="https://github.com/facebookincubator/create-react-app/issues/2636">send a pull request to detect your editor of choice</a>. Setting this environment variable overrides the automatic detection. If you do it, make sure your systems <a href="https://en.wikipedia.org/wiki/PATH_(variable)" rel="nofollow">PATH</a> environment variable points to your editor’s bin folder. You can also set it to <code>none</code> to disable it completely.</td>
</tr>
<tr>
<td align="left">CHOKIDAR_USEPOLLING</td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="left">When set to <code>true</code>, the watcher runs in polling mode, as necessary inside a VM. Use this option if <code>npm start</code> isn't detecting changes.</td>
</tr>
<tr>
<td align="left">GENERATE_SOURCEMAP</td>
<td align="center"><g-emoji class="g-emoji" alias="x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/274c.png">❌</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="left">When set to <code>false</code>, source maps are not generated for a production build. This solves OOM issues on some smaller machines.</td>
</tr>
<tr>
<td align="left">NODE_PATH</td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="center"><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji></td>
<td align="left">Same as <a href="https://nodejs.org/api/modules.html#modules_loading_from_the_global_folders" rel="nofollow"><code>NODE_PATH</code> in Node.js</a>, but only relative folders are allowed. Can be handy for emulating a monorepo setup by setting <code>NODE_PATH=src</code>.</td>
</tr>
</tbody>
</table>
<h2><a id="user-content-troubleshooting-1" class="anchor" aria-hidden="true" href="#troubleshooting-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Troubleshooting</h2>
<h3><a id="user-content-npm-start-doesnt-detect-changes" class="anchor" aria-hidden="true" href="#npm-start-doesnt-detect-changes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm start</code> doesn’t detect changes</h3>
<p>When you save a file while <code>npm start</code> is running, the browser should refresh with the updated code.<br>
If this doesn’t happen, try one of the following workarounds:</p>
<ul>
<li>If your project is in a Dropbox folder, try moving it out.</li>
<li>If the watcher doesn’t see a file called <code>index.js</code> and you’re referencing it by the folder name, you <a href="https://github.com/facebookincubator/create-react-app/issues/1164">need to restart the watcher</a> due to a Webpack bug.</li>
<li>Some editors like Vim and IntelliJ have a “safe write” feature that currently breaks the watcher. You will need to disable it. Follow the instructions in <a href="https://webpack.js.org/guides/development/#adjusting-your-text-editor" rel="nofollow">“Adjusting Your Text Editor”</a>.</li>
<li>If your project path contains parentheses, try moving the project to a path without them. This is caused by a <a href="https://github.com/webpack/watchpack/issues/42">Webpack watcher bug</a>.</li>
<li>On Linux and macOS, you might need to <a href="https://github.com/webpack/docs/wiki/troubleshooting#not-enough-watchers">tweak system settings</a> to allow more watchers.</li>
<li>If the project runs inside a virtual machine such as (a Vagrant provisioned) VirtualBox, create an <code>.env</code> file in your project directory if it doesn’t exist, and add <code>CHOKIDAR_USEPOLLING=true</code> to it. This ensures that the next time you run <code>npm start</code>, the watcher uses the polling mode, as necessary inside a VM.</li>
</ul>
<p>If none of these solutions help please leave a comment <a href="https://github.com/facebookincubator/create-react-app/issues/659">in this thread</a>.</p>
<h3><a id="user-content-npm-test-hangs-on-macos-sierra" class="anchor" aria-hidden="true" href="#npm-test-hangs-on-macos-sierra"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm test</code> hangs on macOS Sierra</h3>
<p>If you run <code>npm test</code> and the console gets stuck after printing <code>react-scripts test --env=jsdom</code> to the console there might be a problem with your <a href="https://facebook.github.io/watchman/" rel="nofollow">Watchman</a> installation as described in <a href="https://github.com/facebookincubator/create-react-app/issues/713">facebookincubator/create-react-app#713</a>.</p>
<p>We recommend deleting <code>node_modules</code> in your project and running <code>npm install</code> (or <code>yarn</code> if you use it) first. If it doesn't help, you can try one of the numerous workarounds mentioned in these issues:</p>
<ul>
<li><a href="https://github.com/facebook/jest/issues/1767">facebook/jest#1767</a></li>
<li><a href="https://github.com/facebook/watchman/issues/358">facebook/watchman#358</a></li>
<li><a href="https://github.com/ember-cli/ember-cli/issues/6259">ember-cli/ember-cli#6259</a></li>
</ul>
<p>It is reported that installing Watchman 4.7.0 or newer fixes the issue. If you use <a href="http://brew.sh/" rel="nofollow">Homebrew</a>, you can run these commands to update it:</p>
<pre><code>watchman shutdown-server
brew update
brew reinstall watchman
</code></pre>
<p>You can find <a href="https://facebook.github.io/watchman/docs/install.html#build-install" rel="nofollow">other installation methods</a> on the Watchman documentation page.</p>
<p>If this still doesn’t help, try running <code>launchctl unload -F ~/Library/LaunchAgents/com.github.facebook.watchman.plist</code>.</p>
<p>There are also reports that <em>uninstalling</em> Watchman fixes the issue. So if nothing else helps, remove it from your system and try again.</p>
<h3><a id="user-content-npm-run-build-exits-too-early" class="anchor" aria-hidden="true" href="#npm-run-build-exits-too-early"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm run build</code> exits too early</h3>
<p>It is reported that <code>npm run build</code> can fail on machines with limited memory and no swap space, which is common in cloud environments. Even with small projects this command can increase RAM usage in your system by hundreds of megabytes, so if you have less than 1 GB of available memory your build is likely to fail with the following message:</p>
<blockquote>
<p>The build failed because the process exited too early. This probably means the system ran out of memory or someone called <code>kill -9</code> on the process.</p>
</blockquote>
<p>If you are completely sure that you didn't terminate the process, consider <a href="https://www.digitalocean.com/community/tutorials/how-to-add-swap-on-ubuntu-14-04" rel="nofollow">adding some swap space</a> to the machine you’re building on, or build the project locally.</p>
<h3><a id="user-content-npm-run-build-fails-on-heroku" class="anchor" aria-hidden="true" href="#npm-run-build-fails-on-heroku"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm run build</code> fails on Heroku</h3>
<p>This may be a problem with case sensitive filenames.
Please refer to <a href="#resolving-heroku-deployment-errors">this section</a>.</p>
<h3><a id="user-content-momentjs-locales-are-missing" class="anchor" aria-hidden="true" href="#momentjs-locales-are-missing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Moment.js locales are missing</h3>
<p>If you use a <a href="https://momentjs.com/" rel="nofollow">Moment.js</a>, you might notice that only the English locale is available by default. This is because the locale files are large, and you probably only need a subset of <a href="https://momentjs.com/#multiple-locale-support" rel="nofollow">all the locales provided by Moment.js</a>.</p>
<p>To add a specific Moment.js locale to your bundle, you need to import it explicitly.<br>
For example:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">moment</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>moment<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-s"><span class="pl-pds">'</span>moment/locale/fr<span class="pl-pds">'</span></span>;</pre></div>
<p>If import multiple locales this way, you can later switch between them by calling <code>moment.locale()</code> with the locale name:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">import</span> <span class="pl-smi">moment</span> <span class="pl-k">from</span> <span class="pl-s"><span class="pl-pds">'</span>moment<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-s"><span class="pl-pds">'</span>moment/locale/fr<span class="pl-pds">'</span></span>;
<span class="pl-k">import</span> <span class="pl-s"><span class="pl-pds">'</span>moment/locale/es<span class="pl-pds">'</span></span>;

<span class="pl-c"><span class="pl-c">//</span> ...</span>

<span class="pl-smi">moment</span>.<span class="pl-en">locale</span>(<span class="pl-s"><span class="pl-pds">'</span>fr<span class="pl-pds">'</span></span>);</pre></div>
<p>This will only work for locales that have been explicitly imported before.</p>
<h3><a id="user-content-npm-run-build-fails-to-minify" class="anchor" aria-hidden="true" href="#npm-run-build-fails-to-minify"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><code>npm run build</code> fails to minify</h3>
<p>Some third-party packages don't compile their code to ES5 before publishing to npm. This often causes problems in the ecosystem because neither browsers (except for most modern versions) nor some tools currently support all ES6 features. We recommend to publish code on npm as ES5 at least for a few more years.</p>
<br>
To resolve this:
<ol>
<li>Open an issue on the dependency's issue tracker and ask that the package be published pre-compiled.</li>
</ol>
<ul>
<li>Note: Create React App can consume both CommonJS and ES modules. For Node.js compatibility, it is recommended that the main entry point is CommonJS. However, they can optionally provide an ES module entry point with the <code>module</code> field in <code>package.json</code>. Note that <strong>even if a library provides an ES Modules version, it should still precompile other ES6 features to ES5 if it intends to support older browsers</strong>.</li>
</ul>
<ol start="2">
<li>
<p>Fork the package and publish a corrected version yourself.</p>
</li>
<li>
<p>If the dependency is small enough, copy it to your <code>src/</code> folder and treat it as application code.</p>
</li>
</ol>
<p>In the future, we might start automatically compiling incompatible third-party modules, but it is not currently supported. This approach would also slow down the production builds.</p>
<h2><a id="user-content-alternatives-to-ejecting" class="anchor" aria-hidden="true" href="#alternatives-to-ejecting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Alternatives to Ejecting</h2>
<p><a href="#npm-run-eject">Ejecting</a> lets you customize anything, but from that point on you have to maintain the configuration and scripts yourself. This can be daunting if you have many similar projects. In such cases instead of ejecting we recommend to <em>fork</em> <code>react-scripts</code> and any other packages you need. <a href="https://auth0.com/blog/how-to-configure-create-react-app/" rel="nofollow">This article</a> dives into how to do it in depth. You can find more discussion in <a href="https://github.com/facebookincubator/create-react-app/issues/682">this issue</a>.</p>
<h2><a id="user-content-something-missing" class="anchor" aria-hidden="true" href="#something-missing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Something Missing?</h2>
<p>If you have ideas for more “How To” recipes that should be on this page, <a href="https://github.com/facebookincubator/create-react-app/issues">let us know</a> or <a href="https://github.com/facebookincubator/create-react-app/edit/master/packages/react-scripts/template/README.md">contribute some!</a></p>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2019 GitHub, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-QxcIZ5pa4j8P5eL6FLQaU/FAIfodWkzV2rf+7OlyiiiIM9ZaG3MODvgQme+LVDUPMBdmjYYZ+svSlFu5yjFhRw==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-43170867.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-pWb+XERZ8B74prW8yPNeOMfFEfMfo8DvbO4kDA/DzPk10uGiVYPCB51sRRwisgKrPyfXtC+Igc5k9BfUpepmtQ==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-a566fe5c.js"></script>
    
    
    
  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

