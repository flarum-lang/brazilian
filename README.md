# Português do Brasil

## ⚠️ | *Aviso de Tradução*

*Este repositório é mantido por uma única pessoa, que **não é um tradutor profissional**. Embora tenhamos feito o nosso melhor para garantir a precisão, podem ocorrer erros de tradução. Pedimos desculpas por qualquer confusão que isso possa causar e agradecemos a sua compreensão. Se você encontrar algum erro ou problema de tradução, sinta-se à vontade para abrir [uma solicitação aqui](https://weblate.rob006.net/projects/flarum/). Obrigado por sua colaboração!* 

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

* [Weblate](https://weblate.rob006.net/projects/flarum/) - Plataforma para moderação de traduções.

## 🖇️ | Erros/Bugs

Caso encontre um erro ou bug abra uma solicitação  [aqui](https://github.com/flarum-lang/brazilian/issues/new) e escreva os detalhes sobre o erro .


## 🚀 | Tradução Flarum/core

| componente | Status |
| --- | --- |
| [Core](https://github.com/flarum/flarum-core) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pt_BR/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/core/pt_BR/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum/pt_BR/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/validation/pt_BR/) |


## 🚀 | Tradução extensões oficiais flarum

<!-- flarum-extensions-list-start -->

| Extensão | Status |
| --- | --- |
| [`flarum/akismet`](https://github.com/flarum/akismet) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-akismet/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-akismet/pt_BR/) |
| [`flarum/approval`](https://github.com/flarum/approval) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-approval/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-approval/pt_BR/) |
| [`flarum/bbcode`](https://github.com/flarum/bbcode) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-bbcode/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-bbcode/pt_BR/) |
| [`flarum/emoji`](https://github.com/flarum/emoji) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-emoji/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-emoji/pt_BR/) |
| [`flarum/flags`](https://github.com/flarum/flags) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-flags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-flags/pt_BR/) |
| [`flarum/gdpr`](https://github.com/flarum/gdpr) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-gdpr/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-gdpr/pt_BR/) |
| [`flarum/likes`](https://github.com/flarum/likes) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-likes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-likes/pt_BR/) |
| [`flarum/lock`](https://github.com/flarum/lock) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-lock/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-lock/pt_BR/) |
| [`flarum/markdown`](https://github.com/flarum/markdown) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-markdown/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-markdown/pt_BR/) |
| [`flarum/mentions`](https://github.com/flarum/mentions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-mentions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-mentions/pt_BR/) |
| [`flarum/nicknames`](https://github.com/flarum/nicknames) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-nicknames/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-nicknames/pt_BR/) |
| [`flarum/pusher`](https://github.com/flarum/pusher) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-pusher/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-pusher/pt_BR/) |
| [`flarum/statistics`](https://github.com/flarum/statistics) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-statistics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-statistics/pt_BR/) |
| [`flarum/sticky`](https://github.com/flarum/sticky) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-sticky/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-sticky/pt_BR/) |
| [`flarum/subscriptions`](https://github.com/flarum/subscriptions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-subscriptions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-subscriptions/pt_BR/) |
| [`flarum/suspend`](https://github.com/flarum/suspend) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-suspend/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-suspend/pt_BR/) |
| [`flarum/tags`](https://github.com/flarum/tags) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/flarum-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-tags/pt_BR/) |

<!-- flarum-extensions-list-stop -->


## 🚀 | Tradução para extensões Friends of Flarum

<!-- fof-extensions-list-start -->

| Extensão | Status |
| --- | --- |
| [`fof/best-answer`](https://github.com/FriendsOfFlarum/best-answer) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-best-answer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-best-answer/pt_BR/) |
| [`fof/byobu`](https://github.com/FriendsOfFlarum/byobu) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-byobu/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-byobu/pt_BR/) |
| [`fof/custom-footer`](https://github.com/FriendsOfFlarum/custom-footer) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-custom-footer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-custom-footer/pt_BR/) |
| [`fof/default-group`](https://github.com/FriendsOfFlarum/default-group) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-default-group/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-default-group/pt_BR/) |
| [`fof/discussion-templates`](https://github.com/FriendsOfFlarum/discussion-templates) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-discussion-templates/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-discussion-templates/pt_BR/) |
| [`fof/discussion-thumbnail`](https://github.com/FriendsOfFlarum/discussion-thumbnail) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-discussion-thumbnail/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-discussion-thumbnail/pt_BR/) |
| [`fof/disposable-emails`](https://github.com/FriendsOfFlarum/disposable-emails) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-disposable-emails/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-disposable-emails/pt_BR/) |
| [`fof/doorman`](https://github.com/FriendsOfFlarum/doorman) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-doorman/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-doorman/pt_BR/) |
| [`fof/follow-tags`](https://github.com/FriendsOfFlarum/follow-tags) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-follow-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-follow-tags/pt_BR/) |
| [`fof/formatting`](https://github.com/FriendsOfFlarum/formatting) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-formatting/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-formatting/pt_BR/) |
| [`fof/forum-statistics-widget`](https://github.com/FriendsOfFlarum/forum-statistics-widget) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-forum-statistics-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-forum-statistics-widget/pt_BR/) |
| [`fof/frontpage`](https://github.com/FriendsOfFlarum/frontpage) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-frontpage/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-frontpage/pt_BR/) |
| [`fof/gamification`](https://github.com/FriendsOfFlarum/gamification) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-gamification/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-gamification/pt_BR/) |
| [`fof/links`](https://github.com/FriendsOfFlarum/links) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-links/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-links/pt_BR/) |
| [`fof/moderator-notes`](https://github.com/FriendsOfFlarum/moderator-notes) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-moderator-notes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-moderator-notes/pt_BR/) |
| [`fof/moderator-warnings`](https://github.com/FriendsOfFlarum/moderator-warnings) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-moderator-warnings/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-moderator-warnings/pt_BR/) |
| [`fof/oauth`](https://github.com/FriendsOfFlarum/oauth) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-oauth/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-oauth/pt_BR/) |
| [`fof/pages`](https://github.com/FriendsOfFlarum/pages) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-pages/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-pages/pt_BR/) |
| [`fof/polls`](https://github.com/FriendsOfFlarum/polls) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-polls/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-polls/pt_BR/) |
| [`fof/prevent-necrobumping`](https://github.com/FriendsOfFlarum/prevent-necrobumping) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-prevent-necrobumping/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-prevent-necrobumping/pt_BR/) |
| [`fof/reactions`](https://github.com/FriendsOfFlarum/reactions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-reactions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-reactions/pt_BR/) |
| [`fof/recaptcha`](https://github.com/FriendsOfFlarum/recaptcha) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-recaptcha/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-recaptcha/pt_BR/) |
| [`fof/sitemap`](https://github.com/FriendsOfFlarum/sitemap) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-sitemap/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-sitemap/pt_BR/) |
| [`fof/socialprofile`](https://github.com/FriendsOfFlarum/socialprofile) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-socialprofile/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-socialprofile/pt_BR/) |
| [`fof/split`](https://github.com/FriendsOfFlarum/split) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-split/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-split/pt_BR/) |
| [`fof/subscribed`](https://github.com/FriendsOfFlarum/subscribed) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-subscribed/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-subscribed/pt_BR/) |
| [`fof/terms`](https://github.com/FriendsOfFlarum/terms) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-terms/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-terms/pt_BR/) |
| [`fof/upload`](https://github.com/FriendsOfFlarum/upload) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-upload/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-upload/pt_BR/) |
| [`fof/user-bio`](https://github.com/FriendsOfFlarum/user-bio) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-user-bio/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-user-bio/pt_BR/) |
| [`fof/user-directory`](https://github.com/FriendsOfFlarum/user-directory) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/fof-user-directory/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-user-directory/pt_BR/) |

<!-- fof-extensions-list-stop -->


## 🚀 | Tradução para extensões da comunidade

<!-- various-extensions-list-start -->

| Extensão | Status |
| --- | --- |
| [`acpl/mobile-tab`](https://github.com/android-com-pl/mobile-tab) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/acpl-mobile-tab/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/acpl-mobile-tab/pt_BR/) |
| [`archlinux-de/flarum-click-image`](https://github.com/archlinux-de/flarum-click-image) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/archlinux-de-click-image/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/archlinux-de-click-image/pt_BR/) |
| [`askvortsov/flarum-markdown-tables`](https://github.com/askvortsov1/flarum-markdown-tables) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/askvortsov-markdown-tables/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-markdown-tables/pt_BR/) |
| [`askvortsov/flarum-rich-text`](https://github.com/askvortsov1/flarum-rich-text) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/askvortsov-rich-text/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-rich-text/pt_BR/) |
| [`blomstra/mark-unread`](https://github.com/blomstra/flarum-ext-mark-unread) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/blomstra-mark-unread/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/blomstra-mark-unread/pt_BR/) |
| [`blomstra/sort-order-toggle`](https://github.com/blomstra/flarum-ext-sort-order-toggle) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/blomstra-sort-order-toggle/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/blomstra-sort-order-toggle/pt_BR/) |
| [`clarkwinkelmann/flarum-ext-emojionearea`](https://github.com/clarkwinkelmann/flarum-ext-emojionearea) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/clarkwinkelmann-emojionearea/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-emojionearea/pt_BR/) |
| [`clarkwinkelmann/flarum-ext-formatted-banner`](https://github.com/clarkwinkelmann/flarum-ext-formatted-banner) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/clarkwinkelmann-formatted-banner/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-formatted-banner/pt_BR/) |
| [`datlechin/flarum-remove-sidenav`](https://github.com/datlechin/flarum-remove-sidenav) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/datlechin-remove-sidenav/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-remove-sidenav/pt_BR/) |
| [`datlechin/flarum-signup-button`](https://github.com/datlechin/flarum-signup-button) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/datlechin-signup-button/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-signup-button/pt_BR/) |
| [`datlechin/flarum-usercard-uid`](https://github.com/datlechin/flarum-usercard-uid) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/datlechin-usercard-uid/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-usercard-uid/pt_BR/) |
| [`extiverse/mercury`](https://github.com/extiverse/mercury) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/extiverse-mercury/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/extiverse-mercury/pt_BR/) |
| [`justoverclock/discussion-hero-showtags`](https://github.com/justoverclockl/discussion-hero-showtags) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/justoverclock-discussion-hero-showtags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-discussion-hero-showtags/pt_BR/) |
| [`justoverclock/hot-discussions`](https://github.com/justoverclockl/hot-discussions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/justoverclock-hot-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-hot-discussions/pt_BR/) |
| [`justoverclock/last-post-useravatar`](https://github.com/justoverclockl/last-post-useravatar) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/justoverclock-last-post-useravatar/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-last-post-useravatar/pt_BR/) |
| [`malago/flarum-achievements`](https://github.com/malago86/flarum-achievements) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/malago-achievements/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/malago-achievements/pt_BR/) |
| [`michaelbelgium/flarum-discussion-views`](https://github.com/MichaelBelgium/flarum-discussion-views) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/michaelbelgium-discussion-views/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/michaelbelgium-discussion-views/pt_BR/) |
| [`migratetoflarum/fake-data`](https://github.com/migratetoflarum/fake-data) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/migratetoflarum-fake-data/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/migratetoflarum-fake-data/pt_BR/) |
| [`miniflar/top-like-givers-widget`](https://github.com/miniflar/top-like-givers-widget) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/miniflar-top-like-givers-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/miniflar-top-like-givers-widget/pt_BR/) |
| [`nearata/flarum-ext-copy-code-to-clipboard`](https://github.com/Nearata/flarum-ext-copy-code-to-clipboard) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-copy-code-to-clipboard/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-copy-code-to-clipboard/pt_BR/) |
| [`nearata/flarum-ext-embed-video`](https://github.com/Nearata/flarum-ext-embed-video) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-embed-video/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-embed-video/pt_BR/) |
| [`nearata/flarum-ext-maintenance-mode`](https://github.com/Nearata/flarum-ext-maintenance-mode) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-maintenance-mode/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-maintenance-mode/pt_BR/) |
| [`nearata/flarum-ext-minecraft-avatars`](https://github.com/Nearata/flarum-ext-minecraft-avatars) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-minecraft-avatars/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-minecraft-avatars/pt_BR/) |
| [`nearata/flarum-ext-password-strength-enforcer`](https://github.com/Nearata/flarum-ext-password-strength-enforcer) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-password-strength-enforcer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-password-strength-enforcer/pt_BR/) |
| [`nearata/flarum-ext-related-discussions`](https://github.com/Nearata/flarum-ext-related-discussions) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-related-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-related-discussions/pt_BR/) |
| [`nearata/flarum-ext-signup-confirm-password`](https://github.com/Nearata/flarum-ext-signup-confirm-password) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-signup-confirm-password/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-signup-confirm-password/pt_BR/) |
| [`nearata/flarum-ext-tags-color-generator`](https://github.com/Nearata/flarum-ext-tags-color-generator) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-tags-color-generator/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-tags-color-generator/pt_BR/) |
| [`nearata/flarum-ext-twofactor`](https://github.com/Nearata/flarum-ext-twofactor) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nearata-twofactor/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-twofactor/pt_BR/) |
| [`neoncube/flarum-private-messages`](https://github.com/neoncube2/flarum-private-messages) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/neoncube-private-messages/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/neoncube-private-messages/pt_BR/) |
| [`nomiscz/flarum-ext-auth-steam`](https://github.com/NomisCZ/flarum-ext-auth-steam) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nomiscz-auth-steam/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nomiscz-auth-steam/pt_BR/) |
| [`nomiscz/flarum-ext-auth-wechat`](https://github.com/NomisCZ/flarum-ext-auth-wechat) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/nomiscz-auth-wechat/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nomiscz-auth-wechat/pt_BR/) |
| [`ralkage/flarum-hcaptcha`](https://github.com/Ralkage/flarum-hcaptcha) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/ralkage-hcaptcha/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/ralkage-hcaptcha/pt_BR/) |
| [`serakoi/flarum-hideprofile`](https://github.com/Serakoi/flarum-hideprofile) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/serakoi-hideprofile/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/serakoi-hideprofile/pt_BR/) |
| [`sycho/flarum-profile-cover`](https://github.com/SychO9/flarum-profile-cover) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/sycho-profile-cover/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/sycho-profile-cover/pt_BR/) |
| [`v17development/flarum-blog`](https://github.com/v17development/flarum-blog) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/v17development-blog/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/v17development-blog/pt_BR/) |
| [`v17development/flarum-seo`](https://github.com/FriendsOfFlarum/seo) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/v17development-seo/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/v17development-seo/pt_BR/) |

<!-- various-extensions-list-stop -->


## 🚀 | Tradução de extensões premium

<!-- premium-extensions-list-start -->

| Extensão | Status |
| --- | --- |
| [`justoverclock/website-live-screenshot`](https://flarum.org/extension/justoverclock/website-live-screenshot) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/justoverclock-website-live-screenshot/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-website-live-screenshot/pt_BR/) |
| [`v17development/flarum-support`](https://flarum.org/extension/v17development/flarum-support) | [![Status da tradução](https://weblate.rob006.net/widgets/flarum/pt_BR/v17development-support/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/v17development-support/pt_BR/) |

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
