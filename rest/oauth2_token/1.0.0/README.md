To regenerate the project in /tmp and compare with the existing, run from parent folder ~/networknt

```
java -jar light-codegen/codegen-cli/target/codegen-cli.jar -f swagger -o /tmp/token -m model-config/rest/oauth2_token/1.0.0/swagger.json -c model-config/rest/oauth2_token/1.0.0/config.json
```