---
layout: page
title: Install the BeLL Apps on your local computer the easy way
tagline: 
---

1. Install Firefox Web Browser on your local computer. See [http://firefox.com](http://firefox.com)
1. Install CouchDB on your local computer. See [http://couchdb.apache.org](http://couchdb.apache.org)
1. Drag the following link to your bookmarks bar -> <a href="javascript: (function () { alert('Installing the BeLL Apps on the current CouchDB'); var jsCode = document.createElement('script'); jsCode.setAttribute('src', 'https://raw.github.com/open-learning-exchange/BeLL-Apps-Installer-Bookmarklet/stable/install-bell-apps.js'); document.body.appendChild(jsCode); }() );">BeLL Apps Installer Bookmarklet</a>
1. Go to your local CouchDB's Futon at [http://127.0.0.1:5984/_utils](http://127.0.0.1:5984/_utils)
1. Create your first CouchDB Server admin by clicking "Fix this" in the bottom right of the Futon web page and then follow the instructions. You will need to remember these credentials for the BeLL Apps install.
1. Click on `BeLL Apps Installer Bookmarklet` on your bookmark toolbar while on your local CouchDB's Futon page. Follow the prompts. Note that if you have been given a different "Source Server URL" to use, the install prompts will give you an opportunity to give it this new Source Server URL.
1. The script may take a few minutes to complete. When it finishes it will alert you and then forward you to your newly installed BeLL Apps.



