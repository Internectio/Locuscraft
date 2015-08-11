# What is Locuscraft?
Locuscraft is a means for all internet users in the world to sort, rate, and review websites and information on the internet. It is also a means for individual users to personalize their internet experience, based on their own goals and interests, through a central, customized, user internet profile. Think Wikipedia meets Facebook meets Reddit. The best part of all is this will be free for everyone in the world.

Locuscraft's motto is "Learn. Built. Share." Why? Because this should be the order of creation. Locuscraft hopes to encompass all of these as a means to revolutionize the internet.

Currently I am creating Locuscraft using Django 1.9. I have already reserved the domain space locuscraft.com, .net, and .org. I am hosting the website with an Arvixe shared server, which also includes cPanel and unlimited mySQL databases. Once we get a decent user base and acquire dontations or funding, I will to upgrade the server to a dedicated server so we can handle a higher load of traffic.

# Site Planning Questionnaire

Who is the target audience?
The general public

How can I tailor the web site to reach that audience?
Make the website as instrumental, intuitive, and user friendly as possible so that anyone with any background or experience may use the website.

What are the goals for the site?
1. To create an organized and centralized hub of the internet's information and services. Locuscraft will help users find information and services on the internet through categorization, much like how one might find a product on Amazon by navigating to the department (or category) the product is in. User's will also be able to search by keyword of course.
2. To cater towards each user's interests and goals as much as possible, by providing them with an extensively customizable profile. This will allow users to better manage their time and utility while on the internet, as well as provide an entertaining, useful, go-to internet home. Whether the user's goal is to do research, to be entertained, to socialize, etc., Locuscraft should cater to and help the user accomplish this. Ways of accomplishing this will be discussed below.
3. To utilize user data for the good. Privacy is incredibly important, especially for a website that learns so much about it's users. This is why the software must be open source and viewable by anyone. Once privacy is accomplished and ensured, user data can be collected either anonymously or at user discretion, then publicized, used for research, or other purposes. For example, there will be many tasks related to the user's opinion of something. This information will be collected and shared so users can see the general consensus about a topic, company, product, etc. This could be a revolution in gauging public opinion.
4. To build a large and dedicated user base. None of the other goals are possible without the help of many, many users. In order to make the website more engaging and make users come back, we must give users great utility, and use some psychology. Users will be able to subscribe to interests (basically any category) and create goals. User's will earn points by completing tasks related to their interests and goals. More details below.

How will the information be gathered?
All of the information will come from the users. All we (the developers) have to do is create the interface that the users will use. Then the users will take care of information categorization and organization (tongue twister there). Information could come in the form of links, multimedia, and text. It could come from references to websites, profile information (based on privacy settings), polls they have answered, uploads, and maybe other sources. Tasks and points for those tasks will be the main driving force for gathering this information. User's will acquire tasks from interests or tasks feeds they've subscribed to. They will see all of their tasks in a task feed on their home page. A task could be a question about something, it could be to confirm that something is true, to watch a video, to click a link, to complete something, help someone, create something, or anything else the users can come up with. Once the task is complete they will acquire locus points if the task helped them, community points if it helped everyone else, or both if it helped both.

What are my sources for multimedia content?’
Right now, I am creating all the multimedia content myself, or creating different images using free stock images from the internet and modifying them. I have done this with the logo and background images on the front page.

What is my budget?
My own pocket for the time being. I am open to donations and would like to expand if I acquire enough.

How long do I have to complete the project?
I will work on this as long as it takes, but I would like to get it going ASAP. Currently, working by myself, it could be a year before I have a basic usable user interface for the website. I am still learning how to use Django. The more people we get working on this, the sooner it will revolutionize the internet.

Who is on my project team?
No one yet. I would love to hear from anyone who has experience programming and wants to help. Also if you have constructive criticism or a suggestion for the project, I would like to hear it.

How often should the site be updated?
Probably daily but that is down the road.

Who is responsible for updating the site?
Just me for the time being.


# More about my Plan
When a person creates a new profile, they will be subscribed to a default list of interests/categories. This list will include questions/tasks such as the following:
•	What is your favorite color?
•	When is your birthday?
•	List five of your favorite shows.
•	What was the last show you watched?
•	What is your favorite cuisine?
•	Do you have any pets?
•	If yes > Select the kind of pets you have on this list.
o	There will be a list of the most common types of pets (dogs, cats, birds, rodents)
o	These options will have subcategories of the species/breed of animal they have and it will also ask the number of each that they have.
To make people feel more productive and less like they are simply doing a survey, the website will also ask the person about things they should be doing, things they need, things they want, etc., then have them do tasks in order to get closer to reaching their own goals. 
For example, there could be a fill in the blank type question that could say… “I need a new ___.” If the user were to put in “vacuum”, then the website could ask the user questions about vacuums specifically, such as “how much money are you willing to spend?” “Which of the following criteria are important? Functionality, looks, price, …” The website could then ask them to research vacuums online, find the one they want, and copy and paste the link onto their profile. Then this person will have a list labelled “Things I Need”. Under this list will be a vacuum along with a link to the one they chose. Completing a series of questions/tasks like this will give them a good amount of points.

Privacy Options
You have the option of sharing your information with the world (you can share anonymously) or keep your information absolutely private and do this just for you. A simple and honest privacy policy will need to be created.
Options:	Share with the World!		Don't share.
		 /                 \
        Share anonymously      Share openly

