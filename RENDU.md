# Rendu

### `GET /citations`

- **Statut :** `200 OK`
- **Contenu :** Tableau de citations au format JSON.
- **Content-Type :** `application/json`

### `GET /inconnue`

- **Statut :** `404 Not Found`
- **Contenu :** Message d'erreur « Route introuvable » au format JSON.

---

### Rôle de `req` et `res`

- **`req` (Request) :** Contient toutes les informations de la requête envoyée par le client.
- **`res` (Response) :** Permet au serveur de construire et d'envoyer une réponse au client.

### Gestion du `Content-Type`

- **`/ping` :** `text/plain` (texte brut)
- **`/citations` :** `application/json` (format JSON)
