---
id: doc7
title: Chapter 7. API Teams
---

Great things in business are never done by one person. They’re done by a team of people.

Steve Jobs

You may have noticed that we’ve put off discussion about how you create, populate, and manage teams for your API program. While this is a very important topic, it turns out to be quite a challenge to collect and reflect general information about such a personal and organization-dependent topic. Each company has its own way of managing people, its own boundaries within the organization (divisions, products, services, sections, teams, etc.), and its own way of creating some form of hierarchy to manage its people. All these variables make it hard for us to come up with just one set of recommended practices for building successful API teams.

However, by talking with several companies we have been able to identify some general patterns and practices that we can share. In our observations, organizations all use some form of teams, titles, and job roles to describe the work they need to get done and assign that work to the people responsible for doing it. We don’t find much consistency in the titles companies use for the members of teams, but what we do find is fairly consistent across companies is a set of roles for handling tasks within a team. In other words, no matter what titles people have, the same kinds of work need to be done.

This idea of focusing on roles rather than titles is echoed by software architect, author, and trainer Simon Brown. When referring to software architecture in particular, he says, “Becoming a software architect isn’t something that simply happens overnight or with a promotion. It’s a role, not a rank.”

In our experience this sentiment applies to all the roles on an API team. For that reason, we’ll start this chapter with what we call a common set of API roles. Similar to the way we presented the API pillars (see Chapter 4), we see these roles as representing common tasks and responsibilities; ones that someone in your organization needs to take on. For that reason, we’ll also spend time discussing how the API pillars match up to the API roles we define here.

We also find that, in some cases, the exact makeup of the API team can vary based on the maturity of the API they are working on. For example, in the early create stage (see “Stage 1: Create”) you don’t need to focus on testing or DevOps, and in the maintain stage (see “Stage 4: Maintain”) there is usually not much work for frontend or backend developers. So, we’ll review the mix of API roles you can expect to need as each of your APIs travels through its lifecycle.

Another important aspect to all this is how API teams interact with each other. Most of the companies we work with offer some coordinating body or “team of teams” that helps keep all the teams (no matter where their APIs are in their lifecycle), keep up with each other, manages interoperability, and encourages collaboration. This additional process of “engineering the engineers” will be covered in depth in the next few chapters as we introduce our notion of the API landscape.

Finally, a big part of making teams work well together falls under the name “company culture.” This is another area we find successful companies invest time and resources into managing. As was discussed in Chapter 2, one of the ways to scale up API governance is to distribute some of the decision making. One way to ensure consistency in decision making in this distributed environment is to pay close attention to the company culture and—where needed—learn to nudge that culture in positive directions. In the last section of this chapter we’ll spend time on some key concepts we see organizations use to help them identify, monitor, and influence company culture in order to improve the overall effectiveness of their API programs.

But to start out, let’s identify the set of common roles we find in most API teams and how these roles can be applied to make sure you cover the API pillars we talked about in Chapter 4.

API Roles
Just as we showed you a set of common skills for dealing with the aforementioned API pillars, we have also put together a set of common roles for dealing with APIs. In this chapter, the roles are presented as a set of job titles. However, our experience is that titles for API positions are not very standardized across companies. An API program manager in one company is called the API owner in another company, the API architect at company B is called the product architect at company Z, and so forth.

For that reason, the titles we’re using here may not correspond to the titles in your company. However, we’re pretty sure the actual roles do exist somewhere in your organization—or at least they should. That’s because, just as we stated that the API pillars were all skills that are common to successful API programs, the roles we’re describing here are the ones you’ll need to make sure someone on the team is responsible for.

That means while you are reading this list of API roles (and the titles we gave them), you can do the work of associating them with their equivalents in your own organization. That’s a really good exercise, by the way. If you go through your list of job titles and descriptions and find that one or more of our roles isn’t represented, that’s a pretty good indication that you have an opportunity to enhance your organization’s job descriptions to make sure all the responsibilities we list here are covered somewhere in your list of API-related jobs.

SCOPE OF RESPONSIBILITY
It is also important to keep in mind that these roles each represent a defined scope of responsibility. When someone takes on a role, they take on the responsibility for all the tasks within the scope of that role. And most of the tasks involve decision making with a particular skill set (designing, development, deployment, etc.).

With that explanation as a backdrop, let’s go through our list of API roles to establish a basic understanding of the kind of responsibilities involved in a healthy API program. You’ll notice that we’ve divided the list up into two parts:

Business roles

Technical roles

This division may seem a bit arbitrary, and it might not track with the way your company arranges job titles and responsibilities. But we think it can help to point out which roles tend to lean more toward meeting business objectives (OKRs) and which roles tend more toward meeting technical objectives (KPIs). We talked how the two relate to each other and their use in managing your APIs in “OKRs and KPIs”.

A REMINDER ABOUT ROLES AND TITLES
Remember, the job titles we list in this book were invented for the purpose of reinforcing the connection between API roles and the API pillars from Chapter 4. The roles and job titles within your own company will likely be different from the ones we use here; however, the API pillars we covered earlier are all skills and responsibilities your company will need to cover. How you associate the pillars with your own job roles and titles is an exercise we leave to you, the reader.

Business Roles
The first group of roles we’ll review are the ones we call business roles. The people who take on these roles are primarily focused on the business side of the APIs. They often have the responsibility of speaking in the customer’s voice, aligning the product with clear strategic goals (e.g., promoting new products, improving sell-through, etc.), and matching APIs with company-wide OKRs. Sometimes the people fulfilling these roles will come from the business or product parts of your company. Other times, they will come from within the IT ranks. The important difference between these roles and the technical roles we’ll cover next is that business roles focus first on business objectives.

We’ve defined five business roles to represent the decision-making responsibilities we see in healthy API programs:

