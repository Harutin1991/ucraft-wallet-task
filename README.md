
## About Project
To DO

### To get the project up and running:

2. Run `sail up` to start the containers. `sail up -d` will start the containers in the background and is generally more convenient.
3. Run `sail composer install` to install PHP dependencies.
4. Run `sail artisan migrate:fresh --seed` to prepare the database.
5. Run `sail artisan storage:link` to prepare file system for serving public images.
6. Run `sail npm i` to install node dependencies.
7. Run `sail npm run dev` to start asset compilation and HMR, or `sail npm run prod` to simply compile assets.
9. Website will be available at `http://localhost:38000` and will have HMR / auto-reload, if `npm run dev` is running. Otherwise, there will be no auto-reload.
10. Press `ctrl+c` or run `sail stop` to stop the containers.

### Day-to-day usage

`sail up -d` and `sail npm run dev` is usually enough to start working when the project has been set up already.


## Integrations

#### Livewire
#### Filement ( partial )
#### Mail
#### Google Login
#### Facebook Login


## Random notes

Used Github Repo: https://github.com/bavix/laravel-wallet

https://filamentphp.com/plugins/spatie-activity-log

https://github.com/ryangjchandler/filament-tools

https://filamentphp.com/plugins/spatie-health

https://laravel-livewire.com/

### Onboarding

Email verified: yes / no
