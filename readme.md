TinyMCE - The JavaScript Rich Text editor
==========================================

TinyMCE Concord: Do not forget to cherry-pick those commits
-----------------------------------------------------------
```
* 8f1cd9dff (HEAD -> tinymce-upgrade, tag: 4.7.1-patch-4) Do not scan for images on set content
* c87160a6d (tag: 4.7.1-patch-3) FIX: tinymce selctor bug
* 610c71d19 (tag: 4.7.1-patch-2) FIX: Check dom node preset on init editor
* a27ec6d17 (tag: 4.7.1-patch-1) extend condition to get specified font property
* 2eb0adf53 add gitignore
* fe43edff3 add uglify bash script
```

Building TinyMCE
-----------------
Install [Node.js](https://nodejs.org/en/) on your system.
Clone this repository on your system
```
$ git clone https://github.com/tinymce/tinymce.git
```
Open a console and go to the project directory.
```
$ cd tinymce/
```
Install `grunt` command line tool globally.
```
$ npm i -g grunt-cli
```
Install all package dependencies.
```
$ npm install
```
Now, build TinyMCE by using `grunt`.
```
$ grunt
```

Build tasks
------------
`grunt`
Lints, minifies, unit tests and creates release packages for TinyMCE.

`grunt test`
Runs all qunit tests on PhantomJS.

`grunt --help`
Displays the various build tasks.

Bundle themes and plugins into a single file
---------------------------------------------
`grunt bundle --themes=modern --plugins=table,paste`
Minifies the core, adds the modern theme and adds the table and paste plugin into tinymce.min.js.

Contributing to the TinyMCE project
------------------------------------
TinyMCE is an open source software project and we encourage developers to contribute patches and code to be included in the main package of TinyMCE.

__Basic Rules__

* Contributed code will be licensed under the LGPL license but not limited to LGPL.
* Copyright notices will be changed to Ephox Corporation, contributors will get credit for their work.
* All third party code will be reviewed, tested and possibly modified before being released.
* All contributors will have to have signed the Contributor License Agreement.

These basic rules ensures that the contributed code remains open source and under the LGPL license.

__How to Contribute to the Code__

The TinyMCE source code is [hosted on Github](https://github.com/tinymce/tinymce). Through Github you can submit pull requests and log new bugs and feature requests.

When you submit a pull request, you will get a notice about signing the __Contributors License Agreement (CLA)__.
You should have a __valid email address on your GitHub account__, and you will be sent a key to verify your identity and digitally sign the agreement.

After you signed your pull request will automatically be ready for review & merge.

__How to Contribute to the Docs__

Docs are hosted on Github in the [tinymce-docs](https://github.com/tinymce/tinymce-docs) repo.

[How to contribute](https://www.tinymce.com/docs/advanced/contributing-docs/) to the docs, including a style guide, can be found on the TinyMCE website.
