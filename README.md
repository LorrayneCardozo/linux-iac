# Infraestrutura como Código: Script de Criação de Estrutura de Usuários, Diretórios e Permissões

O projeto consiste em um desafio do curso de Linux da plataforma [Digital Innovation One - DIO](https://www.dio.me/), cujo objetivo é colocar em prática os conhecimentos obtidos durante as aulas criando um script que realize os seguintes passos:
* Atualizar o servidor;
* Instalar o apache2;
* Instalar o unzip;
* Baixar a aplicação disponível no endereço https://github.com/denilsonbonatti/linux-site-dio/archive/refs/heads/main.zip no diretório /tmp;
* Copiar os arquivos da aplicação no diretório padrão do apache.


## ⚙️ Como rodar
Após clonar o repositório e logar como root, é necessário atribuir permissão de execução ao arquivo `script.sh` e, por fim, executá-lo:
```bash
chmod +x script.sh
./script.sh
```