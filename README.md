
# Module Grantham NewsletterGraphQl

    ``grantham/module-newslettergraphql``

- [Main Functionalities](#markdown-header-main-functionalities)
- [Installation](#markdown-header-installation)

## Main Functionalities
Unsubscribe from Newsletter using graphql

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

- Unzip the zip file in `app/code/Grantham`
- Enable the module by running `php bin/magento module:enable Grantham_NewsletterGraphQl`
- Apply database updates by running `php bin/magento setup:upgrade`\*
- Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

- Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
- Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
- Install the module composer by running `composer require grantham/module-newslettergraphql`
- enable the module by running `php bin/magento module:enable Grantham_NewsletterGraphQl`
- apply database updates by running `php bin/magento setup:upgrade`\*
- Flush the cache by running `php bin/magento cache:flush`
