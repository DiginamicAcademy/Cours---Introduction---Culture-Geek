---
marp: true
theme: default
style: |
  section {background-color: #121114}
  h1,h2,h3 {color: #8393f0}
  p,ul,li,td,th {color: #ccc}
  section table td {background-color: #121114}
  section table th {background-color: #272133; font-weight: bolder}
  pre {background-color: #17151a; color: #ccc}
  blockquote {border: 2px green solid; border-left-width: 15px; padding: 0.5em 15px;font-style: italic }
paginate: true
header: "Culture Geek"
footer: "![height:20px](https://raw.githubusercontent.com/DiginamicInternal/PublicAssets/refs/heads/main/Logo-diginamic-color-blk.png)"
---

<center>

![Culture geek](https://github.com/DiginamicAcademy/Cours---Introduction---Culture-Geek/blob/main/res/logo.png?raw=true)

</center>

---

# Programme

1. C'est quoi un ordinateur ?
2. RTFM : la doc, c'est la base
3. L'IA n'est pas votre amie (mais peut le devenir)
4. Le hacking : une histoire de chapeaux
5. Sécurité et hygiène numérique
6. Bonnes pratiques

---

# 1. C'est quoi un ordinateur ?

Qu'est-ce qu'un ordinateur ?

---

# 1. C'est quoi un ordinateur ?

<s>Qu'est-ce qu'un ordinateur ?</s>

Quel est le concept d'ordinateur ?

---

# 1. C'est quoi un ordinateur ?

C'est quoi un concept ?

---

# 1. C'est quoi un ordinateur ?

Un concept, c'est une définition fonctionnelle et factuelle d'une chose.

> Le concept de chaise est "un objet dédié au fait de s'asseoir, avec un dossier, avec ou sans accoudoirs, avec un confort simple".

Le concept ne décrit pas physiquement, il donne une **description factuelle** de la chose qu'on cherche à conceptualiser.

> Conceptualiser c'est penser les caractéristiques sans le décrire visuellement.

---

# 1. C'est quoi un ordinateur ?

Quel est le concept d'un smartphone ?

---

# 1. C'est quoi un ordinateur ?

Quel est le concept d'un smartphone ?

> un appareil mobile de taille réduite (qui tient dans la main) disposant d'un écran tactile, d'un ou plusieurs dispositifs de capture d'images, permettant d'installer et d'utiliser tout type d'application et connecté à internet par un ou plusieurs réseaux sans fil, qui permet de téléphoner et communiquer en mode texte ou vidéo.

Pourquoi est-ce "juste" un téléphone ?

---

# 1. C'est quoi un ordinateur ?

Quel est le concept d'ordinateur ?

---

# 1. C'est quoi un ordinateur ?

Quel est le concept d'ordinateur ?

> Une ou plusieurs unités de calcul, associées à une ou plusieurs interfaces d'entrée-sortie, associées à une ou plusieurs unités de stockage, tout ou partie de ces éléments pouvant être virtuels.

---

# 1. C'est quoi un ordinateur ?

En suivant ce concept 

> Une ou plusieurs unités de calcul, associées à une ou plusieurs interfaces d'entrée-sortie, associées à une ou plusieurs unités de stockage, tout ou partie de ces éléments pouvant être virtuels.

quels objets sont "aussi" des ordinateurs ?

---

# 1. C'est quoi un ordinateur ?

Quels objets sont "aussi" des ordinateurs ?

- le smartphone, la tablette, la montre connectée
- la console de jeu, la box internet, la télé "smart"
- la voiture (plusieurs dizaines de calculateurs !)
- la machine à laver, le frigo connecté, l'ampoule connectée
- la carte bancaire (sa puce est un mini-ordinateur)
- le serveur qui héberge votre site... et qui n'existe peut-être pas physiquement

---

# 1. C'est quoi un ordinateur ?

"tout ou partie de ces éléments pouvant être **virtuels**"

- **Machine virtuelle (VM)** : un ordinateur simulé par un autre ordinateur
- **Conteneur** (Docker...) : un environnement isolé qui partage le noyau de l'hôte
- **Cloud** : des ordinateurs loués à la demande, quelque part dans un datacenter

> Le cloud, c'est juste l'ordinateur de quelqu'un d'autre.

---

# 1. C'est quoi un ordinateur ?

## L'architecture de von Neumann (1945)

Presque tous nos ordinateurs suivent encore ce modèle :

| Élément | Rôle | Exemple |
|---|---|---|
| Unité de calcul | exécute les instructions | CPU, GPU |
| Mémoire vive | stocke ce qui est en cours d'utilisation | RAM |
| Stockage | conserve les données durablement | SSD, disque dur |
| Entrées / sorties | communique avec l'extérieur | clavier, écran, réseau |

Le programme et les données sont stockés **dans la même mémoire**.

---

# 1. C'est quoi un ordinateur ?

## Les unités

| Unité | Valeur (SI) | Valeur (binaire) |
|---|---|---|
| Ko / Kio | 1 000 octets | 1 024 octets |
| Mo / Mio | 1 000 Ko | 1 024 Kio |
| Go / Gio | 1 000 Mo | 1 024 Mio |
| To / Tio | 1 000 Go | 1 024 Gio |

---

# 1. C'est quoi un ordinateur ?

## Les couches

```
  Vous
   │
  Applications        navigateur, IDE, jeux...
   │
  Système d'exploitation (OS)   Windows, macOS, Linux, Android, iOS
   │
  Firmware            BIOS / UEFI
   │
  Matériel            CPU, RAM, stockage, périphériques
```

Chaque couche **cache la complexité** de celle du dessous : c'est l'**abstraction**.

---

# 2. RTFM : la doc, c'est la base

Que veut dire **RTFM** ?

---

# 2. RTFM : la doc, c'est la base

Que veut dire **RTFM** ?

> **R**ead **T**he **F**\*\*\*ing **M**anual

La réponse (pas très polie) qu'on reçoit sur un forum quand la réponse à la question **est dans la documentation**.

Le message derrière : **cherchez d'abord par vous-même**.

---

# 2. RTFM : la doc, c'est la base

Pourquoi la doc officielle plutôt qu'un tuto ou une vidéo ?

---

# 2. RTFM : la doc, c'est la base

Pourquoi la doc officielle plutôt qu'un tuto ou une vidéo ?

- Elle est écrite par **ceux qui font l'outil**
- Elle correspond à **une version précise**
- Elle est **exhaustive** : tous les paramètres, tous les cas
- Elle est **mise à jour**, contrairement au tuto de 2017

> Un tuto vous montre **un** chemin. La doc vous donne **la carte**.

---

# 2. RTFM : la doc, c'est la base

## Les 4 types de documentation (Diátaxis)

| Type | Objectif | Question à laquelle il répond |
|---|---|---|
| Tutoriel | apprendre | "Par où je commence ?" |
| Guide pratique | accomplir une tâche | "Comment je fais X ?" |
| Référence | décrire | "Que fait exactement cette option ?" |
| Explication | comprendre | "Pourquoi ça marche comme ça ?" |

Savoir quel type on cherche, c'est déjà savoir **où** chercher.

---

# 2. RTFM : la doc, c'est la base

## Où trouver la doc ?

La doc est déjà **dans votre terminal** :

```bash
man ls           # le manuel complet d'une commande
ls --help        # l'aide courte (la plupart des commandes)
help cd          # l'aide des commandes internes de bash (cd, echo, export...)
git help commit  # le manuel d'une commande git (= git commit --help)
git commit -h    # le résumé des options
```

Et en ligne : **git-scm.com/docs**, le livre **Pro Git** (gratuit, traduit en français), le **manuel de Bash** sur gnu.org.

---

# 2. RTFM : la doc, c'est la base

## Lire une page `man`

Toutes les pages de manuel ont la même structure :

| Section | Contenu |
|---|---|
| NAME | le nom et une ligne de description |
| SYNOPSIS | comment appeler la commande |
| DESCRIPTION | ce qu'elle fait |
| OPTIONS | toutes les options, une par une |
| EXAMPLES | des exemples (quand il y en a !) |
| SEE ALSO | les commandes voisines |

---

# 2. RTFM : la doc, c'est la base

## Lire un SYNOPSIS

```
cp [OPTION]... SOURCE... DIRECTORY
```

- `[ ]` : **optionnel**
- `...` : **répétable** (plusieurs options, plusieurs sources)
- `MAJUSCULES` ou `<chevrons>` : à **remplacer** par votre valeur
- `a | b` : l'**un ou l'autre**

Donc : `cp -r -v img/ css/ backup/` est valide.

---

# 2. RTFM : la doc, c'est la base

## Naviguer dans `man`

| Touche | Action |
|---|---|
| `Espace` / `b` | page suivante / précédente |
| `/mot` | chercher "mot" |
| `n` / `N` | occurrence suivante / précédente |
| `q` | quitter |

> Ne lisez pas une doc comme un roman : cherchez (`/`) l'info dont vous avez besoin.

Sous Git Bash (Windows), `man` n'existe pas : `git help` ouvre la doc dans le navigateur, et `--help` fonctionne pour le reste.

---

# 2. RTFM : la doc, c'est la base

## Le message d'erreur est aussi une doc

```
$ git push
To github.com:moi/projet.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:moi/projet.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```

Qu'est-ce qu'il vous dit ?

---

# 2. RTFM : la doc, c'est la base

## Le message d'erreur est aussi une doc

- **Quoi** : le push de `main` a été **refusé** (`rejected`)
- **Pourquoi** : le dépôt distant contient des commits que vous n'avez pas en local
- **Que faire** : récupérer ces changements d'abord (`git pull`), puis pousser
- **Où en savoir plus** : `git push --help`, section *Note about fast-forwards*

Git vous donne **la cause**, **la solution** et **le lien vers la doc**.

> Lisez l'erreur **en entier** avant de la copier sur Google. Et surtout pas de `git push --force` pour "faire passer" !

---

# 2. RTFM : la doc, c'est la base

## Qui se plaint ?

```
$ gti status
bash: gti: command not found
$ cd Mes Documents
bash: cd: too many arguments
$ ./deploy.sh
bash: ./deploy.sh: Permission denied
$ git comit -m "ajout du menu"
git: 'comit' is not a git command. See 'git --help'.
```

Pour chaque erreur : **qui** parle, et **quel** est le problème ?

---

# 2. RTFM : la doc, c'est la base

## Qui se plaint ?

Le premier mot dit **qui** parle : `bash:` ou `git:`

- `gti` : faute de frappe, bash ne trouve aucune commande de ce nom
- `cd Mes Documents` : l'espace sépare les arguments → `cd "Mes Documents"`
- `./deploy.sh` : le fichier n'est pas exécutable → `chmod +x deploy.sh`
- `git comit` : bash a bien trouvé `git`, c'est **git** qui ne connaît pas `comit`

---

# 2. RTFM : la doc, c'est la base

## Chercher efficacement

- Chercher **en anglais** : 10 fois plus de résultats
- Utiliser des **mots-clés**, pas des phrases : `git undo last commit`
- Le `"message exact"` entre guillemets : `"refusing to merge unrelated histories"`
- Cibler un site : `site:git-scm.com`, `site:unix.stackexchange.com`
- Connaître sa **version** : `git --version`, `bash --version`
- Regarder la **date** du résultat

---

# 2. RTFM : la doc, c'est la base

## Stack Overflow & forums

- Lire la **question** : est-ce vraiment votre problème ?
- Regarder la **date** et la **version** utilisée
- Lire **plusieurs réponses** et les commentaires
- **Comprendre** avant de copier-coller

Méfiance absolue avant de coller une commande qui contient : `sudo`, `rm -rf`, `git push --force`, `git reset --hard`, `curl ... | bash`

> Si vous ne pouvez pas expliquer la commande que vous avez copiée, ne l'exécutez pas.

---

# 2. RTFM : la doc, c'est la base

## Bien poser une question

1. **Contexte** : OS, shell (bash, zsh, PowerShell...), `git --version`, ce que vous essayez de faire
2. **Attendu** : ce qui devrait se passer
3. **Obtenu** : la commande tapée **et** sa sortie complète (copiée, pas une photo de l'écran)
4. **Essayé** : ce que vous avez déjà tenté
5. **Exemple minimal** : les quelques commandes qui reproduisent le problème (+ `git status`)

Souvent, en écrivant l'étape 5... on trouve la solution tout seul.

---

# 2. RTFM : la doc, c'est la base

## La méthode du canard en plastique 🦆

Expliquez votre code, ligne par ligne, à voix haute... à un canard en plastique.

> En expliquant, on s'oblige à formuler ce qu'on croit que le code fait. Et on découvre souvent que ce n'est pas ce qu'il fait.

(Un collègue marche aussi, mais il a moins de patience.)

---

# 2. RTFM : la doc, c'est la base

## Où chercheriez-vous ?

| Question | Où chercher | Réponse |
|---|---|---|
| Fichiers cachés | `ls --help` → `/hidden` | `ls -a` |
| Log sur une ligne | `git log -h` | `git log --oneline` |
| `$?` | `man bash` → `/Special Parameters` | le code de retour de la dernière commande |
| `reset` vs `revert` | `git help reset`, `git help revert` | `reset` réécrit l'historique, `revert` ajoute un commit qui annule |

> Tout était déjà dans le terminal.

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

Qui utilise déjà ChatGPT, Claude, Copilot, Gemini... ?

Pour quoi faire ?

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

Quel est le concept d'un **LLM** (Large Language Model) ?

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

Quel est le concept d'un **LLM** (Large Language Model) ?

> Un modèle statistique, entraîné sur une énorme quantité de textes, qui produit la suite **la plus probable** d'un texte donné, morceau par morceau (token par token).

- Ce n'est **pas** une base de données
- Ce n'est **pas** un moteur de recherche
- Ce n'est **pas** une personne

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

## Pourquoi "pas votre amie" ?

Elle peut se tromper... avec **beaucoup d'assurance**.

- **Hallucinations** : fonctions, bibliothèques, options ou sources qui n'existent pas
- **Connaissances datées** : elle ne connaît pas forcément la dernière version
- **Complaisance** : elle a tendance à vous donner raison
- **Code plausible ≠ code correct** : ça a l'air bien, mais est-ce que ça marche ? Est-ce sécurisé ?

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

## Pourquoi "pas votre amie" ?

Elle peut vous empêcher d'**apprendre**.

- Apprendre demande un **effort** : chercher, se tromper, comprendre
- Si l'IA fait l'effort à votre place, **c'est elle qui apprend l'exercice, pas vous**
- En entretien, en examen, en production à 3h du matin... elle ne sera pas toujours là

> On n'apprend pas à nager en regardant quelqu'un nager.

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

## Pourquoi "pas votre amie" ?

Ce que vous lui donnez **ne vous appartient plus tout à fait**.

- Ne collez **jamais** : mots de passe, clés d'API, fichiers `.env`
- Ni données personnelles (clients, collègues...)
- Ni code confidentiel de votre entreprise sans autorisation
- Vérifiez la politique de votre entreprise : outils autorisés, données autorisées

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

## Mais elle peut le devenir

Utilisée comme un **assistant**, pas comme un **pilote** :

- Expliquer un message d'erreur ou un concept
- Reformuler une doc difficile, avec d'autres exemples
- Vous poser des questions pour **vérifier** que vous avez compris
- Relire votre code et suggérer des améliorations
- Générer des cas de test auxquels vous n'aviez pas pensé
- Faire le canard en plastique 🦆 (qui répond)

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

## Bien lui parler

❌ "Dis-moi comment **[faire telle chose]**."

✅ "Je suis en formation **[développeur web, DevOps...]**, dans le contexte suivant : **[langage, outils, contraintes]**. Je souhaite **[objectif]**. Voici comment je ferais : **[ma solution]**. Dis-moi ce que tu en penses."

**Contexte**, **objectif**, **votre proposition d'abord** : l'IA commente votre raisonnement au lieu de le remplacer.

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

## Toujours vérifier

- **Exécuter** le code, ne pas juste le lire
- **Tester** les cas limites (vide, nul, très grand, caractères spéciaux...)
- **Vérifier dans la doc** que la fonction proposée existe (RTFM !)
- **Vérifier** qu'un paquet suggéré existe vraiment et est maintenu avant de l'installer

> Vous êtes responsable du code que vous livrez. Si vous ne pouvez pas l'expliquer, ne le commitez pas.

---

# 3. L'IA n'est pas votre amie (mais peut le devenir)

## La règle pendant la formation

> **D'abord comprendre, ensuite accélérer.**

Comme la calculatrice : on apprend d'abord à compter, puis on l'utilise pour aller plus vite.

- Exercice → **sans IA** d'abord
- Bloqué → doc, collègues, formateur, **puis** IA pour **expliquer**, pas pour **faire**

---

# 4. Le hacking : une histoire de chapeaux

Qu'est-ce qu'un **hacker** ?

---

# 4. Le hacking : une histoire de chapeaux

Qu'est-ce qu'un **hacker** ?

> À l'origine (MIT, fin des années 50), un **hack** est une solution astucieuse et inattendue à un problème. Un hacker est quelqu'un qui aime comprendre comment les choses fonctionnent... pour les détourner.

Hacker ≠ pirate. Le hacking est une **compétence**, pas une intention.

---

# 4. Le hacking : une histoire de chapeaux

Pourquoi des **chapeaux** ?

---

# 4. Le hacking : une histoire de chapeaux

Pourquoi des **chapeaux** ?

> Dans les vieux westerns, les gentils portaient un chapeau **blanc** et les méchants un chapeau **noir**.

---

# 4. Le hacking : une histoire de chapeaux

| Chapeau | Qui ? | Autorisé ? |
|---|---|---|
| ⚪ White hat | cherche des failles pour les faire corriger (pentesteur, chercheur) | ✅ oui |
| ⚫ Black hat | exploite des failles pour nuire ou s'enrichir | ❌ non |
| 🔘 Grey hat | entre les deux : pénètre sans autorisation, mais sans (trop) nuire | ❌ non |

En entreprise, on parle aussi de **Red team** (attaque), **Blue team** (défense) et **Purple team** (les deux ensemble).

---

# 4. Le hacking : une histoire de chapeaux

## Quelques histoires célèbres

| Année | Événement |
|---|---|
| 1988 | Le **ver Morris** paralyse une partie de l'Internet de l'époque |
| 1995 | Arrestation de **Kevin Mitnick**, maître de l'ingénierie sociale |
| 2010 | **Stuxnet**, un virus conçu pour saboter des centrifugeuses nucléaires |
| 2017 | **WannaCry**, un rançongiciel qui touche notamment les hôpitaux britanniques |

---

# 4. Le hacking : une histoire de chapeaux

Quelle est la faille la plus exploitée ?

---

# 4. Le hacking : une histoire de chapeaux

Quelle est la faille la plus exploitée ?

> L'**humain**.

L'**ingénierie sociale** : obtenir un accès en manipulant les gens plutôt que les machines.

- un faux mail de la banque (phishing)
- un faux appel du "support informatique"
- une clé USB "oubliée" sur le parking
- un inconnu qui vous tient la porte du bureau

---

# 4. Le hacking : une histoire de chapeaux

## Et la loi ?

En France, le Code pénal (articles 323-1 et suivants, issus de la loi Godfrain de 1988) punit :

- l'**accès** frauduleux à un système informatique
- le **maintien** frauduleux dans ce système
- l'**entrave** à son fonctionnement
- la **modification** ou la suppression de données

> "Je voulais juste voir si c'était possible" n'est **pas** une défense. Sans autorisation écrite, c'est illégal.

---

# 4. Le hacking : une histoire de chapeaux

## Hacker légalement

- **CTF** (Capture The Flag) : des compétitions de hacking
- Plateformes d'entraînement : **Root-Me**, **TryHackMe**, **Hack The Box**
- **Bug bounty** : être payé pour trouver des failles (YesWeHack, HackerOne...)
- **Divulgation responsable** : prévenir l'éditeur avant de rendre une faille publique

---

# 4. Le hacking : une histoire de chapeaux

## Et pour un développeur ?

Vous écrirez du code qui **sera attaqué**. Connaissez les attaques classiques :

- **Injection** (SQL, commandes...) : ne jamais faire confiance aux entrées utilisateur
- **XSS** : injecter du JavaScript dans une page
- **Contrôle d'accès défaillant** : accéder aux données d'un autre utilisateur
- **Mots de passe mal stockés** : en clair, ou avec un hash faible

> Référence : l'**OWASP Top 10**, la liste des risques les plus critiques des applications web.

---

# 5. Sécurité et hygiène numérique

Contre quoi vous protégez-vous ?

---

# 5. Sécurité et hygiène numérique

Contre quoi vous protégez-vous ?

> La sécurité parfaite n'existe pas. On cherche à rendre l'attaque **plus coûteuse** que ce qu'elle rapporte.

La plupart des attaques ne vous visent pas **personnellement** : elles sont **automatisées** et visent les cibles les plus faciles.

Ne soyez pas la cible la plus facile.

---

# 5. Sécurité et hygiène numérique

Qu'est-ce qu'un **bon** mot de passe ?

---

# 5. Sécurité et hygiène numérique

Qu'est-ce qu'un **bon** mot de passe ?

- `P@ssw0rd!` : court, prévisible, dans tous les dictionnaires d'attaque
- `cheval-agrafe-batterie-correct` : long, simple à retenir, bien plus dur à deviner

> La **longueur** compte plus que la complexité.

Et surtout : **un mot de passe différent pour chaque site**.

---

# 5. Sécurité et hygiène numérique

## Pourquoi un mot de passe unique par site ?

1. Un site mal sécurisé se fait voler sa base de données
2. Votre e-mail + mot de passe se retrouvent en vente
3. Des robots essaient cette combinaison **partout** : mail, banque, réseaux sociaux...

C'est le **credential stuffing**.

> Testez votre adresse sur **haveibeenpwned.com**

---

# 5. Sécurité et hygiène numérique

## Le gestionnaire de mots de passe

Impossible de retenir 150 mots de passe uniques ? Normal.

- Un seul mot de passe **maître**, long et solide
- Il génère et retient tous les autres
- Exemples : **Bitwarden**, **KeePassXC**, **Proton Pass**, 1Password...

> "Mais si le gestionnaire se fait pirater ?" C'est un risque, mais bien plus faible que de réutiliser le même mot de passe partout.

---

# 5. Sécurité et hygiène numérique

## L'authentification multifacteur (MFA / 2FA)

Prouver qui on est avec **au moins deux** de ces facteurs :

| Facteur | Exemple |
|---|---|
| Ce que je **sais** | mot de passe, code PIN |
| Ce que je **possède** | téléphone, clé de sécurité |
| Ce que je **suis** | empreinte digitale, visage |

Du plus fort au plus faible : **passkey / clé physique** > **application (TOTP)** > **SMS** > rien.

Activez-la au minimum sur votre **e-mail** : c'est lui qui permet de réinitialiser tous les autres comptes.

---

# 5. Sécurité et hygiène numérique

## Le phishing (hameçonnage)

Les signaux d'alerte :

- **Urgence** : "votre compte sera suspendu dans 24h"
- **Expéditeur** bizarre : `service@lab4nque-postale.com`
- **Lien** qui ne mène pas où il prétend (survolez avant de cliquer)
- Demande d'**informations sensibles** : mot de passe, code reçu par SMS, numéro de carte
- **Trop beau** pour être vrai

> Votre banque ne vous demandera **jamais** votre mot de passe.

---

# 5. Sécurité et hygiène numérique

## Les bons réflexes

- **Mises à jour** : OS, navigateur, applications. La plupart corrigent des failles.
- **Sauvegardes** : la règle du **3-2-1**
  - **3** copies de vos données
  - sur **2** supports différents
  - dont **1** hors site (cloud, autre lieu)
- **Verrouiller** sa session quand on quitte son poste (`Win + L`)
- **Wi-Fi public** : pas d'opérations sensibles, vérifier le **HTTPS**

---

# 5. Sécurité et hygiène numérique

## Vos traces numériques

- Tout ce qui est publié sur Internet peut y **rester**
- Les recruteurs **cherchent votre nom**
- Les photos contiennent des **métadonnées** (lieu, date, appareil)
- Chaque service "gratuit" se paie avec vos **données**

Le **RGPD** vous donne des droits : accès, rectification, effacement, portabilité...

---

# 5. Sécurité et hygiène numérique

## Côté développeur

- **Jamais** de secret dans le code ni dans Git : utilisez un `.env` et le `.gitignore`
- Un secret poussé sur Git = un secret **compromis** → on le **révoque**, on ne se contente pas de le supprimer
- **Dépendances** : chaque paquet installé est du code d'un inconnu (`npm audit`, `composer audit`)
- **Moindre privilège** : chaque utilisateur, service ou base de données n'a accès qu'au strict nécessaire
- Mots de passe utilisateurs : **hachés** avec un algorithme adapté (bcrypt, Argon2), jamais en clair

---

# 5. Sécurité et hygiène numérique

## Ressources

- **cybermalveillance.gouv.fr** : conseils, assistance aux victimes
- **ANSSI** : le *Guide d'hygiène informatique*
- **haveibeenpwned.com** : vos comptes ont-ils fuité ?
- **OWASP** : la sécurité des applications web

---

# 5. Sécurité et hygiène numérique

## Levez la main si...

- ... vous utilisez le même mot de passe sur plusieurs sites
- ... vous avez activé la MFA sur votre e-mail principal
- ... vous utilisez un gestionnaire de mots de passe
- ... vous avez déjà cliqué sur un lien de phishing (ou failli)
- ... vous avez une sauvegarde de vos données de moins d'un mois
- ... vous avez déjà perdu des données pour de bon

> Pas de honte : tout le monde a au moins une main levée au mauvais endroit.

---

# 6. Bonnes pratiques

Le code est lu **beaucoup plus souvent** qu'il n'est écrit.

Par qui ?

---

# 6. Bonnes pratiques

Le code est lu **beaucoup plus souvent** qu'il n'est écrit.

Par qui ?

- vos collègues
- le formateur, le jury, le recruteur
- le développeur qui vous remplacera
- **vous**, dans 6 mois

---

# 6. Bonnes pratiques

## Nommer les choses

```js
// ❌
const d = 86400;
function calc(a, b) { return a * b * 0.2; }

// ✅
const SECONDS_PER_DAY = 86400;
function computeVat(unitPrice, quantity) { return unitPrice * quantity * VAT_RATE; }
```

- Des noms qui disent **ce que c'est**, pas comment c'est fait
- Choisir une langue (souvent l'anglais) et **s'y tenir**
- Respecter les **conventions** du langage (`camelCase`, `snake_case`...)

---

# 6. Bonnes pratiques

## Les principes à connaître

| Principe | Signification | En clair |
|---|---|---|
| **KISS** | Keep It Simple, Stupid | la solution simple est souvent la bonne |
| **DRY** | Don't Repeat Yourself | une logique = un seul endroit |
| **YAGNI** | You Aren't Gonna Need It | ne codez pas ce dont vous n'avez pas besoin **maintenant** |

---

# 6. Bonnes pratiques

## Versionner son travail

- **Git** dès la première ligne de code, même pour un petit projet
- Des **petits commits**, souvent
- Des **messages** qui expliquent ce qui change et pourquoi

```
❌ fix
❌ modifs
❌ ça marche enfin !!!
✅ Corrige le calcul de la TVA sur les produits remisés
```

---

# 6. Bonnes pratiques

## Tester

"Ça marche sur ma machine" n'est pas un test.

- Tester **manuellement** : cas normal, cas vides, cas absurdes
- Écrire des **tests automatisés** : ils vérifient que ce qui marchait marche toujours
- Un bug corrigé = un test qui empêche qu'il revienne

---

# 6. Bonnes pratiques

## Maîtriser ses outils

- Apprendre les **raccourcis clavier** de son éditeur (et de son OS)
- Ne pas avoir peur du **terminal**
- Savoir utiliser le **débogueur** plutôt que des `console.log` partout
- Personnaliser son environnement... sans y passer ses journées

> Un bon artisan connaît ses outils.

---

# 6. Bonnes pratiques

## Apprendre à apprendre

Dans ce métier, ce que vous apprenez aujourd'hui sera en partie obsolète dans 5 ans.

- Faire de la **veille** : newsletters, blogs, podcasts, conférences
- Faire des **projets perso** : c'est là qu'on apprend le plus
- **Lire du code** : celui des autres, des projets open source
- Rejoindre une **communauté** : meetups, Discord, forums
- Oser dire **"je ne sais pas"**... puis chercher

---

# 6. Bonnes pratiques

## Prendre soin de soi

- **Faire des pauses** : la solution arrive souvent loin de l'écran
- **Posture** et **écran** bien réglés : vous allez passer des milliers d'heures assis
- **Dormir** : le code écrit à 3h du matin, c'est le bug de demain
- **Demander de l'aide** après avoir cherché, mais sans attendre 3 jours

---

# 6. Bonnes pratiques

## Petit lexique geek

| Expression | Signification |
|---|---|
| *Hello World* | le premier programme de tout développeur |
| *It works on my machine* | l'excuse universelle |
| *Have you tried turning it off and on again?* | la solution universelle |
| *42* | la réponse à la grande question sur la vie, l'univers et le reste |
| *Bug* | un défaut, en souvenir d'un papillon de nuit coincé dans un ordinateur en 1947 |
| *PEBKAC* | Problem Exists Between Keyboard And Chair |

---

# Ce qu'il faut retenir

1. Un ordinateur est un **concept**, et il y en a partout
2. **RTFM** : la doc est votre première source
3. L'IA est un **assistant**, pas un pilote : vous restez responsable
4. Hacker est une compétence : le **chapeau**, c'est l'intention (et l'autorisation)
5. Mots de passe **uniques**, **gestionnaire**, **MFA**, **mises à jour**
6. Écrivez du code pour **ceux qui le liront**

---

<center>

# Des questions ?

Le cours complet, à relire à tête reposée : **README.md**

</center>