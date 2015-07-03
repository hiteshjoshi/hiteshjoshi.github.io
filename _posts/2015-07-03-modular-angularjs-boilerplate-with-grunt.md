---
layout: post
title: "Modular angularjs boilerplate with grunt"
description: ""
category: angularjs,frontend
tags: [frontend]
---
{% include JB/setup %}

# Modular Angularjs Boiler plate.

This boilerplate is made using 

  - [Angularjs]
  - [Angular-ui-router]
  - And a lot more to add on the list.

I have added built in support for small REST like library too. Which is basically this [gist]. So inside your controller just add 'api' as dependency.

####Controllers
Controllers can be defined inside every module directory. 
> ![Controller structure](http://i.imgur.com/GIfayt2.png)
> ![Imgur](http://i.imgur.com/OSWkidi.png)
Routing is defined inside moduleDirectory/configs/routes.js , eg. dashboard/configs/routes.js


####Views
Master views are defined in core modules. And every view for module routing can be defined in configs/routes.js in module directories.
![Master views](http://i.imgur.com/jq88Tgr.png)



[AngularJS]:http://angularjs.org
[angular-ui-router]: https://github.com/angular-ui
[gist]:https://gist.github.com/ThomasBurleson/2432692
