# AWallet

```
Algorand community wallet built by community for community, fully open source since 2021
```

Currently working features:

- Creating wallet / Export wallet / Import wallet / Destroying wallet
- Creating account, Creating multisign account, Adding public account
- Account overview
- Transaction overview
- Sending algo payment, Signing and sending multisig payments
- Multilanguage support
- Rekeying of standard accounts, multisig accounts and rekeyed accounts

Source code: https://github.com/scholtz/wallet

Technology stack: Vue3, JsAlgoSDK, CICD to pure HTML+JS

Docker image: https://hub.docker.com/r/scholtz2/a-wallet/tags

Please create a pull request for contribution to the project.

## Deployments

https://www.a-wallet.net - Most stable deployment - Private onprem K8S cluster run by Scholtz&Co. Docker image released after some time in main branch deployment.

## Main branch deployments

- https://main.h3.a-wallet.net - Private onprem K8S cluster run by Scholtz&Co
- https://vercel.a-wallet.net - Built and hosted by vercel
- https://ww2.a-wallet.net - Built by github and hosted on github pages
