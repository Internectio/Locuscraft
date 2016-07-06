# What is Locuscraft?

A website built for everyone and by everyone. Locuscraft's aim is to bridge the gap between information and people. Locuscraft aims to be globally used as an open source, decentralized medium of information sharing and creation through individual and collaborative efforts, with the use of open source tools, a user-friendly interface, and data architecture centered around and voted on by its users.

Locuscraft's purpose is to maximize human awareness. Today, disinformation is rampant in the media, but at the same time there is explosive growth in information sharing on the internet. I believe there is great untapped potential in the way and the extent to which we can share information and learn information on the internet. We can take awareness to the max by bridging the gap between the source of and consumer of information. We can create a central, globally unified repository of information, that is not filtered through third parties, in order to create a reliable, universal, and truthful information hub for everyone in the world.

Information on Locuscraft will come in the form of entries, which are similar to Wikis with increased functionality and more *kinds* of information. Each entry represents a topic, and every entry will house several tools/outlets for sharing all corners of information for that topic. The best part is, any user can add to entries, share them, edit them, create new ones, or browse them. Every Locuscraft entry has its own:

 * Posts (similar to Reddit posts)
 * Forums
 * Community tasks (more on this later)
 * The best sources relating to the entry
 * Guides
 * Reviews/Ratings
 * and more

Why should you care about this idea? As Steve Jobs said, we should take the best and spread it around "so that everybody grows up with better things".

1. **Everyone will have control** over all of the content on Locuscraft.
2. **Maximum organization and efficiency** in finding the information you want.
3. **Global awareness** - since high quality, personalized information will be visible on everyones' homepage; since everyone will contribute information from all walks of life; and since there will be no borders.
4. **Global reviews** - every entry, and it's posts, tasks, comments, and guides can have a rating. The highly rated stuff will be highly visible while low ratings will be at the bottom. 
5. **Community tasks** will be the driving force for the creation of new information on the website among other things. Read about them below.

In additon to these reasons, there will be **no CEO's**, **no advertisements**, **no profiteering**, and **no borders**. The **privacy policy**, too, will be created by the users and centered around the user's needs.

Below is a sample of what a user's homepage might look like.


