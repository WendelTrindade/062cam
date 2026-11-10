# 062 Cam

Câmera da 062 Fish controlada por voz, offline, que grava mesmo com a tela bloqueada.
Desenvolvido por Wendel Emílio de Souza Matias — oficial.respostas@gmail.com

## Comandos de voz
- "gravar" — começa a gravar (com os segundos de pré-gravação)
- "parar" — encerra e salva o vídeo
- "foto" ou "tirar foto" — tira uma foto (também durante o vídeo)
- "marca" — marca o momento durante a gravação (veja em Ajustes > Momentos marcados)
- "salva isso" — salva os últimos segundos da pré-gravação, sem estar gravando

Palavra de ativação opcional (Ajustes): "câmera gravar", "zero meia dois gravar"...

Vídeos: Filmes/062Cam · Fotos: Imagens/062Cam

## Como gerar o APK
1. Crie um repositório novo no GitHub (ex.: 062cam).
2. Envie todos os arquivos desta pasta.
3. Crie o arquivo `.github/workflows/gerar-apk.yml` pelo botão "Add file > Create new file".
4. Em Actions, rode "Gerar APK" e baixe o arquivo 062Cam-apk.

## Ligar e desligar
O app abre desligado. Toque no botão amarelo para ligar (câmera e microfone começam a funcionar).
Para desligar: botão de energia no topo da tela, "Desligar" na notificação, ou fechando o app
pela tela de apps recentes (se não estiver gravando).

## Tela escura
Com o app ligado, depois de 30 s sem tocar a tela fica preta, com brilho mínimo, mostrando só
"062 Cam ouvindo" (verde) ou "GRAVANDO 00:00" (vermelho). Toque duas vezes para voltar.

## Editor de vídeo
Toque na miniatura da galeria (ou em "Meus vídeos") e depois em "Editar".
- Zoom: cria um trecho com zoom; arraste o quadro amarelo até o ponto e escolha 1,5× a 4×.
- Lento / Acelerar: trecho em 0,25×, 0,5×, 2× ou 4×.
- Zoom e velocidade podem ficar no mesmo trecho; cada um pode ser repetido em vários trechos.
- Corte: arraste as pontas amarelas da faixa de imagens.
- Som: liga ou desliga o som do vídeo editado.
Salvar gera um vídeo novo em Filmes/062Cam; o original continua guardado.
Também dá para abrir pela galeria do celular: Compartilhar > "Editar no 062 Cam".
