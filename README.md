# Two-Factor Auth via Email

Simple demo-project to add two-factor authentication, with sending 6-digit unique verification code via email.

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there, also email provider settings (to send verification codes)
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to adminpanel with default credentials __admin@admin.com__ - __password__

## License

Basically, feel free to use and re-use any way you want.