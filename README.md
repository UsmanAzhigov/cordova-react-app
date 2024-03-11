../CrossCr-F/build Выполняете команду

1)
npx create-react-app my-react-app --template typescript

cd my-react-app

npm run build

2) Выходите с папки 
cordova create my-cordova-app

cd my-cordova-app

rm -rf www

ln -s ../my-react-app/build www

cordova platform add android

cordova build android
