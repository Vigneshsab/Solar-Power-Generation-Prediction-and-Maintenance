# Solar-Power-Generation-Prediction-and-Maintenance

![Diagram](https://github.com/Vigneshsab/Solar-Power-Generation-Prediction-and-Maintenance/blob/main/santnu_new.jpg)

This was an independent project implemented to help the world transition to a sustainable form of energy. In this project, data was gathered from the sensors in the solar plant and used to implement predictive models. The models implemented were able to predict the power generated and identify the need for maintenance in the plant. Due to the less amount of data, the model was only able to accurately predict the total yield produced by the solar plant for the next 2 days.

# Dataset Details

1) Plant Generation Data
Solar power generation data for one plant gathered at 15 minutes intervals over a 34 days period. 
COLUMNS : TIMESTAMP, PLANT_ID, SOURCE_KEY, AC_POWER, DC_POWER, DAILY_YIELD, TOTAL_YIELD

2) Plant Weather Data
Weather sensor data gathered for one solar plant every 15 minutes over a 34 days period.
COLUMNS: TIMESTAMP, PLANT_ID, SOURCE_KEY, AMBIENT_TEMPERATURE, MODULE_TEMPERATURE, IRRADIATION

# Future Work

Future work of this project is to extend the models to help the users in various other aspects. Till now, the model only predicts the power generation. 
Some other which can be solved are:
->Can we identify the need for panel cleaning/maintenance?
->Can we identify faulty or suboptimally performing equipment?

These can be done by implementing an Anomaly Detection Engine (ADE) for each parameter, with real-time alerting. This ADE can be extended by implementing a Causes & Recommendation Engine too. This Engine could be used to identify the root-cause behind each anomaly, and give recommendations to the plant user. This can be very useful to identify the need for panel cleaning/maintenance and any faults in the equipment. 
