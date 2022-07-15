# Understanding and Optimizing DBpedia Question Answering through Explanations 
Hi guys, I am Udit Arora.<br /> 
I am glad to share that I have been selected for GSoC 2022 for the project: [Understanding and Optimizing DBpedia Question Answering through Explanations](https://summerofcode.withgoogle.com/programs/2022/projects/xMuRURaT).
I will work under the guidance of my mentors - [Andreas Both](https://www.linkedin.com/in/andreas-both-94267222/), [Aleksandr Perevalov](https://www.linkedin.com/in/alexander-perevalov-837780111/?lipi=urn%3Ali%3Apage%3Ad_flagship3_people_connections%3BU%2FpdNmPFSUqmoz82LyrZKA%3D%3D), [Ricardo Usbeck](https://www.linkedin.com/in/ricardo-usbeck/?lipi=urn%3Ali%3Apage%3Ad_flagship3_people_connections%3BQQw%2Bvv%2FvRwmEwkG30ZxSsQ%3D%3D), and [Ram Athreya](https://www.linkedin.com/in/ramgathreya/?lipi=urn%3Ali%3Apage%3Ad_flagship3_people_connections%3BQQw%2Bvv%2FvRwmEwkG30ZxSsQ%3D%3D) over the span of this project.
<br />
<br />

## Table of Contents
<a href="#community_period">GSOC Community Bonding period</a>   
<a href="#coding_period">GSOC Coding period</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weekone">Week One</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weektwo">Week Two</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weekthree">Week Three</a> <br /> 
<span>&#8226;</span> <a href="#coding_period_weekfour">Week Four</a><br /> 
<!-- <span>&#8226;</span> <a href="#coding_period_weekfive">Week Five</a><br />
<span>&#8226;</span> <a href="#coding_period_weeksix">Week Six</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weekseven">Week Seven</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weekeight">Week Eight</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weeknine">Week Nine</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weekten">Week Ten</a><br /> 
<span>&#8226;</span> <a href="#coding_period_weekeleven">Week Eleven</a><br /> 
 -->

<h3 id="community_period">GSOC Community Bonding period</h3>

I attended my first meeting with my mentors, other students who would be working on project under DBpedia, and their mentors. We all gave our introductions and share about the amazing and exciting projects that all of us would be pursing as a part of GSoC 2022. I enjoyed talking with everyone and am very excited and ready to start with the coding period for my project. <br> 

<h3 id="coding_period">GSOC Coding period</h3>

<h4 id="coding_period_weekone">Week one</h4>
I had a meeting with my mentors discussing more about my skills and about what tech-stack to we plan to use for the project.<br />
1) Decided on new usecases/examples on how the future chatbot system.<br />
2) Went through the current system and made a holistic picture of it on [Github](https://github.com/UditArora2000/GSoC2022_Question_Answering#:~:text=Visualization%20of%20the%20current%20QA%20system%3A).<br />
I created a Github repository and added the initial README.md file. I created a diagram of the current chatbot system using [Mermaid](https://mermaid-js.github.io/mermaid/#/).
3) Completed the [Dialogflow tutorial](https://cloud.google.com/dialogflow/es/docs/tutorials/build-an-agent) to learn about the implementation details.<br />
I learned about how to create and customize agents, how to create intents with parameters, and how to create fulfillment using webhook.
4) Read more on Function as a Service ([FaaS](https://www.sumologic.com/glossary/function-as-a-service/)).<br />
I got to know how it supports a server-less architecture and its impact on system scalability.<br /><br />

<h4 id="coding_period_weektwo">Week two</h4>
I had a meeting with my mentors where we dicussed the [issues](https://github.com/dbpedia/dbpedia-chatbot-frontend/issues/1) I would be working on this week.<br />
1) Evaluated the query "tell me an order of components list" and how it is handled by the current system.<br />
2) Composed SPARQL queries to extract entities recognized by the system<br />
I encountered a bug in my queries, which I hope to get resolved in the next meeting.<br />
3) Suggested new textual questions, that would help to enhance the user experience<br />
4) Tried to setup the chatbot locally on my system<br />
I encountered errors in connecting with the server where the chatbot is hosted. I hosted the chatbot on heroku to be added as webhook for the fulfillment on the Dialogflow agent.<br /><br />

<h4 id="coding_period_weekthree">Week three</h4>
I had a meeting with my mentors where we dicussed the [issues](https://github.com/dbpedia/dbpedia-chatbot-frontend/issues/4) I would be working on this week.<br />
1) Resolved the doubt in my SPARQL query with the help of my mentors during the meeting<br />
2) Tried to setup the chatbot locally with some fixes suggested by the mentors<br />
The app is still unable to reach the server<br />
3) Created three new intents on dialogflow based on the previously suggested textual questions<br />
<br /><br />