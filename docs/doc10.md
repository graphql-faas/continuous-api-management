---
id: doc10
title: Chapter 10. Managing the API Lifecycle in an Evolving Landscape
---

Many drops make a bucket, many buckets make a pond, many ponds make a lake, and many lakes make an ocean.

Percy Ross

Hopefully, if you’ve been following along in the book up to this point, you’ve noticed that there are some key differences between managing the lifecycle of a single API and managing the lifecycle of an entire landscape of APIs. In, fact, it is our experience that companies that notice—and act according to—this important distinction between “the one” and “the many” are the companies that have the best chance of long-term success in their digital transformation efforts.

In this chapter, we’ll touch briefly on these differences and then dive into the lifecycle pillars we introduced in Chapter 4—this time, we’ll focus on the landscape (the many, as introduced in Chapter 8) instead of the API (the one). This should give you some perspective on how the challenges of scope, scale, and standards we discussed in Chapter 1 come into play when you are growing your API ecosystem.

Along the way, we’ll return to the eight Vs of the API landscape (introduced in Chapter 8 and refined in Chapter 9) and touch on some of the decision-making elements to employ (described in Chapter 2). Bringing all these elements together will help you gain a point of view on how you can best apply these patterns and practices in your teams, for your products, in a way that fits your company’s culture and values.

API Products and Lifecycle Pillars
As we pointed out in Chapter 3, applying the appropriate level of “product thinking” to your API efforts helps focus your teams on consumer-centric uses of your interfaces. This is your first-level opportunity to instill Clayton Christensen’s Jobs-to-be-Done (JTDB) approach to designing and implementing your APIs. And, at the business level, teaching your design and architecture teams to ask questions such as “How does this help us achieve our business goals?” and “What OKRs are we hoping to affect with this design?” can reduce the chances of your backend teams ending up simply releasing data-centric interfaces that don’t have a clear user-driven workflow. With this JTBD and user-driven focus, it is easier for IT leadership to quiz teams on their contributions and help keep your API initiatives clearly tied to not just IT-centric KPIs but shared business-level OKRs.

Along with the API-as-a-Product strategy, we’ve also introduced what we call the API lifecycle pillars (see Chapter 4). While not a true cycle (as in a fixed order that you repeat over and over again), the lifecycle pillars identify essential elements that support a healthy API program. You can use the pillars as a guide in creating your APIs. In this way, the AaaP model and the lifecycle pillars support each other at the single-API level.

However, as you’ve seen in the last couple of chapters that introduce the notion of the API landscape, companies rarely work in a world where there are just a few isolated APIs. Instead, most organizations are working to create an ecosystem of interdependent and interoperable APIs that help expose business value and reduce the cost and risk of using APIs and services to reach business-related goals (OKRs).

API Landscapes
So far this book has focused on how to continuously manage individual APIs, and how these fit into the bigger picture of the API landscape. The eight Vs described in Chapters 8 and 9 were used to focus attention on individual aspects of this big picture, helping you to make sure that you consider everything that’s important while you manage your growing and ever-evolving API landscape.

In this chapter, our goal is to bring together the perspective of individual API management and the context of the API landscape they are a part of. We will focus on our general theme that the interaction between individual APIs and API landscapes always should be a two-way street. APIs contribute to the landscape and should be as observable as possible so that the landscape can gain insights into how individual APIs are being designed and how they evolve. The landscape guides and supports API product teams by providing insights into the overall picture of principles, protocols, and practices in the landscape, and by providing guidance and support.

The eight Vs (the landscape aspects) can be used to focus attention for the individual API lifecycle pillars. Our way to bring together the individual API and API landscape perspectives will be to discuss how the pillars are affected when an API is part of a landscape, and which landscape aspects are most important to consider when rethinking that particular pillar (and how to support API product teams relying on that pillar) in the context of the landscape.

Decision Points and Maturity
In “Decisions”, we made a point of saying that the code and interfaces we create today are “dumb”—that our releases just do exactly what they are told to do, and nothing more. Code can’t decide or explore or experiment; it can only do. The decisions and creativity come from humans, and those decisions must be translated into code and APIs at some point in order to be realized.

A big part of decision making is knowing when to decide. It turns out that putting off a decision is often a smart option when it comes to helping to realize an API landscape. There are so many interdependent, interoperable elements in a growing ecosystem that deciding “too soon” can reduce the number of possibilities in the future and may even eliminate some of the best options for solving your architecture problems. Tom and Mary Poppendieck, authors of several books including Lean Software Development: An Agile Toolkit (Addison-Wesley), recommend that you “delay commitment until the last responsible moment, that is, the moment at which failing to make a decision eliminates an important alternative.”

However, this practice of delaying commitment can be difficult for system-level IT managers and designers. The common question is when the “last responsible moment” is. Our goal with this chapter is to help you recognize common changes in the shape of your API landscape by walking through the pillars and calling out common challenges related to the different landscape aspects. This should help you compare the observable aspects within your company (variety, volume, etc.) with the examples we offer here. Hopefully our examples will give you enough of a guideline that you’ll be able to identify pillars that need special attention due to your growing ecosystem.

Landscape Aspects and API Lifecycle Pillars
Just as the lifecycle pillars and the API-as-a-Product guidance work together to form a set of practices to apply to the work of designing, building, and releasing APIs in your organization, these same pillars can be helpful in managing a growing ecosystem or API landscape. In fact, we can create a simple matrix (see Table 10-1) that combines the previously mentioned landscape aspects and the API lifecycle pillars in order to give you a sense of the surface area you need to manage in an API ecosystem.

Table 10-1. API landscape lifecycle pillars and landscape aspects
Variety	Volume	Vocabulary	Velocity	Vulnerability	Visibility	Versioning	Volatility
Strategy

✔️

✔️

✔️

Design

✔️

✔️

✔️

Documentation

✔️

✔️

✔️

✔️

Development

✔️

✔️

✔️

✔️

Testing

✔️

✔️

✔️

✔️

Deployment

✔️

✔️

✔️

✔️

Security

✔️

✔️

✔️

Monitoring

✔️

✔️

✔️

Discovery

✔️

✔️

✔️

✔️

✔️

Change management

✔️

✔️

✔️

✔️

Every pillar mentioned in Chapter 4 along with every aspect identified in Chapter 8 deserves attention. As your landscape grows, it does not just “get bigger.” Instead, your ecosystem changes shape. In a small API landscape (e.g., a single team working on one related set of APIs), you don’t need to spend much time creating guidance and standards on API styles or message formats. That is because everyone is working on the same team, using the same tools, and aiming for the same results.

However, as your API ecosystem grows, you’ll be adding more teams, with varying goals. Some of these teams may be in remote locations, using different sets of tools, with a different history of API styles and guidance. A growing landscape can result in greater variety, a broader vocabulary, and varying levels of visibility, volume, velocity, and vulnerability. Growing landscapes change shape over time.

While it is important to review each of the landscape aspects as they apply to the lifecycle pillars, that would require a much larger book than we can offer you today. Instead, we’ve decided to focus on select aspects of each of the lifecycle pillars along with helpful examples and, in some cases, suggested guidance to consider when tackling the challenges along the way.

Hopefully, you’ll be able to use the following reviews as a guide while your landscape grows in scale and scope and you move through the maturity stages over time, as discussed in the previous chapter. Since each company’s culture is different, you may find it useful to create your own blank matrix templates to use as a way to spur conversation among your teams and drive open discussion that allows everyone in your organization to contribute examples and guidance along the lines offered here.

With that in mind, let’s take a tour through the API lifecycle pillars and highlight some of the more common landscape aspects that you will encounter as your ecosystem grows and changes over time.

Strategy
As a company’s API landscape grows, the tactics and even short-term goals of its API strategy initiative may undergo changes. In “OKRs and KPIs”, we showed how questions about general digital strategy were informed by OKRs and KPIs, as well as the common uses and audiences for APIs (private, partner, public). While these continue to be critical as your landscape expands, the details for each of them will transform.

For example, the KPIs for your initial set of APIs might have focused on reliability, increased use within the company, and contribution to revenue or cost reduction. As your program expands to tens, hundreds, or even thousands of APIs, you may need to adjust your KPIs to focus on considerations unique to large API ecosystems. This is where you can apply the landscape aspects introduced in Chapter 8 to clarify your tactics and implementation directives to match your current ecosystem challenges.

Among the landscape aspects that should be considered when adjusting your strategy as your ecosystem grows, three of them stand out as needing special attention: variety, volume, and velocity. Let’s review each briefly.

VARIETY
As you add more product groups, more teams, and more API consumers to your API landscape, your ability to control and constrain each element of API design and implementation will become less effective, meaning a natural tendency toward more variety. It is relatively easy to constrain a single team or small group of colocated teams to make sure they all follow the same design conventions and use the same formats, tools, and testing and release practices. However, as you add more locations (e.g., office halfway around the globe), begin to support APIs from other product groups (e.g., acquired companies), and work with products using vastly different technologies (STFP, mainframe systems, etc.), you’ll find that you can no longer dictate just “how” things get done.

