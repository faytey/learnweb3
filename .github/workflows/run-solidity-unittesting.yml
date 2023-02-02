
  name: Running Solidity Unit Tests
  on: [push]

  jobs:
    run_sol_contracts_job:
      runs-on: ubuntu-latest
      name: A job to run solidity unit tests on github actions CI
      steps:
        - name: Checkout
          uses: actions/checkout@v2
        - name: Run SUT Action
          uses: EthereumRemix/sol-test@v1
          with:
            test-path: 'tests'
            compiler-version: '0.8.15'
    