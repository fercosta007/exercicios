# exercicios

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
         
    <script>

        // exercicio de numero1 // 

        var num1;
        var divisao;

        num1= prompt("digite um numero");
        num1= parseFloat(num1);
        if (num1>20)  {
            divisao= num1/2;
            
            alert(""+divisao);
        }


        // exercicio de numero 2 // 
    
       var senha = prompt("Digite a senha:");

        if (senha === "Patinho Feio") {
        
          alert("Acesso permitido");
                
        } else {
        alert("Voce nao tem acesso ao sistema");
         
     }

     // exercicio de numero 3 // 
     
     var numero1 = parseInt(prompt("Digite o primeiro numero inteiro:"));
     var numero2 = parseInt(prompt("Digite o segundo numero inteiro:"));


     var resultado = numero1 + numero2;

// Verificar se o resultado e maior que 10
if (resultado > 10) { 

  alert("O resultado da adicao e: " + resultado);
}

        //exercicio de numero 4 // 
     
    var numero = parseInt(prompt("Digite um numero:")); 


      if (numero >= 20 && numero <= 90) {
  alert("O numero esta compreendido entre 20 e 90.");
      } else {

  alert("O numero nao esta compreendido entre 20 e 90.");
    }


    // exercicio de numero 5 // 



    var numero1 = parseFloat(prompt("Digite o primeiro numero:"));

    var numero2 = parseFloat(prompt("Digite o segundo numero:"));

 
         if (numero1 > numero2) {
  alert("O maior numero e: " + numero1);
} else if (numero2 > numero1) {
  alert("O maior numero e: " + numero2);
} else {
  alert("Os numeros sao iguais.");
}        
              // exercicio de numero 6 / / 

              
       var numero1 = parseFloat(prompt("Digite o primeiro numero:"));
       var numero2 = parseFloat(prompt("Digite o segundo numero:"));


if (numero1 > numero2) {
  alert(numero1 + " e maior que " + numero2);
  alert(numero2 + " e menor que " + numero1);
} else if (numero2 > numero1) {
  alert(numero2 + " e maior que " + numero1);
  alert(numero1 + " e menor que " + numero2);
} else {
  alert("Os numeros sao iguais.");
}                   
                 
//  exercicio de numero 7 // 
        
var numero1 = parseFloat(prompt("Digite o primeiro numero:"));
var numero2 = parseFloat(prompt("Digite o segundo numero:"));
var numero3 = parseFloat(prompt("Digite o terceiro numero:"));


if (numero1 <= numero2 && numero1 <= numero3) {
  alert(numero1 + " e o menor numero.");
} else if (numero2 <= numero1 && numero2 <= numero3) {
  alert(numero2 + " e o menor numero.");
} else {
  alert(numero3 + " e o menor numero.");
}            

// exercicio de numero 8 // 
            
var numero1 = parseFloat(prompt("Digite o primeiro numero:"));
var numero2 = parseFloat(prompt("Digite o segundo numero:"));
var numero3 = parseFloat(prompt("Digite o terceiro numero:"));

// Verificar e imprimir os nmeros em ordem crescente
if (numero1 <= numero2 && numero1 <= numero3) {
  if (numero2 <= numero3) {
    alert(numero1 + ", " + numero2 + ", " + numero3);
  } else {
    alert(numero1 + ", " + numero3 + ", " + numero2);
  }
} else if (numero2 <= numero1 && numero2 <= numero3) {
  if (numero1 <= numero3) {
    alert(numero2 + ", " + numero1 + ", " + numero3);
  } else {
    alert(numero2 + ", " + numero3 + ", " + numero1);
  }
} else {
  if (numero1 <= numero2) {
    alert(numero3 + ", " + numero1 + ", " + numero2);
  } else {
    alert(numero3 + ", " + numero2 + ", " + numero1);
  }
}               

// exercico de numero 11 // 


var nome1 = prompt("Digite o nome da primeira pessoa:");
var peso1 = parseFloat(prompt("Digite o peso da primeira pessoa em kg:"));


