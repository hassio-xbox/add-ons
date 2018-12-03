# Xbox Live Credentials Manager

The Xbox Live Credentials Manager add-on performs authentication against Xbox Live and maintains the access token used by the Xbox Live API Service. It uses the Redis add-on to pass the token data over to the Xbox Live API Service.

## Installation

Please install and start the Redis add-on prior to installing and configuring this add-on. Once installed you must configure your Xbox Live account information. _I highly recommend you create a new account for this_ because it cannot use 2FA authentication. Enter the account information in place of "set me" and star the service. Check the logs to ensure you get "Cached authorization header OK." Once you have success here you can continue on to installing the Xbox Live API Service add-on.

## Troubleshooting

If you get errors and you've already validated your username and password it's likely that you need to approve the sign in request. Do so by visiting https://account.live.com, clicking security and selecting Review Activity. 