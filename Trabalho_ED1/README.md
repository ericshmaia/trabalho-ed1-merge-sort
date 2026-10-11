# Trabalho Prático: Algoritmos de Busca e Ordenação

Professora: Rosana Cibely Rego  
PEX1241 - Algoritmos e Estrutura de dados I  
Bacharelado Interdisciplinar em Tecnologia da Informação - UFERSA  

Componentes: Danilo de Oliveira Nunes e Eric Maia Carlos  
Algoritmo: Merge Sort Iterativo  

---

O projeto consiste em um simulador interativo desenvolvido em linguagem C com a biblioteca gráfica Raylib, aplicando os seguintes tópicos estudados na disciplina:
- Tipos Estruturados (Struct para representação das barras)
- União (Union para armazenamento de metadados)
- Enumerações (Enum para controle dos estados do simulador)
- Manipulação de Arquivos (Leitura de dados a partir do arquivo dados.txt)

---

### Controles do Simulador:
- [I] Iniciar / Continuar a ordenação automática
- [P] Pausar o simulador
- [R] Reiniciar o vetor com os dados do arquivo
- [N] Próximo passo manual (Avança um frame por clique)

---

### Compilando e executando o simulador no terminal do Windows (VS Code)

Para compilar o simulador com a linkagem da biblioteca Raylib, digite o comando abaixo no terminal:

```text
C:\msys64\ucrt64\bin\gcc.exe trabalho_ed1.c -o trabalho_ed1.exe -I C:\msys64\ucrt64\include -L C:\msys64\ucrt64\lib -lraylib -lopengl32 -lgdi32 -lwinmm
```

Para entrar na pasta do projeto e garantir o diretório correto, digite:

```text
cd C:\Prog\Trabalho_ED1
```

Para executar o simulador na sua máquina, digite:

```text
.\trabalho_ed1.exe
```

---

### Significado dos parâmetros utilizados no compilador:
- C:\msys64\ucrt64\bin\gcc.exe: é o caminho direto do compilador do C que transforma o código fonte em um executável.
- -o trabalho_ed1.exe: indica o nome do arquivo executável que será gerado após a compilação.
- -I e -L: indicam ao compilador os caminhos das pastas onde estão guardados os arquivos de inclusão (.h) e as bibliotecas (.lib) da Raylib no MSYS2.
- -lraylib -lopengl32 -lgdi32 -lwinmm: realiza a linkagem das bibliotecas gráficas necessárias para abrir a janela do jogo no Windows.

---

UFERSA - Campus Pau dos Ferros
