# Meio Termo — cifras na sua medida

PWA para violão/guitarra. Você digita a música, a IA (Gemini grátis ou Claude) busca a cifra simplificada e a avançada na internet e monta uma versão intermediária. Cada trecho tem botões Simples / Intermediária / Avançada, e você pode editar o texto de qualquer trecho. Tudo fica salvo no aparelho.

## Publicar no GitHub Pages
1. Crie um repositório e envie estes arquivos na raiz.
2. Settings > Pages > Deploy from a branch > `main` / root.
3. Abra `https://SEU-USUARIO.github.io/NOME-DO-REPO/` no celular e use "Instalar app" / "Adicionar à tela inicial".

## Usar
1. Em Configurações, escolha o provedor e cole a chave: Gemini (grátis, aistudio.google.com/apikey) ou Anthropic (paga). A chave fica só no seu aparelho. No Gemini gratuito não há busca na web.
2. Nova música > Buscar na internet (ou Colar cifras) > Gerar.

## Virar APK
Com o site no ar, use https://www.pwabuilder.com, cole a URL e baixe o pacote Android.

## Dica sobre colar cifras
Copie o texto da cifra (acordes em cima da letra). Funciona bem porque o app mostra em fonte monoespaçada e preserva os espaços.

## Sem gastar e sem IA
Em "Colar cifras" há o botão "Gerar sem IA": o app deriva as versões simples e intermediária da cifra avançada por regras (tira extensões e baixos invertidos, mantendo o alinhamento). Funciona offline.
