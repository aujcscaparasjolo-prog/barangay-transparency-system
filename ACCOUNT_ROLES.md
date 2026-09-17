
## Account roles and settings

The prototype now supports two account types during sign-up:

- **Barangay Citizen**: opens the resident portal for document requests and public updates.
- **Barangay Admin**: opens `admin.html` for request management and publishing updates.

Accounts are stored in browser `localStorage` for this prototype. The same email cannot register twice. Users can change their password from Settings in the resident portal; admin users can change it from the admin settings section when added to the production backend.

Default demo admin:

- Email: `admin@barangay.ph`
- Password: `admin123`

For a real deployment, use a server database, hashed passwords, email verification, role permissions, and server-side authentication. Browser localStorage is not secure enough for permanent production accounts.
