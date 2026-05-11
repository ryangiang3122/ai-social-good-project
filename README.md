# ai-social-good-project
Project 3 for 110A

Part 3
Who specifically is affected, and how? 

I think one person affected by this problem would be my grandma. She doesn’t speak English whatsoever so trying to submit a complaint or just trying to say anything in English would be a problem. So by creating this service, my grandma and other non English speakers can actually communicate.

What is the exact failure point? 

The problem is not that the city service doesn’t already exist. The problem is that residents who do not speak English well may struggle to submit complaints correctly or understand city responses. Also this is just a good way to translate in general.

Which AI capability addresses that failure? 

I am using text generation from Lab 1. Gemini can read a complaint, detect the language, translate the meaning, and generate a polite response in the same language.

What is the workflow?

Residents submit a complaint in Vietnamese, or another language.
The AI detects the language.
The AI translates the complaint into English for city staff.
The AI identifies the issue being reported.
The AI writes a short confirmation response in the resident’s original language.
A city worker reviews or processes the complaint.

What is the main ethical risk? 


The AI could mistranslate the complaint or misunderstand urgency. For example, if a dangerous road issue is treated as minor, repairs may be delayed and someone could get hurt. But still overall, a human should always review the report and the AI isn’t replacing anyone, just assisting their job.

	

Part 4
4.1 One Failure Case. 

A realistic failure occurs when a complaint involves both a physical issue like trash, and a human situation, like a homeless person sleeping behind a building. The AI system classified the complaint as a sanitation issue and routed it to the wrong department. This is a failure because the situation may require social services intervention, not just cleanup. A consequence of this would be that the homeless person probably couldn’t get the help they needed because the complaint was routed to the wrong department.

4.2 Oversight Decision.

I think one position where a human has to review before the AI is any complaint that is related to people or the safety of people. This is because as observed in the labs, if a prompt is too complex, even though the AI does a good job, it really can’t recognize some of the human elements in a prompt sometimes. So an actual human is needed to further consult the problem.

4.3 The One Change. 

I think adding a flagging system would be a good change to the problem in 4.1. If the prompt has multiple issues or unclear intent, the system would flag the report for further review instead of just automatically routing it. This reduces risk of misclassification and increases reliability of the system in complex cases. The tradeoff is that it does take longer and increases labor cost because someone has to manually review it instead of it being fully automated.
