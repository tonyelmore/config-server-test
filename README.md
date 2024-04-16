# config-server-test

The order the config files are brought in ... top one first - overridden by lower ones

* application.yml
* application.properties
* <appname>.properties
* <appname>-<profile>.properties

You can also just have a json file and then target that json file directy in the code

- Need to test how the cook-encryption.properties file works with encrypted data
