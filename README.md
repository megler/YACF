# YACF

YACF (pronounced "Yack-Siff") may sound like what your cat does when he has a hairball, but in reality, it's a flexible CSS only Framework. With YACF, the hard work of layout has been thought out for you. All you need to do is strategically place your classes and you're all set.

##### Want to customize? Not a problem!

With YACF you have a customization page for all your Sassy/CSS needs so you can change anything to make it more suitable to your needs!

### How To Install:
You have the following options to install YACF:

- You can download the lastest release with pre-built CSS.
- Clone the repo to get all source files including build scripts: `git clone git://github.com/megler/YACF.git`

If you just want to use YACF out of the box with no modifications, download the latest release up in step 1 and extract either `yacf-style.css` or `yacf-style-min.css` and call it in your header.

You place the stylesheet in your header like this:

`link rel="stylesheet" href="/directory-to-style-folder/yacf-style.css"`

If you would like to customize YACF via the built-in SASS, then you can install using either step 1 or 2 above and extracting the entire package. You will still place your stylesheet normally, but now you will have all of the Sass files and optional npm scripts for automation.

That will give you full access to all the YACF classes. That's it! You're ready to roll! 

### Build Notes

YACF gives you the option of running an NPM build that will install [node-sass](https://www.npmjs.com/package/node-sass) and [npm-run-all](https://www.npmjs.com/package/npm-run-all) as dev dependencies.  You will also need [browser-sync](https://www.browsersync.io/) installed globally for the scripts found in package.json to run.

There are pre-built scripts in the package.json file that when run, will auto compile your sass and update your browser.  You'll want to run `npm start` to initiate this process.  The script is set to update Firefox.  If you prefer a different browser, check the [browser-sync docs](https://www.browsersync.io/docs/options#option-browser). 

### Documentation:

You can read all of the documentation on the YACF homepage.

### YACF In Action

Here is an example page using YACF.  View the page source to see the classes in action.
