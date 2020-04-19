# Laravel Challenge - 2FA Demo
A laravel app to demonstrate the functionality of [boxed-code/laravel-challenge](https://github.com/boxed-code/laravel-challenge).
## Getting Started
- Clone or download the zipball of this repository
- Install with `composer install`
- Setup your mail configuration in the `.env.` file
- Create a user using `./artisan tinker` and then `User::create(['name' => 'User', 'email' => 'email@address.com', 'password' => Hash::make('password')])`
- Login an enrol yourself to the default 'email' verification method at `http://localhost/tfa/email/enrol`
- Logout and the back in again to be challenged for 2FA via e-mail.
## License
MIT