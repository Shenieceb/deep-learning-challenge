ANSWERS TO QUESTIONS

Identifying the Model’s Target: The model’s target is encapsulated in the “IS_SUCCESSFUL” variable, which serves as a binary indicator of an organization’s historical success in utilizing their funding.

Determining the Model’s Features: The model incorporates the following features:

Application Type: The category of the application.
Affiliation: The association with a sector or group.
Classification: The categorization according to government standards.
Use Case: The intended purpose for the funds.
Organization: The type of applying entity.
Status: The current operational state.
Income Amount: The financial tier of the organization.
Special Considerations: Any exceptional factors relevant to the application.
Ask Amount: The amount of funding requested.
Variables to Exclude: Non-informative variables such as EIN (tax ID) and Name are excluded from the input data as they do not serve as targets or features.

Neural Network Architecture: The neural network model is structured as follows:

Input Layer: A dense layer with 80 neurons employing the ReLU activation function.
Hidden Layer: A dense layer with 30 neurons, also using the ReLU activation function.
Output Layer: A dense layer with a single neuron activated by the sigmoid function.
Achieving Target Performance: The model did not reach the target performance goal of 75%, with the highest accuracy achieved being 73%.

Efforts to Enhance Performance: Adjustments were made to the dataset size, the number of neurons, layers, activation functions, epochs, and learning rate in an attempt to improve performance.

Model Performance Summary and Recommendations: The deep learning model, after several optimization attempts, did not surpass 73% accuracy. This outcome suggests that the neural network may not be the optimal approach for this dataset. An alternative, such as the Random Forest model, which constructs multiple decision trees during training, could offer a more robust solution. Similarly, a Gradient Boosting model, which iteratively corrects errors from previous trees, could also be effective in improving accuracy.




































