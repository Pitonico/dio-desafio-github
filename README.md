![Git n GitHub](C:\Users\dio_d\Desktop\Programação\DIO\Git\desafio\imgs\git-and-github.png)

# Repositório do Desafio de Git/GitHub da DIO

## Git
É um software livre para o **controle de versões distribuída**, usado principalmente no desenvolvimento de software, mas pode ser utilizado para registrar o histórico de edições de qualquer tipo de arquivo.

_Link:_ [Git Website Oficial](https://git-scm.com/)

## GitHub
É uma **plataforma de hospedagem de código-fonte e arquivos com controle de versão utilizando o Git**, permitindo que qualquer usuário, principalmente programadores e empresas de TI, cadastrado na plataforma contribuam em projetos privados e/ou código aberto de qualquer lugar do mundo, além de divulgarem seus trabalhos, servindo como um portfólio.

_Link_: [GitHub Website Oficial](https://github.com)

#### Alguns Comandos Git
Comandos|Descricao
-|-
init | Criar um novo repositório
add | Adicionar arquivos/diretórios novos ou modificados para a area staged
commit -m | Comitar arquivos/diretórios
remote add | Vincular um repositório local a um remoto
push | Enviar arquivos/diretórios para o repositório remoto
pull | Atualizar repositório local baseado no repositório remoto
clone | Clonar um repositório remoto
status | Verificar o estado dos arquivos/diretório

#### Exemplo
```
git init
git status
git add .
git commit -m 'mensagem'
git remote add origin https://github.com/user/repositorio_remoto.git
git push -u origin master
```