API product manager
The product manager (PM)—sometimes called the product owner—is the main point of contact for the API. This is in keeping with the API-as-a-Product (AaaP) approach we covered in Chapter 3. They are responsible for making sure the API has clear OKRs and KPIs and that the other members of the team are in place to support the needed API pillars (Chapter 4). The PM is also responsible for monitoring the API and shepherding it successfully through the full API lifecycle (Chapter 6). The API PM role is in charge of defining and describing to the rest of the team the what of the API (or jobs-to-be-done). It will be the technical roles on the team that will be responsible for the how. PMs are also responsible for ensuring the expected developer experience (design, onboarding, and ongoing relationship) meets the needs of the API consumers. The PM’s role is to make sure all the moving parts come together as expected.

API designer
The API designer is responsible for all aspects of the design. This includes making sure the physical interface is functional, usable, and offers a positive experience for developers. The designer also needs to make sure the API helps the team to achieve the identified business OKRs. In some cases, the designer will work with the technical roles to make sure the design helps the team meet the technical KPIs, too. Often the designer is the first line of contact for API consumers and may be responsible for taking on the “voice of the consumer” when helping the team make decisions about the look and feel of the API. Finally, the designer may be called upon to make sure the overall design matches established company-wide style guidelines.

API technical writer
The API tech writer is responsible for writing the API documentation for all stakeholders connected with the API product. This includes not just the API consumers (e.g., the developers using the end product) but also the internal team members as well as other stakeholders from the business community (e.g., the CIO, CTO, etc.). Most tech writers will come from a technical background and have some programming experience, but this is not always the case, nor is it always required. It is important for tech writers to be effective communicators as well as effective researchers and interviewers, since they often need to understand the point of view of both the API providers and the API consumers. For this reason, tech writers often work closely with the API designer and product manager to make sure the documentation is accurate, up to date, and in keeping with the company’s design and style guidelines.

API evangelist
The API evangelist is responsible for promoting and supporting the API practice and culture within the company. This is especially true in large organizations where internal users do not have easy access to the original API team that created the product. Evangelists make sure all internal developers using the API understand it and can accomplish their goals with it. Evangelists are also responsible for listening to API consumers and passing their feedback on to the rest of the product team. In some cases, evangelists may be responsible for creating samples, demos, training materials, and other support activities in order to maximize the developer experience for those using the product.

Developer relations
The developer relations role, sometimes called the developer advocate or DevRel role, is usually focused on external use of the API (i.e., outside the company that created it). Like the API evangelists, DevRel staff are responsible for creating samples, demos, training materials, and other assets to help promote the use of the product. And like evangelists, DevRels are often the ones responsible for listening to API consumers and helping turn their feedback into fixes or features that the API team can deal with. However, unlike internal evangelists, DevRels are also often tasked with “selling” the API product to a wider audience, and as such may participate in customer onsites, presales activities, and ongoing product support for key customers. Additional duties can include speaking at public events, writing blog posts or articles on how to use the product, as well as other brand-awareness activities in order to help the team reach their stated business goals.

While these five roles are often aligned with business goals and strategies, as you can see from the descriptions, most of the roles still rely on some level of technical knowledge and skill in order to meet their objectives. The next set of roles we’ll review are focused directly on the technical aspects of creating, deploying, and maintaining the API product.

Technical Roles
The second set of roles we defined are what we call technical roles. These roles are focused on the technical details of actually implementing the API’s design, testing and deploying it, and maintaining it in a healthy, usable state throughout its active life. Typically these roles are responsible for speaking in the voice of the IT department, including advocating for safe, scalable, and secure implementations that can be properly maintained over time. Often, the technical staff are responsible for achieving important KPIs as well as helping the business staff reach their OKRs.

Even though we’ve divided our list of roles into two distinct groups, there are some parallels between the business roles and the technical roles. For example, the business role of product manager has a parallel in the lead API engineer on the technical side. And both groups of API roles have, as their ultimate goal, the creation and deployment of a technically stable and economically viable API product.

We’ve defined six technical roles to represent the key decision making involved in the work of implementing, deploying, and maintaining successful APIs:

Lead API engineer
The lead API engineer is the key point of contact for all the work related to the development, testing, monitoring, and deployment of the API product. This role is the technical equivalent of the product manager business role. Just as the PM is responsible for the what of the API—the design and business goals—the API lead engineer is responsible for the how of the API—the technical details of what it takes to build, deploy, and maintain the API. The lead engineer is the one with the responsibility to coordinate the other technical members of the team.

API architect
The API architect is responsible for the architectural design details for the API product itself as well as making sure that the API can easily interact with required system resources, including APIs from other teams. It is the responsibility of the API architect to advocate for the overall software and system architecture of the entire organization. This includes supporting the security considerations, stability and reliability metrics, protocol and format selections, and other so-called nonfunctional elements that have been established for the company’s software systems.

Frontend developer
The frontend API developer (FE) is responsible for making sure the API offers a quality consumer experience. That means helping to implement the company’s API registry, consumer portal, and any other activities related to the frontend or consumer end of the API. Similar to the designer role on the business side, the FE has the job of advocating for API consumers, but from the technical point of view.

Backend developer
The backend developer (BE) is reponsible for the details of implementing the actual interface of the API, connecting it to any other services it needs to complete its work, and generally faithfully executing on the vision of the PM and API designer’s description of what the API should do and how it should do it. It is the responsibility of the BE to make sure the API is reliable, stable, and consistent once it is placed into production.

Test/QA engineer
The API test/QA (quality assurance) engineer is responsible for everything related to validating the API design and testing its functionality, safety, and stability. Typically the test/QA role is charged with writing (or helping the FE/BE write) the actual tests and making sure they run effectively and efficiently. Often this testing goes beyond simple bench tests and behavior testing and includes making sure there are tests for interoperability, scalability, security, and capacity. Typically this involves the use of testing frameworks and tooling selected by the test/QA community within the company.

