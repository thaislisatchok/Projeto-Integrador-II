# Concepção do Projeto

Acesso rápido:
  
 - [Introdução](./introdução.md)
  - [Design/Projeto](./design.md)
  - [Implementação](./implementação.md)
  - [Operação](./operação.md)

  O intuito do projeto  de trata de desenvolve um sistema de automação residencial contruído e integrado à internet das coisas garantindo um maior conforto,comodidade,seguran e custo beneficio. Alem de definir os "princípios" de acordo com a necessidade do cliente, considerando modernidade, estrategia empresarial e os critérios de desenvolvimento de planos conceituais ,técnicos e de negocios.
  
  Objetivação:
 
 * Controle remoto de toda a iluminação da casa: ativadas e desativadas de acordo com o movimento na residência;
*  controle da umidade e temperatura externa e interna:  no caso externo, será no jardim, para controlar quando deve ser regado de acordo com sua umidade, que será diferente no período de chuva e nos períodos mais secos, já o sistema de temperatura será utilizado para saber a quantidade que precisa de água para não haver desperdício. Já no caso interno, se refere ao aquecimento e refreamento da casa, dependendo se o período é verão/primavera ou inverno/outono ; 
*  sensor de presença para a luz do corredor de entrada e para o portão principal: no momento em que o farol do carro for ativado no portão, ele abre automaticamente, sem a necessidade de apertar o botão, depois que o carro passar, o portão fechará(analisando o movimento por completo para manter aberto até que o carro esteja totalmente na garagem ) e nesse instante a luz da garagem irá se acender por conta do reconhecimento de presença;
*  sensor de gás para detectar vazamentos localizado na cozinha, havendo um aviso por meio de um alerta sonoro: quando o sensor de gas detectar gas vai liberar um sinal sonoro e a janela do ambiente será aberta;
*  alarme para segurança: no momento em que a casa estiver vazia e de noite será acionado o alarme, no qual, caso um movimento estranho desconhecido for detectado será considerado como uma invasão acionando um aviso sonoro;



### Componentes eletrônicos:

| Componentes                          |Representação       |
| -------------------------------------|------------------- |
|  Placa MEGA 2560 R3+Fonte+Cabo USB          |![MEGA 2560](https://www.filipeflop.com/wp-content/uploads/2017/07/1AC04-1.jpg) |
|Sensor de Umidade e Temperatura DHT11        | ![DHT11](https://www.filipeflop.com/wp-content/uploads/2017/07/Dht11.jpg) |
|Sensor de presença e movimento PIR        | ![PIR](https://www.filipeflop.com/wp-content/uploads/2017/07/1220801-2.jpg) |
|Sensor de gás MQ-2 inflamável e fumaça     |![MQ2](https://www.filipeflop.com/wp-content/uploads/2017/07/sku_193001_2.png) |
|   Micro Servo SG92R 9g TowerPro           |![SERVO](https://cdn.awsli.com.br/600x450/535/535286/produto/121183340/f853b364ba.jpg) |
|Módulo Sensor de Umidade/Nível Água Chuva | ![NIVELAGUA](https://cdn.awsli.com.br/600x700/468/468162/produto/25255981/eb4cd1de03.jpg) |
|   Módulo Relé 5 V e um Canal                            |![rele](https://www.filipeflop.com/wp-content/uploads/2017/07/SKU099653h.jpg) |
|   Sensor ultrasônico HC-SR04                             | ![ultrassonico](https://cdn.awsli.com.br/600x700/78/78150/produto/2888532/62bc744cec.jpg) |
|   Módulo Matriz de LED 8×8 com MAX7219    | ![matrizled](https://www.usinainfo.com.br/1017274-thickbox_default/modulo-matriz-de-led-8x8-vermelho-max7219-jumpers.jpg) |
|   Buzzer passivo                                                     | ![buzzer](https://www.filipeflop.com/wp-content/uploads/2017/07/2-142.jpg) |
|   Display LCD 16×2 I2C Backlight Azul             | ![display](https://cdn.awsli.com.br/600x700/468/468162/produto/19414150/display-lcd-16x2-i2c-backlight-azul-7ff37942.jpg) |

## Referências

