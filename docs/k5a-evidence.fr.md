# K5A Zone — preuves publiques et vérification

[English](k5a-evidence.md) · Français

**Sources consultées le 25 novembre 2026 (Europe/Zurich).** Cette page présente ce qu'un visiteur peut vérifier lui-même et comment tester le crédit d'activité. Elle ne revendique pas d'audit indépendant des soldes privés.

## Sources publiques consultables

| Source | Ce qu'un évaluateur peut vérifier | Limite |
| --- | --- | --- |
| [Site KOM-5A](https://kom-5a.com/) et [présentation de K5A](https://kom-5a.com/about) | L'accès public au produit et la description publiée de K5A comme unité interne de participation et de service | Les déclarations du projet n'auditent pas le registre des récompenses |
| [Conditions des services K5A](https://kom-5a.com/service-terms?lang=en) | Les conditions publiées, dont celles de Publication Boost, les devis, l'éligibilité et les limites des résultats promis | Les conditions ne prouvent pas qu'un compte précis a reçu une récompense ou un service |
| [Démonstration Web datée](demo.md) et [fiche App Store officielle](https://apps.apple.com/ch/app/kom-5a/id6756894425) | Des accès publics au produit et à l'application | Elles ne démontrent pas le registre privé des récompenses K5A |
| [Contrat de test Polygon Amoy](https://amoy.polygonscan.com/address/0x382c77b6646e7aef5650f0465b7b8e71697dcb79#code) et [code vérifié](https://sourcify.dev/server/v2/contract/80002/0x382c77b6646e7aef5650f0465b7b8e71697dcb79?fields=sources,creationMatch,runtimeMatch) | Un prototype ERC-20 déployé sur un réseau de test, dont le code est consultable | Ce n'est ni un lancement sur le réseau principal, ni un audit de sécurité, ni une preuve de synchronisation avec les soldes de l'application |

## Test privé et portée des preuves

Le projet a fourni des captures de la K5A Zone en test privé pour examen. Elles ne sont **pas publiées** ici car elles contiennent des informations de compte privées. Une capture seule ne permet pas d'établir indépendamment l'exactitude du registre serveur ni de montrer qu'une récompense de l'application est arrivée dans un portefeuille blockchain.

Une démonstration publique plus solide nécessite un **compte de démonstration sans données personnelles**, un enregistrement daté avant et après l'action, un export CSV de l'activité et un rapprochement entre identifiants d'événement, montants et soldes. Un évaluateur doit pouvoir refaire les mêmes étapes.

## Protocole de vérification reproductible

1. Relever le solde K5A initial d'un compte de démonstration, l'heure et la dernière entrée d'activité.
2. Effectuer une action admissible ou démarrer une session de récompense disponible. Relever l'identifiant et l'heure de l'action.
3. Comparer le nouveau solde, l'écriture d'activité et l'avancement de la session.
4. Exporter le CSV du compte. Rapprocher ses écritures du solde affiché et vérifier qu'une même action n'a pas été créditée deux fois.
5. Pour une revue plus poussée, comparer les événements exportés à un extrait contrôlé du registre serveur. Ne publier que des éléments dépersonnalisés et la méthode de rapprochement.

**État de la blockchain :** la synchronisation entre l'application et Amoy **n'est pas active au 25 novembre 2026**. Aucune transaction sur la chaîne n'est donc attendue aujourd'hui pour une récompense d'activité. Quand un pilote sera actif, son hash de transaction et ses règles de rapprochement pourront être ajoutés à cette page.

[Comprendre la K5A Zone](k5a.fr.md) · [Rejoindre KOM-5A](https://kom-5a.com/register) · [Demander une démonstration ciblée](https://kom-5a.com/contact)
