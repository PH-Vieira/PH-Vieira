# Bem-vindo(a)

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=PH-Vieira&show_icons=true&theme=ocean_dark&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=PH-Vieira&theme=ocean_dark)](https://github.com/anuraghazra/github-readme-stats)

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=PH_Vieira&theme=ocean_dark)](https://github.com/anuraghazra/github-readme-stats)

Índice
======
  * [Minhas informações](#Minhas_informações)
  * [Projetos](#Projetos)
  * [Meus wallpapers favoritos](#Meus_wallpapers_favoritos)
  * [Músicas favoritas](#Músicas_favoritas)

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
 * [Índice](#Índice)

Minhas_informações
==================

```c
char nome[] = "Pedro Henrique Vieira";
char ocupacao[] = "Desenvolvedor full-stack";
char *linguagens[] = {"C", "C#", "C++", "Python", "JavaScript", "PHP", "Java"};
char *interesses[] = {"IA", "Automacao", "Linux", "Matematica", "Estatistica"};
```
 * [Índice](#Índice)

Projetos
========

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
 * [Índice](#Índice)

Meus_wallpapers_favoritos
=========================

![woman and oni wallpaper](https://github.com/PH-Vieira/wallpapers/blob/main/wallhaven-3lgk6y_1920x1080.png)
![dragon under water wallpaper](https://github.com/PH-Vieira/wallpapers/blob/main/wallhaven-gpxxq7_1920x1080.png)
![purple black hole wallpaper](https://github.com/PH-Vieira/wallpapers/blob/main/wallhaven-l8v7kq_1920x1080.png)
Vou adicionar mais algumas aqui logo.
 * [Índice](#Índice)

Músicas_favoritas
=================

![<img src="">](https://open.spotify.com/intl-pt/track/6xGruZOHLs39ZbVccQTuPZ?si=8622868624ed4ad1)

 * [Índice](#Índice)
