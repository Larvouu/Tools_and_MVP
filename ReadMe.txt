ok branche 1

Un pull est d�conseill� quand y'a plusieurs branches. On conseille merge + fetsh

pour merge la branche 1 avec la branche master :

git checkout master
git merge branche1

ok

pour régler un conflict, on essaye de merge, si ça passe pas ca affiche 
<<<< head

===

>>> income

On conserve ce qu'on veut là dedans puis on add/status/commit
Puis le merge marche tranquille