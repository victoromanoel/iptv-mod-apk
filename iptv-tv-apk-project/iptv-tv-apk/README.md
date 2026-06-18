# 📺 IPTV Pro Player - Android TV (TCL)

APK WebView para TCL TV (Android TV) gerado automaticamente via GitHub Actions.

## 🚀 Como usar

### 1. Suba o projeto no GitHub
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

### 2. O GitHub Actions gera o APK automaticamente
- Vá em **Actions** no seu repositório
- Aguarde o build terminar (~3-5 minutos)
- Clique em **IPTV-Pro-Player-TV-APK** para baixar o APK

### 3. Instale na TV TCL

**Opção A - Via pendrive:**
1. Coloque o APK em um pendrive FAT32
2. Plugue na TCL TV
3. Vá em Configurações → Meu Fire TV → Opções de desenvolvedor → Apps de fontes desconhecidas: ON
4. Use o gerenciador de arquivos para instalar o APK

**Opção B - Via ADB (Wi-Fi):**
```bash
adb connect IP_DA_TV:5555
adb install app-debug.apk
```

**Opção C - Downloader App:**
1. Instale o app "Downloader" na TV
2. Use um link direto do GitHub Releases ou Google Drive
3. Instale via Downloader

## ✅ Requisitos
- TCL TV com Android TV 5.0+
- Conexão com internet para carregar os streams

## 📋 Funcionalidades
- Player IPTV completo em WebView
- Suporte a controle remoto (D-pad)
- Tela cheia imersiva
- Suporte a vídeo HTML5
