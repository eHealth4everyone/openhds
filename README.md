# openhds
## Openhds with a windows bias

Below are release files friendly to winwods users

[Download war](https://github.com/eHealth4everyone/openhds/raw/master/war/openhds.war)
File is at https://github.com/eHealth4everyone/openhds/raw/master/war/openhds.war

Important notes:
Username/password is data/data
Points to mysql at localhost:3306

Default database.properties:
dbDriver=com.mysql.jdbc.Driver
hibernateExport=update
dbUser=data
hibernateShowSql=false
dbUrl=jdbc:mysql://localhost:3306/openhds?createDatabaseIfNotExist=true&amp;useEncoding=true&amp;characterEncoding=UTF-8
dbType=MYSQL
dbPass=data
hibernateDialect=org.hibernate.dialect.MySQL5InnoDBDialect


