ADR: UI Framework Chosen

Status

Proposed?

Context

A UI framework needed to be chosen for the creation of our mobile app, a native app for a retail company to be more specific. Key features like browsing and purchasing products, viewing order history, tracking delivery status, and a loyalty program, needed to be considered when picking a framework, whilst having a goal of a clean and efficient user experience.

Decision

Considering our initial plan of having it be a native app to fit their requirements, two frameworks are needed for each platform, iOS and Android. With that in mind we have chosen the following for each platform:

iOS:

We have chosen to use SwiftUI for our iOS framework as it allows for the use of iOS native UI components. SwiftUI seems to have a lesser learning curve in comparison to maybe something like UIKit, which will help as our team isn't the most experienced in mobile application development yet. The more advanced customization options given by other options aren't necessary either, so SwiftUI is enough for our needs.

Android:

We have chosen to use Java/Kotlin for our Android framework with android native UI components. Our team's familiarity with Java was a good reason to pick this framework as it would lessen the difficulty in figuring out how to use the language. Allowing us to put more effort in creating a more efficient app with a better user experience. Kotlin is specifically designed for android native apps which matches our previous requirements as well.

Consequences

Pros:

- The use of platform-specific UI components creates a familiar environment for users of each platform, making the end users' experience much better.

- After familiarizing ourselves with each framework, the development time long term should decrease as these frameworks allow for more efficiency

Cons:

- The initial learning curve will be steep, as we would need to create two native apps instead of a single cross-platform app. Each with their own language syntax and such.

- We would still need to maintain two different apps after completion of each app, resulting in possibly more work or resources.