DevOps engineer
The DevOps role is responsible for every aspect of the building and deployment of the API. This includes monitoring the API’s performance to make sure it is in line with the stated technical KPIs and is properly contributing to the business-level OKRs. This usually means working the delivery pipeline tooling, authoring build scripts (or teaching others how to do this), managing the release schedule, archiving the build artifacts, and supporting any rollbacks of broken releases, if needed. The DevOps role is also responsible for maintaining a dashboard showing real-time monitoring data as well as storing and, when needed, mining offline API logs to aid in the review, diagnosis, and repair of any problems identified while the API is in production. Depending on the company’s production hosting options, DevOps staffs will need to support several environments, including desktop, build, test, staging, and production. This may include both on-premise and cloud systems.

In this section, we introduced the idea of thinking about the work to be done over the life of your API as a set of roles, or scopes, of responsibility. To make things a bit easier for our discussion, we came up with two sets of roles (business and technical) and gave these roles names that look like typical job titles.

As we mentioned at the start of this section, the roles are just that—they identify areas of expertise that need to be covered within your API programs. We’ll look at this aspect of team composition next.

API Teams
In the previous section, we identified 11 roles that represent scopes of responsibility. Teams need people to fill these roles in order to cover all the important aspects of managing APIs throughout their lifecycle. However, a role is different from an actual person on a team. You might not need every role on the team represented by a unique person. Some people may be able to cover more than one role. For example, in many organizations, both the API evangelist and the developer relations role can be handled by the same person. Another example is that some small teams may rely on a single person to fulfill both the test/QA and DevOps roles.

PEOPLE CAN BELONG TO MULTIPLE TEAMS
Although we are going to describe some specific teams in this section, it’s up to you to decide how you want to distribute people amongst these teams. It’s perfectly fine to fill each API team with full-time, dedicated members, but it’s also fine to allow people to be members of multiple teams at the same time. Later in this chapter, we’ll share the story of Spotify’s “squads, tribes, chapters, and guilds” model that takes a matrix approach to team membership.

Also, your team may not need to cover all the roles throughout all the API maturity stages (see Chapter 6). For example, in the maintain phase of the API lifecycle, you usually do not need much help from frontend and backend developers. And for some organizations, some of the roles are not hosted directly in the team, but are filled by “floating” staff shared within the company. For example, the role of designer might be filled by one of the business-side product design people who works in an on-demand basis for any API team that needs design work.

Teams and API Maturity
In each stage of the API product lifecycle, some roles play a primary role and some play only a secondary or supporting role. Primary roles are the ones that make the biggest impact with their decisions. For example, in the create stage, almost everyone on the team has important responsibilities, but the designer’s decisions about the interface design strongly influence all of the other work.

Primary roles are also the ones responsible for the work that must be done in an API. For example, in the publish stage, the API can’t be deployed unless someone takes on the DevOps role and builds a deployment architecture.

As you can see, team population is greatly affected by the API’s maturity and the roles needed at any one time. With that in mind, let’s go through the API lifecycle stages from Chapter 6 and identify the primary and secondary roles in each, along with the types of activities that each of these roles will be responsible for.

STAGE 1: CREATE
Primary role(s)
Product manager, designer, API lead

Secondary role(s)
API evangelist, DevOps, API architect, backend developer

The create stage is your opportunity to come up with a foundational strategy and the best interface design at a time when you won’t impact real users. To come up with the best API strategy you’ll need someone with a good understanding of the organizational context and the API product domain, and the ability to set the best course of action. That person is usually the product manager. A good API product manager will have enough experience to identify an API goal that can help the sponsoring organization as well as the tactical plan that will enable it.

The designer role is a natural fit for the work of designing an interface. A good API designer will be able to make high-quality decisions about the interface model’s design based on their experience. That means making decisions about how the model should look and also decisions about how the design assumptions should be tested and validated. Most importantly, a good designer will have a sense of how much design investment is needed based on the context of the situation.

In addition to the work of designing the interface, someone will need to develop the first implementation of the API. Some of that work will be experimental and exploratory in nature. For example, the designer might decide that a prototype should be developed to try out the design. But there is also a need to build the first implementation of the API. This is the implementation that will eventually be released to the public in the subsequent publish stage. This development work usually involves a team of people, but is orchestrated by the API architect and API lead roles.

Table 7-1. Primary activities in the create stage
Activity	Role(s)
Develop the strategy

Product manager

Design the interface model

Designer

Develop the initial implementation

API architect, API lead, backend developer

Table 7-2. Supplementary activities in the create stage
Activity	Role(s)
Develop prototypes

API lead, backend developer

Test the implementability of the design

API architect, API lead, backend developer, technical writer

Test the security of the design and implementation

API architect, test/QA engineer

Test the marketability of the design

API evangelist, DevRel

Test the usability of the design

Designer

Plan and execute a testing strategy for the implementation

API lead, test/QA engineer

STAGE 2: PUBLISH
Primary role(s)
Product manager, API technical writer, DevOps

Secondary role(s)
Frontend developer, designer, backend developer, API evangelist, DevRel

Reaching the publish stage means you’re ready to let users have access to your product. To get this work going you’ll need people with expertise in deployment, documentation, and discovery activities. There are also a host of supplementary activities that you’ll want to cover if the API is valuable and you have the bandwidth to do it.

Getting an initial set of documentation published is an important piece of work in this stage, so you’ll need someone who can handle the role of technical writer to do the work of writing and publishing the docs. The technical writer is a key role in the publish stage. A good writer will make it easier for prospective users to get started and for existing users to work faster. That’s something that you’ll definitely want in this stage because it will help you reach the realize stage faster.

