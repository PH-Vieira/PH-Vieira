# Bem-vindo(a) ao meu perfil do GitHub!

```c
#include <stdio.h>
#include <string.h>

typedef struct {
  int id;
  char *nome;
  char *descricao;
  char *tecnologias;
  char *linkRepo;
} Projeto;

Projeto *criarProjeto(int id, char *nome, char *descricao, char *tecnologias, char *linkRepo) {
  Projeto *p = malloc(sizeof(struct Projeto));

  p->id = id;
  p->nome = strdup(nome);
  p->descricao = strdup(descricao);
  p->tecnologias = strdup(tecnologias);
  p->linkRepo = strdup(linkRepo);

  return p;
}

```
# Minhas informações

```c
char nome[] = "Pedro Henrique Vieira";
char ocupacao[] = "Desenvolvedor full-stack";
char *linguagens[] = {"C", "C#", "C++", "Python", "JavaScript", "PHP", "Java"};
char *interesses[] = {"IA", "Automacao", "Linux", "Matematica", "Estatistica"};
```

# Projetos

```c
Projeto *ocr_grade_report = criarProjeto(1, "OCR grade report", "Algorithm for idetifying grades in a grade report and automating related processes", "PyTesseract, Python", "");

```
