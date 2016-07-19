# pickrr-magento
pickrr magento plugin for order placing


###Installation Instructions:
1. Download the zip and unzip it and go inside the folder and copy pickrr folder to your magento server  app->code->local
2. Now got to app->etc->modules and create a file 
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

