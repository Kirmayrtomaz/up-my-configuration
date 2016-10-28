## terminal



## Terminator
  Primeiramente a se fazer é instalar um terminal melhorado chamado [Terminator](http://ubuntued.info/terminator-tenha-varios-terminais-numa-so-janela) 

###   Vantagens
* Permite abrir multiplas janelas ao mesmo tempo
* Executar comandos sincronamentes em vários terminaris diferentes(Isso ajuda muito quando precisa acessar varios servidores ao mesmo tempo)


```
sudo apt install terminator
```

## Instalando Oh My ZSH

```
sudo apt-get install zsh
```

## Oh My ZSH

Customizando a interface de linha de comando 



*Via Curl*
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

```


### Install Powerline fonts

Baixe o projeto para o computador

``` 
wget https://github.com/Lokaltog/powerline/raw/develop/font/PowerlineSymbols.otf https://github.com/Lokaltog/powerline/raw/develop/font/10-powerline-symbols.conf
mkdir -p ~/.fonts/ && mv PowerlineSymbols.otf ~/.fonts/
fc-cache -vf ~/.fonts
mkdir -p ~/.config/fontconfig/conf.d/ && mv 10-powerline-symbols.conf ~/.config/fontconfig/conf.d/

```




## vim


### Gerenciador de pacotes de vim `apt-vim`

Essa função instala o gerenciador automaticamente no projeto

### Vim sublime

[Repositório com vários plugins para ajudar na instalação da customização do vim](https://github.com/grigio/vim-sublime)
