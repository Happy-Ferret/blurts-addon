# blurts-addon
Code for the client-side add-on for Firefox Monitor. Communicates with the
[blurts-server](https://github.com/mozilla/blurts-server) service.

## Requirements
* Firefox 61 (use an unbranded build for testing - see https://wiki.mozilla.org/Add-ons/Extension_Signing#Unbranded_Builds)

## Setup
1. Clone the repo
2. $npm install
3. $npm run setup-breaches

## Running
$export FIREFOX_BINARY=/path/to/unbranded/firefox/binary
$export VARIATION_NAME=<integer from 0-4>
$npm start

If you leave out the VARIATION_NAME environment variable, a random variation will be assigned by shield.

## Building
$npm run build
