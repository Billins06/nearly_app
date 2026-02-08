# Welcome to your Expo app 👋

# Nearly-App (NEARLY)

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).
Bracelet anti-perte de téléphone + application mobile.

## Get started

## Pourquoi React Native + Expo (choix proposé)

1. Install dependencies
   Comme tu mets l’accent sur le **design**, React Native + Expo est un excellent point de départ :

- **UI/UX rapide à prototyper** (hot reload, Expo Go).
- **Écosystème riche** (navigation, animations, composants UI).
- **Une base unique** pour Android + iOS.
- **Intégration Bluetooth (BLE)** possible via plugins (quand on passera au bracelet réel).

> Flutter est aussi très solide pour le design, mais RN + Expo est souvent **plus rapide à lancer** et
> plus simple pour itérer si on veut montrer vite des maquettes fonctionnelles.

## Démarrage rapide

1. Installer les dépendances

   ```bash
   npm install
   ```

2. Start the app
3. Lancer l’app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

## Objectifs MVP (version 1)

```bash
npm run reset-project
```

- Connexion bracelet (BLE) — **simulée d’abord**
- Définir la distance limite (ex : 5m, 10m, 15m)
- Type d’alerte (vibration / son / intensité)
- Activer / désactiver temporairement l’alerte
- Historique des alertes
- Option : faire sonner le téléphone

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.
Consulte le plan détaillé : `docs/roadmap.md`.

## Learn more

## Structure du projet

To learn more about developing your project with Expo, look at the following resources:

- `src/` : code de l’application
- `docs/` : notes produit, roadmap et specs

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Prochaines étapes

## Join the community

1. Valider les écrans clés (maquettes simples)
2. Construire le flux principal :
   - Accueil → Connexion → Réglages → Alerte
3. Ajouter une simulation BLE (pour développer avant le gadget)

## Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
  Nom du produit : **NEARLY**
