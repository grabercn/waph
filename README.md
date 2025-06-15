# WAPH-Web Application Programming and Hacking

## Instructor: Dr. Phu Phung

## Student

**Name**: Christian Graber

**Email**: [mailto:grabercn@mail.uc.edu](grabercn@mail.uc.edu)

**Short-bio**: Christian Graber is a CS student at UC and enjoys software development.

![Christians's headshot](https://avatars.githubusercontent.com/u/22225722?s=96&v=4)

**Deployed Website on** [GitHub.io](https://grabercn.github.io/waph/index.html)

**Project Files on** [GitHub.com](https://github.com/grabercn/waph)


## Project 1 Overview (As Seen on Canvas)

### **General requirements (30 pts):**

* Create and deploy a personal website on GitHub cloud (github.io) as a professional profile with your resume, including your name, headshot, contact information, background, e.g., education, your experiences and skills (25 pts).​
* Create a link to a new HTML page to introduce this "Web Application Programming and Hacking" course and related hands-on projects (5 pts).

---

### **Non-technical requirements (20 pts):**

* Use an open-source CSS template or framework such as Bootstrap.
* Target this profile for your potential employer, and your page will be graded as a part of your job application.
* Include a page tracker

---

### **Technical requirements (50 pts):**

**Basic JavaScript code (20 pts):**

* Use jQuery and one more open-source JavaScript framework/library​ to implement JavaScript code introduced in Lab 2, including a digital clock, an analog clock, show/hide your email, and one more functionality of your choice. (5 pts each)

**Two public Web APIs integration (20 pts):**

* Ensure you include a disclaimer stating that the public/third-party services generate the generated contents below and that you are not responsible.
* Integrate the jokeAPI ([https://v2.jokeapi.dev/joke/Any](https://v2.jokeapi.dev/joke/Any)) with the `Any` category of joke to display a new joke in your page every 1 minute.
* Integrate a public API with graphics and display that graphic/image in your page. Examples: [https://xkcd.now.sh](https://xkcd.now.sh)

**Use JavaScript cookies to remember the client (10 pts):**

* If it is a first-time visit, display the message "Welcome to my homepage for the first time!"; otherwise, display the message "Welcome back! Your last visit was <the date/time of last visit>".
* Ensure that you update the `<the date/time of last visit>` value each time the same user visits (-2pts if missing).

---


## What I Learned: 
For this project, I learned how to style and craft a compelling, professional looking website. I also learned how to host my site on the internet (which is very cool) so others can see it. I figured out how to use Ajax to render images from the internet / APIs and put them on the page. I also improved my usage of styling, and CSS classes to make a performant but nice looking website. 

Additionally, I gained experience integrating third party APIs and handling asynchronous JavaScript. I also learned to manage user sessions with cookies. Working with frameworks like Bootstrap and jQuery helped me understand how to build responsive and interactive web pages more efficiently. Overall, this project enhanced my web development skills and gave me practical experience in deploying real-world applications.

## How I Completed Each Subtask
### **General requirements (30 pts):**
For these requirements, I simply created a new repo on GitHub, and went into the settings to ensure it was hosted on the Github.io site. After ensuring this worked, I found a nice w3 template with premade CSS profiles and classes, and made a simple mockup of the site using the same information from previous sites and our markdown headers. Lastly, I added a link to waph.html where the class information and page is on my site.

### **Non-technical requirements (20 pts):**

I used an open source w3 schools template that primarily relies of CSS classes. This made it simple to create a dynamic and nice looking page. To target to potential employers, I made sure to include my professional work history, skills, education, a nice headshot, and my contact information. The page tracker was also added on the sidebar using the Flag tracker.

### **Technical requirements (50 pts):**
**Basic JavaScript code (20 pts):**

For this task I mainly borrowed most of it from the Lab 2 html file that we had worked on earlier. I simplified and cleaned it a bit as well, but it remains largely the same. For the new javascript functionality, I implemented a Click to Download Resume button on the sidebar. This allows you to easily download my resume securely, to reduce spam. 

**Two public Web APIs integration (20 pts):**

I added a small disclaimer at the bottom of my first block on the site, in regards to the two implemented APIs. I made small changes to our existing JokeAPI calls to use the any category and recall it every minute on a timer to update the joke every 1 minute. I also added a Pokemon of the Day, which grabs data and a picture of a random pokemon and displays it. For the two public web apis you can use the input bar and buttons. I used the same AGE API, while I added another new API input call to the nationality API which guesses your Nationality based off name using Javascript. I found that one to be pretty cool.

**Use JavaScript cookies to remember the client (10 pts):**

For this task, I found a simple method online to create a cookie when the page is first visited and if there is not a cookie yet, to display that the user is new to the page. Now after that, it will get that cookie that has the last time the page was visited, and display that instead if it exists. It will also update that cookie each time the page is visited and after it is displayed. 