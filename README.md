# Clone - MINGW64: /e/dods/github/docs

Administrator@HPMPC-MAIN MINGW64 /e/docs/github<br/>
$ git config --global core.safecrlf false<br/>
$ git clone https://github.com/hpalman/docs.git<br/>
$ cd docs<br/>
$ mkdir spring-boot<br/>
$ echo "test" spring-boot/README.md<br/>
$ git add .<br/>
$ git commit -m "spring-boot docs directory"<br/>
$ git push -u origin main<br/>



implementation 'mysql:mysql-connector-java:8.0.30'

spring.datasource.schema2.jdbc-url=jdbc:mysql://localhost:3386/schema2
spring.datasource.schema2.username=schema2
spring.datasource.schema2.password=schema2
spring.datasource.schema2.driver-class-name=com.mysql.cj.jdbc.Driver        
