# OpenRewrite Recipes

This project implements [OpenRewrite](https://docs.openrewrite.org) recipes for Oracle products.

Each folder of this project contains a group recipe that can contain multiple composite recipes. Each composite recipe is a set of recipes that you can use to migrate to a specific version of a product.

Example: `rewrite-weblogic` is a group recipe that contains composite recipes, like ones to migrate your WebLogic applications to WebLogic 14.1.2 and Java 21, or to WebLogic 14.1.2 and Java 17. With each new version of WebLogic, a new composite recipe will be added, for example, to migrate to WebLogic 15.1.1.

## Getting Started

Before getting started, select the recipe you want to use. Each recipe has its own README file that explains how to use it.

| Recipe | Description |
| :--- | --- |
| <code><span style="white-space: nowrap;">[rewrite-weblogic](rewrite-weblogic/README.md)&nbsp;</span></code> | Migrate your WebLogic applications to the latest version of WebLogic and Java with OpenRewrite. Automatically. |

> [!TIP]
> Click on the recipe name to get more details about a specific recipe (for example, `rewrite-weblogic`) and how to use it

## Get Help

For `rewrite-weblogic`:

We have a public Slack channel where you can get in touch with us to ask questions about using OpenRewrite recipes with WebLogic, or give us feedback or suggestions about features and improvements you would like to see. We would love to hear from you.

To join our channel, please visit this [site](https://join.slack.com/t/oracle-weblogic/shared_invite/zt-32ly2o8nl-HjLiIM4fazQ3vjZaqHPPRQ) to get an invitation. The invitation email will include details on how to access our Slack workspace. After you are logged in, please go to #wls-app-upgrade-openrewrite and say, "Hello!"

## Contributing

This project welcomes contributions from the community. Before submitting a pull request, please [review our contribution guide](./CONTRIBUTING.md).

## Security

Please consult the [security guide](./SECURITY.md) for our responsible security vulnerability disclosure process.

## License

Copyright (c) 2025 Oracle and/or its affiliates.

Released under the Universal Permissive License v1.0 as shown at
<https://oss.oracle.com/licenses/upl/>.
