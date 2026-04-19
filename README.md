# Português do Brasil

## ⚠️ | *Aviso de Tradução*

*Este repositório é mantido por uma única pessoa, que **não é um tradutor profissional**. Embora tenhamos feito o nosso melhor para garantir a precisão, podem ocorrer erros de tradução. Pedimos desculpas por qualquer confusão que isso possa causar e agradecemos a sua compreensão. Se você encontrar algum erro ou problema de tradução, sinta-se à vontade para abrir [uma solicitação aqui](https://weblate.rob006.net/projects/flarum2/). Obrigado por sua colaboração!* 

Extensão para Tradução do **[Flarum](https://flarum.org)** para **Português do Brasil**.
## 🚀 | Começando

Essas instruções permitirão que você obtenha a extensão para traduzir sua instância Flarum. 


### 📋 | Pré-requisitos

Você deve seguir os [requisitos de instalação do Flarum](https://docs.flarum.org/install.html) e obrigatoriamente possuir acesso **SSH no servidor**.

> **Hospedagem Compartilhada**:
Não é possível instalar o Flarum baixando um arquivo ZIP e enviando os arquivos para o seu servidor web. Isso ocorre porque o Flarum usa um sistema de gerenciamento de dependências chamado [Composer ](https://getcomposer.org/)que precisa ser executado na linha de comando.

>Isso não significa necessariamente que você precisa de um VPS. A maioria dos hosts decentes suporta acesso SSH, por meio do qual você deve conseguir instalar o Composer e o Flarum sem problemas.

## 🔧 | Instalação

Utilize os comandos abaixo para realizar a instalação da extensão Português do Brasil em sua instância Flarum.

Utilize o comando:

```
composer require "flarum-lang/brazilian:*"
```

Em seguida:

```
php flarum cache:clear
```

Após o termino do processo, basta entrar na **Administração** e ativar a extensão ;) .


### 🆕 | Atualizando

Para realizar a atualização da extensão, utilize os comandos abaixo:

    composer update flarum-lang/brazilian
&

    php flarum cache:clear

## 🛠️ |  Contribua

Contribua com a tradução Português do Brasil acessando o link e se registrando na plataforma abaixo:

* [Weblate](https://weblate.rob006.net/projects/flarum2/) - Plataforma para moderação de traduções.

## 🖇️ | Erros/Bugs

Caso encontre um erro ou bug abra uma solicitação  [aqui](https://github.com/flarum-lang/brazilian/issues/new) e escreva os detalhes sobre o erro .


## 🚀 | Tradução Flarum/core

| componente | Status |
| --- | --- |
| [Core](https://github.com/flarum/flarum-core) | [![Translation status](https://weblate.rob006.net/widgets/flarum2/pt_BR/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/core/pt_BR/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum2/pt_BR/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/validation/pt_BR/) |


## 🚀 | Tradução extensões oficiais flarum

<!-- flarum-extensions-list-start -->

| Extensão | Status |
| --- | --- |
| [`flarum/akismet`](https://github.com/flarum/akismet) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-akismet/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-akismet/pt_BR/) |
| [`flarum/approval`](https://github.com/flarum/approval) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-approval/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-approval/pt_BR/) |
| [`flarum/bbcode`](https://github.com/flarum/bbcode) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-bbcode/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-bbcode/pt_BR/) |
| [`flarum/emoji`](https://github.com/flarum/emoji) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-emoji/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-emoji/pt_BR/) |
| [`flarum/flags`](https://github.com/flarum/flags) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-flags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-flags/pt_BR/) |
| [`flarum/gdpr`](https://github.com/flarum/gdpr) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-gdpr/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-gdpr/pt_BR/) |
| [`flarum/likes`](https://github.com/flarum/likes) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-likes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-likes/pt_BR/) |
| [`flarum/lock`](https://github.com/flarum/lock) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-lock/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-lock/pt_BR/) |
| [`flarum/markdown`](https://github.com/flarum/markdown) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-markdown/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-markdown/pt_BR/) |
| [`flarum/mentions`](https://github.com/flarum/mentions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-mentions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-mentions/pt_BR/) |
| [`flarum/nicknames`](https://github.com/flarum/nicknames) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-nicknames/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-nicknames/pt_BR/) |
| [`flarum/pusher`](https://github.com/flarum/pusher) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-pusher/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-pusher/pt_BR/) |
| [`flarum/statistics`](https://github.com/flarum/statistics) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-statistics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-statistics/pt_BR/) |
| [`flarum/sticky`](https://github.com/flarum/sticky) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-sticky/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-sticky/pt_BR/) |
| [`flarum/subscriptions`](https://github.com/flarum/subscriptions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-subscriptions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-subscriptions/pt_BR/) |
| [`flarum/suspend`](https://github.com/flarum/suspend) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-suspend/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-suspend/pt_BR/) |
| [`flarum/tags`](https://github.com/flarum/tags) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/flarum-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-tags/pt_BR/) |

<!-- flarum-extensions-list-stop -->


## 🚀 | Tradução para extensões Friends of Flarum

<!-- fof-extensions-list-start -->

| Extensão | Status |
| --- | --- |
| [`fof/best-answer`](https://github.com/FriendsOfFlarum/best-answer) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-best-answer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-best-answer/pt_BR/) |
| [`fof/byobu`](https://github.com/FriendsOfFlarum/byobu) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-byobu/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-byobu/pt_BR/) |
| [`fof/default-group`](https://github.com/FriendsOfFlarum/default-group) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-default-group/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-default-group/pt_BR/) |
| [`fof/discussion-templates`](https://github.com/FriendsOfFlarum/discussion-templates) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-discussion-templates/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-discussion-templates/pt_BR/) |
| [`fof/discussion-thumbnail`](https://github.com/FriendsOfFlarum/discussion-thumbnail) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-discussion-thumbnail/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-discussion-thumbnail/pt_BR/) |
| [`fof/disposable-emails`](https://github.com/FriendsOfFlarum/disposable-emails) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-disposable-emails/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-disposable-emails/pt_BR/) |
| [`fof/follow-tags`](https://github.com/FriendsOfFlarum/follow-tags) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-follow-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-follow-tags/pt_BR/) |
| [`fof/formatting`](https://github.com/FriendsOfFlarum/formatting) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-formatting/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-formatting/pt_BR/) |
| [`fof/forum-statistics-widget`](https://github.com/FriendsOfFlarum/forum-statistics-widget) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-forum-statistics-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-forum-statistics-widget/pt_BR/) |
| [`fof/frontpage`](https://github.com/FriendsOfFlarum/frontpage) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-frontpage/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-frontpage/pt_BR/) |
| [`fof/gamification`](https://github.com/FriendsOfFlarum/gamification) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-gamification/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-gamification/pt_BR/) |
| [`fof/links`](https://github.com/FriendsOfFlarum/links) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-links/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-links/pt_BR/) |
| [`fof/moderator-notes`](https://github.com/FriendsOfFlarum/moderator-notes) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-moderator-notes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-moderator-notes/pt_BR/) |
| [`fof/moderator-warnings`](https://github.com/FriendsOfFlarum/moderator-warnings) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-moderator-warnings/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-moderator-warnings/pt_BR/) |
| [`fof/oauth`](https://github.com/FriendsOfFlarum/oauth) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-oauth/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-oauth/pt_BR/) |
| [`fof/pages`](https://github.com/FriendsOfFlarum/pages) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-pages/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-pages/pt_BR/) |
| [`fof/polls`](https://github.com/FriendsOfFlarum/polls) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-polls/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-polls/pt_BR/) |
| [`fof/reactions`](https://github.com/FriendsOfFlarum/reactions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-reactions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-reactions/pt_BR/) |
| [`fof/sitemap`](https://github.com/FriendsOfFlarum/sitemap) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-sitemap/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-sitemap/pt_BR/) |
| [`fof/socialprofile`](https://github.com/FriendsOfFlarum/socialprofile) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-socialprofile/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-socialprofile/pt_BR/) |
| [`fof/split`](https://github.com/FriendsOfFlarum/split) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-split/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-split/pt_BR/) |
| [`fof/subscribed`](https://github.com/FriendsOfFlarum/subscribed) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-subscribed/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-subscribed/pt_BR/) |
| [`fof/terms`](https://github.com/FriendsOfFlarum/terms) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-terms/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-terms/pt_BR/) |
| [`fof/upload`](https://github.com/FriendsOfFlarum/upload) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-upload/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-upload/pt_BR/) |
| [`fof/user-bio`](https://github.com/FriendsOfFlarum/user-bio) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-user-bio/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-user-bio/pt_BR/) |
| [`fof/user-directory`](https://github.com/FriendsOfFlarum/user-directory) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/fof-user-directory/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-user-directory/pt_BR/) |

<!-- fof-extensions-list-stop -->


## 🚀 | Tradução para extensões da comunidade

<!-- various-extensions-list-start -->

| Extensão | Status |
| --- | --- |
| [`datlechin/flarum-signup-button`](https://github.com/datlechin/flarum-signup-button) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/datlechin-signup-button/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datlechin-signup-button/pt_BR/) |
| [`migratetoflarum/fake-data`](https://github.com/migratetoflarum/fake-data) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/migratetoflarum-fake-data/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/migratetoflarum-fake-data/pt_BR/) |
| [`ralkage/flarum-hcaptcha`](https://github.com/Ralkage/flarum-hcaptcha) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/ralkage-hcaptcha/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/ralkage-hcaptcha/pt_BR/) |
| [`sycho/flarum-profile-cover`](https://github.com/SychO9/flarum-profile-cover) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum2/pt_BR/sycho-profile-cover/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/sycho-profile-cover/pt_BR/) |

<!-- various-extensions-list-stop -->


## 🚀 | Tradução de extensões premium

<!-- premium-extensions-list-start -->

| Extensão | Status |
| --- | --- |

<!-- premium-extensions-list-stop -->


## 📌| Versão

![Versão](https://img.shields.io/github/v/release/flarum-lang/brazilian?label=VERS%C3%83O&style=for-the-badge)


## 📄 | Licença

![MIT](https://img.shields.io/github/license/flarum-lang/brazilian?label=Licen%C3%A7a&style=for-the-badge)

Este projeto está sob a licença MIT - veja o arquivo [LICENSE.md](https://github.com/flarum-lang/brazilian/blob/main/LICENSE) para detalhes.

## 🌐 | Links

-   [GitHub](https://github.com/flarum-lang/brazilian "GitHub")
-   [Packagist](https://packagist.org/packages/flarum-lang/brazilian "Packagist")
-   [Extiverse](https://extiverse.com/extension/flarum-lang/brazilian)


---
Pacote de Idioma **Português do Brasil** feito com ❤️ por [Ramon](https://ramonguilherme.com.br) 😊
