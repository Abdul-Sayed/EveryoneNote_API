# lazy_Chef_API

Back End for [EveryoneNote](https://github.com/Abdul-Sayed/EveryoneNote)

[Live Demo](https://everyonenote.surge.sh/)

<img src="https://i.ibb.co/fFZcsKb/evernote.png" alt="evernote" border="0">

## Technologies/Frameworks used

Built with Ruby on Rails

- Ruby 2.6.1
- Rails 6.0.1

Features the ActiveRecord models user:`has_many :notes` and note: `belongs_to :user`.

Utilizes the bcrypt and JWT gems for Authentication/Authorization. Saves to a PostgreSQL database.

### Getting Started

#### Installing

Clone down the repo

`bundle install`

#### Deployed App

Backend deployed on [Heroku](heroku.com)
Frontend deployed on [Surge](https://everyonenote.surge.sh/)

### Authors

[Abdul Sayed](https://www.linkedin.com/in/abdul-sayed-engr/)
