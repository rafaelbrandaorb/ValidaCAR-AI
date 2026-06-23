# 🤖 ValidaCAR AI — Inteligência Preditiva Anti-Fila do SICAR

> **haCARthon 2026 — Desafio 1: Modernização do sistema CAR DPG** > Desenvolvido como um **Bem Público Digital (Open Source)** para mitigar erros de preenchimento e reduzir gargalos na regularização ambiental.

---

## 📋 Sobre o Projeto

O **ValidaCAR AI** é uma solução de malha fina preventiva projetada para atuar na ponta do processo (antes do envio definitivo dos dados ao SICAR). A ferramenta foca na usabilidade e na inclusão digital de pequenos produtores rurais — como o perfil do *Seu Nonato* —, transformando regras complexas de conformidade ambiental em alertas visuais simples e acionáveis em tempo real.

Ao validar os dados na origem, a plataforma evita o ciclo infinito de retificações entre analistas e produtores, limpando a base de dados de entrada e promovendo uma estratégia de **Fila Zero** no governo.

---

## 🛠️ Tecnologias e Arquitetura Planejada

Embora a interface atual funcione como um protótipo de alta fidelidade interativo, a arquitetura de produção do ecossistema foi desenhada de forma modular:

* **Módulo OCR & NLP (Processamento de Documentos):** Utiliza Visão Computacional para leitura automática de arquivos `.pdf` (Matrículas e Certidões de Ônus Reais), cruzando instantaneamente dados críticos (como CPF e área declarada) para eliminar erros de digitação.
* **Módulo de IA Geométrica (Geoprocessamento):** Processa malhas territoriais em formatos `.kml` ou `.shp` contra repositórios oficiais e bases geográficas do Governo Federal, calculando de forma preditiva sobreposições com Terras Indígenas (TIs) ou Unidades de Conservação (UCs).
* **Front-end Responsivo:** Desenvolvido em HTML5, CSS3 estruturado com variáveis nativas (`:root`) e JavaScript Vanilla (Assíncrono), priorizando leveza, acessibilidade e alto desempenho em conexões rurais limitadas.

---

## 🚀 Como Executar o Protótipo Localmente

Por ter sido projetado sob a filosofia de arquitetura descentralizada e ecossistema modular, o protótipo de validação prévia roda inteiramente no navegador do usuário, sem necessidade de servidores robustos ou dependências complexas na máquina local.

1. Baixe os arquivos deste repositório.
2. Abra o arquivo `index.html` em qualquer navegador web moderno.
3. Para simular o fluxo técnico da Inteligência Artificial, anexe os dois arquivos de testes recomendados (`matricula_teste.pdf` e `mapa_teste.kml`) nos campos de upload indicados.
4. Clique em **"Rodar Validação Inteligente"** para assistir à simulação de processamento preditivo.
5. Altere o final do CPF para `-00` para validar o cenário de conformidade com nota **100/100**.

---

## ⚖️ Licença e Governança (Código Aberto)

Este repositório é distribuído sob a licença **MIT**. Como premissa obrigatória estabelecida no modelo de cooperação do haCARthon 2026, o código é totalmente aberto, livre para modificações e pronto para ser integrado a sistemas estaduais (OEMAs) ou à base nacional do SICAR, garantindo total soberania de dados do governo.

---

## 👥 Equipe-054

* **Rafael da Silva Brandão** 
* **Tony Sandro Sales** 