Getting the API published means that instances of the API will need to be deployed. That’s typically the job of the DevOps engineer role. The DevOps engineer’s responsibility in this stage includes designing the deployment process, monitoring solutions, and deployment architecture for the API instance.

Finally, the product manager will need to trigger the publishing event. Depending on your API and context, that means for your API and your context. It could mean registering the API in an internal service catalogue, sending an email to your prospective users, or something else. However it’s done, it’s the PM’s responsibility to make sure that it happens.

Beyond these primary activities are a set supplementary activities that will improve the quality of the API product. The documentation and other supporting assets are going to need to live somewhere, so lots of organizations implement a developer portal at this stage. Once the API is actively used, you’ll be able to improve the design and implementation based on the usage data (the monitoring pillar). It’s also a good idea to continue to drive usage by performing marketing and discovery work.

Table 7-3. Primary activities in the publish stage
Activity	Role(s)
Write and publish documentation

Technical writer

Design the deployment architecture and deploy instances

DevOps

Publish the API (i.e., make it officially discoverable)

Product manager

Table 7-4. Supplementary activities in the publish stage
Activity	Role(s)
Design and implement a portal

Frontend developer

Market the API

API evangelist, DevRel

Gather design feedback from users

API evangelist, DevRel

Improve the interface design

Designer

Collect usage information from deployed instances

API lead, DevOps

Improve and optimize the implementation

API lead, backend developer

Test the security of the implementation and deployment

API architect, test/QA engineer

STAGE 3: REALIZE
Primary role(s)
DevOps, product manager

Secondary role(s)
Designer, test/QA engineer, API architect, API lead, backend developer, frontend developer, technical writer, DevRel, API evangelist

When the API is realized, the stakes are raised. Now, it’s important to have people involved who can make sure that the API stays available for your high-value users. That’s why the primary activities are the management of changes and improvement of the deployment architecture.

Even though the API is realized, there’s still going to be a great deal of change happening to the interface, implementation, and instances. A good product manager should be able to manage all of that change in a way that will keep driving realized value without negatively impacting existing users. How exactly this should be done depends a lot on the people involved, the strategic priorities, and the culture of the organization.

While the product manager is managing change, the DevOps engineer is focusing on improving the resilience, observability, scalability, and performance of the deployment architecture. A good DevOps engineer will be able to apply the right set of tools and practices based on the situational aspects of the API. The goal is to prevent any diminishment of quality for established, high-value users.

To continue to drive realized value it makes sense to continue to enhance and market your offering. That’s why a similar set of analysis, implementation, and discovery supplementary activities have been defined for this stage as for the previous stage. You don’t have to do these things, but without constant improvement your API may pass quickly into the maintain stage before you have a chance to recoup a good return on any investment you’ve made.

Table 7-5. Primary activities in the realize stage
Activity	Role(s)
Improve and optimize the deployment architecture

DevOps

Manage and prioritize changes

Product manager

Table 7-6. Supplementary activities in the realize stage
Activity	Role(s)
Improve the interface design

Designer

Improve and optimize tests

Test/QA engineer

Improve and optimize the implementation

API architect, API lead, backend developer

Test the security of the implementation and deployment

API architect, test/QA engineer

Improve and optimize the onboarding and learning experience

Frontend developer, technical writer, DevRel

Market the API

API evangelist, DevRel

STAGE 4: MAINTAIN
Primary role(s)
DevOps, DevRel, API architect

Secondary role(s)
Product manager, API lead, backend developer

In the maintain stage, the goal is to keep the API running. That means the key role is that of the DevOps engineer, who must monitor and maintain the deployed instances. In addition to this basic maintenance work, it’s important to have an eye on what may change in the system and how that might create new work for the API team. A good API architect will be tuned into potentially impactful changes and will be able to identify the kinds of changes needed in the API to accommodate them and keep the product running.

You’ll need also to have some level of engagement and support for existing users, even if the API is no longer being actively shopped around. The DevRel role is best placed to provide this kind of support and can help the product to continue to deliver value to new and existing users, even as the rate of realization stagnates.

Finally, to support this maintenance work, the product manager and technical team will need to be ready to make any necessary changes. Although the rate of enhancements and improvements will have dropped drastically, there is still a need to make changes in support of issues that the API architect or DevRel have identified from their respective domains.

Table 7-7. Primary activities in the maintain stage
Improve and optimize the monitoring system	DevOps
Support existing users

DevRel

Identify system changes that will deteriorate API quality

API architect

Table 7-8. Supplementary activities in the maintain stage
Activity	Role(s)
Plan and schedule implementation changes

Product manager

Make required implementation changes

API lead, backend developer

Make required deployment changes

DevOps, backend developer

STAGE 5: RETIRE
Primary role(s)
Product manager

Secondary role(s)
DevRel, API evangelist, API architect, DevOps, API lead

The primary work of the retirement stage is strategic, so the product manager plays the key role. A good PM will be able to identify a deprecation strategy that works best for the given circumstances. In the same way that they have the experience to develop a tactical plan for a new API, they should have sufficient experience to build one for retirement.

Enabling this strategy means doing the work of removing the deployed instance from the deployment architecture and supporting users through the time of transition. The DevOps engineer is responsible for deprecating the API in the deployment domain and the DevRel is responsible for deprecating the API in the user domain.

There also may be a need to form a technical plan to enable the product manager’s strategic plan. For example, it might make sense to return response messages indicating that deprecation is imminent or choose specific response headers that indicate the retirement state of the API. This plan needs to be developed by someone with technical expertise, so it is usually handled by the API architect or API lead.

