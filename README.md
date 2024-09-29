# Brent's tmux configuration

## Quickstart

- Create a tmux configuration directory:

  ```bash
  mkdir -p .tmux/plugins
  ```

- Install [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm):

  ```bash
  git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
  ```

- Clone this repo and create a soft link to its config file:

  ```bash
  git clone https://www.github.com/pappasbrent/tmux-config.git .tmux
  ln -s .tmux/.tmux.config .tmux.conf
  ```
