This is a sample gradle project for JPA entity class generation. The project defines a gradle task that uses hibernate tools ant task to generate java entity classes.
The project uses postgresql [Dell DVD store sample database](http://linux.dell.com/dvdstore/)

Configure database connection properties in src/main/resources/hibernate.cfg.xml

Configure schema-selection and table-filter properties in src/main/resources/hibernate.reveng.xml

run 
```bash
gradle generate
```
