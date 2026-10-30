# Aetheria: Ecos da Aurora — protótipo Android

O projeto Godot 4 **Proto03** já foi enviado ao GitHub, com cenário 3D, personagem-base Nóctis, Aria, inimigo, interface e música de abertura.

## Baixar APK no Chrome

Depois que a compilação do GitHub Actions terminar com sucesso, o instalador será publicado aqui:

**https://github.com/sryck352-netizen/Aetheria-/releases**

Na versão `aetheria-proto03-android`, escolha **Aetheria-Noctis-Android.apk** (não selecione o Source code ZIP).

**Importante:** o link só funcionará depois de uma compilação bem-sucedida. Consulte o estado em [Actions](https://github.com/sryck352-netizen/Aetheria-/actions).

## Como o projeto foi armazenado

Os 7,5 MB do arquivo ZIP original foram divididos em 20 partes Base64 na pasta `archive_parts/`. O GitHub Actions reconstrói o arquivo original e verifica o SHA-256:

`ee5ab25028cdf8838e0f364f551cfdb7764bd0abec9923a913551b3d93cda748`.

Depois utiliza Godot 4.4.1 para importar o projeto e tentar exportar o APK Android.

## Limitações da versão

**Isto ainda é um protótipo técnico, não o RPG cinematográfico completo das 18 etapas.**

- Não é o modelo 3D definitivo de Nóctis: mantém a versão provisória rejeitada como visual final.
- Ainda faltam rig e animações articuladas, grande parte do mundo, chefes, outros personagens e sistemas completos.
- O funcionamento no Galaxy A15 ainda depende de testes no dispositivo.
- A música foi extraída do vídeo fornecido pelo criador. Antes de distribuir publicamente o APK, confirme que possui os direitos necessários sobre o áudio.

Para desenvolvimento futuro, não publique como versão final até a aprovação visual e os testes de jogabilidade.
