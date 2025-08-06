# 🧠 Trackie: Solução de Acessibilidade com Tecnologia Vestível

O **Trackie** é uma plataforma de acessibilidade baseada em inteligência artificial voltada para pessoas com deficiência visual. Diferente de soluções comerciais caras e fechadas, o Trackie é um projeto social **livre, acessível, e modular**, podendo ser usado tanto em dispositivos móveis quanto em chapéus inteligentes.

## 📱 Uso Sem Chapéu

Usuários podem instalar o **app do Trackie** diretamente em seus celulares Android, utilizando a câmera e o microfone do próprio dispositivo. Esse modo oferece funcionalidades básicas como:

- Leitura de textos e placas
- Descrição de ambientes
- Identificação de sons e pessoas
- Comandos de voz para navegação assistida

Esse modo **não exige nenhum hardware adicional**, ideal para testes e uso cotidiano.

---

## 🎩 Modos de Uso com Chapéu Inteligente

Existem **dois módulos vestíveis principais** para o Trackie: **SpotWay** e **CoreWay** (também conhecido como RaspWay).

---

## 🟢 SpotWay – Leve, Conectado ao Celular

### 🎯 Visão Geral

O **SpotWay** é um chapéu inteligente com sensores embutidos que se conectam a um celular Android. Os dados são processados no celular, enquanto o chapéu funciona como um conjunto de entradas/saídas sensoriais.

### 🧩 Componentes

- 2x câmeras (frontal e lateral)
- Microfones embutidos
- Alto-falantes ou fones embutidos
- Sensores de distância (ultrassônicos ou infravermelhos)
- Microcontrolador (ESP32 ou similar)
- Bateria recarregável (powerbank pequeno)

### 🔗 Como funciona

1. O chapéu coleta dados (imagem, som, distância).
2. Os dados são enviados via Bluetooth ou cabo OTG para o celular.
3. O app Trackie processa os dados com IA embarcada ou via nuvem.
4. A resposta é transmitida por áudio ao usuário.

### 💰 Custo Estimado

Entre **R$ 200 a R$ 300**, dependendo dos sensores e câmeras escolhidas.

### ⚠️ Limitações

- Depende do celular para funcionar.
- Pode ter latência maior em modelos de celular mais simples.

---

## 🔵 CoreWay (RaspWay) – Autonomia Total com Computação Embarcada

### 🎯 Visão Geral

O **CoreWay** é um chapéu avançado com **computação embarcada**, permitindo que o Trackie funcione totalmente de forma independente, sem depender do celular. Ideal para uso contínuo, industrial ou situações com pouca conectividade.

### 🧩 Componentes

- Microcomputador (ex: Orange Pi CM4, Raspberry Pi 4/5)
- 2x câmeras (modulares USB ou CSI)
- Microfone USB ou digital
- Fones de ouvido ou transdutores ósseos
- Sensores de presença, distância e temperatura
- Bateria de longa duração (powerbank de 10.000mAh ou mais)

### ⚙️ Sistema Operacional

- Linux otimizado com terminal
- Python com bibliotecas IA embarcada (ONNX, Whisper.cpp, Piper TTS, etc)
- Rodando Trackie de forma local

### 🧠 Funcionalidades Avançadas

- Reconhecimento facial e objetos
- Detecção de perigos em tempo real
- Navegação por áudio baseada em memória espacial
- Comando por voz offline
- Modo de emergência e rastreamento

### 💰 Custo Estimado

Entre **R$ 500 a R$ 700**, com performance similar a soluções de R$ 20.000 como o **OrCam MyEye**.

---

## 🔄 Comparativo

| Funcionalidade       | SpotWay                  | CoreWay (RaspWay)         |
|----------------------|--------------------------|---------------------------|
| Processamento        | Celular Android          | Computador embarcado      |
| Custo estimado       | R$ 200–300               | R$ 500–700                |
| Peso                 | Leve                     | Médio                     |
| Autonomia            | Limitada ao celular      | Totalmente independente   |
| Funciona offline     | Parcialmente             | Sim                       |
| Ideal para           | Usuário urbano leve      | Uso contínuo ou industrial|

---

## 🤝 Missão Social

Trackie é um projeto **aberto, modular e acessível**. **Nenhum tipo de compra de hardware é obrigatório** — o objetivo é empoderar a comunidade com soluções reais e sustentáveis. Toda a tecnologia é documentada para que qualquer pessoa possa montar seu próprio sistema com peças acessíveis.

---

## 🛠️ Contribuição

Quer participar ou montar o seu? Acesse:

- Repositório: [github.com/TruveSoftware/Trackie](https://github.com/phkaiser13/TrackWay)
- Site (Em construção): [vyAI.com/TrackWay](vyAI.com/TrackWay)
---
