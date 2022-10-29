# Addings HTTPS to a React application (MacOS X)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Author: https://flaviocopes.com/:

[Installing https via openssl ](https://flaviocopes.com/react-how-to-configure-https-localhost/)

[Addings PEM files to keychain on MacOS](https://flaviocopes.com/macos-install-ssl-local/)

The certificate files were NOT included in this repository.  Those files are added to your root directory after running the following commands from a terminal.

- openssl req -x509 -newkey rsa:2048 -keyout keytmp.pem -out cert.pem -days 365

- openssl rsa -in keytmp.pem -out key.pem

## Available Scripts

After installation (previous links to author's page above) to package.json, you can, run:

### `npm run start`

Runs the app in the development mode.\
Open [https://localhost:3000](https://localhost:3000) to view it in your browser.

Using Safari, literally drag/drop local.cer to a secure directory.
Open that directory, then double-click the local.cer file to add it to the MacOS system keychain.
Make sure to reset Trust to Always Trust. 
