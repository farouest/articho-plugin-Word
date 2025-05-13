Détails techniques
Le mot de passe du fichier est : Vcf8fA50!
- Clef de licence spéciale : 915E15NH91211811R
Cette clef prolonge de 15 jours
- Clef de licence spéciale : ARTICHO2024
Cette clef prolonge de 77 jours si la date courante est en 2023
- Clef de licence spéciale : ARTICHO2025 (existe dans la version modifiée par Wdes)
Cette clef prolonge de 77 jours si la date courante est en 2024
Dans le code il existe des cas spécifiques pour les clients « Capstan » et « Havas »
Le logiciel Articho utilise https://articho.eu/vers.txt pour gérer la dernière version disponible.

Et utilise https://www.timeanddate.com/worldclock/fullscreen.html?n=2 avec l’entête de réponse
« Date » pour en déduire la date / heure au moment de la licence.
Re-construction du logiciel Articho.eu

Il y a un logiciel qui est utilisé pour protéger le code source du vol. Il y avait un mot de passe, mais j’ai simplement utilisé le
mot de passe le plus commun de Mr Bidault. Ce qui m’a permis de constater que le code source du
logiciel est désormais modifiable. Pour prouver cela j’ai fait une modification de la version du
logiciel et ajouté un nouveau code d’activation « ARTICHO2025 ».
Une fois le programme compilé et signé, j’ai vérifié qu’il était bien protégé. Ensuite il suffit de
lancer la recette Innosetup et de changer la version du logiciel dans la recette.
Le fichier fourni est un installeur pour Windows. La dernière étape est de signer ce fichier avec «
DigiCertUtil ».
