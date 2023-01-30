# PageSpeed Insights

> Ce site utilise des cookies de Google pour fournir ses services et analyser le trafic.

Ce site utilise des cookies de Google pour fournir ses services et analyser le trafic.

![](https://www.gstatic.com/pagespeed/insights/ui/img/icon-field.svg)

Découvrez l'expérience de vos utilisateurs

* * *

![](https://www.gstatic.com/pagespeed/insights/ui/img/icon-lab.svg)

Analysez les problèmes de performances

Les couleurs d'arrière-plan et de premier plan ne sont pas suffisamment contrastées

Un texte faiblement contrasté est difficile, voire impossible à lire pour de nombreux utilisateurs. [En savoir plus](https://web.dev/color-contrast/?utm_source=lighthouse&utm_medium=lr)

| 
Éléments non conformes

 |
| --- |
| 

"L'agence la Panthére est une excellente agence web ! Les web designers ont réu…

<blockquote class="temoignage">

 |
| 

L'agence La Panthère est une agence de web design qui aide les entreprises à de…

<section class="bloc bgc-white l-bloc" id="bloc-2-services">

 |

The page has a logical tab order

Tabbing through the page follows the visual layout. Users cannot focus elements that are offscreen. [Learn more](https://web.dev/logical-tab-order/?utm_source=lighthouse&utm_medium=lr).

Interactive controls are keyboard focusable

Custom interactive controls are keyboard focusable and display a focus indicator. [Learn more](https://web.dev/focusable-controls/?utm_source=lighthouse&utm_medium=lr).

Interactive elements indicate their purpose and state

Interactive elements, such as links and buttons, should indicate their state and be distinguishable from non-interactive elements. [Learn more](https://web.dev/interactive-element-affordance/?utm_source=lighthouse&utm_medium=lr).

The user's focus is directed to new content added to the page

If new content, such as a dialog, is added to the page, the user's focus is directed to it. [Learn more](https://web.dev/managed-focus/?utm_source=lighthouse&utm_medium=lr).

User focus is not accidentally trapped in a region

A user can tab into and out of any control or region without accidentally trapping their focus. [Learn more](https://web.dev/focus-traps/?utm_source=lighthouse&utm_medium=lr).

Custom controls have associated labels

Custom interactive controls have associated labels, provided by aria-label or aria-labelledby. [Learn more](https://web.dev/custom-controls-labels/?utm_source=lighthouse&utm_medium=lr).

Custom controls have ARIA roles

Custom interactive controls have appropriate ARIA roles. [Learn more](https://web.dev/custom-control-roles/?utm_source=lighthouse&utm_medium=lr).

Visual order on the page follows DOM order

DOM order matches the visual order, improving navigation for assistive technology. [Learn more](https://web.dev/visual-order-follows-dom/?utm_source=lighthouse&utm_medium=lr).

Offscreen content is hidden from assistive technology

Offscreen content is hidden with display: none or aria-hidden=true. [Learn more](https://web.dev/offscreen-content-hidden/?utm_source=lighthouse&utm_medium=lr).

HTML5 landmark elements are used to improve navigation

Landmark elements (<main>, <nav>, etc.) are used to improve the keyboard navigation of the page for assistive technology. [Learn more](https://web.dev/use-landmarks/?utm_source=lighthouse&utm_medium=lr).

Les attributs `[aria-*]` correspondent à leurs rôles

Chaque \`role\` ARIA est rattaché à un sous-ensemble spécifique d'attributs \`aria-\*\`. S'ils ne sont pas correctement associés, les attributs \`aria-\*\` ne seront pas valides. [En savoir plus](https://web.dev/aria-allowed-attr/?utm_source=lighthouse&utm_medium=lr)

`[aria-hidden="true"]` ne figure pas sur le document `<body>`

Les technologies d'assistance, telles que les lecteurs d'écran, présentent un fonctionnement irrégulier lorsque \`aria-hidden="true"\` est défini sur l'élément \`<body>\` du document. [En savoir plus](https://web.dev/aria-hidden-body/?utm_source=lighthouse&utm_medium=lr)

Les attributs `[aria-*]` ont des valeurs valides

Les technologies d'assistance telles que les lecteurs d'écran ne peuvent pas interpréter les attributs ARIA si leurs valeurs ne sont pas valides. [En savoir plus](https://web.dev/aria-valid-attr-value/?utm_source=lighthouse&utm_medium=lr)

Les attributs `[aria-*]` sont valides et correctement orthographiés

Les technologies d'assistance telles que les lecteurs d'écran ne peuvent pas interpréter les attributs ARIA si leurs noms ne sont pas valides. [En savoir plus](https://web.dev/aria-valid-attr/?utm_source=lighthouse&utm_medium=lr)

Les boutons ont un nom accessible

Lorsqu'un bouton n'a pas de nom accessible, les lecteurs d'écran annoncent simplement qu'il s'agit d'un "bouton", ce qui le rend inutilisable pour les personnes qui se servent de tels outils. [En savoir plus](https://web.dev/button-name/?utm_source=lighthouse&utm_medium=lr)

Les éléments d'image possèdent des attributs `[alt]`

Les éléments informatifs doivent contenir un texte de substitution court et descriptif. L'attribut alt peut rester vide pour les éléments décoratifs. [En savoir plus](https://web.dev/image-alt/?utm_source=lighthouse&utm_medium=lr)

La page contient un titre, un lien "Ignorer" ou un point de repère

En ajoutant des méthodes pour contourner les contenus répétitifs, vous permettez aux internautes qui utilisent un clavier de naviguer plus efficacement sur la page. [En savoir plus](https://web.dev/bypass/?utm_source=lighthouse&utm_medium=lr)

Le document contient un élément `<title>`

Le titre donne aux utilisateurs de lecteurs d'écran un aperçu de la page. En outre, les moteurs de recherche s'appuient principalement sur ce dernier pour déterminer la pertinence du contenu proposé. [En savoir plus](https://web.dev/document-title/?utm_source=lighthouse&utm_medium=lr)

Les attributs `[id]` sur des éléments sélectionnables actifs sont uniques

Tous les éléments sélectionnables doivent être associés à un \`id\` unique pour qu'ils soient visibles par les technologies d'assistance. [En savoir plus](https://web.dev/duplicate-id-active/?utm_source=lighthouse&utm_medium=lr)

L'élément `<html>` contient un attribut `[lang]`

Lorsqu'une page ne spécifie pas d'attribut "lang", les lecteurs d'écran considèrent qu'elle est rédigée dans la langue par défaut sélectionnée au moment de leur configuration par l'utilisateur. Si la page n'est pas rédigée dans cette langue par défaut, les lecteurs d'écran risquent de ne pas énoncer correctement son contenu. [En savoir plus](https://web.dev/html-has-lang/?utm_source=lighthouse&utm_medium=lr)

La valeur de l'attribut `[lang]` de l'élément `<html>` est valide

Le fait de spécifier une [langue BCP 47](https://www.w3.org/International/questions/qa-choosing-language-tags#question) valide permet d'aider les lecteurs d'écran à énoncer correctement le texte. [En savoir plus](https://web.dev/html-lang-valid/?utm_source=lighthouse&utm_medium=lr)

Les liens ont un nom visible

Rédigez du texte visible et unique pour les liens (et pour le texte de substitution des images, si vous vous en servez dans des liens), afin que les utilisateurs de lecteurs d'écran puissent facilement positionner le curseur dessus et bénéficient d'une meilleure expérience de navigation. [En savoir plus](https://web.dev/link-name/?utm_source=lighthouse&utm_medium=lr)

Les éléments d'en-tête sont classés séquentiellement par ordre décroissant

Les en-têtes correctement classés qui respectent les niveaux transmettent la structure sémantique de la page, ce qui garantit une navigation plus aisée et permet d'identifier plus facilement dans quels cas utiliser les technologies d'assistance. [En savoir plus](https://web.dev/heading-order/?utm_source=lighthouse&utm_medium=lr)

Les valeurs `[accesskey]` sont uniques

Les clés d'accès permettent aux utilisateurs de positionner rapidement le curseur dans une partie spécifique de la page. Pour les aider à naviguer correctement, pensez à définir des clés d'accès uniques. [En savoir plus](https://web.dev/accesskeys/?utm_source=lighthouse&utm_medium=lr)

Les éléments `button`, `link` et `menuitem` ont des noms accessibles

Lorsqu'un élément n'a pas de nom accessible, les lecteurs d'écran l'annoncent avec un nom générique, ce qui le rend inutilisable pour les personnes qui se servent de tels outils. [En savoir plus](https://web.dev/aria-name/?utm_source=lighthouse&utm_medium=lr)

Les champs de saisie ARIA ont des noms accessibles

Lorsqu'un champ de saisie n'a pas de nom accessible, les lecteurs d'écran l'annoncent avec un nom générique, ce qui le rend inutilisable pour les personnes qui se servent de tels outils. [En savoir plus](https://web.dev/aria-name/?utm_source=lighthouse&utm_medium=lr)

Les éléments ARIA `meter` ont des noms accessibles

Lorsqu'un élément n'a pas de nom accessible, les lecteurs d'écran l'annoncent avec un nom générique, ce qui le rend inutilisable pour les personnes qui se servent de tels outils. [En savoir plus](https://web.dev/aria-name/?utm_source=lighthouse&utm_medium=lr)

Les éléments ARIA `progressbar` ont des noms accessibles

Lorsqu'un élément \`progressbar\` n'a pas de nom accessible, les lecteurs d'écran l'annoncent avec un nom générique, ce qui le rend inutilisable pour les personnes qui se servent de tels outils. [En savoir plus](https://web.dev/aria-name/?utm_source=lighthouse&utm_medium=lr)

Tous les éléments `[role]` contiennent les attributs `[aria-*]` requis

Certains rôles ARIA ont des attributs obligatoires qui décrivent l'état de l'élément aux lecteurs d'écran. [En savoir plus](https://web.dev/aria-required-attr/?utm_source=lighthouse&utm_medium=lr)

Les éléments ayant un `[role]` ARIA, qui exigent que les enfants incluent un `[role]` spécifique, possèdent tous les enfants requis.

Certains rôles ARIA parents doivent contenir des rôles enfants spécifiques afin de remplir correctement leurs fonctions d'accessibilité. [En savoir plus](https://web.dev/aria-required-children/?utm_source=lighthouse&utm_medium=lr)

Les éléments `[role]` sont inclus dans l'élément parent approprié

Certains rôles ARIA enfants doivent être inclus dans un rôle parent spécifique afin de remplir correctement leurs fonctions d'accessibilité. [En savoir plus](https://web.dev/aria-required-parent/?utm_source=lighthouse&utm_medium=lr)

Les valeurs `[role]` sont valides

Les rôles ARIA doivent comporter des valeurs valides afin de remplir correctement leurs fonctions d'accessibilité. [En savoir plus](https://web.dev/aria-roles/?utm_source=lighthouse&utm_medium=lr)

Les champs d'activation/de désactivation ARIA ont des noms accessibles

Lorsqu'un champ d'activation/de désactivation n'a pas de nom accessible, les lecteurs d'écran l'annoncent avec un nom générique, ce qui le rend inutilisable pour les personnes qui se servent de tels outils. [En savoir plus](https://web.dev/aria-name/?utm_source=lighthouse&utm_medium=lr)

Les éléments ARIA `treeitem` ont des noms accessibles

Lorsqu'un élément n'a pas de nom accessible, les lecteurs d'écran l'annoncent avec un nom générique, ce qui le rend inutilisable pour les personnes qui se servent de tels outils. [En savoir plus](https://web.dev/aria-name/?utm_source=lighthouse&utm_medium=lr)

Les éléments `<dl>` ne contiennent que des groupes `<dt>` et `<dd>` ainsi que des éléments `<script>`, `<template>` ou `<div>` dans le bon ordre.

Si les listes de définition ne sont pas correctement balisées, les lecteurs d'écran risquent de donner des résultats confus ou imprécis. [En savoir plus](https://web.dev/definition-list/?utm_source=lighthouse&utm_medium=lr)

Les éléments de liste de définition sont encapsulés dans des éléments `<dl>`

Les éléments de liste de définition (\`<dt>\` et \`<dd>\`) doivent être encapsulés dans un élément \`<dl>\` parent afin que les lecteurs d'écran puissent les énoncer correctement. [En savoir plus](https://web.dev/dlitem/?utm_source=lighthouse&utm_medium=lr)

La valeur d'un ID ARIA doit être unique afin que les différentes instances soient toutes prises en compte par les technologies d'assistance. [En savoir plus](https://web.dev/duplicate-id-aria/?utm_source=lighthouse&utm_medium=lr)

Aucun champ de formulaire ne comporte plusieurs libellés

Les champs de formulaire comprenant plusieurs libellés peuvent être annoncés par les technologies d'assistance comme des lecteurs d'écran utilisant le premier, le dernier ou tous les libellés, ce qui peut prêter à confusion. [En savoir plus](https://web.dev/form-field-multiple-labels/?utm_source=lighthouse&utm_medium=lr)

Les éléments `<frame>` ou `<iframe>` ont un titre

Les lecteurs d'écran s'appuient sur le titre des frames pour décrire le contenu de ces derniers aux utilisateurs. [En savoir plus](https://web.dev/frame-title/?utm_source=lighthouse&utm_medium=lr)

Les éléments `<input type="image">` contiennent du texte `[alt]`

Lorsqu'une image est utilisée comme bouton \`<input>\`, vous pouvez aider les utilisateurs de lecteurs d'écran à comprendre son utilité en ajoutant un texte de substitution. [En savoir plus](https://web.dev/input-image-alt/?utm_source=lighthouse&utm_medium=lr)

Les éléments de formulaire sont associés à des libellés

Les libellés permettent de s'assurer que les éléments de contrôle des formulaires sont énoncés correctement par les technologies d'assistance, comme les lecteurs d'écran. [En savoir plus](https://web.dev/label/?utm_source=lighthouse&utm_medium=lr)

Les listes contiennent uniquement des éléments `<li>` et des éléments de type script (`<script>` et `<template>`).

Les lecteurs d'écran ont une façon spécifique d'énoncer les listes. Pour leur permettre de donner de bons résultats, pensez à bien structurer ces dernières. [En savoir plus](https://web.dev/list/?utm_source=lighthouse&utm_medium=lr)

Les éléments de liste (`<li>`) sont inclus dans des éléments parents `<ul>` ou `<ol>`

Les lecteurs d'écran requièrent que les éléments de liste (\`<li>\`) soient contenus dans un élément parent \`<ul>\` ou \`<ol>\` pour les énoncer correctement. [En savoir plus](https://web.dev/listitem/?utm_source=lighthouse&utm_medium=lr)

Les éléments `<object>` contiennent du texte de substitution

Les lecteurs d'écran ne peuvent pas traduire les contenus non textuels. En ajoutant un texte de substitution aux éléments \`<object>\`, vous aiderez les lecteurs d'écran à transmettre votre message aux utilisateurs. [En savoir plus](https://web.dev/object-alt/?utm_source=lighthouse&utm_medium=lr)

Aucun élément n'a de valeur `[tabindex]` supérieure à 0

Une valeur supérieure à 0 implique un ordre de navigation explicite. Bien que cela soit valide d'un point de vue technique, cela crée souvent une expérience frustrante pour les utilisateurs qui s'appuient sur des technologies d'assistance. [En savoir plus](https://web.dev/tabindex/?utm_source=lighthouse&utm_medium=lr)

Les éléments `<th>` et ceux portant l'attribut `[role="columnheader"/"rowheader"]` décrivent des cellules de données.

Les lecteurs d'écran proposent des fonctionnalités qui permettent de naviguer plus simplement dans les tableaux. En vous assurant que les en-têtes de tableaux fassent toujours référence à un ensemble de cellules spécifique, vous pourrez améliorer l'expérience des utilisateurs de lecteurs d'écran. [En savoir plus](https://web.dev/th-has-data-cells/?utm_source=lighthouse&utm_medium=lr)

Les attributs `[lang]` ont une valeur valide

Le fait de spécifier une [langue BCP 47](https://www.w3.org/International/questions/qa-choosing-language-tags#question) valide pour les éléments permet de s'assurer que le texte sera prononcé correctement par les lecteurs d'écran. [En savoir plus](https://web.dev/valid-lang/?utm_source=lighthouse&utm_medium=lr)

Les éléments `<video>` contiennent un élément `<track>` avec `[kind="captions"]`

Le fait d'ajouter des sous-titres à une vidéo rend cette dernière plus accessible aux personnes sourdes et malentendantes. [En savoir plus](https://web.dev/video-caption/?utm_source=lighthouse&utm_medium=lr)

La page utilise des bibliothèques JavaScript frontales présentant des failles de sécurité connues 9 failles détectées

Certains scripts tiers peuvent présenter des failles de sécurité connues, faciles à identifier et à exploiter par des pirates informatiques. [En savoir plus](https://web.dev/no-vulnerable-libraries/?utm_source=lighthouse&utm_medium=lr)

| 
Version de la bibliothèque

 | 

Nombre de failles

 | 

Extrême

 |
| --- | --- | --- |
| [Bootstrap@3.3.5](https://snyk.io/vuln/npm:bootstrap?lh=3.3.5&utm_source=lighthouse&utm_medium=ref&utm_campaign=audit) | 

5

 | 

Moyenne

 |
| [jQuery@2.1.0](https://snyk.io/vuln/npm:jquery?lh=2.1.0&utm_source=lighthouse&utm_medium=ref&utm_campaign=audit) | 

4

 | 

Moyenne

 |

Garantir l'efficacité de la CSP contre les attaques XSS

Une CSP (Content Security Policy) efficace réduit considérablement le risque d'attaques de script intersites (XSS). [En savoir plus](https://web.dev/csp-xss/?utm_source=lighthouse&utm_medium=lr)

| 
Description

 | 

Directive

 | 

Gravité

 |
| --- | --- | --- |
| 

Aucune CSP trouvée en mode de mise en conformité

 |  | 

Élevée

 |

Bibliothèques JavaScript détectées

Toutes les bibliothèques JavaScript frontales détectées sur la page. [Découvrez-en davantage](https://web.dev/js-libraries/?utm_source=lighthouse&utm_medium=lr).

| 
Nom

 | 

Version

 |
| --- | --- |
| 

Bootstrap

 | 

3.3.5

 |
| 

jQuery

 | 

2.1.0

 |

Tous les sites doivent être protégés par le protocole HTTPS, même ceux qui ne traitent pas de données sensibles. Par conséquent, vous devez éviter le [contenu mixte](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content?utm_source=lighthouse&utm_medium=lr), qui provoque le chargement de certaines ressources sur HTTP bien que la demande initiale soit diffusée via HTTPS. Le protocole HTTPS empêche les intrus de détourner ou d’écouter passivement les communications entre votre application et les utilisateurs. Il constitue également une condition préalable à l'utilisation de HTTP/2 et de nombreuses nouvelles API de plates-formes Web. [En savoir plus](https://web.dev/is-on-https/?utm_source=lighthouse&utm_medium=lr)

Aucune autorisation de géolocalisation n'est demandée au chargement de la page

Les utilisateurs se méfient des sites qui demandent leur position sans contexte. Envisagez plutôt d'associer la demande à des actions de l'utilisateur. [En savoir plus](https://web.dev/geolocation-on-start/?utm_source=lighthouse&utm_medium=lr)

Aucune autorisation d'envoi de notifications n'est demandée au chargement de la page

Les utilisateurs se méfient des sites qui demandent à envoyer des notifications sans contexte. Envisagez plutôt d'associer la demande à des gestes de l'utilisateur. [En savoir plus](https://web.dev/notification-on-start/?utm_source=lighthouse&utm_medium=lr)

Autoriser les utilisateurs à copier un contenu dans les champs de mot de passe

Empêcher la copie de contenu dans les champs de mot de passe nuit aux règles de sécurité. [En savoir plus](https://web.dev/password-inputs-can-be-pasted-into/?utm_source=lighthouse&utm_medium=lr)

Images affichées au bon format

Les dimensions d'affichage des images doivent correspondre au format naturel. [En savoir plus](https://web.dev/image-aspect-ratio/?utm_source=lighthouse&utm_medium=lr)

Images diffusées dans la résolution appropriée

Pour que la clarté de l'image soit optimale, ses dimensions naturelles doivent être proportionnelles à la taille d'affichage et au taux de pixels. [En savoir plus](https://web.dev/serve-responsive-images/?utm_source=lighthouse&utm_medium=lr)

La page n'a pas d'attribut doctype HTML

La spécification d'un attribut doctype empêche le navigateur de passer en mode quirks. [Découvrez-en davantage](https://web.dev/doctype/?utm_source=lighthouse&utm_medium=lr).

Le charset est défini correctement

La déclaration d'encodage des caractères est obligatoire. Elle peut être effectuée avec une balise \`<meta>\` dans les 1 024 premiers octets du code HTML, ou dans l'en-tête de réponse HTTP Content-Type. [En savoir plus](https://web.dev/charset/?utm_source=lighthouse&utm_medium=lr)

La page n'utilise pas d'API obsolètes

Les API obsolètes seront finalement supprimées du navigateur. [En savoir plus](https://web.dev/deprecations/?utm_source=lighthouse&utm_medium=lr)

Aucune erreur de navigateur enregistrée dans la console

Les erreurs enregistrées dans la console indiquent des problèmes non résolus. Ces derniers peuvent être dus à des requêtes réseau qui ont échoué et à d'autres problèmes du navigateur. [En savoir plus](https://web.dev/errors-in-console/?utm_source=lighthouse&utm_medium=lr)

Aucun problème dans le panneau `Issues` des outils de développement Chrome

Les problèmes enregistrés dans le panneau \`Issues\` des outils de développement Chrome indiquent des problèmes non résolus. Ceux-ci peuvent être dus à des requêtes réseau qui ont échoué, à des contrôles de sécurité insuffisants ou à d'autres problèmes du navigateur. Ouvrez le panneau "Issues" dans les outils de développement Chrome pour en savoir plus sur chaque problème.

La page contient des mappages source valides

Les mappages source traduisent le code minimisé pour obtenir le code source d'origine. Ce processus aide les développeurs à effectuer le débogage en phase de production. De plus, Lighthouse est en mesure de fournir d'autres renseignements. Envisagez de déployer des mappages source pour profiter de ces avantages. [En savoir plus](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps?utm_source=lighthouse&utm_medium=lr)

Les polices qui utilisent `font-display: optional` sont préchargées

Préchargez les polices \`optional\` pour que les nouveaux visiteurs puissent les utiliser. [En savoir plus](https://web.dev/preload-optional-fonts/?utm_source=lighthouse&utm_medium=lr)

Les données structurées sont valides

Une balise `<meta name="viewport">` ayant l'attribut `width` ou `initial-scale` est configurée

Le document contient un élément `<title>`

Le titre donne aux utilisateurs de lecteurs d'écran un aperçu de la page. En outre, les moteurs de recherche s'appuient principalement sur ce dernier pour déterminer la pertinence du contenu proposé. [En savoir plus](https://web.dev/document-title/?utm_source=lighthouse&utm_medium=lr)

La page renvoie un code d'état HTTP de réussite

Les pages renvoyant des codes d'état HTTP d'échec peuvent ne pas être indexées correctement. [En savoir plus](https://web.dev/http-status-code/?utm_source=lighthouse&utm_medium=lr)

Les liens contiennent un texte descriptif

Le texte descriptif d'un lien aide les moteurs de recherche à comprendre votre contenu. [En savoir plus](https://web.dev/link-text/?utm_source=lighthouse&utm_medium=lr)

Les liens peuvent être explorés

Les moteurs de recherche peuvent utiliser les attributs \`href\` des liens pour explorer les sites Web. Assurez-vous que l'attribut \`href\` des éléments d'ancrage pointe vers une destination appropriée, pour que davantage de pages du site puissent être détectées. [En savoir plus](https://support.google.com/webmasters/answer/9112205)

L'indexation de cette page n'est pas bloquée

Les moteurs de recherche ne peuvent pas inclure vos pages dans les résultats de recherche s'ils ne sont pas autorisés à les explorer. [En savoir plus](https://web.dev/is-crawable/?utm_source=lighthouse&utm_medium=lr)

Les éléments d'image possèdent des attributs `[alt]`

Les éléments informatifs doivent contenir un texte de substitution court et descriptif. L'attribut alt peut rester vide pour les éléments décoratifs. [En savoir plus](https://web.dev/image-alt/?utm_source=lighthouse&utm_medium=lr)

L'attribut `hreflang` du document est valide

Les liens hreflang indiquent aux moteurs de recherche la version de la page qu'ils doivent répertorier dans les résultats de recherche pour une page ou une région donnée. [En savoir plus](https://web.dev/hreflang/?utm_source=lighthouse&utm_medium=lr)

L'attribut `rel=canonical` du document est valide

Les liens canoniques suggèrent l'URL à afficher dans les résultats de recherche. [En savoir plus](https://web.dev/canonical/?utm_source=lighthouse&utm_medium=lr)

Le document utilise des tailles de police lisibles 100 % du texte lisibles

Les tailles de police inférieures à 12 pixels sont trop petites pour être lisibles et nécessitent que les visiteurs sur la version mobile pincent l'écran pour zoomer et lire le texte. Veuillez utiliser une police de texte de plus de 12 pixels sur plus de 60 % du texte de la page. [En savoir plus](https://web.dev/font-size/?utm_source=lighthouse&utm_medium=lr)

| 
Source

 | 

Sélecteur

 | 

% du texte de la page

 | 

Taille de police

 |
| --- | --- | --- | --- |
| 

Texte lisible

 |  | 

100.00%

 | 

≥ 12px

 |

Le document évite les plug-ins

Les moteurs de recherche ne peuvent pas indexer le contenu des plug-ins, et de nombreux appareils limitent l'utilisation de ces derniers, voire ne les acceptent pas. [En savoir plus](https://web.dev/plugins/?utm_source=lighthouse&utm_medium=lr)

Les éléments tactiles sont dimensionnés correctement 100 % des éléments tactiles sont correctement dimensionnés

Les éléments interactifs comme les boutons et les liens doivent être suffisamment larges (48 x 48 pixels) et avoir suffisamment d'espace autour d'eux pour que l'utilisateur puisse appuyer facilement dessus sans appuyer en même temps sur d'autres éléments. [En savoir plus](https://web.dev/tap-targets/?utm_source=lighthouse&utm_medium=lr)

Le fichier robots.txt est valide

Si votre fichier robots.txt n'est pas créé correctement, il se peut que les robots d'exploration ne puissent pas comprendre comment votre site Web doit être exploré ou indexé. [Découvrez-en davantage](https://web.dev/robots-txt/?utm_source=lighthouse&utm_medium=lr).


[Source](https://pagespeed.web.dev/report?url=https%3A%2F%2Flysianebo.github.io%2FStartingwebsite2%2F&hl=fr)