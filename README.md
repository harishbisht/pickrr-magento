# pickrr-magento
pickrr magento plugin for order placing


###Installation Instructions:
1: Download the zip and unzip it and go inside the folder and copy pickrr folder and paste it your magento server  app->code->local
2: Now inside your magento server go to app->etc->modules and create a file 
```
Pickrr_Magento1.xml 
```
and paste the code

```
<?xml version="1.0" encoding="UTF-8"?>
<config>
    <modules>
        <Pickrr_Magento1>

            <active>true</active>
            <codePool>local</codePool>

        </Pickrr_Magento1>
    </modules>
</config>
```
3: Now open your admin panel and go to system->configuration and find the pickrr extension 
4: Now tick the automatic shipment enable to "yes" and fill your auth token which is provided by pickrr
5: Now in shipment detail enter your name, phone number pincode and address and leave pickup time to NULL
6: After that try placing a order and confirm it on pickkr.com
7: All done and plugin is ready to use.
