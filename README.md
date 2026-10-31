# Indicador de Mídia (V2)

App para guardar animes, séries e filmes, dar notas e receber indicações pelo Gemini (grátis).
Começa vazio, sem nenhum dado pré-carregado.

## Gerar o APK (grátis, na nuvem do GitHub)

1. Crie um repositório novo e vazio no GitHub (pode ser privado).
2. Envie todo o conteúdo desta pasta para ele (inclusive a pasta oculta `.github`).
3. No GitHub: aba **Actions** > **Gerar APK** > **Run workflow** (ele também roda sozinho a cada envio).
4. Espere uns 5 a 10 minutos. Abra a execução concluída e baixe o arquivo **indicador-midia-apk** (um .zip com o `app-debug.apk`).
5. Mande o `app-debug.apk` para o celular de quem vai usar e instale (o Android pede para permitir "fontes desconhecidas").

## Usar sem APK (opcional)

A pasta `www` é um site que funciona como app. Publicada em qualquer hospedagem (por exemplo GitHub Pages),
dá para abrir no Chrome do celular e tocar em "Adicionar à tela inicial".

## Na primeira abertura

O app pergunta o nome, mostra um tour rápido e ensina a criar a chave grátis do Gemini em
https://aistudio.google.com/apikey (basta uma conta Google). A chave e a lista ficam só no celular.

## Dados usados

AniList (animes), TVmaze (séries), IMDb/TMDB (filmes) e Gemini (indicações, sinopses em português e parecidos).
