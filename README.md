<h1 id="covid19_scenarios" align="center">
  Twitter Dashboard
</h1>

<blockquote align="center">
Web application and data visualization tool on Twitter dataset developed using Python standard library, Javascript, HTML and CSS without any framework
</blockquote>

### Run the project

* Clone this repository.
* Enter the directory where you clone it, and run the following code in the terminal (or command prompt).
```sh
docker build -t web-app .
docker run -p 8000:8000 -d --net=host web-app
```
The application is now available at : http://localhost:8000
