# nuxt-vuetify-bug
Reproducing `ERROR: Vuetify Not initialized properly` in production mode but works fine is dev mode

steps to reproduce : 
```
cd functions/
npm install

cd ../src/
npm install 
npm run build

cd ..
firebase emulators:start
```
One could go with Regular `nuxt build` and `nuxt-start` 
-------------------------------------------

**setting up firebase emulators**
run following in root directory
```
firebase init emulators
```
proceed and select emulators for hosting, functions
