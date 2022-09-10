# spring-boot-scurity-reset-password
spring boot, JPA, MariaDB, spring security, and Oauth 2.0
<br>
Register
<br>
![image](https://user-images.githubusercontent.com/36573782/189472814-3c0138a3-a97d-492f-8b71-8137fd8aac3c.png)
<br>
Reset token(use post request) not get
<br>
![image](https://user-images.githubusercontent.com/36573782/189472768-9b2881bc-f6cd-43a9-bdfa-4ee28c0f773e.png)
<br>
Reset password
<br>
![image](https://user-images.githubusercontent.com/36573782/189472725-ea60f6d8-8636-4895-b5ad-766e3097c007.png)
<br>
Save new password
<br>
![image](https://user-images.githubusercontent.com/36573782/189472695-91f4ba67-0cdb-463c-9abe-09da115cfd5c.png)
<br>
Change password(first i register new user then try to change the password) 
<br>
![image](https://user-images.githubusercontent.com/36573782/189473329-1f335851-b2f6-4d2d-93ba-4583721d6aae.png)
<br>
![image](https://user-images.githubusercontent.com/36573782/189473367-17cde0cf-f008-4205-ba06-541deeacaeaf.png)
<br>
![image](https://user-images.githubusercontent.com/36573782/189473371-165c1c21-6963-4a62-9f04-5cc0e77752f0.png)
<br>
Now we need Login functionlity(here we use OAuth 2.0) OAuth 2.0 uses Access Token and also check the below link
<br>
https://www.baeldung.com/spring-security-oauth-auth-server
<br>
![image](https://user-images.githubusercontent.com/36573782/189482400-0a6aa986-2b9c-4416-a6a9-c52633189632.png)
<br>
https://www.oauth.com/playground/
<br>
![image](https://user-images.githubusercontent.com/36573782/189484008-8351dbf7-004d-479b-9bf7-3455a2ad8ec9.png)
<br>
Here with implementation of Oauth 2.0, i change ports of client into 8080, Oauth authorization server port is 9000, and Oauth resource server port is 8090
<br>
![image](https://user-images.githubusercontent.com/36573782/189487830-80698a55-87ad-47e1-80d7-217c5d334ce5.png)
<br>
Change the Host Entry
<br>
To make the "ProviderSettings" bean work, we need to add the below entry in the server's hostfile (/etc/hosts).
<br>
127.0.0.1 auth-server
<br>
![image](https://user-images.githubusercontent.com/36573782/189487877-7b419da3-2576-4218-96db-408925f38cb4.png)
<br>
I added the Oauth resource server port 8090
<br>
![image](https://user-images.githubusercontent.com/36573782/189489961-16e4b7c1-9597-4e28-8540-d0acbaee83d8.png)
<br>
![image](https://user-images.githubusercontent.com/36573782/189490003-8fac893a-6528-468a-ac41-51d1ea58cc79.png)
<br>
![image](https://user-images.githubusercontent.com/36573782/189490026-a103402a-ea66-4d72-9b40-7e9f16d67a81.png)
<br>
![image](https://user-images.githubusercontent.com/36573782/189490051-7a1f12c0-249c-4ff5-9a80-0be7f108037d.png)




