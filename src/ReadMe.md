
Build via:

```
docker build --pull --rm -f .\Newsletter.Api\Dockerfile  -t moerwald/newsletterapi:1.2 $(PWD)
docker build --pull --rm -f .\Newsletter.Reporting.Api\Dockerfile  -t moerwald/newsletterreportingapi:1.0 $(PWD)
```