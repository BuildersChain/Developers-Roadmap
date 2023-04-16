## What is DevOps?
DevOps is a methodology in the software development and IT industry. Used as a set of practices and tools, DevOps integrates and automates the work of software development and IT operations as a means for improving and shortening the systems development life cycle.

## 1 - Software Development Basics
As you are working closely with the development team to improve and automate tasks for them, you need to understand the concepts of:

* how developers work and
* what workflows they use,
* how they collaborate on developing features,
* the modern processes like agile and scrum,
* what Git workflow they use and

Now here it's important to mention that you don't need to be a software developer or the one implementing those agile and scrum processes. You need to understand how those things work on a high level, conceptually.

## 2 - Software Deployment
The next one is software deployment. Once the feature is developed, it needs to be released to the end users, which means you need an environment, where your application will be running and be available for the end users.

### 2.1 - Operating Systems & Linux Basics
And as a DevOps engineer you need to know how to provision and prepare these environments and
how to maintain them.
And for that you need knowledge of general server administration like creating virtual machines, mostly with Linux operating system, installing software, doing patches, configure networking on premise as well as on cloud.

### 2.2 - Containers with Docker
And as part of the more modern infrastructure concepts you need to understand how to work with containers and the most popular container technology, which is Docker.


### 2.3 - Container Orchestration with Kubernetes
And for projects with tens or hundreds of Docker containers you need to know how to work with container orchestration platforms like Kubernetes, which is the most popular one nowadays.



### 2.4 - Cloud - Learn 1 of the most popular cloud provider
If you're working on cloud like AWS, which is the most popular and most used cloud platform for now, you also need to know AWS specific services and how to manage the whole deployment infrastructure on AWS.

AWS Market Share
Source: Statista Cloud Infrastructure Market Share

## 3 - CI/CD - Continuous Integration and Continuous Deployment
And connecting all these pieces together and kind of the heart of the DevOps processes is CI CD pipelines.

How do you connect these two software development and deployment? In other words, when software is being developed, how do you deploy those developed features?

It's not just about deploying it to the deployment environment, we don't just take it and throw it on there. Why? Because humans make mistakes, either because of lack of knowledge in some area or just accidentally. So instead we add many gatekeepers before the deployment, so the deployed code needs to go through various of these gate checks in order to be allowed on the final environment and that's what the DevOps CI/CD pipeline is for:

* testing code,
* packaging it and
* deploying all the way to the end environment 
* to deliver it to their end users.
* CI/CD Pipeline

Now what are those gatekeepers? Well, testing the code quality, testing code logic, testing that it didn't break any previously existing code, checking for any security issues, testing that it functions as it's supposed to etc. So tools for implementing this whole CI/CD pipelines with all those gatekeepers is a super important skillset.

So knowing any CI/CD tools like Jenkins, Gitlab CI/CD, GitHub Actions, Circle CI and so on. And most importantly how to integrate this tool with all other technologies to test things, deploy the code and so on is very important.



## 4 - Monitoring and Observability
Now again we are humans and we can assume that even with the most cautious measures and a lot of extensive testing, we can't always 100% test every single aspect of the deployment and some issue may slip through in the production. That's why we have bugs in production and that's okay as long as we have a plan for handling a bug or issue when it appears in production.

So again a part of DevOps skillset is to create a process of handling discovered issues in production instead of having a panic mode. So what does that skillset include? Well, it's a thing called "monitoring and observability".

So in the last stage of CD or continuous deployment, after deploying the code changes, we don't just say: "hey we're done, that's deployed so now let's move on to the next task", instead we observe and monitor closely what happens. If some user encounters an error, if something crashes or doesn't work, so we know we need to proactively fix that. So maybe for a couple of hours or within the next days of deployment, we're actively looking and observing whether some kind of issue appears in production.



## 5 - Automation
And finally the last missing piece of really conquering DevOps is automating all this. 👏 So basically you automate most of your own work and work of other engineers, automating especially in areas where the same task needs to be repeated.

Let me give you some examples, for every new code released:

* you always need to test your application,
* you always need to check for security,
* you always need to package and
* deploy application changes.

These tasks should happen automatically, so you make sure to execute automated tests that developers or test engineers write, you have automated security checks, quality checks and you have scripts or automation code that deploys that code to the end environment:
CI/CD automates all human tasks