As your landscape grows, its variety naturally increases. Instead of trying to avoid this healthy diversity, it is important to change your API strategy to embrace differences and focus on overriding principles all teams share, instead of trying get everyone to use the same practices across technology stacks and product groups (see “Principles, Protocols, and Patterns”).

Increasing variety is not a bad thing.

VOLUME
A large API landscape can also mean increases in varying types of volume—more APIs, more traffic, more teams, and so forth. However, you may still have limited resources available for managing this growth. This usually means you need to make choices about what new initiatives to support, what old ones to deprecate, and what APIs need to be kept as they are for the near future.

When it comes to making choices, focusing on APIs that are clearly bringing in more positive business, ones that are easier to update and maintain, and other business-centric goals can help you manage the increasing volume. You may need to start to invest in platforms that “scale better” at high traffic volumes. You may also need to move from on-premise releases to virtual machines in the cloud that are more easily scaled. You may have some APIs that will perform better in a Function-as-a-Service (FaaS) environment, and so on. And in some cases, it might make more sense to bring traffic back into your own local infrastructure to reduce distance and costs.

Volume is one of the most common aspects you’ll need to deal with as your landscape grows, and there are many ways to address it.

VELOCITY
The last landscape aspect we’ll call out here is velocity. Several customers tell us that “things are just getting faster and faster,” and it’s challenging to keep up. While sometimes this is true, other times it is not just the speed of change but the number of changes that becomes a problem. Velocity can be experienced in several forms.

As your ecosystem grows, more parts will need to change, and that means you notice change more often. Your API strategy will need to adjust to make sure changes are not disruptive (see “Change Management”) and to that they are cheaper and less risky. Usually this means setting up barriers to large-scale changes (e.g., formal proposals, careful reviews, and sign-off) and removing barriers for minor changes (e.g., small changes in UI layout bug fixes, nonbreaking API changes, etc.).

Velocity can also be experienced as an increase in customer business. If you’ve implemented successful APIs that bring in more orders, but your back-office teams are still stuck doing things like credit reviews and customer approvals manually, you’ll discover overwhelming backlogs and may lose critical revenue. Your API strategy reaches beyond just the technical details of designing and releasing code—it includes everyone in the organization.

Velocity is not just experienced as simple speed; it can also cause perceived slowdowns in some parts of the company.

Design
As discussed in “Design”, interface design is an important pillar of API product work. And new challenges are introduced when APIs are designed in the context of a landscape. As part of an API landscape, an API is not a standalone product anymore, but instead can be seen as part of a “product family.” How much that view should influence the design of individual APIs very much depends on the projected use of an API:

APIs that may see a lot of use, are projected to be highly visible, and will be used as “single-user touchpoints” still can be designed very much as individual products, with their design optimized primarily for the API consumers. However, in terms of implementation (which is not visible to the users of the API) it may still make sense to harmonize the API with the landscape, allowing developers to take advantage of support and tooling.

APIs that are more likely to be used as part of the API landscape, for example in conjunction with other APIs of that “product family,” should be designed with that usage pattern in mind. Design familiarity will play a larger role: developers using and combining various APIs from the same landscape can benefit when there is harmonization on the API design level.

Looking at these two scenarios, it becomes clear that API design plays an important role in both cases, but in strikingly different ways. For the former, harmonization is mostly an issue when it comes to implementation issues, while API design of course still can take design cues from the guidelines when it comes to identifying and solving API design issues. For the latter, harmonization becomes more important both at the API design and the implementation level, meaning that guidelines play a bigger role in that scenario.

When it comes to considering how design should be approached in the API landscape, the considerations mentioned here can be complemented with the landscape aspects introduced in Chapter 8. Of these aspects, the design pillar is most impacted by considerations of variety, vocabulary, and versioning.

VARIETY
Variety happens as a natural result of an evolving API landscape. One reason for this is changing design patterns over time, so that the same problem naturally gets solved in different ways, based on the context of established practices at design time. The second reason is that different products can fulfill different needs and target different consumers, and there may be no one design practice that is the perfect fit for all these different consumer groups.

For these reasons, variety should be allowed, instead of trying to constrain the solution space to one possible design. However, curating the design space through design guidance managed by a C4E (as discussed in “The Center for Enablement”) helps to constrain it in a way that helps designers, who have a set of design options in front of them and can make informed decisions based on which options are practiced in which way and supported by which tooling.

One of the anti-patterns of variety shows up in design when the same problem is being solved in different ways in different APIs, without a good reason. This not only wastes team resources by inventing new solutions instead of using existing ones, but also negatively impacts consumer productivity because every API needs to be relearned. This is often referred to as individual APIs being treated like “precious snowflakes,” each of them unique and different in their most intricate details, instead of promoting and supporting reuse where it makes sense.

In summary, design variety makes sense and should be embraced when there is a product-driven reason behind it. Otherwise, it is more economical and benefits the landscape when design uses established patterns.

VOCABULARY
Aligning design vocabularies across an organization can help to create a more coherent design practice, and it can also help to avoid repeated (and in the worst case conflicting) attempts to create models for the same domain. On the other hand, defining and harmonizing vocabularies comes at a certain cost, so simply choosing the path of trying to harmonize everything across an organization may not be the most economical option.1

As a general rule, domain concepts that can be safely encapsulated in a service (i.e., that do not show up in the service’s API) do not need to be harmonized at all. These are implementation details of the service, and making them visible outside the service would directly contradict the principle of encapsulation.

For concepts that are relevant for a service’s API, we can distinguish two cases:

Domain-independent vocabularies should be easy to find in an organization. A simple example would be something like a list of countries or a list of languages. Any API using vocabularies should try to separate the API and the vocabulary, and then list all vocabularies so that vocabulary use becomes observable.

Domain-specific vocabularies may need to be set up (instead of just being referenced) as part of the API design. Depending on the maturity of this aspect (as discussed in “Vocabulary”), the landscape may provide support for this, so that defining and populating a new vocabulary can be done easily by API product teams.

Generally speaking, managing vocabularies for API design follows the general idea that vocabulary harmonization is good, and that observation and support can help with that. APIs listing their vocabulary use helps landscape managers to observe vocabulary usage and evolution, which in turn can lead to simplifying API design by reusing established vocabularies instead of reinventing them.

VERSIONING
One of the main goals of an advanced API strategy is to decouple the evolution of services, so that they can individually evolve at the velocity that is best for them. This evolution means that the service implementation may change, and the API may change as well. From a design point of view, the former is still important as it may indicate that the product team has chosen to solve a problem in a new way.

In order to understand the rate of change in the API landscape, it is important to keep track of versions, as discussed in “Versioning”. Following the “API the APIs” principle (see “API the APIs”), this means that APIs should expose their versions, so that changes in their implementation and design become visible.

Managing versions also becomes important from the client’s perspective, as discussed in more detail in “Change Management”. An important part of API design therefore is to follow design principles that make it easy for consumers to handle new versions, ideally in a way that consumers can always learn about new versions being made available, but only have to do something about that when they decide that they want to take advantage of new features, for example.

In summary, design in API landscapes should always take into account that services will evolve continuously. Designing for change then means to make it easy both for landscape management and for service consumers to learn about new versions, while at the same time practicing design that requires as little effort as possible by consumers to adapt to new versions.

Documentation
As introduced in “Documentation”, documentation is heavily influenced by API maturity, even though some basic documentation always is a good idea—and, in the case of the API-as-a-Product approach (see Chapter 3) even is what API products get started with.

Documentation is a pillar that has a particularly wide range: minimal documentation can be generated from technical artifacts such as OpenAPI descriptions, can be enriched with comments and examples, and can even be integrated into the API itself with the goal of optimizing the developer experience to the point where almost all friction of using the API is removed, and the API becomes a highly optimized self-serve product.

However, this final step of investing in documentation can be rather expensive, and in all likelihood only is a good investment when the effort of creating highly refined documentation is offset by the number of developers benefitting from it.

The level of investment in documentation for individual APIs mostly will be a function of API maturity and the projected consumer community, as discussed in Chapter 6. However, the landscape should provide guidance and support once that investment decision has been made. Of the landscape aspects, the four that are most important in helping make the landscape support the documentation pillar of individual APIs are variety, vocabulary, versions, and visibility.

VARIETY
Allowing and managing a variety of documentation styles helps ensure that each team can pick the best style for the API they are developing and evolving. This choice will depend both on the API style and on the maturity and intended audience of the individual APIs.

Enabling teams to choose the documentation tooling and depth that fits their API design, its maturity stage, and its audience will help them to publish the documentation that fits their current needs.

If there are “clusters” of documentation requirements, then it’s useful to have specific guidance and tooling, and also to have validation tooling that allows teams to integrate documentation checks into their delivery pipeline. In most cases, it will not be possible to check all aspects of documentation in an automated fashion, but often at least some sanity checks (“Are there sections about extensibility and about versioning, and are they called out and marked explicitly?”) can be included, so that teams know a bit better what the expectation are.

