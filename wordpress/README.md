# Codacy configuration for WordPress projects
Copy these files to the root of your project before your first commit, then push them to the master branch in Bitbucket. They will be used by Codacy instead of the default ones.

If you are using the [Lean Theme](https://github.com/wearenolte/lean-theme), these files are already located in the `wp-content/themes/<theme>` and `wp-content/themes/<theme>/frontend` folders for your local linting process, and all the required packages are already included in the package.json.

If not using the Lean Theme, for these linters to work you'll need to install these dependencies (we recommend using [Yarn](https://github.com/yarnpkg/yarn) over NPM as the package manager, for some advantages like speed, security, cache features, etc.):

### [ESLint](https://github.com/eslint/eslint)
ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.

`$ yarn add eslint --dev`
or
`$ npm install eslint --save-dev`

### [stylelint](https://github.com/stylelint/stylelint)
A modern linter that helps you avoid errors and enforce conventions in your styles.

`$ yarn add stylelint --dev`
or
`$ npm install stylelint --save-dev`

### [stylelint-config-property-sort-order-smacss](https://github.com/cahamilton/stylelint-config-property-sort-order-smacss)
Stylelint config for Property Sort Ordering based on the [SMACSS](http://smacss.com/) methodology.

`$ yarn add stylelint-config-property-sort-order-smacss --dev`
or
`$ npm install stylelint-config-property-sort-order-smacss --save-dev`

### [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard)
Extends [stylelint-config-recommended](https://github.com/stylelint/stylelint-config-recommended).

Turns on additional rules to enforce the common stylistic conventions found within a handful of CSS styleguides, including: [The Idiomatic CSS Principles](https://github.com/necolas/idiomatic-css), [Google's CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#CSS_Formatting_Rules), [Airbnb's Styleguide](https://github.com/airbnb/css#css), and [@mdo's Code Guide](http://codeguide.co/#css).

`$ yarn add stylelint-config-standard --dev`
or
`$ npm install stylelint-config-standard --save-dev`
