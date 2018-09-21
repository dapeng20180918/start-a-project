





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



  <link crossorigin="anonymous" media="all" integrity="sha512-1FLfhli3wF1EqKy4+DmsB7My96mQ71ZtDpkmg/2A8RP+5uDgJ0zAT8sRDwSG0p75xQjd9aMIVb58gpjhC//ngA==" rel="stylesheet" href="https://assets-cdn.github.com/assets/frameworks-dcca19dafecb17dea634d2f083dc7f9f.css" />
  <link crossorigin="anonymous" media="all" integrity="sha512-ERzCrxQ9/KT3hsH+BMLLRcbwQp3/xat+ZqZrlySbC6YsUxwYAAGOf+5SpbATykqQxh1+B/Wz0kSpYnpdaff/tg==" rel="stylesheet" href="https://assets-cdn.github.com/assets/github-77ae44d8225d1c06908f977e09b0adab.css" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>styleguide/javascript.md at master · fex-team/styleguide</title>
    <meta name="description" content="文档与源码编写风格. Contribute to fex-team/styleguide development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta property="og:image" content="https://avatars2.githubusercontent.com/u/6668906?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="fex-team/styleguide" /><meta property="og:url" content="https://github.com/fex-team/styleguide" /><meta property="og:description" content="文档与源码编写风格. Contribute to fex-team/styleguide development by creating an account on GitHub." />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MzE4NzE2MzU0OjQ2NDcxMGQ2NDA3M2RiNDIxMmQ4M2ZiNTM1MjI5YTk4MmYzNDNmNDA3MjBmMmNjN2FjNmY4ODQ5Yzk1NmZiNGY=--751a1e17dfa135236aff5aa1dcc1be8a59bac8ef">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="5011:21AD:1C7BA49:2D5E912:5BA45990" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="5011:21AD:1C7BA49:2D5E912:5BA45990" /><meta name="octolytics-dimension-region_edge" content="iad" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-actor-id" content="43374281" /><meta name="octolytics-actor-login" content="dapeng20180918" /><meta name="octolytics-actor-hash" content="6293f28a1e3bbacf588e768df90c10e24cea0149c06a49bafca6fb717c59dba5" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="ed9c5dc085910e9845f366caa974d62d" %>

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="dapeng20180918">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="YmRmYTI2MjkzYWFmMzZhMzUxODdiMmQ1YWUxMDllZTcwOGJiYzk3ZDg5ZTdkYmM3NGEzZGQ0OGMwZTQ1YTMyZnx7InJlbW90ZV9hZGRyZXNzIjoiMTA2LjM4LjM4LjExNCIsInJlcXVlc3RfaWQiOiI1MDExOjIxQUQ6MUM3QkE0OToyRDVFOTEyOjVCQTQ1OTkwIiwidGltZXN0YW1wIjoxNTM3NDk3NDk4LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="DASHBOARD_V2_LAYOUT_OPT_IN,EXPLORE_DISCOVER_REPOSITORIES,UNIVERSE_BANNER,MARKETPLACE_PLAN_RESTRICTION_EDITOR,MARKETPLACE_RETARGETING,QUOTE_MARKDOWN">

  <meta name="html-safe-nonce" content="b950db46bd3a2bef8c27b0cbca794e4e2a221abb">

  <meta http-equiv="x-pjax-version" content="8943bc0f37eaab6f76380f38e9c5aeda">
  

      <link href="https://github.com/fex-team/styleguide/commits/master.atom" rel="alternate" title="Recent Commits to styleguide:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/fex-team/styleguide git https://github.com/fex-team/styleguide.git">

  <meta name="octolytics-dimension-user_id" content="6668906" /><meta name="octolytics-dimension-user_login" content="fex-team" /><meta name="octolytics-dimension-repository_id" content="17503102" /><meta name="octolytics-dimension-repository_nwo" content="fex-team/styleguide" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="17503102" /><meta name="octolytics-dimension-repository_network_root_nwo" content="fex-team/styleguide" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/fex-team/styleguide/blob/master/javascript.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        
<header class="Header  f5" role="banner">
  <div class="d-flex flex-justify-between px-3 container-lg">
    <div class="d-flex flex-justify-between ">
      <div class="">
        <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg height="32" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

      </div>

    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" data-scope-type="Repository" data-scope-id="17503102" data-scoped-search-url="/fex-team/styleguide/search" data-unscoped-search-url="/search" action="/fex-team/styleguide/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control header-search-wrapper header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=twUKX1BCJgzwj9j/ckazkRS6r7lP91RWTanJvmB8sKSMLUuzQGHtH1CEHUV0Qda7xCeuDeAbG/zCbovOWZOs+g=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://assets-cdn.github.com/images/search-shortcut-hint.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              <ul class="d-none js-jump-to-suggestions-template-container">
                <li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item" role="option">
                  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center p-2 jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open" href="">
                    <div class="jump-to-octicon js-jump-to-octicon mr-2 text-center d-none">
                      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
                      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
                      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
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
                <li class="d-flex flex-justify-center flex-items-center p-3 f5 d-none">
                  <span class="text-gray">No suggested jump to results</span>
                </li>
              </ul>

              <ul id="jump-to-results" role="listbox" class="js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container" >
                <li class="d-flex flex-justify-center flex-items-center p-0 f5">
                  <img src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
                </li>
              </ul>
            </div>
      </label>
</form>  </div>
</div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a class="js-selected-navigation-item HeaderNavlink px-2" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
                Pull requests
</a>            </li>
            <li>
              <a class="js-selected-navigation-item HeaderNavlink px-2" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
                Issues
</a>            </li>
              <li>
                <a class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
                   Marketplace
</a>              </li>
            <li>
              <a class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li class="dropdown">
    <span class="d-inline-block  px-2">
      
    <a aria-label="You have no unread notifications" class="notification-indicator tooltipped tooltipped-s  js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:43374281" href="/notifications">
        <span class="mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M13.99 11.991v1H0v-1l.73-.58c.769-.769.809-2.547 1.189-4.416.77-3.767 4.077-4.996 4.077-4.996 0-.55.45-1 .999-1 .55 0 1 .45 1 1 0 0 3.387 1.229 4.156 4.996.38 1.879.42 3.657 1.19 4.417l.659.58h-.01zM6.995 15.99c1.11 0 1.999-.89 1.999-1.999H4.996c0 1.11.89 1.999 1.999 1.999z"/></svg>
</a>
    </span>
  </li>

  <li class="dropdown">
    <details class="details-overlay details-reset d-flex px-2 flex-items-center">
      <summary class="HeaderNavlink"
         aria-label="Create new…"
         data-ga-click="Header, create new, icon:add">
        <svg class="octicon octicon-plus float-left mr-1 mt-1" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg>
        <span class="dropdown-caret mt-1"></span>
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


  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="fex-team/styleguide">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/fex-team/styleguide/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </details-menu>
    </details>
  </li>

  <li class="dropdown">

    <details class="details-overlay details-reset d-flex pl-2 flex-items-center">
      <summary class="HeaderNavlink name mt-1"
        aria-label="View profile and more"
        data-ga-click="Header, show menu, icon:avatar">
        <img alt="@dapeng20180918" class="avatar float-left mr-1" src="https://avatars3.githubusercontent.com/u/43374281?s=40&amp;v=4" height="20" width="20">
        <span class="dropdown-caret"></span>
      </summary>
      <details-menu class="dropdown-menu dropdown-menu-sw">
        <ul>
          <li class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/dapeng20180918" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">dapeng20180918</strong></a></li>
          <li class="dropdown-divider"></li>
          <li><a role="menuitem" class="dropdown-item" href="/dapeng20180918" data-ga-click="Header, go to profile, text:your profile">Your profile</a></li>
          <li><a role="menuitem" class="dropdown-item" href="/dapeng20180918?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a></li>
          <li><a role="menuitem" class="dropdown-item" href="/dapeng20180918?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a></li>
            <li><a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your gists</a></li>
          <li class="dropdown-divider"></li>
          <li><a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a></li>
          <li><a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a></li>
          <li>
            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="eudaKHpiK9rrgWfytLifnJIfGW9hInObw2QfzHoctOFukCX83cahFYPZjtwWQvt6fFg/GRLOn9PL+6KICJnEQQ==" />
              <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
                Sign out
              </button>
</form>          </li>
        </ul>
      </details-menu>
    </details>
  </li>
</ul>



        <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="sr-only right-0" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="Bb9Zd/T3tHYQO+vpieecDpYno0NEEXF9W2dCIAit+b4RyCajU1M+uXhjAscrHfjoeGCFNTf9nTVT+P9keiiJHg==" />
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">


</div>



  <div role="main" class="application-main ">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      





  



  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-autosubmit="true" data-remote="true" class="js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="jmus9Uw9Dztgth6KI8ZQCDfSEdtIsO7azN/G7ZURQ3GBXbHzgrdOk1DF+nWYQ42xtFRrll4UAD9xnMBJxPn7XA==" />      <input type="hidden" name="repository_id" id="repository_id" value="17503102" class="form-control" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/fex-team/styleguide/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
          <a class="social-count js-social-count"
            href="/fex-team/styleguide/watchers"
            aria-label="145 users are watching this repository">
            145
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg class="octicon octicon-x js-menu-close" role="img" aria-label="Close" viewBox="0 0 12 16" version="1.1" width="12" height="16"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
                  <div class="select-menu-item-text">
                    <input type="radio" name="do" id="do_included" value="included" checked="checked" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
                  <div class="select-menu-item-text">
                    <input type="radio" name="do" id="do_subscribed" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
                  <div class="select-menu-item-text">
                    <input type="radio" name="do" id="do_ignore" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/fex-team/styleguide/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="JE6Ntk6UODJ7o6orQ4OxhG04tmuRrObROvWyzLiMhaN43sscvlJHgh6v9cxv8wFCbJ76igDzmlYC9ZHcx3e26A==" />
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar fex-team/styleguide"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/fex-team/styleguide/stargazers"
           aria-label="1510 users starred this repository">
          1,510
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/fex-team/styleguide/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="rJd9I3KvxwJ/r8XF8e96IgIA5GgAJJlbSe7tV3YSi7xop8hxK/UukvpK/fgnnSXpi6O2/5FDwpnwidVJPnCxjg==" />
      <input type="hidden" name="context" value="repository"></input>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star fex-team/styleguide"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/fex-team/styleguide/stargazers"
           aria-label="1510 users starred this repository">
          1,510
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="btn-with-count" action="/fex-team/styleguide/fork" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="P+WIMStW1cZF5BEEW3arCtmGduwRDN2sGi+VXw85KjV8yNOiaSeag07fLyt3zJ9fNrivZHcr5Um9qz75EqKZTg==" />
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of fex-team/styleguide to your account"
                aria-label="Fork your own copy of fex-team/styleguide to your account">
              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/fex-team/styleguide/network/members" class="social-count"
       aria-label="618 users forked this repository">
      618
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" href="/fex-team">fex-team</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/fex-team/styleguide">styleguide</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /fex-team/styleguide" href="/fex-team/styleguide">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /fex-team/styleguide/issues" href="/fex-team/styleguide/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">20</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /fex-team/styleguide/pulls" href="/fex-team/styleguide/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">1</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /fex-team/styleguide/projects" href="/fex-team/styleguide/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>


    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /fex-team/styleguide/wiki" href="/fex-team/styleguide/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>
  <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /fex-team/styleguide/pulse" href="/fex-team/styleguide/pulse">
    <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
  <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/fex-team/styleguide/blob/e2b6e47d86902504f88d218595841309c6852e42/javascript.md">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:db3293b094490c18de44d0a11d8c5491 -->

  

  <div class="file-navigation">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg class="octicon octicon-x js-menu-close" role="img" aria-label="Close" viewBox="0 0 12 16" version="1.1" width="12" height="16"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
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
               href="/fex-team/styleguide/blob/master/javascript.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
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
      <a href="/fex-team/styleguide/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <clipboard-copy for="blob-path" class="btn btn-sm BtnGroup-item">
        Copy path
      </clipboard-copy>
    </div>
    <div id="blob-path" class="breadcrumb">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a data-pjax="true" href="/fex-team/styleguide"><span>styleguide</span></a></span></span><span class="separator">/</span><strong class="final-path">javascript.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/fex-team/styleguide/commit/e2b6e47d86902504f88d218595841309c6852e42" data-pjax>
          e2b6e47
        </a>
        <relative-time datetime="2016-01-24T05:17:22Z">Jan 24, 2016</relative-time>
      </span>
      <div>
        <a rel="contributor" data-skip-pjax="true" data-hovercard-user-id="6889" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/nwind"><img class="avatar" src="https://avatars0.githubusercontent.com/u/6889?s=40&amp;v=4" width="20" height="20" alt="@nwind" /></a>
        <a class="user-mention" rel="contributor" data-hovercard-user-id="6889" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/nwind">nwind</a>
          <a data-pjax="true" title="fix typo" class="message" href="/fex-team/styleguide/commit/e2b6e47d86902504f88d218595841309c6852e42">fix typo</a>
      </div>

    <div class="commit-tease-contributors">
      
<details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
  <summary class="btn-link" aria-haspopup="dialog"  >
    
    <span><strong>6</strong> contributors</span>
  </summary>
  <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast " aria-label="Users who have contributed to this file">
    <div class="Box-header">
      <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <h3 class="Box-title">Users who have contributed to this file</h3>
    </div>
    
        <ul class="list-style-none overflow-auto">
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/2betop">
                <img class="avatar mr-2" alt="" src="https://avatars2.githubusercontent.com/u/2698393?s=40&amp;v=4" width="20" height="20" />
                2betop
</a>            </li>
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/nwind">
                <img class="avatar mr-2" alt="" src="https://avatars0.githubusercontent.com/u/6889?s=40&amp;v=4" width="20" height="20" />
                nwind
</a>            </li>
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/zswang">
                <img class="avatar mr-2" alt="" src="https://avatars2.githubusercontent.com/u/536587?s=40&amp;v=4" width="20" height="20" />
                zswang
</a>            </li>
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/techird">
                <img class="avatar mr-2" alt="" src="https://avatars2.githubusercontent.com/u/1901286?s=40&amp;v=4" width="20" height="20" />
                techird
</a>            </li>
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/Singularity-zju">
                <img class="avatar mr-2" alt="" src="https://avatars1.githubusercontent.com/u/1298247?s=40&amp;v=4" width="20" height="20" />
                Singularity-zju
</a>            </li>
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/miller">
                <img class="avatar mr-2" alt="" src="https://avatars0.githubusercontent.com/u/398506?s=40&amp;v=4" width="20" height="20" />
                miller
</a>            </li>
        </ul>

  </details-dialog>
</details>
          <a class="avatar-link" data-hovercard-user-id="2698393" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/fex-team/styleguide/commits/master/javascript.md?author=2betop">
      <img class="avatar" src="https://avatars2.githubusercontent.com/u/2698393?s=40&amp;v=4" width="20" height="20" alt="@2betop" /> 
</a>    <a class="avatar-link" data-hovercard-user-id="6889" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/fex-team/styleguide/commits/master/javascript.md?author=nwind">
      <img class="avatar" src="https://avatars0.githubusercontent.com/u/6889?s=40&amp;v=4" width="20" height="20" alt="@nwind" /> 
</a>    <a class="avatar-link" data-hovercard-user-id="536587" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/fex-team/styleguide/commits/master/javascript.md?author=zswang">
      <img class="avatar" src="https://avatars2.githubusercontent.com/u/536587?s=40&amp;v=4" width="20" height="20" alt="@zswang" /> 
</a>    <a class="avatar-link" data-hovercard-user-id="1901286" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/fex-team/styleguide/commits/master/javascript.md?author=techird">
      <img class="avatar" src="https://avatars2.githubusercontent.com/u/1901286?s=40&amp;v=4" width="20" height="20" alt="@techird" /> 
</a>    <a class="avatar-link" data-hovercard-user-id="1298247" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/fex-team/styleguide/commits/master/javascript.md?author=Singularity-zju">
      <img class="avatar" src="https://avatars1.githubusercontent.com/u/1298247?s=40&amp;v=4" width="20" height="20" alt="@Singularity-zju" /> 
</a>    <a class="avatar-link" data-hovercard-user-id="398506" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/fex-team/styleguide/commits/master/javascript.md?author=miller">
      <img class="avatar" src="https://avatars0.githubusercontent.com/u/398506?s=40&amp;v=4" width="20" height="20" alt="@miller" /> 
</a>

    </div>
  </div>



  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/fex-team/styleguide/raw/master/javascript.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/fex-team/styleguide/blame/master/javascript.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/fex-team/styleguide/commits/master/javascript.md">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="x-github-client://openRepo/https://github.com/fex-team/styleguide?branch=master&amp;filepath=javascript.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/fex-team/styleguide/edit/master/javascript.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="Jp7+bh+d5d9luUNIp1ltX/y5lBPiT31POZ0ztr/eBhs+FfVssz7f5BoCKxZI2Xk/gwfxOsJRoc/+YBGTcRWqOg==" />
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
              <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
            </button>
</form>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/fex-team/styleguide/delete/master/javascript.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="qV6X64hHXiBX6uKeCHDmmReuGgt2eGJ1hvSX/z0RGlCrwyZYwVwcQ3305edqfZtkeI9YjXQaFdZHMmmaefEqPw==" />
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      <span class="file-mode" title="File mode">executable file</span>
      <span class="file-info-divider"></span>
      2887 lines (1882 sloc)
      <span class="file-info-divider"></span>
    60.7 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-javascript编码规范" class="anchor" aria-hidden="true" href="#javascript编码规范"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>JavaScript编码规范</h1>
