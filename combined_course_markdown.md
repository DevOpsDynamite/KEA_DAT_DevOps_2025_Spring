
# File: ICON_LICENSE.md

Silk icon set 1.3 by Mark James <mjames@gmail.com>

http://www.famfamfam.com/lab/icons/silk/

License: [CC-BY-2.5](https://creativecommons.org/licenses/by/2.5/)
or [CC-BY-3.0](https://creativecommons.org/licenses/by/3.0/)



# File: create_an_issue_template.md

## Create an issue template

**Type**: Group work

**Deadline**: If you have classes on Friday then feel free to commence with this assignment after the holiday. 

---

## The task

This is similar to the `Create a pull request template` assignment.

Create at least one issues template. First create a `ISSUE_TEMPLATE` folder in the `.github` directory.

You are free to define the templates that makes sense for you group. Example of template types:


- **Default Template Names:**

- `bug_report.yml`
- `feature_request.yml`
- `security.yml`
- `config.yml`
- `general.yml`

Learn more about issues here:

https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue




# File: how_are_you_devops.md

# How are you DevOps?

**Type**: Group work

**Part of Mandatory II**

---

## The assignment

Inspired by the guest lecture start writing down arguments for why you are DevOps.

Also write down what keeps you from being fully DevOps while reflecting on why. 



# File: read_devops_literature_II.md

# Read DevOps Literature II

**Type**: Individual

**Deadline**: Before the next week's guest lecture if possible. 

**Motivation**: Reading this ahead of the guest lecture will enhance your experience. Reading it after will still be beneficial. 

---

## What to read

The file is in Teams.

---

## The DevOps Handbook

The first chapter of the DevOps Handbook is full of insightful truths and multiple readings will uncover them. You will get 3 weeks to read this chapter since it is dense and full of information. Make sure to have read it before the guest lecture. I recommend going back on your own throughout the semester. 

Filename: `Chapter 1.pdf`

<img src="./devops_handbook.png" alt="DevOps Handbook"/>

---

## Reflect

Consider while reading the material, how your group applies these principles.

- Flow
- Feedback
- Continual Learning and Experimentation

Feel free to write them down in order to better remember them. 

<!-- ## The Phoenix Project - Excerpt

This is part of the novel about implementing DevOps at a fictional company where the protagonist "sees the light". 
It's meant to be a light read to show an interesting medium of conveying DevOps principles in. 
You are not expected to understand who the people are but in case you are curious:

Characters: 
- Erik: Mysterious and philosophical IT guru, guiding mentor.
- Chris: Diligent, competent Head of IT Operations.
- John: Overwhelmed, cynical, but skilled IT security manager.
- Steve: Stressed, results-driven, CEO of the company.

<img src="./the_phoenix_project.png" alt="The Phoenix Project"/>

Filename: `The Phoenix Project - Excerpt` -->




# File: detecting_agile_bs.md

# Detecting Agile BS

**Type**: Group work

**Motivation**: There is a lot of BS floating around when it comes to agile and DevOps. Can you detect it?

---

## The document

Go through the the Department of Defense's diagram of `Detecting Agile BS`. 

It can be found on the last page here:

https://media.defense.gov/2018/Oct/09/2002049591/-1/-1/0/DIB_DETECTING_AGILE_BS_2018.10.05.PDF

1. See if you can answer **yes** or **no** to the questions. Write down if you answer **No** to any of the answers. 

2. Compare notes. If anyone in your group has answered **No** to any of the questions then write down a plan so that you can answer yes in the future.




# File: mandatory_I.md

# Mandatory I

**Type**: The assignments are group work but you must hand it in individually

**Deadline**: Check Teams for the deadline. You hand in in Teams under assignments. If you miss the deadline you must upload the documents in the assignments channel in Teams. 

**Motivation**: You must hand in both mandatories individually to be eligible for the exam. 

---

## Requirements

These hand-ins serve as an opportunity for you to reflect. Focus on creating material that brings value to you and your group.

You are free to choose any (reasonable) format for the documents.

You are expected to be able to answer questions reflecting on the content and in certain cases we might look at the documents created. But do not spend too much time perfecting these documents. 

The links must be public. 

---

## The assignments

[Create a dependency graph](../01._Introduction/02._After/create_a_dependency_graph.md)

[Problems with the codebase](../01._Introduction/02._After/problems_with_the_codebase.md)

[Generate your own OpenAPI specification](../02._Conventions_OpenAPI_DotEnv/02._After/generate_openapi_specification.md)

[Choose a branching strategy](../04._Sofware_Quality_Linting_CI/02._After/choose_a_git_branching_strategy.md)





# File: mandatory_II.md

# Mandatory II 

**Type**: The assignments are group work but you must hand in individually

**Deadline**: Check Teams for the deadline. You hand in in Teams under assignments. If you miss the deadline you must upload the documents in the assignments channel in Teams. 

**Motivation**: You must hand in both mandatories individually to be eligible for the exam. 

---

## Requirements

These hand-ins serve as an opportunity for you to reflect. Focus on creating material that brings value to you and your group.

You are free to choose any (reasonable) format for the documents.

You are expected to be able to answer questions reflecting on the content and in certain cases we might look at the documents created. But do not spend too much time perfecting these documents. 

The links must be public. 

---

## The assignments

Reflect on how your group uses version control. Inspired by [Branching Strategy](../04._Sofware_Quality_Linting_CI/02._After/choose_a_git_branching_strategy.md) and other Git / Github related assignments. 

[How are you DevOps?](../07._Guest_Lecture/02._After/how_are_you_devops.md)

[Software Quality](../04._Sofware_Quality_Linting_CI/02._After/software_quality.md)

[Monitoring Realization](../11._Searching_Logging_Monitoring_Serverless/02._After/monitoring_realization.md)

---

### [Optional] Postmortem

Create a summary of an incident postmortem you've made. You are encouraged to create multiple postmortems but focus on only one of your choosing. 



# File: begin_dockerization.md

# Begin Dockerization

Dockerize backend / frontend.

**Type**: Group work

---

## Start Dockerization

This assignment is for experimenting with how to Dockerize the language of your choosing. Create a new branch and play around with it. Next week you will build upon this task with `Docker-compose`.

Depending on if the frontend is served by the backend you might end up with 1 or 2 separate containers for the application.

---

## The Database Problem

The goal after next week is to publish the images to a public registry. Because it has to be public, it disallows you to include the SQLite database in the image.

You must figure out how to securely get the file on the production server and use it without leaking it to the public.

There are many ways to approach this interesting problem. Discuss it well with your group and consider the pros and cons of each approach.




# File: docker_from_scratch.md

# [Highly_Optional] Docker from scratch

Code along to the tutorial or you can simply watch it.

**Type**: Individual

**Motivation**: If you personally need to see the inner workings to understand something better, this might aid you. 

---

## Docker in Go

The Golang standard library come with functions that allow us to interact with the Linux kernel. It is very easy to get started. Docker is written in Go. 

Follow-along tutorial:

[![Building a Container from Scratch in Go - Liz Rice (Microscaling Systems)](http://img.youtube.com/vi/Utf-A4rODH8/0.jpg)](https://www.youtube.com/watch?v=Utf-A4rODH8)

Written tutorial:

https://www.infoq.com/articles/build-a-container-golang/

---

## Pocker - Docker in Python

https://github.com/Zakaria-Ben/Pocker

---

## Bocker - Docker in Bash

https://github.com/p8952/bocker/tree/master



# File: setup_postman_monitoring.md

# Setup Postman Monitoring

Monitors will run in Postman Cloud and send you emails if the tests fail.

**Type**: Group work

---

## Create collection

You must create a collection in Postman first. A collection is a group of requests.

<img src="./assets_postman_monitoring/create_collection.png">

https://learning.postman.com/docs/getting-started/first-steps/creating-the-first-collection/

---

## Create a request

Click on the "+" button to create a new request and for now write a placeholder request URL. I wrote `localhost:8080/api/movies`.

---

## Save request

Click on the `💾 Save` button on the top right corner of the request.

Give it a name and assign it to the collection.

<img src="./assets_postman_monitoring/save_request.png">

---

## Set variables

Highlight the URL and tool tip will pop up with a `Set as variable` button. Click on it.

<img src="./assets_postman_monitoring/set_variables.png">

Create a BASE_URL and PORT variable and set the scope to the collection.

---

## Edit variables

You can edit variables by clicking on the `...` icon on the upper left side (the collection drawer) and selecting edit.

Choose the `Variables` tab and edit the variables.

<img src="./assets_postman_monitoring/edit_variables.png">

---

## Create tests

On the request page, click on the `Post-response` in the `Scripts` tab:

<img src="./assets_postman_monitoring/create_tests.png">

You can optionally watch the API test segment of the video below to learn more:

## [![Postman Beginner's course](http://img.youtube.com/vi/VywxIQ2ZXw4/0.jpg)](https://youtu.be/VywxIQ2ZXw4?t=3772)

## Write a test

In the snippets on the right side select `Status code: Code is 200`;

```javascript
pm.test("Status code is 200", function () {
  pm.response.to.have.status(200);
});
```

---

## Run the test

Send the request and select the `Test Result` tab in the lower bottom (the response part).

<img src="./assets_postman_monitoring/run_test.png">

---

## Improve the test

```javascript
pm.test("Status code is 200", function () {
  pm.response.to.have.status(200);
});

pm.test("Response time is less than 200ms", function () {
  pm.expect(pm.response.responseTime).to.be.below(200);
});

pm.test("Response body is present", function () {
  const body = pm.response.json();
  pm.expect(body).to.include("data");
  pm.expect(body.data).to.be.an("array");
});
```

<!-- ---

<div class="title-card">
    <h1>Runners</h1>
</div>

---

## Collection runner

A runner automates running a collection of requests instead of having to run each of them manually.

You can find the runner in the the bottom right corner of the Postman app.

<img src="./assets_postman_monitoring/runner_button.png">

---

## Adding the collection to the runner

Simply drag the collection from the collection drawer to the runner.

<img src="./assets_postman_monitoring/adding_collection_to_runner.png">

---

## Run the runner

Click on the `Run` button in the runner (bottom right).

---

## Automate Run

<img src="./assets_postman_monitoring/automate_run.png">

---

# Schedule run

You can schedule a run to run at a specific time and send you emails if the tests fail.

Postman cloud runs the tests for you and you don't have to setup a server.

<img src="./assets_postman_monitoring/schedule_run.png">


---


## Schedule CI/CD - I

You can run a runner in CI/CD. For instance, you can make test that all the routes are working before deploying to production.

Or you could immediately role back in production in case of a failed test.
6
<img src="./assets_postman_monitoring/schedule_CICD.png">

---


## Schedule CI/CD - II

Click on `Configure command` and you will be able to get a snippet and instruction on how to add the code to your CI/CD pipeline.

<img src="./assets_postman_monitoring/copy_CICD_code.png"> -->

---

# Monitors

---

## Enable Monitors

Click on the icon below `history` in the left side and enable Monitors.

---

## Create a Monitor

Click on `Monitors` on the left sie and selct `Create a Monitor`:

<img src="./assets_postman_monitoring/create_a_monitor.png">

Give the monitor a name, select the collection.

---

## Run the monitor

<img src="./assets_postman_monitoring/run_monitor.png">

---

## [Optional] Consider creating a team to enable collaboration

https://web.postman.co/purchase?quantity=1&utm_source=postman&utm_medium=app_desktop&utm_term=upgrade&utm_content=navbar

Beware that free teams have an account of up to 3 members.

It is fine not to create a Postman team and just have one person be in charge of the Postman monitoring.

---

## What now?

Now that you have tried to create a monitor for a single test, you can consider writing duplicated tests in `Post-response` for the collection.

https://learning.postman.com/docs/tests-and-scripts/write-scripts/intro-to-scripts/

As an example, if getting a status `200` for all requests is expected then you can put the test as a `Post-response` instead of pasting it onto each endpoint.



# File: refresh_docker_knowledge.md

# [Optional] Refresh Docker knowledge

A treasure trove of resources to refresh your Docker knowledge.

**Type**: Individual

---

## Requirements

This task has been marked optional since some of you are confident in your Docker knowledge (based on the self-assessment survey). 

The requirements are that this will help you get more confident in Docker as a concept and working with Docker files. Docker-compose isn't covered until next week.

Some of you had nice introductory hands-on tutorials from last semester. Let me know if you want me to share Erik's with the entire class. 

---

## Docker Introduction

Fast-paced introductory Fireship video introducing Docker concepts:

[![101 Computer Science and Docker Concepts](http://img.youtube.com/vi/rIrNIzy6U_g/0.jpg)](https://www.youtube.com/watch?v=rIrNIzy6U_g)

Another great Fireship video that takes you through everything from the concept, to defining and running containers:

[![Learn Docker in 7 Easy Steps - Full Beginner's Tutorial](http://img.youtube.com/vi/gAkwW2tuIqE/0.jpg)](https://www.youtube.com/watch?v=gAkwW2tuIqE)

Feel free to code along with the videos.

If you prefer text, this blog post is very concisely written:

https://www.learncloudnative.com/blog/2020-04-29-beginners-guide-to-docker/

---

## The Dockerfile

Overview of all the possible values in Docker:

https://docs.docker.com/reference/dockerfile/

---

## Hands-on practice

[This interactive website](https://training.play-with-docker.com/) explains concepts and provides a terminal to practice in. It can be a bit tricky to find how to get started, from [this page](https://training.play-with-docker.com/dev-stage1/) but the first tutorial can be found by clicking further from this page:

https://training.play-with-docker.com/ops-s1-hello/

You have found it, if you are seeing something that matches this screenshot:

<img src="./docker_classroom.png" alt="docker classroom learn interactive">

It requires you to sign in with your Docker account. If you don't already have on, here is your chance to create one. 

Docker swarm is not part of the curriculum, but if you are interested in it, you can try out that section as well.

---

## Bonus: Cheat sheets

I have placed some cheat sheets in the repository:

[Docker cheat sheet](./docker_cheatsheet.pdf)

[Docker cheat sheet - PhoenixNAP](./docker-commands-cheat-sheet.pdf)

---

## Bonus: Learn about the different Linux directories

Only if you are interested and have the time:

https://www.youtube.com/watch?v=42iQKuQodW4

---

## Further reading

The official documentation:

https://docs.docker.com/




# File: the_simulation.md

# The simulation

Get ready for the simulation. 

**Type**: Group work

---

## Overview

There are two pieces deployed. The simulator and the plot server.

<img src="./assets_the_simulation/the_simulation.png" alt="the simulation setup">

The **simulator**:

1. Simulates a user interacting with the website.

2. Logs responses and potential errors. 

The **plot server**:

1. Creates a weekly and total plot of how many errors have been logged per group. 

2. Gives you access to the logs for debugging. In principle this should not be necessary as you will suceed as long as you follow the OpenAPI specification. 


---

## The Simulator

The simulator also simulates a growing interest in your product. As the semester progresses, the number of users will increase. But expect this to grow in an organic and realistic way. 

---

## The simulator - Max expected response times

Adhering to a good rule of thumb, the maximum acceptable response times are as following:

| Route        | Maximum Response Time (seconds) |
|--------------|---------------------------------|
| /            | 10                              |
| /search      | 10                              |
| /weather     | 10                              |
| /register    | 10                              |
| /login       | 10                              |
| /api/search  | 6                               |
| /api/weather | 6                               |
| /api/register| 10                              |
| /api/login   | 10                              |
| /api/logout  | 6                               |

If a user experiences higher response times, then they will leave the site.

---

## The plot server

You will find the IP address to the plot server pinned in the `#general` channel in Teams.

Remember not to push the IP address to your repositories. 

Accessing it on port `8000` might give you a view like this:

<img src="./assets_the_simulation/plot_server_landing_page.png" alt="plot server landing page">

You can savely ignore the `/logs/date/last`. It is a heartbeat function used to monitor if both the simulator and the plot server are up and running.



# File: keep_rewriting.md

# Keep rewriting

**Type:** Group work

---

## Keep going

We will do a trial run on the simulation next week.

It would be optimal if you could have implemented all the routes by then (but not necessarily the internals). 



# File: deploy.md

# Deploy!

Time to deploy your application. 

**Type**: Group work

---

## Requirement

You must deploy your application to the cloud. Feel free to use any cloud provider you like.

You must deploy to a Virtual Machine or similar. Services like Web Apps etc. are great and easy to use, but it removes your chance to learn and reach the course goals.

Since the simulator will expect a fixed IP address, you should deploy with static IP.

---

## PR to `repositories.py`

Once you have deployed, create a PR to [repositories.py](/repositories.py). The relevant part to replace is:

```python
            "backend": "http(s)://<IP_DOMAIN>/<APIURL>",
            "frontend": "http(s)://<IP_DOMAIN>/<FrontEndURL>",
            "stack": ["Flask", "Svelte", "CouchDB", "Redis"],
```

Backend and frontend could be the same IP address. 

The `<APIURL>` and `<FrontEndURL>` parts are optional. For instance, if you prepend all your API with `v1`. The endpoints should be accessible given the values + the endpoints as defined in the OpenAPI specification.

Updating the stack is a great idea, since it allows you to connect with other groups using the same technology if you are stuck. You are encouraged to do so. 

Remember to make sure that your forked repository's state is up to date with the original repository before making your pull request.

Next week, we will do a trial run before starting the simulation for real. 



# File: azure_oddities.md

# Azure Oddities

This is not an assignment, but a document for odd behavior experienced in Azure.

---

### Can't work with Azure external to Azure

**Issue**: Getting problems with Service Principal authentication.

**Symptoms**: Can't authenticate Azure in GitHub Actions or can't work with others in the same Azure portal.

**Cause**: KEA has checked off the ability to allow external interaction with Azure. This is done because of concerns for GDPR. It takes a checkbox in order to enable it, but it requires a thorough security assessment also.

**Resolution**: There's nothing that can be done as the security department is blocking us.

---

### The VM was shut down 

**Issue**: VM was shut down by Azure.

**Symptoms**: The VM is no longer accessible.

**Cause**: Though no official source confirm that Azure has a policy of shutting down inactive VMs several students have reported this issue. It usually happens if the VM has been idle for X amount of weeks, for instance during the exam preparation period. It could very well be a KEA Azure policy.

**Resolution**: Start the VM again.

---

### VM restart removes port rules

**Issue**: VM restart cleared all port rules from the network interface.

**Symptoms**: SSH inaccessible after reboot.

**Cause**: Port rules were not persistent across restarts.

**Resolution**: Manually re-add required port rules post-restart.

---

### Can't log in to Azure

**Issue**: Can't log in to Azure. 

**Symptoms**: Stuck in a loop of getting a "More information required" screen. Clicking next shows "Success!" but hitting "Done" returns to the "More information required" screen.

<img src="./assets_azure_oddities/authenticator_error_1.png" alt="Authenticator error 1" />

<img src="./assets_azure_oddities/authenticator_error_2.png" alt="Authenticator error 1" />

**Cause**: A previously authenticator app is no longer valid.

<img src="./assets_azure_oddities/authenticator_error_3.png" alt="Authenticator error 1" />

**Resolution**: Go to https://mysignins.microsoft.com/security-info and delete the authenticator app. Then log in again.

---

<!-- ### 

**Issue**:

**Symptoms**: 

**Cause**:

**Resolution**:

-->


# File: azure_cost_managment.md

# [Highly_Optional] Azure Cost Managment

**Type**: Individual

**Motivation**: Azure can drain all your credit before you can blink and in suprising ways. Always monitor the budget. It can be found under subscriptions. 

---

## Introduction

Some of you have already received a similar document in the 3rd semester. 

The content here is not strictly necessary if you are only using Azure for Students but it's still good knowledge to carry into your work life.

Scroll down to [Final words](#final-words) for useful tips.

---

## Set limitations on your spendings

It is only possible to set limitations on a Pay-As-You-Go subscription. Azure For Students accounts have a cap of $100 and do not allow users to set up additional alerts. 

---

### Pay-As-You-Go

In case that you have your credit card associated to the account then the following steps are recommended. 

With a pay as you go subscription you should **ALWAYS** set a limit on your spendings.

The way to set limitations on Azure is by creating a `budget`.

1. First, go to your subscription.

2. Then, open "**Budgets**".

<img src="./assets_azure_cost_management/step_1.png" alt="subscription budget menu">

3. On your budget page, you will be able to see the different limits you have set.

4. To create a new budget, click "Add".

<img src="./assets_azure_cost_management/step_2.png" alt="subscription budget menu">

5. This will bring you to a page where you can specify details about the new budget, as an example, I have set up the following:

<img src="./assets_azure_cost_management/step_3.png" alt="subscription budget menu">


6. The budget above sets a limit of kr.- 10 per month.

7. After entering your requested details, click "next" at the bottom of the page

8. On the next page, you must specify "alerts" or warnings given when reaching your limits

<img src="./assets_azure_cost_management/step_4.png" alt="subscription budget menu">


9. The example given above will setup the following warnings:
- Warn If 10% of the budget has been used.
- Warn If Azure predicts that 50% or more will be used during the "Reset period".
-   Warn If 80% of the budget has been used.

10. If any of the warnings is triggered, an email will be sent to <your_email>@stud.kea.dk".

11. When everything has been set up, just click "Create" at the bottom of the page.

---

## Final words

As much as possible, use `Azure Free Services`. Search for it and it should appear.

<img src="./assets_azure_cost_management/azure_free_services.png" alt="free services">

Delete things you don't need. Services that are stopped will still cost money. This includes resource 

Beware that a resource group still consumes credit even if there is no service associated with it. This can be surprisingly costly.






# File: read_about_github_actions.md

# Read about GitHub Actions

**Type**: Invdividual

**Motivation**: Learn the correct terminology surrounding GitHub Actions.

---

# Read this

Read this documentation page on GitHub Actions: 

https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions

It's okay if you don't understand everything in the first try. Feel free to revisit the page later on in the course. 





# File: github_pr_template.md

# GitHub Pull Request template

**Type**: Group work

**Motivation**: To ensure that all pull requests are created in a consistent manner and that all necessary information is provided.

---

## How to create a PR template in Github

Create a file called PULL_REQUEST_TEMPLATE.md in .github.

Everyone in the group should agree on a template. 

Try to create a PR and see if the template is working.

---

## Tip regarding notifications

Change notification settings to avoid getting a ton of emails:

https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/configuring-notifications#choosing-your-notification-settings




# File: upgrade_the_database.md

# Upgrade The Database

For scalability and performance reasons, the SQLite database no longer cuts it.

**Type**: Group work

---

## Choosing the right database

You are free to choose NoSQL or relational databases. Your chioces should be informed and based on the business domain and the data model of `whoknows`. (Not personal preference).

If the choice is between PostgreSQL and MySQL your choice for a modern stack should without a doubt be PostgreSQL. Here are a plethora of reasons why:

https://www.datacamp.com/blog/postgresql-vs-mysql

---

## Github Discussions

Following the DevOps principle of showing your work the discussions regarding ORM and migration tools should be made public on Github Discussions.

https://github.com/features/discussions

You could use the voting feature to vote for the ORM and migration tool you would like to use. Remember that making a benchmark repository and testing out the tools is the best way to approach this, even if you don't implement it in the final project.


---

## Where to put the database

The problem with PostgreSQL and other databases is that they take up a lot of resources on the VM if placed with the rest of the application. 

There are many ways to solve this issue. You *are* allowed to use a managed database service.

But your solution should consider not only scalability but also cost.

---

## [Optional] ORM

It is not a requirement to use an ORM. 

Unless your goal is to learn to use an ORM in the respective language the argument should be that given you know how basic the data modeling of the application is, an ORM would be the wrong choice for this project.

**Requirement**: What is a requirement is that you must research ORMs.

---

## [Optional] Migration

As opposed to the ORM task setting up a migration tool is a good idea but still not a hard requirement. A migration tool can help you with:

1. Changes to the schema. Propagating the change for the developers or in production.

2. Migrating data from SQLite to the new database.

3. Backing up the database. (Better solutions might exist here depending on your chosen database).

To the best of your ability, try to avoid downtime while migrating to a new database.

**Requirement**: What is a requirement is that you must research migration tools and even if you don't use any you should have a clear plan for which you would go with and how it would work.



# File: let_them_search.md

# Let them search

Users are crazy about your product and wish that they could search for more content than just programming. 

**Type**: Group work

**Deadline**: See the [Suggested Timeline](#suggested-timeline) section.

**Motivation**: Use logging to understand how users are actually using your system -> Learn to scrape and index webpages. 

---

## Requirements

Use logging to get insight into what users are searching for. Use that knowledge to know what content to scrape.

Scrape and index webpages by adding them to a database. It doesn't have to be the same database as the one for your users. 

---

## Suggested timeline

Here is a proposed timeline:

1. **Week 1**: Brainstorm how to web scrape. Try out different tools. Agree on a tool.

2. **Week 2**: Log to see what the users are searching for.

3. **Week 3**: Scrape the content and index it. Deployment is optional: Decide whether to run the script locally or on a server. 

---

## Web crawling scope

You will not be able to scrape the entire internet and you must select few websites. 

You should log the searches to see what the users are searching for.

You will not be evaluated by the scale of your indexing operation but the scalability of your solution. 

---

## How to log?

Do not overengineer this task.

To implement a serious log stack such ELK is time consuming and requires a lot of resources such as memory. The same for other industry standards like Datadog. 

Logs can be achieved simply by writing lines to a file or INSERT statements in a SQLite database. Next week, we will talk about formats for logging.

Look into leveraging the logging system in your framework / language if it requires minimal work. For instance, `.NET Core` has an excellent built-in logging system.




# File: indexing.md

# Indexing

**Type**: Group work

**Motivation**: Creating indexes will enhance your performance several. 

---

## The task

Create indexes where you see it fit on the database you are using.

This can be done in both relational and NoSQL databases.

---

## [Optional] Measure the performance boost

It would be interesting to measure the performance before and after the indexes.

This could also be evident by your Postman monitors depending on the thoroughness of the tests. 

Keep this number and feel free to bring it up during the exam presentation. 



# File: whoknows_variations_database.md

# WhoKnows Variations Database

**Type**: Individual

Check out the docker-compose setup for PostgreSQL and learn about ORMs and migration tools in python.

---

## The Resource

https://github.com/who-knows-inc/whoknows_variations/tree/database_postgresql

`sqlalchemy` is used as the ORM.

It's a great opportunity to also learn about migrations and seeing how `alembic` does it. 

---

## Other resources

You could also get inspired by the [Awesome Compose](https://docs.docker.com/samples/postgres/) PostgreSQL examples.

They also provide an example for [Nginx, Flask, and MySQL](https://github.com/docker/awesome-compose/tree/master/nginx-flask-mysql).



# File: try_elk_logging.md

# [Optional] Try ELK logging

Try out logging with the ELK stack.

**Type**: Individual

**Motivation**: This is a quick task. Just run the docker-compose up and check it out.

---

## Awesome Compose sample

Awesome compose has a sample for the ELK stack.

https://github.com/docker/awesome-compose/tree/master/elasticsearch-logstash-kibana


---

## Change ports if you are on a Mac

If you are on a Mac then port `5000` is in use by AirPlay.

You can change the exposed port to a different port. Change this part of the `docker-compose.yml` file:

```yaml
    ports:
      - "5000:5000/tcp"
      - "5000:5000/udp"
```

To port `6000` for instance:

```yaml
    ports:
      - "6000:5000/tcp"
      - "6000:5000/udp"
```

---

# Running it

Run it with:

```bash
$ docker compose up -d
```

And you can access and verify the status of each service in your browser with (as mentioned in the `README.md` file):

* Elasticsearch: [`http://localhost:9200`](http://localhost:9200)
* Logstash: [`http://localhost:9600`](http://localhost:9600)
* Kibana: [`http://localhost:5601/api/status`](http://localhost:5601/api/status)

Additionally, you can access Kibana in your browser with:

* Kibana: [`http://localhost:5601`](http://localhost:5601)



# File: monitoring_realization.md

# Monitoring realization

**Type**: Group work

**Part of Mandatory II**

**Motivation**: The end-goal of monitoring is to make you see a new dimension of your system. 

---

## The task

Write a small section on something that your monitoring made you realize and fix. 

The way to quantify successful metrics gathering is if it gives you a grand realization.



# File: monitoring_PR.md

# Monitoring PR

**Type**: Individual

**Deadline**: Before the last week's lecture

---

## The task

In the [repositories.py](/repositories.py) file the following key-value pair exists:

```python
"monitoring_dashboard_url": "http(s)://<IP/DOMAIN>/<MonitoringURL>"
```

Please update the value of the key `monitoring_dashboard_url` with the URL of your monitoring dashboard.

---

## Access / Credentials

You can choose to either have:

- A public dashboard

- A dashboard that requires a login

In the latter case I will share credentials on Teams and you should create a user with those credentials. 

All groups will get the same credentials.

I encourage you to check out each other's dashboards but please do not break anything.




# File: monitoring.md

# Monitoring

**Type**: Group work

**Motivation**: Understand your system better in order to identify the pain points and improve it.

---

## Requirements

You have already setup health monitoring with Postman monitoring and while health monitoring of the system is fine, your focus should be to gather telemetry from users. Take on the role as a DevOps detective that asks questions in order to investigate how your system is being used and how it is bringing value to the users.

During the exam I will ask you to explain why you choose to monitor the metrics that you did. Though only a single person could set up monitoring I suggest that each group starts this assignment with a meeting where you discuss what to monitor for.

It's an impressive sign if your setup makes you realize something that helps you improve your system. Feel free to bring it up in the final presentation.

---

## Prometheus Client Libraries

Just like with everything else, the only requirement is that you must have monitoring. Not to do it specifically with Prometheus. But Prometheus is a good choice. It offers official client libraries for many languages: 

  * Go
  * Java or Scala
  * Python
  * Ruby
  * Rust

Unofficial third-party client libraries:

  * Bash
  * C and C++
  * Common Lisp
  * Dart
  * Elixir and Erlang
  * Haskell
  * Lua for Nginx and Tarantool
  * .NET / C#
  * Node.js
  * OCaml
  * Perl
  * PHP
  * R

For more information see: https://prometheus.io/docs/instrumenting/clientlibs/

Once Prometheus can extract metrics, Grafana or similar can use Prometheus as a data source and is agnostic to the programming language. 

---

## [Highly_Optional] Alerts

It is possible to setup alerts in Grafana. You can make it work with KEAs teams by setting up a webhook. This is done by clicking on the apps button and selecting `Incoming Webhook`. Grafana can then post alerts to in the Teams channel.

---

## Docker Example + PR request

In the [Docker Docs](https://docs.docker.com/samples/prometheus/) own example, they have defined configuration in `datasource.yml` for Grafana and a `prometheus.yml` for Prometheus. It can be found [here](https://github.com/docker/awesome-compose/tree/master/prometheus-grafana)

If you have a breakthrough in your monitoring setup that you are proud of you can either:

1. Expand the `whoknows_variations` tutorial with a new section and make a PR.

2. Reach out to me and I will consider adding it to the tutorial.

---

## Document your dashboards

The simulation will be run again before the exam to repopulate your graphs with data.

To be on the safe side, take screenshots of your dashboards during the semester for the exam.

---

## After thought

It is sufficient to setup only one dashboard for the course but beware that in companies the better practice is to create a dashboard per service (frontend, backend, database etc.).



# File: server_telemtry.md

# Gather telemetry about the server via the terminal

**Type**: Group work

**Motivation**: You might learn something critical about the server and its performance.

---

## Introduction

The goal of this assignment is not to create a monitoring setup but to try out different commands to gather information about the server.

---

## Monitoring CPU usage

```bash
$ top
top - 14:24:42 up 13 days, 23:42,  1 user,  load average: 0.00, 0.00, 0.00
Tasks:  85 total,   1 running,  46 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.3 us,  0.3 sy,  0.0 ni, 99.3 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
KiB Mem :  1009172 total,   187524 free,    98916 used,   722732 buff/cache
KiB Swap:        0 total,        0 free,        0 used.   728164 avail Mem

  PID USER      PR  NI    VIRT    RES    SHR S %CPU %MEM     TIME+ COMMAND
29200 root      20   0   44540   4112   3520 R  0.3  0.4   0:00.04 top
    1 root      20   0  159928   9500   7056 S  0.0  0.9   0:10.70 systemd
    2 root      20   0       0      0      0 S  0.0  0.0   0:00.01 kthreadd
    4 root       0 -20       0      0      0 I  0.0  0.0   0:00.00 kworker/0:0H
```

---

## Load

```bash
$ uptime
 15:50:34 up 14 days,  1:08,  1 user,  load average: 0.00, 0.00, 0.00
```

---

## Monitoring Memory

```bash
$ free -m
              total        used        free      shared  buff/cache   available
Mem:            985          96         183           0         705         711
Swap:             0           0           0
```

---

## Excessive memory consumption

Finding if a program was killed by `OOMKiller` (Out of memory) due to excessive memory consumption:

```bash
$ grep -i -r 'killed process' /var/log/
$ dmesg | grep -i 'killed process'
```

---

## Monitoring the Network

```bash
sudo apt-get install iftop
sudo apt-get install nethogs
```

```
$ iftop
                12.5Kb          25.0Kb          37.5Kb          50.0Kb    62.5Kb
└───────────────┴───────────────┴───────────────┴───────────────┴───────────────
webserver                  => nat-10.XXX.XX              4.34Kb  4.57Kb  4.55Kb
                           <=                            2.23Kb  2.23Kb  2.21Kb
webserver                  => 67.207.67.3                   0b      0b     48b
                           <=                               0b      0b     81b
webserver                  => static-28.108.248.49-tata     0b      0b     16b
                           <=                               0b      0b     21b
webserver                  => 185.156.73.54                 0b      0b      8b
                           <=                               0b      0b     16b





────────────────────────────────────────────────────────────────────────────────
TX:             cum:   49.2KB   peak:   6.25Kb  rates:   4.34Kb  4.57Kb  4.62Kb
RX:                    28.0KB           4.23Kb           2.23Kb  2.23Kb  2.33Kb
TOTAL:                 77.2KB           9.73Kb           6.58Kb  6.80Kb  6.95Kb
```

```
$ nethogs
NetHogs version 0.8.5-2

    PID USER     PROGRAM                    DEV        SENT      RECEIVED
  29948 root     sshd: root@pts/0           eth0        0.757       0.490 KB/sec
      ? root     ...225.103.230:21-104.206              0.000       0.000 KB/sec
      ? root     ...225.103.230:4071-45.13              0.000       0.000 KB/sec
      ? root     ...225.103.230:23-75.165.              0.000       0.000 KB/sec
  28239 do-age.. ..pt/digitalocean/bin/do-  eth0        0.000       0.000 KB/sec
      ? root     unknown TCP                            0.000       0.000 KB/sec

  TOTAL                                                 0.757       0.490 KB/sec
```

---

## Disk

```bash
$ df -h
Filesystem      Size  Used Avail Use% Mounted on
udev            481M     0  481M   0% /dev
tmpfs            99M  620K   98M   1% /run
/dev/vda1        29G  4.9G   25G  17% /
tmpfs           493M     0  493M   0% /dev/shm
tmpfs           5.0M     0  5.0M   0% /run/lock
tmpfs           493M     0  493M   0% /sys/fs/cgroup
/dev/vda15      105M  3.6M  101M   4% /boot/efi
tmpfs            99M     0   99M   0% /run/user/0
$ du -h
```




# File: kpi.md

# KPI (Key Performance Indicators)

**Type**: Group work

**Deadline**: Before next class

---

## The task

I have been contacted by a venture capital fund. Some of their investors have shown interest in becoming angel investors in your company. 

They have requested a basic report on the KPIs of your application.

* CPU load on the server.

* Total amount of users.

* Cost of the infrastructure / complete setup (monthly and/or total so far).

* [Optional] Total amount of active users.

* [Optional] Average amount of searches per day.

Bring them to class next time and be prepared to answer how you calculated these values.



# File: whoknows_variations_monitoring.md

# Whoknows Variations Monitoring

Understand the example with Prometheus and Grafana as a dashboard. 

**Type**: Individual

---

## The resource

Have a look at the repository and read the tutorials:

https://github.com/who-knows-inc/whoknows_variations/tree/monitoring

Try to understand the moving parts. Feel free to run it and write down questions. 

We will run it again together in class. 



# File: consider_a_deployment_strategy.md

# Consider a Deployment Strategy

**Type**: Group work

**Motivation**: In your current setup, deploying would mean that your system is down while Docker restarts the containers. Consider a better deployment strategy.

---

## Agree on a deployment strategy

Discuss with your group the various deployment strategies from the lecture or other sources.

Consider how to improve the current setup to achieve high availability, fault tolerance and scalability.

Feel free to bring this up during your exam presentation and be ready to answer what considerations informed your decision.

**To be clear**: It is not expected that you implement this in your project.




# File: take_down_your_system.md

# [Optional] Take down your system

**Type**: Group work

**Motivation**: Cement your know-how on what it took to set up your system.

---

## Additional motivation

Notice that this is an **Optional** assignment. However, I still recommend that you do it. Maybe the group could take out a day to sit together and do this.

The course requirement is that the system must be running during the exam. 

Since the exam could be much later than the last lecture and because of limited amount of credit it might be a necessity. 

But even if credit is no problem, you could still try to recreate the entire setup from scratch in parallel to the system that you have running.

Doing it a second time is how you go from vaguely remembering and forgetting over time to mastery. 

---

## **Important** if you used the `one.com` coupon

Delete your domain at `one.com` after the exams. 

At some point afterwards, they will send you an invoice if you continue to use the domain and give you a small window to cancel the domain. This should usually not be a problem, but you might miss the mail to your KEA account while you are in the middle of your internships.




# File: service_level_agreement.md

# Service level agreemnent

**Type**: Group work

**Motivation**: Provide a SLA to promote your system with its guaranteed availability.

---

## SLAs vs. SLOs vs. SLIs

Learn about the difference between SLAa/SLOs/SLIs. Here are some optional resources:

https://www.atlassian.com/incident-management/kpis/sla-vs-slo-vs-sli

https://cloud.google.com/blog/products/devops-sre/sre-fundamentals-sli-vs-slo-vs-sla

---

## Service Level Agreement

You must create a service level agreement. It must be published. 

**Advice**: As highlighted in the links above, don't overpromise; especially not for new systems. Professional SLAs incorporate a compensation mechanism that offers payouts. These payouts escalate in accordance with the duration of downtime surpassing the agreed-upon thresholds.

The SLA should contain:
 
* **Service Scope**: Defined services, features, and processes.

* **Performance Metrics**: Key performance benchmarks (uptime, response time).

* **Response and Resolution**: Expected times for incident handling.

* **Security Measures**: Defined protections.

* **Compliance Standards**: Required regulations.

* ~~Compensation Scheme: Penalties for not meeting metrics.~~

Compensation scheme is crossed out for obvious reasons, but kept to show that professional SLAs usually include it.

Feel free to be inspired by these: https://cloud.google.com/terms/sla/

---

## [Optional] SLO / SLI

Additional, create a SLO and/or SLI.


# File: docker_swarm_tutorial.md

# [Highly_Optional] Docker Swarm Tutorial

**Type**: Individual

---

## The resource

Even if Docker Swarm is deprecated and now included as a plugin in Kubernetes, this tutorial is a pleasant introduction to the world of orchestration. 

https://training.play-with-docker.com/swarm-mode-intro/


# File: create_a_dot_github_repository_for_your_organisation.md

# [Optional] Create a .github repository for your organisation

Style your organisation's profile by creating a `.github` repository.

**Type**: Group work

**Motivation**: Create a nice frontpage for your organisation.

---

## Explanation

A .github repository is a unique type of repository. Its `README.md` will be displayed on your organisation's profile page.

You can also define a `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `ISSUE_TEMPLATE.md`, `PULL_REQUEST_TEMPLATE.md` that become valid on all repositories in your organisation.

Here is an article to get you started and help you understand the different files that can go in there:

https://www.freecodecamp.org/news/how-to-use-the-dot-github-repository/

It misses the `SECURITY.md` file. Here is the work of a former KEA student that has it all, including an alternative way of defining the README.md inside of the `profile` folder:

https://github.com/CardMesh/.github/tree/main

Assess which of the files you need and create them.



# File: readme_badges.md

# [Optional] Create a GitHub Badge for your GitHub Actions

*DevOps principle: Show your work!*

**Type**: Group work

---

## What are badges?

Badges can be added to the repository's README to visualize various things.

In this assignment, you will create a shield for a workflow so that you can see the status of it when looking at the frontpage of your repository. This makes sense for the CI task of this week. 

---

## Get started

To help you get started, place this template in your `README.md` file to show the status of a GitHub Action:

```markdown
![<TEXT ON SHIELD>](https://github.com/<ORGANIZATION>/<REPOSITORY>/actions/workflows/<WORKFLOW_FILENAME.yml>/badge.svg?branch=main)
```

Replace:

- `<TEXT ON SHIELD>` with the text you want to display on the shield (A good name would be the name of the workflow)
- `<ORGANIZATION>` with your organization's name
- `<REPOSITORY>` with the name of the repository that the GitHub Action is defined on
- `<WORKFLOW_FILENAME.yml>` with the **exact** name of the workflow file as it appears in the `.github/workflows` directory. 
- `?branch=main` is optional and can be removed to show the status across all branches. In this example only the status of the main branch will be shown. 

---

# Generate a workflow status badge through the Github UI

You can also select a specific workflow execution in the actions tab and click on the three dots and `Create status badge` to generate a badge.

<img src="./assets_readme_badges/generate_workflow_status_badge.png" alt="github actions workflow status badge">

---

# [Optional] SuperLinter badge

Here is how you can create a Superlinter badge for your repository.

https://github.com/marketplace/actions/super-linter#add-super-linter-badge-in-your-repository-readme

---

# [Optional] Shields.io for more badges

Shields.io is a service that lets you create advanced custom badges:

https://shields.io/

For instance, you could use it to showcase the stack you are using. Check out the repository if you are interested:

https://github.com/badges/shields



# File: software_quality.md

# Analyze software quality

Add maintainability and technical debt estimation tools to your projects and fix the most prominent issues.

**Type**: Group work

**Deadline**: Same as Mandatory II. Even though software quality is important, you can add this task to your kanban and do it later if you are swamped with higher priority tasks.

**Motivation**: Improve code quality and avoid technical debt.

---

## Task

These tools will analyze your code and provide you with a maintainability index and an estimation of the technical debt. 

They will also point out potential problems. You do not have to fix everything. But prominent issues that you agree on, should be fixed from now on.

They will also become part of your CI pipeline and you should try to keep the quality metrics high as you push new code. 

Remember that from the lecture the learning goal should be to think critically about these tools. 

---

## SonarQube

The easiest way to get started with SonarQube is to use SonarCloud which is a readily available hosted version of SonarQube.

1. Navigate to https://sonarcloud.io/ and click the `Start Now -->` button. [Start Using SonarCloud](https://sonarcloud.io/) and login via GitHub.

2. Login via GitHub. 

3. Add a new project by clicking the `+` sign on the top right of the window followed by `Analyze new project`.

4. Select the repository or the repositories that you want to assess.

If you are interested, you can learn more about how SonarQube calculates metrics [here](https://docs.sonarqube.org/latest/user-guide/metric-definitions/#header-4).

---

## Code Climate

1. Navigate to https://codeclimate.com/quality and click the `Sign up with Github` button.

2. Choose `Sign up with Github` again. 

3. Select the repositories that you want to assess.

---

## DeepSource

1. Navigate to https://deepsource.io/ and click the `Quickstart with` + the GitHub button.

2. Authorize deepsource.io and follow the instructions to set it up.

---

## Requirement for Mandatory II

After you have setup a these code quality tools and gone through the issues, your group should create a brief document that answers the following questions:

  - Do you agree with the findings?

  - Which ones did you fix?

  - Which ones did you ignore?

  - Why?

Simply showcasing software quality tools for the exam as the source of truth about your project is the wrong way to approach it during the exam. The above questions are meant to help you develop and remember your reflections on the tools you used. 




# File: branch_protection_rules.md

# Branch protection rules

**Type**: Group work

**Deadline**: No fixed deadline. 

---

## Introduction

This is an extension of the `research git branching strategies` assignment. With this assignment, you can enforce some rules regarding your chosen strategy. 

## What are branch protection rules?

Branch protection rules can, for instance, help secure the main branch so that it doesn't get accidentally broken.

Learn more about them here:

https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/managing-a-branch-protection-rule


## How to setup a branch protection rule

In this example, the rule requires at least two people to review a pull request before being able to merge with main.

1. **⚙️ Settings**: Navigate to your repository on GitHub. Click on the "Settings" tab at the top.
2. **🌿 Branches**: In the settings menu, find and click on the "Branches" menu located on the left side.
3. **🔒 Branch Protection Rules**: Scroll down to the "Branch protection rules" section.
4. **✏️ Edit**: Find the branch you want to set rules for and click on "Edit" (or "Add rule" if you're setting this up for the first time).
5. **🔀 Require a Pull Request Before Merging**:
    - Check the option "Require a pull request before merging".
    - 🧑‍⚖️ **Required Number of Approvals**: Set the "Required number of approvals before merging" to **`2`**.
6. **✅ Require Status Checks**:
    - Check "Require status checks to pass before merging".
    - 🔍 **Search and Select Status Checks**: Search for the specific status checks you want to require and select them.
7. **💾 Save**: Once you're done setting up your rules, don't forget to save the changes.


## What other rules could be helpful?

Branch protection rules can help you enforce passing tests, limit who can push to a branch and more.


# File: linting.md

# Linting

Enhance your CI pipelines with a static analysis tools.

**Type**: Group work

**Motivation**: Improve code quality with linting

---

## Considerations

Consider whether you want to ensure linting before anyone can push their code or make it part of a CI pipeline or both. 

---

## Tools

How to approach this task highly depends on the language you are using.

Here is a great collection of tools for every major language:

https://github.com/mre/awesome-static-analysis

You could (additionally) consider SuperLinter:

https://github.com/marketplace/actions/super-linter




# File: consumer_report.md

# Consumer Report!

A consumer report has revealed a change in the market! 

**Type**: Group work

**Deadline**: Before the simulation next week. If you are pressed for time, just create the route that returns the correct response type and solve this task at a later date. 

---

## Description

Consumers have become highly interested in the weather recently. Create a weather page that displays the forecast. 

---

## Motivation

This is an excellent opportunity to: 

1. Integrate with a 3rd party service. 

2. Test the integration as part of your pipelines later on.

---

## Considerations

Research services that provide weather forecasts. Consider limitations such as cost and allotted API calls over a certain timeframe.

Decide on how to integrate with the service. Frontend or backend? Are any of the choices problematic in your setup? 

Consider scalability. How would you handle a large number of users without burdening the service? You don't have to solve anything here, but you should have a plan for it.

Consider limitations (allotted API calls over a certain timeframe) and how to possibly cache the result at a fixed interval. 

<details> 
  <summary>Spoiler to the scalability question</summary>
   Hint: Caching
</details>

---

<!-- todo future: consider creating a competition / graph for that group whose forecast is the most accurate  -->


# File: whoknows_variations_continuous_integration.md

# [Optional] Whoknows Variations Continuous Integration

Learn about different tools for linting in Python and see an example of linting in Github Action. 

**Type**: Individual

---

## Description

This task is optional, since linting in Python might not be relevant for you. But it's a good introduction to the `whoknows_variations` project. 

You can inspect the code and check it out or you can run it/fork it if you feel like it.

Here is the correct branch for this task: 

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_integration



# File: choose_a_git_branching_strategy.md

# Choose a git branching strategy

**Type**: Group work

**Part of mandatory I.**

---

## Exam requirement

For the exam your group will be expected to have picked a workflow and branching strategies.

Every group member should be able to talk about the chosen version control strategy and reflect on the pros and cons.

--- 

### Document for the mandatory

Create a document for the mandatory that answers the following questions:

- What version control strategy did you choose and how did you actually do it / enforce it?

- Why did your group choose the one you did? Why did you not choose others?

- What advantages and disadvantages did you run into during the course?

Feel free to revise the document even after deadline with new insights during the course.





# File: create_a_merge_conflict.md

# [Optional] Create a merge conflict

Try to create a merge conflict on purpose and learn how to resolve it. 

**Type**: Individual

**Motivation**: By learning how to create a merge conflict, you will understand why they happen and what situation causes them.

---

# Create a merge conflict - Step 1

Create a new folder and initialize it as a repository:

```bash 
$ git init
```

Create a new file with content:

```bash 
$ echo "Hello world" > example.txt
```

Add and commit the file:

```bash 
$ git add example.txt
$ git commit -m "Initial commit"
```

---

# Create a merge conflict - Step 2

Create a new branch:

```bash 
$ git checkout -b merge-conflict-branch
```

The new branch will have the file and content of the main branch.

Make changes in the new branch to the same file, same line:

```bash 
$ echo "Hello from feature branch" > example.txt 
$ git commit -am "Update message in feature branch"
```

---

# Create a merge conflict - Step 3

Checkout the main branch:

```bash 
$ git checkout main
```

**Status check**: So we have a file with different content in the main branch and the feature branch.

We want to have different content in the same line of the same file.

This is what will cause a merge conflict because git does not have a strategy for resolving this.


```bash 
$ echo "Main is changing the first line of example.txt" > example.txt 
$ git commit -am "Changed first line of example.txt"
```

---

# Create a merge conflict - Step 4

We are now going to merge the feature branch into the main branch.
    
```bash 
$ git merge merge-conflict-branch
```

This is the message:

```
Auto-merging example.txt
CONFLICT (content): Merge conflict in example.txt
Automatic merge failed; fix conflicts and then commit the result.
```

---

# Create a merge conflict - Step 5

There are many smart graphical tools for resolving merge conflicts.

Doing it manually is also an option. This is what the file looks like:

```
<<<<<<< HEAD
Main is changing the first line of example.txt
=======
Hello from feature branch
>>>>>>> merge-conflict-branch
```

Delete everything until there is only one line left (the one you want to keep or the combination of the two you want).

That's it! Now you can commit the changes.

---



# File: research_git_branching_strategies.md

# Research Branching strategies

**Type**: Individual

**Deadline**: Will be useful to have a good overview ahead of the lecture and be ready to discuss it with your group and implement one after. 

**Motivation**: This assignment will help you with the task that follows the lecture, which is to choose a branching strategy.

---

## General Research

This is a daunting task. Everyone is required to research the topic so that the group can make an informed decision. I have tried to mark things as required / not required to make time management easier. 

Here is a long course on Git. You are not required to watch this video but do jump around and see if there are any interesting concepts and terminology you can gain from it:

[![Git for Professionals Tutorial](http://img.youtube.com/vi/Uszj_k0DGsg/0.jpg)](https://www.youtube.com/watch?v=Uszj_k0DGsg)
---

## Branching strategies resources

Good overview with pros and cons for each strategy:

https://www.geeksforgeeks.org/branching-strategies-in-git/

Look at these pages:

https://www.atlassian.com/git/tutorials/comparing-workflows
https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

**Recommendation**: poke around in the Atlassian documentation and read what catches your eye and seems useful. 

Github Flow:

https://docs.github.com/en/get-started/using-github/github-flow


Trunk Based Development:

https://trunkbaseddevelopment.com/


---

## Merging vs. Rebasing

Really nice visuals to explain Git Merge vs. Rebase:

[![Git Merge vs. Rebase: Everything you need to know](http://img.youtube.com/vi/0chZFIZLR_0/0.jpg)](https://www.youtube.com/watch?v=0chZFIZLR_0)

From the video:

<div>
    <img src="./assets_research_git_branching_strategies/git_merge_vs_rebase_vs_squash_commit_pros_cons.png" alt="Git merging vs. rebasing the great debate"/>
</div>


Try out rebasing! You could follow this guide (the video has really nice visuals):

https://www.themoderncoder.com/a-better-git-workflow-with-rebase/


Another nice video with great hands-on explanations (you are not required to watch it):

[![Git Merge vs. Rebase](http://img.youtube.com/vi/CRlGDDprdOQ/0.jpg)](https://www.youtube.com/watch?v=CRlGDDprdOQ)

---

## Additional links

If you find a nice resource that you found enlightening then make a PR. 



# File: define_github_secrets.md

# [Optional] Define GitHub Secrets

Learn various ways to define GitHub secrets and how to invoke them in your workflow file.

**Type**: Individual

---

## Prerequisites

This assumes that you have gh installed and configured from the lecture. 

Installation from here: https://cli.github.com/

Log in with:

```bash
$ gh auth login
```

---

## Create a test repository

For convenience `gh` will be used to create and later on delete the repository. 

```bash
$ gh repo create
```

Go through the steps and choose what makes sense to you. 

---

## Define secrets in the GitHub UI


1. **🖥️ Go to Your Repository**: First, navigate to your GitHub repository where you want to add the secret.

2. **⚙️ Settings**: Look for the "Settings" tab at the top of your repository page and click on it.

3. **🔐 Secrets**: On the left-hand side menu, you'll see a list of options. Find and click on "Secrets".

4. **➕ New Secret**: You will see a button labeled "New repository secret". Click on it to add a new secret.

5. **🏷️ Name Your Secret**: In the "Name" field, type **`MY_NOT_SO_SECRET`**. This will be the reference name for your secret.

6. **🔑 Add Secret Value**: In the "Value" field, enter the secret content you want to store. Usually this would be things to keep private, like API keys, tokens, etc. For this exercise just write a short message that isn't secret. 

7. **💾 Save**: After you've entered the secret, click the "Add secret" button to save it.

8. **🎉 Done!**: Your secret is now saved and can be used in your GitHub Actions workflows.

---

## Using the secret in the workflow

In `github/workflows` create a new file called `echo_secret.yml` and add the following content:


```yaml
name: Echo Secret

on: [push]

jobs:
  echo_secret:
    runs-on: ubuntu-latest
    steps:
      - name: Echo Secret
        run: echo "Secret is ${{ secrets.MY_NOT_SO_SECRET }}"
        env:
          YOUR_SECRET: ${{ secrets.MY_NOT_SO_SECRET }}
```

This accesses the secret `MY_NOT_SO_SECRET` and echos it. By echoing it, you can see the secret in the logs.

Once you define a secret you can never read them in the UI. If you forget, you will have to rotate them. 

And you should never expose the secret like the example above. This is a toy example to show how it works. 

---

# Define secrets with `gh`

Running `gh` in the relevant repository, you can always do the following:

```bash
$ gh secret list
```

And you can set a new secret. 

```bash
$ gh secret set <MY_NOT_SO_SECRET>
```

For automation, you could consider doing the following:

```bash
$ gh secret set <MY_SECRET_NAME> < <path_to_secret_file>
```

---

## Clean up

To delete the repository, run:

```bash
$ gh repo delete
```

That's it. You have now learned how to define GitHub secrets and use them in your workflow.




# File: github_issue_template.md

## Create an issue template

Create an issues template. This mirrors the `github_pr_template` assignment. 

**Type**: Group work

**Motivation**: If you have a standardized way to create issues, you will have better defined tasks in your Github Project. 

---

# How to create an issue template

Create a file named `ISSUE_TEMPLATE.md` inside of the `.github` folder. 

Define a template for issues and try to create a new issue. 

This will provide a template for people looking to create issues (bugs, feature requests etc.).

https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue




# File: docker_compose_continuous_delivery.md

# Docker Compose + Continuous Delivery

Set up Docker Compose for your project and implement continuous delivery.

**Type**: Group Work

**Deadline**: There is no rush to finish this assignment. Let other tasks of higher priority take precedence.

**Motivation**: This is a great leap towards continuous deployment.

---

## Dev vs. Prod

Based on the lecture look into how to achieve hot-reloading for your server for development. 

Consider creating a separate setups for dev and prod for Dockerfiles and potentially docker-compose.

Consider how to securely load environment variables.


# File: whoknows_variations_continuous_delivery.md

# Whoknows_variations Continuous Delivery

Learn how to publish Docker packages to Github Packages. 

**Type**: Individual

**Motivation**: Even if your group does not chose to publish Docker images, knowledge and experience about container registries is valuable.

---

## Nice information about Github Packages

The official Github Packages documentation: 

https://github.com/features/packages

Really great video:

[![GitHub Packages](http://img.youtube.com/vi/gqseP_wTZsk/0.jpg)](https://www.youtube.com/watch?v=gqseP_wTZsk)

---

## The tutorial

You can try out the tutorial by forking the repository and following the instructions in the `README.md` file and the individual tutorials in the `continuous_delivery` branch.

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_delivery

---

## After the tutorial

Once you have tried out the tutorial, discuss with your group how you want to approach continuous delivery. There are many options here and be open to change your approach later in the course.




# File: workflow_strategies.md

# Research and pick a workflow strategy

**Type**: Do this assignment individually (the research part) and then make a group decision on how you want to collaborate. 

For the exam your group will be expected to have picked a workflow and branching strategies.

During the exam you will be expected to be able to explain your choices and reflect on pros and cons about the specific choice in comparison with others. 

---

### General Research

You are not required (but recommended) to watch this video but do jump around and see if there are any interesting concepts and terminology you can gain from it:

https://www.youtube.com/watch?v=Uszj_k0DGsg

---

### Workflow Research

**Required**: Read these pages:

https://www.atlassian.com/git/tutorials/comparing-workflows
https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

And poke around in the Atlassian documentation and read what catches your eye and seems useful. 

Here is a good summary of pros and cons:

https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy

Here is an article on trunk-based development and why you should avoid long-lived branches. You don't have to agree with it, but it's food for thought:

https://www.thoughtworks.com/insights/blog/enabling-trunk-based-development-deployment-pipelines


---

### Merging vs. Rebasing

Really nice visuals to explain Git Merge vs. Rebase:

https://www.youtube.com/watch?v=0chZFIZLR_0

From the video:

<div>
    <img src="./git_merge_vs_rebase_vs_squash_commit_pros_cons.png" alt="Git merging vs. rebasing the great debate"/>
</div>


**Required**: Try out rebasing! You could follow this guide:

https://www.themoderncoder.com/a-better-git-workflow-with-rebase/


Another nice video. You are not required to watch it:

https://www.youtube.com/watch?v=CRlGDDprdOQ

---

### Additional links

If you find a nice resource that you found enlightening then make a PR to this file. 




# File: read_devops_literature_I.md

# Read DevOps Literature I

**Type**: Individual

**Motivation**: We will discuss DevOps during the lecture and you will get the chance to ask any questions you might get while reading the material.

---

# What to read

The files can be found in Teams in the General channel. 

---

## The DevOps Handbook

<img src="./devops_handbook.png" alt="DevOps Handbook"/>

---

## History

Filename: `History.pdf`

Provides the historical angle of DevOps. Briefly covers different movements, why they were needed, and what they were trying to solve.

---

## Myths

Filename: `Myths.pdf`

Tries to dispel common myths about DevOps.

Start reading from "*The goal of writing this book* [...]" and continue to the end.


---

## Read DevOps Literature II

Note that there is more reading material for before the guest lecture next week. It can be found [here](../../07._Guest_Lecture/01._Before/read_devops_literature_II.md).

I consider the task of reading the literature before the guest lecture to be of a higher priority to the Continuous Delivery assignment. 


# File: refresh_docker-compose.md

## Refresh Docker Compose

Different resources to refresh or learn important concepts about Docker Compose.

**Type:** Individual

**Motivation**: This will leave your prepared you for the lecture.

---

## Tutorial with Flask

Follow this tutorial and read along:

https://docs.docker.com/compose/gettingstarted/

---

## Networking

Great page to understand networking in Docker Compose:

https://docs.docker.com/compose/networking/

---

# Volumes vs. Bind Mounts

Read the beginning of these two links and skim the rest:

https://docs.docker.com/engine/storage/volumes/    

https://docs.docker.com/engine/storage/bind-mounts/


---

## Check out the possible values for the `docker-compose.yml` file

Especially the `Services top-level element` section. 

You don't have to read it all but just click around and read what catches your attention:

https://docs.docker.com/reference/compose-file/



# File: generate_cr_pat.md

# Generate CR PAT

**Type**: Individual

**Deadline**: Before the next week's guest lecture. 

---

## How to generate a CR PAT

https://github.com/who-knows-inc/whoknows_variations/blob/continuous_delivery/tutorials/02._Generating_CR_PAT.md

---

## Deadline

We will use the CR PAT during the lecture. If you want to follow along during class then solve this assignment.

Remember to write it down somewhere and have it ready.


# File: 100+_docker_concepts_you_need_to_know.md

# 100+ Docker Concepts you Need to Know

**Type**: Individual

**Motivation**: This fast-paced video will give you another opportunity to refresh Docker concepts. 

---

## The Fireship video

[![100+ Docker Concepts you Need to Know](http://img.youtube.com/vi/rIrNIzy6U_g/0.jpg)](https://www.youtube.com/watch?v=rIrNIzy6U_g)



# File: git_release.md

# Git Tagging and Release

Create your first release. 

**Type**: Group work

Feel free to create multiple releases this week. One for checking in the legacy code and one after working on it. 

You are encouraged to create new releases moving forward for every major milestone in your development.


## Create a release on GitHub

It is very easy to create a [release in GitHub](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository). 

1. Click on `Create a new release` on the right side of your repository. This is also where you releases will be accessible.

<img src="./github_release/github_release_1.png" alt="github release">

2. First you must `+ Create new tag`. You are encouraged to use [semantic versioning](https://semver.org/) for tagging. `v.0.1.0` would be a good start.

<img src="./github_release/github_release_2.png" alt="github release">


3. Click on the “Generate release notes”. 

Release notes can be [automatically generated by GitHub](https://docs.github.com/en/repositories/releasing-projects-on-github/automatically-generated-release-notes
). It uses a mixture of PRs, issues, commit messages, tags, contributors and labels. This is why you should always have clear commit messages that explain what has happened.

4. Click on `Publish release` and you are done.


## Tag using git

In the above example the tag is created using GitHub's interface. It's also possible to create a tag using git: 


```bash
$ git add -A
$ git commit -m "Created the first release"
$ git push

$ git tag v0.1.0
$ git push origin v0.1.0
```


# File: github_started.md

# GitHub started

**Type**: Group work

---

## Alternatives to GitHub

Using GitHub is not mandatory in this course. Both Gitlab and Bitbucket offer services similar to GitHub Actions. Or you could even host your own git server and setup CI/CD manually.

The course resources will assume that your group went with GitHub and tutorials will all focus on GitHub.

---

## [Group] GitHub organizations

With your designated semester groups create a new [organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch). 

1. Create an organization.

2. Add each other as collaborators on the organization level. Give everyone admin rights. 

3. [Optional] Create a `test` repository in the organization.

4. [Optional]  Clone the repository and push a change on the main branch. 

Do not fork the repository. Forking it creates a new repository. 

Now that you are collaborators you can work on the same repository. 

5. [Optional]  Delete the `test` repository. 

6. Create (a) joint repositor(y/ies) as you see fit. 

---

## Naming 

You are free to name the repositories and the search engine whatever your like. 

You are not required to go with the WhoKnows branding.

---

## Make the main code repositories public

The course aims to teach you techniques on how to never push sensitive information 

---

## License

Because of the previous point, it is important that you consider the [license types](https://en.wikipedia.org/wiki/Software_license#Software_copyright) for your repositories.

If you use a permissive license, you will allow other groups to reuse your code. 

Unlike popular belief, no license does not entail free for all. Having no license is the most restrictive type and will legally disallow other groups from using your work. 

[Source](https://choosealicense.com/no-permission/)



# File: upgrade_the_application.md

# Upgrade the application

Upgrade the server code from Python 2.0 to Python 3.x.x. Get a feel for the server. 

**Type**: Group work


**Motivation**: The goal is for everyone to study the code base and get familiar with the functionalities.


# The application

In case you missed it, the application can be found here:

https://github.com/who-knows-inc/whoknows_variations

The main branch is the same as what we copied from the server. 

## Converting from Python 2 -> 3.  

There are multiple ways to achieve this. One is to install and use the `2to3` tool.


#### Usage

Check installation and find some useful flags here.

```bash
$ 2to3 --help
```

You can run it on the server file like this:

```bash
$ 2to3 app.py
```

<!-- #### Check the result

In cause you use 2to3 to auto-fix it then save it to a different file and compare these two before you push the changes. 

For *nix systems, use the `diff` command to compare the files: 

```bash
$ diff app.py app.py3
```

For Windows use the FC (File Compare) command:

```powershell
$ FC app.py app.py3
``` -->



## Fix the shell script: `run_forever.sh`

In the `src` directory you can find `run_forever.sh` script. Use `shellcheck` to fix potential problems. 

#### Installation

MacOS:

```bash
$ brew install shellcheck
```

Windows:

```bash
$ choco install shellcheck
```

#### Usage

Assuming that you are in the `src` directory:

```bash
$ shellcheck run_forever.sh
```



# File: problems_with_the_codebase.md

# Problems with the codebase

Idenfity all the problematic parts of the legacy code. 

**Type**: Group work

**Part of mandatory I**

**Motivation**: This task is an excellent opportunity for everyone to study the code base and become familiar with the functionality, components and Flask which is likely new for you.

---

## What to do

Create a document that lists all the problems in the provided codebase. The list should be sorted after priority. The most critical problems should appear first. 

While the problems of the legacy code doesn’t relate to your final product, it is still a topic of interest during the exam to see how you mitigated these problems. 




# File: create_a_dependency_graph.md

# Create a dependency graph (Digraph) for the legacy system

**Type**: Group work

**Submission**: Save the graph as a SVG or image and store it somewhere where the entire group has quick access to it.

**Motivation**: Helps you understand the dependencies between different parts of the application. Seeing how everything is coupled could help you understand how it could be deocoupled later on for easier maintenance and fault tolerance. 

**Part of mandatory I.** 

---

## What is a dependency graph?

A [Dependency Graph](https://en.wikipedia.org/wiki/Dependency_graph) is part of [Graph Theory](https://en.wikipedia.org/wiki/Graph_theory) and consists of [Nodes/Vertices and Edges](https://en.wikipedia.org/wiki/Vertex_(graph_theory)#/media/File:Small_Network.png).

---

## How to create a dependency graph?

There are many great tools for it. Here is an [online Graphviz Tool](https://dreampuf.github.io/GraphvizOnline/).

Try replacing their default example with the snippet below.


```dot
digraph G {

    a -> b
    b -> c
    b -> d

}
```

Try replace `a` with `Flask`. Remember that it's not just for the `Flask` server and its dependencies but the entire system. 



# File: create_a_pr_to_repositories_py.md

# Create a PR to repositories.py

Add your group to [repositories.py](/repositories.py) which is in the root of the semester repository. 

**Type**: Group work

**Deadline**: 1 day before the next lecture

**Hard Deadline**: By week 2 lecture


## `repositories.py`

The file may look like this before other groups update it:

```python
GROUP_REPOS = [
        {
            "name": "Example Group",
            "gitLinks": ["https://<git_link>"],
            "backend": "http(s)://<IP_DOMAIN>/<APIURL>",
            "frontend": "http(s)://<IP_DOMAIN>/<FrontEndURL>",
            "monitoring": "http(s)://<IP_DOMAIN>/<MonitoringURL>",
            "stack": ["Flask", "Svelte", "CouchDB", "Redis"],
            "documentation": ["link to documentation", "another link if it applies", "et cetera"],
            "sla": "link to sla",
        }
]
``` 

1. Create a new `dict` and add the template:

`dict` is the data structure in Python which looks similar to JSON. 

Paste the following template in the `GROUP_REPOS` list variable:

```python
{
    "name": "",
    "gitLinks": [""],
    "backend": "",
    "frontend": "",
    "monitoring": "",
    "stack": [],
    "documentation": [],
    "sla": "",
}
```

2. By next week you must fill the values for the following keys: 

- `name`: The name of your group.

- `gitLinks`: The link(s) to your repositories.


3. Validate the syntax: 

Remember commas after the last dict when you add a new one.

To validate the file before making a PR, you can use the following command:

```bash
$ python -m py_compile repositories.py
```

4. **IMPORTANT** Get the latest changes. 

Just before you push your changes, make sure you have the latest changes from the repository. See [Pulling from the Original Repository into your fork](#pulling-from-the-original-repository-into-your-fork) for more information.


If you do not do this then merge conflicts will occur. 

5. Make a PR.

Here are some resources to help you get started:

[![How to make a PR](http://img.youtube.com/vi/8lGpZkjnkt4/0.jpg)](https://www.youtube.com/watch?v=8lGpZkjnkt4)

https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests

https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project


4. Make sure to update this file with the correct information throughout the course. Let me know if you've made a pull request later on and I miss it.


## Pulling from the original repository into your fork

It is **crucial** that you do this before you push changes and make a PR. Otherwise, you might encounter merge conflicts with other groups. 

1. Add the original repository as a remote:

```bash
$ git remote add upstream <original-repo-url>
```

2. Fetch the latest changes from the original repository:

```bash
$ git fetch upstream
```

3. Merge the changes into your local branch:

```bash
$ git merge upstream/main
```

4. Push the merged changes to your forked repository (Adding origin and branch name is optional):

```bash
$ git push <origin main>
```




# File: refresh_yaml_syntax.md

# [Optional] Refresh YAML

**Type**: Individual


**Soft Deadline**: Before week 2


## Great basic YAML syntax overview

https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html


## YAML video tutorial

If you are the type that learns best from videos try this out:

[![YAML tutorial](http://img.youtube.com/vi/1uFVr15xDGg/0.jpg)](https://www.youtube.com/watch?v=1uFVr15xDGg&list=PLy7NrYWoggjxKDRWLqkd4Kbt84XEerHhB&index=6)




# File: refresh_basic_terminal_commands.md

# [Optional] Refresh basic terminal commands


**Type**: Individual


Windows users, use `Powershell`, or even better, `Windows subsystem for Linux`.

---


## Directories and moving

Output current directory (`pwd`):

```bash
$ pwd
```

Change into a directory (`cd`):

```bash
$ cd <directory>
```

Move one directory up (note: `..` is a special directory name that is the parent of the current directory):

```bash
$ cd ..
```

---

## Listing files and directories

List directory contents (`ls`):

```bash
$ ls
```

List directory contents with details (`ls -l`):

```bash
$ ls -l
```

List directory contents with details and hidden files (`ls -la`):

```bash
$ ls -la
```

---

## Listing files in a directory

List files in a directory (`ls <directory>`):

```bash
$ ls <directory>
```

List files in this directory (note: `.` is a special directory name that refers to the current directory):

```bash
$ ls .
```

---

<div class="exercise-card" style="color: green;">
    <h1>Exercise</h1>
</div>

How do you list the files in the parent directory?

---

## Creating and deleting directories

Create a new directory (`mkdir`):

```bash
$ mkdir <directory_name>
```

Delete a directory (`rmdir`):

```bash
$ rmdir <directory_name>
```

Delete a directory (`rm -rf`):

```bash
$ rm -rf <directory>
```

---

<div class="exercise-card" style="color: green;">
    <h1>Exercise</h1>
</div>

Create a directory called `test`, move into it and create a directory called `test2`.
Now move back into the parent directory and delete `test2` and `test`.

---

## File handling:

Copy a file (`cp`):

```bash
$ cp <source> <destination>
```

Move or rename a file (`mv`):

```bash
$ mv <source> <destination>
```

Delete a file (`rm`):

```bash
$ rm <filename>
```






# File: install_these.md

# Install these 

**Type**: Individual

In case the list is overwhelming and time is sparse I have split it into things that you must have done before week 1 and things that you can do later.

---

## Must do before week 1


#### Editor / IDE

Have an editor / IDE ready (including renewing licenses). You are free to use any editor during the course. I will use VSCode but it has very little significance for the lectures. 


#### Ensure that you can run `ssh` in your terminal

Run `ssh` in your terminal. If you get a message that it is not installed then you need to install it or use a different terminal. This is needed already for the first lecture!


### Windows users only

Install `Chocolatey`: https://chocolatey.org/

Don't use CMD. 

Install `Windows subsystem for Linux`: https://learn.microsoft.com/en-us/windows/wsl/install

Make sure that you can actually run it. If you have Docker installed prior to it then it will try to launch in Docker and fail. This is the solution to that problem:

https://stackoverflow.com/questions/75157946/wsl-failed-to-initialize-on-windows-11


#### Make sure you can run Python

Python comes preinstalled on all operating systems but make sure that you can run Python on your computer. 

You might need to run this on Windows in an admin Powershell terminal to run Python. 

```powershell
$ Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
```


### Mac users only

Install homebrew: https://brew.sh/

Video guide on how to download for Macbook M1 or newer: https://youtu.be/Qvfvj-UCJuQ?t=55

---

#### Try out your package manager

Now that you have `homebrew` or `chocolately` installed see if you can install Python 2:

```bash
$ brew install python
```

```powershell
$ choco install python2
```

---

## Must do before week 3

You can do the following before the semester start or later on. Once the semester start there are many assignments of higher priority so consider postponing this section.

#### GitHub Student Developers Pack

Check the GitHub Student Developers Pack: https://education.github.com/pack. For instance, you can get some credit for DigitalOcean as an alternative to Azure.

There are benefits to getting a GitHub Pro account. 


#### Azure

Set up or renew your Azure for students account. Look into Azure for Students where you will get free credit.

https://azure.microsoft.com/en-us/free/students/

[Guide with screenshots](./how_to_renew_azure_for_students/how_to_renew_azure_for_students.md)


#### SSH keys

Many of you generated a SSH key pair last semester. If you have lost it then generate a new one. Generate a RSA key pair. Specifically, RSA, will be required for Terraform later in the course.

---

## Must do before week 4

#### Install Postman and create account

https://www.postman.com/

Create an account. We will be using features that require the non-lightweight version as they call it. You can use a throwaway email to signup. 


#### Install Node.js. 

Install Node.js: https://nodejs.org/en/download

Both LTS (long-time support) or Current are fine. 

Verify that you have Node.js installed. 

```bash 
$ node --version
```

#### Docker

Have Docker Desktop installed and be ready to work with Docker. Success criteria: Can run `docker --version` in the teminal. 

Install Docker: https://www.docker.com/products/docker-desktop/.


---

## Can do before week 10

#### `az` (Azure CLI)

Install Azures CLI `az`. Look here to find how to install it for your OS:

https://learn.microsoft.com/en-us/cli/azure/install-azure-cli

OR a perhaps a better command to install for Windows here:

https://developer.hashicorp.com/terraform/tutorials/azure-get-started/azure-build

Successful criteria: Can run `az --version` in the terminal that you use. So if you install it for Powershell but always use Git Bash for instance, then you might consider a different installation method.

#### Terraform

Install Terraform:

https://developer.hashicorp.com/terraform/install?product_intent=terraform

---

## Optional

#### Sqlite3 CLI

There is an SQLite3 CLI that you can install. It will allow you to interact with Sqlite databases from the terminal.


<!-- #### Install Poetry

Still unsure if this will be used in the course so this is very optional for now.

https://python-poetry.org/docs/main/ -->






# File: how_to_renew_azure_for_students.md

# How to renew Azure for students

---

## Know that your credit is about to expire.

I got the following email:

<img src="./assets/upgrade_azure_email.png" alt="email upgrade azure">

But the link won't work

<img src="./assets/the_link_wont_work.png" alt="upgrade azure moved">

---

## Find the page for Azure for students

https://azure.microsoft.com/en-us/free/students/

Scroll down the page and find the "**Start free**" button:

<img src="./assets/azure_for_students_start_free_button.png" alt="azure for students start free">

You will be prompted to verify your Academic status (by using your KEA mail):

<img src="./assets/academic_verification.png" alt="academic verification">

I am immediately verified and redirected to the following page in the portal and I see the budget going up:

<img src="./assets/verifaction_complete.png" alt="azure portal verification new budget">


# File: refresh_basic_git.md

# [Optional] Refresh basic git

**Type**: Individual


## Learn how to push and pull code from a remote repository

### Create a repository

You can use the GitHub interface. Copy the URL and in your terminal:

```bash
$ git clone <url>
```

The rest assumes that you have `cd`'d into the repository. 


### Pushing, Step 1: Adding Files

Create some files to add. 

Add all files:

```bash
$ git add -A
```
Add everything here and nested foloders:

```bash
$ git add . 
```

```bash
$ git add <filename\folder>
```

---

### Pushing, Step 2: Commiting Files

Commit with a message:

```bash
$ git commit -m "<message>"
```

---

### Pushing, Step 3:  Pushing to remote

Push the code to remote:

```bash
$ git push
```

---

### Pulling

If others are working on the same repository, get the latest changes:

```bash
$ git pull
```

---


# File: your_infrastructure_as_code.md

# [Highly Optional] Your Infrastructure as Code

**Type**: Group work

**Motivation**: Achieve consistency, efficiency, scalability, reproducibility, automation, versioning, portability, collaboration, agility and resilience.

---

## Scope

Replicate your infrastructure or some parts of it using Terraform.

Remember that this is a **highly optional** task. 

Feel free to provision new resources without using them in production.




# File: kea_learn_terraform.md

# [Optional] Learn basic Terraform concepts

Follow a beginner friendly tutorial to learn the basic concepts of Terraform thoroughly.

**Type**: Individual

**Motivation**: Understand what makes up Terraform better to help you debug and maintain the infrastructure.

---

## The resource

https://github.com/anderslatif/Kea_learn_terraform

I recommend only going through 1 - 3.




# File: software_maintenance.md

# Software Maintenance

Prioritize tasks for software maintenance in the short remaining time. 

**Type**: Group work

**Motivation**: You are now entering software maintenance mode. Use your time wisely.

---

## Tasks during software maintenance

- **Bug Fixing**: Identifying and correcting defects in the software.

- **Performance Optimization**: Enhancing system performance and resource usage.

- **Security Patching**: Fixing vulnerabilities to protect against threats.

- **Documentation**: Keeping documentation current with code changes.

- **Logging/Monitoring**: Monitoring and managing log files for errors and performance issues.

- **Backup/Restore**: Ensuring data integrity and availability.

- **Implement remaning features**: Reprioritize the backlog and implement the remaining crucial features.

---

## A Final Release

It would make sense to release a final version of your system before the end of the project.



# File: whoknows_variations_continuous_deployment.md

# [Optional] Whoknows variations - Continuous Deployment

Use your acquired skills to quickly provision infrastructure and achieve continuous deployment.

**Type**: Individual

**Motivation**: Easy task, newly aquired skill.

---

# The task

1. Fork the repository. 

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_deployment

2. Change `infrastructure/terraform.tfvars_copy` to `inffrastructure/terraform.tfvars` and fill in the variables.

3. Provision the infrastructure using Terraform with the following commands:

```bash
$ cd infrastructure
$ terraform init
$ terraform apply
```

4. Once the infrastructure is provisioned, run the `setup.sh` script to add the necessary values to Github Secret. (Requires Container Registry Personal Access Token).

5. Trigger the Github Actions workflow to deploy the application.




# File: improve_accessibility.md

# Improve accessibility

**Type**: Group work

**Motivation**: Make your website accessible for all users. 

---

## Introduction

Your website has gained a lot of traction!

As a result, an accessible web awareness group (AAAAA!) has eyed your website. They have found several flaws that causes your website to be inaccessible to some. Here is the email:

```plaintext
Dear Webmaster,

We are from AAAAA!. 

We recently reviewed your website and identified several accessibility issues that could impact users with disabilities.

To assist you in addressing these issues, we recommend the following resources:

	•	https://wave.webaim.org/
	•	https://www.whocanuse.com/

Alternatively, you could also use Lighthouse:

	•	https://developer.chrome.com/docs/lighthouse/overview/

We urge you to review and resolve these accessibility concerns promptly to ensure your website is accessible to all users.

Regards,
Accessibility Awareness Always And Anywhere Association! (AAAAA!)
```

---

## Task

Prioritize and focus on solving some of the most egregious issues. Even professional website do not get a perfect score in these tools. Make sure that you write down the issues you have fixed but also write down if you have arguments for chosing not to fix a certain issue.


# File: harden_yourself.md

# Harden Yourself

**Assignment Type:** Group work

**Motivation** Make your system more secure. 

---

## Introduction

Here are a bunch of resources. It is up to your group to decide which ones make sense to use.

For the first category of tools, consider how you can make them part of your CI/CD pipeline.

---

## Scan the code / container

--

### snyk

[snyk](https://snyk.io/) has a a database full of exploits. They've created multiple tools to help you find and fix vulnerabilities in your code.

1. Install snyk (`brew install snyk-cli` / `choco install snyk` / `npm i -g snyk`). You will then have to autheticate with:

```bash
$ snyk auth
```

2. You can run snyk on your project:

```bash
$ snyk test
```

3. You can also run snyk on a Docker container but I recommend Docker Scout for that.


---

### Docker scout

Docker also provides a vulnerability scanner:

https://docs.docker.com/scout/quickstart/

You can access it through Docker Desktop or through the command line.

---

### Trivy

Trivy is a general purpose security scanner:

https://github.com/aquasecurity/trivy


---

## Scan the website

--

### Mozilla Observatory

You can perform a website security test by entering your website URL:

https://observatory.mozilla.org/


---

### Detectify

A popular website security scanner but it requires an account:

https://detectify.com/


## Scan the server

--

### Lynis

Lynis is a security auditing tool for Unix and Linux based systems. It performs an in-depth security scan.

It will analyze your server from within and treat it as a white box as opposed to a black box.

```bash
$ apt install -y lynis
$ sudo lynis audit system
```




# File: implement_tests.md

# Implement tests

Implement various types of tests as part of your development process. 

**Type**: Group work

**Motivation**: Make your application more robust and avoid fatal errors in the rest of the course.

---

# Where to implement 

Notice that it says to implement tasks as part of your development process; not just CI/CD.

Tests can run locally before pushing to the repository.

Tests can also run after a new version of the application has been deployed. 

---

# What to implement

It is optional to implement unit tests. It would be nice to implement a few just to see how it works in your chosen language. 

It is required to implement integration tests. This could be mock  tests. End-to-end tests are a subset of integration tests. For inspiration regarding how to make it work with Playwright check out https://github.com/who-knows-inc/whoknows_variations/tree/end-to-end_testing

Feel free to implement other types of tests as well.

You must consider all types of test and remember why you decided that they were not relevant to the project.

---

# How much to implement

For the sake of the course it is better to setup a variety of tests to show that you can rather than performing one type of tests exhaustively.





# File: setup_https.md

# Setup HTTPS

**Type**: Group work

**Motivation**: Secure 

---

## Introduction

You should setup HTTPS on your server.

You have been provided. 

Remember to make a PR to `repositories.py` with the new URL.

---

## Using whoknows_variation

Here is a guide on how to register a domain with one.com, adding the IP address and creating a certificate on the server:

https://github.com/who-knows-inc/whoknows_variations/tree/tls




# File: fail2ban.md

# fail2ban

Secure your server from bots trying to guess your password. 

**Type**: Group work

**Motivation**: Harden your server by preventing one-point brute-force attacks on your server.

---

## Why fail2ban exists

Check the amount of times bots on the internet have discovered your server and failed to guess your password.

```bash
$ sudo grep "Failed password" /var/log/auth.log
```

You should completely disable password authentication if you are using SSH. 

Fail2ban keeps track of IP addresses that try to gain access to your server and bans them for a certain amount of time.

---

## Installation

All you need to do is the following:

```bash
$ sudo apt install -y fail2ban
$ sudo systemctl enable fail2ban
$ sudo systemctl start fail2ban
```

`enable` will make sure that fail2ban starts on boot, and `start` will start it now.

---

## Configuration

This is not needed but if you are interested, you can learn how to configure fail2ban by reading the [official documentation](https://github.com/fail2ban/fail2ban/wiki), the section for [configuring fail2ban](https://github.com/fail2ban/fail2ban/wiki/Proper-fail2ban-configuration). For instance, you can set the number of failed login attempts before a ban is imposed, the duration of the ban, and the services to monitor.




# File: security_breach.md

# Security Breach!

A hacker has managed to breach the security of your application!

**Type**: Group

**Soft Deadline**: As soon as possible.

---

## Description

A hacker has managed to breach the security of your application and gained access to your database. To prove it he has hand-picked some users and sent them to you.  

Implement a feature that informs your users and forces them to change their password. 

There are many possible solutions. You could use email but informing is not enough. They must be forced to change password if they want to use your system. 

---

## Hacker message

Here is the message that the hacker sent to you:

```plaintext
To whom it may concern,

I have managed to breach your security. I have access to all your data. I will give yo a grace period to close the gap before I choose to act on your bad security. 

To prove that I am not making it up, here are some of your users and their corresponding passwords. 
```

<!-- todo     CREATE TABLE IF NOT EXISTS users (
        username TEXT NOT NULL PRIMARY KEY,
        email TEXT NOT NULL UNIQUE,
        password TEXT NOT NULL,
        group_name TEXT NOT NULL
    );-->



# File: whoknows_variations_security_testing.md

# Whoknows_variations Security Testing

**Type**: Individual

**Motivation**: Understand different possible security tests that can be performed in Github Actions

---

## Instructions

Study this branch individually:

https://github.com/who-knows-inc/whoknows_variations/tree/security_testing

All group members should have an understanding of the security tests that can be performed in Github Actions.

If you find something smart that makes sense to include in your own project, please do so.




# File: security_hardening_github_actions.md

# Security hardening for GitHub Actions

**Type**: Individual

**Motivation**: Make sure that you follow the best practices for security when using GitHub Actions.

---

## Reading material

Since it's important that all developers are aware of the security risks and best practices when using GitHub Actions, all group members should read the following documentation:

https://docs.github.com/en/actions/security-for-github-actions/security-guides/security-hardening-for-github-actions

You are **not** expected to read the link thoroughly. Just skim the page and see if anything applies to your project.

If you make any changes after reading the documentation, then make a note of it or tell your group members about it.



# File: registering_domain_onecom.md

# Registering domains with one.com

Register a domain now so that you are ready to set up HTTPS later. 

**Type**: Group work

**Motivation**: It can take over an hour for the registration to be completed so this is a good asynchroneous task to complete before the lecture.

---

## Introduction

This task is only to register the domain. After the lecture you can follow `whoknows_variation` to setup HTTPS.

Get the voucher coupon from Teams. 

Remember that it's optional to use one.com and you are welcome to use other methods. 

Other services offer student discounts. With this method you do not need to use your credit card.

Here is the guide on how to set it up with one.com:

https://github.com/who-knows-inc/whoknows_variations/blob/tls/tutorials/01._registering_domains_with_one.com.md




# File: generate_openapi_specification.md

# Create OpenAPI Specification

**Type**: Group work

**Part of mandatory I.**

**Motivation**: Learn how to generate OpenAPI Specification for your framework and programming language of choice. 

---

## The provided OpenAPI Specification

You have been provided with the following OpenAPI Specification file [`openapi.json`](./openapi.json). 

It's a must that you should adhere to this specification. You are free to add more routes, though. 

**But this task is about creating your own specification based on your own code.**

Yes, it's a weird assignment because your result should match the provided OpenAPI Specification. The purpose of this assignment is to learn how to generate OpenAPI Specification for your server.


## How to generate OpenAPI Specification for your server

This step differs vastly depending on the framework and multiple approaches exist within the same framework.

---



# File: commence_the_rewrite.md

# Commence the rewrite

Start converting the legacy code to your own stack. 

**Type**: Group

**Motivation**: [This is how dandy you will look if you do it with a structured way](https://www.oreilly.com/library/view/re-engineering-legacy-software/9781617292507/)

---

## How to get started

You should have agreed on a programming language and server framework by now. 

Agree with your group how to organize the code in folders and the overall structure of the new project. 

Consider if you want to have a monorepo or a multi-repo setup.

---

## Gradual rewrite

Keep the legacy code in your repository and slowly build up a new code base alongside with it. Consider, if this was a much larger project, how you would dismantle the legacy project and phase in the new.

The goal is not to have a ground up working version for the application. It’s to realize that a rewrite requires a different approach than when you build projects up from scratch in other courses. Solving this task linearly from top of the app.py file to the bottom is not a good approach. Instead, flesh out the server (in your language of choice) in stages. Deligate the tasks so that everyone can work on their own part independently. You are not definitely not expected to have all features by next week. Next week we will look into deployment and you should have something in a language that can be deployed.

---

### Gall's Law

Do not do the big rewrite! In real-world software development, follow Gall's Law. Here is an abridged version:

> "*if you want a complex system to work, build a simpler system first, then improve over time.*"

[Full version](http://principles-wiki.net/principles:gall_s_law)

I suggest that you keep the legacy code alongside with the new codebase as you slowly phase it out. 

---

## Strangler fig pattern

[The strangler fig pattern](https://en.wikipedia.org/wiki/Strangler_fig_pattern) considers how to gradually replace old code with new code in incremental steps. This ensures no downtime. 

You are not expected to do this but consider how you would've since this is a common approach in the industry.

---

## The OpenAPI specification

You must adhere to the provided [OpenAPI specification](./openapi.json) exactly.

As you can see the `/about` page is optional. 






# File: kanban_github_project.md

# Kanban

Create a kanban / issue tracker for the project. 

**Type**: Group work

**Motivation**: This will aid you in structuring the many tasks you have ahead of you with the rewrite.

---

## GitHub Project

One way is to create a project in GitHub. 

Learn about projects:

https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects

Quickstart:

https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects

It's up to which view you prefer:

https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/changing-the-layout-of-a-view

---

## Alternatives

It's perfectly fine if you prefer Trello or similar kanban solutions but try to create a board in GitHub for the sake of this assignment at least. Then you can weigh the pros and cons of your choice better. 




# File: generate_openapi_spec_in_postman.md

 # [Optional] Generate an OpenAPI spec in Postman

**Type**: Individual


Only if you are interested in seeing how you can use Postman to generate an OpenAPI spec. It is possible to do either based on your collection definition (**Option 2**) but in this example since we have none, we will make Postman generate an example spec for us (**Option 1**).

---

### Create collection

You must create a collection in Postman first. A collection is a group of requests. 

<img src="./assets_openapi/01._create_collection.png">

<!-- ---

#### Enable Monitors

Click on the icon below `history` in the left side and enable Monitors. 

<img src="./assets_openapi/02._enable_monitors.png"> -->

---

# Option 1: Create a new API

Click on the `API` button in the top-left side below `Collections` and in the pane that opens, click on `Create an API`.

<img src="./assets_openapi/03._create_an_API.png">

---

### Author from scratch

Click the `+` button next to `Definition` and choose `Author from scratch`.

<img src="./assets_openapi/04._author_from_scratch.png">

---

### Select `Use a boilerplate`

And OpenAPI version 3.1.

<img src="./assets_openapi/05._use_a_boilerplate.png">

---

### Exercise: Try to understand the YAML file

---

# Option 2: Import OpenAPI spec (Paste)

This was done during class. Check the lecture notes. 



# File: learn_branching.md

 # Learn branching

**Type**: Individual

**Deadline**: No fixed deadline but it might become useful this week already. 

**Motivation**: Branching should be second nature to you as should be used a lot in your group. 

---

## Setup

I recommend that you create a new repository for this task as a playground that can be deleted later.

---

## Let's get started

1. Consider where to create a branch.

A branch can be created:

- On GitHub
- Locally, using `git`

In this tutorial we will go with `git`. 


2. Create a new branch locally. 

```bash
$ git checkout -b <branch-name>
```

The `-b` flag creates a new branch.

In the future if you just want to switch to a branch you can simply do:

```bash
$ git checkout <branch-name>
```

3. Create a change. Add it. Commit it. 


4. Push the branch to GitHub.

```bash
$ git push -u origin <branch-name>
```

5. Create a pull request in the GitHub UI that someone else in the group accepts. 


6. You can always list all branches.

List all branches:

```bash 
$ git branch
```

List all branches (including remote branches):

```bash 
$ git branch -a
```

Note: You might need to press `q` to exit the list.


# File: terminal_files.md

# Terminal Files

Work with files through the terminal.

**Type**: Individual

**Motivation**: This will help you when you want to work with files on the server. (You are welcome to skip the Windows sections if they do not apply to you).

---

## File creation (\*nix):

Output hello:

```bash
$ echo hello
```

Create an empty file (`touch`):

```bash
$ touch <filename>
```

Display file contents (`cat`):

```bash
$ cat <filename>
```

---

## File creation (Windows):

Create a new file (PowerShell):

```powershell
touch <filename>
```

Display file contents (PowerShell):

```powershell
cat <filename>
```

---

## Tips regarding files

Avoid spaces in files and folders!

**Use Descriptive Names**: Choose file names that clearly indicate the content or purpose of the file.

**Avoid Special Characters**: Besides spaces, avoid using special characters like `/`, `\`, `:`, `*`, `?`, `"`, `<`, `>`, `|`, etc.

**Cross-Platform Compatibility**: If files will be used across different operating systems, consider compatibility (e.g., case sensitivity in file names in \*NIX vs. Windows).

---

## Hidden files and folders

**In \*nix**, a file or folder is made hidden by prefixing its name with a dot `.`. For example, `.example`.

**In Windows**, the 'hidden' attribute is set on the file or folder, which can be done through file properties or using the command `attrib +h`.

Finder / Explorer can be configured to either show or hide hidden folders / files.

---

## Text Editors - Windows:

No native text editors for the terminal. Alternatives (but will not work on servers):

```powershell
$ notepad <filename>
```

```powershell
$ code <filename>
```

---

## Text Editors in \*nix Systems

#### **Nano**: Simple and User-Friendly.

#### **Vi/Vim**: Advanced and Powerful: Offers extensive functionality for complex editing tasks.

---

# Vim

**Multiple Modes**:

- **Normal Mode**: Default mode for navigation and command execution.

- **Insert Mode**: Allows typing and editing text, similar to standard text editors.

- **Visual Mode**: Enables text selection using arrow keys; supports standard clipboard operations.

- **Visual Block Mode**: Facilitates block-shaped text selection and manipulation.

---

# Using a different editor for Git

If you have ever typed `git commit` without the `-m`, you will be presented with the `vim` editor.

If you prefer nano, you can change the default editor for `git` like this:

```bash
$ git config --global core.editor "nano"
```

---

# Install Nano and Vim on Windows:

Depending on your terminal you might already have them.

You can test it by running `nano` or `vim`. Otherwise:

```bash
$ choco install nano
```

```bash
$ choco install vim
```

---

## Quitting

The last part is not only about files but it's generally useful how to quit any program in the terminal.

Different programs have different ways to terminate them. The most common are:

```
q
```

```
:q
```

```
:q!
```

```
CTRL-C
```

```
CTRL-D
```

---



# File: git_advanced.md

# [Optional] Advanced git

Try out some fun git commands, but only if you have the time. This is very optional. 

**Type**: Individual

---

## Git log

See the commit history:

```bash
$ git log
```

This will show each commit. There is a SHA (unique identifier) associated with each commit. 

You can checkout a specific commit with:

```bash
$ git checkout <sha>
```

You can go back to the head of the branch (latest commit) with:

```bash
$ git checkout head
```

To see a graph of the commits:

```bash
$ git log --graph
```

You can quit by pressing `q`. 

The graph view is more interesting if you have multiple branches.

---

## Git stash

Stashing is helpful when you want to pull (requires uncommited file changes) but don't want to create a commit just yet. 

1. Try to create a new file with some content:

2. Stash (temprorarily shelve) changes:

```bash
$ git stash
```

3. Reapply the most recent stash:

```bash
$ git stash pop
```

It's also possible to stash by a name and apply a specific stash.

---

# When nothing else works...

"Just give me what is in the repository right now".
Warning: this throws away all your uncommited changes:

```bash
$ git reset --hard origin
```





# File: decide_on_a_framework.md

# Decide on a framework

**Type**: Group work

**Deadline**: Immediately after the lecture on week 2 so that you can coordinate and create a battle plan with your group. 


**Motivation**: Be quick in making a choice. If you postpone the decision making you will reduce your available developer time and the simulation is bound to start soon. (Your group needs users and start making money to stay afloat.)

---

## Excluded choices

You are not allowed to use `Flask`, `Express` or `Spring Boot`.


## Choose a micro-web-framework

Advice: Do not choose full-webframeworks like Django, Blazor, Spring MVC, Ruby on Rails. 

If I were in your position, I would consider one of the following:

| Language                                     | Framework                                             |
|----------------------------------------------|-------------------------------------------------------|
| [Crystal](https://crystal-lang.org)          | [Kemal](https://kemalcr.com)                          |
| [Elixir](https://elixir-lang.org)            | [Phoenix](https://www.phoenixframework.org)           |
| [Go](http://golang.org/)                     | Standard Library or [Gorilla](http://www.gorillatoolkit.org/) |
| [Nim](https://nim-lang.org)                  | [Jester](https://github.com/dom96/jester)             |
| [Ruby](https://www.ruby-lang.org)            | [Sinatra](http://sinatrarb.com/)                      |
| [Rust](https://www.rust-lang.org/)           | [Rocket](https://rocket.rs/)                          |

Choose a language and framework that you want to practice or one that you always wanted to learn but never had the time to do.

You have seen the Flask server which has a relatively small size and complexity. Choosing something wildly unfamiliar should not be daunting considering the size of the server.

---

## Client-side rendering vs. server-side rendering

There are two ways to render your frontend. 

### Server-side rendering: The client serves the frontend. Probably through a templating engine. 

Here are just some different pairings of templating engines:

| Language       | Framework               | Library                                         |
|----------------|---------------------------------------------------------------|--------------------------------------------------------------|
| C♯             | [ASP.Net minimal web application](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0)                               | [Razor Pages](https://learn.microsoft.com/en-us/aspnet/core/razor-pages/?view=aspnetcore-8.0&tabs=visual-studio) |
| C♯             | [ASP.Net minimal web application](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-8.0)                               | [Scriban](https://www.nuget.org/packages/Scriban)            |
| Crystal        | [Kemal](https://kemalcr.com)                                  |                                                              |
| Elixir         | [Phoenix](https://www.phoenixframework.org)                   |                                                              |
| Go             | Standard Library                                              | [Gorilla](http://www.gorillatoolkit.org/)                    |
| Java           | [Spark](https://sparkjava.com/)                               | [jinjava](https://github.com/HubSpot/jinjava)                |
| Nim            | [Jester](https://github.com/dom96/jester)                     |                                                              |
| Python         | [Pyramid](https://trypyramid.com/)                           or  [Bottle](https://bottlepy.org/docs/dev/) | [Jinja2](https://jinja.palletsprojects.com/en) |
| Ruby           | [Sinatra](http://sinatrarb.com/)                              |                                                              |
| Rust           | [Rocket](https://rocket.rs/)                                  |                                                              |   


### Client-side rendering: The client is stand-alone and fetches data from the server. The server only sends data. 

Examples include: HTML, React, Svelte, Vue, Angular

My recommendation here is to not use this course to learn a heavy web framework. There are a lot of tasks to complete in this course already. And using a complicated web framework does not score extra points since it does not relate to DevOps. 

---

## Additional comments

If your group i still undecided then you should at least have picked a handful of possible frameworks and a method for your group to agree on one.

You don't have to decide on a database yet. Keep using the SQLite database for a couple of weeks until we cover the topic of databases.  

---

## Reminder: Part of Mandatory II

For your entire stack, make sure that you write down how you made choices and relevant considerations your group had. 

You should revise the document later on by reflecting on the pros and cons of your choice. 

---

## Resources to help sway your decision

It's always good to make a data-driven decision. Besides the obvious biases, beware that these sources paint a picture that sometimes differs from the reality in Denmark. 

https://survey.stackoverflow.co/2023/

https://github.blog/2023-11-08-the-state-of-open-source-and-ai/#the-most-popular-programming-languages


https://www.thoughtworks.com/radar

















# File: user_feedback_survey.md

# User feedback survey!

A user feedback survey has been conducted and the results are in...

**Type**: Group

**No Deadline**: Make sure to implement it eventually. I recommend starting after you have achieved Continuous Deployment so that you get the enjoy your labor.

**Motivation**: Just like how market research uncovered the need for the weather feature, listening to your users is a great way to improve your product.

---

## Description

Users have reported that they would like to be logged in after they register, rather than being redirected to the login page and asked to log in again.

If this is already implemented, then there is no need to do anything.




# File: continuous_deployment.md

# Continuous Deployment


Achieve full and automatic continous deployment.

**Type**: Group Work

**Deadline**: No rush. If you are struggling with achieving full CD or experimenting with different ways to achieve it, then spending a few weeks is fine.

**Motivation**: Solve this task before the `user feedback survey` to enjoy that the functionality automatically gets shipped when you push to trunk. 

---

## Full CD

There are many ways to achieve continous deployment. 

Brainstorm with your group and you could even try different ways in different branches / test repos. 

You should aim for "full CD". What is meant by this is that it should work on a fresh server with all the necessary tools installed. 

If your solution requires transfering files to the server, then build it into the workflow.

---

## [Optional / Individual] Whoknows Variations

I offer a solution that you are free to discard for something better. But try it out individually so you get a feel for what the workflow does.

Try out the [continuous deployment branch](https://github.com/who-knows-inc/whoknows_variations/tree/continuous_deployment) to get a taste of one way to make it work. 

The steps are:

1. Fork the repository to your user, check out the branch.

2. Deploy any server that you can SSH into with an SSH key.

3. Run the `setup.sh` script in the root of the repository. It will prompt you for values to put in GitHub Secrets so that the workflow will work. 

4. Trigger the workflow and see it deploy the whoknows legacy app on `<ip_address>:8080`


# File: hadolint.md

# Run hadolint locally and setup in CI pipeline

Lint your Dockerfile using `hadolint`.

**Type**: Group work

---

## Running it locally

All group members should try running `hadolint` locally.

Install hadolint with `brew`, `choco` or similar. 

Then run the following:

```bash
$ hadolint Dockerfile
```

---

## Setup in CI pipeline

Hadolint comes with Super Linter if you have already set it up.

You can also get it seperately with the following action:

https://github.com/hadolint/hadolint-action



# File: fts5.md

# Sqlite FTS5

**Type**: Group work

**Motivation**: Use FTS4 in SQLite for faster searches.

---

## Use FTS5 in SQLite
    
Notice how the SQL `LIKE` operator is used. Let's use the SQLite extension called FTS5 (Full Text Search 5). FTS5 wasn't introduced until October 14, 2015 with version 3.9.0.  https://sqlite.org/fts5.html

Good information on linking with the virtual table and create triggers to keep the data consistent across both tables. Also shows, near the end, how to rank for relevance:

[![SQLite FTS5](http://img.youtube.com/vi/eXMA_2dEMO0/0.jpg)](https://youtu.be/eXMA_2dEMO0?t=175)

---

## Questions everyone should be able to answer 

*What are the advantages/disadvantages of the LIKE operator? What are the advantages/disadvantages of FTS5?*

*What are the limitations of using SQLite?*



# File: smoke_testing.md

# [Optional] Smoke testing

Add a smoke test to your setup. 

---

## What is smoke testing?

To summarize, a smoke test is a sanity check to check that all parts of the system er operational. 

To help your understanding there are two claims to the origin of the term "smoke test", but they both illustrate well why it is named that:

1. **Hardware testing**: Engineers would turn on components and look for smoke. 

2. **Plumbing**: The practic of sending smoke through pipes to check for leaks.

The Wikipedia article provides great terminology and explanations:

https://en.wikipedia.org/wiki/Smoke_testing_(software)

---

## When to check?

You have 3 choices. Include it as part of:

1. **Continuous Integration**: Run the code on the runner (only possible with cURL and not the Postman tutorial) or a staging server and run the smoke test on it before deploying to production. 

2. **Continuous Deployment**: Run the smoke test on the production server after deployment. This wil still be valuable as a visual indicator on GitHub whether the deployment was successful or not instead of having to go to the website and check if everything is running.

3. **Both CI/CD**: Run the smoke test, then deploy and then do another sanity check to verify. 

Given how simple the pipeline setup is, either of those choices are valid. 

---

## The most basic test (cURL)

The most simple smoke test would be to use cURL. Here is an example workflow. 

```yaml
name: Smoke Test

on:
  workflow_run:
    workflows: "CI"
    types:
      - completed

jobs:
  smoke-test:
    runs-on: ubuntu-latest
    if: ${{ github.event.workflow_run.conclusion == 'success' }}

    steps:
    - name: Run smoke test with cURL
      run: |
        # Replace with the actual URL you want to test
        URL="https://your-app-url.com/"

        # Perform the request and capture the HTTP status code
        HTTP_STATUS=$(curl -o /dev/null -s -w "%{http_code}\n" $URL)

        # Check if the status code is 200
        if [ $HTTP_STATUS -eq 200 ]; then
          echo "Smoke test passed."
        else
          echo "Smoke test failed with status code $HTTP_STATUS"
          exit 1
        fi
```

---

## Create a GitHub Action job with Postman

This is a tutorial on how to create a smoke test with Postman. It is surprisingly easy if you already has a collection (with the production URL) with tests saved to it.

I recommend it as it makes it easier to test for a lot more things than doing it with cURL. 

1. Create or use an existing collection in Postman. The collection should have tests saved to it. It could be to verify a response within a fixed time limit and a status code of `200`.

2. Select the collection and click on `Run`. 

<img src="./assets_smoke_testing/smoke_testing_1.png" alt="smoke test postman cli">

3. Select `Automate runs via CLI`. 

4. Under **Run on CI/CD** click on the underlined link **Configure command**.

<img src="./assets_smoke_testing/smoke_testing_2.png" alt="smoke test postman cli">

5. As the CI/CD provider, select `GitHub Actions` assuming that this is what you are using.

<img src="./assets_smoke_testing/smoke_testing_3.png" alt="smoke test postman cli">

6. Remember to generate your API key. This should be stored as a GitHub Action secret in your repository with the key name: `POSTMAN_API_KEY`.

7. Copy the command and paste it into your GitHub Action workflow.

8. Success! You can now run your Postman tests as part of your pipeline. 




# File: postmortem.md

# [Optional] Postmortem

Create a postmortem for a major incident that happened. Only do it if it makes sense. 

**Type**: Group work

---

## How to write a postmortem

Templates for how to conduct a postmortem exist. Each company usually develops their own based on their business domain. 

You could find inspiration online. Atlassian has a very thorough write-up on the matter:

https://www.atlassian.com/incident-management/handbook/postmortems#what-is-post-mortem

In this assignment, your postmortem can take any form you'd like. It can be as simple as you want. 

The main idea is that you investigate a major incident, establish (a) root cause(s) and propose solutions to prevent it from happening again.

**Requirement**: The postmortem should be blameless. 




# File: github_discussions.md

# Setup GitHub Discussion

**Type**: Group work

**Motivation**: Using Github Discussions instead of a closed forum adhers to the DevOps principle of transparency. 

---

## Requirement

Your group is not required to use GitHub Discussions. However, you must use a public forum for discussions. 

The requirement is transparency. Github Discussions is an obvious tool to achieve this, but you could use similar tools as long as they allow for public and anonymous access.

---

## What is it?

Here is a great overview by GitHub:

https://github.com/features/discussions

This link explains how to enable it:

https://docs.github.com/en/discussions/quickstart

---

## When to use it and for what?

It might not be immediately useful but keep it in mind for future discussions regarding design choices.

For instance, it might be perfect for the coming task where you are tasked to choose a better database.




# File: read_about_gitops.md

# Read about GitOps

**Type**: Individual

**Motivation**: You might have heard the term before - you are likely to hear it again. 

---

# What to read

Only read this page; you don't need to read the book:

https://www.gitops.tech/




# File: deploy_to_github_pages.md

# [Optional] Deploy to GitHub Pages

Github Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub. It's only for static content. You cannot run servers with Github Pages. 

**Type**: Individual

**Motivation**: This is a free way to host static content that is easily integrated with your workflows. 

---

## Prerequisites

Create a new repository.

```bash
$ gh repo create
```

---

## Prepare the page

In this assignment you will create an HTML file and it will be deployed via Github Pages. If you push a change to the HTML file the Github Page will eventually reflect that change. Do note that sometimes it can take a few minutes for a change to take place. 

Another method will be shown later on in [whoknows_variations](https://github.com/who-knows-inc/whoknows_variations/tree/end-to-end_testing) where an HTML file is generated in a workflow and then deployed. The HTML file is never checked into version control. In the later case, we deploy to a `gh-pages` branch which is a reserved name for Github Pages. Here we deploy directly from the `main` branch.


1. 📂 Create an `index.html` file in the root of your repository. You can put anything into it that you wish to display on the page. 

---

## Enable GitHub Pages

  - Go to your repository on GitHub.
  - Click on the "**Settings**" tab (⚙️) on the top right.
  - Scroll down to the "**Pages**" section.
  - In the "**Source**" dropdown, select the `main` branch.
  - Set the directory to `/root` in our case. Creating a `/docs` folder is also common.
  - Click "Save".

---

## Create a workflow

Create a file called `deploy_to_github_pages.yml` in `.github/workflows` and add the following content:

```yaml
name: Deploy to GitHub Pages

on:
  push:
    branches:
      - main  # Set this to your default branch

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2

      - name: Deploy to GitHub Pages
        uses: JamesIves/github-pages-deploy-action@4.1.0
        with:
          branch: gh-pages  # The branch the action should deploy to.
          folder: .         # The folder the action should deploy.
```

---

## Access the page

After the workflow has run successfully, you can access your page at `https://<username_or_organisation_name>.github.io/<repository_name>`.

---

## Adding images to the page

Images should be in a folder called /images in root for Github Pages to be able to serve them. Link to the image(s) in your HTML with `src="./images/your_image.png"`.

---

## 🧹 Clean up

Delete the repository with:

```bash
$ gh repo delete
```




# File: about_the_exam.md

# About the exam

Read more about the official [course requirements](https://katalog.kea.dk/course/3050407/2024-2025).

Everything in the link above holds true, but additional information can be found below. 

---

## Collaboration

While it's a group exam you will be graded individually. 

An important part of this course is to learn to work together. It's not just about technologies. Culture is one of the keystones of what it means to be DevOps.

---

## The deployment

What is interesting is that the life span of the application is known in advance. 

You can take down the services once the simulation stops. 

The system must be deployed during the exam. This might mean that you will run out of credit if you are only using a single students' account. 

Don't worry about this part yet. You will learn how to make your life easier the second time around. 

---

## Solution agnostic

During the lectures and the guides focus on a certain way of doing DevOps. 

Don’t wanna use GitHub Actions and want to use CI/CD tools (Travis CI, Jenkins etc.) instead? Great!

Don’t want to use Terraform and want to use Vagrant or Serverless Framework etc.? Great!

That's why I have provided the requirements mentioned below. 

---

## Requirements

I have provided some documents containing the minimum requirements for the exam. Your grade will depend on how much work you put into the project.

I also provide suggestions and guides on how to implement certain things. You can consider them as a fallback if you are stuck. 

What will elevate you is if your group either makes great choices based on research or gain a fresh understanding of the different approaches, the pros and cons of each. Basically, reflecting on your choices. 

The requirement documents are:

- [Exam Project Requirements](./exam_project_requirements.md)
- [Exam Report Requirements](./exam_report_requirements.md)
- [Exam Presentation Requirements](./exam_presentation_requirements.md)



# File: exam_project_requirements.md

# Exam requirements

This document is a to provide an overview of overall requirements without listing each one. It is a supplement to the course material and assignments on the semester plan.

A substantial part of the grade will be based on your project work during the semester but this includes implementation of the DevOps principles into your work.

---
---

# DevOps

This section is an attempt to make you aware of the non-functional requirements that are not directly mentioned in the assignment descriptions in the semester plan.

---

## What is DevOps (Theory)

The theory can be found in slides and the guest lecture. You may even supplement with your own reading on the subject. 

DevOps is not the technology we have learned, though we may use it to aide us in becoming DevOps. 

**Example**: you can use pipelines to help you achieve DevOps principles but pipelines are a concept that predates and exist independently from DevOps. Don't conflate the tooling and technology with the theory of DevOps. DevOps is a culture. It is about the people and the processes.

---

## What is DevOps to you?

Though there are truths like the Weekly DevOps Principles slides many supporting definitions and some conflicting exist. I cannot provide a single definition that you must memorize. And even if I could, it wouldn't be interesting to me. 

It is up to each individual to formulate what being DevOps means to them. I hope that I have given you the tools to do so throughout the course.

---

## Be DevOps

In a way the course runs on two planes. The technological track [Technology](#technology) and the DevOps track [DevOps](#devops). The first track is easy to give tangible assignments for. The second track is something each group must constantly be aware of and intrinsically assignem themselves to work on.

---

## In case you weren’t DevOps

Group work often fail in educational institutions and it would be dealt with differently at work places. I will generate graphs before the exam that represent the commit activity of each group member to gauge participation. This is for people who aren't participating much in their group. It isn't a measuring contest.

The goal is not to point fingers but to highlight the situation that has presented you with an excellent opportunity to put your DevOps principles into use such as [psychological safety](https://en.wikipedia.org/wiki/Psychological_safety). 

During the group presentation I would like you to initiate the conversation by bringing it up. Rather than a negative it is seen as fortitude that you are able to analyze and reflect on real-world problems. This will show that not only have you learned the DevOps theory but managed to apply it to your own group situation. 

---
---

# Technology

These are the functional requirements. All assignments in the semester plan that are not described as [Optional] must be completed.

---

## Tech stack

The server must be rewritten in another framework. You are not allowed to use `Flask`, `Express` or `Spring Boot`.

---

## Organization

Use version control.

Employ a branching strategy.

Have a way to manage issues.

To your best ability, create thorough documentation.

---

## Software quality

Ensure software quality (static analysis / linting).

You must perform testing.

---

## Automation

Setup a CI/CD pipeline.

---

## Monitoring

You must have monitoring.

---

## Deployment

Your application must be deployed to a Virtual Machine or similar. Services like Web Apps or PaaS like Vercel etc. are great and easy to use, but it removes your chance to learn about topics such as server management, maintenance and upkeep.

While not required to implement it, you must've discussed scaling and an optimal deployment strategy in your groups.

---

## Production

Your system must be deployed for the exam.

---
---

# Other Requirements

You must have all your group data filled out in the `repositories.py` file. This must be done exactly when you are asked to do it in the course preparation.

---

## Learning goals

The learning goals are designed to help you understand at what level you should know the content.

While the general content of the slides is mandatory knowledge, sources and external links (included in the slides) are not required reading unless explicitly mentioned in the semester plan / slides.

---
---




# File: exam_report_requirements.md

# Exam report requirements

**Motivation**: The exam report is written by the group and will be read by me and the censor. 

---

## Requirements

**Deadline**: Check the deadline on WiseFlow. Remember to create groups yourselves when you submit the report. The exam plan will be created based on the groups you create.

You are allowed to work on the project after handing in the report.

**Language**: Danish/English

**Length**: Max 8 pages

Rules per the study curriculum:

- A page is defined as 2400 characters (including spaces).

- Images are counted as much as the space that they take up. If you make the images too small to be read without digitally zooming in, then it will be considered as imcomprehensible.

Please add the necessary images and diagrams instead of writing 8 pages of text.

If you exceed the limit, then anything above the limit will not count towards the grade.

---


## Report formalities

The word "report" is just a name. Don't look at this as a document that requires a page of content, introduction, abstract, synopsis, conclusion, etc. This is just a technical writeup that sets the stage for the exam. The report is not decisive for your grade. It is just to give the censor and I an idea of your project in advance. 

However, these are the formalities that your report must include:

- Group name (as per `repositories.py`) and student names with KEA mail and GitHub usernames (if applicable).

- Page numbers

- **Justify margins**: The entire report text (except titles) must be justified on both sides. To get you started, here is how you can do it in Google Docs and Word:

https://youtu.be/cGExqD1PIFE?t=17

https://youtu.be/5CUF3bgazCE?t=35

Justifying text helps readability and gives the report a professional look.


---

## Sections to include

Since the mandatories specify a set of documents that you must bring to the exam, it would be interesting to allow you complete freedom for the exam report. 

Giving an overview of the setup with diagram(s) is a good start, though.

My advice: Keep it concise!

---

## Use of language models

This course encourages you to use tools that might aid you in coding, debugging and correctly configuring your systems.

However, do **not** use AI to write the report. Even with proper prompting language models don't seem to be able to write in the concise manner required without losing meaning. The report is an excercise in trying to formulate the subject in a way that forces you to cut down to the heart of the subjects and what matters in this course.



# File: about_the_course.md

# About the course

[Kea Katalog](https://katalog.kea.dk/course/3050407/2024-2025)

---

## Terminology

**The semester repository**: This repository is where all the course material is. It will serve as the main repository for the semester.

**The simulation**: The simulation will simulate real-world web traffic to your website. 

**The project**: Throughout the semester you will work on a single project and this is also what you defend at the exam. Scale down your expectations significantly regarding implementing a search engine.

---

## Reading

There is only a bit of literature to read in this course. (It is likely to be brought up during the exam.)

There is a lot of course material and I expect everyone to read and understand it. Even if you are not the one to have implemented the task you should've at least thoroughly read and understood the assignment.

---

## Course workload

**Workload**: There is a steep work load in the beginning. It's supposed to become easier towards the end which should fit well with the idea of DevOps. You should create a lot of automation which allows you to lean back later on.  

**Complexity**: The topics are relatively simple in the beginning. Becomes more complex and difficult to implement later on. 

---

## Group work

Everyone must actively participate in the group work and commit. Prior to the exam we will run a script to investigate repository activity on a student basis.  

Use the fact that you work in groups to your advantage. Support each other. Share knowledge. 

I don't expect everyone to know exactly how something was implemented but I expect all group members to take shared responsibility for the project. This means that the exam will focus on **why** a choice was made, what advantages and disadvantages you predicted in advance and what you learned from it.

---

## [Whoknows variations](https://github.com/who-knows-inc/whoknows_variations)

For select few topics you will be provided step-by-step tutorials. 

Flask variations are optional in the sense that it is not required to attend the exam. However, I recommend that everyone tries to follow the tutorials for themselves, even if it isn't used in the exam project. They aim to teach you useful skills.

These tutorials are meant to be as simple as possible. There are better practices and more professional approaches. For the exam you will be evaluated on your knowledge on these practices, personal reflections and your group's implementation. 

Therefore, feel free to deviate from the tutorials if you found a better way. Your grade will reflect your level of ambition. The tutorials exist as a fallback so that no group gets left behind. 

---

## Assignments

Assignments aim to follow this structure:

```markdown
# [[Optional]] Assignment title

Summary / tagline

**Type**: Individual, Group work

**Soft Deadline/Hard Deadline/No Deadline**: 

[**Motivation**: Why you want to complete this task.]

[**Part of mandatory I/II**]
[**Part of the exam report**]


[## Requirement]
```

Square brackets indicate that the element is optional.

For the type:

- Individual: I want everyone to engage with the assignment alone and learn how to do it or learn from it.

- Group work: You are free to delegate the work, however, everyone is still expected to understand the assignment and how your group solved it.

---

## Lecture structure

A lecture day will typically consist of a presentation of a new topic with hands-on class work. 

By the end of it, you get the chance to ask questions. If you have questions then please write them down so you can remember to ask them during the designated Q+A.

Some days you might get some time to coordinate group work. 

---

## Course overall structure

This overview is to make you see the future milestones and know how to pace yourself throughout the course. I recommend starting simple, working in iterations and holding out on implementing the topics that come later. 

| Week | Topics                                            | Milestones (complete after the lecture)                       |
|------|---------------------------------------------------|---------------------------------------------------------------|
| 1    | Intro + Tools                                     | Understand the legacy code + system                           |
| 2    | REST API, OpenAPI, GitHub Actions                 | Start rewriting the project                                   |
| 3    | Cloud, Azure, Deployment                          | Deploy the project, prepare for the simulation trial          |
| 4    | Software Quality, Linting, CI                     | Ensure software quality, implement CI, fix simulation errors  |
| 5    | Docker, The Simulation                            | Begin Dockerization                                           |
| 6    | Docker-compose, CD, Agile, DevOps                 | Implement Continuous Delivery, reflect on DevOps              |
| 7    | Eficode Sofus (External lecturer)                 |                                                               |
| 8    | Continuous Deployment                             | Implement Continuous Deployment                               |
| 9    | Testing, Security                                 | Create tests, integrate security in pipelines, start using TLS|
| 10   | Databases, ORM, Data Scraping / Web Crawling      | Explore databases beyond SQLite, consider ORM, start scraping |
| 11   | Searching, Logging, Monitoring                    | Set up monitoring                                             |
| 12   | Infrastructure as Code (IaC)                      | Consider IaC                                                  |
| 13   | Deployment Strategies, Orchestration, Maintenance | Consider a deployment strategy, The simulation is taken down  |
| 14   | Report                                            |                                                               |
| 15   | Report + Exam Preparation                         |                                                               |


---

## Teams

#### Remember!!!! I really want the Teams room to be lively. If you make it nice to post in the channels, then you improve the overall course experience for yourselves.


Teams subchannels:

| Channel Name     | Explanation                                                                                                                                                    |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **General**      | Course material, lecture corrections, course information and anouncements.                                                                                                                                  |
| **Assignments**  | For the mandatories and handing in missed assignments.                                                                                                         |
| **Not_in_a_group** | For help with group formation, especially for students who are not present the first week.                                                                      |
| **Course_Help**        | I will happily respond to questions here. Especially things regarding the course material, big or small. This involves questions about the course meta, the course material, the tutorials (e.g., "I don't understand this tutorial at all, I am stuck and I think it's the tutorial's fault"), the assignments, etc. If you are using what feels like an unreasonable amount of time on a tutorial then the problem is probably not you. Please don't hold back. |
| **Help_Each_Other**         | The purpose of this channel is to give you a free space to communicate in. You can write to each other for help or even inspiration. I will not be as active, and you can help each other across groups here. You can @ me or take it to A_Q+A if you had a discussion involving multiple people and everyone is stuck. This is for help with setup, debugging, etc. |
| **Random**  | For inspirational links and miscellaneous discussions. Everyone is encouraged to post random DevOps related things here here.                                                                                                         |


---

## Choices and challenges

Create a group document for choices and challenges.

The document doesn't have to be long but enough for you to look up later and recall the challanges. 

**Motivation**: This will help knowledge share across your team. It is also good advice for your main thesis. Show the work!

### Choices

For every major problem you encountered, you must:

- Write down how you made the choice

- Write down relevant considerations your group had 

- Reflect in retrospect on the pros and cons of your choice


### Challenges

For every major choice you've made, you must:

- Write down the considerations you had regarding other choices

- Reflect on the pros and cons of the choice as you make it

- Later on add a reflection on how the choice turned out and unexpected consequences

---

## PR, Please

I really want you to take ownership of the course material and interact with it critically. 

Make Pull Requests to suggest changes. It can be anything from fixing typos, improving explanations or tutorials etc. 







# File: exam_presentation_requirements.md

# Exam Presentation Requirements

---

## The Format

This is taken directly from the source of truth, [Kea Katalog](https://katalog.kea.dk/course/3050407/2024-2025):

> Eksamen starter som et gruppeoplæg/-præsentation, der varer i 5 minutter per studerende. Herefter individuel eksamination i 20 minutter inkl. votering.

Remember that the allotted time always includes getting into the room, setting up and getting out. I recommend that you try to connect your computer to the projector in the exact room ahead of the exam. Maybe have a backup and have the demo ready on more than one computer.

Only have one laptop open. No timers. No notes. 

---

# Advice for the group presentation

Avoid slides. If you want to show diagrams, you could have them open in a tab.

Avoid reading. Each student only has to memorize less than 5 minutes.

Starting with an agenda brings little value. Just jump straight into the presentation.

Focus on demoing every part of the system rather than presenting through slides. This is the first time censor and I see the final product and your job is to sell us on the technical aspects of the entire system.

Both censor and I know what `whoknows` is. You can briefly flash the website without demoing it since it’s probably the least interesting part of your system. 

You can safely assume that we have read the report. This is another case for demoing, which is something the report can't do.

If you choose to show SonarQube Cloud it is more interesting to show how you've set it up to interact with a PR or push. Pointing out how few warnings you have in the dashboard is not a flex considering how easy they are to dismiss. 

---

# Advice for the individual examination

Study based on the learning goals in the semester plan. 

Have the following ready:

- The exam report
- Relevant tabs open for the website, monitoring, CI/CD pipeline, documentation, etc.
- The mandatories



# File: 03._packaging.md

<div class="title-card">
    <h1>Packaging</h1>
</div>

---

# Why package?

* **Reusability**: You can reuse your code in other projects.

* **Distribution**: You can distribute your code to others.

* **Versioning**: You can version your code.

* **Dependency management**: You can manage dependencies.

---

# How to distribute code

## As source code

All: `.zip` / `.tar.gz` for instance in GitHub Releases. 

Python: `setup.py` + `requirements.txt`

## As binary code

All: `.exe` / `.dmg` / `.deb` / `.rpm`

Java: `.jar`

C++: `.dll`

## As a container

Docker, Kubernetes, Podman. 

## As a library

Node Modules, Python Packages, Java Libraries.

---

# Examples

<img src="./assets_packaging/packages.png" alt="packages examples types of packages per language">

---

# Services

* **DockerHub**

* **GitHub**: You can distribute your code on via GitHub Packages.
    
* (+) Integrates nicely with your pipelines in GitHub Actions.

* **JFrog Artifactory**: Supports many types of artifact repositories. 

<img src="./assets_packaging/jfrog_logo.png" alt="Jfrog Artifactory logo">


---

# [Semantic versioning](https://semver.org/)

**Major**: MAJOR version when you make incompatible API changes

**Minor**: MINOR version when you add functionality in a backward compatible manner

**Patch**: PATCH version when you make backward compatible bug fixes

Additional labels for pre-release and build metadata are available as extensions to the `MAJOR.MINOR.PATCH` format.






# File: 04._virtualization_containerization.md

<div class="title-card">
    <h1>Virtualization vs. containerization</h1>
</div>

---

# What is virtualization? What can you virtualize?

*What is virtualization?*

*Given a computer, what can you virtualize?*

---

# Virtualization

**Definition**: Virtualization is the process of creating a software-based (or virtual) representation of something rather than a physical one.

**Types**:

1. **Hardware Virtualization**: Virtualization of hardware resources like CPU, memory, and storage.

2. **Software Virtualization**: Virtualization of software resources like operating systems, applications, and networks.

---

# Hypervisor

> "A hypervisor or virtual machine monitor (VMM) is *computer software*, *firmware* or *hardware* that creates and runs virtual machines. A computer on which a hypervisor runs one or more virtual machines is called a **host machine**, and each virtual machine is called a **guest machine**.

> This contrasts with **operating-system-level virtualization**, where all instances (usually called containers) must **share a single kernel**, though the guest operating systems can **differ in user space**, such as different Linux distributions with the same kernel."

<img src="./assets_virtualization_containerization/hypervisor.png" alt="hypervisor" style="height: 22vh;">

[Source: Wikipedia - Hypervisor](https://en.wikipedia.org/wiki/Hypervisor)

---

# Containerization

The benefit of containerization is to have multiple applications that share the same kernel. 

As opposed to virtual machines that require a new OS for each environment, containers do not. This makes containers lightweight.


| Containers                                                                 | Virtual Machines                                                                |
|----------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| <img src="./assets_virtualization_containerization/containers.png" alt="containers" style="width: 16vw;">  | <img src="./assets_virtualization_containerization/virtual_machines.png" alt="virtual machines" style="width: 16vw;"> |

[Source](https://web.archive.org/web/20201101123422/https://docs.docker.com/get-started/)

[Source 2](https://www.docker.com/resources/what-container/)

---

# Docker's definition of containers

> A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

> Containers isolate software from its environment and ensure that it works uniformly despite differences for instance between development and staging.

[Source: Docker Docs](https://www.docker.com/what-container)

---

# Why containerize?

*Can you think of reasons?*

---

# Benefits of containerization

**Faster Project Setup:** Installing a database + surrounding environment with a single command. 

**Portability:** Containers can run on any machine that has Docker installed.

**Reproducibility:** Consistent setup across systems.
  - Solves the "It Works on My Machine" Problem.

**Isolation:** Separate dependencies for each application. 

**Scailability**: Easier to scale individual services.

---

# Made possible by namespaces and cgroups (control groups)

The Linux kernel provides two key features for containers:

* **Namespacing**: isolates resources (hard drive, networking, hostnames, users, etc) on a machine for a particular process

* **Control Groups (CGroups)**: limits the amount of resources a process can use (CPU, memory, disk I/O, network, etc)

[Source](https://www.opsramp.com/guides/why-kubernetes/container-vs-vm/)

---

# History of containers

Containers have been around for decades before Docker. 

**1979 - 1982**: [chroot](https://en.wikipedia.org/wiki/Chroot) command in Unix enables users to create environments for processes. 

**1999**: [FreeBSD jail](https://en.wikipedia.org/wiki/FreeBSD_jail) expands on `chroot` to create isolated environments. Containers are still sometimes called jails. 

**2001 - 2008**: Linux VServer, OpenVZ, cgroups (Google) and LXC.

**2013**: The rise of Docker. Written in Go. 

---

# Modern container runtimes

[containerd](https://containerd.io/)

[Podman](https://podman.io/)

[Kata Containers](https://katacontainers.io/)

Docker

---

# Containerization and DevOps

Containers are not DevOps. But they can help you achieve DevOps. 

According to an early real-world case, Dwayne Holmes experienced how containers increase productivity by **abstracting**:

1. **infrastructure**: the dial-tone principal - you pick up the phone and it works without needing to know how it works

2. **specialization**: operations could create containers that developers could use over and over again

3. **automation**: containers can be built over and over again and everything will just work

Source: Holmes, How a Hotel Company Ran $30B of Revenue in Containers (2020)






# File: 02._build_tools.md

<!-- Build tools -->

<div class="title-card">
    <h1>Build tools</h1>
</div>

---

# What build tools / package managers do you know?

Discuss in pairs:

*OS level package managers?*

*Package managers for specific programming languages?*

*Other build tools and their build files?*

---

# OS level package managers

* **Windows**: chocolatey

* **MacOs**: homebrew

* **Linux**: apt, yum, dnf, pacman, zypper, portage, rpm, snap, flatpak, nix 
 
---

# Package managers for programming languages

<div>
    <img src="./assets_build_tools/programming_languages.png" alt="Programming Languages Package Managers"/>
</div>

---

# Build tools / Build files

<div>
    <img src="./assets_build_tools/build_files.png" alt="Build Files"/>
</div>


---

# Python Build Tools

I have placed an optional tutorial here [Python Build Tools / Virtual Environments](./assets_build_tools/python_build_tools.md) if you are interested in the different types of ways to create virtual environments in Python.

I really recommend using [poetry](https://python-poetry.org/).





# File: python_build_tools.md

# Different ways to create virtual environments in Python

Focusing on pros and cons of each and with argumentation for why we use Poetry

---

### No virtual environments

Try to run this program

```python
import emoji

print(emoji.emojize("Python is not :ambulance:"))
```

We can install it with `pip` but:
- Globally but don't want to pollute the global package space. What if projects need conflicting versions?
- Locally installed packages won't carry over to deployed servers. 

---

## virtualenv

virtualenv is handy and comes pre-installed with Python.

Then run it in the folder:
```bash
$ virtualenv .
```
OR point it to a folder you would like to virtualize:
```bash
$ virtualenv <foldername>
```

This creates the bin (binary) folder. Run activate: 
```bash
$ source ./bin/activate
```

Notice how the terminal prompt changes to indicate that you are now in a virtual environment. 

To deactivate, simply type:

```bash
$ deactivate
```

You don't want to push the bin folder. Solution:
```bash
$ pip freeze > requirements.txt 
```

To read from requirements: 
```bash
$ pip install -r requirements.txt
```

Downside: You must remember to freeze the requirements every time before you deploy. 

---

## pipenv

Install pipenv with pip. 

Run this in the folder:
```bash
$ pipenv install
```

```bash
$ pipenv install emoji
```

```bash
$ pipenv shell
```

Downside: Has its own non-standard Pipfile. Wouldn't it be nice to have a project file that follows the Python standard (PEP 518) and allows for creating and deploying Python packages?

https://peps.python.org/pep-0518/

---

## poetry

Install with or without pip (as described in the documentation). Homebrew or Choco are good ways of doing it. 

```bash
$ poetry init
```

With non-interactive mode:

```bash
$ poetry init -n
```

```bash
$ poetry install
```
```bash
$ poetry shell
```

To install additional libraries:
```bash
$ poetry add <library>
```

To initialize a project with a structure that includes tests etc.
```bash
$ poetry new <project_name>
```

---

## Bonus Info

For MacOS and Linux the virtual environments can be found here: .local/share/virtualenvs

For Windows it's probably somewhere around: %USERPROFILE%\AppData\Local\\....?

This is useful cause virtual environments cannot be named the same and can be deleted here. 



# File: 05._docker.md

<div class="title-card">
    <h1>Docker</h1>
</div>

---

# Docker terminology?

**Image**

**Container**

**Volume**

**Networking**

*Can you give informal definitions for these?*

---

# Docker terminology (informal)

**Image**: Blueprint / Recipe

**Container**: The instance of the image

**Volume**: Holds the data of the containers

**Networking**: Enables the pieces to speak


---

# Basic CLI example

Run the [hello-world container](https://hub.docker.com/_/hello-world/) from DockerHub and delete it after its execution:

```bash
$ docker run --rm hello-world
```

---

# Overview with Redis example

[https://hub.docker.com/_/redis/](Redis is a popular key-value store). 

*Can you explain the following commands?*

```bash
$ docker pull redis
$ docker run redis
```

Run in detached mode:

```bash
$ docker run -d redis
$ docker ps
$ docker stop <container-id>
```

---

# Alpine Linux

[Alpine Linux](https://en.wikipedia.org/wiki/Alpine_Linux) is a very lightweight Linux distribution.

Get an interactive [Alpine Linux](https://hub.docker.com/_/alpine/) shell:

```bash
$ docker run -it --rm alpine /bin/sh
```

`-it` is short for `i` = `--interactive` and `t` = `--tty` (Pseudo-TTY).

**Note**: Windows users might need to prefix the `docker run` with `winpty`.

Go back to the local terminal by typing `exit` in the container shell.

```bash
/ # exit
```

---

<div class="title-card">
    <h1>Volumes</h1>
</div>

---

# Volumes

Docker volumes are **external** storage for containers, like a USB drive for a laptop. The container can read and write data, but the volume persists even if the container is deleted. 

You can mount directories (volumes) from your host to a container using the `-v` flag.

1. Create a directory with a file in it locally:

    ```bash
    $ mkdir mydockerdata
    $ echo 'Hello from the host!' > ./mydockerdata/mountedfile.txt
    ```

2. Run an Alpine container and mount the directory:

    ```bash
    $ docker run -it -v ./mydockerdata:/data alpine:latest /bin/sh
    ```

*Where can I find the file?*


---

# Volumes - II

*What happens if you delete the `mydockerdata` folder locally?* 

*Let's try it*. First delete the folder locally.


1. Find the container ID:

    ```bash
    $ docker ps -a
    ```

2. Start the container and attach it to interact with it:

    ```bash
    $ docker start <CONTAINER_ID>
    $ docker attach <CONTAINER_ID>
    ```

In the container run:

```bash
$ cat /data/mountedfile.txt
```

---

# Create a volume for data

Create a volume:

```bash
$ docker volume create test-volume
```

Use the volume in a container:

```bash
$ docker run -it --rm -v test-volume:/mydata alpine /bin/sh
```

In the Alpine shell add a file to the `mydata` directory:

```bash
/ # echo 'Hello from the volume!' > /mydata/volume.txt
```

---

# Check out the content of the volume

The best way to interact with the volume is through the container. 

You could run Docker with elevated privileges to access the volume directly, but it's not recommended.

```bash
$ docker volume inspect test-volume
```

In Docker Desktop, choose volumes and choose `test-volume` to see the content.

<img src="./assets_docker/volume_docker_desktop.png" alt="volume docker desktop">


---

# Why volumes?

*Can you give use cases for when you would want to mount in a Docker container?*

---

# Volumes: That's why!

Database data:

```bash
$ docker run -d -v /my/local/data:/var/lib/mysql mysql:latest
```

Configuration files:

```bash
$ docker run -d -v /my/local/nginx.conf:/etc/nginx/nginx.conf nginx:latest
```

Sharing data between containers:

```bash
$ docker run -d -v /my/local/data:/shared/data webserver:latest
$ docker run -d -v /my/local/data:/shared/data worker:latest
```

Source code, persistent storage for applications (fx. CMS), storing log files, SSL certificates, backup local data in a container etc.

---

<div class="title-card">
    <h1>Docker Networking</h1>
</div>

---

# Docker Networking

Let's explore networks in Docker by creating a network and then have two containers join it.

Create a network:

```bash
$ docker network create mynetwork
```

Run two named containers on the `mynetwork` network:

```bash
$ docker run -dit --name container1 --network mynetwork alpine:latest
$ docker run -dit --name container2 --network mynetwork alpine:latest
```

`-d`: Runs the container in detached mode (in the background).

`-i`: Keeps STDIN open even if not attached (interactive mode).

`-t`: Allocates a pseudo-TTY (a terminal interface).

---

# Verify networking between the containers

Access `container1` by attaching it:

```bash
$ docker attach container1
```
From `container1` ping `container2` (with example response):

```bash
/ # ping container2
PING container2 (172.18.0.3): 56 data bytes
64 bytes from 172.18.0.3: seq=0 ttl=64 time=0.075 ms
...
...
```

After a while stop the ping by pressing `Ctrl+C`.

If you see no packet loss, the containers are connected. Example:

```txt
--- container2 ping statistics ---
37 packets transmitted, 37 packets received, 0% packet loss
round-trip min/avg/max = 0.110/0.225/0.566 ms
```

---

# Expose ports to the host

Run an Nginx Container:

```bash
$ docker run -dit --name webserver --network mynetwork -p 8080:80 nginx:latest
```

Check out `http://localhost:8080` in a browser.

In `container2` request the webserver on the same network (install CURL first):

```bash
/ # apk add curl
/ # curl http://webserver
```

Inspect the network to see which containers are connected and their IP addresses. 

```bash
$ docker network inspect mynetwork
```

---

# Clean up!

```bash
$ docker stop container1 container2 webserver
$ docker rm container1 container2 webserver
$ docker network rm mynetwork
```




# File: 06._dockerfile.md

<div class="title-card">
    <h1>The Dockerfile</h1>
</div>

---

# Dockerfile Python example 

<img src="./assets_dockerfile/dockerfile.png" alt="dockerfile">


```Dockerfile
FROM python:3.9-slim

WORKDIR /usr/src/app

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

# Copy all files from current directory to /usr/src/app in container
COPY . .

CMD ["python", "app.py"]
```

*Can you explain each line?*

---

# Dockerfile Node.js example 

```Dockerfile
FROM node

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080
CMD [ "npm", "start" ]
```

*Can you explain each line?*

---

# Note on EXPOSE

`EXPOSE` is a way to document the port(s).

It doesn't actually publish the port (make them accessible to the outside). 

[Source](https://docs.docker.com/reference/dockerfile/#expose)

---

# Two ways to start

One runs the file directly. The other runs a start script defined in `package.json` that likely does the first option.

```Dockerfile
CMD ["node", "app.js"]
# AND
CMD ["npm", "start"]
```

---

# Running commands in Dockerfile

RUN can be specified multiple times while CMD and ENTRYPOINT can only be specified once.

```Dockerfile
RUN npm install
```

Two possible syntaxes:

```Dockerfile
CMD ["node", "app.js"]
# OR
CMD node app.js
```

ENTRYPOINT example:

```Dockerfile
ENTRYPOINT ["node", "app.js"]
```

---

# RUN vs CMD vs ENTRYPOINT

**RUN**: Executes during the build phase to set up the image. Can be run multiple times.

**ENTRYPOINT**: Defines the main command to run when the container starts. You can pass flags when running the container.

**CMD**: Provides the default command to execute when starting a container. You can override `CMD` when running the container by adding `node another_app.js` after `docker run <image_name>` for example. 

You can combine the last two:

```Dockerfile
ENTRYPOINT ["node"]
CMD ["app.js"]
```

Which gives the freedom to do the following:

```bash
$ docker run --entrypoint node_runtime_latest <image_name>
$ docker run <image_name> another_app.js
```

---

# Let's set up a Python flask project

Make the folder and create the virtual environment:

```bash
$ mkdir 03._Docker_Python_Project
$ cd 03._Docker_Python_Project
$ python -m venv venv
```

*Nix users:

```bash
$ source ./venv/bin/activate
```

Windows users:

```powershell
$ .\venv\Scripts\activate
```

Install flask and save the dependency:

```bash
$ pip install flask
$ pip freeze > requirements.txt
```

---

# Setup the server

Create a file named `app.py` and in it:

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def hello_world():
    return { "data": 'Hello, World!' }

if __name__ == '__main__':
    app.run(host="0.0.0.0", port=8080)
```

Explicitly binding the host to `0.0.0.0` is essential to be able to access the server from outside the container.

---

# Create the `Dockerfile`

```Dockerfile
FROM python

WORKDIR /usr/src/app

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 8080
CMD ["python", "app.py"]
```

---

# Build and run

Let's name the image `python_project` (remember the period at the end to specify the build context):

```bash
$ docker build -t <image_name> .
```

We want to map both the host port and the container port to `8080`:


```bash
docker run -p <host_port>:<container_port> <image-name>
```

*Can you figure it out?*

---

# Build and run solution

Solution: 

```bash
$ docker build -t python_project .
$ docker run -p 8080:8080 python_project
```

Combined:
    
```bash
$ docker build -t node_project . && docker run -p 8080:8080 python_project
```


---

# Dockerfile create a non-root user for privilege separation

```Dockerfile
FROM python

RUN adduser --system --home /home/appuser appuser

WORKDIR /usr/src/app

COPY requirements.txt ./

RUN pip install --no-cache-dir --upgrade pip && pip install --no-cache-dir -r requirements.txt

COPY . .

USER appuser

EXPOSE 8080
CMD ["python", "app.py"]
```

---

# Check user

Run it with an interactive shell:

```bash
$ docker build -t python_project .
$ docker run -it --rm python_project /bin/sh
```

See the user:

```bash
$ whoami
appuser
```

Check out who owns the files:

```bash
$ ls -l
```

<img src="./assets_dockerfile/file_user_ownership.png" alt="docker created user and file ownership" style="height: 10vh;">

Not surprising but in other languages and with other user configuration you might run into issues such as ownership and certain users not being able to access files.

---

<div class="title-card">
    <h1>.dockerignore</h1>
</div>


---

# .dockerignore

<img src="./assets_docker/dockerignore_logo.png" alt="docker gitignore logo">

*What are files and folders to ignore?*

---

# `.dockerignore` possible python template

```plaintext
**/.git
**/.gitignore
**/.vs
**/.vscode
**/__pycache__
**/*.pyc
**/*.pyo
**/*.pyd
**/*.db
**/*.sqlite
**/.venv
**/venv
**/env
**/.mypy_cache
**/.pytest_cache
**/.coverage
**/htmlcov
**/logs
**/secrets.dev.yaml
**/values.dev.yaml
```

Let's add it to the project.

---

<div class="title-card">
    <h1>Docker layers</h1>
</div>

---


# Docker layers

Each image consists of a layer. 

When you build an image, Docker creates a new layer for each instruction in the Dockerfile. 

When you change the Dockerfile and rebuild the image, only the layers that have changed are rebuilt.

Inspect the layers with:

```bash
$ docker history <image-name>
```

---

# Docker layers optimization

When building an image, Docker will only execute instructions from top to bottom. But it only executes the instructions that have changed.

Otherwise it will reuse the layers from the cache.

This file is not optimized. *How can we use Docker's caching mechanism more efficiently?*

```Dockerfile
FROM node

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 8080

CMD [ "node", "app.js" ]
```

---

# Improved Dockerfile

If there is no change to `package.json` then there is no need to run `npm install` again.  

```Dockerfile
FROM node

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "app.js" ]
```

---

# Dockerfile optimization result

<img src="./assets_dockerfile/optimized_node_build.png" alt="dockerfile optimized node build" style="height: 50vh;">






# File: 01._introduction.md

<div class="title-card">
    <h1>Docker, Continuous Delivery, The Simulation</h1>
</div>


---

# Not in a group

---

# Weekly commit activity

<iframe src="./assets_introduction/commit_activity_weekly.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_weekly.svg" />
</div>

---

# Daily commit activity

<iframe src="./assets_introduction/commit_activity_daily.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_daily.svg" />
</div>


---

# Do not leak sensitive information

Don't push the SQLite database file into the repository!

We have a database. How do we securely get it to the server is a fun challenge. 

---

# Weekly DevOps Principle!

**Fail fast, recover fast**



# File: 02._github_actions.md

<div class="title-card">
    <h1>GitHub Actions</h1>
</div>

---

# Do you know the difference?

<div style="display: flex; align-items: center;">
    <img src="./assets_introduction/git_logo.png" alt="Git Logo" style="width:20vw; background: white;"/>
    <img src="./assets_introduction/github_logo.png" alt="GitHub Logo" style="width:20vw; background: white;"/>
</div>

*Discuss in pairs*

---

# Let's install GitHub CLI (`gh`)

https://cli.github.com/


This is required only once:

```bash
$ gh auth login
```

Then we can run commands like:

```bash
$ gh repo create
$ gh repo delete
$ gh issue create
$ gh pr create
$ gh workflow run
```

...and many more.


---

<div class="title-card">
    <h1>GitHub Actions</h1>
</div>

---


# How to create a workflow

First let's create a new repository with:

```bash
$ gh repo create
```

Then create any YAML file in the `.github/workflows` directory.

---

# YAML indentation should be 2 spaces

The problem is that VSCode defaults to 4 spaces (in the workflows folder). Here is how to change it:

<img src="./assets_github_actions/01._change_tab_size.png" alt="vscode change tab size yaml" style="height: 12vh;">

<img src="./assets_github_actions/02._change_tab_size.png" alt="vscode change tab size yaml" style="height: 15vh;">

<img src="./assets_github_actions/03._change_tab_size.png" alt="vscode change tab size yaml" style="height: 15vh;">

---

# GitHub Actions

An Action creates an automation based on triggers related to repositories. Run common tasks in repeatable fashion.

Anders' definition: 

> A GitHub Action allows us to borrow a server at GitHub to run some commands for a short while.

<img src="./assets_github_actions/ci_cd_platform_github_actions.png" alt="GitHub Actions logo" style="height: 30vh;">

---

# Alternatives offered by other Git platforms


- **BitBucket**: Atlassian Bamboo:

<img src="./assets_github_actions/ci_cd_platform_atlassian_bamboo.png" alt="Atlassian Bamboo logo" width="200" height="100">

- **Gitlab**: Gitlab CI/CD:

<img src="./assets_github_actions/ci_cd_platform_gitlab_ci_cd.png" alt="Gitlab CI/CD logo" width="100" height="100">

---

# Why use GitHub Actions?

* (+) You are already using GitHub

* (+) It’s free with some limitations (but the alternatives have the same limitation)

https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions#included-storage-and-minutes

* (-) The free version is slow


---

# GitHub Actions Marketplace

Contains useful templates for Actions

Community Actions

Create custom actions and upload them to the marketplace


---

# GitHub Actions (terminology) - I

**Event**: Triggers that start a workflow

**Workflows**: Defines an automation from start to finish

**Jobs**: A workflow contains one or more jobs. A job is one or more steps.

**Steps**: Simple commands, shell scripts or actions. Steps can’t run in parallel. Runs in sequence from top to bottom.


---

# GitHub Actions (terminology) - II

**Runner**: Compute layer where jobs are executed. Each job has its own runner.

Runners can run in parallel.

GitHub provides 3 types of runners: Ubuntu, Windows and MacOS.

Using a self-hosted runner is also possible.

GitHub runners comes with pre-installed tools, runtimes and compilers that require minimal configuration.

---

# Single Workflow - Overview I

<img src="./assets_github_actions/github_actions_overview_II.png" alt="GitHub Actions Overview" width="1000" height="500">

---

# Overview II

<img src="./assets_github_actions/github_actions_overview_III.png" alt="GitHub Actions Overview" width="1000" height="500">

---

# Great Video!

I really recommend this video. 

[![Video Link](https://img.youtube.com/vi/-hVG9z0fCac/0.jpg)](https://youtu.be/-hVG9z0fCac?list=PLArH6NjfKsUhvGHrpag7SuPumMzQRhUKY&t=138)

His others videos in the series are unfortunately not as useful. (I mention this so you can better invest your time).

---

# Overview from the video

<img src="./assets_github_actions/github_actions_overview_I.png" alt="GitHub Actions Overview" width="1000" height="500">

---


# Technical requirements:

Workflows must be stored in the `.github/workflows` folder.

Workflows are defined with YAML.

Workflows must define:

* Trigger and branches 
* Permissions
* Job and runner 
* Steps

---



# Workflows from templates

Check out the actions tab in the repository to discover preset workflow templates. 

<div>
    <img src="./assets_github_actions/workflow_template.png" alt="Preset workflow from template" style="height: 45vh;" />
</div>

---

# Choose an action from the marketplace

In the actions tab choose this workflow:

<img src="./assets_github_actions/node_github_action_marketplace.png" alt="Node GitHub Actions Marketplace" style="height: 30vh;">

---

# The checkout action (actions/checkout@v3)

Allows one to clone the repository code to the runner. 

Made by GitHub: https://github.com/actions/checkout

The following can be specified: 

`@<tag>`, `@<branch>`, `@<commit_sha>`

---

# Let's do it ourselves from scratch!

But this time manually (this is how we will be doing it from now on).

```bash
$ gh repo create

$ mkdir .github

$ cd .github

$ mkdir workflows

$ cd workflows
```

Create `hello_world.yaml`


---

# Hello World workflow

Let's manually create a workflow that echoes (logs) "Hello World" on every push and PR.

1. Create a new repository. 

2. Create `.github/workflows`

3. In it, create a file called hello_world.yaml

---

# In hello_world.yaml 


```yaml
name: Hello world workflow

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  hello:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Run hello world
        run: echo "Hello world"
        shell: bash
```

---

# Let's study the above snippet - Can you spot the uneccessary part?

---

# workflow_dispatch

workflow_dispatch provides a UI button so that a workflow can be triggered in the GitHub UI without the above event triggers.

Under the `on` key add the following: 

```yaml
on: 
    workflow_dispatch:
```




# File: 08._running_in_production.md

<div class="title-card">
    <h1>Running code in production</h1>
</div>

---

# Node.js in production

Some of you may have heard of `node` and `nodemon`. 

But these are not suitable for production.

**Why? What would be better?**

---

# PM2 - Running Node.js in production - Part I

Install PM2:

```bash 
$ npm install pm2 -g
```

Start the application:

```bash 
$ pm2 start app.js
```

List All Running Applications:
 
```bash
$ pm2 list
```

---

# PM2 - Running Node.js in production - Part II

Stop the application: 

```bash
$ pm2 stop <app_name_or_id>
```

Delete an Application from PM2's List:

```bash
$ pm2 delete <app_name_or_id>
```

---

# Python in production

The same is true for Python. `gunicorn` is recommended for production. 

Here is how to run the Flask application with 4 worker processes. 

```bash
$ gunicorn -w 4 -b 0.0.0.0:8000 app:app
```

Also in the server configuration in Flask remember to set `DEBUG=FALSE`.

---

# Course spoiler - Reverse proxies

As the course progresses, you can start considering a reverse proxy like `nginx`.

Using a reverse proxy is a good practice for production. 

There are many benefits such as HTTP caching, load balancing etc. 

We will explore them when we talk about security. 





# File: 06._more_cloud.md

<div class="title-card">
    <h1>More Cloud - Other cloud services and cloud providers</h1>
</div>

---

# Cloud Providers

<div>
    <img src="./assets_cloud_and_azure/top_cloud_providers.png" alt="Top Cloud Providers" style="height: 40vh;"/>
</div>

---

# Cloud storage

AWS: S3 (Simple Storage Service)

<img src="./assets_cloud_and_azure/aws_s3_logo.png" alt="AWS S3" width="200" height="100">

Azure: Azure Blob Storage

<img src="./assets_cloud_and_azure/azure_blob_storage_logo.png" alt="AWS S3" width="200" height="100">

---

# Azure Blob Storage - I

Use the one under Free Services. 

<img src="./assets_cloud_and_azure/azure_blob_storage_free_service.png" alt="Azure blob storage free service" width="200" height="100">

A Blob Storage can contain multiple contains. Try to upload a file but create a container first. 

Anonymous access level (No other access level is allowed on Azure For Students):

* Private (no anonymous access)

---

# Azure Blob Storage - II

Access not permitted when trying to open the file:

<img src="./assets_cloud_and_azure/azure_blob_storage_access_not_permitted.png" alt="Azure blob storage access not permitted">

Here are the thing that can be done: 

1. Enable Anonymous Public Read Access 

2. Using Azure AD (Active Directory)

3. Generate a Shared Access Signature (SAS) URL

---

# Shared Access Signature (SAS)

There is a subfolder in this folder titled `generating_sas_token_azureblobstorage` in it you will find a code example in Node.js for how to generate a SAS token. 

Read the README.md to see how. The instructions assume that `az` has been installed. 


---

# AWS S3 policies

Policy Generator: 

https://awspolicygen.s3.amazonaws.com/policygen.html

---

# Serverless computing

<img src="./assets_cloud_and_azure/aws_lambda_vs._azure_functions.png" alt="AWS Lambda vs. Azure Functions" style="height: 30vh">


---

# Why serverless?

Saves time. Easier to deploy.

Scalable. 

Saves money. (Azure Functions Different pricing plans.)


---

# Azure Functions - subscription models

* **Consumption plan**: Pay for the time that your code runs.

* **Premium plan**: You specify a number of pre-warmed instances that are always online. 

* **App service plan**: Run as if they are web apps. Not serverless.

---

# Cold starts - A problem

Cold start: The time it takes to allocate the function to a server and setup the runtime environment before your code can run.

Functions are held warm for roughly 20 minutes according to below source.


<img src="./assets_cloud_and_azure/cold_start.png" alt="Cold start" style="height: 30vh">



(Source: https://azure.microsoft.com/en-us/blog/understanding-serverless-cold-start/)

---

# More cold start metrics

<img src="./assets_cloud_and_azure/cold_start_per_language.png" alt="Cold start per language" style="height: 30vh">


(Source: https://mikhail.io/serverless/coldstarts/azure/)

---

# Triggers and bindings

https://learn.microsoft.com/en-us/azure/azure-functions/functions-triggers-bindings?tabs=isolated-process%2Cpython-v2&pivots=programming-language-csharp#supported-bindings

---


# Azure Key Vault

A way to store values outside of the code such as environment variables. 

Can be used to authenticate services. 
Also useful for authorization. Access policies can limit usage.

Example use case:
Define the database connection string here. Functions can then get the connection string from the Key Vault. Now it’s removed from the code and can be changed in one place.






# File: 09._deployment_considerations.md

<div class="title-card">
    <h1>Deployment considerations</h1>
</div>

---

# Let's brainstorm: Simple deployment strategies

How would you go about deploying new versions of the application?

I am not looking for the optimal solution since your deployment strategy is bound to change throughout the course.

Our goal with the brainstorming session is to end with a simple solution that you could implement today.

*Suggestions?*

---

# Ways to deploy a new version of an application

1. File transfer via SCP/FTP -> manual restart

2. SSH -> git pull -> manual restart

3. Cron job on the server that keeps syncing with a git repo

4. Using build systems / CI/CD

There are 2 types of deployment strategies.

*If you had to put to group two of the list items in one group and two in the other, which would it be?*

---

# Push vs. Pull-based Deployment

`1` and `4` are push-based deployment strategies.

`2` and `3` are pull-based deployment strategies.

[![Push vs. Pull-based deployment](http://img.youtube.com/vi/f5EpcWp0THw/0.jpg)](https://youtu.be/f5EpcWp0THw?list=PLy7NrYWoggjxKDRWLqkd4Kbt84XEerHhB&t=418)

For now pull-based deployment will do, but we are aiming for push-based deployment.

---

# Remember to continuously improve your deployment strategy

It's great if you can get something working quickly.

You will get many chances to iterate on your deployment strategy.

But be willing to discard it as something better presents itself.

This course is about letting go of legacy, even the parts you create. 

---

# Next Week - Trial run

Make sure that you have deployed and made a PR to `repositories.py` with the IP address.

We will make a trial run of the simulation next week so you get 1 week to fix issues. 

The real simulation starts in 2 weeks.



# File: 07._ssh.md

<div class="title-card">
    <h1>More about SSH</h1>
</div>


---

# SSH files

```bash
$ ls -la ~/.ssh
```

*What files do you see? What are their respective purposes?*

---

# Public private key pairs

*Which is the public key? Which is the private key?*

[Public-key cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)

---

# Try to answer these questions in pairs

1. *If a GitHub Action needs to SSH into a server, which key should be defined in the GitHub Action: public or private?*

2. *If I have provisioned a server and **now** I want to SSH into it from my local machine, which key do I use: public or private?*

3. *If I have provisioned a server and want to configure it to allow SSH access from my other local machine with a different SSH key, which key do I save on the server: public or private?*

"To provision a server" means to set up a server.

Number 3 can be achieved by pasting your key in the `~/.ssh/authorized_keys` file on the server.

---

# SSH Config - A helpful tip

So you don't have to remember or write keep the IP address close. 


Here is how you define it. In the `~/.ssh/config` file. 

Add something like this:

```bash
Host devopscourse
    HostName 169.89.31.226
    User admin
```

Now, instead of having to type `ssh admin@169.89.31.226` every time you can simply invoke it with:

```bash
$ ssh devopscourse
```










# File: 04._github_secrets.md

<div class="title-card">
    <h1>GitHub Secrets</h1>
</div>

---

# Define the secret in the GUI

1. Go to the repository
2. Click on `Settings`
3. On the left side choose `Secrets and Variables`
4. Click on `Actions`
5. Click on `New repository secret`
6. Add the secret `GREETING` and value `Hello`

---

# What are the 3 top-level keys that a Github workflow must have?

---

# Required keys: Answer

1. `name`
2. `on`
3. `jobs`



---

# The workflow file

```yaml
name: Working with secrets in GitHub Actions

on:
    push:
        branches:
        - main

jobs:
    build:
        runs-on: ubuntu-latest

        steps:
        - name: Print the secret
          run: echo ${{ secrets.GREETING }}
```

---

# GitHub Actions Secrets are secret

As a security measure Github Action prevents us from logging the secrets.

---

# Let's set secrets through the `gh` CLI

```bash
$ gh secret set <secret_name>
```

1. Run `gh secret delete GREETING` in the terminal.

2. Check the secrets browser page.

2. Run `gh secret set GREETING` in the terminal.

3. Refresh the browser page.

---

# Clean up time - Delete the repository 

While in the repository run:

```bash
$ gh repo delete
```


# File: 03._github_issues_workflow.md


<div class="title-card">
    <h1>GitHub Issues Workflow</h1>
</div>


---

# Let's try to automate publishing a comment every time an issue is created

What is a GitHub Issue? Why is auto-commenting useful?

---

# GitHub Actions - Context

Contexts inject useful information into the server environment. 

Can be accessed via `${{ <context> }}`.

https://docs.github.com/en/actions/learn-github-actions/contexts

For example, we can access repository meta information through `${{ github }} `. 

*Let's look for where the issue number is defined.*

---

# Dump the context to examine it

```yaml
name: Create a comment on new issues
permissions:
  issues: write
on:
  issues:
    types: [opened]
jobs:
  comment:
    runs-on: ubuntu-latest
    steps:
      - name: "Dump GitHub context"
        run: echo '${{ toJson(github) }}'
```

*Where is the issue number?*

---

# Found it?

Under issue it is called "number". 

Note: toJson is a utility provided by GitHub Actions.

---

# Use the following package

https://github.com/marketplace/actions/create-or-update-comment

But replace issue-number: 1 with: ${{ github.event.issue.number }}

```yaml
      - name: Create comment
        uses: peter-evans/create-or-update-comment@v3
        with:
          issue-number: 1
          body: |
            This is a multi-line test comment
            - With GitHub **Markdown** :sparkles:
            - Created by [create-or-update-comment][1]
            
            [1]: https://github.com/peter-evans/create-or-update-comment
          reactions: '+1'

```

---





<!-- Using the GitHub API in workflows -->

<div class="title-card">
    <h1>Using the GitHub API in workflows</h1>
</div>

---

# Using the GitHub API in workflows

```yaml
comment-with-api:
        runs-on: ubuntu-latest
        steps:
        - name: Create comment with API
            run: |
            gh api -X POST \
                /repos/${{ env.ORGANIZATION }}/${{ env.REPOSITORY }}/issues/${{ env.ISSUE_NUMBER }}/comments \
                -f body='This is a multi-line test comment from the API'
            env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
            ORGANIZATION: ${{ github.repository_owner }}
            REPOSITORY: ${{ github.event.repository.name }}
            ISSUE_NUMBER: ${{ github.event.issue.number }}
```



# File: 05._azure.md

<div class="title-card">
    <h1>Azure</h1>
</div>

---

# Azure data centers

<div>
    <img src="./assets_cloud_and_azure/azure_data_centers.png" alt="Azure data centers" style="height: 50vh;"/>
</div>


---

# Cost management - Resource Groups I


Please beware that even if no services are running, if a resource group exists it can still use a lot of money. Delete resource groups when not in use. 

Exception: Network Watcher:

https://learn.microsoft.com/en-us/azure/network-watcher/network-watcher-overview

---

# Cost management

Recommendation: When possible use free services. 

<div>
    <img src="./assets_cloud_and_azure/azure_free_services.png" alt="Azure free services" style="height: 30vh;"/>
</div>

I have provided a guide with the course material on how to setup limitations on Pay-As-You-Go accounts (not Azure for students).

---


<div class="title-card">
    <h1>Virtual Machines</h1>
</div>

---

# Virtual machines 

Virtual machine is the generic term for servers in the cloud.

In AWS they are called **EC2**. In Azure, **Azure Virtual Machines**.

Let's manually create a virtual machine (through Azure Free Services). 

But first, let's generate an SSH key locally which we will use to login.

---

# Generating a SSH-key

Generate a 4096-bit RSA SSH-key pair. 

*nix (tldr ssh-keygen):

```bash
$ ssh-keygen -t rsa -b 4096
```

Windows (2048-bit RSA key is the default): 

```powershell
$ ssh-keygen -m PEM -t rsa -b 4096
```

Just press enter 3 times and go with the defaults. No need to enter a passphrase.

https://learn.microsoft.com/en-us/azure/virtual-machines/linux/create-ssh-keys-detailed

---

# Let's create a virtual machine

Various OS to choose from. We will use the latest version of Ubuntu.

Allow port 22 so we can ssh into it. 

<div>
    <img src="./assets_cloud_and_azure/allow_port_22.png" alt="Port 22 ssh inbound rule allow"/>
</div>

---

# SSH into the virtual machine

In case of permission issues:

```bash
$ chmod 600 /path/to/your/file.pem
```

---

# The `apt` package manager

Since we setup an Ubuntu server we can use the default package manager for Debian. 

Ubuntu is a flavor within the broader Debian ecosystem.

If a package exists in the default repository we can run:

```bash
$ sudo apt install <package_name>
```

---

# Upgrade the Ubuntu server

When you provision a new server it's a good idea to upgrade it. Here is how: 

```bash
$ sudo do-release-upgrade
```

Alternative way:

```bash
$ sudo apt update
$ sudo apt full-upgrade
```

---

# Network management: Ports I

There are two type of rules:

1. Inbound: Traffic going **TO** the VM.

2. Outbund: Traffic going **OUT** from the VM. 

Define an inbound rule to whitelist the port that the application is running on so we can access it from the internet.

---
 
# Network management: Ports II

<img src="./assets_cloud_and_azure/vm_network_port.png" alt="network vm port">


---

# Create a static IP address

https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/virtual-networks-static-private-ip-arm-pportal

---

# Let's tear it down!

Delete it and **REMEMBER** to also delete the resource group!

**Repetition**: In Azure, a resource group will still cost money, even if there is no service associated with. 







# File: 01._introduction.md


<div class="title-card" style="color: cyan;">
    <h1>Github Actions, Cloud, Azure, Deploy</h1>
</div>

---

# Weekly commit activity

<iframe src="./assets_introduction/commit_activity_weekly.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_weekly.svg" />
</div>

---

# Daily commit activity

<iframe src="./assets_introduction/commit_activity_daily.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_daily.svg" />
</div>

---

# Weekly DevOps Principle!

**Reduce WIP (Work In Progress)**

Avoid large batch sizes.

Limit active branches. Merge branches to trunk at least daily.

Avoid long-lived branches.


---

# Simple is always best

Given how simple the frontend is, would React be the right choice?

How does the frontend benefit from a component based web framework?

It's also on me for not properly explaining that the website will not grow in complexity much.

I do not grade higher if you chose a more complex solution when a simpler solution does the job just as well. 

I only value complex solutions if they come with additional benefits such as scalability, maintainability, etc.

Remember, during the exam everything should pass the "*why*" test. 

If you want to put in an extra effort right away, then use that energy on creating tests. Unfortunately, we won't cover that until much later.



# File: 02._databases_orm.md


<div class="title-card">
    <h1>Databases, ORM</h1>
</div>

---

# What is the most important thing to remember when choosing a database?

---

# It should be the right choice for your use case

There are many other arguments to consider, but if the above condition is not satisfied then the rest is irrelevant.

Discussion: *Is the argument "that's the database I know best" valid?*

---

# SQLite is actually good enough

You will never run into limitations with SQLite for most web applications! Especially in Denmark.

[Fun SQLite facts](https://avi.im/blag/2024/sqlite-facts/)

---

# Should you use an ORM?

In this project, given its scope, fixed deadline and data complexity an ORM does not make sense. There isn't going to be more functionality on the serve from this point on.

I want you to be aware that it is not always a good choice.

An ORM is either equal to or less efficient than writing raw SQL. An ORM is not "more secure". 

When creating a small project or MVP, developers shouldn't waste their time on setting up an ORM.

I will accept during the exam that the reason you set up an ORM was to learn how to use it for the language you are using.

---

# PostgreSQL vs. MySQL

MySQL is a proprietary database, while PostgreSQL is open-source. 

Scalability and high available features for MySQL are locked behind the Enterprise Edition.  

MySQL is more used, historically, but that's changing as PostgreSQL is [the preferred choice today](https://survey.stackoverflow.co/2023/#section-most-popular-technologies-databases).

PostgreSQL supports JSON and JSONB data types, while MySQL has limited support.

https://www.datacamp.com/blog/postgresql-vs-mysql



---

<div class="title-card">
    <h1>ORM / Migrations</h1>
</div>

---

# What is an ORM?

*How did you work with JPA last semester?*

---

# Example: Objection.js

How to create models:

https://vincit.github.io/objection.js/guide/models.html

How to query:

https://vincit.github.io/objection.js/guide/getting-started.html


---

# Prisma

[Prisma](https://www.prisma.io/orm) officially supports Javascript and Typescript. Community support for Rust, Python, Dart and Go.

https://playground.prisma.io/




# File: 08._scrapy.md

<div class="title-card" style="color: cyan;">
    <h1>Hands-on: Scrapy</h1>
</div>

---

# Wikipedia Spider

Inspired by this:
https://www.proxiesapi.com/blog/how-to-scrape-wikipedia-using-python-scrapy.html.php

Install Scrapy with `virtualenv`:

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install scrapy 
```

**OR** with `poetry`:

```bash
$ poetry init -n
$ poetry add scrapy
$ poetry shell
```

---

# Generate a new Scrapy project

Scaffold a new Scrapy project:

```bash
$ scrapy startproject wikicrawler
$ cd wikicrawler
```

---

<div class="title-card" style="color: cyan;">
    <h1>Method 1 - Create a spider and run it</h1>
</div>

---

# Create a spider

Inside of the wikicrawler folder:

```bash
$ scrapy genspider WikiPageSpider https://en.wikipedia.org/wiki/List_of_common_misconceptions
```

---

# Create a WikipageSpider

Update the file /wikicrawler/wikicrawler/spiders/WikiPageSpider.py with the following code:

```python
import scrapy
from scrapy.linkextractors import LinkExtractor
from scrapy.spiders import CrawlSpider, Rule

class WikipageSpider(CrawlSpider):
    name = 'WikiPageSpider'
    allowed_domains = ['en.wikipedia.org']
    start_urls = ['https://en.wikipedia.org/wiki/List_of_common_misconceptions']

    rules = (
        Rule(LinkExtractor(allow=r'/wiki/'), callback='parse_item', follow=True),
    )

    def parse_item(self, response):
        yield {
            'url': response.url,
            'title': response.css('h1::text').get(),
            'content': response.css('p::text').getall()
        }
```

---

# Run the spider

Run spider and output content:
```bash
$ scrapy crawl WikiPageSpider -o output.json
```

---

# Filter out already processed URLs

```python
# ....
    rules = (
        Rule(LinkExtractor(allow=r'/wiki/'), callback='parse_item', follow=True, process_links='process_links'),
    )

    visited_urls = set()

    def parse_item(self, response):
        if response.url in self.visited_urls:
            return
        self.visited_urls.add(response.url)
        
        yield {
            'url': response.url,
            'title': response.css('h1::text').get(),
            'content': response.css('p::text').getall()
        }
    
    def process_links(self, links):
        # Filter out already visited URLs
        return [link for link in links if link.url not in self.visited_urls]
```

---

# Add politeness

Add custom settings to the Spider class as a field:

```python
    custom_settings = {
        'DOWNLOAD_DELAY': 1,
        'CONCURRENT_REQUESTS': 8,
        'CONCURRENT_REQUESTS_PER_DOMAIN': 2,
        'AUTOTHROTTLE_ENABLED': True,
        'AUTOTHROTTLE_START_DELAY': 1,
        'AUTOTHROTTLE_MAX_DELAY': 10,
        'AUTOTHROTTLE_TARGET_CONCURRENCY': 1,
        'RANDOMIZE_DOWNLOAD_DELAY': True,
        'LOG_LEVEL': 'DEBUG'

    }
```

---

<div class="title-card" style="color: cyan;">
    <h1>Method 2 - Scrape directly from the shell</h1>
</div>

---

# Use the shell

Interact via shell:

```bash
$ scrapy shell https://en.wikipedia.org/wiki/List_of_common_misconceptions
```

To see response in the shell:
```bash
> response 
```

To get the title:

```bash
> response.css('h1').get()
```


To get the text content add ::text at the end of the selector:
```bash
> response.css('h1 > span ::text').get()
```

---

# Another good resource on Scrapy

[![Scrapy for Beginners - A Complete How To Example Web Scraping Project](http://img.youtube.com/vi/s4jtkzHhLzY/0.jpg)](https://www.youtube.com/watch?v=s4jtkzHhLzY&list=PLRzwgpycm-Fjvdf7RpmxnPMyJ80RecJjv&index=5)





# File: 07._beautifulsoup4.md

<div class="title-card" style="color: cyan;">
    <h1>Hands-on: BeautifulSoup4</h1>
</div>

---

# Install BeautifulSoup4

https://pypi.org/project/beautifulsoup4/

Install BeautifulSoup4 with `virtualenv`:

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install beautifulsoup4 requests
```

On Windows instead of `source venv/bin/activate` (omit `source` if using Powershell):

```powershell
$ source venv\Scripts\activate
```


**OR** with `poetry`:

```bash
$ poetry init -n
$ poetry add beautifulsoup4 requests
$ poetry shell
```

---

# Use the `lxml` parser

[More about parsers and BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-a-parser)

```python
import requests

html = requests.get("https://en.wikipedia.org/wiki/List_of_Monty_Python_projects").text

from bs4 import BeautifulSoup


html_parsed = BeautifulSoup(html, features="lxml")
```

*Something is missing? What is it?*

---

# You need to install the parser

```bash
$ pip install lxml
```

**OR** with `poetry`:

```bash
$ poetry add lxml
```

...

*Now we need to get the content of the article. Inspect the DOM and find the right tag.*

---

# Solution: Get the main article

```python
tags = html_parsed.find("div", { "class": "mw-parser-output" })
```

---

# Loop through the tags

```python
projects = {}

current_category = None

for tag in tags:
    if tag.name == "div" and "mw-heading" in tag.get("class", []):
        current_category = tag.text.replace("[edit]", "")

        projects[current_category] = []
    elif tag.name == "ul":
        for li in tag.find_all("li"):
            projects[current_category].append(li.text)
```

---

# Clean up

After the loop, clean up the dictionary and pretty print it:

```python
del projects["References"]
del projects["Notes"]
del projects["Further reading"]

from pprint import pprint
pprint(projects)
```


---

# Another example: Web Crawler with BeautifulSoup4

```python
import requests
from bs4 import BeautifulSoup
import re

BASE_URL = "https://en.wikipedia.org"

visited_pages = set()
to_visit_queue = []


def get_parsed_wiki_page(endpoint):
    html_page = requests.get(BASE_URL + endpoint).text
    return BeautifulSoup(html_page, "lxml")

# Rules for internal Wikipedia links:
# They reside within the div with the id set to bodyContent
# The URLs do not contain colons
# The URLs begin with /wiki/
def get_internal_wiki_link_tags(parsed_page):
    return parsed_page.find('div', { "id": "bodyContent" }).find_all('a', href=re.compile("^(/wiki/)((?!:).)*$"))    

def add_tags_in_visiting_queue(link_tags):
    # if no links were found in an article
    if link_tags is None:
        return

    new_queue = []
    for link_tag in link_tags:
        if "href" in link_tag.attrs:
            internal_link = link_tag.attrs["href"]
            if internal_link not in visited_pages and internal_link not in to_visit_queue:
                new_queue.append(internal_link)
    return new_queue

parsed_root_page = get_parsed_wiki_page("/wiki/Monty_Python")
root_internal_links = get_internal_wiki_link_tags(parsed_root_page)
to_visit_queue = add_tags_in_visiting_queue(root_internal_links)

while True:
    new_temp_visit_queue = []
    for link_to_visit in to_visit_queue:
        print(link_to_visit)
        parsed_page = get_parsed_wiki_page(link_to_visit)
        internal_links = get_internal_wiki_link_tags(parsed_page)
        new_temp_visit_queue = add_tags_in_visiting_queue(internal_links)

        visited_pages.add(link_to_visit)
    
    to_visit_queue += new_temp_visit_queue

print(visited_pages)
```



# File: 06._cheerio.md

<div class="title-card" style="color: cyan;">
    <h1>Hands-on: Node (Cheerio)</h1>
</div>

---

# What is cheerio?

[cherio](https://www.npmjs.com/package/cheerio) is an NPM package for parsing and manipulating HTML.

It is an implementation of jQuery core but meant for the server (Node.js).

---

# Initialize a Node project

Install the `cheerio` package:

```bash
npm init -y
npm install cheerio
```

And remember to change the `type` in `package.json` to `module`.

---

# Task: Download a page

1. Download this page: https://www.proshop.dk/Baerbar-computer

2. Save it to a file called `proshop.html`.

3. Read the file as a string. 


*Can you solve the task?*

---

# Download a page: Solution

```javascript
import fs from "fs";

const response = await fetch("https://www.proshop.dk/Baerbar-computer");
const result = await response.text();
fs.writeFileSync("index.html", result);

const htmlPageString = fs.readFileSync("index.html").toString();
```

---

# Load the page with cheerio and iterate over the products

```javascript
import { load } from "cheerio";

const $ = load(htmlPageString);

$("#products [product]").each((index, element) => {
    console.log($(element).text());
});
```

---

# Extract the data

I want the name, description and price of each product.

*Can you find the correct selectors?*

---

# Extract the data: Solution

```javascript
    const name = $(element).find(".site-product-link h2").text();
    const description = $(element).find(".site-product-link").text();
    const price = $(element).find(".site-currency-lg").text();

    console.log(name);
    console.log(price);
```




# File: 05._web_scraping_web_crawling.md

<div class="title-card" style="color: cyan;">
    <h1>Web Scraping and Web Crawling</h1>
</div>

---

# Web Scraping vs. Web Crawling?

- **Web <u>scraping</u>**: downloading structured data from the web.

[Web scraping](https://en.wikipedia.org/wiki/Web_scraping) = Data scraping

- **Web <u>crawling</u>**: traversing and downloading the web pages.

---

# Web Scraping vs Data mining

Note that the legal documents enforce rules on data mining and not web scraping. Difference:

- **Web scraping**: extracting the data.

- **Data mining**: analyzing the data (often involving extensive data sets).


---

# Rules and legality

1. Do not break websites. 

2. You can scrape public data. But if the data isn't intended to be public, you can't scrape it.

3. The Danish law [Ophavsretslovens § 11b](https://www.elov.dk/ophavsretsloven/paragraf/11b/) is based on the EU directive [DSM-direktivets artikel 4.](https://eur-lex.europa.eu/eli/dir/2019/790/oj) 

4. Do not violate Copyright laws.

5. Do not violate the GDPR.


---

# Anti-scraping Techniques

Example: [Pricerunnner - Disallow rules](https://www.pricerunner.dk/robots.txt)

<img src="./assets_data_scraping_web_crawling/anti-scraping_techniques.png" alt="anti-scraping techniques">

[Source](https://kinsta.com/knowledgebase/what-is-web-scraping/)


---

# Politeness

https://en.wikipedia.org/wiki/Spider_trap#Politeness

Rules for politeness:

1. **Crawl-delay**: Create a delay between requests.

2. **Respect User-agent rules**: The name of the bot.

3. **Respect Allow/Disallow rules**: The pages that should not be crawled.

4. **Respect Sitemap rules**: The sitemap of the website.

---

# Web Scraping Tools

Example of categories:

<img src="./assets_data_scraping_web_crawling/web_scraping_tools.png" alt="web-scraping tools" style="height: 40vh;">

[Source](https://www.scrapingbee.com/blog/web-scraping-tools/)


---

# Web Scraping Problem

If the website requires client-side rendering (JavaScript) to load, you need to use a headless browser.

Example: 

```javascript
import { chromium } from 'playwright';

const url = "..."; // The URL of the website that requires JavaScript.

const browser = await chromium.launch();
const page = await browser.newPage();
await page.goto(url, { waitUntil: 'networkidle' });

const content = await page.content();
```


# File: 03._migrations.md


<div class="title-card">
    <h1>Migrations</h1>
</div>

---

# What is a migration?

A migration is a way to defines changes to the database. 

An alternative to having a single SQL file. 

*What are the two types of migrations that exist?*

---

# Two types of migrations

1. Schema migration (DDL)

2. Data migration / Seeding (DML)

  - Data migration usually refers to moving data from one database to another.

  - Seeding is the process of populating a database with data, usually a new database.

Confusingly, they are all referred to as simply migration.

---

# Example: Knex.js

Migration with rollback:

https://knexjs.org/guide/migrations.html#transactions-in-migrations

---

# How migrations can help you in your project

1. Changes to the schema. Propagating the change for the developers or in production.

2. Migrating data from SQLite to the new database.

3. Backing up the database. (Better solutions might exist here depending on your chosen database).

4. Once you implement web scraping and web crawling, you could use batch seeding to add data en masse to your database. 

---

<div class="title-card">
    <h1>Hands-on with Knex</h1>
</div>

---

# Create the `.env` file

```bash
POSTGRES_DB=mydatabase
POSTGRES_USER=myuser
POSTGRES_PASSWORD=mypassword
POSTGRES_HOST=localhost
```

---

# Create the `docker-compose.yml` file

```yaml
services:
  db:
    image: postgres:latest
    env_file:
      - .env
    ports:
      - "5432:5432"
    volumes:
      - postgres_data:/var/lib/postgresql/data

volumes:
  postgres_data:
```

Then run it:

```bash
$ docker compose up
```

---

# [Optional] See if you can connect through the terminal
    
```bash
$ docker ps
$ docker exec -it <container_id> psql -U myuser -d mydatabase
```

List databases (we don't have any tables in `mydatabase` yet):

```sql
\list # list databases
\dt # list tables
```

---

# Install Knex

https://knexjs.org/guide/

Create a new project and in the folder install Knex and the PostgreSQL driver:

```bash
$ npm init -y
$ npm install knex pg dotenv
```

Remember to add or modify the following in `package.json`:

```json
"type": "module"
```

---

# Initialize Knex

Initialize the Knex project (to get a config file):

```bash
$ npx knex init
```

Change the config file:

```javascript
import 'dotenv/config';

/**
 * @type { import("knex").Knex.Config }
 */
export default {
  client: 'postgresql',
  connection: {
    database: process.env.POSTGRES_DB,
    user: process.env.POSTGRES_USER,
    password: process.env.POSTGRES_PASSWORD,
    host: process.env.POSTGRES_HOST,
  },
  migrations: {
    tableName: 'knex_migrations'
  }
};
```

---

# [Optional] Connect to the database

Create index.js:

```javascript
import knex from 'knex';
import knexConfig from './knexfile.js';

const db = knex(knexConfig);

db.raw('SELECT 1+1 AS result')
.then((result) => {
    console.log('Database connected successfully', result.rows);
})
.catch((error) => {
    console.error('Database connection failed:', error);
})
.finally(() => {
    db.destroy(); 
});
```

---

# Create a migration

```bash
$ npx knex migrate:make create_users_products_table
```

The content we will use is inspired by the documentation:

https://knexjs.org/guide/migrations.html#transactions-in-migrations

*Where in the project is the migration defined?*

---

# Create a migration

Replace the `migrations/<timestamp>_create_users_table.js` file with the following:

```javascript
export function up(knex) {
    return knex.schema
        .createTable('users', (table) => {
            table.increments('id');
            table.string('first_name', 255).notNullable();
            table.string('last_name', 255).notNullable();
        })
        .createTable('products', (table) => {
            table.increments('id');
            table.decimal('price').notNullable();
            table.string('name', 1000).notNullable();
        });
}

export function down(knex) {
    return knex.schema
        .dropTable('products')
        .dropTable('users');
}
```

---

# Run the migration

Then run the migration:

```bash
$ npx knex migrate:latest
```

Check it out in the database:

```sql
\dt
\d users
```

Run commands PostgreSQL's SQL mode (run the commands twice if they fail the first time):

```sql
SELECT * FROM knex_migrations;
SELECT * FROM knex_migrations_lock;
```

---

# Rollback the migration

You can always rollback:

```bash
$ npx knex migrate:rollback
```

Check out the database:

```sql
\dt
```

*What are the benefits of creating database migrations?*

---

# Benefits of migrations

* You can easily setup a new database from scratch.

* You can automatically apply a migration to the production database through your pipelines when you deploy.

* You can propagate changes to the schema to other developers. It's basically version control for databases.

* You can easily rollback a migration if something goes wrong.

---

# Data migration: Seed data

Create a seed file:

```bash
$ npx knex seed:make seed_users
```

Add this to the file:

```javascript
/**
 * @param { import("knex").Knex } knex
 * @returns { Promise<void> } 
 */
export async function seed(knex) {
  await knex('users').del();

  await knex('users').insert([
    { id: 1, first_name: 'John', last_name: 'Doe' },
    { id: 2, first_name: 'Jane', last_name: 'Smith' },
    { id: 3, first_name: 'Alice', last_name: 'Johnson' }
  ]);
}
```

---

# Run the seed

```bash
$ npx knex seed:run
```

Check out the database:

```sql
SELECT * FROM users;
```

*In what case would seeding a users table make sense?*

<details> 
  <summary>Spoiler</summary>
   Creating an admin user, creating other less privileged users per default.
</details>

---

# Knex Cheat Sheet

https://devhints.io/knex

---

# Whoknows variations - PostgreSQL

https://github.com/who-knows-inc/whoknows_variations/tree/database_postgresql


---

# Getting started

SQLAlchemy is a Python SQL tookit and ORM. Alembic is a tool for creating migrations. 

Create a virtual environment:

```bash
$ python -m venv venv
```

Initialize the shell for *nix:

```bash
$ . ./venv/bin/activate
```


Initialize the shell for powershell:

```powershell
$ ./venv/Scripts/activate
```

Init the project using Alembic:


```bash
$ pip install alembic sqlalchemy psycopg2-binary
$ alembic init alembic
```

---

# Configuration

Update the `alembic.ini` with the database connection information. Example for PostgreSQL:

```ini
sqlalchemy.url = postgresql://myuser:mypassword@localhost:5432/mydatabase
```

---

# Creating a migration

```bash
$ alembic revision -m "create account table"
```

Update the file with the migration code from the documentation. But let's pluralize the table name to `accounts`:

https://alembic.sqlalchemy.org/en/latest/tutorial.html#create-a-migration-script

```python
def upgrade():
    op.create_table(
        'accounts',
        sa.Column('id', sa.Integer, primary_key=True),
        sa.Column('name', sa.String(50), nullable=False),
        sa.Column('description', sa.Unicode(200)),
    )

def downgrade():
    op.drop_table('accounts')
```

---

# Running the migration

```bash
$ alembic upgrade head
```

Rollback the migration:

```bash
$ alembic downgrade -1
```
---

# Seeding

Inspired by this comment https://stackoverflow.com/a/19338319 but with some adjustments. Define the upgrade function as the following:

```python
def upgrade():
    accounts_table = op.create_table(
        'accounts',
        sa.Column('id', sa.Integer, primary_key=True),
        sa.Column('name', sa.String(50), nullable=False),
        sa.Column('description', sa.Unicode(200)),
    )
    op.bulk_insert(accounts_table,
    [
        {'id': 1, 'name': 'John Smith', 'description': 'CEO'},
        {'id': 2, 'name': 'Ed Williams', 'description': 'CTO'},
        {'id': 3, 'name': 'Wendy Jones', 'description': 'CFO'},
    ]
)
```



# File: 04._backup_documentation.md

<div class="title-card">
    <h1>Backup and documentation</h1>
</div>

---

# Take a PostgreSQL dump

Run `pg_dump` inside the container:

```bash
$ docker compose exec -T db pg_dump -U myuser mydatabase > pgdump.sql
```

*What does the file contain?*

<details> 
  <summary>Answer</summary>
   DDL, DML and DCL statements. Basically, everything needed to recreate the database.
</details>

---

# Stop and restart the container

*Does the database persist?*

---

# Get a clean database

The data consists because it is defined in a volume.

Manually get a clean database by:

1. Stop the database. 

2. Delete the image first, then the volume. 

3. Restart the database.

4. [Optional] Verify that the database is empty.

Or use the command to take down the volume:

```bash
$ docker compose down -v
```

---

# Load from the dump into the database

```bash
$ PGPASSWORD=mypassword psql -U myuser -h 127.0.0.1 -d mydatabase < pgdump.sql
```

Check the database.

---

# Load the file when initializing the database

1. Create a folder `initdb` in the same directory as the `docker-compose.yml` file.

2. Move the `pgdump.sql` file to the `initdb` folder and rename it to `init.sql`.

3. Load the file as a volume. In `docker-compose.yml`:

    ```yaml
        volumes:
        - postgres_data:/var/lib/postgresql/data
        - ./initdb/init.sql:/docker-entrypoint-initdb.d/init.sql # new line
    ```

4. Take down the database and start it again:

    ```bash
    $ docker compose down -v
    $ docker compose up
    ```

---

# Take a MySQL dump

`mysqldump` comes installed with MySQL. If you have MySQL installed locally run:

```bash
$ mysqldump -u <user> -p <database_name> > mysqldump.sql
```

---

# MRO: Generate migrations from an existing schema

MRO: **M**odel **R**elations to **O**bjects

The opposite of an ORM. It generates objects from an existing database.

```bash
$ npx mro
```

Choose the prompt `Knex.js Migrations`.

Run it from where the `.env` file is defined to skip several prompts. 

**Tip**: All prompts can be autoskipped by defining the correct keys in a `.env` file. This is useful for using it in pipelines.

---

# MRO: Generate HTML documentation

```bash
$ npx mro
```

Choose the prompt: `HTML documentation`.

---

# Generating database documentation

*How else can you document your database?*

---

# Documenting databases

**Relational databases**: ER diagrams

**NoSQL databases**: JSON schema, HTML

**Graph databases**: GraphML, Graphviz

And more...




# File: 01._introduction.md


<div class="title-card">
    <h1>Databases, ORM, Web scraping, Web crawling</h1>
</div>


---

# Weekly DevOps Principle!

**Value Stream Mapping** and **LEAN**

Identify bottlenecks - reduce waste.    

Optimize your indexes: Query smart, query fast.




# File: 03._monitoring.md

<div class="title-card">
    <h1>Monitoring</h1>
</div>

---

# Telemetry vs. Monitoring

**Telemetry**: Data collection and transmission (sending data from one location to another)

**Monitoring**: Data analysis, visualization, and alerting based on telemetry data

---

# Telemetry Levels

| Level                      | Examples                                                                                   |
|----------------------------|--------------------------------------------------------------------------------------------|
| **Business level**         | Sales transactions, revenue, user sign-ups, churn rate, A/B test results                  |
| **Application level**      | Transaction durations, response times, application errors                                  |
| **Infrastructure level**   | Server traffic, CPU load, disk usage, network latency                                     |
| **End-user experience level** | App crashes, client-side response times, user-measured performance                      |
| **Deployment pipeline level** | Build status, deployment lead times, frequency, environment health                      |
| **Security level**         | Failed logins, unauthorized access, data access patterns                                  |

---

# Types of monitoring

| Type                   | Description                                                |
|------------------------|------------------------------------------------------------|
| **Health monitoring**  | Checks if the system is up and running.                    |
| **Performance monitoring** | Checks the performance of the system.                  |
| **Alerting**           | Notifies the team when something goes wrong.               |
| **Tracing**            | Tracks the flow of a request through the system.           |
| **Profiling**          | Measures the performance of the system.                    |
| **Auditing**           | Checks the system for compliance with security policies.   |
| **Business monitoring** | Checks the system for compliance with business policies.  |

---


# Monitoring vs. Logging

While logging is about recording individual events, monitoring is about observing the system.

Monitoring aggregates numerical data over time from various events. 

* Number of HTTP requests processed.

* The total time spent processing requests.

* The number of requests being handled concurrently.

* The number of errors encountered.

* CPU, memory, and disk usage.

---

# What is monitoring?

The most important quote regarding monitoring in the DevOps course:

> "Monitoring is for asking questions."

— Dave Josephsen, Monitorama 2016

**Point**: It's not just about the health of the system. We want to adhere to a DevOps principle of **continuous learning**/**improving**.


---


# How would you achieve monitoring in every step?

<img src="./assets_monitoring/möbius_strip.png" alt="devops 8">

---


# Observability

<a href="https://en.wikipedia.org/wiki/Observability_(software)#Etymology,_terminology_and_definition">Various definitions for observability exist</a>

Full-stack observability - The end-goal of DevOps:

https://www.dynatrace.com/knowledge-base/full-stack-observability/


---

# Observability-Driven Development (ODD)

> "If Engineering at Etsy has a religion, it’s the Church of Graphs. If it moves, we track it. Sometimes we’ll draw a graph of something that isn’t moving yet, just in case it decides to make a run for it...  Tracking everything is key to moving fast, but the only way to do it is to make tracking anything easy..."

\- Ian Malpass, Engineer at Etsy

---

# Reminder: Observability is not a substitute to testing!

Incidents in production are costly and hard to debug

---

# Monitoring solutions

Worth checking out for the visuals on the frontpage:

https://www.datadoghq.com

https://healthchecks.io/

https://cronitor.io/

---

# Specialized monitoring tools

* Nagios https://www.nagios.com/products/nagios-log-server/

* Munin http://munin-monitoring.org/

* Netdata https://my-netdata.io/

* Shinken http://www.shinken-monitoring.org/

* StatsD https://github.com/statsd/statsd

* Prometheus https://prometheus.io/

---

# Pull versus Push Monitoring

## Pull/polling-based

The monitoring system actively queries (or “pulls”) metrics from monitored sub-systems.

Example: Prometheus is pull-based monitoring system that scrapes metrics from application endpoints at regular intervals. 

## Push-based

Hosts, services, and applications send (or “push”) metrics to a central monitoring collector.

Example: Graphite, certain setups of Nagios

---

# Whoknows variations - Monitoring

https://github.com/who-knows-inc/whoknows_variations/tree/monitoring

---

# Why do we **NOT** run our monitoring setup on the same server?

*Discuss in pairs*

---

# Why **NOT** - quote

> "Monitoring is so important that our monitoring systems need to be more available and scalable than the systems being monitored"

\- Adrian Cockcroft, Monitorama

---

# Frontend monitoring

Recording user interactions with the the website to discover what hinders them from completing a flow.

[Amazon found every 100ms of latency cost them 1% in sales.](https://www.gigaspaces.com/blog/amazon-found-every-100ms-of-latency-cost-them-1-in-sales/)

---

# Monitoring the business (KPIs)

| Key Performance Question                                      | Related Metric                                      |
|--------------------------------------------------------------|-----------------------------------------------------|
| Are the numbers of active users growing, declining, or stagnant? | Daily/weekly/monthly active user  |
| How engaged are the users?                                   | Session duration, pages per session, retention rate |
| Are users returning?                                         | Retention rate, churn rate                          |
| Are the users happy?                                          | Net promoter score (likelihood of a customer recommending your product) |
| Can we/are we making money?                                   | Revenue per customer                                |
| Are we profitable?                                            | Cost per customer<br>Burn rate (how fast money is spent) |



---

# Beware: Alert fatigue 

> "That is, monitoring doesn’t exist to generate alerts: alerts are just one possible outcome. With this in mind, remember that every metric you collect and graph does not need to have a corresponding alert."

\-  Mike Julian, Practical Monitoring, 2017

> "When deciding whether a message should be ERROR or WARN, imagine being woken up at 4 AM. Low printer toner is not an ERROR."

\- Dan North, While working at ThoughtWorks in 2006. 

(He coined the term BDD (Behavior-Driven Development) and helped to develop the early ideas behind DevOps.)


---

# Monitoring should not be reacting to symptoms

Monitoring should be used to predict and prevent issues.




# File: 05._crawling.md

<div class="title-card">
    <h1>Web crawling - Where to run the script?</h1>
</div>

---

# Running the script on a server

Not recommended because of:

**Competing ressources**: If we run it on the same server as our production VM.

**Cost**: If we run provision a dedicated server just to run the script.

---

# Running the script locally

Create a script that can be run manually. 

Let it scrape from the internet and upload to the production database via the backend.

**Recommendation**: When uploading, create a route that allows batch inserts to the database. Since the endpoint would be public, create a key to authenticate the request.

---

# Github Actions (Cron Schedule)

You can run a GitHub action workflow in intervals (not triggered by actions in the repository).

However, there are major downsides:

> Jobs may be dropped during high load times. Avoid this by scheduling at odd hours.

> In a public repository, scheduled workflows are automatically disabled when no repository activity has occurred in 60 days. For information on re-enabling a disabled workflow, see "Disabling and enabling a workflow."

https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows#schedule

---

# Github Actions Cron Schedule - Example


```yaml
name: Run Scrapy Project Daily

on:
  schedule:
    - cron: '0 0 * * *'  # Runs at midnight (UTC) every day

jobs:
  run-scrapy:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: Set up Python
        uses: actions/setup-python@v4
        with:
          python-version: '3.8'

      - name: Install dependencies
        run: |
          python -m pip install --upgrade pip
          pip install -r requirements.txt

      - name: Run Scrapy Spider
        run: |
          scrapy crawl <spider_name> -o output.json

```

---

# In a Serverless Function

This would be the optimal solution in a modern company.

You only pay for the time the serverless function is running.

You don't have to deal with installing things to get the runtime working. 

---

# How often should your script run?

This depends on what the users are searching for.  

* **Once**: If the data is not changing.

* **At regular intervals**: Keep overwriting rows / adding new rows.

---

<div class="title-card">
    <h1>Hands-on crawling - Running it locally</h1>
</div>

---

# Let's set up a small project

Set up a project and install jsdom that will help us parse HTML:

```bash
$ npm init -y
$ npm install jsdom
```

Remember to change `"type": "module"` in your `package.json` to use ES modules.

Create a file called `crawler.js` and paste the code on the next slide into it. Run it with:

```bash
$ node crawler.js
```

---

# Crawler Example

```javascript
import { JSDOM } from 'jsdom';
import { URL } from 'url';

const visitedUrls = new Set();

function delay(ms) {
    return new Promise(resolve => setTimeout(resolve, ms));
}

async function crawlPage(pageUrl) {
    const cleanUrl = new URL(pageUrl);
    cleanUrl.hash = '';

    if (visitedUrls.has(cleanUrl.href)) {
        return;
    }

    visitedUrls.add(cleanUrl.href);

    try {
        const response = await fetch(cleanUrl.href);
        if (!response.ok) {
            console.error(`Failed to fetch ${cleanUrl.href}: ${response.statusText}`);
            return;
        }

        const html = await response.text();
        const { window } = new JSDOM(html);
        const document = window.document;

        const mainContent = Array.from(document.querySelectorAll('.mw-parser-output p, .mw-parser-output h1, .mw-parser-output h2, .mw-parser-output h3'))
            .map(element => element.textContent.trim())
            .join(' ')
            .replace(/[\t\n\r]+/g, ' ')
            .trim();

        console.log('Indexing:', cleanUrl.href);
        // todo send or save cleanUrl.href, mainContent somewhere

        const links = Array.from(document.querySelectorAll('a')).map(link => link.getAttribute('href'));
        for (let href of links) {
            if (href && href.startsWith('/wiki/') && !href.includes(':')) {
                const resolvedUrl = new URL(href, cleanUrl.origin).href;
                const normalizedUrl = resolvedUrl.split('#')[0];
                
                if (!visitedUrls.has(normalizedUrl)) {
                    await delay(1000);
                    await crawlPage(normalizedUrl);
                }
            }
        }
    } catch (error) {
        console.error(`Error crawling ${cleanUrl.href}:`, error);
    }
}

crawlPage('https://en.wikipedia.org/wiki/Elasticsearch');
```


# File: 06._serverless_functions.md

<div class="title-card" style="color: cyan;">
    <h1>Serverless Functions</h1>
</div>

---

# Serverless Functions

<img src="./assets_serverless_functions/aws_lambda_vs._azure_functions.png" alt="AWS Lambda vs. Azure Functions" style="height: 30vh">

---

# Why serverless?

* (+) Saves time. Easier to deploy.

* (+) Scalable. 

* (+)  Saves money. (Azure Functions Different pricing plans.)

---

# Azure Functions - subscription models

* **Consumption plan**: Pay for the time that your code runs. This is **serverless**. 

* **Premium plan**: You specify a number of pre-warmed instances that are always online. 

* **App service plan**: Run as if they are web apps. Not serverless.

---

# Azure Functions - Ways to deploy

* In the browser.

* Terminal. 

* IDE (extensions).

* IaC tools. 

---

# Cold starts - A problem

Cold start: The time it takes to allocate the function to a server and setup the runtime environment before your code can run.

Functions are held warm for roughly 20 minutes according to the source below.


<img src="./assets_serverless_functions/cold_start.png" alt="Cold start" style="height: 38vh">


[Source: Azure Microsoft](https://azure.microsoft.com/en-us/blog/understanding-serverless-cold-start/)

---

# More cold start metrics

<img src="./assets_serverless_functions/cold_start_per_language.png" alt="Cold start per language" style="height: 45vh">


[Source](https://mikhail.io/serverless/coldstarts/azure/)

---

# Triggers and bindings

https://learn.microsoft.com/en-us/azure/azure-functions/functions-triggers-bindings?tabs=isolated-process%2Cpython-v2&pivots=programming-language-csharp#supported-bindings


---

<div class="title-card" style="color: cyan;">
    <h1>Let's deploy a serverless function</h1>
</div>

---

# Azure Web Crawler

This is a project to showcase a function that reads 10 wikipedia pages and returns and array of the content.

https://github.com/who-knows-inc/azure_web_crawler

Feel free to fork and reuse the repository. Just replace the code in `web-crawler-func-app/src/functions/index.js` with your own scraper / crawler code.

---

# Installation

Make sure that the Azure CLI is installed or get it from [here](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli).

Login to your Azure account:

```bash
$ az login
```

In order to give permission to create Function Apps, you need to register the Microsoft.Web provider:

```bash
$ az provider register --namespace Microsoft.Web
```

---

# Create a Resource Group, Azure Blob Storage, Function App

1. All services must have a resource group associated with them.

2. A Function App must be created which can contain multiple functions.

3. Azure Blob Storage is used to store the function code.  

Storage accounts must have globally unique names because the name forms part of the Blob Storage URL.


```bash
$ az group create --name web-crawler-rg --location westeurope

$ az storage account create --name <unique_storage_name> --location westeurope --resource-group web-crawler-rg --sku Standard_LRS

$ az functionapp create --resource-group web-crawler-rg --consumption-plan-location westeurope --runtime node --runtime-version 20 --functions-version 4 --name web-crawler-func-app --storage-account <unique_storage_name> --os-type Linux
```

Replace `<unique_storage_name>` with a unique name.

---

# Get ready to deploy (only needs to be done once)

Install the Azure Functions Core Tools:

```bash
$ npm install -g azure-functions-core-tools@4 --unsafe-perm true
```

Clone the [Azure Web Crawler project](https://github.com/who-knows-inc/azure_web_crawler) and **IMPORTANTLY** `cd` into the `web-crawler-func-app` folder.

After `cd`'ing, init the runtime:

```bash
$ func init . —worker-runtime javascript
```

Make sure that the above command runs `npm install`.

---

# Deploy

Publish the function:

```bash
$ func azure functionapp publish web-crawler-func-app
```

You can make changes to the `index.js` file and redeploy the function with the same command.

Once successful, you will get an invokation URL. Call it in the browser and wait for it to finish scraping the pages.

To understand what the function does, check out [index.js](https://github.com/who-knows-inc/azure_web_crawler/blob/main/web-crawler-func-app/src/functions/index.js).


---

#  Clean up

```bash
$ az group delete --name web-crawler-rg --yes --no-wait
```

**REMEMBER**: Go to the portal and make sure that all the resource groups are deleted.


---


<div class="title-card" style="color: cyan;">
    <h1>Let's deploy a serverless function from scratch</h1>
</div>

---

# Create a ressource group

```bash
$ az group create --name <RESOURCE_GROUP_NAME> --location <LOCATION>
```

**RESOURCE_GROUP_NAME**: `class-http-trigger-rg`

**LOCATION**: `westeurope`

**Solution**:

```bash
$ az group create --name class-http-trigger-rg --location westeurope
```

---

# Create a storage account

You must create a storage account to associate with the Function App. This is where the code will be stored. 

```bash
$ az storage account create --name <STORAGE_ACCOUNT_NAME> --location <LOCATION> --resource-group <RESOURCE_GROUP_NAME> --sku Standard_LRS
```

An HTTP trigger means that the function will run when an HTTP request is made to its endpoint.

**Solution**:

```bash
$ az storage account create --name classhttptriggerstorage --location westeurope --resource-group class-http-trigger-rg --sku Standard_LRS
```

**Note**: The storage account name is used in the blob storage URL and must be unique. Define a different one from above. 

---

# Create the function app

```bash
$ az functionapp create --resource-group <RESOURCE_GROUP_NAME> --consumption-plan-location <LOCATION> --runtime node --runtime-version 22 --functions-version 4 --name <FUNCTION_APP_NAME> --storage-account <STORAGE_ACCOUNT_NAME>
```

**Solution**:

```bash
$ az functionapp create --resource-group class-http-trigger-rg --consumption-plan-location westeurope --runtime node --runtime-version 22 --functions-version 4 --name class-http-trigger --storage-account classhttptriggerstorage
```

---

# Create the function

```bash
func init <PROJECT_NAME> --javascript
func new
```

**PROJECT_NAME**: `class-http-trigger`

For `func new`, select `8. HTTP trigger`.

If you don't have func installed you can install it with npm:

```bash
npm install -g azure-functions-core-tools@3 --unsafe-perm true
```

[Or check out other installation options here.](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=macos%2Cisolated-process%2Cnode-v4%2Cpython-v2%2Chttp-trigger%2Ccontainer-apps&pivots=programming-language-csharp#install-the-azure-functions-core-tools)

---

# Deploy the function

```bash
$ func azure functionapp publish <FUNCTION_APP_NAME>
```

**FUNCTION_APP_NAME**: `class-http-trigger`


---

# Try to update the code and redeploy

```bash
$ func azure functionapp publish class-http-trigger
```

---

# Timer triggers

If you generate a Time Trigger function instead of an HTTP Trigger function, you can set the schedule in the generated `function.json` file.

```json
{
  "bindings": [
    {
      "name": "myTimer",
      "type": "timerTrigger",
      "direction": "in",
      "schedule": "0 0 0 * * *"
    }
  ]
}
```

---

# Clean up

```bash
$ az group delete --name class-http-trigger-rg --yes --no-wait
```

**REMEMBER**: Go to the portal and make sure that all the resource groups are deleted.






# File: 04._searching.md

<div class="title-card">
    <h1>Searching</h1>
</div>

---

# Searching in SQLite with FTS5

* **Tokenization**: FTS5 breaks down the text into words.

* **Indexing**: FTS5 uses tokenization and word positions to create an index for words. The index contains:

  - **Document ID**: The `rowid` of the document.
  - **Column Index**: Identifies which column the term appears in.
  - **Token Offset**: Specifies the position of the term within the column.
 
* **Performance**: Unlike the LIKE operator which performs a sequential scan of all rows the MATCH operator is faster since it uses an index.

* **Scoring**: At query time, FTS5 calculates a score for each match using [bm25](https://en.wikipedia.org/wiki/Okapi_BM25) as the default ranking function, but only if the `rank` column is selected or used in `ORDER BY`.

---

# Searching in PostgreSQL

In PostgreSQL, you must create a `tsvector` column to store the tokenized text:

```postgresql
ALTER TABLE pages ADD COLUMN content_tsv tsvector;
```

Then populate it using English stemming if your page content is in English:

```postgresql
UPDATE pages SET content_tsv = to_tsvector('english', content);
```

Create a generalized inverted index (GIN) on the `tsvector` column. Otherwise it would perform a sequential scan:

```postgresql
CREATE INDEX content_tsv_idx ON pages USING GIN(content_tsv);
```

---

# Searching in PostgreSQL II

Create a trigger to automatically update the `tsvector` column after INSERT or UPDATE:

```postgresql
CREATE FUNCTION update_content_tsv() RETURNS trigger AS $$
BEGIN
	NEW.content_tsv := to_tsvector('english', NEW.content);
	RETURN NEW;
END;
$$ LANGUAGE plpgsql;

CREATE TRIGGER tsvector_update BEFORE INSERT OR UPDATE
ON pages FOR EACH ROW EXECUTE FUNCTION update_content_tsv();
```

Query example using the `@@` operator to match the `tsvector` column against a search term:

```postgresql
SELECT * FROM pages
WHERE content_tsv @@ plainto_tsquery('english', 'my search terms')
ORDER BY ts_rank(content_tsv, plainto_tsquery('english', 'my search terms')) DESC;
```

---

# Vector Databases

You could also consider using a vector database to achieve semantic search.

You could use PostgreSQL for users and business logic and have a separate vector database for search.





# File: 02._logging.md

<div class="title-card">
    <h1>Logging vs. Monitoring vs. Tracing vs. Profiling</h1>
</div>


---

# Logging vs. Monitoring vs. Tracing vs. Profiling

**Logging**: Record events in a software system.

**Monitoring**: Observe the system.

**Tracing**: Record the sequence in which events propagate through the system (especially useful for distributed systems).

**Profiling**: Measure the performance.

---

# Tracing

End-to-end journey of a request across a distributed system. 

Keeps track of how a request flows through various services.

**Not logging**: it focuses on the path and duration across services rather than discrete events.

**Not monitoring**: it focuses on individual request paths rather than system-wide metrics.

---

# Profiling

> "In software engineering, profiling ("program profiling", "software profiling") is a form of dynamic program analysis that measures, for example, the space (memory) or time complexity of a program, the usage of particular instructions, or the frequency and duration of function calls."

<a href="https://en.wikipedia.org/wiki/Profiling_(computer_programming)">Source: Wikipedia</a>

[JMeter](https://jmeter.apache.org/), [Gatling](https://gatling.io/),  [Locust](https://locust.io/) etc.

**Not logging**: Doesn't record descrite events or historical data. 

**Not monitoring**: Doesn't track system-wide metrics over time. 

---

# Logging

**Definition**: Record events in a software system.

- Used for debugging and diagnostics
- Captures discrete events (e.g., errors, warnings, info)
- Often stored in files or external log systems

**Not monitoring**: Doesn't provide real-time system metrics

---

# Monitoring

**Monitoring**: Observe the system.

- Tracks metrics (CPU, memory, request rate, error rate, etc.)
- Provides dashboards, alerts, and trend analysis
- Often used for operational awareness and SLOs

**Not logging**: Doesn't capture detailed event history

**Not tracing**: Doesn't follow request paths through services

**Not profiling**: Doesn't analyze fine-grained performance

---

<div class="title-card">
    <h1>Logging</h1>
</div>

---

# Logging

The activity of collecting and analyzing data generated by applications, infrastructure, and other components of a system.

- **Streams** of

- **aggregated**

- **time-ordered** events

- collected from **running processes**

---

# Why log?

*Why would you need need to log?*

---

# Why log?

1. **Diagnosis**: What went wrong. 

2. **Anomaly detection**: Perform statistical analysis to find outliers and variances. 

3. **Understanding**: How is your system being used?

4. **Security**: Detecting unauthorized access.

5. **Compliance**: Legal requirements to create audit trails. 

---

# Motivation: Logging is big business

> "Dansk IT-sikkerhedsvirksomhed solgt for ukendt stort milliardbeløb"

https://finans.dk/erhverv/ECE15230842/dansk-itsikkerhedsvirksomhed-solgt-for-ukendt-stort-milliardbeloeb/

**LogPoint** specializes in in SIEM (Security Information and Event Management).

There are many such companies and they are all very profitable.

---

# Where to log to?

It is fine to log on the same server as the application. 

In Linux there is a `/var/log` folder meant for exactly this. The data there will persist even if the server restarts.

It's also possible to use a logging server such as:

[Logstash](https://www.elastic.co/logstash), [Splunk](https://www.splunk.com/), [Graylog](https://www.graylog.org/) etc.

---

# What shouldn't you log?

*And how should you avoid doing so?*


---

# What not to log?

**NEVER** log sensitive data like passwords, credit card numbers, etc.

If it is personal data (as defined by GDPR) there are rules such as the right to be forgotten, deleting data after a certain time period etc.

Mixing personal data with the logs will make it an impossible task to comply with these rules.

Solution:

* Create an ID for the sensitive data and store it somewhere else from your logs.

* Bonus points if the ID is different from the IDs in your application database for an added layer of security.


---

<div class="title-card">
    <h1>Logging formats</h1>
</div>

---

# Syslog

* Developed in 80s

* Standardizes **formatting** and **transmission** of logs in a network ([RFC 3164 (2001)](https://tools.ietf.org/html/rfc3164), [RFC 5424 (2009)](https://tools.ietf.org/html/rfc5424))

* Popular in Linux

* General - for any system exchanging logs

---

# Syslog - Format

<img src="./assets_logging/syslog_format.png" alt="syslog format">

[Source: Stackifly / Flylib](https://stackify.com/syslog-101/)

https://en.wikipedia.org/wiki/Syslog

---

# A syslog compliant Python example

```python
import sys
import logging
import socket

logging.basicConfig(
    format="%(asctime)s %(hostname)s %(module)s[%(process)d]: %(levelname)s %(message)s",
    datefmt="%Y-%m-%d %H:%M:%S",
    level=logging.INFO,
    stream=sys.stdout
)

# Add hostname dynamically
logging.Logger.adapter = logging.LoggerAdapter(logging.getLogger(), {'hostname': socket.gethostname()})

logging.debug('This is a debug message in the syslog format')
```


---

# Common logging levels


| Logging Level | Description                                                                                                                                          |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| **DEBUG**     | Information about anything that happens in the program, often used during debugging. Debug logs are usually disabled in production but enabled temporarily during troubleshooting. |
| **INFO**      | Actions that are user-driven or system-specific (e.g., “beginning credit card transaction”).                                                         |
| **WARN**      | Conditions that could potentially become an error (e.g., a database call taking longer than some predefined time). These often initiate alerts and troubleshooting. |
| **ERROR**     | Focuses on error conditions (e.g., API call failures, internal error conditions).                                                                    |
| **FATAL**     | Indicates when we must terminate (e.g., a network daemon can’t bind a network socket).                                                     |

Additionally, Syslog has `Notice`, `Critical`, `Alert` and  `Emergency` but does not have `Fatal`. [Source](https://en.wikipedia.org/wiki/Syslog#Severity_level)



---

# Logging levels - Python Example


The smart thing is that you can use the logging levels to filter out output.

Example with `logging` which is part of the Python standard library:

```python
import logging

logging.basicConfig(level=logging.INFO)

logging.debug('This is a debug message')
logging.info('This is an info message')
logging.warning('This is a warning message')
logging.error('This is an error message')
logging.critical('This is a critical message')
```

**Question**: *Can you guess what will be shown?*

---

# Logging levels - What will be shown

```python
import logging

logging.basicConfig(level=logging.INFO)

logging.debug("Oops, got here.")                           # This will not be shown
logging.info("User updated preferences.")                  # This will be shown
logging.warning("Could not retrieve any items from feed.") # This will be shown
logging.error("Google Translate API not answering")        # This will be shown
logging.critical("Out of memory")                          # This will be shown
```

---

# Logging levels - Display levels

| Logging Level | Displays Messages at Levels |
|---------------|-----------------------------|
| **DEBUG**     | DEBUG, INFO, WARNING, ERROR, CRITICAL |
| **INFO**      | INFO, WARNING, ERROR, CRITICAL |
| **WARNING**   | WARNING, ERROR, CRITICAL     |
| **ERROR**     | ERROR, CRITICAL              |
| **CRITICAL**  | CRITICAL                     |


---

<div class="title-card">
    <h1>Logging stacks</h1>
</div>

---

# ELK stack

* ElasticSearch = Scalable full text search DB

* Logstash = Java-based log parser

* Kibana = Visualization tool tailored for ElasticSearch

---

# Other common logging stacks

* **ELK stack**: Elasticsearch, Logstash, Kibana

* **EFLK stack**: Elasticsearch, Filebeat, Logstash, Kibana

* **EFK stack**: Elasticsearch, Fluentd, Kibana

* **Graylog**: Graylog server, MongoDB, Elasticsearch, Graylog web interface

* **Loki + Grafana**: Loki, Grafana

Then there are single-purpose tools like **Splunk**, **Loggly**, **Sumo Logic**, **Papertrail**, **LogDNA**, **Datadog** and many more.

You can always do it yourself! That's what the `simulator` and `plot server` does.

---

# Docker and logging

Access logs in docker:

```bash
$ docker logs <container_id>
```

**Note**: If logs aren’t collected or persisted, they are lost on container stop/restart.

Persist logs using syslog driver:

```bash
$ docker run --log-driver=syslog <image>
```

On Ubuntu (20.04+) access the logs (add the `-f` flag to follow live):

```bash
$ journalctl -t <container_name>
```

Persist logs to host filesystem:

```yaml
volumes:
  - /host/logs:/var/log/container
```





# File: 01._introduction.md


<div class="title-card">
    <h1>Searching, Logging, Monitoring</h1>
</div>

---

# Remember to be DevOps

I can task you to do technical assignments but you have to solve the DevOps task yourself.

There is guaranteed to be friction in your group. 

*How do identify problems?*

*How do you solve them?*

*How do you achieve psychological safety in your group so that members can speak out about the issues?*

If I ask you in the Exam how the group work was and you say "perfect" and nothing more I will be sceptical.

Take this reflection-solving mentality with you when you write your thesis.

---

# Indexing the database

*Did you do it*? 

*Can you tell me how much faster your response times have become? How can you check?*

---

# KPI (Key Performance Indicators)

Let's discuss the assignment! 

* CPU load on the server.

* Total amount of users.

* Cost of the infrastructure / complete setup (monthly and/or total so far).

* [Optional] Total amount of active users.

* [Optional] Average amount of searches per day.

---

# Weekly DevOps Principle!

**Continuous Feedback**

Measure everything!

Ask questions, understand the data and improve the product. 






# File: 03._deployment_strategies.md

<div class="title-card">
    <h1>Deployment Strategies</h1>
</div>

---

# Goal: Deploying with zero downtime

Discuss in pairs/groups.

*How would you achieve it?*

---

# Thinks to consider when deploying

*What are the considerations to make when choosing a deployment strategy?*

---

# Thinks to consider when deploying

- **Zero downtime**

- **Scalability**

- **Downtime tolerance**

- **Rollback plan**

- **Cost efficiency**

---

# Topic: Colorful deployment strategies

Images without a source in the next couple of slides are from this article:

https://devopsbootcamp.org/8-deployment-strategies-explained-and-compared/

But the material is from various sources.

---

# Blue-Green deployment

Two identical environments, where only one is "live" at any time. Let's say that blue is "live". 

In that case, use the blue environment as your staging environment.

Once all tests in staging pass, you can switch the traffic to green.

This additionally makes it much easier to roll back if something goes wrong.

<img src="./assets_deployment_strategies/blue-green_deployment.gif" alt="blue-green deployment" style="height: 30vh; background-color: white;">


---

# Blue-Green deployment and databases

There are two approaches for how to handle the database

1. **Create two databases** (a blue and a green). If we switch from blue to green, we make blue read-only, create a back-up and restore it onto green. 

2. **Decouple the database** changes from application changes: 

<img src="./assets_deployment_strategies/blue-green_deployment_with_database.png" alt="blue-green deployment" style="height: 30vh; background-color: white;">

[Source](https://dev.to/semaphore/what-is-blue-green-deployment-1ong)

---

# Canary deployment

Gradually roll out a new version to a small subset of users before rolling it out to the entire infrastructure. 

Observe if the system is healthy, otherwise roll back.

The name comes from the old usage of canaries in coal mining to test air quality. If the canary died, it was time to get out of the mine.

<div style="display: flex; gap: 10px; align-items: center;">
  <img src="./assets_deployment_strategies/canary_mine.png" alt="canary deployment mine" style="width: 20vw;">
  <img src="./assets_deployment_strategies/canary_deployment.gif" alt="canary deployment" style="width: 28vw;">
</div>

---

# Cluster immune system

An expanded version of the canary deployment strategy that **automates** a rolling back mechanism. 

If health checks and monitors fail within a certain margin it will roll back. 

---

# Rolling updates

Gradual roll out of the infrastructure (instances) with the new version.

Health checks are performed and if it is healthy, more instances are flipped to the new version.

<img src="./assets_deployment_strategies/rolling_updates.gif" alt="rolling updates" style="height: 45vh;">

---

# Canary deployment vs. rolling updates

Canary deployment can still be considered a type of rolling update. But there are key differences. 

Unlike canary deployment which is focused on users, rolling updates are focused on infrastructure.

Canary deployment will try for a subset of users and if it is successful roll out the entire change. Rolling updates will do it in small increment. 

---

# Rolling updates vs. ramped deployment

Rolling updates deploy to one server at a time in a round-robin fashion. 

Ramped deployment deploys to an increasingly higher percentage of servers every time.

<img src="./assets_deployment_strategies/ramped_deployment_rolling_deployment.gif" alt="rolling ramped updates" style="height: 20vh;">

---

# Impact of update strategies on the consistency of the results that the users see

* With **blue-green** they never see inconsistent results

* With **rolling-updates** they might see different results in different calls

*Can you figure out why that is the case with rolling updates?*

---

# Shadow Deployment / Dark Launching

**Backend  Example**: Requests are duplicated and additionally sent to a shadow API in order to assess how it handles the requests.

<img src="./assets_deployment_strategies/shadow_deployment_API.gif" alt="shadow deployment api">


**Frontend Example**: Facebook does a thing that they call **Feature Toggling**. For instance, they deploy invincible features that exist in the DOM but are not visible to users just to see how it holds up. Feautures can be released for months without users seeing them but they are on the production servers. 

---

# Case: How Facebook Releases 

Facebook has a dedicated *release team* and they use the internal tool - Facebook Gatekeeper - to release to specific groups. 

**Facebook Gatekeeper** can target a release to users in certain demographics / regions.

They have a 3 step release model. Release to:

- **A1 group**: production servers that only serve internal employees.

- **A2 group**: production servers that only serve a small percentage  of  customers  and  are  deployed  when certain  acceptance  criteria  have  been  met  (either automated or manual).

- **A3 group**:  the  rest  of  the  production  servers,  which are  deployed  after  the  software  running  in  the  A2 cluster meets certain acceptance criteria

---

# Other internal tools

Facebook GateKeeper has just been mentioned. 

**Etsy Feature API** and **Netflix Archaius library** are other famous examples of tools used for deployment strategies that can achieve many of the techniques mentioned so far.




# File: 09._course_conclusion.md



<div class="title-card">
    <h1>DevOps course conclusion</h1>
</div>

---

# The simulation is over!


---

# The repo will be made unavailable after the first exam

Remember to fork the repo if you want it.

---

# Learning Goals

Remember to check the learning goals for the course and make sure that you have achieved them.

It's a good measure of my expectation for the exam.

---

# Let's look at the exam report requirements and exam requirements

They can be found as links at the top of the semester plan.


---

# Do you agree with this? React to it only if you do

https://github.com/orgs/community/discussions/114734

---

# Thank you, Contributors!

<img src="./assets_course_conclusion/contributors_thank_you.png" alt="github contributors" style="height: 30vh;">

https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/graphs/contributors

https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/network

---

# Course Survey


---

# Did we learn Devops - A historical overview

Compilation of blog posts and articles of historical importance:

https://gist.github.com/jpswade/4135841363e72ece8086146bd7bb5d91


---

# Did we learn Devops - Roadmap

This is a famous roadmap for DevOps:

This course was not developed with it in mind but see how much of it we have achieved:

https://roadmap.sh/devops

---


# DevOps course as DevOps

This course has aimed to be DevOps!

Examples:

* IaC: First weeks server and the simulation.

* Various Github Actions. 

* Monitoring of student activity, 

* Behind-the-scenes monitoring of the simulator.

* Continuous improvement of the course.

---

# Debois' definition of DevOps


> *It's taken me 10-plus years to come up with my own one-line definition of DevOps:*

> ***"DevOps is whatever you do to bridge friction created by silos, and all the rest is engineering."***

> *And so, if you're doing technology just for the technology and you're not trying to overcome some friction of the human kind of siloing or group siloing or information siloing or whatever, then you're just doing the engineering part and you're not, in my opinion, doing the DevOps part."*

\- Patrick Debois

---

# Were you DevOps?

The big exam question: *Were you DevOps?*

While you have to ask yourselves if you were DevOps you should also ask if you did what was best for your team in the context of the course.

DevOps offers a solution to common problems. 

---

# Was I DevOps?

DevOps shouldn't be the end goal. 

It's about continuous improvement. 

I hope you can use this in your general life. 





# File: 06._kubernetes_hands-on.md


<div class="title-card">
    <h1>Minikube setup</h1>
</div>

---

# Installing kubectl and minikube

**kubectl**: the command line tool for interacting with Kubernetes.

**minikube**: creates a single-node Kubernetes cluster on your local machine (only for local development and testing).

MacOS:

```bash
$ brew install kubectl minikube
```

Powershell:

```powershell
$ choco install kubernetes-cli minikube
```
---

# Starting minikube

You have to sepcify the driver.

Possible drivers are: `Docker`, `Hyperkit`, `KVM2`, `Parallels`, `Podman` `VirtualBox`, `VMware Fusion`, `VMware Workstation`

```bash
$ minikube start --driver=docker
```

**Beware**: There are limitations to using the `Docker` driver for Minikube [which is that it doesn't support ingress outside of Linux](https://stackoverflow.com/questions/76470764/why-i-cant-get-access-to-app-from-browser-with-kubernetes-minikube).


Since we already have Docker installed, we will use it.

Check the status:

```bash
$ minikube status
```

You can always stop minikube with:

```bash
$ minikube stop
```

---

# SSH into it

SSH into it:

```bash
$ minikube ssh
```

The default user name for minikube is `docker`, even if you are not using the `docker` driver.

---

# Check the services

After ssh'ing into the minikube, you can check the services:

```bash
$ docker ps
```

You will recognize some of these services from the previous architecture diagrams. 

---

# Using `kubectl` to interact with minikube

`kubectl` is a command line tool, external to minikube, which allows us to interact with Kubernetes clusters.

It is common to alias `kubectl` to `k`.

Run the following commands in a new terminal:

```bash
$ kubectl cluster-info
```

```bash
$ kubectl get nodes
```

```bash
$ kubectl get services
```

---

# Namespaces and pods

We haven't created any pods yet:

```bash
$ kubectl get pods
```

Check the namespaces:

```bash
$ kubectl get namespaces
```

When we listed pods we only did so in the default namespace.

Check the pods in the `kube-system` namespace:

```bash
$ kubectl get pods -n kube-system
```

---

# Let's run a pod

Let's pull the `Nginx` image from DockerHub and run it in a pod:

```bash
$ kubectl run nginx --image=nginx
```

Check the pods:

```bash
$ kubectl get pods
```

```bash
$ kubectl describe pod nginx
```

---

# Deleting the pod

The problem is that running a new pod with `kubectl run` only creates a single pod which goes against the idea of Kubernetes. 

Instead, we want to create a deployment which will create a replica set of pods.

First, let's delete the pod:

```bash
$ kubectl delete pod nginx
```

---

# Create a deployment

Pull the `Nginx` image from DockerHub and create a deployment:

```bash
$ kubectl create deployment nginx --image=nginx
```

Check the deployments:

```bash
$ kubectl get deployments
```

Check the pods:

```bash
$ kubectl get pods
```

---

# Exposing the pod

We cannot access the pod from outside the cluster. The IP address of the pod is internal.

There are multiple ways to expose the pod:

1. **NodePort**: Exposes the service on each Node's IP at a static port.

2. **LoadBalancer**: Exposes the service which proxies to pods using a cloud provider's load balancer.

3. **ClusterIP**: Exposes the service on a cluster-internal IP.

4. **ExternalName**: Maps the service to the contents of the `externalName` field.

---

# Exposing the pod using minikube

Expose the deployment using `NodePort`:

```bash
$ kubectl expose deployment nginx --port=80 --type=NodePort
```

With `minikube` the URL will be mapped to localhost and the port can be retrieved with:

```bash
$ minikube service nginx --url
```

Done! You can now delete the service:

```bash
$ kubectl delete service nginx
```

---


<div class="title-card">
    <h1>Deployments</h1>
</div>

---

# Creating a deployment

Let's create a deployment for a simple Express server running on port `3000` (image in my account):

```bash
$ kubectl create deployment k8s-web-hello --image=andlocker/k8s-web-hello
$ kubectl expose deployment k8s-web-hello --port=3000 --type=NodePort
```

Get the URL:

```bash
$ minikube service k8s-web-hello
```

The first IP address will be the same as:

```bash
$ minikube ip
```

---

# Manually scaling the deployment

```bash
$ kubectl scale deployment k8s-web-hello --replicas=4
```

---

# Cleaning up

Delete the service (`svc` is shorthand for `service`):

```bash
$ kubectl delete svc k8s-web-hello
```

Or delete all:

```bash
$ kubectl delete all --all
```

---

<div class="title-card">
    <h1>Declaratively working with Kubernetes</h1>
</div>

---

# Imperative vs Declarative

We were working imperatively before by typing commands into the terminal.

Now we will work declaratively by creating a `yaml` file which describes the desired state of the cluster.

---

# Create a deployment

Create a `deployment.yaml` file.

If you are in VSCode, install the Microsoft Kubernetes extension to get auto-complete.

Then, in `deployment.yaml` type "Deployment" and press `tab` to get the template then:

| Replace Key     | Replacement Value               |
|-----------------|---------------------------------|
| `name` (x2k )     | `k8s-web-hello`                 |
| `app` (x2)     | `k8s-web-hello`                 |
| `image`         | `andlocker/k8s-web-hello:latest`|
| `containerPort` | `3000`                            |

The containerPort is `3000` because my Express server is running on port `3000`.

---

# Apply the deployment

```bash
$ kubectl apply -f deployment.yaml
```

Check the deployment:

```bash
$ kubectl get deployments
```

Check the amount of pods:

```bash
$ kubectl get pods
```

---

# Add more replicas

Edit the `deployment.yaml` file and add the `replicas` field under the "top-level" `spec` key:

```yaml
spec:
  replicas: 4
```

Reapply and check the pods.

We want it to run as a service so that we can access it from the browser.

But, it is not running as a service yet. Check `$ kubectl get services`.

---

# Create a service

We want to create a `LoadBalancer` service to expose the pods.

Create a `service.yaml` file, type "Service" and press `tab` to get the template.

| Replace Key          | Replacement Value        |
|-----------------------|--------------------------|
| `name`               | `hello`          |
| `app`                | `k8s-web-hello`          |
| `port`               | `3000`   |
| `targetPort`         | `3000`    |
| `type` (under `spec`)| `LoadBalancer`           |

```yaml
spec:
  type: LoadBalancer
```

The `targetPort` in the serviced must be the same as the `containerPort` in the deployment.

---

# Apply the service

```bash
$ kubectl apply -f service.yaml
```

Check the service:

```bash
$ kubectl get services
```

Open the service in the browser:

```bash
$ minikube service hello
```

---

# Cleaning up

Delete the deployment and service:

```bash
$ kubectl delete -f deployment.yaml -f service.yaml
```

---

# Combine the two files

It is standard to combine a deployment and a service into one file. We will call it `deployment_service.yaml`.


1. Paste the deployment. 

2. Add `---` after it.

3. Paste the service.

This makes it easier to apply.


*Can you apply the new file, open the URL in the browser and then delete it all?*

---

# Solution - Apply the combined file and take it down

```bash
$ kubectl apply -f deployment_service.yaml
$ minikube service hello
$ kubectl delete -f deployment_service.yaml
```

---

# `deployment_service.yaml`

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: k8s-web-hello
spec:
  replicas: 4
  selector:
    matchLabels:
      app: k8s-web-hello
  template:
    metadata:
      labels:
        app: k8s-web-hello
    spec:
      containers:
      - name: k8s-web-hello
        image: andlocker/k8s-web-hello:latest
        resources:
          limits:
            memory: "128Mi"
            cpu: "500m"
        ports:
        - containerPort: 3000
---
apiVersion: v1
kind: Service
metadata:
  name: k8s-web-hello
spec:
  type: LoadBalancer
  selector:
    app: k8s-web-hello
  ports:
  - port: 3000
    targetPort: 3000
```

---


<div class="title-card">
    <h1>Helm</h1>
</div>

---

# What is Helm?

* [**Helm Charts**](https://artifacthub.io/packages/search?kind=0&sort=relevance&page=1): public and private repositories for Kubernetes manifests.

* **Templating engine**: allows for dynamic values in the manifests. Define values in a `values.yaml` file. 
  *  Example: Define service name in one place and invoke it with `{{ .Values.serviceName }}`.

* **Release Management**: Versioning, configuration, upgrades and rollbacks.

---

# Install Helm

https://helm.sh/


```bash
$ brew install helm
```

```powershell
$ choco install kubernetes-helm
```

Example command that (downloads, names, deploys and creates the resources to the default configured Kubernetes cluster):

```bash
$ helm install my-nginx bitnami/nginx
```



# File: 08._maintenance.md

<div class="title-card">
    <h1>Maintenance</h1>
</div>

---

# Maintenance: The Missing Piece in your Education

During your time at KEA, you learn how to build things from scratch. 

And you might spend time bug fixing and refactoring.

This is your opportunity to maintain a system that is already in production.

---

# What comprises Maintenance?

* fixing bugs

* keeping its systems operational

* investigating failures

* adapting it to new platforms

* modifying it for new use cases

* repaying technical debt

* adding new features

* etc.

\- [Kleppmann "Designing Data-Intensive Applications" (2017)](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch01.html)

---

# Maintenance as viewed by the [ISO 25010](https://www.iso.org/standard/35733.html) specification

To aid maintenance, the software should be designed for:

* Modularity

* Reusability

* Analysability

* Modifiability

* Testability

*What does this slide remind you of?*

---

# Parallels to earlier in the course

Topic: Technical debt. 

---

# Design for Maintainability

> [...] minimize pain during maintenance, and thus avoid creating legacy software ourselves.

> * a) **Operability**
>  Make it easy for operations teams to keep the system running smoothly.

> * b) **Simplicity**
>  Make it easy for new engineers to understand the system, by removing as much complexity as possible from the system. (Note this is not the same as simplicity of the user interface.)

> * c) **Evolvability**
  > Make it easy for engineers to make changes to the system in the future, adapting it for unanticipated use cases as requirements change. Also known as extensibility, modifiability, or plasticity.

\- [Kleppmann "Designing Data-Intensive Applications" (2017)](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch01.html)


---

# SLAs vs. SLOs vs. SLIs

Promises made by a service provider to a customer regarding systems in production.

<div style="display: flex; justify-content: space-between;">
  <img src="./assets_maintenance/sla_slo_sli_definitions.png" alt="sla slo sli definition" style="width: 23vw;">
  <img src="./assets_maintenance/sla_sli_sli_templates.png" alt="sla slo sli template" style="width: 23vw;">
</div>

[Source - Atlassian](https://www.atlassian.com/incident-management/kpis/sla-vs-slo-vs-sli).

---

# Examples of real-life SLAs

https://www.microsoft.com/licensing/docs/view/Service-Level-Agreements-SLA-for-Online-Services?lang=1&year=2023

https://cloud.google.com/terms/sla/

---


# Definition of done

Let's discuss:

*When will you know when your work on the project is over?*

There is no right answer. Each group might come up with their own definition.



# File: 02._deploying_infrastructure_configuration_managment.md

<div class="title-card">
    <h1>Deploying Infrastructure and Configuration Managment</h1>
</div>

---

# Platform engineering

Create platforms that enable on-demand creation of dev, test and production environments.

Continuation from last week: Using Infrastructure as Code tools as part of our CI/CD pipeline.

Imagine if you had to make a create a product similar to *whoknows* **every week** at your company. What tools and automations would you need to develop so that all 5 days a week could be used to build unique features.

---

# Platform Engineering

<img src="./assets_maintenance/platform_engineering_devops8.png" alt="platform engineering devops8">

[Source - Microsoft: What is Platform Engineering?](https://learn.microsoft.com/en-us/platform-engineering/what-is-platform-engineering)

---

# CDE (Cloud Development Environment)

Development-environments-as-code. 

Faster onboarding: Enable developers to quickly setup any project.

Never give out secrets.

https://coder.com/

https://www.gitpod.io/

---

# Make infratructure easier to rebuild than repair

> *Bill Baker, a distinguished engineer at Microsoft, quipped that we used to treat servers like pets: “You name them and when they get sick, you nurse them back to health. Now servers are treated like cattle. You number them and when they get sick, you shoot them.*

\- The DevOps Handbook p. 141

[CERN agrees with Cattle rather than pets (slide 17)](https://www.slideshare.net/slideshow/cern-data-centre-evolution/15246440#9)

<img src="./assets_deployment_strategies/cern_slide_pets_vs_cattle.png" style="height: 28vh;" alt="cern slide pets vs cattle">


---

# Watch me kill my baby

```bash
scp the_simulator:/var/log/the_simulation/plot_server_error.log .
scp the_simulator:/var/log/the_simulation/simulator_error.log .
scp the_simulator:/var/log/the_simulation/simulator.db .
```

```bash
$ terraform destroy
```

---

# Problem: Avoid configuration drift

> *The 2014 - 2019 State of DevOps Reports led by co-author Dr. Nicole Forsgren show that use of version control for all production artifacts was a higher predictor for software delivery performance*[...]

> *Because in almost all cases, there are orders of magnitude more configurable settings in our environment than in our code. Consequently, it is the environment that needs to be in version control the most.*

\- The DevOps Handbook page 140-141 

---

# Possible solution: Immutable infrastructure

Example. Wanting to update an nginx server. Two ways to do it:

<img src="./assets_deployment_strategies/mutable_immutable_architecture.png" alt="mutable immutable architecture" style="height: 40vh;">

[Source](https://www.opsramp.com/guides/why-kubernetes/infrastructure-as-code/)

**Next topic**: *How do can we achieve this without downtime?*



# File: 04._orchestration.md

<div class="title-card">
    <h1>Orchestration</h1>
</div>

---

# Fault tolerance - One solution: Redundancy

Solution to the single-point-of-failure problem. Creates resilience. 

*The human body is resilient. Give examples of redundancy.*

<details> 
  <summary>The human body</summary>
   The human body has two kidneys, two lungs, two eyes, two ears, and so on. If one fails, the other can take over.
</details>

---

# Scalability

Designing for scalability -> accommodate increased demand. 

- **Vertical scaling**: increase the capacity of a single server

- **Horizontal scaling**: add more servers

[Example](https://www.cloudzero.com/blog/horizontal-vs-vertical-scaling/)

<img src="./assets_orchestration/vertical_horizontal_scaling.png" alt="horizontal vertical scaling" style="height: 30vh;">

---

# Congestion

A bottleneck in the system where the capacity is exceeded.

The solution: load balancing

Example: [Azure Load Balancer](https://learn.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)

<img src="./assets_orchestration/azure_load_balancer.png" alt="azure load balancer">


---

# Example of Load Balancing with Nginx

```nginx
http {
    upstream backend {
        server backend1.example.com;
        server backend2.example.com;
        server backend3.example.com;
    }
}

server {
    location / {
        proxy_pass http://backend;
    }
}
```

`backend` being the name for the docker containers. 

It's also possible to have them on the same server but on different ports.

```nginx
...
  upstream backend {
      server localhost:8080;
      server localhost:8081;
      server localhost:8082;
  }
...
```

Nginx will round robin the requests to the different servers.

---

# Load Balancing and keepalive

[Source: Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-create-a-high-availability-setup-with-heartbeat-and-reserved-ips-on-ubuntu-16-04)

<img src="./assets_orchestration/load_balancing_keep_alive.gif" alt="load balancer keep alive ubuntu digitalocean">

Another pouplar setup is [HAProxy with Keepalived](https://kifarunix.com/configure-highly-available-haproxy-with-keepalived-on-ubuntu/).

---

# Advanced orchestration platforms

- **Kubernetes**

- **Docker Swarm** *(deprecated and added as a plugin to Kubernetes instead)*

- **OpenShift**

- **Mesos**

- **Nomad**




# File: 07._resilience.md

<div class="title-card">
    <h1>Resilience</h1>
</div>


---

# KEA's Resilience Research

---

# Chaos Engineering

> "*Chaos engineering is the discipline of experimenting on a system in order to build confidence in the system's capability to withstand turbulent conditions in production.*" 

[Source - Wikipedia](https://en.wikipedia.org/wiki/Chaos_engineering)

---

# Netflix Simian Army

https://netflixtechblog.com/the-netflix-simian-army-16e57fbab116

https://github.com/Netflix/chaosmonkey

https://netflix.github.io/chaosmonkey/

<img src="./assets_resilience/chaosmonkey_logo.png" alt="chaosmonkey logo">


---

# Story from the trenches


> "*An even more interesting example of resilience at  Netflix  was  during  the  “Great  Amazon  Reboot  of  2014,” when nearly 10% of the entire Amazon EC2 server fleet had to be rebooted to apply an emergency Xen security patch.*

> *When  we  got  the  news  about  the emergency EC2 reboots, our jaws dropped. When we got the list  of  how  many  Cassandra  nodes  would  be  affected,  I  felt ill.”*

> *Then  I  remembered  all  the Chaos  Monkey  exercises  we’ve  gone  through.  My  reaction was, ‘Bring it on!’*"

\- Christos  Kalantzis  of  Netflix  Cloud  Database Engineering

Find exact data on how well they performed on Page 316 in the DevOps Handbook.

> "*Even more surprising, not only was no one at Netflix working active incidents due to failed Cassandra nodes, no one was even in the office — they were in Hollywood at a party celebrating an acquisition milestone.*"

---

# KubeInvaders

Try the Game Mode: 

https://kubeinvaders.platformengineering.it/

---

# Let's create our own "chaos monkey"

In `keasmonkey.sh`:

```bash
#!/bin/bash

while true
do
    echo "Choosing a pod to kill..."

    PODS=$(kubectl get pods | grep -v NAME | awk '{print $1}')
    POD_COUNT=$(kubectl get pods | grep -v NAME | wc -l)

    if [ "$POD_COUNT" -eq 0 ]; then
        echo "No pods found. Exiting loop."
        break
    fi

    K=$(( (RANDOM % POD_COUNT) + 1))

    TARGET_POD=$(kubectl get pods | grep -v NAME | awk '{print $1}' | head -n ${K} | tail -n 1)

    echo "Killing pod $TARGET_POD"
    kubectl delete pod $TARGET_POD

    sleep 1
done
```

---

# Running the `keasmonkey` script

First apply the `deployment_service` from previously:

```bash
$ kubectl apply -f deployment_service.yaml
```

Then run the chaos monkey (on Windows try Git Bash):

```bash
$ ./keasmonkey.sh
```

It will delete a random pod every second.

---

# Kubernetes dashboard

Kubernetes comes with a dashboard. 

This is very easy to access with Minikube. Outside of Minikube it is a bit more complicated and requires login credentials/token.

Let's visualize the `keasmonkey` script. Run the dashboard:

Open the dashboard:

```bash
$ minikube dashboard
```

---

# What is fake about the previous example?

*What made our test useless?*

---

# What are we testing for?

Our little test basically tests Kubernetes' self-healing capabilities.

If our infrastructure was more complex and pods depended on each other, we would gain more insight into how our system behaves under stress.

Remember to introduce real world events such as:

* server crashes
* network failures
* power outages
* hard-drive malfunction

---

# Game days

A game day is a practice where a team simulates a failure on a system to test its resilience. It happens in a predetermined time and all hands are on deck to solve problems that arise.

It is important to clearly define the **blast radius** in advance.

---

# Game days at Amazon

Amazon is known for its game days.

> "*a service is not really tested until we break it in production.*"

\- Jesse Robbins, known as the "Master of Disaster" at Amazon


---

# Game days are scary but they provide us unexpected lessons ahead of disaster

Game days in actual companies end up resulting in a handful of suprising failure that no one was able to predict. It's all about uncovering these failure points.

Examples at **DiRT** teaches us that:

"*It's not just about how to solve problems. Sometimes it's about knowing who to call.*"

...

> "*When the data centers ran out of diesel for the backup generators, no one knew the procedures for making emergency purchases through the supplier, resulting in someone using a personal credit card to purchase $50,000 worth of diesel.*"

\- Kripa Krishnan, Google's **Di**saster **R**ecovery **T**esting (DiRT). 


---

# SRE (Site Reliability Engineering)

https://sre.google/books/

---

# Health checks in Docker containers

https://docs.docker.com/engine/reference/builder/#healthcheck

```yaml
    healthcheck:
      test: curl localhost:8080/available_languages | grep ', "en",'
      interval: 30s
      timeout: 13s
```


---

# Avoid the cargo cult mentality that pervades our industry

Many companies jump on the idea of implementing high-availability, fault-tolerant and highly scalable systems.

In Denmark most companies do not need this but there is a tendency to look at what the big companies are doing. 

You are in no way expected to implement today's topics for your project. The goal is to inform you about the possibilities and how to solve certain challenges, may they present themselves to you.

**Counter point**: The blog post - [You have built a Kubernetes](https://www.macchaffee.com/blog/2024/you-have-built-a-kubernetes/) - details how in an attempt to avoid using Kubernetes and through custom parameterized shell scripts and Docker Compose, a worse version of Kubernetes was built.




# File: 05._kubernetes.md

<div class="title-card">
    <h1>Kubernetes</h1>
</div>

---

# K8s

Originally developed by Google but is now open-source. 

Google runs several billions of containers weekly in Google Cloud:

https://cloud.google.com/containers

<img src="./assets_kubernetes/kubernetes_logo.png" alt="kubernetes logo" style="height: 20vh;">

---

# Features of Kubernetes

**Auto-scaling**.

**Monitoring**: It monitors the health of the containers and the nodes. Kubernetes dashboard comes out of the box.

<img src="./assets_kubernetes/kubernetes_features.png" alt="kubernetes features" style="height: 25vh;">

[Source OpsRamp](https://www.opsramp.com/guides/why-kubernetes/kubernetes-architecture/)

**Automatic Deployment** across different servers, even different regions. 

---

# How Kubernetes works

[![How Kubernetes works](http://img.youtube.com/vi/daVUONZqn88/0.jpg)](https://www.youtube.com/watch?v=daVUONZqn88)

---

# Kubernetes Diagram 1

<img src="./assets_kubernetes/kubernetes_archtecture_diagram.png" alt="kubernetes architecture diagram" style="height: 55vh;">

[Source OpsRamp](https://www.opsramp.com/guides/why-kubernetes/kubernetes-architecture/)

---

# Kubernetes Diagram 2

<img src="./assets_kubernetes/kubernetes_architecture.png" alt="kubernetes architecture diagram" style="height: 55vh;">

[Source OpsRamp](https://www.opsramp.com/guides/why-kubernetes/kubernetes-architecture/)

---

# Kubernetes Architecture

* **Container**: A lightweight, standalone, executable package of software that includes everything needed to run it: code, runtime, system tools, system libraries, settings.

* **Pod**: A group of one or more containers.

A pod shares the same volume, namespace, and network (IP address).

* **Service**: A way to expose an application running in a set of pods as a network service.

* **Node**: A physical or virtual machine.

* **Cluster**: A group of nodes. The Master Node manages the Worker Nodes.


---

# Supported container runtimes

* Docker

* Containerd

* CRI-O

---

# Kubernetes in the cloud

* Linode Kubernetes

* Google Kubernetes Engine (GKE)

* Azure Kubernetes Service (AKS)

* Amazon Elastic Kubernetes Service (EKS)

[EKS pricing calculator](https://calculator.aws/#/createCalculator/EKS)

**Guessing game**: *How much would the default values of 1 cluster (Standard Support) and 2 clusters (Extended Support) cost per month?*

---


# [Optional] AKS hands-on

AKS is included in Azure `Free Services`. That means that the cluster management is free, but you will still be charged for VM, storage and networking usage etc.

Recommended video on how to get started with AKS.

The timestamped part contains a very elegant explanation of the propogation from `Kubectl` -> `Control Plane` -> `Node`. 

[![AKS hands-on](http://img.youtube.com/vi/RUoejLILgyA/0.jpg)](https://youtu.be/RUoejLILgyA?t=144)

---

# Kubernetes is not a silver bullet for scaling

Many think that Kubernetes will magically solve all scalability issues. These issues remain:

* Properly managing container resource allocation

* Anticipating peak demand and scaling accordingly

* Handling inefficient scaling of stateful applications

* Addressing underlying infrastructure bottlenecks

That's why configure management is the essence of a large-scale Kubernetes deployment.

It would not be unusual to have 1 or 2 full-time employees dedicated to managing a large Kubernetes cluster.

---

# Downsides to Kubernetes

| Challenge                                | Details                                                                                                                           |
|------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Meeting isolation standards              | Isolation of applications on the same server is vital for security.                                                               |
| Internal networking challenges           | The latency between services needs to be accounted for in large clusters.                                                         |
| Limited visibility into resource utilization | In large clusters with many applications and services running, it is difficult to know what level of resources systems are consuming. |
| Optimizing resource usage                | As the cluster grows in size, cost management and resource optimization become more critical and more complex.                     |
| Deployment failovers and downtime mitigation | Large-scale application rollouts must have fail-safes to avoid downtime risk.                                                     |
| Reduced visibility into data flows       | As a cluster grows in size and across regions, maintaining visibility into data flows becomes increasingly complex.                |
| Patch management                         | Applying K8s security patches and updates at scale without interrupting service or impacting performance is an operational challenge.|
| Access management and tenant isolation   | For large clusters, isolation between different teams or customers using the cluster must be configured.                           |
| On-prem challenges                       | Running clusters on your own data center infrastructure adds additional management complexities, including avoiding network partitions and upgrading servers. |

[Source](https://www.opsramp.com/guides/why-kubernetes/challenges-with-kubernetes/)

---

# Do you need Kubernetes?

Probably not! Just because Google does it, doesn't mean you should. 

Challenges of Kubernetes:

* Extremely high cost 

* Steep learning curve, time sink

* Configuration complexity, risk of misconfiguration

* Security challenges  

* Computational overhead  

* Local replication difficulty  




# File: 01._introduction.md


<div class="title-card">
    <h1>Orchestration, Deployment Strategies, Maintenance</h1>
</div>

---

# The Final Total Graph of the Simulation

<iframe src="./assets_introduction/Errors in Total by Group.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>


---

# The Final Weekly Graph of the Simulation

<iframe src="./assets_introduction/Errors in the Past Week by Group.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

---

# Let's have a look at your monitors

---

# Weekly DevOps Principle!

**DevOps is culture.**



# File: 05._branching_strategies.md


<div class="title-card">
    <h1>Branching strategies</h1>
</div>

---

# Branching strategies

Why? To allow agile teams to collaborate. Branching strategies is an agreement on how agile teams collaborate and create production-ready releases.

**Note**: The past couple of years there has been an influx of new and shiny branching strategies that everyone suddenly *must* follow. This should give a clue that branching is a problem with no perfect solution. 

---

# Branching strategies 

- **Feature Branching**: Each feature is developed in a separate branch.

- **Trunk-based Development**: All developers merge their changes to the trunk multiple times a day.  

- **Release Branching**: A branch is created for each release.

- **Gitflow**: A branching model that uses master, develop, feature, release, and hotfix branches.

- **GitHub Flow**: Adds the concept of Pull Requests and Github Discussions before merging with main.

---

# Merge vs. Rebase

[![Merge vs. Rebase](http://img.youtube.com/vi/zOnwgxiC0OA/0.jpg)](https://youtu.be/zOnwgxiC0OA?t=180)



# File: 04._linting.md

<div class="title-card">
    <h1>Linting</h1>
</div>

---

# We have already used a linting tool

*Can you think of it?*

---

# Answer: ShellCheck

*What did it do?*

<details> 
  <summary>The command</summary>

        $ shellcheck run_forever.sh 
</details>


---

# Why lint?

Linters perform static analysis on the code without executing it.

> Linters are a [static code analysis tool used to flag programming errors, bugs, stylistic errors and suspicious constructs](https://en.wikipedia.org/wiki/Lint_%28software%29).


Discuss in pairs: *Give some reasons for why you should lint your code. What type of problems can you lint for?*


---

# What can you lint for?

**Error Detection**: Identifies programming errors, such as syntax errors or type mismatches.

**Code Quality and Consistency**: Checks for adherence to coding standards and conventions, ensuring consistency across the codebase.

**Improving Readability**: Helps in formatting code in a readable and maintainable way.

**Finding Potential Bugs**: Detects code patterns that are likely to be errors or could lead to bugs in the future.

**Security**: Identifies security vulnerabilities and insecure coding practices.

**Performance**: Identifies code that could be optimized for better performance. [Interesting example: Million](https://million.dev/)

---

# Popular linters

| Programming Language | Popular Linters                 |
|----------------------|---------------------------------|
| JavaScript           | ESLint, JSHint, JSLint, Standard|
| Python               | Pylint, flake8, Pyflakes, Black |
| Java                 | Checkstyle, PMD, FindBugs       |
| C/C++                | Clang-Tidy, CPPLint, GCC        |
| Ruby                 | RuboCop, Reek                   |
| PHP                  | PHP_CodeSniffer, PHPMD          |
| CSS                  | Stylelint, CSSLint              |
| TypeScript           | TSLint, ESLint                  |
| Go                   | Golint, Gofmt, Go Vet           |
| Swift                | SwiftLint                       |
| Kotlin               | Ktlint, Detekt                  |
| Rust                 | Clippy                          |




---

# When and where to lint?

**Locally before pushing to version control.**

vs.

**CI/CD pipelines.** 

*Let's do some hands-on first and consider the pros and cons of each.*

---


<div class="title-card">
    <h1>Git hooks - Hands-on</h1>
</div>


---

# Let's lint a Node.js project using standard

1. Let's make a Node.js project with intentional code style mistakes. 

2. Run locally: `npx standard --fix` 

We don't want to run --fix in the CI pipeline since it modifies code and the code in the CI pipeline does not update the code in version control.

---

# Git Hooks

It is in the DevOps mindset to try to catch problems as early as possible.

We can disallow developers from pushing if their code isn't up to standard. 

Downside: Git Hooks must be manually configured on every machine. There is no way to push them into version control. 

---

# Git Hooks - Our first hook

Let's first try to create a `hello world` git hook.

First initialize a git repository. 

In the `.git/hooks` folder, create a file called `pre-commit`. You can copy the sample for inspiration (assuming you are in the hooks folder):

```bash
$ mv pre-commit.sample pre-commit
```

Add an echo statement to the file:

```bash
$ echo "Hello, world!" > pre-commit
```

Now try to commit and see the result. 
 
---

# Linting with `Standard`

Create a Javscript file with some intentional errors.

You can run [Standard](https://www.npmjs.com/package/standard#is-there-a-git-pre-commit-hook) in the project to lint the code

```bash
$ npx standard
```

Or to fix it:

```bash
$ npx standard --fix
```

---

# Git Hooks - Adding `Standard` to a hook (*nix and Git Bash)

In the `pre-commit` file replace the content with the following. 

https://www.npmjs.com/package/standard#is-there-a-git-pre-commit-hook

It requires you to have Standard installed. The above script will work if you install it globally:

```bash
$ npm install -g standard
```

Or you could modify the script to use the `npx` command:

```bash
xargs_r -E '' -t npx standard
```


You could also install it locally in the project with (`npm install standard`) and modify the script like this:

```bash
xargs_r -E '' -t ./node_modules/.bin/standard
```

---

# Git Hooks - Adding `Standard` to a hook (Powershell)

```powershell
# Ensure all JavaScript files staged for commit pass standard code style
function xargs-r {
    param (
        [ScriptBlock]$Command
    )

    $paths = git diff --name-only --cached --relative | Select-String -Pattern '\.jsx?$' | ForEach-Object { $_.Line }

    if ($paths) {
        $paths | ForEach-Object {
            &$Command $_
        }
    }
}

$xargsCommand = { param ($path) standard $path }

xargs-r $xargsCommand

if ($LASTEXITCODE -ne 0) {
    Write-Host 'JavaScript Standard Style errors were detected. Aborting commit.'
    exit 1
}
```

---

# pre-commit library

Tip: There is a library called `pre-commit` that can be used to manage and easily install git hooks.

https://pre-commit.com/

---

# devenv.sh

https://devenv.sh/

Built-in support for adding Git Hooks to your project.

---

# Git hooks pros and cons?

*Let's discuss*

---

# Git hooks pros and cons

**Pros**

  - Early Error Detection / Immediate Feedback

  - Prevents bad commits from being checked in to version control

**Cons**

  - Local Only

  - Manual Configuration

  - Bypassable (with the `--no-verify` flag)

  - Cross-Platform Issues (bash scripts could cause problems on Windows)


---

<div class="title-card">
    <h1>Linting in Github Actions</h1>
</div>

---

# sonarlint

IDE extension for linting in real-time.

https://www.sonarsource.com/products/sonarlint/

Works with various IDEs.

---

# CI - Linting example in lint.yaml

This is to give you an idea of how to set up a linter in a CI pipeline.

Look into other linters for Node.js such as ESLint and JSHint.

The previous slides use Standard because it requires no configuration.

```yaml
lint:
    name: 'Run linter'
    defaults:
        run:
        shell: bash
        # Defines the working directory for all run steps in the workflow
        working-directory: ./web
    runs-on: ubuntu-latest
    steps:    
    - uses: actions/checkout@v2
        name: 'Checkout repository'
    
    - name: 'Install Dependencies'
        run: npm install

    - name: 'Run Linter'
        run: npx standard -v
```

*Why doesn't it make sense to run `--fix` in GitHub Actions?*

---

# Superlinter


https://github.com/marketplace/actions/super-linter

---

# hadolint

Once we start working with Docker, we can use [hadolint](https://github.com/hadolint/hadolint) to lint our Dockerfiles.


---

# Break things, let the linter catch you

Focusing on software quality should not make you risk averse. The point of tools like linters is to allow us to fail.

If you only open PRs that do not break anything, then you are not moving fast enough.

And if you break something, then use it as an opportunity to set up tools to prevent it from happening again.




# File: 02._software_quality.md

<div class="title-card">
    <h1>Software Quality</h1>
</div>

---

# Software quality

Are your systems any good?

How good/bad are they?

What can be done to improve them? 

Our goal is to quantify and answer these questions.

---

# What is software quality? - I

The definition is pretty uniform and standardized. 

> "[...] *the totality of characteristics of an entity that bear on its ability to satisfy stated and implied needs.*"

\- [ISO 8402:1994, Quality management and quality assurance – Vocabulary](https://www.iso.org/standard/20115.html)

> "*capability of a software product to satisfy stated and implied needs when used under specified conditions*"
  
\- [_Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — Guide to
SQuaRE_, International Organization for Standardization, Geneva, CH, Standard, May 2015](https://www.iso.org/obp/ui/#iso:std:64764:en)



---

# What is software quality? - II

More definitions:

> "*degree to which a software product satisfies stated and implied needs when used under specified conditions*"

\- [_Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — System and software quality models_, International Organization for Standardization, Geneva, CH, Standard, May 2015](https://www.iso.org/obp/ui/#iso:std:iso-iec:25010:ed-1:v1:en)

> "*degree to which a software product meets established requirements*"

\- [_IEEE 730-2014 IEEE Standard for Software Quality Assurance Processes_](https://standards.ieee.org/standard/730-2014.html)

> "*Good software should deliver the required functionality and performance to the user and should be maintainable, dependable, and usable.*"

\- [I. Sommerville, _Software Engineering_, 9th ed. USA: Addison-Wesley Publishing Company, 2010.](https://www.pearson.com/us/higher-education/product/Sommerville-Software-Engineering-9th-Edition/9780137035151.html)


---

# Why call it "Software Quality" instead of "Code Quality"?

> "[...] software is not just the programs themselves but also all associated documentation and configuration data that is required to make these programs operate correctly."

\- Sommerville _"Software Engineering"_ (9th Ed.)

Also check out: 

https://en.wikipedia.org/wiki/Software_quality

---

<div class="title-card">
    <h1>DevOps vs. Software Quality</h1>
</div>


---

# Definition of Value Stream:

> "*A value stream is an end-to-end set of activities which collectivities create value for a customer.*"

\- James Martin, "The Great Transition"

---

# DevOps vs. Software Quality

DevOps is hyperfocused on delivering value to the customer. During development you should ask:

* What is the value of this feature to the customer?

* How can we accellerate when the feature starts generating value?

But this seems at odds with software quality?

---

# Bringing value to the customer vs. DX

DevOps should not exclude **D**eveloper E**x**perience. 

There are things that don't directly bring value to the customer, but are valuable to the organization. 

---

# The value stream vs. The `ilities`

Industry-wide recommendation is that at least 20% should be reserved for Non-Functional Requirements of the type `ilities` such as:

* maintainability

* manageability

* scalability

* reliability

* testability

* deployability

* security

[Comprehensive list of non-functional requirements](https://quality.arc42.org/properties/)

---


# Pull-requests

*What is the value in making PRs?*

---

# Pull-request - Value

  - Ensuring code quality

  - Avoiding the addition of technical debt

  - Knowledge sharing and opportunity for learning and improvement

  - Sharing insight into new features


---

# Practices for Software Quality: Code reviews - I

> At a cost of 1-2% of the project, a 40% decrease in the number of issues was found.

\- R.A. Baker Jr [_"Code reviews enhance software quality"_](https://dl.acm.org/doi/pdf/10.1145/253228.253461)

> Findings  show  that  unreviewed  commits  (i.e., commits  that did  not  undergo  a  review  process)  have  over  two  times  more chances of introducing bugs than reviewed commits (i.e., commits that  underwent  a  review  process).  In  addition,  code  committed after  review  has  a  substantially  higher  readability  with  respect to  unreviewed  code.

\- G. Bavota et al. [_"Four eyes are better than two: On the impact of code reviews on software quality"_](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.709.2980&rep=rep1&type=pdf)

---

# Practices for Software Quality: Code reviews - II

> we ﬁnd that both code review coverage and participation share a significant link with software quality. Low code review coverage and participation are estimated to produce components with up to two and five additional post-release defects respectively. Our results empirically confirm the intuition that poorly reviewed code has a negative impact on software quality [...]

\- S. McIntosh [_"The impact of code review coverage and code review participation on software quality: a case study of the Qt, VTK, and ITK projects"_](https://dl.acm.org/doi/abs/10.1145/2597073.2597076)


---

<div class="title-card">
    <h1>Technical debt</h1>
</div>

---

# Technical Debt

A metaphor to financial debt:

> "*The longer you wait to pay it off, the more expensive it becomes. Cost of Change (CoC).*"

When prototyping, you will make take technical shortcuts in order to move fast. This is not neccessarily bad, but you need to be aware of the debt you accrue. 

---

# Motivations for technical debt

<img src="./assets_software_quality/motivations_for_technical_debt.png" alt="motivations technical debt">

[Source](https://18f.gsa.gov/2015/09/04/what-is-technical-debt/)

---

# [Types of technical debt](https://blog.logrocket.com/product-management/what-is-technical-debt-examples-prioritize-avoid/#types-of-technical-debt)

* **Code debt**: Poorly written code that is hard to understand, maintain, and extend.

* **Design debt**: Poorly designed code that is hard to understand, maintain, and extend.

* **Infrastructure debt**: Outdated infrastructure that is hard to maintain and scale.

* **Testing debt**: Lack of automated tests, or poorly written tests.

* **Documentation debt**: Lack of documentation or poorly written documentation.

* **People debt**: Lack of skilled people or unmotivated people. 

---

# Avoiding technical debt

<img src="./assets_software_quality/causes_of_technical_debt.png" alt="technical debt causes" style="height: 45vh; background: white;">

The [Source](https://www.sonarsource.com/learn/technical-debt/) goes further into how to avoid technical debt.

Great [list on how to avoid technical debt](https://www.digitalocean.com/resources/article/what-is-technical-debt#10-ways-to-manage-and-reduce-technical-debt).

---

# Concept - Code smells

> "*a code smell is any characteristic in the source code of a program that possibly indicates a deeper problem.*"

https://en.wikipedia.org/w/index.php?title=Code_smell&oldid=932717947#Common_code_smells

The blog post that coined the term:

https://martinfowler.com/bliki/CodeSmell.html


---

<div class="title-card">
    <h1>Software Quality tools</h1>
</div>


---

# Software Quality tools

**SonarQube**: Provides a maintainability and Technical Debt measure/index

<img src="./assets_software_quality/sonarqube_logo.png" alt="sonarqube logo" style="height: 15vh;">

**Code Climate**: Provides a maintainability index

<img src="./assets_software_quality/codeclimate_logo.png" alt="codeclimate logo" style="height: 15vh;">

**Beware** that tools will always give an opionated view of quality. Be critical and ask yourself along with your group members:

> *Do we agree with the tool's assessment?*






# File: 06._cron.md


<div class="title-card">
    <h1>Cron / Cron jobs / Crontab</h1>
</div>

---

# Cron terminology

**Cron**: a time-based job scheduler in Unix-like operating systems. 

**Cron job**: a command or script that is scheduled to run periodically by the cron daemon.

**Crontab** is a file that contains the schedule of cron entries that schedules tasks (commands) to run periodically at fixed times, dates, or intervals.

---

# Cron syntax

```cron
* * * * * command_to_execute
│ │ │ │ │
│ │ │ │ └── Day of the week (0-7, 0 and 7 are Sunday)
│ │ │ └──── Month (1-12)
│ │ └────── Day of the month (1-31)
│ └──────── Hour (0-23)
└────────── Minute (0-59)
```

https://crontab.guru/

---

# How to edit the crontab

The environment variables (`EDITOR`) is optionally. Use it to set the editor you want to use instead of the default one:

```bash
$ EDITOR=nano crontab -e
```

Add the following:

```cron
* * * * * echo "$(date)" >> $HOME/logfile.txt
```

*What does the above do? How often?*

---

# Is it running?

Verify that the cron job is running:

```bash
$ crontab -l
```

Since the smallest unit of time in a cron job is a minute, consider this question while we wait:

*How would we go about running a job every 10 seconds?*

---

# Answer

Let the cron job call a script that contains this:

```bash
#!/bin/bash

for i in {1..6}; do
    echo "$(date)" >> $HOME/logfile.txt
    sleep 10
done
```

You *could* use a while loop and make the script run in the background, but the benefit of a cron job is that it still works after a reboot.

---

# Let's check the log file

```bash
$ cat ~/logfile.txt
```

Great!

---

# Example: Cron job for continuous deployment


```cron
*/5 * * * * cd /path/to/repo && git pull && <command to rerun application>
```

*There's something less optimal about the above approach. Can you spot it?*

---

# Crontab: optimized version

The previous example pulls the repository and restarts the repository every time. Instead, only do it when there is a new commit.

```cron
*/5 * * * * cd /path/to/repo && git fetch && [ "$(git rev-parse HEAD)" != "$(git rev-parse @{u})" ] && git pull && <command to stop the application> && <command to run the application>
```

**Tip**: The cron job is getting complicated. Create a shell script that your cron job can run.

**Note**: These cronjob slides are not an endorsement for picking this solution. They serve to introduce you to the concept.




# File: 03._ci_cd.md

<!-- CI/CD/CD -->

<div class="title-card">
    <h1>CI/CD/CD</h1>
</div>

---

# CI/CD/CD

* Continuous Integration

Pushing code to a Version Control System (VCS such as git etc.).

* Continuous Delivery

Packaging your code (We will create Docker images).

* Continuous Deployment

Deploy to a server.

We will look differently at continuous delivery vs. deployment in this course, but we will call it CI/CD. 

---

# Overview of CI/CD/CD

Goal: automation. 
Term: Pipelines

![CI/CD](./assets_ci_cd/ci_cd_cd.png)

---

# Continuous Integration (CI)

  - Developers frequently merge code changes into a central repository

  - Automatically builds and tests merged code

  - Detects integration issues early on

  - Goal: Resolve problems early and quickly

---

# Continuous Delivery (CD)

  - Ensures merged and tested code is always in a releasable state

  - Automated build process

  - Goal: To have code ready for release

---

# Continuous Deployment (CD)

  - Approach that emphasizes continuously delivering new features and improvements

  - Integrates feedback from users and stakeholders

  - Iterates on the product

  - Continuously deploys updates

  - Provides value at a faster pace

---

# Continuous Delivery vs. Continuous Deployment

There are many different interpretations of the two terms.

Historically, the continuous delivery was the first term to exist. Continuous deployment is a more recent term.

1. For some the two terms are interchangeable. 

2. For others, continuous delivery has been superseded by the term continuous deployment.

3. One popular interpretation is that continuous delivery requires a manual step to deploy to production, while continuous deployment is fully automated (hands-off deployments).

We will go with a 4th interpretation in this course.

---

# This course's interpretation of Continuous Delivery vs. Continuous Deployment

**Continuous Delivery**: Deliver build artifacts. In our case we will build Docker images and publish them to a container registry.

**Continuous Deployment**: Deploy to production. In our case we will deploy the Docker images to a server and run them.

You don't have to agree with this interpretation, but we use it to make a clear distinction between delivering artifacts and deploying to production.

Beware that you might end up in a job that uses the terms differently.

---

# In the DevOps 8, which part relate to CI, CD, CD and CF?

CF = Continuous Feedback. 

*Discuss in pairs*

<div>
    <img src="./assets_ci_cd/möbius_strip.png" alt="Dev Ops Möbius strip"/>
</div>

---

# DevOps 8, CI, CD, CD, CF

<div>
    <img src="./assets_ci_cd/devops_8.png" alt="DevOps 8"/>
</div>

[Source](https://www.atlassian.com/devops/what-is-devops/devops-best-practices)


---


# CI/CD solutions

There are many CI/CD solutions. In our following example we will have a closer look to GitHub Actions.

However, you might consider an alternative technology.

The following lists should link you to some commonly used products.

---

# CI/CD solutions - Self-hosted

[Jenkins](https://jenkins.io/index.html)  

[Bamboo](https://www.atlassian.com/software/bamboo)  

[TeamCity](https://www.jetbrains.com/teamcity/)  

[Concourse](https://concourse.ci)  

[Azure DevOps Server](https://azure.microsoft.com/en-us/services/devops/server/)  

[Drone](https://www.drone.io/)

---

# CI/CD solutions - CI/CD as a service

[Travis CI](https://travis-ci.org/)  

[CircleCI](https://circleci.com)  

[GitHub Actions](https://github.com/features/actions)  

[GitLab CI](https://docs.gitlab.com/ee/topics/build_your_application.html)  

[GoCD](https://www.gocd.org/)  

[AWS CodePipeline](https://aws.amazon.com/codepipeline/)

[Azure DevOps Services](https://azure.microsoft.com/en-us/services/devops/)

---

# Whoknows Variations - Continuous Integration

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_integration

My recommendation is for everyone to fork this repository and try to deploy to the `continuous_integration` branch and see the GitHub Action in action. Feel free to play around with the code and see what happens.


# File: 01._introduction.md


<div class="title-card">
    <h1>Software Quality, Linting, CI</h1>
</div>



---

# Weekly commit activity

<iframe src="./assets_introduction/commit_activity_weekly.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_weekly.svg" />
</div>

---

# Daily commit activity

<iframe src="./assets_introduction/commit_activity_daily.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_daily.svg" />
</div>


---

# PR reminder

Remember to criticially engage with the course material. 

This should be easier once you get the `whoknow_variations` assignments. 


---

# Mandatory I

[Mandatory I](https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/blob/main/00._Course_Material/01._Assignments/00._Mandatories/mandatory_I.md)

Use your energy on the semester project. Use the mandatory to structure and write down your reflections.

---

# Weekly DevOps Principle!

**Collaboration and Communication**

Be nice! Make PRs of a readable size. 

- Instead of a daily standup meeting -> daily PR?

---

# One DevOps definition: CALMS

[![CALMS](http://img.youtube.com/vi/jiDwhKNS9A0/0.jpg)](https://www.youtube.com/watch?v=jiDwhKNS9A0)





# File: 06._devops.md

<div class="title-card">
    <h1>DevOps</h1>
</div>


---

# What is DevOps? A short but informative video by GitHub.

[![What is DevOps?](http://img.youtube.com/vi/kBV8gPVZNEE/0.jpg)](https://www.youtube.com/watch?v=kBV8gPVZNEE)

---

# Why DevOps?

*DevOps is an easy sell because it is focused on creating value (for the business > for customers > for developers):*

Easy to make small changes and fix bugs ⇒ better product for user ⇒ business makes cash

Quicker way to deploy new features ⇒ deliver a more competitive product to the market ⇒ business makes cash

Better security means lesser chance of bad press ⇒ products has a better reputation ⇒ business makes cash

Tests ensure robustness ⇒ production isn’t down ⇒ business doesn't lose profit ⇒ business makes cash

Infrastructure is reproducible ⇒ recovery takes minutes rather than days or weeks ⇒ product is more robust ⇒ business makes cash


---

# Literature: DevOps Handbook

<div>
    <img src="./assets_devops/devops_handbook.png" alt="The DevOps Handbook" style="height:45vh;" />
</div>

---

# Literature: The Phoenix Project

<div>
    <img src="./assets_devops/the_phoenix_project.png" alt="The Phoenix Project"/>
</div>

---

# Historical View 

Before DevOps: release cycle: months - years

Ideal: Multiple times a day

Goal: How do we create infrastructure to reach the ideal without firefighting

Why? To bring value to the users

---

#  Dev vs. Ops

<img src="./assets_devops/dev_vs_ops.png" alt="Dev vs. Ops"/>

---

# The role of operations in a DevOps company

> Dianne Marsh, Director of Engineering Tools at Netflix, states that her team’s
charter is to “support our engineering teams’ innovation and velocity. We don’t
build, bake, or deploy anything for these teams, nor do we manage their
configurations. Instead, we build tools to enable self-service. It’s okay for people
to be dependent on our tools, but it’s important that they don’t become
dependent on us.”

- The DevOps Handbook p. 118

---

# DevOps Möbius strip

<img src="./assets_devops/möbius_strip.png" alt="Dev Ops Möbius strip"/>


---

# Yet another rant

Your company is not DevOps if it has a DevOps team. 

I had a discussion recently where I heard from this company in Denmark saying:

“We have a dedicated DevOps team, so that the developers don’t have to ever concern themselves about pipelines and deployment.”

That is antithetical to the goal of DevOps. The idea of DevOps is to give everyone a stake in the product by making them own the entire flow.

That company calls itself DevOps but is actually doing the opposite. 

---

# DevOps is a culture

Values on display at [Factbird](https://factbird.com/).

<div style="display: flex; justify-content: space-between;">
  <img src="./assets_devops/factbird_value_1.png" alt="fact bird values" style="height: 25vh;">
  <img src="./assets_devops/factbird_value_2.png" alt="fact bird values" style="height: 25vh;">
</div>
<img src="./assets_devops/factbird_value_3.png" alt="fact bird values" style="height: 20vh">

---

# Shook's model of behavior

**Change behavior to change culture**

<img src="./assets_devops/shooks_model_of_behavior.png" alt="john shook change behavior culture" style="height: 40vh;">

[Image source](https://www.oreilly.com/content/business-transformation-starts-with-leadership-transformation/)

\- John Shook - First American manager at Toyota


---

# DevOps culture = Review culture

It's a culture of transparency. 

---

# Code Reviews at Google

<img src="./assets_devops/code_review_turnaround_by_size.png" alt="google code review turnaround size" style="height: 50vh;">

The larger the change, the longer to get reviews completed. 

[Source](https://qconsf.com/sf2010/dl/qcon-sanfran-2010/slides/AshishKumar_DevelopingProductsattheSpeedandScaleofGoogle.pdf)

---

# Pair programming

*What do you personally think about it?*

There are no wrong answers.

---

# A quote

> "I can’t help wondering if pair programming is nothing more than code review on steroids... The advantage of pair programming is  its  gripping  immediacy:  it  is  impossible  to ignore  the  reviewer  when  he  or  she  is  sitting  right  next  to you.

> Most  people  will  passively  opt  out  [of reviewing code] if given the choice. With pair programming, that’s  not  possible.  Each  half  of  the  pair  has  to  understand the code, right then and there, as it’s being written. Pairing may  be  invasive,  but  it  can  also  force  a  level  of communication that you’d otherwise never achieve.”"

\- Jeff Atwood, One of the founders of Stack Exchange

---

# Slower but better

> "paired  programmers  are  15%  slower  than  two independent individual programmers, while “error-free” code  increased  from  70%  to  85%.  Since  testing  and debugging are often many times more costly than initial programming,  this  is  an  impressive  result.  Pairs typically  consider  more  design  alternatives  than programmers working alone and arrive at simpler, more maintainable  designs;  they  also  catch  design  defects early."

\- Dr. Laurie Williams (Study performed in 2001)

---

# The roadmap for the next two weeks

Please read all the material before the guest lecture. 

Let the guest lecture inspire you. 

There is dedicated time to discuss the more philosophical aspects of DevOps and a chance for you to be critical of the concepts the week after. 

For now, focus on understanding the concepts and engaging with the literature.



# File: 02._docker-compose.md

<div class="title-card">
    <h1>Docker-compose</h1>
</div>


---

# Recap from last semester

The assumption is that you have already with docker-compose. 

Recap of what it is:

We can define multiple services, networks, and volumes in a single file.

Docker-compose provides a simple singular command to start, stop, and manage multiple containers at once.

---

# Docker-compose vs. Docker compose

`docker-compose` is the separate command-line tool from Docker. It allows us to define and run multi-container Docker applications. Written in Python.

A more recent attempt has been made to include docker compose functionality in the Docker CLI. The plugin can be invoked with `docker compose`. Rewritten in Go.

If you want to use `docker-compose` you will have to install it separately. (`brew install docker-compose`, `choco install docker-compose`, etc.)

---

# Docker-compose and Docker compose are not interchangeable

Given this compose file:

```Dockefile
services:
  web:
    build: ./node_project
```

`$ docker-compose build web` will generate the following image tag: `node_project_web`

`$ docker compose build web` will generate the following image tag: `node_project-web`

Notice the hyphens and underscores. 

This will matter if you are using the image name in your setup. In all of the course material, I will use `docker-compose` for consistency.

---

# Let's explore at a compose file

Are you familiar with `Awesome Compose`?

*Look at this file below and try to understand it line by line*:

https://github.com/docker/awesome-compose/blob/master/spring-postgres/compose.yaml

Feel free to discuss it with people around you.

---

# Quick quiz

```yaml
services:
  web:
    build: .
    ports:
      - "8000:8000"
  db:
    image: postgres
    ports:
      - "8001:5432"
```

*Where is the Dockerfile defined? How do you know?*

<details> 
  <summary>Answer</summary>
  It is defined in the same directory as the compose file.
</details>


*What is the default port for PostgreSQL? What is the other number for?*

<details> 
  <summary>Answer</summary>
  Default port for PostgreSQL is `5432`. 
  The other number, `8001`, is the port that the container will expose i.e. the port you can connect to the database from the outside.
</details>

---

# [Networking](https://docs.docker.com/compose/networking/)

For example, suppose your app is in a directory called `myapp`, and your compose file looks like this:

```yaml
services:
  web:
    build: .
    ports:
      - "8000:8000"
  db:
    image: postgres
    ports:
      - "8001:5432"
```

When you run docker compose up, the following happens:

1. A network called `myapp_default` is created.
2. A container is created using web's configuration. It joins the network `myapp_default` under the name web.
3. A container is created using db's configuration. It joins the network `myapp_default` under the name db.

---

# Volumes vs. Bind mounts

> "Volumes are the preferred mechanism for persisting data generated by and used by Docker containers. While bind mounts are dependent on the directory structure and OS of the host machine, volumes are completely managed by Docker."

> "a volume doesn't increase the size of the containers using it, and the volume's contents exist outside the lifecycle of a given container."

[Source - Docker Docs](https://docs.docker.com/engine/storage/volumes/)

---

# Volume example with Nginx

**Problem**: We want to define a configuration file for nginx.

**Solution 1**: Mount your configuration file when running the container:

```bash
$ docker run --name my-custom-nginx-container -v /host/path/nginx.conf:/etc/nginx/nginx.conf:ro -d nginx
```

[Source - DockerHub](https://hub.docker.com/_/nginx/)

**Solution 2**: Build a custom image with the configuration file:

```Dockerfile
FROM nginx
COPY nginx.conf /etc/nginx/nginx.conf
```

```bash
$ docker build -t my-custom-nginx .
$ docker run --name my-custom-nginx-container -d my-custom-nginx
```

---

# Cleaning up

## Clean up

```bash
$ docker compose rm -v
```

## Nuclear clean up

```bash
$ docker stop $(docker ps -q)
$ docker rm $(docker ps -aq)
$ docker system prune -a --volumes -f
```

---

# Hot tip

Remembering all the `docker-compose` commands are tedious and they take time to type. 

*How can we combine a previous lesson in order to make our life easier?*

(I will give you this hot tip for free. In the future I want you all to be better at identifying small pain points.)

---

# Create a makefile

```makefile
.PHONY: postgresql access_postgresql all

postgresql:
	@echo "Starting Docker Compose in postgresql folder..."
	cd postgresql && docker-compose up

access_postgresql:
	@echo "Logging onto PostgreSQL..."
	docker exec -it postgres_db psql -U postgres -d pagila

all: postgresql access_postgresql
```

Now you can run `make postgresql` to start the database and `make access_postgresql` to access it.




# File: 03._hot_reload_in_docker.md

<div class="title-card">
    <h1>Hot reload in Docker</h1>
</div>

---

# Live reload / Hot reload

| Language   | Tool                             |
|------------|----------------------------------|
| Python     | Comes built-in with many frameworks |
| Java       | `jrebel`                         |
| Node.js    | `nodemon`                        |
| Rust       | `cargo watch`                    |
| Ruby       | `guard`, `rerun`                |
| Go         | `air`, `realize`                 |

Note: These tools are not for production.

**Problem**: Docker makes it harder to achieve hot-reload.  

**Goal**: Improve the development experience by automatically reloading the application when the code changes.

---

# Let's create a simple server in Node.js

1. Let's create a folder called `04._Docker_Node_Project`.

2. Run `npm init -y` to create a `package.json` file.

3. Install Express (a server framework) with `npm install express`.

4. Create an `app.js` file with the following content:

```javascript
const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send({ data: 'Hello, World!' });
});

app.listen(8080, () => {
  console.log('Server is running on port', 8080);
});
```


---

# Nodemon with Docker example

Create a `Dockerfile.dev` file:

```Dockerfile
FROM node

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install

# Install nodemon globally
RUN npm install -g nodemon

COPY . .

CMD npm config set prefer-offline true && nodemon --legacy-watch app.js
```

---

# docker-compose.dev.yml

Create a docker-compose file outside of `node_project`. This allows for a nicer separation from the server if we create more services later on. 

The docker-compose file allows us to define volumes which is necessary for caching the `node_modules` folder:

```Dockerfile
services:
  backend:
    build:
      context: ./node_project
      dockerfile: Dockerfile.dev
    ports:
      - "8080:8080"
    volumes:
      - ./node_project:/usr/src/app
      - backend_node_modules:/usr/src/app/node_modules

volumes:
  backend_node_modules:
```

---

# Running the setup

Where the `docker-compose.dev.yml` file is located:

```bash
$ docker-compose -f docker-compose.dev.yml up --build
```

Try to make a change in `app.js` and see the magic happen.


---

# WhoKnows Variations - Continuous Delivery

Let's look at the different guides and run the application locally.

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_delivery/

To run the application locally, cd to `src` where the `docker-compose.dev.yml` file is and run the following command:

```bash
$ docker-compose -f docker-compose.dev.yml up --build
```


# File: 07._continuous_delivery.md


<div class="title-card">
    <h1>Continuous Delivery</h1>
</div>


---

# Same discussion again

> "A CI system clones the codebase for the software under consideration from a source control system such as GitHub, builds the software into an artifact that can be a binary, a tar archive, or a Docker image, and, very importantly, also runs unit and/or integration tests for the software. A CD system deploys the artifacts built by the CI system to a target environment. This deployment can be automated for nonproduction environments, but usually includes a manual approval step for production. A more advanced type of such systems is a continuous delivery platform, which automates the deployment step to production and is capable of rolling back the deployment based on metrics obtained from monitoring and logging platforms."

N. Gift et al. [Python for DevOps](https://www.oreilly.com/library/view/python-for-devops/9781492057680/)

*Do you consider anything off about the definition above?*

<details> 
  <summary>Answer</summary>
  
  The definition above seems to consider building Docker images as part of Continuous Integration.
  
  Most other sources would not agree with this. 
  It's important to understand that the responsibility of each step is fluid and defined differently in different organizations.
</details>

---

# Deploying a Docker container to GitHub Packages

Remember to specify the correct image name under the organizations namespace in the docker-compose file. 

For instance:

```yml
services:
  backend:
    build: ./backend
    image: ghcr.io/<org_name>/<image_name>:latest
    ports:
      - "8080:8080"
    volumes:
      - ./backend:/usr/src/app
      - backend_node_modules:/usr/src/app/node_modules
    depends_on:
      db:
        condition: service_healthy
    environment:
      DATABASE_HOST: db
```

---

# Whoknows variations - Continuous Delivery

This time, let's look at how Continuous Delivery is achieved and where to find GitHub Packages.

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_delivery

---

# Whoknows variations - `is_valid_crpat.sh` script

It can be hard to verify that the CR PAT that you've generated has the right permissions to deploy packages and it is time consuming to debug in workflows. 

I've created a script called `is_valid_crpat.sh` in the root of the [whoknows variations - continuous delivery branch](https://github.com/who-knows-inc/whoknows_variations/tree/continuous_delivery).

Let's run it!




# File: 05._agile.md

<div class="title-card">
    <h1>Agile</h1>
</div>

---

# Historical View: NOT! agile

Software __engineers__ created software **blueprints**.

Before you could even start implementing (coding) you had to do:

- Feasibility study, Market research

- Risk analysis

- Requirement analysis

- Write thorough specification

- System and software design

- Feature extraction and estimation

---


# The waterfall model

<div>
    <img src="./assets_devops//waterfall_model.png" alt="Waterfall model"/>
</div>

Source: https://theincrowdvlog.com/article/8-fundamental-sdlc-models-every-developer-should-know-ishir

---

# Discuss: What are the problems with the waterfall model?

---

# Don't be a hater: Waterfall model has its place

For some projects the waterfall model is the right choice. For instance, when there is only one iteration needed before the project is done. 

Also, analyzing and planning before coding is extremely important, especially for large systems. 

Agile development does not eliminate those steps.
Instead it allows one to move back and forth between the steps. 

---

# The Agile Manifesto

https://agilemanifesto.org/

---

# Video about The Agile Manifesto

[![The Agile Manifesto - 4 Agile Values Explained](http://img.youtube.com/vi/rf8Gi2RLKWQ/0.jpg)](https://www.youtube.com/watch?v=rf8Gi2RLKWQ)

(Sorry about the happy ukulele music.) 

---

# Let's be critical!

Research into the state of agile in the industry: 

https://www.itpro.com/software/agile-development-is-fading-in-popularity-at-large-enterprises-and-developer-burnout-is-a-key-factor

Problems: 

- Culture clash: Organizational resistance
- Lack of leadership support
- Siloed teams 

> "“The larger the organization, the more likely it is to use a hybrid model,” the report said, noting that bigger teams are also more likely to still use waterfall."

The research still finds value in agile. It finds it to be best in small organizations. 

---

# Be critical of buzzwords in this industry

Many companies claim that they're agile when they're not. 




# File: 04._debug_docker-compose.md

<div class="title-card">
    <h1>Debug docker-compose</h1>
</div>

---

# Let's set up a Node.js project

In a new directory:

```bash
$ npm init -y
$ npm install express
```

In the top-level of package.json change to `type: module`.

---

# Let's create a simple Express server

In `app.js`:

```javascript
import express from 'express';
const app = express();

app.get('/', (req, res) => {
    res.send({ data: 'Hello World!'});
});

app.listen(80, () => {
    console.log('App running on port 80');
});
```

---

# Create the faulty `Dockerfile`

Create a folder called `app` and add to the `Dockerfile`:

```Dockerfile
FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]
```

---

# Create the faulty `docker-compose.yml`

Outside of the `app` directory create a `docker-compose.yml`:

```yaml
version: '3.8'
services:
  app:
    build:
      context: ./app
      dockerfile: Dockerfile
    ports:
      - "3000:80"
    networks:
      - app_net

  db:
    image: postgres
    environment:
      POSTGRES_USER: root
      POSTGRES_PASSWORD: pass123
    networks:
      - db_net

networks:
  app_net:
    driver: bridge
  db_net:
    driver: bridge
```

---

# Let's run it

```bash
$ docker-compose up --build
```

---

# Did it start?

Is the process running? How do we check?

<details> 
  <summary>Answer</summary>
    
    <!-- ```bash -->
    $ docker-compose ps -a
    <!-- ``` -->
</details>

How do we check the logs?

<details> 
  <summary>Answer</summary>

    <!-- ```bash -->
    $ docker-compose logs <container_name>
    <!-- ``` -->
</details>


---


# You might've noticed it when running `docker-compose up --build`

But the it doesn't run because it expect to find a start script in `package.json`.

Add it:

```json
"scripts": {
  "start": "node app.js"
}
```

Run `docker-compose up --build` again and check if it's running.

```bash
$ docker-compose ps
```

---

# Check the logs

You should be able to guess the `container_name` based on how it named the db service:

```bash
$ docker logs <container_name>
```

There doesn't seem to be any startup errors. It's running as it should on port `80`.

But try to access it from `localhost:80`. *Does it work?*

---

# Verify what ports have been opened in the container

See which ports have been opened in the container:

```bash
$ docker ps --format "{{.Names}}: {{.Ports}}"
```

`ss` is a utility to investigate sockets. It's an alternative to `netstat`. Use it to checkout the app:

```bash
$ docker exec -it <container_name> ss -tuln
```

---

# Let's see if the environment variables work 

In `app.js`, change the route to the following:

```javascript
app.get('/', (req, res) => {
  res.send({ data: `Hello from the ${process.env.NODE_ENV} environment` });
});
```

Where has the `NODE_ENV` environment variable been set? What do we expect it to be?

Rerun `docker-compose up --build` and check in the browser if it works. 

---

# It doesn't work

In the browser it says:

```json
{
  "data": "Hello from the undefined environment"
}
```

Let's see if the environment variable is set in the container.

```bash
$ docker exec <container_name> env | grep NODE_ENV
```

---

# The way we defined the environment variable is incorrect

In the `docker-compose-yml` file, we can use either:

```yaml
  environment:
      - NODE_ENV=production
```

or

```yaml
  environment:
      - NODE_ENV: production
```

---

# Let's test out the database

Install the PostgreSQL driver (`pg`):

```bash
$ npm install pg
```

Add this to the `app.js`:

```javascript
import pkg from 'pg';
const { Pool } = pkg;

const pool = new Pool({
  user: process.env.POSTGRES_USER,
  host: 'db',
  database: 'postgres',
  password: process.env.POSTGRES_PASSWORD,
  port: 5432,
});

pool.query('SELECT NOW()', (err, res) => {
  if (err) {
    console.error(err);
  } else {
    console.log(res.rows[0]);
  }
});
```

---

# First: Let's debug the container

Verify the database container is running:

  ```bash
  $ docker-compose ps
  ```

Check logs for database startup issues:

  ```bash
  $ docker logs <db_container_name>
  ```

---

# Next: Let's debug the connection

Pre-debug step: Install `ping` in the app container:

  ```bash
  $ docker exec -it <app_container_name> apt-get update
  $ docker exec -it <app_container_name> apt-get install -y iputils-ping
  ```

Test connection between containers (using Docker’s built-in networking):

  ```bash
  $ docker exec -it <app_container_name> ping db
  ```

We are **not** able to ping it.

Try connecting manually to the db container:

  ```bash
  $ docker exec -it <db_container_name> psql -h db -U root -d postgres
  ```

But we *are* able to access the database.

---

# See which networks the containers are connected to

List all networks:

```bash
$ docker network ls
```

Check which networks the containers are connected to:

```bash
$ docker inspect <app_container_name> --format='{{json .NetworkSettings.Networks}}' | jq '.[].NetworkID'
$ docker inspect <db_container_name> --format='{{json .NetworkSettings.Networks}}' | jq '.[].NetworkID'
```

`.[].NetworkID'` is a `jq` filter to only display the network id. You can also try without it.

The networks have different ids. They are not connected to the same network.

---

# Simplify the `docker-compose.yml` and let them join the same network

```yaml
version: '3.8'
services:
  app:
    build:
      context: .
      dockerfile: Dockerfile
    ports:
      - "3000:80"
    environment:
      - NODE_ENV=production

  db:
    image: postgres
    environment:
      POSTGRES_USER: root
      POSTGRES_PASSWORD: pass123
```

---

# Problems with the environment variables again

To see the environment variables in the container:

```bash
$ docker exec <app_container_name> env
```

*What is the problem? How do we fix it?*


---

# The problem is the environment variables are not set

The db credentials have not been defined as environment variables on the app container. 

There are better solutions that will not require us to push the environment variables but for now let's add them to the docker-compose file:

```yaml
environment:
    POSTGRES_USER: root
    POSTGRES_PASSWORD: pass123
```

Try it out. It should work now. 



# File: 01._introduction.md


<div class="title-card">
    <h1>Docker-compose, DevOps, Continuous Delivery</h1>
</div>

---

# Where are we in the course? Milestones.

[Weekly Plan](https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/blob/main/00._Course_Material/00._Meta_Course_Material/about_the_course.md#course-overall-structure)

---

# Weekly DevOps Principle!

**The A in CALMS**

Automate everything!

Remove friction, make everyone's life easier.




# File: 02._the_legacy_project.md

<div class="title-card" style="color: cyan;">
    <h1>The legacy project</h1>
</div>

---

# This is how it all started

A group of students tried to develop a search engine in 2009 with the latest technology at its time. 

They called it: `¿Who Knows?`. 

<img src="./assets/monkgroup.png" alt="monk group legacy team" style="height: 45vh;">


---

# What they managed to create

 - a backend

 - a frontend

 - an SQLite database (containing scraped Wikipedia articles about programming)

---

# Website screenshot

<img src="./assets/whoknows_website.png" alt="whoknows website screenshot">


---

# But it was abandoned

After they presented their main thesis in January 2010, the project was abandoned.

The stack is outdated and the code is not maintained.

The code is in many ways flawed. 

The database contains outdated content from that date or prior. 

Your group will inherit their legacy code. But it's too much to rewrite it in one go. We need CI/CD pipelines to help us rewrite in increments. 

---

# It will be your job to:

  - Analyze the code for flaws

  - Modernize the stack

  - Update the database content


But as a starting point, we need to get the code. 

---

<div class="title-card">
    <h1><a href="https://en.wikipedia.org/wiki/Software_archaeology">Source code archeology</a></h1>
</div>

---

# The only thing we managed to dig up

 - An IP address. 

 - Username

 - Password

Question: *Now what?*

---

# SSH

```bash
ssh <username>@<ip_address>
```

<!-- Optionally, to force it to use password instead of key (this might not be needed for you): 

```
ssh -o PreferredAuthentications=password -o <username>@<ip_address>
```
-->

Username: `monkgroup`

Password: `blackmonktime!`

<!-- todo -->
IP address: `52.178.171.76`

---

# How do we check if anything is running? And on which port?

There are multiple ways to do it. 

*Can you think of one?*

---

# Nmap

Usually, `nmap` is used for port scanning other servers but we can use it locally. 

Let's see if we can run it.

```bash
$ sudo nmap
```

`nmap` could be a good start but it's possible that something is running on the server that isn't exposed to the network.

---

# **P**rocess **s**tatus with `ps`

List all processes:

```bash
$ sudo ps aux
```

Too much output. Let's filter with `grep` (Global Regular Expression Print):

```bash
$ sudo ps aux | grep "whoknows"
```

Maybe not so useful but we can see that it runs with `python2`.


---

# **l**i**s**t **o**pen **f**iles with `lsof`

The `-i` flag specifies network files. 

```bash
$ sudo lsof -i
```

The port is listed as: `*:http-alt`

<details> 
  <summary>Question: What port is that?</summary>
    Port 8080
</details>

Or use the network ports flag (`-nP`) to see the port number. 

```bash
$ sudo lsof -i -nP
```

---

# Doing it again with `netstat`

```bash
$ sudo netstat -tuln
```

`t`: TCP

`u`: UDP

`l`: listening to ports

`n`: numeric output (no DNS lookup)

---

# Where is the code?

---

# We found some code

How do we get it locally?

---

# Secure copy

From your **local machine** (not ssh'd), run this command:

```bash
$ scp -r <username>@<ip_address>:/path/to/directory /path/to/destination
```

The `-r` flag is required because we are retrieving a directory. Without `-r`, it will fail with:

```bash
scp: download /path/to/directory/: not a regular file
```

Replace `/path/to/directory` with `/home/`. Try to figure out the rest. 

DO NOT run this while ssh'd into the server!

---


<div class="title-card" style="color: cyan;">
    <h1>Running it locally</h1>
</div>

---

# This section requires you to have `python2` installed

Windows: You can install it with `chocolatey`:

```powershell
$ choco install python2
```

Mac: You can install it with `homebrew`:

```bash
$ brew install python@2
```

Python 2 is outdated. The point is that after today you should not need it again for this course.

You can choose to install it, if it's simple or lean back and watch and try to answer the questions. 

---

# Python versions

Write Python in your terminal and hit `tab` to see suggestions. What do you see? Do you see `python2`?

Note that `python2` and `python3` are shorthand for the highest available version of Python 2 and Python 3 respectively. 

Additionally, in my tutorials I might write `python` instead of `python3`.

That's because, I have an alias that runs the latest version of Python 3 when I type `python`.

You can consider setting that up too. 

---

# Let's run it

*Problems?*

---

# We didn't get the database

*Where is the database?*

*What is the command to get it?*

---

# Getting the database 

```bash
$ scp monkgroup@<ip_address>:/tmp/whoknows.db .
```

---

# Let's run it again

```bash
$ python main.py
```

The problem is that it has valid Python 2 syntax but not valid Python 3 syntax.

Instead of remembering the syntax, we can use a tool to help us with the different commands.

---

# `Make`

A build automation tool. Allows us to run commands. 

[Make (software)](https://en.wikipedia.org/wiki/Make_%28software%29)

Actions are defined in a `Makefile`.

Can you find it?

---

# Install `make`

Comes with *nix. The following is only needed for Windows users: 

```powershell
$ choco install make
```

---

# Run using `make`

Execute the command where the `Makefile` is located. 

```bash
$ make run
```

---

# Any more snooping suggestions? 





# File: 01._course_introduction.md


<div class="title-card" style="color: cyan;">
    <h1>Welcome to DevOps</h1>
</div>
 

---

# Meta-course introductions

This week: About the course

Next week: About the exam

---

# Course platforms

## Teams 

- Communication
- Hand-ins

## GitHub

- Assignments
- Slides
- Code 
- Tutorials

The course repository is pinned in the General Teams channel!


---

# About the course

https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/blob/main/00._Course_Material/00._Meta_Course_Material/about_the_course.md

---

# Motivation - Why you would want to work hard at this course

Good preparation for your internship next semester. 

Closest to real life. Most lessons learned will prove useful in your professional career. 

---

# Weekly DevOps Principle!

**Continuous improvement and learning!**

**Culture of collaboration and shared responsibility**

---

# Group work

Let's line you up to match your ambitions.

---

# Let's form groups!

3 - 4 students.

---

<div class="title-card" style="color: cyan;">
    <h1>A small rant</h1>
</div>

---

# What is DevOps?

We aim to be able to answer this by the middle/end of the course. It won't be the focus until a couple of weeks in.

Even though DevOps is not a protected title and the understanding of it has changed through the years...

...I would claim that you have not been DevOps at KEA so far.


---

# Is it DevOps?

DevOps is **not** just technology. It's **culture**. But...

<img src="./assets/devops_technologies.png" alt="devops 8" style="height: 35vh;">

[Source](https://shalb.com/blog/what-is-devops-and-where-is-it-applied/)

Just like how being 10% agile doesn't make you agile at all. 

A good gauge is to ask, "How do you monitor?" 

---

# The exam question - Are we DevOps?

At the exam you will be expected to reflect as a team and answer these two questions:

1. What made you DevOps?

2. In what ways were you not DevOps?




# File: 03._conclusion.md


<div class="title-card" style="color: cyan;">
    <h1>Conclusion</h1>
</div>

---

# We now enter start-up mode

The most exciting times with lots of small tasks to do!

---

# What now?

If time permits, this is how we aim to finish every week.

  1. Q&A session based on previous week's work (prepare questions ahead of class)

  2. Go through all the course work + Q&A session

  3. Coordinate with your groups (if time allows)




# File: 07._terraform_github_provider.md


<div class="title-card">
    <h1>Terraform - GitHub Provider</h1>
</div>

---

# X as Code

<div>
    <img src="./assets_terraform_github_provider/X_as_Code.png" alt="X as Code" style="height: 40vh;"/>
</div>

[Source](https://youtu.be/f5EpcWp0THw?list=PLy7NrYWoggjxKDRWLqkd4Kbt84XEerHhB&t=49)

---

# A GitHub provider 

GitHub has created [a provider](https://registry.terraform.io/providers/integrations/github/6.5.0/docs) for Terraform.

With it, you can codify your GitHub infrastructure. 

---

# Prerequisites

1. Create a PAT token that has the following scopes: `repo`, `admin:org` (which implicitly contains `admin:read`).

This is different to the Read/Write permissions for GitHub Packages in CR PAT. 

2. Create a new organisation. This can only be done through the UI.

---

# Create `variables.tf`

```hcl
variable "github_token" {
  type = string
}

variable "github_org" {
  type = string
}

variable "team_members" {
  type = list(string)
}
```

---

# Define the secrets in `terraform.tfvars`


```hcl
github_token = "github_token_here"
github_org   = "name_of_the_organisation"
team_members = ["your_github_username"]
```

---

# In `main.tf`

```hcl
provider "github" {
  owner = var.github_org
  token = var.github_token
}

resource "github_repository" "repo" {
  name               = "terraform_provisioned_repo"
  description        = "Provisioned via Terraform"
  visibility         = "public"
  has_issues         = true
  has_projects       = true
  has_wiki           = true
  auto_init          = false
  license_template   = "mit"
  gitignore_template = "Python"
  archive_on_destroy = true
}

resource "github_branch_default" "default" {
  repository = github_repository.repo.name
  branch     = "main"
}

resource "github_repository_file" "readme" {
  repository          = github_repository.repo.name
  file                = "README.md"
  content             = "# Terraform Provisioned Repo \n\nThis repository was provisioned using Terraform."
  commit_message      = "Initial commit"
  overwrite_on_create = true
  branch              = "main"
}

resource "github_repository_file" "github_dir_placeholder" {
  repository          = github_repository.repo.name
  file                = ".github/.keep"
  content             = "This has been provisioned by Terraform"
  commit_message      = "Create .github directory"
  overwrite_on_create = true
  depends_on          = [github_repository_file.readme]
  branch              = "main"
}


resource "github_branch_protection" "main" {
  repository_id = github_repository.repo.node_id
  pattern       = "main"

  required_pull_request_reviews {
    required_approving_review_count = 1
    dismiss_stale_reviews           = false
    require_code_owner_reviews      = false
  }

  enforce_admins = false
}

resource "github_team" "example_team" {
  name        = "core-devs"
  description = "Core developers team"
  privacy     = "closed"
}

resource "github_team_membership" "members" {
  for_each = toset(var.team_members)
  team_id  = github_team.example_team.id
  username = each.value
  role     = "maintainer"

  depends_on = [github_team.example_team]
}
```

---

# Try to provision the resources

```bash
$ tf init
$ tf fmt
$ tf validate
$ tf plan
$ tf apply
```

Check in the UI that the:

1. [team exists](https://github.com/orgs/testterraformprovider/teams)

2. [repository exists](https://github.com/orgs/testterraformprovider/repositories)

3. [branch rule was setup](https://github.com/testterraformprovider/terraform_provisioned_repo/settings/branches)

---

# Archiving vs. Deleting repositories

In `main.tf` the following line has been defined:

```hcl
  archive_on_destroy = true
```

1. If it has been set to `true`, then the repository will be archived. Running `tf apply` again will not work because the repository already exists. The repository must first be manually deleted.

2. If it is set to `false`, then the repository cannot be deleted and the `tf destroy` command will fail with the following error:

```text
│ Error: DELETE https://api.github.com/repos/testterraformprovider/terraform_provisioned_repo: 403 Must have admin rights to Repository. []
```

This is not a problem with appropriate permissions or ownership but simply GitHub disallowing deleting repositories this way as a security mechanism. Do it manually in the UI first.

---

# Destroy 

Time to destroy the resources:

```bash
$ tf destroy
```

Everything will be destroyed except for the repository which will be archived.






# File: 05._terraform_hands-on.md


<div class="title-card">
    <h1>Terraform - Get Started</h1>
</div>

---

# Install and log in to `az`

`az` is the Azure CLI. By logging in locally Terraform can get access to our cloud.

https://developer.hashicorp.com/terraform/tutorials/azure-get-started/azure-build

```bash
$ az login
```

Verify the login:

```bash
$ az account show
```

---

# Clarification: Terraform under the hood

Though possible to provision everything through `az`, this is not how Terraform does it.

Terraform uses `az` to generate a user token for authorization.

This token is used to validate against what they call [Azure REST API](https://learn.microsoft.com/en-us/rest/api/azure/).

---

# Install Terraform

https://developer.hashicorp.com/terraform/install?product_intent=terraform

Success criterion: You can run the following and see the version number:

```bash
$ terraform --version
```

---

# Suggestions for later 1: Install auto-completion for Terraform

Install terraform auto-complete (tab completion) for your terminal:

https://developer.hashicorp.com/terraform/tutorials/azure-get-started/install-cli#enable-tab-completion

---

# Suggestions for later 2: Alias `terraform` as `tf`

Aliasing the `terraform` command so that you can invoke it by simply typing `tf` is pretty standard practice for Terraform users.

***nix**: 

Write `alias tf="terraform"` in the terminal and it will work in the session.

For a more permanent solution add this to your terminal's rc file (such as ~/.bashrc, ~/.zshrc).

**Windows**: Create a terminal profile if it doesn't exist, in either case open it

```powershell
$ if (!(Test-Path -Path $PROFILE)) { New-Item -ItemType File -Path $PROFILE -Force }
notepad.exe $PROFILE
```
You can now manually add this line to it and save:

```powershell
Set-Alias -Name tf -Value terraform
```

---

<div class="title-card">
    <h1>First Terraform project - Let's test it out</h1>
</div>

---

# Let's create our first Terraform project

In an empty folder run:

```bash
$ terraform init
```

It is missing a configuration file. Let's create `main.tf`. Then run init again.

---

# .tf files and VSCode Extensions

The `.tf` file extension is used for Terraform. In VSCode there are extensions for syntax highlighting and Intellisense. 

The official one by Hashicorp seems to be universally hated. Instead, consider the one that is higher rated.

<img src="./assets_infrastructure_as_code/hashicorp_vscode_extension_review.png" alt="hashicorp vscode extension review">

---


<div class="title-card">
    <h1>Terraform Workflow</h1>
</div>

---

# Terraform workflow - I

<img src="./assets_infrastructure_as_code/terraform_workflow_1.png" alt="Terraform workflow stages" style="height: 45vh;">

Source: https://developer.hashicorp.com/terraform/tutorials/azure-get-started/infrastructure-as-code

---

# Terraform Planning

During the planning, Terraform tries to assess the current state and find out how to get to the desired state. 

It creates a dependency graph of all resources and the order that they must be created in.

*When creating a virtual machine in Azure what ressources need to be created and in what order?*

<details> 
  <summary>Hint - How many that are needed</summary>
   8 resources have to be created.
</details>


---

# Virtual Machine Resource Creation and Order

1. Resource Group

2. OS Disk

3. Virtual Network

4. Subnet

5. Network Security Group

6. Public IP

7. Network Interface

8. Virtual Machine


---

# Terraform commands - overview

| Command                | Description                                          |
|------------------------|------------------------------------------------------|
| `terraform init`       | Initializes a Terraform configuration directory. Prepares your directory for other commands, installs necessary providers. |
| `terraform plan`       | Shows a preview of the actions Terraform plans to take based on the configuration files. Useful for reviewing changes before applying them. |
| `terraform apply`      | Applies the changes described by `terraform plan`. Provisions or updates infrastructure according to the Terraform configuration. |
| `terraform destroy`    | Removes all resources defined in the Terraform configuration, tearing down the managed infrastructure. |
| `terraform fmt`        | Automatically formats Terraform configuration files to a canonical format and style. |
| `terraform validate`   | Validates the syntax of the Terraform configuration files for correctness. |
| `terraform output`     | Displays the output variables defined in the configuration, useful for extracting important information like IP addresses. |
| `terraform refresh`    | Updates the local state file against real-world resources, realigning the state with the actual state of resources in the cloud. |
| `terraform import`     | Brings real-world infrastructure into Terraform management by adding it to the Terraform state file. |
| `terraform workspace`  | Manages different workspaces, allowing for managing separate states for the same configuration, useful for different environments (e.g., staging, production). |


---


# Terraform workflow - II

Let's look at the previous table again. 

*Can you spot a command and guess which stage they relate to?*

<img src="./assets_infrastructure_as_code/terraform_workflow_2.png" alt="Terraform workflow stages">

Source: https://developer.hashicorp.com/terraform/intro


---

# Let's add the Azure Provider

1. Get the Azure Provider snippet in the [provider docs](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs). 

    <img src="./assets_terraform_get_started/azure_provider.png" style="height: 22vh;" alt="azure provider terraform snippet">

2. Paste it in the `main.tf` file. 

3. Run the following to download initialize which downloads the provider locally:

```bash
$ terraform init
```

*What was created?*

---

# Terraform `.gitignore`

The provider is a large file which will cause problems if pushed to git

Add Terraform templates to your `.gitignore`. Find one by searching for Terraform in [gitignore.io](http://www.gitignore.io):

This will also ensure that no Terraform secrets (like the state file) are pushed to git.

---

# [Optional step] Format

Formatting will make your code look nicer: 

```bash
$ terraform fmt
```

---

# Azure Virtual Machine with hardcoded and visible password

Our end goal is to move away from hardcoded passwords. This is not our final version.

To ensure that we have the latests version, delete the first block below and replace the `required_providers` with the one you got from the provider page.

```hcl
terraform {
  required_providers {
    azurerm = {
      source  = "hashicorp/azurerm"
      version = "4.27.0"
    }
  }
}

provider "azurerm" {
    features {}
    subscription_id = "00000000-0000-0000-0000-000000000000"
}

resource "azurerm_resource_group" "terraform_class" {
  name     = "terraform_class-resources"
  location = "North Europe"
}

resource "azurerm_virtual_network" "terraform_class" {
  name                = "terraform_class-vnet"
  address_space       = ["10.0.0.0/16"]
  location            = azurerm_resource_group.terraform_class.location
  resource_group_name = azurerm_resource_group.terraform_class.name
}

resource "azurerm_subnet" "terraform_class" {
  name                 = "internal"
  resource_group_name  = azurerm_resource_group.terraform_class.name
  virtual_network_name = azurerm_virtual_network.terraform_class.name
  address_prefixes     = ["10.0.2.0/24"]
}

resource "azurerm_public_ip" "terraform_class" {
  name                = "terraform_class-publicip"
  location            = azurerm_resource_group.terraform_class.location
  resource_group_name = azurerm_resource_group.terraform_class.name
  allocation_method   = "Static"
  sku                 = "Standard"
}

resource "azurerm_network_interface" "terraform_class" {
  name                = "terraform_class-nic"
  location            = azurerm_resource_group.terraform_class.location
  resource_group_name = azurerm_resource_group.terraform_class.name

  ip_configuration {
    name                          = "internal"
    subnet_id                     = azurerm_subnet.terraform_class.id
    private_ip_address_allocation = "Dynamic"
    public_ip_address_id          = azurerm_public_ip.terraform_class.id
  }
}

resource "azurerm_linux_virtual_machine" "terraform_class" {
  name                = "main-vm"
  resource_group_name = azurerm_resource_group.terraform_class.name
  location            = azurerm_resource_group.terraform_class.location
  size                = "Standard_B1s"
  admin_username      = "adminuser"
  network_interface_ids = [
    azurerm_network_interface.terraform_class.id,
  ]
  os_disk {
    caching              = "ReadWrite"
    storage_account_type = "Standard_LRS"
  }
  source_image_reference {
    publisher = "Canonical"
    offer     = "0001-com-ubuntu-server-jammy"
    sku       = "22_04-lts-gen2"
    version   = "latest"
  }

  disable_password_authentication = false
  admin_password                  = "badpasword1!"

}

resource "azurerm_network_security_group" "terraform_class_nsg" {
  name                = "terraform_class-nsg"
  location            = azurerm_resource_group.terraform_class.location
  resource_group_name = azurerm_resource_group.terraform_class.name

  security_rule {
    name                       = "allow-8080"
    priority                   = 100
    direction                  = "Inbound"
    access                     = "Allow"
    protocol                   = "Tcp"
    source_port_range          = "*"
    destination_port_range     = "8080"
    source_address_prefix      = "*"
    destination_address_prefix = "*"
  }
}

resource "azurerm_network_security_rule" "terraform_class_ssh_rule" {
  name                        = "SSH"
  priority                    = 1000
  direction                   = "Inbound"
  access                      = "Allow"
  protocol                    = "Tcp"
  source_port_range           = "*"
  destination_port_range      = "22"
  source_address_prefix       = "*"
  destination_address_prefix  = "*"
  network_security_group_name = azurerm_network_security_group.terraform_class_nsg.name
  resource_group_name         = azurerm_resource_group.terraform_class.name
}

resource "azurerm_subnet_network_security_group_association" "terraform_class_assoc" {
    subnet_id                 = azurerm_subnet.terraform_class.id
    network_security_group_id = azurerm_network_security_group.terraform_class_nsg.id
}
```


---

# Terraform Validate + Plan

```bash
$ terraform validate
$ terraform plan
```

*What happens?*

---

# Subscription ID

Seeing how validate succeeds while plan doesn't shows the difference. 

`validate` is to check the syntax and internal consistency. 

`plan` is to check execution logic.

We are missing the subscription ID. Get it by running:

```bash
$ az account show
```

The `id` field is the subscription ID.

In the `main.tf` file, replace the subscription ID to the provider block:

```hcl
provider "azurerm" {
    features {}
    subscription_id = "00000000-0000-0000-0000-000000000000"
}
```

**Note**: This is another thing that we do not wish to hardcode and push.

---

# Terraform Apply

Running apply will give you an overview once again. Type `yes` to enact them:

```bash
$ terraform apply
```

Once finished look for this line and the numbers instead of X, Y, Z:

```
Apply complete! Resources: **X** added, **Y** changed, **Z** destroyed.
```

---

# Can we SSH into it?

Go into the Azure portal and check if the VM is running. Copy the `ip_address` and try to SSH into it:

```bash
$ ssh adminuser@<ip_address>
```

Enter the password as defined in the `main.tf` file.

---

# Create a `outputs.tf` file

Wouldn't be neat if we could get some dynamic information after applying? 

We can define that if we create a file named exactly `outputs.tf` in the same directory as the `main.tf` file.

```hcl
output "public_ip_address" {
  value = azurerm_public_ip.terraform_class.ip_address
}

output "ssh_command" {
  value = "ssh ${azurerm_linux_virtual_machine.terraform_class.admin_username}@${azurerm_public_ip.terraform_class.ip_address}"
}
```

Then run apply again:

```bash
$ terraform apply
```

---

# Visualizing the Dependency Graph

Combining Terraform and GraphViz, you can actually visualize the graph on *nix:

```bash
$ terraform graph | dot -Tpng > graph.png
```

Resulting in a graph like this:

<img src="./assets_terraform_get_started/terraform_dependency_graph.png" alt="terraform dependency graph">


---

# Declare variables

To exemplify using variables for both **secrets** and **dynamic values**, create a `variables.tf` file (named exactly that and in the same directory as the `main.tf` file):

```hcl
variable "subscription_id" {
  description = "The azure subscription ID"
  type        = string
}

variable "vm_name" {
  description = "The name of the virtual machine"
  type        = string
  default     = "main-vm"
}

variable "ssh_password" {
  description = "The password for the SSH user"
  type        = string
  sensitive   = true
}
```

The `sensitive = true` value ensure that the password is never printed in the console.

---

# Define variables

Then define them in a `terraform.tfvars` file (fill out the correct subscription ID):

```hcl
subscription_id = "00000000-0000-0000-0000-000000000000"
vm_name = "main-vm"
ssh_password = "badpassword1!"
```

*What would happen if we don't define `vm_name`?*

---

# Use variables

In `main.tf` replace the hard-coded values with the two variables like this:

```hcl
var.subscription_id
var.vm_name
var.ssh_password
```

*Can you figure out where to replace with variables?*

To summarize, because `*.tfvars` are part of the standard `.gitignore` template for Terraform, defining secrets there ensure that we do not push sensitive data to Terraform while being able to retrieve them in our `.tf` files. It also allows us to define dynamic and reusable values in a single place. We can't use libraries like `.env` since HCL is not an imperative programming language.

---


# Overview: The Files of Terraform

| File Type              | Description                                           |
|------------------------|-------------------------------------------------------|
| `*.tf` / `*.tf.json`   | Infrastructure definitions in HCL or JSON.            |
| `*.tfvars` / `*.tfvars.json` | Variable definitions for configurations.                |
| `.terraform.lock.hcl` | Tracks provider versions and dependencies.            |
| `outputs.tf`           | Defines output values from Terraform.                 |
| State Files (`terraform.tfstate`, `terraform.tfstate.backup`) | Maps configurations to real-world resources.            |



---

# Replace password authentication with SSH key

If you have a RSA SSH key, then replace the password authentication with the public key.

Find this block:

```hcl
  disable_password_authentication = false             # flip this to true     
  admin_password                  = var.ssh_password  # delete this line
```

And replace it with this:

```hcl
  disable_password_authentication = true
  admin_ssh_key {
    username   = "adminuser"
    public_key = file("~/.ssh/id_rsa.pub")
  }
```

Now apply and try to ssh into the VM.

If you suceed at this step, delete the `ssh_password` variable. 

---

# Add a remote provisioner

This is not what you should use Terraform for, but it will be useful for your projects.

Inside of the `azurerm_linux_virtual_machin` block, add the following:

```hcl
  provisioner "remote-exec" {
    inline = split("\n", templatefile("${path.module}/inline_commands.sh", {}))

    connection {
      type        = "ssh"
      user        = "adminuser"
      private_key = file("~/.ssh/id_rsa")
      host        = self.public_ip_address
      timeout     = "2m"
    }
  }
```

---

# Create a `inline_commands.sh` file

Make sure that there are no empty lines as they will not be valid shell commands.

The echo commands are because you cannot pass comments to the shell. 

```bash
echo "============================================================================================"
echo "Update packages"
echo "============================================================================================"
sudo apt-get update && sudo apt-get install -y software-properties-common
echo "============================================================================================"
echo "Install Docker and give user permission"
echo "============================================================================================"
sudo apt install -y docker.io
sudo usermod -aG docker $(whoami)
sudo systemctl restart docker
sudo apt install -y docker-compose
```

---

# Time to destroy

This will tear down your cloud services provisioned by Terraform:

```bash
$ terraform destroy
```

As mentioned earlier, the smart thing about Terraform is that they take care of the dependency graph 
and will shut down services in the necessary order. 

*Verify in Azure Portal that it is gone.*

---

<div class="title-card">
    <h1>Terraform Workspaces</h1>
</div>

---

# Workspaces

Similar to branches. Each workspace is its own context. 

Type the following to see the possible options:

```bash
$ terraform init
$ terraform workspace
```

*Using the help menu, can you solve the assignment?* 

## Assignment:

1. List workspaces.
2. Create a new workspace called `dev` and one named `prod`.
3. Select the `dev` workspace.
4. Show the current workspace.
5. Select the `prod` workspace.

**Bonus Question**: *What keeps track of what the current workspace is?*

---

# Solution: Working with workspaces

```bash
$ terraform workspace list
$ terraform workspace new dev 
$ terraform workspace new prod
$ terraform workspace select dev
$ terraform workspace show
$ terraform workspace select prod
```

---


# Why workspaces in Terraform?

*Consider why...*

---

# Why workspaces in Terraform?

Each workspace maintains its own state, allowing for isolated management of resources.

Besides having different environments like `dev`/ `test` / `prod`, you can also create sandboxes for each developer.

Or you can use it to create a white label solution for each client.

The state is kept in `terraform.tfstate`file inside of the `terraform.tfstate.d` directory.

In a project with provisioned resources, the state file changes with the workspace.






# File: 04._imperative_vs_declarative.md

<div class="title-card">
    <h1>Imperative vs. Declarative</h1>
</div>

---

# Imperative vs. Declarative

## Imperative

Focus on *how* to achieve the desired outcome.

Explicitly defines the steps in a sequence of operations.

State changes are directly managed in the code.


## Declarative

Focus on *what* the desired outcome is.

The tool or system determines the steps to achieve the result.

Defined in configuration, expressions, or rules.

<br>

*Can you think of examples of each?*

---

# Examples of Imperative vs. Declarative

## Imperative

* General-purpose programming languages.

* Scripting languages: Bash etc.

* Most low-level languages (such as Assembly).

## Declarative

* HTML.

* CSS.

* Most Query Langauges. Example: SQL (has some imperative elements, though).

* YAML (Github Action is built on a declarative paradigm).

---

# Imperative IaC example with [Pulumi](https://www.pulumi.com/)

Supports many languages like Python, JavaScript, TypeScript, Go and C#. And YAML.

Simple example in Python:

```python
import pulumi
from pulumi_aws import s3

# Create an AWS S3 bucket
bucket = s3.Bucket('my-bucket')

# Export the bucket name
pulumi.export('bucket_name', bucket.id)
```

---

# Problematic Imperative Example

Bash example:

```bash
#!/bin/bash
mkdir logs
INSTANCE_ID=$(aws ec2 run-instances --image-id ami-0c55b1bfafe1f0c59 --instance-type t2.micro --query 'Instances[0].InstanceId' --output text)
echo "Instance ID: $INSTANCE_ID" >> ./logs/logs.txt
```

*Can you identify the problems above?*

<details> 
  <summary>Hint</summary>
   It will fail at the first script line.
</details>

---

# Problems with the script

If one thing fails then everything fails.

1. We didn't think to check if the folder already exists. . You can't `mkdir` a folder that already exists.

2. No error handling. This includes: 
    * Misconfigured AWS CLI.
    * Failure to create the instance.
    * Insufficient permissions to write to the logs.txt file.

In the imperative approach we have to concern ourselves with all the edge cases that might happen.

---

# It's a symptom of the script being non-idempotent

> "*Idempotence is the property of certain operations […] whereby they can be applied multiple times 
without changing the result beyond the initial application.*"

Source: https://en.wikipedia.org/wiki/Idempotence

Our goal is to achieve idempotency.

---

# Declarative example

We just write what we want. 

Terraform (HCL) example:

```hcl
resource "aws_instance" "example" {
    ami           = "ami-0c55b1bfafe1f0c59"
    instance_type = "t2.micro"
}
```

Continues where it left off even despite potential failures in the middle of the process.

If the block is added on top of already provisioned infrastructure then it will create a new instance.

If the block is removed then it will destroy the instance.

---

# HCL (HashiCorp Configuration Language)

Terraform can be defined as either HCL or JSON. But HCL is commonly used because it is:

* Descriptive: Aims to be a readable JSON-like alternative to JSON

Generally about HCL, it is:

* A **domain-specific langauge** designed for IaC.
* **Declarative**: Focused on the desired end state
* **Non-Imperative**: Specifies *what* is needed, not *how* to accomplish it.
* **Idempotent**: Applying the same configuration multiple times results in the same state, without unintended side effects.

Interestingly enough, Github Actions were originally defined in HCL but uses YAML now.

---

# Declarative vs. Imperative - Pros and cons

| Aspect       | Declarative                                     | Imperative                                     |
|--------------|-------------------------------------------------|------------------------------------------------|
| **Focus**    | What the end state should be.                   | How to achieve the end state.                  |
| **Idempotency** | Naturally idempotent, can be applied multiple times with the same outcome. | Requires careful scripting to achieve idempotency. |
| **Ease of Use** | Higher level of abstraction, easier for defining complex infrastructure. | Requires detailed step-by-step scripting, potentially more complex for large infrastructures. |




# File: 02._why_infrastructure_as_code.md


<div class="title-card">
    <h1>Why Infrastructure as Code (IaC)</h1>
</div>

---

# Ways to work with cloud services

From okay to best:

1. Console UI (ClickOps)

2. CLI / API (Shell, Bash)

3. SDK/CDK (Software/Cloud Development Kit) (Custom code scripts in programming languages)

4. IaC (Framework for provisioning of resources, Declarative, Prescriptive)

*Pros and cons of each?*

---

# Ways to work with cloud services - Pros and cons

| Method    | Cons                                                   | Pros                                                                                             |
|-----------|--------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Console UI| Not suitable for scaling, prone to manual errors       | Quick setup for experiments, easy access to resources for immediate management                   |
| CLI / API | Requires scripting for automation, potential for script-based errors | Flexible for both development and production environments, enables automation and integration    |
| SDK/CDK   | Need for coding skills, potential overhead for setup and maintenance | Facilitates complex deployments, integrates seamlessly with existing development workflows        |
| IaC       | Requires understanding of syntax and structure, overhead in template management | Ensures consistent environments, ideal for both development and production, supports CI/CD processes |

*The table is sorted by the least ideal option first. Why not just always choose IaC then?*

---

# Best method is...?

The further down the list we go:

* the steeper is the learning curve. 

* the time sink to get started grows larger.


---

# Why IaC?

* Version control your infrastructure and add comments to it

* Automation

* Collaboration

* Sandboxing

* Testability

* Reproducibility (the "*works on my machine problem*")

* Recoverability

* Idempotency

---

# The disaster scenario

Imagine that your entire infrastructure is destroyed. 

It could happen because of a disgruntled employee or due to multiple types of accidents. 

As a company you should ask yourself:

- how prepared you are for the disaster scenario. 

- how long will it take you to recover?

Companies have folded because they couldn't recreate years of work in time to gain lost revenue from failing infrastructure.

IaC aims to solve that.  






# File: 03._iac_configuration_management_tools.md

<div class="title-card">
    <h1>IaC tools</h1>
</div>

---

# IaC tools - The definition of IaC

A quick note about the definition of IaC and how we use it in the course:

`1.` [**Broad Definition**] IaC: Any tool that uses code to define anything related to our infrastracture.

Example: Configuration Management Tools are also called IaC even though their focus is on what to do once the resource has been provisioned. 

`2.` [**Narrow Definition**] IaC: A specific type of tool that allows us to provision cloud resources.

Even though `1` is technically correct definition which encompasses `2`, from here on out, I will colloquially use IaC in the narrow sense of definition `2`.

Ansible is the exception, it can do both. 

<span style="font-size: small;">While we are on the topic of definitions: Provisioning translates best to "Oprettelse" or "Udrulning".</span>

---


# Top 5 Configuration Management Tools - I

<table>
  <tr>
    <td><img src="./assets_infrastructure_as_code/logos_configuration_management_tools/ansible_logo.png" alt="ansible logo" style="height:5vh;"><br><a href="https://www.ansible.com/">Ansible</a><br>Automates cloud provisioning, configuration management, and application deployments.</td>
    <td><img src="./assets_infrastructure_as_code/logos_configuration_management_tools/puppet_logo.png" alt="puppet logo" style="height:5vh;"><br><a href="https://www.puppet.com/">Puppet</a><br>Manages infrastructure as code, providing automation and deployment capabilities.</td>
    <td><img src="./assets_infrastructure_as_code/logos_configuration_management_tools/chef_logo.png" alt="chef logo" style="height:5vh;"><br><a href="https://www.chef.io/">Chef</a><br>Turns infrastructure into code to automate server deployment and configuration.</td>
  </tr>
  <tr>
    <td><img src="./assets_infrastructure_as_code/logos_configuration_management_tools/salt_logo.png" alt="salt logo" style="height:5vh;"><br><a href="https://saltproject.io/">Salt</a><br>Offers powerful automation, orchestration, and configuration management in one.</td>
    <td><img src="./assets_infrastructure_as_code/logos_configuration_management_tools/CFEngine_logo.png" alt="CFEngine logo" style="height:5vh;"><br><a href="https://cfengine.com/">CFEngine</a><br>Provides automated configuration and maintenance of large-scale IT systems.</td>
  </tr>
</table>

<span style="font-size: small;">Ordered by most popular first.</span>

*What do you think the benefits for configuration management tools are?*


---

# Benefits: configuration management tools

- **Automation**: Reduces manual effort and errors.

- **Time Saving**: Does not require a person to react to different outcomes.

- **Consistency**: Ensures uniform configurations across environments.

- **Scalability**: Manages large-scale infrastructure efficiently.

- **Version Control**: Track changes via versioning.

- **Security**: Enforces security policies and standards.

- **Recovery**: Aids in quick disaster recovery.

- **Collaboration**: Enhances DevOps collaboration.

---

# IaC tools - Cloud Provider Specific

## Azure

**Bicep**: A domain-specific language for declaratively deploying Azure resources.

**Azure Resource Manager (ARM) Templates**: A service provided by Microsoft Azure to deploy and manage Azure resources in a consistent manner using JSON templates.

## AWS

**AWS CloudFormation**: An AWS service that gives developers and businesses an easy way to create a collection of related AWS and third-party resources, provision and manage them in an orderly and predictable fashion.

## Google Cloud 

**Google Cloud Deployment Manager**: A service provided by Google Cloud that enables the management of cloud resources using declarative templates.


---

# IaC tools - Cloud Provider Agnostic

We are interested in a tool that isn't too proprietary and which doesn't bolt us down to a certain cloud provider. 

Very large companies use several cloud providers and a cloud provider agnostic solution would be optimal for them:

[Pulumi](https://www.pulumi.com/): Infrastructure as code in general-purpose languages like JavaScript, Python, etc.

[Serverless Framework](https://www.serverless.com/): Uses declarative YAML to define services with support for many cloud providers. 

<span style="font-size: small;">Note: Not to be confused with serverless functions or the concept of a serverless cloud service.</span>

[Ansible](https://www.ansible.com/): Automates cloud provisioning and config management with YAML.

[Terraform](https://www.terraform.io/): Define cloud and on-prem resources with versionable files.

<span style="font-size: small;">We will pick Terraform for being the most widely used of all.</span>

---

# Terraform

Maintains a dependency graph which is useful to know what order to create or destroy in. 

Keeps track through a state through the Terraform state file.

Collaborate and keep track of changes to your infrastructure in VCS. 

Declarative: Define the infrastructure you want, it manages how to achieve that.

---

# Terraform alternatives

OpenTofu is an open source fork of Terraform made because of changes in their licensing.

https://opentofu.org/

Though the code for Terraform is also available:

https://github.com/hashicorp/terraform





# File: 06._terraform_limitations_problems.md


<div class="title-card">
    <h1>Terraform - Limitations</h1>
</div>


---


# Limitation for us, students

Azure for Students at KEA doesn't support the creation or management of a **Service Principal**.

[Learn more](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/guides/service_principal_client_secret)

Creating a Service Principal would allow us to programatically authenticate ourselves instead of using `az login` which opens a browser.

If only... Then we would be able to run Terraform in CI. For instance, a GitHub Action that uses Terraform to automatically provision a new test environment for every build on a speocific branch. That would be **close to pro**!

---


# Limitations - What Terraform is not

When you have a fresh VM what is it that you always do? Upgrade, install, setup etc.

Terraform is mainly for provisionining cloud services and not for changing the internal state of VMs for instance.

It can be achieved with Terraform with `remote-exec` or `local-exec` but it is severely limited.

Anisble is much more suited for this task.

*Can you think of use cases where one might prefer to use Configuration Management Tools?*

---

# Limitation: Why is Terraform so slow?

It is true that Terraform can hog your computer's resources.

But know that the heavy lifting happens on the cloud provider's side. 

It might feel sluggish but it is because it takes time for Azure to provision or tear down new resources.

Consider the alternative of having to manually provision services a hundred times! Or how before cloud it took days if not months to get new hardware approved, purchased and then setup.

---

<div class="title-card">
    <h1>Terraform - Problems</h1>
</div>

---

# The state file

A reminder about the Terraform state file:

- Stored locally.

- Always in JSON. 

- Named `terraform.tfstate`

Is used to:

* keep track of references to existing resources

* maintain the dependency graph between services

It is stored locally by default, though everyone in a team should have the latest version.

---

# Why using a VCS for the state is no good

Terraform is excellent for versioning your infrastructure.

But you should not push the state file into git because it risks:

* merging two versions of the file incorrectly, resulting in an invalid file.

* exposing secrets about your system which can compromise security.

---

# State Drift

It can lead to a failure to provision the infrastructure if the state file is not up to date with the infrastructure when running `terraform apply`.

Rarely a state change can be ammened with `terraform refresh`. If it can't then there isn't a fix for it. You have to start completely over.

A **MAJOR** downside with Terraform is how there ufortunately is no standardized way to deal with state file. 

**Note**: This problem can be solved among you with coordination in your groups but let's look at how they deal with them in large companies. 

---

# The State File - Finding a viable solution

A viable place to store the state file must adhere to the following principles:

## Provide a write mechanism

Consider a CI/CD pipeline where runners are destroyed after use. If the pipeline updates the infrastructure then it should be able to save the state changes. The same is true locally. 

## Locking

Ensure single concurrent access. Two developers cannot use the same Terraform setup at the same time.

## Version Consistency

Ensure that users apply changes against the latest state version.



---

# Common Solution - Using cloud storage without lock support - I

Storing it only solves half of the problem. 

Some scripting could ensure that the state file is locked when a developer is working on it.


---

# Common Solution - Using Cloud Storage with Lock Support

- [HashiCorp vault](https://www.hashicorp.com/products/vault)

- [Google Cloud Storage](https://cloud.google.com/docs/terraform/resource-management/store-state)

- [Azure Storage Account](https://learn.microsoft.com/en-us/azure/developer/terraform/store-state-in-azure-storage?tabs=azure-cli#4-understand-state-locking)

- [Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault/)

- AWS S3 combined with DynamoDB (for lock handling)

Remember that the problem is that there is no standardized, agreed-upon way to solve this issue. 

---

# How other IaC tools deal with state

What sets the competing IaC tools apart is how they deal with state. 

One example is Bicep which stores its state files entirely in cloud by default. 

Downside: Then you are locked into using Azure as your cloud provider. 
 

| IaC Tool    | State Management                                  | Default Storage               | Self-manage Options              |
|-------------|---------------------------------------------------|-------------------------------|----------------------------------|
| Terraform   | Causes the problems we have seen                  | Local filesystem              | AWS S3, Azure Blob, GCS, etc.    |
| Pulumi      | Cloud-based with history, auditing, rollbacks     | Pulumi Service (Cloud)        | Local, AWS S3, Azure Blob, GCS   |
| Chef        | Stores state as attributes on Chef server         | Chef Server                   | Local mode, Chef Automate        |
| Puppet      | Compiles catalogs representing desired state      | Puppet Master/Server          | Local filesystem, PuppetDB       |


But Terraform is [still the most used IaC tool](https://survey.stackoverflow.co/2023/#section-most-popular-technologies-other-tools) and an industry standard. 

---

# Problem: How do we ensure that developers do not go crazy with the infrastructure that they provision

There are various ways to enforce policies. In the IaC world, it is called **guard rails**.

Example: Spacelift is a platform for this:

https://spacelift.io/

---

# Repeated warning: Terraform is a time sink

---

# Discussion

*Running Terraform isn't easy so why is it still worth it?*


---

# Project requirements regarding Terraform




# File: 01._introduction.md

<div class="title-card">
    <h1>Infrastructure as Code</h1>
</div>

---

# Mandatory II has dropped!

Check the deadline in Teams.

---

# Don't let your dashboards go unseen

It is not enough to just have setup monitoring. You must gain insights from your gathered data.  

>  "*Without monitoring you are not doing your job.*"

- James Turnbull "The Art of Monitoring"

---

# Weekly DevOps Principle!

Infrastructure as Code:

Repeatable, Reliable, Redeployable




# File: 04._security_in_github.md

 
<div class="title-card">
    <h1>Security in GitHub</h1>
</div>

---

# What is the problem with these Github Action snippets?

I see students come to the exam with this:

```yaml
 steps:
      - name: SSH into the server
        uses: appleboy/ssh-action@v1.2.0
        with:
          host: ${{ secrets.HOST }}
          username: ${{ secrets.USERNAME }}
          key: ${{ secrets.SSH_PRIVATE_KEY }}
          script: |
            whoami
            uname -a
```

```yaml
   steps:
      - name: Upload file to remote server
        uses: appleboy/ssh-action@v1.2.0
        with:
          host: ${{ secrets.HOST }}
          username: ${{ secrets.USERNAME }}
          key: ${{ secrets.SSH_PRIVATE_KEY }}
          port: ${{ secrets.PORT }}
          script: |
            scp /path/to/local/file ${{ secrets.USERNAME }}@${{ secrets.HOST }}:/path/to/remote/destination
```

---

# Don't blindly use third part Github marketplace actions

Especially when it comes to handing over credentials. 

*How would you create a `ssh` and `scp` step without the above?*

---

# It's actually much simpler!

You already learned how to use `ssh` and `scp` from the command line. No need to use a third-party extension:

```yaml
  deploy:
    name: Deploy using SSH and SCP
    runs-on: ubuntu-latest
    steps:
      - name: Copy file to remote server using SCP
        run: |
          scp -i ${{ secrets.SSH_PRIVATE_KEY }} /path/to/local/file ${{ secrets.USERNAME }}@${{ secrets.HOST }}:/path/to/remote/destination

      - name: Execute commands on remote server using SSH
        run: |
          ssh -i ${{ secrets.SSH_PRIVATE_KEY }} ${{ secrets.USERNAME }}@${{ secrets.HOST }} << 'EOF'
            echo "I am on the server now"
          EOF
```

[Example: Whoknows Variations](https://github.com/who-knows-inc/whoknows_variations/blob/continuous_deployment/.github/workflows/continuous_delivery_deployment.yaml#L85)


---

# Hash-pinning

Related to the above. What if you want to use a third-party action? How do you avoid that they don't add malicious code in the future?

https://docs.github.com/en/actions/security-for-github-actions/security-guides/security-hardening-for-github-actions#using-third-party-actions

*Why does the documentation recommend hash-pinning rather than using a specific version?*

---

# SAST and DAST - whoknows_variations example

https://github.com/who-knows-inc/whoknows_variations/tree/security_testing


---

# Dependency scanning - Keep proper update hygiene

The 2020 State of the Octoverse report shows that keeping your software current is the best way to secure your codebase. 

https://octoverse.github.com/2020/#securing-software

---


# Dependabot

https://github.com/who-knows-inc/whoknows_variations/security/dependabot

---

# Enable Dependabot alerts and security updates

1. Navigate to the **Settings** tab.

2. Display the settings for **Code security and analysis**.

3. **Enable** Dependabot alerts. **Enable** Dependabot security updates.

4. **Wait about 60 seconds for Dependabot to check for alerts.**

5. Navigate to the **Security** tab.

6. Under "Vulnerability alerts" in the side bar, select **Dependabot** to view a list of the Dependabot alerts for the default branch.

https://github.com/skills/secure-repository-supply-chain

---

# Enable and trigger Dependabot version updates

1. Navigate to the **Settings** tab and select **Code security**.

2. Locate "Dependabot version updates" and click **Configure** to open a new file editor with pre-poplulated contents. The file is called `dependabot.yml`.

Change `"monthly"` to `"weekly"`. This will run on Mondays by default. 

https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file#scheduleday




# File: 02._devsecops.md


<div class="title-card">
    <h1>DevSecOps</h1>
</div>

---

# How is DevSecOps different from DevOps + Security?

Security is automated and becomes part of every step of CI/CD.

All developers become responsible of security.

The security team becomes advisors rather than police.

---

# The Phoenix Project

According to **The Unicorn Project**: The security team should work to help the DevOps mission of getting value to the customer faster in a secure way rather then strike paranoia.

<img src="./assets_devsecops/the_phoenix_project.png" alt="the phoenix project cover">

---

# Motivation: why automate tests? - Shifting security left

> "[...] This shortage is even worse in Infosec - the ratio of engineers in Development, Operations and Infosec in a typical technology organization is 100:10:1. When Infosec is that outnumbered, without automation and integrating information security into the daily work of Dev and Ops, Infosec can only do compliance checking, which is the opposite of security engineering - and besides, it also makes everyone hate us."

\- James Wicket (Creator of the Gauntlt security tool and organaizer of DevOpsDays Austin and Lonestar Application Security conference)

---

# Shifting left - A DevOps principle

[![How to make a PR](http://img.youtube.com/vi/rKpnEnK0ACg/0.jpg)](https://www.youtube.com/watch?v=rKpnEnK0ACg)



---

# DevSecOps Figure 8

<img src="./assets_devsecops/devsecops_figure8.png" alt="devsecops figure 8 figure8">


---

# DevSecOps Figure 8 - Version 2

<img src="./assets_devsecops/devsecops_figure8_2.png" alt="devsecops figure 8 figure8">

[Source](https://www.mend.io/blog/sast-static-application-security-testing/)

---

# SAST vs. DAST - And tools

## SAST: Static Application Security Testing

Also called white-box testing.

SonarQube, Checkmarx, Fortify, Veracode, etc.

## DAST: Dynamic Application Security Testing

Also called black-box testing.

OWASP ZAP, Burp Suite, etc.

---

# Security Gates in CI/CD

- Pre-commit (static analysis, dependency scanning)

- Pre-merge (code review)

- Pre-deployment (testing)

- Post-deployment (monitoring)

---

# Tool that delivers security in CI/CD: Jfrog Xray

End-to-end security and compliance for your software supply chain.

https://jfrog.com/xray/

---

# Monitor

In a professional setting where security matters, you should monitor the following:

- traffic

- access

- file changes

etc. 

Dashboard tool: Zabbix.

---

# Red-Team vs Blue-Team

Red team:

- Attackers

Blue team:

- Defenders

---

# Be prepared for a breach

Automate back-ups. 

Data is probably your most precious asset; don't lose it.

*What should you do if there a breach has happened and incidence response is over?*

---

# GDPR

Inform the affected parties (users). Inform the authorities.

In the simulation, I do not expect you to adhere to GDPR if there is a data leak. Please don't contact datatilsynet.

<div class="title-card">
    <h1>fail2ban</h1>
</div>

---

# Let's look at the auth logs

On your server, try running this command:

```bash
$ cat /var/log/auth.log
```

*What do you see?*

---

# The solution => Fail2Ban

Since 2004, Fail2Ban has been protecting servers from brute-force attacks.

https://en.wikipedia.org/wiki/Fail2ban

---

<div class="title-card">
    <h1>SSL / TLS</h1>
</div>

---

# SSL / TLS

*What is the difference?*

---

# CA (Certificate Authority)

---

# Certbot

https://certbot.eff.org/





# File: 05_continuous_testing.md


<div class="title-card">
    <h1>Continuous Testing</h1>
</div>

---

# What type of tests fit into CI/CD?

*Can you think of tests to run during*:

- Continuous Integration (CI)

- Continuous Delivery (CD) (During the staging phase)

- Continuous Deployment (CD) (Production)

---

# Test View

**Continuous Integration (CI):**
- Unit-level tests
- Linting

**Continuous Delivery (CD) (Staging phase):**
- System-level tests
- Integration tests
- Smoke tests

**Continuous Deployment (CD):**
- Production tests
- Monitoring
- Smoke tests

Result is: **Continuous Testing**

---

# Let me start with a sincere apology

We should've started with tests in week 2 or 3. 

At that time there were so many topics and tasks and I had to neglect testing. 

This often happens in companies too. 

Today we try remedy this and moving forward we strive for test-driven development (TDD). 

You are not expected to write all the types of tests mentioned in the previous slide because there isn't enough time. This mirrors the real world. 

---

# Shift left vs. Shift right

<img src="./assets_continuous_testing/shift_left_vs._shift_right.png" alt="shift left vs. shift right">

[Source](https://www.dynatrace.com/news/blog/what-is-shift-left-and-what-is-shift-right/)

I **highly** recommend reading the source article.

---

# History - Manual testing

**Developer testing**:

The Developer themselves print out and verify that it works to the best of their ability. 

**UI testing**: 

Sending it to a sales or QA team to click around, type things and verify that everything still works. Sometimes this was done during their 

**Exploratory testing**: 

No predefined test cases. The tester learns about the system as they go along. 

---

# Testing and DevOps

**DevOps goal**: get immediate and reliable feedback. 

Solution: **automated testing**. 

**DevOps goal**: Catch errors early. 

Solution: **run automated tests in parallel**.

> "If all the tests were run sequentially, Sussman states that “the 7,000 trunk tests would take about half an hour to execute. So we split these tests up into subsets, and distribute those onto the 10 machines in our Jenkins [CI] cluster... Spliting up our test suite and running many tests in parallel, gives us the desired 11 minute runtime."

\- Noah Sussman, Test architect at Etsy

---

# Quality gate

It is not enough to test. 

Tests must act like a **quality gate**. If they do not pass, then stop delivery and deployment. 

Worst case scenario (happens too often): 

1. someone checks in code that breaks the test and it isn't rolledback or fixed immediately

2. more people check in code

3. tests are broken, never fixed and then just ignored

---

# Great quote regarding fixing things at Google

> "**We prioritize the team goals over individual goals — whenever we help someone move their work forward, we help the entire team. This applies whether we’re helping someone fix the build or an automated test, or even performing a code review for them**. And of course, we know that they’ll do the same for us, when we need help. This system worked without a lot of formality or policy—everyone knew that **our job was not just “write code,” but it  was to “run a service.”**  This is why we prioritized all quality issues, especially those related to reliability and scaling, at the highest level, treating them as Priority 0 “show-stopper” problems. From a systems perspective, these practices keep us from slipping backwards."

\- Randy Shoup, former engineering director for Google App Engine

---

# Test big and small

> "The simplest test is defined by:

> * A single behavior you are testing, usually a method or API that you are calling

> * A specific input, some value that you pass to the API

> * An observable output or behavior

> * A controlled environment such as a single isolated process"

\- [T. Winters et al. Software Engineering at Google](https://research.google/pubs/software-engineering-at-google/)

---

# How to test

Positive / Negative tests

Boundary tests: Upper bound, lower bound, edge cases

Special characters: especially in Denmark where we have letters like æ, ø, å.

---

# Happy paths vs sad paths

https://en.wikipedia.org/wiki/Happy_path

Remember to test for both.

Security testing, for example, is often about testing the sad paths.

---

<div class="title-card">
    <h1>Types of testing</h1>
</div>

---

# The Test Pyramid

<img src="./assets_continuous_testing/test_pyramid.png" alt="test pyramid" style="height: 50vh;">

[Source: Twillio](https://www.twilio.com/en-us/blog/unit-integration-end-to-end-testing-difference)

---

# Unit testing

*Have you written unit tests for any of your classes?*

*What frameworks have you used?*

---

# Unit testing example: Whoknows Variations

https://github.com/who-knows-inc/whoknows_variations/blob/main/src/backend/app_tests.py

---

# Integration tests

<img src="https://twilio-cms-prod.s3.amazonaws.com/images/MyR86UeunZJcErQJmlEoEwWpAt56uIH2k2mHFqfsA95S2R.width-500_NbXJ1BV.png" style="height: 30vh;">

> "In contrast to unit tests, integration tests:
>
> * Use the actual components that the app uses in production.
> * Require more code and data processing.
> * Takes longer to run."


[Source: Aspnet Core](https://learn.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-6.0)

---

# End-to-end testing

We will do it hands-on with Playwright in a bit. 

For now know that there are multiple tools for end-to-end testing such as: 

* Sellenium

* Cypresss

* Capybara 

* Pupeteer

* Playwright


---

# Test coverage

[Istanbul](https://istanbul.js.org/), Jest, etc.

---

# Performance testing / Load testing

[JMeter](https://jmeter.apache.org/)

[Gatling](https://gatling.io/)

---

# A/B testing

First example of a *shift-right* test so far. 

<img src="./assets_continuous_testing/ab_testing.png" style="height: 42vh;" alt="a/b test">

[Source](https://trymata.com/blog/2021/06/11/moderated-testing-vs-ab-testing-whats-the-difference/)

---

# A/B testing template

How to approach A/B testing (based on a real-life case from to The DevOps Handbook):

* **We believe** increasing the size of hotel images on the booking page

* **Will result** in improved customer engagement and conversion

* **We will have confidence to proceed when** we see a 5% increase in customers who review hotel images who then proceed to book in forty-eight hours.​


---


<div class="title-card">
    <h1>Hands-on with Playwright</h1>
</div>

---

# Hands-on with Playwright

Let's follow the tutorial. 

https://playwright.dev/docs/intro

Install in an existing folder:

```bash
$ npm init playwright@latest
```

Run tests:

```bash
$ npx playwright test
```

---

# Make it work for your project

In `playwright.config.js`:

```javascript
import { defineConfig } from '@playwright/test';

export default defineConfig({
  testDir: './tests',
  use: {
    baseURL: 'http://localhost:8080',
  },
});
```

---

# Recording tests

```bash
$ npx playwright codegen
```

---

# Example of a search test

```javascript
import { defineConfig, devices } from '@playwright/test';

export default defineConfig({
	testDir: './tests',
	use: {
		baseURL: 'http://localhost:8080',
	},
	projects: [
		{ name: 'chromium', use: { ...devices['Desktop Chrome'] } },
		{ name: 'firefox', use: { ...devices['Desktop Firefox'] } },
		{ name: 'webkit', use: { ...devices['Desktop Safari'] } },
	],
});
```

Since you have defined baseURL in the config, `/` will get the base URL appended. You could also write the full URL. 

Try it out:

```bash
$ npx playwright test
```

---

# Headed mode = browser visible

Play the text in headed mode:

```bash
$ npx playwright test --headed
```

Play the test in `inspector` mode:

```bash
$ PWDEBUG=1 npx playwright test --project=chromium
```

---

# Generated report page

Playwright creates an HTML page with the result of the tests. 

It can be found in `playwright-report` in root. 


---

# WhoKnows Variations - E2E testing

https://github.com/who-knows-inc/whoknows_variations/tree/end-to-end_testing

---

<div class="title-card">
    <h1>Continuous Integration for Node.js</h1>
</div>

---

# A simple Node project

Let's create a new repository for creating out first GitHub Action. 

Create a Node.js project. 

```bash 
$ npm init -y
```

Define these scripts in package.json:

```json
"scripts": { 
    "build": "echo Building...", 
    "test": "echo Running tests..." 
}
```

Test it out! 

---

# GitHub Actions for Node.js - Part I

```yaml

This workflow will do a clean installation of node dependencies, cache/restore them, build the source code and run tests across different versions of node

```yaml
name: Node.js CI

on:
  push:
    branches: [ "main" ]
  pull_request:
    branches: [ "main" ]
```

---

# GitHub Actions for Node.js - Part II

```yaml
jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [14.x, 16.x, 18.x]
        # See supported Node.js release schedule at https://nodejs.org/en/about/releases/

    steps:
    - uses: actions/checkout@v3
    - name: Use Node.js ${{ matrix.node-version }}
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}
        cache: 'npm'
    - run: npm ci
    - run: npm run build --if-present
    - run: npm test
```






# File: 03._docker_firewalls.md

<div class="title-card">
    <h1>Docker Security and Firewalls</h1>
</div>

---

# Introduction: Firewalls

A firewall is a network security device that monitors and controls incoming and outgoing network traffic based on predetermined security rules. 

Firewalls can be either on hardware or software level.  

## Types of Firewalls

- Packet-filtering Firewalls

- Stateful Firewalls

- Proxy Firewalls

- Next-generation Firewalls (NGFW)

---

# Firewalls in Linux

*Try to run the two commands on your server*

## iptables

`iptables` is low-level and highly flexible, providing granular control over traffic.

```bash
$ sudo iptables -L
```

## ufw

`ufw` (Uncomplicated Firewall) is a higher-level interface for `iptables`, designed to simplify firewall management.


```bash
$ sudo ufw status
```

---

# iptables examples

*Do not run these commands on your production server unless you intend to do so*

Allow incoming HTTP traffic on port `80`:

```bash
$ sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT
```

Block a specific IP address:

```bash
$ sudo iptables -A INPUT -s 192.168.1.100 -j DROP
```

Allow SSH (port 22) from a specific IP address:

```bash
$ sudo iptables -A INPUT -p tcp -s 192.168.1.101 --dport 22 -j ACCEPT
```

Allowing ssh with `ufw`:

```bash
$ sudo ufw allow ssh
```

---

# Docker and firewalls

Docker circumvents the UFW firewall and alters iptables directly when you instruct it about ports

Mapping the ports with -p 9200:9200 (or in docker-compose) maps the port to the host but also opens it to the world! (bug report from '19)

> "Publishing ports produce a firewall rule that binds a container port to a port on the Docker host, ensuring the ports are accessible to any client that can communicate with the host."

[Issue](https://github.com/docker/for-linux/issues/690)

In general it should not be a problem because there is an additional firewall on the cloud provider level. 

---

# Possible solution - Limiting the IP range the service is accessible from


Define the IP range to control where the service is accessible.

**Internal service** (only accessible from the host):

```yaml
ports:
  - "127.0.0.1:8080:8080"
```

**Public service** (accessible externally):

```yaml
ports:
  - "80:80"
```

Sources: [Documentation](https://docs.docker.com/reference/compose-file/services/#ports) and [Stackoverflow](https://stackoverflow.com/questions/35429837/docker-compose-port-mapping#46220742)


---

# Docker tip: Create a non-root user

Always provided the least privileges possible:

```Dockerfile
# Base image
FROM ubuntu:latest

# Install packages (**as root**)
RUN apt-get update && apt-get install -y curl

# Create a non-root user
RUN useradd -m myuser

# Switch to the non-root user
USER myuser

# Set the working directory
WORKDIR /home/myuser

# ... continue with other instructions ...
```



# File: 01._introduction.md


<div class="title-card">
    <h1>Testing, Security</h1>
</div>

<!-- todo remember to run the security breach script and share on Teams -->

---

# Let's review your projects!

<!-- todo -->

This is what I have found by using the website as a normal user would. I have not reviewed the security feature for old accounts.

**DebuggerDemons**: The website was down when I tried.

**DevOpsDynamite**: No weather information on the weather page. Missing navigation. Consider creating your own 404 page.

**DevOops23b**: The website was down when I tried.

**PipelinePionee.rs**: No weather page. Can't access the login / signup from the frontpage. 

All groups: Why is the footer not at the bottom of the page?

---

# gh pr view example

```bash
$ gh pr view
$ gh pr list --state all
$ gh pr view <number>
```

---

# New Github Copilot feature

Add Copilot as a reviewer to your PRs and it will suggest code changes that can be accepted with a click.

---

# New Copilot feature integrated in Github Actions

Explain Error:

<img src="./assets_introduction/explain_error.png" alt="explain error github copilot feature">

https://github.com/who-knows-inc/whoknows_variations/actions/runs/10325192454/job/28586272559


---

# Weekly DevOps Principle!

**DevSecOps**

Secure by design, not as an afterthought.



# File: 03._openapi.md

<div class="title-card">
    <h1>OpenAPI</h1>
</div>

---

# What is OpenAPI?

- OpenAPI is a specification for APIs.

- Industry standard for describing REST APIs.

- Is a language-agnostic specification.

<img src="./assets_openapi/openapi_logo.png">

---

# History: Swagger

1. Swagger: the company behind OpenAPI. 

2. Swagger: also the previous name of the specification before OpenAPI. 

OpenAPI started at version 3.0. A lot has happened from 3.0 to 3.1.0 (allowing JSON schema): https://www.openapis.org/blog/2021/02/16/migrating-from-openapi-3-0-to-3-1-0

<img src="./assets_openapi/swagger_logo.png" style="height: 30vh;">

---

# APIs <==> OpenAPI

1. **API => OpenAPI spec**: You can generate OpenAPI documentation from your API.

2. **OpenAPI spec => API**: There are also tools to generate API code from OpenAPI documentation.

3. **Hybrid**: Write API code and OpenAPI spec simultaneously to document it. 


---

<div class="title-card">
    <h1>The whoknows spec</h1>
</div>

---

# We have found a spec for the whoknows API

[OpenAPI specification](https://raw.githubusercontent.com/who-knows-inc/KEA_DAT_DevOps_2024_Autumn/main/00._Course_Material/01._Assignments/02._Conventions_OpenAPI_DotEnv/02._After/openapi.json)

---

# Let's paste it into the online Swagger editor

https://editor.swagger.io/

When it prompts you to convert to YAML, do it.

We see errors in the specification. This does not mean that the specification is faulty. 

---

# Use the newest version of the Swagger Editor

https://editor-next.swagger.io/ 


---

# Time to inspect the documentation. 

*What do you find?*

---

<div class="title-card">
    <h1>How to import it into Postman</h1>
</div>

---

# Select import

<img src="./assets_openapi/01._Select_Import.png" alt="postman import openapi select import">

---

# Paste the spec

<img src="./assets_openapi/02._Paste_Spec.png" alt="postman import openapi paste spec">

---

# Select import

<img src="./assets_openapi/03._Select_Import.png" alt="postman import openapi select import ">

---

# Alternative ways to see the Swagger UI

You can also run the editor locally with Docker as described here:

https://swagger.io/docs/open-source-tools/swagger-editor/

```bash 
$ docker pull swaggerapi/swagger-editor
$ docker run -p 80:8080 swaggerapi/swagger-editor
```

You can also show it in plain HTML. Great knowledge for Github Pages:

https://github.com/ITAKEA/swagger-docs-test/blob/master/index.html

And of course, the programming language you are using has a library for it. 



# File: 02._conventions.md


<div class="title-card" style="color: cyan;">
    <h1>Conventions</h1>
</div>

---

# What folders and files should never be pushed?

*And why?*

---

# Folders and files that should never be pushed

IDE preferences that are user specific should not be forced upon others:

  - JetBrains creates the `.idea`. 
  - VSCode creates `.vscode`. 

OS specific files should not be pushed:

  - MacOS creates `.DS_Store` folders that relate to Finder settings. 
  - Windows creates `Thumbs.db` to cache folder thumbnails.

Build artifacts relating to the programming language should not be pushed:

  - Python: `__pycache__`.
  - Node.js: `node_modules`.

---

# .gitignore.io

[gitignore.io](https://www.gitignore.io/) is a website that generates `.gitignore` files for you.

---

# Why you would also want to use a global .gitignore

If it relates to your IDE or OS and not the codebase itself, it should be in a global .gitignore.

---

# Add to the global .gitignore: \*nix

Check if file exists:

```bash
$ git config --global core.excludesfile
```

Modify the file:

```bash
$ nano ~/.gitignore
```

Configure the file (tell Git to use it, remember to point correctly to the file):

```bash
$ git config --global core.excludesfile ~/.gitignore
```

---

# Add to the global .gitignore: Windows

Check if file exists:

```powershell
$ git config --global core.excludesfile
```

Modify the file:

```powershell
$ notepad C:\Users\YourUsername\.gitignore_global
```

Configure the file (tell Git to use it):

```powershell
$ git config --global core.excludesfile C:\Users\YourUsername\.gitignore_global
```

---

# Git advice - write proper commit messages - I

* **Clarity**: Explains changes for team members and future reference.
* **Tracking**: Aids in understanding project evolution and change history.
* **Review Efficiency**: Simplifies code reviews by clearly explaining changes.
* **Debugging Aid**: Helps pinpoint when and why changes were made for troubleshooting.
* **Documentation**: Acts as a record for future reference, helpful for new team members.
* **Professionalism**: Reflects disciplined, best practice approach in software development.

---

# Git advice - write proper commit messages - II

Personal suggestion (this is how I do it, it helps me, you are not required to follow it):

`<past_tense_verb> + <action>`

Examples: 

- Refactored the integration tests

- Created a dark mode feature

- Implemented a POST /users route

- Fixed the bug in the login form

*Can you come up with more commit messages that follow this structure?*

---

## Conventions that we will follow 

<table>
  <thead>
    <tr>
      <th>Concept/Context</th>
      <th>Convention</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Python Variables and Functions</td>
      <td>Snake case</td>
      <td><code>my_variable</code>, <code>my_function</code></td>
    </tr>
    <tr>
      <td>Database Tables/Collections</td>
      <td>Plural</td>
      <td><code>customers</code>, <code>orders</code></td>
    </tr>
    <tr>
      <td>Relational Database Naming</td>
      <td>Snake case</td>
      <td><code>customer_id</code>, <code>order_date</code></td>
    </tr>
    <tr>
      <td>JavaScript Variables and Functions</td>
      <td>Camel case</td>
      <td><code>myVariable</code>, <code>myFunction</code></td>
    </tr>
    <tr>
      <td>JavaScript Classes</td>
      <td>Pascal case</td>
      <td><code>MyClass</code>, <code>UserManager</code></td>
    </tr>
    <tr>
      <td>Web Framework Components</td>
      <td>Pascal case</td>
      <td><code>HeaderComponent</code>, <code>UserList</code></td>
    </tr>
    <tr>
      <td>CSS Classes</td>
      <td>Kebab case</td>
      <td><code>.my-class</code>, <code>.user-profile</code></td>
    </tr>
    <tr>
      <td>Environment Variables</td>
      <td>Upper snake case</td>
      <td><code>DATABASE_URL</code>, <code>API_KEY</code></td>
    </tr>
    <tr>
      <td>Constants in Code</td>
      <td>Upper snake case</td>
      <td><code>MAX_SIZE</code>, <code>DEFAULT_COLOR</code></td>
    </tr>
  </tbody>
</table>

---

# It's time to decide on your own conventions!

Agree with your group either verbally or in writing. 

Example of what a professional style guide looks like:

https://airbnb.io/javascript/react/

You will have to develop a style as you go along but you will soon appreciate naming consistency.



# File: 05._environment_variables.md

<div class="title-card">
    <h1>Environment Variables</h1>
</div>

---

# Environment variables hierarchy

*What are the different levels or scopes of environment variables?*

---

# Environment variables hierarchy answer

1. **OS Level** – System-wide environment variables set at the operating system level.  

2. **User Level** – Environment variables specific to a user session.  

3. **Shell Level** – Variables set within a shell session (e.g., in `.bashrc`, `.zshrc`).  

4. **Process Level** – Variables set for a specific process and its child processes.  

5. **Runtime Level** – Variables managed within a programming language runtime (e.g., `process.env` in Node.js, `os.environ` in Python).

---

# A thorough discussion on the pros and cons of defining secrets in config files vs. environment variables

If you are interested:

https://serverfault.com/questions/892481/what-are-the-advantages-of-putting-secret-values-of-a-website-as-environment-var

We will work with environment variables defined in config files called dotenv. 

Dotenv exists across many languages. The standard is that the files are named `.env`.

---

# Defining it locally 

Let's use dotenv in Python first, then Node.js. 

---

# Python: Virtual environments

Mac users can't run pip globally because of the way Python is installed which restricts `pip` to avoid breaking the system Python or Homebrew setup. 

Mac users try to run `pip install python-dotenv` and see what happens.

While other OS users can run pip globally, it's not recommended. *Can you think of reasons why?*

**Solution**: Virtual environments!

Create a virtual environment and activate it:

```bash
$ python -m venv venv
$ source venv/bin/activate
```

You can always deactivate with:

```bash
$ deactivate
```

---

# Install dotenv for Python

This is the package:

https://pypi.org/project/python-dotenv/

Note that the package to install is called `python-dotenv` but we import the library as `dotenv`. This is because of how modules work in Python. 


Once the virtual environment is activated install the package:

```bash
$ pip install python-dotenv
```

Bonus: You can run Python with Nodemon for hot reload with the following command:

```bash
$ nodemon --exec python your_script.py
```

---

# Python: Two ways to use dotenv

```python
from dotenv import load_dotenv
import os

load_dotenv()
print(os.getenv("API_KEY"))

```

Or:

```python
from dotenv import dotenv_values

config = dotenv_values(".env")
print(config["API_KEY"])
```

---

# Create a template file!

Your `.env` should be added to .gitignore and never pushed. 

Create a copy of your `.env` file and remove the sensitive information but keep the keys and perhaps add example values. 

This file should be pushed. There is no single naming convention but usually they are called something similar to:

- `.env.example`
- `.env.sample`
- `.env.template`

*What is the purpose of doing this?*

---

# In GitHub Action - Manually

```yaml
name: Create .env file

on: [push]


jobs:
    build:
        runs-on: ubuntu-latest
    
        - name: Create .env file
          run: |
            echo "API_KEY=${{ secrets.ENV_API_KEY }}" >> .env
            echo "OTHER_SECRET=${{ secrets.ENV_OTHER_SECRET }}" >> .env
```

You don't *have* to prepend the secrets with `ENV_` but it's a nice way to show that they are different from other secrets and their purpose. 

---

# In GitHub Action - Marketplace extension


Using [SpicyPizza/create-envfile@v2.0](https://github.com/SpicyPizza/create-envfile) is a very popular way of doing it:

```yaml
name: Create .env file

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: Create .env file
        uses: SpicyPizza/create-envfile@v2.0
        with:
          envkey_API_KEY: ${{ secrets.ENV_API_KEY }}
          envkey_OTHER_SECRET: ${{ secrets.ENV_OTHER_SECRET }}
          file_name: .env
```

The manual way is significantly more difficult and preferable for security reasons.

---

# With docker-compose.yaml

**Example 1**: Defining environment variables:

```yaml
services:
  app:
    image: myapp:latest
    environment:
      - PUBLIC_KEY=publickey
      - NOT_SECRET=thisisnotsecret
```

**Example 2**: Defining secrets and reading them from `.env` files into the environment example:

```yaml
services:
  app:
    image: myapp:latest
    env_file:
      - /path/to/your/env/.env
```

Then access them in your programming language how you normally would. 


# File: 01._introduction.md

<div class="title-card" style="color: cyan;">
    <h1>Conventions, OpenAPI, DotEnv</h1>
</div>

---

# How's it going?

* Anyone still not in a group? Remember that it's a requirement to be eligible for the exam.

* Did you manage to create a valid pull request to repositories.py?

---

# How did the refactoring from Python 2 to 3 go?

* What did you have to change?

* Which files did you modify and how?

* Did you create a release with your refactored solution?

---

# How did the dependency graph task go?


There are tools that could help you with this task such as:

- [`debtree`](https://manpages.ubuntu.com/manpages/trusty/man1/debtree.1.html) to create a dependency graph of the Debian packages for the application running on the server.

- [`pipdeptree`](https://pypi.org/project/pipdeptree/) for the pure Python dependencies.

---

# An example of a thorough dependency graph

Assuming Ubuntu Trusty (14.04):

<img src="./assets_introduction/dependencies.png" alt="complete dependencies dependency graph" style="height: 50vh;">


---

# Weekly commit activity

<iframe src="./assets_introduction/commit_activity_weekly.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_weekly.svg" />
</div>

---

# Daily commit activity

<iframe src="./assets_introduction/commit_activity_daily.svg" style="height: 50vh; width: 100%;" frameborder="0"></iframe>

<div class='ignore-presentation'>
    <img src="./assets_introduction/commit_activity_daily.svg" />
</div>

---

# About the exam

[About the exam](https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/blob/main/00._Course_Material/00._Meta_Course_Material/about_the_exam.md)

[Exam project requirements](https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/blob/main/00._Course_Material/00._Meta_Course_Material/exam_project_requirements.md)

[Exam report requirements](https://github.com/who-knows-inc/KEA_DAT_DevOps_2025_Spring/blob/main/00._Course_Material/00._Meta_Course_Material/exam_report_requirements.md)

---

# Brand your projects

You can name your projects and search whatever you like. 

You are not required to go with the WhoKnows branding. 

It doesn't make sense to call it `variations` because the variations repository is named that for containing multiple variations of the same project. 

You can always rename your repositories and make a new PR. 

---

# Weekly DevOps Principle!

**Transparency, visibility, and knowledge sharing!**

Break down information and knowledge silos.

Show your work!

*How?*

---

# Show your work - Examples

* VCS combined with good commit messages

* Releases + release notes

* Kanban

* PRs

* Public Issues

* README.md badges 

* Public dashboards (is it down) https://www.githubstatus.com/

* Documentation

---

# What the code!?

*Is there anything you don't understand about the codebase?*

---

# Jinja2

https://jinja.palletsprojects.com/en/2.10.x/


---

# Why do we do that? Why do I have to understand other peoples' code?

> "**Unfortunately, computer programming education often focuses on how to single-handedly develop programs from scratch in a single language and single execution environment**, a development style prevalent in the 1950s and 60s. **Nowadays, software development is typically a team-based activity and most often involves extending and maintaining existing systems written in a multitude of languages for diverse execution environments**. It’s now even more important to understand code concepts, forms, structures, and idioms to be able to write code that other programmers can read easily."

[Diomidis Spinellis _"Reading, Writing, and Code: The key to writing readable code is developing good coding style."_](https://dl.acm.org/doi/pdf/10.1145/957717.957782)

---

# Work systematically

While working, take notes of what you are doing.

A text file in your workspace might serve you well as a notebook.

Keep a record of when you did what.

Note down what went wrong, where you found a solution, and keep a link for that.

**This is a course requirement that will not be given as a weekly assignment since it should be done from start until the end.**



# File: 04._monolith_monorepo_multirepo.md


<div class="title-card" style="color: cyan;">
    <h1>Monolithic, mono-repo, multi-repo</h1>
</div>

---

# Monorepos

*The new old fad!*

Monorepo: Developers push code changes into a central repository. 

Monolithic vs. monorepo:

> "A related concept is the monolithic application, but whereas a monolith combines its sub-projects into one large project, a monorepo may contain multiple independent projects."

[Source: Wikipedia - Monorepo](https://en.wikipedia.org/wiki/Monorepo)

---

# Advantages and disadvantages of monorepos?

**Hints**: In relation to large-scale applications, team collaboration, developers individually, in the context of version control and CI/CD. 

*Discuss in pairs*

---

# Great overview of advantages and disadvantages

https://en.wikipedia.org/wiki/Monorepo

---

# Monolithic applications vs. Microservices 

**Note**: that is not about monorepos. This relates to architecture. 

It's possible to have microservices in a monorepo. 

|                    | Monolithic          | Microservices               |
|--------------------|---------------------|-----------------------------|
| **Running**        | Single application | Many small, one-responsibility services |
| **Internal Communication** | Within the same program | Inter-service communication over a network |



*Pros and cons?*

---

# Monolithic applications vs. Microservices - Pros and Cons

|            | Monolithic Applications                    | Microservices                           |
|------------|--------------------------------------------|-----------------------------------------|
| **Pros**   | Simplicity in deployment and development.  | Scalability, flexibility, fault isolation.|
| **Cons**   | Scalability challenges, potential coupling.| Increased complexity in deployment, management.|


You will be creating a monolithic application this semester but a lot of companies are currently trying their hands on microservices. 

---

# Google Research paper

Google stores all their code in a single repository. 

That's a billion files and billions lines of code.

They have experienced that this improves the quality of code checked in as wells as the reusability.

https://dl.acm.org/doi/pdf/10.1145/2854146

---

# Stack Overflow

<img src="./assets_monolith_multirepo/stackoverflow_setup.png" alt="stackoverflow setup">

[Post was made to promote this podcast](https://hanselminutes.com/847/engineering-stack-overflow-with-roberta-arcoverde)


# File: 06._reverse_proxies.md

<div class="title-card">
    <h1>Reverse Proxies</h1>
</div>

---

# Reverse proxies

Example: Nginx, Apache, HAProxy, Traefik

<img src="./assets_reverse_proxies/reverse_proxy.png" alt="reverse proxy" style="height: 40vh;">

[Source](https://medium.com/zrp-tech/reverse-proxy-deployment-aws-cloudfront-encryption-caching-performance-5e48f931a4c3)

*Why have a reverse proxy?*

---

# Why have a reverse proxy?

* Load balancing

* HTTP caching

* Security:

    * port protection in a centralized manner

    * TLS encryption deployed only once (between the reverse proxy and the client rather than than the proxy and every single server)

---

# Run Nginx in a Docker container

Run Docker (map port 80 internal to port 8080 external):

```bash
$ docker run --rm -it -p 8080:80 nginx
```

*Try accessing it in your browser.*

Nginx is now serving its default page. We can see that it is served by Nginx by looking at the `Server` response header in the browser's developer tools.

Try stopping the container. 

*What happens when you refresh the page?*

<details> 
  <summary>Answer</summary>
   Depends! Sometimes the browser has a tendency to cache the page. Try a hard refresh if you still see something outdated content or a page even after Nginx was stopped.
</details>

---

# The Nginx configuration file

Nginx defines things in a nginx.conf file. See what it contains here:

```
$ docker run --rm nginx cat /etc/nginx/nginx.conf
```

Alternatively, create a shell for the container and check it out:

```
$ docker run --rm -it nginx sh
```

*Can you figure out where to find the file based on this slide?*

---

# Nginx configuration

Syntax: 

* Directives have keys and values and are separated by semicolons.

* Contexts are blocks of directives.

*Can you point out examples of both in the `nginx.conf` file?*

---

# Example of a default `nginx.conf`

```nginx

#user  nobody;
worker_processes  1;

#error_log  logs/error.log;
#error_log  logs/error.log  notice;
#error_log  logs/error.log  info;

#pid        logs/nginx.pid;


events {
    worker_connections  1024;
}


http {
    include       mime.types;
    default_type  application/octet-stream;

    #log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
    #                  '$status $body_bytes_sent "$http_referer" '
    #                  '"$http_user_agent" "$http_x_forwarded_for"';

    #access_log  logs/access.log  main;

    sendfile        on;
    #tcp_nopush     on;

    #keepalive_timeout  0;
    keepalive_timeout  65;

    #gzip  on;

    server {
        listen       8080;
        server_name  localhost;

        #charset koi8-r;

        #access_log  logs/host.access.log  main;

        location / {
            root   html;
            index  index.html index.htm;
        }

        #error_page  404              /404.html;

        # redirect server error pages to the static page /50x.html
        #
        error_page   500 502 503 504  /50x.html;
        location = /50x.html {
            root   html;
        }

        # proxy the PHP scripts to Apache listening on 127.0.0.1:80
        #
        #location ~ \.php$ {
        #    proxy_pass   http://127.0.0.1;
        #}

        # pass the PHP scripts to FastCGI server listening on 127.0.0.1:9000
        #
        #location ~ \.php$ {
        #    root           html;
        #    fastcgi_pass   127.0.0.1:9000;
        #    fastcgi_index  index.php;
        #    fastcgi_param  SCRIPT_FILENAME  /scripts$fastcgi_script_name;
        #    include        fastcgi_params;
        #}

        # deny access to .htaccess files, if Apache's document root
        # concurs with nginx's one
        #
        #location ~ /\.ht {
        #    deny  all;
        #}
    }


    # another virtual host using mix of IP-, name-, and port-based configuration
    #
    #server {
    #    listen       8000;
    #    listen       somename:8080;
    #    server_name  somename  alias  another.alias;

    #    location / {
    #        root   html;
    #        index  index.html index.htm;
    #    }
    #}


    # HTTPS server
    #
    #server {
    #    listen       443 ssl;
    #    server_name  localhost;

    #    ssl_certificate      cert.pem;
    #    ssl_certificate_key  cert.key;

    #    ssl_session_cache    shared:SSL:1m;
    #    ssl_session_timeout  5m;

    #    ssl_ciphers  HIGH:!aNULL:!MD5;
    #    ssl_prefer_server_ciphers  on;

    #    location / {
    #        root   html;
    #        index  index.html index.htm;
    #    }
    #}
    include servers/*;
}
```

---

# Serving static content - Create `mywebsite`

Create a folder called `mywebsite` somewhere on your computer and put an `index.html` file in it.

In the html file put a greeting message.

---

# Serving static content - Configure Nginx

Create a `nginx.conf` and add the following to it:

```nginx
events {}

http {
    server {
        listen  8080;
        root    /usr/share/nginx/html;
    }
}
```

Nginx will automatically look for an `index.html` file in the root folder.

*Can you fix the above snippet?*

---

# Running the example with mywebsite

Let's run the container with the conf file and the `mywebsite` folder:

```bash
$ docker run --rm -it -p 8080:8080 \
	-v $(pwd)/nginx.conf:/etc/nginx/nginx.conf:ro \
	-v $(pwd)/mywebsite:/usr/share/nginx/html:ro \
	nginx
```
The assumption is that both `nginx.conf` and `mywebsite` are in the same folder as where you are running the command.

The format is `host_path:container_path:mode`. The `ro` mode is read-only.

If it doesn't work with `$(pwd)`, replace it with the absolute path to the folder.

---

# Changing the static content

It should work now after the previous slide!

Now, make a change to the HTML. 

*What will happen if we refresh the browser Nginx?*

While it works with changing the HTML in the host machine, if we make changes to the `nginx.conf` file, we have to restart Nginx.

Since we are working with containers we can do this by simply stopping and starting the container.

---

# Mime types

Let's add a `styles.css` file to the `mywebsite` folder.

```css
body {
    background-color: lightblue;
}
```

Add a link to the `styles.css` file in the `index.html` file.

```html
<link rel="stylesheet" href="styles.css">
```

*Does it work? Why or why not? Where can we check? What is wrong?*

---

# Mime types - Debugging

The Nginx server is correctly serving the CSS file.

We can check in the browser's developer tools in the Network tab.

The response header `Content-Type` is set to `text/plain`.

It should be `text/css`.

---

# Mime types - Fixing it

Add a types context to the http context:

```nginx
events {}

http {
    types {
        text/css            css;
        text/html           html;
        text/javascript     js;
    }

    ...
}

... 
```

What it does is that it maps the `Content-Type` to the file extension.

Refresh in the browser. 

It works! But it's not optimal. *Why not?* 

---

# Mime types

But our solution is not ideal. We would have to manually add every mime type.

Nginx has a built-in list of mime types in the file `mime.types`.

Instead of pasting the types context in the `nginx.conf` file, we can include the `mime.types` file.

```nginx
http {
    include     mime.types;

    ...
}
```

*Rerun Nginx and test it out.*

---

# Defining a location blocks

Create a folder in `mywebsite` called `myfavoritethings` and create an `index.html` in it that displays some of your favorite things.

Add a location block to the server block in the `nginx.conf` file:

```nginx
...
http {
    ...

	server {
		listen 8080;
		root /usr/share/nginx/html;

		location /myfavoritethings {
			root /usr/share/nginx/html;
		}
	}
}
```

Because the location is `/myfavoritethings`, it will find the `index.html` in the `myfavoritethings` folder.

*Rerun Nginx and test it out.*

---

# Location blocks

Reuse the `myfavoritethings` html, but serve it on a different path:

```nginx
http {

    ...

    server {
        ...

        location /generallynicethings {
            alias /usr/share/nginx/html/myfavoritethings;
        }
    }
}
```

So while defining a `root` will append the location to the root, 

`alias` will replace the location with the alias.

---

# Regular expressions in paths

Regular expressions can be defined following the `~*` operator.

```nginx
location ~* /count/[0-9] {
    try_files /count/count.html /index.html =404;
}
```

*What do you think the above location block does?*

We haven't talked about `try_files` but it tries the files in order and `=404` is how we can return an error if everything else fails.


---

# Running Nginx on a server without Docker - I

This slide is might become useful if you ever have to run a bare Nginx server.

## Starting Nginx
 
Right now we are running Nginx automatically as we start the container. But if has been installed on a server, we could do the following to start it:

```bash
$ nginx
```

## Reloading

Every time we make changes to the config we have to reload Nginx:

```bash
$ nginx -s reload
```

---

# Running Nginx on a server without Docker - II

## Stopping Nginx

Graceful stop:

```bash
$ nginx -s quit
```

Force stop:

```bash
$ nginx -s stop
```

---


# Whoknows variations - Continuous Deployment

Let's see on how Nginx has been made to work:

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_deployment

There are two approaches to how to configure Nginx as discussed here:

https://github.com/who-knows-inc/whoknows_variations/blob/continuous_deployment/tutorials/01._Ways_to_Achieve_Continuous_Deployment.md#deploying-nginx

---

# [The `nginx.conf` file](https://github.com/who-knows-inc/whoknows_variations/blob/continuous_deployment/src/network/nginx.conf)

```nginx
events { }

http {
    server {
        listen 80;

        location / {
            proxy_pass http://whoknows_flask:8080;
            proxy_set_header Host $host;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
        }
    }
}
```

**Host**: Keeps the original request’s host header.

**X-Real-IP**: Passes the client’s real IP address.

**X-Forwarded-For**: Tracks the client’s IP across proxies.

**X-Forwarded-Proto**: Keeps the original request’s protocol (http or https).



# File: 03._devops_is_people.md

<div class="title-card">
    <h1>DevOps is People</h1>
</div>

---

# People are not machines

It may sound like DevOps is so focused on value stream and the immediate end-result that it is willing to sacrifice the well-being of the team. That would be a a misuse of the overall philosophy behind DevOps.

DevOps at its core simply tries to identify friction and annoyances in order to alleviate the pain points.

DevOps should not be used as a tool against the workers.

It is unsustainable to constantly push for productivity. 

> "*High productivity is masking an exhausted workforce*"

[Source](https://www.microsoft.com/en-us/worklab/work-trend-index/hybrid-work)


---

# The PTT framework

DevOps literature thoroughly consider the human aspect of the process and it has inspired multiple frameworks.

Example: **PPT framework**

3 keys to an organization's success:

1. People

2. Process

3. Technology

Never sacrifice one for the other.

---

# SPACE

Rather than focusing on shallow metrics such as number of commits (looking at you DevOps course), the SPACE framework is a more holistic approach to measuring productivity: 

* **S**atisfaction and well-being
* **P**erformance
* **A**ctivity
* **C**ommunication and Collaboration
* **E**fficiency and flow.


---

# Example of how to create a positive DevOps culture: Swarming problems together

Andon Cord is a concept from the Toyota Production System. 

https://en.wikipedia.org/wiki/Andon_(manufacturing)

It appears in various DevOps literature. 

https://devops.com/youre-not-devops-cant-pull-cord/

The DevOps Handbook brings a case of how Excella implemented the Andon cord.

---

# Definition: Cycle time

*Does this sound familiar?*

> "Excella noticed during a team retrospective that their cycle times were beginning to rise. They had what Joshua Cohen described as a case of the “almost dones.” He noted, “During standup, our developers would give an update on the feature they were working on the previous day. They would say, ‘Hey, I made a lot of progress. I’m almost done.’ And the next morning they would say, ‘Hey, I ran into some issues but I worked through them. I just have a few more tests to run. I’m almost done.’”"

\- Ayers and Cohen, “Andon Cords in Development Teams.”

> "To measure their Andon cord experiment, the team decided to focus on reduction in cycle time as the key metric for success, as well as increasing the team’s collaboration and getting rid of the “almost dones” by talking about issues when they arose."

---

# Andon cord at Excella

<img src="./assets_devops_is_people/andon_cord_at_excella.png" alt="andon cord at excella" style="height: 60vh;">

---

# Psychological safety

<img src="./assets_devops_is_people/andon_cord_psychological_safety.png" alt="andon cord psychological safety" style="height: 60vh;">

---

# How they implemented it

> "Instead of a literal string or cord to pull, the team created a bot in Slack as a metaphorical Andon cord. When someone typed in andon, the bot would @here the team, notifying everyone in Slack. But they didn’t want to end it there. They also created an “if/this/then/that” integration in Slack that would turn on a rotating red light, string lights, and even a dancing “tube” man in the office."

---

# Free discussion

DevOps shouldn't be a cult. 

First you had to understand it better and now is your chance to think critically about DevOps.

*What do you think?*




# File: 04._postmortem.md

<div class="title-card">
    <h1>Postmortem</h1>
</div>

---

# Postmortem

A postmortem is a document that outlines the steps taken to resolve an incident.

Do you remember from the guest lecture what was important in a postmortem?

**Hint**: *It's an important part of the DevOps culture.*

---

# Blameless Postmortem

[Optional] Assignment: Create a blameless postmortem for a major incident you may run into. 

---

# Github Incident

<img src="./assets_github_incident/Screenshot 2024-08-15 at 01.36.35.png" alt="github incident">

---

# Github Incident

<img src="./assets_github_incident/Screenshot 2024-08-15 at 01.36.42.png" alt="github incident">

---

# Github Incident

<img src="./assets_github_incident/Screenshot 2024-08-15 at 01.36.49.png" alt="github incident">

---

# Github Incident

<img src="./assets_github_incident/Screenshot 2024-08-15 at 11.07.51.png" alt="github incident">

---

# Github Incident

<img src="./assets_github_incident/Screenshot 2024-08-15 at 22.07.02.png" alt="github incident">

---

# Cloudflare Incident

https://blog.cloudflare.com/cloudflare-incident-on-february-6-2025/

> We’re deeply sorry for this incident: this was a failure of a number of controls, and we are prioritizing work to implement additional system-level controls related not only to our abuse processing systems, but so that we continue to reduce the blast radius of any system- or human- action that could result in disabling any production service at Cloudflare.

Humans should be expected to fail. Systems should be designed to handle human errors, otherwise it's a failure of the system.



# File: 02._devops.md

<div class="title-card">
    <h1>DevOps</h1>
</div>

---

# What is DevOps?

*Discuss in pairs.*

---

# [What is DevOps? A Systematic Mapping Study on Definitions and Practices](https://www.researchgate.net/publication/308857081_What_is_DevOps_A_Systematic_Mapping_Study_on_Definitions_and_Practices)

**Problem**: There is no common definition of DevOps.

**Solution**:

A research paper that has compared definitions and practices of DevOps in research literature. 

Identify and classify practices associated with DevOps.

Compare DevOps with other development methods.


---

# Research paper - Central definitions

<img src="./assets_devops/research_paper_what_is_devops_central_definitions.png" alt="what is devops central definitions">

---

# Research paper - DevOps practices

<img src="./assets_devops/research_paper_what_is_devops_devops_practices.png" alt="what is devops practices" style="height: 55vh;">

---

# DevOps Handbook

What are some principles you remember from the `DevOps Handbook`?

---

# DevOps Handbook - The Three Ways

<img src="./assets_devops/devops_handbook_three_ways.png" alt="devops handbook three ways" style="height: 55vh;">

Disclaimer: The Three Ways is one way to think about DevOps. It's rooted in Lean principles. 

---

# The Principles of Flow

* Make Work Visible. 

* Limit Work in Progress

* Reduce Batch Sizes

* Reduce the Number of Handoffs

* Continually Identify and Evaluate Constraints

* Eliminate Hardships and Waste in the Value Stream

*How do you achieve these in your group?*

---

#  The Principles of *Feedback*

* See Problems as They Occur

* Swarm and Solve Problems to Build New Knowledge

* Keep Pushing Quality Closer to the Source

* Enable Optimizing for Downstream Work Centers

*How do you achieve these in your group?*

---

#  The Principles of *Continual Learning and Experimentation*

* Institutionalize the Improvement of Daily Work

* Transform Local Discoveries into Global Improvements

* Inject Resilience Patterns into Our Daily Work

* Leaders Reinforce a Learning Culture

*How do you achieve these in your group?*

---

# Information silos vs. knowledge silos

* **Information silos**: Departments are isolated from each other and do not share data or information. 

* **Knowledge silos**: Expertise is isolated and isn't shared across teams or individuals. 

The number one reflection during the exams is that the group was hindered by not sufficiently sharing knowledge. Tackle this problem now.

*What are ways you could break down knowledge silos in you group?*

---

# Meta-slide: This course actually contains two ongoing tracks at once

1. The Technical track: The things you need to implement and the technical challenges that you face.

2. The DevOps track: Applying DevOps principles 

It's easy to give you assignments for the first track. It's impossible to write assignments for how you should think and behave. But to ace the course, it's insufficient to only excel in the first track. 

Your task is to see the technical challenges as a way to practice the DevOps principles. Even without explicit assignments, you must constantly consider how to apply the theory presented in this course.





# File: 05._continuous_deployment.md


<div class="title-card">
    <h1>Continuous Deployment</h1>
</div>

---

# Motivation: We want to avoid Big Bang Deployment

**Big Bang Deployment**: Deploying the entire application at once.

*Why do you think it's called that?*

*What problems could occur with this approach?*

---

# Quick recap of CI/CD/CD definitions

---

# Quote from the Github Skills course: Deploy To Azure

> "A lot of things go into delivering "continuously". These things can range from culture and behavior to specific automation. In this exercise, we're going to focus on the deployment part of our automation."

[Source after hitting Start The Course](https://github.com/skills/deploy-to-azure?tab=readme-ov-file)

---

# Types of deployment exemplified with the Flask app

#### Code on the server:

1. `git pull` -> `python app.py` / `gunicon app:app` (gunicorn is preferred in production)

2. `git pull` -> `docker compose`

#### Codebase never touches the server:

3. Use the server as a runner agent. 

4. `docker pull <image>` -> `docker run <image>`

5. docker-compose file is on the server -> `docker-compose pull` / `docker-compose up`

---

## Docker-compose build vs. not building

Consider this snippet from `whoknows variations`:

```yaml
  whoknows_flask:
    image: ghcr.io/who-knows-inc/whoknows_variations_server:latest
    build:
      context: ./backend
      dockerfile: Dockerfile.dev
    ports:
      - "8080:8080"
    networks:
      - my_network
```

The following - which requires the codebase to be present - will build the image:

```bash
$ docker-compose build
```

With no building, running this on the docker-compose file:

```bash
$ docker-compose pull
$ docker-compose up
```

It will pull the image hosted on `ghcr.io/who-knows-inc/whoknows_variations_server:latest` and run it with the volumes and network as specified in the docker-compose file.

---

# Full Continuous Deployment

Consider these two options:

4. `docker-compose pull` -> `docker-compose up`

5. `scp` the docker-compose file onto the server -> `docker-compose pull` -> `docker-compose up`

*What are the downsides of the first option?*

---

# The goal is Full CD

1. The first option would not work if there are changes to the docker-compose file. It requires a manual step to place the file on the server.

2. Only the second option would work on a new server (assuming all necessary libraries are installed).

I have coined the term `Full CD`. This should be our end goal.


---

# Using a continuous deployment tool

https://octopus.com/

https://deploybot.com/

---

# Remember to architect your pipeline for reduced runtime

You will be evaluated at the exam for how you construct your pipelines. 

One of the goals is to reduce the runtime of the pipeline.

You should also have quality gates in place.

---


# Quality gates in one job

Since everything runs sequentially in a job, each step will automatically act as a quality gate.

If it fails, it won't proceed.

```yaml
name: CI/CD with a security gate

on: [push, pull_request]

jobs:
  security-tests:
    runs-on: ubuntu-latest

    steps:
    - name: Security Testing
      run: |
        echo "Running security tests..."
      if: success() # default behavior written explicitly

    - name: Deploy to Production
      run: |
        echo "Deploying to production..."
```

---

# Quality gates with multiple jobs

*How would you achieve that a job only runs if job A and job B are successful?*

---

# Multiple jobs acting as quality gates

```yaml
name: CI/CD with a security gate

on: [push, pull_request]

jobs:
  security-tests:
    runs-on: ubuntu-latest
    steps:
    - name: Security Testing
      run: |
        echo "Running security tests..."

  build-tests:
    runs-on: ubuntu-latest
    steps:
    - name: Build and Run Tests
      run: |
        echo "Building and running tests..."

  deploy:
    runs-on: ubuntu-latest
    needs: [security-tests, build-tests]

    steps:
    - name: Deploy to Production
      run: |
        echo "Deploying to production..."
```

---

# Run a workflow after another workflow

```yaml
name: Post-Test Workflow

on:
  workflow_run:
    workflows: ["Test Workflow"]
    types:
      - completed
```

---

# Rollback

When we talk about pipelines we often describe them from left to right. 

But one important aspect is to ensure the quick ability to rollback. 

Now that we've looked at CI/CD in its enterity:

*How can we rollback changes during every step of the process?*

**Steps**: Continuous Integration, Continuous Delivery, Continous Deployment. 

---


<div class="title-card">
    <h1>How big companies build and deploy</h1>
</div>


---

# GitHub

<blockquote style="font-size: medium;">
  We are constantly deploying at GitHub. Dozens of times a day.  
  <br><br>
  Any employee can deploy to production from Campfire with a single message. When someone pushes to master, after watching the tests pass, they're encouraged to immediately deploy to production. This way, everyone is responsible for their own code being production-ready, and people don't have to worry about pushing someone else's code and breaking production.  
  <br><br>
  Recently, this process got even better. Now, after someone pushes to master and the tests pass, master is deployed to production automatically. We have ways of preventing this from happening (an employee can temporarily lock deployment while they're collecting data, for example), but by default, production is always up-to-date with master.  
  <br><br>
  This is a fantastic way of doing things. Deploying constantly means we completely avoid giant scary "deployment days", and our fast and painless deployment process means we can quickly fix problems as they're discovered.
</blockquote>
  
\- [Jake Boxer](https://www.quora.com/How-often-do-major-software-companies-such-as-GitHub-Facebook-Google-Quora-Pinterest-etc-push-code-to-production-Is-there-any-standard-pattern-of-release-cycle-which-any-company-can-follow)

---

# Amazon

<blockquote style="font-size: medium;">
  <strong>Amazon May (2011) Deployment Stats (production hosts & environments only)</strong>
  <br><br>
  <ul>
    <li>Mean time between deployments (weekday): 11.6 seconds</li>
    <li>Max # of deployments in a single hour: 1,079</li>
    <li>Mean # of hosts simultaneously receiving a deployment: 10,000</li>
    <li>Max # of hosts simultaneously receiving a deployment: 30,000</li>
  </ul>
  <br>
  <a href="https://web.archive.org/web/20160305150815/http://assets.en.oreilly.com/1/event/60/Velocity%20Culture%20Presentation.pdf">https://web.archive.org/web/20160305150815/http://assets.en.oreilly.com/1/event/60/Velocity%20Culture%20Presentation.pdf</a>
  <br><br>
  <strong>Results</strong>
  <br><br>
  <ul>
    <li>75% reduction in outages triggered by software deployments since 2006</li>
    <li>90% reduction in outage minutes triggered by software deployments</li>
    <li>~0.001% of software deployments cause an outage</li>
    <li>Instantaneous automated rollback</li>
    <li>Reduction in complexity</li>
  </ul>
  <br>
  <a href="http://www.youtube.com/watch?v=dxk8b9rSKOo">Here is the entire talk with the above numbers mentioned.</a>
</blockquote>

---

# Facebook

Facebook in 2012 deploys:

* One minor update on most business days

* One major update on a weekly basis, usually Tuesdays

https://arstechnica.com/information-technology/2012/04/exclusive-a-behind-the-scenes-look-at-facebook-release-engineering/

Facebook since 2016 deploys:

* quasi-continuous deployment from master

* rolled out to 100 percent of production in a tiered fashion over a few hours

https://engineering.fb.com/2017/08/31/web/rapid-release-at-massive-scale/

---

# Whoknows Variations - Continuous Deployment

https://github.com/who-knows-inc/whoknows_variations/tree/continuous_deployment


# File: 01._introduction.md


<div class="title-card">
    <h1>DevOps, Postmortem, Continuous Deployment, Reverse Proxies</h1>
</div>

---

# Weekly DevOps Principle!

**End-to-End Responsibility**

Break the wall!

Let all the team members have a stake in both Dev and Ops.

Dev and Ops, working as One.

---

# Static-code analysis tools

**Reminder**: Static-code analysis means analyzing the code without executing it.

Remember, remember, remember to be be critical of these tools. Don't use them to make objective conclusions about your project for the exam. 




# File: CHANGELOG.md

# NOTE: CHANGELOG.md is deprecated

After the release of v4.24.0, please see the [GitHub release notes](https://github.com/integrations/terraform-provider-github/releases) for the provider in order to view the most up-to-date changes.

# 4.24.0 (Apr 28, 2022)

ENHANCEMENTS:
* Support for allow_forking on a repository/update to go-github v42 by @diogopms in https://github.com/integrations/terraform-provider-github/pull/1033
* Upgrade go-github to v43.0.0 by @btkostner in https://github.com/integrations/terraform-provider-github/pull/1087

BUG FIXES:

* Fix go module path by @turkenh in https://github.com/integrations/terraform-provider-github/pull/961
* fix: remove incorrect required schema key on ref data source by @youcandanch in https://github.com/integrations/terraform-provider-github/pull/1109
* Bump Go version for Actions release CI to 1.18 by @kfcampbell in https://github.com/integrations/terraform-provider-github/pull/1134
* build(deps): bump actions/setup-go from 2 to 3 by @dependabot in https://github.com/integrations/terraform-provider-github/pull/1110
* Fix linting issues by @kfcampbell in https://github.com/integrations/terraform-provider-github/pull/1107


# 4.23.0 (Mar 25, 2022)

ENHANCEMENTS:

* Add support for disabling the use of the vulnerability management endpoint by @enieuw in https://github.com/integrations/terraform-provider-github/pull/1022
* Added orgname in github_orgranization attributes by @Kavinraja-G in https://github.com/integrations/terraform-provider-github/pull/1052
* Add a data source for refs. by @youcandanch in https://github.com/integrations/terraform-provider-github/pull/1084
* build(deps): bump actions/checkout from 2 to 3 by @dependabot in https://github.com/integrations/terraform-provider-github/pull/1086

BUG FIXES:

* fix: use pagination to fetch all team members by @carocad in https://github.com/integrations/terraform-provider-github/pull/1092
* docs: fix typos in d/users.html.markdown by @pallxk in https://github.com/integrations/terraform-provider-github/pull/1049

# 4.22.0 (Mar 18, 2022)

ENHANCEMENTS:

* feat: add `tree` data source by @jasonwalsh in https://github.com/integrations/terraform-provider-github/pull/1027
* feat: support for issues using github_issue resource by @ewilde in https://github.com/integrations/terraform-provider-github/pull/1047
* feat: add configurable read_delay_ms by @morremeyer in https://github.com/integrations/terraform-provider-github/pull/1054

## 4.21.0 (Mar 11, 2022)

ENHANCEMENTS:

* Adding BypassPullRequestActorIDs to branch protection by @jtyr in https://github.com/integrations/terraform-provider-github/pull/1030
* Adding suspended_at attribute to github_user data source by @mrobinson-anaplan in https://github.com/integrations/terraform-provider-github/pull/1070
* Documentation: Add id to github_user data dource by @kangaechu in https://github.com/integrations/terraform-provider-github/pull/1061

BUG FIXES:

* fix: use the appropriate ID when trying to import `github_team_members` objects by @bison-brandon in https://github.com/integrations/terraform-provider-github/pull/1074
* Environment ID gets set incorrectly on update by @aceresia-bg in https://github.com/integrations/terraform-provider-github/pull/1058
* Fix whitespace in documentation for branch_protection_v3 by @JCradock in https://github.com/integrations/terraform-provider-github/pull/1059

## 4.20.1 (Mar 3, 2022)

BUG FIXES:

* Remove team from state if deletion failed and it does not exist by @cytopia in https://github.com/integrations/terraform-provider-github/pull/1039
    * Note that this is a behavior change from previous GitHub Terraform provider releases: now, if a GitHub team deletion operation fails and the team does not exist, the team will be automatically removed from state.
* Make data_github_repository work with non-existing repositories by @tobiassjosten in https://github.com/integrations/terraform-provider-github/pull/1031
* Standardize logs by @kfcampbell in https://github.com/integrations/terraform-provider-github/pull/1053

## 4.20.0 (Feb 3, 2022)

ENHANCEMENTS:

* Add new resource `github_team_members` to allow authoritative team management by @stawik-mesa in https://github.com/integrations/terraform-provider-github/pull/975

BUG FIXES:

* test: checkout pull request via sha instead of ref by @jcudit in https://github.com/integrations/terraform-provider-github/pull/1043
* Small CI cleanup by @kfcampbell in https://github.com/integrations/terraform-provider-github/pull/1048

**Full Changelog**: https://github.com/integrations/terraform-provider-github/compare/v4.19.2...v4.20.0


## 4.19.2 (Jan 20, 2022)

BUG FIXES:

- Update `go-github` to v42.0.0 ([#1035](https://github.com/integrations/terraform-provider-github/pull/1035))
- Adjust count requirement of `required_approving_review_count` option for `github_branch_protection` ([#971](https://github.com/integrations/terraform-provider-github/pull/971))
- Add `nil` check for `require_conversation_resolution` field of `github_branch_protection` resource ([#1032](https://github.com/integrations/terraform-provider-github/pull/1032))

## 4.19.1 (Jan 5, 2022)

BUG FIXES:

- Update `go-github` to v41.0.0 ([#993](https://github.com/integrations/terraform-provider-github/pull/993))
- Add `nil` check for `plan` field of `github_organization` data source ([#1016](https://github.com/integrations/terraform-provider-github/pull/1016))


## 4.19.0 (Dec 13, 2021)

ENHANCEMENTS:

- Export `branches` attribute of `github_repository` resource ([[#959](https://github.com/integrations/terraform-provider-github/pull/959)])
- Add `require_conversation_resolution` support for `github_branch_protection` resource ([[#904](https://github.com/integrations/terraform-provider-github/pull/904)])

BUG FIXES:

- Adjust length requirement to `topics` option for `github_repository` ([[#996](https://github.com/integrations/terraform-provider-github/pull/996)])
- Add `required_linear_history` support for `github_branch_protection` resource ([[#935](https://github.com/integrations/terraform-provider-github/pull/935)])


## 4.18.2 (Nov 30, 2021)

BUG FIXES:

- Add length requirement to `name` option for `github_repository` ([[#965](https://github.com/integrations/terraform-provider-github/pull/965)])
- Various documentation fixes 🙇

## 4.18.1 (Nov 22, 2021)

BUG FIXES:

- Add length requirement to `topics` option for `github_repository` ([[#951](https://github.com/integrations/terraform-provider-github/pull/951)])
- Add pagination to `selected_repositories` option for `github_actions_runner_group` ([[#970](https://github.com/integrations/terraform-provider-github/pull/970)])
- Add handling for new `node_id` format introduced to the GitHub GraphQL API (`github_repository`) ([[#914](https://github.com/integrations/terraform-provider-github/pull/914)])

## 4.18.0 (Nov 8, 2021)

ENHANCEMENTS:

- **New Resource:** `github_actions_organization_permissions` ([[#920](https://github.com/integrations/terraform-provider-github/pull/920)])

BUG FIXES:

- Add newline compatbility to GitHub App provider authentication ([[#931](https://github.com/integrations/terraform-provider-github/pull/931)])
- Fix `strict` setting of `required_status_checks` for `github_branch_protection` resource ([[#880](https://github.com/integrations/terraform-provider-github/issues/880)])


## 4.17.0 (Oct 17, 2021)

ENHANCEMENTS:

- **New Resource:** `github_repository_autolink_reference` ([[#924](https://github.com/integrations/terraform-provider-github/pull/924)])
- **New Data Sources** `github_users` ([#900](https://github.com/integrations/terraform-provider-github/pull/900))
- Add `allow_auto_merge` option for `github_repository` ([#923](https://github.com/integrations/terraform-provider-github/pull/923))

BUG FIXES:

- Various documentation fixes 🙇

## 4.16.0 (Oct 5, 2021)

ENHANCEMENTS:

* **New Data Source:** `github_repository_file` ([#896](https://github.com/integrations/terraform-provider-github/pull/896))
- Add `write_delay_ms` provider option [#907](https://github.com/integrations/terraform-provider-github/pull/907))

BUG FIXES:

- Update `go-github` to v39.0.0 ([#905](https://github.com/integrations/terraform-provider-github/pull/905))

## 4.15.1 (Sep 23, 2021)

BUG FIXES:

- Revert suppression of  `etag` changes for `github_repository` resources ([[#910](https://github.com/integrations/terraform-provider-github/issues/910)])

## 4.15.0 (Sep 22, 2021)

ENHANCEMENTS:

- **New Resource:** `github_actions_organization_secret_repositories` ([[#882](https://github.com/integrations/terraform-provider-github/issues/882)])
- **New Resource:** `github_actions_runner_group` ([[#821](https://github.com/integrations/terraform-provider-github/issues/821)])
- Add `require_linear_history` to `github_branch_protection` resource ([[#887](https://github.com/integrations/terraform-provider-github/issues/887)])
- Add `branches` attribute to `github_repository` resource ([[#892](https://github.com/integrations/terraform-provider-github/issues/892)])


BUG FIXES:

- Update documentation for `d/github_ip_ranges` ([#895](https://github.com/integrations/terraform-provider-github/issues/895))
- Update `go-github` to v38 ([#901](https://github.com/integrations/terraform-provider-github/issues/901))
- Suppress `etag` changes for `github_repository` resources ([[#909](https://github.com/integrations/terraform-provider-github/issues/909)])


## 4.14.0 (Sep 2, 2021)

BUG FIXES:

- Adds support for recreating a `github_team_repository` when repository is renamed ([#870](https://github.com/integrations/terraform-provider-github/issues/870))
- Adds logging of configured authentication on provider startup ([#867](https://github.com/integrations/terraform-provider-github/issues/867))
- Update documentation for `github_ip_ranges` data source ([#857](https://github.com/integrations/terraform-provider-github/issues/857))
- Add support for IPv6 addresses returned by `github_ip_ranges` data source ([#883](https://github.com/integrations/terraform-provider-github/issues/883))
- Update `go-github` to v37.0.0 ([#893](https://github.com/integrations/terraform-provider-github/issues/893))

## 4.13.0 (Jul 26, 2021)

BUG FIXES:

- Fix setting `vulnerability_alerts` on private `github_repository` creation ([#768](https://github.com/integrations/terraform-provider-github/issues/768))

ENHANCEMENTS:

- Add `restrict_dismissals` option to `github_branch_protection` resource ([#839](https://github.com/integrations/terraform-provider-github/issues/839))

## 4.12.2 (Jul 12, 2021)

BUG FIXES:

- Update `go-github` to v36.0.0 ([#841](https://github.com/integrations/terraform-provider-github/issues/841))

## 4.12.0 (Jun 18, 2021)

ENHANCEMENTS:

* **New Resource:** `github_actions_environment_secret` ([[#805](https://github.com/integrations/terraform-provider-github/issues/805)])
* **New Resource:** `github_repository_environment` ([[#805](https://github.com/integrations/terraform-provider-github/issues/805)])
* Add `members` field to `github_organization` data source ([[#811](https://github.com/integrations/terraform-provider-github/issues/811)])
* Add `repositories` field to `github_team` data source ([[#791](https://github.com/integrations/terraform-provider-github/issues/791)])
* Add `repositories` field to `github_organization_teams` data source ([[#791](https://github.com/integrations/terraform-provider-github/issues/791)])


BUG FIXES:

- Document incompatibility between `github_app_installation_repository` and GitHub App authentication ([#818](https://github.com/integrations/terraform-provider-github/issues/818))
- Document migration from `hashicorp/terraform-provider-github ([#816](https://github.com/integrations/terraform-provider-github/issues/816))
- Allow users and apps to also be applied to push restrictions for `github_branch_protection` ([#824](https://github.com/integrations/terraform-provider-github/issues/824))


## 4.11.0 (Jun 7, 2021)

BREAKING CHANGES:

- Allow PEM data to be passed directly for GitHub App provider authentication ([#803](https://github.com/integrations/terraform-provider-github/issues/803))

ENHANCEMENTS:

- Add `encrypted_value` field to `github_actions_secret` and `github_actions_organization_secret` resources ([#807](https://github.com/integrations/terraform-provider-github/issues/807))

BUG FIXES:

- Fix error handling when branch does not exist for `github_branch` resource ([#806](https://github.com/integrations/terraform-provider-github/issues/806))

## 4.10.1 (May 25, 2021)

BUG FIXES:

* Improve documentation for provider authentication options ([#801](https://github.com/integrations/terraform-provider-github/issues/801))


## 4.10.0 (May 21, 2021)

ENHANCEMENTS:

* Add GitHub App authentication option to provider ([#753](https://github.com/integrations/terraform-provider-github/issues/753))
* Add Actions and Dependabot IP ranges to `github_ip_ranges` data source ([#784](https://github.com/integrations/terraform-provider-github/issues/784))
* Add additional fields to `github_repository` data source ([#778](https://github.com/integrations/terraform-provider-github/issues/778))

## 4.9.4 (May 11, 2021)

BUG FIXES:

- Add EMU support by allowing `internal` visibility to be configured for `github_repository` ([#781](https://github.com/integrations/terraform-provider-github/issues/781))
- Update `go-github` to 35.1.0 ([#772](https://github.com/integrations/terraform-provider-github/issues/772))

## 4.9.3 (May 7, 2021)

BUG FIXES:

- Mark `slug` as `computed` when `name` is changed for `github_team` ([#757](https://github.com/integrations/terraform-provider-github/issues/757))

## 4.9.2 (April 18, 2021)

BUG FIXES:

- correct visibility for repositories created via a template ([#761](https://github.com/integrations/terraform-provider-github/issues/761))


## 4.9.1 (April 17, 2021)

BUG FIXES:

- Bump Go version to 1.16 for acceptance tests and darwin/arm64 releases
- Update acceptance tests to v2.2.0
- Re-instate releases of darwin/arm64

## 4.9.0 (April 17, 2021)

ENHANCEMENTS:

* **New Data Sources** `github_repository_pull_request` / `github_repository_pull_requests` ([#739](https://github.com/integrations/terraform-provider-github/issues/739))
* **New Resource** `github_repository_pull_request` ([#739](https://github.com/integrations/terraform-provider-github/issues/739))
* Add `repositories` attribute for `github_organization` data source ([#750](https://github.com/integrations/terraform-provider-github/issues/750))
* Add import functionality for `github_actions_organization_secret` ([#745](https://github.com/integrations/terraform-provider-github/issues/745))

BUG FIXES:

- Detect and overwrite value drift for `github_actions_secret` and `github_actions_organization_secret` ([#740](https://github.com/integrations/terraform-provider-github/pull/740))
- Do not destroy repositories when `name` attribute changes ([#699](https://github.com/integrations/terraform-provider-github/pull/699))

## 4.8.0 (April 9, 2021)

BUG FIXES:

-  Deprecate `organization` / `GITHUB_ORGANIZATION` provider configuration options ([#735](https://github.com/integrations/terraform-provider-github/pull/735))

## 4.7.0 (April 9, 2021)

REGRESSIONS:

- new repositories created via a template have a public visibility ([#758](https://github.com/integrations/terraform-provider-github/issues/758))
  - workaround: a subsequent plan / apply will set the visibility to what is configured
  - fix: see v4.9.2

ENHANCEMENTS:

* **New Data Source** `github_organization_teams` ([#725](https://github.com/integrations/terraform-provider-github/issues/725))

BUG FIXES:

- Set visibility on create instead of update for `github_repository` ([#746](https://github.com/integrations/terraform-provider-github/pull/746))
- Various documentation updates

## 4.6.0 (March 23, 2021)

ENHANCEMENTS:

* **New Resource** `github_app_installation_repository` ([#690](https://github.com/integrations/terraform-provider-github/issues/690))

BUG FIXES:

- Fix panic for `github_repository_file` ([#732](https://github.com/integrations/terraform-provider-github/pull/732))
- Improve error messaging for `github_branch` ([#734](https://github.com/integrations/terraform-provider-github/pull/734))
- Improve error messaging for `github_branch_protection` ([#721](https://github.com/integrations/terraform-provider-github/pull/721))
- Fix update operation for `github_default_branch` ([#719](https://github.com/integrations/terraform-provider-github/pull/719))
- Add name validation for `github_actions_organization_secret` ([#714](https://github.com/integrations/terraform-provider-github/pull/714))


## 4.5.2 (March 16, 2021)

BUG FIXES:

- Fix updating `default_branch` on `github_repository` ([#719](https://github.com/integrations/terraform-provider-github/pull/719))


## 4.5.1 (March 3, 2021)

BUG FIXES:

- Fix `github_branch_protection` import by repository node ID and pattern ([#713](https://github.com/integrations/terraform-provider-github/pull/713))
- Add pagination when retrieving team members for `data_source_github_team` ([#702](https://github.com/integrations/terraform-provider-github/pull/702))


## 4.5.0 (February 17, 2021)

ENHANCEMENTS:

- Add ability for `github_team_repository` to accept slug as a valid `team_id` ([#693](https://github.com/integrations/terraform-provider-github/pull/693))

BUG FIXES:

- Add more context to error messaging for `github_branch_protection` ([#691](https://github.com/integrations/terraform-provider-github/pull/691))
- Satisfy linter recommendation for `github_branch_protection` ([#694](https://github.com/integrations/terraform-provider-github/pull/694))

## 4.4.0 (February 5, 2021)

BUG FIXES:

- Add `create_default_maintainer` option to `github_team` ([#527](https://github.com/integrations/terraform-provider-github/pull/527)), ([#104](https://github.com/integrations/terraform-provider-github/pull/104)), ([#130](https://github.com/integrations/terraform-provider-github/pull/130))
- Add diff-suppression option to `repository_collaborator` ([#683](https://github.com/integrations/terraform-provider-github/pull/683))


## 4.3.2 (February 2, 2021)

BUG FIXES:

* Improved detection of repository name for `github_branch_protection` ([#684](https://github.com/integrations/terraform-provider-github/issues/684))
* Reverts error handling in provider configuration ([#685](https://github.com/integrations/terraform-provider-github/issues/685))

## 4.3.1 (January 22, 2021)

REGRESSIONS:

- provider configuration breaks for individual accounts ([#678](https://github.com/integrations/terraform-provider-github/issues/678))

BUG FIXES:

* Send valid payload when editing a repository resource with `github_branch_default` ([#666](https://github.com/integrations/terraform-provider-github/issues/666))
* Add handling to surface errors in provider configuration ([#668](https://github.com/integrations/terraform-provider-github/issues/668))

## 4.3.0 (January 14, 2021)

ENHANCEMENTS:

* **New Resource** `github_branch_protection_v3` ([#642](https://github.com/integrations/terraform-provider-github/issues/642))
* Add `pages` feature to `github_repository` ([#490](https://github.com/integrations/terraform-provider-github/issues/490))


## 4.2.0 (January 07, 2021)

BREAKING CHANGES:

- Project transfer from `terraform-providers` organization to `integrations`
    - See [#652](https://github.com/integrations/terraform-provider-github/issues/652) for migration steps and [#656](https://github.com/integrations/terraform-provider-github/issues/656) for discussion

ENHANCEMENTS:

- Add `allowDeletions` and `allowsForcePushes` to `github_branch_protection` ([#623](https://github.com/integrations/terraform-provider-github/pull/623))
- Add GitHub App actor support to `github_branch_protection` ([#615](https://github.com/integrations/terraform-provider-github/pull/615))

BUG FIXES:

- Allow `required_status_checks` `strict` to be `false` for `github_branch_protection` ([#614](https://github.com/integrations/terraform-provider-github/pull/614))
- Remove `ForceNew` on template-related options for `github_repository` ([#609](https://github.com/integrations/terraform-provider-github/pull/609))
- Fix parsing of input during imports of `github_branch_protection` ([#610](https://github.com/integrations/terraform-provider-github/pull/610))
- `github_repository_file` resource no longer iterates through all commits ([#644](https://github.com/integrations/terraform-provider-github/pull/644))

## 4.1.0 (December 01, 2020)

ENHANCEMENTS:

- Add `github_actions_organization_secret` resource ([#261](https://github.com/integrations/terraform-provider-github/pull/261))
- Add `github_repository_milestone` resource ([#470](https://github.com/integrations/terraform-provider-github/pull/470))
- Add `github_repository_milestone` data source ([#470](https://github.com/integrations/terraform-provider-github/pull/470))
- Add `github_project_card` resource ([#460](https://github.com/integrations/terraform-provider-github/pull/460))
- Add `github_branch_default` resource ([#194](https://github.com/integrations/terraform-provider-github/pull/194))


## 4.0.1 (November 18, 2020)

BUG FIXES:

- `github_team` data source query no longer iterates through a list of teams ([#579](https://github.com/integrations/terraform-provider-github/pull/579))
- `github_repository_file` resource no longer iterates through all commits ([#589](https://github.com/integrations/terraform-provider-github/pull/589))
- fix parsing of `repo:pattern` format during `github_branch_protection` import ([#599](https://github.com/integrations/terraform-provider-github/pull/599))


## 4.0.0 (November 10, 2020)

REGRESSIONS:

- fails parsing of `repo:pattern` format during `github_branch_protection` import ([#597](https://github.com/integrations/terraform-provider-github/issues/597))

BREAKING CHANGES:

- `pattern` replaces `branch` in changes to `github_branch_protection` introduced in `v3.1.0` ([#566](https://github.com/integrations/terraform-provider-github/issues/566))
- `dismissal_restrictions` documented for `github_branch_protection` ([#569](https://github.com/integrations/terraform-provider-github/pull/569))
- project license changes from MPL2 to MIT ([#591](https://github.com/integrations/terraform-provider-github/pull/591))

BUG FIXES:

- `repository_id` for `github_branch_protection` accepts repository name as well as node ID ([#593](https://github.com/integrations/terraform-provider-github/issues/593))

ENHANCEMENTS:

- Add support to get currently authenticated user to `data_source_github_user` ([#261](https://github.com/integrations/terraform-provider-github/pull/261))
- Add importing to `github_organization_webhook` ([#487](https://github.com/integrations/terraform-provider-github/pull/487))


## 3.1.0 (October 12, 2020)

REGRESSIONS:

- undocumented, breaking configuration changes to `github_branch_protection` ([#566](https://github.com/integrations/terraform-provider-github/issues/566))
- slowed performance of `github_branch_protection` ([#567](https://github.com/integrations/terraform-provider-github/issues/567))
- change to default branch breaks refresh of existing `github_repository_file` resources ([#564](https://github.com/integrations/terraform-provider-github/issues/564))

BREAKING CHANGES:

- Deprecate `anonymous` Flag For Provider Configuration ([#506](https://github.com/integrations/terraform-provider-github/issues/506))

BUG FIXES:

- re-instante resources unavailable in the context of an organization ([#501](https://github.com/integrations/terraform-provider-github/issues/501))
- allow overwrite-on-create behaviour for `github_repository_file` resource ([#459](https://github.com/integrations/terraform-provider-github/issues/459))


ENHANCEMENTS:

- update `go-github` to `v32.1.0` ([#475](https://github.com/integrations/terraform-provider-github/issues/475))
- add `vulnerability_alerts` to `github_repository` ([#444](https://github.com/integrations/terraform-provider-github/issues/444))
- add `archive_on_destroy` to `github_repository` ([#432](https://github.com/integrations/terraform-provider-github/issues/432))
- uplift `branch_protection` to GraphQL ([#337](https://github.com/integrations/terraform-provider-github/issues/337))


## 3.0.0 (September 08, 2020)

BREAKING CHANGES:

- `token` becomes optional
- `organization` no longer deprecated
- `individual` and `anonymous` removed
- `owner` inferred from `organization`
- `base_url` provider parameter no longer requires `/api/v3` suffix

BUG FIXES:

- `terraform validate` fails because of missing token ([#503](https://github.com/integrations/terraform-provider-github/issues/503))
- organization support for various resources ([#501](https://github.com/integrations/terraform-provider-github/issues/501))

ENHANCEMENTS:

* **New Data Source** `github_organization` ([#521](https://github.com/integrations/terraform-provider-github/issues/521))


## 2.9.2 (July 14, 2020)

- Adds deprecation of `anonymous` flag for provider configuration ahead of next major release ([#506](https://github.com/integrations/terraform-provider-github/issues/506))
- Adds deprecation of `individual` flag for provider configuration ahead of next major release ([#512](https://github.com/integrations/terraform-provider-github/issues/512))

## 2.9.1 (July 01, 2020)

BUG FIXES:

- Reverts changes introduced in v2.9.0, deferring to the next major release

## 2.9.0 (June 29, 2020)

**NOTE**: This release introduced a provider-level breaking change around `anonymous` use.
See [here](https://github.com/integrations/terraform-provider-github/pull/464#discussion_r427961161) for details and [here](https://github.com/integrations/terraform-provider-github/issues/502#issuecomment-652379322) to discuss a fix.

ENHANCEMENTS:
* Add Ability To Manage Resources For Non-Organization Accounts ([#464](https://github.com/integrations/terraform-provider-github/issues/464))
* resource/github_repository: Add "internal" Visibility Option ([#454](https://github.com/integrations/terraform-provider-github/issues/454))

## 2.8.1 (June 09, 2020)

BUG FIXES:

* resource/github_repository_file: Reduce API requests when looping through commits ([[#466](https://github.com/integrations/terraform-provider-github/issues/466)])
* resource/github_repository: Fix `auto_init` Destroying Repositories ([[#317](https://github.com/integrations/terraform-provider-github/issues/317)])
* resource/github_repository_deploy_key: Fix acceptance test approach ([[#471](https://github.com/integrations/terraform-provider-github/issues/471)])
* resource/github_actions_secret: Fix Case Where Secret Removed Outside Of Terraform ([[#482](https://github.com/integrations/terraform-provider-github/issues/482)])
* Documentation Addition Of `examples/` Directory

## 2.8.0 (May 15, 2020)

BUG FIXES:

* resource/github_branch_protection: Prevent enabling `dismissal_restrictions` in GitHub console if `dismissal_users` and `dismissal_teams` are not set ([#453](https://github.com/integrations/terraform-provider-github/issues/453))
* resource/github_repository_collaborator: Allow modifying permissions from `maintain` and `triage`  ([#457](https://github.com/integrations/terraform-provider-github/issues/457))
* Documentation Fix for `github_actions_public_key` data-source ([#458](https://github.com/integrations/terraform-provider-github/issues/458))
* Documentation Fix for `github_branch_protection` resource ([#410](https://github.com/integrations/terraform-provider-github/issues/410))
* Documentation Layout Fix for `github_ip_ranges` and `github_membership` data sources ([#423](https://github.com/integrations/terraform-provider-github/issues/423))
* Documentation Fix for `github_repository_file` import ([#443](https://github.com/integrations/terraform-provider-github/issues/443))
* Update `go-github` to `v31.0.0` ([#424](https://github.com/integrations/terraform-provider-github/issues/424))

ENHANCEMENTS:
* **New Data Source** `github_organization_team_sync_groups` ([#400](https://github.com/integrations/terraform-provider-github/issues/400))
* **New Resource** `github_team_sync_group_mapping` ([#400](https://github.com/integrations/terraform-provider-github/issues/400))

## 2.7.0 (May 01, 2020)

BUG FIXES:

* Add Missing Acceptance Test ([#427](https://github.com/integrations/terraform-provider-github/issues/427))

ENHANCEMENTS:

* Add GraphQL Client ([#331](https://github.com/integrations/terraform-provider-github/issues/331))
* **New Data Source** `github_branch` ([#364](https://github.com/integrations/terraform-provider-github/issues/364))
* **New Resource** `github_branch` ([#364](https://github.com/integrations/terraform-provider-github/issues/364))


## 2.6.1 (April 07, 2020)

BUG FIXES:

* Documentation Fix For Option To Manage `Delete Branch on Merge` ([#408](https://github.com/integrations/terraform-provider-github/issues/408))
* Documentation Fix For `github_actions_secret` / `github_actions_public_key` ([#413](https://github.com/integrations/terraform-provider-github/issues/413))

## 2.6.0 (April 03, 2020)

ENHANCEMENTS:

* resource/github_repository: Introduce Option To Manage `Delete Branch on Merge` ([#399](https://github.com/integrations/terraform-provider-github/issues/399))
* resource/github_repository: Configure Repository As Template ([#357](https://github.com/integrations/terraform-provider-github/issues/357))
* **New Data Source** `github_membership` ([#396](https://github.com/integrations/terraform-provider-github/issues/396))

## 2.5.1 (April 02, 2020)

BUG FIXES:

* Fix Broken Link For `github_actions_secret` Documentation ([#405](https://github.com/integrations/terraform-provider-github/issues/405))

## 2.5.0 (March 30, 2020)

REGRESSION:

* `go-github` `v29.03` is incompatible with versions of GitHub Enterprise Server prior to `v2.21.5`. ([[#404](https://github.com/integrations/terraform-provider-github/issues/404)])

ENHANCEMENTS:

* Add `apps` To `github_branch_protection` Restrictions
* **New Data Source** `github_actions_public_key` ([[#362](https://github.com/integrations/terraform-provider-github/issues/362)])
* **New Data Source** `github_actions_secrets` ([[#362](https://github.com/integrations/terraform-provider-github/issues/362)])
* **New Resource:** `github_actions_secret` ([[#362](https://github.com/integrations/terraform-provider-github/issues/362)])

BUG FIXES:

* Prevent Panic From DismissalRestrictions ([[#385](https://github.com/integrations/terraform-provider-github/issues/385)])
* Update `go-github` to `v29.0.3` ([[#369](https://github.com/integrations/terraform-provider-github/issues/369)])
* Update `go` to `1.13` ([[#372](https://github.com/integrations/terraform-provider-github/issues/372)])
* Documentation Fixes For Consistency And Typography


## 2.4.1 (March 05, 2020)

BUG FIXES:

* Updates `go-github` to `v29` to unblock planned feature development ([#342](https://github.com/integrations/terraform-provider-github/issues/342))
* Fixes `insecure_ssl` parameter behaviour for `github_organization_webhook` and  `github_repository_webhook` ([#365](https://github.com/integrations/terraform-provider-github/issues/365))
* Fixes label behaviour to not create new labels when renaming a `github_issue_label` ([#288](https://github.com/integrations/terraform-provider-github/issues/288))

## 2.4.0 (February 26, 2020)

ENHANCEMENTS:

* **New Data Source** `github_release` ([#356](https://github.com/integrations/terraform-provider-github/pull/356))

* **New Resource:** `github_repository_file` ([#318](https://github.com/integrations/terraform-provider-github/pull/318))

## 2.3.2 (February 05, 2020)

BUG FIXES:

* Handle repository 404 for `github_repository_collaborator` resource ([#348](https://github.com/integrations/terraform-provider-github/issues/348))

## 2.3.1 (January 27, 2020)

BUG FIXES:

* Add support for `triage` and `maintain` permissions in some resources ([#303](https://github.com/integrations/terraform-provider-github/issues/303))

## 2.3.0 (January 22, 2020)

BUG FIXES:

* `resource/resource_github_team_membership`: Prevent spurious diffs caused by upstream API change made on 17th January ([#325](https://github.com/integrations/terraform-provider-github/issues/325))

ENHANCEMENTS:

* `resource/repository`: Added functionality to generate a new repository from a Template Repository ([#309](https://github.com/integrations/terraform-provider-github/issues/309))

## 2.2.1 (September 04, 2019)

ENHANCEMENTS:

* dependencies: Updated module `hashicorp/terraform` to `v0.12.7` ([#273](https://github.com/integrations/terraform-provider-github/issues/273))
* `resource/github_branch_protection`: Will now return an error when users are not correctly added ([#158](https://github.com/integrations/terraform-provider-github/issues/158))
* `provider`: Added optional `anonymous` attribute, and made `token` optional ([#255](https://github.com/integrations/terraform-provider-github/issues/255))

BUG FIXES:
* `resource/github_repository`: Allow setting `default_branch` to `master` on creation ([#150](https://github.com/integrations/terraform-provider-github/issues/150))
* `resource/github_team_repository`: Validation of `team_id` ([#253](https://github.com/integrations/terraform-provider-github/issues/253))
* `resource/github_team_membership`: Validation of `team_id` ([#253](https://github.com/integrations/terraform-provider-github/issues/253))
* `resource/github_organization_webhook`: Properly set webhook secret in state ([#251](https://github.com/integrations/terraform-provider-github/issues/251))
* `resource/github_repository_webhook`: Properly set webhook secret in state ([#251](https://github.com/integrations/terraform-provider-github/issues/251))

## 2.2.0 (June 28, 2019)

FEATURES:

* **New Data Source** `github_collaborators` ([#239](https://github.com/integrations/terraform-provider-github/issues/239))

ENHANCEMENTS:

* `provider`: Added optional `individual` attribute, and made `organization` optional ([#242](https://github.com/integrations/terraform-provider-github/issues/242))
* `resource/github_branch_protection`: Added `require_signed_commits` property ([#214](https://github.com/integrations/terraform-provider-github/issues/214))

BUG FIXES:

* `resource/github_membership`: `username` property is now case insensitive ([#241](https://github.com/integrations/terraform-provider-github/issues/241))
* `resource/github_repository`: `has_projects` can now be imported ([#237](https://github.com/integrations/terraform-provider-github/issues/237))
* `resource/github_repository_collaborator`: `username` property is now case insensitive [[#241](https://github.com/integrations/terraform-provider-github/issues/241))
* `resource/github_team_membership`: `username` property is now case insensitive ([#241](https://github.com/integrations/terraform-provider-github/issues/241))


## 2.1.0 (May 15, 2019)

ENHANCEMENTS:

* `resource/github_repository`: Added validation for lowercase topics ([#223](https://github.com/integrations/terraform-provider-github/issues/223))
* `resource/github_organization_webhook`: Added back removed `name` attribute, `name` is now flagged as `Removed` ([#226](https://github.com/integrations/terraform-provider-github/issues/226))
* `resource/github_repository_webhook`: Added back removed `name` attribute, `name` is now flagged as `Removed` ([#226](https://github.com/integrations/terraform-provider-github/issues/226))

## 2.0.0 (May 02, 2019)

* This release adds support for Terraform 0.12 ([#181](https://github.com/integrations/terraform-provider-github/issues/181))

BREAKING CHANGES:

* `resource/github_repository_webhook`: Removed `name` attribute ([#181](https://github.com/integrations/terraform-provider-github/issues/181))
* `resource/github_organization_webhook`: Removed `name` attribute ([#181](https://github.com/integrations/terraform-provider-github/issues/181))

FEATURES:

* **New Resource:** `github_organization_block` ([#181](https://github.com/integrations/terraform-provider-github/issues/181))
* **New Resource:** `github_user_invitation_accepter` ([#161](https://github.com/integrations/terraform-provider-github/issues/161))
* `resource/github_branch_protection`: Added `required_approving_review_count` property ([#181](https://github.com/integrations/terraform-provider-github/issues/181))

BUG FIXES:

* `resource/github_repository`: Prefill `auto_init` during import ([#154](https://github.com/integrations/terraform-provider-github/issues/154))

## 1.3.0 (September 07, 2018)

FEATURES:

* **New Resource:** `github_project_column` ([#139](https://github.com/integrations/terraform-provider-github/issues/139))

ENHANCEMENTS:

* _all resources_: Use `Etag` to save API quota (~ 33%) ([#143](https://github.com/integrations/terraform-provider-github/issues/143))
* _all resources_: Implement & use RateLimitTransport to avoid hitting API rate limits ([#145](https://github.com/integrations/terraform-provider-github/issues/145))

BUG FIXES:

* `resource/github_issue_label`: Return genuine errors instead of ignoring them when reading existing resource ([#142](https://github.com/integrations/terraform-provider-github/issues/142))
* `resource/github_membership`: Return genuine errors instead of ignoring them when reading existing resource ([#142](https://github.com/integrations/terraform-provider-github/issues/142))
* `resource/github_repository_deploy_key`: Return genuine errors instead of ignoring them when reading existing resource ([#142](https://github.com/integrations/terraform-provider-github/issues/142))
* `resource/github_team`: Return genuine errors instead of ignoring them when reading existing resource ([#142](https://github.com/integrations/terraform-provider-github/issues/142))
* `resource/github_team_membership`: Return genuine errors instead of ignoring them when reading existing resource ([#142](https://github.com/integrations/terraform-provider-github/issues/142))
* `resource/github_team_repository`: Return genuine errors instead of ignoring them when reading existing resource ([#142](https://github.com/integrations/terraform-provider-github/issues/142))
* `resource/github_user_gpg_key`: Return genuine errors instead of ignoring them when reading existing resource ([#142](https://github.com/integrations/terraform-provider-github/issues/142))

## 1.2.1 (August 17, 2018)

BUG FIXES:

* `resource/github_repository`: Avoid spurious diff for `topics` ([#138](https://github.com/integrations/terraform-provider-github/issues/138))

## 1.2.0 (August 17, 2018)

FEATURES:

* **New Data Source:** `github_repository` ([#109](https://github.com/integrations/terraform-provider-github/issues/109))
* **New Data Source:** `github_repositories` ([#129](https://github.com/integrations/terraform-provider-github/issues/129))
* **New Resource:** `github_organization_project` ([#111](https://github.com/integrations/terraform-provider-github/issues/111))
* **New Resource:** `github_repository_project` ([#115](https://github.com/integrations/terraform-provider-github/issues/115))
* **New Resource:** `github_user_gpg_key` ([#120](https://github.com/integrations/terraform-provider-github/issues/120))
* **New Resource:** `github_user_ssh_key` ([#119](https://github.com/integrations/terraform-provider-github/issues/119))

ENHANCEMENTS:

* `provider`: Add `insecure` mode ([#48](https://github.com/integrations/terraform-provider-github/issues/48))
* `data-source/github_ip_ranges`: Add importer IPs ([#100](https://github.com/integrations/terraform-provider-github/issues/100))
* `resource/github_issue_label`: Add support for `description` ([#118](https://github.com/integrations/terraform-provider-github/issues/118))
* `resource/github_repository`: Add support for `topics` ([#97](https://github.com/integrations/terraform-provider-github/issues/97))
* `resource/github_team`: Expose `slug` ([#136](https://github.com/integrations/terraform-provider-github/issues/136))
* `resource/github_team_membership`: Make role updatable ([#137](https://github.com/integrations/terraform-provider-github/issues/137))

BUG FIXES:

* `resource/github_*`: Prevent crashing on invalid ID format ([#108](https://github.com/integrations/terraform-provider-github/issues/108))
* `resource/github_organization_webhook`: Avoid spurious diff of `secret` ([#134](https://github.com/integrations/terraform-provider-github/issues/134))
* `resource/github_repository`: Make non-updatable fields `ForceNew` ([#135](https://github.com/integrations/terraform-provider-github/issues/135))
* `resource/github_repository_deploy_key`: Avoid spurious diff of `key` ([#132](https://github.com/integrations/terraform-provider-github/issues/132))
* `resource/github_repository_webhook`: Avoid spurious diff of `secret` ([#133](https://github.com/integrations/terraform-provider-github/issues/133))


## 1.1.0 (May 11, 2018)

FEATURES:

* **New Data Source:** `github_ip_ranges` ([#82](https://github.com/integrations/terraform-provider-github/issues/82))

ENHANCEMENTS:

* `resource/github_repository`: Add support for archiving ([#64](https://github.com/integrations/terraform-provider-github/issues/64))
* `resource/github_repository`: Add `html_url` ([#93](https://github.com/integrations/terraform-provider-github/issues/93))
* `resource/github_repository`: Add `has_projects` ([#92](https://github.com/integrations/terraform-provider-github/issues/92))
* `resource/github_team`: Add `parent_team_id` ([#54](https://github.com/integrations/terraform-provider-github/issues/54))

## 1.0.0 (February 20, 2018)

ENHANCEMENTS:

* `resource/github_branch_protection`: Add support for `require_code_owners_review` ([#51](https://github.com/integrations/terraform-provider-github/issues/51))

## 0.1.2 (February 12, 2018)

BUG FIXES:

* `resource/github_membership`: Fix a crash when bad import input is given ([#72](https://github.com/integrations/terraform-provider-github/issues/72))

## 0.1.1 (July 18, 2017)

BACKWARDS INCOMPATIBILITIES / NOTES:

* `resource/github_branch_protection`: The `include_admin` attributes haven't been working for quite some time due to upstream API changes. These attributes are now deprecated in favor of the new top-level `enforce_admins` attribute. The `include_admin` attributes currently have no affect on the resource, and will yield a `DEPRECATED` notice to the user.

IMPROVEMENTS:

* `resource/github_repository`: Allow updating default_branch ([#23](https://github.com/integrations/terraform-provider-github/issues/23))
* `resource/github_repository`: Add license_template and gitignore_template ([#24](https://github.com/integrations/terraform-provider-github/issues/24))
* `resource/github_repository_webhook`: Add import ([#29](https://github.com/integrations/terraform-provider-github/issues/29))
* `resource/github_branch_protection`: Support enforce_admins ([#26](https://github.com/integrations/terraform-provider-github/issues/26))
* `resource/github_team`: Supports managing a team's LDAP DN in GitHub Enterprise ([#39](https://github.com/integrations/terraform-provider-github/issues/39))

BUG FIXES:

* `resource/github_branch_protection`: Fix crash on nil values ([#26](https://github.com/integrations/terraform-provider-github/issues/26))

## 0.1.0 (June 20, 2017)

FEATURES:

* **New Resource:** `github_repository_deploy_key` [[#15215](https://github.com/integrations/terraform-provider-github/issues/15215)](https://github.com/hashicorp/terraform/pull/15215)

IMPROVEMENTS:

* `resource/github_repository`: Adding merge types ([#1](https://github.com/integrations/terraform-provider-github/issues/1))
* `data-source/github_user` and `data-source/github_team`: Added attributes ([#2](https://github.com/integrations/terraform-provider-github/issues/2))


# Overview

## The Docker setup

Since this branch (`continuous_delivery`) is focused on delivering the application to a container registry, only the prod versions of the Dockerfiles and Docker Compose files are important. But the both sets of files are included in the repository to show how you can specifiy the file when building the image and pushing it to the container registry.


The `src/backend/Dockerfile.prod` file installs the dependencies and runs the Flask server with Gunicorn which is recommended for production. 

The `src/docker-compose.prod.yml` file specifies the image to use and the port to expose.

## The Docker Compose setup

The `docker-compose.prod.yml` serves the Flask app. It differs from the dev version by: 

1. Not enabling hot reload

2. Creating an Nginx proxy server on port 80. 


## Running it locally

To run the application locally, cd to `src` where the `docker-compose.prod.yml` file is and run the following command:

```bash
$ docker-compose -f docker-compose.prod.yml up --build
```

You can now access it at `http://localhost:8080` or since there is also an Nginx server running, you can access it at `http://localhost:80`.

## The workflow file

There is a workflow file in `.github/workflows/continuous_delivery.yml` which builds the image and pushes it to the Github container registry. It will be explained later. 

# The workflow file

## Overview

In [.github/workflows/continous_delivery.yml](../.github/workflows/continuous_delivery.yml) you will find the workflow that builds and pushes the images to the Github Container Registry.

The workflow file uses `buildx`. Buildx is a very powerful toolkit in testing and generating images for multiples architectures.

The smart thing is that you don't have to define the image names in the workflow file since it gets them from the `docker-compose.prod.yml` file.

## The workflow file

The workflow file does the following:

1. Checks out the repository. This way it has access to the files in the repository, including the `docker-compose.prod.yml` file.

2. Sets up `buildx` which, amongst many things, sets up the Docker daemon on the runner. 

3. Logs in to the Github Container Registry.

4. Builds and pushes the images. The crucial part is that the working directory and the file it uses should be correct.

This is correct for this repository but might not be the structure that you have:

```yaml
    - name: Build and Push Docker Images
      working-directory: ./src
      run: |
        docker buildx bake -f docker-compose.prod.yml --push
```

## Get started

1. Remember to set the secrets in the repository settings (assuming [Github CLI](https://cli.github.com/) is installed):

```bash
$ gh secret set CR_PAT
$ gh secret set DOCKER_GITHUB_USERNAME
```

Or run the setup script (in the root of this repository):

```bash
$ ./setup.sh
```

2. Change the two image names in `docker-compose.prod.yml` to your own.

For the first one, where it says:

```yaml
    image: ghcr.io/who-knows-inc/whoknows_variations_server:latest
```

Change this: `ghcr.io/<your_username_or_organisation>/<your_own_image_name>:latest` to your own.

3. **Note**, you might have to change the trigger. 

If you are using a different branch, perhaps in your own repository, then remember to change the trigger in the workflow file:

```yaml
on:
  push:
    branches: [ continuous_delivery ] # change me
  pull_request:
    branches: [ continuous_delivery ] # change me
```# Environment variables

As you were instructed to in the README.md, you should have created a `env` file for the dev setup. 

However, if you look in `src/backend/.dockerignore`, you will see that it contains `.env`. This means that when when an image is build, the `.env` file will not be included.

This is a good practice and allows us to make the image public without worrying about leaking sensitive information.

## Accessing the value on the server

One the server the following section has been added:

```python
################################################################################ 
# Environment Variables
################################################################################

from dotenv import load_dotenv

load_dotenv()

@app.route('/greeting')
def home():
    return os.getenv('GREETING')
```

The dotenv package has been added to requirements.txt and it loads the values from the `.env` file. The greeting defined in the `.env` file will be returned when the `/greeting` endpoint is hit.

## Production 

This is a setup to show one possible way to handle environment variables production. 

In the continuous deployment branch the workflow file will contain the following:

```yaml
      - name: Create .env file
        run: |
          echo "GREETING=${{ secrets.ENV_GREETING }}" >> .env

      - name: Transfer .env file to server
        run: |
          scp -i ~/.ssh/ssh_key -o StrictHostKeyChecking=no .env $SSH_USER@$SSH_HOST:.env
        env:
          SSH_USER: ${{ secrets.SSH_USER }}
          SSH_HOST: ${{ secrets.SSH_HOST }}
```

It creates the `.env` file with the environment variable `GREETING` on the runner and then transfers the file to the server.

By adding echo statements you can add more environment variables to the `.env` file.

Once you have the `.env` file on the server, you use the `--env-file` flag when running the container to load the environment variables:

```bash
$ docker run -d --env-file .env --network my_network -p 8080:8080 --name whoknows_variations_server ghcr.io/who-knows-inc/whoknows_variations_server
```# CLI Example

This step is not necessary and you can just set it up in a workflow. 

But it might give a better understanding of what the workflow does and it's great knowledge for debugging.

Please read it through before proceeding, because there some general information at the bottom. 

## Publish the packages through your terminal.

1. Create environment variables. 

Here is how to do it for *nix (replace with your own values):

```bash
$ export CR_PAT=<your_fine_grained_token>
$ export DOCKER_GITHUB_USERNAME=<your_github_username>
```

2. Login to Github Container Registry:

```bash
$ echo $CR_PAT | docker login ghcr.io -u $DOCKER_GITHUB_USERNAME --password-stdin
```
It should return `Login Succeeded`.

3. Build and push docker images. 

This example uses my own values. Replace with your own. 

Assuming that you are in `src`, this will build and push the server image:

```bash
$ docker-compose -f docker-compose.prod.yml build whoknows_flask
$ docker push ghcr.io/who-knows-inc/whoknows_variations_server:latest
```

And this will build and push our custom nginx image that has our [configuration](../src//network/nginx.conf) which points to whoknows_flask on port `8080`:

```bash
$ docker-compose -f docker-compose.prod.yml build whoknows_nginx
$ docker push ghcr.io/who-knows-inc/whoknows_variations_nginx:latest
```

## Check the images

This section relates to pushing images via a Github Action workflow. 

You will be able to find the packages in:

https://github.com/orgs/who-knows-inc/packages

If you have pushed your own images, then replace `who-knows-inc` with your own user / organisation name you published to.

### Publishing the images

The images are private by default. 

If you would like to publish the images first go to the organization page and click on the `Packages`: 

`https://github.com/organizations/<your_organisation_here>/settings/packages`

Under **Package creation** check the **Public** box.

Then go to the package under `https://github.com/orgs/who-knows-inc/packages`. Replace `who-knows-inc` with your own user / organisation name you published to.

On the right side, click `⚙️ Package settings`. Scroll down and in the Danger Zone there is a an option called: `Change package visibility`.# Generating a CR_PAT (Container Registry Personal Access Token)

You can read more about personal access tokens on Github here:

https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens

To deploy to Github Packages (Github's own container registry) via. Github Actions, you need a personal access token.

It is a convention to call the token for accessing Github Packages CR_PAT (Container Registry Personal Access Token). I will do that from now on in this tutorial.

Github has a new default type of token:

1. Fine-grained personal access tokens

It is usually preferred to use Fine-grained tokens. These offer better security and control. In the past, Fine-grained tokens did not allow read and write permissions to "Packages", but that has changed.

Now it is possible to grant read and write access to Packages when creating a Fine-grained token. This makes it suitable for publishing packages to Github Packages.

---

# How to generate a CR_PAT (Container Registry Personal Access Token)

We are going to create a **Fine-grained personal access token**: https://github.com/settings/personal-access-tokens

This access token will be created on your personal account. It is used to authenticate (logging in) to the container registry. For organisations you must allow the organisation to accept personal access tokens (PATs).

## Step 1: Create a policy for your organisation to accept PATs

https://docs.github.com/en/organizations/managing-programmatic-access-to-your-organization/setting-a-personal-access-token-policy-for-your-organization

https://www.youtube.com/watch?v=T-eqWEUdjeM

## Step 2: Generate a PAT

As the name implies (Personal Access) this should be done on your personal account.

https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

Before clicking **Generate token** choose the **Resource owner** as the organisation you want to give access to.

For better security, you can also choose specific repositories that it has access to. 

Set Repository Permissions  
You will need to set the following Repository and Organization permissions:
	•	Contents: Read and Write  
	•	Metadata: Read-only  
	•	Actions: Read and Write  
	•	Deployments: Read and Write (necessary for some deployment actions)  
	•	Environments: Read and Write (necessary for managing environments and secrets)  
	•	Packages: Read and Write (required for publishing to Github Packages)  

Copy the token. 

(The user must have write access to the repository. This is not automatic even if the user has created the organisation. It can be setup in the repository settings -> Collaborators and teams -> Manage access and click **Add people**.)

## Step 3 (Optional): Verify that the token is on the repository. 

1. Go to the repository settings page.

2. On the left choose **Personal access tokens** and **Active tokens** under it. The token should now appear in the list. 

Under **Organization permissions** it should have green check marks for the following:

✅ Read and Write access to organization administration  

And under **Repository permissions** it should have green check marks for the following:

✅ Read access to metadata  
✅ Read and Write access to actions and code  
✅ Read and Write access to packages  

---

# Validating the CR_PAT

In the root of this branch there is a script named [is_valid_crpat.sh](../is_valid_crpat.sh). It can be used to validate the CR_PAT.

The script will take your CR_PAT and test whether it has permission to push packages to a given repository.

Make sure not to choose `Y` when asked to use this repository unless this is the actual target. Either:

1. Paste the URL of the repository you want to deploy to when prompted.

2. Move the script to the target repository and let it automatically extract the URL from there.

# Continuous Delivery

As mentioned in the `README.md`, this tutorial builds on the [Continuous Delivery](https://github.com/who-knows-inc/whoknows_variations/tree/continuous_delivery) branch.

---

## Where to find the images

The images have been made available so that anyone can pull them and try out the tutorial on their own servers. They can be found here:

https://github.com/orgs/who-knows-inc/packages/container/package/whoknows_variations_server

https://github.com/orgs/who-knows-inc/packages/container/package/whoknows_variations_nginx

The names are defined in the [docker-compose.prod.yml](../src/docker-compose.prod.yml) file as the value of the image keys:

```yaml
    image: ghcr.io/who-knows-inc/whoknows_variations_server:latest
    image: ghcr.io/who-knows-inc/whoknows_variations_nginx:latest
```

---

## Public vs. private images

The images have been made public.

If you want to deploy your own images then you must change the visibility manually in the Github UI once. This cannot be configured in the workflow file.

It's possible to make the example work with private images by adding a login step on the server.

Since the repositories are public, there should be no problem in making the images public too.

Even with private images, should we absolutely avoid building in secrets in the images.

Instead, this example shows how to add `.env` files at runtime. See [Environment Variables](./04._Environment_Variables.md) for more.

# Environment Variables

This shows how we can transfer environment variables to the server without compromising with security. 

The goal is to have one local `.env` file and one for the server. They should contain a greeting message that will be displayed on the newly created route `/envgreeting`.

Our goal is to observe how we see different greetings locally compared to the server.

---

## Prerequisites to run it locally

You are not required to run it locally to use this example or deploy successfully. After all, the goal is that the deployed version will use a different environment file.

But if you want to run it locally, you must copy [.env.sample](../src/backend/.env.sample) to `.env`. 

The `GREETING` variable has already been set in the example as it isn't a secret but environment specific.

In [app.py](../src/backend/app.py) you can find this new section:

```python
################################################################################
# Environment Variables
################################################################################

from dotenv import load_dotenv
load_dotenv()

@app.route('/envgreeting')
def home():
    return os.getenv('GREETING')
```

**Note** that the dependency `python-dotenv` has been added to `requirements.txt`. Docker will make sure to read install it, but if you want to replicate this example then remember to add the dependency to your project.

---

## Running it locally

After having created the `.env` file, you can run the server in the `src` folder with:

```bash
$ docker-compose -f docker-compose.dev.yml up --build
```

You should see the greeting on: `http://localhost:8080/envgreeting`.

---

## The difference between local and deployed

The [.dockerignore](../src/backend/.dockerignore) file has been updated to ignore the `.env` file. This is to prevent it from being added to the images put on Github Container Registry.

The `.docker-compose.dev.yml` file then explicitly adds the `.env` file to the development container with the following addition:

```yaml
    env_file:
      - backend/.env
```

This evades the `.dockerignore` file.

Another approach would be to have two sets of `.dockerignore` files. Then add a line like this for `docker-compse.dev.yml` for example:

```yaml
    args:
      - dockerignore_file=.dockerignore.dev
```

And in the `Dockerfile.dev` add the corresponding `.dockerignore.dev` file as defined in the `ARG`:

```dockerfile
COPY $dockerignore_file .dockerignore
```

---

## The deployed setup

In the `continuous_deployment` workflow file the `GREETING` has been hardcoded to better illustrate the example:

```yaml
      - name: Create .env file
        run: |
          echo "GREETING=Hello from Github Action" >> .env
```

It should've been set as a Github Secret (preferably prefixed with `ENV_` or similiar) and could've been part of the `setup.sh` script, but by doing it this way, the setup process isn't hidden.

---

## Transfering the .env file to the server

After the `.env` file has been created, it is transferred to the server with secure copy (scp):

```yaml
      - name: Transfer .env file to server
        run: |
          scp -i ~/.ssh/ssh_key -o StrictHostKeyChecking=no .env $SSH_USER@$SSH_HOST:.env
        env:
          SSH_USER: ${{ secrets.SSH_USER }}
          SSH_HOST: ${{ secrets.SSH_HOST }}
```

---

## Starting the container with the environment variable

In the last step of the workflow file we see:

```yaml
        docker run -d --env-file .env --network my_network -p 8080:8080 --name whoknows_flask who-knows-inc/whoknows_variations_server:latest
```

By defining the `--env-file` flag we can point to a file on the server and it will load the environment variables from there.

---

## Success criteria

After a successful deployment you should be able to see the greeting message `Hello from Github Action` when accessing the `/envgreeting` route in your browser.# The Continuous Deployment Workflow

This will walk you through the workflow file [continuous_delivery_deployment.yaml](../.github/workflows/continuous_delivery_deployment.yaml) in the `.github/workflows` directory.

---

## The default branch problem

The problem is that Github requires you to let something trigger from the default branch in order to be able to trigger other workflows. This will not work in this case where the workflows have been defined in this branch: `continuous_deployment`.

One solution would be to make it trigger the workflow file over the Github API. 

The solution this repository has gone with is combining the two workflow files as two jobs: `build` and `deploy`. The deploy job then has the following to key defined to keep it from running in parallel with the build job:

```yaml
  deploy:
    needs: build
```

In your case making it trigger from the main branch would be the obvious choice and the following section will help you set that up.

---

## Triggering the Deployment Workflow

The deployment workflow should most likely not run on push but instead be dependent on other workflows. This can be achieved like this:

```yaml
on:
  workflow_run:
    workflows: ["<name_of_workflow>"]
    types:
      - completed
```

---

## Adding the SSH key to the runner to allow access to the server

The private SSH key is pasted from Github Secrets into a file on the runner and given appropriate permissions:

```yaml
    steps:
      - name: Add SSH key to runner
        run: |
          mkdir -p ~/.ssh/
          echo "$SSH_PRIVATE_KEY" > ~/.ssh/ssh_key
          chmod 600 ~/.ssh/ssh_key
        env:
          SSH_PRIVATE_KEY: ${{ secrets.SSH_PRIVATE_KEY }}
```

---

## Network

While the network has been defined correctly in the `docker-compose.prod.yml` file, this information does not carry over when building the individual images. 

To create the network on the server this is done:

```yaml
    docker network create my_network || true
```

The `|| true` is there to prevent the workflow from failing if the network already exists.

The network is then passed via the `--network` flag when running the containers:

```yaml
    docker run -d --env-file .env --network my_network -p 8080:8080 --name who-knows-inc/whoknows_variations_server:latest

    docker run -d --network my_network -p 80:80 --name whoknows_nginx who-knows-inc/whoknows_variations_nginx:latest
```

Since they have both been given `my_network` as the network, they will be able to communicate with each other.

---

## Image name vs. `--name`

The `--name` flag is used to give the container a name. This is not the same as the image name. The image name is used when pulling the image from the registry.

In this case:

```yaml
  docker pull ghcr.io/who-knows-inc/whoknows_variations_server:latest
  docker run -d --env-file .env --network my_network -p 8080:8080 --name whoknows_flask ghcr.io/who-knows-inc/whoknows_variations_server:latest
```

The image name is `ghcr.io/who-knows-inc/whoknows_variations_server:latest` and the container name is `whoknows_flask`.

---

## Refactored workflow file

For readability, the workflow in the `.github/workflows` folder has hardcoded all the names.

A refactored example can be found in this folder and is named [refactored_workflow.yml](./refactored_workflow.yml).

It might offer some insight into the different parts. To ensure that `./run.sh` always runs on startup, you can create a systemd service. Here are the steps to create and enable a systemd service for your GitHub Actions runner:

1. Create a systemd service file:

```bash
$ sudo nano /etc/systemd/system/github-actions-runner.service
```

2. Add the following content to the file (ensure that the paths and user are correct):

```ini
[Unit]
Description=GitHub Actions Runner
After=network.target

[Service]
ExecStart=/home/adminuser/actions-runner/run.sh
WorkingDirectory=/home/adminuser/actions-runner
User=adminuser
Restart=always
RestartSec=10

[Install]
WantedBy=multi-user.target
```

3. Reload systemd:

```bash
$ sudo systemctl daemon-reload
```

4. Enable the service on boot:

```bash
$ sudo systemctl enable github-actions-runner
```

5. Start the service:

```bash
$ sudo systemctl start github-actions-runner
```

6. [Optional] Check the service status:

```bash
$ sudo systemctl status github-actions-runner
```
# Self-hosted runner

Rather than using Github's servers you can also define your own runner. You can read more about the concept [here](https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/about-self-hosted-runners).

## How to setup a self-hosted runner

1. Go to your repository on Github.

2. Click on the `Settings` tab.

3. Click on the `Actions` tab in the left side and choose `Runners` under it. 

4. Click on the `New self-hosted runner` button.

5. Choose the correct OS and architecture. Follow the instructions to download and configure the runner.

Once you are done, `run.sh` should be running and you are ready to try it out. 

## Create a basic workflow for your self-hosted runner

You can find it under [basic_self-hosted.yml](../.github/workflows/basic_self-hosted.yml).

```yaml
name: Test self-hosted runner

on:
  workflow_dispatch:
  push:
    branches:
        - main

jobs:
  echo_hello_world:
    runs-on: self-hosted

    steps:
    - name: "Echo Hello World"
      run: echo "Hello World"

  create_file:
    runs-on: self-hosted

    steps:
    - name: "Create a file"
      run: |
        touch test.txt
        echo "Hello World" > test.txt
```

The workflow:

1. Outputs `Hello world` on your own server. 
2. Creates a `test.txt` file with the content `Hello World`.



## Avoid having to `run.sh` script constantly

The way Github instructs you, you must run the `run.sh` script constantly. 

Even if you run it in the background so that you can log out of the server, it is still not ideal because it won't be started when the server restarts.

Solution: [Create a systemd service for it](./always_run_run.sh.md). 
# Ways to achieve Continuous Deployment

---

## Pull vs. push deployment

Earlier in the course we have looked at various ways to achieve pull deployments. From now on we will focus solely on push deployments.

---

## Building Docker images on the server

One option is to pull the Github repository on the server, build the Docker images there and run them.

But as a continuation from the `continuous_delivery` path, we assume that the Docker images have already been built and are available to us.

---

## Push deployments with Github Actions and pre-built Docker images

Excluding CI/CD systems, there are two ways to solve this with Github Actions:

1. SSH from the runner into your server and execute commands remotely.

2. Treat your server as a Github Actions runner which allows you execute commands on it. 

This example does it with the first approach.

---

## Your deployment server as a Github Actions runner

For the second approach there are some incomplete tutorial for inspiration but feel free to skip this part:

[Deploying with a self-hosted runner.](./tutorials/self_hosted_runner.md)

---

## Deploying with Github Actions over SSH

We will focus specifically on how to achieve Continuous Deployment for Docker images.

1. Use Github Action to create a script that pulls the latest Docker images and reruns them. Let the runner transfer the script to the server. Then execute the script remotely.

2. Use Github Action to run commands on the server. It would contain the same commands as in the script from above.

This example does it with the second approach.

---

## Deploying nginx

The thing is that we have a config file [nginx.conf](../src/network/nginx.conf) that specifies which port the application runs on and later on we want to specify SSL.

There are two approaches for how to run nginx with Docker. 

1. Create a custom nginx image with the config file baked in. Then we only have to run the image.

2. Get the nginx image from DockerHub and mount the config file as a volume when running the container.

This example does it with the first approach. The second approach is just as valid. 

For the second approach it can be done like this (after transfering the `nginx.conf` file to the server):

```bash
$ docker run -d -p 80:80 -v /path/to/nginx.conf:/etc/nginx/nginx.conf nginx
```

---

## Summary

This branch builds docker images based on the setup in the [docker-compose.prod.yml](../src/docker-compose.prod.yml) file.

Once the `continuous_delivery` workflow has finished building the images, the `continuous_deployment` workflow commences.

It logs on to the server over SSH. On the server it pulls the latest images and reruns them.```yaml
name: Continuous Delivery Deployment

on:
  push:
    branches: [ continuous_deployment ]
  pull_request:
    branches: [ continuous_deployment ]
  workflow_dispatch:

env:
  CR_PAT: ${{ secrets.CR_PAT }}
  DOCKER_GITHUB_USERNAME: ${{ secrets.DOCKER_GITHUB_USERNAME }}
  ENV_GREETING: ${{ secrets.ENV_GREETING }}

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - name: Check Out Repository
      uses: actions/checkout@v2

    - name: Set up Docker Buildx
      uses: docker/setup-buildx-action@v1

    - name: Log in to GitHub Container Registry
      run: echo ${{ env.CR_PAT }} | docker login ghcr.io -u ${{ env.DOCKER_GITHUB_USERNAME }} --password-stdin

    - name: Build and Push Docker Images
      working-directory: ./src
      run: |
        docker buildx bake -f docker-compose.prod.yml --push


  deploy:
    needs: build
    runs-on: ubuntu-latest
    env:
      # Make sure that the SSH_USER has permission to run docker
      SSH_USER: ${{ secrets.SSH_USER }}
      SSH_HOST: ${{ secrets.SSH_HOST }}


    steps:
      - name: Add SSH key to runner
        run: |
          mkdir -p ~/.ssh/
          echo "$SSH_PRIVATE_KEY" > ~/.ssh/ssh_key
          chmod 600 ~/.ssh/ssh_key
        env:
          SSH_PRIVATE_KEY: ${{ secrets.SSH_PRIVATE_KEY }}

      - name: Create .env file
        run: |
          echo "GREETING=Hello from Github Action" >> .env


      - name: Transfer .env file to server
        run: |
          scp -i ~/.ssh/ssh_key -o StrictHostKeyChecking=no .env $SSH_USER@$SSH_HOST:.env
        env:
          SSH_USER: ${{ secrets.SSH_USER }}
          SSH_HOST: ${{ secrets.SSH_HOST }}

      # - name: Deploy to server
      #   run: |
      #     ssh -i ~/.ssh/ssh_key -o StrictHostKeyChecking=no $SSH_USER@$SSH_HOST << 'EOF'
      #     docker network create my_network || true
      #     docker pull ghcr.io/who-knows-inc/whoknows_variations_server:latest
      #     docker rm -f whoknows_flask || true
      #     docker run -d --env-file .env --network my_network -p 8080:8080 --name whoknows_flask ghcr.io/who-knows-inc/whoknows_variations_server:latest
      #     docker pull ghcr.io/who-knows-inc/whoknows_variations_nginx:latest
      #     docker rm -f whoknows_nginx || true
      #     docker run -d --network my_network -p 80:80 --name whoknows_nginx ghcr.io/who-knows-inc/whoknows_variations_nginx:latest
      #     EOF
      #   env:
      #     SSH_USER: ${{ secrets.SSH_USER }}
      #     SSH_HOST: ${{ secrets.SSH_HOST }}

      - name: Check Out Repository
        uses: actions/checkout@v2
    
      - name: Transfer Docker compose file to server
        run: |
          scp -i ~/.ssh/ssh_key -o StrictHostKeyChecking=no src/docker-compose.server.yml $SSH_USER@$SSH_HOST:docker-compose.yml
        env:
            SSH_USER: ${{ secrets.SSH_USER }}
            SSH_HOST: ${{ secrets.SSH_HOST }}
    
      - name: Deploy to server
        run: |
          ssh -i ~/.ssh/ssh_key -o StrictHostKeyChecking=no $SSH_USER@$SSH_HOST << "EOF"
            sudo docker-compose pull
            sudo docker-compose up -d
          EOF
        env:
          SSH_USER: ${{ secrets.SSH_USER }}
          SSH_HOST: ${{ secrets.SSH_HOST }}```



# Linting in Python

## Introduction

This is a forray into the linting world in Python. 3 libraries as showcased here:

1. Flake8 - Linter
2. Black - Code formatter (fixes the code)
3. Ruff - Linter and code formatter 

The workflow is setup with Ruff, only. 

## Preconditions

**Note**: Linting has already been run on the codebase to fix errors to show a passing GitHub Actions workflow. It would be more interesting to take the unlinted code from other branches and replace app.py with it. 

The tutorial assumes using [Poetry](https://python-poetry.org/). You can install it with the following command:

```bash
$ curl -sSL https://install.python-poetry.org | python3 -
```

Everything has setup in the `pyproject.toml` file in the root of the project already.

---

## Flake8

### What is flake8?

https://pypi.org/project/flake8/

### Running flake8 locally

1. Ensure you have poetry installed:

```bash
$ poetry --version
```

2. Everything has already been setup in the `pyproject.toml` file in the root of the project. From now on all Poetry commands are to be run where the `pyproject.toml` file is located.

Since Flake8 has been setup as a dev dependency but it needs to be installed 

```bash
$ poetry install
```

3. Run it with the following:

```bash
$ poetry run flake8 src/backend
```

In root you can define your style rules in the `.flake8` file.

---

## Prospector

Prospector is a "meta-tool" since it incorporates results from other static analysis tools such as [Pylint](https://pypi.org/project/pylint/), [pep8](https://peps.python.org/pep-0008/) and [McCabe complexity](https://pypi.org/project/mccabe/) and more.

Run it: 

```bash
$ poetry run prospector
```

---

## Black

[Black](https://black.readthedocs.io/en/stable/index.html) is a code formatter for Python. While Flake8 only points out the errors, Black fixes them. 

Black is said to be an opinionated code formatter which means that it is not configurable.

1. If you haven't installed from previously:

```bash
$ poetry install
```

2. You can now run it with the following:

```bash
$ poetry run black src/backend
```

---

## Ruff

As of time of writing [Ruff](https://github.com/astral-sh/ruff) is the new toy that combines linting and code formatting. But a major reason for its rise is how much faster it is compared to other options. 

```bash
$ poetry run ruff check src/backend
```

```bash
$ poetry run ruff check src/backend --fix
```

## The workflow file

The linting job checks out the code, sets up python 3 and installs the requirements.

Then it uses the Github marketplace action for Ruff to run the linting. (Remember that it does not make sense to try and fix the code in a CI/CD pipeline.)

```yaml
      - name: Run linter
        uses: chartboost/ruff-action@v1
        with:
          args: check src/backend
```

The args ensure that the linter is run on the backend code. They are not strictly necessary and you could just run it on the whole repository. 
# Testing

## Setup

In `src/backend/app_test.py` tests have already been setup for the server using the `unittest` module.

They can be run by running the file after installing the requirements. 

The test suit does not require running the server. What it does is:

1. Create a server instance:

```python
    self.app = app.app.test_client()
```

2. Create a test SQLite database:

```python
    self.db = tempfile.NamedTemporaryFile(delete=False)
    app.DATABASE = self.db.name
    app.init_db()
```

3. Run the tests. Here is example of how to hit an endpoint:

```python
self.app.post(
            "/api/register",
            data={
                "username": username,
                "password": password,
                "password2": password2,
                "email": email,
            },
            follow_redirects=True,
        )
```

And an example of an assertion:

```python
        self.assertIn(b"You were successfully registered and can login now", rv.data)
```

4. Close the database and delete the file:

```python
    self.db.close()
    os.unlink(self.db.name)
```

## The test job in the workflow

In `.github/workflows/ci.yml`, the test job checks out the code, sets up python 3 and installs the requirements. The last job runs the tests like we would do locally:

```yaml
      - name: Run tests
        run: |
          python src/backend/app_tests.py
```

```yaml
name: CI

on:
  push:
    branches:
      - "continuous_integration" # Should be on all branches - "**"
  pull_request:
    branches:
      - "continuous_integration" # Should be on all branches - "**"
  workflow_dispatch:

jobs:
  test:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: Set up Python
        uses: actions/setup-python@v4
        with:
          python-version: '3.x'

      - name: Install dependencies
        run: |
          python -m pip install --upgrade pip
          pip install -r src/backend/requirements.txt

      - name: Run tests
        run: |
          python src/backend/app_tests.py
  
  lint:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: Set up Python
        uses: actions/setup-python@v4
        with:
          python-version: '3.x'

      - name: Install dependencies
        run: |
          python -m pip install --upgrade pip
          pip install -r src/backend/requirements.txt

      - name: Run linter
        uses: chartboost/ruff-action@v1
        with:
          args: check src/backend ```



# The database

The Dockerfile is simple. It gets the latest version of the database and copies the `schema.sql` file into the `/docker-entrypoint-initdb.d/` folder. This folder is used by the PostgreSQL image to initialize the database.

```Dockerfile
FROM postgres:latest
COPY schema.sql /docker-entrypoint-initdb.d/
```

In the `src` folder a `docker-compose.yml` file is created to show how to setup the database with user credentials. You should absolutely consider how you can define these credentials in a way that ensure it won't be pushed into version control. 

### Volumes

Furthermore, the `docker-compose.yml` file shows that a volume has been created called `database`. This ensures that even if the container is stopped and restarted, the data will persist. 

You can deploy your image to a registry and then deploy it to a server.

You can run the database with the following command in the `src` folder (run without `-d` (detached mode) to see the logs the first time):

```bash
$ docker-compose up --build
```

**Note**: The `restart: always` attribute means that the service tries to restart the container if it crashes.

## Accessing the database

While the database is running, you can access the database with the following command:

```bash
$ docker exec -it whoknows_db psql -U postgres -d whoknows
```

You should see a prompt that looks like this (version numbers may vary):

```plaintext
psql (16.3 (Debian 16.3-1.pgdg120+1))
Type "help" for help.

whoknows=# 
```

To verify the schema creation and see the tables:

```sql
whoknows=# \dt
```

You can always find PostgreSQL cheat sheets online.


## Debugging help

If you issues with the database and want to start over, you should remember to remove the volume too:

```bash
$ docker-compose down -v
```

The above command removes both the container and the volume in one go. 

For convenience, here is a single command to connect and see the created tables:

```bash
$ docker exec -it whoknows_database psql -U postgres -d whoknows -c '\dt'
```# Migration (`alembic`)

While SQLAlchemy is a Python SQL tookit and ORM, Alembic is a tool for creating migrations. 

## Pre-requisites

1. Make sure that the PostgreSQL database is running. 

2. Install the `alembic` package. 

Success criteria: You can run the `alembic` command:

```bash
$ alembic --version
```

The optimal way is to avoid installing it globally by having a virtual environment.  

Here is how you can do it using [Poetry](https://python-poetry.org/):

```bash
$ poetry init -n
$ poetry add alembic psycopg2 sqlalchemy
$ poetry run alembic init alembic
$ poetry shell
```

You might simply be able to install it with pip:

```bash
$ pip install alembic
```

But this will not work on Mac with `pip` installed via Homebrew. I recommend using `poetry` despite the initial installation hurdle. 

## Configuration

Create the `alembic` setup in the `src/backend` folder:

```bash
$ alembic init alembic
```

This will create a folder called alembic where you run it.

Update the `alembic.ini` with the database connection information. Assuming that you have exposed the PostgreSQL container to localhost on the default port 5432:

```ini
# sqlalchemy.url = postgresql://<username>:<password>@localhost:5432/<db_name>
sqlalchemy.url = postgresql://postgres:password@localhost:5432/whoknows
```

## Creating a migration

This is inspired from the official documentation. First, generate a migration file:

```bash
$ alembic revision -m "create account table"
```

The file will be created in the `src/backend/alembic/versions` folder.

Update the file with the migration code from the documentation. But let's pluralize the table name to `accounts`:

https://alembic.sqlalchemy.org/en/latest/tutorial.html#create-a-migration-script

```python
def upgrade():
    op.create_table(
        'accounts',
        sa.Column('id', sa.Integer, primary_key=True),
        sa.Column('name', sa.String(50), nullable=False),
        sa.Column('description', sa.Unicode(200)),
    )

def downgrade():
    op.drop_table('accounts')
```

## Running the migration

```bash
$ alembic upgrade head
```

Check on the database. You should see the `accounts` table. 

It also created a table called `alembic_version` to keep track of the migrations. 

Rollback the migration:

```bash
$ alembic downgrade -1
```

Check on the database again. The `accounts` table should be gone.

## Seeding

Inspired by this comment https://stackoverflow.com/a/19338319 but with some adjustments. Define the upgrade function as the following:

```python
def upgrade():
    accounts_table = op.create_table(
        'accounts',
        sa.Column('id', sa.Integer, primary_key=True),
        sa.Column('name', sa.String(50), nullable=False),
        sa.Column('description', sa.Unicode(200)),
    )
    op.bulk_insert(accounts_table,
    [
        {'id': 1, 'name': 'John Smith', 'description': 'CEO'},
        {'id': 2, 'name': 'Ed Williams', 'description': 'CTO'},
        {'id': 3, 'name': 'Wendy Jones', 'description': 'CFO'},
    ]
)
```

## Final words

1. **With the idea of migration** you should be inspired to create version control for your database. Any future changes can be tracked and rolled back if necessary. It will ease the process of deploying changes to the database but also to ensure that all developers can easily apply the latest changes to the database when they pull the code.

2. **With the concept of seeding** you should be inspired to take the data from your SQLite database and populate it into the PostgreSQL database.

There are multiple ORMs and migration tools out there. Research the ones in the programming langauge that you are working with. One recommendation is to create a separate benchmark repository to test out different tools and see which one fits your project the best.# ORM (`sqlalchemy`)

The ORM setup lies in `src/bakend/db/`.

1. `db_orm.py` sets up the connection to the database.

2. `models.py` defines the tables, constraints and relationships.

## `.env`

To get started you must copy .env.example in `src` to `.env` and fill in the correct values:

```plaintext
POSTGRES_SERVER=whoknows_database
POSTGRES_USER=postgres
POSTGRES_PASSWORD=password
POSTGRES_PORT=5432
POSTGRES_DB=whoknows
```

The interesting part is that due to the setup in the docker compose file, the application is on the same network as the database. Instead of an IP adress we can refer to it through the key defined in the `docker-compose.yml` file (`whoknows_database`). 

## The dependencies

Take a note of the new dependencies in `src/backend/requirements.txt`. 

`psycopg` is the driver that allows us to connect to `PostgreSQL` but it requires some non-Python OS-level dependencies to be installed. 

This is taken care of in the `src/backend/Dockerfile`:

```Dockerfile
# Install psycopg2 dependencies
RUN apt install libpq-dev -y
```

## `app.py`

In the `app.py` file the SQLite database check is disabled and a new section has been added:

```python
from db.models import User, Page
from db.db_orm import Database

database = Database()

with database.connect_db() as db:
    users = db.query(User).all()
    for user in users:
        print(user.username)
```

It should print out `admin` if you still have the following in your `schema.sql` file:

```sql
INSERT INTO users (username, email, password) 
    VALUES ('admin', 'keamonk1@stud.kea.dk', '5f4dcc3b5aa765d61d8327deb882cf99');
```

## Final words

You are now well on your way to use the ORM in your project. Let copilot guide you on how to do the rest.

Next step is [migrations](./Migration.md).# The setup

In the [infrastructure](../infrastructure/) folder, you will find the following files:

---

## Current files

[main.tf](../infrastructure/main.tf) - The main file that contains the resources to be provisioned. Usually this is the first file that will run. It would be possible to put all Terraform code in `main.tf`, and some do, but this project has split the code into multiple files for readability.

The `main.tf` file contains the following resources:

- `terraform` block: Contains the required provider and Terraform configurations.
- `provider "azurerm"` block: Contains the Azure provider configuration.
- `azurerm_resource_group`: Creates the resource group in Azure.

[network.tf](../infrastructure/network.tf) - Contains the network resources to be provisioned. 

This file defines the virtual network, subnet, network interface and public IP address. This is standard and required to have a VM running in Azure.

`azurerm_network_security_rule` defines the `whoknows_ssh_rule` which allows SSH traffic on port 22. This has been created in its own block to give readability to the more custom rules that follow below.

`azurerm_network_security_group` defines defines two security rules that open up ports 80 and 443. This is a standard configuration for running a web server which is the goal of this project. 

You can read more about configuring Azure Firewall rules, especially the meaning of the priority numbering [here](https://learn.microsoft.com/en-us/azure/firewall/rule-processing).


[vm.tf](../infrastructure/vm.tf) - Contains the virtual machine resources to be provisioned.

The resource group and network settings are being attached to it. A disk is also being attached to the VM.

The `source_image_reference` block defines which image to pull from the Azure Marketplace.

Password authentication has been disabled and an SSH key is being transferred to the VM.

```hcl
  admin_ssh_key {
    username   = var.admin_username
    public_key = file(var.ssh_public_key)
  }

  disable_password_authentication = true
```

There is a `remote-exec` block which will be discussed in depth in the next section.

[outputs.tf](../infrastructure/outputs.tf) - Contains the outputs to be displayed after running `terraform apply`.

This is just a convenience thing where it prints out the IP address and ssh command to connect to the VM.

[variables.tf](../infrastructure/variables.tf) - Contains the variables to be used in the Terraform code.

---

## `remote-exec`

In the `vm.tf` file, there is a `remote-exec` block. This is a provisioner that allows you to run scripts on a remote machine. It looks like this:

```hcl
  provisioner "remote-exec" {
    inline = split("\n", templatefile("${path.module}/inline_commands.sh", {}))

    connection {
      type        = "ssh"
      user        = var.admin_username
      private_key = file(var.ssh_private_key)
      host        = self.public_ip_address
      timeout     = "2m"
    }
  }
```

It breaks down each line in my `inline_commands.sh` file and runs them on the remote machine over SSH.

This is non-standard and is not recommended. Instead a tool like Ansible should be used. 

The [inline_commands.sh](../infrastructure/inline_commands.sh) file updates and upgrades the system, installs Docker and creates a new user etc. 

---

## During init

If you were to run `$ terraform init` at a later step, then Terraform will download the Azure provider plugin.

This wil create the `.terraform` folder which contains a lot of nested folders and at one point contains the provider plugin that targets my system architecture on my local machine.

---

## During plan

If you were to run `$ terraform plan` at a later step, then Terraform will create a plan of what it will do.

`terraform.tfstate` is created. This is a JSON file that contains the state of the infrastructure. It is used to compare the current state of the infrastructure with the desired state. This should not be committed to the repository since it contains sensitive information. But keeping it up to date with everyone provisioning with Terraform is crucial. 

`terraform.tfstate.lock.hcl`: Locks the statefile to prevent concurrent modifications.


[Optional] `planfile`. Created by running `$ terraform plan -out=planfile`. This is a binary file that contains the plan. With a planfile, the apply step will follow the plan in the file instead of creating a new plan.

---

## During apply

Both `terraform.tfstate` and `terraform.tfstate.lock.hcl` are updated during the `$ terraform apply` step.

`terraform.tfstate.backup` is created. This contains a backup of the previous state before is applies the changes.

---

## Next: Running locally

Before you get started you might want to create a `terraform.tfvars` file first. This will be explained in [running Terraform locally](./02._running_terraform_locally.md).
# Making local changes

---

## Prerequisites

Make sure that you have fulfilled the prerequisites in [Running Terraform locally](./02._running_terraform_locally.md#prerequisites-to-run-terraform-locally).

---

## Before you apply

Once you have made changes to the Terraform files, here are some steps to go through. 

Format the code with:

```bash
$ terraform fmt
```

This will automatically format the code according to the HashiCorp style guide.

Now you can try out some [additional (non-Terraform) steps](#additional-non-terraform-steps) or you can continue.

Verify that the code is correct with:

```bash
$ terraform validate
```

This will check the syntax of the Terraform files. You could also consider installing a plugin for Terraform in your IDE to get real-time feedback.

Make a plan with:

```bash
$ terraform plan
```

Apply the changes with:

```bash
$ terraform apply
```

---

## Additional (non-Terraform) steps

You might want to run some additional checks with tools outside of the Terraform toolbox like Tflint, Checkov, or Tfsec.

All these commands assume that you are in the infrastructure folder. 

[Install tflint](https://github.com/terraform-linters/tflint) and run the linter with:

```bash
$ tflint
```

[Install Checkov](https://www.checkov.io/2.Basics/Installing%20Checkov.html) and run the scanner with:

```bash
$ checkov -d .
```

`-d` is the directory flag. It tells Checkov to scan the current directory.

[Install Tfsec](https://aquasecurity.github.io/tfsec/v1.4.2/getting-started/installation/) and run the scanner with:

```bash
$ tfsec .
```

## The tools

**Tflint** is a Terraform linter focused on possible errors, best practices, etc. It is a great tool to use to catch errors before running `terraform plan` or `terraform apply`.

**Checkov** is a static code analysis tool for infrastructure as code. It scans your IaC files and looks for security issues, compliance issues, and best practices.

**Tfsec** is a static analysis tool for Terraform code. It looks for security issues and best practices.

---

## The workflow

The workflow should be suprisingly readable. It installs and runs the 3 tools mentioned above and then finalizes by running `terraform validate`.

For the `tflint` and `checkov` steps the following key has been defined:

```yaml
    continue-on-error: true
```

It should be considered whether this is a good idea. The two tools will fail for the current setup for things that are intentional and desired. The compromise is to let them generate reports in the pipeline but not be blocking. 

The following are the different parts of the workflow files. 

---

### Setup

Checks out the code and installs Terraform:

```yaml
    - name: Set up Terraform
      uses: hashicorp/setup-terraform@v1
      with:
        terraform_version: 1.0.11
```

---

### The `tflint` step

Tflint is installed and run:

```yaml
    - name: Install TFLint
      run: |
        curl -s https://raw.githubusercontent.com/terraform-linters/tflint/master/install_linux.sh | bash

    - name: Run TFLint
      run: tflint
      working-directory: infrastructure
```

---

### The `Checkov` step

Checkov is installed and run:

```yaml
    - name: Install Checkov
      run: pip install checkov

    - name: Run Checkov
      run: checkov -d .
      working-directory: infrastructure
      continue-on-error: true
```

**Note**: The `continue-on-error: true` is set to allow the pipeline to continue even if Checkov fails. This is because the current setup will fail for things that are intentional and desired. The same is true for `tfsec`.

See the type of warnings and errors it outputs [here](https://github.com/who-knows-inc/whoknows_variations/actions/runs/11000062066/job/30541638577) by clicking on `Run Checkov`.

One of the failures is that the VM allows all internet traffic to access it on port `80`. This is something that is desired so it is a false positive.

---

### The `tfsec` step

tfsec is installed and run:

```yaml
    - name: Install tfsec
      run: |
        curl -L "$(curl -s https://api.github.com/repos/aquasecurity/tfsec/releases/latest | jq -r '.assets[] | select(.name == "tfsec-linux-amd64") | .browser_download_url')" -o tfsec
        chmod +x tfsec
        sudo mv tfsec /usr/local/bin/

    - name: Run tfsec for static analysis
      run: tfsec
      working-directory: infrastructure
      continue-on-error: true
```

The first cURL line fetches a document that contains a URL for the latest release candidate of `tfsec`. It uses this URL to install from. 

See the type of warnings and errors it outputs [here](https://github.com/who-knows-inc/whoknows_variations/actions/runs/11000062066/job/30541638577) by clicking on `Run tfsec for static analysis`.

For instance, it warns that SSH is accessible from any IP address which is what I want it to be in my case but for a company it would be smart to restrict it to a specific IP range (office network) and require employees to VPN into the office network if they need to access the VM outside of the office.

---

### The `terraform validate` step

Finally, Terraform is initialized and validated. This is to ensure that the Terraform code is valid if the developer has forgotten to do the step locally.

```yaml
    - name: Terraform Init
      run: terraform init
      working-directory: infrastructure

    - name: Terraform Validate
      run: terraform validate
      working-directory: infrastructure
```
# Running Terraform locally

---

## Prerequisites to run Terraform locally

Install [Terraform](https://developer.hashicorp.com/terraform/install?product_intent=terraform) and [Azure CLI](https://developer.hashicorp.com/terraform/tutorials/azure-get-started/azure-build) on your local machine.

The assumption is that you have an SSH key-pair in your `~/.ssh` directory named `id_rsa` and `id_rsa.pub`. If you have a different name, you can change it in the `variables.tf` file.

---

## Defining variables


`variables.tf` contains all variables that are used in the Terraform files. For many of them, the variables are harcoded with a default value. 

Currently, if you were to run `terraform plan` and `terraform apply`, you would be prompted to enter the values not hardcoded in `variables.tf`.

Instead, you could create a file named `terraform.tfvars` and define the values there. This file is automatically loaded by Terraform and its values are used as default values for the variables. In a `.gitignore` template for Terraform it will be ignored.

Aditionally, even if you have defined a default value for a variable, you can overwrite it in the `terraform.tfstate` file.

A sample has been provided. It is named `terraform.tfvars_copy`. Copy it and name the file `terraform.tfvars`. Make changes as needed and you are ready to proceed.

**Note**: Be careful not to push snesitive information. In a standard `.gitignore` template for Terraform it will be ignored because it might contain sensitive information about your infrastructure.

---

## Provisioning with Terraform

To run Terraform, you need to initialize the working directory. This is done by running:

```bash
$ terraform init
```

[Optional] Run `plan` to see what changes will be made:

```bash
$ terraform plan
```

Finally, apply the changes:

```bash
$ terraform apply
```

You will get a chance to see the changes again and confirm them by typing `yes`.

After a successful run, you should see the public IP address and the ssh command in the terminal. Try to log into the VM using the provided command.

---

## Destroying the resources

At some point you might want to take down the infrastructure. 

You can destroy the resources by running:

```bash
$ terraform destroy
```

## Flask - Prometheus setup

In `requirements.txt` in the `src/backend` folder, the following packages have been added:

```txt
prometheus-client==0.13.1
psutil==5.8.0
```

Psutil is a cross-platform library for retrieving information on running processes and system utilization (CPU, memory, disks, network, sensors) in Python.

In `app.py` in the `src/backend` folder, all new sections have been clearly commented. Just search for `prometheus`. 

Here is the setup:

```python
CPU_GAUGE = Gauge(
    "whoknows_cpu_load_percent", "Current load of the CPU in percent."
)
REPONSE_COUNTER = Counter(
    "whoknows_http_responses_total", "The count of HTTP responses sent."
)
REQUEST_DURATION_SUMMARY = Histogram(
    "whoknows_request_duration_milliseconds", "Request duration distribution."
)


# Add /metrics route for Prometheus to pull metrics from
@app.route("/metrics")
def metrics():
    return Response(
        generate_latest(), mimetype="text/plain; version=0.0.4; charset=utf-8"
)
```

For every client HTTP request a counter is increased, the request duration is measured. 

```python
@app.before_request
def before_request():
    """Make sure we are connected to the database each request and look
    up the current user so that we know he's there.
    """
    # Prometheus metrics
    request.start_time = datetime.now()
    CPU_GAUGE.set(psutil.cpu_percent())
    # Prometheus metrics end
    g.db = connect_db()
    g.user = None
    if 'user_id' in session:
        g.user = query_db("SELECT * FROM users WHERE id = '%s'" % session['user_id'], one=True)


@app.after_request
def after_request(response):
    """Closes the database again at the end of the request."""
    g.db.close()
    # Prometheus metrics
    REPONSE_COUNTER.inc()
    t_elapsed_ms = (datetime.now() - request.start_time).total_seconds() * 1000
    REQUEST_DURATION_SUMMARY.observe(t_elapsed_ms)
    return response
```

Additionally, on every poll the CPU value is retrieved. 

The file `src/prometheus.yml` is a config file for Prometheus. It has been clearly commented to aid you. 


---

## docker-compose.yml

The docker-compose.yml should be pretty straightforward. 

The services are in the same network `app-network`. There is also an order in which they depend on each other. 

Port `3000` for Grafana and `9090` for Prometheus are the default ports. 

---

## Try it out

```bash
$ docker-compose up --build
```

Now go to http://localhost:8080/metrics. You can try refreshing a couple of times and see some of the metrics change (CPU usage, request counter).

This is the URL that Prometheus requests. How often it does this is defined in `src/prometheus.yml`.## Grafana

In your browser nagivate to http://localhost:3000/. The default login is `admin`/`admin`.

1. Click `Add your first data source`.

<img src="./assets/grafana_1.png" alt="grafana dashboard setup">

2. Select `Prometheus` as the data source.

<img src="./assets/grafana_2.png" alt="grafana dashboard setup">

3. Type http://prometheus:9090 in the URL field. Prometheus reflects the name of the service in the `docker-compose.yml` file.

<img src="./assets/grafana_3.png" alt="grafana dashboard setup">

4. Scroll down and click `Save & Test`. After you click, you should see the following message on the same page: `Successfully queried the Prometheus API`. In that case click on `building a dashboard`.

<img src="./assets/grafana_4.png" alt="grafana dashboard setup">

5. Click on `+ Add visualization`.

<img src="./assets/grafana_5.png" alt="grafana dashboard setup">

6. Change the default visualization type from `Time Series` to `Stat`. 

<img src="./assets/grafana_6.png" alt="grafana dashboard setup">

7. Search in the `Metrics` browser. Unlike the screenshot. You could search for `whoknows_cpu_load_percent`, `whoknows_http_responses_total` or `whoknows_request_duration_milliseconds`. These are the metrics that have been set up in `app.py`. 

<img src="./assets/grafana_7.png" alt="grafana dashboard setup">

8. You can click `Run Queries` to check out the result. Click `Apply`. (The blue button in the top right)

9. To save the dashboard, click on the `Save` icon. Give the dashboard a name and click `Save`.

<img src="./assets/grafana_8.png" alt="grafana dashboard setup">

10. Click `Add` and `Visualization` to keep adding panels to the dashboard. You can give them titles. 

<img src="./assets/grafana_9.png" alt="grafana dashboard setup">

<img src="./assets/grafana_10.png" alt="grafana dashboard setup">

11. Remember to set the update interval to anything but `OFF`. Select `Auto` or match it with the Prometheus update interval.

<img src="./assets/grafana_13.png" alt="grafana dashboard setup">

12. Star the repository, for quicker access from the frontpage. 

<img src="./assets/grafana_14.png" alt="grafana dashboard setup">

Grafana has changed the UI a lot and setting the dashboard to be what appears on the Home page is not straightforward.

---

## [Highly Optional] Installing plugins for Grafana

If you would like to visualize the data in a different way than the default, you can install plugins for Grafana.

1. Go to the `Panel plugins for Grafana` page: https://grafana.com/grafana/plugins/panel-plugins/

2. Let's try it with this plugin: https://grafana.com/grafana/plugins/grafana-clock-panel/

3. First, log into (-it = interactive) the bash shell of the grafana instance. Verify it's name on your machine with `docker ps`. In my case it is `src-grafana-1`.:

```bash
$ docker exec -it src-grafana-1 /bin/bash
```

4. Once logged in run the install command, see the success message and typee `exit` to leave the shell:

```bash
04830e2291c1:/usr/share/grafana$ grafana cli plugins install grafana-clock-panel
✔ Downloaded and extracted grafana-clock-panel v2.0.1 zip successfully to /var/lib/grafana/plugins/grafana-clock-panel

Please restart Grafana after installing or removing plugins. Refer to Grafana documentation for instructions if necessary.
04830e2291c1:/usr/share/grafana$ exit
exit
```

The exact command can be found on the installation tab:

https://grafana.com/grafana/plugins/grafana-clock-panel/?tab=installation

5. Restart the Grafana service. In mycase, where it is named `src-grafana-1`:

```bash
$ docker restart src-grafana-1
```

6. After restarting the service, installed plugins should be available immediately. You always verify the installation by going to http://localhost:3000/plugins.

7. Go to your dashboard, click `Add` and `Visualization` and you should see the new plugin available. Search for `clock` and you should see the new plugin.

<img src="./assets/grafana_11.png" alt="grafana dashboard setup">

8. It's possible to style the background color, font size etc. in the options tab. 

9. Success! You have now installed a plugin for Grafana.

<img src="./assets/grafana_12.png" alt="grafana dashboard setup">


---

## [Highly Optional] Use a dashboard template

For this course I recommend that you create the dashboard yourselves so that you make conscious decisions on what to display. But it's possible to find and import dashboards from here:

https://grafana.com/grafana/dashboards/

---

## Codify your creation

Make sure to turn your Grafana configuration into code, so that you do not go through the manual setup:

Search for "Grafana Predefined Dashboards":

https://runkiss.blogspot.com/2020/01/using-prometheus-grafana-to-monitor.html

Or you can build a custom Grafana image:

https://grafana.com/docs/grafana/latest/setup-grafana/configure-docker/#build-a-custom-grafana-docker-image 
## What is `safety`?

[Safety](https://pypi.org/project/safety/) is a vulnerability scanner for Python packages. It checks the packages in `requirements.txt` against the [PyUp Safety DB](https://pyup.io/safety-db/).

[Snyk](https://snyk.io/) is another widely uses vulnerability scanner that works for multiple programming languages. 

---

## The workflow file

The workflow file is named [safety.yml](../.github/workflows/safety.yml). It is a simple workflow that installs Safety and analyzes the packages in `requirements.txt`.



## What is `OWASP ZAP`?

[OWASP ZAP](https://www.zaproxy.org/) is a security tool that helps find security vulnerabilities in web applications. It is a widely used tool for security testing and is available as a standalone application or as a plugin for browsers. 

Unlike `bandit` and `safety`, `OWASP ZAP` requires the application to be running in order to scan it. 

There are more than one Github Marketplace Action for OWASP ZAP. The one used in this tutorial is the [OWASP ZAP Full Scan Action](https://github.com/zaproxy/action-full-scan).

---

## The workflow file

The workflow file is named [owasp_zap.yml](../.github/workflows/owasp_zap.yml). It is a simple workflow that runs the application locally on the runner and then runs the OWASP ZAP scan on the application.

1. 

First part of the workflow is to install and run the application. Care is taken to ensure that the application is running before the scan starts. 

```yaml
    - name: Start the application
      run: |
        python src/backend/app.py &
        sleep 10  # Give the app time to start

    - name: Ensure the app is running
      run: |
        curl --retry 5 --retry-connrefused --retry-delay 5 http://localhost:8080
```

2.  

The second part performs that scan. It's possible to make the scan create a Github Issue with the results. Here it is set to `false` to avoid creating Issues.

```yaml
    - name: ZAP Scan
      uses: zaproxy/action-full-scan@v0.10.0
      with:
        token: ${{ secrets.GITHUB_TOKEN }}
        target: 'http://localhost:8080'
        cmd_options: '-a' # automatic mode
        allow_issue_writing: false
```

3.

The last part uploads the result of the scan as an artifact. 

```yaml
    - name: Upload OWASP ZAP report
      uses: actions/upload-artifact@v3
      with:
        name: zap-report
        path: zap.out 
```

[Here](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/downloading-workflow-artifacts) is how to download the artifact.

---

## Giving the right workflow permissions

If you were to run the workflow right away, you will encounter the following error in the logs:

```plaintext
Error: Resource not accessible by integration
```

It is caused by the workflow not having the correct permissions despite having permissions set up in the Workflow file.

Permission should be granted to the workflow. 

Try doing it in the repository settings:

<img src="./assets/workflow_permissions_repository.png" alt="workflow permissions repository">

If the repository is part of an organization, the option to set it as `read/write` permission might be disabled. The solution is to set it in the organization settings first:

<img src="./assets/workflow_permissions_organisation_1.png" alt="workflow permissions organisation">
<img src="./assets/workflow_permissions_organisation_2.png" alt="workflow permissions organisation">

Then go back to the repository settings and set the permissions. 

Remember to retrigger the workflow after setting the permissions. Running the same failed workflow execution will run it with the old permission settings. 

## What is `bandit`?

[Bandit](https://github.com/PyCQA/bandit) analyzes Python code statically and finds potential security issues. 

The official documentation can be found [here](https://bandit.readthedocs.io/en/latest/).

---

## The workflow file

The workflow file is named [bandit.yml](../.github/workflows/bandit.yml). It is a simple workflow that runs Bandit on the Python code in the repository.

The workflow is straight forward. In this case it runs on a single Python file but it can also be configured to run on a directory. 

---

## The exucution

Since the server has several security vulnerabilities, the Bandit scan will fail with a list of issues.

Try fixing the issues in your own fork and try to make the scan pass.
# Registering domains with one.com

Get the voucher coupon from Teams. 

Remember that it's optional to use one.com and you are welcome to use other methods. 

Other services offer student discounts. 


---

# Steps I

Note that the design of the website may change over time.

1. Go to [one.com](https://www.one.com/en/)

2. Click on "Domain" in the top menu.

3. Enter the domain you want to register in the search field and click "Search".

4. Click on "Add to cart" next to the domain you want to register.

5. Click on "Do you have a voucher code?" and enter the voucher. Click "Add".

---

# Steps II

6. Click on "Continue to checkout".

7. Fill in the required information and click "Continue". You must use your real email and phone number since you will get an activation link + code. 

If you get the chance, then select "I want one.com to administrate my *** domains." 

In your case it means that when you wish to terminate the domain you allow one.com to do it on your behalf rather than you having to contact another company to do it.

Take a break! It can take up to an hour before you get the domain. 

# Prerequisite: Make sure that Docker is installed

This is if you are on Ubuntu and haven't installed Docker already.

Make sure that your have updated and upgraded `apt`:

```bash
$ sudo apt update
$ sudo apt upgrade -y
```

Then run the following:

```bash
$ sudo apt install docker.io -y
$ sudo systemctl restart docker
$ sudo apt install -y docker-compose
```

You should also have made sure that the A record is pointing to your server:

```bash
$ dig A <yourdomain.com> +short
```

---

# Install Certbot

Certbot is a tool that will help you get a certificate from Let's Encrypt.

```bash
$ sudo apt install -y certbot
```

---

# Get the certificates

Run the following command:

```bash
$ sudo certbot certonly --standalone -d <yourdomain.com> -d <www.yourdomain.com>
```

---

# Running Nginx over HTTPS

In the `tls` directory, you will find two files:

1. `docker-compose.yml`
2. `nginx.conf`

You can try them out to begin with to get the setup running and later on adjust to fit your needs.

---

# docker-compose.yml

The [docker-compose.yml](../tls/docker-compose.yml) file sets up Nginx with the DockerHub Nginx image and loads the certificates into the container volume.

It exposes port `80` and `443` to the host machine.

**Remember to change all instances of keacloud.dk to your domain.** in this file. 

---

# nginx.conf

The [nginx.conf](../tls/nginx.conf) file is the configuration file for Nginx.

**Remember to change all instances of keacloud.dk to your domain.** in this file. 

---

# Running the setup

Add the two files to the server. You could make a directory for them.

To run the setup, you can run the following command (from the directory where the files are):

```bash
$ sudo docker-compose up -d 
```

Now test it out by going to your domain in a browser.

You should've suceeded.# Prerequisite: Have a server

If you don't already have a server running or if you would like to try this setup then create a server. 

Make sure that you have a public IP.

Make sure that port 80 and 443 are open.

You can do it with the following commands:

```bash
$ sudo ufw allow 80
$ sudo ufw allow 443
```

---

# Find the DNS setting

The DNS setting is tucked away at the bottom.

<img src="./assets/dns_settings.png" alt="dns settings one.com">

---

# Add the A record

Add the A record with the IP address of your server.

<img src="./assets/add_a_record.png" alt="add a record one.com">

---

# Make sure that the A record is added

After a few minutes, make sure that the A record is added with the following command (from your local machine):

```bash
$ dig A <yourdomain.com> +short
```

