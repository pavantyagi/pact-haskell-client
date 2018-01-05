# A REST client for using the pact language and blockchain playground environment

Haskell client for blockchain language and playground pact REST server https://github.com/kadena-io/pact

You need to have pact installed. Run it as a service using:

    cd pact_server/
    pact --serve pact_server_config.yaml

Note: the pact server serves and static files in the directory where you run it.

## Implementation notes

- uses the excellent wreq REST client library: http://www.serpentine.com/wreq/
