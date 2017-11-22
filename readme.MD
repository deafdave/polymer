Microsoft Windows [Version 10.0.15063]
(c) 2017 Microsoft Corporation. All rights reserved.

C:\Users\DeafDave>mkdir prj && cd prj

C:\Users\DeafDave\prj>dir
 Volume in drive C is DeafDave PC
 Volume Serial Number is 28D1-2D86

 Directory of C:\Users\DeafDave\prj

22/11/2017  11:27 PM    <DIR>          .
22/11/2017  11:27 PM    <DIR>          ..
               0 File(s)              0 bytes
               2 Dir(s)  1,722,773,868,544 bytes free

C:\Users\DeafDave\prj>bower init
? name prj
? description a simple polymer prj
? main file index.html
? keywords
? authors DeafDave <deafdave@gmail.com>
? license MIT
? homepage
? set currently installed components as dependencies? Yes
? add commonly ignored files to ignore list? Yes
? would you like to mark this package as private which prevents it from being ac? would you like to mark this package as private which prevents it from being accidentally published to the registry? No

{
  name: 'prj',
  authors: [
    'DeafDave <deafdave@gmail.com>'
  ],
  description: 'a simple polymer prj',
  main: 'index.html',
  license: 'MIT',
  homepage: '',
  ignore: [
    '**/.*',
    'node_modules',
    'bower_components',
    'test',
    'tests'
  ]
}

? Looks good? Yes

C:\Users\DeafDave\prj>bower install --save Polymer/polymer
bower cached        https://github.com/Polymer/polymer.git#2.2.0
bower validate      2.2.0 against https://github.com/Polymer/polymer.git#*
bower cached        https://github.com/webcomponents/shadycss.git#1.1.0
bower validate      1.1.0 against https://github.com/webcomponents/shadycss.git#^v1.0.0
bower cached        https://github.com/webcomponents/webcomponentsjs.git#1.0.19
bower validate      1.0.19 against https://github.com/webcomponents/webcomponentsjs.git#^v1.0.2
bower install       polymer#2.2.0
bower install       shadycss#1.1.0
bower install       webcomponentsjs#1.0.19

polymer#2.2.0 bower_components\polymer
├── shadycss#1.1.0
└── webcomponentsjs#1.0.19

shadycss#1.1.0 bower_components\shadycss

webcomponentsjs#1.0.19 bower_components\webcomponentsjs


   ╭─────────────────────────────────────╮
   │                                     │
   │   Update available 1.8.0 → 1.8.2    │
   │   Run npm i -g bower to update      │
   │                                     │
   ╰─────────────────────────────────────╯


