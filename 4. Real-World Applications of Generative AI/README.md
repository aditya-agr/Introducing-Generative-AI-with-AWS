# SageMaker Model Cards

## Model Cards
A model card is a detailed document or report that provides critical information about a machine learning (ML)/AI model in a structured and accessible format. It's designed to offer transparency and governance for machine learning models, especially when they are deployed in real-world applications.

Key elements of a model card typically include:

### Model Overview
A general description of the model, its purpose, the problem it's intended to solve, and the algorithm type it employs.

### Intended Use
Outlines the specific scenarios and applications for which the model is designed. It also mentions scenarios where the model should not be used, thus guiding responsible deployment and use.

### Risk Ratings
The model is categorized based on the level of risk associated with its application, which can range from low to high. This helps in understanding the potential implications of the model's predictions and decisions.

### Training and Evaluation Details
Information about how the model was trained, the data it was trained on, the training environment, and the metrics used to evaluate its performance.

### Model Performance and Metrics
Specific performance metrics, observations from evaluations, and any relevant graphs or statistical data are documented here.

### Ethical Considerations and Recommendations
Any ethical concerns related to the model and recommendations for its use, including any limitations or biases that users should be aware of.

### Versioning
Model cards maintain a record of changes made to the model, ensuring that there is a transparent history of its development and modifications.

### Additional Information
Custom details, caveats, and any other relevant information that doesn't fit into the standard sections can be included here.

Model cards in Amazon SageMaker follow a JSON schema to standardize the format and make it easier to create, share, and update these documents.

For more information on SageMaker model cards, check out the official AWS documentation (opens in a new tab).
