Tools
=====

1.  Adoptium OpenJDK 11
2.  Ballerina 2201.3.0 (Swan Lake Update 3)

Proses build
============

$ bal build
Compiling source
	bpdp/hello_docker:0.1.0

Generating executable

Generating artifacts


Building the docker image

Sending build context to Docker daemon  36.19MB
Step 1/76 : FROM ballerina/jvm-runtime:1.0
 ---> 9eaa5aa5db5d
Step 2/76 : LABEL maintainer="dev@ballerina.io"
 ---> Running in 273df9862189
Removing intermediate container 273df9862189
 ---> 2f27d53527be
Step 3/76 : COPY auth-native-2.5.0.jar /home/ballerina/jars/
 ---> 3a965074e72b
Step 4/76 : COPY ballerina-auth-2.5.0.jar /home/ballerina/jars/
 ---> a280fbacc826
Step 5/76 : COPY ballerina-cache-3.3.0.jar /home/ballerina/jars/
 ---> 037ccc4a61f3
Step 6/76 : COPY ballerina-cloud-2.4.0.jar /home/ballerina/jars/
 ---> 182cf6018837
Step 7/76 : COPY ballerina-constraint-1.0.1.jar /home/ballerina/jars/
 ---> 245bb26c2b81
Step 8/76 : COPY ballerina-crypto-2.3.0.jar /home/ballerina/jars/
 ---> be4258cd3c27
Step 9/76 : COPY ballerina-file-1.5.0.jar /home/ballerina/jars/
 ---> 68eb65b2bb2e
Step 10/76 : COPY ballerina-http-2.5.1.jar /home/ballerina/jars/
 ---> 9745ddf86b41
Step 11/76 : COPY ballerina-io-1.3.1.jar /home/ballerina/jars/
 ---> 44afa1b03042
Step 12/76 : COPY ballerina-jwt-2.5.0.jar /home/ballerina/jars/
 ---> 49eecb2eb455
Step 13/76 : COPY ballerina-log-2.5.0.jar /home/ballerina/jars/
 ---> b1b7227084a1
Step 14/76 : COPY ballerina-mime-2.5.0.jar /home/ballerina/jars/
 ---> b46cdb513bfa
Step 15/76 : COPY ballerina-oauth2-2.5.0.jar /home/ballerina/jars/
 ---> bbe41f2b886e
Step 16/76 : COPY ballerina-observe-1.0.6.jar /home/ballerina/jars/
 ---> 268bfde0b605
Step 17/76 : COPY ballerina-observe.mockextension-1.0.6.jar /home/ballerina/jars/
 ---> a540c45803ed
Step 18/76 : COPY ballerina-os-1.5.0.jar /home/ballerina/jars/
 ---> 781ddb413ded
Step 19/76 : COPY ballerina-regex-1.3.2.jar /home/ballerina/jars/
 ---> b099f51e35af
Step 20/76 : COPY ballerina-rt-2201.3.0.jar /home/ballerina/jars/
 ---> 8fe512ab4fb7
Step 21/76 : COPY ballerina-task-2.3.0.jar /home/ballerina/jars/
 ---> d9f88d3d6b1c
Step 22/76 : COPY ballerina-time-2.2.3.jar /home/ballerina/jars/
 ---> 1c6249cbf9e7
Step 23/76 : COPY ballerina-url-2.2.3.jar /home/ballerina/jars/
 ---> f81243b259d3
Step 24/76 : COPY ballerinai-observe-0.0.0.jar /home/ballerina/jars/
 ---> c63ed29ebb34
Step 25/76 : COPY bcpkix-jdk15on-1.69.jar /home/ballerina/jars/
 ---> 8579c05a65ee
Step 26/76 : COPY bcprov-jdk15on-1.69.jar /home/ballerina/jars/
 ---> 40e383561fe1
Step 27/76 : COPY cache-native-3.3.0.jar /home/ballerina/jars/
 ---> 58b167ceca07
Step 28/76 : COPY commons-pool-1.5.6.wso2v1.jar /home/ballerina/jars/
 ---> d860786331c5
Step 29/76 : COPY constraint-native-1.0.1.jar /home/ballerina/jars/
 ---> e29d0e19ef88
Step 30/76 : COPY crypto-native-2.3.0.jar /home/ballerina/jars/
 ---> 2d92f1d3f647
