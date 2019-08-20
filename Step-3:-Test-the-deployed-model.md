You can test the deployed model from the deployment details page:

* On the **Test** tab of the deployment details page, enter the following test data.

```Json
{"input_data":[{ "fields": ["GENDER","AGE","MARITAL_STATUS","PROFESSION",
"PRODUCT_LINE","PURCHASE_AMOUNT"], "values": [["M",27,"Single", "Professional",
"Camping Equipment",144.78]] }]}
```

Note that the test data replicates the data fields for the model with the exception of the prediction field.

* Click **Predict** to predict whether a customer with the entered attributes is likely to buy a tent. The resulting prediction indicates that a customer with the attributes entered has a very high probability of purchasing a tent.

![Tent model prediction](https://github.com/IraAngeles-IBM/WatsonAutoAi/blob/master/Predictor_test.png)