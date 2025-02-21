# Circuitos Lógicos e Digitais 🎛️

*Repositório de estudos para a disciplina, por alunos do 2° périodo de Ciência da Computação*

# Disclaimer: 
- Todo os conteúdos presentes devem ser revisados e são passíveis de conter erros
- Não copiar as resoluções caso elas estejam contidas nos arquivos, use apenas como material de estudo, copiar e usar como de sua autoria estará sujeito a paulada.

## 📚 Aula 21/02/2025
  **Conceito, Funcionalidade e construção dos circuitos a seguir:**
- Complemento de 2  
- Subtrator

# Importante:
  Saber converter decimal para binário
    Saber achar o negativo de um número binário com [Complemento de 2]
      Saber somar números binários
        A partir da soma, somar um número positivo com negativo resulta em uma subtração = [Subtrator]

## 📚 [Complemento de 2]
 **Conceito**
 O Complemento de 2 é uma técnica usada para representar números inteiros com sinal em binário, amplamente utilizada em sistemas computacionais.
- Definição: O Complemento de 2 de um número é obtido invertendo todos os bits do número original e adicionando 1 ao resultado.
- Representação de Números: Números positivos são representados em binário direto, enquanto números negativos são representados pelo Complemento de 2, com o bit mais significativo sendo 1.
- Cálculo:
  1°: Inverter todos os bits
  2°: somar 1 bit
  Exemplo: 3₍₁₀₎ = 0011₍₂₎
  1°: 1100
  2°: 1100 + 0001 = 1101
    Usos:
  - É fundamental em sistemas computacionais para realizar operações aritméticas com números inteiros com sinal
  - **Obter o valor negativo de um número binário**

## 🔌 Exemplo de circuito [Complemento de 2]
![image](https://github.com/user-attachments/assets/56e83dfd-c377-4a82-b168-5a0666177796)

## 📚 Subtrator
- É uma soma utilizando valor negativo, para possibilitar a subtração de valores binários, obtido através do [Complemento de 2]

## 🔌 Exemplo de circuito [Subtrator]
![image](https://github.com/user-attachments/assets/ad1158f2-608e-4d7d-a3f7-de51ec8f6617)

![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow) 
![Licença](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.pt_BR)

📄 **Licenciamento**  
Este material está licenciado sob [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.pt_BR). Você pode:  
- Compartilhar o conteúdo **sem alterações**  
- Usar para fins **não comerciais** (ex: estudo individual, aulas)  

❌ **Não permitido**:  
- Copiar trechos inteiros de respostas  
- Modificar/adaptar imagens técnicas  
- Usar em plataformas pagas ou com fins lucrativos  

Atribuição obrigatória:  
`Material adaptado de [SeuNome/Repositório] (GitHub)`.