<p><a href="#1-%E5%89%8D%E8%A8%80">1 前言</a></p>
<p><a href="#2-%E4%BB%A3%E7%A0%81%E9%A3%8E%E6%A0%BC">2 代码风格</a></p>
<p>　　<a href="#21-%E6%96%87%E4%BB%B6">2.1 文件</a></p>
<p>　　<a href="#22-%E7%BB%93%E6%9E%84">2.2 结构</a></p>
<p>　　　　<a href="#221-%E7%BC%A9%E8%BF%9B">2.2.1 缩进</a></p>
<p>　　　　<a href="#222-%E7%A9%BA%E6%A0%BC">2.2.2 空格</a></p>
<p>　　　　<a href="#223-%E6%8D%A2%E8%A1%8C">2.2.3 换行</a></p>
<p>　　　　<a href="#224-%E8%AF%AD%E5%8F%A5">2.2.4 语句</a></p>
<p>　　<a href="#23-%E5%91%BD%E5%90%8D">2.3 命名</a></p>
<p>　　<a href="#24-%E6%B3%A8%E9%87%8A">2.4 注释</a></p>
<p>　　　　<a href="#241-%E5%8D%95%E8%A1%8C%E6%B3%A8%E9%87%8A">2.4.1 单行注释</a></p>
<p>　　　　<a href="#242-%E5%A4%9A%E8%A1%8C%E6%B3%A8%E9%87%8A">2.4.2 多行注释</a></p>
<p>　　　　<a href="#243-%E6%96%87%E6%A1%A3%E5%8C%96%E6%B3%A8%E9%87%8A">2.4.3 文档化注释</a></p>
<p>　　　　<a href="#244-%E7%B1%BB%E5%9E%8B%E5%AE%9A%E4%B9%89">2.4.4 类型定义</a></p>
<p>　　　　<a href="#245-%E6%96%87%E4%BB%B6%E6%B3%A8%E9%87%8A">2.4.5 文件注释</a></p>
<p>　　　　<a href="#246-%E5%91%BD%E5%90%8D%E7%A9%BA%E9%97%B4%E6%B3%A8%E9%87%8A">2.4.6 命名空间注释</a></p>
<p>　　　　<a href="#247-%E7%B1%BB%E6%B3%A8%E9%87%8A">2.4.7 类注释</a></p>
<p>　　　　<a href="#248-%E5%87%BD%E6%95%B0/%E6%96%B9%E6%B3%95%E6%B3%A8%E9%87%8A">2.4.8 函数/方法注释</a></p>
<p>　　　　<a href="#249-%E4%BA%8B%E4%BB%B6%E6%B3%A8%E9%87%8A">2.4.9 事件注释</a></p>
<p>　　　　<a href="#2410-%E5%B8%B8%E9%87%8F%E6%B3%A8%E9%87%8A">2.4.10 常量注释</a></p>
<p>　　　　<a href="#2411-%E5%A4%8D%E6%9D%82%E7%B1%BB%E5%9E%8B%E6%B3%A8%E9%87%8A">2.4.11 复杂类型注释</a></p>
<p>　　　　<a href="#2412-amd-%E6%A8%A1%E5%9D%97%E6%B3%A8%E9%87%8A">2.4.12 AMD 模块注释</a></p>
<p>　　　　<a href="#2413-%E7%BB%86%E8%8A%82%E6%B3%A8%E9%87%8A">2.4.13 细节注释</a></p>
<p><a href="#3-%E8%AF%AD%E8%A8%80%E7%89%B9%E6%80%A7">3 语言特性</a></p>
<p>　　<a href="#31-%E5%8F%98%E9%87%8F">3.1 变量</a></p>
<p>　　<a href="#32-%E6%9D%A1%E4%BB%B6">3.2 条件</a></p>
<p>　　<a href="#33-%E5%BE%AA%E7%8E%AF">3.3 循环</a></p>
<p>　　<a href="#34-%E7%B1%BB%E5%9E%8B">3.4 类型</a></p>
<p>　　　　<a href="#341-%E7%B1%BB%E5%9E%8B%E6%A3%80%E6%B5%8B">3.4.1 类型检测</a></p>
<p>　　　　<a href="#342-%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2">3.4.2 类型转换</a></p>
<p>　　<a href="#35-%E5%AD%97%E7%AC%A6%E4%B8%B2">3.5 字符串</a></p>
<p>　　<a href="#36-%E5%AF%B9%E8%B1%A1">3.6 对象</a></p>
<p>　　<a href="#37-%E6%95%B0%E7%BB%84">3.7 数组</a></p>
<p>　　<a href="#38-%E5%87%BD%E6%95%B0">3.8 函数</a></p>
<p>　　　　<a href="#381-%E5%87%BD%E6%95%B0%E9%95%BF%E5%BA%A6">3.8.1 函数长度</a></p>
<p>　　　　<a href="#382-%E5%8F%82%E6%95%B0%E8%AE%BE%E8%AE%A1">3.8.2 参数设计</a></p>
<p>　　　　<a href="#383-%E9%97%AD%E5%8C%85">3.8.3 闭包</a></p>
<p>　　　　<a href="#384-%E7%A9%BA%E5%87%BD%E6%95%B0">3.8.4 空函数</a></p>
<p>　　<a href="#39-%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1">3.9 面向对象</a></p>
<p>　　<a href="#310-%E5%8A%A8%E6%80%81%E7%89%B9%E6%80%A7">3.10 动态特性</a></p>
<p>　　　　<a href="#3101-eval">3.10.1 eval</a></p>
<p>　　　　<a href="#3102-%E5%8A%A8%E6%80%81%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%A0%81">3.10.2 动态执行代码</a></p>
<p>　　　　<a href="#3103-with">3.10.3 with</a></p>
<p>　　　　<a href="#3104-delete">3.10.4 delete</a></p>
<p>　　　　<a href="#3105-%E5%AF%B9%E8%B1%A1%E5%B1%9E%E6%80%A7">3.10.5 对象属性</a></p>
<p><a href="#4-%E6%B5%8F%E8%A7%88%E5%99%A8%E7%8E%AF%E5%A2%83">4 浏览器环境</a></p>
<p>　　<a href="#41-%E6%A8%A1%E5%9D%97%E5%8C%96">4.1 模块化</a></p>
<p>　　　　<a href="#411-amd">4.1.1 AMD</a></p>
<p>　　　　<a href="#412-define">4.1.2 define</a></p>
<p>　　　　<a href="#413-require">4.1.3 require</a></p>
<p>　　<a href="#42-dom">4.2 DOM</a></p>
<p>　　　　<a href="#421-%E5%85%83%E7%B4%A0%E8%8E%B7%E5%8F%96">4.2.1 元素获取</a></p>
<p>　　　　<a href="#422-%E6%A0%B7%E5%BC%8F%E8%8E%B7%E5%8F%96">4.2.2 样式获取</a></p>
<p>　　　　<a href="#423-%E6%A0%B7%E5%BC%8F%E8%AE%BE%E7%BD%AE">4.2.3 样式设置</a></p>
<p>　　　　<a href="#424-dom-%E6%93%8D%E4%BD%9C">4.2.4 DOM 操作</a></p>
<p>　　　　<a href="#425-dom-%E4%BA%8B%E4%BB%B6">4.2.5 DOM 事件</a></p>
<h2><a id="user-content-1-前言" class="anchor" aria-hidden="true" href="#1-前言"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1 前言</h2>
<p>JavaScript在百度一直有着广泛的应用，特别是在浏览器端的行为管理。本文档的目标是使JavaScript代码风格保持一致，容易被理解和被维护。</p>
<p>虽然本文档是针对JavaScript设计的，但是在使用各种JavaScript的预编译语言时(如TypeScript等)时，适用的部分也应尽量遵循本文档的约定。</p>
<h2><a id="user-content-2-代码风格" class="anchor" aria-hidden="true" href="#2-代码风格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2 代码风格</h2>
<h3><a id="user-content-21-文件" class="anchor" aria-hidden="true" href="#21-文件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.1 文件</h3>
<h5><a id="user-content-建议-javascript-文件使用无-bom-的-utf-8-编码" class="anchor" aria-hidden="true" href="#建议-javascript-文件使用无-bom-的-utf-8-编码"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] <code>JavaScript</code> 文件使用无 <code>BOM</code> 的 <code>UTF-8</code> 编码。</h5>
<p>解释：</p>
<p>UTF-8 编码具有更广泛的适应性。BOM 在使用程序或工具处理文件时可能造成不必要的干扰。</p>
<h5><a id="user-content-建议-在文件结尾处保留一个空行" class="anchor" aria-hidden="true" href="#建议-在文件结尾处保留一个空行"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 在文件结尾处，保留一个空行。</h5>
<h3><a id="user-content-22-结构" class="anchor" aria-hidden="true" href="#22-结构"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2 结构</h3>
<h4><a id="user-content-221-缩进" class="anchor" aria-hidden="true" href="#221-缩进"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2.1 缩进</h4>
<h5><a id="user-content-强制-使用-4-个空格做为一个缩进层级不允许使用-2-个空格-或-tab-字符" class="anchor" aria-hidden="true" href="#强制-使用-4-个空格做为一个缩进层级不允许使用-2-个空格-或-tab-字符"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 使用 <code>4</code> 个空格做为一个缩进层级，不允许使用 <code>2</code> 个空格 或 <code>tab</code> 字符。</h5>
<h5><a id="user-content-强制-switch-下的-case-和-default-必须增加一个缩进层级" class="anchor" aria-hidden="true" href="#强制-switch-下的-case-和-default-必须增加一个缩进层级"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>switch</code> 下的 <code>case</code> 和 <code>default</code> 必须增加一个缩进层级。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">switch</span> (variable) {

    <span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>1<span class="pl-pds">'</span></span>:
        <span class="pl-c"><span class="pl-c">//</span> do...</span>
        <span class="pl-k">break</span>;

    <span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>2<span class="pl-pds">'</span></span>:
        <span class="pl-c"><span class="pl-c">//</span> do...</span>
        <span class="pl-k">break</span>;

    <span class="pl-k">default</span>:
        <span class="pl-c"><span class="pl-c">//</span> do...</span>

}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">switch</span> (variable) {

<span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>1<span class="pl-pds">'</span></span>:
    <span class="pl-c"><span class="pl-c">//</span> do...</span>
    <span class="pl-k">break</span>;

<span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>2<span class="pl-pds">'</span></span>:
    <span class="pl-c"><span class="pl-c">//</span> do...</span>
    <span class="pl-k">break</span>;

<span class="pl-k">default</span>:
    <span class="pl-c"><span class="pl-c">//</span> do...</span>

}</pre></div>
<h4><a id="user-content-222-空格" class="anchor" aria-hidden="true" href="#222-空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2.2 空格</h4>
<h5><a id="user-content-强制-二元运算符两侧必须有一个空格一元运算符与操作对象之间不允许有空格" class="anchor" aria-hidden="true" href="#强制-二元运算符两侧必须有一个空格一元运算符与操作对象之间不允许有空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 二元运算符两侧必须有一个空格，一元运算符与操作对象之间不允许有空格。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> a <span class="pl-k">=</span> <span class="pl-k">!</span><span class="pl-smi">arr</span>.<span class="pl-c1">length</span>;
a<span class="pl-k">++</span>;
a <span class="pl-k">=</span> b <span class="pl-k">+</span> c;</pre></div>
<h5><a id="user-content-强制-用作代码块起始的左花括号--前必须有一个空格" class="anchor" aria-hidden="true" href="#强制-用作代码块起始的左花括号--前必须有一个空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 用作代码块起始的左花括号 <code>{</code> 前必须有一个空格。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (condition) {
}

<span class="pl-k">while</span> (condition) {
}

<span class="pl-k">function</span> <span class="pl-en">funcName</span>() {
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (condition){
}

<span class="pl-k">while</span> (condition){
}

<span class="pl-k">function</span> <span class="pl-en">funcName</span>(){
}</pre></div>
<h5><a id="user-content-强制-if--else--for--while--function--switch--do--try--catch--finally-关键字后必须有一个空格" class="anchor" aria-hidden="true" href="#强制-if--else--for--while--function--switch--do--try--catch--finally-关键字后必须有一个空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>if / else / for / while / function / switch / do / try / catch / finally</code> 关键字后，必须有一个空格。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (condition) {
}

<span class="pl-k">while</span> (condition) {
}

(<span class="pl-k">function</span> () {
})();

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span>(condition) {
}

<span class="pl-k">while</span>(condition) {
}

(<span class="pl-k">function</span>() {
})();</pre></div>
<h5><a id="user-content-强制-在对象创建时属性中的--之后必须有空格-之前不允许有空格" class="anchor" aria-hidden="true" href="#强制-在对象创建时属性中的--之后必须有空格-之前不允许有空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 在对象创建时，属性中的 <code>:</code> 之后必须有空格，<code>:</code> 之前不允许有空格。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> obj <span class="pl-k">=</span> {
    a<span class="pl-k">:</span> <span class="pl-c1">1</span>,
    b<span class="pl-k">:</span> <span class="pl-c1">2</span>,
    c<span class="pl-k">:</span> <span class="pl-c1">3</span>
};

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> obj <span class="pl-k">=</span> {
    a <span class="pl-k">:</span> <span class="pl-c1">1</span>,
    b<span class="pl-k">:</span><span class="pl-c1">2</span>,
    c <span class="pl-k">:</span><span class="pl-c1">3</span>
};</pre></div>
<h5><a id="user-content-强制-函数声明具名函数表达式函数调用中函数名和--之间不允许有空格" class="anchor" aria-hidden="true" href="#强制-函数声明具名函数表达式函数调用中函数名和--之间不允许有空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 函数声明、具名函数表达式、函数调用中，函数名和 <code>(</code> 之间不允许有空格。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">function</span> <span class="pl-en">funcName</span>() {
}

<span class="pl-k">var</span> <span class="pl-en">funcName</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">funcName</span>() {
};

<span class="pl-en">funcName</span>();

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">function</span> <span class="pl-en">funcName</span> () {
}

<span class="pl-k">var</span> <span class="pl-en">funcName</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">funcName</span> () {
};

<span class="pl-en">funcName</span> ();</pre></div>
<h5><a id="user-content-强制--和--前不允许有空格" class="anchor" aria-hidden="true" href="#强制--和--前不允许有空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>,</code> 和 <code>;</code> 前不允许有空格。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-en">callFunc</span>(a, b);

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-en">callFunc</span>(a , b) ;</pre></div>
<h5><a id="user-content-强制-在函数调用函数声明括号表达式属性访问if--for--while--switch--catch-等语句中-和--内紧贴括号部分不允许有空格" class="anchor" aria-hidden="true" href="#强制-在函数调用函数声明括号表达式属性访问if--for--while--switch--catch-等语句中-和--内紧贴括号部分不允许有空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 在函数调用、函数声明、括号表达式、属性访问、<code>if / for / while / switch / catch</code> 等语句中，<code>()</code> 和 <code>[]</code> 内紧贴括号部分不允许有空格。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>

<span class="pl-en">callFunc</span>(param1, param2, param3);

<span class="pl-en">save</span>(<span class="pl-c1">this</span>.<span class="pl-smi">list</span>[<span class="pl-c1">this</span>.<span class="pl-smi">indexes</span>[i]]);

needIncream <span class="pl-k">&amp;&amp;</span> (variable <span class="pl-k">+=</span> increament);

<span class="pl-k">if</span> (num <span class="pl-k">&gt;</span> <span class="pl-smi">list</span>.<span class="pl-c1">length</span>) {
}

<span class="pl-k">while</span> (len<span class="pl-k">--</span>) {
}


<span class="pl-c"><span class="pl-c">//</span> bad</span>

<span class="pl-en">callFunc</span>( param1, param2, param3 );

<span class="pl-en">save</span>( <span class="pl-c1">this</span>.<span class="pl-smi">list</span>[ <span class="pl-c1">this</span>.<span class="pl-smi">indexes</span>[ i ] ] );

needIncreament <span class="pl-k">&amp;&amp;</span> ( variable <span class="pl-k">+=</span> increament );

<span class="pl-k">if</span> ( num <span class="pl-k">&gt;</span> <span class="pl-smi">list</span>.<span class="pl-c1">length</span> ) {
}

