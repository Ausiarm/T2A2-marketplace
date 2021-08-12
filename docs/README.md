# T2A2 Marketplace Project - FitFoundation


## Problem To Be Solved
- In the fitness sphere of the internet community there is a preponderance of services that guide new learners down paths that lead to bad habits, personal-image-shaming, and ultimately failure of the goal to make health and fitness a part of ones' life. This issue is compounded by investors pushing products through leaders of the community who are paid to support them without necessarily believing in them. These products, regardless of their efficacy, are seen by acolytes and initiates as panaceas to their personal problems. As more individuals seek to adopt healthy lifestyles this duplicity is leading to a lack of faith in the pursuit of health and causing newcomers to believe that vanity is more important than well-being. 
- To further elaborate on this problem it can be broken down into two constituent parts:
    1. Personal
        - Too often is it the case that beginners find themselves being incredibly critical of their own abilities as well as their image. It stands to reason that as a result, if someone wants to change their health, they must first be willing to adjust the system of judgement that they use to analyze their own life. 
    2. Extra-Personal
        - Beyond personal barriers, the second most significant threat to successfully bettering ones' health and well-being is interaction with others. Humans often rely on experts in fields that they have little-to-no practice in to guide them in a safe and sound direction. Unfortunately, this is not the case in the health and fitness industry. Often, professionals who have put in the time to gain status in the community use that status to sell products that had very little bearing on their own ability to attain a high health status. This misleading can very often cause beginners to give up, believing that they have some intrinsic flaw that is holding them back when they can't attain the "immediate" results that these industry professionals tout so highly. 
        - Comparison of phsyical form, also falling into the Extra-Personal category, can be very damaging to a beginner's mentality. Many professionals in industry fail to make it known that they have spent almost a lifetime attaining the form they have. This misleading must be addressed early on in the journey of a beginner or run the risk of tainting their understanding of how beautiful their own form is. 
--- 

## Why Solve This Problem? 
- Overall health and well-being are critical to the maintainence of a thriving life in the developed communities around planet earth today. It is easy for an individual to overlook or not place emphasis on these two facets of life when they are obfuscated by the obligations that most working adults face. However, a moderate and healthy focus on these two aspects of being lead to healthier humans who both live longer and are more productive members of the societies within which they exist. It is critical that, in the wake of a rapid expansion thanks to sensationalism on the part of the internet and influencers, regular humans develop a healthy relationship with health. Teaching them to focus on what works for them and what makes them feel best regardless of the influence of dubious products and sellers who seek to confuse attainment of health with attainment of wealth for themselves at the cost of those who they train. 
    - ### How does this application serve this purpose?
        - Themelio will provide users a no frills experience that will isolate them from the paid abuse of their trust that typically occurs in the health and fitness industry.
            - The site will not take funds from companies in industry to push products on their users nor will it endorse certain methodologies over others. It is simply a platfrom that will allow users to search for guides that seem interesting to them. Later on, after initial MVP release, functionallity will be built into the application to allow users to reach out to one another. This will allow for collaboration in the event that a user really appreciates a point of view from a guide and wants to learn more from the person who created the listing that houses the guide.  
--- 

