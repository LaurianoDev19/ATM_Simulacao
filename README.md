🛠️ Passo a Passo para Execução
1. Abrir o Terminal
No Windows: Prime a tecla Win + R, digita cmd e prime Enter.

No VS Code: Prime Ctrl + ' (crase) para abrir o terminal integrado.

2. Navegar até à pasta do Projeto
Usa o comando cd para entrar na pasta onde descarregaste o arquivo .jar. Exemplo:

cd Downloads/ATM_Simular
3. Executar o Comando
Copia e cola o seguinte comando para iniciar o simulador:

java -jar ATM_Simular-1.0.jar
⚠️ Por que não usar o Clique Duplo?
Se tentares abrir o ficheiro com dois cliques no ambiente gráfico (Windows Explorer):

O Windows abre uma janela preta por milissegundos.

O programa executa o código inicial e, como não encontra um terminal ativo para manter a sessão, fecha automaticamente.

Não conseguirás introduzir o teu PIN ou ver o Menu Principal.

Dica: Se vires um erro de "Versão", certifica-te de que tens o Java 25 instalado, conforme configurado no ficheiro pom.xml.
