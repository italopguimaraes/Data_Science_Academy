# Deploy de Modelo de Machine Learning em Producao com App Web

*reconhecendo digitos manuscritos usando deep learning*

O objetivo desse projeto é desenvolver uma aplicação web para reconhecer digitos manuscritos usando redes neurais convolucionais.
O modelo foi pré-treinado e será carregado apenas no momento de realizar a previsão, a interface foi desenvolvida usando HTML, CSS e JavaScript.

Esse projeto é parte da Data Science Academy

## Dependências de Software

Tenha certeza que `flask`,`scipy`, `numpy`, `keras`, `re`, `tensorflow` e `base64` estão instalados:

`conda install flask scipy numpy keras re tensorflow base64`

## Instruções do Projeto

1. Clone o repositório ou faça o download e navegue no diretório contendo o arquivo app.py usando anaconda ou prompt de comando.

2. Configure no arquivo app.py o endereço Ip localhost a ser utilizado, os endereços disponíveis são 127.0.0.1 e 0.0.0.0, você pode escolher o endereço ip que funcionar apenas descomentando a linha: app.run(host=ip, port=port) no final do script, o endereço padrão é 127.0.0.1.

3. Configure o script model/load.py o diretório em sua máquina local para os carregar arquivos model.json e model.h5 alterando as linhas 14 e 18 do script conforme o exemplo abaixo:

json_file = open('/Users/OneDrive/Documentos/cursos/IA/Data_Science_Academy/4-Machine_Learning/Cap_19_Bonus_Deploy_de_Modelo_de_Machine_Learning_em_Producao_com_App_Web/Projeto/model/model.json','r')

loaded_model.load_weights("/Users/OneDrive/Documentos/cursos/IA/Data_Science_Academy/4-Machine_Learning/Cap_19_Bonus_Deploy_de_Modelo_de_Machine_Learning_em_Producao_com_App_Web/Projeto/model/model.h5")

4. Execute o comando: python app.py, clique em permitir na janela que se abrir, copie o endereço que será exibido no prompt> http://127.0.0.1:5000/ ou http://0.0.0.0:5000/ e cole no navegador, conforme o endereço localhost selecionado anteriormente. Para executar a aplicação no web browser basta o usuário desenhar o digito usando o mouse na área indicada pelo retângulo e após clicar em prever, será exibido a previsão do digito.

Obs. Não é necessário executar o script train.py ele foi utilizado apenas para treinar o modelo para gerar os pesos, os arquivos model.h5 e model.json contém respectivamente os pesos aprendidos pelo modelo e uma representação em formato json da arquitetura do modelo.
