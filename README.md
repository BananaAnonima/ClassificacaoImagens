# 🐶🐱 Dataset de Classificação — Gatos e Cachorros

Este repositório contém o dataset utilizado para treinar um **classificador de imagens** baseado em **Transfer Learning + Fine-Tuning**, usando a arquitetura **MobileNetV2**.  
O objetivo é treinar um modelo capaz de **distinguir imagens de gatos e cachorros** de forma eficiente.

---

## 📁 Estrutura do Dataset

O dataset segue a organização padrão recomendada pelo TensorFlow:

dataset/
│
├── train/ # Imagens usadas para o TREINAMENTO
│ ├── gato/ # Imagens da classe “gato”
│ └── cachorro/ # Imagens da classe “cachorro”
│
└── val/ # Imagens usadas para a VALIDAÇÃO
├── gato/ # Imagens de validação da classe “gato”
└── cachorro/ # Imagens de validação da classe “cachorro”
