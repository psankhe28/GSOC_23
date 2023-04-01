Hey, my name is Pratiksha Sankhe and I study at VJTI in Mumbai. This is the first time applying for GSoC. After researching a wide range of organisations and learning about their initiatives, I discovered the "*Collection and Study Management*" project of **caMicroscope** to be pretty fascinating.

## Getting Started

I joined Slack and began delving more into the projects. I finished the setup locally and started working on the coding challenge task listed under my project. This blog will summarise my approach to finishing the code challenge assignment.

## Getting Warmed up
Each project included a code challenge assignment for new contributors to demonstrate their inventiveness, comprehension of the topic, and ability to execute on a project proposal. I, too, began to comprehend and apply it.

### 1. Building caMicroscope and running it locally
- First I followed the [Getting Started](https://github.com/camicroscope/caMicroscope#hosted-setup) section on caMicroscope's repository, which involved installing it using docker. I was able to successfully build and test its working on my PC.
- Then, I started exploring the different pages and finding bugs in the pages of [caMicroscope](https://github.com/camicroscope/caMicroscope) repository and [camicroscope.github.io](https://github.com/camicroscope/camicroscope.github.io) repository.
-  Following are the PRs that I have raised to date:

     In [camicroscope.github.io](https://github.com/camicroscope/camicroscope.github.io):<br/>
    ● [Scroll to top feature added](https://github.com/camicroscope/camicroscope.github.io/pull/22)<br/>
    ● [Improved the Index and the Community Page](https://github.com/camicroscope/camicroscope.github.io/pull/23)<br/>
    ● [Changed link of navbar](https://github.com/camicroscope/camicroscope.github.io/pull/27)<br/>
    ● [Created README](https://github.com/camicroscope/camicroscope.github.io/pull/28)<br/><br/>

    In [caMicroscope](https://github.com/camicroscope/caMicroscope):<br/>
    ● [Landing page UI modified](https://github.com/camicroscope/caMicroscope/pull/619)<br/>
    ● [Fixed UI of admin page](https://github.com/camicroscope/caMicroscope/pull/620)<br/><br/>

### 2. A simple webapp demonstrating CRUD operation
- As I already made similar application using MERN Stack which performed CRUD operations, this was a fairly easy task for me.I created a react-app and then installed the dependencies required for creating stories.
- I started by going through the [Getting Started](https://storybook.js.org/docs/react/get-started/install/) section on storybook's website, which included installing dependencies and documentation. I read through all of the documentation on the website and became acquainted with it.
-  To use the storybook in a react application, I created a react-app and then installed the dependencies required for creating stories.
  ```
  npx create-react-app notebook
  ```
- I decided to create a 'backend' folder and initialize the application.
  ```
  npm init -y
  ```
- My next target was to build models for User and Notes.
- For authentication, I made use of jsonwebtoken and bcrypt.js for hashing passwords.
- The next step which I performed was created the routes for authentication as well as notes which included POST, GET, PUT and DELETE requests.
- Finally I created routes and tested it. Tadaa! Everything was working fine.
- The backend was running smoothly and now the only part remaining was frontend.
- For keeping things simple, I used Bootstrap and use the already built forms for signup, login and adding and updating notes.
0I used the navbar which was already available in Bootstrap.
- To connect the backend with frontend, I made use of Context and using it, I successfully completed the task.
- A cloud-based note application was created successfully.
- [GitHub](https://github.com/psankhe28/notebook)
- [Hosted application](https://storybook2023.netlify.app)


<br>

### 3. Creating URL Storing Website - UrlSafe
- After reading about project description and creating a simple CRUD operation website, I thought of creating a website which somewhat is a mini version of our project.
- So, I decided to make a website which utilizes the concept of collection and tags and I came up with the idea of UrlSafe.
- UrlSafe is a bookmark + archive manager to collect, and save websites for offline use.
- Some of the key features are as folows: <br/>
    ● Sleek, minimalist design<br/>
    ● 🌤 Dark/Light mode support<br/>
    ● ↔️ Responsive design<br/>
    ● 🔎 Search, filter and sorting functionality<br/>
    ● 🏷 Set multiple tags to each link<br/>
    ● 🗂 Assign each link to a collection where we can further group links<br/>
- In "*Collection and Study Management*" project too, we have to implement collection and tag feature which would be similar to this..
- This website is built using MERN Stack.
- [GitHub](https://github.com/psankhe28/url-safe)
- [Demo Video](https://drive.google.com/file/d/1Xxid1e_21QboV5qEOD8416jSBDrxmxtJ/view)

<br>
 
