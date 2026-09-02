<script>
  const title = 'À propos : site de test SvelteKit, notre stack et nos choix SEO';
  const description = "Découvrez notre site de test SvelteKit : une page témoin saine servant de fixture pour valider et démontrer les corrections automatiques. À explorer !";
  const canonical = 'https://noyaru-stack-sveltekit.netlify.app/a-propos';
</script>

<svelte:head>
  <title>{title}</title>
  <meta name="description" content={description} />
  <link rel="canonical" href={canonical} />
  <meta property="og:type" content="website" />
  <meta property="og:title" content={title} />
  <meta property="og:description" content={description} />
  <meta property="og:url" content={canonical} />
  <meta property="og:image" content="https://noyaru-stack-sveltekit.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content={title} />
  <meta name="twitter:description" content={description} />
  <meta name="twitter:image" content="https://noyaru-stack-sveltekit.netlify.app/og.png" />
</svelte:head>

<h1>{title}</h1>
<p>Page temoin : elle doit rester intacte apres la correction.</p>
