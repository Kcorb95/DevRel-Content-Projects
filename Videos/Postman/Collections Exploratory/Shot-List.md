[Kevin on Screen]
Welcome to the exploratory. In this video we'll be taking a look at organizing your requests in Postman and improving your workflow with Postman Collecitons.

[Switch to Postman UI, Show clean interface of organized collections]
Postman Collections assist in organizing requests, examples and other elements in your workspace while enabling collaboration and automation. These executable API descriptions can also be generated from your API schemas and help link elements like mocks, monitors, and tests to streamline your API development process.

[Navigate to the Run History Tab, Simpsons Quotes]
Postman Collections are a group of saved requests. Every request you send in Postman appears under the History tab of the sidebar.
Currently you may be used to relying on the history tab in Postman where you run and re-run requests without too much structure or organization.

[Messy History Tab]
On a small scale, using requests like this may be convenient, but you will quickly find it time-consuming to find a particular request in your history.
Instead of scrolling through your history section, you can save all of your requests in a group for easier access.

[Navigate to workspace, Collections tab]
Start by creating or navigating to your workspace. 
Select "New" at the top of the sidebar and select "Collection"
You should see a new element appear on the sidebar which represents our collection.

[Rename Collection, start writing description]
We can give our collection a new name by clicking on the pencil at the top of this window.
Additionally, it is very important to fill out the description to document what this collection is about and how to use it.

[add request]
Selecting the more actions icon and choosing "add request", we can save a new request to our collection.

[More collections, re-organize requests]
Existing requests can also be re-organized and dragged into your other collections as your workspace grows.

[Add requests from history to Simpsons Collection]
You may also add requests from your history to a collection. Select "History" in the sidebar and find the request that you wish to save. Select the more actions icon next to the request and select "Save Request". Choose the collection to add the request to and then select Save.

[Collection Overview, Collection Templates]
Say you aren’t sure how to get started from here. Maybe you are looking to pick up some of the basics of working with a RESTful API. That’s where Collection Templates come in to help.
Navigate to the collection overview by selecting your collection and then select “More Templates”.
We have a growing list of Collection templates to help you get started with various topics including integration and regression testing, RESTful API basics, API documentation, Authorization methods, data visualization, conditional workflows, mock data generation and running collections with data files.
Postman’s collection templates help with exploring the Postman API platform's capabilities with ease, gaining insights into tried and tested workflows for API development and eliminates the need to build or create collections from scratch to expedite development and testing time.

[New, HTTP Request, Collection]
If you’re looking to just quickly get working with Postman and sending requests, another option is to select “Create HTTP Request”, build your request and select “Save” to create a collection.

[Collection Overview]
In addition to the benefits of documenting and organizing your requests with a Collection, collections also allow you to speed up your development and testing workflows.

[Click Auth tab]
Select the "Authorization" tab to configure authorization details for all requests in this collection. Each request within your collection will inherit this authorization unless they specify their own.

[Pre-request Scripts]
Write Pre-request scripts which will run before each request in your collection is sent to the server. These will always run, even if your requests have their own pre-request scripts.

[Test Scripts]
Similarly, Test scripts will run after a response is received.
For example, testing to see if all of your requests return a status code 200 and other similar things that you’d want to do across all requests.

[Variables]
Variables allow you to define values that are shared across all requests in the collection.

[Pin collections]
To help organize things further, You can pin collections to the top of your list by selecting the star icon next to it.

[Search Bar]
Use the collection search bar to filter through your collections.

[Add Folders]
You can also add sub-folders to create extra levels of nesting for your collection's requests and examples.
Folders also have their own set of Authorization, Pre-request and Test scripts sections.

[Drag & Drop]
Re-order your requests, folders and examples inside a collection by dragging and dropping them.

[Delete Collection]
Delete a collection by selecting the more actions icon next to the collection's name and select "Delete".

[Recover Collection]
You can also recover a deleted collection by selecting the more actions icon next to the collection search bar and opening the trash.
Select the restore icon next to the collection that you wish to recover.
Items remain in your trash for up to one day, or longer depending on your Postman plan.

[Collection Overview]
Now let’s talk about some of the more advanced ways you can use Collections in Postman.

