# lombok-xjb-sample

Generates schema objects, with lombok annotations, using JAXB binding.

Run
```bash
mvn clean compile
```

Then look into the **target** directory for compiled classes and generated soources.

Make sure to update the XPath within the bindings file, according to your schema format.

Also, within the POM, make sure to leave the 
```xml
<schemaLanguage>WSDL</schemaLanguage>
```
configuration section as is, if it is a SOAP WSDL file. 
