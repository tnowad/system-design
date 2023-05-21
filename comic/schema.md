# Comic website schema

## Entities

- User
- Comic
- Chapter
- Comment
- Role
- Permission
- Author
- Category
- Rating
- Genre
- Subscription
- Favorite
- Report

## Features

- Users with a normal role can:

  - Register
  - Login
  - Change user information
  - View comics
  - View history
  - Follow comics
  - Rate comics
  - Level up
  - Publish comics if they have permission to do so.
  - Subscribe to receive notifications about new chapters of followed comics
  - Add comics to their favorites list
  - Report inappropriate content

- Users with a moderator role can:

  - Do something if they have been granted permission.
  - Review and moderate reported content

- Users with an admin role can:

  - Do everything that users with a normal or moderator role can do, and also:
    - Manage users
    - Manage comics
    - Manage chapters
    - Manage categories
    - Manage genres

- Users with a super admin role can:
  - Do everything that users with a normal, moderator, or admin role can do, and also:
    - Manage roles
    - Manage permissions

## Relationships

- A comic has many chapters.
- Each chapter has many comments.
- A comic can belong to multiple categories.
- A comic can have multiple genres.
- Users can subscribe to multiple comics.
- Users can have multiple comics in their favorites list.
- Users can report multiple comics, chapters, or comments.