[Create Mock for Collection]
Postman enables you to create mock servers to assist with API development and testing.
A mock server simulates the behavior of a real API server by accepting requests and returning responses.
By adding a mock server to your collection and adding examples to your requests, you can simulate the behavior of a real API.
When you send a request to a mock server, Postman matches the request to a saved example in your collection. Postman then responds with the data you added to the example.
Check out Postmanaut Joyce’s Exploratory on Mock Servers in Postman: https://youtu.be/n_7UUghLpco

[Setup Monitor for Collection]
Postman Monitors give you continuous visibility into the health and performance of your APIs.
A collection-based monitor runs a series of requests from the Postman cloud on a schedule that you set.
When creating a monitor, you choose a collection with the requests you want to run. For example, these can be basic requests that indicate whether an endpoint is up and reachable.
More complex collections can make use of chained requests, test scripts, and environment variables to validate API responses and functionality.
Once the monitor is running you’ll be alerted to any test failures, so you can identify and address issues before your API’s consumers are affected.
Check out Postmanut Joyce’s Exploratory on Monitoring your APIs in Postman: https://youtu.be/tDQzY1Hn2LY

[Collection Overview]
Documentation is an important part of any collection or API. Good documentation helps the people who use your collection understand what it does and how each request works.
Postman automatically generates basic documentation for any collection you create. View the documentation for details about all of the requests in your collection, along with sample code in various client languages.

[Scroll through request documentation]
Request details include the method, authorization type, URL, headers, request and response structures, and examples.
In addition, the documentation displays all key-value pairs for request parameters, headers, and bodies.

[Go through requests, add descriptions]
To make your documentation even more valuable to people consuming your APIs and working with your collections, add descriptions to the requests and other elements in your collection. Any descriptions you add are automatically included in the documentation for your collection.

[Collection Overview]
You can also edit descriptions when viewing the complete documentation for a collection. Select “View Complete Collection Documentation” at the bottom of the collection overview, and then edit the descriptions as usual.

[Add documentation to parameters]
Add descriptions to parameters and headers to help others understand and use the requests in your collection. These descriptions are visible to people who have access to your collection or anyone viewing your published documentation.

[Authorization in Documentation]
Your documentation automatically includes the type of authorization required to access your endpoints. These details appear below the collection description and also below each request in your documentation.

[Examples in Documentation]
Any examples you add to a collection are also automatically included in the documentation. For each request, your documentation shows the example code snippets as well as the example response body and headers.

[Collection Overview]
Now without going into detail on the API builder, you can also generate a new collection for API documentation by selecting APIs in the sidebar and selecting an API.

[Navigate to APIs, select API and generate]
On the API's overview, next to collections, select + and select "Generate from API definition." Change any settings to customize this new collection and then select Generate Collection.
This new collection displays on your API's overview and under your API in the sidebar. To view the documentation for the collection, expand the collection and select View Full Documentation.

[Link existing]
Similarly, you can also use an existing collection for API documentation by selecting Copy Existing Collection instead and select the collection that you wish to assign.

[Publish Documentation]
Publishing your documentation makes it publicly available to anyone with the link to the documentation and a web browser. Publish your documentation to help people around the world learn how to use your collection or interact with your public API.
Public documentation automatically includes details for each request or endpoint in the published collection, along with sample code in various client languages. As you update your collection, the published documentation automatically stays in sync with your latest changes. There's no need to publish the documentation again after making changes.
Your public documentation also includes the Run in Postman button so users can interact with your collection or API directly in Postman.
Check out Postmanaut Joyce’s video on building better documentation in Postman for more information and best practices: https://youtu.be/XNVo9WkCoak

[Collection Overview, Import URL and then from github]
You can additionally import and export collections in Postman.
Select "Import" in the upper left and then enter the URL or raw text for your collection.
Additionally, you can upload files or folders or even import from various git repositories, code repos and other API gateways.

[Export Collection overview]
To export a collection, select the more actions icon next to the collection and then select "Export". This JSON file can be used to run the collection in the Postman CLI, Newman and your CI/CD pipelines.

[Collection Overview, Share]
There are a number of ways that you can share a collection in Postman.
Invite others to collaborate by selecting the more actions icon next to the collection name and selecting "Share". You can enter names, email addresses and group names here for the people you want to share the element with.
You may also select whether or not these people will have Viewer or Editor permissions for the element that you are trying to share.

[Share window, copy link]
Additionally you can share by copying a link and sending it directly.

