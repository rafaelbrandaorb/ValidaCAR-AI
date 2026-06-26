# 🤖 ValidaCAR_IA — Inteligência Preditiva Anti-Fila do SICAR

> **haCARthon 2026 — Desafio 1: Modernização do sistema CAR DPG** > *Desenvolvido como um Bem Público Digital (Open Source) focado em atuar como uma camada preventiva de pré-cadastro para eliminar erros formais de entrada e zerar filas de análise.*

---

## 📋 Sobre o Projeto

O **ValidaCAR_IA** é um ecossistema de inteligência preditiva projetado para atuar estritamente como um **Módulo de Pré-Cadastro Preventivo (Malha Fina)**. 

### A Dor de Negócio que Resolvemos:
Sabendo que a arquitetura pública atual do SICAR não recebe documentos comprobatórios (como certidões e matrículas) na fase de inscrição inicial, o sistema sofre historicamente com a entrada de **dados "sujos"** — erros formais de digitação de CPFs, dados civis divergentes e perímetros com sobreposições inadvertidas. Isso gera um passivo de milhões de processos retidos aguardando análise manual.

### A Nossa Solução:
O ValidaCAR_IA atua na ponta do processo, **antes do envio definitivo dos dados ao governo**. A ferramenta foca na usabilidade e na inclusão digital de pequenos produtores rurais — como a persona do *Seu Nonato* —, coletando a documentação e transformando regras complexas de conformidade civil e ambiental em alertas visuais simples, intuitivos e acionáveis em tempo real. Ao garantir dados 100% corretos na origem, eliminamos o ciclo de retificações e viabilizamos uma cultura de **Fila Zero**.

---

## 🛠️ Tecnologias e Arquitetura Modular

Embora a interface atual funcione como um protótipo de alta fidelidade interativo focado na experiência do usuário, a arquitetura de produção do ecossistema foi desenhada para operar de forma totalmente modular:

* **Módulo OCR & NLP (Consistência Civil):** Atuando na camada de pré-cadastro, utiliza Visão Computacional para ler arquivos em formato PDF (como Matrículas de Imóveis). A IA extrai o CPF e o nome do proprietário e confronta instantaneamente com o formulário digitado, garantindo conformidade estrita antes do cruzamento nos barramentos da Dataprev.
* **Módulo de IA Geométrica (Análise Espacial):** Processa malhas territoriais em formatos vetoriais (`.kml`, `.geojson` ou `.shp`) contra repositórios e bases geográficas oficiais federais, calculando em tempo real sobreposições críticas com Terras Indígenas (TIs), Territórios Quilombolas ou Unidades de Conservação (UCs).
* **Front-end Responsivo e Leve:** Desenvolvido em HTML5, CSS3 estruturado com variáveis nativas (`:root`) e JavaScript Vanilla (Assíncrono), priorizando altíssimo desempenho em conexões rurais limitadas e acessibilidade na ponta.

---

## 🚀 Como Executar o Protótipo Localmente

Por ter sido projetado sob a filosofia de arquitetura descentralizada e agnóstica, o protótipo de validação prévia roda inteiramente no navegador do usuário, sem necessidade de servidores complexos ou dependências na máquina local.

1.  Faça o clone ou baixe os arquivos deste repositório.
2.  Abra o arquivo `index.html` em qualquer navegador web moderno.
3.  **Fluxo de Teste da IA (Simulação de Negócio):**
    * Mantenha o CPF de teste padrão preenchido.
    * Anexe os dois arquivos de testes simulados: `matricula_teste.pdf` e `mapa_teste.kml`.
    * Clique em **"Rodar Validação Inteligente"**.
    * O motor de inteligência artificial identificará o erro civil (Score 45) e listará os alertas de inconsistência.
4.  **Cenário de Correção na Origem:**
    * Altere o final do CPF no formulário para `-00` (corrigindo a divergência com o documento).
    * Clique novamente em **"Rodar Validação Inteligente"** para assistir à IA concedendo a conformidade total (**Nota 100/100**) e liberando o cadastro seguro para envio.

---

## ⚖️ Licença e Governança (Bem Público Digital)

Este repositório é distribuído sob a licença **MIT**. Cumprindo as premissas obrigatórias de cooperação e transparência do haCARthon 2026, o código é 100% aberto, modular e livre para modificações. 

A arquitetura foi desenhada para ser adotada como uma extensão de utilidade pública de três formas:
1.  Como um **plug-in nativo** acoplado na interface do portal do SICAR Nacional.
2.  Como ferramenta autônoma de triagem prévia para Órgãos Estaduais de Meio Ambiente (**OEMAs**).
3.  Como portal utilitário para **sindicatos rurais** e escritórios de assistência técnica agrícola apoiarem os produtores na ponta.

---

## 👥 Equipe-054

* **Rafael da Silva Brandão** - Técnico em Automação Industrial
* **Tony Sandro Sales** - Licenciatura em Língua Portuguesa
