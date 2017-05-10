Java Enterprise project with registration / authorization and a role-based interface (USER, ADMIN).         
The administrator can create / edit / delete / users, and the user can manage his profile and data (day, food, calories)
through UI (AJAX) and REST interface with basic authorization. It is possible to filter data by date and time, while the color of the food 
table entry depends on whether it exceeds amount calories per day rate (an editable parameter in the user profile). 
The entire REST interface is covered by JUnit tests using Spring MVC Test and Spring Security Test.

User login: user@yandex.ru / password
Admin login: admin@gmail.com / admin

Stack of technologies: Spring Security, Spring MVC, Spring Data JPA, Spring Security Test, Hibernate ORM, Hibernate Validator, SLF4J, 
Json Jackson, JSP, JSTL, Apache Tomcat, WebJars, DataTables plugin, Ehcache, PostgreSQL, JUnit, Hamcrest, jQuery, jQuery notification, 
Bootstrap.
