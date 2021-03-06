# Data Engineering with cloud services

## Course decription
Existing "ERP-SAP" courses ended last year, and this is a course for Big Data Engineering. Do NOT confuse, please

This course covers Big Data Engineering, which handles large-scale data in the cloud.  Today's many information systems collect large-scale log data from operating the machines, and the organizations use them to make data-driven decisions. The amount of data generated per day is difficult to handle with one computer.  To end this, The techniques that process large volumes of data by combining multiple machines, called big data engineering, are actively utilized. In particular, as cloud services have been being activated, much data is stored in cloud services, and big data processing technologies are used to support the extraction, transformation, and loading (ETL) of required data from the storage.

In this course,  you learn the various concepts and techniques needed for big data engineering. Typical examples are data storage platforms such as Hadoop and Spark, large data query tools such as Apache BEAM and Google Big Query, and data extraction tools such as Flume and Kafka. We also learn machine learning algorithms such as recommendation and clustering and try to implement a big data system including data pipeline for data extraction.

You need to understand Python and SQL as a preliminary step for learning this lesson. An understanding of the elementary linear algebra and probability is helpful to you. It will be a highly challenging course.

본 강좌는 대용량 데이터를 클라우드 상에서 처리하는 빅 데이터 엔지니어링에 대해서 다룬다. 오늘날 많은 정보시스템은 대용량 로그 데이터를 수집하여, 데이터 기반의 의사결정에 사용하고 있다. 하루에 생성되는 데이터 양은 한 대의 머신으로 처리하기 어려운 수준이다. 이를 위해 여러 대의 머신들을 엮어 대용량 데이터를 처리하는 빅 데이터 엔지니어링 기술들이 활발히 사용되고 있다. 특히 클라우드 서비스가 활성화되면서 많은 데이터들을 대용량 데이터를 클라우드 서비스에 저장하고, 빅 데이터 처리 기술들을 활용하여 필요한 데이터의 ETL(Extraction, Transoformation, Loading) 과정을 지원하고 있다.

본 강좌에서는 빅 데이터 엔지니어링에서 필요한 다양한 개념과 기술들을 습득한다. 대표적으로 하둡, 스파크와 같은 데이터 저장 플랫폼과 아파치 BEAM, 구글 빅쿼리 등의 대용량 데이터 쿼리 도구, Flume, Kafka와 같은 데이터 추출 도구들을 학습한다. 또한 추천, 클러스터링 등 대용량 데이터를 활용한 머신 러닝 프로그램을 습득하고, 파이프라인을 포함한 실제 구현을 시도한다.

본 강좌의 학습 위한 선행 과정으로 파이썬과 SQL에 대한 이해가 필요하다. 또한 기본적인 선형대수나 확률에 대한 이해가 있으면 도움이 될 것이다. 상당히 난이도가 있는 과정으로 쉽지않은 도전이 될 것이다.


## Syllabus
### ch0
- Course introduction: [slide](https://1drv.ms/b/s!ApZ4mg7k2qYhgcAP7sZ0e8ckCsRgoQ)

### ch1 - Business Intelligence Overview
- Business Inteligence: [slide](https://1drv.ms/b/s!ApZ4mg7k2qYhgcARkgr5FEuvLQP5dg)
- Components of BI: [slide](https://1drv.ms/b/s!ApZ4mg7k2qYhgcASxbjeLI4B5dG9sw)

### ch2 - AWS - Cloud Service
- AWS overview: [slide](https://1drv.ms/b/s!ApZ4mg7k2qYhgcAQS-RBKzr_Ejje0g)
- [AWS EC2 생성 및 접속](https://github.com/higee/elastic/wiki/AWS-EC2-Instance-%EC%83%9D%EC%84%B1-%EB%B0%8F-%EC%A0%91%EC%86%8D)
- DevOps & AWS : [video](https://vimeo.com/291064949/28834a9f91)
  - DevOps: [Ndc17 DevOps? DevOps개발자?](https://www.slideshare.net/taehyunkim73700/ndc17-devops-devops-6)
  - AWS S3: [AWS 시작하기 및 Amazon S3 살펴보기](https://www.slideshare.net/awskorea/aws-getting-started-and-amazon-s3)
  - AWS boto3 Enviroment Setup : [doc](document/aws_cli/1_aws_cli_boto3.md)
  - s3 : [video](https://vimeo.com/293270093/2415b21aa5), [doc](document/aws_cli/2_aws_cli_basics.md), [code](https://github.com/TEAMLAB-Lecture/big-data-101/tree/master/code/1_aws_cli_basics/s3)
  - vpc : [video](https://vimeo.com/293267772/bd6a419b8a), [doc](document/aws_cli/2_aws_cli_basics.md), [code](https://github.com/TEAMLAB-Lecture/big-data-101/tree/master/code/1_aws_cli_basics/vpc)
  - ec2 : [video](https://vimeo.com/293271553/29720abad5), [doc](document/aws_cli/2_aws_cli_basics.md), [code](https://github.com/TEAMLAB-Lecture/big-data-101/tree/master/code/1_aws_cli_basics/ec2)
  - Lab Assignment - [handling your VPCs](https://github.com/TEAMLAB-Lecture/big-data-101/blob/master/assignment/handling_your_vpcs.md)
- Web application
  - Web application configurations : [video](https://vimeo.com/293730019/aafcae3df6), [doc](./document/1_configure_web.md)
  - AMI : [video](https://vimeo.com/293811336/9ee658e265), [doc](), [code](https://github.com/TEAMLAB-Lecture/big-data-101/tree/master/code/2_web_application)
  - crontab : [video](https://vimeo.com/293814949/9b59298a31), [doc](https://github.com/TEAMLAB-Lecture/big-data-101/blob/master/document/web_basics/3_crontab_basics.md)
  - Lab Assignment - [AMI with crontab](./assignment/ami_with_crontab.md)


### ch3 - Hadoop
  - Cloudera - [Video](https://vimeo.com/299263569/8af7bce577)


## Projects
#### 2018 Members
- https://github.com/Kangchangwoo1/2018-2nd-semester-gachon-ERPSAP-teamproject-repo
- https://github.com/HyunaShin/bigdata_engineering_inflearn_project
- https://github.com/JeongChanwoo/REYNOLDS_system_project
-
## References
https://www.slideshare.net/JaehoonJung/sk-ict-tech-summit-2017-sk-planet?ref=https://readme.skplanet.com/?p=13903
