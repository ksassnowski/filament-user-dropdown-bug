# User Dropdown Bug Reproduction

The repository contains a `database.sqlite` file that's already seeded with an example user. So there is no need to set up a database or run the migration manually.

1. Serve the page `php artisan serve`
2. Navigate to `http://localhost:8000/admin`
3. Use credentials `test@example.com` / `password`

After logging in, you will notice that the user dropdown is already visible. Clicking on the user's avatar positions the dropdown correctly, but you will still be unable to close it.
