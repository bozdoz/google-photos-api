# Forked Google Photos API

Forked from the node.js sample application for the [Google Photos Library API](https://developers.google.com/photos).

## Set up
Before you can run this sample, you must set up a Google Developers project and configure authentication credentials. Follow the
[get started guide](https://developers.google.com/photos/library/guides/get-started) to complete these steps:
1. Set up a Google Developers Project and enable the **Google Photos Library API**.
1. In your project, set up new OAuth credentials for a web server application. Set the authorized JavaScript origin to `http://127.0.0.1` and the authorized redirect URL to `http://127.0.0.1:8080/auth/google/callback` if you are running the app locally.
1. The console will display your authentication credentials. Add the `Client ID` and `Client secret` to the file `config.js`, replacing the placeholder values:
```
// The OAuth client ID from the Google Developers console.
config.oAuthClientID = 'ADD YOUR CLIENT ID';

// The OAuth client secret from the Google Developers console.
config.oAuthclientSecret = 'ADD YOUR CLIENT SECRET';
```

You are now ready to run the sample:
1. Install dependencies: Run `npm ci`,
1. Start the app: Run `npm start`.

By default, the app will listen on port `8080`. Open a web browser and navigate to [http://127.0.0.1:8080](http://127.0.0.1:8080) to access the app.
