# SMS Spam Detector

This project is an SMS Spam Detector that classifies SMS messages as either "spam" or "ham" (not spam) using a machine learning model. The project uses a dataset of SMS messages to train the model and provides a web interface for users to input their own SMS messages for classification.

## Project Structure

- `gradio_sms_text_classification.ipynb`: Jupyter notebook containing the main code for training the model and creating the web interface using Gradio.
- `gradio_sms_text_classification copy.ipynb`: A copy of the main notebook for backup or additional experimentation.
- `Resources/SMSSpamCollection.csv`: Dataset containing SMS messages labeled as "spam" or "ham".
- `spam.csv`: Another dataset containing SMS messages labeled as "spam" or "ham".
- `.gradio/flagged/dataset1.csv`: Contains flagged data from the Gradio interface.
- `sms_text_classification_solution.ipynb`: Solution notebook for the SMS text classification task.

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd sms_spam_detector
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook [gradio_sms_text_classification.ipynb](http://_vscodecontentref_/5) and run all cells to train the model and launch the Gradio web interface.

2. The Gradio interface will be available at `http://127.0.0.1:7860`. You can input your SMS messages and get the classification result.

## Dataset

The dataset used for training the model is [SMSSpamCollection.csv](http://_vscodecontentref_/6), which contains SMS messages labeled as "spam" or "ham".

## Model

The model is a machine learning pipeline that uses `TfidfVectorizer` for text feature extraction and `LinearSVC` for classification.

## Example

Here is an example of how to use the Gradio app to classify an SMS message:

1. Open the Jupyter notebook [`gradio_sms_text_classification.ipynb`](gradio_sms_text_classification.ipynb) and run all cells to train the model and launch the Gradio web interface.

2. The Gradio interface will be available at `http://127.0.0.1:7860`. You can input your SMS messages and get the classification result.

3. Enter an SMS message in the input box and click "Submit" to see the classification result.

Example usage:

1. Start the Gradio app by running the notebook.
2. Open your web browser and go to `http://127.0.0.1:7860`.
3. Enter the following SMS message in the input box:
    ```
    Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005. Text FA to 87121 to receive entry question(std txt rate)T&C's apply 08452810075over18's
    ```
4. Click "Submit" to see if the message is classified as "spam" or "ham".

