# ABAP package version shield

https://img.shields.io/endpoint?url=https://<LAMBDA>.execute-api.eu-west-1.amazonaws.com/default/mytest?type=github&owner=sbcgua&repo=mockup_loader&file=src/zif_mockup_loader_constants.intf.abap

- type=github
- owner=sbcgua
- repo=mockup_loader
- file=src/zif_mockup_loader_constants.intf.abap
- attr=version (default)


## Useful
- https://stackify.com/aws-lambda-with-node-js-a-complete-getting-started-guide/
- https://postman-echo.com/get?foo1=bar1

## Deployment
- `serverless config credentials --provider aws --key <your_access_key_id> --secret <your_access_key_secret>`
- `serverless deploy`
- `serverless logs -f getAbapVersionShieldJson --stage dev`
- `serverless info -f getAbapVersionShieldJson --stage dev` - url in particular

