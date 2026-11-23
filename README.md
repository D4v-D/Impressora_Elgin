# Integração C com a Impressora Elgin I9

## Sobre o projeto
Este projeto foi desevolvido por alunos do curso de Engenharia da Computação com o objeivo de desevolver uma aplicação C capaz de se comunicar com a impressora Térmica Elgin i8/i9

## Tecnologias utilizadas
- MinGW 6.3.0
- VSCode (Visual Studio Code)
- Biblioteca .x32 de DLLs

## Instalação e execução

### 1 - Baixar o Projeto do Gihub
1. Acesse o repositório.
2. Clique no botão *Code*.
3. Selecione *Download ZIP*.
4. Aguarde o download.

### 2 - Extrair o arquivo ZIP
1. Vá até o local onde o arquivo foi salvo.
2. Clique com o botão direito → *Extrair aqui* / *Extract All*.
3. Será criada uma nova pasta com os arquivos. (Mantenha todos os arquivos dentro da mesma pasta)

### 3 - Importar no VSCode (Visual Studio Code)
1. Clique em *File* → *Open File*
2. Selecione e abra o arquivo "main.c"
3. Clique em **Run Code**


## Controle - Impressora Elgin i9
Ao rodar o arquivo "main.c", será necessario fazer login para poder uilizar o programa. Utilize essas credenciais: Usuário: admin;  Senha: 1234.
Após isso aparecerá o Menu da Impressora, cada opção realiza uma ação específica(digite apenas números):

1. Configurar Conexao  -- **Configura o tipo de conexão e os parametros que serão usados**
2. Abrir Conexao -- **Abre a conexão com a impressora**
3. Fechar Conexao -- **Encerra a conexão com a impressora**
4. Imprimir Texto -- **Imprime o texto que o usuário desejar e pergunta a quantidade de cópias**
5. Imprimir QR Code -- **Imprime um QR Code**
6. Imprimir codigo de barras -- **Imprime um Código de Barras**
7. Imprimir XML SAT -- **Imprime o XML SAT**
8. Imprimir XML de cancelamento SAT -- **Imprime o XML SAT de cancelamento**
9. Abrir gaveta (Elgin) -- **Abre a gaveta de dinheiro**
10. Abrir gaveta -- **(Item 9)**
11. Sinal sonoro -- **Apita a impressora**
12. Sair -- **Encerra o programa**

## Autores
- David Lucas Silva de Carvalho
- João Marcelo
- Luis Felipe
- Miguel Tenório de Faria

