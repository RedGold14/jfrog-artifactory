# JFrog Artifactory 

- Windows installation
- Docker installation
- Customize configuration 
- JFrog CLI
- Users and groups

---

Minimum System Requirements: **4 CPU**, **4 GB** Memory.<br />
External Ports: **8081**, **8082**.

---

Default username for the build-in administrator user: *admin*<br />
Default password for the build-in administrator user: *password*

---

Check service binding:
>ss -tunelp | grep 8081<br />
>ss -tunelp | grep 8082

---

### File structure:
/backup<br />
/bootstrap<br />
/data<br />
/etc<br />
/log<br />
/work<br />

---

**Welcome screen:**<br />
![alt text](images/artifactory-setup-1.jpg)
**Reset admin password:**<br />
![alt text](images/artifactory-setup-2.jpg)
![alt text](images/artifactory-setup-3.jpg)
![alt text](images/artifactory-setup-4.jpg)
**Set base URL:**<br />
![alt text](images/artifactory-setup-5.jpg)
**Configure default proxy:**<br />
![alt text](images/artifactory-setup-6.jpg)
**Create repositories:**<br />
![alt text](images/artifactory-setup-7.jpg)
**Finish:**<br />
![alt text](images/artifactory-setup-8.jpg)
**JFrog Platform welcome screen:**<br />
![alt text](images/artifactory-setup-9.jpg)
**HTTP Status 404 - Not Found:**<br />
![alt text](images/errors/http_status_404_not_found.jpg)
