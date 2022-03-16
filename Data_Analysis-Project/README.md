# Data_Analysis-Project
This repository was created in order to submit the project about Summer Olympics Data Analysis to Elite Techno Group's Skill India python ML/AI Internship.

I have created this project on my own without any third party's help

About this project:

In the Summer.ipynb: - Initially I have written the code to read values for summer.csv dataset provided by ETG-Team using pandas to covert it into a dataframe object.
                       Then I started coding for Questions asked by ETG-Team to analyse the data from the given dataset.
                     
                     - Question 1. In how many cities Summer Olympics is held so far?
                       
                       My Answer: I have written the code to get the unique value of cities [ df['City'].unique() ] where olympics held and then to get no of citites
                                  I used the built in len function [ len(df['City'].unique()) ]
                                 
                    - Question 2. Which sport is having most number of Gold Medals so far? (Top 5)
                       
                       My Answer: I have written the code to get the Sport which having gold medals and coverted it into dataframe as medal [ medal=df[df['Medal']=='Gold']] 
                                  With the dataframe I Analysed the sport which is having the most number of gold by converting them into 2d list of sport and no of gold medals
                                  Then sorted it in reverse order with respect to values of Medals.Then finally I plotted bar chart of TOP 5 Sport with most no of Gold medals 
                                  with the data I have analysed.
                                  
                     - Question 3. Which sport is having most number of medals so far? (Top 5)
                       
                       My Answer: I have written the code to get the Sport which having no of medals and coverted it into dataframe as medal [ medal=df['Medal']] 
                                  With the dataframe I Analysed the sport which is having the most number of medals by converting them into 2d list of sport and no of medals
                                  Then sorted it in reverse order with respect to values of Medals.Then finally I plotted bar chart of TOP 5 Sport with most no of medals 
                                  with the data I have analysed.
                       
                      - Question 4. Which player has won most number of medals? (Top 5)
                       
                        My Answer: I have written the code to get the Athlete which having no of medals and coverted it into dataframe as medal [ medal=df['Medal']] 
                                  With the dataframe I Analysed the Player who is having the most number of medals by converting them into 2d list of Athlete and no of medals
                                  Then sorted it in reverse order with respect to values of Medals.Then finally I plotted bar chart of TOP 5 Player with most no of medals 
                                  with the data I have analysed.
                                                                   
                      - Question 5. Which player has won most number Gold Medals of medals? (Top 5)
                       
                        My Answer: I have written the code to get the Athlete who having no of gold medals and coverted it to dataframe as medal[medal=df[df['Medal']=='Gold']]     
                                  With the dataframe I Analysed the Player who is having the most number of gold medals by converting them into 2d list of Athlete and no of gold medals
                                  Then sorted it in reverse order with respect to values of gold medals.Then finally I plotted bar chart of TOP 5 Player with most no of gold medals 
                                  with the data I have analysed.
                                  
                                  
                      - Question 6. In which year India won first Gold Medal in Summer Olympics?
                       
                        My Answer: I have written the code to get the unique value of Gold medal winning countries [df[df['Medal']=='Gold']] and given dataframe name as
                                   indian_medal and then to get no of gold medals won by INDIA [ indian_medal[indian_medal['Country']=='IND'] ].From the dataframe having 
                                   the list of gold medals won by INDIA I print the first values using .head(1) function.
                                
                     - Question 7. Which event is most popular in terms on number of players? (Top 5)
                       
                        My Answer: I have written the code to get the Event which having most poppularity and coverted it to dataframe as medal[df[df['Event']==event])]]     
                                  With the dataframe I Analysed the Event which is having the most popularity by converting them into 2d list of Event and popularity
                                  Then sorted it in reverse order with respect to values of popularity.Then finally I plotted bar chart of TOP 5 Events with most popularity 
                                  with the data I have analysed.             
                                  
                      - Question 8. Which sport is having most female Gold Medalists? (Top 5)
                       
                        My Answer: I have written the code to get the Women_Athlete who having no of gold medals and coverted it to dataframe as medal[medal=df[df['Medal']=='Gold']]     
                                  With the dataframe I Analysed the Women_Player who is having the most number of gold medals by converting them into 2d list of Women_Athlete and no of gold medals
                                  Then sorted it in reverse order with respect to values of gold medals.Then finally I plotted bar chart of TOP 5 Women_Player with most no of gold medals 
                                  with the data I have analysed.
                                  
                                  
                                  

                   Thank you for Reading this file, Have a Nice Day.....
About Me: I am KISHORE S, studying Bsc Computer Science Final year at C.Abdul Hakeem college ,I had started studying python basis during the covid period, 
then I Enhanced my skill by practicing code everyday and learning new methods amd concepts.
Now I have joined in Data Science in Tamil groups to enchance my skill further more with proper learning.

Contact Me: LinkedIn : https://www.linkedin.com/in/kishore-s-764031229

Email Id : kishorekrish0037@gmail.com
