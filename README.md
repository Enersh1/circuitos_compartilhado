<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

# Circuitos Lógicos e Digitais 🎛️

*Repositório de estudos para a disciplina de Ciência da Computação*


## 📚 Tópicos Principais
- **Álgebra Booleana**  
  Fundamentos matemáticos para análise de circuitos digitais [^1][^6]
- **Portas Lógicas**  
  AND, OR, NOT, NAND, NOR, XOR e XNOR - Blocos básicos de construção [^4][^9]
- **Simplificação de Circuitos**  
  Técnicas como Mapas de Karnaugh e Álgebra Booleana [^5][^8]



## 🔌 Exemplo de Porta Lógica (AND)


### Porta AND
**Símbolo:**  
![AND Gate](https://example.com/and-gate.png)  
**Tabela Verdade:**  

| Entrada A | Entrada B | Saída |
|-----------|-----------|-------|
| 0         | 0         | 0     |
| 0         | 1         | 0     |
| 1         | 0         | 0     |
| 1         | 1         | 1     |

**Expressão Booleana:**  


Q = A \cdot B



**Aplicação Prática:**  
Circuito detector de presença usando dois sensores [^9][^4]



## 🛠️ Exemplo de Circuito Combinacional


### Meio Somador
**Diagrama:**  


A ----|        |
|  XOR   |---- Soma
B ----|________|

A ----|        |
|  AND   |---- Carry
B ----|________|



**Equações:**  


S = A \oplus B
C = A \cdot B



**Implementação Física:**  
Lista de componentes:
- CI 7408 (AND)
- CI 7486 (XOR)
- Protoboard
- Fios jumpers [^4][^5]



## 📂 Estrutura do Repositório

```bash
.
├── labs/               # Laboratórios práticos
├── simulacoes/         # Arquivos de simulação digital
├── referencias/        # Datasheets e manuais técnicos
├── img/                # Diagramas e fotos de circuitos
└── README.md           # Documentação principal
```


## 💡 Dicas de Estudo


- Use o [Logisim](https://www.cburch.com/logisim/) para simulações
- Revise a folha de dados (datasheet) dos CIs antes de montar circuitos [^4]
- Pratique a conversão entre tabela verdade e expressão booleana [^8]



## 🧩 Exemplo de Exercício


**Problema:**  
Implemente a função `F = (A + B') \cdot (C \oplus D)` usando portas lógicas básicas

**Solução Sugerida:**  
1. Implemente o NOT para B
2. Crie a porta OR com A e B'
3. Faça a porta XOR com C e D
4. Conecte as saídas das etapas 2 e 3 em uma porta AND [^5][^8]


Esta estrutura usa recursos do Markdown como:

- Títulos hierárquicos (`##` e `###`)
- Blocos de código para equações e diagramas
- Tabelas para organização de dados
- Imagens embutidas
- Listas organizadas
- Destaques em **negrito** para termos técnicos
- Links implícitos para arquivos locais[^1][^6]

Para badges e status do projeto, você pode adicionar no topo:


![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow) 
![Licença](https://img.shields.io/badge/Licença-MIT-blue)


<div style="text-align: center">⁂</div>

[^1]: https://ubc-library-rc.github.io/rdm/content/03_create_readme.html

[^2]: https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/

[^3]: https://github.com/othneildrew/Best-README-Template

[^4]: https://professor.luzerna.ifc.edu.br/ricardo-kerschbaumer/wp-content/uploads/sites/43/2021/09/Roteiro-do-experimento-1-de-Sistemas-Digitais-Experimental.pdf

[^5]: https://www.inf.ufes.br/~zegonc/material/Introducao_a_Computacao/Apostila Circuitos e Sistemas Digitais.pdf

[^6]: https://tilburgsciencehub.com/topics/collaborate-share/share-your-work/content-creation/readme-best-practices/

[^7]: https://blog.rocketseat.com.br/como-fazer-um-bom-readme/

[^8]: https://periodicos.set.edu.br/cadernoexatas/article/download/3471/1948/10763

[^9]: https://www.inf.ufes.br/~jssalamon/wp-content/uploads/disciplinas/introcomp/slides/Aula 8 - Noções de circuitos lógicos.pdf

[^10]: https://dev.to/your-ehsan/how-to-easily-create-folder-structure-in-readme-markdown-with-two-simple-steps-3i42

[^11]: https://github.com/iuricode/readme-template

[^12]: https://www.makeareadme.com

[^13]: https://www.readme-templates.com

[^14]: https://github.com/kriasoft/Folder-Structure-Conventions/blob/master/README.md

[^15]: https://readme.so

[^16]: https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

[^17]: https://gitlab.com/kopino4-templates/readme-template

[^18]: https://www.drupal.org/docs/develop/managing-a-drupalorg-theme-module-or-distribution-project/documenting-your-project/readmemd-template

[^19]: https://github.com/GSimas/EEL5105

[^20]: https://www.feis.unesp.br/Home/departamentos/engenhariaeletrica/lab_digitais_01_exp_01_tutorialmax.pdf

[^21]: https://github.com/menotti/ld

[^22]: https://wiki.ifsc.edu.br/mediawiki/index.php/AULA_14_-_Eletrônica_Digital_1_-_Graduação

[^23]: https://www.youtube.com/watch?v=0GzaXbMNB10

[^24]: https://www.researchgate.net/publication/358351576_LOGISIM_FERRAMENTA_PARA_SIMULACAO_DE_CIRCUITOS_COMBINACIONAIS_e_SEQUENCIAIS_DIGITAIS

[^25]: http://www.fem.unicamp.br/~grace/introducao_logicos.pdf

[^26]: https://www.passeidireto.com/arquivo/99385913/circuitos-digitais-atividade-tema-02

[^27]: https://materialpublic.imd.ufrn.br/curso/disciplina/1/17/2/2

[^28]: https://repositorio.ufba.br/bitstream/ri/13988/1/_Eletronica.pdf

[^29]: https://marcielbp.github.io/Circuits/lab/pr03_simulador.html

[^30]: https://www.reddit.com/r/learnprogramming/comments/vxfku6/how_to_write_a_readme/

[^31]: https://www.reddit.com/r/opensource/comments/txl9zq/next_level_readme/

[^32]: https://stackoverflow.com/questions/23989232/is-there-a-way-to-represent-a-directory-tree-in-a-github-readme-md

[^33]: https://www.youtube.com/watch?v=QXKDXoc6YPI

[^34]: https://www.academia.edu/6227222/Conhecendo_Ruby

[^35]: https://www.profelectro.info/simulador-basico-de-circuitos-logicos-sistemas-digitais/

