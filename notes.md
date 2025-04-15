# This script is for keeping notes for not missing any thing !

After initialising the project and running the dev server by :
npx expo start
we should set up the styling .
1- PS C:\nodeJSProjects\movies-app> npm install nativewind tailwindcss react-native-reanimated react-native-safe-area-context

this command will install all packages we gonna need for styling <!-- go to nativeWind you will find all what you have to do -->

*"npx expo customize metro.config.js" command
What npx expo customize Does ?
Generates Config Files
Creates editable versions of configuration files in your project root, letting you customize:
Webpack (webpack.config.js) → For web builds.
Metro (metro.config.js) → For React Native bundling.
Babel (babel.config.js) → For JS/TS transpilation.
Non-Destructive
Only creates files if they don’t already exist.
Won’t modify existing files (safe to run).
Avoids Ejecting
Lets you tweak build tools without leaving Expo’s managed workflow.
Common Use Cases
Customizing Webpack (e.g., adding SVG loaders, aliases).
Extending Metro (e.g., adding react-native-reanimated plugin).
Modifying Babel (e.g., adding new presets/plugins).


*The command npx expo start --clear (or npx expo start -c) does the following in an Expo project:
What It Does
Clears the Metro bundler cache
Forces Expo to rebuild all JavaScript/TypeScript files from scratch.
Fixes issues caused by outdated or corrupted cache (e.g., stale code, missing modules).
Resets the React Native packager (Metro)
Restarts the development server (expo start) with a fresh state.
Does NOT delete:
Your node_modules or project files.
Expo config (app.json/app.config.js).
Strange build errors (e.g., Module not found, outdated UI).

Code changes not reflecting in the app (Hot Reload not working).

"Something went wrong" Expo app crashes with no clear reason.

