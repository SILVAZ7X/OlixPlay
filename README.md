# Olix Play — Android

Primeira base do aplicativo Android do Olix Play.

## Objetivo

O app não acessa o MySQL diretamente. Ele conversa com o servidor através da API compatível, permitindo:

- login por servidor/usuário/senha;
- categorias;
- Live;
- VOD;
- base para Séries;
- reprodução via URLs do servidor;
- futura integração com uma API própria do Olix Play.

## Estrutura

- `app/src/main/java/com/olixplay/app/ApiClient.kt` — cliente da API.
- `app/src/main/java/com/olixplay/app/ui/OlixPlayApp.kt` — telas iniciais.
- `MainActivity.kt` — entrada do app.

## Próxima etapa

Adicionar:
1. player Media3;
2. tela de detalhes;
3. favoritos;
4. busca;
5. EPG;
6. histórico/continue assistindo;
7. suporte a Android TV/controle remoto;
8. armazenamento seguro da sessão;
9. tratamento de séries/temporadas/episódios;
10. identidade visual final do Olix Play.

Use apenas conteúdo e serviços para os quais você tenha autorização.
