Différence entre git reset et git revert :

git revert :

Crée un nouveau commit qui annule les changements
Préserve l'historique complet
Sûr pour les branches partagées
Permet de tracer qui a annulé quoi et quand

git reset :

Supprime le(s) commit(s) de l'historique
Réécrit l'historique Git
Dangereux pour les branches partagées (nécessite un --force)
Peut causer des problèmes pour les collaborateurs

Conclusion : Utilisez git revert pour les branches publiques/partagées, et git reset uniquement pour vos branches locales non poussées.