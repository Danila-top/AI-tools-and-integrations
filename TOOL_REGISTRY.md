# Tool registry

| Capability | Typical use | Verification |
|---|---|---|
| Repository write | Create/update code and docs | Read back changed file |
| Database access | Query structured state | Validate query result |
| File storage | Archive and retrieve artifacts | Verify path and metadata |
| Deployment | Publish an application | Open and test deployed result |
| Computer control | Operate a user-authorized machine | Observe resulting state |

Never record secrets or access tokens in this registry.
