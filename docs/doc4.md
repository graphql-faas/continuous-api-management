---
id: doc4
title: Chapter 4. The Ten Pillars of an API Product
---

When it’s done well, it does look easy. People have no idea how complicated and difficult it really is. When you think of a movie, most people imagine a two hour finished, polished product. But to get to that two hour product, it can take hundreds or thousands of people many months of full time work.

George Kennedy

In the last chapter we established the perspective of treating the API as a product. Now let’s take a look at the work you’ll need to do to build and maintain your product. The truth is that it takes a lot of hard work to develop a good API. In Chapter 1, you learned that APIs have three different parts: interfaces, implementations, and instances. To create your API you’ll need to put time and effort into managing all three of those aspects. On top of that, you’ll need to keep everything up to date as your product continually matures and changes. To help you understand and manage all of that complexity, we’ve divided this body of work into a set of ten pillars.

We call them pillars because of the way they support your API product. If you don’t invest in any pillars, your product is doomed to fall and fail. But that doesn’t mean all the pillars need maximum investment for your API to succeed. The nice thing about having ten pillars is that they don’t all have to carry the same amount of weight. Some pillars can be stronger than others, and you can even decide that some pillars don’t need much investment at all. The important thing is that the combined strength of these pillars raises your API up, even as it evolves and changes over time.

Introducing the Pillars
Each of the API pillars forms a boundary for a work domain. Or, putting it another way, each pillar bounds a set of API-related decisions. In reality, your work effort can’t be categorized this precisely, and some of the pillars will overlap with each other. But that’s OK. Our intent isn’t to define an irrefutable truth about API work; instead, it’s to develop a useful model for examining and talking about the work that goes into producing API products. We’ll be building upon this foundational concept of pillars througout the book as we develop more advanced models for team organization, product maturity, and landscape aspects in future chapters.

The ten pillars we’ve defined for API work are as follows:

Strategy

Design

Documentation

Development

Testing

Deployment

Security

Monitoring

Discovery

Change management

In this chapter, we’ll introduce each of these pillars and examine what they are and why they are important for the success of an API product. We’ll also describe the decision space for each pillar along with some general guidance on how to strengthen it. We won’t be giving you any specific guidance on how to implement any of the pillars in this chapter—after all, a complete discussion of each of these areas of work could fill a book on its own and we still have many more API management concepts to tackle. However, we’ll call out some of the most important decisions in each area from a governance perspective. Let’s start by taking a look at the first pillar of an API product: strategy.

Strategy
Great products start with a great strategy, and API products are no different. The API strategy pillar includes two key decision areas: why you want to build your API (the goal) and how an API will help you to achieve that goal (the tactics). It’s important to understand that your strategic goal for the API can’t exist in a vacuum. Whatever goal you come up with for your API product needs to bring value to the organization that owns it. Of course, that means you’ll need to have some idea of your organization’s strategy or business model in the first place. If you’re in the dark about your organizational goals, figure that out before you start spinning up new APIs.

POWERING YOUR BUSINESS WITH APIS
The amount of impact that your API product has on your organizational strategy depends a lot on the context of your business. If your company’s main revenue source is selling API access to third-party developers (for example, Twilio’s communication APIs or Stripe’s payments API), then your API product strategy will be heavily intertwined with your company strategy. If the API does well, the company profits; if the API suffers, the company fails. The API product becomes the primary value channel for your organization and its architecture and business model will be implicitly aligned with the objectives of the company.

However, most organizations have preexisting, “traditional” businesses that the APIs will support. In these cases an API will not become the new primary revenue source unless the company makes a major change to its strategy. For example, a bank that has been operating for hundreds of years may open an API to external developers in support of an “open banking” initiative. Narrowly focusing only on the API’s business model might lead to adopting a revenue model for the API—one that charges developers for access to API-based banking functions. But thinking about the bigger picture for the bank, this API strategy would be detrimental because it creates a barrier to usage. Instead, the banking API can be offered for free (at a loss) in the hopes of increasing the bank’s digital reach, leading to an increase in sales of the core banking products.

API strategy isn’t just for APIs that are being offered to the outside world; this is also an important pillar for your internal APIs. That means you’ll need to define a product strategy for them as well. The only real difference between internal API strategy and external API strategy is in the users they serve. For both types of APIs, the work of understanding why the API needs to exist and how it can fulfill that need remains the same. No matter what the context is for your API, it’s worthwhile to develop a strategic goal for the API that will bring value to your organization.

Once you have a strategic goal for your API product, you’ll need to develop a set of tactics that will help you achieve it.

DEFINING TACTICS
Achieving a strategic API goal will require you to create a plan for your product that leads you there. You’ll need to develop a set of tactics for your work that gives you the best chance of success. Essentially, your strategy guides all of the decision-based work you’ll make in the other nine pillars. The challenge is in understanding the link between each of those decision work domains and your goal.

Let’s take a look at a few examples:

Goal: Increase business-aligned capabilities in your platform
If the focus is on building up a bigger set of business-aligned APIs, your tactics should include some changes to how you design and create your API in the first place. For example, you’ll probably want to involve the business stakeholders early in the design stage of your API to make sure that the right capabilities are being exposed through your interface. You’ll also probably take their lead in understanding who the primary users are and what the boundaries of the API should be.

Goal: Monetize internal assets
A monetization focus requires a set of tactics that help you bring your product to a user community that finds it valuable. It also usually means that you’ll be operating in a competitive market, so the developer experience (DX) of using your API becomes very important. Tactically, that means a heavier investment in the design, documentation, and discovery pillars of work. It also means you’ll need to do some market research to identify the right audience for your API and make sure you have the right type of product for them.

Goal: Harvest business ideas
If the goal is to find innovative ideas from outside your company, you’ll need to develop a set of tactics that fosters the use of your API in innovative ways. That will mean marketing the API to the outside world and designing it to be appealing to a user community that provides the most potential innovative value. It also makes sense to invest heavily in the discovery pillar to make sure that you can drive usage as high as possible in order to harvest as many ideas as possible. Equally, you’ll need a clear tactic for identifying the best ideas and developing them further.

As we can see from these three examples, you’ll need to do the following to develop strong tactics for your API:

Identify which pillars are essential to success.

Identify which user communities will drive success.

Gather contextual data to drive your decision-making work.

ADAPTING YOUR STRATEGY
While it’s important to develop good tactics when you begin building your API, it’s also essential that your strategy remains fluid and ready to change. It’s no good setting your strategic goal and tactical plan once and then walking away. Instead, you’ll need to adjust your strategy based on the results you get from your product. If you aren’t making any progress, you’ll need to make some changes to your tactics, perhaps adjusting your goal or even scrapping the API and starting again.

