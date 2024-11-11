** Supervised_ML**

In real estate: pricing is a central aspect to the business. Traditionally, it’s the domain of home appraisers to determine the value of a property, which must be executed in an unbiased way, following an official criteria to ensure that there is no favour towards either the buyer or the seller..

When the appraisal price is set, clients need to decide whether they should buy the property or not. It all boils down to this simple question: is the “true value” of the property above or below the price set by the appraisal? Data is the key to answer this question reliably and efficiently.

In this casestudy we use a dataset containing a historical register of housing prices in Ames, a small city in Iowa —the actual prices at which the properties were sold. For each house, it also contains around 80 different features, such as the area, the state of the property, whether it has a backyard or not, etc.

**Project overview**

This real estate consultancy project will be conducted in two primary phases:

	1.	Classification Phase: The goal is to predict whether a house is “Expensive” or “Not expensive.” This is a classification task, meaning the model’s output is categorical. This phase allows for straightforward evaluation: predictions are either correct or incorrect, which simplifies measuring accuracy.
	2.	Regression Phase: Here, the model will predict the exact price of the house in dollars, making it a regression task. Since exact values are rarely predicted perfectly, this phase will focus on minimizing prediction error, aiming to get as close as possible to the true value.

In each phase, we’ll follow a structured Machine Learning workflow:

	1.	Understanding the Context: This means researching housing price determinants and characteristics specific to Ames, Iowa, as well as understanding the features in the dataset (e.g., the types of roof materials and their relevance to pricing).
	2.	Data Exploration & Cleaning: Data quality is paramount; here, we’ll examine the data to identify inconsistencies, irrelevant features, or missing values. Effective cleaning helps ensure the model learns from reliable information.
	3.	Data Pre-processing: This stage includes transforming data to be model-ready. This involves steps like imputation for missing values, feature scaling, and engineering new features that may improve model performance.
	4.	Modeling: We’ll train and tune the model, testing various algorithms to find the most accurate fit. Automated model selection can streamline this process.
	5.	Error Analysis: Models are never perfectly accurate, so we’ll assess errors to understand where the model’s predictions deviate and by how much, focusing on which types of errors matter most for practical use.
	6.	Implementation: Finally, we’ll either report findings or deploy the model, depending on its use case. Deployment could involve building an API for live predictions, while reporting could focus on valuable insights into price determinants.

This process isn’t strictly linear; it’s agile and iterative. After an initial Minimum Viable Product (MVP) is developed, we can refine the model through further iterations, incorporating more features and improving performance. We’ll start with a basic classification solution and gradually enhance it as we progress toward the regression phase.


