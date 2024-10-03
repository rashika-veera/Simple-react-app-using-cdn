# React App
1. Hello world program using cdn links
    => Use the cdn links from this website: https://legacy.reactjs.org/docs/cdn-links.html and integrate it on your App.js file

2. Integrating parcel into the app

   2.1 `npx install -D parcel` : command to install the bundler -parcel into our appplication

   2.2 `npx parcel index.html` : To build our app and host it on a local server , this is meant for dev env. In case of production env , we can use `npx parcel build index.html`

   2.3 Remove the cdn links and you can import react and react-dom libraries through npm install and you can ignite your application. 

   2.4 Use `type="module"` on script tag to make sure that the browser treats it as a EC modules to enable the usage of import or export statements.
   
3. Use browserlists to enable the usage of this app on particular browsers or geographic locations.


