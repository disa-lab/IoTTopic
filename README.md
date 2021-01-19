# IoTTopic
Replication package for topic analysis study of SO IoT posts

In text mining, we often used collections of documents in form of blog posts, news articles and comments that are further divided into natural groups. This will help to understand the content of each document separately. Topic modelling is a sub technique of unsupervised classification of textual documents that help to identify groups of similar behaviour.
Internet of Things (IoT) is regarded as a remarkable development of the modern information technology. There is abundant digital products data on the IoT, linking with multiple types of objects/entities. As the use of IoT product market is growing in large number, there is a need to address the most common issues faced by the users while using technologies associated to IoT. In this study, we download a large number of Stack Overflow posts that contain discussions about various IoT technologies. We apply topic modeling on the textual contents of the posts. We label the topics and categorize the topics into hierarchies. We analyse the popularity and difficulty of the topics. 
Our study offers several findings based on the four research questions as discussed below;

_Q1.What  topics  are  discussed  by  IoT  developers  in  Stack  Overflow  (SO)?_ 

_Q2.  How do the IoT topics evolve over time?_ 

_Topic Absolute Impact:_ 

We compute topic popularity metric is used  to identify the topic popularity for each topic _Zk_ within corpus _cj_ as
<a href="https://www.codecogs.com/eqnedit.php?latex=popularity&space;(z_k,c_j)&space;=&space;\frac{|{d_i}|}{|c_j|}:dominant&space;(d_i)=z_k,1<=i<=c_j" target="_blank"><img src="https://latex.codecogs.com/gif.latex?popularity&space;(z_k,c_j)&space;=&space;\frac{|{d_i}|}{|c_j|}:dominant&space;(d_i)=z_k,1<=i<=c_j" title="popularity (z_k,c_j) = \frac{|{d_i}|}{|c_j|}:dominant (d_i)=z_k,1<=i<=c_j" /></a>

We compute topic absolute impact  to analyse the temporal trends of topics, we define the absolute impact metric of a topic zk in month m as
<a 
href="https://www.codecogs.com/eqnedit.php?latex=impact_{absolute}(z_k;m)&space;=&space;\sum_{di=1}^{Dm}&space;\theta&space;(d^i;&space;z^k)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?impact_{absolute}(z_k;m)&space;=&space;\sum_{di=1}^{Dm}&space;\theta&space;(d^i;&space;z^k)" title="impact_{absolute}(z_k;m) = \sum_{di=1}^{Dm} \theta (d^i; z^k)" /></a>

_Topic Relative Impact:_

We  use  the  relative  impact  metric to  calculate  the  relative  impact  of  IoT  topic  for  a  specific  time. We define the relative impact metric of a topic zk in month mover corpus c as
<a href="https://www.codecogs.com/eqnedit.php?latex=impact_{relative}(c,zk,m)&space;=&space;\frac{1}&space;{|D(c,m)|}\sum_{di=1}^\theta&space;(di;&space;zk)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?impact_{relative}(c,zk,m)&space;=&space;\frac{1}&space;{|D(c,m)|}\sum_{di=1}^\theta&space;(di;&space;zk)" title="impact_{relative}(c,zk,m) = \frac{1} {|D(c,m)|}\sum_{di=1}^\theta (di; zk)" /></a>

_Q3.  What types of questions are asked across the IoT topics?_


_Q4.  How do the popularity and difficulty of the topics vary? _