var nome2 = prompt("Digite o nome da segunda pessoa:");
var peso2 = parseFloat(prompt("Digite o peso da segunda pessoa em kg:"));


if (peso1 > peso2) {
  alert(nome1 + " e a pessoa mais gorda.");
} else if (peso2 > peso1) {
  alert(nome2 + " e  a pessoa mais gorda.");
} else {
  alert("As duas pessoas tem o mesmo peso.");
}

 
// exercicio de numero 12 // 
                
   var numero = parseInt(prompt("Digite um numero:"));


      if (numero % 3 === 0) {
  alert(numero + " e multiplo de 3.");
} else {
  alert(numero + " nao e multiplo de 3.");
}
 
//exercicio de numero 14//
var nota;

do {
  nota = parseFloat(prompt("Digite uma nota entre zero e dez:"));

  if (isNaN(nota) || nota < 0 || nota > 10) {
    alert("Valor invalido. Digite novamente.");
  }
} while (isNaN(nota) || nota < 0 || nota > 10);

alert("Nota valida: " + nota);

//exercicio de numero 14//
var nomeUsuario, senha;

do {
  nomeUsuario = prompt("Digite o nome de usuario:");
  senha = prompt("Digite a senha:");

  if (senha === nomeUsuario) {
    alert("Erro: a senha nao pode ser igual ao nome de usuario.");
  }
} while (senha === nomeUsuario);

alert("Nome de usuario: " + nomeUsuario + "\nSenha: " + senha);

//exercicico de numero 15//
var nome, idade, salario, sexo, estadoCivil;


do {
  nome = prompt("Digite seu nome:");
} while (nome.length <= 3);


do {
  idade = parseInt(prompt("Digite sua idade:"));
} while (idade < 0 || idade > 150);


do {
  salario = parseFloat(prompt("Digite seu salario:"));
} while (salario <= 0);


do {
  sexo = prompt("Digite seu sexo (f/m):");
} while (sexo !== 'f' && sexo !== 'm');


do {
  estadoCivil = prompt("Digite seu estado civil (s/c/v/d):");
} while (estadoCivil !== 's' && estadoCivil !== 'c' && estadoCivil !== 'v' && estadoCivil !== 'd');

// Exibicao das informacoes validadas
alert("Nome: " + nome +
      "\nIdade: " + idade +
      "\nSalario: " + salario +
      "\nSexo: " + sexo +
      "\nEstado Civil: " + estadoCivil);

      //exercicio de numero 16//
    var opcao = prompt("Digite 1 para exibir os numeros abaixo um do outro ou 2 para exibi-los ao lado:");

if (opcao === '1') {
  
  for (var i = 1; i <= 20; i++) {
    alert(i);
  }
} else if (opcao === '2') {
          
  
  var numeros = '';
  for (var i = 1; i <= 20; i++) {
    numeros += i + ' ';
  }
  alert(numeros);
} else { 
  alert("Opcao invalida.");
}        

//exercicio de numero 17//

var numeroInicial = 1;
var numeroFinal = 50;

var numerosImpares = "";

for (var i = numeroInicial; i <= numeroFinal; i++) {
  if (i % 2 !== 0) {
    numerosImpares += i + "\n";
  }
}

alert("Numeros impares entre " + numeroInicial + " e " + numeroFinal + ":\n\n" + numerosImpares);


//exercico de numero 18//
var numero1 = parseInt(prompt("Digite o primeiro numero inteiro:"));
var numero2 = parseInt(prompt("Digite o segundo numero inteiro:"));

var numerosIntervalo = "";

if (numero1 <= numero2) {
  for (var i = numero1; i <= numero2; i++) {
    numerosIntervalo += i + " ";
  }
} else {
  for (var i = numero2; i <= numero1; i++) {
    numerosIntervalo += i + " ";
  }
}

alert("Numeros no intervalo: " + numerosIntervalo);
                







                 




    </script>




    
</body>
</html>
