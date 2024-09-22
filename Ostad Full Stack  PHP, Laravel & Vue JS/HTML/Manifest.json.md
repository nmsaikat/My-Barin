
## Structure of ``manifest.json``

1. ``name:``
	- The full name of the application.

2. ``short_name:``
	- A shorter name for the application, used where space is limited.

3. ``start_url:``
	- The entry point of the application when launched. It's relative to the location of the manifest file.

4. ``display:``
	- Defines the preferred display mode, such as ``fullscreen`` , ``standalone`` , ``minimal-ui ,`` or ``browser``.

5. ``background_color:``
	- Specifies a background color for the splash screen when the app is launched.

6. ``description:``
	- A brief description of the application.

7. ``lang:``
	- The primary language of the app, specified using a language tag ( ``en-US`` , ``fr`` , etc.).

8. ``dir:``
	- The text direction of the app, like ``ltr`` (left-to-right) or ``rtl`` (right-to-left).

9. ``orientation:``
	- Specifies the default orientation of the app, such as ``portrait`` or ``landscape``.

10. ``theme_color:``
	- Defines the default theme color for the application.

11. ``icons:``
	- An array of image objects representing the app icon in different sizes. Each object typically includes ``src`` , ``sizes`` , and ``type`` properties.

12. ``scope:``
	- Specifies the set of URLs that the browser considers to be within your app, and navigations to those URLs stay within the app.

13. ``related_applications:``
	- An array of objects specifying native apps that are related to the web app, potentially with a ``platform`` and a ``url`` or ``id`` depending on the platform.

```js
{
  "name": "Example App",
  "short_name": "App",
  "start_url": "/",
  "display": "standalone",
  "background_color": "#ffffff",
  "description": "An example Progressive Web App",
  "lang": "en-US",
  "dir": "ltr",
  "orientation": "portrait",
  "theme_color": "#000000",
  "icons": [

{
      "src": "icon/lowres.webp",
      "sizes": "48x48",
      "type": "image/webp"

}, {

      "src": "icon/hd_hi.ico",
      "sizes": "72x72 96x96 128x128 256x256",
      "type": "image/x-icon"

} ],

  "scope": "/",
  "related_applications": [

    {      "platform": "play",
      "url": "https://play.google.com/store/apps/details?id=com.example.app"

}, {

      "platform": "itunes",

      "url": "https://itunes.apple.com/app/example-app/id123456789"
    }

] }
```