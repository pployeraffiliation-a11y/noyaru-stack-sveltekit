<script>
  const title = 'A propos du site de test SvelteKit';
  const description = "Page temoin du site fixture SvelteKit : elle est saine et doit rester rigoureusement intacte apres la correction automatique.";
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
  <meta property="og:image" content="https://noyaru-stack-sveltekit.netlify.app/og.png" alt="Image de prévisualisation du site SvelteKit" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content={title} />
  <meta name="twitter:description" content={description} />
  <meta name="twitter:image" content="https://noyaru-stack-sveltekit.netlify.app/og.png" alt="Image de prévisualisation du site SvelteKit" />
</svelte:head>

<h1>{title}</h1>
<p>Page temoin : elle doit rester intacte apres la correction.</p>
