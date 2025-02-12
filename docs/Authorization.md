## Overview 
1. The scope of these end points is to standardise issuance of access tokens using existing OAuth2/OIDC standards. <br>
2. Helps standardise end point access across g2p complaint api stack using x-access-token that is <b>compliant with JWT specs</b>. <br>
3. DPGs & COTS products may also provide similar authz api end points with G2P Connect documented scopes as part of each country specific implementation (if any). <br>
4. Additional security like IP white listing, private networks, etc are outside the scope of G2P Connect standards. Each country shall decide required operational models. <br>

### References
1. API specification [link](https://g2p-connect.github.io/specs/dist/g2p-authz.html)
2. Discussion [thread](https://github.com/G2P-Connect/.github/discussions)


## Interface List
| Interface ID | End Point | Description | 
| ------------ | --------- | ----------- |
| AUTHZ-TOKN | /oauth2/client/token |  Provide access token to registered senders & receivers | 

## Request For Comments
1. Authorization Scopes - [AUTHZ-TOKN-Scope-Draft-01](https://github.com/G2P-Connect/specs/blob/draft/docs/rfc/specs-draft/g2p_authz_scope_codes.md)

## Integration Schematics

