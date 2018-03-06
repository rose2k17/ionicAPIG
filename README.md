# ionicAPIG -- > Google API IONIC

Primero hay que hacer un npm install, antes de hacer un <b>ionic start (nombre-proy) blank --cordova</b> o hacerlo con <b>ionic start --pro -id (numero)</b> porque parece que los logs son los que dan problemas y errores.

También es mejor que ionic cree la carpeta platform al crear el proyecto con ionic pro, porque da problemas al añadir ios.

 # Para integrar Google Maps
Se hace con el comando que aparece a continución:

<b>ionic cordova plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID="YOUR_ANDROID_API_KEY_IS_HERE" --variable API_KEY_FOR_IOS="YOUR_IOS_API_KEY_IS_HERE" --save</b>

Y luego se instala la dependencia de Google Maps:

<b>npm install @ionic-native/google-maps --save</b>

# Pasos 

Los archivos que hay que modificar son: 
  - De la carpeta app: app.module.ts y app.component.ts
  - De la carpeta pages/home: home.ts, home.html y añadir home.module.ts
  
 
