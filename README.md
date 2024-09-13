# tech-blog

## Table of Contents

<ol>
<li>
<a href="#description"> Description </a>
</li>
<li><a href="#installation"> Installation </a>
</li>
<li>
<a href="#executing-program"> Executing program </a>
</li>
<li><a href="#usage"> Usage </a>
</li>
<li><a href="#contribution"> Contribution </a>
</li>
<li>
<a href="#tests"> Tests </a>
</li>
<li>
<a href="#screenshot-and-video"> Screenshot and Video </a>
</li>
</ol>

## Description

A blog where a user can login logout. \
User can post, edit, or delete a post. And comment on other and their post.

## Installation

```
npm i
```

<ins>Dependencies used:</ins>

- bcrypt
- connect-session-sequelize
- dotenv
- express
- express-handlebars
- express-session
- handlebars
- pg
- sequelize

## Executing program

After installation
<br>

```
First..
psql -U postgres

input your password..
then
```

```
If you are not in db folder
\i db/schema.sql

If you are in db folder
\i schema.sql

After either of two above..
\q
to exit
```

```
Lastly...
npm run seed && npm run start
```

Run the local host

## Usage

User can create, update, delete post. \
User can comment on other posts and share thoughts.

## Contribution

Git clone or fork the repository and create a feature for me ❤️

## Tests

Try to create an account, login, and make a post. \
Also try to comment on existing posts.

## Screenshot and Video

The following video shows the application's appearance and functionality:\
Click on the image below for a video

[![Video of program](./assets/images/screen.png)](./assets/videos/e-commerce%20backend.mp4)
