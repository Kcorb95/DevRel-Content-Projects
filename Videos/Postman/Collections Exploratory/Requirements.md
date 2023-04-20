Ticket: https://github.com/postmanlabs/devrel-content/issues/27
Refresher to this video: [How to use and share Postman Collections](https://youtu.be/bF8q8wvLs8A)

- Benefits of collections
- Use cases (grouping requests, sharing, documentation, running workflows, test suites)
- Collection variables, using with Env
- Collection-level scripts, execution order
- Etc.

How in depth are we looking to go?
Do we want to discuss collaboration, mocks, monitors etc.?

- Collections are an organizational tool that you can use to put together your requests into groups
- Can be done for personal use or for sharing with teams and the public
- “Need” a postman account!
- Go into personal workspace and introduce collections sidebar. Show how collections contain requests and are like folders
- Show how to create a collection by “NEW” or “+”
- Add basic request to collection 
- Add documentation for the collection
- Add variable to collection and demonstrate scope (Workspace vs Collection vs Environment variables)
- Collection level scripts to run something before every request and after every request (Use the twitch bot perhaps?)
- Create Fork and PR
- Brief overview of adding comments
- Setup a monitor to run a collection
- Cover sharing, moving and running collections in collection runner
- Show Duplicate and Export collections
- Private API network as a place to share APIs (and collections) with team members
- Git integrations to share collections with team members
- When building integrations or API workflows, you can use the Postman API to `GET` a collection, like as part of a CI/CD pipeline.
- Show how to import a collection through “Import” 
- public api network as a place to browse and fork collections from public APIs.

Joyce’s Story Arc:
- simplest definition of collection = group of api requests
- Foundational building block for more advanced features: documentation, monitors etc.
- collections allow you to collaborate

Structure:
- Introduce definition of a collection as it's simplest level, a group of API requests.
- Create collection
- Add request to collection
- Documentation
- Add variables to collection and demonstrate scope (workspace vs collection vs env variables)
- Talk about collection level scripts.
- Serves as a foundational building block for more advanced features: monitors, collection runner, etc..
- Exporting: Duplicate & Export, Private API Network, Git Integrations
- Collaboration: Forking, PRs, Comments etc.
- Importing as JSON, github and public API network.

- Generating collections from API schemas
- Linking collections to API elements and APIs
- Run in Postman button

Useful Resources:
- https://www.postman.com/collection/
- https://learning.postman.com/docs/sending-requests/intro-to-collections/
- https://learning.postman.com/docs/designing-and-developing-your-api/the-api-workflow/
- https://learning.postman.com/docs/collaborating-in-postman/sharing/
- https://learning.postman.com/docs/publishing-your-api/documenting-your-api/
