# 💼 LLM-Driven Marketing Campaign Assistant
This Streamlit-based application leverages Language Learning Models (LLMs) like Google Palm to assist in generating customized marketing content such as sales copy, tweets, and product descriptions. The app tailors content for specific target audiences, including kids, adults, and senior citizens.

## 🚀 Features
- **Content Generation**: Generate marketing content (sales copy, tweets, product descriptions) based on user inputs.
- **Target Audience Customization**: Choose from different age groups: Kids, Adults, or Senior Citizens, for personalized messaging.
- **LLM-Powered Responses**: Utilizes Google's LLM (Google Palm) API to generate intelligent responses based on the selected task and target audience.
- **Streamlit Interface**: User-friendly web interface built using Streamlit for ease of use.
  
## 🛠️ Technologies Used
- **Streamlit**: Front-end interface for user interaction.
- **LangChain**: Framework for handling prompts and few-shot learning.
- **Google Palm API**: The LLM engine used for generating responses.
- **Python**: Core programming language for the app.
- **dotenv**: For managing environment variables securely.

## 🔧 Setup and Installation
1. **Clone the Repository**:

```bash
git clone https://github.com/mshaadk/LLM-Driven-Marketing-Campaign-Assistant.git
cd LLM-Driven-Marketing-Campaign-Assistant
```

2. **Install Dependencies**: Ensure you have Python installed, and then install the required packages:

```bash
pip install -r requirements.txt
```

3. **Set Up Environment Variables**: Create a .env file in the root directory and add your Google API key:

```makefile
GOOGLE_API_KEY=your_google_api_key
```

4. **Run the Application**: Use Streamlit to run the application:

```bash
streamlit run app.py
```

## 📦 File Structure
```bash
├── app.py                  # Main application script
├── requirements.txt        # Required Python packages
├── .env                    # Environment variables
├── README.md               # Project documentation
├── LICESNE.txt             # License File
```

## 🌟 How to Use
1. **Enter the Product**: Provide the product name.
2. **Select the Task**: Choose from 'Write a sales copy', 'Create a tweet', or 'Write a product description'.
3. **Choose Target Audience**: Select the age group for content personalization (Kids, Adults, Senior Citizens).
4. **Generate Content**: Click the "Generate" button to get customized content.

## 🤝 Contributing
Contributions are welcome! 

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.
