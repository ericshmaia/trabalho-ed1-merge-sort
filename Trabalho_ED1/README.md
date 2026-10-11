# Trabalho Prático: Algoritmos de Busca e Ordenação
**Professora:** Rosana Rego | PEX1241 - Algoritmos e Estrutura de Dados I  
**Instituição:** Bacharelado Interdisciplinar em Tecnologia da Informação - UFERSA  

**Dupla:** Danilo de Oliveira Nunes e Eric Maia Carlos  
**Algoritmo:** Merge Sort 

---

### Projeto
O projeto consiste em um simulador interativo desenvolvido em linguagem C com a biblioteca gráfica Raylib, aplicando os seguintes tópicos estudados na disciplina:

*   **Tipos Estruturados:** `struct` para a representação e renderização das barras.
*   **União de Dados:** `union` para o armazenamento otimizado de metadados.
*   **Enumerações:** `enum` para o controle preciso da máquina de estados do simulador.
*   **Manipulação de Arquivos:** Leitura dinâmica de dados a partir do arquivo `dados.txt`.

---

### Controles do Simulador
*   `[I]` **Iniciar / Continuar:** Ativa a ordenação automática contínua.
*   `[P]` **Pausar:** Congela o estado atual das variáveis e barras.
*   `[R]` **Reiniciar:** Recarrega o arquivo `dados.txt` e reseta os contadores.
*   `[N]` **Próximo Passo:** Avança apenas um frame/iteração por clique (modo manual).

---

### Como Compilar e Executar (Windows)
Para compilar o simulador com a correta linkagem da biblioteca Raylib, abra o terminal no VS Code e digite o comando abaixo:

```bash
g++ trabalho_ed1.c -o trabalho_ed1.exe -lraylib -lopengl32 -lgdi32 -lwinmm
```

Após a compilação, execute o programa com:
```bash
./trabaho_ed1.exe
```
