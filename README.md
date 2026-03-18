# atlas-external-apps
A collection of external apps for Atlas Launcher created by the community.

# Installation Guide:
1) Go to your home directory
2) Open AtlasLauncher
3) If a folder isn't in that directory make a folder called externalapps
4) Unzip & Drag n Drop your external app folder into there
5) Reload (CTRL + R) or Restart the app
6) Done! your external app should now show there!

External Apps are maintained by the source NOT by the creator of them as they have no control over those apps/sites.

# How To Make An External App
1) In your externalapps folder make a folder based on the site you want to turn into an app
2) Get a nice screenshot of the home page or really any page that seems fitting
3) Name that screenshot banner.png (By default it should be a png, so just rename it as banner if you can't see that extension)
4) Create a config.json file and insert the following code template below in it.

```json
{
  "name": "AnimeKai",
  "url": "https://animekai.to/home",
  "contentType": "sfw"
}
```

5) Replace the name and url with the accurate name and url of your desired app.
