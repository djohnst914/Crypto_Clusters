# Crypto Clusters 
For this challenge, I've assumed the role of an advisor in one of the top five financial advisory firms in the world. Competitors are fierce, so I have proposed a novel approach to my manager for assembling investment portfolios that are based on cryptocurrencies. Instead of basing this proposal on only returns and volatility, I have included other factors that might impact the crypto market, leading to better performance for a portfolio. 

Based off this proposal, I have been asked to create a prototype for submitting this crypto portfolio proposal to the company board of directors. In order to do so, I've combined financial Python programming skills with new unsupervised learning skills.

Above, I have created a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods, which have been plotted within the notebook and are ready for presentation! 

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, hvPlot, pathlib, sklearn(KMeans, PCA, StandardScaler), warnings
- **Framework:** JupyterLab
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

**First things first:**
If you don't have Python, Jupyter Lab, or Anaconda installed on your operating system ..

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**

The libraries listed above all come automatically installed with the Anaconda package. To confirm installation for one or more of the libraries, reference steps/example below:

1. Activate the Conda dev environment (if it isn’t already) by running the following in your terminal:

        conda activate dev
2. When the environment is active, run the following in your terminal:

        conda list scikit-learn

- You'll get a similar output as shown below:
<img width="514" alt="Screenshot 2023-05-17 at 12 22 00 PM" src="https://github.com/djohnst914/github_upload/assets/123714457/ceee775f-ebca-4197-8733-23c7d85ea124">

- **Clone Repo** - Once you have checked off all previous installation steps, its now time to clone/download this repository onto your local machine for use. To do that, first copy the SSH keys which can be found here: 
<img width="429" alt="Screenshot 2023-05-17 at 12 29 07 PM" src="https://github.com/djohnst914/github_upload/assets/123714457/4af8260a-ec81-43cc-be49-2d2ee41fe654">

- Now, in your terminal cd to a location where you want this repo folder to reside. I recommend choosing your desktop as the location due to it's easy access/simple path. Once you are in your preferred current directory in the terminal, enter the following:

        git clone git@github.com:djohnst914/Crypto_Clusters

- Nicely done! You now are ready to utilize the code. To run the repo folder in JupyterLab for usage, simply cd to the repo folder, then type and enter:

        jupyter lab

### **IMPORTANT:** Ensure the Conda 'dev' environment is activated before running the 'jupyter lab' command. Otherwise, the application may result in errors when you try to run it

---

## *Usage*

- First, open 'crypto_investments.ipynb' in your file browser. 
- With your mouse navigate near the top of the tab, select 'Kernel', then inside Kernel you'll select 'Restart Kernel and Run All Cells...' This will automatically run the whole program for you start to finish. 
![Screenshot 2023-05-11 at 10 24 08 AM](https://github.com/djohnst914/github_upload/assets/123714457/b90fb7ec-793c-40c4-98ed-f0c68d5541f0)
- Once the jupyter notebook has fully loaded after running all cells, there are a few interactive graphs the user can manipulate to better understand a trend or explore a hypothesis they might have. The graphs are reltaively very user friendly, but if you find yourself having issues interacting with the them .. 

-**[Configuring hvPlot Tools](https://docs.bokeh.org/en/2.4.0/docs/user_guide/tools.html)**

---

## *Contributor*
For any questions, comments, concerns: 
- Dylan Johnston
- Email: dylanhjjohnston@gmail.com
- [GitHub](https://github.com/djohnst914)

---

## *License*

This software is licensed under the GNU General Public License v3.0. See [LICENSE](https://github.com/djohnst914/Crypto_Clusters/blob/main/LICENSE) file for details. 
