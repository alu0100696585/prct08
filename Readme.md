Cristo González Rodríguez
Juvenal Santiso Hernández

Grupo 07 - Turno de mañana

====> Práctica 8 <====

  Se crean los ficheros "Gemfile", "Rakefile" y "Guardfile" para poder trabajar con la herramienta de integración continua
(Continuos Integration) Travis, y con la herramienta de comprobación continua (Continuous testing) Guard.

  Creación del fichero ".travis.yml" pata trabajar con la herramienta de integración continua Travis.

  Creación del fichero "spec/spec_matriz.rb" vacío, que contendrá las espectativas de la clase Matriz.
  
  Primera definición de espectativas: instancias de objetos para los test, y acceso correcto a filas y columnas de la matriz.
    Se satisfacen las espectativas: definición de la clase, métodos initialize, métodos factoría y attr_reader.
  
  Segunda definición de espectativas: conversión a string, y acceso y modificación de los elementos de la matriz.
    Se satisfacen las espectativas: método to_s, y de acceso y asignación de los elementos de la matriz.
    
  Tercera definición de espectativas: operaciones aritméticas (suma, resta, multiplicación(matriz y escalar)), y comparación de matrices (==).
    Se satisfacen las espectativas: sumar, restar, multiplicar por una matriz o por un escalar y la comparación(==) de matrices.
  
  Incluyendo clase Fraccion: modificación de defensa de práctica - matrices de fracciones.
