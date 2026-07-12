# Next.js : revalidateTag pour invalider le cache à la demande

Taguer les fetch avec `next: { tags: [...] }` puis appeler `revalidateTag(tag)` dans une action serveur pour invalider le cache à la demande.
