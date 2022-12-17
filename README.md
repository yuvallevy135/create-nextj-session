# create-nextj-session

Next.js for Beginners: Create a Blog Website
Next.js is a powerful JavaScript framework for building server-rendered and statically-exported applications.
It is especially useful for creating blogs and other content-heavy websites, as it allows you to easily create pages and posts using Markdown files.

Installation and Setup
To use Next.js, you will need to have [Node.js](https://nodejs.org/en/) installed on your machine.

Open a terminal and install homebrew:
```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

After that install git:
```brew install git```

Please create a github account from:
[GitHub](https://github.com/)

Please download VS-Code from:
[VS-Code](https://code.visualstudio.com/download)

Please follow this youtube video to add ssh key to github account:
```https://www.youtube.com/watch?v=nZYJKXXMvkM```

You now can create a new Next.js project using the following command:
```npx create-next-app my-blog```
This will create a new directory called my-blog that contains all the files you need to start building your website.

Project Structure
Next.js uses the following directory structure for your project:

pages: This directory contains the pages and routes of your website. Each file in this directory represents a route, and the filename determines the URL of the route. For example, a file named about.js will be available at /about.
public: This directory contains any static files that you want to serve, such as images, fonts, and stylesheets.
components: This directory contains React components that you can use to build your pages and layout.
Creating a Blog
To create a basic blog with Next.js, you will need to follow these steps:

Create a posts directory inside the pages directory. This is where your blog posts will be stored.
Inside the posts directory, create a file for each of your blog posts. The filename should be the slug of the post (e.g. my-first-post.md) and the file should contain the content of your post in Markdown format.
Create a [slug].js file inside the posts directory to represent each of your blog posts. This file should export a React component that renders the content of the corresponding Markdown file.
In the pages directory, create a posts.js file that exports a React component that fetches and renders a list of your blog posts.
In the pages directory, create an index.js file that exports a React component that renders a list of links to your blog posts.
