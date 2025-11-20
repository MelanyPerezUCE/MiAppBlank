# MiAppBlank

Plantilla Expo + React Native.

## Requisitos
- Node.js (16+ recomendado)
- npm o yarn
- Expo CLI (se puede usar vía `npx`)

## Instalación
```sh
npm install
```

## Comandos principales usados para crear este proyecto
- Crear proyecto (Plantilla en blanco):
```sh
npx create-expo-app MiAppBlank --template blank 
```
- Entrar al proyecto:
```sh
cd MiAppBlank
```
- Ejecutar en desarrollo:
```sh
npx expo start
```
- Ejecutar en plataformas:
```sh
npm run ios
npm run android
npm run web
```

## Ejecutar (resumen)
- Desarrollo: `npx expo start` (o `npm run start`)
- iOS: `npm run ios`
- Android: `npm run android`
- Web: `npm run web`

Los scripts están en `package.json`.

## Estructura principal
- app/
  - app/_layout.tsx (layout raíz)
  - app/(tabs)/_layout.tsx (layout de pestañas)
  - app/(tabs)/index.tsx (pantalla principal)
  - app/(tabs)/explore.tsx (pantalla Explore)
  - app/modal.tsx (modal de ejemplo)
- components/
  - themed-text.tsx, themed-view.tsx
  - ui/icon-symbol.tsx, ui/icon-symbol.ios.tsx
  - parallax-scroll-view.tsx, hello-wave.tsx
  - ui/collapsible.tsx, external-link.tsx, haptic-tab.tsx
- hooks/
  - use-color-scheme.ts, use-color-scheme.web.ts
  - use-theme-color.ts
- constants/theme.ts
- tsconfig.json
- eslint.config.js