So you don't deploy the application locally from your own machine, but rather CI/CD pipeline deploys it automatically.

Another one is monitoring. Obviously you don't want to be sitting in front of a computer and observing and waiting to see if something breaks in the application, instead you want to deploy tools that monitor the application and notify you if something's off or if something happens:
Monitoring tools

So monitoring and observability tools go under your DevOps toolbelt as well.

### 5.1 - Infrastructure as Code
But in DevOps we don't stop there with automation, we also automate things that don't repeat on every code change deployment, but still prove to be incredibly efficient.

So for example provisioning infrastructure or setting up a Kubernetes cluster is not something you do very often but we still automate it in DevOps. Why? Because we want to be able to easily replicate our deployment environments if they get corrupted or if we need multiple staging environments, like DEV, TEST and PRODUCTION:
Infrastructure as Code

And generally having everything in code versus some manual scripts that some person on a team executes and no one knows about has many benefits:

First of all, encouraging collaboration in a team on infrastructure configuration
Documenting changes to infrastructure
Transparency of the infrastructure state and
Accessibility to that information in a centralized place versus being scattered around on people's local machines in the form of some scripts.
This is an infrastructure as code concept as part of the whole movement towards automating all workflows to make them more efficient.

And some of the most popular tools in this area are Terraform for Infrastructure Provisioning and Ansible for Configuration Management.


### 5.2 Scripting skills
While you don't need to actually program the application as a DevOps engineer (more to that later in the article), you will need some scripting or basic programming skills to automate various DevOps processes.

This can be simple shell scripting or even better a full-fledged programming language like Python. However, you don't need to be able to develop web applications with Python like a software developer. Being able to write automation scripts with Python is absolutely enough and is actually way easier to learn.

Some examples would be writing a shell script to do a task in a Jenkins job in a CI/CD pipeline or writing a small utility script for flushing the cache, starting the builds and deployments, connecting different tools etc.

There are many programming languages, but I would recommend starting with Python. Python is widely used, easy to learn and used for many different use cases, especially in DevOps. And the good thing is, programming concepts stay the same, so when you learn one language well, you can easily learn new ones quite quickly.



## 6 - Version Control with Git
You write all automation logic mentioned above as code.
And just like developers manage the application code with a version control tool, like Git, you need to manage this automation code and configuration files with a version control tool as well.

So these are the fundamental processes and respective tools that are part of DevOps. So any other DevOps tools you may come across - and there are hundreds of them - are simply optimizing or improving different parts of this workflow.

What is YOUR zero or starting point? 🤔
So having those DevOps skills is the final goal and you're starting from zero, but many of you are transitioning to DevOps or starting your DevOps journey having various different backgrounds. So the zero or that starting point is different for all of you and as I mentioned at the beginning you may be systems administrator or software engineer or QA engineer etc or may not have an IT background at all and want to transition into DevOps:
Different starting points when transitioning into DevOps

So now I want to show you how you can transition to DevOps and basically learn all these tools that I just mentioned starting from your specific background. ✅

Starting as a Systems Administrator 🧑🏽‍💻
If you are a systems administrator you know how to administer servers and other systems. So you already have some skills in:

setting up infrastructure
configuring and preparing it for deployment
so working with operating systems, installing and running software
security, networking configuration etc is already familiar for you.
Some of the other tasks you do as systems administrator are things like monitoring systems, health, backup and disaster recovery, installing and patching servers and so on.

In smaller projects you may have to also do database administration, network administration or security administration.

All of these are very useful skills, if you want to become a DevOps engineer. 👍 So you already have a lot of skills you can use in the deployment and operations side of DevOps:
Skills in deployment and operations part of DevOps

This includes Day 0 activities such as initial setup of the infrastructure, but also Day 1 tasks like maintaining and operating this infrastructure.

Many systems administrators also know scripting, so that will be helpful in the automation part of DevOps. So as a systems administrator you already have a very good foundation to get into DevOps, however the big part missing here to start in DevOps is learning the software development basics:

understanding the git workflows
how developers work and so on
Now very important to note, even though some DevOps engineers do know how to program, it's not an essential skill in DevOps, because as a DevOps engineer your main task is not developing and programming the application it's creating automated processes for delivering the developed software to the end users efficiently with as few bugs and issues as possible:
Process to deliver app to end users

But to be able to deliver the application changes, of course you need to understand how that application was built, developed and how it works.

