# User Dropdown Bug Reproduction

For convenciences sake, the database and `.env` file have been checked into the repository. There is no need to copy over the `.env.example`, run the migrations or generating an app key.

1. Install dependencies `composer install`
1. Serve the page `php artisan serve`
2. Navigate to [`http://localhost:8000/admin`](http://localhost:8000/admin)
3. Use credentials `test@example.com` / `password`

After logging in, you will notice that the user dropdown is already visible. Clicking on the user's avatar positions the dropdown correctly, but you will still be unable to close it.