Table 7-9. Primary activities in the retire stage
Activity	Role(s)
Develop a retirement strategy

Product manager

Table 7-10. Supplementary activities in the retire stage
Activity	Role(s)
Communicate the retirement plan and help users transition

DevRel, API evangelist, technical writer

Design a technical retirement strategy

API architect, API lead

Update the deployment architecture and remove instances gracefully

DevOps, API lead

In this section we’ve talked about how the lifecycle stage of any single API product affects the composition of its team and the primary and secondary roles that make up that team. We’ve learned that, as an API changes over time, so does the complexion of the team that owns that API.

Another important aspect of API teams is scaling across teams. In most companies with a healthy API program there is more than one API team. How do the teams work together? What tactics can you use to make sure teams are not working at cross purposes or contradicting each other? And how do you ensure consistency in execution across a collection of teams? These kinds of considerations are the last thing we’ll cover in this section.

Scaling Up Your Teams
Understanding that roles are the essential building blocks of teams and that team composition requirements are affected by the maturity stage of the API product is just the start of the challenges of governing API teams. Another big element is dealing with many teams. Often each API has a team, but there is more than one API. Working in a community of teams (a team of teams?) brings a whole new level of complication.

It is a good idea to treat each API team as an independent group—that means they can solve their own problems with minimal dependencies on other teams. But reality is not quite the same as theory. Theoretically, teams don’t need each other. Actually, teams can’t work well without each other! So how does that work? There is a constant push/pull between maintaining independence and working well with others. It is important to build more than a single team strategy. It is also important to have a larger view of how the various parts (teams) fit together as a whole.

In his book Team of Teams (Portfolio), General Stanley McChrystal talks about a different way of thinking about how large organizations succeed: “As the world grows faster and more interdependent, we need to figure out ways to scale the fluidity of teams across entire organizations.” That means understanding how to get teams to work together without forcing them to become dependent upon each other.

One organization that has built a reputation for being able to scale up its team system is the digital music company Spotify. Spotify’s 2012 whitepaper on the topic is an often-quoted reference to thinking about ways to improve the effectiveness of both individual teams and cross-team communications. Even though the paper is a bit dated (six years is a long time in Internet terms!), we find many other organizations using similar approaches to those outlined in that Spotify paper—so much so that we think it is still valuable to understand the key lessons from Spotify and explore how you can apply them in your company.

Teams and Roles at Spotify
In 2012, Agile coaches Henrik Kniberg and Anders Ivarsson published the paper “Scaling Agile @ Spotify”. Its opening line acknowledges, “Dealing with multiple teams in a product development organization is always a challenge!” Kniberg and Ivarsson then go on to explain how Spotify designed its team management model to help maximize information sharing without jeopardizing team independence. This model (or some variation of it) is now something we see at many companies.

The Spotify team model has four key elements or groupings:

Squad

Tribe

Chapter

Guild

Squads are small, self-contained teams of five to seven members, similar to a Scrum team. They are the basic unit of work at Spotify. A squad has all the skills needed to do its assigned work, from design to deployment, just like the teams we’ve been talking about here. At Spotify, each squad has a mission or job within a larger product group. For example, for the Android music player, one squad might “own” the playback experience, another might own the search experience, and so forth. The squads get the work done.

At Spotify, the tribe represents a larger product scope, such as the aforementioned Android music player, or the website, or the backend storage service used by all other client products. In this way tribes are collections of squads. At Spotify, they try to keep the total number of people in a tribe to around 100. This is considered large enough that there is enough diversity in the group to get things done, but not so large that it gets too hard to maintain healthy relationships.

DUNBAR’S NUMBERS
The maximum squad size (7) and tribe size (100) are based on the work of British socioanthropologist Robin Dunbar. We’ll cover Dunbar in more detail in “Leveraging Dunbar’s Numbers”.

With squads and tribes, Spotify is able to build an effective strategy for creating and maintaining its products and services. However, that’s only one half of the challenge. It is also important to enable some level of efficiency in this community. That means some kind of inter-squad and inter-team communication to share knowledge and ensure consistency across teams and products—and that’s where Spotify’s chapters and guilds come into play.

Since each team is self-contained, each team is likely to have a designer, or backend developer, product manager, etc. Each person fulfilling these roles has their own challenges and learning experiences. However, often these experiences are similar to those of others in the same role on other teams. For example, what it takes to be a good product manager for a squad in the Infrastructure tribe is a set of skills all product managers share, even if their exact approaches are not the same. It therefore makes sense for product managers in the same tribe to get together once in a while and share their experiences and knowledge with each other. At Spotify this is what a chapter is about—people with the same roles within a single tribe (e.g., the same product group) getting together and sharing knowledge.

Guilds, on the other hand, are a way to share knowledge across multiple product groups at Spotify. For example, getting some of the product managers from all areas of the company together (from customer-facing products to internal-facing systems) offers an additional level of knowledge sharing. In your company, a guild might represent a collection of team leaders from across the globe who get together once a year to share what they are working on in their various divisions.

At Spotify, the model of squads, tribes, chapters, and guilds provides the right mix of self-contained teams without creating isolated groups of people who don’t talk to each other. This is their way of balancing independence with cooperation.

Scaling Your Teams on Paper
The Spotify approach to scaling teams represents a decentralized point of view. Scaling is built into the working model itself. Another way we see companies scaling their teams is by employing a central team designed to collect information from all the other teams and share it through whitepapers, standards documents, and best practice training.1

In this way, it’s possible to scale up knowledge sharing without requiring face-to-face meetups or internal conferences. This method is particularly effective for very large organizations where teams are scattered across the globe and in different time zones, making even virtual meetings complicated.

However, it is not a good idea to rely only on shared documentation and pretaped presentations for sharing experience and knowledge across the company. In-person training, sharing, and collaborating is always more effective and often more efficient than just reading an article or watching a video.

