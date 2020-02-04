# Help Site

https://blog.codingmilitia.com/2018/01/31/quick-intro-to-docker-and-docker-compose-angular-aspnetcore-postgres-app

# AngularAspNetCoreDockerSample
A very simple sample using Angular, ASP.NET Core and Docker.

The application does basically nothing but increment some counters. The goal was just to get Docker Compose to run an application composed by a frontend Angular app, a backend ASP.NET WebApi using a PostgreSQL database. To route the incoming requests there's an HAProxy.

# Running
`docker-compose up -d` on the repository root will build the container images and then run all the containers in daemon mode (as instructed by the `-d` argument). 
