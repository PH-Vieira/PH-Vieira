# Bem-vindo(a) ao meu perfil do GitHub!

```c
#include <stdio.h>

int main() {
  char nome[] = "Pedro Henrique Vieira";
  char ocupacao[] = "Desenvolvedor full-stack";
  char *linguagens[] = {"C", "C#", "C++", "Python", "JavaScript", "PHP", "Java"};
  char *interesses[] = {"IA", "Automacao", "Linux", "Matematica", "Estatistica"};

  void abrirLinkedIn() {
    printf("[LinkedIn](https://www.linkedin.com/in/pedro-henrique-vieira-2426a31b7/)");
  }

  void abrirInstagram() {
    printf("[Instagram](https://www.instagram.com/dompedro_terceiro/)");
  }

  void abrirFacebook() {
    printf("[Facebook](https://www.facebook.com/profile.php?id=100070832881630)");
  }

  // <a href="https://www.linkedin.com/in/pedro-henrique-vieira-2426a31b7/">abrirLinkedIn();</a>
  abrirInstagram();
  abrirFacebook();

  return 0;
}
