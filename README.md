# Bem-vindo(a) ao meu perfil do GitHub!

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

#define MAX_TECNOLOGIAS 8

typedef struct {
  int id;
  char *nome;
  char *descricao;
  char **tecnologias;
  char *linkRepo;
} Projeto;

Projeto *criarProjeto(int id, char *nome, char *descricao, char **tecnologias, char *linkRepo) {
  Projeto *p = (Projeto *)malloc(sizeof(struct Projeto));

  p->id = id;
  p->nome = strdup(nome);
  p->descricao = strdup(descricao);

  p->tecnologias = malloc(MAX_TECNOLOGIAS * sizeof(char*));
  for (int i = 0; i < MAX_TECNOLOGIAS; i++) {
    p->tecnologias[i] = ( tecnologias[i] ? strdup(tecnologias[i]) : NULL );
  }

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
Projeto *ocr_grade_report = criarProjeto(
  1,
  "OCR grade report",
  "Algorithm for idetifying grades in a grade report and automating related processes",
  ["PyTesseract", "Python", NULL, NULL, NULL, NULL, NULL, NULL],
  ""
);

Projeto *arch_rice = criarProjeto(
  2,
  "Arch Linux Rice",
  "My first attemp on ricing a linux distro, hope it ends up nice",
  ["Arch", "xorg", "qtile", "rofi", "alacritty", "piwal", "picom", NULL],
  "https://github.com/PH-Vieira/dotfiles"
);
```
