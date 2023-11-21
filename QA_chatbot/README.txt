1. Download the code folder which contains code files from drive: https://shorturl.at/gJNSU
2. Open code folder in VS Code IDE
3. Open new terminal
4. Change your directory in terminal to the folder in which you have placed your code files (QA_chatbot in this case)
5. create a new virtual environment by running this code in terminal: python -m venv env
6. Go to https://replicate.com/ and create an account(i.e. sign in) using your github account
7. After you sign in, you can see your username on top left corner, click on the drop down, you will see API tokens, click on that.
8. Create own token by writing your own custom token name you like and press the "Create token" button. Your token will get generated.
9. Just hover your mouse over the token, you will see copy option, copy it.
10. Go to the .env file and assign the Replicate API token obtained from Replicate website to REPLICATE_API_TOKEN variable 
	REPLICATE_API_TOKEN = ***** (replace this ***** with your own token that you just copied)
11. save the .env file (you can press ctrl+s)
12. we have one "requirements.txt" file which contains all the required libraries. 
    Install these libraries by running this code in the terminal: pip install -r requirements.txt 
	(have patience, it may take around 4-5 minutes)
13. Now, you are ready to run the app. Run this code in the termnial: streamlit run app.py
    Your app will start running in the browser.
14. Upload your corpus by clicking on the "Browse files" button provided on top left corner.
15. Your QA chatbot will get initiated. Ask your questions and AI powered chatbot will reply.
16. To stop the app, go to the terminal and press "ctrl+c"

