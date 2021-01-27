# React / Node Sample Demo App


## Getting Started

```bash
# clone repo
git clone https://github.com/aleemlatif/react-sample.git

# navigate to repo
cd react-sample-app

# install deps
npm install
```

**Backend**

```bash
# Run in terminal
npm run serve
```

**Frontend**

```bash
# run in terminal
npm run dev
```

**Database**

No configuration should be necessary necessary. Data backend is simply a json file called `todos.json` in `data/`.
If you run into any issues make sure `todos.json` has the following inside before starting the
server. This will become more robust overtime.

```json
{
    "todos": []
}
```

## Not meant for production

There are a couple of issues to fix before this code base should
be used as a model for a production ready application.

* Swap out the file based data model for a real data backend.
* Replace webpack dev server with an application server or serve up the app with the Node server.

## Technologies

* [node](https://nodejs.org/en/)
* [express](http://expressjs.com/)
* [webpack](https://webpack.github.io/)
* [react](https://facebook.github.io/react/)
* [material-ui](http://www.material-ui.com/#/)
* [babel](https://babeljs.io/)
* [eslint](http://eslint.org/)
