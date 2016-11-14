# ng-demo
Angular 2 boilerplate project: A pristine Angularific front-end "skeleton" for your app. Build your own custom Classes, Services, Components and APIs on top.

All boilerplate code should be taken from this example, which is based on [Getting Started with Angular 2](https://bootcamp-coders.cnm.edu/screencasts/getting-started-with-angular2/).

# Instructions
Have Node, NPM, TypeScript and Webpack installed and up-to-date on your laptop ~ AND ~
have the Angular, JavaScript Support, and Node plugins installed/activated in PhpStorm. Ok? Let's get rolling!

1. Create a new GitHub repository for your project. Add the `.gitignore` (boilerplate), clone, and create a new deployment!
2. Add `package.json` (boilerplate), and **update the relevant fields for YOUR project**.
3. Open Terminal or Git BASH. `cd` into your project root directory and run `npm install` on your laptop (hereafter referred to as "**locally**") _AND_ on bootcamp-coders.cnm.edu (henceforth referred to as "**remote**")
4. Add `tsconfig.json` (boilerplate)

5. Add `.bootstraprc` (boilerplate)

6. Create the `/webpack` directory in the project root, and now we'll create all your webpack files!
 - Create `helpers.js` (boilerplate)
 - Create `webpack.common.js` (boilerplate)
 - Create `webpack.live.js` (boilerplate)
 - Create `index.php` - This is your Webpack HTML template. Webpack will build your main app page based on this template. **Update the custom tag here with your app name**. We'll reference this later in Angular.

7. Create the `/app` directory, and we'll add all your app files here.
 - Create `app/vendor.ts` (boilerplate). Select OK to TypeScript compiling in PhpStorm.
 - Create `app/polyfills.ts` (boilerplate)
 - Create `app/app.css` You can leave this blank for now. All your custom CSS will be written here.
 - Create `app/app.ts` (boilerplate)
 - Create `app/app.module.ts` - *Mostly* boilerplate code, but you'll need to update this later on. You'll need to reference your Services here in the future.
 - Create `app/app.component.ts` - **Update the *selector* here** with your app name. The *custom tag* you previously set inside your webpack/index.php file needs to MATCH here. Update the `templateUrl` filename to be "*yourappname*-app.php". We'll create and update this file later.
 - Create `app/app.routes.ts` - **Update these routes for YOUR app**. Since we only have a Home Page View for now, the only Component we need is HomeComponent. You will need to update this file for any additional Views you create later.

8. Create the `app/components` directory and create your app Components here.
 - Create `home-component.ts` The sample code here is BARE BONES. Customize as needed.
 - **NOTE: All your TypeScript "transpiling" should now resolve! ~~**

9. Create your `/public_html/templates` directory
 - Create your base template HTML: `yourapp-app.php`
 - Create your splash/home template HTML: `home.php`

10. add the `.htaccess` file to /public_html - boilerplate code

**Run `npm run build` both locally and remote and you should be good to go!**