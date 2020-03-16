1- Esta automação está preparada para utilizar o Firefox como navegador de testes padrão.
2- Entre no site https://rubyinstaller.org/downloads e baixe o Ruby + Devykit a versão mais nova compativel com o seu sistema operacional, (caso já possua o Ruby + Devkit instalado, vá para o item 9).
3- Instale o executavel do Ruby + Devkit.
4- Marque a opção "I accept the License" e depois clique no botão "Next >".
5- Marque todas as opções e depois clique no botão "Install".
6- Marque todas as opções e depois clique no botão "Next >", aguarde a instalação.
7- Marque todas as opções e clique no botão "Finish" , uma tela do cmd ira se abrir.
8- Na tela digite a opção 3 e aperte "Enter".
9- Apos a instalação aperte "Enter" para sair.
10- Descompacte o projeto testinmetrics.zip no diretório C:.
11- Faça o download da versão mais nova do geckodriver nesse link https://github.com/mozilla/geckodriver/releases, escolhendo a versão do seu sistema operacional, (caso já possua o geckodriver atualizado vá para o item 12).
12- Descompacte o geckodriver no diretório C:/Windows.
12- Faça o download do firefox nesse link https://www.mozilla.org/en-US/firefox/new/, (caso possua o firefox instalado va para o item 12).
13- Faça a atualização do seu navegador Firefox utilizando os seguintes passos, clique em menu > ajuda > sobre o firefox, uma janela Sobre o Firefox será aberta e será verificado se existe alguma atualização automaticamente, caso exista ele irá fazer o download e após isso clique em reiniciar para atualizar o Firefox, (caso o seu navegador esteja atualizado vá para o item 13)
14- Abra o executar utilizando os botõs "Windows + r", depois digite "cmd" e em seguida aperte no botão "OK".
15- Com o cmd aberto digite "cd C:\testinmetrics".
16- Digite "gem install bundler", para a instalação da gem do bundler (caso já possua a gem instalada vá para o item 17, caso esteja desatualizada digite "gem update bundler").
17- Digite bundle install para a instalação de outros pacotes necessarios.
18- Para rodar o programa digite "cucumber -t@criar_usuario", após o término é gerado um relatorio.
19- No diretorio "C:\testinmetrics\report" estara um arquivo relatorio.html, onde tera o relatorio com as evidencias apos a execução da automação.