It is likely that documentation variety will evolve over time. Some styles of documentation may become historical, while new ones may get adopted. Ideally, variety in documentation styles should be decoupled from documentation content, so that, for example, some important principles (such as the guidance about extensibility and versioning sections in the documentation) can be carried across specific documentation styles.

VOCABULARY
As discussed in “Vocabulary”, one sign of maturity in API landscapes is to manage vocabularies across APIs, so that it becomes easier for API producers to find and reuse existing vocabularies, and for API consumers to use their understanding of vocabularies across APIs.

Managing vocabularies for better documentation means managing documentation for these vocabularies, so that any API using a given vocabulary can reuse this existing documentation. Depending on how documentation is managed, this reuse can be “webby” and simply involve linking to existing documentation that is available elsewhere. Or, if the documentation style is a little less webby and more about creating self-contained documentation per API, then reusing documentation might mean including it in the API documentation.2

It is important to keep in mind that managing documentation vocabularies is also extremely valuable from the observation point of view: if APIs document the vocabularies they use in a way that is supported by the landscape, or at the very least observable for the landscape, then it becomes much easier to understand vocabulary use across APIs, suggest and focus on emerging vocabularies, and understand which ones are not used as widely anymore. Once again, observing APIs to better support the landscape and supporting APIs in a way that makes things observable are the two sides of the coin that provide the best way to combine benefits for individual APIs and for the API landscape.

VERSIONING
One of the main goals of APIs and API landscapes is to decouple implementations, so that individual products can be evolved individually. This increase in product velocity naturally leads to an increase in product versions, as discussed in “Versioning”. While ideally the majority of versions should be nonbreaking from the API point of view, each version that results in changes of the minor version when using a semantic versioning scheme should still be documented. This helps consumers to understand the changes that may have happened, and allows producers to make their documentation useful across versions.

As discussed in “API the APIs”, documentation (like everything else about the API) should be part of the API. Following this principle, it also means that documentation history should be part of the API, allowing API consumers to understand the evolution of an API by traversing its documentation history.3

Guidance about versions can help make APIs easier to use, and can help consumers stay updated about API versions and better decide when and how they want to adjust to API updates. Providing API product teams with guidance on how to produce and publish documentation across versions makes it easier for them to follow these practices. The landscape can provide support and tooling for testing, so that API developers get more immediate feedback about how they document their APIs across versions.

For API landscapes using semantic versioning and following webby principles, one possible landscape guidance is to recommend that all API documentation should make all versions navigable using RFC 5829 links. This scheme includes a navigable version documentation history, as well as interlinked documentation of individual versions. Testing for the presence of these links could be done when APIs and their documentation get deployed, making it possible to validate at least the schematic part of the documentation practice.

In summary, documentation in API landscapes naturally will involve the versioning aspect, and by providing guidance and support for documenting versions in an observable way, landscape management can get some insight into API versions and their documentation.

VISIBILITY
Documentation potentially can be a rather complex resource in itself, with quite a bit of content and structure to it. As discussed so far, it helps if there is existing tooling and support around documentation, so that API teams may rely on certain production pipelines for their documentation instead of having to choose or build their own.

It is important to keep in mind, though, as discussed in “Variety”, that the main goal of guiding and supporting documentation should not be to tell teams “how” to produce it, but “what” they should be producing. There can be supported toolchains, allowing them to easily satisfy the “what” by following a supported “how,” but separating the toolchain from what it is supposed to produce is important.

API documentation should be always be visible, and with it all the aspects that are important from the landscape point of view. This is important both for consumers of the documentation and for the landscape itself, which can then use this visibility as an important way to gain detailed insights into APIs and to provide deep links into documentation when required. This means that it is important for landscape guidance to address what needs to be observable from the landscape perspective, and to add these aspects to guidance and tooling.

Development
On the surface (and what a nice pun that is!), development does not play such a big role for API landscapes. After all, the role of APIs is to encapsulate implementations, and thus how they are developed is out of scope from the pure API point of view. However, there clearly are no APIs without somebody developing an implementation, so the development pillar (as discussed in “Development”) is an essential part of API landscapes. Increasing the overall effectiveness of the API landscape is one of the main goals of managing API landscapes, so looking into how development fits into the landscape perspective is important.

Once again, looking at the web as the biggest known API landscape there is can be informative. It probably would have been the kiss of death for the web early on if somehow somebody had declared and enforced the constraint that all applications for the web must be programmed using the same language and development tools. After all, one of the main winning recipes of the web, in particular when compared to competing approaches in its early days, was that it gave development teams complete freedom in how to develop their solutions, as long as what they released worked as an application that could be used with a browser.

On the other hand, while it was essential for the web’s success that development languages and tools were not mandated by web architecture, with web-based applications becoming mainstream, development support became a major factor of making web application development more effective. web-oriented languages and frameworks such as PHP, ASP, JSP, JSF, Django, Flask, Ruby on Rails, Node.js, and many others have shaped the way web applications were and are developed. But they also go through a lifecycle themselves, and it is safe to say that the web not only has already outlived many of the languages and tools that have been used for web-based applications, but will outlive the rest too, and any new ones that appear.

The lesson from this view of development practices and support on the web directly applies to API landscapes: it helps productivity and helps with certain protocols and patterns a lot when there are languages and tools for supporting the development of individual products. However, it is important to keep in mind that as protocols and patterns change, so will the languages and tools. And even without protocols and patterns changing, there still will be a steady stream of languages and tools claiming to be better solutions to existing problems.

Not looking at the development pillar from the landscape perspective, therefore, will cause you to miss important opportunities to leverage economies of scale, to establish and share development practices across teams, and to evaluate and adopt new languages and tools as they become available. For the landscape to support and realize these opportunities, the most important landscape aspects to keep in mind are variety, velocity, versioning, and volatility.

VARIETY
Looking from the API-as-a-Product standpoint (as discussed in Chapter 3), the initial stages of API conception are not concerned with implementation details, or how to develop the API product. Everything is about the design, and about discussing prototypes and seeing how early feedback might impact these early design stages.

After it is clear what the API product should look like, in this idealized picture the next task is to consider the best way to actually build the product. This decision should be based on the product design (making sure to pick the right tool for the job) and on the product team (making sure the team feels comfortable with the tool selection).

Since different APIs serve different purposes, target different consumer groups, and are developed by different API product teams, it is likely that there is no such thing as the single best development language and tool suite to use to develop every single API. Therefore, it is important to support variety in the landscape, and to allow teams to experiment with new approaches when they feel the need to do so.

Balancing variety with the need to not create a landscape of implementations is not an easy task. One of the main considerations should be the goal to have some continuity regarding the variety aspect: it is acceptable to use a variety of languages and tooling, but it is advisable to limit these choices so that there is some continuity in the choices, so investments and education become worthwhile through economies of scale, and so there is always some “critical mass” around development choices. If there are more than a given number of API products using particular development languages or tools, then these might move from being “experimental” to being “implementation” choices.

VELOCITY
For individual APIs, velocity captures how quickly a first API product can be released, and how quickly it can be changed and adapted to changing requirements. When it comes to development, velocity is impacted by the whole development and deployment pipeline, as discussed here and in “Deployment”. While it’s important to use languages and tools that are good solutions for the implementation problem, the landscape can help by providing support and tools to make the development and deployment process smoother and faster.

Velocity is also impacted by the size of the developer community: the more teams are using languages and tools, the quicker they evolve, and the quicker issues with them are likely to be addressed and resolved. This means that velocity is not just a question of choosing languages and tools that are appropriate for solving a problem; it’s also a question of how variety (discussed in the previous section) gets managed. If variety makes sure that there always is a critical mass to identify, address, and resolve issues, then managing velocity can be described as “picking the best solution for the given problem where there is critical mass at the organization level.”

VERSIONING
The practices around versioning have a clear impact on the development practices for APIs. As we discussed in “Versioning”, versioning is an important aspect of API landscapes, and responsible versioning becomes essential as the complexity of an API landscape grows in terms of landscape size, service dependencies, and the number of changes that are made throughout the landscape.

From the consumer point of view, versioning can be highly beneficial (when APIs are improved to provide services that consumers are interested in) or unnecessarily disruptive (when APIs change but the consumers are not interested in changing their consumption of the service). As discussed in “Velocity”, having a development process that allows the velocity required to quickly deploy changes, but also follows design practices that minimize the negative impact of new versions, will maximize the overall value that service agility can produce.

At the landscape level, it is important to make sure that development velocity is observable, so that it is possible to observe the rate of change, and to possibly provide ways to make information about various versions visible and accessible. Using standardized ways of meaningfully identifying (as discussed in “Semantic versioning”) and exposing version numbers is a good way to start, and already can provide deep insights into the dynamics of the overall API landscape.

