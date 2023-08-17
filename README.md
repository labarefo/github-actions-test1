# github-actions-test1

## dispathes
see postman collection: github-actions.postman_collection.json

## Encrypt sectert file with gpg
```bash
gpg --symmetric --cipher-algo AES256  secret.json
```
produces secret.json.gpg
