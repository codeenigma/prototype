# Code Enigma Prototype tool

## Usage

1. Install dependencies with NPM/Yarn
    ```
    yarn install
    ```
    or
    ```
    npm install
    ```
2. Generate the prototype and start php built-in server.

   ```
   npm start

   ```
3. Browse http://localhost:8080/ for the prototype, http://localhost:8000/ for JsonPopulate

## Drupal synchronisation

1. Adjust the path (relative) to the Drupal theme in the .npmrc file.

2. Synchronize the 'assets' folder to the theme with

   ```
   npm run sync:drupal
   ```
* Note: this is a "destructive" operation, do not keep unmanaged files in the "assets" folder of your theme. *
