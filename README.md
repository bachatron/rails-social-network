# Social Network

Fullstack social media application built with Ruby on Rails.

This project implements core social platform features such as user authentication, posts, interactions and social relationships while focusing on backend architecture and database-driven functionality.

## Features

- User authentication
- User profiles
- Create and manage posts
- Like and interact with content
- Friend / follow system
- Dynamic feed functionality
- Database persistence with PostgreSQL
- Form validation and error handling

## Tech Stack

- Ruby
- Ruby on Rails
- PostgreSQL
- HTML
- CSS
- JavaScript

## Installation

Clone the repository:

```bash
git clone https://github.com/bachatron/social-network.git
cd social-network
```

Install dependencies:

```bash
bundle install
```

Setup the database:

```bash
rails db:create
rails db:migrate
rails db:seed
```

Start the Rails server:

```bash
rails server
```

## Environment Variables

Create a `.env` file if required:

```env
DATABASE_URL=
SECRET_KEY_BASE=
```

## Application Structure

The application follows a traditional Rails MVC architecture with:

- Authentication system
- Relational database models
- Server-side rendering
- RESTful routing
- User relationship management

## Future Improvements

- Real-time notifications
- Chat system
- Image uploads
- Better responsive design
- API version
- Docker support

## Author

Bachatron
