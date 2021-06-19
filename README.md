For Mac (follow this URL: https://coralogix.com/blog/how-to-install-and-configure-jenkins-on-the-mac-os/):

To install Jenkins on Mac<br>
```brew install jenkins-lts```

To start jenkins server:<br>
```brew services start jenkins-lts``` <br>
To stop the jenkins server:<br>
```brew services stop jenkins-lts``` <br>
Or, if you don't want/need a background service you can just run:<br>
```jenkins-lts```<br>

Open the following URL after Jenkins server startup<br>
```http://localhost:8080/```<br>
Enter the password from the mentioned path and click continue<br>
```cat given_path``` (in the command line to get the password) <br>




