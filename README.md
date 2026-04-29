I had to make this for my big data class during my studies. <br>
The goal here is to do predefined analyses on a US Domestic Flights Delay Prediction (2013 - 2018) dataset from kaggle:
https://www.kaggle.com/datasets/gabrielluizone/us-domestic-flights-delay-prediction-2013-2018 <br>
Since it was for class, jupyter markdown cells had their contents written in polish. <br> <br>

### Dependencies:
* pip install pandas matplotlib seaborn

Main analyses:
* verifying data integrity
* calculating mean delay for each airline (for this one I only included delays >0)
* calculating delayed flights % for each airline (and rank them)
* finding airports generating the largest delays
* finding mean delay for each origin airport (and find 10 worst)
* comparing delays between months/quarters
* studying correlation between distance and delays (really close to 0 pearson~~-0.01)
* calculating cancelled and diverted flights % (0 because of the dataset not containing such)
* finding relationships between DayOfWeek/Month and Cancelling/Diverting flights

### Notes: 
Certified classic: we were forced to specifically use a faulty dataset without any cancelled or diverted flights, as well as there were only 9 airlines (meanwhile requiring us to provide 10 worst ones).

I'm not using notes to criticise the education system, rather want to show my understanding of data verification, cleanup and thought process backing my steps.
