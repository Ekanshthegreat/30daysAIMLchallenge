recap Day 1:
must generate a label - automation

Agents can decide on that instead. Agent can adapt and decide when to retrieve and can use other availaible tools if possible
Agent swarm framework allows us:seperatre responsivbilities
    1. reduce hallucinations
    2. outsource more complex tasks
    3. system easier to scale

Multi-agent frameworks that i can use
    1. autogen by microsoft - (but limited conversational patterns)
agents hallucinate because no clear seperation of jobs

Crewai - introduces process into agent communication (built on langchain - no automatic typechecking or errorchecking)

AI Agent Use Cases - These can range from simple ones like setting reminders to more complex tasks such as managing a company’s entire operation through automation. 

By themselves, language models can't take actions - they just output text. A big use case for LangChain is creating agents. Agents are systems that use LLMs as reasoning engines to determine which actions to take and the inputs necessary to perform the action. After executing actions, the results can be fed back into the LLM to determine whether more actions are needed, or whether it is okay to finish. This is often achieved via tool-calling.

#Following this course roadmap
![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/coursecontent.png)

Generative AI Pipeline

1. Data acquisition (csv,txt,pdf,docs,xlsx) , db , internet, fetch thru api, scrapping

If augmenting data then less data ->  replace with synonyms

2. Data preperation

3. Feature Engineering
4. Modeling
5. Evaluation
6. Deployment
7. Monitoring and Model Updating
