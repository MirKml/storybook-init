# Storybook 7 minimal bootstrap
Minimal bootstrap for Storybook 7 with React 17, Typescript 5.2, Webpack 5

    $ cd sb-init
    $./sb-init.sh

Or `npm install; npm run init` on Windows.

It initializes minimal storybook setup for React. Tested with Webpack5. Adjust package.json, lock files, installs some template stories etc.
Result is in the directory `sb-bootstrapped`. You can use `sb-bootstrapped` dir for referenced minimal configuration, for troubleshooting etc.

Then when you type `npm run storybook` you will see the latest minimal functional Storybook.
