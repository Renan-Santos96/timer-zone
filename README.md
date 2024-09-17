# :clock1:TimerZone 

O TimerZone é uma extensão para Google Chorme com objetivo de gerenciar o tempo de tela do usuário. A extensão permite que o usuário defina um tempo de foco de até 60 minutos. Ele recebará um aviso sonoro para alertar  que o tempo estipulado foi atingido. TimerZone é simples e bem dinâmico de usar, botões bem intuitivos e interface minimalista.


## :wrench:Funcionalidades

 - :alarm_clock:Timer: O usuário defini o tempo de tela. Uma contagem regressiva dará inicio para seu ciclo de foco.
 - :heavy_check_mark:Botão Play: Inicia a contagem do tempo definido pelo usuário.
 - :x:Botão Stop: Finaliza a contagem antes do tempo definido pelo usuário.
 - :arrows_counterclockwise:Botão Reset: Reinicia a contagem do tempo.
 Observação: Efeito sonoro :bell: é ativado ao ser finalizado o timer para sinalizar o usuário.
 

## :file_folder:Estrutura do repositório
TimerZone/
│
├── assets/               # Pasta contendo os ícones e áudio da extensão
│   ├── pomodoro148.png
│   ├── pomodoro16.png
│   ├── pomodoro24.png
│   └── alarm.mp3
│
├── README.md      # Arquivo de documentação
├── manifest.json       # Configuração da extensão do Chrome
├── popup.html          # HTML da interface do popup
├── script.js                # Lógica do Pomodoro em JavaScript
└── styles.css             # Estilos da interface em CSS



## :computer:Como instalar localmente

 1. Faça o download ou clone este repositório no computador.
 2. Abra o Google Chrome e navegue até ....
 3. Ative o **Modo do Desenvolvedor**.
 4. Clique em **Carregar sem compactação** e selecione a pasta onde o projeto da extensão se encontra.
 5. A extensão será baixada e aparecerá na lista de extensões do Chrome.

## :hammer:Como usar

1. Clique no ícone do  **TimerZone**  na barra de ferramentas do Chrome.
2. Defina o tempo desejado
3. Pressione o botão  **Start**  para iniciar a sessão.
4. Pressione  **Stop**  para encerrar a sessão a qualquer momento.
5. Pressione **Reset** para reiniciar a contagem

💡  **Dica:**  Sempre que se encerrar um clico, faça uma outra atividade para relaxar antes de dar início a outro Timer Zone, assim seu foco e produtividade serão melhores.

## :memo:Melhorias Futuras

 - Permitir que o usuário escolha entre várias opções de alertas quando o tempo for atingido.
 - Melhorar interface, ser mais elegante e moderna.
