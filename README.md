# Theme-UAT
Repository for Envato theme developers to check in their themes during the UAT process

Requirements -

* Theme developer must have a GitHub account
* Theme developer will upload their bundle to https://www.github.com/Bigcommerce-Envato/Theme-UAT
* All theme bundles must be zipped using the `stencil bundle` command using the latest Stencil CLI, https://github.com/bigcommerce/stencil-cli
* Exceptions to theme requirements must be noted with sufficient details in the Changelog file during UAT process and must be omitted for final release
* Bundles should have all meta information completed including:
 * Name
 * Version
 * Documentation URL
 * Author information (name, email, URL)
 * Composed image
* Feedback will be provided to the author email address within the `config.json` file
* Bundles must use versioning through UAT process.  EX: If the first submitted bundle is `New_Theme v0.0.1`, the next version submitted must be a higher version number, `New_Theme v0.0.2`
* All themes must install correctly in the storefront and using Stencil CLI
