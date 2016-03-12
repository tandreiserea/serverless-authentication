#serverless-authentication

This project is aimed to be generic authentication library for serverless (http://www.serverless.com)


set environmental variables for config, e.g.

sls env set -k PROVIDER_FACEBOOK_ID -v NNNNN
sls env set -k PROVIDER_FACEBOOK_SECRET -v NNNNN
sls env set -k PROVIDER_GOOGLE_ID -v NNNNN
sls env set -k PROVIDER_GOOGLE_SECRET -v NNNNN
sls env set -k PROVIDER_MICROSOFT_ID -v NNNNN
sls env set -k PROVIDER_MICROSOFT_SECRET -v NNNNN
sls env set -k REDIRECT_CLIENT_URI -v http://laardee.github.io/serverless-authentication-gh-pages/
sls env set -k REDIRECT_URI -v https://*API-ID*.execute-api.eu-west-1.amazonaws.com/dev/callback/{provider}
sls env set -k TOKEN_SECRET -v token-secret
