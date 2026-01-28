Instagram Database Clone (SQL)

A relational database clone of core Instagram features using MySQL, including a schema and a set of analysis queries. It's just a small showcase of some SQL skills.

Database Schema:
- **users** (accounts)
- **photos** (posts)
- **comments** (photo comments)
- **likes** (many-to-many: users ↔ photos)
- **follows** (many-to-many: users ↔ users)
- **tags** + **photo_tags** (hashtags, many-to-many: photos ↔ tags)

Analysis Queries
Practical queries for product/growth style questions:
- 5 oldest users (early adopters)
- Most popular registration day(s)
- Inactive users (no photos)
- Most liked photo + user who posted it
- Average photos per user
- Most used hashtags
- Users who liked **every** photo (potential bot behavior)
