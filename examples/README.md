# Examples

The `ballerinax/mailchimp.marketing` connector provides practical examples illustrating usage in various scenarios.

1. [List Mailchimp Audiences](https://github.com/ballerina-platform/module-ballerinax-mailchimp.marketing/tree/main/examples/list_audiences) – Fetch and display a list of all your Mailchimp audience lists.
2. [List Mailchimp Campaigns](https://github.com/ballerina-platform/module-ballerinax-mailchimp.marketing/tree/main/examples/list_campaigns) – Fetch and display a list of all campaigns from your Mailchimp account.

## Prerequisites

- Ballerina Swan Lake Update 12 (or later)
- A Mailchimp account
- A Mailchimp API Key. You can generate an API key from your Mailchimp account settings: `Profile > Extras > API Keys`.

## Running an example

Execute the following commands to build an example from the source:

* To build an example:

    ```bash
    bal build
    ```

* To run an example:

    ```bash
    bal run
    ```

## Building the examples with the local module

**Warning**: Due to the absence of support for reading local repositories for single Ballerina files, the Bala of the module is manually written to the central repository as a workaround. Consequently, the bash script may modify your local Ballerina repositories.

Execute the following commands to build all the examples against the changes you have made to the module locally:

* To build all the examples:

    ```bash
    ./build.sh build
    ```

* To run all the examples:

    ```bash
    ./build.sh run
    ```
