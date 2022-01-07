# Angularmaterial

ng add @angular/material
ng --version

https://material.angular.io/

npm i -s @angular/flex-layout

ng g m demo/demo --dry-run --flat --routing
ng g c demo/buttons --dry-run --no-spec --inline-style --inline-template




-   g stand for generate
-   m stand for module

Provides a component, a module, etc. and accepts all parameters like normal
wrapping the ng g call in package.json: "ngd": "ng g -d --"

    npm run ngd c my/component/
    npm run ngd m moduleName
    npm run ngd d directiveName

    ng new example --skip-tests

if you don't want that extra folder, you can use the --flat option

-   **ng eject** It will disable the CLI for your project and create you a webpack configuration file

ng s -o 
-   serve and open

## scaffolding app

-   --dry-run It does exactly what you stated. "Run through without making any changes" 

    ng g m contactmanager --dry-run
    ng g m contactmanager
    ng g c contactmanager\contactmanager-app --dry-run
    ng g c contactmanager\contactmanager-app --dry-run --flat --skip-tests --inline-style --inline-template
    ng g c contactmanager\contactmanager-app --flat --skip-tests --inline-style --inline-template

    ng g c contactmanager\components\toolbar --dry-run
    ng g c contactmanager\components\toolbar --skip-tests
    ng g c contactmanager\components\main-content --skip-tests
    ng g c contactmanager\components\sidenav --skip-tests

    ng g s contactmanager\services\user --dry-run
    ng g class contactmanager\models\user
    ng g class contactmanager\models\note
    


