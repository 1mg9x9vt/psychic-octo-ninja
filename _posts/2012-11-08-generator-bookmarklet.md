---
title: "generator bookmarklet"
subtitle: "a bookmarklet adapted to show the generator meta tag
published: true
---

<a href="javascript:(function(){t=document.getElementsByTagName(%22meta%22);s=%22%22;for(i=0;i<t.length;i++){if(t[i].name==%22generator%22)s=t[i].content;};if(s==%22%22)alert(%22No%20data%20available%22);else%20window.alert(%22Generator:%20%22+s)}());">show gen. meta</a>

