# Hoja-de-herramientas-
// Herramientas para JavaScript

//.parseInt(num,2)
//. Convierte (parsea) un argumento de tipo cadena y devuelve un entero de la base especificada.

//.split()
var string = 'Mi Casa Esta En San Pedro'
string.split(' ')  // === ["Mi", "Casa", "Esta", "En", "San", "Pedro"]
string.split('a')  // === ["Mi C", "s", " Est", " En S", "n Pedro"]

//.join()
var array = ['El auto', 'la casa', 'los muebles']
array.join(' y ')  // === "El auto y la casa y los muebles"
array.join(' ')    // === "El auto la casa los muebles"

//.slice()
var nombres = ['Rita', 'Pedro', 'Miguel', 'Ana', 'Vanesa'];
var masculinos = nombres.slice(1, 3); // === ['Pedro','Miguel']

//.toUpperCase()
var cadena = 'hola'
cadena.toUpperCase() // === 'HOLA'

//.charAt()
var cadena = 'hola como estas?'
cadena.charAt(0) // === 'h'
cadena.charAt(1) // === 'o'
cadena.charAt(2) // === 'l'
cadena.charAt(3) // === 'a'

// forEach()


//.toString()

//.concat()
var array = ['El auto', 'la casa', 'los muebles'];
var numbers = [1, 2, 3];
array.concat(numbers) // === ["El auto", "la casa", "los muebles", 1, 2, 3]

// Object.values
var object = { computadora: 'Computadora', mouse: 'Mouse', auriculares: 'Auriculares', }
var an_obj = { 1: 'a', 8: 'b', 7: 'c',};
Object.values(object) // === ["Computadora", "Mouse", "Auriculares"]
Object.values(an_obj) // === ["a", "c", "b"]

//.reduce()
var array2 = [6, 4, 10, 5]
array2.reduce(function(acumulador, elemento) {
    return result = acumulador + elemento
  }) // === 25
  var integrado = [[0,1], [2,3], [4,5]]
  integrado.reduce(function(a,b) {
    return a.concat(b);
  }) // === [0, 1, 2, 3, 4, 5]

//.map()
var numbers = [1, 5, 10, 15];
var doubles = numbers.map(function(elemento) {
   return elemento * 2; }) // === [2, 10, 20, 30]
