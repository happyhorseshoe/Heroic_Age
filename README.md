> # **Project Heroic Age or Heroic Population**

### More information on the Carnegie Hero Fund Commission can be found here:
https://www.carnegiehero.org/

The Carnegie Hero Fund was established in 1905 by Andrew Carnegie who said "we live in a Heroic Age". This project will examine if people are more willing to risk their life for a stranger if they live in a smaller population area. I chose the Carnegie Hero Fund for data because of its requirements and number of years available. The award is given 4 times a year to civilians who voluntarily risks life to an "extraordinary degree" and have "no full measure of responsibility for the safety of the victim". Part One will focuse on cleaning and analysis of the Carnegie Hero Fund data. Part Two will introduce and clean population data from the Census Bureau. Part Three will merge the two data frames. Part Four will summarize my finidings.

>> 
<br> 

Full data for the Carnegie Medal can be viewed in medal.xlsx<br>
Full data for the population growth of all counties in California can be viewed in CAPOP.xlsx<br>
All project work is found in hero.ipynb<br>
See DATA_DICTIONARY.md for terminology explanations<br>
See visuals on Tableau at https://public.tableau.com/app/profile/elizabeth.morrison3800/viz/HeroicAgeorHeroicPopulation_16590510292000/Story <br>
>>
### Relevant Packages:
Jupyter Notebook (my project is an .ipynb file) <br>
Python 3 and higher <br>
See requirement.txt for all packages<br>
I created my project on a Windows machine using Visual Studio Code and PowerShell creating a virtual environment in my Jupyter Notebook (kernel .venv Python 3.10.1)

### To Run:
For information on how to install and run Jupyter Notebook, please see the documentation at https://jupyter.org/install

- Install Jupyter Notebook with: pip install notebook in order to run the notebook, hero.ipynb
- Run the command jupyter notebook in the command prompt (Windows) or terminal (Mac).
- Navigate to the project directory Heroic_Age and open the hero.ipynb file

- Once the notebook has opened, select Kernel and Restart & Run All to run all cells in the file.

- Note: You might need to repeat the steps in this section to git clone and install requirements

- git clone https://github.com/happyhorseshoe/Heroic_Age

- Install required packages by running pip install -r requirement.txt
<br>

### Alternative Instructions for running:

- Setup: Run git clone <your repo url.git> to clone the repository.
-  the directory for the project ('Heroic_Age'), run python3 -m venv venv to create the virtual environment.
- Activate the newly created python virtual environment. From the project directory run the following command:
>> - if using Windows Command Prompt: venv\Scripts\activate.bat
>> - if using Linux or Mac with bash/zsh: venv/bin/activate
- For additional help troubleshooting, see the "venv - Creation of virtual environments" documentaiton: https://docs.python.org/3/library/venv.html
- Run pip install -r requirement.txt to install the required packages.
- From the project directory, run python src\hero.ipynb on Windows, or python src/hero.ipynb on Linux/Mac, then follow the terminal prompts.

<br>

#### Please note that I use Markdown to explain each cell in my Notebook, demonstrating the required features listed below:


### Feature List:
1. Read TWO data files (JSON, CSV, Excel, etc.). 
2. Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.  
3. Make a Tableau dashboard to display your data.
4. Utilize a virtual environment and include instructions in your README on how the user should set one up.
    - Build a custom data dictionary and include it either in your README or as a separate document. This will only apply if your data set does not already have a data dictionary or if you’re building a custom data set.
5. Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. 



