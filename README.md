# nuxt-vuetify-bug
Reproducing `ERROR: Vuetify Not initialized properly` in production mode but works fine is dev mode

steps to reproduce : 
```
cd functions/
npm install

cd ../src/
npm install 
npm run dev

cd ..
firebase emulators:start
```

