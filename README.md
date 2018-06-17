# PHPUnit files for Magento 1

## Usage

Just copy all the files in your local Magento 1 root folder.

After files are copied, you must setup PHPStorm to handle this files for the Test Framework configuration

## PHPStorm

The steps to setup PHPStorm for using PHPUnit as your Test Framework are:

1. At Preferences, setup phpunit phar path file on Test Frameworks (Languages and Frameworks > PHP > Test Frameworks)
2. Select the Test Runner files under dev folder on the step 1 screen (phpunit.xml as defaul configuration file and bootstrap.php as default bootstrap file)
3. At Run -> Edit Configurations, create a PHPUnit configuration using the '+' button.
4. Select the directory, class, or method on the assistant and save changes.
5. Run or debug your test!