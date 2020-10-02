# kafka-java-app-group-4

## Team Lead

Name: Bharat Reddy

GitHub profile: [bharat-reddy-male](https://github.com/bharat-reddy-male)

Step-1 : To start the zookeeper service  run the command below from the kafka folder:

``` .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties```

Step-2 : To start the kafka service  run the command below from the kafka folder: 

``` .\bin\windows\kafka-server-start.bat .\config\server.properties```

Step-3 : Create you application code similar to the code available at 

``` src\main\java\edu\nwmissouri\bigdatadevelopersg4```

Step-4 : Create a jar file using mvn from the root folder of the java application

``` mvn clean compile assembly:single```


Step-5 : Run the consumer from the root folder of the application using below command where topic is topic name of your choice and group is the group name of your choice.

```java -cp .\target\kafka-java-app-group-4-1.0-SNAPSHOT-jar-with-dependencies.jar com.edu.nwmissouri.bigdatadevelopersg4.Consumer topic group ```

Step-6 : Similarly start the consumer: 

```java -cp .\target\kafka-java-app-group-4-1.0-SNAPSHOT-jar-with-dependencies.jar com.edu.nwmissouri.bigdatadevelopersg4.CustomProducerBharat topic```

The producer should be able to send messages to the consumer now.

--
--
--
--
--
--
--
--
--
## Bhavya Deepthi

GitHub profile: [Bhavya](https://github.com/Bhavya-123)

--
--
--
--
--
--
--
--
--
--
--
## Chinmayi

GitHub profile:[Chinmayi](https://github.com/Chinmayi98)

--
--
--
--
--
--
--
--
--
--
--
--
## Chetan 

GitHub profile:[Chetan](https://github.com/chetankudaravalli16)

--
--
--
--
--
--
--
--
--
--
--
--

## Manisha

GitHub profile:[Manisha](https://github.com/Manisha-Mengani)

--
--
--
--
--
--
--
--
--
--






