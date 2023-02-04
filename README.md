# RemixJokes

## Intro

I'm using this repo to learn the rising in popularity React framework, Remix.  

I really like that it prioritizes server-side-rendering, supports traditional forms, and, has great performance everywhere.

## Getting Started

First, clone the repo from the command line:

    git clone https://github.com/Nyumat/RemixJokes.git

Now that you haved checked out the repo locally, start in creating an .env file by running `touch .env` in the root dir.

After this, open the .env file you just created in a text editor and format it like so:

```DATABASE_URL="file:./dev.db"```

We're using SQLite & Prisma, so be sure to run: 
<br>
 `npm install` <br>
 `npx prisma init --datasource-provider sqlite`
 <br> 
 `npx prisma db push`
 <br>

to install the dependency, initalize prisma, create the DB in the file prisma/dev.db, and, push the changes in the DB to match our schema.





