# kali-psychic-spoon
Kali Linux Learning Path docs 
Fork a repo
Dans cet article
À propos des duplications (fork)
Prérequis
Duplication d’un dépôt
Clonage de votre dépôt dupliqué
Configuration de Git pour synchroniser votre duplication avec le référentiel en amont
Rechercher un autre dépôt à dupliquer
Étapes suivantes
Une duplication est un nouveau référentiel qui partage le code et les paramètres de visibilité avec le référentiel « en amont » d’origine.
Platform navigation
Mac
Windows
Linux
Tool navigation
GitHub CLI
Desktop
Web browser
À propos des duplications (fork)

Une duplication est un nouveau référentiel qui partage le code et les paramètres de visibilité avec le référentiel « en amont » d’origine. Les duplications sont souvent utilisées pour itérer sur les idées ou les modifications avant qu’elles ne soient proposées à nouveau au référentiel en amont, par exemple dans des projets open source ou lorsqu’un utilisateur n’a pas d’accès en écriture au référentiel en amont. Pour plus d’informations, consultez « Utilisation des duplications ».

Proposer des modifications à apporter au projet d’une autre personne

Par exemple, vous pouvez utiliser des duplications pour proposer des modifications liées à la correction d’un bogue. Au lieu de journaliser un problème pour un bogue que vous avez trouvé, vous pouvez :

Dupliquez (fork) le dépôt.
Appliquer le correctif.
Soumettre une demande de tirage au propriétaire du projet.
Utiliser le projet d’une autre personne comme point de départ de votre propre idée.

Les logiciels open source reposent sur l’idée que le partage de leur code nous permet de les améliorer et de les rendre plus fiables. Pour plus d’informations, consultez « À propos de l’initiative open source » sur le site Open Source Initiative.

Pour plus d’informations sur l’application des principes open source au travail de développement de votre organisation sur GitHub.com, consultez le livre blanc de GitHub intitulé « An introduction to innersource ».

Quand vous créez votre dépôt public à partir d’une duplication du projet d’une autre personne, veillez à inclure un fichier de licence qui détermine la façon dont vous souhaitez que votre projet soit partagé avec d’autres personnes. Pour plus d’informations, consultez la page « Choose an open source license » du site choosealicense.com.

Pour plus d’informations sur l’open source, plus précisément sur la manière de créer et de faire évoluer un projet open source, nous avons créé des Guides Open Source qui vous aideront à promouvoir une communauté open source saine en recommandant des meilleures pratiques pour la création et la gestion des dépôts pour votre projet open source. Vous pouvez également suivre un cours gratuit GitHub Skills sur la maintenance des communautés open source.

Prérequis

Si vous ne l’avez pas encore fait, configurez d’abord Git et l’authentification avec GitHub.com à partir de Git. Pour plus d’informations, consultez « Configurer Git ».

Duplication d’un dépôt

Vous pouvez dupliquer un projet pour proposer des modifications au référentiel en amont. Dans ce cas, une bonne pratique consiste à synchroniser régulièrement votre duplication avec le dépôt en amont. Pour cela, vous avez besoin d’utiliser Git sur la ligne de commande. Vous pouvez vous entraîner à définir le dépôt en amont à l’aide du même dépôt octocat/Spoon-Knife que vous venez de dupliquer (fork).

Sur GitHub.com, accédez au dépôt octocat/Spoon-Knife.
Dans le coin supérieur droit de la page, cliquez sur Dupliquer.
Capture d’écran de la page principale d’un dépôt. Un bouton, étiqueté avec une icône de duplication (fork) et « Fork 59.3k », est encadré en orange foncé.
Sous « Propriétaire », sélectionnez le menu déroulant et cliquez sur un propriétaire pour le dépôt dupliqué.
Par défaut, les duplications ont le même nom que leurs référentiels en amont. Si vous le souhaitez, pour mieux distinguer votre duplication, dans le champ « Nom du dépôt », tapez un nom.
Dans le champ « Description », vous pouvez taper la description de votre duplication.
Si vous le souhaitez, sélectionnez Copier la branche PAR DÉFAUT uniquement.
Dans de nombreux scénarios de duplication, tels que la contribution à des projets open source, vous devez uniquement copier la branche par défaut. Si vous ne sélectionnez pas cette option, toutes les branches sont copiées dans la nouvelle duplication.
Cliquez sur Créer une duplication.
Remarque : si vous souhaitez copier des branches supplémentaires à partir du référentiel en amont, vous pouvez le faire depuis la page Branches. Pour plus d’informations, consultez « Création et suppression de branches dans votre référentiel ».
