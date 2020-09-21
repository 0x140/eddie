[![codebeat badge](https://codebeat.co/badges/75f9430c-aa10-4988-a6c3-9002d270cf2e)](https://codebeat.co/projects/github-com-edwinnduti-dev-to-static-site-master) ![License: MIT](https://img.shields.io/badge/Blog-Personal-blue.svg)

![License: MIT](https://img.shields.io/badge/Site%20name-edwinnduti.com-red.svg)

# Running The Site Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        >npm install

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        >export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch additional site contents from Stackbit if needed:

        >npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5e1a2be47e184700194abf9d

1. Starts a development server

        >npm run develop

1. Browse to [http://localhost:8000/](http://localhost:8000/)
