# Encryption

When we want to upload a code to any server and also want to protect the username and password so that password will not go to the server and while we also want out password back when we clone it then the decryption of password will be used so, this code will help you encrypt your password and decrypt it simultaneously

For running the code provide you can provide a secretkey like i have provided hellohere in the code you can choose your own 
and that secret key will be added to your vm options.


In your application.properties file write the encrypted password using ENC(encrypted password)
While running the application put in vm options. -Djasypt.encryptor.password=yoursecretkey