Site Navigation
•	Home
Home must be the users’ base. It must display everything important to the user, including their tasks, and remind them of their goals. New users’ homes will display suggestions for where they should start. Users who have goals already will have a sort of “feed” listing their daily tasks, things they need to work on, etc. There will be an option at the top right corner of every task saying “Not now”. If the task is marked as urgent, or if the due date is upcoming soon, a warning message will appear notifying them and they will have two options: “I know” (continue) or “Okay, I’ll do it”. If this turns out to be annoying, it might be changed.
Possible Organization of the Homepage:
o	Craft your Locus
Here is where Locuscraft will learn about the user and make suggestions.
o	Daily Tasks
These will be fully customizable by the user. They can be completed in a short amount of time, completed on a daily basis or regular basis, or are scheduled for the current day. Locuscraft will have a database of tasks for the user to choose from. For specific tasks that have not yet been created in the database, users will be able to create their own and set it's parameters. For some of them, progress will be measurable in some way. For others, they will simply be set as completed or incomplete. Regular Basis Examples:
	Answer profile questions.
	Voice my opinion. Answer top survey questions; could be based on subscribed categories; could be random.
	Watch a video on Khan Academy. This could be checked off after linking to Khan Academy or perhaps profile information from Khan Academy could be sent to Locuscraft through a partnership.
	Look on Reddit for 20 minutes. Locuscraft will set a timer then alert after 20 minutes.
	Watch the news. Users will be able to link their favorite news source.
	Add a task (find tasks - this will be similar to the way Facebook finds music or movies to add to your profile. Other users will have tasks and in order to link public tasks that are the same, users will select tasks from a list or create a completely new one.)

If the user has not added any tasks yet, Locuscraft will make suggestions for where they should start. Some examples:
	Make a calendar
•	Either link an existing calendar or create a new one
•	Add important birthdays to remember
•	If you are in school do you have homework due dates or upcoming exams?
•	If you are working, do you have jobs to complete?
	Make a list of personal goals
	Start a journal
	List things you think you should be doing every day. Example:
•	Work 8 hours
•	Exercise for 45 minutes
•	Cook
•	Meditate for 15 minutes
•	Write in my journal
•	Craft my locus for 30 minutes (answer questions or complete tasks on Locuscraft)
•	Watch one show
•	Play video games for 1 hour
•	Sleep for 7.5 hours
o	Projects/Long-term tasks. 
These will be tasks that take a while to complete, that cannot be completed in one day, or that have multiple sub-tasks. Some examples of this might be:
	Fix lawn mower
	Create diet regimen
	List things to do around the house
o	What’s Popular Today
o	Browse
	Categories
	Recommended
•	My Profile
o	My Goals
The user will be able to view their current goals, add to them, or change them here.
o	My Interests
The user will be able to view a list of topics they are interested. These will be categories listed on the website and subscribe them to these categories.
o	Information about me
This will list questions the user has answered. The user will be able to edit their answers. They will be listed in a format such as:
Favorite color:	Blue
Favorite movies:
•	2001
•	Blade Runner
•	Pokémon
•	Ask a question/Set a task (Ask the public?)
•	Search
•	Browse
o	The World’s Favorites (basic information about Locuscraft users)
	Favorite Colors (e.g. 32% blue, 24% green, etc.)
	Favorite Shows
	Favorite Restaurants
o	Shopping Guides (browse reviews of products, see recommendations, etc.)
o	Public Opinion
Organized by:
	Hot (like Reddit’s formula)
	Top
	New
	Random
•	About Locuscraft

Tasks
Tasks will vary in many different ways. A user should be able to put any task they please, however in order to receive points for completing a task, the task will probably need to be in Locuscraft’s database.
Tasks will have different states. Possible states:
•	Not started
•	In Progress
•	Complete
•	Removed (?)
•	Failed (?)
Tasks might be measured in different ways, such as:
•	Timed - a timer will start once a page or file is open and continue timing while it is open. Once the timer run outs, the task will be marked as complete.
•	A certain number of words must be written
•	A certain number of list items must be given
•	A certain answer may need to be given
•	Any answer must be given
•	A “finished” bit sent by third-party tasks
To prevent people from cheating, certain measures must be taken. People need to be honest in order for the site to be a good source of information. One way of enforcing this is to spell check all text and make sure all words are in their dictionary. In case there are real words that aren’t in their dictionary, they will have the option of adding the word still. When people just type gibberish though, it will be more of a pain to type gibberish than to write something coherent.
Another way to prevent cheating is to have other people read their answers and validate that they make since in context to the question. This could be tricky.




The two main focuses of Locuscraft
Your Locus
Your Locus is the part of Locuscraft that centers around your life, your personality, your interests, and your goals. Here you have full control over what Locuscraft does for you. Your Locus consists of: 
•	Goals: Set Goals you want to accomplish in your real life. 
•	Interests
•	Tasks
•	Customization
The Community
The Community is where we make use of the collective brainpower and opinions of everyone. This is where we will shape the internet to become a truly useful place for all human beings. The Community consists of:
•	Opinion: There will be polls on everything whether its about current events, companies, policies, or simply what you want, we all want to know what everyone really thinks!
•	Categorization: This is where we will really organize the information on the internet, bringing together all related information in a wiki style of organization.
•	Reviews



Users will have the option of sharing their information publicly, rather than anonymously, and entering a leaderboard that displays which users have collected the most points in various categories. Other users will be able to look at the profiles of users set to publicly share their information similar to Facebook’s privacy settings.

To make use of the plethora of information already available on the internet, I think it will be important to partner with other websites and organizations to make their resources available to Locuscraft users. For example Khan Academy could be one such website that could help users complete tasks relating to subjects on their website.
