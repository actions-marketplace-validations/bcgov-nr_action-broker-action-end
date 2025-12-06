# Broker Action End V3

This action ends an action, so progress with an intention can be tracked.

If you encounter an error, ensure that the Broker URL is correct and that the intention was not automatically closed at the end of the time to live (ttl) period.

# Broker Documentation

Please refer to the [NR Broker Repository](https://github.com/bcgov-nr/nr-broker) for full usage details.

# Usage

<!-- start usage -->
```yaml
- uses: bcgov-nr/action-broker-action-end@v3
  with:
    # The token of the action to start
    action_token: ''

    # The broker url.
    # Default: 'https://broker.io.nrs.gov.bc.ca'
    broker_url: ''

    # The outcome of the action. Must be 'success', 'failure' or 'unknown'
    # Default: 'success'
    outcome: 'success'
```
<!-- end usage -->

# License

The scripts and documentation in this project are released under the [Apache License](LICENSE)

