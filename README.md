# Basic Coding Standard Repo, set for magento 2 currently

## How to use code style tools in module?

- Copy action in .github to your own module + update env ${{ secrets.PHP_VERSION_CODE_QUALITY }}
- create a PR in your module and watch it work

## This currently includes 2 basic rulessets, Rector & PHPCS

1. Rector: see src/rector.php  (List of rules https://github.com/rectorphp/rector/blob/main/docs/rector_rules_overview.md)
2. PHPCS: see src/ruleset.xml (List of premade standards https://github.com/squizlabs/PHP_CodeSniffer/tree/master/src/Standards)
