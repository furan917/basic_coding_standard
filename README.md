# Basic Coding Standard Repo, set for magento 2 currently

## How to use code style tools in module?

- Create a copy of this module in your organisation
- Copy the basic-coding-standard action in the .github to a test module, point it to your new repo + update the env ${{ secrets.PHP_VERSION_CODE_QUALITY }}
- create a PR in your module and watch it work
- Once happy and you can see it works, advance on this to your heart desires

## This currently includes 2 basic rulessets, Rector & PHPCS

1. Rector: see src/rector.php  (List of rules https://github.com/rectorphp/rector/blob/main/docs/rector_rules_overview.md)
2. PHPCS: see src/ruleset.xml (List of premade standards https://github.com/squizlabs/PHP_CodeSniffer/tree/master/src/Standards)
