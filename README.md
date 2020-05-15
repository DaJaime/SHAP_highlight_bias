# Use of SHAP to highlight discriminatory bias
The model predict a student's average based on various factors. We use a random forest to make a prediction.

See the train dataset here : http://roycekimmons.com/tools/generated_data/exams

Following this tutorial : https://towardsdatascience.com/explain-your-model-with-the-shap-values-bc36aac4de3d

After inspecting our model, we could see that he judged mens and a certain ethnic group to be less successful. If we use this model in university recruitment, he will had a discriminating impact on students applying.

## Features impact
![shapPlotDetail](https://user-images.githubusercontent.com/33934807/82074163-a300d880-96da-11ea-9745-f7a3fc66cdbb.png)
