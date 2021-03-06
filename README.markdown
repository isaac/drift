Drift
=======

Drift is a [Gist](http://gist.github.com)-backed text editor written in [MacRuby](http://www.macruby.org/). Depending on how you look at it, it either lets you edit your gists, or gives you an always-already versioned, cloud-backed text-editor. Here's a screenshot:

![Drift circa 8/14/9](http://img.skitch.com/20090814-pukd9qr6r43sbg75x1hrhr9wp1.jpg)

Features
---------

* Create and upload new gists
* Edit and update existing gists (created with Drift)
* Store github credentials
* Display activity when going over the wire to GitHub
* Copy gist url into clipboard on creation

Drift Needs a Logo!
-------------------

Do you have slick Mac app logo-creating ability? Now accepting submissions: greg DOT borenstein AT gmail DOT com


TODO:
--------

* deal with save prompt on quit for unsaved docs
* rename GEDocument's associated_library to something that indicates it's a tableView and not a library; like maybe "associatedTableView"
* unifying networking code to remove duplication from GEDocument#putGist and GEDocument#postGist
* break out functionality for copying gist url
* error handling on talking to GH
* make creating a new document not open a new window
* figure out why GEGistListDelegate doesn't have access to associatedDocument in numberOfRowsInTableView
* control-click menu to put gist url in clipboard
* control-click menu to remove gist from tracked gists
* control-click menu to refresh gist from server
* control-click menu to delete gists
* clean up some of the logging
* import all gists belonging to the user (if we have gh info)