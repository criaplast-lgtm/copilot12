# copilot12
Versão 12 do aplicativo de Jussier Pereira
Desenvolvedor: https://copilot.microsoft.com/chats/ZX33SSpJcBMyjHpVto6Uh


Atue como um grande mestre de programação, vamos desenvolver um aplicativo web que envolve HTML, CSS, JavaScript, PHP, SQL e MySQL.

• Este aplicativo é voltado essencialmente para celular.
• O aplicativo usará a bússola e a geolocalização (Latitude e Longitude).
• Dê o nome de <title>Copiloto5</title>.
• A cor do background do aplicativo é: "salmon".
• A cor do background da janela é: "#ECE5DD".

• Na tela inicial, simule o acesso ao aplicativo via Google, colocando inclusive o logotipo do Google e o texto "Entrar com o Google".
• Use o logo do google do endereço "https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Google_%22G%22_logo.svg/768px-Google_%22G%22_logo.svg.png".

• Certifique-se o simulador de acesso via Google está funcionando no PC e no celular.
• Somente depois e acionar o simulador de login do Google é que o aplicativo pedirá permissão para usar o geoposicionamento e a bússola.
• Na tela principal do aplicativo vamos colocar 6 botões, sendo 2 linhas de 2 botões e 2 colunas de 2 botões identificados como:
botão 1 "id='Norte'" com 150px por 150px,
botão 2 "id='Sul'" com 150px por 150px,
botão 3 "id='soma'" com 150px por 150px,
botão 4 "id='esconder'" com 150px por 150px,

• Abaixo dos botões coloque uma bússola totalmente funcional.

• No botão 1 coloque o ângulo da bússola Norte.
• No botão 2 coloque o ângulo da bússola Sul.
• No botão 3 coloque a soma dos ângulos Norte + Sul.

• Verifique se os ângulos estão todos funcionando: Norte, Sul e a soma dos 2.

• Os ângulos da bússola são acionados exclusivamente pelo movimento do celular.
• Permita que a tela do aplicativo role para baixo para permitir ver o aplicativo por completo.
• Inclua no final da página 2 botões com a "latitude" e a "Longitude" totalmente funcionais, nestes botões devem ser mostrados as coordenadas do GPS, latitude e longitude.
• Permita que a tela role para mostrar todo o conteúdo da HTML.

• Crie um Array com ângulos e links que permita que eu inclua diversos ângulos e diversos links para que quando o Norte dá bússola atingir um dos valores constante na Array, um botão azul com as dimensões de  300px por 60px será mostrado abaixo do 4 botões e permanecerá enquanto os valores do ângulo Norte estiverem dentro da faixa determina, ficando invisível quando estiver fora da faixa. Ao ser clicado, e somente quando clicado o link correspondente será aberto numa nova aba.

• Coloque no botão azul o link que ele abrirá.

"        const angleLinks = [
            { angle: 0, link: 'https://www.netflix.com' },
            { angle: 90, link: 'https://www.uol.com.br' },
            { angle: 180, link: 'https://www.youtube.com' },
            { angle: 270, link: 'https://www.x.com' }
        ];
"

• Desenvolva um designer bonita para a página.
• HTML, CSS e JavaScript, tudo em um só arquivo HTML.