Charting your strategic progress means you’ll need to have a way of measuring your API results. In fact, it’s essential that you have a set of measures for your strategic objectives—otherwise you’ll never know how well you are doing. We’ll talk more about objectives and measurements for APIs in Chapter 6 when we introduce OKRs and KPIs for APIs. Measurement also depends on having a way of gathering data about the API, so you’ll also need to make an investment in the monitoring pillar.

You should also be ready to change your strategy if the context of your API changes: for example, if your organization changes its strategic goal, or a new competitor shows up in your market, or the government introduces a new type of regulation. In each of these cases, being quick to adapt can greatly increase the value your API provides. But strategic change is limited by the changeability of your API, so the pillar of change management (discussed later in this chapter) is an essential investment.

KEY DECISIONS FOR STRATEGY GOVERNANCE
What is the API’s goal and tactical plan?
Defining a goal and a plan to achieve it is a core of strategy work. It’s important to consider carefully how this decision work should be distributed. You can allow individual teams to define their own goals and tactics to take advantage of local optimization, or you can centralize goal planning to improve system optimization. If you choose to decentralize API strategy work you’ll need to build incentives and controls to prevent any single API from causing irreparable harm. For example, centralizing the authorization step of a goal-setting decision may slow the process down, but can prevent unexpected problems.

How is the strategic impact measured?
The API’s goal is a local definition, but you’ll also need to govern how well that goal aligns with the organization’s interests. That measurement can be decentralized and left to your API teams or it can be centralized and standardized. For example, you can introduce a consistent process with standardized metrics that teams need to follow for API reports. This gives you the benefit of consistent data for system-level analysis.

When does the strategy change?
Sometimes goals need to change, but who is allowed to make that decision? The trouble with changing an API’s goal is that it tends to be highly impactful, both to API itself and to the people who depend on it. While you might give your teams the freedom to set the goal of a new API, you’ll need to introduce more controls for goal changes, especially once the API has entered a stage of heavy usage.

Design
Design work happens when you make decisions about how something you are creating will look, feel, and be used. Everything you create or change involves design decisions. In fact, all of the decision-making work we describe in the different sections of this chapter can also be thought of as design work. But the pillar of API Design we are describing here is special. It’s constrained to a specific type of design work: the decisions you make when you are designing the API’s interface.

We’ve called out interface design as its own pillar because it has such a big impact on your API. Although it’s only one part of what makes an API, the interface is all that your users see when they want to use your product. For them, the interface is the API. Because of that, whatever interface design you come up with has a big impact on the decisions you’ll make in the other pillars. For example, deciding that your API should have an event-based interface radically changes the implementation, deployment, monitoring, and documentation work you’ll need to do.

You’ll have lots of decisions to make when you are designing your interface. Here are a few of the important things you’ll need to consider:

Vocabularies
What are the words and terms that your users will need to understand? What special characters will they need to know about?

Styles
What protocols, message patterns, and interface styles will the interface adopt? For example, will your API use the Create, Read, Update, Delete (CRUD) pattern? Or will it use an event style? Or something like the GraphQL query style?

Interactions
How will your API allow users to meet their needs? For example, what calls will they have to make to achieve their goals? How will the status of calls be communicated to them? What kind of controls, filters, and usage hints will you provide to them in the interface?

Safety
What design features will help your users avoid making mistakes? How will you convey errors and problems?

Consistency
What level of familiarity will you provide to your users? Will the API be consistent in terms of other APIs in your organizations or your industry? Will the interface design be similar to other APIs that your users may have used, or will it surprise them with its innovation? Will you adopt ratified industry standards in your design?

That’s not an exhaustive list, but as you can see, there is a lot of decision-making ground for you to cover. Designing a good interface is difficult work. But let’s be more precise about what the goal is. What is good design for an API’s interface, and how do you make better design decisions?

WHAT IS GOOD DESIGN?
If you’ve done the work of establishing a strategy for your API, then you’ve already defined a strategic goal for your API. We need to figure out how the design of the interface can help you get closer to that objective. As we saw in “Strategy”, you can come up with lots of different goals and tactics for an API. But generally speaking, all of them boil down to a choice between two common objectives:

Acquire more API users.

Reduce the development costs for API usage.

In practice, you’ll need a much more nuanced view of strategy if you want to be effective. But by generalizing the objectives this way we can make an important observation: good interface design will help you achieve both of these generalized goals. If the overall experience of using the API is good, more users will be willing to use it. Interface design plays a big role in the developer experience of your API, so good interface design should lead to higher user acquisition. Also, a good interface is one that makes it harder to do the wrong things and easier to do the things that solve a user’s problems. That translates to a lower development effort for the software that you write when you use a well-designed API.

So, good interface design is worth investing in. But there isn’t a concrete set of decisions that makes an interface a “good” one. The quality of your interface depends entirely on the goals of your users. Improving usability and experience is impossible if you don’t know who you are designing for. Thankfully, if you’ve already established why you are building this API, it should be a fairly straightforward exercise to figure out who you are designing for. Target that user community and make design decisions that will improve their experience of using your API.

DEVELOPER EXPERIENCE (DX)
Throughout this chapter and in this book we’ll refer to the developer experience of your API. DX is really just the user experience that your API provides, but with the acknowledgment that it is for a very particular type of user—a software developer. An API’s DX is the sum of all the interactions that the developer will have with your API product. Interface design is a big part of that, but your documentation, marketing, and support all contribute to the experience you are creating. Ultimately, DX is a measure of how happy or (unhappy) your user base is.

USING A DESIGN METHOD
To get the best results from your interface design work, your best bet is to use a method or process. A big part of creating a design is making guesses or assumptions about what you think will work. You have to start somewhere, so you might start by copying an API interface that you like or by following some guidance in a blog post. That’s perfectly fine. But if you want to maximize the value that your design interface provides, you’ll need a way of testing those assumptions and making sure the decisions you’ve made are the best ones.

For example, you could decide to adopt the following lightweight process:

Come up with a prototype for the interface.

Write our own client that uses the prototype.

Update the prototype based on what we’ve learned and try it once more.

A heavier-duty process might look like this:

Have an early design meeting with all stakeholders (i.e., users, supporters, and implementers).

Codesign a vocabulary for the interface.

Conduct surveys with the user community.

Create a prototype.

Test the prototype with target user communities.

Validate the prototype with implementers.

Iterate as necessary.

The big difference between these two examples is the amount of investment you’d need to make and the amount of information you’d gather. Deciding how heavily to invest in the design process is a strategic decision. For example, you’ll probably scrutinize the interface of an external API being sold in a competitive market more than you would an internal API being used by your own development team. But remember that even a lightweight design process can pay big dividends.

