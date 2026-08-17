# LP2 — Exercícios de Linguagem de Programação 2

Repositório com exercícios práticos da disciplina de **Linguagem de Programação 2 (LP2)**, desenvolvidos em **C# / Windows Forms (.NET Framework)**. Cada pasta corresponde a uma atividade avaliativa (ou à prova), contendo um projeto Visual Studio completo compactado em `.zip`.

## 📁 Estrutura do repositório

```
LP2/
├── Atividade1/   Pvolume.zip   – Cálculo de volume de cilindro
├── Atividade2/   Pcalc.zip     – Calculadora básica
├── Atividade3/   PIMC.zip      – Calculadora de IMC
├── Atividade4/   PTriangulos.zip – Classificação de triângulos
├── Atividade5/   PMetodos.zip  – Exercícios de métodos e strings (MDI)
├── Atividade8/   PMatrizes.zip – Vetores, matrizes e ArrayList
└── Prova/        PFilme02.zip  – Avaliação de filmes (prova)
```

Cada pasta contém um `.zip` com a solução do Visual Studio (`.sln` + projeto `.csproj`) e um arquivo `readme` (atualmente vazio, reservado para anotações da atividade).

## 🧩 Descrição das atividades

### Atividade 1 — [`Pvolume`](https://github.com/MGS-BR/LP2/blob/main/Atividade1/Pvolume.zip)
Formulário WinForms que calcula o **volume de um cilindro** a partir do raio e da altura informados pelo usuário, com validação de campos (impede valores não numéricos ou ≤ 0) via eventos `Validated` e `TryParse`.

### Atividade 2 — [`Pcalc`](https://github.com/MGS-BR/LP2/blob/main/Atividade2/Pcalc.zip)
**Calculadora simples** com as quatro operações básicas (soma, subtração, multiplicação e divisão), tratamento de divisão por zero e validação de entradas usando `ErrorProvider`.

### Atividade 3 — [`PIMC`](https://github.com/MGS-BR/LP2/blob/main/Atividade3/PIMC.zip)
Calculadora de **Índice de Massa Corporal (IMC)**: valida peso e altura, calcula o IMC e classifica o resultado (Magreza, Normal, Sobrepeso, Obesidade, Obesidade Grave).

### Atividade 4 — [`PTriangulos`](https://github.com/MGS-BR/LP2/blob/main/Atividade4/PTriangulos.zip)
Verifica se três lados informados formam um **triângulo válido** (desigualdade triangular) e classifica o triângulo em Equilátero, Isósceles ou Escaleno.

### Atividade 5 — [`PMetodos`](https://github.com/MGS-BR/LP2/blob/main/Atividade5/PMetodos.zip)
Aplicação **MDI (Multiple Document Interface)** com um formulário principal e menu que abre sub-formulários (`FrnExercicio2` a `FrnExercicio5`), cobrindo:
- Comparação e manipulação de strings (`Insert`, `Replace`);
- Inversão de string com `Array.Reverse`;
- Contagem de números, letras e espaços em branco em um texto;
- Sorteio de número aleatório dentro de um intervalo (`Random`).

### Atividade 8 — [`PMatrizes`](https://github.com/MGS-BR/LP2/blob/main/Atividade8/PMatrizes.zip)
Exercícios com **vetores, matrizes multidimensionais e `ArrayList`**, usando `Interaction.InputBox` (Microsoft.VisualBasic) para entrada de dados:
- Preenchimento e inversão de um vetor de 20 posições;
- Remoção de item de uma `ArrayList` de nomes;
- Matriz de notas (20 alunos × 3 notas) com cálculo de médias;
- Contagem de caracteres em nomes digitados (`frmExercicio4`);
- Correção de gabarito de prova comparando respostas de 3 alunos × 10 questões (`frmExercicio5`).

### Prova — [`PFilme02`](https://github.com/MGS-BR/LP2/blob/main/Prova/PFilme02.zip)
Exercício avaliativo (prova): coleta notas de **2 pessoas para 2 filmes** (matriz 2×2) com validação de intervalo (0–10) e calcula a média de avaliação de cada filme.

## 🛠️ Tecnologias

- **Linguagem:** C#
- **Framework:** .NET Framework 4.7.2 / 4.8
- **UI:** Windows Forms (WinForms)
- **IDE:** Visual Studio
- Uso pontual de `Microsoft.VisualBasic.Interaction.InputBox` para entrada rápida de dados em algumas atividades

## ▶️ Como executar

1. Extraia o `.zip` da atividade desejada.
2. Abra o arquivo `.sln` no **Visual Studio** (2019 ou superior recomendado).
3. Restaure/compile o projeto (`Ctrl+Shift+B`).
4. Execute com `F5`.

> ⚠️ Os projetos são baseados em .NET Framework (WinForms clássico), portanto exigem Windows + Visual Studio com a carga de trabalho "Desenvolvimento para desktop com .NET" instalada. Não são compatíveis nativamente com .NET (Core) multiplataforma.
