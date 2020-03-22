# Desfecho do ADABAS

Migração das base de dados do banco de dados SGA/ADABAS para o banco de dados IBM/DB2, nos projetos desenvolvidos pela linguagem SAG/NATURAL.

## Instruções

Estes projeto deve ser utilizado apanes para trabalho HOME_OFFICE, quando não há possilidade dos analista não estarem presente as instalações 
do Banco do Brasil.

## Pré-requisitos
* **GIT** - O software de controle de versionamento
* **Microsoft Visual Studio** - Editor de Texto e Projeto
   ou 
* **Sublime Text 3** - Editor de Texto

## Instalação
  * **GIT**
    Tutorial de instalação do  [Git](https://dicasdeprogramacao.com.br/como-instalar-o-git-no-windows/)

  * **Microsoft Visual Studio**  
        Tutorial de Instalação do  [VS](https://docs.microsoft.com/pt-br/visualstudio/install/install-visual-studio?view=vs-2019)
     ou 
  * **Sublime Text 3**
        Tutorial de Instalação do  [subl](https://www.melhorhospedagemdesites.com/dicas-e-ferramentas/sublime-text-editor/)

## Customizações
  * Acessando o GiitHub via chaves SSH 
    1. Open Git Bash.

    2. Cole o texto abaixo, substituindo o endereço de e-mail pelo seu GitHub Enterprise.
        $ ssh-keygen -t rsa -b 4096 -C "seu_email@exemplo.com.br"
        - O comando criará a chave SSH, usando o e-mail fornecido como uma etiqueta.

        - Generating public/private rsa key pair.
            - Quando aparecer a solicitação "Enter file in which to save the key (/c/Users/usuario_000/.ssh/id_rsa):" 
              Insira o nome do arquivo no qual salvará a chave SSH ou presssione 'Enter' para local padrão do arquivo.
              Será exibida a confirmação "Created directory '/c/Users/usuario_000/.ssh'."
            - Insira a password ou vazio: "Enter passphrase (empty for no passphrase):"
            - Insira novamente a password: "Enter same passphrase again:"
            - As mensagens a seguir confirma a crição da chave:
              **Your identification has been saved in /c/Users/usuario_000/.ssh/id_rsa.**
              **Your public key has been saved in /c/Users/usuario_000/.ssh/id_rsa.pub.**
```
        - Veja este Exemplo:
            Generating public/private rsa key pair.
            Enter file in which to save the key (/c/Users/usuario_000/.ssh/id_rsa):
            Created directory '/c/Users/usuario_000/.ssh'.
            Enter passphrase (empty for no passphrase):
            Enter same passphrase again:
            Your identification has been saved in /c/Users/usuario_000/.ssh/id_rsa.
            Your public key has been saved in /c/Users/usuario_000/.ssh/id_rsa.pub.
            The key fingerprint is:
            SHA256:lnNp5nVp9Z191XUXKJH8wcmx/9FJXqE6X3pWUhYYAo8 kenio.sousa@bbts.com.br
            The key's randomart image is:
            +---[RSA 4096]----+
            |                 |
            +----[SHA256]-----+
```
    3. [Adicionar uma nova chave SSH à sua conta do GitHub](https://help.github.com/pt/enterprise/2.17/user/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

## Arvore de Diretório e Arquivos

```
     --
       |--- /.git
       |     .gitignore
       |     README.md (Este arquivo)
       |--- /Dados --
                    |--- /Controles   (Relatorios de acompanhamento)
                    |
                    |--- /Desenvolvimento --     (Modulos Natural)
                    |                      | /ANCPRG 
                    |                      |
                    |                      | /ACXPRG ()
                    |                      |
                    |                      ....
                    |
                    |--- /Documentação
                       
```


## Autores

- **Neuler Coelho** - ***Ideia inicial*** - (neuler.coelho@bb.com.br)

- Veja também a lista de [participantes](https://github.com/desfecheAdabas/Dados/Documentacao/participantes.pdf)

