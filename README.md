npm install -g expo-cli
expo init projectname
cd projectname
npm start



(then scan the qr code through expo go app in your mobile and go)



for the Deployment: 
expo install react-native-web@~0.17.1 react-dom@17.0.1 @expo/webpack-config@0.12.0
expo build:web
npm install -g vercel
cd web-build
vercel
