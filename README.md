This is the Basic App Code Starting Environment.

#TODO: Seite noch in Markdown konvertieren!

- Moved CSS Imports from App.tsx to index.tsx
- Rearranged dev-dependencies in package.json
- Changed "scripts" in package.json to:
    - "start": "ionic serve",
    - "build": "ionic build",
- Reinstalled dependencies > "npm install" (deleted package-lock.json first)
- Reinstalled ionic-cli as dev-depedency > "npm install @ionic/cli --save-dev --save-exact"
- Added SplashScreen.hide() function to index.tsx
    - (import { Plugins } from '@capacitor/core';)