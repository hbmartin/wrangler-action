---
"wrangler-action": minor
---

This reapplies [303](https://github.com/cloudflare/wrangler-action/pull/303) add parity with pages-action for pages deploy outputs. Thanks @courtney-sims! - Support pages-deployment-id, pages-environment, pages-deployment-alias-url and deployment-url outputs for Pages deploys when wrangler version is >=3.81.0. deployment-alias-url was also deprecated in favour of pages-deployment-alias.
