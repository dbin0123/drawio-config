# diagrams.net Configuration

With the *diagrams.net configuration* app you can edit your custom configuration for diagrams.net. This app will generate a custom configuration based on the information from the diagrams.net helpdesk ([see here](https://desk.draw.io/support/solutions/articles/16000058316-how-to-configure-draw-io-)). You are able to add custom colors, presets and fonts to diagrams.net.

## configure online
You can open the configurator on [drawio-config.herokuapp.com](https://drawio-config.herokuapp.com/)


## Add your configuration to diagrams.net

If you open diagrams.net (either on [diagrams.net](https://app.diagrams.net) or as desktop app) you need to open the *diagrams.net Configuration …* from the *Extras* menu. Paste the json string that you copied from this app into the input field and press the *apply* button. You need to restart diagrams.net to apply the configuration.

## Run it locally

This app is build with `create-react-app` and can also run on your local mashine (node/npm needs to be installed):

```bash
#-- using yarn: --
yarn
yarn start

# -- using npm: --
npm install
npm run start
```
