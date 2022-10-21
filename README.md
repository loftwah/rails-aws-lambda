# LoftwahRailsLambda

- Rails v6.x on Ruby 2.7 runtime.
- Integrated JavaScript development.
- Compiles CSS/JS assets.
- No ActiveRecord. Read our [Database Options](https://lamby.custominktech.com/docs/database_connections) guides.

## Setup & Deploy

Copy and fill out the `.env` file from the example.

```bash
./bin/bootstrap
./bin/setup
./bin/deploy
```

## Next Steps

- Provide a new value for the `SECRET_KEY_BASE`. Alternatively, you can set this using Dotenv & SSM Parameter Store in the [Environments & Configuration](https://lamby.custominktech.com/docs/environment_and_configuration) section of your build file.
- Using JavaScript? everything is setup and ready to go.
