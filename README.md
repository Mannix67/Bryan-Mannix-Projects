# Bryan-Mannix-Python movie cororolation project 
 #In this project we will be working in Python to find correlations between variables. to do this, i downloaded a movie data set from kaggle that deals
# with many different variables. I thought it would be interesting to use tools within python to see what factor is the most influencial in ensuring a 
# movie makes a high gross profit. 

![Screenshot (111)](https://user-images.githubusercontent.com/84920516/124481886-abb1e380-dda0-11eb-8bab-10eeabfa58b4.png)
#budget company country    director  genre  gross name rating  released runtime score star votes writer year    
#These are the different factors that data set composed of. My job is to find which one of thse has the highest corrorlation with gross profit. 

![Screenshot (112)](https://user-images.githubusercontent.com/84920516/124483502-51b21d80-dda2-11eb-989c-43661f9e009b.png)

#I then went about cleaning the data. I first looked to see if there was data missing and found that there wasn't. I then changed the data type for budget and gross 
to make it look better while also sorting the columbns.I also dropped any duplicates. 
Now the data was ready to plot on a graph. 

![Screenshot (115)](https://user-images.githubusercontent.com/84920516/124487908-254cd000-dda7-11eb-9b0f-68e68639c1b4.png)

I have a prediction that high budget corolates with high gross profit. to see if this was the case, i used seaborn 
sns.regplot scatter plot to see if there was a clear correlation. At first glance of the graph, it is clear that budget and gross profit are 
corrorlated. 

![Screenshot (117)](https://user-images.githubusercontent.com/84920516/124490915-90e46c80-ddaa-11eb-9e99-d7dc306372e1.png)

To see the exact corrorlation between gross profit and budget, i used the pearson correlation coefficient.the most common method to use for numerical variables; it assigns a value between − 1 and 1, where 0 is no correlation, 1 is total positive correlation, and − 1 is total negative correlation.  As you can see, there is a high corolation between gross revenue and magnitude of the budget at 0.712. I included other variables including score, run time, year, and votes to see they might have a higher coororlation than budget. 

![Screenshot (118)](https://user-images.githubusercontent.com/84920516/124492037-d5bcd300-ddab-11eb-95d7-4c03ec6c3046.png)

I used a heat map to make the correlations easier to see. Black low correlation, brighter colors for high. As we can, see Budget does have the highest corolation 
which means my prediction is correct so far, Votes also had a very high corrolation to high gross profit. 
However these are only for the numeric features. There are other string features which still have to measured for corolation which i will do so by changing them to numeric features. 

![Screenshot (121)](https://user-images.githubusercontent.com/84920516/124493102-2680fb80-ddad-11eb-8704-48e9f6b363ec.png)
![Screenshot (122)](https://user-images.githubusercontent.com/84920516/124493126-2f71cd00-ddad-11eb-81b6-68dd7f316366.png)

Before and after pic of the tables. String to numerized so i could analyse their corelation. 











 
















