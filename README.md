# Music-Recommender-System-using-ML-Algorithm-with-Apache-Spark

## Project Summary.

1. **프로젝트 개요**
    - 설명 : [Last.fm](http://Last.fm) 에서 제공하는 Playlist 데이터를 활용하여, 사용자별 음악 추천시스템 구축
    - 소스코드 : https://github.com/yooinsun/Music-Recommender-System-using-ML-Algorithm-with-Apache-Spark 

      ![System Architecture.png](System%20Architecture.png)


2. **진행한 작업**
   - Hadoop eco system (HDFS, Yarn, PySpark) 활용하여,  ETL 진행
   - Cassandra, Redis 와 연동하여 데이터 저장 
   - SparkML 의 ALS 알고리즘 학습 
   - AWS S3, AWS Glue 를 사용하여 Batch 스케줄링 및 모니터링

3. **사용기술**
    - Hadoop HDFS, YARN, PySpark, SparkML 
    - SQL, Python 
    - Cassandra, Redis 
    - Jupyter, Zeppelin
    - AWS Glue, AWS S3