Starting as a Software Developer 👩‍💻
If you are a software developer, again you have a pretty good background, because you already know an important part of DevOps, which is the software development processes and how these work.

But most probably you are missing skills in server management. So you need to start by learning about:

virtual machines
creating and configuring servers
configuring infrastructure security, networking etc
And since most modern applications run on cloud, you need to also learn how to do all these on cloud infrastructure.

So that would be your starting point when learning DevOps as a software developer.

And once you have that foundation you can build on that by learning about how containers work on top of the virtual machines and how to run applications in containers and how to run containers on a platform like Kubernetes etc.

And of course your programming skills will be great help in writing automated scripts for various parts of the application development and deployment processes. 👍

Starting as a Test Automation Engineer👨🏼‍💻
Another common background people have when transitioning into DevOps is a test automation engineer. Now here you may have a bit more catching up to do and more skills to learn compared to developers or systems administrators, but you can definitely reuse many of your skills in DevOps.

As a test engineer you most probably know how the software developers are working, like the agile processes, Jira workflows and so on. And as part of your test automation knowledge you understand the different testing scopes like

testing on code level
testing the whole application on a more abstract level
testing how the application integrates with other services etc.
You also understand how to test different aspects of an application and that knowledge is really helpful for setting up an automated CI/CD pipeline, because in order to automate the pipeline and streamline delivering your application changes all the way to the production environment, you need extensive automated testing:

Extensive testing for multi-stage deployments

Because as soon as you need a human element you will break the automated pipeline and add a bottleneck:
Manual process breaks automated pipeline

And since you know how to write automated tests in various programming languages, your skills in various testing frameworks is definitely helpful here for scripting and coding some automation parts of DevOps processes. Or let's say it won't be completely new to you. 👍

Starting as a Network Engineer🧑🏻‍💻
The last honorable mention of a background going into DevOps is network engineering. This is probably the farthest from DevOps compared to the other three that I just mentioned, but you still have some skills that you can bring into DevOps as a network engineer.

As a network engineer you know how to configure devices and networking between devices. So you have valuable knowledge in configuring networking for infrastructure on premise.

Transition to Cloud Network Engineer
But as most companies are moving their infrastructure to cloud, many network engineers transition to cloud network engineering:
Moving to cloud

So they do all of that on cloud platforms. And instead of configuring routes and switches and networks on on-premise infrastructure, they configure virtual routes and virtual switches and virtual networks on cloud infrastructure.

With networking and virtual networking knowledge you have an advantage to understand networking in virtual machines and containers, which is a big part of how modern applications are running. So it will be easier for you to understand Docker and Kubernetes networking for example and these are usually pretty difficult parts to manage and troubleshoot or secure, when you're configuring and maintaining the deployment environments with Kubernetes and containers on them.

So you can definitely use your knowledge and expertise in this area. Some network engineers even know scripting in bash or python for example, which is another helpful skill when it comes to automation part of DevOps.

DevOps Bootcamp considering these different backgrounds 💡
Now all of these backgrounds we actually considered when creating our DevOps bootcamp curriculum.

So we added the Linux Basics module, where you learn everything about Operating Systems and Linux as well as Networking, Bash scripting and so on. Everything from scratch:
Linux Module for Software Developers and Testers

So if you are a software developer or a test automation engineer, this will give you the prerequisite knowledge and foundation for learning things like provisioning deployment servers, configuring servers and preparing for deployment etc as well as how to administer some DevOps tools like Jenkins and Kubernetes cluster and so on.

Obviously as a system administrator you would skip that part, but instead you would need to learn Git and how to work with Git workflows, to use it for writing infrastructure as code for example. You also need to learn about build and packaging tools to package the applications written in various languages.

So as you see there are some prerequisites you need to have in DevOps and various backgrounds bring various of those prerequisites with them and we included those prerequisites as well for those missing them, but after those prerequisites are fulfilled the path pretty much looks the same for everybody, because tools like Kubernetes, Terraform, EKS, even Docker are pretty new to many professionals and there is no one profession that was specifically dedicated to those tools previously. So everyone needs to learn them no matter what their IT background is:

### DevOps Bootcamp

Starting with no or little IT background 🙉
Finally, we also get many questions about starting our DevOps Bootcamp with very little to no IT background. Which means there are probably many of you reading this article, who are thinking about getting into DevOps without much IT pre-knowledge and want to know what the path is to DevOps.

