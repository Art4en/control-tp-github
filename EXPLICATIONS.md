ethan portero

					control tp note git/github


Pour commencer j’ai vérifié que c'était mon bon mail qui allait envoyer les commits et vérifier le pseudo qui était mis en faisant ces deux commandes .

>>git config user.name
art4en
>> git config user.email
ethan06042007@gmail.com

l’objectif est ensuite de faire le commit de A et de B sur le main
>>git branch A
>>git branch B

ensuite pour renommer la branche A je fais >>git branch -m dark
git branch -m application

en suite pour changer la couleur du fond dans root je vais changer la couleur par celle demande donc #17223b et pour le texte pareil #ffffff .

je verifie que tout est bon je me met bien sur la branche A et je commit

git add style.css
git commit -m "Passe le thème en sombre : fond et couleur du texte"
git log --oneline -3

(je précise que j’ai utiliser l’ia qui me permet de m’aider pour bien me situer et dans qu’elle ordre allez et il ne peut pas me donner le code car c’est un tp donc utilisation pour la compréhension )

apres je repasse sur la branche B je fais les changement demande et une fois fini je commit de la meme facon que pour A (A est devenue dark et B est devenue application mais je reste sur a et b pour que se soit plus simple sur le rendu)
une fois fini je dois fusionner les deux branche.



ensuite pour hotfix je fais ces 3 commande 
git switch main
git switch -c hotfix ( créer la branche et me mène dessus -hotflix)
git branch --show-current (vérifie sur quelle branche je suis)

 j’ai ensuite remplacer pour que sur le fond sombre la confirmation soit visible en modifiant le .receipt .receipt { color: var(--page-text); font-weight: bold; padding: 12px 0; }

ensuite pareil ont fais pareil un commit suivi d’une merge entre hotflix et le main pour tout assembler



je fais un depot sur github git remote add origin https://github.com/Art4en/control-tp-github.git
