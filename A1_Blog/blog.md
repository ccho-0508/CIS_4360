
# Thoughts on : Innovation Insight for Microservices by Gartner

In the section defining microservices, the adjectives 'strongly encapsulated and loosely coupled' reminded me of React's design principle of creating applications with [specialized reusable components](https://reactjs.org/docs/design-principles.html)  so functionality can be added without affecting the entire app. I'm new to React, but using it has helped out immensely by keeping my code clean and manageable, so I can see the benefits of designing architecture with this principle in mind.

There were a lot of new words and concepts being thrown around I wasn't sure of, so I spent a lot of time watching videos and reading articles trying to understand the technologies and methodologies referenced. For the definition of DDD, the notes were helpful and I could see how its principles influenced microservices with the emphasis on the business functionality of a service rather than primarily focusing on the technology. I found this [video](https://www.youtube.com/watch?v=NNFJREcalc0&ab_channel=AlphaCode) which added to my understanding.

Amongst the key findings, it was recommended that delivery teams should practice many things, such as test-driven development. I'm learning about test driven development now, specifically unit testing, and I was curious as to how TDD would work out with microservices, and what behaviors would be tested. Unit testing can be quite tedious but extremely helpful in refactoring and improving overall design. I found an [article](https://nordicapis.com/using-test-driven-development-for-microservices/) on the company Cybus and the different testing strategies they used. They conclude with the note that business requirements direct TDD, and "privileging the customer story" results in features that are catered towards the user base, and thus the company. 

The service mesh was another concept I was unfamiliar with, but this [article](https://www.redhat.com/en/topics/microservices/what-is-a-service-mesh) helped me understand its use. It is separate from the services and it helps optimize communication between them so the they don't need built in communication logic. Developers can just focus on adding business value rather than connecting services. 

I found the granularity spectrum (micro, mini, and macro) and diagrams helpful in my understanding of how microservices are implemented in comparison to miniservices and macroservices, and how they can all be adopted according to the business needs. 

![](https://github.com/ccho-0508/CIS_4360/blob/master/A1_Blog/Granularity%20Spectrum.png)

With my first read through, even though I didn't understand all the terms, the report was clear on the risks and implications of a premature adoption of microservices. With another reading and research done on the terms I was unfamiliar with, I was able to develop a more nuanced understanding of the prerequisites listed to adopt MSA and the risks involved. 
