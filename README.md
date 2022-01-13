# Surfs_UP

#Analysis 


##The written analysis has the following:


##Overview of the statistical analysis:

W. Avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.


Deliverable 1: Determine the Summary Statistics for June 

Using Python, Pandas functions and methods, and SQLAlchemy, we filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the      temperatures for the month of June. We then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.
We wrote a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June.
We converted the June temperatures to a list.
We created a DataFrame from the list of temperatures for the month of June.
We then generated the summary statistics for the June temperatures DataFrame.

![june_df_describe](https://user-images.githubusercontent.com/93686963/149413405-5c093d66-f1af-4b36-8884-669ee0479fc4.png)

![june_df](https://user-images.githubusercontent.com/93686963/149413891-37fb3a68-b8d8-48a0-a3f5-f865a5bdc066.png)


   
Deliverable 2: Determine the Summary Statistics for December 
   

Using Python, Pandas functions and methods, and SQLAlchemy, we have filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. we then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.
We wrote a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of December.
We converted the December temperatures to a list.
We created a DataFrame from the list of temperatures for the month of December.
We then generated the summary statistics for the December temperatures DataFrame.

![dec_df describe](https://user-images.githubusercontent.com/93686963/149413668-d7365c52-340a-496a-96cf-1bd1c6c8ac6b.png)

![dec_df](https://user-images.githubusercontent.com/93686963/149413744-28619f76-bfee-4780-8012-afd4fa32e99b.png)


       
Results:

The three key different in weather between June and December are listed below:
     . The total count between June and December are different. June has total 1700
       count while December has 1517 count.

     . The temperature mean is higher in the month of June, at 74.944118 
     . The December mean temperature is 71.04 which is lower compare to June.  
       
     . Both June and December temperatures fluctuated. The difference is that in June, the 
       temperatures ranged from lowest 71 to highest at 85 degrees while in December, temperatures ranged
       from 71 to 83 degrees.


