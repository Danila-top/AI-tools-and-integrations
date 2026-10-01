# Capability matrix

| Capability | Read | Write | Verification |
|---|---:|---:|---|
| GitHub repositories | yes | yes | read changed resource back |
| File storage | yes | depends on connector | inspect metadata/content |
| Databases | yes | depends on connector | query after mutation |
| Deployment | yes | depends on provider | test deployed endpoint |
| Computer control | yes | yes when authorized | observe resulting state |

Before granting an agent a new capability, document its scope, failure mode, and verification method.
