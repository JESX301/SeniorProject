# SeniorProject
Simple data analytics app for college alumni statistics

Not the original repo, ripped from a zip file on my college laptop. All work was done using git and we pushed our work both from home and from the college linux lab. Using a version control framework was a part of the project requirements.

I managed building out the backend. We used WAMP, and using the MariaDB framework I created a database containing the names of schools, occupations, salaries, GPA's etc. to produce meaningful analytics using Node.js javascript graphics. 

Specifically I correleated all of these attributes with a StudentID (name) and a SchoolID (name). The difficult part was assigning these values meaningfully to show realistic analytics. Writing the actual sql involved taking the csv file I was using and running it through a converter script (because writing sql explicitly is insane). Using the sql code I had "written" on MariaDB I then built out the database. 

We used the laravel PHP framework. One team member generated all 2k+ lines of PHP, and another team member helped implement Node.js for the frontend. Backend is where I am strong, which is why I built out the DB
