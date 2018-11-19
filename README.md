# Wildfly Application Server package for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wildfly.svg)](https://ci-apps.yunohost.org/jenkins/job/wildfly%20%28Community%29/lastBuild/consoleFull)  

[![Install wildfly with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=wildfly)<br><br>
=======
**Shipped Version: 14.0.1.Final**

**Requirement: YunoHost 3.0.0**

## WildFly

* Fast Startup
* Small Footprint
* Modular Design
* Unified Configuration and Management

And of course Java EE!

## Building
-------------------

Prerequisites:

* JDK 8 or newer - check `java -version`
* Maven 3.3.1 or newer - check `mvn -v`
* On *nix systems, make sure that the maximum number of open files for the user running the build is at least 4096
  (check `ulimit -n`) or more, depending on what other i/o intensive processes the user is running.
  
## Installation

### Guidelines 

 1. Require dedicated domain like **wildfly.domain.tld**. Domain like domain.tld/wildfly will not work.
 1. Will run in **standalone mode**.
 1. No LDAP support.
 
 ### Install

 1. **App can be installed by YunoHost admin interface or by the following command:**

         $ sudo yunohost app install https://github.com/YunoHost-Apps/wildfly_ynh
 
 1. After installation user should be created by running **./add-user.sh** from the **bin** directory of the app.

 
 ### To-do:
   - [x] Install
   - [x] Remove
   - [X] Upgrade (not fully functional)
   - [X] Backup (need testing)
   - [X] Restore (need testing)
   - [X] Multi-instance (need testing)
   
