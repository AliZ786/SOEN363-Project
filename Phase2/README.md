# SOEN 363: Project Phase 2
![image](https://user-images.githubusercontent.com/59709752/167078413-ad370904-93d1-422b-ab49-63406f79bab7.png)

## Objectives
* Appreciating the power of SQL in extracting and analyzing useful information from real datasets
* Practicing and applying the data systems concepts, mainly modeling, storing, and querying datasets on large datasets
* Appreciating the power of NoSQL in extracting and analyzing big datasets
* Providing a comparison between SQL and NoSQL systems.

**Data Systems used**:
  * **For SQL**: PostgreSQL
  * **For NOSQL**: Neo4J with Cypher

**Dataset used**: (https://www.kaggle.com/datasets/abhijitk/ghcn-daily-weather-data-by-city-20152020)
<br>
   Since the total file size was very large, we added the dataset to the following [Google Drive Link](https://drive.google.com/drive/folders/1lettO8xSJz4LAsgOh9gU81lKtx9DgJKr?usp=sharing)
   
![image](https://user-images.githubusercontent.com/59709752/167081830-675532f6-b7d0-4ebb-859a-526b8b1d235c.png)

![image](https://user-images.githubusercontent.com/59709752/167082016-59888b66-3f9c-41da-8b67-cb4fd04dcbaf.png)

## SQL (PostgreSQL)

### ER Diagram
![image](https://user-images.githubusercontent.com/59709752/167082510-7b21ed52-94cf-4e47-87cb-c7b72cab941a.png)

### Schema
![image](https://user-images.githubusercontent.com/59709752/167082684-75c34e7e-08e2-407c-a6e9-4b33fa6fbee7.png)


## NoSQL (Neo4J)

### Data Model

![image](https://user-images.githubusercontent.com/59709752/167082873-39809312-9348-4ddc-bc41-e8f0d7f04d70.png)

### Schema

![image](https://user-images.githubusercontent.com/59709752/167083182-991a3eae-6946-473e-af4d-89807a7a34d2.png)

## Queries
For the project, we had to demonstrate a total of 8 queries, 4 in SQL and 4 in NoSQL. The first 3 are shared statements for both systems. 
However, we had to change the last one since the execution time become longer, hence the last queries are different for both systems.

![image](https://user-images.githubusercontent.com/59709752/167083355-f3bf57d6-9465-4568-8f12-626f73c0de94.png)

![image](https://user-images.githubusercontent.com/59709752/167083398-d97c4f2f-abc4-4dcf-89ac-3da11f72530f.png)

![image](https://user-images.githubusercontent.com/59709752/167083433-ad34afca-5d98-4cc5-9686-3d4cfdd4974e.png)

### SQL- 4th Query

![image](https://user-images.githubusercontent.com/59709752/167084922-b9f7ebb8-5ac7-4cb7-aec3-f63c48629812.png)


### NoSQL - 4th Query

![image](https://user-images.githubusercontent.com/59709752/167085004-ca5a6d9f-e895-4496-bef4-441c23359c24.png)

To see the complete slides, including discussion about indexing, execution times, as well as the results at the end. Please look at the SOEN363_Presentation.pdf file.