API DESCRIPTION FORMATS
You can make your design work easier by using a machine-readable interface description to describe it. Not every style of API has an established standard format, but some of the more common ones do. For example, if you are designing SOAP APIs you can use the WADL format, if you are designing a CRUD-style HTTP API you can use the OpenAPI Specification, or if you are designing gRPC APIs you can use Protocol Buffers. Each of these description formats makes it easier for you to generate prototypes with tooling and persist and share the interface description internally as a file.

KEY DECISIONS FOR DESIGN GOVERNANCE
What are the design boundaries?
An API team with no design constraints can create an interface model that maximizes usability and the experience for their users. But usability is user-centric and comes at the cost of flexibility for users in general. That means there is a system impact to this kind of local optimization. If you are producing many APIs and users will need to use more than one of them, you’ll need to introduce some constraints around design decisions. That means you’ll need to either centralize the design work, or centralize the selection of choices designers have. Some centralized teams publish a “style guide” to document these kinds of design constraints; it can include the vocabularies, styles, and interactions that are officially allowed.

How are interface models shared?
Deciding how the model of an interface should be shared means deciding how the work of API design should be persisted. For example, if you centralize this decision completely, you can decide that all API teams need to provide designs in the OpenAPI description format. This has the drawback of limiting all possible design choices to the options available in the OpenAPI Specification, but also makes it easier to share work between teams and use consistent tooling and automation across the system.

Documentation
No matter how well you design the interface of your API, your users won’t be able to get started without a little help. For example, you may need to teach users where the API is located on the network, what the vocabulary of the messages and interface is, and in what order they should make calls. The pillar of API documentation captures the work of creating this API learning experience. We call this pillar “API documentation” instead of “API learning” because the most popular API learning experiences are delivered in the form of human-readable documentation.

It’s worth providing good documentation for the same reason it’s worth designing a good interface: a better developer experience translates into more strategic value. If you don’t have good documentation, the API will be more difficult to learn and understand. If it’s too difficult to learn how to use, fewer people will use it. If they are forced to use it, the software they write will take longer to develop and is more likely to have bugs. Developing good documentation turns out to be a big part of creating a good developer experience.

DOCUMENTATION METHODS
You can deliver API documentation in a lot of different ways: you can provide an encyclopedia-like reference to the resources of your API: you can provide tutorials and conceptual content; you can even provide highly documented, complex sample applications for users to copy and learn from. There is an incredible amount of variety in the styles, formats, and strategies of technical documentation. To make things easier, we’ll split API documentation into two broad, fundamental practices: the teach don’t tell method and the tell don’t teach method. In our experience, you’ll need to adopt both approaches if you want to create the best learning experience for your users.

The tell don’t teach approach to documentation focuses on communicating facts about your API that will help users to use it. Documenting the list of your API’s error codes and providing a list of message body schemas it uses are both examples of this fact-based approach. This type of documentation gives your users a reference guide for your interface. Because it is highly factual, it is fairly easy to design and develop. In fact, you may be able to use tooling to produce this style of documentation very quickly, especially if the interface design has been serialized in a machine-readable format (see “API Description Formats”). Overall, this type of factual reporting of interface details and behavior requires less design effort and decision making from your team. The key decisions have to do with choosing which parts of the API need to be documented, rather than how to convey that information in the best way.

Conversely, the teach don’t tell approach to documentation focuses on designing a learning experience. Instead of just laying out the facts for readers to sift through, this approach provides a tailored learning experience to users. The goal is to help your API users achieve their usability goals while learning how to use your API in a focused, targeted manner. For example, if you own a mapping API, you could write a six-step tutorial that teaches your users how to retrieve GPS information for a street address. This way you can help them accomplish a fairly typical task with a minimum level of effort.

But documentation doesn’t have to be passive. References, guides, and tutorials are all helpful to read, but you can also deploy tooling that will help your users learn about your API in a more interactive way. For example, you can provide a web-based API explorer tool that allows your users to send requests to your API in real time. A good API explorer tool is more than a “dumb” network request tool; it guides the learning experience by providing a list of activities, vocabularies, suggestions, and corrections to the user. The big advantage of interactive tooling is that it shortens the feedback loop for users: the cycle of learning something, trying to apply what has been learned, and learning from the results. Without tooling, your users will need to spend time writing code or finding and using external tools, which can result in a much longer loop.

THE DEVELOPER PORTAL
In the world of APIs, a developer portal is the place (usually a website) where all the supplementary resources for an API are hosted. You don’t have to have a developer portal, but it can really help improve the developer experience for your API by giving users a convenient way to learn about and interact with your product.

INVESTING IN DOCUMENTATION
If you are only providing one type of API documentation, chances are that you are underserving your user community. Different users have different needs, and you’ll need to cater to each of them if you care about their learning experience. For example, new users can benefit a lot from the teach don’t tell approach to documentation because it’s prescriptive and easy to follow, but users who are experienced with your API will appreciate your tell don’t teach documentation because they can quickly navigate to the facts that they need. Similarly, interactive tools can appeal to users who enjoy a live experience, but won’t be great for users who prefer to understand and plan—or just have a preference for reading.

In practice, providing all of this documentation for your API can be costly. After all, someone has to design and write all of it—and not just once, but over the lifetime of your API. In fact, one of the difficulties of API documentation work is in keeping it synchronized with interface and implementation changes. If the docs are wrong, users can become very unhappy, very quickly. So, you’ll need to make smart decisions about how much of a documentation effort is sustainable for your API product.

The key factor in making your documentation investment decision should be the value of improving the API’s learning experience to your organization. For example, good documentation can help differentiate a public API product from its competitors. It can also be a big help for an internal API that is used by developers who aren’t familiar with the API owner’s system, business, or industry. The level of documentation investment for a public API operating in a competitive market will usually be higher than for an internal one, and that’s OK. Ultimately, you’ll need to decide how much documentation is good enough for your API. The good news is that it’s always possible to increase that investment as your API grows.

KEY DECISIONS FOR DOCUMENTATION GOVERNANCE
How should the learning experience be designed?
Decisions around learning experience design are often governed separately from the design, implementation, and deployment of an API. If you have lots of APIs, your users will appreciate having a single, consistent learning experience for all of them. But, centralizing this decision carries the usual costs: less innovation and more constraints for API teams as well as a potential bottleneck of centralized technical writing. You’ll need to balance the need for consistency against the amount of variety and innovation you need to support. One option is to introduce a hybrid model where most of the APIs have centralized documentation, but teams are allowed to create their own learning experiences if they are trying something new.