C:\Users\DeafDave\prj>npm i -g bower
npm WARN deprecated bower@1.8.2: ...psst! Your project can stop working at any moment because its dependencies can change. Prevent this by migrating to Yarn: https://bower.io/blog/2017/how-to-migrate-away-from-bower/
C:\Users\DeafDave\AppData\Roaming\npm\bower -> C:\Users\DeafDave\AppData\Roaming\npm\node_modules\bower\bin\bower
C:\Users\DeafDave\AppData\Roaming\npm
`-- bower@1.8.2


C:\Users\DeafDave\prj>bower install --save paper-button
bower cached        https://github.com/PolymerElements/paper-button.git#2.0.0
bower validate      2.0.0 against https://github.com/PolymerElements/paper-button.git#*
bower cached        https://github.com/PolymerElements/iron-flex-layout.git#2.0.1
bower validate      2.0.1 against https://github.com/PolymerElements/iron-flex-layout.git#1 - 2
bower cached        https://github.com/PolymerElements/paper-styles.git#2.0.0
bower validate      2.0.0 against https://github.com/PolymerElements/paper-styles.git#1 - 2
bower cached        https://github.com/PolymerElements/paper-behaviors.git#2.0.1
bower validate      2.0.1 against https://github.com/PolymerElements/paper-behaviors.git#1 - 2
bower cached        https://github.com/PolymerElements/paper-ripple.git#2.0.1
bower validate      2.0.1 against https://github.com/PolymerElements/paper-ripple.git#1 - 2
bower cached        https://github.com/PolymerElements/font-roboto.git#1.0.3
bower validate      1.0.3 against https://github.com/PolymerElements/font-roboto.git#^1.0.1
bower cached        https://github.com/PolymerElements/iron-behaviors.git#2.0.0
bower validate      2.0.0 against https://github.com/PolymerElements/iron-behaviors.git#1 - 2
bower cached        https://github.com/PolymerElements/iron-checked-element-behavior.git#2.0.0
bower validate      2.0.0 against https://github.com/PolymerElements/iron-checked-element-behavior.git#1 - 2
bower cached        https://github.com/PolymerElements/iron-form-element-behavior.git#2.0.0
bower validate      2.0.0 against https://github.com/PolymerElements/iron-form-element-behavior.git#1 - 2
bower cached        https://github.com/PolymerElements/iron-validatable-behavior.git#2.0.0
bower validate      2.0.0 against https://github.com/PolymerElements/iron-validatable-behavior.git#1 - 2
bower cached        https://github.com/PolymerElements/iron-a11y-keys-behavior.git#2.0.1
bower validate      2.0.1 against https://github.com/PolymerElements/iron-a11y-keys-behavior.git#1 - 2
bower cached        https://github.com/PolymerElements/iron-meta.git#2.0.3
bower validate      2.0.3 against https://github.com/PolymerElements/iron-meta.git#1 - 2
bower install       paper-button#2.0.0
bower install       paper-styles#2.0.0
bower install       iron-flex-layout#2.0.1
bower install       paper-behaviors#2.0.1
bower install       font-roboto#1.0.3
bower install       iron-checked-element-behavior#2.0.0
bower install       paper-ripple#2.0.1
bower install       iron-behaviors#2.0.0
bower install       iron-validatable-behavior#2.0.0
bower install       iron-form-element-behavior#2.0.0
bower install       iron-a11y-keys-behavior#2.0.1
bower install       iron-meta#2.0.3

paper-button#2.0.0 bower_components\paper-button
├── iron-flex-layout#2.0.1
├── paper-behaviors#2.0.1
├── paper-styles#2.0.0
└── polymer#2.2.0

paper-styles#2.0.0 bower_components\paper-styles
├── font-roboto#1.0.3
├── iron-flex-layout#2.0.1
└── polymer#2.2.0

iron-flex-layout#2.0.1 bower_components\iron-flex-layout
└── polymer#2.2.0

paper-behaviors#2.0.1 bower_components\paper-behaviors
├── iron-behaviors#2.0.0
├── iron-checked-element-behavior#2.0.0
├── paper-ripple#2.0.1
└── polymer#2.2.0

font-roboto#1.0.3 bower_components\font-roboto

iron-checked-element-behavior#2.0.0 bower_components\iron-checked-element-behavior
├── iron-form-element-behavior#2.0.0
├── iron-validatable-behavior#2.0.0
└── polymer#2.2.0

paper-ripple#2.0.1 bower_components\paper-ripple
├── iron-a11y-keys-behavior#2.0.1
└── polymer#2.2.0

iron-behaviors#2.0.0 bower_components\iron-behaviors
├── iron-a11y-keys-behavior#2.0.1
└── polymer#2.2.0

iron-validatable-behavior#2.0.0 bower_components\iron-validatable-behavior
├── iron-meta#2.0.3
└── polymer#2.2.0

iron-form-element-behavior#2.0.0 bower_components\iron-form-element-behavior
└── polymer#2.2.0

iron-a11y-keys-behavior#2.0.1 bower_components\iron-a11y-keys-behavior
└── polymer#2.2.0

iron-meta#2.0.3 bower_components\iron-meta
└── polymer#2.2.0

C:\Users\DeafDave\prj>dir
 Volume in drive C is DeafDave PC
 Volume Serial Number is 28D1-2D86

 Directory of C:\Users\DeafDave\prj

22/11/2017  11:28 PM    <DIR>          .
22/11/2017  11:28 PM    <DIR>          ..
22/11/2017  11:30 PM               374 bower.json
22/11/2017  11:30 PM    <DIR>          bower_components
               1 File(s)            374 bytes
               3 Dir(s)  1,722,702,475,264 bytes free

C:\Users\DeafDave\prj>cd bower_components

C:\Users\DeafDave\prj\bower_components>dir
 Volume in drive C is DeafDave PC
 Volume Serial Number is 28D1-2D86

 Directory of C:\Users\DeafDave\prj\bower_components

22/11/2017  11:30 PM    <DIR>          .
22/11/2017  11:30 PM    <DIR>          ..
22/11/2017  11:30 PM    <DIR>          font-roboto
22/11/2017  11:30 PM    <DIR>          iron-a11y-keys-behavior
22/11/2017  11:30 PM    <DIR>          iron-behaviors
22/11/2017  11:30 PM    <DIR>          iron-checked-element-behavior
22/11/2017  11:30 PM    <DIR>          iron-flex-layout
22/11/2017  11:30 PM    <DIR>          iron-form-element-behavior
22/11/2017  11:30 PM    <DIR>          iron-meta
22/11/2017  11:30 PM    <DIR>          iron-validatable-behavior
22/11/2017  11:30 PM    <DIR>          paper-behaviors
22/11/2017  11:30 PM    <DIR>          paper-button
22/11/2017  11:30 PM    <DIR>          paper-ripple
22/11/2017  11:30 PM    <DIR>          paper-styles
22/11/2017  11:28 PM    <DIR>          polymer
22/11/2017  11:28 PM    <DIR>          shadycss
22/11/2017  11:28 PM    <DIR>          webcomponentsjs
               0 File(s)              0 bytes
              17 Dir(s)  1,722,700,062,720 bytes free

C:\Users\DeafDave\prj\bower_components>cd ..

C:\Users\DeafDave\prj>dir
 Volume in drive C is DeafDave PC
 Volume Serial Number is 28D1-2D86

 Directory of C:\Users\DeafDave\prj

22/11/2017  11:34 PM    <DIR>          .
22/11/2017  11:34 PM    <DIR>          ..
22/11/2017  11:30 PM               374 bower.json
22/11/2017  11:30 PM    <DIR>          bower_components
22/11/2017  11:39 PM               612 index.html
               2 File(s)            986 bytes
               3 Dir(s)  1,722,640,588,800 bytes free

C:\Users\DeafDave\prj>polymer serve
info:    Files in this directory are available under the following URLs
      applications: http://127.0.0.1:8081
      reusable components: http://127.0.0.1:8081/components/prj/

^CTerminate batch job (Y/N)? y

C:\Users\DeafDave\prj>git init
Initialized empty Git repository in C:/Users/DeafDave/prj/.git/

C:\Users\DeafDave\prj>git add README.md
fatal: pathspec 'README.md' did not match any files

C:\Users\DeafDave\prj>git add index.html

C:\Users\DeafDave\prj>git add style.css

C:\Users\DeafDave\prj>git commit -m "first commit"
[master (root-commit) 61b2318] first commit
 2 files changed, 44 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

C:\Users\DeafDave\prj>git remote add origin https://github.com/deafdave/polymer.git

C:\Users\DeafDave\prj>git push -u origin master
Counting objects: 4, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 729 bytes | 0 bytes/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/deafdave/polymer.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

C:\Users\DeafDave\prj>