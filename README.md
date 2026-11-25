# Anon Multistream

Estúdio para Windows x64 com transmissão e gravação horizontal e vertical, Multichat integrado, eventos, alertas, mixer de áudio e diagnóstico de saúde das lives.

Este repositório é destinado à distribuição do aplicativo. O desenvolvimento é mantido em repositório privado.

## Download

**[Baixar Anon Multistream para Windows x64](https://github.com/AnonStudioOfficial/Anon-Multistream-Downloads/releases/download/v0.6.0-beta.14/Anon-Multistream-0.6.0-beta.14-Windows-x64.zip)** · versão 0.6.0-beta.14 · aproximadamente 255 MB.

[Notas da versão e checksum](https://github.com/AnonStudioOfficial/Anon-Multistream-Downloads/releases/tag/v0.6.0-beta.14). Os arquivos automáticos “Source code” desta página de distribuição não são o aplicativo.

## Xbox Remote Play experimental

Adicione uma fonte Xbox para conectar seu console, jogar em uma janela separada e usar imagem e áudio nas cenas. O áudio aparece no canal JOGO. O modo Automático é recomendado; a janela **Qualidade recebida · detalhes** mostra resolução, FPS, bitrate, perdas e tempo de decodificação quando disponíveis. Inclui reconexão e redução de consultas repetidas na conexão.

Esta integração não é oficial Microsoft. A qualidade depende do console e da rede; acesso fora da rede local ainda exige validação. Métricas Xbox não são gravadas no relatório geral.

A beta.14 também corrige a confirmação do status do chat Instagram e isola os destinos do repasse com filas e recuperação independentes.

## Gravação local

O botão **Gravar** permite gravar horizontal, vertical ou ambos em arquivos MKV separados, sem iniciar uma live. Em **Configurações → Gravação**, escolha pasta, nome, encoder, controle de qualidade e canais de áudio. Modos CQP/CRF, VBR, CBR e ABR aparecem conforme o encoder disponível. Resolução e FPS acompanham o estúdio.

## Instalação

1. Baixe o ZIP do aplicativo e extraia a pasta inteira para uma pasta local.
2. Execute `Anon Multistream.exe` dentro da pasta extraída.
3. Configure suas próprias plataformas, cenas e dispositivos de áudio.

Requer Windows x64 e Microsoft Edge WebView2 Runtime. Esta é uma versão **Beta**: faça um teste de vídeo, áudio e conexão antes da primeira transmissão.

## Atualizar preservando contas e cenas

Feche o Anon e faça uma cópia da pasta `data` antes de atualizar. Preserve essa pasta no mesmo usuário/computador. O ZIP público começa sem dados pessoais; credenciais protegidas pelo Windows não são transferíveis para outro usuário ou computador.

## Privacidade

O pacote compartilhável começa sem contas, chaves, cookies ou cenas pessoais. Depois de usar o aplicativo, a pasta `data` conterá suas configurações e dados privados; compartilhe apenas o ZIP original, nunca sua pasta de uso.

## Reportar problemas

Abra uma Issue com a versão, os passos para reproduzir e o comportamento esperado. Não envie credenciais, cookies, chaves de transmissão, URLs pareadas nem sua pasta de dados.
