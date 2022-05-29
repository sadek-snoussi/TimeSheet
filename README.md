# TimeSheet
Java web application

### Summary
- All java based configuration
- Login module
  - Spring security custom UserDetailsService
  - separate user roles: employee/manager
  - login, logout pages
  - registration form and validation
- Models and relationship
  - hibernate as JPA implementation
  - auto generated tables
  - relationship and cascade
- Thymeleaf template
  - reusable header fragment
  - navi bar
  - map exceptions
- Manager module
  - display all employees
  - bootstrap table
  - add new employee
    - generate random password
    - ajax call to refresh employee list
  - reset password for employees
  - disable employees
- User module
  - modify user profile
- Project module
  - create new project
  - set employees to selected project
  - multiselect plugin
- timesheet module
  - user action
    - employee submit / unsubmit
    - manager approve / disapprove
  - ajax call to reload sheet based on project and date
  - bootstrap-datepicker plugin
- *home page summary

### Frameworks & Tools
Front end
- HTML5 Thmeleaf
- Bootstrap
- Bootstrap table
- jQuery

Spring
- Spring MVC
- Spring Security
- Spring Data JPA

Logging
- slf4j
- Logback

Caching
- ehcache

Database
- MySQL

Connection Pool
- HikariCP

Testing
- Spring Test
- H2 embedded database
- Mockito

Build tool
- Gradle

Applciation server
- Embedded Tomcat

IDE
- Eclipse
- Intellij


 
