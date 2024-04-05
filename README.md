# Aprendendo Elixir

## Instalação

Para instalar o Elixir, optei por usar um gerênciador de pacotes, assim fica
mais fácil testar/instalar outras versões. O gerênciador escolhido foi
o **asdf**.

### Instalando asdf

```sh
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.14.0
```

Adicionar `. "$HOME/.asdf/asdf.sh"`  ao **~/.zshrc**.


Adicionar plugin para gerênciar as versões do elixir:

```sh
asdf plugin-add elixir https://github.com/asdf-vm/asdf-elixir.git
```

### Instalando Elixir

```sh
asdf install elixir 1.16.1-otp-26 && asdf global elixir 1.16.1-otp-26
```
