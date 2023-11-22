# Authentication and Authorization

The goals of this repository:
* Establish a thorough understanding of modern authentication and authorization standards
* Investigate implementation details
* Identify how to integrate proper auth/auth into development framework in a way that:
    * allows an open source, self-hosted option for use during development: [Keycloak](https://www.keycloak.org/) or [ASP.NET Core Identity](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-8.0&tabs=visual-studio)
    * seamlessly transitions to a cloud-native platform in production: [Microsoft Entra](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

## Contents

* [Standards](./standards)
    * [OAuth](./standards/oauth.md)
    * [OpenID](./standards/openid.md)

## Resources

* [OAuth](https://oauth.net/2/)
    * [OAuth Modern Guide](https://fusionauth.io/articles/oauth/modern-guide-to-oauth)
    * [OAuth 2 Simplified](https://aaronparecki.com/oauth-2-simplified/)
    * [RFC 6749 - The OAuth 2.0 Authorization Framework](https://datatracker.ietf.org/doc/html/rfc6749)
* [OpenID](https://openid.net/)
* [ASP.NET Core Security](https://learn.microsoft.com/en-us/aspnet/core/security/?view=aspnetcore-8.0)


## Training
* [Secure a .NET Web App with the ASP.NET Core Identity framework](https://learn.microsoft.com/en-us/training/modules/secure-aspnet-core-identity/)