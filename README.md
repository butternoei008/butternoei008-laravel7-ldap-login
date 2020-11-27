In project make auth by vue. If you don't want vue you can doing follow this step before doing next step

-   Remove package `vue` and `vue-template-compiler` in package.json
-   In `resource/js/app.js` remove code line 9 - 33
-   Delete folder `compenents` in `resource/js/`

## Install

-   `composer install`
-   `cp .env.example .env`
-   Fix Database and LDAP according your setup in `.env`
   ```
   LDAP_SCHEMA=OpenLDAP
   LDAP_HOSTS=
   LDAP_BASE_DN=
   LDAP_USER_ATTRIBUTE=
   LDAP_USER_FORMAT=
   LDAP_CONNECTION=default
   ```
- `npm run install` or `yarn install`
- `npm run dev` or `yarn dev`
- Run project

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
```
