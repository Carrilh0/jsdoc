
								ARRAYS


JSON.stringfy() // tranforma em string;

JSON.parse(); // transforma em obj;

arr.indexOf() // procura no array a existencia do paramentro passado, se resultador = -1 então é falso, caso contrario = true;

arr.unshift(3) // adciona um item no começo do array;

arr.push(3) // adciona um item no final do array;

arr.pop() // remover o ultimo item de um array;

arr.shift() // remover o primeiro item de um array;

arr.join(', ') // juntar intens de um array transformando em string;

arr.reverse() // ordem alfabetica contraria;

arr.sort() // ordenar em ordem alfabetica;

arr.concat([outro array]) // concatenar o array, mas não armazena no principal;

arr.ToString() // transofrmar array/objeto em string;

arr.slice(1,4) / arr.slice(-1) // Mostra os arrays selecionados de acordo com os indices (between);

arr.splice() // O método splice() altera o conteúdo de uma lista, adicionando novos elementos enquanto remove elementos antigos;

arr.forEach(function(item,index,array){}) // O método forEach() executa uma dada função em cada elemento de um array.

arr.every(function(item, index, array){)} // Retorna true ou false, se todos os itens testatos forem true, ex: return return item < 8; // true;

arr.some(function(item,index,array){)} // Retorna true ou false se apenas um item do array for true;

arr.map(function(item,index,array){return item+1}) // faz alguma operação com todos os itens do array;

arr.filter(function(item,index,array){return item>5}) // retorna um array de acordo com oq você quiser;

arr.reduce(function(acumulado,atual,index,array){return acumulado + atual} // O valor de retorno da sua função reducer é atribuída ao acumulador. O acumulador, com seu valor atualizado, é repassado para cada iteração subsequente pelo array, que por fim, se tornará o valor resultante, único, final.

arr.reduceRight(function(previousValue, currentValue, index, array) // Mesma coisa do reduce, porem da direita para a esquerda;


							STRINGS
							
							
							
str.length = retornar em numero a quantidade de letras;
str.charAt(0) = retorna a letra na posição do parametro ex: 'vitor' str.charAt(0) = 'v';
str.concat('a','b') = concatena varias strings em apenas uma;
str.indexOf('') = verifica sem tem o parametro passado no array;
str.replace('a','s') = substitui o primeiro parametro na string pelo segundo;
str.slice 

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


//acessar valores de um objeto

for (var i=0; i<books.length; i++){
for (var prop in books[i]){
    console.log(prop +': '+ books[i][prop])
}}

//transformar array em objeto

arr.forEach(function(item,index){
	newarr.push({id:index,nome:item})
	console.log(index,item);
});