And that leads us to the last section of this chapter, which is about company culture. The way team members work together and the way teams collaborate with each other is greatly influenced by the culture and values that already exist within an organization. For that reason, it is important to invest time in learning about and crafting your own company’s culture.

Culture and Teams
Company culture can act as an implicit form of governance for your organization. In Chapter 2, we introduced the idea of centralized and decentralized decisions. To review here, when decisions are centralized, you need to use authority to make sure people implement them properly. However, when you decentralize a decision, using authority as a means of compliance and validation does not work. That’s where culture comes in. Culture is like an invisible hand that shapes decision making within teams and throughout the company, without the need for extensive authority mechanisms such as processes, standards, or common tooling. Essentially, with the “right” culture and people you can safely decentralize more of your decisions while still maintaining a consistency of outcomes. That is why investing in crafting company culture can pay off in big ways. A consistent culture can ensure consistent outcomes, even when you are working to distribute decision making and scale up responsibility.

The process of making the right decisions involves more than just knowing what needs to be changed and how to go about distributing the responsibility for making those changes. Company culture is another important element in all of this. This is an area some people in the IT space are not comfortable talking about, but the culture of the organization is a thing that deserves attention.

The concept of company culture made its first appearance in print in the book The Changing Culture of a Factory (Psychology Press). Dr. Elliott Jaques defined it as follows:

“The culture of the factory is its customary and traditional way of thinking and doing of things, which is shared to a greater or lesser degree by all its members, and which new members must learn.”

The acknowledgment that an organization even has a culture leads to the possibility of actually affecting the existing culture; of steering it in some direction. And that leads to notions of how to recognize what kind of culture is operating within your company and what it would take to modify it.

The 1970s and ’80s gave way to a wave of books and theories on how to identify, categorize, and manage corporate culture. One important book from that era is Gareth Morgan’s Images of Organization (Sage). Morgan put forward the idea that corporate culture can be characterized using simple metaphors such as machines, organisms, brains, and so forth. These metaphors can then help you think about how your company culture operates and how you can identify ways in which you can change the organization’s culture.

We won’t try to review the last 70 years of scholarship on corporate culture here, but we note that many companies we work with are actively working to understand their company culture and how they can improve and direct corporate culture in meaningful ways. To that end, we will share three topics that come up often when we visit with companies working to create and manage APIs and services in an IT environment. They are:

Mel Conway’s observations on how group interactions affect output

Robin Dunbar’s theories on how team size affects communication

Christopher Alexander’s observations about how variety affects productivity

We’ll also touch on the role of experimentation in company culture and how it affects teams.

Recognizing Conway’s Law
In the last several years, Mel Conway’s 1967 paper “How Do Committees Invent?” has become an almost required topic in presentations about microservices as well as APIs in general. This paper is the source of what Fred Brooks dubbed “Conway’s law” in his 1975 book Mythical Man Month (Addison-Wesley). Conway’s law states that:

Organizations which design systems…are constrained to produce designs which are copies of the communication structures of these organizations.

This “law” is an observation about how the way groups are organized affects the output they produce. An often-cited supporting observation comes from Eric S. Raymond, author of The Cathedral & the Bazaar (O’Reilly), who states: “If you have four groups working on a compiler, you’ll get a 4-pass compiler.” Boiled down to its essence, Conway’s law tells us that, when it comes to producing working software, the organziational boundaries you have will determine the applications you get. This is both good and bad news.

As we mentioned at the start of this chapter, the software we write is “dumb”—it does only (and precisely) what humans tell it to do. Conway reminds us that the way we arrange people into groups—where we place the boundaries between teams—determines the results. For this reason some IT consultants talk about implementing a “reverse Conway.” They encourage setting up your teams and boundaries first in order to get the results you want. This can work to some extent, but has its own problems. In the same 1967 paper Conway warns us about getting too aggressive with our organizational scalpels:

[Conway’s Law] creates problems because the need to communicate at any time depends on the system in effect at that time. Because the design which occurs first is almost never the best possible, the prevailing system may need to change. Therefore, flexibility of organization is important to effective design.

Essentially, you can’t “out-Conway” Conway’s law! There is a trade-off here. It’s important to point out that the notion of organizational structure is key to influencing company culture. Companies that seem to do well in managing culture have at least two things in common: they work to make boundaries both clear and, flexible over time.

It is fine to establish clear boundaries between teams early in the project. This helps sort out responsibilities within teams and delineate interfaces between teams. However, it is also important to keep Conway’s warning in mind: “the design which occurs first is almost never the best possible” Therefore, as you move forward with your API and component projects, it is important to adjust boundaries based on real-world discoveries. This is a normal part of the work.

Just like so many other aspects of the API management space, managing the culture is continuous. Conway gives us hints on what we can do to effect change (e.g., focus on the boundaries between teams) and warns us that our first attempts are rarely the best possible option (“the prevailing system may need to change”). That leads to questions about how teams and team size can affect the corporate culture. And this leads us to the work of Robin Dunbar.

Leveraging Dunbar’s Numbers
Conway tells us about how teams and boundaries affect the output of any endeavor. So, a logical question is what makes up a team and, more directly, what is an optimal team size. Many of the customers we work with rely on the 1990s research of Dr. Robin Dunbar for the answer. In popular social science writings, his theories on how the brain affects group size are best known through what’s called Dunbar’s number, which posits that we can successfully keep track of and maintain useful relationships with, at maximum, about 150 people. Any group larger than that taxes most brains’ abilities to lead and manage the group. Essentially, once the group grows past this number, keeping the members coordinated, on-task, and working together gets much tougher.

