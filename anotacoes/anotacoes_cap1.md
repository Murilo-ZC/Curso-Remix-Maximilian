# Introdução ao curso:

- Remix é um framework para o React.
- Com o Remix, ainda estaremos escrevendo código React, mas com adicionais tragos pelo Remix durante o processo de construção de aplicações ***Fullstack***.
- Em aplicações Fullstack convencionais, o Frontend é construído e executado em um servidor. Se a aplicação precisar buscar dados no Backend, este precisa ser executado em outro servidor ainda. Nestes casos, o Frontend ainda precisa se preocupar com o feedback enviado para o usuário sobre o estado da requisição (enquanto ela ainda não foi concluída). Outro ponto de atenção é a demanda por lidar com eventuais erros que possam vir do Backend.
- Nunca é demais relembrar: a aplicação do Frontend **JAMAIS** deve possuir acesso direto aos dados do banco de dados. Ela deve passar por alguma camada que gerencia o acesso a esses dados, em geral, no Backend.
- Com Remix, ainda é utilizado React para a construção do Frontend, mas a aplicação do Backend também é desenvolvida no mesmo arquivo. Contudo, apenas o código relacionado ao Frontend vai para o cliente.

