# abpmML
3 XGBoost ML models used for predicting ambulatory blood pressure status from baseline clinical parameters. Each model corresponds was built on a distinct training cohort: Glasgow, Birmingham, and Gdańsk

## Usage

The three models are saved in .json format and can be imported

```
model = xgb.XGBClassifier()
model.load_model("XGB_Cohort.json")
```

All three models have been pretrained and ready to be applied. Please refer to our publication for the input variables.
