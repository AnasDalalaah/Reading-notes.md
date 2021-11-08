# GraphQL @connection

## API (GRAPHQL)
### Overview
The GraphQL Transform provides a simple to use abstraction that helps you quickly create backends for your web and mobile applications on AWS. 
With the GraphQL Transform, you define your application's data model using the GraphQL Schema Definition Language (SDL)
and the library handles converting your SDL definition into a set of fully descriptive AWS CloudFormation templates that implement your data model.

For example you might create the backend for a blog like this:
```
type Blog @model {
  id: ID!
  name: String!
  posts: [Post] @connection(name: "BlogPosts")
}
type Post @model {
  id: ID!
  title: String!
  blog: Blog @connection(name: "BlogPosts")
  comments: [Comment] @connection(name: "PostComments")
}
type Comment @model {
  id: ID!
  content: String
  post: Post @connection(name: "PostComments")
}

```
### Directives
The Amplify CLI provides GraphQL directives to enhance your schema with additional capabilities such as custom indexes,
authorization rules, function triggers, and more.

