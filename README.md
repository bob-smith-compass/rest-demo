# rest-demo

Based on Medium article `how to wrap the REST API` it contains with GraphQL [here](https://medium.com/@graphcool/how-to-wrap-a-rest-api-with-graphql-8bf3fb17547d).

> The GraphQL API wrapping this REST API can be found [here](https://github.com/nikolasburk/graphql-rest-wrapper)

## Routes

```
/users
/users/<id>
/users/<id>/posts
/posts
/posts/<id>
/posts/<id>/user
```

To see the data returned by the routes, check [users.json](./data/users.json) and [posts.json](/data/posts.json).

## Run

yarn start

Sample requests:

- http://localhost:3000/users
- http://localhost:3000/posts
- http://localhost:3000/users/user-1
- http://localhost:3000/users/user-1/posts
- http://localhost:3000/posts/post-4
- http://localhost:3000/posts/post-4/user

## Demo


Sample requests:

- https://rest-demo-hyxkwbnhaz.now.sh/users
- https://rest-demo-hyxkwbnhaz.now.sh/posts
- https://rest-demo-hyxkwbnhaz.now.sh/users/user-1
- https://rest-demo-hyxkwbnhaz.now.sh/users/user-1/posts
- https://rest-demo-hyxkwbnhaz.now.sh/posts/post-4
- https://rest-demo-hyxkwbnhaz.now.sh/posts/post-4/user
