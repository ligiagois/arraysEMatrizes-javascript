Exercício 01

<html>
<head>
<meta charset="UTF-8" />
<title>Programação Estruturada</title>
</head>
<body>
<h1>Entrada do Programa</h1>
<button onclick='executarExercicio()'>OK</button>
 <p id="resultado"></p>
 <script>
 function executarExercicio() {
 // implemente a partir daqui
// Exemplo de comando de entrada
     
     var numeros= [];
     var ordem = [];
     for( i=0; i<=9; i++){
         
var a = Number(prompt("Informe um número:"));
numeros.push(a);
         ordem.push(a);
     }
       ordem.sort(comparacao);
     
     function comparacao(a,b){
         return a-b;
     }
     document.getElementById('resultado').innerHTML =ordem;
 }
   
 </script>
</body>
</html>

				
Exercício 02

<html>
<head>
    <meta charset="UTF-8" />
    <title>Programação Estruturada</title>
</head>
<body>
    <h1>Entrada do Programa</h1>
    <button onclick='executarExercicio()'>Começar</button>
    <p id="resultado"></p>
    <script>
        function executarExercicio() {
            var quantidadeNumeros = [];
            var indices = [];
            var a;
            while(a != 0){
                a = Number(prompt("Informe um número:"));
               quantidadeNumeros.push(a);
            }

            var i;
            var n=0;
            var contador = 0;
            var maior = 0;
            
            for(i = 0; i<quantidadeNumeros.length;i++){
                contador = 0;
                for( j  = 0; j<quantidadeNumeros.length;j++){
                    if(quantidadeNumeros[i]==quantidadeNumeros[j]){
                        contador++;
                    }
                }
                if(contador>maior){
                    maior = contador;
                    n = quantidadeNumeros[i];
                }
            }             
            var r = + n + " foi o número que mais se repetiu, nos índeces : ";
            for( j = 0; j<quantidadeNumeros.length;j++){
                if(quantidadeNumeros[j]==n){
                    r = r + " </br>"+j;
                }
            }

             document.getElementById('resultado').innerHTML = r;
        }
    </script>
</body>

</html>


Exercício 03

<html >
<head>
<meta charset="UTF-8" />
<title>Programação Estruturada - Aula 12</title>
</head>
<body>
<h1>Entrada do Programa</h1>
<button onclick="executarPrograma()">OK</button>
<p id="resposta"></p>
<script>
var linha1 = 10;
var coluna1 = 5;
var soma = 0;
function executarPrograma() {
var matriz = implementar();
var coluna = Number(prompt("Digite a coluna que deseja: "));
for(i = 0; i < linha1; i++) {
soma += matriz[i][coluna];
}
document.getElementById("resposta").innerHTML = `A soma da coluna ${coluna} é ${soma}`;
}

function implementar() {
var matriz = [];
for (var i = 0; i < linha1; i++) {
var linha = [];
for (var j = 0; j < coluna1; j++) {
num_str = prompt("Digite o elemento "+i+" x "+j+":");
num = Number(num_str);
linha.push(num);
}
matriz.push(linha);
}
return matriz;
}
</script>
</body>
</html>






