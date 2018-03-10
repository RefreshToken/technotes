# oauth2

OAuth2
https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth#oauth-central-components

### Clients
  * Public
  * Confidential

### Tokens
  * Access Token
  * Refresh Token

### OAuth Flows
  * Implicit Flow (2 Legged OAuth) - browser only (for SPAs)
  * Authorization Code Flow (3 Legged) - browser-server, back-channel and front-channel
  * Client Credential Flow - server-server
  * Resource Owner Password Flow - legacy mode, you have API but have old-scholl clients who can only user/password
  * Assertion Flow - similar to Client Credential Flow (for SAML integrations)
  * Device Flow - for TV, CLI clients

http://openid.net/connect/
OpenID Connect 1.0 is a simple identity layer on top of the OAuth 2.0 protocol.
