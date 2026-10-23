# WYS — Politique de confidentialité

WYS est édité sous le nom **Otter Appworks**. Son exploitant légal est **Alexandre Wyer**, entrepreneur individuel en Suisse, également responsable des informations volontairement fournies à l’assistance. Cette politique couvre les éditions Mac App Store, iPhone et iPad. Les particularités sont précisées par plateforme. [English version](https://github.com/elzuzu/wys-feedback/blob/main/PRIVACY.md).

Dernière mise à jour : 23 octobre 2026

## Édition iPhone et iPad

WYS transcrit les fichiers audio et vidéo sur l’appareil avec un modèle Parakeet livré dans l’app. Aucun enregistrement, transcription, statistique d’usage ou donnée d’entraînement ne nous est envoyé. Il n’y a ni compte, publicité, SDK d’analyse, transcription cloud, ni téléchargement de modèle vocal. Cette édition importe les fichiers ; elle n’enregistre ni le micro ni les sons du système, n’identifie pas les locuteurs et n’utilise pas Apple Intelligence.

Quand vous choisissez un fichier dans Fichiers, le système ou son fournisseur peut d’abord le télécharger depuis l’emplacement choisi, par exemple iCloud Drive. WYS copie ce fichier dans son dossier privé Application Support/Imports afin que la lecture ne dépende pas de l’original. Elle conserve aussi le texte et ses horodatages, la langue audio, des signets locaux minimaux, le temps d’essai utilisé et la décision versionnée sur les conditions. Elle ne lit pas les autres fichiers et ne demande pas d’accès aux photos, contacts, calendrier, localisation ou micro. Les originaux choisis dans Fichiers restent à vous et ne sont pas supprimés par WYS.

Ces données locales peuvent faire partie des sauvegardes du système, y compris iCloud si vous l’activez. Apple et les fournisseurs de fichiers ou de sauvegarde choisis appliquent leurs propres politiques ; WYS n’exploite aucun stockage cloud et ne déclenche aucun envoi distinct. Gardez des copies indépendantes. Supprimer ou réinstaller l’app peut effacer bibliothèque locale, copies importées, réglages, compteur d’essai et décision sur les conditions ; l’essai n’est pas un quota synchronisé entre appareils. Les droits d’achat Apple se restaurent séparément par StoreKit.

Vous pouvez copier le texte ou le partager/exporter explicitement. WYS écrit une copie d’export temporaire et tente de la retirer quand le partage se termine ou est annulé ; l’app ou le fournisseur destinataire contrôle la copie reçue. Ne partagez pas de contenu confidentiel par inadvertance. Supprimer une transcription retire aussi sa copie importée appartenant à WYS lorsqu’elle est disponible, sans toucher à l’original choisi dans Fichiers. Les Réglages donnent accès aux conditions, à cette politique, aux licences et à l’assistance. Le même achat App Store non consommable débloque la transcription ; Apple gère paiement et vérification, sans communiquer à WYS votre identité de paiement ou carte bancaire. La restauration n’est demandée que lorsque vous touchez « Restaurer les achats ».

L’assistance et les coordonnées sont décrites dans les sections correspondantes plus bas. Les tickets GitHub sont publics : n’y joignez aucun enregistrement ou texte privé. Aucun fichier ni diagnostic n’est envoyé automatiquement. La décision sur les conditions reste locale et ne vaut jamais consentement global aux traitements.

## Édition Mac

Les sections suivantes décrivent l’édition Mac. Dictaphone, dossiers surveillés, Spotlight, relecture contextuelle et résumés ne sont pas proposés par la version iPhone/iPad 1.0.

## En bref

WYS transcrit vos fichiers audio et vidéo **sur votre Mac**. L'app ne collecte aucune donnée vous concernant, ne vous suit pas et n'envoie ni votre audio, ni vos textes, ni des statistiques d'usage à qui que ce soit.

- L'app ne demande aucun accès au réseau et n'a pas de compte : rien n'est à créer ni à connecter.
- Les modèles de reconnaissance sont livrés dans l'app : rien n'est téléchargé, jamais.
- Aucun SDK d'analyse, de publicité ou de mesure.

## Ce que WYS conserve sur votre Mac

Dans le **conteneur** de l'app, un dossier que macOS crée pour elle dans `~/Library/Containers/com.elzuzu.wys/` :

- vos **transcriptions** (texte d'origine, corrections, locuteurs, marqueurs, alertes) et les **résumés et traductions** que vous avez demandés, avec les **noms, termes et description** saisis pour la seconde lecture avec le contexte ;
- les **enregistrements** faits avec le dictaphone et par la dictée, qui appartiennent à l'app (l'enregistrement d'un appel ou d'une réunion peut contenir la voix d'autres personnes ; il reste sur ce Mac, dans le conteneur) ;
- un **index de recherche** (copie du texte, reconstruite à la demande) ;
- vos **dossiers**, **passages favoris**, **règles de texte** et **invites de résumé** (ce que vous avez saisi, gardé dans de simples fichiers), et les réglages de l'**export automatique**, avec un signet vers le dossier d'export que vous avez choisi ;
- vos **réglages** (langue de l'audio, modèle, dossiers surveillés), la **durée de transcription gratuite déjà utilisée** et des **signets** qui permettent de rouvrir les fichiers et dossiers que vous avez choisis.

WYS ne copie pas vos fichiers audio ou vidéo importés : il garde un signet vers l'original (seule exception : un fichier que l'app Raccourcis remet sans emplacement est copié dans le conteneur le temps de la transcription, puis supprimé). Si vous déplacez ou supprimez l'original, la lecture n'est plus possible, le texte reste. Pendant la transcription d'un fichier avec l'identification des locuteurs, WYS écrit une copie décodée temporaire de son audio dans le conteneur (environ 460 Mo pour deux heures) ; elle est supprimée à la fin de la transcription, et toute copie laissée par un plantage est supprimée au lancement suivant. Les actions Raccourcis de WYS (obtenir le texte d'une transcription, l'ouvrir, chercher) remettent le texte des transcriptions que vous choisissez à l'app Raccourcis de votre Mac, que vous contrôlez ; WYS lui-même n'envoie rien nulle part.

## Ce que WYS demande au système

- **Fichiers** : l'accès aux fichiers et dossiers que vous choisissez vous-même (panneau d'ouverture, glisser-déposer, dossiers surveillés).
- **Micro** : uniquement pour le dictaphone et la dictée (par le menu Fichier ou par un raccourci facultatif), après l'invite du système. Transcrire un fichier n'exige pas le micro.
- **Sons du système** : uniquement quand vous choisissez Sons du système ou Les deux dans le dictaphone, après l'invite du système (« Enregistrement des sons du système »). WYS n'enregistre le son que joue le Mac que pendant un enregistrement, et jamais l'écran.
- Aucun accès au calendrier, aux contacts, à la localisation, aux photos ni à l'image de l'écran.

## Traitement

La transcription et l'identification des locuteurs sont faites par des modèles **livrés dans l'app** et exécutés sur votre Mac. Les résumés, les traductions et les suggestions de la seconde lecture avec le contexte (*Transcription › Relire avec le contexte…*) sur les mots faux, quand vous les demandez, sont faits par le modèle de langage d'Apple intégré à macOS 26 ou plus récent (Apple Intelligence), lui aussi exécuté sur votre Mac d'après la documentation d'Apple : WYS n'envoie votre texte à aucun service d'intelligence artificielle distant. Un résumé ou une traduction est produit par un modèle de langage et peut se tromper : vérifiez les noms, les nombres et les négations avec l'enregistrement. Pour la seconde lecture, WYS vérifie lui-même les noms, termes et graphies, sur votre Mac, sans modèle ; les noms et termes que vous saisissez et votre courte description sont enregistrés avec la transcription sur votre Mac et, quand le modèle sur l'appareil est disponible, lui sont transmis avec le texte de la transcription pour proposer de corriger des mots faux. La seconde lecture n'applique d'office que les corrections qu'elle peut justifier (vos noms et termes, les graphies employées ailleurs dans le texte), dans une nouvelle version que vous pouvez relire, refuser ou annuler ; la transcription d'origine n'est jamais écrasée, et les suggestions sur des mots faux ne s'appliquent que si vous les acceptez.

## Fonctions facultatives qui écrivent hors de l'app

Toutes sont désactivées tant que vous ne les activez pas ou ne choisissez pas un dossier. Rien dans cette section n'envoie quoi que ce soit sur le réseau.

- **Spotlight** (*Réglages › Spotlight*) : le titre et le texte de chaque transcription terminée sont confiés à l'index Spotlight de votre Mac (Core Spotlight d'Apple, sur ce Mac seulement), pour retrouver une transcription de n'importe où. Désactiver l'option les retire tous ; supprimer une transcription retire son entrée.
- **Tout exporter…** et **Export automatique** (*Réglages › Export automatique…*) : WYS écrit des fichiers (TXT, SRT, DOCX et les autres formats que vous choisissez) uniquement dans le dossier que vous avez choisi, avec un signet qui lui permet d'y écrire de nouveau. Aucun fichier existant n'est écrasé.
- **Services** (*Services › Transcrire avec WYS* dans le Finder) : le système remet à WYS les fichiers audio ou vidéo sélectionnés, comme un dépôt sur l'icône du Dock.

