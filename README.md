# Soul-of-Reason-NER

## There are three (identical) options for processing your transcript text files & creating the final dataset of named entities:

`1) Running the script: 'SOR_SCRIPT.py'` <br>
`2) Running the Jupyter Notebook: 'SOR_DEMO.ipynb'` <br>
`3) Using the streamlit app: 'app.py'` <br>

`Implementation instructions for each of these options is contained in the SOR_DEMO.ipynb file.`

### Before implementing any of the above, ensure that you have installed the package requirements by doing the following:

1) Clone this repository to your local machine
2) In your command line, cd into the repository
3) Run "pip install -r requirements.txt" in command line


### 1) Running the script (SOR_SCRIPT.py):

1) In your command line, cd into the repository
2) Run 'python3 SOR_SCRIPT.py' in your command line
3) Enter the folder path to your text files when prompted
4) Enter the file path to your metadata when prompted

The script will then create the final dataset, download the csv & json files to your current working directory and return some statistics on the number of entities identified!

`See the section entitled "Demo: Running the Script" in the SOR_DEMO file for complete instructions and an example.`


### 2) Using Jupyter notebook (SOR_JUPYTER.ipynb):

1) Import the required packages
2) Run the NER class
3) Instantiate class 
4) Follow the instructions in SOR_DEMO.ipynb on running each function
  - Note that you will need to replace the example folder & file paths with your speficic file locations
  
`See the section entitled "Demo: Using the Jupyter Notebook" in the SOR_DEMO file for complete instructions and an example.`
  
### 3) Using the streamlit app (app.py)

1) In your command line, cd into the repository
2) Run "streamlit run app.py" in your command line
  - Note: if an error appears here, you may need to upgrade the protobuf package: run "pip install --upgrade protobuf" and then try again
3) The app should automatically open in your browser. Enter the required information on the sidebar and then click "run"

`See the section entitled "Demo: Using the streamlit app" in the SOR_DEMO file for complete instructions and an example.`
