# ES Module Boilerplate

I've set up a simple Babel based boilerplate that allows you to dig into JS
module development straight away.

## Downloading the Boilerplate

In order to fetch the boilerplate your project needs, clone it as follows:

```
git clone https://github.com/mazehall/my-new-es-module.git myModule
```

This will create a new directory, myModule. Inside it you can find everything you need to get ahead.

To make it your very own new project cleanup the git link.

```
cd myModule
rm -rf .git
git init
git add .
git commit -am "Initial commit"
```

After this process you have a fresh project to work against.

## Customization Hints

This very simple examle uses the testing solution [Jest](https://facebook.github.io/jest/).
If you want to remove it, delete the lines in ```package.json``` and ```.eslintrc```.
The test file itself is located in ```src/myNewModule.test.js```.
