# [webcompat-metrics-client][website]

[![Greenkeeper badge](https://badges.greenkeeper.io/webcompat/webcompat-metrics-client.svg)](https://greenkeeper.io/)

[website]: https://webcompat.com/

[![CircleCI status]][circle-ci]
[![travis status]][travis-ci]
[![appveyor status]][appveyor-ci]
[![PRs Welcome]][make-a-pull-request]

webcompat-metrics is a JavaScript application using [React] and [Redux] to power metrics for [webcompat.com]

### Quick Setup

```bash
git clone https://github.com/webcompat/webcompat-metrics-client.git

cd webcompat-metrics-client

yarn
yarn start:dev
# or
npm install
npm run start:dev
# Go to http://localhost:3001
```

### Testing

For testing DOM, React component, and others JavaScript, we use [Jest], [Enzyme] and [Sinon.JS].

For the linting JavaScript process, we use [Prettier] , [Eslint].

For the linting CSS process, we use [stylelint].

you can test application:

```bash
npm run test
# or
yarn test
```

### [Code of Conduct]

Webcompat has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text] so that you can understand what actions will and will not be tolerated.

### License

[MPL 2](./LICENSE)

[prs welcome]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[circleci status]: https://circleci.com/gh/webcompat/webcompat-metrics-client/tree/master.svg?style=shield
[circle-ci]: https://circleci.com/gh/webcompat/webcompat-metrics-client/tree/master
[travis status]: https://travis-ci.org/webcompat/webcompat-metrics-client.svg?branch=master
[travis-ci]: https://travis-ci.org/webcompat/webcompat-metrics-client
[appveyor status]: https://ci.appveyor.com/api/projects/status/o3fd2d32rxstpak4/branch/master?svg=true
[appveyor-ci]: https://ci.appveyor.com/project/magsout/webcompat-metrics-client/branch/master
[make-a-pull-request]: http://makeapullrequest.com
[jest]: https://facebook.github.io/jest/
[enzyme]: http://airbnb.io/enzyme/
[sinon.js]: http://sinonjs.org/
[prettier]: https://prettier.io/
[eslint]: https://eslint.org/
[stylelint]: https://stylelint.io/
[webcompat.com]: https://webcompat.com
[react]: https://reactjs.org/
[redux]: https://redux.js.org/
[code of conduct]: https://github.com/webcompat/webcompat-metrics-client/blob/master/CODE_OF_CONDUCT.md
[the full text]: https://github.com/webcompat/webcompat-metrics-client/blob/master/CODE_OF_CONDUCT.md