Step 31/76 : COPY file-native-1.5.0.jar /home/ballerina/jars/
 ---> 926bbe14995d
Step 32/76 : COPY http-native-2.5.1.jar /home/ballerina/jars/
 ---> 388b76c4c437
Step 33/76 : COPY io-native-1.3.1.jar /home/ballerina/jars/
 ---> 93b5a4a493fd
Step 34/76 : COPY jakarta.activation-1.2.2.jar /home/ballerina/jars/
 ---> 09e3b7a930d5
Step 35/76 : COPY jwt-native-2.5.0.jar /home/ballerina/jars/
 ---> 7f18855b646f
Step 36/76 : COPY log-native-2.5.0.jar /home/ballerina/jars/
 ---> 450939d711fc
Step 37/76 : COPY mime-native-2.5.0.jar /home/ballerina/jars/
 ---> 74647dfe3f61
Step 38/76 : COPY mimepull-1.9.11.jar /home/ballerina/jars/
 ---> b744eaab70a7
Step 39/76 : COPY netty-buffer-4.1.77.Final.jar /home/ballerina/jars/
 ---> 3f645b5e08f2
Step 40/76 : COPY netty-codec-4.1.77.Final.jar /home/ballerina/jars/
 ---> fc34373fffb1
Step 41/76 : COPY netty-codec-http-4.1.77.Final.jar /home/ballerina/jars/
 ---> 840bac12a365
Step 42/76 : COPY netty-codec-http2-4.1.77.Final.jar /home/ballerina/jars/
 ---> 66cd0f529516
Step 43/76 : COPY netty-common-4.1.77.Final.jar /home/ballerina/jars/
 ---> f8e583c76059
Step 44/76 : COPY netty-handler-4.1.77.Final.jar /home/ballerina/jars/
 ---> 6d4d6b2ec7a5
Step 45/76 : COPY netty-handler-proxy-4.1.77.Final.jar /home/ballerina/jars/
 ---> 56703745dd99
Step 46/76 : COPY netty-resolver-4.1.77.Final.jar /home/ballerina/jars/
 ---> 6cca7bacfd4d
Step 47/76 : COPY netty-tcnative-boringssl-static-2.0.52.Final-linux-aarch_64.jar /home/ballerina/jars/
 ---> 3153d3fb58e7
Step 48/76 : COPY netty-tcnative-boringssl-static-2.0.52.Final-linux-x86_64.jar /home/ballerina/jars/
 ---> 44a8caf2c5f0
Step 49/76 : COPY netty-tcnative-boringssl-static-2.0.52.Final-osx-aarch_64.jar /home/ballerina/jars/
 ---> 89792ab1b388
Step 50/76 : COPY netty-tcnative-boringssl-static-2.0.52.Final-osx-x86_64.jar /home/ballerina/jars/
 ---> f8144305b232
Step 51/76 : COPY netty-tcnative-boringssl-static-2.0.52.Final-windows-x86_64.jar /home/ballerina/jars/
 ---> f3a5713f5173
Step 52/76 : COPY netty-tcnative-boringssl-static-2.0.52.Final.jar /home/ballerina/jars/
 ---> 22c940ce5cd7
Step 53/76 : COPY netty-tcnative-classes-2.0.52.Final.jar /home/ballerina/jars/
 ---> f2e43869402d
Step 54/76 : COPY netty-transport-4.1.77.Final.jar /home/ballerina/jars/
 ---> f04c38afecbd
Step 55/76 : COPY oauth2-native-2.5.0.jar /home/ballerina/jars/
 ---> c94af42a8abe
Step 56/76 : COPY observe-internal-native-1.0.4.jar /home/ballerina/jars/
 ---> b50118988d3f
Step 57/76 : COPY observe-native-1.0.6.jar /home/ballerina/jars/
 ---> ff591a2cd5af
Step 58/76 : COPY opentelemetry-sdk-common-1.0.0.jar /home/ballerina/jars/
 ---> bcf7f8d6646e
Step 59/76 : COPY opentelemetry-sdk-testing-1.0.0.jar /home/ballerina/jars/
 ---> 68f4ca82c9d2
Step 60/76 : COPY opentelemetry-sdk-trace-1.0.0.jar /home/ballerina/jars/
 ---> 2e2e34345ce0
