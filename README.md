# Google API IONIC

## Si se descarga este proyecto

Se ubica en el proyecto descargado y se hace:
```
npm install
```
Luego, para descargar las dependencias:
```
ionic cordova prepare
```
Y añadimos las keys de google maps:
```
ionic cordova plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID="YOUR_ANDROID_API_KEY_IS_HERE" 
--variable API_KEY_FOR_IOS="YOUR_IOS_API_KEY_IS_HERE" --save
```
## Si se hace creando el proyecto de Ionic de este <a href="https://blog.ng-classroom.com/blog/ionic2/google-maps-native/">tutorial</a>

Primero hay que hacer un <code><b>npm install</b></code>, antes de hacer un <code><b>ionic start (nombre-proy) blank --cordova</b></code> o hacerlo con <code><b>ionic start --pro -id (numero)</b></code> porque parece que los logs son los que dan problemas y errores.

También es mejor que ionic cree la carpeta platform al crear el proyecto con ionic pro, porque da problemas al añadir ios.

 ## Para integrar Google Maps
Se hace con el comando que aparece a continución:
```
ionic cordova plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID="YOUR_ANDROID_API_KEY_IS_HERE" 
--variable API_KEY_FOR_IOS="YOUR_IOS_API_KEY_IS_HERE" --save
```
Y luego se instala la dependencia de Google Maps:
```
npm install @ionic-native/google-maps --save
```
## Pasos 

Los archivos que hay que modificar son: 
  - De la carpeta app: app.module.ts y app.component.ts
  - De la carpeta pages/home: home.ts, home.html y añadir home.module.ts
  
 
