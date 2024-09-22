
README: Enhancing Restaurant Menu Personalization through Food Image Analysis
Project Overview
This project explores the use of food image classification to enhance restaurant menu personalization, aiming to identify popular food items, analyze presentation preferences, and assess the accuracy of a classification model. By examining a dataset of 24,000 food images across 35 categories, including popular items like Hot Dogs, Crispy Chicken, and Sandwiches, the study provides insights to optimize menu design. The findings reveal opportunities for promoting underrepresented items like Sushi and Chai, while highlighting the need for model improvements to enhance predictive accuracy.

Methodology
The project followed a comprehensive data science approach involving data preprocessing, model development, and evaluation:

Data Preprocessing: Images were resized, normalized, and augmented to improve model training. The dataset was split into training and testing sets to ensure robust evaluation.
Model Development: A Convolutional Neural Network (CNN) model was built using layers of convolution, pooling, and dense connections to classify images into food categories.
Evaluation: The model’s performance was assessed using metrics such as accuracy, precision, recall, and F1-score. Confusion matrices were used to identify areas where the model excelled and struggled.
Visualization: Visual tools like bar charts and heatmaps were used to showcase the distribution of food categories, presentation preferences, and model performance metrics.
Key Findings
Class Representation: Popular items like Hot Dogs, Crispy Chicken, and Sandwiches dominate the dataset, indicating strong consumer interest, while underrepresented items offer promotion potential.
Model Performance: The CNN model showed low overall accuracy (around 9%), pointing to challenges with imbalanced classes and complex visual features, particularly with underrepresented categories.
Consumer Preferences: Brightness and color tone were found to significantly influence consumer choices, highlighting the importance of visually appealing images in menu presentation.
Implications and Applications
The study emphasizes the potential of food image classification in guiding menu personalization. Popular items can be prominently featured, and underrepresented items can be strategically promoted. Insights into image attributes like brightness can be used to enhance food presentation, particularly for digital menus and online ordering platforms.

Ethical Considerations
This analysis used publicly available data from Kaggle, ensuring compliance with data use policies and ethical standards. The recommendations are designed to enhance customer experiences without compromising data privacy, and findings are presented transparently to support ethical business practices.

Future Directions
To further improve menu personalization through food image analysis, the following steps are recommended:

Improve Data Balance: Increase the number of images for underrepresented items and diversify the dataset to achieve better class representation.
Refine Model Architecture: Explore advanced models, such as transfer learning with pre-trained networks like MobileNetV2, to enhance classification accuracy.
Enhance Presentation: Utilize insights from the analysis to improve the visual appeal of food items, especially on online platforms where presentation significantly impacts consumer choices.
Incorporate Feedback: Integrate customer feedback and reviews to continuously refine and align menu offerings with evolving consumer preferences.
Contact
For further information or collaboration inquiries, please contact the project lead at zemelak.s.goraga@gmail.com.