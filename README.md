## Applicant Test

This test is intended to go over a broad array of topics ­ without paying too much attention to each detail. It should also demonstrate learning new things quickly.

###Frontend
You’ve been asked to build a simple site, and handed a wireframe:

![wireframe](/images/wireframe.jpg)

You need to show the homepage on desktop browsers and a phone for the client review. You can use placeholder images for now. The mobile version should collapse down to fit on screens as narrow as 320px. The client changes their mind often, so it should be very easy to change colors and type styling – you’ll probably want to use SASS/SCSS, and a mixin library might help with some of the cross­browser differences.

###Backend
Your client is indecisive and must change the name of the company every day at will. You’ve decided a minimal backend will be needed so the change can be done quickly without writing code. Pick your favorite python based web framework. Create a small backend that:
* Stores the name of the company in a database
* Features either a api or view that shows retrieving the name from the database
* Follows [pep8](https://www.python.org/dev/peps/pep-0008/) style guidelines
Explain all choices made and why you might do this in a real project ­ or maybe you just wanted to play with something new.

###Devops!
Your team uses different operating systems and you need to share the project with them easily.
Use [docker](https://docs.docker.com/) and [docker-compose](https://docs.docker.com/compose/) to run the application. The web server, database, and anything else needed is up to you. The goal is that when someone receives the program they can run it easily without having to set up anything besides docker/compose. Check out the [django example](https://docs.docker.com/compose/django/) and notice how once compose is installed I can just type “docker-compose up” and it works.

After doing this briefly explain what you like and/or dislike about using docker.

###The Deliverable
Push your work up to your fork of this repo. We should be able to run “docker-compose up”, maybe run any extra commands you give us, then go to a web browser and see the finished site. Include a 'notes.md' file with your answers/notes for the above questions.