## Website Link
- [Themelio](https://themelioo.herokuapp.com/)
--- 

## Github Repository Link
 - [github](https://github.com/Ausiarm/T2A2-_Marketplace_Project)
---

## General description
- Purpose: 
    - To provide an self-image-friendly and health-encouraging platform for users with little-to-no experience in the world of fitness. 
- Functionality / features
    - Home page
        - Simple and non-confusing page featuring:
            - Logo.
            - The basic philosophy of the platform in no more than three sentences.
            - Buttons for logging in as well as signing up.
                - *Update_Post_deployment: This feature was modified. Main buttons are now for creation of guides as well as heading straight to the foundry. all other interactivity was moved to the navbar for purposes of simplicity.*
    - Foundry
        - The landing page of the platform
            - Scrollable feed.
            - Features 2-3 images coupled with descriptions per row.
            - Each entity has the ability to be rated by the user (referred to in app as builders).
                - *Update_Post_deployment: For the sake of time this feature was not addressed, would like to add at a later date.* 
            - Clicking an entity takes the user to a page that features its full description as well as the ability to purchase that content for a flat fee, do so will add the content to the Builder's MyFoundry.
                - *Update_Post_deployment: This feature was modified into a see more button to reduce potential confusion.*
    - My Foundry
        - The "profile" page for each builder.
        - features basic information about the builder:
            - name
            - date of birth
            - goals 
            - picture
        - Foreign Materials:
            - Section that shows any content that the builder has either liked or purchased. 
        - Domestic Goods:
            - Section that allows for uploading of personal content that can be featured on the Foundry landing page.
        - *Update_Post_deployment: This page was updated and modified for the sake of time, all it will display currently are the user's purchased guides.*
    - Merchandise
        - Storefront that will sell merchandise related to the fitfoundation brand for the purposes of donating to charity and/or fitness related support groups.
            - *Update_Post_deployment: this feature will be added at a later time as it was more of a nice to have addition and less of a critical part of the application.*
    - Help/FAQ's
        - Page dedicated to questions that are frequently asked.
            - Scrollable feed of commonly asked questions.
            - Box at the bottom to post a question that has not already been asked.
        - *Update_Post_deployment: this feature will be deployed at a later time.* 
- Sitemap
    - ![Themelio_Sitemap](Themelio_sitemap.png)
    - *This version of the sitemap reflects changes made to the application during development. It became necessary to revise and simplify when time began to run down for submittal.*
- Screenshots
    - ![Themelio_home](themelio_home.png)
        - Note the lack of clutter on the home page. The idea here was to remain as minimal as possible with the intention of scaling and scope increase in the future.
    - ![Themelio_the_foundry](themelio_the_foundry.png)
        - On the foundry page all listings can be seen that have been created on the application. From here a user can choose to click into the see more function and purchase a listing.
    - ![Themelio_see_more](themelio_see_more.png)
        - Once a user has clicked on see more they are directed to a page that will show the details of the listing and give the user a better preview before a buy. 
    - ![Themelio_my_foundry](themelio_my_foundry.png)
        - After choosing to purchase a listing the user can find all listings that have been purchased on their my foundry page.
    - ![Themelio_stripe_integration](themelio_stripe_integration.png)
        - Evidence of appropriate stripe incorporation. 
    
- Target audience
    - People with little-to-no experience with fitness who are afraid to try to become healthier due to how daunting the goal seems from afar.
- Tech stack (e.g. html, css, deployment platform, etc)
    - HTML 
        - Utilized for basic type entry and structuring of views. Along with embedded ruby this forms the main foundation of the application from a user presentation point of view.
    - CSS
        - After development of main features from a logic standing, CSS was incorporated to add some pop and interest to the basic page views.
    - Ruby on Rails
        - Language used for devlopment of application.
    - Javascript
        - While still unfamiliar with javascript it was necessary to incorporate for use in the stripe payment integration process. 
    - Heroku
        - Service used to deploy site live. 
    - Amazon 
        - Utilized Amazon S3 for storage of images
    - Ultrahook
        - Utilized in conjunction with stripe to capture payment information and store in databases as well as presenting to the user. 
---

## User Stories
1. Beginner with no experience:
    - As a beginner with no background in fitness, I want access to a trustable source of health training so that I can become healthy and fit in a positive and sustainable manner.
2.  User with moderate experience:
    - As a person who has a moderate amount of exercise and health knowledge, I want access to learning from members of the community with a focus on healthy habits so that I can broaden my scope and diversify my understanding of health. 
3.	Trainer interested in training others:
    - As a trainer, I want to help the fitness community by posting easy to understand information so that beginners can use it to grow their health toolset. 
4.	Expert interested in sourcing different ideas to exercise:
    - As an expert in fitness, I want to be aware of the current trends in fitness and of how the fitness community is evolving so that I can keep up to date in my own practice.
5.	User interested in purchasing merchandise:
    - As a member of the general public I want access to merchandise that represents a positive brand so that I can spread awareness of that brand. 
---

## Wireframes
- ![Wireframes](FF_Wireframe.png)
    - These served as a platform to narrow down the scope of the project, they have been left unmodified as the ultimate goal of the project is to get to the point where it reflects the wireframe design. They can be further broken down into desktop, tablet, and mobile views:
        - Desktop
        - tablet
        - Mobile

---

## ERD
- ![ERD](FF_ERD.png)
    - Above is the original ERD created for this project in the conceptual phase. Please note the differences between it and the revised version posted below:
        - Removed media, post, category, and merchandise tables
            - These tables proved to be too complex to involve in the scope that they were originally intended. Media and its contents were an overcomplication in the planning phase that could be better dealt with through use of Amazon S3. Post proved to be redundant as it was another way of referencing a listing. Category could be more easily included into the listings table as an enumerable to reduce overall complexity. Finally, merchandise works as a table and is a valubale inclusion but lacks purpose currently as the merchandise logic and views were not able to be implemented in time. 
        - These revisions being made, the relationships of entities in the database are much clearer to see and can be added to in the future without having to plan the whole ERD structure over again. 
    - These revisions represent the need for consolidation of tasks in order to meet project deadlines. In addition, the first iteration of the ERD assumed far too much complexity on the part of the application's models and it was necessary to reel this in when actually devloping the application itself. 
- ![Revised_ERD](revised_ERD.png)
---

## Explain the different high-level components (abstractions) in your app
- How does MVC work in this app?
    - Keeping with standards of the MVC (Model, View, and Controller) protocol, this app stores data and logic within the models set up for each of the individual sections. These models are: 
        - Listing
        - Order
        - Payment
        - User
        - ![model_represent](model_represent.png)
    - In order to interact with or change these models in any way, methods are provided in each of their corresponding controllers that allow admin's to CRUD (create read update destroy) the database. These controllers are:
        - Foundry 
        - Home
        - Listings
        - Orders
        - Payments 
        - Restricted
        - ![listing_represent](listing_represent.png)
    - Finally, once a method is called that is set up in the controller, this method routes to a specific view that has been set up in order to display the pertinent information based off user request. These views are:
        - Devise
        - Foundry
        - Home
        - Layouts
        - Listings
        - Orders
        - Payments 
        - Restricted 
        - Shared
        - ![view_represent](view_represent.png)
- What does user interaction look like with routes?
    - The MVC pattern works in conjunction with the config/routes.rb file. Here an application is given instructions on where to send users based off their interaction with the views of the application. The reason that these routes work in conjunction with the MVC pattern mentioned above is that they also reference the specific method names created in the corresponding controller in order to send users to the correct pages based off what links or actions they are interacting with. An example of how routes fit in to the MVC pattern is noted below. Additionally, please reference the attached photo to understand what is meant by saying that routes reference specific method names. 
        - ![Route_example](routes_view.png)
- To better explain these high-level components of the app, an example follows using the Listing MVC:
    - A user navigates to the home page of the app (structure laid out above in sitemap previously posted in section 5) and from here has the option to go to The Foundry. Once they click on this button the server will send a GET request from the browser that is configured in the routes.rb section of this application. this GET request will cause the server to append the end of the url with the ```/listings``` suffix. Now that this route has been correctly added to the link, the applications MVC pattern takes over. The ```/index``` method that is in the listings controller will be invoked. When this is done the controller will communicate with the model to access the listings database. Once this communcation occurs the controller will subsequently communicate with the appropriate view (if adhering to ruby best practices, this view will be located in the listings folder in views and be called index.html.erb). When named correctly, rails will know that the index method in the listings controller is meant to function in conjunction with the index view specifically created in that listings folder. The controller will essentially assess the structure of the views page and use it to populate the new webpage that the user has navigated to. In this case (as can be seen below) the index.html.erb view dictates that a loop shall run, creating a card style presentation for each of the listings in the database. What the user will see is rendered visual representation of the data from the listings database and from here they can navigate to see more or go back to the home page. 
        - ![View_example](listings_view.png)

---

## Detail any third party services that your app will use
- Heroku
    - Used for live deployment due to ease of access as well as ability to deploy for free while under a certain amount of data usage.
- Amazon S3
    - Amazon's cloud storage for images/media proved to be very helpful for storing uploaded photos outside of the application so that load times would not become extraneous in the event of high traffic and usage of the site. 
- Stripe
    - Stripe's easy to integrate functionallity, along with its free use proved to be the perfect tool for implementing a payment service. Additionally it allows for much safer interaction with user's private payment information that could potentially be handled poorly in the event that an application was attempting to store it on the back-end.
- Ultrahook 
    - Ultrahook served as the free service that allowed for the creation of a webhook that would catch user information and route it to the server so that the application could effectively integrate with stripe and be able to process user receipts as well as allowing payments to be properly processed.
- Github
    - Github served for version control throughout the process of developing the app. As is the case with all other projects, version control proved critical when the application broke and changes were impossible to rectify. 
- Trello
    - Trello provided the platform for monitoring daily effectivness in task completion as well as creating a proper schedule that led to on time delivery of the project.
---

## Describe your projects models in terms of the relationships (active record associations) they have with each other
- For the sake of being able to deliver a working MVP (minimum viable product), the models of this project associate with one another through one-to-many interactions. 
    - What is a one-to-many interaction? 
        - What the one-to-many status on a model indicates is that one entity from a model may have or create many entities that exist within another model and maintain ownership of those entities. This is best demonstrated with the user model from this application in relation to the listings model. Note the pictures of the models below:
        - ![user_model_example](user_model.png)
        - ![listing_model_example](listing_model.png)
        - Note the ```has_many :listings``` code at the top of the user model and the ```belongs_to :user``` at the top of the listing model. These two snippets of code create the one-to-many relationship referenced above. With this relationship in place, a user can create as many listings as they like. Each of those listings will be added to the database with a specific identifier (a foreign key) that establishes which user created them. Specfically, one user, as this relationship is a one-to-many relationship.
- outside of the user and listing model used to explain the relationship they share, this application has an order and a payment model as well. Both of these models belong to the user model in the same one-to-many style of relationship while order has another one-to-many relationship that binds it to listing as well. This is important as it makes clear that for an order to actually be processed, it must be bound to a listing. 
--- 

## Discuss the database relations to be implemented in your application
---

## Provide your database schema design (Ask teej what this is??)
- plan ERD
- discuss the relations of the ERD
--- 

## Describe the way tasks are allocated and tracked in your project
- Trello was used in order to accurately track progress as well as breaking down the assignment into manageble portions of work. This resource can be accessed free of charge by navigating to trello.com and signing up for an account. Once a project page has been created it can be populated with tasks and set up in the manner that best suits the project planner. This assignment was broken down into 4 sections on trello:
- ![final_trello_example](final_trello.png)
    - Documentation
        - This section of the trello board was critical for laying out which portions of the documentation could be completed before the projects commencement and which would need to be saved until completion. 
        - It was further split into three sections and included checkable boxes that allowed for constant monitoring of which tasks remained to be completed.
        - See documentation photos for examples of the above:
            - ![completed_docs_example](completed_docs.png)
                - Here is where tasks that could be immediately completed were recorded.
            - ![updated_docs_example](updated_docs.png)
                - Here is the location that allowed for keeping track of how documentation was being progressed through.
            - ![docs_in_progress_example](docs_in_progress.png)
                - Here is where all remaining and not-yet-completed documentation tasks were stored
    - User stories
        - In this section the user stories that were implemented to handle planning scope and purpose of the application were stored. Through constant reference to these cards it was possible to develop an application that kept true to its overall purpose and scope rather than deviating during development. Note that the beginner user story is the main focus of attention for this iteration of the application. 
            - ![user_stories_example](user_stories.png)
            - ![user_stories_beginner_example](user_stories_beginner.png)
    - Development
        - Here is where all development tasks were stored, much like the documentation section above, this column was broken down into levels of completion. This staggering of completedness allowed for constant movmement through tasks without not knowing what to work on after completion of a single job. In addition, this section included timed due dates on objects in order to properly pace out the project and be sure to have enough time to revise documentation after development. 
            - ![development_trello_example](development_trello.png)
            - Note that there was a nice to have section included here. This column served as a reminder of what can be added at a future date and to show that the project isn't over simply because it has been turned in. 
    - Presentation
        - Lastly, due to the need to compartmentalize this project to handle time management, the presentations section was left until the end. This approach allowed for the presentation to not only demonstrate the product but also reflect the challenges incurred to get to the product rather than showing off a concept without any real object to point to. 
            - ![presentation_doc_example](presentation_doc.png)
--- 