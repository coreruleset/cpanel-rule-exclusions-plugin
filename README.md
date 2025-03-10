# OWASP CRS - cPanel Rule Exclusions Plugin

[![Integration tests](https://github.com/coreruleset/cpanel-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg)](https://github.com/coreruleset/cpanel-rule-exclusions-plugin/actions/workflows/integration.yml)
[![.github/workflows/lint.yml](https://github.com/coreruleset/cpanel-rule-exclusions-plugin/actions/workflows/lint.yml/badge.svg)](https://github.com/coreruleset/cpanel-rule-exclusions-plugin/actions/workflows/lint.yml)

## Description

This plugin contains rule exclusions for [cPanel](https://cpanel.net/), a web hosting control panel. These rule exclusions are designed to resolve common false positives and allow for easier integration with the OWASP CRS (CRS).

## Installation

For full and up to date instructions for the different available plugin installation methods, refer to [How to Install a Plugin](https://coreruleset.org/docs/concepts/plugins/#how-to-install-a-plugin) in the official CRS documentation.

### Conditionally enable plugins for multi-application environments

For full and up to date instructions on how to conditionally enable/disable this plugin on a multisite environment, please refer to [Conditionally enable plugins for multi-application environments](https://coreruleset.org/docs/concepts/plugins/#conditionally-enable-plugins-for-multi-application-environments) in the official CRS documentation.

## Testing

After the plugin is enabled, cPanel should work without problems caused by CRS (for example, false positives while blocking requests). If problems still occur then please file a new issue on [GitHub](https://github.com/coreruleset/cpanel-rule-exclusions). (Note that high paranoia level deployments may require additional tuning beyond this plugin.)

## License

Copyright (c) 2022-2024 OWASP CRS project. All rights reserved.

The OWASP CRS and its official plugins are distributed under Apache Software License (ASL) version 2. Please see the enclosed LICENSE file for full details.