![](https://cloud.githubusercontent.com/assets/11935672/10345112/e64f0746-6cec-11e5-86ba-231b8815e937.png)

As you can see, there is also a "My Tasks" section. This section is for individual endeavors. Users can make any task they want, and can even share them to create a repository of tasks other users can choose from. Tasks may be in the form of a list or a timeline; may include goals, to-do lists, reminders, etc.

# Why Locuscraft?

Compare the internet with the human brain for a moment. Each human on the internet is like one neuron in a brain. Like the brain, the internet is a vast network connecting each neuron (human) to each other. Both the internet and the human brain have memories and emotions. The human brain is actually more sophisticated though, with more than simple memories and emotions.

Humans have this part called the frontal lobe which controls the executive functions of the brain, the part of the brain responsible for planning, decision-making, intellect, behavior, attention, abstract thinking, coordinated movements, and personality. Besides the small amount of scattered working memory that websites like Reddit have given the internet, the internet's frontal lobe is virtually non-existant. Humans on the internet cannot make decisions on a global level, we cannot globally pay attention to important things happening in the world, and we cannot coordinate our actions. In other words, the internet doesn't really work as a singular organ, and instead still works at the cellular level where every cell is fighting for its own survival.

John Lennon sang it, monks have been saying it for millenia - **we must be as one**. We are one species on one tiny planet in one massive universe. We have bigger problems! Thankfully, the greatest human invention ever created for sharing ideals and uniting humans has just been created - the internet. 

**The internet (humanity) needs a singular unified thought process, an attention span, a higher level of awareness, and the ability to make decisions (the correct ones) at a global level.**

This is what the Locuscraft project aims to provide for the internet and the world.

Also, if anyone is interested I have answered a short [site planning questionaire](https://github.com/Zachcraft/Locuscraft/issues/2). It seemed a bit redundant so I decided to link it here, rather than write it up in this readme.

##Locuscraft To-Do List

* Make this list more detailed.
* **The interface for the website**, front-end and back-end. The question is how should it be built? I was thinking about using Django for this. My ideas for the details of the interface are outlined below, under "Locuscraft Plan".
  * Develop the basic structure of subject entry pages. The initial framework for entries can come from the "Wiki".
  * Create a few starter subject pages to be used for the User Homepage.
  * Develop the User Homepage including user's post feed, community task feed, My Tasks, and user sidebar.
  * Create the default categories all new accounts will have in their interests.
* **A Privacy Policy.** This is important and I know nothing about writing a privacy policy.
* **Spread the word.** This is what I'm working on now. If you know any online communities or other outlets we could share this with, please do so or let me know!

# Locuscraft Site Map

This is a basic navigational map of the website for your reference. It is not comprehensive and may change.

![](https://cloud.githubusercontent.com/assets/11935672/9947312/d9994216-5d5e-11e5-92eb-5a57ff8cbe41.png)


# Locuscraft Plan

##Navigation Bar

The navigation bar is critical to Locuscraft's user friendliness. It must be intuitive to use and provide quick access to everywhere else on the site. The navigation bar excludes logged in users' information. It is the navigation for all users logged in or out. 

The navigation bar at the very least will have the "home" link to the Locuscraft front page, and a search bar. The search bar could have a category drop down to search by category (like Amazon's search by department).

The rest of the navigation bar is dependent on the functionality of Locuscraft. There needs to be a way to browse Locuscraft's entries in a variety of ways i.e. by category, popularity, featured, etc. There's products, subjects, and sponsored.

**Discover**
* Subjects
  * [Wikipedia Category Structure](https://en.wikipedia.org/wiki/Portal:Contents/Categories) or [Web Directory Structure](http://botw.org/)
  * Hot
  * Top Viewed
  * Newly Added
  * Random
  * Featured
* Products
  * [Amazon Category Structure](http://www.amazon.com/gp/site-directory/ref=nav_shopall_fullstore)
  * Most Purchased
  * Most Viewed
  * New
  * Recommended
  * Highest Reviews
  * Featured
  * Buying Guide
* Sponsored
* Entertainment
* News
* Games
* Tools

**Create**
* A Post
* A Task
* New Project
* New Entry
* Art
* Get Inspiration

**Share**
* A Post
* A Task
* Help With a Project
* Help Someone
* Donate

##Entries

An entry is simply a subject/article/category of information, such as an entry about apples. Locuscraft entries are similar in nature to Wikipedia entries, but with additional kinds of information, detailed below. Like Wikipedia, Locuscraft will rely on its users to create the entries.

There are of course different kinds of apples. You might ask how Locuscraft would differentiate between Apple, the company, and apple, the fruit. This would work exactly the same way it does on Wikipedia. There will be separate entries for each kind of apple, and there will be pages like [this](https://en.wikipedia.org/wiki/Apple_%28disambiguation%29) showing all of them when searching.

Take a look at the [entry for Apple (the fruit) on Wikipedia](https://en.wikipedia.org/wiki/Apple). It contains a vast amount of information about the simple fruit including its history, cultural aspects, cultivation, nutrition and then some. The Locuscraft entry will have this *kind* information *about* apples under a "description" section. So what other kinds of information are there for apples? How about recipes? How about what people think about apples? How about a place to comment on the subject? Videos, pictures, and other multimedia? Where to buy apples on the internet? Locuscraft's purpose is to bring the internet of information about a subject into one central place. This is the purpose of Locuscraft entries. At the moment, Locuscraft entries will include the following:

* Basic, need-to-know, information about the subject, followed by an expandable section headings (like Wikipedia headings) of additional,  information about the subject, followed by the best places (websites/resources) on the internet to learn more about the subject.
* Latest news on the subject.
* If the subject is related to a discipline or art, there will be a guide for learning that art. In the case of apples, this could be recipes or cultivation.
* Videos, pictures, and other multimedia of the subject found on the internet (filterable and sortable).
* Locuscraft user statistics relating to the subject (such as users' favorite apples, percent of user's that like apples, etc.).
* User created community tasks (more about tasks below) for the subject (such as opinion polls, create a header image, add information to the apple entry, etc.)
* A list of communities/organizations/clubs relating to the subject.
* A list of other subjects closely related to the subject.
* Forums on the subject.
* The ability to add the subject to your interests.

All of this vast amount of information for each entry needs to be well organized, and the user should be able to further organize, or filter the information the way they want. Each division/bullet point should be orderable in different ways (similar to how posts on Reddit can be ordered), where appicable, such as: newest; "hot"; top posts by hour, day, week, month, year; rising, etc. There will also be a search bar which allows you to quickly search for information within the subject.

###Categorization

Locuscraft should be a place of discovery. The first word in our motto is "learn". If you don't discover new information, then your learning is limited to things you already know about. Google is amazing and makes good information on the internet findable. The problem is, you have to know, or at least have an idea of what it is you are searching for. 

The purpose of categorization is to make entries you might be interested in more easily discoverable, by throwing them into branches you already have an interest in. An excellent example of categorization is Amazon's "shop by department". It breaks every product on their website down into categories. A user like myself might just go to "Electronics & Computers" then see "Wearable technology" and discover products I wouldn't have seen otherwise. After clicking this, you can break the department down into even narrower sub-categories. Why not do this with the internet's information too? If we value the internet so much, why shouldn't we pitch good information and sell it to internet users the same way a retail outlet would market its products to customers?

Categories will be hierarchical, meaning there will be top-level, mid-level (possibly multiple), and bottom-level categories. Categories are used to give users another way to browse, find, or discover entries. Let's say a user is looking to buy a new chainsaw as an example. It could be navigated to like this: 

Products > Patio, Lawn, & Garden > Lawn Mowers & Outdoor Power Tools > Chainsaws

This is actually how you would find a chainsaw on Amazon.com.

####Top-Level Categories

There are three top-level categories at this time: Subjects, Products, and Sponsored.

#####Subjects

These include basically anything you would find on Wikipedia, minus any articles about a specific product. It could be people, places, ideas, companies, etc. These entries will include information laid out in a similar way to the apple example above.

#####Products

These would be basically anything you would find on Amazon. They will be laid similarly to subjects but with more of a focus on the quality of the product, where to buy the product, reviews on the product, etc. They will include something similar to the following:

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
  
#####Sponsored

I've included this category as a potential source of revenue for Locuscraft. 

Some organizations, communities, or individuals would surely like to create their own entries that target their consumers, members, or anyone else; or maybe they want to make a personal entry just for fun. For whatever reason, these groups/individuals will be able to buy a sponsored entry. Names for sponsored entries must be approved in order to confirm the individual/group has the right/trademark to that name (maybe?).

Sponsored entries come with their own perks that other entries do not. Sponsored entries will be linked to a locuscraft account, and that account will have admin like privileges over that entry. These privileges include full control over the tasks; whether the entry is open to the public or requires private membership; what Locuscraft users can change or add to the entry, or forums; and anything else associated with entries.

There will be different price tiers, each tier changing the visibility of the entry to Locuscraft users (though views and ratings are the greatest factor for visibility). Since sponsored entries could become a source of misinformation or advertisement, they will only be visible in certain places. They will not be mixed in with posts and tasks unless a user subscribes to the sponsored entry. Sponsored entries can be found under navigation pages, certain categories, certain sorts/filters like highest rated (if it has a high rating), and possibly at the bottom of the users' homepage under its own heading by default (they'll be able to change what's displayed on their homepage). User's will only be able to subscribe to their posts and tasks if it doesn't require membership or if they are a member.

As an example, say McDonald's buys a sponsored entry and they make it publicly accessible. They could create tasks that give them information about their consumers, such as surveys. Users can then earn community points by completing McDonald's tasks.

I consider sponsored entries to be somewhat low on the list of priorities. Subject and product entries should certainly be finished first.

####Low-Level Categories

These will be applied with tags, like people might put keywords for a photo. With the apple example, it would be tagged with fruit, food, plant, tree, cooking etc. 

####Mid-Level Categories

These can also be applied to an entry with tags. With the apple example, food and plant are mid-level categories since they have lower-level categories like fruit and tree below them.

If an entry only has low-level category tags like fruit though, then Locuscraft will automatically be able to fill in the mid-level categories. Say apple was only tagged with the tag "fruit", then Locuscraft should automatically know that fruit falls under the mid-level category food. 

If browsing for apples one could go to Subjects > Plants > Trees > Apple. Alternatively one could go to Subjects > Food > Fruit > Apple. Maybe that's a bad example since one is referring to an apple tree and one is an apple the fruit. But just understand that a single entry can be navigated to through different branches of the category hierarchy, assuming it falls under multiple categories.

##User Profile/Homepage

Picture the user profile and homepage as you would Facebook's. On Facebook, the user can add interests to their profile. The user can subscribe to a page and see posts made from another user/organization. The user sees an "activity feed" of all their friends and subscriptions. All of this is similar to the Locuscraft, except instead of being centered around other users, socializing, and status, the Locuscraft profile will be centered around interests, goals, and contributing to the internet (tasks). New users’ homes will display suggestions for where they should start.

###Profile Page

This will display everything related to the user. This includes their points, their interests, their contributions, their tasks, their history, their statistics, and anything else I missed.

###Points

**Community Points**

Users can earn community points by completing tasks. Community points are a measurement of what a user has contributed to the community, to Locuscraft, and therefore to the internet itself. Points are a free source of positive reinforcement for the users and will encourage them to keep up the good work.

Similar to Reddit's karma, any user will be able to see any other user's points. Therefore points could become a representation of status. To further their value, a leaderboard could keep track of users with the most points. Eventually, I would like to make points unlock actual things for the user's profile as well, such as custom skins or avatars, maybe web tools. I'm open to other ideas.

Read about [Tasks](.####Tasks) below to see ways community points can be earned.

**Other Points**

I had planned on including another type of points, called locus points, which would be awarded for completing tasks that affect only that user. I came to the conclusion that this would just add complexity and confusion to tasks. For example how do you gauge if a user read an article, watched a video, or did something for themselves in the real world like mow the lawn? It would be much more trouble than it's worth and these tasks are done for personal reasons anyway.

###Interests

Adding an interest is basically the same thing as subscribing to a subject entry. The user can navigate to a subject and click add to interests at the top. By adding an interest, the user adds that entry's activities and tasks to their activity feed, and therefore their activity feed will reflect their own interests. 

Say one of the user's interests is funny stuff, they can add "comedy" to their interests. Comedy itself would be a mid-level category with many categories below it, so adding humor would add all of the bottom-level categories beneath it. This could be fine-tuned to that user's sense of humor.

New accounts will have a few default interests that everyone starts with, including comedy, similar to the way new Reddit users start with default subreddit subscriptions.

###Activity Feed

The activity feed is the medium through which the user will do things on Locuscraft/the internet in a personalized and exploratory way. Activies in the activity feed will be a reflection of their interests. The activies can be filtered and sorted in various ways including most popular, highest rated, newest, and other more specific ways depending on the activity and category.

There will be periodic suggestions in the activity feed to give the user ideas or other things they might be interested in. This can be turned of in their settings.

Activities include posts and tasks.

####Posts

Posts will be the first thing to appear (by default) under the activity feed on the user's home page. A post on Locuscraft is very similar to a post on reddit in that any user can make a post on Locuscraft. Likewise, interests are similar to subreddits (in regard to the fact that adding an interests is like subscribing to a subreddit). Just like on Reddit, a post is simply text or a link to something (we could include media uploads too). Users will be able to comment on posts as well.

The key differences will be in the way posts are rated and organized. 

**Rating**

Reddit's upvoting and downvoting system has been criticized for [being prone to groupthink](http://www.popularmechanics.com/science/health/a9335/upvotes-downvotes-and-the-science-of-the-reddit-hivemind-15784871/) and [for being abused by its users](https://www.reddit.com/r/changemyview/comments/1wfgur/reddits_voting_system_discourages_dissent_cmv/). To address this, we must have a new system of rating. The website Slashdot has tried to address this issue with [a system of moderators](http://slashdot.org/moderation.shtml?source=autorefresh). This is an option and provides some ideas, but I believe the best solutions are the most simple and eloquent. The best system of moderation would give everyone moderation powers rather than a select few, effectively allowing all users to run Locuscraft and the internet itself, as is our goal. 

Here's what we do for comments: we give all users, say ten "tokens" per day. A token can be used to like or dislike a comment. This will encourage users to think more before they like or dislike a comment. I don't know how well this would solve groupthink, but seems like it would work. Community points could be awarded for highly rated comments.

Now for posts: let users rate posts in various aspects on a scale of 1 to 5 stars. User's would have to rate *specific aspects* of the post rather than giving the post itself a single rating. This would help eliminate people liking or disliking for different reasons, and it would help users understand the quality of the post in different aspects, *and* could help to sort/categorize posts based on different criteria. Taking an article as an example, the user could rate it in content, interest, relevance, writing quality, references, etc. There could be a dozen criteria to rate the article in, and not all users will want to do this all the time, so users would be able to rate as many criteria as they choose. To prevent abuse of the system, community points could not be awarded. Each criteria will receive an average rating based on all user ratings in that criteria. The post itself will receive a rating based on the average of it's criteria ratings.

**Organization**

By default, posts from all the user's interests will be displayed and they will be listed based on the number of ratings and value of the rating. There will be ten posts on the homepage, with an option to "see more" which will simply extend the page and show ten more posts. Below this option, will be the next subdivision of activity which is tasks.

The user will have the option to *filter* the posts based on interest, selectively including and omitting the interests they choose. They can also filter by content, selectively including and omitting articles, videos, gifs, text, images, etc. Furthermore, they will be able to filter based on the criteria rated by users. Since this varies based on the content, it will be a subdivision of the content filter.

The user will also be able to *sort* the posts by newness, ratings over different times (day, week, year...), number of views, number of comments, rising (suddenly receiving lots of ratings), and maybe some other criteria.

Users can go to the entry page for one of their interests and filter and sort posts within that interest in the same fashion.

Users can also save posts to view or share later. This is under the options for the post.

####Tasks

All tasks require the completion of some sort of work on the part of the user. Tasks come in two forms: community tasks and goals.

#####Community Tasks

Community tasks have a few similarities to posts. Like posts community tasks are always associated with a specific entry/interest. They also have their own feed on the activity feed like posts, and will be sortable/filterable. 

They are different from posts in that they contribute to other users of Locuscraft, rather than to the entertainment or knowledge of the individual. This part of Locuscraft involves both building and sharing. To compensate users for completing tasks and doing their part, community points are awarded to the user.

Community tasks will vary based on the entry they are associated with, but examples include:

* Complete surveys
* Categorize websites by linking them to entries
* Add descriptions to entries
* Answer user questions
* Be active in forums
* Help create buying guides, how-to guides, or learning guides (or linking guides)
* Participate in opinion polls
* Review answers
 
I believe there should be certain **special entries** that focus on certain types of tasks. For example, there should be an entry called "Opinion" where users participate in general polls on a wide range of topics. It will ask questions where we want the opinion of as many people as possible. This special entry should be under the interests of all new user accounts by default. Another special entry could be one that focuses on Locuscraft itself. Tasks will involve the user's opinions about certain aspects of Locuscraft, user opinions on whether a change should be made to Locuscraft, and then tasks that involve actually making those changes.

We want people to express their opinion as much as possible too. That includes hearing what people like and dislike. We could have people make lists of their favorite things, or of their least favorite things, and combine them to see what the average global consensus is on something.

You might ask, *how can we know if a user is being honest on community tasks* and not just farming for points or trolling? There are a few measures we can take to validate answers:

* Spellcheck to make sure real words were used. If there are more than, say, 10 errors then it can be assumed that it is a fake response, and the form will not allow the user to submit.
* Links can be verified by the number of times different users put it as a source. Linking tasks could remain active until at least 100 links are submitted. Links that are submitted more than once will show on the entry page. To further verify links, users will be able to report a link if they click it and it goes to somewhere not related to the entry.
* Other entry fields like descriptions, uploads, and responses can be verified through either ratings, or through a system similar to github where changes have to be commited. Highly rated submissions will be visible, while low rated submissions will be buried. 

Community tasks will be sorted by most important and urgent by default. Importance and urgency are ways of gauging task priority. Other ways of sorting are by number of submissions the task already has (number of users who have completed the task), newness of the task, and the number of points the tasks award.

#####My Tasks

My Tasks are unlike posts and community goals in that they aren't subscribed to, but are instead created by the user for individual reasons. Being personal, they don't award community points. These tasks can be short-term or long-term. They include the user's daily to-do's as well as their long-term goals in life. 

The user's personal tasks can be displayed on their homepage in timeline format or in list format. Typically it will be displayed in order of which one needs to be completed soonest, but it can be sorted or filtered like posts/community tasks.

Each task has a variety of entry fields, tools, and settings that can be customized to fit the task. Our goal in designing My Tasks is to give the user as many tools as possible to assist them in completing that goal, so this list will surely be lengthened.

Entry fields include:

* Title
* Any number of text fields (description, commentary, notes, logs) which may be listed and have nested lists.
* Resources (links, interests, uploads, related tasks/posts)

Settings and tools include:

* Priority
* Start time
* Deadline/expiration/end time
* Recurrence or multiple specific timeframes
* Reminders
* Specific tools such as calculators, generators, free design software

Tasks and sub-tasks can be marked by the user as not started, in progress, incomplete, or complete.

Tasks can also be organized into separate lists, and the list given a name, to group tasks together. For example one may want to make a list of goals, or a to-do list.

An example of a personal task could be to learn more about carpentry. It's title would be "Learn more about carpentry". The user could find the carpentry entry on locuscraft and link it to the task as a resource. They could have the Carpentry activity feed be displayed under the task. They could link specific videos or websites as well. They can write a description detailing specifically what they know and want to learn. They can set a timeframe to work on this the following day from 10 AM to 11:30 AM and recurring every day after for a week. They could create sub-tasks for each day that must be completed in order, such as watch these videos, then build this, then build that. The user could share their task by posting it on Carpentry. It may not get any hits, but who knows? The user could go a step further by helping create a step-by-step learning guide under Carpentry, and earn community points in the process.

Locuscraft will also give suggestions to the user to give them ideas. Here's some examples we might suggest:

* Create a daily journal.
* Add birthdays to your calendar.
* Make a list of personal goals.
* List your ideal daily routine. (Give examples too)
* Try cooking some highly rated recipes! (Recipes can be added as tasks)
* Create a daily exercise routine.
* Create a daily meditation task.
* Work on a diet regimen! (Link to a guide)

###Customization

The user will be able to organize the layout of their homepage. This means they will be able to move My Tasks, Posts, tools, and other things around on the page.

In addition they will be able to customize the format to some extent. I'm thinking the colors, background images, and perhaps the font. There could also be avatar pictures, maybe? These could be integrated as rewards for certain amounts of community points.

This part is not well established yet because it is low on the list of priorities.

##Privacy

Privacy is extremely important for a website like this. Users need to feel secure in knowing the vast amount of information Locuscraft stores about them is not going to be shared with anyone, unless they themselves share it.

At the same time however, there is a lot of information that could be beneficial to the world. Statistical type information mainly. This information can be collected anonymously however. 

We will have to write a privacy policy, and my legalese is pretty bad. Any takers?

##Ideas for the Future

To make use of the plethora of information already available on the internet, I think it will be important to **partner with other websites** and organizations to make their resources available to Locuscraft users. For example Khan Academy could be one such website that could help users complete tasks relating to subjects on their website. It would be a mutually beneficial relationship. A Khan Academy API could be developed to make their tutorials and videos seamlessly integrated with Locuscraft.

Locuscraft has a lot of development potential. One idea I thought of was to make **"teachers" and "students"** similar to the way Khan Academy does, where teachers can assign tasks to students and the students can submit their work through the task. It really doesn't even have to be a teacher/student relationship. We could make it so any user can "share" a task with another user, and that other user can agree to complete it, or not.

Another idea is to **find or create free and open source tools**, and link/integrate them with certain entries and their tasks on Locuscraft. For example, a video editor that can be found under the different entries related to that field. A drawing tool for graphic design related entries. Locuscraft can find a currently existing tool and help the developers make it better through collaboration with community tasks. Alternatively we can create our own through the same means.

We could **increase the functionality of product pages** by having tasks associated with each product. Once a user purchases a product, they could tell Locuscraft they purchased it and give Locuscraft the tracking number, then on the user's homepage it will keep up with where in transit the package is at. Once the user receives the package, tasks will appear in the user's "My Tasks" associated with the product. It could be instructions or guides on using the product, things they should know, etc. Locuscraft could even bookmark the user manual online so the user always has it.

**Allow users to access their profiles, and especially "My Tasks" on their phones.** This means creating a Locuscraft app for small devices. Users may create a shopping list on their Locuscraft account on their computer. They can keep it on there forever if they want then access the list when they're at the store. Convenience! Allow them to browse posts, entries, and their tasks too.

**Imagine the possibilites with bitcoin.** Imagine a world without governemnets, but just a community of online users with a system of self-governance. Taxes could be collected from user's bitcoin accounts based on an annual percentage, and the users put these funds into the community the way they see fit. Users can vote on the changes they want to see or the projects they want funded and their taxes will go directly into those things. Of course this is more like a fantasy than an idea, but just imagine...


