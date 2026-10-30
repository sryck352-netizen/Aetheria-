# Aetheria: Ecos da Aurora — Android

Este repositório prepara a **compilação automática de um APK do protótipo Godot 4**.

**Importante:** o projeto 3D atual (Protótipo 03) é uma versão técnica provisória. Ele ainda **não é o RPG cinematográfico completo** aprovado nas 18 etapas. O modelo definitivo e as animações de Nóctis ainda não foram concluídos.

## Como gerar o APK usando o Chrome

1. Envie para a raiz deste repositório o arquivo `Aetheria_Noctis_3D_Proto03_Com_Musica.zip` do projeto original. O arquivo precisa manter exatamente esse nome.
2. No GitHub, abra **Actions → Aetheria - APK Android → Run workflow**. O envio do ZIP para a branch `main` também inicia a compilação.
3. Espere a execução terminar com sucesso. Em **Releases**, aparecerá uma versão de **teste**, com o APK para Android.
4. Baixe o APK pelo Chrome e instale no celular, autorizando instalações dessa origem quando solicitado.

Se o processo falhar, abra a execução vermelha em **Actions** para ver a mensagem do compilador. Não existe APK até uma execução concluir com sucesso.

## Arquivos necessários

- `Aetheria_Noctis_3D_Proto03_Com_Musica.zip` — necessário, ainda não enviado;
- `.github/workflows/aetheria-android.yml` — automação de compilação;
- `README.md` — instruções.

## Limites atuais

- O trabalho anterior contém um modelo 3D base para Nóctis, terreno, combate inicial e música na tela de abertura.
- Ainda não possui o personagem cinematográfico definitivo, todas as animações, regiões ou sistemas completos.
- A compilação e o funcionamento no Galaxy A15 precisam ser comprovados por testes.
- Antes de distribuir publicamente os modelos e a música extraída do vídeo, confirme que possui os direitos necessários.

**Não confundir o APK de teste com o jogo completo.**