There are many confirmations of the power of 150 when it comes to communicating with groups. William “Bill” Gore, founder and chairman of the W. L. Gore company from 1970 to 1986, established a rule that once a single factory contained more than 150 people, the group should be split up and a new building built (sometimes right next to the existing one). Netflix’s Patty McCord calls this the “stand-on-a-chair” number: once you get past 150, a team leader can’t easily just stand on a chair to address the entire group.

While Dunbar’s 150 is an important number, our experience tells us the research behind that number is more valuable. Dunbar’s theory is that we need to spend time and energy to successfully communicate in groups and that group size affects the amount of effort needed to maintain successful connections. In fact, his early research determined that teams of 150 “would require as much as 42% of the total time budget to be devoted to social grooming.” In other words, as teams grow larger, more time needs to be devoted (by everyone) to maintaining group cohesion. In the modern office setting “social grooming” takes the form of meetings, emails, phone calls, instant messaging, daily stand-ups, shift meetings, and so forth. Large teams are costly when it comes to coordination.

The good news is, Dunbar has more than just one number. He actually identifies a series of numbers starting with 5, 15, 50, 150, and on up into the 1,000s. At the lower end of the scale (e.g., 5 and 15), the coordination cost—social grooming—is very small. In a team of five, everyone knows each other well, everyone knows their job, and—most likely—everyone knows who, if anyone, is not pulling their weight in the group. The social grooming time is quite minimal. Even at group sizes up to 15, the comminication cost is relatively low. You may notice that the team sizes we recommended earlier in this book hover around the 5-person mark (give or take 2 or 3).

This small (five- to seven-person) team is what we call a Dunbar Level One team. It is the size most common for early startups. Dunbar Level Two teams of up to 15 people are often found in young companies that have gotten past their first angel funding rounds and are actively building the business. Many of the IT organizations we talk to work to keep their team sizes at Dunbar Level One and Two in order to minimize communication costs and maximize the effectiveness of the teams in general. Spotify, for example, aims for “squads” of about five to seven people each (see “Teams and Roles at Spotify”).

Dunbar shows us that team size matters and that communications within smaller teams can be more efficient. Conway reminds us that the interconnection between teams determines the ultimate output. The challenge, then, in crafting a successful API management culture is shepherding lots of teams inside a large organzation. Just as working with a landscape of APIs presents different challenges to working with a single or a small set of APIs, there are unique aspects to confront when you are working with a landscape of teams. Some of the work of physical architect Christopher Alexander can help with this “team of teams” challenge.

Enabling Alexander’s Cultural Mosaic
Leading and/or supporting a single team is not an easy task. Getting a group up and running, helping them find their footing and style and learn to be positive contributors to the company mission, is hard (but rewarding) work. Those who do this kind of work often also know that every team is unique. Each team has to travel through the same general landscape in its own way. The variations from team to team are key to building diversity and strength into your company. Even though it might seem that you’d want all teams to look and act the same way, that is not a sign of a healthy ecosystem.

This “landscape of teams” presents the same kinds of challenges and opportunities as a landscape of APIs (see Chapter 8), and many of the same landscape aspects we outline in that chapter apply to the landscape of teams too. As you grow your API enterprise, you’ll be dealing with more variety, volume, volatility, and other elements of a healthy ecosystem. In fact, human systems (e.g., teams) typically become better as variety is introduced. Most of us have experienced cases where adding a new “outsider” to our teams has resulted in a stronger team. There are all sorts of aphorisms along these lines, including “What doesn’t kill you makes you stronger”—the notion that unexpected challenges can help us get better. Nassim Taleb’s 2012 book Antifragile (Random House) is based on this very premise.

Another point of view on the power of “teams of teams” can be found in the writings of the physical architect and thinker Christopher Alexander. His 1977 book A Pattern Language (Oxford University Press)—the book credited with launching the patterns movement in software—includes the concept of a “mosaic of subcultures” as a way to organize communities in a healthy, sustainable way.

ALEXANDER’S INFLUENCE ON SOFTWARE
Although Christopher Alexander is a physical architect, his writing and thinking have greatly influenced software archtecture, too. His book A Pattern Language introduced the notion of thinking in patterns when constructing large systems and is cited often as the catalyst for the software patterns movement. The patterns book is a heavy read, and only one of our team can claim to have gotten through the entire work. A smaller and more accessible book by Alexander is The Timeless Way of Building (Oxford University Press). We often recommend Alexander’s writing to software architects dealing with very large ecosystems.

Alexander’s “mosaic of subcultures pattern” idea describes three essential ways to deal with large collections of people and the smaller groups that emerge within the whole. Alexander’s writing is applied to city-sized collections, but in our experience it has important parallels for IT leadership dealing with global and enterprise-level organizations.

Alexander outlines three approaches to how subgroups appear within large communities (his point of view being the city itself):

Heterogenous
People are mixed together irrespective of their lifestyle or culture, reducing all lifestyles to a common denominator that turns out to be homogeneous and dull.

Ghetto
People cluster along their most basic and banal forms of differentiation, race and/or economic status, creating isolated groups which are still homogeneous within each ghetto.

Mosaic
A number of small areas with clear boundaries of separation form, between which people can freely move in order to experience the lifestyles and cultures that interest and inspire them.

It may take a bit of effort to get past Alexander’s city-planning domain, but our experience is that these notions of widespread homogeneity (“We all use the same tools and processes throughout the company”) vs. ghettos (“We’re all data engineers here; the QA people are in the other building”) vs. mosaics (“I joined this group because I wanted to work on our mobile app”) are prevalent in IT organizations, too. Every company has its own shared cultural elements, and subcultures that grow up within that organization. Being aware of these subelements of culture is the first step toward dealing with them and, in most cases, leveraging them in the mission of growing a healthy and resilient API management culture.

