## Setup Commands
Create React App
```bash
npx create-react-app ./
```

Clear out `src` folder

Create `index.js` inside `src`

Copy [packages](https://raw.githubusercontent.com/adrianhajdin/project_syncfusion_dashboard/main/package.json) from course and update `package.json`

Install new packages
```bash
npm install --legacy-peer-deps
```

Create `index.css` and copy [contents from course](https://raw.githubusercontent.com/adrianhajdin/project_syncfusion_dashboard/main/src/index.css)

Create `App.css` and copy [contents from course](https://raw.githubusercontent.com/adrianhajdin/project_syncfusion_dashboard/main/src/App.css)


Create `tailwind.config.js` in root folder and copy [contents from course](https://raw.githubusercontent.com/adrianhajdin/project_syncfusion_dashboard/main/tailwind.config.js)

Create `craco.config.js` in root folder and copy [contents from course](https://raw.githubusercontent.com/adrianhajdin/project_syncfusion_dashboard/main/craco.config.js)

Add ESLint
```bash
npm install eslint
```

Setup `eslintrc`
```bash
./node_modules/.bin/eslint --init
```

May need to go to Settings in VS Code to setup format on save. Guide [here](https://www.digitalocean.com/community/tutorials/linting-and-formatting-with-eslint-in-vs-code)

## Start Server
Now it's time to start the server to check and make sure everything is working as it should.

```bash
npm start
```

## Project Structure
Add the following folders to `src`:
  - components
  - contexts
  - pages

Download and paste the [data folder](https://github.com/adrianhajdin/project_syncfusion_dashboard/tree/main/src/data) from the course.
