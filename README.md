
# Lightbulb

Lightbulb will be an app/program that encourages open forum discussion between users. Users being commenters and creators of original posts. The website will be primarily oriented towards individuals trying to crowdsource entrepreneurial ideas. The ideas can vary in range from simple questions on how or where to start, to more specific and niche questions pertaining to very specific problems. The site will hold an open forum system that is thread based. Where users can comment on each other's comments and rank their responses. Rather than creating categories directed at specific topics, the posts will be sorted through keywords tags that the post creator will tag to the original post.

## Team Roster

* **Jonathan Padilla** 
* **Steven Zuniga** 
* **Jamie Smith** 
* **Richmond Baafi** 

## Intended Users

- People trying to crowdsource ideas, gather information, or find ways of improvement for their project(s).
- Commenters who would like to share their knowledge and information that they have gathered through personal experience.
- Passive users browsing the site for ideas as well, but due to the open nature of the site direct interaction won't be necessary with the correct query and sufficient information established.

### [User Stories](user-stories.md)



## Entity Classes and ERD
### [Keyword](https://github.com/team-lightbulb/server/blob/master/src/main/java/edu/cnm/deepdive/lightbulb/model/entity/Keyword.java)
### [Comment](https://github.com/team-lightbulb/server/blob/master/src/main/java/edu/cnm/deepdive/lightbulb/model/entity/Comment.java)
### [User](https://github.com/team-lightbulb/server/blob/master/src/main/java/edu/cnm/deepdive/lightbulb/model/entity/User.java)
### [Entity-Relationship-Diagram](erd.md)
### [DDL](https://github.com/team-lightbulb/server/blob/master/create.sql)



## External Services

- A database that can hold the posted messages and comments, that way they can be accessed by anyone and at any time.
- Google authentication sign in for account verification.
- Calendar to log the post dates.
