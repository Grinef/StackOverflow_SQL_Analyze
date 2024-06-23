# StackOverflow Data Analysis Project

## Project Overview

The goal of this project is to analyze the StackOverflow database, focusing on posts, users, badges, and votes. The database contains information about posts created in 2008, including details about user interactions and post evaluations made later. The project consists of two parts: solving SQL tasks in an SQL trainer and writing SQL queries in Jupyter Notebook using SQLAlchemy.

## Database Schema

### Table Descriptions

#### badges

Contains information about badges awarded for various achievements.

- **Fields**: id, name, user_id, creation_date

#### post_types

Contains information about the types of posts (Question or Answer).

- **Fields**: id, type

#### posts

Contains information about posts.

- **Fields**: id, title, creation_date, favorites_count, last_activity_date, last_edit_date, user_id, parent_id, post_type_id, score, views_count

#### users

Contains information about users.

- **Fields**: id, creation_date, display_name, last_access_date, location, reputation, views

#### vote_types

Contains information about types of votes.

- **Fields**: id, name

#### votes

Contains information about votes on posts.

- **Fields**: id, post_id, user_id, bounty_amount, vote_type_id, creation_date
