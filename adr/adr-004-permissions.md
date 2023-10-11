ADR: How Permissions are Handled

Status

Proposed

Context

The app, as mentioned in all the other ADR's features shopping, order tracking, loyalty programs, and push notifications, all of which require various device permissions. Our goal is to figure out how to get, and manage,  these permissions responsibly and efficiently.

Decision

- Location Permissions: We will request location permissions when necessary, to be more specific, it's when users require delivery tracking, or maybe even store locator services. We will request these permissions only when needed, this is to build trust with the user as well as respect their privacy.

- Camera and Photos Permissions: As for the camera and photos access, these will be requested when users need to scan products or upload images. Again, we will prompt for these permissions at the moment they are required, to again, build trust with the user as well as respect their privacy.

- Notification Permissions: For notifications, we will request notification permissions. Users will be prompted to allow or deny notifications when they open the app for the first time, or when they first encounter a scenario where notifications are relevant.

- Internet Access: Internet access permissions are a default requirement for our app to connect to the server. We won't explicitly ask for internet access, there doesn't seem to be a reason to, this is already standard for most mobile applications in the market already.

Consequences

Pros:

- Requesting permissions with context and only when they are needed increases user trust, thus enhancing user experience as well

- With permission requests only activating whilst using a specific feature, users aren't bombarded with a bunch of permission requests when first opening the app

Cons:

- We must be careful in how we use the permissions, misuse of these permissions without explicitly stating it may result in a bad consequences

- Some features may not be usable without the permissions, resulting in poorer user experience, we must take that into account