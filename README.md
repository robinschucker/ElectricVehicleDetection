# ElectricVehicleDetection

Author: Robin Schucker
date: 05/31/16

From smart meter data (30 min interval load over 2 month) of 100+ homes, train a classifier that detects if a house owns an EV and if yes when that EV is likeley to be charging.

Input:

EV_train.csv:

    House_ID, Interval_1,Interval_2,Interval_3,Interval_4,Interval_5,...
    1234567,1.013,0.215,0.217,0.217,0.217,...
    1234568,0.22,0.22,0.215,0.215,3.612,....
  
EV_train_labels.csv:

    House_ID, Interval_1,Interval_2,Interval_3,Interval_4,Interval_5,...
    1234567,0,0,0,0,0,...
    1234568,0,0,0,0,1,...
  
In label: 1 = EV is being charged, 0 = EV is not being charged  
