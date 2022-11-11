# Using Clear ML for ML Operations on a Movie Rating Prediction Problem

We recommend you to create a Conda Python Environment so that ClearML can function independently in your system without affecting the core system.

I recommend Github + VS code for this walkthrough. But you can do this in any IDE or Versioning Platform. You’re expected to have Python and Conda installed in your system.

In your VS Code Terminal (cmd) : To create a virtual environment, 

    conda create -n clearml python=3.9 anaconda

    conda activate clearml

reference: https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/


You can clone my repository, to your system, and run the following after activating the Conda environment.

	conda activate clearml


I’ve made a list of requirements you can install in your environment for ease of use, with the following commands. You can also do this independently with pip.

    pip install -r requirements.txt

    pip install clearml
    
Once your environment is set up, you just need to initialize clearML in your terminal.
    
    clearml-init

You would have to goto the prompted link and connect your ClearML with the WebApp. The steps are very intuitive and you just need to follow the prompted steps.

Now that you have ClearML running and environment set up.

You can follow the rest of the steps in the Codes\model_training.ipynb notebook.