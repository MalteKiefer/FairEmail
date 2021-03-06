# Aide de configuration

La configuration de FairEmail est assez simple. Vous devrez ajouter au moins un compte pour recevoir des courriels et au moins une identité si vous voulez envoyer des courriels. La configuration rapide ajoutera un compte et une identité en une seule opération pour la plupart des principaux fournisseurs.

## Pré-requis

Une connexion Internet est nécessaire pour configurer les comptes et les identités.

## Configuration rapide

Entrez simplement votre nom, votre adresse e-mail et votre mot de passe et appuyez sur *Aller*.

Ceci fonctionnera pour la plupart des principaux fournisseurs de messagerie.

Si la configuration rapide ne fonctionne pas, vous devez configurer un compte et une identité d'une autre manière, voir ci-dessous pour les instructions.

## Configuration d'un compte - recevoir des e-mails

Pour ajouter un compte, appuyez sur *Gérer les comptes* et appuyez sur le bouton orange *ajouter* en bas. Sélectionnez un fournisseur dans la liste, entrez le nom d'utilisateur, qui est principalement votre adresse e-mail et entrez votre mot de passe. Appuyez sur *Vérifier* pour permettre à FairEmail de se connecter au serveur de messagerie et de récupérer une liste de dossiers système. Après avoir examiné la sélection des dossiers système, vous pouvez ajouter le compte en appuyant sur *Enregistrer*.

Si votre fournisseur n'est pas dans la liste des fournisseurs, sélectionnez *Personnalisé*. Entrez le nom de domaine, par exemple *gmail.com* et appuyez sur *Obtenir les paramètres*. Si votre fournisseur supporte l'[auto-découverte](https://tools.ietf.org/html/rfc6186), FairEmail remplira le nom d'hôte et le numéro de port, sinon vérifiez les instructions de configuration de votre fournisseur pour le nom d'hôte IMAP, le numéro de port et le protocole (SSL/TLS ou STARTTLS). Pour plus d'informations, veuillez voir [ici](https://github.com/M66B/FairEmail/blob/master/FAQ.md#authorizing-accounts).

## Configuration d'une identité - envoyer des e-mails

De même, pour ajouter une identité, appuyez sur *Gérer les identités* et appuyez sur le bouton orange *ajouter* en bas. Entrez le nom que vous souhaitez voir apparaître dans le champ de: pour les e-mails que vous envoyez et sélectionnez un compte lié. Appuyez sur *Enregistrer* pour ajouter l'identité.

Si le compte a été configuré manuellement, vous devez probablement configurer l'identité également manuellement. Entrez le nom de domaine, par exemple *gmail.com* et appuyez sur *Obtenir les paramètres*. Si votre fournisseur supporte l'[auto-découverte](https://tools.ietf.org/html/rfc6186), FairEmail remplira le nom d'hôte et le numéro de port, sinon vérifiez les instructions de configuration de votre fournisseur pour le nom d'hôte IMAP, le numéro de port et le protocole (SSL/TLS ou STARTTLS).

Voir [cette FAQ](https://github.com/M66B/FairEmail/blob/master/FAQ.md#FAQ9) sur l'utilisation des alias.

## Accorder les permissions - accéder aux informations de contact

Si vous souhaitez rechercher des adresses e-mail, avoir les photos de contact affichées, etc, vous devez accorder la permission de lire les contacts à FairEmail. Appuyez simplement sur *Accorder les autorisations* et sélectionnez *Autoriser*.

## Configurer les optimisations de batterie - recevoir des e-mails en continu

Sur les versions récentes d'Android, Android mettra les applications en veille lorsque l'écran est éteint pendant un certain temps pour réduire l'utilisation de la batterie. Si vous souhaitez recevoir de nouveaux courriels sans retard, vous devez désactiver les optimisations de batterie pour FairEmail. Appuyez sur *Désactiver les optimisations de batterie* et suivez les instructions.

## Questions ou problèmes

Si vous avez une question ou un problème, veuillez [voir ici](https://github.com/M66B/FairEmail/blob/master/FAQ.md) pour obtenir de l'aide.