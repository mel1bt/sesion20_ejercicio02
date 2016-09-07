# sesion20_ejercicio02
## Codigo Inicial
var feature = 'closures'; 
(function () {     
if ( typeof feature === 'undefined' ){         
var feature = 'callbacks';         
console.log('JS coders love its ' + feature );     
} else {         
console.log('JS developers love its ' + feature );     
} 
})();
## Solucion planteada 
#### La solución que planteo es el cambio de valores a las variables globales y locales. Ya que la variable local siempre prevalecera de la global.
var feature = 'callbacks'; 
(function () {     
if ( typeof feature === 'undefined' ){         
var feature = 'closures';         
console.log('JS coders love its ' + feature );     
} else {         
console.log('JS developers love its ' + feature );     
} 
})();

