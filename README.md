# EDA-of-911-calls-dataset
In this project, I have taken a dataset from Kaggle regarding the 911 calls and analysed the dataset for drawing various insights from the dataset.

## Importing libraries and reading the dataset
![image](https://user-images.githubusercontent.com/67495591/215993981-118f1f6a-b746-4dd6-a9b1-ed2a0fb934f1.png)

## Reviewing the dataset
![image](https://user-images.githubusercontent.com/67495591/215994411-4bf425d7-74aa-44d8-aa29-2315e9d225b1.png)
![image](https://user-images.githubusercontent.com/67495591/215994502-2b6b766b-5eaf-4611-ba0b-062645f0c9e3.png)

## Answering basic questions about the dataset
![image](https://user-images.githubusercontent.com/67495591/215995404-93cb824d-eebb-460a-a7db-5041a983d481.png)

## Creating New features in the dataset
In this section, we will create a new feature called 'Reason'. As we can see from the data that before each title, there are reasons listed such as : **EMS (Emergency Medical Services),Fire and Traffic**. We will use **.split()** method and **.apply()** method to split the title for each record.

![image](https://user-images.githubusercontent.com/67495591/215996232-a4cd5e04-7b19-44d4-9922-9b1bc567d707.png)

## Exploratory Data Analysis
First, we will count the no. of calls made for each reason using the newly created 'Reason' column.
![image](https://user-images.githubusercontent.com/67495591/215996783-254570d4-9985-4af3-8f8e-29b2b7f7129c.png)
![image](https://user-images.githubusercontent.com/67495591/215996848-731d5a8e-73dc-417b-a955-dc1f3512de41.png)

![image](https://user-images.githubusercontent.com/67495591/215997943-6462ebdb-4e58-49da-bcd1-e1430a6bd2f3.png)
![image](https://user-images.githubusercontent.com/67495591/215998150-c57de18e-a4ea-47fc-a4cf-1f8ac1316276.png)

Now, since in the above graph, we can see that there are a few months missing from the dataset. Hence, we will try to create a Count VS Month linear plot.

![image](https://user-images.githubusercontent.com/67495591/215998614-da4cd0fe-6a78-466a-b1a8-5e113a0c949d.png)

![image](https://user-images.githubusercontent.com/67495591/215999047-5bf541a8-828c-4d8e-91e8-dc33e9852563.png)

## Conclusions and Insights
Following obervations have been made after all the analysis performed on this dataset:
- The maximum number of calls made to 911 have been made for Medical emergencies.
- The top 5 townships with the most number of calls are:
    - LOWER MERION =  8443
    - ABINGTON     =  5977
    - NORRISTOWN   =  5890
    - UPPER MERION =  5227
    - CHELTENHAM   =  4575  
- The maximum number of calls have been made in the month of January.

## Sources 
- Google
- Udemy (Jose Portilla - Python for data science and Machine Learning bootcamp)
- Kaggle
