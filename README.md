# RNBO with Vite.js

A starter template to build RNBO web apps using Vite.js

## System Requirements

a relatively recent Node

## Quick Start

To run locally:

```
npm install
npm run dev
```

The terminal output will log the Local url where the web app is served (probably http://localhost:5173/). Open that URL with your browser.

Click `Start Audio`. You should be hearing a sine wave, if it is all working.

To deploy:

```
npm run build
```

Under the `dist` folder you should see the artifacts. Copy all the files to your server.

You can use the Github Actions defined under `.github/workflows/publish.yml` to deploy the web app to Github Pages for your repository on every push to the main branch.

See it in action: https://ahmetkizilay.github.io/vite-rnbo/ 

## Project Structure

* Copy RNBO exports under `public/rnbo_export`
* Initialize the WebAudio and RNBO in main.js.


