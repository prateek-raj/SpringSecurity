# SpringSecurity
Spring Security provides ways to perform authentication and authorization in a web application. We can use spring security in any servlet based web application.
<a href="https://rprateek11.wixsite.com/prateekraj/single-post/Spring-Security">To know more</a>

# Topics
We will discuss many topics such as:
1. Benefits of Spring Security.
2. Spring Security Demonstration.
3. Understanding Security-context.xml 

# Benefits of Spring Security 
Spring Security expand the capablities of securities in Java EE applications.
Benefits are as follows:
1. Portablitiy.
2. Session Maintenance.
3. CSRF Token Authentication.

<a href="https://rprateek11.wixsite.com/prateekraj/single-post/Spring-Security">many more</a>


# Spring Security Demonstration

1. It all start with web.xml file. Within the xml file we specify the simple servlet filter. Servlet filter is provied by spring. It's the delegating filter proxy.
2. Setup the filter mapping to setup the every request coming into the application by using <b> "url-mapping"</b> tag.
3. How does it determine the logic for the process for security? Answer is to specify the <b>security-context</b>.
4. <b>Acess Control Row :</b> <br>
   1. <b>Http tag : </b> http tag says we are going to protect some other request coming into the web application.<br>
   2. <b>Intercept-url tag : </b> It consist of <b>pattern</b> which says that, for which tag you want to restrict the access & access consist of the ROLE_ to which the access is issued.
5. <b>Authentication Control Row :</b> <br>
    <b>Authentication-manager</b> is used to authenticate the access of the user to valid user acess.<br>
    <b>User-service</b> provides the number of user with the name, password and authorities. Authorities can consist multiple paramaeters separated by <b>commas</b> example <b>authorites ="ROKE_ADMIN,ROLE_USER"</b>.
