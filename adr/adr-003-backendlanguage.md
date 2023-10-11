ADR: Selection for the Backend Language

Status:

Proposed

Context:

In the process of creating a mobile app for a retail company a backend language is needed. Main features of the app being order tracking, shopping, and a loyalty program. Considering the potentially massive amount of traffic in a retail store app, careful consideration for which language to be used for the backend needed to be done.

Decision:

We have decided to use Node.js for backend development. The reason being as follows:

Scalability of Node.js: Like previously mentioned, the varying server loads a retail app may experience needs scalability. With node.js it is known to offer easy scalability, so it is well suited for this type of application. (I honestly tried learning the reasoning but couldn't quite wrap my head around it).

Use of JavaScript: Javascript is being utilized which is a language our team is familiar with. This will simplify development, as we can focus on coding rather than figuring out a new language.

Optimized with caching: Node.js can be optimized with caching services. Without a cache, the server application will have to execute the entire code and retrieve information from the database each time it processes a request.

Consequences:

Pros:

Cons:

Pros:

- The use of platform-specific UI components creates a familiar environment for users of each platform, making the end users' experience much better.

- After familiarizing ourselves with each framework, the development time long term should decrease as these frameworks allow for more efficiency

Cons:

- The initial learning curve will be steep, as we would need to create two native apps instead of a single cross-platform app. Each with their own language syntax and such.

- We would still need to maintain two different apps after completion of each app, resulting in possibly more work or resources.