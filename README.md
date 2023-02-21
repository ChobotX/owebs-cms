## Development
### Before first run
* Add sail alias to your terminal
  * ``alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'``
* Install project dependencies and start up docker containers
  * ``composer install``
  * ``sail up -d``
  * ``sail yarn``
  * ``sail php artisan migrate``
### During development
* Start development server
  * ``sail yarn dev``
* Run static analysis
  * ``sail yarn stan``
* Run linter
    * ``sail yarn lint``
* Run linter with auto-fix
    * ``sail yarn lint-fix``