<span class="pl-k">while</span> ( len<span class="pl-k">--</span> ) {
}</pre></div>
<h5><a id="user-content-强制-单行声明的数组与对象如果包含元素-和--内紧贴括号部分不允许包含空格" class="anchor" aria-hidden="true" href="#强制-单行声明的数组与对象如果包含元素-和--内紧贴括号部分不允许包含空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 单行声明的数组与对象，如果包含元素，<code>{}</code> 和 <code>[]</code> 内紧贴括号部分不允许包含空格。</h5>
<p>解释：</p>
<p>声明包含元素的数组与对象，只有当内部元素的形式较为简单时，才允许写在一行。元素复杂的情况，还是应该换行书写。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> arr1 <span class="pl-k">=</span> [];
<span class="pl-k">var</span> arr2 <span class="pl-k">=</span> [<span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>];
<span class="pl-k">var</span> obj1 <span class="pl-k">=</span> {};
<span class="pl-k">var</span> obj2 <span class="pl-k">=</span> {name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>obj<span class="pl-pds">'</span></span>};
<span class="pl-k">var</span> obj3 <span class="pl-k">=</span> {
    name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>obj<span class="pl-pds">'</span></span>,
    age<span class="pl-k">:</span> <span class="pl-c1">20</span>,
    sex<span class="pl-k">:</span> <span class="pl-c1">1</span>
};

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> arr1 <span class="pl-k">=</span> [ ];
<span class="pl-k">var</span> arr2 <span class="pl-k">=</span> [ <span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span> ];
<span class="pl-k">var</span> obj1 <span class="pl-k">=</span> { };
<span class="pl-k">var</span> obj2 <span class="pl-k">=</span> { name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>obj<span class="pl-pds">'</span></span> };
<span class="pl-k">var</span> obj3 <span class="pl-k">=</span> {name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>obj<span class="pl-pds">'</span></span>, age<span class="pl-k">:</span> <span class="pl-c1">20</span>, sex<span class="pl-k">:</span> <span class="pl-c1">1</span>};</pre></div>
<h5><a id="user-content-强制-行尾不得有多余的空格" class="anchor" aria-hidden="true" href="#强制-行尾不得有多余的空格"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 行尾不得有多余的空格。</h5>
<h4><a id="user-content-223-换行" class="anchor" aria-hidden="true" href="#223-换行"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2.3 换行</h4>
<h5><a id="user-content-强制-每个独立语句结束后必须换行" class="anchor" aria-hidden="true" href="#强制-每个独立语句结束后必须换行"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 每个独立语句结束后必须换行。</h5>
<h5><a id="user-content-强制-每行不得超过-120-个字符" class="anchor" aria-hidden="true" href="#强制-每行不得超过-120-个字符"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 每行不得超过 <code>120</code> 个字符。</h5>
<p>解释：</p>
<p>超长的不可分割的代码允许例外，比如复杂的正则表达式。长字符串不在例外之列。</p>
<h5><a id="user-content-强制-运算符处换行时运算符必须在新行的行首" class="anchor" aria-hidden="true" href="#强制-运算符处换行时运算符必须在新行的行首"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 运算符处换行时，运算符必须在新行的行首。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (<span class="pl-smi">user</span>.<span class="pl-en">isAuthenticated</span>()
    <span class="pl-k">&amp;&amp;</span> <span class="pl-smi">user</span>.<span class="pl-en">isInRole</span>(<span class="pl-s"><span class="pl-pds">'</span>admin<span class="pl-pds">'</span></span>)
    <span class="pl-k">&amp;&amp;</span> <span class="pl-smi">user</span>.<span class="pl-en">hasAuthority</span>(<span class="pl-s"><span class="pl-pds">'</span>add-admin<span class="pl-pds">'</span></span>)
    <span class="pl-k">||</span> <span class="pl-smi">user</span>.<span class="pl-en">hasAuthority</span>(<span class="pl-s"><span class="pl-pds">'</span>delete-admin<span class="pl-pds">'</span></span>)
) {
    <span class="pl-c"><span class="pl-c">//</span> Code</span>
}

<span class="pl-k">var</span> result <span class="pl-k">=</span> number1 <span class="pl-k">+</span> number2 <span class="pl-k">+</span> number3
    <span class="pl-k">+</span> number4 <span class="pl-k">+</span> number5;


<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (<span class="pl-smi">user</span>.<span class="pl-en">isAuthenticated</span>() <span class="pl-k">&amp;&amp;</span>
    <span class="pl-smi">user</span>.<span class="pl-en">isInRole</span>(<span class="pl-s"><span class="pl-pds">'</span>admin<span class="pl-pds">'</span></span>) <span class="pl-k">&amp;&amp;</span>
    <span class="pl-smi">user</span>.<span class="pl-en">hasAuthority</span>(<span class="pl-s"><span class="pl-pds">'</span>add-admin<span class="pl-pds">'</span></span>) <span class="pl-k">||</span>
    <span class="pl-smi">user</span>.<span class="pl-en">hasAuthority</span>(<span class="pl-s"><span class="pl-pds">'</span>delete-admin<span class="pl-pds">'</span></span>)) {
    <span class="pl-c"><span class="pl-c">//</span> Code</span>
}

<span class="pl-k">var</span> result <span class="pl-k">=</span> number1 <span class="pl-k">+</span> number2 <span class="pl-k">+</span> number3 <span class="pl-k">+</span>
    number4 <span class="pl-k">+</span> number5;</pre></div>
<h5><a id="user-content-强制-在函数声明函数表达式函数调用对象创建数组创建for语句等场景中不允许在--或--前换行" class="anchor" aria-hidden="true" href="#强制-在函数声明函数表达式函数调用对象创建数组创建for语句等场景中不允许在--或--前换行"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 在函数声明、函数表达式、函数调用、对象创建、数组创建、for语句等场景中，不允许在 <code>,</code> 或 <code>;</code> 前换行。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> obj <span class="pl-k">=</span> {
    a<span class="pl-k">:</span> <span class="pl-c1">1</span>,
    b<span class="pl-k">:</span> <span class="pl-c1">2</span>,
    c<span class="pl-k">:</span> <span class="pl-c1">3</span>
};

<span class="pl-en">foo</span>(
    aVeryVeryLongArgument,
    anotherVeryLongArgument,
    callback
);


<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> obj <span class="pl-k">=</span> {
    a<span class="pl-k">:</span> <span class="pl-c1">1</span>
    , b<span class="pl-k">:</span> <span class="pl-c1">2</span>
    , c<span class="pl-k">:</span> <span class="pl-c1">3</span>
};

<span class="pl-en">foo</span>(
    aVeryVeryLongArgument
    , anotherVeryLongArgument
    , callback
);</pre></div>
<h5><a id="user-content-建议-不同行为或逻辑的语句集使用空行隔开更易阅读" class="anchor" aria-hidden="true" href="#建议-不同行为或逻辑的语句集使用空行隔开更易阅读"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 不同行为或逻辑的语句集，使用空行隔开，更易阅读。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 仅为按逻辑换行的示例，不代表setStyle的最优实现</span>
<span class="pl-k">function</span> <span class="pl-en">setStyle</span>(<span class="pl-smi">element</span>, <span class="pl-smi">property</span>, <span class="pl-smi">value</span>) {
    <span class="pl-k">if</span> (element <span class="pl-k">==</span> <span class="pl-c1">null</span>) {
        <span class="pl-k">return</span>;
    }

    <span class="pl-smi">element</span>.<span class="pl-c1">style</span>[property] <span class="pl-k">=</span> value;
}</pre></div>
<h5><a id="user-content-建议-在语句的行长度超过-120-时根据逻辑条件合理缩进" class="anchor" aria-hidden="true" href="#建议-在语句的行长度超过-120-时根据逻辑条件合理缩进"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 在语句的行长度超过 <code>120</code> 时，根据逻辑条件合理缩进。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 较复杂的逻辑条件组合，将每个条件独立一行，逻辑运算符放置在行首进行分隔，或将部分逻辑按逻辑组合进行分隔。</span>
<span class="pl-c"><span class="pl-c">//</span> 建议最终将右括号 ) 与左大括号 { 放在独立一行，保证与 if 内语句块能容易视觉辨识。</span>
<span class="pl-k">if</span> (<span class="pl-smi">user</span>.<span class="pl-en">isAuthenticated</span>()
    <span class="pl-k">&amp;&amp;</span> <span class="pl-smi">user</span>.<span class="pl-en">isInRole</span>(<span class="pl-s"><span class="pl-pds">'</span>admin<span class="pl-pds">'</span></span>)
    <span class="pl-k">&amp;&amp;</span> <span class="pl-smi">user</span>.<span class="pl-en">hasAuthority</span>(<span class="pl-s"><span class="pl-pds">'</span>add-admin<span class="pl-pds">'</span></span>)
    <span class="pl-k">||</span> <span class="pl-smi">user</span>.<span class="pl-en">hasAuthority</span>(<span class="pl-s"><span class="pl-pds">'</span>delete-admin<span class="pl-pds">'</span></span>)
) {
    <span class="pl-c"><span class="pl-c">//</span> Code</span>
}

<span class="pl-c"><span class="pl-c">//</span> 按一定长度截断字符串，并使用 + 运算符进行连接。</span>
<span class="pl-c"><span class="pl-c">//</span> 分隔字符串尽量按语义进行，如不要在一个完整的名词中间断开。</span>
<span class="pl-c"><span class="pl-c">//</span> 特别的，对于HTML片段的拼接，通过缩进，保持和HTML相同的结构。</span>
<span class="pl-k">var</span> html <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span> <span class="pl-c"><span class="pl-c">//</span> 此处用一个空字符串，以便整个HTML片段都在新行严格对齐</span>
    <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;article&gt;<span class="pl-pds">'</span></span>
    <span class="pl-k">+</span>     <span class="pl-s"><span class="pl-pds">'</span>&lt;h1&gt;Title here&lt;/h1&gt;<span class="pl-pds">'</span></span>
    <span class="pl-k">+</span>     <span class="pl-s"><span class="pl-pds">'</span>&lt;p&gt;This is a paragraph&lt;/p&gt;<span class="pl-pds">'</span></span>
    <span class="pl-k">+</span>     <span class="pl-s"><span class="pl-pds">'</span>&lt;footer&gt;Complete&lt;/footer&gt;<span class="pl-pds">'</span></span>
    <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;/article&gt;<span class="pl-pds">'</span></span>;

<span class="pl-c"><span class="pl-c">//</span> 也可使用数组来进行拼接，相对 + 更容易调整缩进。</span>
<span class="pl-k">var</span> html <span class="pl-k">=</span> [
    <span class="pl-s"><span class="pl-pds">'</span>&lt;article&gt;<span class="pl-pds">'</span></span>,
        <span class="pl-s"><span class="pl-pds">'</span>&lt;h1&gt;Title here&lt;/h1&gt;<span class="pl-pds">'</span></span>,
        <span class="pl-s"><span class="pl-pds">'</span>&lt;p&gt;This is a paragraph&lt;/p&gt;<span class="pl-pds">'</span></span>,
        <span class="pl-s"><span class="pl-pds">'</span>&lt;footer&gt;Complete&lt;/footer&gt;<span class="pl-pds">'</span></span>,
    <span class="pl-s"><span class="pl-pds">'</span>&lt;/article&gt;<span class="pl-pds">'</span></span>
];
html <span class="pl-k">=</span> <span class="pl-smi">html</span>.<span class="pl-c1">join</span>(<span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>);

<span class="pl-c"><span class="pl-c">//</span> 当参数过多时，将每个参数独立写在一行上，并将结束的右括号 ) 独立一行。</span>
<span class="pl-c"><span class="pl-c">//</span> 所有参数必须增加一个缩进。</span>
<span class="pl-en">foo</span>(
    aVeryVeryLongArgument,
    anotherVeryLongArgument,
    callback
);

<span class="pl-c"><span class="pl-c">//</span> 也可以按逻辑对参数进行组合。</span>
<span class="pl-c"><span class="pl-c">//</span> 最经典的是baidu.format函数，调用时将参数分为“模板”和“数据”两块</span>
<span class="pl-smi">baidu</span>.<span class="pl-en">format</span>(
    dateFormatTemplate,
    year, month, date, hour, minute, second
);

<span class="pl-c"><span class="pl-c">//</span> 当函数调用时，如果有一个或以上参数跨越多行，应当每一个参数独立一行。</span>
<span class="pl-c"><span class="pl-c">//</span> 这通常出现在匿名函数或者对象初始化等作为参数时，如setTimeout函数等。</span>
<span class="pl-c1">setTimeout</span>(
    <span class="pl-k">function</span> () {
        <span class="pl-en">alert</span>(<span class="pl-s"><span class="pl-pds">'</span>hello<span class="pl-pds">'</span></span>);
    },
    <span class="pl-c1">200</span>
);

<span class="pl-smi">order</span>.<span class="pl-c1">data</span>.<span class="pl-en">read</span>(
    <span class="pl-s"><span class="pl-pds">'</span>id=<span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-smi">me</span>.<span class="pl-smi">model</span>.<span class="pl-c1">id</span>, 
    <span class="pl-k">function</span> (<span class="pl-smi">data</span>) {
        <span class="pl-smi">me</span>.<span class="pl-en">attchToModel</span>(<span class="pl-smi">data</span>.<span class="pl-smi">result</span>);
        <span class="pl-en">callback</span>();
    }, 
    <span class="pl-c1">300</span>
);

<span class="pl-c"><span class="pl-c">//</span> 链式调用较长时采用缩进进行调整。</span>
<span class="pl-en">$</span>(<span class="pl-s"><span class="pl-pds">'</span>#items<span class="pl-pds">'</span></span>)
    .<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>.selected<span class="pl-pds">'</span></span>)
    .<span class="pl-en">highlight</span>()
    .<span class="pl-en">end</span>();

<span class="pl-c"><span class="pl-c">//</span> 三元运算符由3部分组成，因此其换行应当根据每个部分的长度不同，形成不同的情况。</span>
<span class="pl-k">var</span> result <span class="pl-k">=</span> thisIsAVeryVeryLongCondition
    <span class="pl-k">?</span> resultA <span class="pl-k">:</span> resultB;

<span class="pl-k">var</span> result <span class="pl-k">=</span> condition
    <span class="pl-k">?</span> thisIsAVeryVeryLongResult
    <span class="pl-k">:</span> resultB;

<span class="pl-c"><span class="pl-c">//</span> 数组和对象初始化的混用，严格按照每个对象的 { 和结束 } 在独立一行的风格书写。</span>
<span class="pl-k">var</span> array <span class="pl-k">=</span> [
    {
        <span class="pl-c"><span class="pl-c">//</span> ...</span>
    },
    {
        <span class="pl-c"><span class="pl-c">//</span> ...</span>
    }
];</pre></div>
<h5><a id="user-content-建议-对于-ifelsetrycatchfinally-等语句推荐使用在--号后添加一个换行-的风格使代码层次结构更清晰阅读性更好" class="anchor" aria-hidden="true" href="#建议-对于-ifelsetrycatchfinally-等语句推荐使用在--号后添加一个换行-的风格使代码层次结构更清晰阅读性更好"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于 <code>if...else...</code>、<code>try...catch...finally</code> 等语句，推荐使用在 <code>}</code> 号后添加一个换行 的风格，使代码层次结构更清晰，阅读性更好。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">if</span> (condition) {
    <span class="pl-c"><span class="pl-c">//</span> some statements;</span>
}
<span class="pl-k">else</span> {
    <span class="pl-c"><span class="pl-c">//</span> some statements;</span>
}

<span class="pl-k">try</span> {
    <span class="pl-c"><span class="pl-c">//</span> some statements;</span>
}
<span class="pl-k">catch</span> (ex) {
    <span class="pl-c"><span class="pl-c">//</span> some statements;</span>
}</pre></div>
<h4><a id="user-content-224-语句" class="anchor" aria-hidden="true" href="#224-语句"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2.4 语句</h4>
<h5><a id="user-content-强制-不得省略语句结束的分号" class="anchor" aria-hidden="true" href="#强制-不得省略语句结束的分号"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 不得省略语句结束的分号。</h5>
<h5><a id="user-content-强制-在-if--else--for--do--while-语句中即使只有一行也不得省略块-" class="anchor" aria-hidden="true" href="#强制-在-if--else--for--do--while-语句中即使只有一行也不得省略块-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 在 <code>if / else / for / do / while</code> 语句中，即使只有一行，也不得省略块 <code>{...}</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (condition) {
    <span class="pl-en">callFunc</span>();
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (condition) <span class="pl-en">callFunc</span>();
<span class="pl-k">if</span> (condition)
    <span class="pl-en">callFunc</span>();</pre></div>
<h5><a id="user-content-强制-函数定义结束不允许添加分号" class="anchor" aria-hidden="true" href="#强制-函数定义结束不允许添加分号"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 函数定义结束不允许添加分号。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">function</span> <span class="pl-en">funcName</span>() {
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">function</span> <span class="pl-en">funcName</span>() {
};

<span class="pl-c"><span class="pl-c">//</span> 如果是函数表达式，分号是不允许省略的。</span>
<span class="pl-k">var</span> <span class="pl-en">funcName</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
};</pre></div>
<h5><a id="user-content-强制-iife-必须在函数表达式外添加-非-iife-不得在函数表达式外添加-" class="anchor" aria-hidden="true" href="#强制-iife-必须在函数表达式外添加-非-iife-不得在函数表达式外添加-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>IIFE</code> 必须在函数表达式外添加 <code>(</code>，非 <code>IIFE</code> 不得在函数表达式外添加 <code>(</code>。</h5>
<p>解释：</p>
<p>IIFE = Immediately-Invoked Function Expression.</p>
<p>额外的 ( 能够让代码在阅读的一开始就能判断函数是否立即被调用，进而明白接下来代码的用途。而不是一直拖到底部才恍然大悟。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> task <span class="pl-k">=</span> (<span class="pl-k">function</span> () {
   <span class="pl-c"><span class="pl-c">//</span> Code</span>
   <span class="pl-k">return</span> result;
})();

<span class="pl-k">var</span> <span class="pl-en">func</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
};


<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> <span class="pl-en">task</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-c"><span class="pl-c">//</span> Code</span>
    <span class="pl-k">return</span> result;
}();

<span class="pl-k">var</span> func <span class="pl-k">=</span> (<span class="pl-k">function</span> () {
});</pre></div>
<h3><a id="user-content-23-命名" class="anchor" aria-hidden="true" href="#23-命名"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.3 命名</h3>
<h5><a id="user-content-强制-变量-使用-camel命名法" class="anchor" aria-hidden="true" href="#强制-变量-使用-camel命名法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>变量</code> 使用 <code>Camel命名法</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> loadingModules <span class="pl-k">=</span> {};</pre></div>
<h5><a id="user-content-强制-常量-使用-全部字母大写单词间下划线分隔-的命名方式" class="anchor" aria-hidden="true" href="#强制-常量-使用-全部字母大写单词间下划线分隔-的命名方式"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>常量</code> 使用 <code>全部字母大写，单词间下划线分隔</code> 的命名方式。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> <span class="pl-c1">HTML_ENTITY</span> <span class="pl-k">=</span> {};</pre></div>
<h5><a id="user-content-强制-函数-使用-camel命名法" class="anchor" aria-hidden="true" href="#强制-函数-使用-camel命名法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>函数</code> 使用 <code>Camel命名法</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">stringFormat</span>(<span class="pl-smi">source</span>) {
}</pre></div>
<h5><a id="user-content-强制-函数的-参数-使用-camel命名法" class="anchor" aria-hidden="true" href="#强制-函数的-参数-使用-camel命名法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 函数的 <code>参数</code> 使用 <code>Camel命名法</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">hear</span>(<span class="pl-smi">theBells</span>) {
}</pre></div>
<h5><a id="user-content-强制-类-使用-pascal命名法" class="anchor" aria-hidden="true" href="#强制-类-使用-pascal命名法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>类</code> 使用 <code>Pascal命名法</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">TextNode</span>(<span class="pl-smi">options</span>) {
}</pre></div>
<h5><a id="user-content-强制-类的-方法--属性-使用-camel命名法" class="anchor" aria-hidden="true" href="#强制-类的-方法--属性-使用-camel命名法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 类的 <code>方法 / 属性</code> 使用 <code>Camel命名法</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">TextNode</span>(<span class="pl-smi">value</span>, <span class="pl-smi">engine</span>) {
    <span class="pl-c1">this</span>.<span class="pl-c1">value</span> <span class="pl-k">=</span> value;
    <span class="pl-c1">this</span>.<span class="pl-smi">engine</span> <span class="pl-k">=</span> engine;
}

<span class="pl-smi">TextNode</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">clone</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> <span class="pl-c1">this</span>;
};</pre></div>
<h5><a id="user-content-强制-枚举变量-使用-pascal命名法枚举的属性-使用-全部字母大写单词间下划线分隔-的命名方式" class="anchor" aria-hidden="true" href="#强制-枚举变量-使用-pascal命名法枚举的属性-使用-全部字母大写单词间下划线分隔-的命名方式"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>枚举变量</code> 使用 <code>Pascal命名法</code>，<code>枚举的属性</code> 使用 <code>全部字母大写，单词间下划线分隔</code> 的命名方式。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> TargetState <span class="pl-k">=</span> {
    <span class="pl-c1">READING</span><span class="pl-k">:</span> <span class="pl-c1">1</span>,
    <span class="pl-c1">READED</span><span class="pl-k">:</span> <span class="pl-c1">2</span>,
    <span class="pl-c1">APPLIED</span><span class="pl-k">:</span> <span class="pl-c1">3</span>,
    <span class="pl-c1">READY</span><span class="pl-k">:</span> <span class="pl-c1">4</span>
};</pre></div>
<h5><a id="user-content-强制-命名空间-使用-camel命名法" class="anchor" aria-hidden="true" href="#强制-命名空间-使用-camel命名法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>命名空间</code> 使用 <code>Camel命名法</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-smi">equipments</span>.<span class="pl-smi">heavyWeapons</span> <span class="pl-k">=</span> {};</pre></div>
<h5><a id="user-content-强制-由多个单词组成的缩写词在命名中根据当前命名法和出现的位置所有字母的大小写与首字母的大小写保持一致" class="anchor" aria-hidden="true" href="#强制-由多个单词组成的缩写词在命名中根据当前命名法和出现的位置所有字母的大小写与首字母的大小写保持一致"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 由多个单词组成的缩写词，在命名中，根据当前命名法和出现的位置，所有字母的大小写与首字母的大小写保持一致。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">XMLParser</span>() {
}

<span class="pl-k">function</span> <span class="pl-en">insertHTML</span>(<span class="pl-smi">element</span>, <span class="pl-smi">html</span>) {
}

