# IoTTopic
Replication package for topic analysis study of SO IoT posts

In text mining, we often used collections of documents in form of blog posts, news articles and comments that are further divided into natural groups. This will help to understand the content of each document separately. Topic modelling is a sub technique of unsupervised classification of textual documents that help to identify groups of similar behaviour.
Internet of Things (IoT) is regarded as a remarkable development of the modern information technology. There is abundant digital products data on the IoT, linking with multiple types of objects/entities. As the use of IoT product market is growing in large number, there is a need to address the most common issues faced by the users while using technologies associated to IoT. In this study, we download a large number of Stack Overflow posts that contain discussions about various IoT technologies. We apply topic modeling on the textual contents of the posts. We label the topics and categorize the topics into hierarchies. We analyse the popularity and difficulty of the topics. 
Our study offers several findings based on the four research questions as discussed below;

**StackOverflow IoT dataset**: collected from IoT related 53K SO posts. List of all tags used in the IoT data collection:
The Stack Overflow September 2019 data dump is used. The dump can be downlaoded from [archive.org](https://archive.org/details/stackexchange)

The final list of 78 IoT tags that we used to collect our IoT posts from Stack Overflow as as follows.

- ***arduino***: arduino, arduino-c++, arduino-due, arduino-esp8266, arduino-every, arduino-ide, arduino-mkr1000, arduino-ultra-sonic, arduino-uno, arduino-uno-wifi, arduino-yun, platformio
- ***iot***: audiotoolbox, audiotrack, aws-iot, aws-iot-analytics, azure-iot-central, azure-iot-edge, azure-iot-hub, azure-iot-hub-device-management, azure-iot-sdk, azure iot-suite, bosch-iot-suite, eclipse-iot, google-cloud-iot, hypriot, iot-context-mapping, iot-devkit, iot-driver-behavior, iot-for-automotive, iot-workbench, iotivity, microsoft iot-central, nb-iot, rhiot, riot, riot-games-api, riot.js, riotjs, watson-iot, windows-10-iot-core, windows-10-iot-enterprise, windows-iot-core-10, windowsiot, wso2iot, xamarin.iot
- ***raspberry-pi***: adafruit, android-things, attiny, avrdude, esp32, esp8266, firmata, gpio, hm-10, home-automation, intel-galileo, johnny-five, lora, motordriver, mpu6050, nodemc, omxplayer, raspberry-pi, raspberry-pi-zero, raspberry-pi2, raspberry-pi3, raspberry-pi4, raspbian, serial-communication, servo, sim900, teensy, wiringpi, xbee

The list of tags for each question in our dataset can be found in QuestionTags.json file.

**Replication Materials to Answer to RQs in the paper.**
IoT post metadata required in each RQ: IoTPostInformation.csv

- ***RQ1 supporting files***: TopicLabelingIoT.xlsx and TopicIdsWithDominantDocIds.pkl
- ***RQ2 supporting files***: Relative and Absolute Posts.xlsx, IoTPostInformation.csv
- ***RQ3 supporting files***: Consensus Applied sample.xlsx, Percentage of Posts.xlsx 
- ***RQ4 supporting files***: TopicLabelingIoT.xlsx and TopicIdsWithDominantDocIds.pkl, IoTPostInformation.csv, Popularity.xlsx, Difficulty.xlsx

**_Topic Absolute Impact:_** 

We compute topic popularity metric is used  to identify the topic popularity for each topic for IoT domain from corpus collected from Stackoverflow from September,2008 to August 2019. We compute the absolute impact of the topic for fourcategory (Software,Hardware,Network, Tutorial). 


**_Topic Relative Impact:_**

We  use  the  relative  impact  metric to  calculate  the  relative  impact  of  IoT  topic  for  a  specific  time. We define the relative impact metric of a topic for a month as compare to the total posts for particluar moth.

