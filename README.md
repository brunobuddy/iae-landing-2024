# Travail individuel: Création d'une page web

L'objectif est de créér et de déployer une **landing page** pour une entreprise.

- Compte comme **Note individuelle du cours**

## Votre mission

Vous êtes développeur/euse web pour l'entreprise qui est née de votre hackathon. La team marketing (dont vous ne faites évidemment pas partie) vous demande de créer une **landing page** de votre produit / service.

Heureusement vous pouvez compter sur vos compétences en HTML / CSS et votre compréhension des frameworks CSS. De plus, votre web designer vous a transmis [un zonning pour votre landing page](https://github.com/brunobuddy/iae-landing/blob/master/landing.pdf), vous n'avez plus qu'à le développer.

> Ces travaux sont focalisés sur la partie développement web. Le contenu (images et texte) peut être factice. Néanmoins, c'est toujours plus parlant si vous y mettez des contenus plus ou moins réels (sans vous prendre la tête) ou que vous piochez des images dans votre thème.

## Les règles

- Durée: 3h
- Livrable: 1 fichier **index.html** avec la page web et le style intégré
- Livraison par tiinyhost/codesandbox/github/email. Comptez 10 minutes dans votre temps pour la livraison. Envoyez moi l'URL générée bruno@buddyweb.fr

## Resources

- [Le zonning de la landing page](https://github.com/brunobuddy/iae-landing/blob/master/landing.pdf)
- [Code Sandbox - Editeur de code en ligne](https://codesandbox.io/)
- [Framework CSS Bulma](https://bulma.io/documentation/overview/start/) ou [autres alternatives pour les plus courageux/euses](https://github.com/troxler/awesome-css-frameworks)
- [Pexels - Banque d'images libres de droit](https://www.pexels.com/)
- [Documentation HTML de MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [Documentation CSS de MDN](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

## Petits rappels intéressants

Pratiques et toujours bon à savoir.

### Intégrer une librarie dans le HTML

```html
<head>
  <link rel="stylesheet" href="https://y-fake-library.css" />
</head>
```

### Styliser des éléments en CSS

```css
p {
  color: red;
}
```

### Intégrer une balise style dans le HTML

```html
<head>
  <style>
    body {
      background-color: black;
      color: white;
      height: 1000px;
    }
    h1,
    h2 {
      color: white !important;
    }
    #login-button {
      float: right;
    }
  </style>
</head>
```

### Que faire si ça ne marche pas ??? :fearful::fearful:

- Keep calm
- Est-ce que certaines parties de mon code sont soulignées en rouge sur l'éditeur ? Il a peut-être detécté quelque chose à cet endroit si c'est le cas.
- Les balises HTML sont elles bien ouvertes et fermées correctement ? Voir la documentation HTML
- Fonctionnez par élimination: Effacez les éléments 1 par 1 pour voir là où ça coince. Une fois le problème réglé vous pouvez re-intégrer les éléments supprimés.
- La syntaxe des déclarations CSS est-elle correcte ? Accolades, deux-points, point-virgule...
- ChatGPT
- Google
- Si le problème persiste quoi qu'il arrive, recommancez à zéro. Ce n'est pas si grave en soi car vous irez beaucoup plus vite cette fois !


## Livraison sur Tiinyhost (recommandée)
- Copier coller le contenu HTML CSS dans un fichier qu'on sauvegarde avec le nom `index.html` (si besoin télécharger l'éditeur de texte **SublimeText**)
- Aller sur https://tiiny.host/ et créer un compte et uploadez le fichier
- Enoyez moi l'URL publique

![image](https://github.com/user-attachments/assets/5bde381f-e45b-4bb7-9fb9-5b5b955d61fb)


## Livraison sur codesandbox

- Il vous faut créer un compte sur la plateforme **codesandbox** en cliquant sur **sign in**
- Ensuite vous avez une icone "fusée" dans le menu à gauche. Cliquez dessus puis "deploy to Netlify"
- Cette action génère une URL publique. Copiez-là et envoyez-la moi à bruno@buddyweb.fr

![image](https://github.com/brunobuddy/iae-landing/assets/6626184/bc65b018-7ce9-4ece-93b1-544d7affd7ef)

  
## Livraison sur Gihub Pages

[Github](https://github.com/) est une plateforme d'hébergement du code source. Leur outil **Github Pages** permet de déployer des sites web sans avoir besoin de configurer des serveurs.

Voici les étapes pour déployer votre projet achevé:

- Créer un compte [Github](https://github.com/) si vous n'en avez pas déjà un
- Créer un nouveau _repository_ et appellez le **landing-page-COMPANY** en remplaçant "COMPANY" par le nom de votre projet de création d'entreprise. L'option **public** doit être cochée
- Cliquez sur le petit lien "create a new file" (il est vraiment petit)
- Dans l'éditeur, nommez votre fichier index.html et collez votre code dedans puis cliquez sur **commit new file**
- Ensuite allez dans **settings** puis **pages**. Dans **branch** selectionnez "master" puis cliquez sur **save**
- Dans quelques secondes vous devriez voir un encart qui dit "your site is live at". Envoyez moi l'adresse de votre site à bruno@buddyweb.fr

![image](https://user-images.githubusercontent.com/6626184/194229789-a98577cd-549b-41b2-bd9b-f4e0043d24f5.png)

## Livraison par email

- Intégrez l'ensemble du contenu dans un fichier `index.html` et envoyez le moi par email à bruno@buddyweb.fr
