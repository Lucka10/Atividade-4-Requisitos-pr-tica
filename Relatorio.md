Relatorio da Atividade 4

### 1) Definir 2 requisitos funcionais de um sistema qualquer
  
  R1. Login
  
  R2. Enviar email.
  
### 2) Descrever o Caso de Uso Expandido para os 2 requisitos 
  
  #### R1) **Caso de Uso: Login**
  
  **Descrição geral:**<br>
  O caso de uso inicia quando o ususario deseja acessar sua pagina
  
  **Atores:**<br>
  Usuario
  
  **Pre-condições:**<br>
  Nenhuma
  
  **Garantia de sucesso(pós-condiçãões):**<br>
  Fornecer dados validos de endereço de email e senha.
  
  **Requisitos especias:**<br>
  Segurança
  
  **Fluxo principal:**<br>
    1. Sistema solicita informações de endereço de email e senha. <br>
    2. Usuario preenche os campos designados com os dados corretos. <br>
    3. Sistema realiza validação dos dados fornecidos.<br>
    3.1. Sistema checa se o endereço existe. Se não vai para o Fluxo Alt. Endereço não existe. <br>
    3.2. Sistema checa se senha corresponde ao email fornecida. Se não, vai pra fluxo Alt. Senha incorreta. <br>
    4. Com informações validadas, o sistema direciona o usuario para a pagina Caixa de entrada correspondente ao email. <br>
  
  **Fluxo alternativo:**<br>
    3.1.1. Endereço de email não existe não existe no banco de dados de sistema.<br>
      3.1.2. Sistema recarrega a pagina de login e retorna um mensagem informando que o endereço de email não existe.<br>
    3.2.1. Senha incorreta.  a senha não corresponde ao email fornecido.<br>
      3.2.2. Sistema recarrega a pagina de login e retorna mensagem informando que a senha está incorreta.<br>
  
  #### R2) **Caso de Uso:Enviar de email.**
  
  **Descrição geral:**<br>
  Um sistema que permite compor, enviar e receber mensagens online de forma assíncrona.
  
  **Atores:**<br>
  Usuario

  **Pre-condições:**<br>
  Usuario logado no sistema.
  
  **Garantia de sucesso(pós-condiçãões):**<br>
  Mensagem enviada corretamente para o endereço de email do destinatario, quando este for fornecido e for valido.
  
  **Requisitos especias:**<br>
  Segurança e privacidade.
  
  **Fluxo principal:**<br>
    1.Usuario está na pagina da caixa de entrada e pode:<br>
      1.1. Escrever e enviar emails.<br>
        1.1.1. clicando em escrever, irá abrir uma caixa de texto onde deverá fornecer o endereço de email do destinatario(obrigatorio) e assunto da mensagem(opcional) e poderá escrever uma mensagem. quando terminar deve clicar no botão ENVIAR para enviar a mensagem.<br>
        1.1.2. o sistema irá checa se o email do destinatario existe. se sim, irá enviar a mensagem e retorna a mensagem informando que foi enviado. se não, Fluxo alt. destinatario não existe.<br>
      1.2. Visualizar o assunto e remetente de emails recebidos, em ordem do mais recente.<br>
        1.2.1. Clicando em um email será direcionado para uma pagina com conteudo e historico das mensagens sob esse assunto  com o destinatario.<br>
        1.2.2. Na pagina do email, usuario tem a opção de responder ao email, o que irá abrir uma caixa de texto, com os dados do destinatario já inseridos.<br>
          1.2.2.1. O usuario clica em enviar e segue o mesmo fluxo de 1.1.2.<br>
          
  **Fluxo alternativo:**<br>
  1.1.2. destinatario não existe.<br>
    1.1.2.1 Sistema retorna uma mesma informando que a mensagem não foi enviada e o endereço do destinatario não existe.<br>
  
### 3) Descrever User Storie para os 2 requisitos

#### User Stories: Login

Como um usuario do sistema, eu quero usar meu email e senha, para que eu posso ter acesso a minha conta 

#### User Stories: Enviar Email

Como o usuario de email, eu quero enviar mensagem, para que eu posso me comunicar com outras pessoas.

### 4) Fazer o protótipo da tela para cada um dos requisitos

https://www.figma.com/file/09Wl38jz7WNcxnA7Lw8taK/At4ProtoRequisitos?node-id=0%3A1
  
