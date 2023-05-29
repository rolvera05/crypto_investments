# *Crypto Investment*
In this project, I've adopted a novel perspective on assembling crypto-based investment portfolios. Beyond just examining returns and volatility, I'm delving into a variety of factors that might impact the crypto market, aiming to enhance the performance of these portfolios.

The centerpiece of this repository is a Jupyter notebook. Here, I've integrated Python programming with unsupervised learning techniques to cluster cryptocurrencies based on their performance over different time periods. To make the results more comprehensible, I've also included visualizations of these clusters.

The analysis relies on a CSV file that contains price change data for different cryptocurrencies over several time periods.

Feel free to explore this fascinating crossroad of finance and machine learning, showcasing a fresh approach to portfolio management.

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, hvplot, scikit-learn, pathlib

- **Framework:** JupyterLab
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

**First things first:**
If you don't have Python, JupyterLab, or Anaconda installed on your operating system:

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**

With the Anaconda package installed, you should already have all the necessary libraries to run the main application downloaded except for yfinance and voilà. For this section, all listed commands should be executed in your operating system's terminal.


**1. Conda 'dev' Environment** - To run the main application you will need to activate a 'dev' environment in your terminal. Luckily a 'dev' environment is included with the Anaconda package, and can be activated with:

        conda activate dev

If you do not have a 'dev' environment, or wish to create a new one that will be compatible with this application, type and enter the following. You will still use the previous steps' command to activate:

        conda create -n dev python=3.7 anaconda

**2. Other Libraries** - It was mentioned earlier that the other required libraries should already be installed with the Anaconda package. To confirm installation for these libraries, you can either use the 'conda list' command followed by the library name to confirm installation same as for yfinance listed above. Or, you can install the libraries which will either install successfully or if already installed, will result in a 'requirement already satisfied' message. Listed below are the commands to install each library if needed:
        
        pip install pandas
        pip install hvplot
        pip install scikit-learn

**3. Clone Repo** - Once you have checked off all previous installation steps, its now time to clone/download this repository onto your local machine for use. To do that, first copy the SSH keys.

Now, in your terminal cd to a location where you want this repo folder to reside. We recommend choosing your desktop as the location due to it's easy access/simple path. Once you are in your preferred current directory, enter the following:

        git clone copied ssh keys here

Nicely done! You now are ready to utilize the code. To run the repo folder in JupyterLab for usage, simply cd to the repo folder, then type and enter:

        jupyter lab

### **IMPORTANT:** Ensure your conda 'dev' environment is activated before running the 'jupyter lab' command. Otherwise, the application will most likely result in errors when you try to run it.
---

## *Usage*

### 1. User Input
- Once JupyterLab is open with the repo code, the first thing you will do is open the user_input.ipynb notebook. 
- Once the user_input notebook is open, under 'Kernel' in the menu bar select 'Restart Kernel and Run All Cells'.

- Once the application loads, a box of inputs such as 'Ticker' and 'Strategy' will open up under the first code block. Go ahead and input your prefferred information as follows and hit the 'Submit' button.

- To confirm upload, manually select the next block of code under 'User Inputs', followed by 'shift+enter' on your keyboard two times.

### 2. crypto_investments (main application)
- Once you have completed the above usage steps, in JupyterLab open the crypto_investments.ipynb file.
- Once open, same as before, under 'Kernel' in the menu bar select 'Restart Kernel and Run All Cells'.
- This will automatically run the entire application for your viewing and analyzing pleasure with your inputs from the user_input notebook

---
## *References*
- [hvplot Usage](https://hvplot.holoviz.org/)
- [scikit-learn](https://www.analyticsvidhya.com/blog/2015/01/scikit-learn-python-machine-learning-tool/)

---

## *Contributors*

For any questions, comments, concerns, feel free to contact below: 

**Rosalinda Olvera Fernandez**

[GitHub](https://github.com/rolvera05) - rolvera98271@gmail.com


---