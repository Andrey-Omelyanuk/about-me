# Senior Full Stack Developer (Python/TypeScript)
## Andrey Omelyanuk 
- Location: Belarus, Brest
- Email: andreyomelyanuk@gmail.com
- Russian: Native
- English: Intermediate
- GitHub: https://github.com/Andrey-Omelyanuk
- LinkedIn: https://www.linkedin.com/in/andrey-omelyanuk-36904154/
- UpWork: https://www.upwork.com/o/profiles/users/_~01b1cfb09d499e00cb/


### Skills
    Python, Django, Django REST Framework, FastAPI, SQLAlchemy, Celery, SQL, PostgreSQL,
    Ansible, Docker, JavaScript, TypeScript, Vue, React, Angular, RxJs, MobX.

### About 
    I have been working remotely since January 2013 (9 years).

    TODO: I don't like it anymore, I have to rewrite it.
    Check my GitHub account, I have two own projects that you can be interesting: mobx-orm and  project-template. They are not perfect now but when you'll check it they can look better. 
    In the "project-template" I try to gather all my best practices. Unfortunately, I cannot spend a lot of time to finish but I have stable small progress on it.


# Experience

## Virtual Clarity 
https://www.virtualclarity.com/

June 2019 – Dec 2021 (2.5 years)

### Position
    Jun 2021 - Dec 2021 (0.5 years) Tech Lead Frontend Developer 
    Jun 2019 - Jun 2021 (  2 years) Senior Full Stack Developer

### Team
    5-7 developers.

### Tech stack
    Python, Django, SqlAlchemy, MSSQL, AWS, Docker, Typescript, Angular, RxJs, MobX, AgGrid.

### Responsibilities and Achievements
- Developing software that serves big corporations. 
- Sorry. I have a strong NDA and I cannot share more details about what I did.


## Zig 
https://zigtheapp.xyz

Sep 2015 – May 2019 (3.7 years)

The mix of task management and freelance platform.
The project was 80% completed before I left. 
The site is not available now but design still available [here](https://www.figma.com/file/PE70acTNcIgI1flYCqQUl4KQ/Zig-UI?node-id=791%3A10)

### Position
    Jun 2016 – May 2019 (2.8 years) Team Lead   Full Stack Developer  
    Sep 2015 – Jun 2016 (0.9 years) Senior      Full Stack Developer

### Team
    3-5 developers, 1 web-designer.

### Tech stack
    Python, Django, Django REST Framework, Celery, PostgreSQL, HTML, Pug, CSS, Stylus, JavaScript, TypeScript, Webpack, Angular, Vue.js, JSData, RxJS, Cordova, Ansible.

### Responsibilities and Achievements
- lead the team and the project
- everything that the project required except web design and things that I could delegate to other developers.
- TODO: add more details!!!!
- TODO: Mobile! android and iOS version
- TODO: external services like Senty, PubNub etc
- TODO: build architecture (microservices etc)

### More details
TODO: recheck the details

    I lead the project and I was team and tech leader.
    The project was started with Angular 1 and no data layer. When I joined, I split the project into two parts (back and front). This has facilitated the work of front-end developers (they know nothing about backend, they have only api now). Also, we started to use js-data https://www.js-data.io/v2.9/docs/home for the data layer, Pug instead of pure HTML and Stylus instead of pure CSS.
    Little later I tried to use TypeScript and I liked it and we migrated to TypeScript. It was very easy.
    After 2 year, I was disappointed with Angular 1 (terrible performance and I didn’t believe to Angular anymore) and we migrated to Vue.js (performance much better now! some tests showed boost up to x15).
    After Vue migration, I integrated MobX into js-data for reactivity.
    On the backend, I use Django + Django Rest Framework. These tools helped me to build REST API very quickly and effectively, actually only I worked on the backend, teammates worked only on the front-end. I had integrated the PubNub service for async messages from  back-end to front-end(web and mobile) like a new message in a chat or other user notifications. For long tasks that should be run in background, I used celery with rabbitmq broker. 
    I had no performance issues on the backend, all queries to DB were optimized by me, all tables used correct indexes. Actually, it was not a big win because I had not a lot of data, production DB had a ~400MB size and grew not too fast (~30MB per month).
    I have integrated Sentry to gather errors from users.
    Also, I have tried to split monolith into microservices. It should be auth and message microservices but the project did not get new round investments and was closed.


## Nord-Soft   
http://nord-soft.com/

Jan 2013 - May 2015 (2.4 years)

The outsource company.

### Position
    Jan 2013 - May 2015 (2.4 years) Senior Full Stack Developer

### Team
    1-7 developers.

### Tech stack: 
    Python, Django, Django REST Framework, Celery, PostgreSQL, Redis
    HTML, CSS, JavaScript, jQuery, Angular, Git, Mercurial, Bootstrap.

### Responsibilities and Achievements
- developed a lot of small/middle web projects 
- leading projects from scratch to final
- development software architecture
- development front-end and back-end
- deploying projects on servers

### Interesting tasks that I remember
- Video montage.

    A web application that makes a video from pictures and soundtracks.
    I used Celery to run a background job and FFmpeg for making a video.

- Optimized DB query.

    It was a company that repairs airplanes.
    They had a web application for counting repairs. 
    It was a very unusual DB schema, they used PostgreSQL table inheritance and it made a problem for performance. 
    I made the query faster ~20% using indexes but it still was not acceptable.
    The last option was to remove table inheritance and required a lot of time to refactor.
    The customer did not agree to make the refactoring and bought a more powerful server.


## System Technologies 
https://www.st.by/

Oct 2008 - Dec 2012 (4.2 years) 

Developing banking software.

### Position
    Jan 2010 - Dec 2012 (  3 years)   Middle Software Developer  
    Oct 2008 - Dec 2010 (1.2 years)   Junior Software Developer

### Team
    6-10 developers, 6 testers, 3 business analysts.

### Tech stack: 
    C++, MFC, T-SQL (Sybase).

### Responsibilities and Achievements
- developed reports for business (created SQL procedures and UI using C++)
- developed templates for new contracts and other business documents
- analyzed and optimized many heavy SQL queries (Production DB size is ~80TB)
- analyzed and fixed many deadlocks
- developed UI for new features using C++
- developed and maintained an internal tool for version control for Sybase using C++


# Education

## Brest State Technical University  
http://en.bstu.by/

Sep 2003 – Jul 2008 (5 years)

Bachelor's degree, Computer science
