# DARK STUDIO AI

Estúdio gratuito de produção de vídeos dark, executado no navegador.

## Recursos do MVP
- Dividir roteiro em cenas por parágrafos (ou frases, se houver apenas um parágrafo).
- Editar texto e duração de cada cena.
- Adicionar imagem/vídeo local por cena para a prévia e montagem.
- Prévia de narração com Speech Synthesis do navegador.
- Gerar e baixar legendas SRT.
- Exportar/importar projetos JSON e salvar no armazenamento local.
- Renderizar vídeo WebM com Canvas + MediaRecorder, com trilha de áudio local opcional.
- Layout responsivo.

## Publicar na Vercel
1. Envie estes arquivos para a raiz do repositório GitHub `Ezequielesf/dark-studio-ai`.
2. Na Vercel, importe esse repositório.
3. Use as configurações padrão para site estático, sem build command.
4. Clique em Deploy.

## Limitações atuais
- A renderização ocorre no navegador. Mantenha a aba aberta.
- A exportação é WebM; MP4 não é garantido. A conversão para MP4 não está implementada.
- A prévia de voz não é incorporada ao vídeo exportado. A trilha de áudio é um arquivo separado escolhido pelo usuário.
- Arquivos de mídia locais não são embutidos no JSON; selecione-os novamente após importar.
- Os projetos são salvos localmente; login e sincronização Supabase ainda não estão implementados.
- Geração de roteiro/imagens por IA, tendências e publicação no YouTube ainda não estão implementadas.
- Use apenas mídia que você tenha direito de usar. Nenhuma API key é necessária para o MVP.
