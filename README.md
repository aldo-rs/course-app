# CourseApp V2

Improve CourseApp version by adding CI integration

```shell
docker image build -t tomcat-course-app -f docker/Dockerfile .
docker container run -it --name course-app --publish 8081:8080 tomcat-course-app
```

