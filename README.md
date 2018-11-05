# e-mart

![demo](https://thumbs.gfycat.com/ThoroughShabbyJunebug-size_restricted.gif)

e-mart is an open source full stack online mart complete with real credit checkout. Users can search, sell, add to cart and checkout their favourite grocery items.

This is a full stack JavaScript application built with React.js, GraphQL, Node.js and friends.

## The Tech Stack

![](docs/images/tech_stack.png)

## Application Architecture

The following is the design of the frontend and backend of the application.

The application has five main models:
— Users
- Items
- Orders
- CartItems
- OrderItems

all of which are relational and utilizing the power of relational GraphQL Queries.

The app also includes many server side bits including:
- JWT authentication
- permissions
- sending email
- uploading images
- charging credit cards

## Development

Developer skills required to build an online mart with React, GraphQL and some of today's top JavaScript technology.

### React.js and Modern JavaScript

You should be already familiar with the basics of React - components, state, props, modules and event handlers.

You should be comfortable with both writing and debugging modern JavaScript including arrow functions, classes, promises, async+await and other commonly used parts of ES6.

The backend of the app is written in Node.js. Prior Node.js knowledge is nice, but not required.

The app requires knowledge of GraphQL, Prisma, databases, or testing React components.

### What is GraphQL?

Just as React has transformed the way we build web applications, GraphQL is changing how we build APIs to query and mutate data.

<img src="docs/images/graphql_code_example.png" width="300" />

GraphQL is a type-safe query language for APIs and a runtime for fulfilling those queries with your existing data.

What?! It's a replacement for (_or addition to_) your REST API and Ajax Calls.

GraphQL requires buy-in from both your client and your server — it then puts the power of requesting **only what you want** into the client and the business logic of finding and filtering that data into **backend resolvers**.

Specifically in this course it enables libraries that make caching, loading, error handling and pagination a breeze.

Complex Relational Data queries and server-side mutations like signing up or checking-out are a snap with GraphQL.

GraphQL is just a standard and can be implemented in any language or framework.

### Concepts

The concepts implemented into our entire full-stack application along with general JavaScript best practices:

- React Best Practices
- Server Side Rendering
- Styled Components
- Theming
- React Render Props
- Routing
- GraphQL Schema
- Queries and Mutations
- JSON Web Token (JWT)
- Resolvers
- Cache Management
- Loading and Error States
- Sending Email
- Logic and Flow with Async + Await
- Authentication and Permissions
- Charging Credit Cards
- Hosting and Transforming Images
- Pagination
- Forms in React
- Animations
- Third party React Components
- Unit Testing
- Mocking Components
- Mounting vs Shallow Rendering
- Deployment

## License

This repository contains a variety of content; some developed by Cedric Chee, and some from third-parties. The third-party content is distributed under the license provided by those parties.

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer.*

The content developed by Cedric Chee is distributed under the following license:

### Code

The code in this repository, including all code samples in the notebooks listed above, is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

### Text

The text content of the book is released under the CC-BY-NC-ND license. Read more at [Creative Commons](https://creativecommons.org/licenses/by-nc-nd/3.0/us/legalcode).