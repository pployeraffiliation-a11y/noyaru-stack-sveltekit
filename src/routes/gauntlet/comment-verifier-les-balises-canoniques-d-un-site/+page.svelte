<script>
  // Page de contenu : verifier les balises canoniques d'un site.
  // Canonical auto-referentielle et correcte, aucune anomalie volontaire ici.
</script>

<svelte:head>
  <meta name="viewport" content="width=device-width" />
  <title>Comment verifier les balises canoniques d'un site</title>
  <meta name="description" content="Methode pratique pour verifier les balises canoniques d'un site : ou les trouver, quoi controler et les erreurs frequentes a corriger." />
  <link rel="canonical" href="https://noyaru-stack-sveltekit.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Comment verifier les balises canoniques d'un site" />
  <meta property="og:description" content="Methode pratique pour verifier les balises canoniques d'un site : ou les trouver, quoi controler et les erreurs frequentes a corriger." />
  <meta property="og:url" content="https://noyaru-stack-sveltekit.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site" />
  <meta property="og:image" content="https://noyaru-stack-sveltekit.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Comment verifier les balises canoniques d'un site" />
  <meta name="twitter:description" content="Methode pratique pour verifier les balises canoniques d'un site : ou les trouver, quoi controler et les erreurs frequentes a corriger." />
  <meta name="twitter:image" content="https://noyaru-stack-sveltekit.netlify.app/og.png" />
</svelte:head>

<h1>Comment verifier les balises canoniques d'un site</h1>
<p>La balise canonique indique aux moteurs quelle URL fait autorite pour un contenu donne. Bien reglee, elle evite que plusieurs adresses se disputent le meme texte et diluent le referencement.</p>

<h2>Ou trouver la balise</h2>
<p>Elle se place dans la section head du document sous la forme d'un element link avec l'attribut rel a canonical. Pour la lire, ouvrez le code source de la page ou utilisez l'inspecteur du navigateur et cherchez la ligne concernee.</p>

<h2>Ce qu'il faut controler</h2>
<p>Verifiez d'abord que l'URL declaree est absolue et complete, protocole compris. Assurez-vous ensuite qu'elle renvoie bien un code 200 : une canonique pointant vers une page absente ou redirigee brouille le signal. Chaque page ne doit porter qu'une seule balise, et sur une page standard elle doit se referencer elle-meme.</p>

<h2>Erreurs frequentes</h2>
<p>Les pieges classiques sont une canonique vers l'accueil sur toutes les pages, un melange entre versions avec et sans barre finale, ou une adresse en http alors que le site sert du https. Comparez aussi la canonique avec l'URL reellement visitee pour reperer les incoherences.</p>

<h2>Verification a l'echelle du site</h2>
<p>Pour un site entier, un crawler qui parcourt toutes les pages permet de dresser la liste des canoniques et de detecter les cibles cassees ou dupliquees. Le rapport d'indexation d'un outil pour webmasters aide ensuite a confirmer quelle URL est retenue par le moteur.</p>

<p><a href="/">Retour a l accueil</a></p>
