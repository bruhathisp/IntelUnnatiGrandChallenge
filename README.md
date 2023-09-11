# Contents
## Speed Analysis
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/7da7b293-c690-4e83-8fa1-0750b278dbce)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/20bd15ce-d019-4e16-9394-9d220e0026bb)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/a5c06332-9ba8-4f6c-8d8e-5ac8b0863712)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/ff94ab6c-f8e0-43b1-8ad1-2e99e9a53d85)



## Alert Analysis
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/adefd72c-6e47-49d3-bbed-9fc573fbfbe5)
## temporal Analysis
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/1966deaf-32e4-4b5e-b456-b9a77b04e1e6)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/6d28fa70-d31e-49e0-9bca-ca96bf80ddc1)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/14e397d1-c2b7-4246-b308-60ff07e613a9)









# Day vs Alert
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/eb8116ec-c774-41c3-a2cd-61030eeaa71a)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/7be847f2-8355-4143-89f0-b8d08a2161ab)

## Vehicle Analysis Low data for 1995 vehicle_id
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/14eaa2c0-3449-4f55-b6e8-f375543ce856)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/1c7fa130-69e0-4ece-93a3-ff4ee821b9d1)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/0c386732-35db-442d-adbd-d81a9c48bbc5)
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/17a32fc4-8b68-4a2d-88e9-bb8d900c07b6)

## Speed vs Alert vs Vehicle
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/5d08da07-4986-4bd3-9e88-841b47e8453d)




Stationarity:
Stationarity is a fundamental concept in time series analysis, signifying that the statistical properties of a dataset remain consistent over time. In stationary time series data, factors like mean and variance do not exhibit significant changes as time progresses.

ADF Test:
The Augmented Dickey-Fuller (ADF) test is a statistical test used to determine whether a dataset possesses a unit root, which is an indicator of non-stationarity. Here's a breakdown of how the ADF test functions:

Null Hypothesis: The ADF test initiates with a null hypothesis, suggesting that the dataset contains a unit root, making it non-stationary.

Test Statistic: It calculates a test statistic, and its significance is compared against critical values derived from statistical tables.

Interpretation: If the computed test statistic is less than the critical value, it provides evidence to reject the null hypothesis, signifying that the dataset is stationary. Conversely, if the test statistic surpasses the critical value, there is insufficient evidence to reject the null hypothesis, implying non-stationarity.

![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/23cdc770-af76-48e0-b17c-bfef98f22929)

# T-Test
![image](https://github.com/bruhathisp/IntelUnnatiGrandChallenge/assets/91585301/463b1320-5e8d-4dc1-9e40-a46b7b169213)
The ADF test for these alerts looked at how vehicles behaved when they received warnings about forward collisions. The test found that the way vehicles adjusted their speed during these alerts didn't change much over time. In other words, drivers tend to react consistently to warnings. 
In the context of the analysis you conducted, it means that regardless of the specific type of warning or alert that drivers receive while they are driving (whether it's a warning about a potential forward collision, information regarding highway maintenance, a lane departure warning, or a pedestrian collision warning), the speed at which they are driving doesn't change significantly when they receive these alerts.

In simpler terms, drivers tend to maintain a relatively consistent speed when they encounter these different types of alerts. This suggests that the alerts themselves while conveying various types of information or warnings, do not typically cause drivers to slow down or speed up significantly in response.

This information can be valuable for understanding driver behaviour and the impact of different types of alerts on their driving patterns. It may also indicate that drivers perceive these alerts as informative rather than as urgent warnings that require immediate changes in their speed.







