### Assunto do dia Git e GitHub 

**Git **- Versionamento de código distribuído. 
Rascunho > Rascunho Dois > Revisão do Rascunho > Projeto Final Um > Revisão do Projeto Final > Final 

**GitHub** - É onde será armazenado os arquivos versionados. Repositório. 

**GUI** - Interface gráfica do utilizador

**CLI** - Interface de linha de comandos

O GIT não possui uma interface gráfica, a forma de utilizar ele é por linha de comando. 



##### *O que iremos aprender?*

Mudar de pastas
Listar as pastas
Criar pastas/arquivos 
Deletar pastas/arquivos 

##### Comandos:

**CMD** - Para abrir o Terminal.

**cd** - Muda a direção. 

**dir** - Lista as Pastas.

**..** - É utilizado para retroceder/voltar para uma pasta anterior.

**cls** - Limpa a Tela.

**mkdir** - Cria Pastas.

**del** - Deleta Arquivos.

**rmdit** - Deleta Pastas. 

**echo hello > echo hello.txt** - Cria um arquivo na pasta.

Se der certo o terminal não vai te falar nada. 



 #### *Git debaixo dos panos:*

 **Sha** - Algoritmo de encriptação, que gera um conjunto de caracteres de 40 dígitos únicos. 

*Exemplo: Tenho 1 algoritmo que possui os 40 dígitos gerados, se eu pegar este algoritmo e altera-lo adicionando uma vírgula o git irá gerar outros 40 dígitos. Se eu voltar e apagar está vírgula, o git irá retornar para os 40 dígitos anteriores.*

**Blobs** - Bloco básico de composição 
**Trees** - Armazenam os blobs 
**Commits** - Junta tudo, aponta para tree, parente, autor e mensagem. 

#### *Chaves SSH  e Tokens*

**Chave ssh** - Estabelece uma conexão segura entre duas máquinas, tendo uma chave pública e uma chave privada. 

**Tokens** - Não irei utilizar.



### Tutorial de Publicação git  > github ###

1. Git Init

2. Git Status

3. Git Add . 

4. git commit -m 'Meu comentário bonito'

5. git remote add origin 'https://github.com/usuario/nomedomeuprojeto.git'

6. git remote show origin -n

7. git push origin master

   

##### Cursos:

- [x] Introdução ao Git e ao GitHub
- [x] Desafio: Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso