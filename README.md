# config-server-test

The order the config files are brought in ... top one first - overridden by lower ones

* application.yml
* application.properties
* <appname>.properties
* <appname>-<profile>.properties

You can also just have a json file and then target that json file directy in the code

- Need to test how the cook-encryption.properties file works with encrypted data

the refresh didn't work https://docs.vmware.com/en/Spring-Cloud-Services-for-VMware-Tanzu/3.2/spring-cloud-services/GUID-config-server-writing-client-applications.html#refresh-client-application-configuration

The refresh of the mirrors didn't seem to work either


The only way I can get it to work is to restart the application