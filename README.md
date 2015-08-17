# What is Locuscraft?
Locuscraft is a means for all internet users in the world to browse, sort, rate, and review websites and information on the internet. It is also a means for individual users to personalize their internet experience, based on their own goals and interests, through a central, customized, user internet profile. Think Wikipedia meets Facebook meets Reddit. The best part of all is this will be free for everyone in the world.

Locuscraft's motto is "Learn. Build. Share." Locuscraft hopes to encompass all of these as a means to revolutionize the internet.

Currently I am creating Locuscraft using Django 1.9. I have already reserved the domain space locuscraft.com, .net, and .org. I am hosting the website with an Arvixe shared server, which also includes cPanel and unlimited mySQL databases. Once we get a decent user base and acquire dontations or funding, I will to upgrade the server to a dedicated server so we can handle a higher load of traffic.

# Locuscraft Site Map

Please view the [site map](https://cloud.githubusercontent.com/assets/11935672/9317205/bcc63562-44ff-11e5-85bd-9766431f23d1.png) to get a visualization of the website.

# Site Planning Questionnaire

*Who is the target audience?*

Everyone. Ideally Locuscraft would become a tool that improves everyones day-to-day utility of the internet.

*How can I tailor the web site to reach that audience?*

Make the website as instrumental, intuitive, and user friendly as possible so that anyone with any background or experience may use the website.

*What are the goals for the site?*

1. To create an organized and centralized hub of the internet's information and services. Locuscraft will help users find information and services on the internet through categorization, much like how one might find a product on Amazon by navigating to the department (or category) the product is in. User's will also be able to search by keyword of course.

2. To cater towards each user's interests and goals as much as possible, by providing them with an extensively customizable profile. This will allow users to better manage their time and utility while on the internet, as well as provide an entertaining, useful, go-to internet home. Whether the user's goal is to do research, to be entertained, to socialize, etc., Locuscraft should cater to and help the user accomplish this. Ways of accomplishing this will be discussed below.

3. To utilize user data for the good. Privacy is incredibly important, especially for a website that learns so much about it's users. This is why the software must be open source and viewable by anyone. Once privacy is accomplished and ensured, user data can be collected either anonymously or at user discretion, then publicized, used for research, or other purposes. For example, there will be many tasks related to the user's opinion of something. This information will be collected and shared so users can see the general consensus about a topic, company, product, etc. This could be a revolution in gauging public opinion.

4. To build a large and dedicated user base. None of the other goals are possible without the help of many, many users. In order to make the website more engaging and make users come back, we must give users great utility, and use some psychology. Users will be able to subscribe to interests (basically any category) and create goals. User's will earn points by completing tasks related to their interests and goals. More details below.

*How will the information be gathered?*

All of the information will come from the users. All we (the developers) have to do is create the interface that the users will use. Then the users will take care of information categorization and organization (tongue twister there). Information could come in the form of links, multimedia, and text. It could come from references to websites, profile information (based on privacy settings), polls they have answered, uploads, and maybe other sources. Tasks and points for those tasks will be the main driving force for gathering this information. User's will acquire tasks from interests or tasks feeds they've subscribed to. They will see all of their tasks in a task feed on their home page. A task could be a question about something, it could be to confirm that something is true, to watch a video, to click a link, to complete something, help someone, create something, or anything else the users can come up with. Once the task is complete they will acquire locus points if the task helped them, community points if it helped everyone else, or both if it helped both.

*What are my sources for multimedia content?*

Right now, I am creating all the multimedia content myself, or creating different images using free stock images from the internet and modifying them. I have done this with the logo and background images on the front page. I am somewhat particular about the style of the website. I feel that it should be awe-inspiring and give people a sense of discovery the moment they see the front page. The interface should be minimalistic and uncluttered to make it as easy as possible to navigate and understand.

*What is my budget?*

My own pocket for the time being. I am open to donations and would like to expand if I acquire enough. I would like to have enough income from this project to make it my full-time job and move out of the house I am living in, but if you would like to contribute for a specific purpose, such as some internet service or dedicated servers, I'm sure we can arrange it.

*How long do I have to complete the project?*

I will work on this as long as it takes, but I would like to get it going ASAP. Currently, working by myself, it could be a year before I have a basic usable user interface for the website. I am still learning how to use Django. The more people we get working on this, the sooner it will revolutionize the internet.

*Who is on my project team?*

No one yet. I would love to hear from anyone who has experience programming and wants to help. Also if you have constructive criticism or a suggestion for the project, I would like to hear it.

How often should the site be updated?

Probably daily but that is down the road.

Who is responsible for updating the site?

Just me for the time being.


# More about my Plan

Note that this is a bit outdated. I am working on writing the updated plan.

##Entries

Locuscraft entries are similar in nature to a Wikipedia entry. What is meant by entry is simply a subject/article/category of information, such as an entry about apples. Wikipedia was a revolutionary creation for the internet. It made paper encyclopedias obsolete with its plethora of encyclopedia based knowledge that its users, not the Wikimedia Foundation, added to the website. What can Locuscraft use from Wikipedia's example? What can Locuscraft bring to the table? 

Take a look at the [entry for Apple on Wikipedia](https://en.wikipedia.org/wiki/Apple). It contains a vast amount of information about the simple fruit including its history, cultural aspects, cultivation, nutrition and then some. Similarly to Wikipedia's article for the apple, Locuscraft will have an entry likely with a table of contents with similar information. What does Wikipedia lack for the apple that the internet has, or could have? How about recipes? How about what people think about apples? How about a forum on the subject? Videos, pictures, and other multimedia? Where to buy apples on the internet? Locuscraft's purpose is to bring the internet of information about a subject into one central place. This is specifically the purpose of the entry. At the moment, Locuscraft entries will include the following:

* Basic, need-to-know, information about the subject, followed by an expandable section of additional, useful, common and uncommon information about the subject, followed by the best places (websites) on the internet to learn more about the subject.
* Latest news on the subject.
* If the subject is related to a discipline or art, there will be a guide for learning that art. In the case of apples, this could be recipes or cultivation.
* Videos, pictures, and other multimedia of the subject found on the internet.
* Locuscraft user statistics relating to the subject (such as users' favorite apples, percent of user's that like apples, etc.).
* User created tasks (more about tasks below) for the subject (such as watch a video about the subject, write your opinion about apples, answer a questionaire or poll about apples, etc.)
* A list of communities/organizations/clubs relating to the subject.
* A list of other subjects closely related to the subject.
* Forums on the subject.
* The ability to add the subject to your interests.

All of this vast amount of information for each entry needs to be well organized, and the user should be able to further organize, or filter the information the way they want. Each division/bullet point should be orderable in different ways (similar to how posts on Reddit can be ordered), where appicable, such as: newest; "hot"; top posts by hour, day, week, month, year; rising, etc. There will also be a search bar which allows you to quickly search for information within the subject.

##Categorization

Locuscraft should very much be a place of discovery. The first word in our motto is "learn". If you don't discover new information, then your learning is limited to things you already know about. Google is amazing and makes good information on the internet findable. The problem is, you have to know, or at least have an idea of what it is you are searching for. The purpose of categorization is to make entries you might be interested in more easily discoverable, by throwing them into branches you already have an interest in. An excellent example of categorization is Amazon's "shop by department". It breaks every product on their website down into categories. A user like myself might just go to "Electronics & Computers" then click "Wearable technology" and discover products I never knew existed. After clicking this, you can break the department down into even narrower sub-categories. Why not do this with the internet's information too? If we value the internet so much, why shouldn't we pitch good information and sell it to internet users the same way Amazon markets its products to customers? I can't think of a better way to educate people, than to make them want it, give them free range, and make it free.

Categories will be hierarchical, meaning there will be top-level and bottom-level categories. 

###Top-Level Categories

There is so much information on the internet. How can we possibly categorize it all? Well it isn't hard if we make it broad enough. I have come up with the following top-level categories:

* Subjects - These include basically anything you would find on Wikipedia, minus any articles about a specific product. It could be people, places, ideas, companies, etc. These entries will include information laid out in a similar way to the apple example above.
* Products - These would be basically anything you would find on Amazon. They will be laid similarly to subjects but with more of a focus on the quality of the product, where to buy the product, reviews on the product, etc. They will include something similar to the following:
  * Basic, need-to-know, information about the product, followed by an expandable section of additional, useful, common and uncommon information about the product, followed by the best places (websites) on the internet to learn more about the product.
  * Latest news on the product if applicable.
  * A list of subjects related to the product
  * Videos, pictures, and other multimedia of the product found on the internet.
  * Locuscraft user statistics relating to the product (users' preferences on the category of products, number of users with an interest in that product, etc.)
  * User created tasks (more about tasks below) for the subject (such as write a review about the product, answer a poll of where you buy products in a category, etc.).
  * A list outlets that sell the product, ordered by cheapest, most reliable, most consumers, etc.
  * Reviews on the product, including reviews from other websites.
  * Buying guides for the product. Using vacuums as an example, you should be able find the best vacuums in different price tiers, with different functions, reliability, durability, portability, etc.
  * The ability to add the product to your interests.

Locuscraft will hopefully become a source for unbiased product reviews and buying guides for any and all products. Product entries will be different than subject entries, as they will be focused on the quality of the product, sources of the product, reviews of the product, etc.
* Sponsored - This could be a good source of revenue for Locuscraft. I'm sure some organizations or communities would like to create their own entries that target their consumers or members. These organizations would have full control over their entries including the tasks, what Locuscraft users can change or add to the entry, forums, and anything else associated with entries. There would be different price tiers, each tier changing the visibility of the entry to Locuscraft users. As an example, say McDonald's buys a sponsored entry. Users can then earn points by completing McDonald's tasks which might include a survey of what people think of McDonald's food. This could be an unbiased source of data about consumers and their opinons of McDonalds.

###Low-Level Categories

These will applied with tags, like people might put keywords for a photo. 






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
