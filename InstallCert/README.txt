1.) Create installcert.bat file with:
	java -Djsse.enableSNIExtension=false -jar installcert.jar nexus.devnet.local -force
	
2.) Put JAR and .bat script in folder.

3.) Run bat file.

4.) Copy generated cert to Java security folder.