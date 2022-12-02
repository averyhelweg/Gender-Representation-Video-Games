# Gender-Representation-Video-Games

## In this project my group and I decited to examine 3 datasets that involved various elements of gender representation in different video games, we wanted to investigate how we could increase gender representation in video games. To do that we began by investigating the average reviews of each game and the sexualization of each character in each game because we felt that those two variables would be at least moderatly positivly correlated. However, because our data was seperated into three different dataframes we had to figure out a way to merge all three before we could run any analysis. We were able to start by concatonating the sexualization dataset with the characters dataset on the 'ID' column and then joined that to the games dataframe by creating a data dictionary that included each 'Game_Id' with the sexualization of each game and then converting that dictionary into a dataset. We then were able to concationate the games dataset to the newly converted dictionary on the 'Game_Id' column to create the final dataset for our analysis. To analyze the correleation of each variable in the dataset we decided it would prudent to create a heat map. From that we were able to discover that sexualization and average reviews weren't nearly as correlated as we initially thought. This finding was shocking to us and caused us to question how sexuality was calculated. It also inspired us to shift our focus to two variables that had a better correlation, the number of females integrated on the design teams and the number of non male protagonists in these various games. 




## I've attached the PDF that contains the data dictionary, the original 3 datasets, the merged dataset I created in my notebook, and the notebook where I conducted my analysis.

## The original data can be found here on kaggle https://www.kaggle.com/datasets/br33sa/gender-representation-in-video-games 
### The licence of the data I used was the Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license, and the license of my data is the MIT lisence.
