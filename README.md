# spring-boot-jms-activemq
How to use ActiveMq Pub/Sub

## Install ActiveMq
* Download ActiveMq https://activemq.apache.org/components/classic/download/
* Unzip & go to ../apache-activemq-5-16.3/bin/win64, run activemq file ( in gitbash: ./activemq.bat)
* Open it with http://localhost:8161/admin
* login: *admin/admin*
## Run app
  - Run app, go to Topics (ActiveMq Dashboard) and choose **inbound.queue** 
  - Create a message test & send it : **{"name":"Foo"}** & check console.
