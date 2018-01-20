## Folder Structure

After creation, your project should look like this:

```
app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
  src/
	components/
		Auth/
			login.js
			signup.js
	services/
		FirebaseAuthService.js
		FirebaseDBService.js
	styles/
		base.scss
    App.scss
    App.js
    index.scss
    index.js
```
For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>

### `npm run deploy`

Builds the app for production to the `build` folder and then deploys to the gh-pages branch<br>

## Installing a Dependency

You may install other dependencies with `npm`:

```sh
npm install --save react-router
```
