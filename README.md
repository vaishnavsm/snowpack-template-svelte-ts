# New Project

> 💞 Modified By vaishnavsm
> ✨ Originally Bootstrapped with Create Snowpack App (CSA).

To create an application using this as a template, use degit:
```
npx degit vaishnavsm/snowpack-template-svelte-ts svelte-ts-app
```

This is a minimal configuration, without a testing system installed.
Importantly, this does **not** use the official svelte configuration (app-scripts-svelte) but a simplified version written by myself. This removes the need for jest.

Do remember that snowpack uses babel to compile ts, which does not check the types set by ts!

!! Snowpack uses esbuild, which requires post-install scripts to work.
Make sure you are using post install scripts (this is default), or run the install.js manually.

## Available Scripts

### npm start

Runs the app in the development mode.
Open http://localhost:8080 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.


### npm run build

Builds a static copy of your site to the `build/` folder.
Your app is ready to be deployed!

**For the best production performance:** Add a build bundler plugin like "@snowpack/plugin-webpack" or "@snowpack/plugin-parcel" to your `snowpack.config.json` config file.

### npm run validate

Runs svelte-check, which checks for Typescript Errors, Unused CSS, and provides A11y hints.

### Q: What about Eject?

No eject needed! Snowpack guarantees zero lock-in, and CSA strives for the same.
