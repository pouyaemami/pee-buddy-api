# PeeBuddy

## Database

**Type:** PostgreSQL

### Schema

**users**
- id
- first_name
- last_name
- email
- profile_image

**user_friends**
- user_id
- friend_id
- blocked
- pending

**devices**
- device_id
- user_id

**messages**
- id
- content
- timestamp

**user_messages**
- message_id
- user_id
- read
