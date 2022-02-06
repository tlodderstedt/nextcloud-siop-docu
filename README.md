# Description

This repository contains slides and example messages that show how [SIOP v2](https://openid.net/specs/openid-connect-self-issued-v2-1_0.html)
and [OpenID Connect for Verifiable Presentations](https://openid.bitbucket.io/connect/openid-connect-4-verifiable-presentations-1_0.html)
can be used to log into a Nextcloud instance.

In our prototype, we use Hyperledger Indy Anoncreds that are requested 
using the Presentation Exchange syntax. The PE format has to be translated to
Anoncred proof requests before they can be processed by the Hyperldeger Indy SDK.
The messages that are exchanged during login as well as the translation from PE to
Anoncred proof requests can be found in the ``messages/`` folder.