<span class="pl-k">var</span> httpRequest <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">HTTPRequest</span>();</pre></div>
<h5><a id="user-content-强制-类名-使用-名词" class="anchor" aria-hidden="true" href="#强制-类名-使用-名词"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] <code>类名</code> 使用 <code>名词</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">Engine</span>(<span class="pl-smi">options</span>) {
}</pre></div>
<h5><a id="user-content-建议-函数名-使用-动宾短语" class="anchor" aria-hidden="true" href="#建议-函数名-使用-动宾短语"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] <code>函数名</code> 使用 <code>动宾短语</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">getStyle</span>(<span class="pl-smi">element</span>) {
}</pre></div>
<h5><a id="user-content-建议-boolean-类型的变量使用-is-或-has-开头" class="anchor" aria-hidden="true" href="#建议-boolean-类型的变量使用-is-或-has-开头"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] <code>boolean</code> 类型的变量使用 <code>is</code> 或 <code>has</code> 开头。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> isReady <span class="pl-k">=</span> <span class="pl-c1">false</span>;
<span class="pl-k">var</span> hasMoreCommands <span class="pl-k">=</span> <span class="pl-c1">false</span>;</pre></div>
<h5><a id="user-content-建议-promise对象-用-动宾短语的进行时-表达" class="anchor" aria-hidden="true" href="#建议-promise对象-用-动宾短语的进行时-表达"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] <code>Promise对象</code> 用 <code>动宾短语的进行时</code> 表达。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> loadingData <span class="pl-k">=</span> <span class="pl-smi">ajax</span>.<span class="pl-c1">get</span>(<span class="pl-s"><span class="pl-pds">'</span>url<span class="pl-pds">'</span></span>);
<span class="pl-smi">loadingData</span>.<span class="pl-c1">then</span>(callback);</pre></div>
<h3><a id="user-content-24-注释" class="anchor" aria-hidden="true" href="#24-注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4 注释</h3>
<h4><a id="user-content-241-单行注释" class="anchor" aria-hidden="true" href="#241-单行注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.1 单行注释</h4>
<h5><a id="user-content-强制-必须独占一行-后跟一个空格缩进与下一行被注释说明的代码一致" class="anchor" aria-hidden="true" href="#强制-必须独占一行-后跟一个空格缩进与下一行被注释说明的代码一致"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 必须独占一行。<code>//</code> 后跟一个空格，缩进与下一行被注释说明的代码一致。</h5>
<h4><a id="user-content-242-多行注释" class="anchor" aria-hidden="true" href="#242-多行注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.2 多行注释</h4>
<h5><a id="user-content-建议-避免使用--这样的多行注释有多行注释内容时使用多个单行注释" class="anchor" aria-hidden="true" href="#建议-避免使用--这样的多行注释有多行注释内容时使用多个单行注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 避免使用 <code>/*...*/</code> 这样的多行注释。有多行注释内容时，使用多个单行注释。</h5>
<h4><a id="user-content-243-文档化注释" class="anchor" aria-hidden="true" href="#243-文档化注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.3 文档化注释</h4>
<h5><a id="user-content-强制-为了便于代码阅读和自文档化以下内容必须包含以--形式的块注释中" class="anchor" aria-hidden="true" href="#强制-为了便于代码阅读和自文档化以下内容必须包含以--形式的块注释中"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 为了便于代码阅读和自文档化，以下内容必须包含以 <code>/**...*/</code> 形式的块注释中。</h5>
<p>解释：</p>
<ol>
<li>文件</li>
<li>namespace</li>
<li>类</li>
<li>函数或方法</li>
<li>类属性</li>
<li>事件</li>
<li>全局变量</li>
<li>常量</li>
<li>AMD 模块</li>
</ol>
<h5><a id="user-content-强制-文档注释前必须空一行" class="anchor" aria-hidden="true" href="#强制-文档注释前必须空一行"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 文档注释前必须空一行。</h5>
<h5><a id="user-content-建议-自文档化的文档说明-what而不是-how" class="anchor" aria-hidden="true" href="#建议-自文档化的文档说明-what而不是-how"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 自文档化的文档说明 what，而不是 how。</h5>
<h4><a id="user-content-244-类型定义" class="anchor" aria-hidden="true" href="#244-类型定义"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.4 类型定义</h4>
<h5><a id="user-content-强制-类型定义都是以开始-以结束" class="anchor" aria-hidden="true" href="#强制-类型定义都是以开始-以结束"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 类型定义都是以<code>{</code>开始, 以<code>}</code>结束。</h5>
<p>解释：</p>
<p>常用类型如：{string}, {number}, {boolean}, {Object}, {Function}, {RegExp}, {Array}, {Date}。</p>
<p>类型不仅局限于内置的类型，也可以是自定义的类型。比如定义了一个类 Developer，就可以使用它来定义一个参数和返回值的类型。</p>
<h5><a id="user-content-强制-对于基本类型-string-number-boolean首字母必须小写" class="anchor" aria-hidden="true" href="#强制-对于基本类型-string-number-boolean首字母必须小写"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 对于基本类型 {string}, {number}, {boolean}，首字母必须小写。</h5>
<table>
<thead>
<tr>
<th>类型定义</th>
<th>语法示例</th>
<th>解释</th>
</tr>
</thead>
<tbody>
<tr>
<td>String</td>
<td>{string}</td>
<td>--</td>
</tr>
<tr>
<td>Number</td>
<td>{number}</td>
<td>--</td>
</tr>
<tr>
<td>Boolean</td>
<td>{boolean}</td>
<td>--</td>
</tr>
<tr>
<td>Object</td>
<td>{Object}</td>
<td>--</td>
</tr>
<tr>
<td>Function</td>
<td>{Function}</td>
<td>--</td>
</tr>
<tr>
<td>RegExp</td>
<td>{RegExp}</td>
<td>--</td>
</tr>
<tr>
<td>Array</td>
<td>{Array}</td>
<td>--</td>
</tr>
<tr>
<td>Date</td>
<td>{Date}</td>
<td>--</td>
</tr>
<tr>
<td>单一类型集合</td>
<td>{Array.&lt;string&gt;}</td>
<td>string 类型的数组</td>
</tr>
<tr>
<td>多类型</td>
<td>{(number｜boolean)}</td>
<td>可能是 number 类型, 也可能是 boolean 类型</td>
</tr>
<tr>
<td>允许为null</td>
<td>{?number}</td>
<td>可能是 number, 也可能是 null</td>
</tr>
<tr>
<td>不允许为null</td>
<td>{!Object}</td>
<td>Object 类型, 但不是 null</td>
</tr>
<tr>
<td>Function类型</td>
<td>{function(number, boolean)}</td>
<td>函数, 形参类型</td>
</tr>
<tr>
<td>Function带返回值</td>
<td>{function(number, boolean):string}</td>
<td>函数, 形参, 返回值类型</td>
</tr>
<tr>
<td>参数可选</td>
<td>@param {string=} name</td>
<td>可选参数, =为类型后缀</td>
</tr>
<tr>
<td>可变参数</td>
<td>@param {...number} args</td>
<td>变长参数,  ...为类型前缀</td>
</tr>
<tr>
<td>任意类型</td>
<td>{*}</td>
<td>任意类型</td>
</tr>
<tr>
<td>可选任意类型</td>
<td>@param {*=} name</td>
<td>可选参数，类型不限</td>
</tr>
<tr>
<td>可变任意类型</td>
<td>@param {...*} args</td>
<td>变长参数，类型不限</td>
</tr></tbody></table>
<h4><a id="user-content-245-文件注释" class="anchor" aria-hidden="true" href="#245-文件注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.5 文件注释</h4>
<h5><a id="user-content-强制-文件顶部必须包含文件注释用-file-标识文件说明" class="anchor" aria-hidden="true" href="#强制-文件顶部必须包含文件注释用-file-标识文件说明"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 文件顶部必须包含文件注释，用 <code>@file</code> 标识文件说明。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * <span class="pl-k">@file</span> Describe the file</span>
<span class="pl-c"> <span class="pl-c">*/</span></span></pre></div>
<h5><a id="user-content-建议-文件注释中可以用-author-标识开发者信息" class="anchor" aria-hidden="true" href="#建议-文件注释中可以用-author-标识开发者信息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 文件注释中可以用 <code>@author</code> 标识开发者信息。</h5>
<p>解释：</p>
<p>开发者信息能够体现开发人员对文件的贡献，并且能够让遇到问题或希望了解相关信息的人找到维护人。通常情况文件在被创建时标识的是创建者。随着项目的进展，越来越多的人加入，参与这个文件的开发，新的作者应该被加入 <code>@author</code> 标识。</p>
<p><code>@author</code> 标识具有多人时，原则是按照 <code>责任</code> 进行排序。通常的说就是如果有问题，就是找第一个人应该比找第二个人有效。比如文件的创建者由于各种原因，模块移交给了其他人或其他团队，后来因为新增需求，其他人在新增代码时，添加 <code>@author</code> 标识应该把自己的名字添加在创建人的前面。</p>
<p><code>@author</code> 中的名字不允许被删除。任何劳动成果都应该被尊重。</p>
<p>业务项目中，一个文件可能被多人频繁修改，并且每个人的维护时间都可能不会很长，不建议为文件增加 <code>@author</code> 标识。通过版本控制系统追踪变更，按业务逻辑单元确定模块的维护责任人，通过文档与wiki跟踪和查询，是更好的责任管理方式。</p>
<p>对于业务逻辑无关的技术型基础项目，特别是开源的公共项目，应使用 <code>@author</code> 标识。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * <span class="pl-k">@file</span> Describe the file</span>
<span class="pl-c"> * <span class="pl-k">@author</span> <span class="pl-en">author-name(mail-name</span>@domain.com)</span>
<span class="pl-c"> *         author-name2(mail-name2@domain.com)</span>
<span class="pl-c"> <span class="pl-c">*/</span></span></pre></div>
<h4><a id="user-content-246-命名空间注释" class="anchor" aria-hidden="true" href="#246-命名空间注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.6 命名空间注释</h4>
<h5><a id="user-content-建议-命名空间使用-namespace-标识" class="anchor" aria-hidden="true" href="#建议-命名空间使用-namespace-标识"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 命名空间使用 <code>@namespace</code> 标识。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * <span class="pl-k">@namespace</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">var</span> util <span class="pl-k">=</span> {};</pre></div>
<h4><a id="user-content-247-类注释" class="anchor" aria-hidden="true" href="#247-类注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.7 类注释</h4>
<h5><a id="user-content-建议-使用-class-标记类或构造函数" class="anchor" aria-hidden="true" href="#建议-使用-class-标记类或构造函数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 使用 <code>@class</code> 标记类或构造函数。</h5>
<p>解释：</p>
<p>对于使用对象 <code>constructor</code> 属性来定义的构造函数，可以使用 <code>@constructor</code> 来标记。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 描述</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@class</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">Developer</span>() {
    <span class="pl-c"><span class="pl-c">//</span> constructor body</span>
}</pre></div>
<h5><a id="user-content-建议-使用-extends-标记类的继承信息" class="anchor" aria-hidden="true" href="#建议-使用-extends-标记类的继承信息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 使用 <code>@extends</code> 标记类的继承信息。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 描述</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@class</span></span>
<span class="pl-c"> * <span class="pl-k">@extends</span> <span class="pl-en">Developer</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">Fronteer</span>() {
    <span class="pl-smi">Developer</span>.<span class="pl-c1">call</span>(<span class="pl-c1">this</span>);
    <span class="pl-c"><span class="pl-c">//</span> constructor body</span>
}
<span class="pl-smi">util</span>.<span class="pl-en">inherits</span>(Fronteer, Developer);</pre></div>
<h5><a id="user-content-强制-使用包装方式扩展类成员时-必须通过-lends-进行重新指向" class="anchor" aria-hidden="true" href="#强制-使用包装方式扩展类成员时-必须通过-lends-进行重新指向"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 使用包装方式扩展类成员时， 必须通过 <code>@lends</code> 进行重新指向。</h5>
<p>解释：</p>
<p>没有 <code>@lends</code> 标记将无法为该类生成包含扩展类成员的文档。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 类描述</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@class</span></span>
<span class="pl-c"> * <span class="pl-k">@extends</span> <span class="pl-en">Developer</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">Fronteer</span>() {
    <span class="pl-smi">Developer</span>.<span class="pl-c1">call</span>(<span class="pl-c1">this</span>);
    <span class="pl-c"><span class="pl-c">//</span> constructor body</span>
}

<span class="pl-smi">util</span>.<span class="pl-en">extend</span>(
    <span class="pl-smi">Fronteer</span>.<span class="pl-c1">prototype</span>,
    <span class="pl-c"><span class="pl-c">/**</span> <span class="pl-k">@lends</span> <span class="pl-en">Fronteer.prototype</span> <span class="pl-c">*/</span></span>{
        <span class="pl-en">_getLevel</span><span class="pl-k">:</span> <span class="pl-k">function</span> () {
            <span class="pl-c"><span class="pl-c">//</span> TODO</span>
        }
    }
);</pre></div>
<h5><a id="user-content-强制-类的属性或方法等成员信息使用-public--protected--private-中的任意一个指明可访问性" class="anchor" aria-hidden="true" href="#强制-类的属性或方法等成员信息使用-public--protected--private-中的任意一个指明可访问性"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 类的属性或方法等成员信息使用 <code>@public</code> / <code>@protected</code> / <code>@private</code> 中的任意一个，指明可访问性。</h5>
<p>解释：</p>
<p>生成的文档中将有可访问性的标记，避免用户直接使用非 <code>public</code> 的属性或方法。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 类描述</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@class</span></span>
<span class="pl-c"> * <span class="pl-k">@extends</span> <span class="pl-en">Developer</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">var</span> <span class="pl-en">Fronteer</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-smi">Developer</span>.<span class="pl-c1">call</span>(<span class="pl-c1">this</span>);

    <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">     * 属性描述</span>
<span class="pl-c">     *</span>
<span class="pl-c">     * <span class="pl-k">@type</span> <span class="pl-en">{string}</span></span>
<span class="pl-c">     * <span class="pl-k">@private</span></span>
<span class="pl-c">     <span class="pl-c">*/</span></span>
    <span class="pl-c1">this</span>.<span class="pl-smi">_level</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>T12<span class="pl-pds">'</span></span>;

    <span class="pl-c"><span class="pl-c">//</span> constructor body</span>
};
<span class="pl-smi">util</span>.<span class="pl-en">inherits</span>(Fronteer, Developer);

<span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 方法描述</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@private</span></span>
<span class="pl-c"> * <span class="pl-k">@return</span> <span class="pl-en">{string}</span> 返回值描述</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-smi">Fronteer</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">_getLevel</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
};</pre></div>
<h4><a id="user-content-248-函数方法注释" class="anchor" aria-hidden="true" href="#248-函数方法注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.8 函数/方法注释</h4>
<h5><a id="user-content-强制-函数方法注释必须包含函数说明有参数和返回值时必须使用注释标识" class="anchor" aria-hidden="true" href="#强制-函数方法注释必须包含函数说明有参数和返回值时必须使用注释标识"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 函数/方法注释必须包含函数说明，有参数和返回值时必须使用注释标识。</h5>
<h5><a id="user-content-强制-参数和返回值注释必须包含类型信息和说明" class="anchor" aria-hidden="true" href="#强制-参数和返回值注释必须包含类型信息和说明"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 参数和返回值注释必须包含类型信息和说明。</h5>
<h5><a id="user-content-建议-当函数是内部函数外部不可访问时可以使用-inner-标识" class="anchor" aria-hidden="true" href="#建议-当函数是内部函数外部不可访问时可以使用-inner-标识"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 当函数是内部函数，外部不可访问时，可以使用 <code>@inner</code> 标识。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 函数描述</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">p1</span> 参数1的说明</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">p2</span> 参数2的说明，比较长</span>
<span class="pl-c"> *     那就换行了.</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{number=}</span> <span class="pl-smi">p3</span> 参数3的说明（可选）</span>
<span class="pl-c"> * <span class="pl-k">@return</span> <span class="pl-en">{Object}</span> 返回值描述</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">foo</span>(<span class="pl-smi">p1</span>, <span class="pl-smi">p2</span>, <span class="pl-smi">p3</span>) {
    <span class="pl-k">var</span> p3 <span class="pl-k">=</span> p3 <span class="pl-k">||</span> <span class="pl-c1">10</span>;
    <span class="pl-k">return</span> {
        p1<span class="pl-k">:</span> p1,
        p2<span class="pl-k">:</span> p2,
        p3<span class="pl-k">:</span> p3
    };
}</pre></div>
<h5><a id="user-content-强制-对-object-中各项的描述-必须使用-param-标识" class="anchor" aria-hidden="true" href="#强制-对-object-中各项的描述-必须使用-param-标识"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 对 Object 中各项的描述， 必须使用 <code>@param</code> 标识。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 函数描述</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{Object}</span> <span class="pl-smi">option</span> 参数描述</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">option.url</span> option项描述</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{string=}</span> <span class="pl-smi">option.method</span> option项描述，可选参数</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">foo</span>(<span class="pl-smi">option</span>) {
    <span class="pl-c"><span class="pl-c">//</span> TODO</span>
}</pre></div>
<h5><a id="user-content-建议-重写父类方法时-应当添加-override-标识如果重写的形参个数类型顺序和返回值类型均未发生变化可省略-paramreturn仅用-override-标识否则仍应作完整注释" class="anchor" aria-hidden="true" href="#建议-重写父类方法时-应当添加-override-标识如果重写的形参个数类型顺序和返回值类型均未发生变化可省略-paramreturn仅用-override-标识否则仍应作完整注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 重写父类方法时， 应当添加 <code>@override</code> 标识。如果重写的形参个数、类型、顺序和返回值类型均未发生变化，可省略 <code>@param</code>、<code>@return</code>，仅用 <code>@override</code> 标识，否则仍应作完整注释。</h5>
<p>解释：</p>
<p>简而言之，当子类重写的方法能直接套用父类的方法注释时可省略对参数与返回值的注释。</p>
<h4><a id="user-content-249-事件注释" class="anchor" aria-hidden="true" href="#249-事件注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.9 事件注释</h4>
<h5><a id="user-content-强制-必须使用-event-标识事件事件参数的标识与方法描述的参数标识相同" class="anchor" aria-hidden="true" href="#强制-必须使用-event-标识事件事件参数的标识与方法描述的参数标识相同"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 必须使用 <code>@event</code> 标识事件，事件参数的标识与方法描述的参数标识相同。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 值变更时触发</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@event</span></span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{Object}</span> <span class="pl-smi">e</span> e描述</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">e.before</span> before描述</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">e.after</span> after描述</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-en">onchange</span><span class="pl-k">:</span> <span class="pl-k">function</span> (<span class="pl-smi">e</span>) {
}</pre></div>
<h5><a id="user-content-强制-在会广播事件的函数前使用-fires-标识广播的事件在广播事件代码前使用-event-标识事件" class="anchor" aria-hidden="true" href="#强制-在会广播事件的函数前使用-fires-标识广播的事件在广播事件代码前使用-event-标识事件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 在会广播事件的函数前使用 <code>@fires</code> 标识广播的事件，在广播事件代码前使用 <code>@event</code> 标识事件。</h5>
<h5><a id="user-content-建议-对于事件对象的注释使用-param-标识生成文档时可读性更好" class="anchor" aria-hidden="true" href="#建议-对于事件对象的注释使用-param-标识生成文档时可读性更好"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于事件对象的注释，使用 <code>@param</code> 标识，生成文档时可读性更好。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 点击处理</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@fires</span> <span class="pl-en">Select#change</span></span>
<span class="pl-c"> * <span class="pl-k">@private</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-smi">Select</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">clickHandler</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">     * 值变更时触发</span>
<span class="pl-c">     *</span>
<span class="pl-c">     * <span class="pl-k">@event</span> <span class="pl-en">Select#change</span></span>
<span class="pl-c">     * <span class="pl-k">@param</span> <span class="pl-en">{Object}</span> <span class="pl-smi">e</span> e描述</span>
<span class="pl-c">     * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">e.before</span> before描述</span>
<span class="pl-c">     * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">e.after</span> after描述</span>
<span class="pl-c">     <span class="pl-c">*/</span></span>
    <span class="pl-c1">this</span>.<span class="pl-en">fire</span>(
        <span class="pl-s"><span class="pl-pds">'</span>change<span class="pl-pds">'</span></span>,
        {
            before<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>foo<span class="pl-pds">'</span></span>,
            after<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>bar<span class="pl-pds">'</span></span>
        }
    );
};</pre></div>
<h4><a id="user-content-2410-常量注释" class="anchor" aria-hidden="true" href="#2410-常量注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.10 常量注释</h4>
<h5><a id="user-content-强制-常量必须使用-const-标记并包含说明和类型信息" class="anchor" aria-hidden="true" href="#强制-常量必须使用-const-标记并包含说明和类型信息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 常量必须使用 <code>@const</code> 标记，并包含说明和类型信息。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 常量说明</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@const</span></span>
<span class="pl-c"> * <span class="pl-k">@type</span> <span class="pl-en">{string}</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">var</span> <span class="pl-c1">REQUEST_URL</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>myurl.do<span class="pl-pds">'</span></span>;</pre></div>
<h4><a id="user-content-2411-复杂类型注释" class="anchor" aria-hidden="true" href="#2411-复杂类型注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.11 复杂类型注释</h4>
<h5><a id="user-content-建议-对于类型未定义的复杂结构的注释可以使用-typedef-标识来定义" class="anchor" aria-hidden="true" href="#建议-对于类型未定义的复杂结构的注释可以使用-typedef-标识来定义"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于类型未定义的复杂结构的注释，可以使用 <code>@typedef</code> 标识来定义。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> `namespaceA~` 可以换成其它 namepaths 前缀，目的是为了生成文档中能显示 `@typedef` 定义的类型和链接。</span>
<span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 服务器</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@typedef</span> <span class="pl-en">{Object}</span> <span class="pl-en">namespaceA~Server</span></span>
<span class="pl-c"> * <span class="pl-k">@property</span> <span class="pl-en">{string}</span> <span class="pl-smi">host</span> 主机</span>
<span class="pl-c"> * <span class="pl-k">@property</span> <span class="pl-en">{number}</span> <span class="pl-smi">port</span> 端口</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>