When should documentation be written?
There is a surprising amount of variability for when a team should start writing their documentation. Writing early is more expensive because of the likelihood of design and implementation changes, but it can expose usability problems early on, making it worthwhile. You’ll need to decide if this is a decision that can be safely decentralized, or one that needs more centralized management. For example, does every API regardless of its intended use need to have written documentation before it can be released? Or should teams use their best judgment to make that decision?

Development
The pillar of API development includes all of the decisions that you make when you bring your API to “life.” This is the hard work of developing your API’s implementation in a way that stays true to its interface design. The development pillar has an overwhelmingly large decision space. You’ll need to decide which technology products and frameworks you want to use to implement the API, what the architecture of the implementation should look like, which programming and configuration languages need to be used, and how the API should behave at runtime. In other words, you’ll need to design and develop the software of your API.

The truth is that your API’s users don’t care how you implement your API. All your implementation decisions about programming languages, tools, databases, and software design are meaningless to them; only the final product matters. As long as the API does what it is supposed to do in the way that it is supposed to do it, your users will be happy. The fact that you do that with a particular database or framework is just a triviality to your users.

But just because your users don’t care about your choices doesn’t mean that your development decisions aren’t important. In fact, development decisions matter a lot, especially for the people who have to build, maintain, and change the API over its lifetime. If you choose technologies that are difficult to use, or esoteric languages that no one in your company understands, the API will be more difficult to maintain. Similarly, if you choose tooling that is too stifling or languages that are just painful to program in, the API will be difficult to change.

When you think about the API development pillar, it’s easy to focus just on the choices you’ll make to build the first release of the product. That’s important, but it’s only a small part of the challenge. The more important goal is to make development decisions that improve the quality, scalability, changeability, and maintainability of your API over its entire lifetime. It takes experience and skill to develop software with that perspective, so you’ll need to make good investments in people and tools. After all, anyone can write a computer program after a few programming classes, but it takes a real professional to write programs that work at scale, in concurrent use, and that handle all the edge cases that come up in real life while remaining maintainable and changeable by other developers.

There aren’t any concrete rules for how you should design and architect your API software, just as there aren’t any concrete rules for designing software in general. But there is, of course, plenty of guidance, philosophy, and advice on how you should design your software. Generally, you can apply any good practices for server-based development to the API development space. The only thing that is particular to APIs is the healthy ecosystem of API-specific frameworks and tooling for developing instances. Let’s take a look at the types of options you have for taking advantage of these helpers.

USING FRAMEWORKS AND TOOLS
A large variety of tools are used in any typical development process, but for API development we’re interested in a specific category of tooling—the kind that helps you offload the API-related decisions and development effort involved in creating a new API release. This includes frameworks that make the job of writing API code easier as well as standalone tools that offer “no-code” or “low-code” implementation.

One tool that is particularly popular in the API management space is the API gateway. An API gateway is a server-based tool that is designed to reduce the cost of deploying APIs within a network. They are typically designed to be highly scalable, reliable, and secure—in fact, improving the security of an API implementation is often the primary motivation for introducing a gateway into a system architecture. They are useful because they can greatly reduce the cost of developing an API instance.

The cost of development goes down when you use a tool like a gateway because it’s built to solve most of your problems. In fact, in most cases, these tools require very little programming effort. For example, a decent HTTP API gateway should be ready to listen for request on an HTTPS port, parse JSON request bodies, and interact with a database right out of the box with only a little bit of configuration required to make it run. Of course, all of this doesn’t happen by magic; someone had to program this tool to do all these things. In the end, you’re shifting the cost of API development to an outside agency.

When tools work well they are a godsend. But the cost of using tools like API gateways is that they can only do what they are designed to do. Just like with any piece of machinery, your flexibility is limited to the functions that the machine provides. So, choosing the right tool becomes a very important development decision. If your API strategy and interface design take you in a direction of doing lots of nonstandard things, you may need to take on more of the development effort yourself.

THE INTERFACE AND IMPLEMENTATION RELATIONSHIP
Supporting the strategy and interface design of your API is really the primary goal for your development work. No matter how great your architecture is and how maintainable your code is, if the API doesn’t do what the interface design says it should, you’ve failed. We can draw two conclusions from this statement:

Conforming to your published interface design is an important quality metric for your implementation.

You’ll have to keep your implementation updated whenever you change the interface.

That means you can’t develop your API until you have an interface design. It also means that the people who are doing your development work need a reliable way of understanding what the interface looks like and when it changes. A big risk for your API product is if the design team decides on an interface design that is impractical or impossible to implement properly. If the interface designer and the implementation developer are the same person or on the same team it’s not such a big deal, but if that’s not the case, make sure that having the implementation team vet the interface is part of your API design method.

USING API DESCRIPTIONS CLOSE TO THE CODE
One way to improve your chances of keeping the implemenation and interface synchronized is to integrate the interface description into your implementation. For example, if you have an API description format that represents the interface design, you can keep that file in your code repository, or even develop an automated test that verifies your adherence to the interface. Taking this further, you can even generate a code skeleton based on the description format—although that’s really only effective for the first release.

You can also take the opposite approach: instead of receiving an interface description and using it with your code, you can embed the interface description by hand directly into your code. For example, some frameworks allow you to use annotations that describe an API interface. The combination of your code and the interface annotations can become the “source of truth” for your interface, and you can even use it to generate API documentation. Any of these approaches can be useful in helping to ensure that your implementation doesn’t break a promise that your interface design makes.



KEY DECISION FOR DEVELOPMENT GOVERNANCE
What can be used for the implementation?
This is the central governance question for implementation. It’s a broad question and includes a lot of decisions within it: Which databases, programming languages, and system components can you choose from? Which libraries, frameworks, and tools can be used to support the work? Which vendors do you have to work with? Are you allowed to use open source code?

At the time of this writing, there’s been a lot of interest in decentralizing these kinds of decisions to improve local optimization. We’ve heard from lots of companies who’ve found that their APIs are more efficient, easier to build, and easier to maintain when teams are given more implementation freedom. But decentralization comes with the usual costs: less consistency and fewer opportunites for system optimization. In practice, this means that it can be harder for people to move between teams, and there’s less opportunity to gain economies of scale and less visibility over the implementation in general.

In our experience, providing more implementation freedom is worth doing, but, you’ll need to consider how much decision freedom your system can afford. One way to make it easier to support decentralized implementation decisions is to centralize the selection element, which means centralizing the technology options while decentralizing the team’s selection and authority over them.

