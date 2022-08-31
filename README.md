# Technical InApp Test
This is a Technical Test for InApps. The codebase is in Typescript, if you prefer realize it in Javascript, [consider this test instead](https://github.com/360medics/inapp-technical-test-javascript).

This project has been built with [Vue.js 3](https://vuejs.org/). It uses [Vuex](https://vuex.vuejs.org/en/index.html) for state management and [Vue Router](https://router.vuejs.org/) for routing. We also added [Font Awesome](https://fontawesome.com/) icons.

# Getting Started
## Requirements
- [Node.js](https://nodejs.org/en/)
- [Git](https://git-scm.com/)

## Clone the repo
You have to clone this repo localy and set remote url origin to a new repo from your account. 
```
git clone git@github.com:360medics/inapp-technical-test-typescript.git
````
then create a new repo from your github account

![alt text](https://doc.360medics.com/assets/clients/charles/gh1.png)
![alt text](https://doc.360medics.com/assets/clients/charles/gh2.png)

then set new url origin
```
git remote set-url origin git@github.com:<user_account>/<repo_name>.git
```
and finally push master
```
git push
```

## Install Dependencies
Run the following command in your terminal:
```
npm install
```

## Compiles and hot-reloads for development
```
npm run serve
```

## Lints and fixes files
```
npm run lint
```

# Development Workflow
You are free to use any workflow you like. We recommend using [Git](https://git-scm.com/) for version control and [VSCode](https://code.visualstudio.com/) for code editing.

# Guidelines
The application is designed to be run on mobile devices. It is not designed to be run on a desktop.

# Features Requirements
There are two main features to implement and a bonus feature.
## See a list of Blog articles
As a user, I want to be able to read blog articles. I want to access the blog articles list page from the home page. I want to see a short preview of each articles.

Articles can be fetched from an API or whatever source you want. Here is an example of a blog article:

```
{
  "id": "1",
  "title": "Article 1",
  "content": "This is the content of the article 1",
  "author": "John Doe",
  "imageUrl": "https://via.placeholder.com/150",
  "date": "2018-01-01"
}
```
> **Note:** We do not ask you to create an API from the ground up (but you can!). You can use an API that already exists. For example:
* https://jsonplaceholder.typicode.com/posts, for content
* https://jsonplaceholder.typicode.com/photos, for article image preview (you could map `post.id` to `photo.albumId`)

## See a full article (details)
As a user, I want to access the article details page from the blog articles list page and be able to read the full article content.

I should be able to navigate back to the blog articles list page from the article details page.

## Bonus: Liked articles
As a user, I want to be able to mark an article as liked. I want to be able to see a list of liked articles from the home page only if there are liked articles.

# Support
You can ask for help in cases you are stuck or have a question.
You can join 360 tech team [here](mailto:tech@360medics.com)