<span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 服务器列表</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@type</span> <span class="pl-en">{Array.&lt;namespaceA~Server&gt;}</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">var</span> servers <span class="pl-k">=</span> [
    {
        host<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>1.2.3.4<span class="pl-pds">'</span></span>,
        port<span class="pl-k">:</span> <span class="pl-c1">8080</span>
    },
    {
        host<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>1.2.3.5<span class="pl-pds">'</span></span>,
        port<span class="pl-k">:</span> <span class="pl-c1">8081</span>
    }
];</pre></div>
<h4><a id="user-content-2412-amd-模块注释" class="anchor" aria-hidden="true" href="#2412-amd-模块注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.12 AMD 模块注释</h4>
<h5><a id="user-content-强制-amd-模块使用-module-或-exports-标识" class="anchor" aria-hidden="true" href="#强制-amd-模块使用-module-或-exports-标识"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] AMD 模块使用 <code>@module</code> 或 <code>@exports</code> 标识。</h5>
<p>解释：</p>
<p>@exports 与 @module 都可以用来标识模块，区别在于 @module 可以省略模块名称。而只使用 @exports 时在 namepaths 中可以省略 module: 前缀。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">define</span>(
    <span class="pl-k">function</span> (<span class="pl-smi">require</span>) {

        <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">         * foo description</span>
<span class="pl-c">         *</span>
<span class="pl-c">         * <span class="pl-k">@exports</span> <span class="pl-en">Foo</span></span>
<span class="pl-c">         <span class="pl-c">*/</span></span>
        <span class="pl-k">var</span> foo <span class="pl-k">=</span> {
            <span class="pl-c"><span class="pl-c">//</span> TODO</span>
        };

        <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">         * baz description</span>
<span class="pl-c">         *</span>
<span class="pl-c">         * <span class="pl-k">@return</span> <span class="pl-en">{boolean}</span> return description</span>
<span class="pl-c">         <span class="pl-c">*/</span></span>
        <span class="pl-smi">foo</span>.<span class="pl-en">baz</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
            <span class="pl-c"><span class="pl-c">//</span> TODO</span>
        };

        <span class="pl-k">return</span> foo;

    }
);</pre></div>
<p>也可以在 exports 变量前使用 @module 标识：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">define</span>(
    <span class="pl-k">function</span> (<span class="pl-smi">require</span>) {

        <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">         * module description.</span>
<span class="pl-c">         *</span>
<span class="pl-c">         * <span class="pl-k">@module</span> <span class="pl-en">foo</span></span>
<span class="pl-c">         <span class="pl-c">*/</span></span>
        <span class="pl-k">var</span> <span class="pl-c1">exports</span> <span class="pl-k">=</span> {};


        <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">         * bar description</span>
<span class="pl-c">         *</span>
<span class="pl-c">         <span class="pl-c">*/</span></span>
        <span class="pl-c1">exports</span>.<span class="pl-en">bar</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
            <span class="pl-c"><span class="pl-c">//</span> TODO</span>
        };

        <span class="pl-k">return</span> <span class="pl-c1">exports</span>;
    }
);</pre></div>
<p>如果直接使用 factory 的 exports 参数，还可以：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * module description.</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@module</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-en">define</span>(
    <span class="pl-k">function</span> (<span class="pl-smi">require</span>, <span class="pl-c1">exports</span>) {

        <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">         * bar description</span>
<span class="pl-c">         *</span>
<span class="pl-c">         <span class="pl-c">*/</span></span>
        <span class="pl-c1">exports</span>.<span class="pl-en">bar</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
            <span class="pl-c"><span class="pl-c">//</span> TODO</span>
        };
        <span class="pl-k">return</span> <span class="pl-c1">exports</span>;
    }
);</pre></div>
<h5><a id="user-content-强制-对于已使用-module-标识为-amd模块-的引用在-namepaths-中必须增加-module-作前缀" class="anchor" aria-hidden="true" href="#强制-对于已使用-module-标识为-amd模块-的引用在-namepaths-中必须增加-module-作前缀"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 对于已使用 <code>@module</code> 标识为 AMD模块 的引用，在 <code>namepaths</code> 中必须增加 <code>module:</code> 作前缀。</h5>
<p>解释：</p>
<p>namepaths 没有 module: 前缀时，生成的文档中将无法正确生成链接。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 点击处理</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@fires</span> <span class="pl-en">module:Select#change</span></span>
<span class="pl-c"> * <span class="pl-k">@private</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-smi">Select</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">clickHandler</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">     * 值变更时触发</span>
<span class="pl-c">     *</span>
<span class="pl-c">     * <span class="pl-k">@event</span> <span class="pl-en">module:Select#change</span></span>
<span class="pl-c">     * <span class="pl-k">@param</span> <span class="pl-en">{Object}</span> <span class="pl-smi">e</span> e描述</span>
<span class="pl-c">     * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">e.before</span> before描述</span>
<span class="pl-c">     * <span class="pl-k">@param</span> <span class="pl-en">{string}</span> <span class="pl-smi">e.after</span> after描述</span>
<span class="pl-c">     <span class="pl-c">*/</span></span>
    <span class="pl-c1">this</span>.<span class="pl-en">fire</span>(
        <span class="pl-s"><span class="pl-pds">'</span>change<span class="pl-pds">'</span></span>,
        {
            before<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>foo<span class="pl-pds">'</span></span>,
            after<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>bar<span class="pl-pds">'</span></span>
        }
    );
};</pre></div>
<h5><a id="user-content-建议-对于类定义的模块可以使用-alias-标识构建函数" class="anchor" aria-hidden="true" href="#建议-对于类定义的模块可以使用-alias-标识构建函数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于类定义的模块，可以使用 <code>@alias</code> 标识构建函数。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * A module representing a jacket.</span>
<span class="pl-c"> * <span class="pl-k">@module</span> <span class="pl-en">jacket</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-en">define</span>(
    <span class="pl-k">function</span> () {

        <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">         * <span class="pl-k">@class</span></span>
<span class="pl-c">         * <span class="pl-k">@alias</span> <span class="pl-en">module:jacket</span></span>
<span class="pl-c">         <span class="pl-c">*/</span></span>
        <span class="pl-k">var</span> <span class="pl-en">Jacket</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
        };

        <span class="pl-k">return</span> Jacket;
    }
);</pre></div>
<h5><a id="user-content-建议-多模块定义时可以使用-exports-标识各个模块" class="anchor" aria-hidden="true" href="#建议-多模块定义时可以使用-exports-标识各个模块"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 多模块定义时，可以使用 <code>@exports</code> 标识各个模块。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> one module</span>
<span class="pl-en">define</span>(<span class="pl-s"><span class="pl-pds">'</span>html/utils<span class="pl-pds">'</span></span>,
    <span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c">     * Utility functions to ease working with DOM elements.</span>
<span class="pl-c">     * <span class="pl-k">@exports</span> <span class="pl-en">html/utils</span></span>
<span class="pl-c">     <span class="pl-c">*/</span></span>
    <span class="pl-k">function</span> () {
        <span class="pl-k">var</span> <span class="pl-c1">exports</span> <span class="pl-k">=</span> {
        };

        <span class="pl-k">return</span> <span class="pl-c1">exports</span>;
    }
);

<span class="pl-c"><span class="pl-c">//</span> another module</span>
<span class="pl-en">define</span>(<span class="pl-s"><span class="pl-pds">'</span>tag<span class="pl-pds">'</span></span>,
    <span class="pl-c"><span class="pl-c">/**</span> <span class="pl-k">@exports</span> <span class="pl-en">tag</span> <span class="pl-c">*/</span></span>
    <span class="pl-k">function</span> () {
        <span class="pl-k">var</span> <span class="pl-c1">exports</span> <span class="pl-k">=</span> {
        };

        <span class="pl-k">return</span> <span class="pl-c1">exports</span>;
    }
);</pre></div>
<h5><a id="user-content-建议-对于-exports-为-object-的模块可以使用namespace标识" class="anchor" aria-hidden="true" href="#建议-对于-exports-为-object-的模块可以使用namespace标识"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于 exports 为 Object 的模块，可以使用<code>@namespace</code>标识。</h5>
<p>解释：</p>
<p>使用 @namespace 而不是 @module 或 @exports 时，对模块的引用可以省略 module: 前缀。</p>
<h5><a id="user-content-建议-对于-exports-为类名的模块使用-class-和-exports-标识" class="anchor" aria-hidden="true" href="#建议-对于-exports-为类名的模块使用-class-和-exports-标识"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于 exports 为类名的模块，使用 <code>@class</code> 和 <code>@exports</code> 标识。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 只使用 @class Bar 时，类方法和属性都必须增加 @name Bar#methodName 来标识，与 @exports 配合可以免除这一麻烦，并且在引用时可以省去 module: 前缀。</span>
<span class="pl-c"><span class="pl-c">//</span> 另外需要注意类名需要使用 var 定义的方式。</span>

<span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * Bar description</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@see</span> <span class="pl-en">foo</span></span>
<span class="pl-c"> * <span class="pl-k">@exports</span>  <span class="pl-en">Bar</span></span>
<span class="pl-c"> * <span class="pl-k">@class</span></span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">var</span> <span class="pl-en">Bar</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-c"><span class="pl-c">//</span> TODO</span>
};

<span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * baz description</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@return</span> <span class="pl-en">{(string|Array)}</span> return description</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-smi">Bar</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">baz</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-c"><span class="pl-c">//</span> TODO</span>
};</pre></div>
<h4><a id="user-content-2413-细节注释" class="anchor" aria-hidden="true" href="#2413-细节注释"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.4.13 细节注释</h4>
<p>对于内部实现、不容易理解的逻辑说明、摘要信息等，我们可能需要编写细节注释。</p>
<h4><a id="user-content-建议-细节注释遵循单行注释的格式说明必须换行时每行是一个单行注释的起始" class="anchor" aria-hidden="true" href="#建议-细节注释遵循单行注释的格式说明必须换行时每行是一个单行注释的起始"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 细节注释遵循单行注释的格式。说明必须换行时，每行是一个单行注释的起始。</h4>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">foo</span>(<span class="pl-smi">p1</span>, <span class="pl-smi">p2</span>, <span class="pl-smi">opt_p3</span>) {
    <span class="pl-c"><span class="pl-c">//</span> 这里对具体内部逻辑进行说明</span>
    <span class="pl-c"><span class="pl-c">//</span> 说明太长需要换行</span>
    <span class="pl-k">for</span> (<span class="pl-k">...</span>) {
        <span class="pl-k">...</span>.
    }
}</pre></div>
<h5><a id="user-content-强制-有时我们会使用一些特殊标记进行说明特殊标记必须使用单行注释的形式下面列举了一些常用标记" class="anchor" aria-hidden="true" href="#强制-有时我们会使用一些特殊标记进行说明特殊标记必须使用单行注释的形式下面列举了一些常用标记"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 有时我们会使用一些特殊标记进行说明。特殊标记必须使用单行注释的形式。下面列举了一些常用标记：</h5>
<p>解释：</p>
<ol>
<li>TODO: 有功能待实现。此时需要对将要实现的功能进行简单说明。</li>
<li>FIXME: 该处代码运行没问题，但可能由于时间赶或者其他原因，需要修正。此时需要对如何修正进行简单说明。</li>
<li>HACK: 为修正某些问题而写的不太好或者使用了某些诡异手段的代码。此时需要对思路或诡异手段进行描述。</li>
<li>XXX: 该处存在陷阱。此时需要对陷阱进行描述。</li>
</ol>
<h2><a id="user-content-3-语言特性" class="anchor" aria-hidden="true" href="#3-语言特性"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3 语言特性</h2>
<h3><a id="user-content-31-变量" class="anchor" aria-hidden="true" href="#31-变量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.1 变量</h3>
<h5><a id="user-content-强制-变量在使用前必须通过-var-定义" class="anchor" aria-hidden="true" href="#强制-变量在使用前必须通过-var-定义"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 变量在使用前必须通过 <code>var</code> 定义。</h5>
<p>解释：</p>
<p>不通过 var 定义变量将导致变量污染全局环境。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>MyName<span class="pl-pds">'</span></span>;

<span class="pl-c"><span class="pl-c">//</span> bad</span>
name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>MyName<span class="pl-pds">'</span></span>;</pre></div>
<h5><a id="user-content-强制-每个-var-只能声明一个变量" class="anchor" aria-hidden="true" href="#强制-每个-var-只能声明一个变量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 每个 <code>var</code> 只能声明一个变量。</h5>
<p>解释：</p>
<p>一个 var 声明多个变量，容易导致较长的行长度，并且在修改时容易造成逗号和分号的混淆。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> hangModules <span class="pl-k">=</span> [];
<span class="pl-k">var</span> missModules <span class="pl-k">=</span> [];
<span class="pl-k">var</span> visited <span class="pl-k">=</span> {};

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> hangModules <span class="pl-k">=</span> [],
    missModules <span class="pl-k">=</span> [],
    visited <span class="pl-k">=</span> {};</pre></div>
