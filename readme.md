# Cálculo Dígito de Verificación DIAN

Función Javascript para calcular el Dígito de Verificación para la DIAN (Colombia) de una cédula o un nit.

Se tomó como base la función de [Calcular Digito de Verificación DIAN de mundonets.com](http://www.mundonets.com/digito-de-verificacion-dian/).

## Usar esta función en Apps Script 

```js
  var codigo = UrlFetchApp.fetch('https://raw.githubusercontent.com/Macorreag/calculo-digito-de-verificacion-dian/master/calcularDigitoVerificacion.js').getContentText();
  eval(codigo);
  Logger.log(calcularDigitoVerificacion("900810991"));
```


## Ejemplo

CodePen: [https://codepen.io/gabrielizalo/pen/bJwXaq](https://codepen.io/gabrielizalo/pen/bJwXaq)


## Historia

2015 04 27 - Primera versión

2019 04 08 - Adicionado ejemplo de CodePen
