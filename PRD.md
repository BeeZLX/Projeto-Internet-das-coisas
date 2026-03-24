# Documento de Requisitos do Produto (PRD)
**Projeto:** Monitoramento e Telemetria Integrada de Medidores Elétricos
**Organização:** Fundamentos de Internet das Coisas (FOT)
**Data de Atualização:** 17 de março de 2026

---

## 1. Introdução e Contextualização
A iniciativa propõe a construção de uma plataforma remota dedicada à extração, processamento e disponibilização de dados de medidores elétricos. O propósito central é modernizar o acompanhamento do consumo e a verificação da integridade ("saúde") dos equipamentos. Ao garantir a atualização contínua das informações, o projeto busca otimizar recursos financeiros e humanos, promovendo uma gestão operacional mais ágil e segura.

## 2. Proposta de Valor e Metas
* **Gestão Proativa (Manutenção Preditiva):** Transição de um modelo de manutenção preventiva baseada em calendário para intervenções guiadas por dados reais de operação.
* **Maximização da Durabilidade:** Extensão da vida útil dos componentes elétricos, minimizando interrupções indesejadas na rede.
* **Otimização Financeira:** Queda substancial nas despesas associadas à manutenção elétrica e eliminação de multas por falhas não detectadas a tempo.
* **Expansão Sustentável:** Capacidade de escalar o monitoramento para diversas localidades de forma viável, sem que os custos fixos cresçam na mesma proporção.

## 3. Especificações da Solução Tecnológica

### 3.1. Arquitetura de Hardware
* **Projeto Eletrônico:** A modelagem dos diagramas esquemáticos e o design da placa de circuito impresso (PCB) proprietária serão conduzidos integralmente via software **KiCad**.

### 3.2. Conectividade e Rede
* **Protocolo de Transmissão:** A rede será baseada na tecnologia **LoRa**, escolhida por sua alta eficiência energética e alcance estendido.
* **Redução de Dependências:** Essa escolha elimina a necessidade de infraestruturas cabeadas complexas ou assinaturas dispendiosas de planos de dados móveis, viabilizando o monitoramento em áreas extensas.

### 3.3. Plataforma Digital e Banco de Dados
* **Centralização em Tempo Real:** Estruturação de um banco de dados dinâmico que consolida as medições dos nós da rede instantaneamente.
* **Interface e Usabilidade:** Criação de uma aplicação de baixo custo operacional, com interface amigável (UX otimizada), garantindo que os gestores analisem os indicadores com facilidade e tomem decisões rápidas.

## 4. Gerenciamento de Riscos e Diretrizes de Segurança

### 4.1. Remanejamento de Investimentos e Desafios
* **Nova Dinâmica Financeira:** Os valores que antes eram desperdiçados com processos manuais de leitura e penalidades de consumo serão reinvestidos na sustentação e evolução desta nova infraestrutura digital.
* **Recursos Humanos:** Será imprescindível a contratação de equipes técnicas capacitadas especificamente para a instalação física segura dos equipamentos.

### 4.2. Prevenção de Acidentes (Mitigação de Riscos)
* **Ameaça Principal:** Instalações inadequadas de sensores nos quadros elétricos principais podem resultar em superaquecimento, curtos-circuitos e focos de incêndio, ameaçando o patrimônio e a vida dos colaboradores.
* **Protocolos de Prevenção:**
    * Rigorosa adequação e execução do projeto seguindo as normas de segurança do trabalho, com destaque para a **NR-10**.
    * Realização obrigatória de testes de isolação e de continuidade elétrica antes do comissionamento e ativação final do sistema.