<h5><a id="user-content-强制-变量必须-即用即声明不得在函数或其它形式的代码块起始位置统一声明所有变量" class="anchor" aria-hidden="true" href="#强制-变量必须-即用即声明不得在函数或其它形式的代码块起始位置统一声明所有变量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 变量必须 <code>即用即声明</code>，不得在函数或其它形式的代码块起始位置统一声明所有变量。</h5>
<p>解释：</p>
<p>变量声明与使用的距离越远，出现的跨度越大，代码的阅读与维护成本越高。虽然JavaScript的变量是函数作用域，还是应该根据编程中的意图，缩小变量出现的距离空间。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">function</span> <span class="pl-en">kv2List</span>(<span class="pl-smi">source</span>) {
    <span class="pl-k">var</span> list <span class="pl-k">=</span> [];

    <span class="pl-k">for</span> (<span class="pl-k">var</span> key <span class="pl-k">in</span> source) {
        <span class="pl-k">if</span> (<span class="pl-smi">source</span>.<span class="pl-en">hasOwnProperty</span>(key)) {
            <span class="pl-k">var</span> item <span class="pl-k">=</span> {
                k<span class="pl-k">:</span> key,
                v<span class="pl-k">:</span> source[key]
            };
            <span class="pl-smi">list</span>.<span class="pl-c1">push</span>(item);
        }
    }

    <span class="pl-k">return</span> list;
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">function</span> <span class="pl-en">kv2List</span>(<span class="pl-smi">source</span>) {
    <span class="pl-k">var</span> list <span class="pl-k">=</span> [];
    <span class="pl-k">var</span> key;
    <span class="pl-k">var</span> item;

    <span class="pl-k">for</span> (key <span class="pl-k">in</span> source) {
        <span class="pl-k">if</span> (<span class="pl-smi">source</span>.<span class="pl-en">hasOwnProperty</span>(key)) {
            item <span class="pl-k">=</span> {
                k<span class="pl-k">:</span> key,
                v<span class="pl-k">:</span> source[key]
            };
            <span class="pl-smi">list</span>.<span class="pl-c1">push</span>(item);
        }
    }

    <span class="pl-k">return</span> list;
}</pre></div>
<h3><a id="user-content-32-条件" class="anchor" aria-hidden="true" href="#32-条件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.2 条件</h3>
<h5><a id="user-content-强制-在-equality-expression-中使用类型严格的-仅当判断-null-或-undefined-时允许使用--null" class="anchor" aria-hidden="true" href="#强制-在-equality-expression-中使用类型严格的-仅当判断-null-或-undefined-时允许使用--null"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 在 Equality Expression 中使用类型严格的 <code>===</code>。仅当判断 null 或 undefined 时，允许使用 <code>== null</code>。</h5>
<p>解释：</p>
<p>使用 === 可以避免等于判断中隐式的类型转换。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (age <span class="pl-k">===</span> <span class="pl-c1">30</span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (age <span class="pl-k">==</span> <span class="pl-c1">30</span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<h5><a id="user-content-建议-尽可能使用简洁的表达式" class="anchor" aria-hidden="true" href="#建议-尽可能使用简洁的表达式"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 尽可能使用简洁的表达式。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 字符串为空</span>

<span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (<span class="pl-k">!</span>name) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (name <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 字符串非空</span>

<span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (name) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (name <span class="pl-k">!==</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 数组非空</span>

<span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (<span class="pl-smi">collection</span>.<span class="pl-c1">length</span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (<span class="pl-smi">collection</span>.<span class="pl-c1">length</span> <span class="pl-k">&gt;</span> <span class="pl-c1">0</span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 布尔不成立</span>

<span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (<span class="pl-k">!</span>notTrue) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (notTrue <span class="pl-k">===</span> <span class="pl-c1">false</span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> null 或 undefined</span>

<span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">if</span> (noValue <span class="pl-k">==</span> <span class="pl-c1">null</span>) {
  <span class="pl-c"><span class="pl-c">//</span> ......</span>
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">if</span> (noValue <span class="pl-k">===</span> <span class="pl-c1">null</span> <span class="pl-k">||</span> <span class="pl-k">typeof</span> noValue <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>undefined<span class="pl-pds">'</span></span>) {
  <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<h5><a id="user-content-建议-按执行频率排列分支的顺序" class="anchor" aria-hidden="true" href="#建议-按执行频率排列分支的顺序"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 按执行频率排列分支的顺序。</h5>
<p>解释：</p>
<p>按执行频率排列分支的顺序好处是：</p>
<ol>
<li>阅读的人容易找到最常见的情况，增加可读性。</li>
<li>提高执行效率。</li>
</ol>
<h5><a id="user-content-建议-对于相同变量或表达式的多值条件用-switch-代替-if" class="anchor" aria-hidden="true" href="#建议-对于相同变量或表达式的多值条件用-switch-代替-if"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于相同变量或表达式的多值条件，用 <code>switch</code> 代替 <code>if</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">switch</span> (<span class="pl-k">typeof</span> variable) {
    <span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>object<span class="pl-pds">'</span></span>:
        <span class="pl-c"><span class="pl-c">//</span> ......</span>
        <span class="pl-k">break</span>;
    <span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>number<span class="pl-pds">'</span></span>:
    <span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>boolean<span class="pl-pds">'</span></span>:
    <span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">'</span>string<span class="pl-pds">'</span></span>:
        <span class="pl-c"><span class="pl-c">//</span> ......</span>
        <span class="pl-k">break</span>;
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> type <span class="pl-k">=</span> <span class="pl-k">typeof</span> variable;
<span class="pl-k">if</span> (type <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>object<span class="pl-pds">'</span></span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
} 
<span class="pl-k">else</span> <span class="pl-k">if</span> (type <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>number<span class="pl-pds">'</span></span> <span class="pl-k">||</span> type <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>boolean<span class="pl-pds">'</span></span> <span class="pl-k">||</span> type <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>string<span class="pl-pds">'</span></span>) {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<h5><a id="user-content-建议-如果函数或全局中的-else-块后没有任何语句可以删除-else" class="anchor" aria-hidden="true" href="#建议-如果函数或全局中的-else-块后没有任何语句可以删除-else"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 如果函数或全局中的 <code>else</code> 块后没有任何语句，可以删除 <code>else</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">function</span> <span class="pl-en">getName</span>() {
    <span class="pl-k">if</span> (name) {
        <span class="pl-k">return</span> name;
    }

    <span class="pl-k">return</span> <span class="pl-s"><span class="pl-pds">'</span>unnamed<span class="pl-pds">'</span></span>;
}

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">function</span> <span class="pl-en">getName</span>() {
    <span class="pl-k">if</span> (name) {
        <span class="pl-k">return</span> name;
    }
    <span class="pl-k">else</span> {
        <span class="pl-k">return</span> <span class="pl-s"><span class="pl-pds">'</span>unnamed<span class="pl-pds">'</span></span>;
    }
}</pre></div>
<h3><a id="user-content-33-循环" class="anchor" aria-hidden="true" href="#33-循环"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.3 循环</h3>
<h5><a id="user-content-建议-不要在循环体中包含函数表达式事先将函数提取到循环体外" class="anchor" aria-hidden="true" href="#建议-不要在循环体中包含函数表达式事先将函数提取到循环体外"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 不要在循环体中包含函数表达式，事先将函数提取到循环体外。</h5>
<p>解释：</p>
<p>循环体中的函数表达式，运行过程中会生成循环次数个函数对象。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">function</span> <span class="pl-en">clicker</span>() {
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}

<span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>, len <span class="pl-k">=</span> <span class="pl-smi">elements</span>.<span class="pl-c1">length</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
    <span class="pl-k">var</span> element <span class="pl-k">=</span> elements[i];
    <span class="pl-en">addListener</span>(element, <span class="pl-s"><span class="pl-pds">'</span>click<span class="pl-pds">'</span></span>, clicker);
}


<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>, len <span class="pl-k">=</span> <span class="pl-smi">elements</span>.<span class="pl-c1">length</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
    <span class="pl-k">var</span> element <span class="pl-k">=</span> elements[i];
    <span class="pl-en">addListener</span>(element, <span class="pl-s"><span class="pl-pds">'</span>click<span class="pl-pds">'</span></span>, <span class="pl-k">function</span> () {});
}</pre></div>
<h5><a id="user-content-建议-对循环内多次使用的不变值在循环外用变量缓存" class="anchor" aria-hidden="true" href="#建议-对循环内多次使用的不变值在循环外用变量缓存"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对循环内多次使用的不变值，在循环外用变量缓存。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> width <span class="pl-k">=</span> <span class="pl-smi">wrap</span>.<span class="pl-smi">offsetWidth</span> <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>px<span class="pl-pds">'</span></span>;
<span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>, len <span class="pl-k">=</span> <span class="pl-smi">elements</span>.<span class="pl-c1">length</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
    <span class="pl-k">var</span> element <span class="pl-k">=</span> elements[i];
    <span class="pl-smi">element</span>.<span class="pl-c1">style</span>.<span class="pl-c1">width</span> <span class="pl-k">=</span> width;
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}


<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>, len <span class="pl-k">=</span> <span class="pl-smi">elements</span>.<span class="pl-c1">length</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
    <span class="pl-k">var</span> element <span class="pl-k">=</span> elements[i];
    <span class="pl-smi">element</span>.<span class="pl-c1">style</span>.<span class="pl-c1">width</span> <span class="pl-k">=</span> <span class="pl-smi">wrap</span>.<span class="pl-smi">offsetWidth</span> <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>px<span class="pl-pds">'</span></span>;
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<h5><a id="user-content-建议-对有序集合进行遍历时缓存-length" class="anchor" aria-hidden="true" href="#建议-对有序集合进行遍历时缓存-length"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对有序集合进行遍历时，缓存 <code>length</code>。</h5>
<p>解释：</p>
<p>虽然现代浏览器都对数组长度进行了缓存，但对于一些宿主对象和老旧浏览器的数组对象，在每次 length 访问时会动态计算元素个数，此时缓存 length 能有效提高程序性能。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>, len <span class="pl-k">=</span> <span class="pl-smi">elements</span>.<span class="pl-c1">length</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
    <span class="pl-k">var</span> element <span class="pl-k">=</span> elements[i];
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<h5><a id="user-content-建议-对有序集合进行顺序无关的遍历时使用逆序遍历" class="anchor" aria-hidden="true" href="#建议-对有序集合进行顺序无关的遍历时使用逆序遍历"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对有序集合进行顺序无关的遍历时，使用逆序遍历。</h5>
<p>解释：</p>
<p>逆序遍历可以节省变量，代码比较优化。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> len <span class="pl-k">=</span> <span class="pl-smi">elements</span>.<span class="pl-c1">length</span>;
<span class="pl-k">while</span> (len<span class="pl-k">--</span>) {
    <span class="pl-k">var</span> element <span class="pl-k">=</span> elements[len];
    <span class="pl-c"><span class="pl-c">//</span> ......</span>
}</pre></div>
<h3><a id="user-content-34-类型" class="anchor" aria-hidden="true" href="#34-类型"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.4 类型</h3>
<h4><a id="user-content-341-类型检测" class="anchor" aria-hidden="true" href="#341-类型检测"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.4.1 类型检测</h4>
<h5><a id="user-content-建议-类型检测优先使用-typeof对象类型检测使用-instanceofnull-或-undefined-的检测使用--null" class="anchor" aria-hidden="true" href="#建议-类型检测优先使用-typeof对象类型检测使用-instanceofnull-或-undefined-的检测使用--null"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 类型检测优先使用 <code>typeof</code>。对象类型检测使用 <code>instanceof</code>。<code>null</code> 或 <code>undefined</code> 的检测使用 <code>== null</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> string</span>
<span class="pl-k">typeof</span> variable <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>string<span class="pl-pds">'</span></span>

<span class="pl-c"><span class="pl-c">//</span> number</span>
<span class="pl-k">typeof</span> variable <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>number<span class="pl-pds">'</span></span>

<span class="pl-c"><span class="pl-c">//</span> boolean</span>
<span class="pl-k">typeof</span> variable <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>boolean<span class="pl-pds">'</span></span>

<span class="pl-c"><span class="pl-c">//</span> Function</span>
<span class="pl-k">typeof</span> variable <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>function<span class="pl-pds">'</span></span>

<span class="pl-c"><span class="pl-c">//</span> Object</span>
<span class="pl-k">typeof</span> variable <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>object<span class="pl-pds">'</span></span>

<span class="pl-c"><span class="pl-c">//</span> RegExp</span>
variable <span class="pl-k">instanceof</span> <span class="pl-c1">RegExp</span>

<span class="pl-c"><span class="pl-c">//</span> Array</span>
variable <span class="pl-k">instanceof</span> <span class="pl-c1">Array</span>

<span class="pl-c"><span class="pl-c">//</span> null</span>
variable <span class="pl-k">===</span> <span class="pl-c1">null</span>

<span class="pl-c"><span class="pl-c">//</span> null or undefined</span>
variable <span class="pl-k">==</span> <span class="pl-c1">null</span>

<span class="pl-c"><span class="pl-c">//</span> undefined</span>
<span class="pl-k">typeof</span> variable <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>undefined<span class="pl-pds">'</span></span></pre></div>
<h4><a id="user-content-342-类型转换" class="anchor" aria-hidden="true" href="#342-类型转换"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.4.2 类型转换</h4>
<h5><a id="user-content-建议-转换成-string-时使用--" class="anchor" aria-hidden="true" href="#建议-转换成-string-时使用--"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 转换成 <code>string</code> 时，使用 <code>+ ''</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
num <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>;

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">new</span> <span class="pl-en">String</span>(num);
<span class="pl-smi">num</span>.<span class="pl-c1">toString</span>();
<span class="pl-c1">String</span>(num);</pre></div>
<h5><a id="user-content-建议-转换成-number-时通常使用-" class="anchor" aria-hidden="true" href="#建议-转换成-number-时通常使用-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 转换成 <code>number</code> 时，通常使用 <code>+</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">+</span>str;

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-c1">Number</span>(str);</pre></div>
<h5><a id="user-content-建议-string-转换成-number要转换的字符串结尾包含非数字并期望忽略时使用-parseint" class="anchor" aria-hidden="true" href="#建议-string-转换成-number要转换的字符串结尾包含非数字并期望忽略时使用-parseint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] <code>string</code> 转换成 <code>number</code>，要转换的字符串结尾包含非数字并期望忽略时，使用 <code>parseInt</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> width <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>200px<span class="pl-pds">'</span></span>;
<span class="pl-c1">parseInt</span>(width, <span class="pl-c1">10</span>);</pre></div>
<h5><a id="user-content-强制-使用-parseint-时必须指定进制" class="anchor" aria-hidden="true" href="#强制-使用-parseint-时必须指定进制"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 使用 <code>parseInt</code> 时，必须指定进制。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-c1">parseInt</span>(str, <span class="pl-c1">10</span>);

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-c1">parseInt</span>(str);</pre></div>
<h5><a id="user-content-建议-转换成-boolean-时使用-" class="anchor" aria-hidden="true" href="#建议-转换成-boolean-时使用-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 转换成 <code>boolean</code> 时，使用 <code>!!</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> num <span class="pl-k">=</span> <span class="pl-c1">3.14</span>;
<span class="pl-k">!!</span>num;</pre></div>
<h5><a id="user-content-建议-number-去除小数点使用-mathfloor--mathround--mathceil不使用-parseint" class="anchor" aria-hidden="true" href="#建议-number-去除小数点使用-mathfloor--mathround--mathceil不使用-parseint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] <code>number</code> 去除小数点，使用 <code>Math.floor / Math.round / Math.ceil</code>，不使用 <code>parseInt</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> num <span class="pl-k">=</span> <span class="pl-c1">3.14</span>;
<span class="pl-c1">Math</span>.<span class="pl-c1">ceil</span>(num);

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> num <span class="pl-k">=</span> <span class="pl-c1">3.14</span>;
<span class="pl-c1">parseInt</span>(num, <span class="pl-c1">10</span>);</pre></div>
<h3><a id="user-content-35-字符串" class="anchor" aria-hidden="true" href="#35-字符串"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.5 字符串</h3>
<h5><a id="user-content-强制-字符串开头和结束使用单引号-" class="anchor" aria-hidden="true" href="#强制-字符串开头和结束使用单引号-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 字符串开头和结束使用单引号 <code>'</code>。</h5>
<p>解释：</p>
<ol>
<li>输入单引号不需要按住 shift，方便输入。</li>
<li>实际使用中，字符串经常用来拼接 HTML。为方便 HTML 中包含双引号而不需要转义写法。</li>
</ol>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> str <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>我是一个字符串<span class="pl-pds">'</span></span>;
<span class="pl-k">var</span> html <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;div class="cls"&gt;拼接HTML可以省去双引号转义&lt;/div&gt;<span class="pl-pds">'</span></span>;</pre></div>
<h5><a id="user-content-建议-使用-数组-或--拼接字符串" class="anchor" aria-hidden="true" href="#建议-使用-数组-或--拼接字符串"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 使用 <code>数组</code> 或 <code>+</code> 拼接字符串。</h5>
<p>解释：</p>
<ol>
<li>使用 + 拼接字符串，如果拼接的全部是 StringLiteral，压缩工具可以对其进行自动合并的优化。所以，静态字符串建议使用 + 拼接。</li>
<li>在现代浏览器下，使用 + 拼接字符串，性能较数组的方式要高。</li>
<li>如需要兼顾老旧浏览器，应尽量使用数组拼接字符串。</li>
</ol>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 使用数组拼接字符串</span>
<span class="pl-k">var</span> str <span class="pl-k">=</span> [
    <span class="pl-c"><span class="pl-c">//</span> 推荐换行开始并缩进开始第一个字符串, 对齐代码, 方便阅读.</span>
    <span class="pl-s"><span class="pl-pds">'</span>&lt;ul&gt;<span class="pl-pds">'</span></span>,
        <span class="pl-s"><span class="pl-pds">'</span>&lt;li&gt;第一项&lt;/li&gt;<span class="pl-pds">'</span></span>,
        <span class="pl-s"><span class="pl-pds">'</span>&lt;li&gt;第二项&lt;/li&gt;<span class="pl-pds">'</span></span>,
    <span class="pl-s"><span class="pl-pds">'</span>&lt;/ul&gt;<span class="pl-pds">'</span></span>
].<span class="pl-c1">join</span>(<span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>);

<span class="pl-c"><span class="pl-c">//</span> 使用 + 拼接字符串</span>
<span class="pl-k">var</span> str2 <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span> <span class="pl-c"><span class="pl-c">//</span> 建议第一个为空字符串, 第二个换行开始并缩进开始, 对齐代码, 方便阅读</span>
    <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;ul&gt;<span class="pl-pds">'</span></span>,
    <span class="pl-k">+</span>    <span class="pl-s"><span class="pl-pds">'</span>&lt;li&gt;第一项&lt;/li&gt;<span class="pl-pds">'</span></span>,
    <span class="pl-k">+</span>    <span class="pl-s"><span class="pl-pds">'</span>&lt;li&gt;第二项&lt;/li&gt;<span class="pl-pds">'</span></span>,
    <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;/ul&gt;<span class="pl-pds">'</span></span>;</pre></div>
<h5><a id="user-content-建议-复杂的数据到视图字符串的转换过程选用一种模板引擎" class="anchor" aria-hidden="true" href="#建议-复杂的数据到视图字符串的转换过程选用一种模板引擎"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 复杂的数据到视图字符串的转换过程，选用一种模板引擎。</h5>
<p>解释：</p>
<p>使用模板引擎有如下好处：</p>
<ol>
<li>在开发过程中专注于数据，将视图生成的过程由另外一个层级维护，使程序逻辑结构更清晰。</li>
<li>优秀的模板引擎，通过模板编译技术和高质量的编译产物，能获得比手工拼接字符串更高的性能。</li>
</ol>
<ul>
<li>artTemplate: 体积较小，在所有环境下性能高，语法灵活。</li>
<li>dot.js: 体积小，在现代浏览器下性能高，语法灵活。</li>
<li>etpl: 体积较小，在所有环境下性能高，模板复用性高，语法灵活。</li>
<li>handlebars: 体积大，在所有环境下性能高，扩展性高。</li>
<li>hogon: 体积小，在现代浏览器下性能高。</li>
<li>nunjucks: 体积较大，性能一般，模板复用性高。</li>
</ul>
<h3><a id="user-content-36-对象" class="anchor" aria-hidden="true" href="#36-对象"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.6 对象</h3>
<h5><a id="user-content-强制-使用对象字面量--创建新-object" class="anchor" aria-hidden="true" href="#强制-使用对象字面量--创建新-object"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 使用对象字面量 <code>{}</code> 创建新 <code>Object</code>。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> obj <span class="pl-k">=</span> {};

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> obj <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Object</span>();</pre></div>
<h5><a id="user-content-强制-对象创建时如果一个对象的所有-属性-均可以不添加引号则所有-属性-不得添加引号" class="anchor" aria-hidden="true" href="#强制-对象创建时如果一个对象的所有-属性-均可以不添加引号则所有-属性-不得添加引号"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 对象创建时，如果一个对象的所有 <code>属性</code> 均可以不添加引号，则所有 <code>属性</code> 不得添加引号。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> info <span class="pl-k">=</span> {
    name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>someone<span class="pl-pds">'</span></span>,
    age<span class="pl-k">:</span> <span class="pl-c1">28</span>
};</pre></div>
<h5><a id="user-content-强制-对象创建时如果任何一个-属性-需要添加引号则所有-属性-必须添加-" class="anchor" aria-hidden="true" href="#强制-对象创建时如果任何一个-属性-需要添加引号则所有-属性-必须添加-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 对象创建时，如果任何一个 <code>属性</code> 需要添加引号，则所有 <code>属性</code> 必须添加 <code>'</code>。</h5>
<p>解释：</p>
<p>如果属性不符合 Identifier 和 NumberLiteral 的形式，就需要以 StringLiteral 的形式提供。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> info <span class="pl-k">=</span> {
    <span class="pl-s"><span class="pl-pds">'</span>name<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>someone<span class="pl-pds">'</span></span>,
    <span class="pl-s"><span class="pl-pds">'</span>age<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-c1">28</span>,
    <span class="pl-s"><span class="pl-pds">'</span>more-info<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>...<span class="pl-pds">'</span></span>
};

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> info <span class="pl-k">=</span> {
    name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>someone<span class="pl-pds">'</span></span>,
    age<span class="pl-k">:</span> <span class="pl-c1">28</span>,
    <span class="pl-s"><span class="pl-pds">'</span>more-info<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>...<span class="pl-pds">'</span></span>
};</pre></div>
<h5><a id="user-content-强制-不允许修改和扩展任何原生对象和宿主对象的原型" class="anchor" aria-hidden="true" href="#强制-不允许修改和扩展任何原生对象和宿主对象的原型"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 不允许修改和扩展任何原生对象和宿主对象的原型。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 以下行为绝对禁止</span>
<span class="pl-c1">String</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">trim</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
};</pre></div>
<h5><a id="user-content-建议-属性访问时尽量使用-" class="anchor" aria-hidden="true" href="#建议-属性访问时尽量使用-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 属性访问时，尽量使用 <code>.</code>。</h5>
<p>解释：</p>
<p>属性名符合 Identifier 的要求，就可以通过 <code>.</code> 来访问，否则就只能通过 <code>[expr]</code> 方式访问。</p>
<p>通常在 JavaScript 中声明的对象，属性命名是使用 Camel 命名法，用 <code>.</code> 来访问更清晰简洁。部分特殊的属性(比如来自后端的JSON)，可能采用不寻常的命名方式，可以通过 <code>[expr]</code> 方式访问。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-smi">info</span>.<span class="pl-smi">age</span>;
info[<span class="pl-s"><span class="pl-pds">'</span>more-info<span class="pl-pds">'</span></span>];</pre></div>
<h5><a id="user-content-建议-for-in-遍历对象时-使用-hasownproperty-过滤掉原型中的属性" class="anchor" aria-hidden="true" href="#建议-for-in-遍历对象时-使用-hasownproperty-过滤掉原型中的属性"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] <code>for in</code> 遍历对象时, 使用 <code>hasOwnProperty</code> 过滤掉原型中的属性。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> newInfo <span class="pl-k">=</span> {};
<span class="pl-k">for</span> (<span class="pl-k">var</span> key <span class="pl-k">in</span> info) {
    <span class="pl-k">if</span> (<span class="pl-smi">info</span>.<span class="pl-en">hasOwnProperty</span>(key)) {
        newInfo[key] <span class="pl-k">=</span> info[key];
    }
}</pre></div>
<h3><a id="user-content-37-数组" class="anchor" aria-hidden="true" href="#37-数组"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.7 数组</h3>
<h5><a id="user-content-强制-使用数组字面量--创建新数组除非想要创建的是指定长度的数组" class="anchor" aria-hidden="true" href="#强制-使用数组字面量--创建新数组除非想要创建的是指定长度的数组"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 使用数组字面量 <code>[]</code> 创建新数组，除非想要创建的是指定长度的数组。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-k">var</span> arr <span class="pl-k">=</span> [];

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> arr <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Array</span>();</pre></div>
<h5><a id="user-content-强制-遍历数组不使用-for-in" class="anchor" aria-hidden="true" href="#强制-遍历数组不使用-for-in"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 遍历数组不使用 <code>for in</code>。</h5>
<p>解释：</p>
<p>数组对象可能存在数字以外的属性, 这种情况下 for in 不会得到正确结果.</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> arr <span class="pl-k">=</span> [<span class="pl-s"><span class="pl-pds">'</span>a<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>b<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>c<span class="pl-pds">'</span></span>];
<span class="pl-smi">arr</span>.<span class="pl-smi">other</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>other things<span class="pl-pds">'</span></span>; <span class="pl-c"><span class="pl-c">//</span> 这里仅作演示, 实际中应使用Object类型</span>

<span class="pl-c"><span class="pl-c">//</span> 正确的遍历方式</span>
<span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>, len <span class="pl-k">=</span> <span class="pl-smi">arr</span>.<span class="pl-c1">length</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
    <span class="pl-en">console</span>.<span class="pl-c1">log</span>(i);
}

<span class="pl-c"><span class="pl-c">//</span> 错误的遍历方式</span>
<span class="pl-k">for</span> (i <span class="pl-k">in</span> arr) {
    <span class="pl-en">console</span>.<span class="pl-c1">log</span>(i);
}</pre></div>
<h5><a id="user-content-建议-不因为性能的原因自己实现数组排序功能尽量使用数组的-sort-方法" class="anchor" aria-hidden="true" href="#建议-不因为性能的原因自己实现数组排序功能尽量使用数组的-sort-方法"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 不因为性能的原因自己实现数组排序功能，尽量使用数组的 <code>sort</code> 方法。</h5>
<p>解释：</p>
<p>自己实现的常规排序算法，在性能上并不优于数组默认的 sort 方法。以下两种场景可以自己实现排序：</p>
<ol>
<li>需要稳定的排序算法，达到严格一致的排序结果。</li>
<li>数据特点鲜明，适合使用桶排。</li>
</ol>
<h5><a id="user-content-建议-清空数组使用-length--0" class="anchor" aria-hidden="true" href="#建议-清空数组使用-length--0"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 清空数组使用 <code>.length = 0</code>。</h5>
<h3><a id="user-content-38-函数" class="anchor" aria-hidden="true" href="#38-函数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.8 函数</h3>
<h4><a id="user-content-381-函数长度" class="anchor" aria-hidden="true" href="#381-函数长度"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.8.1 函数长度</h4>
<h5><a id="user-content-建议-一个函数的长度控制在-50-行以内" class="anchor" aria-hidden="true" href="#建议-一个函数的长度控制在-50-行以内"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 一个函数的长度控制在 <code>50</code> 行以内。</h5>
<p>解释：</p>
<p>将过多的逻辑单元混在一个大函数中，易导致难以维护。一个清晰易懂的函数应该完成单一的逻辑单元。复杂的操作应进一步抽取，通过函数的调用来体现流程。</p>
<p>特定算法等不可分割的逻辑允许例外。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">syncViewStateOnUserAction</span>() {
    <span class="pl-k">if</span> (<span class="pl-smi">x</span>.<span class="pl-c1">checked</span>) {
        <span class="pl-smi">y</span>.<span class="pl-c1">checked</span> <span class="pl-k">=</span> <span class="pl-c1">true</span>;
        <span class="pl-smi">z</span>.<span class="pl-c1">value</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>;
    }
    <span class="pl-k">else</span> {
        <span class="pl-smi">y</span>.<span class="pl-c1">checked</span> <span class="pl-k">=</span> <span class="pl-c1">false</span>;
    }

    <span class="pl-k">if</span> (<span class="pl-k">!</span><span class="pl-smi">a</span>.<span class="pl-c1">value</span>) {
        <span class="pl-smi">warning</span>.<span class="pl-smi">innerText</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Please enter it<span class="pl-pds">'</span></span>;
        <span class="pl-smi">submitButton</span>.<span class="pl-c1">disabled</span> <span class="pl-k">=</span> <span class="pl-c1">true</span>;
    }
    <span class="pl-k">else</span> {
        <span class="pl-smi">warning</span>.<span class="pl-smi">innerText</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>;
        <span class="pl-smi">submitButton</span>.<span class="pl-c1">disabled</span> <span class="pl-k">=</span> <span class="pl-c1">false</span>;
    }
}

<span class="pl-c"><span class="pl-c">//</span> 直接阅读该函数会难以明确其主线逻辑，因此下方是一种更合理的表达方式：</span>

<span class="pl-k">function</span> <span class="pl-en">syncViewStateOnUserAction</span>() {
    <span class="pl-en">syncXStateToView</span>();
    <span class="pl-en">checkAAvailability</span>();
}

<span class="pl-k">function</span> <span class="pl-en">syncXStateToView</span>() {
    <span class="pl-k">if</span> (<span class="pl-smi">x</span>.<span class="pl-c1">checked</span>) {
        <span class="pl-smi">y</span>.<span class="pl-c1">checked</span> <span class="pl-k">=</span> <span class="pl-c1">true</span>;
        <span class="pl-smi">z</span>.<span class="pl-c1">value</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>;
    }
    <span class="pl-k">else</span> {
        <span class="pl-smi">y</span>.<span class="pl-c1">checked</span> <span class="pl-k">=</span> <span class="pl-c1">false</span>;
    }
}

