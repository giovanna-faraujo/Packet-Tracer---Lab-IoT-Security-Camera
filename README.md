# Laboratório Cisco Packet Tracer: Customização e Segurança em Dispositivo IoT

> **Objetivo Prático:** Modificação de componentes, adaptação de scripts (JavaScript) e integração de uma câmera de segurança IoT a um servidor de gerenciamento remoto via Cisco Packet Tracer.

---

##  O que foi feito neste projeto?

Imagine que você comprou uma câmera de segurança simples que apenas fica ligada, mas você deseja que ela **detecte movimentos** e mostre visualmente na rede quando algo acontecer. 

Em vez de comprar um dispositivo novo, este laboratório simula a **reprogramação da câmera existente**:
1. **Identidade Visual:** Adicionei um indicador visual (luz vermelha) no dispositivo para alertar quando houver detecção de movimento.
2. **Reuso e Adaptação de Código:** Reaproveitei e adaptei a lógica de programação em JavaScript de um detector de movimento para a câmera.
3. **Gerenciamento Remoto Seguro:** Conectei a câmera a um servidor central de IoT para permitir o monitoramento e controle em tempo real através de outros dispositivos (como um tablet).

<img width="1905" height="856" alt="image" src="https://github.com/user-attachments/assets/6e109d7f-50cb-4015-828a-552e74371b0d" />

---

## Habilidades Técnicas Demonstradas

- **Internet das Coisas (IoT):** Configuração de status, subcomponentes e regras de estado em dispositivos inteligentes.
- **Programação Aplicada (JavaScript):** Leitura, cópia, refatoração de código e ajuste de variáveis (`type: "Security Camera"`).
- **Redes e Comunicação Remota:** Configuração de endereçamento IP, parâmetros de servidor remoto e autenticação de dispositivos.
- **Testes de Validação:** Simulação de eventos de movimento (tecla `ALT`) e verificação de logs no Dashboard do servidor IoT.

---

## Passo a Passo Resumido da Atividade

### 1. Customização Visual e Regras de Estado
- Importação da imagem de estado ativo do dispositivo.
- Criação de regras de exibição: 
  - **Estado LOW (Inativo):** Ícone padrão da câmera.
  - **Estado HIGH (Ativo/Movimento):** Ícone com indicador de luz vermelha.

### 2. Programação e Refatoração
- Extração do script base em JavaScript de um detector de movimento.
- Criação de um novo projeto de código na câmera e alteração da variável de tipo para associar os eventos corretamente ao novo hardware.

### 3. Integração com Servidor IoT e Testes
- Configuração do servidor remoto no IP `203.0.0.3` com autenticação.
- Validação no navegador via Tablet (`home.com`), simulando movimento do mouse e acompanhando a alteração do status em tempo real.

---

## Tecnologias e Ferramentas
- **Cisco Packet Tracer**
- **JavaScript** (Scripts de automação IoT)
- **Protocolos de Rede e IoT** (Conectividade Servidor-Cliente)

---

### Direitos Autorais e Créditos
*Este laboratório foi realizado com base no material e instruções do curso **Cisco Networking Academy (NetAcad) / Packet Tracer**. Todos os direitos autorais dos cenários e materiais originais pertencem à **Cisco Systems, Inc.***
