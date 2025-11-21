main: branche de base (production)
dev: branche d'intégration
feature/*: branches de fonctionnalités
hotfix/*: corrections urgentes

Choix d'intégration pour la correction hotfix:
- J'intègre la correction sur `main` puis je merges `main` dans `dev` pour propager le fix.
  Raisons: préservation d'un historique clair des corrections en production et simplicité (merge non destructif).
