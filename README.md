# servedubai.com redirect

GitHub Pages site for `servedubai.com`. Every URL is sent to the same path on
`https://servedubai.ae`, which is hosted on Cloudflare Pages.

The domain's registrar account is not available right now, so its nameservers
cannot be moved to Cloudflare, and Cloudflare Pages only serves a bare domain
whose zone is on Cloudflare. So `servedubai.com` points here (GitHub Pages A records)
and this page forwards visitors. Same setup as marblepro-apex-redirect.

Once the nameservers move to Cloudflare, replace this with a Cloudflare
redirect rule and delete this repository.
