- Machine learning (ML) is a type of artificial intelligence where computers learn from data without explicit programming. Instead of being told exactly what to do, ML systems analyze data, identify patterns, and then make predictions or decisions based on that learning. 
- The steps to building and using a model are:

  - Define: What type of model will it be? A decision tree? Some other type of model? Some other parameters of the model type are specified too.
  - Fit: Capture patterns from provided data. This is the heart of modeling.
  - Predict: Just what it sounds like
  - Evaluate: Determine how accurate the model's predictions are.

- There are many metrics for summarizing model quality, but one is called Mean Absolute Error (also called MAE). The prediction error will be : 
  - error = actual value − predicted value
- A DecisionTreeRegressor builds a single decision tree to make predictions. This tree-like structure uses a series of "if-then" statements to arrive at a predicted outcome based on feature values.
- A RandomForestRegressor builds multiple decision trees, each trained on a random subset of the training data and features. This ensemble of trees then averages their predictions to produce the final output.
- Models can suffer from either:
  - Overfitting: capturing various patterns that won't occur in the future, leading to less accurate predictions, or
  - Underfitting: failing to capture relevant patterns, again leading to less accurate predictions.
