# Time Series Analysis

## Dataset Description

The dataset at hand comprises information on the consumption of an electrical blower machine, recorded in time slots of approximately 10-15 minutes. This data has been collected with the assistance of an Internet of Things (IoT) device. The energy consumption has been calculated as the difference between the current and previous timestamps. If the energy consumption is null or less than 0.5, it indicates that the machine was off during the corresponding time slot. The time series consumption is stationary over time, measured in kilowatt-hours (KWH), and the blower motor has a fixed capacity.


## Prediction for the next few hours

Performed using ARIMA Model after decomposition

![image](https://user-images.githubusercontent.com/100481554/232286924-4890260f-39d1-481b-a943-bf420a438605.png)
