# Projeto GoodAccess – Integração de Energia Renovável e Automação Inteligente

## Equipe Envolvida – Turma CCPO

- Gabriel De Biasi Couto | RM: 563247  
- João Pedro da Silva Costa | RM: 565031  
- Pedro Noronha dos Santos | RM: 564572  
- Rodrigo Campos Cordeiro | RM: 566386  
- Lucas Mendes Moraes | RM: 563667  

## Objetivo do Projeto

Desenvolver um sistema funcional que integre geração de energia solar, automação residencial e tecnologias inteligentes, promovendo sustentabilidade, eficiência energética e controle inteligente. O projeto visa demonstrar, de forma prática, como diferentes tecnologias podem atuar em conjunto para criar soluções modernas e sustentáveis.

## Componentes Integrados

- Painel Solar – Responsável pela geração de energia limpa e renovável.  
- Inversor Goodwe – Realiza a conversão da energia gerada para uso em corrente alternada e gerencia o fluxo entre painel, baterias e carga.  
- Baterias – Armazenam a energia excedente para uso em horários de baixa geração.  
- Sensores – Monitoram variáveis como temperatura, luminosidade e consumo energético.  
- ESP32 – Microcontrolador que coleta dados dos sensores, executa comandos automatizados e se comunica com outros dispositivos.  
- Assistente Virtual (Google/Alexa) – Permite o controle por voz de dispositivos integrados ao sistema.  
- Dashboard (Node-RED / Grafana) – Exibe dados em tempo real sobre geração, consumo e status dos dispositivos.

## Justificativa Técnica

A escolha dos componentes foi baseada em critérios de eficiência, compatibilidade e escalabilidade:

- O ESP32 oferece conectividade Wi-Fi e Bluetooth, ideal para aplicações IoT.  
- O Inversor Goodwe é compatível com sistemas híbridos e possui alta eficiência energética.  
- O uso de Node-RED e Grafana permite uma visualização intuitiva e personalizável dos dados coletados.  
- A integração com assistentes virtuais torna o sistema mais acessível e moderno.  
- As baterias de lítio garantem maior durabilidade e capacidade de armazenamento.

## Resultados Funcionais

- Simulação de geração solar com pico de 4.2 kWh/dia.  
- Automação de iluminação e climatização com base em sensores ambientais.  
- Comandos por voz integrados com assistente virtual para controle de dispositivos.  
- Dashboard funcional exibindo dados de geração, consumo e status dos sensores.  
- Comunicação eficiente entre os componentes, demonstrando a integração técnica do sistema.

## Esquema de Integração

Diagramas de blocos, fluxogramas e imagens do protótipo físico ou simulado devem ser incluídos na pasta `Diagramas/` ou `Imagens/`.

[ Painel Solar ] → [ Inversor Goodwe ] → [ Baterias ] ↓ [ Controlador de Carga ] ↓ [ Sensores ] → [ ESP32 ] → [ Automação Residencial ] ←→ [ Assistente Virtual ] ↓ [ Dashboard Node-RED / Grafana ]


## Conexão com a Disciplina

Este projeto aplica conceitos fundamentais da disciplina, como:

- Energia Renovável: uso de fontes limpas e sustentáveis.  
- Automação Inteligente: integração de sensores, microcontroladores e comandos automatizados.  
- Sustentabilidade: redução do consumo energético e otimização do uso de recursos.  
- Integração de Sistemas: comunicação entre hardware, software e interfaces inteligentes.

## Organização do Repositório

Projeto-GoodAccess-Sprint-Sers/ │ ├── README.md # Documento explicativo do projeto ├── Código/ # Scripts e códigos-fonte │ ├── sensores/ # Código dos sensores │ ├── automacao/ # Scripts de automação │ └── dashboard/ # Visualização de dados ├── Diagramas/ # Diagramas de blocos e fluxogramas ├── Imagens/ # Fotos do protótipo físico ou simulações ├── Instrucoes/ # Guia de instalação e uso └── Video/ # Referência ao vídeo técnico


## Instruções de Funcionamento

1. Instale os sensores e conecte ao ESP32.  
2. Configure o Node-RED para receber os dados via MQTT ou HTTP.  
3. Implemente os fluxos de automação com base nas leituras dos sensores.  
4. Conecte o sistema ao assistente virtual para comandos por voz.  
5. Visualize os dados em tempo real no dashboard Grafana.

## Demonstração Funcional

O vídeo técnico com a demonstração do protótipo funcional está disponível em:  
https://youtu.be/IpjfeiAhpbQ?si=npVTiUjycsJoDUWI
