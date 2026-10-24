# Portfolio — Mohamed Elaazzaoui

En ligne : https://mohamed-elaazzaoui.vercel.app (déploiement automatique à chaque push sur `main`).

Site d'une seule page (HTML/CSS/JS, sans build) :

```
index.html                 la page (FR / EN)
assets/CV_Elaazzaoui_Mohamed.pdf
assets/og-image.jpg        image d'aperçu (LinkedIn, WhatsApp…)
assets/photo.jpg           À AJOUTER : votre photo (format portrait, ex. 800×1000)
assets/projets/*.jpg       À AJOUTER : captures des projets (16:9, ex. 1600×900)
robots.txt, vercel.json
```

## Ajouter vos images
Déposez simplement les fichiers avec **exactement** ces noms ; tant qu'un fichier manque, la page affiche un monogramme (photo) ou masque l'emplacement (projet).

| Fichier | Projet |
|---|---|
| `assets/photo.jpg` | Votre portrait |
| `assets/projets/rag.jpg` | Assistant de cours IA (RAG) |
| `assets/projets/pipeline.jpg` | Pipeline de données temps réel |
| `assets/projets/mlops.jpg` | Plateforme data & ML Olist |
| `assets/projets/lias.jpg` | LIAS |
| `assets/projets/cicd.jpg` | CI/CD application de crédit |
| `assets/projets/bert.jpg` | Optimiseurs BERT & GPT |

## Formulaire de contact
Actif : formulaire Formspree « Portfolio – Contact » (ID `xjyygbnn`, déjà renseigné dans `index.html`).
Les messages arrivent sur **mohamedelaazzaoui00@gmail.com** et dans https://formspree.io/forms/xjyygbnn/submissions.
Offre gratuite : 50 messages par mois. Pour recevoir aussi sur Outlook, ajoutez l'adresse dans Account → Linked Emails, puis dans Settings du formulaire.

## Déployer sur Vercel
1. Poussez ce dossier sur un dépôt GitHub (ex. `portfolio`).
2. Sur https://vercel.com → **Add New… → Project** → importez le dépôt.
3. Framework Preset : **Other**, aucune commande de build → **Deploy**.
4. Dans le projet Vercel : onglet **Analytics → Enable** pour les statistiques de visite (déjà intégrées dans la page).
5. Une fois l'adresse connue (ex. `https://elaazzaoui.vercel.app`), remplacez dans `index.html`
   `content="/assets/og-image.jpg"` par l'adresse complète `https://…/assets/og-image.jpg`
   pour que LinkedIn affiche bien l'aperçu.

## Langue
Français par défaut ; le bouton **EN** bascule en anglais (choix mémorisé). Lien direct en anglais : `https://…/?lang=en`.
