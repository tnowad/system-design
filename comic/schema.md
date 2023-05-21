# Comic Website Database Design

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

## Relationships

- User-Comic (Many-to-Many)
- Comic-Chapter (One-to-Many)
- Chapter-Comment (One-to-Many)
- Comic-Category (Many-to-Many)
- Comic-Genre (Many-to-Many)
- User-Report (One-to-Many)

## Storage

### SQL Database:

- User
- Comic
- Chapter
- Role
- Permission
- Author
- Category
- Rating
- Genre

### NoSQL Database:

- Chapter and Mirror Link Image
- List of Viewed Chapters
- Comment in Chapter
