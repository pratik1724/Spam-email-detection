# Spam-email-detection
This project aims to classify emails as spam or non-spam (ham) using machine learning techniques. It utilizes a logistic regression model trained on email data, with text features extracted using TF-IDF (Term Frequency-Inverse Document Frequency).

Introduction
  Spam detection is a crucial application of machine learning in the field of email communication. This project leverages logistic regression to classify emails as     spam or non-spam (ham) based on their textual content. The model is trained on a dataset of labeled emails and uses TF-IDF vectorization to convert text data into    numerical features.

Dataset
  The dataset used in this project should be in CSV format with the following structure:
    Category: Label indicating whether the email is 'spam' or 'ham'.
    Message: The content of the email.
  Ensure the dataset is named mail_data.csv and placed in the same directory as the Jupyter notebook.

Dependencies
  The project requires the following Python libraries:
    numpy
    pandas
    scikit-learn

Contributing
  Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to discuss any changes or improvements.
