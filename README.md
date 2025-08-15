# 🧱 CodeGPT



# 🚀 What's this
CodeGPT is a AI searching assistant for developer that helps code and workspace semantic search


# 🏁 Quick Start
you can follow the steps below to build from source. 
## 📦 Build From Source
1. Pull the latest version of the CodeGPT from the GitHub repository.
1. Pip install the requirements.txt file under the CodeGPT root directory. 
```sh
pip install -r requirements.txt
```
1. Open terminal and run the following command to start the server.
```sh
python run_api.py
```
1. Open terminal and run the following command to start the webapp.
```sh
cd solidportal
npm install
npm run dev
```



 ### 1. Setup Codebase
1. Enter your OpenAI API key. [Get OpenAI API Key](https://openai.com/blog/openai-api)
1. Enter the full path of the folder you wish to onboard. **Suggest onboard lower than 100 files, maximum support 500 files onboarding**. 


 ### 2. Setup Notion (Optional)
1. Configure the Notion API by getting your Notion API secret from [Notion API](https://developers.notion.com/docs/create-a-notion-integration#getting-started) and entering it on the Settings page
1. Give your integration page permissions. [Details](https://developers.notion.com/docs/create-a-notion-integration#give-your-integration-page-permissions)
1. Get Notion Page ID and entering it on the Settings page
<img width="669" alt="image" src="https://github.com/AI-Citizen/SolidGPT-Private/assets/39673228/ae2b5ab3-af61-44e7-bdc1-d81a33462d23">
<img width="315" alt="image" src="https://github.com/AI-Citizen/SolidGPT-Private/assets/39673228/6e96db5b-350a-4e8b-b9ca-b41ccfe6ce7c">

 ### 3. Pick chat resources and start chat


## 🔥 Usecase
- Talk to your codebase, save time hunting for the place to start a change or the right method to call.
- Ask any questions about your codebase, get the answer in seconds.
- Semantic search and summary in Notion, knows your project from documents and track the project sprint board and tickets.
- Get questions answered from your codebase and Notion, no more context switching.

## 📖 Known Issue
1. [Intel Chip Mac]: permission denied 
    - Please run \`cd ~/.vscode/extensions\` and \`chmod -R 777 aict.solidgpt*\` in your terminal to allow the app to run.

## 📣 Feedback!!
If you have any questions or feedback about our project, please don't hesitate to reach out to us. We greatly appreciate your suggestions!
- Email: aict@ai-citi.com
- GitHub Issues: For more technical inquiries, you can also create a new issue in our [GitHub repository](https://github.com/AI-Citizen/SolidGPT/issues).
We will respond to all questions within 2-3 business days.

## Data Safety
- SolidGPT will not collect any of users' data.
- SolidGPT using OpenAI series model API, using SolidGPT indicates that you have read, understood, and agreed to adhere to all terms of use associated with the OpenAI GPT series model API.
