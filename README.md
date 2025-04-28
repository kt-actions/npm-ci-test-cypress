# npm-ci-test-cypress

NPM Continuous Integration test action (with Cypress action)

- checkout
- kt-actions/npm-run-script
  - setup node environment (kt-actions/setup-node-minmax, use cache)
  - install dependencies or restore from cache (uses cache)
- cypress-io/github-action
  - build with `build-script`
  - start with `start-script`
