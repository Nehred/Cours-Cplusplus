# COURS C++
## HISTOIRE
**Bjarne Stroustrup**, pour sa thèse de doctorat lui vient l'idée de créer un
nouveau language. Inspiré de la programmation orientée objet du language **_Simula_**
arrive donc **_C with classes_** qui deviendra plus tard **_C++_**. *1985*,
**_C++_** devient un produit commercial et est normalisé en *1998* sous la norme:
**_ISO/CEI 14882:1998_**.
<br/>**_C++_** continue d'être mis à jour, la dernière norme datant de *2017*:
**_ISO/CEI 14882:2017_**, ou **_C++17_**.

Plus de détails sur [cpluplus.com](http://www.cplusplus.com/info/history/)<br/>

## USAGE
### JEUX VIDÉOS
## SYNTAXE
Exemple de syntaxe:
```c++
#include <iostream>
using namespace std;

int main()
{
  cout << "Hello world!\n";
  return 0;
}
```

**Header:**
```c++
#include <iostream>
```
C++ offre différents headers, chacun contenant les informations nécessaires à votre programme pour bien fonctionner.
<br/>Le **#** cible le pré-processeur du compilateur pour inclure le header <iostream>.

**Namespace (espace de noms):**
```c++
using namespace std;
```
**std** inclus les fonctionnalités de la bibliothèque standard du **C++**.

**Fonction:**
```c++
int main()
{
  cout << "Hello world!\n";
  return 0;
}
```
Le point de démarrage est `main()` peu importe le programme.
<br/>`cout` *print* `Hello World`.
<br/>`return 0` termine `main()`.

## TP
1. Créer un fichier: `<nomdufichier>.cpp`
2. Écrire le code.
3. Ouvrir le terminal et se rendre dans le dossier où se trouve votre fichier .cpp.
3. Compiler le code avec: `$ g++ hello.cpp`
4. Lancer le programme avec: `$ ./a.out`
> Le **$** n'est pas nécessaire sur Windows.





## LIENS EXTERNES
[stroustrup.com](http://www.stroustrup.com/)<br/>
Wikipédia - [Programmation orientée objet](https://fr.wikipedia.org/wiki/Programmation_orient%C3%A9e_objet)<br/>
Wikipédia - [Simula](https://fr.wikipedia.org/wiki/Simula)<br/>
Wikipédia - [C++](https://fr.wikipedia.org/wiki/C%2B%2B)<br/>
Wikipédia - [Compilateur](https://fr.wikipedia.org/wiki/Compilateur)<br/>
Wikipédia - [Bibliothèque standard du C++](https://fr.wikipedia.org/wiki/Biblioth%C3%A8que_standard_du_C%2B%2B)
