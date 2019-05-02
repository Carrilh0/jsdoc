

//calculadora com programação funcional

 function calculadora (operador){
  
	return function (x,y){      //testa se as entradas são numeros
	  if (typeof x !== "number" || typeof y !== "number"){
	    return false;
	};

	if (operador === '+'){      //condição do peração para a operação
	  return x+y;
	}else{
	  console.log('Valor errado');	
	    }
	  }
  }

JSON.stringfy() // tranforma em string
JSON.parse(); // transforma em obj
arr.unshift(3) // adciona um item no começo do array
arr.push(3) // adciona um item no final do array
arr.pop() // remover o ultimo item de um array
arr.shift() // remover o primeiro item de um array
arr.join(', ') // juntar intens de um array transformando em string
arr.reverse() // ordem alfabetica contraria
arr.sort() // ordenar em ordem alfabetica
arr.concat() // concatenar o array, mas não armazena no principal
arr.ToString() // transofrmar array/objeto em string




//mostrar propiedades e valores de um objeto

for (var i=0; i<books.length; i++){
for (var prop in books[i]){
    console.log(prop +': '+ books[i][prop])
}}
