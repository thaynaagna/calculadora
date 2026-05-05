# 🧮 Calculadora em HTML + JavaScript

🔗 Arquivo principal:  
[Baixar calculadora](https://github.com/user-attachments/files/27387822/calculadora.html)

---

## 📄 HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Calculadora</title>
</head>

<body>
  <script>
    let numero1 = parseInt(prompt("Digite o primeiro número: "))
    let numero2 = parseInt(prompt("Digite o segundo número: "))

    if (isNaN(numero1) || isNaN(numero2)) {
      alert("Você digitou algo errado, volte ao início!")
    } else {
      console.log("Número 1: " + numero1)
      console.log("Número 2: " + numero2)

      console.log("Adição: " + (numero1 + numero2))
      console.log("Subtração: " + (numero1 - numero2))
      console.log("Multiplicação: " + (numero1 * numero2))

      if (numero2 !== 0) {
        console.log("Divisão: " + (numero1 / numero2))
        console.log("Resto: " + (numero1 % numero2))
      } else {
        console.log("Divisão: não é possível dividir por zero")
        console.log("Resto: não é possível calcular com zero")
      }

      alert("Operações concluídas com sucesso!")
    }
  </script>
</body>
</html>





