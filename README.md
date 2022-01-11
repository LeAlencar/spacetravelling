# Spacetravelling

This is an application developed at RocketSeat Ignite Bootcamp. It's a blog using a Headless CMS (Prismic). You can check it live here: [SpaceTravelling](https://spacetravelling-2dt5zs9td-lealencar.vercel.app/)

Features:
* Get posts from Prismic CMS API
* List the blog posts with pagination
* On the post page, go to previous and next posts
* Add comment on post page using Utteranc

## 💻 Built With

* [React JS](https://reactjs.org/)
* [TypeScript](https://www.typescriptlang.org)
* [Next.js](https://nextjs.org/learn/basics/create-nextjs-app)
* [Prismic](https://prismic.io/docs)
* [Axios](https://github.com/axios/axios)
* [Date-FNS](https://date-fns.org/)
* [React Icons](https://react-icons.github.io/react-icons/)
* [SASS](https://sass-lang.com/)

## Getting Started

1. Get a free API Key to Primic CMS (check the list on .env.sample)
2. Create the file .env.local on your project and set all the API Keys based on src/services/prismic.ts
3. Clone the repo
   ```sh
   git clone https://github.com/LeAlencar/spacetravelling.git
   ```
4. Install packages
   ```sh
   yarn | npm install
   ```
5. Start the project on root file
   ```sh
   yarn | npm dev
   ```
