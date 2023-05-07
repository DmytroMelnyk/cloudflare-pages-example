## Good sources:

for local development its possible to use 2 approaches:
https://github.com/cloudflare/workers-sdk/issues/1873
CLOUDFLARE_API_TOKEN=token npx wrangler pages publish dist/my-app --project-name pages-dev

or 
CLOUDFLARE_API_TOKEN=token CLOUDFLARE_ACCOUNT_ID=accountid npx wrangler pages publish dist/my-app --project-name pages-dev
But second approach fits CI

Deployment:
https://developers.cloudflare.com/pages/how-to/use-direct-upload-with-continuous-integration/#deploy-with-wrangler