---
layout: post
title:  "Eclipse Luna ohne HI-DPI Support unter Windows 8.1"
date:   2014-08-07 20:00:00
categories: eclipse windows hidpi
---

Es ist wirklich enttäuschend, dass Eclipse in der aktuellen Version 4.4 (Luna) unter Windows 8.1 immer noch nicht für HI-DPI-Displays angepasst wurde. 
Auf meinem Lenovo Yoga 2 Pro mit der nativen Auflösung von 3200 x 1800 Bildpunkten und 200% Inhaltsskalierung 
ist Eclipse vollkommen unbrauchbar (s. Screenshots). Die Schriftgrößen kann man zwar noch über “Preferences” anpassen. 
Das Hauptproblem sind aber die nicht skalierbaren Icons in den Menüs und Tollbars.

Im Eclipse Issue-Tracker gibt es dazu den Bug [421383](https://bugs.eclipse.org/bugs/show_bug.cgi?id=421383). 
Eine Lösung scheint aber nicht in Sicht zu sein. Linux-Nutzer sind ebenfalls von dem Problem betroffen. 
Erstaunlich ist aber, dass Eclipse auf Apple’s Retina-Macbooks mit der hohen Auflösung von Anfang an wenig Probleme hatte.

<img src="/img/2014-08-07-20_53_19-Java-EE-Eclipse-1024x653.png" alt="Eclipse EE HI-DPI 1" style="width: 90%;"/>

<img src="/img/2014-08-07-21_15_51-Java-EE-WebProject_src_Application.java-Eclipse-1024x653.png" alt="Eclipse EE HI-DPI 1" style="width: 90%;"/>