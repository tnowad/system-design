# Comic website schema

## Entities

* User
* Comic
* Chapter
* Role
* Permission
* Author
* Category
* Rating

## Features

* Users with a normal role can:
    * Register
    * Login
    * Change user information
    * View comics
    * View history
    * Follow comics
    * Rate comics
    * Level up
    * Publish comics if they have permission to do so.
* Users with a moderator role can:
    * Do something if they have been granted permission.
* Users with an admin role can:
    * Do everything that users with a normal or moderator role can do, and also:
      * Manage users
      * Manage comics
      * Manage chapters
* Users with a super admin role can:
    * Do everything that users with a normal, moderator, or admin role can do, and also:
      * Manage roles

## Relationships

* A comic has many chapters.
* Each chapter has many comments.