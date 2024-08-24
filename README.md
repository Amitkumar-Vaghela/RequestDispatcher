## RequestDispatcher

## Project Structure:
src/main/java: Java source code
src/main/webapp: Web application resources (HTML, CSS, JS, etc.)
pom.xml: Maven project file

## Dependencies:
javax.servlet-api: for Servlet API
jakarta.servlet-api: for Jakarta Servlet API (if using Jakarta EE)

## Run the Application:
Right-click on the project in Eclipse and select "Run As" > "Maven build..."
In the "Goals" field, enter clean package
Click "Run" to build the WAR file
Deploy the WAR file to a servlet container (e.g., Apache Tomcat)
Access the servlet using a web browser: http://localhost:8080/MyServlet