[Show email]
When you share a collection, external users who aren't on your Postman team will receive an invitation to join your team right away if you're a team admin or super admin.

[Allow guests toggle]
You can allow external users who aren't in your Postman team to view a collection by selecting the more actions icon next to the collection name, selecting Share, then turning on the toggle next to "Allow Guests with the link to join your team and view collection".
This assigns people the "Guest" role at the team level and a limited Viewer role at the collection level. This does not consume paid seats.

[Show run in postman button]
The Run in Postman button can be used to share collections in a website or README by embedding a small snippet of code.

[Collection Overview, watch]
As your team grows and there are more people working on collections in your workspaces, you may find it helpful to "Watch" collections.

[Watch Notification Ex]
After selecting the watch icon for a collection, Postman notifies you when a team member makes changes to the collection, including adding a new request, modifying the existing requests, adding or updating variables, editing pre-request scripts or tests and adding or deleting a folder.

[Show changelog]
Postman users on paid plans can additionally view the collection's changelog to see what has changed since you last looked at a collection.

[Show forks, PRs etc.]
When working with teams and collaborating with others, it’s important to practice proper version control practices.
Being able to fork collections to make a “copy” of it in your own workspace to develop new collection versions, submit a pull request to merge it back into its parent collection and review these PRs is one such workflow.
Check out Postmanaut Joyce’s level up on Version Control for Collections in Postman: https://youtu.be/QKxukXJWRPI

[Show reverting changes]
For users on a paid plan, if you ever need to revert your collection to an earlier state, select the changelog icon on the right sidebar.
Here you can select a session to expand it and then select the more actions icon next to a change and select "Restore to this change."
This will revert a collection to the point immediately after you had performed the selected change.


[Collection Overview, Collection Runner]
Collections can power various parts of your API development, testing and publishing workflows.
Select "Run" to access the collection runner. This allows you to run all requests in a collection and build testing workflows into your runs.
Among the provided configuration options, you can select the number of iterations for your collection run and optionally include a data file for the run and whether or not to persist responses for a session to review after running.
By default, your requests run in the sequence they're listed in in the collection. If you need to change this order, select and drag a request to its new location in the order.
Additionally, you can also remove an individual request from the run by clearing the checkbox next to its name.

[Set Next Request Example in Test Scripts]
You can also alter the flow of execution from your request scripts using setNextRequest to create workflows.
The collection runner logs your request test results and can use scripts to pass data between requests and alter the request workflow.

[Collection Runner Logs]
When running collections manually, Postman displays the results of your request executions and test results in real time.
To learn more about what happened during a collection run, you can view the details about each individual request and its headers and body.

[Show scheduled runs]
In addition to running collections manually, the Collection Runner enables you to schedule collections to run automatically at specified times in the Postman cloud. You can also use collection runs in conjunction with other Postman utilities to build automation into your API projects.
The "Scheduled runs" tab shows all of the scheduled runs for the current collection. This includes the upcoming run's scheduled time, the name of the scheduled run and the environment associated with the scheduled run.

[View results of scheduled run]
You can view the scheduled run's latest results as well as pause, resume, edit and delete scheduled runs from this page.
If you are running the desktop version of Postman, you can also export the results of a collection run to share with your team. Open the collection run in the runner and select "Export Results" at the top right to download the run.

[Documentation on Postman CLI]
The Postman CLI and Newman both allow you to manually run and test your collections locally or in the Postman cloud.
These tools help you automate collection runs on your CI/CD pipelines.
Check out Postmanaut Joyce’s Exploratory on this topic
https://youtu.be/7F3f4WOFs38

[Set up live collection]
Postman Live Collections enable you to keep your collections up-to-date based on the usage of your application. By observing your application, the Postman SDK automatically updates your Live Collections.
Live Collections help improve collaboration by ensuring everyone stays up to date on the latest changes and improvements to your APIs.
It helps promote better testing by allowing developers and testers to easily test your API in a real environment. This can help identify issues and bugs before they are deployed to production.
Postman Live Collections can streamline the development process by enabling developers to quickly and easily set up their collection and maintain it. This can help automate the manual process of creating and updating collections which sometimes results in an incomplete collection.
They can also automatically generate documentation for your API. This documentation can be updated in real-time, making it easier for developers to understand and use your API.
