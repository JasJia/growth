DOC
===

Architecture
---

![Architecture](growth-arch.png)

Setup && Development 
---

###Tech Stack

1. Angular.js
2. Cordova
3. Ionic
4. ngCordova
5. jQuery
6. Nools
7. D3.js
8. collide

Angular Plugins: 

1. angular-highlightjs: HighLight Code
2. angular-marked: Markdown Support 
3. angular-translate: i18n
4. angular-moment: Time i18n
5. angular-resource: HTTP Resource
6. angular-messages: Form Validate

Angular Plugins: ionic-rating, ionic-ion-tinder-cards, ionic.swipecards, ionic-filter-bar, ion-affix 

###Setup

1.Clone

    git clone git@github.com:phodal/growth.git

2.Install Deps

    npm install -g cordova
    npm install -g ionic
    ionic serve

Plugins:

App Rate:

    cordova plugin add https://github.com/pushandplay/cordova-plugin-apprate.git
    
Share:
     
    cordova plugin add https://github.com/EddyVerbruggen/SocialSharing-PhoneGap-Plugin.git


App in Browser:

    cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-inappbrowser.git
    
Google Analytics     
     
    cordova plugin add https://github.com/danwilson/google-analytics-plugin.git // 
    
I18N:
   
    cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-globalization.git
    
####Android
    
Auto Update:    
    
    cordova plugin add cordova-plugin-file  //文件
    cordova plugin add cordova-plugin-file-transfer //下载
    cordova plugin add https://github.com/pwlin/cordova-plugin-file-opener2.git //安装
    cordova plugin add https://github.com/whiteoctober/cordova-plugin-app-version.git //For Update
    cordova plugin add https://github.com/EddyVerbruggen/Toast-PhoneGap-Plugin.git

####Windows Phone & Windows 10: 

Install GA SDK With NuGet

    PM>  Install-Package GoogleAnalyticsSDK 

Google Analytics:  

    cordova plugin add https://github.com/dpolivy/google-analytics-plugin#f516ba05835e6c5ce35c572a912b966949b488eb

1. [https://github.com/Microsoft/cordova-docs/blob/master/articles/getting-started/tutorial-ionic.md](https://github.com/Microsoft/cordova-docs/blob/master/articles/getting-started/tutorial-ionic.md)
2. [http://blog.vjrantal.net/2015/01/08/experiences-with-ionic-on-windows-phone-8-1/](http://blog.vjrantal.net/2015/01/08/experiences-with-ionic-on-windows-phone-8-1/) 
3. [http://www.badpenguin.org/how-to-make-your-ionic-cordova-app-to-run-under-windows-phone-8-1-and-desktop](http://www.badpenguin.org/how-to-make-your-ionic-cordova-app-to-run-under-windows-phone-8-1-and-desktop)

####Desktop

Install Electron and Run

     electron .


Community (Use Flarum)
---

API Document: [http://flarum.org/docs/api/](http://flarum.org/docs/api/)

**Forum**

 - GET /api/forum - get information about the forum, including groups and tags
 - PATCH /api/forum - update forum config

**Discussions**

 - GET /api/discussions - get all discussions (sort is -time by default)
    - filter[q] - filter by username/gambits
 - POST /api/discussions - create a new discussion
 - GET /api/discussions/:id - get a discussion by ID
 - PATCH /api/discussions/:id - update a discussion
 - DELETE /api/discussions/:id - delete a discussion

**Posts**

 - GET /api/posts - get all posts
     - filter[discussion] - filter by discussion ID
     - filter[user] - filter by user ID
     - filter[number] - filter by number (position within the discussion)
     - filter[type] - filter by post type
 - POST /api/posts - create a new post
 - GET /api/posts/:id - get a post by ID
 - PATCH /api/posts/:id - update a post
 - DELETE /api/posts/:id - delete a post

**Users**

 - GET /api/users - get all users
    - filter[q] - filter by username/gambits
 - POST /api/users - register a new user
 - GET /api/users/:idOrUsername - get a user by ID or username
 - PATCH /api/users/:id - update a user
 - DELETE /api/users/:id - delete a user
 - POST /api/users/:id/avatar - upload a user avatar
 - DELETE /api/users/:id/avatar - delete a user avatar
 
**Groups**

 - GET /api/groups - get all groups
 - POST /api/groups - create a new group
 - PATCH /api/groups/:id - update a group
 - DELETE /api/groups/:id - delete a group

**Notifications**

 - GET /api/notifications - get all notifications
 - PATCH /api/notifications/:id - mark a notification as read

**Tags**

 - POST /api/tags - create a new tag
 - PATCH /api/tags/:id - update a tag
 - DELETE /api/tags/:id - delete a tag

其他
---

###Thinking

1. [https://github.com/braydie/HowToBeAProgrammer](https://github.com/braydie/HowToBeAProgrammer)

2. [http://stackshare.io/](http://stackshare.io/)

3. [http://stackshare.io/featured-posts](http://stackshare.io/featured-posts)

4. [https://www.awesomes.cn/](https://www.awesomes.cn/)

前端问题来源于: [http://markyun.github.io/2015/Front-end-Developer-Questions/](http://markyun.github.io/2015/Front-end-Developer-Questions/)

Skill Map基于: [http://bl.ocks.org/wizicer/f662a0b04425fc0f7489](http://bl.ocks.org/wizicer/f662a0b04425fc0f7489)

前端资料基于: [https://github.com/dypsilon/frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks)

部分书评来自于亚马逊、豆瓣。