Testing
If you care at all about the quality of your API, you’ll need to expend some effort on testing it. In the pillar of API testing, you’ll need to make decisions about both what you need to test and how you’ll test it. In general, API testing is not very different from the typical quality assurance (QA) work that you’d do for a software project. You should be able to apply good software quality practices to the implementation, interface, and instances of your API just like you would for a traditional software application. But as with the development pillar, it’s the ecosystem of tools, libraries, and helpers that makes the API domain slightly different from the general testing space.

WHAT NEEDS TO BE TESTED?
The primary goal of testing your API is to make sure it can deliver on the strategic goal you should have defined during its creation. But as we’ve seen throughout this chapter, that strategic goal is enabled by the decision-based work of the ten pillars. Therefore, the secondary goal of API testing is to ensure that all of the work you’ve done across our pillars is of sufficient quality to support the strategy. For example, if the usability and learnability of your API are very low, that could impact a strategic goal of acquiring more API users. That means you need to define specific tests to assess the quality of the interface. You also need to test that the work you’ve done is internally consistent. For example, you’ll need to check that the implementation you’ve developed is consistent with the interface you’ve designed.

Here is a typical list of test categories that API owners use:

Usability and UX testing
Identify usability bugs in the interface, documentation, and discovery. For example: provide the API documentation to developers and perform “over the shoulder” observation testing while they try writing client code using it.

Unit testing
Identify bugs within the implementation at a granular level. For example: run a JUnit test against a Java method in the API implementation’s code on every build.

Integration testing
Identify implementation and interface bugs by making API calls against an instance. For example: run a test script that makes API calls against a running instance of the API in a development environment.

Performance and load testing
Identify non-functional bugs in deployed API instances and instance environments. For example: run a performance test script that simulates a production-level load against a running instance of the API in a production-like test environment.

Security testing
Identify security vulnerabilities in the interface, implementation, and instance of the API. For example: hire a “tiger team” to find vulnerabilities in a running instance of the API in a secure test environment.

Production testing
Identify usability, functionality, and performance bugs after the API product has been published in the production environment. For example: perform a multivariate test using the API documentation in which different users are served slightly different versions of content, and improve the usability of the documentation based on the results.

This certainly isn’t an exhaustive list, and there are lots of other tests you could do. In fact, even the tests we’ve described here could be exploded into many more subcategories. The big strategic decision you’ll need to make in the testing pillar is how much testing is good enough. Hopefully, your API strategy can help guide this decision. If quality and consistency are a high priority, you may find you’ll need to spend a lot of time and money testing your API before it can be released. But if your API is experimental, you can adopt a risk-tolerant approach and perform a minimum level of testing. For example, we’d expect the testing policy for an established bank’s payments API and a startup’s social networking API to be very different in scope.

API TESTING TOOLS
Testing can be expensive, so it’s helpful to adopt process improvements that make it easier to improve your product’s quality. For example, some organizations have had success with a “test-driven” method, where tests are written before the implementation or interface is created. The goal of this type of approach is to change the culture of a team to be test-centric, so that all design decisions result in a more test-friendly implementation. When it works, the net result is an API that is of higher quality because of its implicit testability.

In addition to process and cultural improvements, you can use tooling and automation to reduce the cost of performing tests. The most useful tools in the API testing arsenal are simulators and test doubles or mocks. That’s because the connected nature of API software makes it difficult to test things in isolation, so you’ll need some way of simulating other components. In particular, you’ll probably need tools to simulate each of these components:

Client
When you are testing your API, you’ll need something that can simulate the requests that will come from your API clients. There are lots of tools available that can do this for you. The good ones will give you enough configurability and variability to come very close to the types of messages and traffic patterns you’ll receive in production.

Backend
Chances are your API will have some dependencies of its own. That could be a set of internal APIs, a database, or a third-party, external resource. To perform integration testing, performance testing, and security testing you’ll probably need some way of simulating those dependencies.

Environment
You’ll also need some way to simulate your production environment when you are running preproduction tests. Years ago that could mean maintaining and operating a scheduled environment just for that purpose. Nowadays, many organizations use virtualization tools to make it cheaper to recreate environments for testing.

API
Sometimes you’ll even need to simulate your own API. That can be the case when you want to test one of your supporting components—for example, an API explorer in a development portal that makes calls against the API—but a simulated version of your API is also a valuable resource that you can give to your API’s users. This kind of simulated API is often called a sandbox, presumably because it’s a place where developers can have a play with your API and data without any consequences. It’s a bit of an investment to make, but it can greatly improve the developer experience for your API.

MAKE YOUR SANDBOX FEEL LIKE PRODUCTION
When you release a sandbox for your API’s users, make sure that your sandbox reproduces the production environment as closely as possible. You’ll have a much happier set of users if the only change they need to make when they finish writing code is to point it at your production instance. Nothing is more frustrating than spending a lot of time and energy troubleshooting an API integration only to find out that the production instance looks and behaves differently.

KEY DECISIONS FOR TESTING GOVERNANCE
Where should testing happen?
Over the years testing processes have become more and more decentralized. The big governance decision is to determine how much you want to centralize or decentralize for each of the types of API test stages we’ve described. Centralizing a testing process gives you more control, but comes with the cost of a potential bottleneck. Some of that can be alleviated with automation, but you’ll then need to decide who configures and maintains the automated system. Most organizations employ both centralized and decentralized systems. Our advice is to decentralize early test stages for speed and centralize the later stages for safety.

How much testing is enough?
Even if you decide that individual teams can run their own tests, you might want to centralize the decision of the minimum level of testing they need to do. For example, some companies use code coverage tools that provide reports on how much of the code has been tested. In terms of metrics and quality, coverage isn’t perfect, but it’s quantifiable and it allows you to set a minimum threshold that all teams need to meet. If you have the right people, you can also decentralize this decision and leave it up to individual API teams to do what’s right for their APIs.

Deployment
The implementation of an API is what brings the interface to life, but that implementation needs to be deployed properly in order to be useful. The pillar of API deployment includes all the work of moving the implementation of an API into an environment where your target users can use it. The deployed API is called an instance, and you may need to manage several of these instances to keep your API running properly. The challenge of API deployment work is in making sure that all your instances behave consistently, remain available to your users, and are as easy to change as possible.

The work involved in software deployment is a lot more complicated today than it was in the past. That’s mostly because our software architectures have grown increasingly complex, with more interconnected dependencies than ever before. On top of that, companies have pretty high expectations when it comes to availability and reliability of systems—they expect things to work all the time and every time. Oh, and don’t forget they’ll want changes to be released immediately. You’ll need to make good decisions about your API deployment system to meet all of those expectations.

