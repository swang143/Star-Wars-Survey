# Star-Wars-Survey
While waiting for the movie, Star Wars: The Force Awakens, an interesting question we may want to ask is: “Which Star War movie is most popular and has the highest ranking?”  To solve our curiosity, the team at FiveThirtyEight has collected some data using SurveyMonkey, an online survey tool, to survey Star Wars fans and 835 responses were received. Respondents were asked:

‘Which of the following Star Wars films have you seen? Please select all that apply.’
‘Please rank the Star Wars films in order of preference with 1 being your favorite film in the franchise and 6 being your least favorite film.’

Other information was also collected, such as RespondentID, Gender, Age, Education, Location, Have you seen any of the 6 films in the Star Wars franchise?(Yes or No response) and so on. 

In this project, we did intensively data cleaning, including:
(1) Cleaning up Yes/No columns(convert string type to boolean type)
(2) Cleaning up checkbox columns(movie names and null value to boolean)
(3) Cleaning up ranking columns(string to numeric type)

We are then able to find the moive with the best ranking and saw by most people by calculating and plotting. We also analyze how different groups of people like each Star Wars movie by splitting the dataset into groups based on certain criteria, such as gener, education, location and whether they are a fan of the Star Wars movies.
