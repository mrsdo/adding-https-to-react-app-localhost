# Addings HTTPS to a React application (MacOS X)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Additional Resources:

[Installing https via openssl ](https://flaviocopes.com/react-how-to-configure-https-localhost/)

[Addings PEM files to keychain on MacOS](https://flaviocopes.com/macos-install-ssl-local/)

## Available Scripts

After installation and changes to package.json, you can, run:

### `npm run start`

Runs the app in the development mode.\
Open [https://localhost:3000](https://localhost:3000) to view it in your browser.

Using Safari, literally drag/drop local.cer to a secure directory.
Open that directory, then double-click the local.cer file to add it to the MacOS system keychain.
Make sure to reset Trust to Always Trust. 
