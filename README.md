# Cookieshop
Une fabrique de cookie bar légère pour votre plus grand plaisir

## Légèreté
Le script est autonome, il fonctionne avec un pur javascript naturel. Avec seulement 3ko, il est parfait pour garder la ligne de votre page.

## Instalation
Copier/Coller 
```javascript
<script type="text/javascript" src="cookieBar.js" async defer onload="window.cookieShop.init();"></script>
```
## Custom
###Message
```javascript
var forstingFlavor = "En poursuivant votre navigation sur ce site, vous acceptez l’utilisation de cookies conformément à notre politique de données personnelles.";
```
###Style
```javascript
//bar
var ingerdient = "background: #161616; position: fixed; width: 100%; color: #ffffff; font-family: Helvetica, Arial, sans-serif; z-index: 1510; font-size: 12px; cursor: pointer; margin: 0 auto; height: 30px; line-height: 30px; text-align: center; top: 0; left: 0; right: 0;";
//button
var chip_bottel = "position: absolute; top: 0; bottom: 0; right: 20px; width: 20px; height: 2px; background-color: #ffffff; margin: auto;";
//cross
var spreadBlack = "-webkit-transform: rotate(45deg); -moz-transform: rotate(45deg); -o-transform: rotate(45deg); -ms-transform: rotate(45deg); transform: rotate(45deg);";
var spreadWhite = "-webkit-transform: rotate(90deg); -moz-transform: rotate(90deg); -o-transform: rotate(90deg); -ms-transform: rotate(90deg); transform: rotate(90deg); right: 0;";
```
