# AFB2
//1ªQuestão)

var result = someFun({ someProperty: 'interview'}, function(value){

    console.log('This pointing to ' + value);

});

console.log('Result is', result);

function someFun(var1, var2){

    var2(var1.someProperty);
    return 1;
}

//2ªQuestão) 

var someFn = function(numero) 
    {
        var somar = numero;

        return function (incremento) 
    {
        somar += increment;

        return somar;
    }
    }

    var counter  = someFN(1)

    console.log("First call", counter(3))
    console.log("second call", counter(1))
    console.log("Third call", counter(5))

//3ªQuestão)

function calculator(n1, n2) {
  return callback => callback(n1, n2)
}




//4ªQuestão)

var a  = 5
var b = 10

if(a == 5){
  let a = 4
  var b = 1
  console.log(a)
  console.log(b)
}
console.log(a)
console.log(b)
//RESPOSTA: 4,1,5,1
*/


  }
}
num(2)
*/


//5ªQuestão)


/*
function num(numero)
{
  for(var i = 1; i <= 10; ++i)
  {
    console.log(i * numero)

  }
}
num(2)
*/
