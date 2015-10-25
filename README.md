{\rtf1\ansi\ansicpg1252\cocoartf1343\cocoasubrtf160
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red128\green0\blue128;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardeftab720

\f0\b\fs28 \cf0 \expnd0\expndtw0\kerning0
						Male or Female?\
	 		\cf2 \expnd0\expndtw0\kerning0
Choose the best Name Gender Classifier\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardeftab720

\b0\fs22 \cf0 \expnd0\expndtw0\kerning0
\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardeftab720

\fs24 \cf0 \expnd0\expndtw0\kerning0
\
We started with a template file where we split the data so we would have comparable results.\
\
https://github.com/groupGit/IS620GroupProject3/blob/master/Project3_version_a.ipynb\
\
We then created a chatbot @ Slack.com to exchange our ideas. We then experimented with  different techniques and features.  Our goal was to find the best machine learning classifier for the names corpus dataset. Using slack, we split our work and used github to check-in files as and when we got our classifiers done. \
\
The dataset was pretty small with 7944 rows and was split into three data-frames,  maintaining the same ration of male and female in all the sets:Validation set with 500 rows, Test set with 500 rows and Train set with 6944 rows. This was the basis for all the classifiers and our team built the classifiers mentioned below. \
\
1. Max Entropy: https://github.com/groupGit/IS620GroupProject3/blob/master/Project3_MaxEntropy.ipynb\
\
2. Random Forest: https://github.com/groupGit/IS620GroupProject3/blob/master/RandomForest.ipynb\
\
3. Decision Tree: https://github.com/groupGit/IS620GroupProject3/blob/master/DecisionTreeT2.ipynb\
\
4. Naive Bayes:\
a) https://github.com/groupGit/IS620GroupProject3/blob/master/naive_bayes_2a.ipynb\
b) http://localhost:8888/notebooks/naive_bayes2.ipynb\
\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardeftab720

\fs22 \cf0 \expnd0\expndtw0\kerning0
\
The results are summarized under each classifier. The overall view was that the feature with first letter and the last letter performed the best. \
\
}