VOLATILITY
The volatility of services in API landscapes, discussed in “Volatility”, introduces some challenges for existing development practices. The main issue is that by definition API landscapes are distributed systems, bringing with them all the fundamental challenges created by a decentralized model. Handling the volatility of API landscapes responsibly takes a different approach to programming in more tightly coupled settings, and when it’s ignored, the overall stability of the landscape can suffer (for example, through cascading failures).

When it comes to handling volatility well, development languages and tools, as well as practices, make a big impact. As such, the role of the landscape is to specifically identify and nurture development that is well suited for the volatility inherent in API landscapes. This may not be necessary for all scenarios, but it’s a good way to make sure that volatility is treated properly.

GRAPHQL AND API AVAILABILITY
Volatility may also be isolated in certain ways, meaning that some teams have to deal with it responsibly, and others not so much. For example, when following the Backend for Frontends (BFF) pattern, there will be one backend application serving as the “aggregator” of various APIs, and this backend then exposes one API to frontend apps, possibly in a flexible query-based API model such as GraphQL. In this scenario, the frontend has a very simple API availability model: either GraphQL is available, or it is not. However, the backend might have a much more complex model to deal with. When translating a GraphQL query into various API requests, these APIs all should be considered volatile. A well-written GraphQL resolver would be able to deal with partial outages of the underlying APIs, responding with partial GraphQL responses. In this scenario, managing volatility at the API level has been delegated to the BFF backend, whereas the BFF frontend only has to deal with volatility at the data level (assuming the scenario of partial GraphQL responses), making handling it quite a bit easier for the development team.

Managing the inherent volatility of API landscapes as part of the API development process can have a significant impact on the quality of API products, and on the overall stability of the API landscape. Making sure that development languages and tools, as well as development practices, take this aspect into account will make a difference in how well products behave in the inherently volatile environment of the API landscape.

Testing
In “Testing” we covered the importance of testing. We also set a rather high bar, saying, “No API should go into production without being tested.” As your API landscape grows, this may become challenging. Since time and deadlines are always a factor in software, you may experience pressure to not just speed up the testing process, but also to short-circuit the process by skipping steps or reducing the depth or thoroughness of your testing. This is always a bad idea. However, as you’ll see here, the way you test will need to evolve as your landscape grows.

Another challenge you’re likely to encounter as you scale up your API landscape is that the cost of testing will go up—not only the actual cost of doing the tests (in time and effort), but also the cost of not doing the tests (e.g., the cost of failing to catch issues through tests). In other words, the cost of failure in general goes up. This can be particularly worrisome for system-level architects since system failures are usually very visible and can, if not handled well, be very costly for the business.

The good news is this problem has been faced many times before by experienced companies, and there are available solutions for meeting the API landscape testing challenge. We’ll highlight some of the common ones here and, in the process, hope to give you some ideas on how you can start looking at your testing challenges and coming up with solutions that work for your company. With regard to testing, the four landscape aspects that are most important are volume, velocity, vulnerability, and volatility.

VOLUME
A common challenge as your API landscape grows is that the sheer number of tests needed for “coverage” starts to climb rapidly. And because most API ecosystems rely on calling other APIs, the number of tests grows nonlinearly. Adding one new API endpoint that is used by 12 other APIs doesn’t just add one more set of tests—it requires a modification of 12 more sets of tests! If your testing practice relies primarily on human-driven test suites (e.g., people typing on screens and recording results), the demands of testing a growing API landscape can easily overrun your QA department’s ability to respond.

The nonlinear growth of API testing is one of the big reasons to increase your company’s reliance on automated testing. It is much easier to scale up automated tests (e.g., by adding more test instances to run in parallel) than it is to add more people to your QA team, train them, and supervise them as they run manual tests. Of course, introducing automated tests has its own up-front costs, but these can pay off quickly as your system grows.

Another volume-related challenge for testing is the amount of traffic your tests need in order to produce reliable results. In the early days of your API adventure, simulating 100 requests per second (RPS) may be reflective of your production traffic. However, as you add more teams authoring their own APIs and these APIs start calling each other more often, the sheer volume of traffic can balloon quickly. When production traffic runs at 1,000 RPS, passing tests at 100 RPS is no longer a good predictor of success once the component is released. It is important that you keep close track of production request levels and make sure your test environment continues to reflect production demands as your ecosystem expands.

VELOCITY
As we’ve mentioned, test velocity—the ability to complete tests in a reasonable amount of time—can become an issue as your ecosystem grows. A good rule of thumb is that unit or bench tests should complete in a few seconds, behavior or business tests should complete in less than 30 seconds, integration tests should complete in less than 5 minutes, and scale/capacity tests should complete in less than 30 minutes. If your testing platform can’t keep up with this pace, and your development teams are producing continuous-change-style updates, you’ll run into a major backlog in the test/QA area again.

There are several ways to tackle this kind of volume challenge. We’ll highlight three here:

Parallel testing

Virtualization

Canary builds

One way to improve the velocity of your testing is to employ parallels. The most direct way to do this is to spread your automated tests across a set of machines and run them all at the same time. For example, if you have 35 tests to run after each build of a component, you could run all 35 tests in sequence on a single machine instance, or you could run all 35 tests in parallel on 35 machine instances. Assuming each test runs in 10 seconds or less, with the latter approach you’ll go from a test run that takes just over 5 minutes to one that takes less than 10 seconds. That’s velocity. Of course, this assumes all tests can be run in parallel—that is, there are no dependencies on the order of tests (test 13 MUST be run before test 14, etc.)—which, by the way, is also a good practice. Parallel testing helps improve your testing velocity before you release into production.

While parallels can aid in dealing with velocity at the unit and behavior test levels, the challenge of increasing velocity for interop- and capacity-level testing can be handled with the introduction of virtualization elements. It can be both costly and risky to run interoperability testing of a new component against other services. What if the new component mishandles production data? What if the test target interacts with existing components in an unexpected and damaging way? In small ecosystems, the use of mock services as stand-ins for production components can scale well. However, as the landscape grows, mocks may have a difficult time keeping up with the velocity of change in the ecosystem.

A powerful solution to improving velocity in testing while maintaining safety is to use virtualized services, typically via a general virtualization platform that can consume production traffic and then replay it on demand in a protected test environment. This allows developers to reduce their efforts to keep mock services in sync with production features and functionality while they increase their delivery of the actual production components. As an added benefit, good virtualization platforms will allow developers to create synthetic traffic that does more than mimic well-behaving production services; it can also virtualize malformed or even malicious network interactions and allow developers to test their APIs and services in scenarios that are less than ideal. This helps deal with the vulnerability and volatility aspects covered next.

Another way you can improve your testing velocity is to run some of your tests after you release the service into production. This is sometimes called canary testing or canary release. In this case, after basic bench and behavior testing, you release the new service to a select set of accounts (which may have volunteered to be beta testers). After this partial release, you monitor the results (see “Monitoring”) and, if all goes well, roll the update out to a wider production audience over time.

The canary solution makes a handful of important assumptions:

You still run basic tests to validate the component.

You have the ability to perform a partial release of a subsection of your ecosystem.

You have the proper monitoring in place to be able to assess the impact of the partial release.

You have the ability to back out the change quickly (e.g., within a few seconds) and can revert to the previous production build without damaging functionality or data storage along the way.

VULNERABILITY
As the scope of your API landscape increases (e.g., more endpoints) and the scale goes up (e.g., more teams using those endpoints), your ecosystem becomes more vulnerable. We’ll cover more of this in “Security”, but for now it is important to focus on how growing API landscapes mean increasing vulnerability, and ways to address that.

We’ve already mentioned that scaling up tests means making sure the traffic volume used in your tests matches that of production. This also holds true for cases where there is an increase in the number of teams or the number of other services that will be using a particular API. Your testing regime needs to account for many different API consumers making requests at the same time. For example, there might be cases where some type of consumer-driven state is passed between components. That means the cost of state handling can go up dramatically when you roll an API out to a wide consumer audience. It also means you may need more testing to validate that the state remains isolated between API consumers at the provider point, that large amounts of state don’t overrun working memory as the number of API consumers increases, etc. Vulnerability can shoot up due to more use.

Vulnerability can also increase as the type of users of the API changes over time. The key here is that, at some point, your API users may not be just internal teams, but key external partners or even third-party developers over whom you have very little control. Your tests need to reflect this possible change in the ecosystem and be designed to protect your system (and your data) from any mistaken or malicious activity by external users.

Much has been made in recent years of the famous “mandate” in which Jeff Bezos told his teams (among other things) that “All service interfaces, without exception, must be designed from the ground up to be externalizable.” While our experience with maturity models tells us you may not need to do this from day zero in your API plan, you do need to be prepared to deal with it as your landscape grows over time.

