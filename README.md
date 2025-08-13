# zero-trust-iAM-lab
# Zero-Trust IAM Lab (Keycloak + LDAP + SCIM + RBAC + MFA)

Spin up Keycloak (IdP), a SCIM microservice (FastAPI), and a sample Flask app (OIDC). Great for interviews.

## Quick start
```bash
cd infra
docker compose up -d --build
