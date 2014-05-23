{\rtf1\ansi\ansicpg1252\cocoartf1265\cocoasubrtf190
{\fonttbl\f0\fswiss\fcharset0 ArialMT;}
{\colortbl;\red255\green255\blue255;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}}
\margl1440\margr1440\vieww13860\viewh9480\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural

\f0\fs24 \cf0 Summary:\
This dataset describes the average of each variable for each activity and each subject.  The set includes averages of mean and standard deviations measurements.  Mean and STD values for each measurement were obtained in the original dataset.  Please see the original dataset (URLs referenced below) for explanation of how raw data was obtained and how those values were calculated.\
\pard\pardeftab720\sl420
\cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural
\cf0 The set contains calculations per subject per activity type independent of the subject\'92s classification.  The set does not differentiate whether the subject or the activity performed was part of the test or training set.  Rather, the measurements are merged from both test and training sets and mean of mean and std is calculated from the merged set.\
\pard\pardeftab720\sl420
\cf0 Original dataset - {\field{\*\fldinst{HYPERLINK "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"}}{\fldrslt https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip}}\
A full description of the original data set and raw data -{\field{\*\fldinst{HYPERLINK "http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones"}}{\fldrslt http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones}}\
\pard\pardeftab720\sl420
\cf0 \
Data Dictionary:\
Each record contains the following 68 fields:\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls1\ilvl0\cf0 {\listtext	\'95	}subject - ID of a person/subject\
{\listtext	\'95	}activity_type - type of activity the subject performed\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural
\cf0  \
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls2\ilvl0\cf0 33 columns with -mean() in the column name contain a calculated mean of each measurement\'92s mean per activity type per subject:\
{\listtext	\'95	}tBodyAcc-XYZ - 3 columns\
{\listtext	\'95	}tGravityAcc-XYZ - 3 columns\
{\listtext	\'95	}tBodyAccJerk-XYZ - 3 columns\
{\listtext	\'95	}tBodyGyro-XYZ - 3 columns\
{\listtext	\'95	}tBodyGyroJerk-XYZ - 3 columns\
{\listtext	\'95	}tBodyAccMag\
{\listtext	\'95	}tGravityAccMag\
{\listtext	\'95	}tBodyAccJerkMag\
{\listtext	\'95	}tBodyGyroMag\
{\listtext	\'95	}tBodyGyroJerkMag\
{\listtext	\'95	}fBodyAcc-XYZ - 3 columns\
{\listtext	\'95	}fBodyAccJerk-XYZ - 3 columns\
{\listtext	\'95	}fBodyGyro-XYZ - 3 columns\
{\listtext	\'95	}fBodyAccMag\
{\listtext	\'95	}fBodyAccJerkMag\
{\listtext	\'95	}fBodyGyroMag\
{\listtext	\'95	}fBodyGyroJerkMag\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural
\cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural
\cf0 33 columns with -std() in the column name contain a calculated mean of each measurement\'92s standard deviation per activity type per subject:\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls3\ilvl0\cf0 {\listtext	\'95	}tBodyAcc-XYZ - 3 columns\
{\listtext	\'95	}tGravityAcc-XYZ - 3 columns\
{\listtext	\'95	}tBodyAccJerk-XYZ - 3 columns\
{\listtext	\'95	}tBodyGyro-XYZ - 3 columns\
{\listtext	\'95	}tBodyGyroJerk-XYZ - 3 columns\
{\listtext	\'95	}tBodyAccMag\
{\listtext	\'95	}tGravityAccMag\
{\listtext	\'95	}tBodyAccJerkMag\
{\listtext	\'95	}tBodyGyroMag\
{\listtext	\'95	}tBodyGyroJerkMag\
{\listtext	\'95	}fBodyAcc-XYZ - 3 columns\
{\listtext	\'95	}fBodyAccJerk-XYZ - 3 columns\
{\listtext	\'95	}fBodyGyro-XYZ - 3 columns\
{\listtext	\'95	}fBodyAccMag\
{\listtext	\'95	}fBodyAccJerkMag\
{\listtext	\'95	}fBodyGyroMag\
{\listtext	\'95	}fBodyGyroJerkMag\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural
\cf0 \
\
Transformations:\
The following steps were performed to produce the dataset.\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls4\ilvl0\cf0 {\listtext	\'95	}obtain the \'93Human Activity Recognition Using Smartphones\'94 dataset from {\field{\*\fldinst{HYPERLINK "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"}}{\fldrslt \ul https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip}}\ul . \
\ls4\ilvl0\ulnone {\listtext	\'95	}unzip the files\
{\listtext	\'95	}read in test data set from \'93test/X_test.txt\'94 file\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls4\ilvl0\cf0 {\listtext	\'95	}update column names of the test data set with measurement names read from \'93features.txt\'94 file\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls4\ilvl0\cf0 {\listtext	\'95	}read in activity IDs from \'93test/Y_test.txt\'94 file and add them as a new column \'93activity\'94 to the test data set\
{\listtext	\'95	}read in subject IDs from \'93test/subject_test.txt\'94 file and add them as a new column \'93subject\'94 to the test data set\
{\listtext	\'95	}read in train data set from \'93train/X_train.txt\'94 file\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls4\ilvl0\cf0 {\listtext	\'95	}update column names of the train data set with measurement names read from \'93features.txt\'94 file\
{\listtext	\'95	}read in activity IDs from \'93train/Y_train.txt\'94 file and add them as a new column \'93activity\'94 to the train data set\
{\listtext	\'95	}read in subject IDs from \'93train/subject_train.txt\'94 file and add them as a new column \'93subject\'94 to the train data set\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural
\ls4\ilvl0\cf0 {\listtext	\'95	}eliminate unneeded columns in test and train sets, only keep subject, activity, mean and std measurement columns.\
{\listtext	\'95	}merge the test and train data sets - append train to test\
{\listtext	\'95	}add a column \'93activity_type\'94 and populate it with activity names from the \'93activity_labels.txt\'94 file.  each activity number in the \'93activity\'94 field of the data set has a corresponding activity type.  for example, activity with number 5 maps to \'93STANDING.\'94\
{\listtext	\'95	}remove \'93activity\'94 column as we now have \'93activity_type\'94 column that describes the activity name rather than it\'92s number/ID\
{\listtext	\'95	}melt the data frame into a 4-column table that has \'93subject\'94 and \'93activity_type\'94 id variables and all measured means/standard deviations as measure variables.  measure variables consume two columns - variable name and variable value.\
{\listtext	\'95	}cast the molten frame into a frame that displays mean for each measured variable for each activity and each subject\
{\listtext	\'95	}write out the data frame to the \'93tidy_data.txt\'94 file\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural
\cf0  \
}