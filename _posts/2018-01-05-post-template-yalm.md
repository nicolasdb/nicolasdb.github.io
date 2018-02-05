---
date: 2018/01/05
title: "Template for my posts"
excerpt: "I begin to find my way into this jekyll thing, here is the template I'm working on"
header:
  # image:
  teaser: "/assets/images/post/laser-th.jpg"
  # og_image:
categories:
  - Post
tags:
  - Openfab
  - github
  - superUser
  - loop
  - PBL
---

That's cool, for my 8th posts here (not counting pages or quests) I'll just share some knowledge I gather about a template I feel comfortable using for editing posts.

## Here it is:

On top of the post, this is the YAML section who say specific data to help jekyll to display your post.
```
---
date: 2018/01/05                      # YYYY/MM/DD, nothing special
title: "Template for my posts"        # will show on list and on top of your post.
excerpt: "I blabla bla ...."          # will show on list as a resume
categories:                           # List here the category of this post
  - Post                              # default, Post, Tuto, ....
tags:                                 # List here tags
  - Openfab
  - github
  - superUser
---
```
I use tags to list some posts together. Again, nothing new.

Then I use something like that as a base structure. The 3 base elements like in issues.
Always start with a bit of context, then explain what is your objectives and how you'll target them. 1.Why? 2.What? 3.How?
```
### Contexte
## Objectif(s)
## Propositions
```


And as always, you can help me and [contribute on this one here](https://github.com/nicolasdb/nicolasdb.github.io/blob/master/_posts/2018-01-05-post-template-yalm.md)  
