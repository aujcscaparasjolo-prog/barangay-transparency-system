
## Proper portal update

The project now has separate citizen and admin flows. Citizens can submit and track their own requests, view public updates, and change their password in Settings. Admins have a separate portal with request controls, update publishing, admin password settings, and User management.

User management supports adding, editing, filtering, and deleting accounts. The currently logged-in admin cannot delete itself.

This remains a browser-only prototype using `localStorage`. Do not use it for real personal information or production authentication until a secure server/database, password hashing, email verification, role authorization, and audit logs are implemented.
