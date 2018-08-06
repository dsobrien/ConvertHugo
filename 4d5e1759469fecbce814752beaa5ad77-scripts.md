---
title: '4d5e1759469fecbce814752beaa5ad77-scripts'
date: Thu, 26 Jul 2018 01:53:35 +0000
draft: false
---

/\*\*handles:hired-skip-link-focus-fix\*\*/ !function(){var e=navigator.userAgent.toLowerCase().indexOf("webkit")>-1,t=navigator.userAgent.toLowerCase().indexOf("opera")>-1,n=navigator.userAgent.toLowerCase().indexOf("msie")>-1;(e||t||n)&&document.getElementById&&window.addEventListener&&window.addEventListener("hashchange",function(){var e=location.hash.substring(1),t;/^\[A-z0-9_-\]+$/.test(e)&&(t=document.getElementById(e),t&&(/^(?:a|select|input|button|textarea)$/i.test(t.tagName)||(t.tabIndex=-1),t.focus()))},!1)}();