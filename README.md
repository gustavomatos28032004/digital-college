https://www.programiz.com/javascript/online-compiler/
https://github.com/gildembergleite/fs-39/blob/main/aula-15/atividade-condicionais.md

// Questão 1
// const num1 = +prompt('Digite o primeiro número: ')
// const num2 = +prompt('Digite o primeiro número: ')
// const num3 = +prompt('Digite o primeiro número: ')

// const soma = num1 + num2

// if (soma < num3) {
//     console.log('A soma é menor!')
// } else if (soma === num3) {
//     console.log('A soma é igual')
// } else {
//     console.log('A soma é maior!')
// }

// Questão 3
// const numero = +prompt('Digite um número: ')

// if (numero % 2 === 0) {
//     console.log("PAR")
// } else {
//     console.log("ÍMPAR")
// }

// Questão 4
// const num1 = +prompt('Digite o primeiro número: ')
// const num2 = +prompt('Digite o segundo número: ')

// if (num1 === num2) {
//     const calculo = num1 + num2
//     console.log(`A soma de ${num1} e ${num2} é ${calculo}`)
// } else {
//     const calculo = num1 * num2
//     console.log(`A multiplicação de ${num1} e ${num2} é ${calculo}`)
// }

// Questão 5
// const numero = +prompt('Digite um número: ')

// if (numero > 0) {
//     console.log(numero * 2)
// } else if (numero < 0) {
//     console.log(numero * 3)
// }

// Questão 6
// const primeiro = prompt('Digite VERDADEIRO ou FALSO: ')
// const segundo = prompt('Digite VERDADEIRO ou FALSO: ')

// if (primeiro === 'VERDADEIRO' && segundo === 'VERDADEIRO') {
//     console.log('Ambos são VERDADE!')
// } else if (primeiro === 'FALSO' && segundo === 'FALSO') {
//   console.log('Ambos são FALSOS!') 
// } else {
//     console.log('Os valores são diferentes!')
// }

// Questão 8 - Primeira Solução
// const num1 = +prompt('Digite o primeiro número: ')
// const num2 = +prompt('Digite o segundo número: ')
// const num3 = +prompt('Digite o terceiro número: ')

// let maior
// let meio
// let menor

// if (num1 > num2 && num1 > num3) {
//     maior = num1
// } else if (num2 > num1 && num2 > num3) {
//     maior = num2
// } else {
//     maior = num3
// }

// if (num1 < num2 && num1 < num3) {
//     menor = num1
// } else if (num2 < num1 && num2 < num3) {
//     menor = num2
// } else {
//     menor = num3
// }

// meio = (num1 + num2 + num3) - maior - menor

// console.log(maior, meio, menor)

// Questão 8 - Segunda solução
// const num1 = +prompt('Digite o primeiro número: ')
// const num2 = +prompt('Digite o segundo número: ')
// const num3 = +prompt('Digite o terceiro número: ')

// const maior = Math.max(num1,num2,num3)
// const menor = Math.min(num1,num2,num3)
// const meio = (num1 + num2 + num3) - maior - menor


// EXEMPLO COM SWITCH CASE
// const numeroDoDiaDaSemana = prompt('Digite um numero de 1 a 7: ')

// switch (numeroDoDiaDaSemana) {
//     case '1':
//         console.log('Domingo')
//         break
//     case '2':
//         console.log('Segunda-feira')
//         break
//     default:
//         console.log('Valor inválido')
// }