We’ve made the case here that it is not enough to just understand the dynamics of communication within a single team (e.g., Dunbar). We’ve also highlighted the power of inter-team connections, as described by Mel Conway. Finally, we introduced the notion of a “landscape of teams” and the importance of paying close attention to the way in which teams are formed (e.g., Alexander) and the ecosystem in which they operate. But what is the payoff here? Why spend time on these elements of culture, especially with regard to managing APIs?

It is your company culture that determines the level of innovation, experimentation, and creativity that teams and individuals can exercise. Your culture is the key to success when growing your company.

We’ll touch on this last aspect of culture next.

Supporting Experimentation
One important reason for spending time grooming a company’s culture is to help foster innovation and transformation of the organization’s day-to-day operations. A big reason for this is expressed in a quote attributed to business management guru Peter Drucker: “Culture eats strategy for breakfast.”

Essentially, no matter your strategy, it is the prevailing culture that drives the company. Therefore, if you want to change the direction of your team, your product group, or even the entire organization, it is culture on which you need to focus. This is the message that Conway teaches us, as well: it is the organization and its boundaries that establish the output of the group.

A key to fostering innovation—the creation of new products, methods, and ideas—is the ability to experiment safely. Experimenting doesn’t mean launching some half-thought-through idea into production. Like so many other things we’ve talked about in this book, experimenting starts small (e.g., within a team) and goes through repeated rounds of iteration to learn from, winnow down, and identify related ideas in order to find something valuable, useful, and desirable; something that might be worth spending precious time and resources on in order to bring to life.

In his 2006 book Direct from Dell (HarperCollins), businessman and philanthropist Michael Dell puts it like this: “To encourage people to innovate more, you have to make it safe for them to fail.” The key point here is that failure should be not just easy or common, but safe. Teams should be placed in an atmosphere that allows them ample room to experiment, but constrains them from making costly mistakes that disrupt important company operations. One way to create this kind of ecosystem is to use the decision elements we outlined earlier in this book (see “The Elements of a Decision”). When teams know their boundaries, they have a clearer sense of what kinds of experiments they can use in order to learn how to improve.

Another big part of supporting experimentation is understanding that lots of teams running experiments is better than a few teams (or just one team). In “The Center for Enablement” we discuss the power of having a dedicated team, one that can help establish guidance and guardrails for the enterprise. This is not, however, the place where all the experiments happen. Just as in other aspects of IT, heavy centralization and concentration can lead to increased vulnerability and volatility. On the other hand, distributing activities across a wide range of teams and product groups improves the chances of successfully generating valuable ideas and reduces the likelihood of those experiments causing the company real damage along the way.

This last point might be counterintuitive for some IT leaders. It might follow that more experiments adds to volatility, but this is only true if all the experiments are happening in a single place—for example, in a Center for Enablement (C4E) or some other experimentation hub. This concentration of risk is discussed by Nassim Taleb in his book Skin in the Game (Random House). Author of Black Swan, Antifragile, and other best-selling books, Taleb reminds his readers, “the probabilities of success from the collection of people does not apply to [one person].” Put directly, an ensemble of 100 teams making experiments with new APIs is not the same as one team making 100 experiments in a row. You can use your knowledge of the decision elements to reduce risk while you increase experimentation.

And increasing experimentation means more attempts at innovation, which leads to a continuous API management model (see “The API Product Lifecycle”) that can more easily be sustained over time.

To make this all work at a level that is both sustainable and economical (but not necessarily efficient) you need a diverse community of teams working on projects that drive their passions. And that is where Alexander’s moasic comes into play.

Summary
We’ve covered quite a bit in this chapter. First, we defined a set of roles that capture the decision-making scope and responsibilities needed to design, build, and maintain an API. We also talked about how these roles can be used to put together a physical team of people to do the actual work on the API. And we saw that one person might fulfill multiple roles in the same team, or across several teams.

We also reviewed how the various API lifecycle stages can affect the makeup and need for different roles in an API product team. It turns out teams are dynamic, and the roles reflect the number of people involved and the maturity of the API in question. In addition, we explored the way Spotify has designed a team model that takes into account the way teams interact with each other at various levels within the company. We also pointed out that you can take a centralized or decentralized approach to ensuring efficient knowledge sharing and collaboration across teams within the company.

Finally, we spent some time exploring the power of company culture when it comes to enabling teams. Factors such as team size can affect the quality of communications and the accuracy of the resulting work—and failing to enable cross-team communication can result in “technical ghettos” within your organization that can stifle innovation and creativity.

This last point about the power of culture and enabling cross-team communication leads us to an important milestone in the book. Up until this point, we’ve been focusing on the management of a single API and all the things that go into making sure it meets customers’ needs: understanding the typical skills needed to create and maintain an API, how to ensure healthy change management throughout its lifecycle, and the kinds of roles and teams you need to make it all work.

However, as we’ve mentioned in this chapter, there is another aspect to all of this—cross-team and cross-product work. In all companies we visit, there is more than a single API, more than a single team, and more than a single way of working together. We refer to this world of multiple APIs and multiple teams as your company’s “API landscape.” And managing a landscape is quite different from managing a single plant or a single API.

When your scope of responsibility grows beyond a single API or product, you need to change the way you look at the challenges and the way you come up with solutions to those challenges. To quote (again) Stanley McChrystal:

The temptation to lead as a chess master, controlling each move of the organization, must give way to an approach as a gardener, enabling rather than directing. A gardening approach to leadership is anything but passive. The leader acts as an “Eyes-On, Hands-Off” enabler who creates and maintains an ecosystem in which the organization operates.

Learning what it takes to enable the gardening of your company’s API landscape is what we’ll cover in the next several chapters.

1 We’ll talk more about this team in “The Center for Enablement”.