DEALING WITH UNCERTAINTY
Improving the quality of an API deployment means making sure that your API instances behave the way users expect them to. Obviously, a lot of the work that goes into making that happen occurs outside the pillar of deployment. You’ll need to write good, clean implementation code and test it rigorously if you want to have fewer bugs in production. But sometimes, even when you take all those precautions, bad things happen in production. That’s because there is a high level of uncertainty and unpredictability to deal with for a published API.

For example, what happens if there is a sudden spike in demand for your API product? Will your API instances be able to handle the load? Or what if an operator inadvertently deploys an older version of an API instance, or a third party service your API depends on suddenly becomes unavailable? Uncertainty can pop up in lots of different places: from your users, from human error, from your hardware, and from external dependencies. Increasing deployment safety requires you to take two opposite approaches at the same time: eliminating uncertainty while at the same time accepting it.

A popular method for eliminating uncertainty in API deployments is to apply the principle of immutability. Immutability is the quality of being unable to change—in other words, being “read-only.” You can apply immutability in lots of ways. For example, if you never allow your operators to change a server’s environment variables or install software packages manually, you could say you have an immutable infrastructure. Similarly, you could create immutable API deployment packages; that is, a deployable package that can’t be modified, only replaced. The principle of immutability improves safety because it helps drive out the uncertainty introduced by human intervention.

However, you’ll never be able to eliminate uncertainty completely. You can’t predict every eventuality and you can’t test every possibility. So, a big part of your decision work will be in figuring out how to keep your system safe even when the unexpected happens. Some of this work happens at the API implementation level (e.g., writing defensive code), some of it happens at the landscape level (e.g., designing resilient system architecture), but a lot of work needs to happen at the deployment and operations level. For example, if you can continually monitor the health of your API instances and system resources, you can find problems and fix them before they impact your users.

DESIGNING RESILIENT SOFTWARE
One of our favorite resources for improving the safety of a deployed API is Michael Nygard’s book Release It! (Pragmatic Bookshelf). If you haven’t read it yet, make sure you do. It’s a treasure trove of implementation and deployment patterns for improving the safety and resiliency of your API product.

One kind of uncertainty that you’ll be forced to accept comes in the form of changes to the API. While it would be nice to freeze all changes once you’ve got your API working reliably, change is an inevitability that you’ll need to prepare for. In fact, deploying changes as quickly as possible should be a goal for your deployment work.

DEPLOYMENT AUTOMATION
There are really only two ways to make your deployments happen faster: doing less work and doing work more quickly. Sometimes you can do this by making changes to the way you work; for example, adopting a different way of working, or introducing a new type of culture. It’s hard, but it can really help. We’ll dive into this topic in more detail later, when we talk about people and teams in Chapter 7.

Another way to get faster is to replace human deployment tasks with automation. For example, if you automate the process of testing, building, and deploying your API code you’ll be able to perform releases at the push of a button.

Deployment tooling and automation can be a quick win, but be aware of the long-term costs. Introducing automation in your workflow is like introducing machinery into a factory—it improves efficiency, but it limits your flexibility. Automation also comes with startup and maintenance costs. It’s unlikely that it will work right out of the box and it’s unlikely it will adapt on its own to your changing requirements and context. So, when you improve your system with automation, be prepared to pay those costs over time—that means the costs of maintaining that machinery as well as eventually replacing it.

APIOPS: DEVOPS FOR APIS
A lot of what we’ve described in this section fits in well with the philosophy of DevOps culture. In fact, there’s even an emerging term for applying DevOps practices to API specifically called APIOps. We think that DevOps is a good fit for the API domain and worth learning from, no matter what you want to call it.

KEY DECISIONS FOR DEPLOYMENT GOVERNANCE
Who decides when a release can happen?
The question of who gets to release is central to deployment governance. If you have talented people you can trust, an architecture that is fault tolerant, and a business domain that can excuse the occasional failure, you could completely decentralize the decision. Otherwise, you’ll need to figure out which parts of this decision need to be centralized. Distribution of this decision is usually nuanced. For example, you could enable “push to release” for trusted team members, or release to a test environment where a centralized team can make a “go/no-go” decision. Distribute in a way that fits your constraints and enables the most speed, with the right level of safety at scale.

How are deployments packaged?
In recent years, the question of how software is packaged and delivered has become enormously important. It’s turned out to be the kind of decision that can gradually shift an entire system in another direction. For example, the growing popularity of containerized deployment has made it cheaper and easier to build immutable, cloud-friendly deployments. You’ll need to consider who should be making this important decision for your organization. A decentralized, locally optimized decision maker may not understand the impacts to security, compatability, and scale, but a purely centralized decision maker may not have a solution that fits the variety of implementations and software being deployed. As usual, some type of choice constraint and distribution of the decision is useful.

Beyond just the question of centralization and decentralization, you’ll also need to consider which team is best placed to make the highest-quality decision. Should the operations and middleware teams define packaging options? An architecture team? Or should the implementation teams make the decision? Talent distribution is a key factor here: which teams have the people who can make the best assessments?

Security
APIs make it easier to connect software together, but they also introduce new problems. The openness of APIs makes them a potential target and presents a new kind of attack surface. There are more doors to enter, and the treasure is bigger! So, you’ll need to spend some time improving the security of your API. The pillar of API security focuses on the decisions you’ll need to make to accomplish the following security goals:

Protecting your system, API clients, and end users from threats

Keeping your API up and running for legitimate use by legitimate users

Protecting the privacy of data and resources

These three simple goals hide an enormously complex subject area. In fact, a big mistake that API product owners make is in assuming that securing an API simply means making a few technology decisions. Now, we don’t mean to say that technology decisions about security aren’t important—of course they are! But if you really want to strengthen your API security pillar, you’ll need to broaden the context of security-based decision making.

TAKING A HOLISTIC APPROACH
To truly improve the security of your API you’ll need to make it part of the decision-making process for all of the pillars we’ve described in this chapter. A big part of doing that is the work of implementing security features at runtime. For a start, you’ll need to extract identities, authenticate clients and end users, authorize usage, and implement rate limits. You can write a lot of this yourself, or you can take the safer and faster approach of implementing tooling and libraries that do it for you.

But API security includes a lot of things that happen outside of the client–API software interaction. Cultural changes can improve security by instilling a security-first mentality in engineers and designers. Processes can be implemented to prevent insecure changes from making it to production or staying in production. Documentation can be reviewed to make sure that it doesn’t leak information inadvertently. Sales and support staff can be trained to not inadvertently provide private data or assist in a social engineering attack.

Of course, what we’ve just described is much bigger than the traditional domain of API security. But the truth is that API security can’t exist on its own. It’s part of an interconnected system and needs to be considered as one element of a holistic security approach for your company. It doesn’t do any good to pretend that it’s an island on its own with no connection to your bigger security strategy. The people who want to exploit your system certainly won’t be treating it that way.

