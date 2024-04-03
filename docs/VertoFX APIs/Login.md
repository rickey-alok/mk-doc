# Login

## Method

Post

## Base URL

    https://api-v3-sandbox.vertofx.com/users/login

You first authenticate to the API by providing an "Authorization Token" in the request. You can get your Authorization token using the Authorization service.

This service will require you to send your Client ID & API Key which can be found on your VertoFX account profile.

Simply go to your Verto Account on the right hand side and select API Credentials option. Click on "Generate New API Key" button. Your Client ID and API key will be generated and displayed on the screen.

Click on Copy icon and save it securely for your own records.

For security reasons, once copied, the API key will be invisible. If you lost your existing API key or was not able to save it; then you need to generate a new one by following the same steps.

In response to your request sent to Authorization service, you’ll be provided with a token value that will be valid for 60 minutes. You need to add this token as header parameter to relevant requests requiring it.