<span class="pl-k">function</span> <span class="pl-en">checkAAvailability</span>() {
    <span class="pl-k">if</span> (<span class="pl-k">!</span><span class="pl-smi">a</span>.<span class="pl-c1">value</span>) {
        <span class="pl-en">displayWarningForAMissing</span>();
    }
    <span class="pl-k">else</span> {
        <span class="pl-en">clearWarnignForA</span>();
    }
}</pre></div>
<h4><a id="user-content-382-参数设计" class="anchor" aria-hidden="true" href="#382-参数设计"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.8.2 参数设计</h4>
<h5><a id="user-content-建议-一个函数的参数控制在-6-个以内" class="anchor" aria-hidden="true" href="#建议-一个函数的参数控制在-6-个以内"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 一个函数的参数控制在 <code>6</code> 个以内。</h5>
<p>解释：</p>
<p>除去不定长参数以外，函数具备不同逻辑意义的参数建议控制在 6 个以内，过多参数会导致维护难度增大。</p>
<p>某些情况下，如使用 AMD Loader 的 require 加载多个模块时，其 callback 可能会存在较多参数，因此对函数参数的个数不做强制限制。</p>
<h5><a id="user-content-建议-通过-options-参数传递非数据输入型参数" class="anchor" aria-hidden="true" href="#建议-通过-options-参数传递非数据输入型参数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 通过 <code>options</code> 参数传递非数据输入型参数。</h5>
<p>解释：</p>
<p>有些函数的参数并不是作为算法的输入，而是对算法的某些分支条件判断之用，此类参数建议通过一个 options 参数传递。</p>
<p>如下函数：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 移除某个元素</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{Node}</span> <span class="pl-smi">element</span> 需要移除的元素</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{boolean}</span> <span class="pl-smi">removeEventListeners</span> 是否同时将所有注册在元素上的事件移除</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">removeElement</span>(<span class="pl-smi">element</span>, <span class="pl-smi">removeEventListeners</span>) {
    <span class="pl-smi">element</span>.<span class="pl-c1">parent</span>.<span class="pl-c1">removeChild</span>(element);
    <span class="pl-k">if</span> (removeEventListeners) {
        <span class="pl-smi">element</span>.<span class="pl-en">clearEventListeners</span>();
    }
}</pre></div>
<p>可以转换为下面的签名：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 移除某个元素</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{Node}</span> <span class="pl-smi">element</span> 需要移除的元素</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{Object}</span> <span class="pl-smi">options</span> 相关的逻辑配置</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{boolean}</span> <span class="pl-smi">options.removeEventListeners</span> 是否同时将所有注册在元素上的事件移除</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">removeElement</span>(<span class="pl-smi">element</span>, <span class="pl-smi">options</span>) {
    <span class="pl-smi">element</span>.<span class="pl-c1">parent</span>.<span class="pl-c1">removeChild</span>(element);
    <span class="pl-k">if</span> (<span class="pl-smi">options</span>.<span class="pl-smi">removeEventListeners</span>) {
        <span class="pl-smi">element</span>.<span class="pl-en">clearEventListeners</span>();
    }
}</pre></div>
<p>这种模式有几个显著的优势：</p>
<ul>
<li>boolean 型的配置项具备名称，从调用的代码上更易理解其表达的逻辑意义。</li>
<li>当配置项有增长时，无需无休止地增加参数个数，不会出现 removeElement(element, true, false, false, 3) 这样难以理解的调用代码。</li>
<li>当部分配置参数可选时，多个参数的形式非常难处理重载逻辑，而使用一个 options 对象只需判断属性是否存在，实现得以简化。</li>
</ul>
<h4><a id="user-content-383-闭包" class="anchor" aria-hidden="true" href="#383-闭包"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.8.3 闭包</h4>
<h5><a id="user-content-建议-在适当的时候将闭包内大对象置为-null" class="anchor" aria-hidden="true" href="#建议-在适当的时候将闭包内大对象置为-null"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 在适当的时候将闭包内大对象置为 <code>null</code>。</h5>
<p>解释：</p>
<p>在 JavaScript 中，无需特别的关键词就可以使用闭包，一个函数可以任意访问在其定义的作用域外的变量。需要注意的是，函数的作用域是静态的，即在定义时决定，与调用的时机和方式没有任何关系。</p>
<p>闭包会阻止一些变量的垃圾回收，对于较老旧的JavaScript引擎，可能导致外部所有变量均无法回收。</p>
<p>首先一个较为明确的结论是，以下内容会影响到闭包内变量的回收：</p>
<ul>
<li>嵌套的函数中是否有使用该变量。</li>
<li>嵌套的函数中是否有 <strong>直接调用eval</strong>。</li>
<li>是否使用了 with 表达式。</li>
</ul>
<p>Chakra、V8 和 SpiderMonkey 将受以上因素的影响，表现出不尽相同又较为相似的回收策略，而JScript.dll和Carakan则完全没有这方面的优化，会完整保留整个 LexicalEnvironment 中的所有变量绑定，造成一定的内存消耗。</p>
<p>由于对闭包内变量有回收优化策略的 Chakra、V8 和 SpiderMonkey 引擎的行为较为相似，因此可以总结如下，当返回一个函数 fn 时：</p>
<ol>
<li>如果 fn 的 [[Scope]] 是ObjectEnvironment（with 表达式生成 ObjectEnvironment，函数和 catch 表达式生成 DeclarativeEnvironment），则：
<ol>
<li>如果是 V8 引擎，则退出全过程。</li>
<li>如果是 SpiderMonkey，则处理该 ObjectEnvironment 的外层 LexicalEnvironment。</li>
</ol>
</li>
<li>获取当前 LexicalEnvironment 下的所有类型为 Function 的对象，对于每一个 Function 对象，分析其 FunctionBody：
<ol>
<li>如果 FunctionBody 中含有 <strong>直接调用eval</strong>，则退出全过程。</li>
<li>否则得到所有的 Identifier。</li>
<li>对于每一个 Identifier，设其为 name，根据查找变量引用的规则，从 LexicalEnvironment 中找出名称为 name 的绑定 binding。</li>
<li>对 binding 添加 notSwap 属性，其值为 true。</li>
</ol>
</li>
<li>检查当前 LexicalEnvironment 中的每一个变量绑定，如果该绑定有 notSwap 属性且值为 true，则：
<ol>
<li>如果是V8引擎，删除该绑定。</li>
<li>如果是SpiderMonkey，将该绑定的值设为 undefined，将删除 notSwap 属性。</li>
</ol>
</li>
</ol>
<p>对于Chakra引擎，暂无法得知是按 V8 的模式还是按 SpiderMonkey 的模式进行。</p>
<p>如果有 <strong>非常庞大</strong> 的对象，且预计会在 <strong>老旧的引擎</strong> 中执行，则使用闭包时，注意将闭包不需要的对象置为空引用。</p>
<h5><a id="user-content-建议-使用-iife-避免-lift-效应" class="anchor" aria-hidden="true" href="#建议-使用-iife-避免-lift-效应"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 使用 <code>IIFE</code> 避免 <code>Lift 效应</code>。</h5>
<p>解释：</p>
<p>在引用函数外部变量时，函数执行时外部变量的值由运行时决定而非定义时，最典型的场景如下：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> tasks <span class="pl-k">=</span> [];
<span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> <span class="pl-c1">5</span>; i<span class="pl-k">++</span>) {
    tasks[<span class="pl-smi">tasks</span>.<span class="pl-c1">length</span>] <span class="pl-k">=</span> <span class="pl-k">function</span> () {
        <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>Current cursor is at <span class="pl-pds">'</span></span> <span class="pl-k">+</span> i);
    };
}

<span class="pl-k">var</span> len <span class="pl-k">=</span> <span class="pl-smi">tasks</span>.<span class="pl-c1">length</span>;
<span class="pl-k">while</span> (len<span class="pl-k">--</span>) {
    tasks[len]();
}</pre></div>
<p>以上代码对 tasks 中的函数的执行均会输出 <code>Current cursor is at 5</code>，往往不符合预期。</p>
<p>此现象称为 <strong>Lift 效应</strong> 。解决的方式是通过额外加上一层闭包函数，将需要的外部变量作为参数传递来解除变量的绑定关系：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> tasks <span class="pl-k">=</span> [];
<span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> <span class="pl-c1">5</span>; i<span class="pl-k">++</span>) {
    <span class="pl-c"><span class="pl-c">//</span> 注意有一层额外的闭包</span>
    tasks[<span class="pl-smi">tasks</span>.<span class="pl-c1">length</span>] <span class="pl-k">=</span> (<span class="pl-k">function</span> (<span class="pl-smi">i</span>) {
        <span class="pl-k">return</span> <span class="pl-k">function</span> () {
            <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">'</span>Current cursor is at <span class="pl-pds">'</span></span> <span class="pl-k">+</span> i);
        };
    })(i);
}

<span class="pl-k">var</span> len <span class="pl-k">=</span> <span class="pl-smi">tasks</span>.<span class="pl-c1">length</span>;
<span class="pl-k">while</span> (len<span class="pl-k">--</span>) {
    tasks[len]();
}</pre></div>
<h4><a id="user-content-384-空函数" class="anchor" aria-hidden="true" href="#384-空函数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.8.4 空函数</h4>
<h5><a id="user-content-建议-空函数不使用-new-function-的形式" class="anchor" aria-hidden="true" href="#建议-空函数不使用-new-function-的形式"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 空函数不使用 <code>new Function()</code> 的形式。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> <span class="pl-en">emptyFunction</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {};</pre></div>
<h5><a id="user-content-建议-对于性能有高要求的场合建议存在一个空函数的常量供多处使用共享" class="anchor" aria-hidden="true" href="#建议-对于性能有高要求的场合建议存在一个空函数的常量供多处使用共享"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于性能有高要求的场合，建议存在一个空函数的常量，供多处使用共享。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> <span class="pl-en">EMPTY_FUNCTION</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {};

<span class="pl-k">function</span> <span class="pl-en">MyClass</span>() {
}

<span class="pl-smi">MyClass</span>.<span class="pl-c1">prototype</span>.<span class="pl-smi">abstractMethod</span> <span class="pl-k">=</span> <span class="pl-c1">EMPTY_FUNCTION</span>;
<span class="pl-smi">MyClass</span>.<span class="pl-c1">prototype</span>.<span class="pl-smi">hooks</span>.<span class="pl-smi">before</span> <span class="pl-k">=</span> <span class="pl-c1">EMPTY_FUNCTION</span>;
<span class="pl-smi">MyClass</span>.<span class="pl-c1">prototype</span>.<span class="pl-smi">hooks</span>.<span class="pl-smi">after</span> <span class="pl-k">=</span> <span class="pl-c1">EMPTY_FUNCTION</span>;</pre></div>
<h3><a id="user-content-39-面向对象" class="anchor" aria-hidden="true" href="#39-面向对象"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.9 面向对象</h3>
<h5><a id="user-content-强制-类的继承方案实现时需要修正-constructor" class="anchor" aria-hidden="true" href="#强制-类的继承方案实现时需要修正-constructor"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 类的继承方案，实现时需要修正 <code>constructor</code>。</h5>
<p>解释：</p>
<p>通常使用其他 library 的类继承方案都会进行 constructor 修正。如果是自己实现的类继承方案，需要进行 constructor 修正。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">/**</span></span>
<span class="pl-c"> * 构建类之间的继承关系</span>
<span class="pl-c"> * </span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{Function}</span> <span class="pl-smi">subClass</span> 子类函数</span>
<span class="pl-c"> * <span class="pl-k">@param</span> <span class="pl-en">{Function}</span> <span class="pl-smi">superClass</span> 父类函数</span>
<span class="pl-c"> <span class="pl-c">*/</span></span>
<span class="pl-k">function</span> <span class="pl-en">inherits</span>(<span class="pl-smi">subClass</span>, <span class="pl-smi">superClass</span>) {
    <span class="pl-k">var</span> <span class="pl-c1">F</span> <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Function</span>();
    <span class="pl-c1">F</span>.<span class="pl-c1">prototype</span> <span class="pl-k">=</span> <span class="pl-smi">superClass</span>.<span class="pl-c1">prototype</span>;
    <span class="pl-smi">subClass</span>.<span class="pl-c1">prototype</span> <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">F</span>();
    <span class="pl-smi">subClass</span>.<span class="pl-c1">prototype</span>.<span class="pl-c1">constructor</span> <span class="pl-k">=</span> subClass;
}</pre></div>
<h5><a id="user-content-建议-声明类时保证-constructor-的正确性" class="anchor" aria-hidden="true" href="#建议-声明类时保证-constructor-的正确性"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 声明类时，保证 <code>constructor</code> 的正确性。</h5>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">Animal</span>(<span class="pl-smi">name</span>) {
    <span class="pl-c1">this</span>.<span class="pl-c1">name</span> <span class="pl-k">=</span> name;
}

<span class="pl-c"><span class="pl-c">//</span> 直接prototype等于对象时，需要修正constructor</span>
<span class="pl-smi">Animal</span>.<span class="pl-c1">prototype</span> <span class="pl-k">=</span> {
    <span class="pl-en">constructor</span>: Animal,

    jump: <span class="pl-k">function</span> () {
        <span class="pl-en">alert</span>(<span class="pl-s"><span class="pl-pds">'</span>animal <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-c1">this</span>.<span class="pl-c1">name</span> <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> jump<span class="pl-pds">'</span></span>);
    }
};

<span class="pl-c"><span class="pl-c">//</span> 这种方式扩展prototype则无需理会constructor</span>
<span class="pl-smi">Animal</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">jump</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-en">alert</span>(<span class="pl-s"><span class="pl-pds">'</span>animal <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-c1">this</span>.<span class="pl-c1">name</span> <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> jump<span class="pl-pds">'</span></span>);
};</pre></div>
<h5><a id="user-content-建议-属性在构造函数中声明方法在原型中声明" class="anchor" aria-hidden="true" href="#建议-属性在构造函数中声明方法在原型中声明"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 属性在构造函数中声明，方法在原型中声明。</h5>
<p>解释：</p>
<p>原型对象的成员被所有实例共享，能节约内存占用。所以编码时我们应该遵守这样的原则：原型对象包含程序不会修改的成员，如方法函数或配置项。</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">TextNode</span>(<span class="pl-smi">value</span>, <span class="pl-smi">engine</span>) {
    <span class="pl-c1">this</span>.<span class="pl-c1">value</span> <span class="pl-k">=</span> value;
    <span class="pl-c1">this</span>.<span class="pl-smi">engine</span> <span class="pl-k">=</span> engine;
}

<span class="pl-smi">TextNode</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">clone</span> <span class="pl-k">=</span> <span class="pl-k">function</span> () {
    <span class="pl-k">return</span> <span class="pl-c1">this</span>;
};</pre></div>
<h5><a id="user-content-强制-自定义事件的-事件名-必须全小写" class="anchor" aria-hidden="true" href="#强制-自定义事件的-事件名-必须全小写"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 自定义事件的 <code>事件名</code> 必须全小写。</h5>
<p>解释：</p>
<p>在 JavaScript 广泛应用的浏览器环境，绝大多数 DOM 事件名称都是全小写的。为了遵循大多数 JavaScript 开发者的习惯，在设计自定义事件时，事件名也应该全小写。</p>
<h5><a id="user-content-强制-自定义事件只能有一个-event-参数如果事件需要传递较多信息应仔细设计事件对象" class="anchor" aria-hidden="true" href="#强制-自定义事件只能有一个-event-参数如果事件需要传递较多信息应仔细设计事件对象"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 自定义事件只能有一个 <code>event</code> 参数。如果事件需要传递较多信息，应仔细设计事件对象。</h5>
<p>解释：</p>
<p>一个事件对象的好处有：</p>
<ol>
<li>顺序无关，避免事件监听者需要记忆参数顺序。</li>
<li>每个事件信息都可以根据需要提供或者不提供，更自由。</li>
<li>扩展方便，未来添加事件信息时，无需考虑会破坏监听器参数形式而无法向后兼容。</li>
</ol>
<h5><a id="user-content-建议-设计自定义事件时应考虑禁止默认行为" class="anchor" aria-hidden="true" href="#建议-设计自定义事件时应考虑禁止默认行为"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 设计自定义事件时，应考虑禁止默认行为。</h5>
<p>解释：</p>
<p>常见禁止默认行为的方式有两种：</p>
<ol>
<li>事件监听函数中 return false。</li>
<li>事件对象中包含禁止默认行为的方法，如 preventDefault。</li>
</ol>
<h3><a id="user-content-310-动态特性" class="anchor" aria-hidden="true" href="#310-动态特性"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.10 动态特性</h3>
<h4><a id="user-content-3101-eval" class="anchor" aria-hidden="true" href="#3101-eval"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.10.1 eval</h4>
<h5><a id="user-content-强制-避免使用直接-eval-函数" class="anchor" aria-hidden="true" href="#强制-避免使用直接-eval-函数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 避免使用直接 <code>eval</code> 函数。</h5>
<p>解释：</p>
<p>直接 eval，指的是以函数方式调用 eval 的调用方法。直接 eval 调用执行代码的作用域为本地作用域，应当避免。</p>
<p>如果有特殊情况需要使用直接 eval，需在代码中用详细的注释说明为何必须使用直接 eval，不能使用其它动态执行代码的方式，同时需要其他资深工程师进行 Code Review。</p>
<h5><a id="user-content-建议-尽量避免使用-eval-函数" class="anchor" aria-hidden="true" href="#建议-尽量避免使用-eval-函数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 尽量避免使用 <code>eval</code> 函数。</h5>
<h4><a id="user-content-3102-动态执行代码" class="anchor" aria-hidden="true" href="#3102-动态执行代码"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.10.2 动态执行代码</h4>
<h5><a id="user-content-建议-使用-new-function-执行动态代码" class="anchor" aria-hidden="true" href="#建议-使用-new-function-执行动态代码"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 使用 <code>new Function</code> 执行动态代码。</h5>
<p>解释：</p>
<p>通过 new Function 生成的函数作用域是全局使用域，不会影响当当前的本地作用域。如果有动态代码执行的需求，建议使用 new Function。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> handler <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Function</span>(<span class="pl-s"><span class="pl-pds">'</span>x<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>y<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>return x + y;<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> result <span class="pl-k">=</span> <span class="pl-en">handler</span>(<span class="pl-en">$</span>(<span class="pl-s"><span class="pl-pds">'</span>#x<span class="pl-pds">'</span></span>).<span class="pl-en">val</span>(), <span class="pl-en">$</span>(<span class="pl-s"><span class="pl-pds">'</span>#y<span class="pl-pds">'</span></span>).<span class="pl-en">val</span>());</pre></div>
<h4><a id="user-content-3103-with" class="anchor" aria-hidden="true" href="#3103-with"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.10.3 with</h4>
<h5><a id="user-content-建议-尽量不要使用-with" class="anchor" aria-hidden="true" href="#建议-尽量不要使用-with"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 尽量不要使用 <code>with</code>。</h5>
<p>解释：</p>
<p>使用 with 可能会增加代码的复杂度，不利于阅读和管理；也会对性能有影响。大多数使用 with 的场景都能使用其他方式较好的替代。所以，尽量不要使用 with。</p>
<h4><a id="user-content-3104-delete" class="anchor" aria-hidden="true" href="#3104-delete"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.10.4 delete</h4>
<h5><a id="user-content-建议-减少-delete-的使用" class="anchor" aria-hidden="true" href="#建议-减少-delete-的使用"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 减少 <code>delete</code> 的使用。</h5>
<p>解释：</p>
<p>如果没有特别的需求，减少或避免使用<code>delete</code>。<code>delete</code>的使用会破坏部分 JavaScript 引擎的性能优化。</p>
<h5><a id="user-content-建议-处理-delete-可能产生的异常" class="anchor" aria-hidden="true" href="#建议-处理-delete-可能产生的异常"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 处理 <code>delete</code> 可能产生的异常。</h5>
<p>解释：</p>
<p>对于有被遍历需求，且值 null 被认为具有业务逻辑意义的值的对象，移除某个属性必须使用 delete 操作。</p>
<p>在严格模式或IE下使用 delete 时，不能被删除的属性会抛出异常，因此在不确定属性是否可以删除的情况下，建议添加 try-catch 块。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">try</span> {
    <span class="pl-k">delete</span> <span class="pl-smi">o</span>.<span class="pl-c1">x</span>;
}
<span class="pl-k">catch</span> (deleteError) {
    <span class="pl-smi">o</span>.<span class="pl-c1">x</span> <span class="pl-k">=</span> <span class="pl-c1">null</span>;
}</pre></div>
<h4><a id="user-content-3105-对象属性" class="anchor" aria-hidden="true" href="#3105-对象属性"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.10.5 对象属性</h4>
<h5><a id="user-content-建议-避免修改外部传入的对象" class="anchor" aria-hidden="true" href="#建议-避免修改外部传入的对象"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 避免修改外部传入的对象。</h5>
<p>解释：</p>
<p>JavaScript 因其脚本语言的动态特性，当一个对象未被 seal 或 freeze 时，可以任意添加、删除、修改属性值。</p>
<p>但是随意地对 非自身控制的对象 进行修改，很容易造成代码在不可预知的情况下出现问题。因此，设计良好的组件、函数应该避免对外部传入的对象的修改。</p>
<p>下面代码的 selectNode 方法修改了由外部传入的 datasource 对象。如果 datasource 用在其它场合（如另一个 Tree 实例）下，会造成状态的混乱。</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">Tree</span>(<span class="pl-smi">datasource</span>) {
    <span class="pl-c1">this</span>.<span class="pl-smi">datasource</span> <span class="pl-k">=</span> datasource;
}