So, you’ll need to make decisions about how to integrate your API work with the security strategy within your company. Sometimes that’s pretty easy to do, and other times it’s more difficult. One of the big challenges for APIs is in balancing the desire for openness and usability with the desire to lock things down. How far you go either way should be a product of your organizational strategy and the strategic goals of your API.

KEY DECISIONS FOR SECURITY GOVERNANCE
Which decisions need to be authorized?
All of the decisions that people make in your organization have the potential to introduce a security vulnerability, but it’s impossible to scrutinize every decision that’s being made. You’ll need to determine which decisions have the biggest impact to the security of your API and make sure those decisions are the best ones. That’s going to depend a lot on your context. Are there “trusted” zones in your architecture that need to have secure “edges”? Are designers and implementers already experienced in good security practice? Is all the work happening in-house or are you working with third-party implementers? All of these contextual factors can change your decision authorization focus.

How much security does an API need?
A big part of the apparatus of security is the standardization of work decisions to protect the system and its users. For example, you might have rules about where files can be stored or which encryption algorithms should be used. Increased standardization decreases the freedom for teams and people to innovate. In the case of the security context this is usually justified by the impact of making a single bad decision, but not all APIs necessarily need the same level of scrutiny and protection. For example, an API that is used by external developers for financial transactions will need more of a security investment than an API used for logging performance data. But who makes that decision?

As usual, context, talent, and strategy are the key considerations. Centralizing this decision allows a security team to make a blanket assessment based on their understanding of the system context. However, sometimes these kind of generalized rules make it possible for things to slip between the cracks—especially when API teams are doing new and innovative things that the centralized team couldn’t have accounted for. If the decision is distributed, the teams themselves can make an assessment decision, but this requires a decent level of security knowledge within the team itself. Finally, if you are operating in a domain that prioritized security and risk mitigation, you might end up forcing the highest level of security upon everything, regardless of the local context and impact to speed.

Monitoring
Fostering the quality of observability in your API product is important. You can’t properly manage your API unless you have accurate and up-to-date information about how it is performing and how it is being used. The pillar of API monitoring is all about the work you need to do to make that information available, accessible, and useful. Over time and at scale, monitoring API instances turns out to be just as essential to API management as the design of the interface or development of the implementation—if you’re in the dark, you can’t help but stumble and fall.

There are plenty of things that can be monitored in an API instance:

Problems (e.g., errors, failures, warnings, and crashes)

System health (e.g., CPU, memory, I/O, container health)

API health (e.g., API uptime, API state, and total messages processed)

Message logs (e.g., request and response message bodies, message headers, and metadata)

Usage data (e.g., number of requests, endpoint/resource usage, and requests per consumer)

LEARNING MORE ABOUT MONITORING
With the exception of API and usage monitoring, the types of measurements we’ve described aren’t unique to API-based software components. If you’re looking for a good guide to monitoring network-based software components, we encourage you to read Google’s Site Reliability Engineering (O’Reilly). It’s a great introduction to designing software systems and includes a pretty comprehensive list of the types of things you should be monitoring. Another good resource to take a look at is Weaveworks’s RED Method, which identifies three categories of metrics for a microservice: rate, errors, and duration.

Each of these groups of metrics will help your API in different ways. Health and problem data will help you detect and deal with faults, hopefully reducing the impact of any problems that arise. Message processing data can help you troubleshoot API and system-level issues. Usage metrics can help you improve your API product by helping you understand how your users are actually using your API. But first, you’ll need to put in the work of making that data available. Of course, you’ll also need to make sure you have a reliable way of gathering all that data and presenting it in a usable way.

The more data you can produce, the more opportunities you’ll have to learn and improve your product. So, ideally you’d produce a never-ending stream of data for your API. The costs of data production, harvesting, storage, and analysis can really add up, though, and sometimes those costs are just unbearable; for example, if the round-trip time of your API doubles because it needs to log data, you’ll need to pare down some of your logging or find a better way to do it. One of the more important decisions you’ll need to make is what you can afford to monitor given the known costs.

Another important decision is how consistent your API monitoring will be. If the way that your API provides monitoring data is consistent with other tools, industry standards, or organizational conventions it will be much easier to use. Designing the monitoring system is a lot like designing an interface. If your monitoring interface is completely unique, it will take longer to learn how to use it and gather data. That’s OK when you have a single API and you are the only one monitoring it, but at the scale of tens or hundreds of APIs, you’ll need to reduce that monitoring cost. We’ll explore this idea more in Chapter 6.

KEY DECISIONS FOR MONITORING GOVERNANCE
What should be monitored?
The decision of what to monitor is a big one. You can leave it up to individual teams in the beginning, but at scale, you’ll benefit if you have consistency in your API monitoring. Consistent data will improve your ability to observe system impacts and system behavior. That means you’ll need to centralize some of this decision making.

How is data collected, analyzed, and communicated?
Centralizing the decisions on monitoring implementation will make it easier to work with API data, but it can inhibit the freedom of API teams. You’ll need to decide how much of this decision should be centralized and how much of it should be distributed and decentralized. This becomes especially important when sensitive data is involved that needs to be protected.

Discovery and Promotion
An API is only valuable if it is being used, but to be used it first needs to be found. The pillar of API discovery is all about the work it takes to make your APIs easier to find for your target users. This means helping users to easily understand what your API does, how it can help them, how they can get started, and how they can invoke it. Discovery is an important quality of your API’s developer experience. It requires good design, documentation, and implementation choices, but you’ll also need to do some additional discovery-specific work to really improve the findability of your API product.

In the API world, there are two major types of discovery: design time and runtime. Design-time discovery focuses on making it easier for API users to learn about your API product. That includes learning about its existence, its functionality, and the use cases that it can solve. Conversely, runtime discovery happens after your API has been deployed. It helps software clients find the network location of your API based on some set of filters or parameters. Design-time discovery targets human users and is primarily a promotion and marketing exercise. Run time discovery targets machine clients and relies on tooling and automation. Let’s take a look at each of them.

RUNTIME DISCOVERY
Runtime discovery is a way of improving the changeability of your API landscape. If you have a good runtime discovery system, then you can change the location of your API instances with very little impact to the API’s clients. This is especially useful if there are lots of API instances running at the same time—for example, microservices-style architectures often support runtime discovery to make finding services easier. Most of the work you’ll need to do to make this happen is in the development and deployment pillars of an API.

Runtime discovery is a useful pattern for you to know about and is worth implementing if you are managing a complex system of APIs. We won’t have time to go into the implementation details of how to make it work, but it does require a technology investment at the landscape, API, and consumer levels. For the most part, when we talk about the discovery pillar in this book, we’re talking about design-time discovery.