Now this is a very tricky one, because DevOps is NOT really the entry-level profession in it. It's not the first thing you learn when you want to get into the IT field.
Now why is that? 🤷🏻‍♂️ Because DevOps is about

automating processes and software development and deployment that people have done manually for a very long time.

This means before you automate processes and tasks that are done manually, you first need to understand what those processes and tasks are in the first place. If you don't understand those, you won't know what you're automating or why you even need DevOps.

## 1 - Understand complete software development lifecycle
So if you're completely new to IT and already know you want to eventually become a DevOps engineer, then you should start by understanding the complete software development life cycle first. And the good news is, it's easier than it sounds. You don't need to go and learn software development for months for that and you definitely don't need to become an expert in managing infrastructure and configuring servers.

If you learn the right things, you can actually do it in a relatively short time:
Go find some example projects, where you create a super simple application and learn how to deploy to a virtual server, so learning the steps of developing, packaging, maybe even automatically testing and then deploying an example application on a Linux server on a cloud platform.

This will actually be a very good foundational knowledge for building on it to learn DevOps. In this process

you will learn the basics of creating an application,
you will learn how to create a virtual machine with a Linux server on some easy to use cloud platform and host your application there.
And then repeat the whole process once more, simulating making an update to your application and this will teach you basic skills for each part of the software development process, but most importantly it will make you understand the complete workflow of what goes into that. 👀

You don't need any fancy tools for that, no Jenkins, no fancy programming framework, not even Git. Again these are to understand the basic concepts and then you can start learning those DevOps tools like Jenkins, Docker, Kubernetes and so on. Because this phase is not about learning the tools, it's about understanding the concepts and the complete workflow.

## 2 - How software development teams collaborate
After that go ahead and watch some tutorials about agile and scrum methods and how software development teams collaborate and work in software development projects.

## 3 - DevOps Pre-Requisites and 4 - DevOps Skills
And these skills will actually be enough to start our DevOps Bootcamp, because Linux, Git and all these basic tools you actually learn in our bootcamp from scratch. 🚀 But again you need to understand those workflows first in order to understand, why we're using Git, why we need Jenkins, why we're learning Linux and scripting etc.

And because of a lot of requests for our Bootcamp from IT beginners 🙈, we actually also decided to create a complete bootcamp prerequisites course. So if you're interested in that you can already sign up to get notified when the course is out 🔔: IT Beginners Course

So you can of course learn this as I said all by yourself following those steps and put a learning path together by yourself or you can use our prerequisites course when it's out.

Summary - DevOps Roadmap
So to summarize there are 4 phases:

#### 1 - Getting the pre-requisites right
First one getting the prerequisites right. So depending on which background and pre-knowledge you have, you need to first make sure to get any missing prerequisite knowledge.

So as a system administrator or a network engineer, learn the software development workflows. As a developer, learn the basics of infrastructure, virtual servers etc. Of course with zero IT background, you have to get all this prerequisite knowledge from server administration to development first. So you have a more difficult entry, but it is possible if you know what to learn.

#### 2 - Cloud, Docker, Kubernetes
Second step is learning cloud, Docker and Kubernetes. After learning the prerequisites, you can already get started with important DevOps skills of working with containers and container orchestration tools. So basically learning Docker and Kubernetes to help your teams deploy and efficiently run the application. Kubernetes itself is a very complex tool, so it may take some time to master it and make it production ready.

And since most of the modern applications and Kubernetes clusters are running on cloud, you need to learn cloud infrastructure, how to work with cloud infrastructure, how to configure it, how to scale it and so on.

#### 3 - Automation
The third step is automation. Once you have mastered the above skills and technologies it's time to learn how to optimize and automate the existing processes. And as a DevOps professional automation skills are one of the most important ones.

As the heart of DevOps, learning to build CI/CD pipelines is an essential skill.

And finally you will learn how to automate parts of the complete DevOps processes one by one using the concepts and tools of what's called X as code, including Infrastructure as Code, Configuration as Code, Security as Code, Policy as Code and so on, which basically means just automating everything in the form of code

#### 4 - Go from there. Keep learning 🙌
Number four is just go from there. DevOps is evolving and new tools are being developed all the time. So as a DevOps professional, you should learn how to evaluate and test many new tools, always with the same goal to optimize and automate existing processes and make them efficient.
