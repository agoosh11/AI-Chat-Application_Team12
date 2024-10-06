# Sprint 1 Report (08/26/2024 - 10/5/2024)

## What's New (User Facing)
 * N/A Still mostly in research phase, the actual prototype building has not started.

## Work Summary (Developer Facing)
We successfully scraped a website's Knowledge Base which can be used for training the model we will build in the future. We have the said data in a structured SQL Table with the text data (content) and the keyword (title) which best describes what the content is about, for example a text that explains the basic overview is under the title 'overview'. We also have implemented a locally hostable Private GPT. 

## Unfinished Work
Although the GPT eventually (in 15 minutes) returns an answer to your query on a different training set it was trained in. We did not connect the PrivateGPT to the SQL Database. We decided instead to focus our time preparing for Sprint 2; which was to research vector store, and integrating Langchain. This was both due to the shortage of time, and also the unpracticality of connecting to a GPT that has a high system latency. 

## Completed Issues/User Stories
Here are links to the issues that we completed in this sprint:

 * https://github.com/agoosh11/AI-Chat-Application_Team12/issues/2
 * https://github.com/agoosh11/AI-Chat-Application_Team12/issues/3
 * https://github.com/agoosh11/AI-Chat-Application_Team12/issues/4
 * https://github.com/agoosh11/AI-Chat-Application_Team12/issues/5
 * https://github.com/agoosh11/AI-Chat-Application_Team12/issues/6

 ## Incomplete Issues/User Stories
 Here are links to issues we worked on but did not complete in this sprint:
 
 * https://github.com/agoosh11/AI-Chat-Application_Team12/issues/9 <<Not enough research time to implement the vector DB>>
 * https://github.com/agoosh11/AI-Chat-Application_Team12/issues/10 <<Waiting on Client to give us an API key, also dependent on havin vector DB first>>

## Code Files for Review
Please review the following code files, which were actively developed during this sprint, for quality:
 * [Team_12_PrivateGPT](https://github.com/agoosh11/AI-Chat-Application_Team12/blob/main/Team_12_PrivateGPT.ipynb)
 * [Ai Chatbot Notebook2.ipynb](https://github.com/agoosh11/AI-Chat-Application_Team12/blob/main/Ai%20Chatbot%20Notebook2.ipynb)
 * [ScrapedWebsite.csv](https://github.com/agoosh11/AI-Chat-Application_Team12/blob/main/ScrapedWebsite.csv) <<Has to be donwloaded to view, file too big for github>>
 
## Retrospective Summary
Here's what went well:
  * All the technical aspects went relatively according to our idea.
  * Team communication is fluent and relaxed.
 
Here's what we'd like to improve:
   * More cohesive responsibility, there is too much of a split and knowledge gap in what each of us are doing.
  
Here are changes we plan to implement in the next sprint:
   * Filter out the core functionalities and work on those together before branching out into our own responsibilities. Reduce modularity. 