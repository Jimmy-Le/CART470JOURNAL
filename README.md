# CART470JOURNAL

## (NEW) WEEK 4: Setting Up

My task for this week is to research databases and set up the website.

### Databases
I created a [Figma Jam](https://www.figma.com/board/xuDRhRUVjItJ5sSZrH4wHU/Databases?node-id=0-1&t=04BX6yEVwJPMQP4k-1) to research 3 of the most promising database services that I could find.

**AirTable DB**
- Its really good for our client to easily add new entries to the database without knowing any coding. 
- It also has a decent amount of storage space for its free tier (1 GB). 
- However, it has a limit of 1000 api calls a month. Considering that we are not *that* experienced with React and professional web development, we are probably gonna end up using all of the quota.
- Once we have everything properly setup, we can maybe revisit the idea of switching to this database if we need more space. Otherwise, the client was okay with using other databases as long as we provide an easy way for them to upload and edit information.


**MongoDB**
- I kind of worked with this one when I was in cegep. However it has been a while.
- It has an okayish storage size for the free tier (512 MB)
- It apparently is a part of something called the MERN stack (Mongo, Express, React, Node.js) which we were gonna use the other 3 for our webpage.
- It does have an online webpage to access the database, however it is extremely beginner unfriendly. As such, we will need to develop an Admin Page.
- I will use this to start, since it seems to be well integrated with react JS


**MariaDB**
- This one has a lot of storage *I think* with over 64 TB of space or whatever the hosting site limit is.
- It is also FREE and open source
- It is technically more ethical
- But it does seem more difficult and it is a relational database, so it is less flexible.
- We probably won't use this one, but it would be good to consider if our client needs the space.


### Starting a website

We talked a bit about this in class with one of our friends who is super good at comp sci stuff, he recommended using React for the components which would be useful for making interactive and dynamically generated Arrows or something. I wasn't really paying attention but I also wanted to practice react some more.

At the same time, my personal concern was that we needed a server to handle database request, so I resorted to making a node.js server. I made one of these in a College class, so I know that it is possible, but now that i have AI at my fingertips, i can easily refresh my memory or follow along with its guidance.

I also connected to the MongoDB database, so that it would be easier for us to work on all the parts of the projects at the same time.

### Potential Concerns
Hosting might be an issue, but alledgedly Render can handle hosting a node.js server and the frontend.

Since MongoDB is not very easy to manage, we are gonna have to create a decent UI to handle database operation, this will take away some time working on the project.


---


## WEEK 3: Visual Prototyping

After meeing up with Elizabeth Miller, we got a loooot of information and ideas of what to implement into our final product.
However, each new idea that were being brought up kind of conflicted with eachother design-wise.
For example, we had an idea of travelling to each island as a png of a unit that exists there (bird, ferry, snake, human), but if we want the map to have lined connection based on the type of topics, these two wouldn't look well together.

So we decided to try to convey our vision of what the website would look like either through canva or other media.
We also made it a point to elaborate on these 4 points:
- Navigation
- Information Presentation
- Visual / Art
- Connections


I decided to do a little hand-drawn animation, because that felt quicker for me to explain, especially when I am focusing more on the technical aspects of it, as I promised to make the app scalable and easy for the client to add more information.

![Map Prototype](./images/mapPrototype.gif)


**Overview Map:**

you see all the "Port" Pins where you can spawn at

**Navigation:**

Click on the nodes to navigate towards them, clicking on it again will confirm and do things (land / open description)

**Information presentation:**
Nodes on an island can be color-coded to represent different types of Nodes:

    Ports
    Pollution
    Island Description
    Etc

These nodes' colors should remain consistent for all islands


When approaching a informational node, it will pop up a little sign and users can click on them to access the Description View.


**Visuals / Art:**

    Nodes (Colored Circles, maybe with a Letter inside (for the colorblind))
    Landing on an island changes your character image
    Description View:
        Vertical List of bubbles that changes the view
        Big Image
        Side description


**Connections:**

    Colored Nodes
        We can maybe try having colored nodes from different island connect to each other
    Port Nodes
        Some that are innaccessible by boat can probably use port nodes between islands



---


## WEEK 2: Brainstorming

For our first brainstorming task that we did together, we suggested that everyone take 20 minutes reading through all the given resources and write down what we felt was important to include in the project.

Some things that I noted down include:
- History of each Island
- Island
- Connections between islands
- Historical figures 
- Scalable app
- Local Fauna and Flora
- Pollution, Social Issues
- Zoom out node map?
- Connected segmented maps
- Big Map
- Landscape
- Notable Buildings / Infrastructure

We then took turns talking and elaborating about what we found important, and then drawing out an Interface that to get a clearer idea of how the project will look like.
Considering that the project description included a lot of references and a clear goal of an Interactive Map, our biggest concern is the scope and finer details of what our client wants.

Such as:
- Who are our target audience?
- What context will this be used in?
- Would they want it to be more artistic or education?
- Do they want it to be a downloadable app or web browser accessible? 
- Are they gonna provide us with information about the archipelago or will we have to plan for research time?
- Do they want a scalable Map (they can add more information themselves / reuse for other projects), or a fixed map for this specific project?
- Do they want to have different languages?
- Do they want all the island displayed or to follow along with a select amount, focusing on the story of a set of islands

We will probably have more to talk and do once we meet up with our client and have a clearer idea of what the project will look like.

![Brainstorm 1](./images/brainstorm1.jpg)
![Brainstorm 2](./images/brainstorm2.jpg)