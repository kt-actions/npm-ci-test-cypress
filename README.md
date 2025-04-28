# npm-ci-test-cypress

NPM Continuous Integration test action (with Cypress action)

- checkout
- kt-actions/npm-run-script
  - setup node environment (kt-actions/setup-node-minmax, use cache)
  - install dependencies or restore from cache (uses cache)
  - run `build-script`
- cypress-io/github-action
  - with `run-script`
