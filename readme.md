TinyMCE - The JavaScript Rich Text editor
==========================================

WATCHOUT
--------

When you update TinyMCE, be sure to keep those commits:
```
a25f3c7 FIX Check dom node preset on init editor
1131b8a (tag: 4.6.4-patch-2, tag: 4.6.4-patch-1, fix-aria-function) extend condition to get specified font property
78be7df gen min file from uglify bash script
39a4ed5 add uglify bash script
```
Update this readme file if you added more fixes or new features.

Don't forget to run `./uglify.sh` after your work is done.



Building TinyMCE
-----------------
Install [Node.js](https://nodejs.org/en/) on your system.
Clone this repository on your system
```
$ git clone https://github.com/WitchBird/tinymce-dist
```

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
