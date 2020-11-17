# Methods
* This experiment evaluates the experience of the users using the Constable application. 
* Google Forms were used for getting feedback from the users.
* Since this application required permission for GitHub access, the users were asked about the how comfortable they were to give this access.
* The users were asked to fill out metrics for ease of use, readability, satisfaction and badge. 
* They were also asked to list the challenges they faced along with the things they liked and disliked about the application. 
* A google doc was created with instructions of how to run the application and with the feedback form.

# Materials
* Github
* Google Forms
* Cloud web hosting service - Heroku
* Communication Channel - Slack
* Google Docs


# Observations
### Safety Use
![Safe use](https://github.com/bhavesh242/constable-github-action/blob/main/assets/Q1.JPG)

From the pie chart we can see that 50% of the subjects did not find the application safe to use. One possible reason for this could be that the application requires requires permission for GitHub access and people are not very comfortable giving access of their GitHub account to a third party application. The subjects might have missed the fact that OAuth is used for authentication which ensures security. The other half of the subjects found the application fairly safe.

### Ease of use
![Application_Ease](https://github.com/bhavesh242/constable-github-action/blob/main/assets/Application_ease.JPG)

From the above chart, we observe that the application seems to be pretty easy to use as all the subjects found it moderate to very easy to use. In addition, 60% of the subjects found it very easy to use. This is expected because the application is just a click away and subjects had enough knowledge to use GitHub and new applications, hence the subjects might have found it easy to use.


### Readablility
![Readability Results](https://github.com/bhavesh242/constable-github-action/blob/main/assets/Results_Readable.JPG)

Readability here indicates the ease of reading the result given by the Constable. As, we can see from the above graph, we can see different users found the readability of the result to be different. This may depend on the underlying knowledge of the user on reading and understanding JSON objects.

### Satisfaction Scores
![Satisfaction Scores](https://github.com/bhavesh242/constable-github-action/blob/main/assets/scores_satisfied.JPG)

From the results obtained, it can be inferred that only a few testers (2 out of 10) were completely satisfied by the scores provided by the application. The main reason would be that Constable evaluates a repository based solely on the files and issues present. However, there are many more parameters to be considered such as code frequency, no. of contributors, no. of pull requests etc., and hence the scores provided by the application don't seem to be completely plausible.

### Likeliness of Adding Constable Badge to User's Repository
![Badge Likeliness](https://github.com/bhavesh242/constable-github-action/blob/main/assets/badge_likeliness.JPG)

From the stats above, it can be seen that there is a divided opinion on adding the constable badge to the repository. This is most probably because half of the users that want to add constable badge like the idea of constable and it's scoring whereas the other half of the users do not necessarily agree with the scoring formula's followed by the application. Some users may also not find the contable badge relevant to be added to their respective readme files.   

### Likeliness of Recommending Constable to User's Friends
![Recommendation Likeliness](https://github.com/bhavesh242/constable-github-action/blob/main/assets/recommend_constable.JPG)

60% subjects were likely to recommend Constable to their fellow programmer colleagues whereas 30% were neutral about this. This stat can be considered as a positive for Constable as general feedback from subjects suggests that with a few tweaks, the application has a lot of practical uses.

### Positive Feedbacks
* Most of the users liked the minimalistic, unambiguous User Interface of Constable. 
* Some users also mentioned that the setup-free online environment made constable a really usable application.
* The idea of having a badge was also popular amongst the positive feedbacks.

### Negative Feedbacks
* Almost every user complained about the JSON format of the results, which could have been easily converted to plain text. 
* Some subjects mentioned that they would have liked to know the criteria for scoring so that they could ensure their repos performed better.
* There was also some feedback on the slow nature of the website

# Threats to Validity
- The experiments were performed on only 10 subjects, which is very small sample space and hence we might not draw reliable conclusions.
- Since the subjects were from CSC510 class, they could be from same team and they might have tested the application using their common repositories resulting in duplicate observations.
- The subjects were all graduate student with mostly similar background/experience, hence results could be biased. Instead, if the sample space had (say) 3 college grads, 3 professors and 4 industry level specialists, our results would have been different and much more plausible given the diversity of the subjects.
-  The experiment was conducted asynchronously, hence subject might have filled the form without actually performing the experiment.
- It is possible that the subjects might have tested only repositories of similar quality and formed an opinion on the application resulting in misleading conclusions.
- Some subjects' opinions about the application were also affected by the slow nature of Heroku, which is essentially a free hosting service. Had Constable been hosted on a better hosting service - such as AWS or Cloud Flare, their opinions would have been more on the positive side.
