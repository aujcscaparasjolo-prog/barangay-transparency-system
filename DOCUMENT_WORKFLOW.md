
## Latest UI and document workflow

- `admin.html`: polished barangay staff dashboard with Overview, Requests, Documents, Residents, and Settings tabs.
- `citizen.html`: formal resident document center with request history and downloadable certificates.
- Admins can upload PDF, DOC/DOCX, JPG, JPEG, or PNG files against a request ID. The resident can download them from `citizen.html`.

Run with `python3 -m http.server 5500`, then open `/admin.html` or `/citizen.html`.

The upload/download flow is a browser prototype using localStorage and data URLs. It is not a secure real file server; production deployment needs a backend, access control, database, encrypted storage, and server-side file validation.
