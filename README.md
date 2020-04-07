# Jamie-Alexander-Holim
Creating app... done, floating-ocean-97551
https://jamiealexander09.herokuapp.com/ | https://git.heroku.com/jamiealexander09.git
remote: Compressing source files... done.
remote: Building source:
remote:
remote: -----> Java app detected
remote: -----> Installing JDK 1.8... done
remote: -----> Executing: ./mvnw -DskipTests clean dependency:list install
...
remote:        [INFO] ------------------------------------------------------------------------
remote:        [INFO] BUILD SUCCESS
remote:        [INFO] ------------------------------------------------------------------------
remote:        [INFO] Total time:  15.870 s
remote:        [INFO] Finished at: 2019-07-08T22:42:35Z
remote:        [INFO] ------------------------------------------------------------------------
remote: -----> Discovering process types
remote:        Procfile declares types -> web
remote:
remote: -----> Compressing...
remote:        Done: 70M
remote: -----> Launching...
remote:        Released v5
remote:        https://jamiealexander09.herokuapp.com/ deployed to Heroku
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/jamiealexander09.git
 * [new branch]      master -> master
ps:scale web=1
open
2019-07-08T22:43:04.169634+00:00 app[web.1]: 2019-07-08 22:43:04.169  INFO 4 --- [io-28914-exec-3] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring DispatcherServlet 'dispatcherServlet'
2019-07-08T22:43:04.169767+00:00 app[web.1]: 2019-07-08 22:43:04.169  INFO 4 --- [io-28914-exec-3] o.s.web.servlet.DispatcherServlet        : Initializing Servlet 'dispatcherServlet'
2019-07-08T22:43:04.180097+00:00 app[web.1]: 2019-07-08 22:43:04.179  INFO 4 --- [io-28914-exec-3] o.s.web.servlet.DispatcherServlet        : Completed initialization in 10 ms
java -jar target/java-getting-started-1.0.jar
Free dyno hours quota remaining this month: 987h 28m (98%)
Free dyno usage for this app: 0h 0m (0%)
For more information on dyno sleeping and how to upgrade, see:
https://devcenter.heroku.com/articles/dyno-sleeping
=== web (Free): java -jar target/java-getting-started-1.0.jar (1)
web.1: up 2019/07/08 17:42:57 -0500 (~ 7s ago)
ps:scale web=0
open
<dependencies>
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-actuator</artifactId>
    </dependency>
    <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
...
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 14.266 s
[INFO] Finished at: 2019-07-08T17:43:29-05:00
[INFO] Final Memory: 37M/331M
[INFO] ------------------------------------------------------------------------
<plugin>
  <artifactId>maven-assembly-plugin</artifactId>
  <version>3.0.0</version>
  <configuration>
    <descriptorRefs>
      <descriptorRef>jar-with-dependencies</descriptorRef>
    </descriptorRefs>
    <finalName>I love you</finalName>
  </configuration>
</plugin>
...
7:06:33 PM web.1 |  2019-04-04 19:06:33.539  INFO 97226 --- [           main] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
7:06:33 PM web.1 |  2019-04-04 19:06:33.783  INFO 97226 --- [           main] o.s.b.a.w.s.WelcomePageHandlerMapping    : Adding welcome page template: index
7:06:33 PM web.1 |  2019-04-04 19:06:33.949  INFO 97226 --- [           main] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 2 endpoint(s) beneath base path '/actuator'
7:06:34 PM web.1 |  2019-04-04 19:06:34.047  INFO 97226 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 5000 (http) with context path ''
<dependency>
  <groupId>org.jscience</groupId>
  <artifactId>jscience</artifactId>
  <version>4.3.1</version>
</dependency>
import static javax.measure.unit.SI.KILOGRAM;
import javax.measure.quantity.Mass;
import org.jscience.physics.model.RelativisticModel;
import org.jscience.physics.amount.Amount;
@RequestMapping("/hello")
String hello(Map<String, Object> model) {
    RelativisticModel.select();
    Amount<Mass> m = Amount.valueOf("12 GeV").to(KILOGRAM);
    model.put("science", "E=mc^2: 12 GeV = " + m.toString());
    return "hello";
}
<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org" th:replace="~{fragments/layout :: layout (~{::body},'hello')}">
<body>
  <div class="container">
    <p th:text="${science}"/>
  </div>
</body>
</html>
