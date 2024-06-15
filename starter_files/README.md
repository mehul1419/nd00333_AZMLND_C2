<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/d63606f5-c175-4550-ac92-30c0c56f9f85">Machine learning with Azure - BankMarketing.

In this project of of the course "Machine Learning Engineer with Microsoft Azure", we leverage Microsoft Azure Machine Learning Studio to create a model based on a dataset, deploy it to a web service, consume the endpoints to get the results back and also automated the flow using pipelines.

## Architectural Diagram
![image](https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/15b8dc0d-1373-4e44-a4b9-c34b19dfa1fc)


## Key Steps
1. Create a dataset asset in Azure ML:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/6524bc31-4787-4b30-b5f7-c10717152971">

2. Run an Auto ML experiment in the cloud:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/062428cc-f307-4998-889b-9d079b568072">

3. Completed status of Auto ML experiment:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/e50c2679-8b8f-410e-93f2-a915cb4be892">

4. See the best model given my AutoML
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/f23882af-68a3-40d2-901c-a666f076b264">

5. See the parameters of the best Model - VotingEnsemble.
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/e303d80c-1273-45c5-9396-e2f6c79e30ee">

6. Deploy the model to give an endpoint so that we can consume(Currently - application insights enabled is false)
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/3dc1868b-6d01-4b0b-8424-0353cf6bf011">

7. Use python script to enable application insights and see the logs:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/94724c71-8c99-496a-ba48-a0e0fe57fa2c">

8. Now after running the above script - application insights enabled becomes true:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/34ee4808-8443-4bc0-9442-a3b0691844d6">

9. See logs:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/48b81d3d-0f6d-4853-a588-b88c61cbea03">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/c1d7c471-59a0-4fb5-a4c0-4090878d5027">

10. Deploy swagger to local machine using docker image and use swagger.json file from our model deployment to see documentation about endpoints:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/d3c13f5e-fd35-4e99-8698-a95239d62674">

11. Consume the endpoint giving 2 inputs and see the result using python script:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/ff5c30b5-8a6c-43a3-a7dc-2e14b2cc70d7">

12. Optional step: Benchmark the endpoint with Apache Benchmarking
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/0d14f37d-130e-44c6-bab5-4ba8466e992a">

13. Pipeline creation and running:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/b8b6ccb6-5e08-4aa8-a4ec-fe9111a31829">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/02da33b7-9004-455c-b0f4-402508dfa3a1">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/8af83920-372e-45f7-81e5-057b08c472aa">

14. Pipeline rest endpoint:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/b191f1ff-d153-4c7a-a8c1-ee146854cd6c">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/f7f302ca-f561-4a47-a845-feb8820bbe14">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/bffb1e3a-cf97-4ed0-b108-19f1d4ce15f2">

15. Above step created by notebook:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/47556dfe-b114-4dd3-a044-f4f5fd1bbd1b">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/16efa05e-f419-4e7f-a2a4-ebbea4000ade">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/1b178220-6952-4746-b929-564a46b6901d">

16. Deleting computes after all steps completed:
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/9df6d541-42c9-4001-82d4-bf07925d8471">
<img width="452" alt="image" src="https://github.com/mehul1419/nd00333_AZMLND_C2/assets/51814570/2424bfe2-5229-438d-89d0-69c3d0aeee05">


## Screen Recording
https://drive.google.com/file/d/1ylcVU2bN-xUopNsu6Kd5KHuY2wJc5Uvf/view?usp=drive_link
