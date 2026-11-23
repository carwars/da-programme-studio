# Discipline Athletic — Programme Studio V1.3

Application HTML/CSS/JavaScript autonome (le mannequin 3D nécessite l’accès au CDN Three.js).

- Formulaire initialisé à blanc à **chaque ouverture** ; les données ne sont pas stockées automatiquement.
- Placeholder bénéficiaire : « Ex. Eric ».
- Objectifs à sélection multiple.
- Consignes du coach rattachées au bloc musculation, séparées des exercices et du bloc cardio dans les exports texte et PNG.
- Cardio visible en fin de séance avec grand cœur rouge.
- Export/import JSON, PNG, texte et impression conservés.

Pour conserver un programme entre deux visites, utilisez **Sauvegarder JSON**, puis **Importer JSON** lors d’une autre ouverture.

Correctif : les objectifs et les groupes musculaires sont renvoyés à la ligne dans le PNG ; durée sur une ligne dédiée et hauteur recalculée.

## V1.5 — contrôle des exports et puces

- Contrôle des champs obligatoires avant PNG, JSON, copie, partage et impression.
- Les lignes vides facultatives d'exercice sont ignorées. Une durée de cardio de 0 minute reste valide.
- Retours à la ligne des consignes conservés dans les récapitulatifs : puces dans le PNG et dans le texte copié.
- L'import JSON reste disponible même quand le formulaire est vide.