Step 61/76 : COPY opentelemetry-semconv-1.0.0-alpha.jar /home/ballerina/jars/
 ---> e9563c2d5c46
Step 62/76 : COPY org.wso2.transport.local-file-system-6.0.55.jar /home/ballerina/jars/
 ---> 148bc8c0a81c
Step 63/76 : COPY os-native-1.5.0.jar /home/ballerina/jars/
 ---> 99c1f2509692
Step 64/76 : COPY os-test-utils-1.5.0.jar /home/ballerina/jars/
 ---> 846b812261bb
Step 65/76 : COPY quartz-2.3.2.jar /home/ballerina/jars/
 ---> 6bbd91b32e75
Step 66/76 : COPY task-native-2.3.0.jar /home/ballerina/jars/
 ---> c1c135a8887e
Step 67/76 : COPY testng-7.4.0.jar /home/ballerina/jars/
 ---> 809484fc66f9
Step 68/76 : COPY time-native-2.2.3.jar /home/ballerina/jars/
 ---> 37cf0363ba21
Step 69/76 : COPY url-native-2.2.3.jar /home/ballerina/jars/
 ---> b05ad41a5d6d
Step 70/76 : COPY bpdp-hello_docker-13417835923602398571-observability-symbols.jar /home/ballerina/jars/
 ---> 90cbe3f0703a
Step 71/76 : COPY bpdp-hello_docker-0.1.0.jar /home/ballerina/jars/
 ---> 2732689cdfaf
Step 72/76 : RUN addgroup troupe     && adduser -S -s /bin/bash -g 'ballerina' -G troupe -D ballerina     && apk add --update --no-cache bash     && rm -rf /var/cache/apk/*
 ---> Running in 5d8bcbe41e10
fetch https://dl-cdn.alpinelinux.org/alpine/v3.15/main/x86_64/APKINDEX.tar.gz
fetch https://dl-cdn.alpinelinux.org/alpine/v3.15/community/x86_64/APKINDEX.tar.gz
(1/4) Installing ncurses-terminfo-base (6.3_p20211120-r1)
(2/4) Installing ncurses-libs (6.3_p20211120-r1)
(3/4) Installing readline (8.1.1-r0)
(4/4) Installing bash (5.1.16-r0)
Executing bash-5.1.16-r0.post-install
Executing busybox-1.34.1-r7.trigger
OK: 33 MiB in 36 packages
Removing intermediate container 5d8bcbe41e10
 ---> c529c323bca5
Step 73/76 : WORKDIR /home/ballerina
 ---> Running in 7b8b9a72b732
Removing intermediate container 7b8b9a72b732
 ---> b0798aaf14c0
Step 74/76 : EXPOSE  9090
 ---> Running in 19f915f6460c
Removing intermediate container 19f915f6460c
 ---> 24b8895917e4
Step 75/76 : USER ballerina
 ---> Running in 162ea33d9f89
Removing intermediate container 162ea33d9f89
 ---> 307778f8a405
Step 76/76 : CMD java -Xdiag -cp "bpdp-hello_docker-0.1.0.jar:jars/*" 'bpdp/hello_docker/0/$_init'
 ---> Running in f4dd9984815a
Removing intermediate container f4dd9984815a
 ---> 74da5612dc56
Successfully built 74da5612dc56
Successfully tagged bpdp/hellobal:v0.1.0

Execute the below command to run the generated Docker image: 
	docker run -d -p 9090:9090 bpdp/hellobal:v0.1.0

	target/bin/hello_docker.jar
$ docker images
REPOSITORY              TAG       IMAGE ID       CREATED         SIZE
bpdp/hellobal           v0.1.0    74da5612dc56   5 seconds ago   195MB
ballerina/jvm-runtime   1.0       9eaa5aa5db5d   3 weeks ago     156MB
$

Menjalankan menggunakan Docker
==============================

$ docker run -d -p 9090:9090 bpdp/hellobal:v0.1.0
fa0626df0bc72f153dc458da15090ef2b67e04b3838c27c52a1633d1e8e992f0
$ 

Akses ke service yang sudah dijalankan
======================================

$ curl http://localhost:9090/helloWorld/sayHello
Hello, Docker!⏎ 
$

