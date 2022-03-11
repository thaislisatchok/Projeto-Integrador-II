# Implementação do Projeto

Nesta etapa, será feita a montagem da casa e a inicialização da automatização residencial, recebendo todas as tecnologias baseando-se na estrutura apresentada e projetada na etapa do Design. A seguir, serão descritos os processos de fabricação da maquete, testes dos componentes, e código e validação de cada tarefa do sistema integrado.

Acesso rápido:  
 - [Introdução](./introdução.md)
  - [Concepção](./concepção.md)
  - [Design/Projeto](./design.md)
  - [Operação](./operação.md)

## Maquete

Na etapa do design foi feita a planta baixa da maquete a ser implementada no projeto, baseado nisso foi desenvolvido a ideia inicial e logo em seguida, o resultado.

### Projeto/Ideia Inicial 

![Diagrama](https://github.com/thaislisatchok/Projeto-Integrador-II/blob/main/figuras.md/maquete%20residencial.png)

### Montagem-Resultado
 Material utilizado:
 
- Base de Isopor ;
 - Impressão planta de casa em papel A3 em escala 1:50 ;
 - Papel EVA verde e cinza ; 
 - Papel Cartolina verde ; 
- Papel Paraná número 90 ; 
- Cola de isopor.
 
![Diagrama](https://github.com/thaislisatchok/Projeto-Integrador-II/blob/main/figuras.md/maquete1.jpg)

![Diagrama](https://github.com/thaislisatchok/Projeto-Integrador-II/blob/main/figuras.md/maquete2.jpg)

![Diagrama](https://github.com/thaislisatchok/Projeto-Integrador-II/blob/main/figuras.md/maquete3.jpg)

## Testes com os sensores

Com a maquete pronta, foi iniciado os testes testes individuais com os componentes afim de ratificar que todos estão em perfeito funcionamento para integra-los posteriormente.

Sendo assim, houve a possibilidade de interagir eles entre si, criando novos códigos e adicionando tarefas na IDE do arduíno escrito em funções de C para que a partir de alguns comandos enviados pela comunicação serial ou então pela leitura dos sensores, obtivesse respostas, como por exemplo um LED acendendendo por meio do sensor de movimento presença PIR , um servo abrindo um portão, uma mensagem no display LCD de acordo com a medida do módulo sensor de umidade/nível da água, buzzer emitindo alarme sonoro juntamente do sensor gás ou do sensor presença. Segue o vídeo desses exemplos:

### Sistema entrada na garagem

- [Portão Garagem](figuras.md/Portão Garagem.mp4)
- 
- [Sensor Presença LED](testes/buzzer/buzzer.md)

## Código
Após a implementação de todas as interações e tarefas, é o momento e colocar todas juntas em um único código para ter o sistema inteiro funcionando. 

  #### Código Principal

Para acessar o meu código [**Clique aqui**](./Código.md/casa_domotica.ino)

## Referências

AUTODESK. AutoCAD (Versão gratuita): Sofware CAD com automação de projeto, além de conjuntos de ferramentas, aplicativos para dispositivos móveis e web. Disponível em: https://www.autodesk.com.br/products/autocad/overview?us_oa=dotcom-us&us_si=c73dcba2-ca0f-46ea-aa7b-0bc1f74d2323&us_st=AutoCAD&us_pt=ACD. Acesso em: 05 fev. 2022.
