---
title: '2c490fca8fe4c2f8b43ae6f01285931f-scripts'
date: Wed, 25 Jul 2018 23:07:06 +0000
draft: false
---

/\*\*handles:hired-skip-link-focus-fix\*\*/ !function(){var e=navigator.userAgent.toLowerCase().indexOf("webkit")>-1,t=navigator.userAgent.toLowerCase().indexOf("opera")>-1,n=navigator.userAgent.toLowerCase().indexOf("msie")>-1;(e||t||n)&&document.getElementById&&window.addEventListener&&window.addEventListener("hashchange",function(){var e=location.hash.substring(1),t;/^\[A-z0-9_-\]+$/.test(e)&&(t=document.getElementById(e),t&&(/^(?:a|select|input|button|textarea)$/i.test(t.tagName)||(t.tabIndex=-1),t.focus()))},!1)}();