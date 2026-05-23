# idp-tailscale-sso
Step-by-step walkthroughs connecting Tailscale to identity providers
for SSO authentication and group-based access control.
 
## What problem this solves
By default Tailscale authenticates users with personal accounts.
Connecting an identity provider means only users in your organisation's
directory can join the tailnet and access policy can be driven by
group membership rather than individual device rules.
 
## Integrations to be documented
- [Google Workspace](google-workspace/) — personal Google account or Workspace
- [Okta](okta/) — Okta developer account (free)
 
## Key concepts covered
- OIDC vs SAML — what the difference is and when each is used
- How Tailscale uses identity provider groups to assign tags
- Writing ACL rules that respond to group membership
- What happens when a user is removed from the IdP
