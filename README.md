# DS-Unit-4-Sprint-1-NLP

Hello World!!

Hi Everyone! I'll be your instructor for Unit 4. I hope you all are excited to learn about Natural Language Processing and Neural Networks!

Please fork the repo for this sprint: <https://github.com/LambdaSchool/DS-Unit-4-Sprint-1-NLP>

We will be completing each module this sprint on your local computer via Jupyter Lab. We will be using conda environments to manage the packages and their dependencies for this sprint's content. In Units 1&2, we abstracted away environment management by using Colab. However, as you saw in Unit 3, environment management is an important professional data science skill. We showed you how to manage environments using pipenv during Unit 3, and in this sprint, we will introduce another common environment management tool in the data science community:

conda: Package, dependency and environment management for any language—Python, R, Ruby, Lua, Scala, Java, JavaScript, C/ C++, FORTRAN, and more.

The easiest way to install conda on your machine is via the Anaconda Distribution of Python & R. Once you have conda installed, read "A Guide to Conda Environments". This article will provide an introduction into some of the conda basics.

To get the sprint environment setup:

1. Open your command line tool (Terminal for MacOS, Anaconda Prompt for Windows)

2. Navigate to the folder with this sprint's content (git clone after you fork the NLP repo). There should be a `requirements.txt` in that folder.

3. Run `conda create -n U4-S1-NLP python==3.7` => You can also rename the environment if you would like. Once the command completes, your conda environment should be ready.

4. Now, we are going to add in the require python packages for this sprint. You will need to 'activate' the conda environment: `source activate U4-S1-NLP` on Terminal or `conda activate U4-S1-NLP` on Anaconda Prompt. Once your environment is activate, run `pip install -r requirements.txt` which will install the required packages into your environment.

5. We are going to also add an Ipython Kernel reference to your conda environment, so we can use it from JupyterLab.

6. Next run `python -m ipykernel install --user --name U4-S1-NLP --display-name "U4-S1-NLP (Python3)"` => This will add a json object to an ipython file, so JupterLab will know that it can use this isolated instance of Python.

7. Last step, we need to install the models for Spacy. Run these commands `python -m spacy download en_core_web_md` and `python -m spacy download en_core_web_lg`

8. Deactivate your conda environment and launch JupyterLab. You should know see "U4-S1-NLP (Python3)" in the list of available kernels on launch screen.

I look forward to working with you all again! If you run into any issues getting your conda environment setup, I'll be available on Slack this evening to help.
