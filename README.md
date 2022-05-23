# segunda_avaliacao

//checkpoint_dois

function maiorOuMenor(valor1, valor2, valor3){
        if(valor1 > valor2){
            return "valor 1 é o maior!!!"
        }else if(valor2 > valor1){
            return "valor 2 é maior!!!"
        }if(valor3 > valor1){
            return "valor 3 é o maior"
        }else if(valor1 > valor3){
            return "valor 1 é o maior"
        }if(valor2 > valor3){
            "valor 2 é o maior"
        }else if(valor3 > valor2){
            "valor 3 é o maior"
        }
      } 
console.log(maiorOuMenor( 2, 4, 6));


function doarSangue(idade){
    if(idade >= 18 && idade <= 67){
        return "Voçê pode doar"
    } else {
        return "Voçê não pode doar"
    }
}
console.log(doarSangue(24));


function positivoOuNegativo(valor){
    if( valor > 0){
        return "valor positivo"
    }else if(valor < 0){
        return "numero negativo"
    }
}
console.log(positivoOuNegativo(10));

function mediaAluno(nota1, nota2) {
    let media = (nota1 + nota2)/2;
    if ( media >= 7 && media < 10) {
        return "Aprovado!"
    } else if (media == 10) {
        return "Aprovado com Distinção!"
    } else if (media < 7) {
        return "Reprovado!"
    }
}
console.log(mediaAluno( 10, 10));
