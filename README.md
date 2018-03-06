# ionicAPIG -- > Google API IONIC

Primero hay que hacer un npm install, antes de hacer un ionic start (nombre-proy) blank --cordova o hacerlo con start --pro-id (numero) porque parece que los logs son los que dan problemas y errores.

También es mejor que ionic cree la carpeta platform al crear el proyecto con ionic pro, porque da problemas al añadir ios.

 # Para integrar Google Maps
Se hace con el comando que aparece a continución:

ionic cordova plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID="YOUR_ANDROID_API_KEY_IS_HERE" --variable API_KEY_FOR_IOS="YOUR_IOS_API_KEY_IS_HERE" --save

y luego se instala la dependencia de Google Maps:

npm install @ionic-native/google-maps --save

# Pasos 

Los archivos que hay que modificar son: 
  - De la carpeta app: app.module.ts y app.component.ts
  - De la carpeta pages/home: home.ts, home.html y añadir home.module.ts
  
 
