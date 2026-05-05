# 🧮 Calculadora em HTML + JavaScript

🔗 Arquivo principal:  
[Baixar calculadora](https://github.com/user-attachments/files/27387822/calculadora.html)

---

## 📄 HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Calculadora</title>
  </head>

  <body>
    <script>
      let numero1 = parseInt(prompt("Digite o primeiro número: "))
      let numero2 = parseInt(prompt("Digite o segundo número: "))

      if (isNaN(numero1) || isNaN(numero2)) {
        alert("Você digitou algo errado, volte ao inicio!")
      } else {
        console.log("Número 1: " + numero1)
        console.log("Número 2: " + numero2)

        let resultado = 0

        resultado += numero1 + numero2
        console.log("Adição: " + resultado)

        resultado -= numero1 - numero2
        console.log("Subtração: " + resultado)

        resultado *= numero1 * numero2
        console.log("Multiplicação: " + resultado)

        resultado /= numero1 / numero2
        console.log("Divisão: " + resultado)

        resultado %= numero1 % numero2
        console.log("Resto: " + resultado)

        alert("Você digitou o número correto. Obrigado(a) por usar a calculadora!")
      }
    </script>
  </body>
</html>

---

// Calculadora

let numero1 = parseInt(prompt("Digite o primeiro número: "))
let numero2 = parseInt(prompt("Digite o segundo número: "))

if (isNaN(numero1) || isNaN(numero2)) {
  alert("Você digitou algo errado, volte ao inicio!")
} else {
  console.log("Número 1: " + numero1)
  console.log("Número 2: " + numero2)

  let resultado = 0

  resultado += numero1 + numero2
  console.log("Adição: " + resultado)

  resultado -= numero1 - numero2
  console.log("Subtração: " + resultado)

  resultado *= numero1 * numero2
  console.log("Multiplicação: " + resultado)

  resultado /= numero1 / numero2
  console.log("Divisão: " + resultado)

  resultado %= numero1 % numero2
  console.log("Resto: " + resultado)

  alert("Você digitou o número correto. Obrigado(a) por usar a calculadora!")
}







