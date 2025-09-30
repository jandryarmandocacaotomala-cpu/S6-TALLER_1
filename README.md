// 2) Contar apariciones de una letra específica
  function contarApariciones(cadena, caracter) {
    var c = 0;
    for (var i = 0; i < cadena.length; i++) {
      if (cadena.charAt(i) === caracter) c++;
    }
    return c;
  }
  function SerieContarApariciones(cadenas, car) {
    for (var i = 0; i < cadenas.length; i++) {
      var resp = contarApariciones(cadenas[i], car);
      console.log("La letra '" + car + "' aparece " + resp + " veces en la cadena '" + cadenas[i] + "'");
    }
  }
  SerieContarApariciones(['Me encanta el café', 'Estudio programación'], 'e');
