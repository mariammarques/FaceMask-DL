Deep Learning Procect @NOVA IMS - MSc Data Science & Advanced Analytics 2021/2022
=============================================================================================
Group 10 Elements:
	- António Cymbron    | 20181059
	- Duarte Redinha     | 20181066
	- Gonçalo Silva      | 20181085
	- Maria João Marques | 20181119
	- Pedro Sequeira     | 20181097
=============================================================================================
1) The dataset that we used, can be downloaded at the following link:
	https://www.kaggle.com/datasets/jamesnogra/face-mask-usage

2) A zip containing 4 folders will be downloaded. The 4 folders need to be extracted from the
   zip, into a folder called 'Dataset', created by the user (which will then contain the 4
   folders that came inside the zip).

3) The file 'GROUP_10_report.pdf' is the report we made about the project

4) The file 'Holdout_Preprocessing&Training.ipynb' is the Jupyter Notebook where the
   original images were preprocessed, so that we could create and test models using
   the holdout method. Besides, in this notebook several tests of several models were
   made, with several parameters, and the best 5 were saved (in the 'saved_models' folder,
   which is a folder that the user must create in the directory where he is working).

5) The file 'GROUP10_notebook.ipynb' is the final Jupyter Notebook, where the 5 best models
   obtained through the holdout method (in the 'Holdout_Preprocessing&Training.ipynb') are
   imported and where those models are tested through CrossValidation.