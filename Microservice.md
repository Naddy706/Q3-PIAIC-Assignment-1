# INTRODUCTION
The term "Microservice Architecture" has sprung up over the last few years to describe a particular way of designing software applications as suites of independently deployable services. While there is no precise definition of this architectural style, there are certain common characteristics around organization around business capability, automated deployment, intelligence in the endpoints, and decentralized control of languages and data.

# Why Microservices?
Companies like Netflix, Amazon, and others have adopted the concept of microservices in their products. Microservices are one of the hottest topics in the software industry, and many organizations want to adopt them. Especially helpful is the fact that DevOps can play very well with microservices.

# What are microservices?
Microservices structures an application as a collection of services that are
> 1. Highly maintainable and testable
> 2. Loosely coupled
> 3. Independently deployable
> 4. Organized around business capabilities
> 5. Owned by a small team

The microservice architecture enables the rapid, frequent and reliable delivery of large, complex applications. It also enables an organization to evolve its technology stack.

# Visual View OF Microservice

![Microservice-Architecture](https://user-images.githubusercontent.com/33847438/78710128-57515700-7904-11ea-9a77-2a9cd78b5f8b.png)

# 1. Highly maintainable and testable.
Highly maintainable and testable - enables rapid and frequent development and deployment. Loosely coupled with other services - enables a team to work independently the majority of time on their service(s) without being impacted by changes to other services and without affecting other services.

# 2. Loosely coupled.
Loosely coupled with other services - enables a team to work independently the majority of time on their service(s) without being impacted by changes to other services and without affecting other services.

# 3.Independently deployable.
Microservices should be independently deployable; if not, it probably means that there is some kind of coupling within our architecture that needs to be solved. If we could meet other principles but we fail at this, we are probably decrementing the benefits of this architecture.
Having the ability to deliver constantly is one of the advantages of the microservices architecture; any constraints should be removed, as much as we remove bugs from our applications.
We should take care of deployments from the beginning of the design of our microservices and architecture; finding a constraint on this area at late stages could have a big impact on the overall application.

# 4.Organized around business capabilities.
Organized around business capabilities – Microservices are not organized around technical capabilities of a particular product, but rather business capabilities. As the end goal is user experience and customer satisfaction, the teams leveraging microservices are not divided into UI teams, database teams and so on.

# 5.Owned by small teams.
Each service is owned by a team, which has sole responsibility for making changes. Ideally each team has only one service: Each team is responsible for one or more business functions (e.g. business capabilities). A team owns (has sole responsibility for changing) a code base consisting of one or more modules.