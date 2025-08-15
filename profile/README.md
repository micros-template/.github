# Microservices self-made Template

This organization host microservices self-made template with addition feature of basic authentication.
If you want to copy or use this as a template, make sure you change the modules and dependency using your own path.
The order of change to make it smooth to refactor is:

1. [Event Protobuf Definition](https://github.com/micros-template/proto-event)
2. [File Protobuf Definition](https://github.com/micros-template/proto-file)
3. [User Protobuf Definition](https://github.com/micros-template/proto-user)
4. [Log Service](https://github.com/micros-template/log-service)
5. [Sharedlib](https://github.com/micros-template/sharedlib)
6. [Event Bus Client](https://github.com/micros-template/event-bus-client)
7. [Notification Service](https://github.com/micros-template/notification-service)
8. [File Service](https://github.com/micros-template/file-service)
9. [User Service](https://github.com/micros-template/user-service)
10. [Auth Service](https://github.com/micros-template/auth-service)

For Development purpose, you can use script dev-start and dev-stop in the [Deployment Repository](https://github.com/micros-template/deployment). For production. all of the repos are still not refactored to use public registry and use github action. All of the repo's soon will use public resource and will be developed later.