<span class="pl-smi">Tree</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">selectNode</span> <span class="pl-k">=</span> <span class="pl-k">function</span> (<span class="pl-smi">id</span>) {
    <span class="pl-c"><span class="pl-c">//</span> 从datasource中找出节点对象</span>
    <span class="pl-k">var</span> node <span class="pl-k">=</span> <span class="pl-c1">this</span>.<span class="pl-en">findNode</span>(id);
    <span class="pl-k">if</span> (node) {
        <span class="pl-smi">node</span>.<span class="pl-c1">selected</span> <span class="pl-k">=</span> <span class="pl-c1">true</span>;
        <span class="pl-c1">this</span>.<span class="pl-en">flushView</span>();
    }
};</pre></div>
<p>对于此类场景，需要使用额外的对象来维护，使用由自身控制，不与外部产生任何交互的 selectedNodeIndex 对象来维护节点的选中状态，不对 datasource 作任何修改。</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">function</span> <span class="pl-en">Tree</span>(<span class="pl-smi">datasource</span>) {
    <span class="pl-c1">this</span>.<span class="pl-smi">datasource</span> <span class="pl-k">=</span> datasource;
    <span class="pl-c1">this</span>.<span class="pl-smi">selectedNodeIndex</span> <span class="pl-k">=</span> {};
}

<span class="pl-smi">Tree</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">selectNode</span> <span class="pl-k">=</span> <span class="pl-k">function</span> (<span class="pl-smi">id</span>) {
    <span class="pl-c"><span class="pl-c">//</span> 从datasource中找出节点对象</span>
    <span class="pl-k">var</span> node <span class="pl-k">=</span> <span class="pl-c1">this</span>.<span class="pl-en">findNode</span>(id);
    <span class="pl-k">if</span> (node) {
        <span class="pl-c1">this</span>.<span class="pl-smi">selectedNodeIndex</span>[id] <span class="pl-k">=</span> <span class="pl-c1">true</span>;
        <span class="pl-c1">this</span>.<span class="pl-en">flushView</span>();
    }
};</pre></div>
<p>除此之外，也可以通过 deepClone 等手段将自身维护的对象与外部传入的分离，保证不会相互影响。</p>
<h5><a id="user-content-建议-具备强类型的设计" class="anchor" aria-hidden="true" href="#建议-具备强类型的设计"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 具备强类型的设计。</h5>
<p>解释：</p>
<ul>
<li>如果一个属性被设计为 boolean 类型，则不要使用 1 / 0 作为其值。对于标识性的属性，如对代码体积有严格要求，可以从一开始就设计为 number 类型且将 0 作为否定值。</li>
<li>从 DOM 中取出的值通常为 string 类型，如果有对象或函数的接收类型为 number 类型，提前作好转换，而不是期望对象、函数可以处理多类型的值。</li>
</ul>
<h2><a id="user-content-4-浏览器环境" class="anchor" aria-hidden="true" href="#4-浏览器环境"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4 浏览器环境</h2>
<h3><a id="user-content-41-模块化" class="anchor" aria-hidden="true" href="#41-模块化"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.1 模块化</h3>
<h4><a id="user-content-411-amd" class="anchor" aria-hidden="true" href="#411-amd"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.1.1 AMD</h4>
<h5><a id="user-content-强制-使用-amd-作为模块定义" class="anchor" aria-hidden="true" href="#强制-使用-amd-作为模块定义"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 使用 <code>AMD</code> 作为模块定义。</h5>
<p>解释：</p>
<p>AMD 作为由社区认可的模块定义形式，提供多种重载提供灵活的使用方式，并且绝大多数优秀的 Library 都支持 AMD，适合作为规范。</p>
<p>目前，比较成熟的 AMD Loader 有：</p>
<ul>
<li>官方实现的 <a href="http://requirejs.org/" rel="nofollow">requirejs</a></li>
<li>百度自己实现的 <a href="https://github.com/ecomfe/esl">esl</a></li>
</ul>
<h5><a id="user-content-强制-模块-id-必须符合标准" class="anchor" aria-hidden="true" href="#强制-模块-id-必须符合标准"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 模块 <code>id</code> 必须符合标准。</h5>
<p>解释：</p>
<p>模块 id 必须符合以下约束条件：</p>
<ol>
<li>类型为 string，并且是由 <code>/</code> 分割的一系列 terms 来组成。例如：<code>this/is/a/module</code>。</li>
<li>term 应该符合 [a-zA-Z0-9_-]+ 规则。</li>
<li>不应该有 .js 后缀。</li>
<li>跟文件的路径保持一致。</li>
</ol>
<h4><a id="user-content-412-define" class="anchor" aria-hidden="true" href="#412-define"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.1.2 define</h4>
<h5><a id="user-content-建议-定义模块时不要指明-id-和-dependencies" class="anchor" aria-hidden="true" href="#建议-定义模块时不要指明-id-和-dependencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 定义模块时不要指明 <code>id</code> 和 <code>dependencies</code>。</h5>
<p>解释：</p>
<p>在 AMD 的设计思想里，模块名称是和所在路径相关的，匿名的模块更利于封包和迁移。模块依赖应在模块定义内部通过 local require 引用。</p>
<p>所以，推荐使用 define(factory) 的形式进行模块定义。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">define</span>(
    <span class="pl-k">function</span> (<span class="pl-smi">require</span>) {
    }
);</pre></div>
<h5><a id="user-content-建议-使用-return-来返回模块定义" class="anchor" aria-hidden="true" href="#建议-使用-return-来返回模块定义"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 使用 <code>return</code> 来返回模块定义。</h5>
<p>解释：</p>
<p>使用 return 可以减少 factory 接收的参数（不需要接收 exports 和 module），在没有 AMD Loader 的场景下也更容易进行简单的处理来伪造一个 Loader。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">define</span>(
    <span class="pl-k">function</span> (<span class="pl-smi">require</span>) {
        <span class="pl-k">var</span> <span class="pl-c1">exports</span> <span class="pl-k">=</span> {};

        <span class="pl-c"><span class="pl-c">//</span> ...</span>

        <span class="pl-k">return</span> <span class="pl-c1">exports</span>;
    }
);</pre></div>
<h4><a id="user-content-413-require" class="anchor" aria-hidden="true" href="#413-require"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.1.3 require</h4>
<h5><a id="user-content-强制-全局运行环境中require-必须以-async-require-形式调用" class="anchor" aria-hidden="true" href="#强制-全局运行环境中require-必须以-async-require-形式调用"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 全局运行环境中，<code>require</code> 必须以 <code>async require</code> 形式调用。</h5>
<p>解释：</p>
<p>模块的加载过程是异步的，同步调用并无法保证得到正确的结果。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> good</span>
<span class="pl-c1">require</span>([<span class="pl-s"><span class="pl-pds">'</span>foo<span class="pl-pds">'</span></span>], <span class="pl-k">function</span> (<span class="pl-smi">foo</span>) {
});

<span class="pl-c"><span class="pl-c">//</span> bad</span>
<span class="pl-k">var</span> foo <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>foo<span class="pl-pds">'</span></span>);</pre></div>
<h5><a id="user-content-强制-模块定义中只允许使用-local-require不允许使用-global-require" class="anchor" aria-hidden="true" href="#强制-模块定义中只允许使用-local-require不允许使用-global-require"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 模块定义中只允许使用 <code>local require</code>，不允许使用 <code>global require</code>。</h5>
<p>解释：</p>
<ol>
<li>在模块定义中使用 global require，对封装性是一种破坏。</li>
<li>在 AMD 里，global require 是可以被重命名的。并且 Loader 甚至没有全局的 require 变量，而是用 Loader 名称做为 global require。模块定义不应该依赖使用的 Loader。</li>
</ol>
<h5><a id="user-content-强制-package在实现时内部模块的-require-必须使用-relative-id" class="anchor" aria-hidden="true" href="#强制-package在实现时内部模块的-require-必须使用-relative-id"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] Package在实现时，内部模块的 <code>require</code> 必须使用 <code>relative id</code>。</h5>
<p>解释：</p>
<p>对于任何可能通过 发布-引入 的形式复用的第三方库、框架、包，开发者所定义的名称不代表使用者使用的名称。因此不要基于任何名称的假设。在实现源码中，require 自身的其它模块时使用 relative id。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">define</span>(
    <span class="pl-k">function</span> (<span class="pl-smi">require</span>) {
        <span class="pl-k">var</span> util <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>./util<span class="pl-pds">'</span></span>);
    }
);</pre></div>
<h5><a id="user-content-建议-不会被调用的依赖模块在-factory-开始处统一-require" class="anchor" aria-hidden="true" href="#建议-不会被调用的依赖模块在-factory-开始处统一-require"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 不会被调用的依赖模块，在 <code>factory</code> 开始处统一 <code>require</code>。</h5>
<p>解释：</p>
<p>有些模块是依赖的模块，但不会在模块实现中被直接调用，最为典型的是 css / js / tpl 等 Plugin 所引入的外部内容。此类内容建议放在模块定义最开始处统一引用。</p>
<p>示例：</p>
<div class="highlight highlight-source-js"><pre><span class="pl-en">define</span>(
    <span class="pl-k">function</span> (<span class="pl-smi">require</span>) {
        <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>css!foo.css<span class="pl-pds">'</span></span>);
        <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>tpl!bar.tpl.html<span class="pl-pds">'</span></span>);

        <span class="pl-c"><span class="pl-c">//</span> ...</span>
    }
);</pre></div>
<h3><a id="user-content-42-dom" class="anchor" aria-hidden="true" href="#42-dom"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2 DOM</h3>
<h4><a id="user-content-421-元素获取" class="anchor" aria-hidden="true" href="#421-元素获取"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2.1 元素获取</h4>
<h5><a id="user-content-建议-对于单个元素尽可能使用-documentgetelementbyid-获取避免使用documentall" class="anchor" aria-hidden="true" href="#建议-对于单个元素尽可能使用-documentgetelementbyid-获取避免使用documentall"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于单个元素，尽可能使用 <code>document.getElementById</code> 获取，避免使用<code>document.all</code>。</h5>
<h5><a id="user-content-建议-对于多个元素的集合尽可能使用-contextgetelementsbytagname-获取其中-context-可以为-document-或其他元素指定-tagname-参数为--可以获得所有子元素" class="anchor" aria-hidden="true" href="#建议-对于多个元素的集合尽可能使用-contextgetelementsbytagname-获取其中-context-可以为-document-或其他元素指定-tagname-参数为--可以获得所有子元素"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 对于多个元素的集合，尽可能使用 <code>context.getElementsByTagName</code> 获取。其中 <code>context</code> 可以为 <code>document</code> 或其他元素。指定 <code>tagName</code> 参数为 <code>*</code> 可以获得所有子元素。</h5>
<h5><a id="user-content-建议-遍历元素集合时尽量缓存集合长度如需多次操作同一集合则应将集合转为数组" class="anchor" aria-hidden="true" href="#建议-遍历元素集合时尽量缓存集合长度如需多次操作同一集合则应将集合转为数组"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 遍历元素集合时，尽量缓存集合长度。如需多次操作同一集合，则应将集合转为数组。</h5>
<p>解释：</p>
<p>原生获取元素集合的结果并不直接引用 DOM 元素，而是对索引进行读取，所以 DOM 结构的改变会实时反映到结果中。</p>
<p>示例：</p>
<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent">div</span>&gt;&lt;/<span class="pl-ent">div</span>&gt;
&lt;<span class="pl-ent">span</span>&gt;&lt;/<span class="pl-ent">span</span>&gt;

&lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-k">var</span> elements <span class="pl-k">=</span> <span class="pl-c1">document</span>.<span class="pl-c1">getElementsByTagName</span>(<span class="pl-s"><span class="pl-pds">'</span>*<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-c"><span class="pl-c">//</span> 显示为 DIV</span></span>
<span class="pl-s1"><span class="pl-en">alert</span>(elements[<span class="pl-c1">0</span>].<span class="pl-c1">tagName</span>);</span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-k">var</span> div <span class="pl-k">=</span> elements[<span class="pl-c1">0</span>];</span>
<span class="pl-s1"><span class="pl-k">var</span> p <span class="pl-k">=</span> <span class="pl-c1">document</span>.<span class="pl-c1">createElement</span>(<span class="pl-s"><span class="pl-pds">'</span>p<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1"><span class="pl-c1">document</span>.<span class="pl-c1">body</span>.<span class="pl-c1">insertBefore</span>(p, div);</span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-c"><span class="pl-c">//</span> 显示为 P</span></span>
<span class="pl-s1"><span class="pl-en">alert</span>(elements[<span class="pl-c1">0</span>].<span class="pl-c1">tagName</span>);</span>
<span class="pl-s1"></span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;</pre></div>
<h5><a id="user-content-建议-获取元素的直接子元素时使用-children避免使用childnodes除非预期是需要包含文本注释和属性类型的节点" class="anchor" aria-hidden="true" href="#建议-获取元素的直接子元素时使用-children避免使用childnodes除非预期是需要包含文本注释和属性类型的节点"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 获取元素的直接子元素时使用 <code>children</code>。避免使用<code>childNodes</code>，除非预期是需要包含文本、注释和属性类型的节点。</h5>
<h4><a id="user-content-422-样式获取" class="anchor" aria-hidden="true" href="#422-样式获取"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2.2 样式获取</h4>
<h5><a id="user-content-建议-获取元素实际样式信息时应使用-getcomputedstyle-或-currentstyle" class="anchor" aria-hidden="true" href="#建议-获取元素实际样式信息时应使用-getcomputedstyle-或-currentstyle"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 获取元素实际样式信息时，应使用 <code>getComputedStyle</code> 或 <code>currentStyle</code>。</h5>
<p>解释：</p>
<p>通过 style 只能获得内联定义或通过 JavaScript 直接设置的样式。通过 CSS class 设置的元素样式无法直接通过 style 获取。</p>
<h4><a id="user-content-423-样式设置" class="anchor" aria-hidden="true" href="#423-样式设置"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2.3 样式设置</h4>
<h5><a id="user-content-建议-尽可能通过为元素添加预定义的-classname-来改变元素样式避免直接操作-style-设置" class="anchor" aria-hidden="true" href="#建议-尽可能通过为元素添加预定义的-classname-来改变元素样式避免直接操作-style-设置"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 尽可能通过为元素添加预定义的 className 来改变元素样式，避免直接操作 style 设置。</h5>
<h5><a id="user-content-强制-通过-style-对象设置元素样式时对于带单位非-0-值的属性不允许省略单位" class="anchor" aria-hidden="true" href="#强制-通过-style-对象设置元素样式时对于带单位非-0-值的属性不允许省略单位"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[强制] 通过 style 对象设置元素样式时，对于带单位非 0 值的属性，不允许省略单位。</h5>
<p>解释：</p>
<p>除了 IE，标准浏览器会忽略不规范的属性值，导致兼容性问题。</p>
<h4><a id="user-content-424-dom-操作" class="anchor" aria-hidden="true" href="#424-dom-操作"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2.4 DOM 操作</h4>
<h5><a id="user-content-建议-操作-dom-时尽量减少页面-reflow" class="anchor" aria-hidden="true" href="#建议-操作-dom-时尽量减少页面-reflow"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 操作 <code>DOM</code> 时，尽量减少页面 <code>reflow</code>。</h5>
<p>解释：</p>
<p>页面 reflow 是非常耗时的行为，非常容易导致性能瓶颈。下面一些场景会触发浏览器的reflow：</p>
<ul>
<li>DOM元素的添加、修改（内容）、删除。</li>
<li>应用新的样式或者修改任何影响元素布局的属性。</li>
<li>Resize浏览器窗口、滚动页面。</li>
<li>读取元素的某些属性（offsetLeft、offsetTop、offsetHeight、offsetWidth、scrollTop/Left/Width/Height、clientTop/Left/Width/Height、getComputedStyle()、currentStyle(in IE)) 。</li>
</ul>
<h5><a id="user-content-建议-尽量减少-dom-操作" class="anchor" aria-hidden="true" href="#建议-尽量减少-dom-操作"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 尽量减少 <code>DOM</code> 操作。</h5>
<p>解释：</p>
<p>DOM 操作也是非常耗时的一种操作，减少 DOM 操作有助于提高性能。举一个简单的例子，构建一个列表。我们可以用两种方式：</p>
<ol>
<li>在循环体中 createElement 并 append 到父元素中。</li>
<li>在循环体中拼接 HTML 字符串，循环结束后写父元素的 innerHTML。</li>
</ol>
<p>第一种方法看起来比较标准，但是每次循环都会对 DOM 进行操作，性能极低。在这里推荐使用第二种方法。</p>
<h4><a id="user-content-425-dom-事件" class="anchor" aria-hidden="true" href="#425-dom-事件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2.5 DOM 事件</h4>
<h5><a id="user-content-建议-优先使用-addeventlistener--attachevent-绑定事件避免直接在-html-属性中或-dom-的-expando-属性绑定事件处理" class="anchor" aria-hidden="true" href="#建议-优先使用-addeventlistener--attachevent-绑定事件避免直接在-html-属性中或-dom-的-expando-属性绑定事件处理"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 优先使用 <code>addEventListener / attachEvent</code> 绑定事件，避免直接在 HTML 属性中或 DOM 的 <code>expando</code> 属性绑定事件处理。</h5>
<p>解释：</p>
<p>expando 属性绑定事件容易导致互相覆盖。</p>
<h5><a id="user-content-建议-使用-addeventlistener-时第三个参数使用-false" class="anchor" aria-hidden="true" href="#建议-使用-addeventlistener-时第三个参数使用-false"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 使用 <code>addEventListener</code> 时第三个参数使用 <code>false</code>。</h5>
<p>解释：</p>
<p>标准浏览器中的 addEventListener 可以通过第三个参数指定两种时间触发模型：冒泡和捕获。而 IE 的 attachEvent 仅支持冒泡的事件触发。所以为了保持一致性，通常 addEventListener 的第三个参数都为 false。</p>
<h5><a id="user-content-建议-在没有事件自动管理的框架支持下应持有监听器函数的引用在适当时候元素释放页面卸载等移除添加的监听器" class="anchor" aria-hidden="true" href="#建议-在没有事件自动管理的框架支持下应持有监听器函数的引用在适当时候元素释放页面卸载等移除添加的监听器"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>[建议] 在没有事件自动管理的框架支持下，应持有监听器函数的引用，在适当时候（元素释放、页面卸载等）移除添加的监听器。</h5>
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
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

        
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2018 <span title="0.24344s from unicorn-7997f7644d-k2rxw">GitHub</span>, Inc.</li>
        <li class="mr-3"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://help.github.com/articles/github-security/" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon mr-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3"><a href="https://blog.github.com" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script crossorigin="anonymous" integrity="sha512-RJ1ufbxsSbKjRCyYvinsPNKvTBvcvvKUvEOJ8g+GjtWI5SuRr+QPBlZcvRDws4H9YwAgdQFcGxfL8UbwEfdI7A==" type="application/javascript" src="https://assets-cdn.github.com/assets/compat-daf14de28fadf1e2bc40d100cb773e2b.js"></script>
    <script crossorigin="anonymous" integrity="sha512-Bb0Wovr1o2Cb3KlmHRGIjQlsUxTAa1LYyxdQ/tsndUC+t7gAyu/2fpdLW7eex9HXv13smytm3gzMD5+Z81gb9A==" type="application/javascript" src="https://assets-cdn.github.com/assets/frameworks-2b155dd967d6dd0a278d1a91dcafbeec.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-UaZ4IRKhyD513Mqagj6/YCUeDoZoxLDtN+QVJC/2TFfmzKDExcxugXDXb0BazDVtgGayFbaiE5sOOCFfthb1fQ==" type="application/javascript" src="https://assets-cdn.github.com/assets/github-e855a0d8a0571cc78e55c1111ffe1ff2.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
  </div>
</div>

  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark" open>
    <summary aria-haspopup="dialog" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast">
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

<div id="hovercard-aria-description" class="sr-only">
  Press h to open a hovercard with more details.
</div>


  </body>
</html>

