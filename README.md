# eslint-plugin-email-css-rules
[![js-standard-style](https://cdn.rawgit.com/standard/standard/master/badge.svg)](http://standardjs.com)
[![Build Status](https://travis-ci.org/taskworld/eslint-email-template.svg?branch=master)](https://travis-ci.org/taskworld/eslint-email-template)
[![Coverage Status](https://coveralls.io/repos/github/taskworld/eslint-email-template/badge.svg?branch=master)](https://coveralls.io/github/taskworld/eslint-email-template?branch=master)

React css email's rules.

## installation
Install [ESLint](https://github.com/eslint/eslint) either locally or globally.

```sh
npm install eslint
```

After that

```sh
$ npm install eslint-email-rules --save-dev
```

# Configuration

Add to ```plugins``` section in eslintrc file.

```json
{
  "plugins": [
    "email-css-rules"
  ]
}
```

If it is not already the case you must also configure `ESLint` to support JSX.

```json
{
  "ecmaFeatures": {
    "jsx": true
  }
}
```

# Special Thank

 Thanks for all reference data from [react-html-email](https://github.com/chromakode/react-html-email) to composed those datas to JSON.

 Huge thank from resource from [The Untimate Guide to CSS](https://www.campaignmonitor.com/css/) to collect the css breakdown in every platforms.

# Contribute
I warm welcome all for contributer to make it better (Trump face).
