# Portfolio

Portfolio and blog site to share knowledge and showcase projects.

### Plan

1. Qs
  - What are we building?
  - Who are we building it for?
  - What features do we need to have?
2. User Stories
3. Model our data
4. Think through pages required

### Qs

1. A personal site where I can blog and share projects I am working on with others and have others contact me
2. The site is being built for me with the view to show employers the skills I have and share any interesting knowledge with others
3. - Posts
      - CRUD
      - Markdown
      - Syntax highlighting
      - Comments
   - Projects
      - CRUD
   - Contact
      - Contact form
      - Functionality to send emails via form
   - Users


### User Stories

As a user,
So I can post on my blog,
I would like to be able to create posts

As a user,
So I can maintain my blog,
I would like to be able to edit/delete posts

As a user,
So I can keep things interesting,
I would like to be able to add images to posts

As a user,
So I can format posts easily,
I would like to be able to use markdown formatting

As a user,
So I can share examples of my work with others,
I would like to be able to add projects as I work on them

As a user,
So others can contact me directly,
I would like to have a contact form on my site

As a user,
So I can get feedback from others,
I would like people to have the ability to comment on my posts

### Model data

  **Post**
    title:string
    content:text

  **Project**
    title:string
    description:text
    link:string

  **User**
    Devise

### Pages

  - Homepage
  - Posts#index
  - Posts#show
  - Projects#index
  - Projects#Show
  - Contact