Finally, it is worth mentioning here that one of the most effective ways to improve your testing results is to write your code and your API contracts in ways that reduce the likelihood of test failures in the first place. For this reason, we find that many of the companies we work with that are able to properly respond to the increased scale and scope of testing are putting test experts on the development teams. In other words, they are “shifting left” when it comes to testing. By adding test skills to the teams writing the code and designing the APIs, it is possible to avoid mistakes that result in creating involved tests that take a lot of time to run and may not accurately reflect the conditions that exist in production. Consider reducing your system’s vulnerability by improving the test expertise of your development teams.

VOLATILITY
Lastly, as we’ve already mentioned, a growing API landscape means an increase in complexity—not just a larger ecosystem. What was a minor runtime bug when your company’s API world contained just a handful of endpoints managed by a single team has the potential to render most of your system inoperative if it turns out all your API services depend on one single service running on a single machine at some faraway location.

A larger API landscape runs the risk of becoming a more volatile landscape. One way in which growing ecosystems become more volatile is that things like fatal dependencies creep into the system unseen. A simple example of this can be found in the 2016 “left-pad crisis” in the Node.js community. Without getting into the messy details (see the linked article if you’re curious), a small library was, over a small period of time, included in thousands of Node.js projects. A dispute with the author of this library led them to remove the library from circulation, and almost immediately thousands of builds crashed—including the build for Node.js itself! While it took less than an hour to find and fix the problem, it was a stark reminder of how large systems can become more volatile over time.

And this kind of volatility isn’t limited to cases where components “go missing” or are in some way unavailable. It is also possible that some API or component upon which your system depends will change in a way that breaks critical functionality in your ecosystem. You can train your own teams to reduce this likelihood when they update their code, but you will not have any control over third-party libraries or frameworks that make their way into your ecosystem. As your landscape grows, you’re more likely to increase your use of external APIs, and they will increase the volatility of your landscape.

That means it is important to add tests that expose fatal dependencies and highlight the cost of critical failures of key components. The best place for this is in the interoperability or capacity test phase, where links to other APIs and services are exercised. As we mentioned in the the previous section, a direct way to reduce vulnerability is to add testing expertise to your design and development teams so these kinds of problems can be addressed before a component or API workflow ends up in production.

In larger systems, even small bugs can have wide-ranging effects. Be sure to test for, and code around, cases where key components go missing or change in ways that make them unusable for others in the ecosystem.

Deployment
One of the major pillars of any API program is deployment. No matter what design or build process you use, it is not a “real thing” until the API or component has been published (see “Stage 2: Publish”), and deployment is how you get something published. At the start of your API program you can focus on a clean, simple pipeline for releasing your APIs into production. Many organizations even use manual release processes (e.g., point-and-click in release tools, human-driven selection and execution of scripts, etc.) at the start of their API program. However, as your API landscape begins to grow, manual releases are difficult to scale and introduce a new level of needless volatility into your ecosystem.

The most common tactic for scaling deployment is to automate as much of it as possible. This is the one of the key lessons of the DevOps and continuous delivery movement. Jez Humble, coauthor of the book Continuous Delivery (Addison-Wesley), has been quoted as saying, “[The] goal is to make deployments—whether of a large-scale distributed system, a complex production environment, an embedded system, or an app—predictable, routine affairs that can be performed on demand.”

There are a number of advantages to automating deployment; especially when it comes to scaling deployment for your API landscape. We’ll focus on four of the landscape aspects here: variety, velocity, versioning, and volatility.

VARIETY
In most of this book, we’ve emphasized the value of supporting variety as your ecosystem grows. However, when it comes to the build and deployment process, variety can be a real threat to your landscape’s health and stability. Running a process that results in a production deployment should be consistent, deterministic, and repeatable. If your team executes the installOnboardingAPIs process today, it should produce the exact same results if that process is run several days later. Deployments should be nonvariant.

That means driving variability out of the system. The build and deployment processes are a great place to implement approaches like Six Sigma, Kaizen, Lean production, etc. That means focusing on eliminating minor variations in the release and making sure to build up deployment technology that collects all the release artifacts (code, configuration, etc.) in one place for easy publishing. It also means tracking the operating system and other supporting dependencies carefully and making sure these are exactly the same for each repetition of that same deployment. Good CI/CD platforms will give you the opportunity to design and implement a reliable and repeatable deployment process.

SIX SIGMA, LEAN, KAIZEN
There are a number of models aimed at continuous improvement and driving out variability while increasing quality. Six Sigma, Lean, and Kaizen are probably the best-known of these models, but there are others. And even each of these three has several variations (e.g., Lean Six Sigma, etc.). If your company doesn’t already have a program along these lines, we recommend you look into it. There is a decent article on Formaspace comparing the top three that might be a good place to start.

While driving our variability in your deployments is critical, you may still need to support a variety of CI/CD toolchains. It is not a requirement that all parts of your organization (from mainframe to handheld) across the globe use the exact same platform for deployment. However, we advise constraining your platform variants as much as possible, since most of these deployment platforms represent a large investment of time and money.

VELOCITY
Speeding up the deployment process is often mentioned as a prime goal when companies work to transform their IT processes. There are two aspects of deployment velocity to consider as your landscape expands. The first we call type 1: shortening the time between releases for a single API/component. The second we call type 2: increasing the overall speed of all release cycles in your IT group.

The first case (type 1) is the one most people think of when they think about deployment velocity. And it is an important one. We often talk to our customers about reducing the “feedback-to-feature” loop or, for new projects, getting from “idea to install” faster. Speedier deployment can reduce the risk and cost of experimenting with a new product or service, and that can improve your company’s ability to learn and to innovate over time. Again, automated, deterministic deployments can help you increase your release speed.

The second case (type 2) is something quite different. In this instance, you need to release more things into production over the same time period. That means more teams doing releases, more releases landing in production, and more changes to your landscape. If you are relying on a single central release team for all your production deployments, it will be difficult to gain this type 2 deployment velocity. There are limits to scaling a single release team.

A better approach is to start distributing the responsibility for releases to a wider community. This is another reason that automating as much of the release process as possible is valuable. The more automation you have in place, the more humans can focus on edge cases and expectations in order to get things working properly and consistently. Just as in other pillars that we’ve covered here in this chapter, you can more safely speed up the process by distributing it and/or running parallel processes. This results in more releases overall without necessarily speeding up individual release cycles for everyone.

DISTRIBUTED RELEASE MANAGEMENT AT ETSY
Mike Brittain, engineering director at Etsy, has created a very nice set of slides and video presentation on their version of distributed releases called “Distributed Release Management”. If you’re interested in pursuing this idea, Brittain’s presentation is a good place to start.

When speeding up deployments, be sure to take into account the value of velocity type 1 and velocity type 2.

VERSIONING
We spent some time discussing versioning in general in Chapter 8 (see “Versioning”). While we made the case that design and implementations should avoid versioning the API’s public interface, the story is different when it comes to the internal interface. API consumers should not be bothered with bug fixes or minor (nonbreaking) changes; they should only be alerted when the interface breaks and/or when new features are available. But internal users (the developers, designers, architects, etc.) should be able to see every minor tweak and change of the release package — even small things such as changes to supporting assets like logos, etc.

One way to make sure you expose small changes in the deployment packages is to version the release using the semantic versioning pattern (see “Semantic versioning”) of MAJOR (breaking change), MINOR (backward-compatible new feature), and PATCH (no interface change, bug fix). We’ve also seen customers include an additional level: RELEASE (i.e., MAJOR.MINOR.PATCH.RELEASE). With this added value, it is easier to track every build and/or release cycle down to the smallest change. And that can be important when a production release acts in some unexpected way. The ability to trace the package using the RELEASE number can be very helpful in determining what is different in the package.

Most release tools will also allow you to assign an independent build number to each release. That way, you don’t need to amend the semantic versioning pattern and you still get detailed tracking on every build and production package. Whatever you decide to do, remember that internal releases get detailed identifiers and external interface identifiers only need to change when there is a breaking change.

VOLATILITY
As you might expect, increasing the velocity of deployment—both type 1 and type 2 (see “Velocity”)—runs the risk of increasing the overall volatility of your system. For this reason, many organizations attempt to slow the pace of release. However, this is usually not a good idea. Instead, there are three things you can do to make sure your deployment pillar doesn’t introduce unexpected volatility into your ecosystem:

Ensure nonbreaking changes in releases.

Maintain deterministic, nonvariant deployment packages.

Support instant reversibility of installs.

As mentioned in “Versioning”, deployments should—whenever possible—avoid versioning in the sense that most of us think about it. Our experience is that you can make meaningful changes to a running system without having to “break it” each time. Jason Randolph of GitHub calls this evolutionary design and explains the value of this kind of design work this way:

When people are building on top of our API, we’re really asking them to trust us with the time they’re investing in building their applications. And to earn that trust, we can’t make changes [to the API] that would cause their code to break.

Jason Randolph

As Rudolph mentions in his GitHub talk, you can leverage design elements to make it easier to introduce nonbreaking changes. You can also create tests (see “Testing”) that check for breaking changes and include them in your build pipeline to reduce the chances of disrupting production. Taking the “no breaking changes pledge” can limit the possibility of added volatility as you scale up your deployments.