## Achats

WYS se télécharge gratuitement et inclut 60 minutes de transcription gratuite. Un achat intégré unique débloque la transcription sans limite. Les achats sont traités par l'App Store : WYS ne reçoit ni votre identité de paiement ni vos coordonnées de facturation. « Restaurer les achats » se trouve dans le menu WYS.

## Vos droits et votre contrôle

- **Supprimer une transcription** depuis la bibliothèque, à tout moment. Si elle provient d'un enregistrement fait avec WYS, l'enregistrement est supprimé avec elle (l'app vous prévient avant). Les fichiers que vous avez importés ne sont jamais supprimés par l'app.
- **Supprimer un résumé ou une traduction** depuis la fenêtre Résumés et traductions.
- **Ne plus surveiller un dossier** en le retirant dans les Réglages. **Désactiver le raccourci de dictée**, **Spotlight** et **l'Export automatique** dans les Réglages.
- **Retirer l'accès au micro** à tout moment dans Réglages Système › Confidentialité et sécurité › Micro, et **l'accès aux sons du système** dans Réglages Système › Confidentialité et sécurité › Enregistrement de l'écran et des sons du système.
- **Tout supprimer** : supprimez vos transcriptions dans la bibliothèque, quittez et supprimez l'app, puis supprimez son dossier conteneur (`~/Library/Containers/com.elzuzu.wys/`) ; macOS ne le retire pas automatiquement quand on supprime une app.
- WYS ne détient aucun compte ni aucune donnée vous concernant hors de votre Mac : il n'y a donc rien à nous demander ; rien n'est partagé avec personne.

## Enfants

WYS ne collecte aucune donnée, y compris auprès des enfants.

## Modifications

Toute modification de cette politique est consignée dans ce dépôt public, avec sa date.

## Assistance

*Aide › Contacter l'assistance…* ouvre la page de support publique (GitHub) dans votre navigateur : c'est une action du système, WYS n'envoie rien lui-même. Si vous y ouvrez un ticket, ce que vous écrivez est public et traité par GitHub selon sa propre politique de confidentialité : ne publiez ni enregistrement, ni transcription, ni information personnelle. WYS n'ajoute jamais de journal ni de fichier de lui-même.

## Contact

Questions ou demandes relatives à la vie privée : **wys@elzuzu.ch.eu.org**. Bugs et suggestions : https://github.com/elzuzu/wys-feedback (les tickets sont publics : ne publiez ni enregistrement, ni transcription, ni information personnelle).

## Décision sur les conditions au premier lancement

Les versions qui affichent les conditions au premier lancement conservent la décision **uniquement sur votre Mac** : accord ou poursuite sous la licence existante, révision et empreintes des conditions intégrales, langue de ces conditions, date, version/build et édition de l’app, ainsi qu’une copie du texte affiché. Ouvrir ou fermer l’écran n’enregistre aucun accord. Continuer sous la licence existante est enregistré séparément et ne vaut jamais acceptation. Nous ne recevons pas ce reçu et ne le joignons pas automatiquement aux rapports. Il ne contient aucun compte client, identifiant matériel, enregistrement, nom de fichier ou chemin personnel. Vos propres sauvegardes peuvent l’inclure. Effacer les préférences/le conteneur de l’app supprime ce reçu et l’écran réapparaît. Ce n’est ni une authentification d’identité ni un consentement global aux traitements.
