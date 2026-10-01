# Organizador — como gerar o APK (sem instalar nada no PC)
1. Crie uma conta gratuita em github.com e um repositório novo (privado serve).
2. Envie TODOS os arquivos desta pasta (inclusive a pasta oculta `.github`) para o repositório.
3. Aba **Actions → Gerar APK → Run workflow**. Em ~5 min aparece o artefato **Organizador-APK**.
4. Baixe, descompacte o .zip e envie o `app-debug.apk` para quem quiser. No celular: abrir o arquivo e permitir "instalar de fontes desconhecidas".

Cada pessoa tem seus dados só no próprio celular. Use ⬇️/⬆️ no topo para backup/restauração em .json.
Teste rápido sem APK: abra `www/index.html` no navegador (precisa de `Sortable.min.js` na mesma pasta, vem do `npm run prep`).