Another key to reducing volatility for deployments is ensuring each release package is fully self-contained and, as we mentioned earlier in this chapter, deterministic (see “Variety”). When you can safely predict the results of a deployment (e.g., when you are confident which elements in production will be affected by the release), you can reduce the likelihood of surprises in the production update. Also, anyone responsible for placing a package into production should be able to execute the release in production, or some other environment (on a dev machine, on a test server, etc.), and get the same results. This is critical for testing the release and for uncovering interoperability bugs and other extra-package errors that might occur in production.

Finally, an important aspect of deployment volatility has to do with reversibility. As we mentioned when discussing velocity (see “Velocity”), type 2 velocity (more overall releases) can threaten stability by increasing volatility. Ensuring nonbreaking changes and nonvariant deployment can certainly help reduce disruption in production, but it cannot prevent it 100%. In cases where unexpected bugs creep into releases, it is essential to be able to instantly reverse a change; to back it out within seconds. This is a kind of worst-case-scenario solution. Furthermore, backing out the change means doing it without damaging any collected/stored data. In other words, all your deployments need to account for reversibility of any data schema/model changes. This will mean changes to the way your teams design and implement production updates.

Security
In “Security” we talked about the importance of basic security elements (identification, authentication, and authorization). We also discussed ways to reduce the overall attack surface and add resilience and isolation to each component and/or API released into production (see “Vulnerability”). As you might imagine, each of these elements becomes more important as your landscape grows. And, true to form, they become more challenging, too. Security is a wide-ranging and complex subject—one that we won’t be able to get into in depth here. However, we’ll highlight three of the most relevant landscape aspects here and discuss how they affect overall system security.

VELOCITY
A big challenge to maintaining proper security in an expanding API ecosystem is the velocity of change to the landscape itself. More components are added, usually at a faster pace, and more interconnections are added for more users. Many of our customers operate security infrastructure that requires explicit access control definitions before a component or interface can be released into production. This works when the pace of change and breadth of the ecosystem are relatively limited. However, as the landscape increases in scale and scope, up-front access control definitions can become a bottleneck. They can hold up production releases and slow feature and bug fix rollouts.

A common way to deal with the velocity problem for the security pillar is to make sure components are designed and built to operate in a secure manner even when access control profiles are not yet in place.

Another way to maintain security while speeding up the release process is to introduce automated security testing. Scripting security tests is not a perfect solution (it is hard to test for malicious attempts in scripts), but it can help; running security tests during the build cycle can help you catch problems early, reduce the cost of fixing them, and decrease the likelihood of experiencing runtime damage.

VULNERABILITY
A growing API landscape means an increased surface area and a resulting increase in vulnerability. Having lots of teams releasing lots of components and doing it all quickly makes it very tough to keep up with the possible vulnerabilities introduced into your system. As we just mentioned, adding security tests during the build phase can help, but it is not the only thing you can do to tackle a growing vulnerability aspect in your API landscape.

When each component release is treated as a “one-off” security event, it can be incredibly difficult to monitor, validate, and track your vulnerability space. An important way to deal with this increase in both scope and scale is to 1) rely on blanket policies as a starter for component-level security profiles and 2) push responsibility for the work of tracking and reporting security-related activity as close to the team level as possible.

Relying on policy-driven security implementations (rather than code-specific implementations) has several benefits. First, declarative policies are easier to read and debug than imperative code. Second, most security proxies allow you to treat each policy as a reusable unit (a kind of micro-policy) and then combine these policies into a strong profile package that you can more easily monitor and track. Finally, many security platforms allow you to manage policies via scripting and/or command-line tools that are compatible with CI/CD systems so that you can make your security policy a release package element that all teams must learn to deal with.

And that leads to the second part of the approach: pushing tracking and reporting responsibility toward the developer teams. It is not likely that a single security team (especially one hosted at the corporate level for a global enterprise) can sufficiently closely monitor and respond to component-level security events. Instead, it is much more reasonable to expect the team that developed and released that component or API to keep an eye on things. However, they can only do that well with adequate tooling and support. As your ecosystem grows, it is important to convert central expertise into distributed tools and practice. You can do this by moving some of your company’s security expertise into developer teams (as we recommended for testing). Another way to scale your security skills is to create tools such as design-level practices, build-level testing, and production-level dashboarding. By investing in tools to help scale out your existing security knowledge you can successfully broaden the scope of your reach and improve the overall safety of your API landscape.

VISIBILITY
And that leads to the last aspect to highlight here: visibility. In the world of security, it is the things you don’t know that can hurt you. And you can’t anticipate all possibilities. Instead, along with adopting practices like “zero trust,” policy-driven security rules, and build-time security tests, you can also add increased visibility through the use of logging and dashboarding.

Dashboards are important because they offer a real-time view of network activity. This gives teams from all areas of the company a chance to watch their interfaces and components in action. And that includes the security teams. The initial value of dashboards is to simply “make visible” the common traffic on your network. As time goes on, teams can fashion filters to focus on traffic that they have learned is an important indicator of system health (or lack thereof).

Often the data points that appear on dashboards are the kinds of KPIs and OKRs (see “OKRs and KPIs”) we’ve discussed earlier in this book. It is up to security teams to identify key values worth monitoring and make it easy for all developer teams to supply this real-time information. Most often this information can be pulled from gateways and proxies used throughout the ecosystem, but sometimes individual components will need to be coded to collect and emit important metrics on requests for authentication, validation, access grants/denials, and more. By providing development teams with the data points and patterns security experts expect to see, and ensuring component-level compliance during prerelease testing, you ensure that your security operations can properly respond to the added scale and scope of your company’s growing API landscape.

Typically, logs can be used as part of an “after-action” exercise that helps you and your security team understand what happened and (hopefully) gives clues on how to prevent a repeat of the same problems in the future. Instituting a robust and reliable logging practice for all your development teams is key to making sure this information is captured for possible use in a security postmortem discussion. But just collecting the information in the form of logs is not enough. You also need to make sure to store the information in a form that enables easy data access, filtering, and correlating so you can find and inspect just the records you need. A good way to do this is to adopt a practice of distributed collection (e.g., each team is responsible for collecting tracking information) and centralized storage (e.g., a single platform where all logs get sent for later filtering and review). Central security guidance can also provide recommended and required tracking data points and actions, and you can write build-level tests to ensure all teams comply with the guidance before their work gets released into production.

Monitoring
Monitoring has several useful purposes, including identifying bottlenecks, tracking internal KPIs and external OKRs, and alerting teams to performance anomalies such as unusual traffic spikes, unexpected access grants, and more. In the early days of your API program, monitoring can be handled with relatively small, focused tools and a few simple dashboards and log inspection practices. However, as with many of the other API pillars, as your API landscape grows the challenges of volume, visibility, and volatility can overrun your existing tooling. We’ll call out some common challenges and possible solutions here.

VOLUME
A common challenge to the monitoring pillar as your API landscape expands is that the sheer volume of monitoring information starts to overwhelm your ability to deal with it. This usually happens when the organization has a centralized monitoring management model, where a small group of people with monitoring skills are tasked with collecting, managing, and interpreting the incoming real-time and historical log data. At some point the volume gets beyond what a single team can handle—and expanding the central team does not make this better. Instead, as we suggested in “Vulnerability”, a better strategy is to push the monitoring expertise closer to the teams developing the APIs and components. Distributing the work of collecting and managing the tracking data is the first step. Once teams own their tracking data, they can start developing filters and correlations that result in meaningful insights about that data.

However, single-component or single-API monitoring is only part of the challenge. As your landscape grows, the interplay between these components needs to be monitored, too. A good tactic to meet this new challenge is to create a central repository of tracking data that can be focused on correlations across the various APIs in your organization. In this case, the central data store is often a filtered, correlated subset (often time-compressed) of the actual tracking data owned by the component/API teams. This centralized data is a selective, abbreviated view of the entire operation — one that can be used to spot patterns and anomalies. When they are identified the teams can then find pointers into the tracking details to help root out problems and confirm insights.

Note that the practice here is:

Get teams to collect and manage their tracking details.

Stand up a central repository that pulls selective, filtered data from team tracking stores.

As trends/problems emerge at the central level, rely on the details at the team level to confirm/resolve any issues.

VISIBILITY
The practice of creating a central repository for filtered/correlated data is a key element in maintaining and even improving monitoring visibility. As a corollary to the point we made in “Security” about how you can’t anticipate all possible problems, for the monitoring pillar it is important to remember that you can’t anticipate all possible data points to track. For that reason, early efforts at logging and monitoring often include lots of values that have no known relation to the current state of your network. They do have a relation, just not one that humans might know at any point in time. This can lead to teams truncating data collection by dropping “unrelated” values from the logging streams. This is not usually a good idea.

