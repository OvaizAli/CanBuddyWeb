# CanBuddy

CanBuddy is a generative AI-based web application designed to streamline how Canadians access insights from Reddit posts. Instead of spending extensive time scrolling through various threads or subreddits, users can leverage CanBuddy to quickly obtain comprehensive and relevant news summaries. The application uses large language models to generate detailed AI news articles based on posts from Canadian subreddits, ensuring users stay well-informed about current events and trends in Canada efficiently. Moreover, it also provides functionality to chat with an AI assistant powered by Large Language Models and includes a dashboard offering intuitive insights for the users.

## Features

- **AI News Generation**: Transforms posts from Canadian subreddits into well-structured and informative news articles generated by large language models, providing a consolidated view of key events and discussions.
  
- **AI Assistant**: Engages users in real-time conversations with CanBuddy LLM about the latest news and developments in Canada. The assistant is updated daily at 9:00 AM UTC to ensure the information remains current and contextually relevant.

- **Interactive Dashboard**: Offers users an engaging platform to explore data and visualizations related to Canadian news and trends fetched from the subreddits related to Canada, enabling deeper insights and data-driven decision-making for the application users.

## Installation and Setup

### Clone the Repository:
   git clone https://github.com/your-username/canbuddy.git
   cd canbuddy

### Code Structure

- **`app.py`**: Main Streamlit application script.
- **`htmltemplate.py`**: Contains HTML templates for styling chat messages.
- **`requirements.txt`**: List of Python packages required for the project.

### Set Up Environment

Create a `.env` file in the root directory and add the following environment variables:

HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_token

### Install Dependencies

pip install -r requirements.txt

### Run the Application

streamlit run app.py


## Deployment

CanBuddy is deployed as a SaaS application and uses a multi-cloud deployment model with AWS and GCP services.

## Services Used

- **AWS Services**:
  - **Compute**: AWS Lambda
  - **Storage**: AWS S3
  - **Network**: Amazon EventBridge
  - **General**: AWS Glue, AWS Secrets Manager

- **GCP Services**:
  - **Google Cloud Function**
  - **Google Natural Language API**
  - **Google Cloud Storage**
  - **Looker Studio**

## Contributing

Contributions are welcome! Please follow these guidelines for contributing:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact [your-email@example.com](mailto:your-email@example.com).

