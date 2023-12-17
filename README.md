# Model-Lying
This project is to model lying from sound audio. Using logistic regression and wav files from lying audio and audio telling the truth from the same individual, predict if new audio from them is lying or telling the truth.

DESCRIPTION:
I’m trying to model if someone is lying or not from their voice. I’m going to be using a game called among us that has a group of people doing tasks. One person in the group is the imposter and is trying to kill off all the innocent people. In the game dead bodies can be reported and emergency meetings can be called. In these meetings players can discuss who the imposter is and possibly vote someone off who they think is the imposter. If the innocents complete all the tasks or report the imposter, they win and if the imposter kills everyone off in time they win. The importance of this game is that you can collect audio from someone and if they are the imposter you can for sure know they are lying and if they are innocent you can for sure know they are telling the truth. 

FEATURES USED:
Firstly the model uses the gaps in a persons voice. This is how many pauses the person has when speaking.
Secondly the model also uses average frequency. So it detects the common frequency you talk in when speaking. Then it can see the difference in frequency when you are lying or when you are telling the truth.
Finally the model uses how loud you are. It sees if you are on average louder or softer when lying or not lying.
