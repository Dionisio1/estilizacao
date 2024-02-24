## Início
Sejam  todos muito bem vindos!
Aqui vamos aprender como estilizar os icones do cmd.

## Repositório
Podemos encontrar nosso material no repositório [Terminal-icons](https://github.com/devblackops/Terminal-Icons)

## Instalação
Instalando módulo da galeria do Powershell:
- Abra o powershell como administrador;
- Execute o comando abaixo;

```bash
Install-Module -Name Terminal-Icons -Repository PSGallery
```
![Baixando Módulo](./imagens/Icons/1_baixando_modulo_terminal_icons.png)

- Abra o arquivo de configuração, usando o comando:
```bash
notepad $PROFILE
```
- Adicione o código abaixo no arquivo:
```bash
#Terminal-icons
Import-Module -Name Terminal-Icons
```
![Adicionando trecho de código no arquivo de configuração](./imagens/Icons/2_adicionandoCodigoAoArquivo.png)
- Salve o arquivo;
- Feche o arquivo $PROFILE;

Divirta-se! \o/

### Vídeos associados
[Terminal Icons](https://www.youtube.com/watch?v=84e2R5nMLo8)
