<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> Our philosophy is to empower customers with innovative tools to find and design the perfect shelving solutions for their spaces. By leveraging AI-driven recommendations, 3D planners, and customization options, we aim to make the shopping experience seamless, engaging, and tailored to individual needs.
>
>We believe great shelving transforms spaces, and our mission is to make that transformation simple and accessible for everyone.

### User Stories
- As a user, I want to browse a wide selection of shelves, so I can find one that fits my needs and preferences.
- As a user, I want to view detailed information about each shelf, including dimensions, materials, and load capacity, so I can make an informed decision.
- As a user, I want to use a 3D planner to visualize the shelves in my space, so I can see how they will look before purchasing
- As a user, I want to receive personalized shelf recommendations based on my preferences and browsing history, so I can quickly discover products that suit my needs.
- As a user, I want to add shelves to my cart and securely pay for my order online, so I can complete my purchase without hassle.
- As a user, I want to track the delivery of my purchased shelves, so I know when to expect them.
- As a user, I want to read reviews from other customers, so I can trust the quality of the product before buying.
- As a user, I want to manage my account details and view my order history, so I can keep track of past purchases and re-order easily.

### Admin Stories
- As an admin, I want to add, update, or remove shelf products, so I can keep the product catalog up-to-date.
- As an admin, I want to manage inventory levels, so I can ensure products are always in stock and visible to customers.
- As an admin, I want to view and manage customer orders, so I can ensure timely processing and delivery.
- As an admin, I want to view, edit, or deactivate user accounts, so I can handle customer issues and maintain platform integrity.
- As an admin, I want to access detailed sales and user analytics, so I can make informed business decisions.
- As an admin, I want to moderate customer reviews, so I can ensure only appropriate and constructive feedback is displayed.
- As an admin, I want to access customer queries and respond to support tickets, so I can assist users effectively.

<br><br>
<!-- Tech stack -->
<img src="./readme/title3.svg"/>

###  Shelf Master is built using the following technologies:

- This project uses the [Flutter app development framework](https://flutter.dev/). Flutter is a cross-platform hybrid app development platform which allows us to use a single codebase for apps on mobile, desktop, and the web.
- For persistent storage (database), the app uses the [Hive](https://hivedb.dev/) package which allows the app to create a custom storage schema and save it to a local database.
- To send local push notifications, the app uses the [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications) package which supports Android, iOS, and macOS.
  - 🚨 Currently, notifications aren't working on macOS. This is a known issue that we are working to resolve!
- The app uses the font ["Work Sans"](https://fonts.google.com/specimen/Work+Sans) as its main font, and the design of the app adheres to the material design guidelines.

<br><br>
<!-- UI UX -->
<img src="./readme/title4.svg"/>


> We designed Shelf Master using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/RaPx3W2H4clVwELt8NcfVk/Final-Project?node-id=0-1&node-type=canvas&t=vy9IcsK5jJ0Y8OcS-0)


### Mockups
| Home screen  | Menu Screen | Order Screen |
| ---| ---| ---|
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

###  Architecting Data Excellence: Innovative Database Design Strategies:

- Insert ER Diagram here


<br><br>


<!-- Implementation -->
<img src="./readme/title6.svg"/>


### User Screens (Mobile)
| Login screen  | Register screen | Landing screen | Loading screen |
| ---| ---| ---| ---|
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |
| Home screen  | Menu Screen | Order Screen | Checkout Screen |
| ![Landing](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) | ![fsdaf](https://placehold.co/900x1600) |

### Admin Screens (Web)
| Login screen  | Register screen |  Landing screen |
| ---| ---| ---|
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |
| Home screen  | Menu Screen | Order Screen |
| ![Landing](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) | ![fsdaf](./readme/demo/1440x1024.png) |

<br><br>


<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

###  Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project uses advanced prompt engineering techniques to optimize the interaction with natural language processing models. By skillfully crafting input instructions, we tailor the behavior of the models to achieve precise and efficient language understanding and generation for various tasks and preferences.

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

###  Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

###  Precision in Development: Harnessing the Power of Unit Testing:

- This project employs rigorous unit testing methodologies to ensure the reliability and accuracy of code components. By systematically evaluating individual units of the software, we guarantee a robust foundation, identifying and addressing potential issues early in the development process.

<br><br>


<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up Coffee Express locally, follow these steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [example](https://example.com)
2. Clone the repo
   git clone [github](https://github.com/your_username_/Project-Name.git)
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

Now, you should be able to run Coffee Express locally and explore its features.