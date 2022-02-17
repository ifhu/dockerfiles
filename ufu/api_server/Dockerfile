FROM openjdk:11-jre
COPY .  /springapp
WORKDIR /springapp
RUN mkdir upload
RUN echo "初始化完成,正在构建YMALL容器镜像......"
EXPOSE 8080
ENTRYPOINT ["java","-jar","app.jar"]