## Início
Sejam  todos muito bem vindos!
Aqui vamos aprender como estilizar os icones do cmd.

## Repositório
[Z](https://github.com/badmotorfinger/z)

## Instalação
Instalando módulo da galeria do Powershell:
- Abra o powershell como administrador;
- Execute o comando abaixo;

```bash
Install-Module -Name z -Force
```
- Feche o prompt Powershell para atualizar com o novo módulo;

### Exemplos
```
z foo				cd to most frecent folder matching foo

z temp				cd to most frecent folder matching `Temporary ASP.NET Files`

z foo -o r			cd to highest ranked folder matching foo

z foo -o f			cd to highest frecency folder matching foo

z foo -o t			cd to the most recently accessed folder matching foo

z -l foo			list all dirs matching regex foo

z -l				list all entries

z office			cd to most frecent folder matching office in drive HKLM (The registry)

z -x				remove the current directory from the datafile

z -clean			delete inaccessible paths from the datafile

z c:\windows			go to c:\windows and log in the datafile (works with any valid path)

z c<TAB>			expand entries in the datafile which match 'c'
```


Divirta-se! \o/

### Vídeos associados
[Z Folder Jumper](https://www.youtube.com/watch?v=fviSilPKIhs&t=1390s)
