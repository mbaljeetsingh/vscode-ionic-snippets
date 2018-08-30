# Ionic Snippets for VS Code

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version-short/fivethree.vscode-ionic-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/fivethree.vscode-ionic-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)

Visual Studio Code Extension adds TypeScript and HTML snippets for Ionic v4.

All code snippets are based on and follow the Angular style guide [Ionic v4 Api](https://beta.ionicframework.com/docs/api).

## Using Snippets for Ionic v4

Type part of a snippet, press enter, and the snippet unfolds.

### Overview
* [Snippet Prefix](https://github.com/fivethree-team/vscode-ionic-snippets#snippet-prefix)
* [HTML Snippets](https://github.com/fivethree-team/vscode-ionic-snippets#html-snippets)
* [HTML Properties](https://github.com/fivethree-team/vscode-ionic-snippets#html-properties)
* [SCSS Snippets](https://github.com/fivethree-team/vscode-ionic-snippets#scss-snippets)
* [Typescript Snippets](https://github.com/fivethree-team/vscode-ionic-snippets#typescript-snippets)

### Snippet Prefix

| Prefix | Description |
| ------- | ----------|
| `i-` | Ionic Snippets |

### HTML Snippets

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-app`                | `<ion-app>`                                                    |
| `i-avatar`                | `<ion-avatar>`                                                    |
| `i-back-button`                | `<ion-back-button>`                                                    |
| `i-back-button-default`                | `<ion-back-button>` w/ defaultHref                                                |
| `i-backdrop`                | `<ion-backdrop>`                                                    |
| `i-badge`                | `<ion-badge>`                                                    |
| `i-button`                | `<ion-button>`                                                    |
| `i-button-icon-only`                | `<ion-button>` icon only                                                    |
| `i-button-w-icon`                | `<ion-button>` w/ icon                                                    |
| `i-buttons`                | `<ion-buttons>`                                                    |
| `i-card`                | `<ion-card>`                                                    |
| `i-card-content`                | `<ion-card-content>`                                                    |
| `i-card-header`                | `<ion-card-header>`                                                    |
| `i-card-subtitle`                | `<ion-card-subtitle>`                                                    |
| `i-card-title`                | `<ion-card-title>`                                                    |
| `i-checkbox`                | `<ion-checkbox>`                                                    |
| `i-chip`                | `<ion-chip>`                                                    |
| `i-chip-button`                | `<ion-chip-button>`                                                    |
| `i-chip-icon`                | `<ion-chip>` w/ `<ion-icon>` at the start                                                    |
| `i-chip-icon-end`                | `<ion-chip>` w/ `<ion-icon>` at the end                                                  |
| `i-col`                | `<ion-col>`                                                    |
| `i-content`                | `<ion-content>`                                                    |
| `i-content-events`                | `<ion-content>` w/ events                                                    |
| `i-datetime`                | `<ion-datetime>`                                                |
| `i-fab`                | `<ion-fab>` w/ `<ion-fab-button>`                                                    |
| `i-footer`                | `<ion-footer>`                                                    |
| `i-form`                | `<ion-form>` w/ `<ion-input>` and formGroup                                                    |
| `i-form-error`                | `<ion-form>` w/ `<ion-input>` and formGroup including error text                                                    |
| `i-form-input`                | `<ion-item>` w/ `<ion-input>` and formControlName                                                    |
| `i-form-input-error`                | `<ion-item>` w/ `<ion-input>` and formControlName including error text                                                    |
| `i-grid`                | `<ion-grid>` w/ `<ion-row>` and `<ion-col>`                                                    |
| `i-header`                | `<ion-header>`                                                   |
| `i-hide-when-mode`                | `<ion-hide-when>` w/ mode                                                   |
| `i-hide-when-orientation`                | `<ion-hide-when>` w/ orientation                                                   |
| `i-hide-when-platform`                | `<ion-hide-when>` w/ platform                                                   |
| `i-hide-when-size`                | `<ion-hide-when>` w/ size                                                   |
| `i-icon`                | `<ion-icon>`                                                    |
| `i-item`                | `<ion-item>` w/ `<ion-label>`                                                    |
| `i-item-checkbox`                | `<ion-item>` w/ `<ion-checkbox>`                                                    |
| `i-item-input`                | `<ion-item>` w/ `<ion-input>`                                                    |
| `i-item-toggle`                | `<ion-item>` w/ `<ion-toggle>`                                                    |
| `i-item-radio`                | `<ion-item>` w/ `<ion-radio>`                                                    |
| `i-list`                | `<ion-item>` w/ two `<ion-item>`                                                    |
| `i-list-input`                | `<ion-item>` w/ two `<ion-item>`                                                    |
| `i-menu`                | `<ion-menu>` w/ `<ion-header>` and `<ion-content>`                                                   |
| `i-menu-advanced`                | `<ion-menu>` w/ `<ion-header>`, `<ion-content>` and `<ion-footer>`                                                    |
| `i-menu-button`                | `<ion-menu-button>`                                                    |
| `i-row`                | `<ion-row>` w/ `<ion-col>`                                                   |
| `i-select`                | `<ion-select>` w/ `<ion-select-option>`                                                   |
| `i-select-option`                | `<ion-select-option>`                                                   |
| `i-show-when-mode`                | `<ion-show-when>` w/ mode                                                   |
| `i-show-when-orientation`                | `<ion-show-when>` w/ orientation                                                   |
| `i-show-when-platform`                | `<ion-show-when>` w/ platform                                                   |
| `i-show-when-size`                | `<ion-show-when>` w/ size                                                   |
| `i-skeleton-text`                | `<ion-skeleton-text>`                                                   |
| `i-slide`                | `<ion-slide>`                                                   |
| `i-slides`                | `<ion-slides>` w/ `<ion-slide>`                                                |
| `i-spinner`                | `<ion-spinner>`                                              |
| `i-split-pane`                | `<ion-split-pane>`                                              |
| `i-split-pane-advanced`                | `<ion-split-pane>` w/ a menu including `<ion-header>`, `<ion-content>` and `<ion-footer>`                                           |
| `i-tab`                | `<ion-tab>`                                              |
| `i-tabs`                | `<ion-tabs>`                                              |
| `i-text`                | `<ion-text>`                                              |
| `i-textarea`                | `<ion-textarea>`                                              |
| `i-thumbnail`                | `<ion-thumbnail>`                                              |
| `i-title`                | `<ion-title>`                                              |
| `i-toggle`                | `<ion-toggle>`                                              |
| `i-toolbar`                | `<ion-toolbar>`                                              |

### HTML Properties

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-click`                | (click) event                                              |
| `i-scrollEvents`                | Ionic [scrollEvents] binding for `<ion-content>`                                          |
| `i-size`                | Ionic `<ion-col>` `[size]` property selection                                 |
| `i-slot`                | Ionic slot property                                  |

### SCSS Snippets

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-root`                | `:root { }`                                                    |
| `i-var`                | Ionic scss variables w/ color selection                                                    |
| `i-common`                | `ion-*{*/#common-overrides/*}`                                                    |

### Typescript Snippets

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-action-sheet`                | Ionic action sheet dialog method                                                  |
| `i-action-sheet-ctrl`                | Ionic ActionSheetController    |
| `i-alert`                | Ionic alert dialog method                                                  |
| `i-alert-confirm`                | Ionic alert confirm dialog method                                                  |
| `i-alert-ctrl`                | Ionic AlertController                                                 |
| `i-form`                | Simple form group                                                 |
| `i-form-builder`                | FormBuilder                                                 |
| `i-form-group`                | FormGroup instance                                                 |
| `i-form-value`                | Get value for formControlName `form.get('email')`                                               |
| `i-ctrl-import`                | Imports from `@ionic/angular` package                                               |
| `i-modal`                | Ionic modal dialog method                                                 |
| `i-modal-ctrl`                | Ionic ModalController                                                 |
| `i-popover`                | Ionic popover dialog method                                                 |
| `i-popover-ctrl`                | Ionic PopoverController                                                 |
| `i-toast`                | Ionic toast notification method                                                 |
| `i-toast-ctrl`                | Ionic ToastController                                                 |