Instead, it is smart to log everything and monitor only a selective set of data points. This follows our earlier guidance encouraging teams to own their own data collection and storage while allowing central monitoring entities to pull filtered, correlated versions of that data into a shared set of dashboards for everyone to see. While teams keep an eye on a more detailed (but limited) view of the system, central monitoring operations can keep a wider (but less detailed) view of the same system. This is a down-to-earth instance of Heisenberg’s Uncertainty Principle.

HEISENBERG’S UNCERTAINTY PRINCIPLE
In 1927, Werner Heisenberg published a physics paper which contained the observation that the more precisely the position of some particle is determined, the less precisely its momentum can be known, and vice versa. In the IT world, this usually is commonly experienced as the trade-off between detailed understanding of a small part of the system and knowing how that small part of the system affects the whole system. Attempts to gain both a detailed understanding of each part and a full understanding of how the parts interact—at the same time—are less and less reliable as ecosystems grow. That is why we share the guidance that teams maintain a detailed view and the central monitoring operation maintain a broader, less detailed view.

Another important aspect of visibility for monitoring systems is the related quality of observability. As landscapes grow, it becomes harder to observe their behavior. You can use monitoring, or more specifically the publishing of monitoring data, as a way to improve overall observability. Unexpected results, bugs, and other confusing phenomena often occur because humans can’t see how a system works and/or how components of the system are related to each other. Our experience is that, upon uncovering an odd (“edge case”) bug in a complex system, people are apt to say something like, “Huh, I didn’t know that was possible” or “I didn’t think it worked like that.” Improved monitoring and dashboarding may not prevent something from going wrong, but it can help reduce the likelihood of a surprise when something doesn’t go as planned.

VOLATILITY
Finally, again to echo what was stated in “Security”, it is our experience that larger systems are more likely to experience a higher degree of volatility than smaller systems. This observation was expressed by computer scientist Mel Conway in his 1967 paper “How Do Committees Invent?”: “The structures of large systems tend to disintegrate…qualitatively more so than with small systems.”

While his observation dealt primarily with the development phase of large projects, we see the same kind of behavior at runtime in large systems. One small bug has the potential to crash the entire system, and as the system grows, that crash becomes more and more costly. This can lead companies to assume the quality of their ecosystem is degrading over time, but the truth is these kinds of bugs were most likely always there. It’s just that now that the overall system is larger, their reach—their risk—is higher than before. You can reduce the risk of a single bug disrupting your entire landscape and gain a better perspective on the overall system quality by maintaining a solid monitoring program.

Discovery
As discussed in “Discovery and Promotion”, the discovery and promotion pillar of the API lifecycle consists of all activities that help to make an API findable and usable. For individual APIs, this often means understanding the context in which it should be discoverable, and potentially helping make it easier to find and use.

In complex and constantly growing API landscapes, discovery follows the same general trajectory witnessed over time for websites and pages on the web. Initially, it was sufficient to have a curated list of sites and pages that were compiled into categories in an attempt to make them findable. This approach was practiced by Yahoo! as the initial primary discovery mechanism on the web, and worked well as long as the number of sites and pages was relatively small, the rate of change was small, and it was appropriate to have one categorization scheme for all content on the web.

This approach clearly did not scale well, though, and was rapidly outgrown by the enormous growth, change frequency, and diversity of content on the web. Starting in 1996, Google (initially called BackRub and being a Stanford-only campus-provided service) radically changed discovery by introducing two major changes:

Search by content replaced search by category, meaning that instead of relying on a categorization scheme created by a third party, search was now directly driven by full-text search of the actual content.

Ranking by popularity replaced manual ranking, replacing third-party decisions of how to sort content by computing content relevance as a function of popularity on the web (as given by inbound links).

There is of course a lot more to the story of how discovery evolved on the web, but it is important to have the general trajectory in mind. While this approach does have some side effects (making popular sites even more popular, and making it harder to find less popular sites), it generally worked well enough for users to find it useful, and therefore most discovery tasks on the web today are driven by this general model.

In the world of APIs, content has a different meaning, as APIs are not so much content by themselves, but instead are service descriptions. Popularity, however, is a concept that can translate relatively easily into the world of APIs, where it is not too far-fetched to conceive of an API dependency graph as the equivalent of the web’s link structure.

So far, there is no clear sign of who will become the “Google of the APIs.” And since many API landscapes contain mostly APIs that are in the private/partner space, rather than being public, it is not quite clear whether the exact same trajectory of discovery will be seen for APIs as was seen on the web. However, for discovery and promotion to be scalable, it is important for relevant information to be made available in a way that it can be used for automation and tooling. The major landscape aspects playing into this are variety, volume, vocabulary, visibility, and versioning.

VARIETY
API documentation can be produced in many forms, and the form it is produced in is dictated by the investment decisions in this lifecycle pillar. Investment is driven by API maturity, as well as by the intended audience for an API. Investment also is driven by the support and tooling that may be made available at the landscape level.

With the increasing popularity and importance of APIs, sophisticated solutions for API documentation and discovery are available. Often these are integrated suites, combining aspects of documentation, discovery, code generation, and other DX factors. While these suites are definitely valuable, it should be kept in mind that they necessarily have built-in bias (such as preferred API styles), and like all tooling should be used in such a way that they can be augmented or replaced when necessary.

The ideal solution for making sure that discovery can be assisted by tooling, while remaining open and declarative at its core, is to expose all information necessary for discovery in the API itself (see “API the APIs” for the principle), and then let support and tooling pick up this information and use it for landscape-assisted discovery. This follows the general principle of exposing everything relevant in the API itself, and is discussed in greater detail in “Vocabulary”.

VOLUME
As the API landscape grows in volume, it is important to build up discoverability as an aspect that not only can help find APIs, but also one that can rank them. Finding is necessary but not sufficient, as everybody who has ever used a web search engine that reports millions of hits for a given search term knows.

Discovery thus requires more than just ways to find APIs; it also requires ways to better understand and thus rank them. It is likely that the understanding of “useful ranking” will evolve over time in any given API landscape. Initially, ranking might not even be necessary since there aren’t that many APIs. Then it might become a necessity because of the increasing volume of APIs. Useful ways to perform ranking might change over time too, as volume grows and as the definition of “best matches for a given search” evolves over time.

In order to be able to grow along this axis of continuously changing and improving discovery, it is important to keep in mind that APIs should make as much information available about themselves as seems useful at any given point in time, and that this set of information can continually evolve as the landscape and the discovery needs for APIs change over time.

From the landscape point of view, it is important to provide support and tooling that makes it easy to become easily discoverable in the API landscape. Depending on the discovery model, this set of tasks might look surprisingly similar to Search Engine Optimization (SEO) on the web, where there is a balance between the information that can be harvested and used by discovery services and the level of cooperation that individual providers are willing to invest.

VOCABULARY
Discovery means making APIs easier to find, and while the general principle discussed here follows the pattern of how large-scale discovery on the web moved from Yahoo!’s categorization model to Google’s full-text search and popularity-based ranking model, it is helpful to consider some other developments on the web.

In 2011, Schema.org was started as a collaboration between the major search engines Bing, Google, and Yahoo! in an effort to create a single schema across a wide range of topics that included people, places, events, products, offers, and so on. The main goal of the project is to allow web publishers to mark up their content as they see fit, and to allow search engines to use this markup as another input to their search and ranking algorithms.

It is worth noting that this specifically applies to web content, and not to APIs. But the principle is what matters most: Schema.org keeps evolving as a vocabulary of terms on the web that publishers can use to mark up their content. This is possible because the vocabulary itself and its use by vocabulary users and consumers are decoupled. As the vocabulary evolves, content can be marked in more sophisticated ways, and production and consumption of vocabulary terms is loosely coupled.

For API landscapes, similar principles can be established. The landscape can support and promote the usage of terms to increase discoverability, and it can provide support for producing marked-up content (e.g., in documentation and/or API home documents) as well as for validating it. Deployment pipelines can even automate tests for the presence of some terms: for example, testing for “API style” and, if no such term is found, raising a warning and asking the API team to include this information and make it discoverable.

VISIBILITY
As discussed in “Volume”, one of the primary aspects to keep in mind when thinking about discovery in API landscapes is volume. And as we saw in that section, the main way to manage volume is to make as much information about the API visible in the API as is necessary. The set of “necessary” information of course will evolve over time, so the main thing to keep in mind for visibility is to be able to start small, and to have a plan for how that can be continuously evolved into a bigger set of information exposed in individual APIs.

By keeping the aspect of visibility in mind, and keeping in mind that the set of visible information is likely to evolve over time, discovery can be continuously evolved in the API landscape in the same way as it continuously evolves on the web. Discoverability is never “finished,” and the way it is approached is to evolve the information that is available to discoverability tooling, and to observe the landscape’s evolution and consider what changes would best help improve discovery.

VERSIONING
APIs in an API landscape tend to change, and making that easy is one of the goals of having an API landscape in the first place. Enabling change without breaking all consumers with every new release also is a goal that is inherent in many APIs and API landscapes. With good change management practices, it is possible to better decouple API producers and consumers, and to allow them to evolve independently.

