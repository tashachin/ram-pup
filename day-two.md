__Monday, 06.07.2021__
# Things I've achieved:
- Learned how to better navigate the IDE.
- Read a lot of XML files and oriented myself better.
- Created a Pixel 2 for emulation.
- I received a successful token via Postman (but how do I encode the variables safely?)
- I wrote some pseudo-code to handle the backend business logic of passing tokens safely.
- I now remember what a query string looks like!
# Things I've learned:
- Drawables are built-in to Android/Kotlin. Android Studio (an IDE, built by IntelliJ), has a bunch of native ones. I can drag and drop a folder of asset images into Resource Manager.
- Drawables have different density qualifiers. These are important as they translate dpi into shorthand and only certain qualifiers are supported by iOS. 
- axios.js is a promise-based HTTP client for the browser and Node.js. Axios makes it easy to send asynchronous HTTP requests to REST endpoints and perform CRUD operations. It can be used in plain JavaScript or with a library such as Vue or React.
- OkHTTP is a library for Kotlin to serve async HTTP requests (notice how there is no S).
- These kinds of HTTP libraries all do the same thing in their own native language! (Make network requests to endpoints).
- `res` folder contains resources. Resources may include static image files as well as .xml files.
- XML files are eXtensible Markup Language files and basically use customizable syntax to tell a machine how to render a document.
- Postman is a great resource for testing API responses, especially with the vast number of configurations you can use. I'll worry about testing the application after I get it up and running.

# Topics to research:
- DONE: How do I navigate an Android project file structure? What code should I edit?   More technically: Which file do I edit to change the user story flow? (The Kotlin files, or the XML files that seem to correspond to the res directory?)
- TODO: MVVM Architecture
- IN PROGRESS: Is it worth ignoring the layout right now and focusing on testing that I'm able to fetch the data in the first place?
- TODO: How do I safely store a Client Secret?

# End-of-day reflections:
- I am getting discouraged by the vast volume of work that needs to be done to create a mobile application.
- I have not written a single line of code yet, I am still taking into account all the different technologies that go into making a mobile application.[1]
- Taking short breaks to keep myself grounded is very helpful in pushing through the "swamp" of information.
- I should take some time to reflect upon my progress.

[1] I wrote some pseudo-code after I held myself accountable!

# Goals for tomorrow:
- Read up some more on OkHTTP library and network code. Achieve a high-level understanding of what network code is and find examples of it.
- Figure out how to introduce a new view/activity into my Kotlin project to handle OAuth integration. I'm only using OAuth if I intend to register end-users. The authentication process I've been using up until now is to allow IGDB to talk to Twitch's servers.
