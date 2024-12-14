## Activitat 1. Desenvolupament col·laboratiu
Joan i Miquel són dos desenvolupadors del mateix projecte de programari. Tot i que cadascú treballa unes funcionalitats concretes d'una aplicació, han de treballar amb el mateix codi font. Quins mecanismes i quin procediment creus que seria més convenient utilitzar a la seva feina diària?

Descriu en un fitxer en format markdown els mecanismes que utilitzaries, justificant el tipus, així com el procediment detallat de les operacions que haurien de fer cada vegada que van a treballar amb el projecte.

- Per al proyecye de Joan i Miquel el mecanisme que deurien gastar es el control de versions amb Git, els motius son; seguretat, no afectar a la branca principal i descentralizació, cadascú te una copia en local del repositori del proyecte. Secundant Git amb una plataforma de col·laboració gráfica com GitHub, els motius son; repositori remot, per a tindre accés en quasevol moment i integració contínua.

El procediment sería el següent:
1. Crear i inicialitzar en repositori del proyecte
```
$ git init
```

2. Creació del contingut
Dins del proyecte, se afegixen tots els fitxers i fer el commit-
```
$ git add .
$ git commit -m "texto descriptiu del commmit"

```
Para ver el estado de los archivos del proyecto
```
$ git status
```
Para ver los cambios realizados 
```
$ git log
$ git log --oneline
```
Pujar els canvis al repositori remot

3. Enviant el commit al servidor
```
git push origin main
```

## Activitat 2. Control de versions i model iteratiu
Un equip de desenvolupadors ha decidit abordar un projecte seguint un model de desenvolupament iteratiu i incremental. A la planificació inicial, s'ha decidit que s'abordarà en cinc fases, i cadascuna tindrà com a resultat una versió del producte amb la funcionalitat corresponent a cada iteració.

Per al desenvolupament i treball en equip utilitzaran el SCV Subversion.

Quina estructura o organització creus que seria més interessant per a l'equip al repositori?

Revisa els exemples realitzats sobre Subversion, i les carpetes que aquest SCV suggereix que es facen servi, i redacta la teua proposta d'estructura/organització en un document en format Markdown.