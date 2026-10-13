# LIZORIA VK Auth — public landing only

Public GitHub Pages frontend for LIZORIA. **Not an operational OAuth callback.**

The `callback/` path is a placeholder and must NOT be registered as a production OAuth redirect URI: GitHub Pages cannot securely exchange an authorization code for tokens, and callback URLs can be logged by hosting infrastructure. Use a backend HTTPS callback with server-side state validation, PKCE where applicable, and secret storage. No secrets or access tokens belong in this repository.

Pages publishing must be enabled manually in repository Settings → Pages → Deploy from a branch → main / (root).

Expected URL after enabling Pages: https://sheff1981.github.io/lizoria-vk-auth/

Do not use the public Pages URL as an OAuth redirect until an appropriate backend flow is implemented and verified.
