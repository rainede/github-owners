# Probot: OWNERS

> a GitHub Integration built with [Probot](https://github.com/probot/probot) that @mentions maintainers in Pull Requests based on contents of the [OWNERS](https://github.com/bkeepers/owners) file.

## Usage

1. **[Install the integration](https://github.com/integration/owners)**.
2. Create a [`OWNERS`](/OWNERS) file in your repository.
3. Wait for new Pull Requests to be opened

See [docs/deploy.md](docs/deploy.md) if you would like to run your own instance of this plugin.

## Deploying to Heroku via one click:
You can deploy your own copy of the app using this *button*:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Running Locally and then deploying:

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Command Line](https://devcenter.heroku.com/articles/heroku-cli) installed and in your terminal/command line tools, clone and run the app:

```sh
git clone git@github.com:heroku/github-owners.git # or clone your own fork
cd github-owners
npm install
npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

You can then manually deploy using these *commands* in your terminal/command line tools:
```
heroku create
git push heroku master
heroku open
```

## Documentation

For more information about using Heroku, check out the [Heroku Dev Centre](https://devcenter.heroku.com/)
For more information about creating standalone bots on Github, check out [Github PR Bot](https://github.com/probot/probot/blob/master/docs/deployment.md)
