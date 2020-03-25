# Time-Series-Analysis

## About Dataset
The data provided consists of the reading in the main meter and two sub-meters of five buildings from 01-04-2017 to 31-12-2017. The given timestamp is divided into 15-minute intervals. The dataset consists of electricity consumption of five buildings across three different meters for each timestamp. <br />
The table and graph below describes the statistical property of dataset.  
|         | Main Meter | Sub Meter 1   | Sub Meter 2 |
| ------- | --------   | ------------- | ----------  |
| Mean    | 6095.76    | 2092.88       | 776.83      |
| Std     | 3485.12    | 1135.88       | 883.49      |
| Min     | 61.63      | 0.00          | 0.00        |
| 25%     | 3455.91    | 1365.00       | 4.85        |
| 50%     | 5362.18    | 2075.67       | 621.91      |
| 75%     | 7685.40    | 2772.50       | 1365.89     |

<div align=left>
<img src="https://github.com/harsh-99/Time-Series-Analysis/blob/master/images/graph.png" width="780">
</div>
 <div align=center>
Figure 1: Graph of all 15 timeseries
</div> 
<br />
Train.csv have raw dataset in the interval of 15 minutes. In Intermediate files, the CSV files have dataset in interval of 1 hours. 

## Methods 

Three methods are implemented. 
* [Arima](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average)
* [XGBoost](https://en.wikipedia.org/wiki/XGBoost)
* [Gated Recurrent Unit](https://en.wikipedia.org/wiki/Gated_recurrent_unit) 