Ideally, API teams can evolve their products and release new versions at their own speed. However, while this makes it easy for the API teams, it makes it harder for API consumers to keep track of versions, and to be able to find older versions and explanations of changes between versions.

One possible way for landscapes to make it easier to see and understand APIs and their versions is to require APIs to document all versions. By making the version history available through the API, it can be more easily made discoverable, allowing consumers to discover information about an API’s version, and possibly to understand its evolution throughout the history of the product.

This aspect can become trickier for breaking changes of the API, where the API implementation may have changed completely and it is harder to keep documentation and versions discoverable at all times. In these cases, it may be helpful to provide support so that API teams do not have to spend additional effort keeping legacy versions around, and instead can rely on the landscape either still making some information available, or informing consumers that an old version is still known, but that detailed information is not available anymore.

Change Management
One important pillar of the API lifecycle is change management, as discussed in “Change Management”. Part of the general API journey should be to minimize disruptions of the API ecosystem as an API evolves. Often, one way to help with that is to follow change management principles that may revolve around extensibility models and only making safe changes according to these models; another approach may be to never change released APIs and instead have an operational model that makes it feasible to run many different versions in parallel.

Planning for change is one of the central issues of API landscapes and their ongoing evolution, and thus change management is a pillar that is very much dependent on how the API landscape supports API changes with guidance and tooling. In order to help individual APIs with their change management, the aspects of vocabulary, velocity, visibility, and versioning are the most relevant ones, and are discussed in the following sections.

VOCABULARY
One important aspect to keep in mind when considering change management for APIs is the impact of vocabulary evolution on API evolution. Vocabularies are a common and well-known aspect of API design, and designing a vocabulary into an API always means that vocabulary updates result in API updates. While with the right extension model these updates can be nonbreaking, they still trigger the whole chain of updating the API and its associated resources, and possibly similar activities for API consumers.

Vocabulary management also can be decoupled from an API, turning the vocabulary itself into a resource that can evolve, and thus allowing the API to remain stable even when the vocabulary changes. As discussed in “Vocabulary”, one popular way of doing this is by referring to a registry, either managed by some external authority or possibly managed and hosted as part of the landscape. In this model, vocabulary changes do not necessarily trigger API changes, and there is the added benefit of better vocabulary sharing across APIs.

For these reasons, thinking about vocabularies at the landscape level makes a lot of sense, and can support and simplify the design and evolution work of individual API product teams. At some level, the idea of vocabulary support at the landscape level is related to the concept of a data dictionary, but that term most often is related to specific aspects of database schemas, whereas the idea of vocabularies is to be independent of implementation and essentially just be data types that are managed by themselves and can be reused across various APIs.

VELOCITY
Making changes primarily should be driven by product planning and iteration, based on feedback and feature rollout. Change management is necessary to make this easy, and first and foremost should not get in the way of making changes. Velocity (as discussed in “Velocity”) is one of the main goals of moving to APIs and API landscapes, and understanding how velocity is assisted or hampered by the landscape is an important ongoing activity.

API product teams should be encouraged to provide feedback about how they feel their velocity has been helped or hindered, and this feedback is important to keep in mind when creating guidance about how to improve change management, and building up support and tooling at the landscape level. Change management is one of the pillars that should always be taken seriously, and one reason for that is its direct link with velocity.

However, once again it is important for API products to consider the context of their change management efforts, possibly delaying more sophisticated ways of managing change in later API maturity stages. “If an API changes in the landscape, does anybody care?” is a question that very much depends on who is depending on this API.

If nobody uses the API (so far), it could be argued that any change management is wasted effort and therefore impacting velocity. On the other hand, if usage picks up, there is the conundrum that with broader usage, better change management helps with keeping up velocity, but now that there are users, changing the API to support better change management itself has become more complicated. This means that in order to maintain velocity, in particular through advanced stages of the maturity journey, considering change management from the very beginning is a good investment, and one that should be supported well at the landscape level early on.

VERSIONING
Generally speaking, APIs should follow the model of semantic versioning (as described in “Semantic versioning”). They don’t have to use the exact same scheme, but the distinction of change “levels” is useful:

For patch versions, there is no observable change at the API level, so this kind of change is only interesting for consumers to possibly check whether an implementation has been changed to address a bug.

For minor versions, which are by definition backward-compatible, consumers might be interested to learn about the changes, but they might also choose to ignore them if the service is sufficient for them.

For major versions, consumers must take action, as these introduce breaking changes. Consumers must be notified when major versions are rolled out, and should also be notified about how much time remains before the version they currently depend on is removed from use.

There are many different ways in which these mechanisms can be managed by individual APIs. Since change management and dependency management are central to the robustness of an API landscape, a good guidance is to have some coherence about these issues, so that it becomes easier for API consumers to deal with the velocity of changes in the API landscape.

After all, having the ability to change and update APIs at high velocity is a good thing, as long as the negative side effects are kept in check.

VISIBILITY
Managing visibility is a tricky balance when it comes to change management in API landscapes. Generally speaking, API consumers would like to use an API as undisturbed as possible, unless they learn of new features that they want to use, in which case they are willing to invest in adapting their API consumption to the changed API. Making change management visible and therefore allowing consumers to write code that can react to this information helps to improve the resilience of an API landscape.

As mentioned in the previous section, it is important to build change management into the API landscape so that the velocity of changes does not disrupt services more than necessary. One of the main considerations just discussed is what to make visible. It is recommended to use a model that reflects the semantic versioning scheme of patch, minor, and major versions.

From a security point of view, it may be advisable to not expose patch versions to the public, or even to partners. After all, these changes are not supposed to change the API or its behavior, other than potentially resolving implementation problems.

Minor versions should be made visible, as this helps consumers to understand their availability. Consumers should always have a way to inspect the version history, and ideally what has changed between minor versions should always be documented. Major versions, of course, must always be visible because they introduce breaking changes.

Making versions visible in a unified way helps API consumers adapt to that model of change management in the API landscape, and can even allow them to use and reuse tooling to react to it. For this reason, treating versioning in a way that is consistent across APIs adds considerable value (in the form of better stability) to an API landscape. Providing guidance about what to do, providing support for how to do it, and having tools to verify that APIs actually follow the guidance will help to make change management less challenging for API producers, while allowing API consumers to benefit from robust change management practices throughout the landscape.

Summary
In this chapter, we set out to combine the lifecycle pillars introduced in Chapter 4 with the landscape aspects (the eight Vs) introduced in Chapter 8. The most important goal of this exercise was to highlight the move from focusing on one API to focusing on many APIs, so that on the one hand individual APIs can flourish in the API landscape, and on the other hand the API landscape as the constraining and supporting fabric around APIs can continuously evolve. The main factors in this evolution are feedback by observation, allowing the landscape to understand the evolution of API practices, and support through guidance and tooling, allowing the landscape to turn the observations into actionable ways to facilitate change over time.

The landscape/lifecycle matrix (see “Landscape Aspects and API Lifecycle Pillars”) is a way to show the relationship between landscape aspects and lifecycle pillars. The way we addressed the complexity of the resulting grid was by focusing on those combinations of landscape aspects and lifecycle pillars that deserve special attention.

Our general model of relating landscape aspects and lifecycle pillars is to look at observability in individual APIs, so that from the landscape perspective, it becomes possible to observe how individual APIs behave. This follows the general “API the APIs” principle. The second step, then, is to use these observations to identify areas in which API development could be best guided and supported by investing in pillars. We always apply the “why/what/how” model (see “The Center for Enablement”) to make sure that API guidance and implementation guidance are cleanly separated. This allows API and implementation practices to evolve independently, meaning more continuity in the API landscape because implementations can change without changing API-level practices.

Finally, this chapter was an opportunity to bring together several elements discussed elsewhere in the book. We touched on the notion of maturity as an indicator of when the shape of your landscape is changing, and we mentioned the process of distributed decision making as a tool for sharing responsibility and guiding actions throughout a growing organization. Each company has its own culture, common practice, and levels of expectation. Hopefully, the material here will give you some ideas on how to develop your own unique landscape/lifecycle matrix and learn to use your company’s internal decision-making process to continuously improve your ecosystem as it matures over time.

1 An example of this is the many attempts in larger organizations to create an enterprise information model (see “EIMs and APIs: Perfection Versus Pragmatism”). There are few cases where the enterprise is slow-changing enough to make this a feasible undertaking, and even in those cases these EIM initiatives are rarely reported as successful undertakings.

2 The webby way mentioned first is called transclusion, meaning that it is made accessible via the API documentation, but retains its identity as the documentation of the vocabulary.

3 This is at least true for nonbreaking changes to the API. For breaking changes (major version changes in a semantic versioning scheme), a different scheme may work better, such as archiving the documentation of old versions (which in itself could be become a service provided by the API landscape).