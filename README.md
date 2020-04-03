# hello-world
test


const nome = "Pedro";
const sexo = "M";
const idade = 30;
const contribuicao = 10;

const calculoContribuicao = idade + contribuicao

const homemPodeAposentar = sexo == 'M' && contribuicao >= 35 && calculoContribuicao >= 95;
const mulherPodeAposentar = sexo == 'F' && contribuicao >= 30 && calculoContribuicao >= 90

if (homemPodeAposentar || mulherPodeAposentar) {
    console.log(`${nome}, você pode se aposentar.`)
} else {
    console.log(`${nome}, você ainda não pode se aposentar.`)
}
