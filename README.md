# sigridsong.neocities.org

<!-- 561-group-standards:badges:start -->
[![Causeway Services](https://img.shields.io/badge/561%20Group-Causeway%20Services-115e69)](https://github.com/causeway-services)
[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-115e69)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/causeway-services/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

Sigrid Song's author site at sigridsong.neocities.org, built with VICTOR from persona.json and the house's records (book manifests, launch plans, her newsletter's receipt) and published to Neocities.

## Code

This repository holds only the site's content and publishing parameters (`content/`, `books.json`, `neocities.json`, `data/records/deployments/`, `public/`). The executable application that builds and publishes it (storefront check, `static-site-publisher` config, scripts, tests, `package.json`) lives in [red-cup-engineering/sigridsong-site-service](https://github.com/red-cup-engineering/sigridsong-site-service); overlay a checkout of this repository on that one to build.
