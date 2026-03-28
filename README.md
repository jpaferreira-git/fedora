# 🌌 Fedora Niri Dotfiles - João Ferreira

Bem-vindo ao repositório das minhas configurações pessoais (dotfiles) para o Fedora Workstation, rodando o compositor **Niri (Wayland)**.

Este setup foi construído com foco em minimalismo, elegância e produtividade, combinando a estabilidade do Fedora com a fluidez de um compositor Wayland de "tilting" moderno.

---

## 📸 Showcase

Aqui está uma visão geral do meu desktop atualizado:

<p align="center">
  <img src="images/fedora-niri-preview.png" width="90%" alt="Screenshot do Desktop do João Ferreira">
</p>

### 🛠️ Especificações do Setup:

* **OS:** Fedora Linux
* **Compositor:** Niri (Wayland)
* **Top Bar (Painel):** Waybar (com CSS personalizado)
* **Dock:** Plank (com tema de cantos arredondados)
* **Wallpaper:** Space Nebula Nebula (Azul/Roxo) - Incluído no repositório.
* **Tema de Ícones:** Papirus-Dark (ou similar visível na dock)

---

## 📂 O que tem aqui?

* `config.kdl`: O arquivo principal de configuração do Niri (atalhos de teclado, layouts, etc.).

---

## 🚀 Como Aplicar

Se você já tem o Niri instalado no seu Fedora, siga estes passos para usar a minha configuração:

1.  Faça backup da sua configuração atual:
    ```bash
    mv ~/.config/niri/config.kdl ~/.config/niri/config.kdl.bak
    ```

2.  Clone este repositório na sua pasta de Projetos e copie o arquivo:
    ```bash
    git clone git@github.com:jpaferreira-git/fedora.git
    cp fedora/config.kdl ~/.config/niri/
    ```

3.  O Niri deve recarregar as configurações automaticamente. Se não, reinicie a sessão.

> **Nota:** Para o setup ficar idêntico ao screenshot, você precisará também das minhas configurações de Waybar e Plank (que pretendo adicionar em breve!).

---

## 💙 Créditos e Agradecimentos

* Ao projeto [Niri](https://github.com/YaLTeR/niri) pelo compositor fantástico.
* À comunidade Fedora pela melhor distribuição Linux.

---
