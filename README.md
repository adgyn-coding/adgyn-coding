# Overview
<h1 align="center">Yann · Ingénieur logiciel en construction</h1>

<p align="center">
  Étudiant en prépa ingénieur à l'Ecole Nouvelle Supérieure d'Ingénieurs et de Technologie(ENSIT) en Côte d'Ivoire.<br>
  Je construis des outils pour les élèves d'ici, et j'apprends à les sécuriser.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mian-yann-axel-adingra-1ba74b436/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://noteo-v1-7.vercel.app/login"><img src="https://img.shields.io/badge/Noteo_en_ligne-16A34A?style=for-the-badge&logo=vercel&logoColor=white"></a>
</p>

---

```bash
$ whoami
yann, 18 ans, Côte d'Ivoire

$ cat objectif.txt
Devenir un ingénieur logiciel complet, pas juste quelqu'un qui sait
demander du code à une IA. Comprendre ce que je livre.

$ cat statut.txt
Projet en production · Python en cours · cybersécurité en parallèle
```

---

## 🚀 Noteo : le projet qui tourne en vrai

**Le problème.** Au lycée en Côte d'Ivoire, calculer sa moyenne par matière et par trimestre se fait à la main, avec des coefficients différents selon les séries. C'est long et on se trompe.

**La solution.** Une application web où l'élève entre ses notes et obtient ses moyennes tout de suite. Offre gratuite + offre Pro payante.

**Ce qui tourne derrière :**
- Authentification Google (OAuth)
- Base de données Supabase protégée par des politiques RLS
- Paiements Paystack avec webhooks et logs
- Déploiement continu sur Vercel

👉 **[Essayer Noteo](https://noteo-v1-7.vercel.app/login)**

---

## 🔐 Ce que Noteo m'a appris (les erreurs comprises)

Je ne cache pas mes bugs, je les documente :

- **Une API publique n'est pas un secret.** Les clés `anon` de Supabase sont publiques par conception. La vraie protection, ce sont les règles RLS.
- **Faire confiance au client est une faille.** Je regarde systématiquement ce qu'un utilisateur malin pourrait modifier lui-même.
- **Un agent IA code vite, mais c'est à moi de vérifier.** Chaque fonctionnalité sensible passe par une revue de sécurité avant la mise en ligne.

---

## 🛠️ Mes outils

<p>
  <img src="https://skillicons.dev/icons?i=nextjs,react,js,supabase,vercel,git,github,vscode&perline=8">
</p>

**En apprentissage :**

<img src="https://skillicons.dev/icons?i=python,linux&perline=8">

---

## 📈 Activité

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TON_PSEUDO&layout=compact&hide_border=true&theme=tokyonight">
</p>

---

## 🎯 Prochaines étapes

- [x] Noteo en production avec paiements
- [ ] Certification Python (freeCodeCamp)
- [ ] Comprendre une requête de bout en bout (DNS → HTTP → API)
- [ ] Un labo Linux pour pratiquer la cybersécurité

---

<p align="center"><i>Je documente ce que j'apprends. Si tu veux échanger, écris-moi.</i></p>
