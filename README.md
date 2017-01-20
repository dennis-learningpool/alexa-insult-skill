# alexa insult skill

An [alexa-app](https://github.com/alexa-js/alexa-app) based skill to run along with [alexa-app-server](https://github.com/alexa-js/alexa-app-server).

This app is pretty puerile, and I make no apologies.

# Usage

Follow the documentation in the alexa-app and alexa-app-server projects to get the app up and running somewhere, then define an environment variable INSULTS as a list of `|` separated phrases that include the tag `{name}` appropriately, e.g. `"Get lost {name}"`. 
