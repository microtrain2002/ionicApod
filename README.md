# Ionic: NASA - Astronomy Pic of the Day

Run a CLI program called *ionic*. The ionic command wraps Angular's ```ng``` command with additional functionality. Ionic runs on 
top of the AngularCLI.   

```sh
cd ~
ionic start ionicApod blank
```
Choose a version; **CHOOSE ANGULAR**.

If the installation was successful you will see some instructions for the 
*Next Steps*.

We are only concerned with the first two steps. The last two steps are links to 
documentation; I will post those in the additional resources section.

```sh
cd ionicApod
ionic serve
```

Add .editorconfig file

Define the Apod object. src/app/apod.model.ts

create the apod service.

```sh
ionic generate service apod
```
create the apod page.

```sh
ionic generate page apod
```
Update the routes array in the app-routing module. Replace the routes constant with the following snippet.
app-routing.module.ts
src/app/apod/apod.page.ts

Declare safe pipe as follows
src/app/apod.module.ts

Implement the UI.
src/app/apod/apod.page.html


