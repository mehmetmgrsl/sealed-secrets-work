# WIP

### Why

- Storing sensitive data like secrets objects for kubernetes in a Github repository is not safe and also not recommended. Because raw Kubernetes secrets, which are encoded in base64 and easily decodable.

- Sealed-secrets allow you to encrypt secrets to safely store in a public repository. (2*) 

### Resources

1* https://github.com/bitnami-labs/sealed-secrets

2* [Sealed Secrets: Safeguarding Your Kubernetes Secrets | Step By Step Tutorial | KodeKloud](https://www.youtube.com/watch?v=wWMJCY2E0d4)
