<h1 style="color:blue;text-align:center;" ><b>Employee Address Management</h1>

<h1 style="color:blue;";><b>DataBase </h1>
<p>Sql_Workbench<p>

<h1 style="color:blue;";><b>Data Flow </h1>
<p>Controller -- > Controller package handels all type of Api request. </p>
<p>Model --> Inside model package we store our entity as  class </p>
<p>Service--> Inside the service package,we write all type of the business logic inside Service class</p>
<p>Repo -->Inside Repo Package we have repo interface for each class that allow us to make CRUD opperation</p>
<h1 style="color:blue;";><b>Mappings used in My Project </h1>
<p>@OneToOne</p>

<h1 style="color:blue;";><b>Git Commands </h1>
$ git init
<br>
$ git status
<br>
$ git add
<br>
$ git  commit -m "nitishCommit"
<br>
$ git remote add origin https://github.com/rakesh1234-png/EcommerceApi.git
<br>
$ git push -u origin master

<br>
<h1 style="color:blue;";><b>Application Properties</h1>
spring.datasource.url=jdbc:mysql://localhost:3306/EmployeeAddress
<br>
spring.datasource.username=root
<br>
spring.datasource.password=1Ake2sh@3
<br>
spring.datasource.driverClassName=com.mysql.cj.jdbc.Driver
<br>
spring.jpa.hibernate.ddl-auto=update
<br>

spring.jpa.properties.hibernate.show_sql=true
<br>
spring.jpa.properties.hibernate.use_sql_comments=true
<br>
spring.jpa.properties.hibernate.format_sql=true
