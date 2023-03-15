# infinite-scroll-pseudo-blog
Display blog posts from [jsonplaceholder](https://jsonplaceholder.typicode.com) and add infinite scroll to fetch posts and also add filter box

## Description 

This App fetches posts from an API and displays them on a webpage. It also includes functionality for filtering posts based on user input.

The code starts by defining some variables and constants, such as the posts container, loading spinner, and filter input.
It defines a function called `getPosts` that fetches data from the API and returns it as JSON.
It defines a function called `showPosts` that calls getPosts and then creates HTML elements to display the posts on the page.
It defines a function called `showLoading` that shows a loading spinner, waits for a brief moment, then removes the spinner and calls `showPosts` again to fetch and display more posts.
It defines a function called `filterPosts` that takes user input and filters the displayed posts based on the title and body of each post.
It calls `showPosts` to initially display the posts on the page.
It adds an event listener to the window that listens for scrolling and calls `showLoading` when the user scrolls to the bottom of the page.
It adds an event listener to the filter input that listens for user input and calls `filterPosts` to filter the displayed posts based on the input.

Overall, this sets up a dynamic webpage that fetches and displays posts from an API and allows the user to filter the posts based on their content.

## Project Specifications

- Create UI & custom CSS loader animation
- Fetch initial posts from API and display
- Scroll down, show loader and fetch next set of posts
- Add filtering for fetched posts

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
## Technologies Used
![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
