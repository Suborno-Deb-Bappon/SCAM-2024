# AUTOGENICS
AUTOGENICS: Automated Generation of Context-Aware Inline Comments for Code Snippets on Programming Q&amp;A Sites Using LLM

### There are a total of three folders. 

    - (1) Effectiveness Evaluation of LLMs-Generated Inline Comments (RQ1)
    - (2) Practitioners' Perspective on LLM-Generated Comment Effectiveness & Tool Preference (RQ2)
    - (3) AUTOGENICS- A Browser Plugin to Generate Context-Aware Noise-Free Inline Comments (RQ3)

- In the first folder named _**"Effectiveness Evaluation of LLMs-Generated Inline Comments (RQ1)"**_, there are two sub-folders as follows.

  - **(a) Evaluation of Inline Comment Generated by Gemini:** Initially, we evaluate the inline comments (without context) generated by Gemini for both Python and Java. The quartile-wise evaluation results of this analysis for Python and Java are stored in the _Python_Quartile Analysis.csv_ and _Java_Quartile Analysis.csv_ respectively.
    
  - **(b) Comparative Evaluation of Inline Comments Generated by GPT with Gemini:** We further evaluate the inline comments (without context) generated by GPT and compare its performance with Gemini. The quartile-wise evaluation results of this analysis for Python and Java are stored in the _Python_Quartile Analysis.csv and _Java_Quartile_Analysis.csv_ respectively.


- In the second folder named _**"Practitioners' Perspective on LLM-Generated Comment Effectivenss & Tool Preferecne (RQ2)"**_, there is one file named _"Survey Data.csv"_ which contains the findings from our survey.


- In the third folder "AUTOGENICS- A Browser Plugin to Generate Context-Aware Noise-Free Inline Comments (RQ3)", there are three sub-folders as follows.
  
  - **(a) AUTOGENICS Tool Integration:** This folder contains the source code for _AUTOGENICS_ tool. Installation instructions are described below.
      - Download this folder (_AUTOGENICS Tool Integration_) in your local drive.
      - Open the Chrome browser. Type in the search bar _chrome://extensions_.
      - Activate the _Developer mode_ option in the top right.
      - Click the _Load unpacked_ button to upload the _scripts_ folder into it (which exists within _AUTOGENICS Tool Integration_).
      - Activate the loaded extension (_AUTOGENICS 1.0_)
      - Open Microsoft VS Code IDE. Then, open the _AUTOGENICS Tool Integration_ folder in your VS Code workspace.
      - Open the VS Code terminal and install the requirements by typing _pip install -r requirements.txt_ in the terminal. This will install all the required dependencies for running _AUTOGENICS_.
      - After installing all the requirements, open  the _.env_ file (exists within _AUTOGENICS Tool Integration_ folder) to assign your own Gemini API key to the _GOOGLE_API_KEY_ variable.
      - Open _app.py_ file (which exists within _AUTOGENICS Tool Integration_ folder).
      - Type _python app.py_ in the VS Code terminal. That will run the Flask server in the backend.
      - Don't close the VS code. Minimize the VS Code window and go into the Stack Overflow site. Choose a Python/Java question.
      - There, you will see a button named _AUTOGENICS_ for the corresponding answer code snippets of your chosen question.
      - After clicking the _AUTOGENICS_ button, you will see the generated context-aware and noise-free inline comments for that answer code snippet.
    
  - **(b) AUTOGENICS Tool Effectiveness Evaluation:** After the _AUTOGENICS_ tool development, we evaluate its effectiveness. Later, we store the comparative evaluation results for Python and Java in the  _Python_Quartile Analysis.csv and _Java_Quartile_Analysis.csv_ respectively.
    
  - **(c) AUTOGENICS Working Example- Sample Video:** We provide a sample working example video of _AUTOGENICS_ in the file _AUTOGENICS Working Example Video.mp4_. Here, we demonstrate the functionality of our tool by generating context-aware noise-free inline comments for a sample answer code snippet from Stack Overflow.

