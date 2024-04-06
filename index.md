www.fronteditor.dev/nlw-unite

# HTML

*Hypertext*

*Markup*
-tag
-atributos

*Language*


# CSS
/* declarações */
body {
  background-color: #121214;
  color: #ffffff;
}

# JavaScript
```js
//variaveis 
const mensagem = "oi tudo bem?"
//tipos de dados
//number
//string
//funcao
alert (mensagem)

 //objeto javascript
const Participante = {
   nome: "Pricila Queiroz",
   email: "priscila@gmail.com",
   dataInscricao: new date(2024, 2 ,22 ,19, 20), 
   dataCheckIn: new date(2024, 2, 25, 22, 00)
}

  //array
let participantes = [ 
  {
   nome: "Pricila Queiroz",
   email: "priscila@gmail.com",
   dataInscricao: new date(2024, 2 ,22 ,19, 20), 
   dataCheckIn: new date(2024, 2, 25, 22, 00)
  }, 
]
  //estrutura de repeticao loop
 for(let participante of participantes) {
    output = output + criarNovoParticipante(participante)
    //faca alguma coisa aqui 
    //enquanto tiver participantes
 }