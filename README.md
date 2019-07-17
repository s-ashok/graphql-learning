# graphql-learning
GraphQL learning examples

# Snowtooth API - Lab

In this activity, you'll create an API for Snowtooth Mountain, a fake ski resort.

## Setup

1. In your Terminal or Command Prompt, Download or Clone this Repository: `git clone https://github.com/graphqlworkshop/snowtooth-api`
2. Change directory: `cd snowtooth-api`
3. Install dependencies: `npm install`
4. Start the Server: `npm start`
5. Open the browser to: `http://localhost:4000`


gql takes a string returns schema object
every field in GraphQL maps to a function
default graphql runs on port 4000
Get request to 4000 returns Apollo playground
Apollo wraps the express server, there is package(find out) to customize the express server
Cannot specify fetch all like select * in GraphQL which is by design
liftCount(status: LiftStatus) --> means status is optional

parent for lift count --> is Query
args --> all of the arguments

####links
https://www.apollographql.com/docs/tutorial/schema/
https://graphql.org/code/#java
https://jacobwgillespie.com/from-rest-to-graphql-b4e95e94c26b
https://github.com/moonhighway/oscon


https://pet-library.moonhighway.com
http://vote.moonhighway.com
http://snowtooth.moonhighway.com

