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
