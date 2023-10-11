ADR: App Type Selection

Status: 

Proposed?

Context:

Our team had to make a new mobile app for a retail company with features like browsing and purchasing products, viewing order history, as well as tracking the status of their deliveries. The retail company had quite a few requirements like supporting offline mode, push notifications, and ideas for international expansion. Given all these requirements, app type was a heavy influencer on what can or can't be done in an effective manner.

Decision:

We have decided to create a native mobile app for this project. The main reasons being as follows:

- Better User Experience: Native apps provide a better user experience with the use of platform-specific UI components, which results in a more responsive and intuitive interface. While not explicitly stated or wanted from the company, a better UI/UX draws more customers in, as well as makes them want to use the app longer, indirectly relating to the companies end goals (to make more money). No one wants to use something with terrible UI/UX.

- Access to Device Features: Functions like location-based service, tracking deliveries, etc,  which are wanted from the company, need access to device features like the camera, or gps. Creating a native app allows us to access the full feature set a device has to offer.

- Offline Mode Support: A key requirement of the project is to support offline mode, allowing customers to browse products and view order history even when not connected to the internet (obviously). Native apps are suited to provide a smoother offline experience, synchronizing data with the server when connectivity is restored.

- Push Notifications: Native apps can use platform-specific push notification services, like APNS (Apple Push Notification Service) for iOS, and FCM (firebase cloud messaging) for Android. Allowing for a more efficient, reliable delivery of notifications, which is needed for features like order updates, arrival for new products, and offers/deals.

- Performance and Responsiveness: Native apps are well known for their high performance and responsiveness. Which is important especially when browsing a bunch of product images and completing transactions.

Consequences:

Easier:

 - A higher quality user experience with platform specific UI components.

 - Functionalities previously mentioned are able to be done with access to the full device feature set. (location based stuff) 

 - Offline mode and push notifications are features the retail company wants.

More Difficult:

- More development effort is required since there are 2 separate platforms (ios and android). This also results in more maintenance management as well.

- Harder to learn as compared to a web app or hybrid app.