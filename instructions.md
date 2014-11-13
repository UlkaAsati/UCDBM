Get started with UA-java1
-----------------------------------
Welcome to Java Web Starter application!

This sample application demonstrates how to write a Java Web application (powered by WebSphere Liberty) and deploy it on Bluemix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/BuildingWeb.html#install_cf).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/cea45b64-a981-4847-a1d3-f86a3d9a5b8a/starter-download).
3. Extract the package and `cd` to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u ulka_asati@persistent.co.in
		cf target -o ulka_asati@persistent.co.in -s dev
				
6. Compile the Java code and generate the war package using ant.
7. Deploy your app:

		cf push UA-java1 -p webStarterApp.war

8. Access your app: [http://UA-java1.mybluemix.net](http://UA-java1.mybluemix.net)
