UPDATED STOREFRONT PROJECT

Files to upload to your GitHub Pages repository:
- storefront.html
- signup.html
- style.css
- MCD.jpg
- GYM.jpeg
- VID.jpg

What was updated:
1. Added a responsive navigation link to the new user Sign Up page.
2. Added Email, Username, Confirm Username, Password, and Confirm Password fields.
3. Added JavaScript validation for required fields, email format, matching usernames, and matching passwords.
4. When the form is valid and Sign Up is clicked, all field values are collected into a JavaScript object.
5. The object is displayed on the page as formatted JSON using JSON.stringify(..., null, 2).
6. The form does not reload the page when submitted.
7. Added a Clear button to reset the form and JSON output.

GitHub Pages reminder:
- Keep all of these files in the same folder/repository level so the links and images work.
- If GitHub Pages expects index.html as the landing page, either rename storefront.html to index.html and update links, or keep storefront.html and submit its full URL.
- Test Home -> Sign Up, form validation, JSON output, and images before submitting the URL.

Security note:
The assignment mockup shows password values in JSON. This project follows that requirement for a classroom demo only. Real websites should never display or store plain-text passwords.
