# Retention Modeling Script

This repository contains a Python script designed for modeling user retention using a power-law function.

## Overview

The `RetentionFunctions.ipynb` script offers functionality to:
- Input days and corresponding retention data.
- Fit a power-law model to the data.
- Forecast retention values.
- Plot actual vs. forecasted retention data.
- Calculate the Mean Absolute Difference between actual and forecasted values.

## Usage

Run the script:

Follow the on-screen prompts to input days and retention data.

## Dependencies

- pandas
- numpy
- scipy
- matplotlib

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Example usage:
if __name__ == "__main__":  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;actual_data, forecast_data = run_retention_forecast()  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;plot_forecast(actual_data, forecast_data)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;score = score_points(actual_data, forecast_data)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("Mean Absolute Difference:", score)  

Please enter the days data (separated by commas): -> 1,3,7,30  

Please enter the retention data (separated by commas): -> 35.25%,12.45%,6%,1.5%  

## Sample output:  

![image](https://github.com/a1441/RetentionCurve/assets/49153959/114fee91-5b71-4b12-be87-6c07948e219a)

Mean Absolute Difference: 0.001272312188953283
