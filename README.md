I made this repo because this one 

https://github.com/zitadel/zitadel/blob/v4.3.0/docs/docs/self-hosting/deploy/docker-compose.yaml

has been non-functioning for new deployments for some months and many people were asking for a working version. 

The main point of the fix is to revert to login v1:

```yaml
environment:
  ZITADEL_DEFAULTINSTANCE_FEATURES_LOGINV2_REQUIRED: "false"
```