DESIGN-TIME DISCOVERY
To help people learn about your API at design time you’ll have to make sure you have the right kind of API documentation available. Documentation about what your API does and which problems it solves should be easily available to users who are looking for it. This kind of product marketing “copy” is an essential part of discovery, but it’s not the only thing that matters. Helping your users find that information in the first place turns out to be a critical part of this pillar. You’ll need to engage with your user community and market to them to be successful. How you do that depends a lot on the context of your user base:

External APIs
If your API is primarily being used by people who don’t work in your group or organization, you’ll need to invest in getting your message to them. This means marketing your API product in much the same way you’d market a piece of software: search engine optimization, event sponsorship, community engagement, and advertising. Your goal is to make sure that all of your API’s potential users understand how your product can help them address their needs. Of course, the specific marketing actions you take will depend a lot on your context, the nature of the API, and the users that you are targeting.

For example, if you are developing an SMS API product and competing for developer-users, then you’ll advertise in the places you expect your potential users to be: web developer conferences, blogs about two-factor authentication, and telecom conferences. If you are targeting independent developers you might rely on digital advertising, but if you’re aiming for large enterprises you might invest in a team of salespeople and their network of relationships. If you are competing in a crowded market, you’ll probably need to expend a lot of effort to differentiate yourself, but if your product is unique you may only need a little bit of search engine optimization magic to get people in the door. When it comes to product marketing, context is king.

Internal APIs
If your API is being used by your own developers, you probably have a captive audience. But that doesn’t mean you can ignore discoverability for your API. An internal API has to be discovered to be used, and over time if it’s too difficult to find you’ll run into problems. If internal developers don’t know about it, they won’t be able to use it and might even waste time making another API that does the same thing as yours. A competitive market of APIs internally is usually a healthy sign, and reusability is often overvalued in enterprises. But if people in your company are duplicating perfectly good APIs only because they don’t know about them, it’s a drain on resources.

Internal APIs can be marketed in much the same way as external APIs. Only the marketing ecosystem is different. While you’ll probably target the Google search engine with an external API, for an internal API you may just need to get on the corporate spreadsheet that lists the company’s APIs. Sponsoring a developer conference can be effective for an external API, but a better strategy for an internal API might be to just visit all the dev teams in the company and teach them about your API.

A big challenge for marketing internal APIs is often the lack of maturity and standardization in the organization. In truth, if you are marketing your APIs in a large enterprise, there is a very good chance that there is more than one API list floating around. To do a good job, you’ll need to make sure that your API is on all of the various lists and registries that matter. Similarly, learning about and getting time with all of the development teams in your company may be difficult in practice, but if usage of your API matters to you, it’s worth making the investment.

KEY DECISIONS FOR DISCOVERY GOVERNANCE
What will the discovery experience look like?
You’ll need to design a good discovery experience for your API’s users. That means deciding on discovery tools, user experience, and a target audience. At scale, you’ll also need to decide how consistent this experience should be—if you need high consistency, you may need to centralize the design decisions.

When and how are APIs advertised?
Marketing an API has a time and effort cost, so you’ll need to decide who should decide when to market an API. You can leave it up to individual API teams, or you can make that decision centrally. If you’re distributing the decision to your teams, you’ll need to make sure that any centralized discovery tools and processes don’t inhibit them from their discovery goals.

How is the quality of the discovery experience maintained?
Over time, as APIs change, the information in any discovery system becomes less accurate. Whose job is it to ensure that the discovery system is accurate? Who will make sure that the user experience doesn’t degrade at scale and over time?

Change Management
If you never had to change your API, the job of managing an API would be pretty easy. But APIs need to be fixed, updated, and improved, and you’ll always need to be ready to change yours. The pillar of change management includes all the planning and management decisions you’ll need to make when dealing with change. It’s a vitally important and complex domain—in fact, the pillar of change management is what this book is really about.

Generally speaking, there are three goals for change management:

Choosing the best changes to make

Implementing those changes as fast as possible

Making those changes without breaking anything

Choosing the best changes means making changes that enable your API’s strategic goals. But it also means learning how to prioritize and schedule change based on costs, contexts, and constraints. That’s really the work of managing a product, and it’s one of the reasons we introduced the concept of the API as a product in the previous chapter. If you set clear strategic goals and identify your target user community, you can make better decisions about which changes are the most valuable. As you learn more about the work in each of the other nine pillars, you’ll get better at understanding the costs. Armed with good information about cost and value, you’ll be able to make smart product decisions for your API.

Balancing change safety with change speed is a difficult proposition, but it’s what you’ll need to do. Each of the decisions you make in the pillars of an API product has an impact on the speed or safety of change. The trick is to try and make decisions that maximize one with a minimum cost to the other. In Chapters 5, 6, and 7 we’ll explore this idea further from the perspective of change costs, making changes over time, and the impact of organizations and culture on change. Then, in the last chapters of this book we’ll introduce an added complexity: scale. Chapters 8, 9, and 10 address change management for a landscape of APIs instead of just one.

Implementing changes is only half the work of change management. The other half is letting people know that they have more work to do because you’ve changed something. For example, if you change an interface model, you’ll probably need to let your designers, developers, and operations teams know that there is some new work headed their way. Depending on the nature of the change, you’ll likely need to let your users know that they may need to update their client software too. The usual way of doing this is by versioning your API. How you version depends a lot on the style of your API and the protocols, formats, and technologies you are using; we’ll talk about this more in “Versioning”.

KEY DECISIONS FOR CHANGE MANAGEMENT GOVERNANCE
Which releases need to be fast and which need to be safe?
An important governance decision is how to treat different types of change. If you centralize this decision, you can create a consistent rule that allows for different release processes depending on their impact. Some people call this approach “bimodal” or “two-speed,” but we believe there are more than two speeds in a complex organization. You can also decentralize this decision and let individual teams assess impact on their own. The danger of decentralizing is that your teams may not be able to accurately assess the impact on the system, so you’ll need to make sure you have a system architecture that is resilient.

Summary
In this chapter we took a tour of the ten pillars that form the foundation of API product work. Each pillar contains a set of decision work that has an impact on the final API product. Not all the pillars necessarily require the same amount of work effort, and you’ll need to decide how important each pillar is depending on the context and goals for your API. As your landscape of APIs grows, you’ll also need to think about how the decisions in each of these pillars should be distributed. We’ll say more about that in Chapter 10.

But before we get there, we’ll need to explore our tenth pillar, change management, in more detail. What is the cost of making changes to an API? We’ll dive into that in the next chapter.