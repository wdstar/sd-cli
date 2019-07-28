# sd-cli
Screwdriver CLI

## Development

1. Download Screwdriver API Swagger specification file.
    ```bash
    $ mkdir swagger
    $ curl -L https://api.screwdriver.cd/v4/swagger.json | jq . > swagger/sd-cd.json
    ```
