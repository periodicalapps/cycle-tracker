Notes
Make the PWA accessible: https://developer.mozilla.org/en-US/docs/Learn/Forms
Github pages to PWA https://christianheilmann.com/2022/01/13/turning-a-github-page-into-a-progressive-web-app/

https://docs.gitlab.com/ee/user/project/pages/getting_started/pages_from_scratch.html

Moved to github for easier pages deployment.
- [ ] Will need to sort that out for the final apps.

localStorage seems OK for settings key-value pairs (theme, default solvent, default sort)
Client side storage options: https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API/Using_IndexedDB
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Client-side_storage


To get the js and html working, needed the  <form id="new-period"> ID in there, but also get elements.

Manifest: app-name.json file.

Note: always save changes before checking effects. VSCode keeps them in the buffer.

Start url in manifest could be a good way to setup changes. (tutorial/preferences
"comments": "Match the background colour with the theme colour, so it loads seamlessly.",)

The install event happens when the app is used for the first time, or when a new version of the service worker is detected by the browser. 

Note: Updating VERSION is important when making changes to any application resource, including the CSS, HTML, and JS code, and image assets. The version number, or any change to the service worker file, is the only way to force an update of the app for your users.

Hard browser refresh: On MacOS: Shift+Command+R.
So to see updates, change the version number and hard refresh.
Or:
You can unregister a service worker by clicking on the unregister button in the browser developer tools. Hard refreshing the page will re-register the service worker and create a new cache.