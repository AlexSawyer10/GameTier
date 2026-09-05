# GameTier

GameTier is a full-stack web app for ranking video games.

Users sign in with Auth0, search games, open game details, and build ordered lists. They can slot games into ranked positions, like or dislike lists and comments, and browse public profiles plus top, worst, and searchable lists.

## Stack

- **Frontend:** Angular, Auth0 (OpenID profile and email)
- **Backend:** Express, TypeORM
- **Database:** MySQL
- **Game catalog:** RAWG API

The UI is deployed on Vercel. The API exposes routes for login, search, profiles, lists, and comments.
