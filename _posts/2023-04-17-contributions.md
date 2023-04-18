---
layout: post
title:  "Contributions"
author: damienaicheh
categories: [ tutorial ]
tags: [starter]
excerpt: "This will give you all the rules to contribute to this website"
featured: true
hidden: true
---

### How to use?

As usual, just fork the repository and create your own branch.

### Add your self as contributor

Inside the `_config.yml` file add your self as an author. Keep the alias for the next step.

```yml
  youralias:
    display_name: # Your Name
    gravatar: # gravatar id if you have one
    avatar: 'assets/images/your_path.png' # add your profil picture if you don't have a gravatar id
    web: # Optional
    twitter: https://twitter.com/your-id # Optional
    description: # Short description
```

### Create a new document

In the `_posts` folder add a new file to present your contribution. The naming convention must be:
`yyyy-mm-dd-a-title.md`

Inside it copy past the template below so you can fill it with the right informations:

```yml
---
layout: post
title: # your title (Required)
author: # your alias (Required)
categories: [ Tutorial ] # Based on the list provided below (Required)
tags: [tutorial] # Based on the list provided below (Required)
excerpt: # Short description (Required)
github: https://github.com/ # (Optional) External repository if needed
beforetoc: # (Optional) Short description before the table of content
toc: true # (Optional) Display a Table of Contents at the begining of the post
---
``` 

### List of tags and categories

To keep everything consistent and easy to find please follow the list of tags and list below. If you don't find one that fit your needs, add it in this file in **alphabetical order**.

#### Categories

`cloud-native`, `containers`, `demo`, `devops`, `tutorial`

#### Tags

`apim`, `app-service`, `azure-devops`, `bicep`, `function`, `github-actions`, `github`, `starter`, `terraform`

### Infrastructure As Code

#### Naming convention

When adding your samples of infrastructure as code please make sure to follow the official [naming convention](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/). This is **very important** to give good naming samples during a customer demo.

#### Add your code

You have two posibilities:
- Add your IaC in this repository inside a folder with the **snakecase** naming convention.
- Provide a link to an external repository using the `github` attibute in the post description like you saw previously.

### Provide your changes by Pull Request

When create or updating content just create a PR and fill the template provided so reviewers can quickly understand what you are adding.
