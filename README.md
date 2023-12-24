# Capuchin-Bird-Audio-Count
Using signal processing techniques and CNNs to count the number of Capuchin Birds from audio recordings

## <u>Overview</u>
The Challenge is to build a Machine Learning model and code to count the number of Capuchinbird calls within a given clip. This is Challenge 3 from '[Z by HP Unlocked](https://www.hp.com/us-en/workstations/industries/data-science/unlocked-with-z.html?jumpid=va_973ccb1879)'.

## <u>About the dataset</u>
The data is split into train and test. The training data consist of recordings of Capuchin Bird sounds and recordings of Non-Capuchin bird sounds. Visit [Kaggle](https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing#where-to-start) for more information and the raw dataset. 
In my analysis, in an effort to resolve a class imbalance, I oversampled from the capuchin audio files after altering the pitch of their audio. This method created new files that are added to the data file in my repo. I have also commented the function that saves the new modified files in my notebook since I only used it once.


