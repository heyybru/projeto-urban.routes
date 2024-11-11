# Projeto Urban.Routes

### Descrição do Projeto: Teste de Regressão do Urban Routes

Este projeto abrange a execução de testes de regressão no aplicativo Urban Routes, que é usado para criar rotas e calcular tempo e custo de viagens para diferentes tipos de transporte. O Urban Routes possui uma interface com campos de endereço ("De" e "Para"), três modos de transporte ("Optimal," "Flash" e "Personal") e ícones para diversos meios de locomoção (carro próprio, a pé, táxi, bicicleta, scooter e carsharing). Este projeto, dividido em três fases, faz parte do escopo de treinamento dos alunos no **Bootcamp de Analista de QA** da [TripleTen](https://tripleten.com/pt-bra/qa/meet/).

**Contexto**
O Urban Routes utiliza pontos de origem e destino inseridos pelo usuário para calcular a rota, tempo e custo da viagem através de algoritmos específicos. Testes de regressão são essenciais para assegurar que funcionalidades existentes continuem a operar corretamente após atualizações e correções.

---

### Objetivos

- Elaborar e executar casos de teste com base nos requisitos e designs.
- Relatar quaisquer discrepâncias entre os resultados esperados e os resultados reais.
- Documentar os bugs encontrados em relatórios detalhados para os desenvolvedores.
- Identificar bugs e garantir a estabilidade da aplicação após atualizações.
- Testar funcionalidades específicas como o formulário "Adicionar carteira de motorista" e a funcionalidade de compartilhamento de carros.

---

### Ferramentas Utilizadas

- Google Sheets: Documentação de casos de teste e checklists.
- JIRA: Criação e gerenciamento de relatórios de bugs.
- DevTools (Chrome e Firefox): Análise e inspeção do layout e funcionalidades.
- Figma: Verificação dos designs de referência.
- Navegadores (Google Chrome e Firefox): Execução dos testes em diferentes ambientes e resoluções.

**Obs:** Para acessar os designs de referência, clique aqui: [Figma](https://www.figma.com/file/xmXmdL9XmfkBlqlnRZdmRK/Urban-Routes-PT?type=design&node-id=1-17466&mode=design&t=KqcZZYfdODqiRZrf-0)

---

### Metodologia

A metodologia utilizada neste projeto de testes de regressão segue as práticas de Desenvolvimento Ágil e Testes Baseados em Risco, com ênfase nas seguintes etapas:

 1. **Análise de Requisitos:**
  - Estudo detalhado dos requisitos fornecidos e comparações com os designs de referência.
  - Identificação de casos críticos e funcionalidades com maior impacto para priorização.
  
 2. **Design de Testes:**
  - Uso de técnicas de Particionamento de Classes de Equivalência e Análise de Valores-Limite para a criação de cenários de teste robustos.
  - Desenvolvimento de checklists e casos de teste detalhados, documentados em planilhas para fácil acompanhamento.

 3. **Execução Iterativa:**

  - Realização dos testes em sprints, seguindo um ciclo de desenvolvimento ágil, para ajustes contínuos e feedback imediato.
  - Testes conduzidos em diferentes navegadores e resoluções para validar a consistência da aplicação.

 4. **Documentação e Reporte:**
  - Criação de relatórios de bugs detalhados no JIRA, com informações completas para facilitar a reprodução e resolução dos problemas.
  - Atualizações contínuas na documentação com base nos resultados dos testes e feedback das partes interessadas.

5. **Revisão e Avaliação:**

  - Revisão dos resultados dos testes com a equipe de desenvolvimento e stakeholders para garantir a correção eficiente dos problemas encontrados.
  - Avaliação de testes para identificar possíveis melhorias nos processos futuros.

---
### Resultados
- **Total de Bugs Relatados:** 46
- **Layout:** Pequenas discrepâncias na disposição dos elementos em diferentes resoluções.
- **Funcionalidade:** Inconsistências nos pop-ups de confirmação foram reportadas.
- **Recomendações:** Melhorar a consistência entre o design e os requisitos, e revisar a validação de campos de entrada.
- **Resumo:** O projeto de testes de regressão identificou problemas críticos e menores na funcionalidade e no layout da aplicação Urban Routes. A documentação detalhada dos testes e relatórios de bugs proporcionou uma base sólida para a correção e aprimoramento contínuo do software. A metodologia ágil aplicada permitiu uma resposta rápida aos feedbacks e ajustes nos processos de teste.

---

### Aprendizados

- Execução de testes de regressão.
- Documentação de bugs e uso de ferramentas de QA.
- Testes GUI.
- Analisar e decompor requisitos de um app.
- Identificar classes de equivalência e valores-limite.
- Escrever casos de teste.
- Escolher a configuração para testagem entre navegadores.
- Compilar checklists para abordar todos os testes.
- Testes independentes.
- Este projeto é fundamental para garantir a qualidade do Urban Routes, abordando desde testes de regressão até a validação de novos recursos. A metodologia ágil e a documentação detalhada dos testes contribuem para o aprimoramento contínuo da aplicação e a correção eficiente de problemas identificados.

<img src="images/Image (1).png">
<img src="images/Image (2).png">
<img src="images/Image (3).png">
<img src="images/Image.png">

---
### Melhorias Futuras
- Criar scripts automatizados para testes repetitivos.
- Expandir o escopo dos testes para incluir autenticação e autorizações futuras.

---
### Como Executar o Projeto

#### Fase 1: Teste de Regressão Inicial

**Executar Casos de Teste Pré-Definidos:**
- Utilizar o modelo do Google Sheets para registrar os resultados dos testes.
- Definir o status de cada caso de teste como Aprovado, Reprovado ou Ignorado.
- Criar relatórios de bugs para os casos de teste reprovados, com detalhes como ID, título, etapas, resultado esperado, resultado real e prioridade (Bloqueador, Crítico, Grande, Pequeno, Trivial).
  
**Relatar Bugs:**

- Criar relatórios completos no modelo fornecido, preenchendo todas as informações necessárias.

**Procedimento**
1. Iniciar o Servidor: Iniciar o servidor e acessar o aplicativo pelo navegador.
2. Execução de Testes: Executar os casos de teste descritos e documentar os resultados.

**Resultados Esperados**
- Garantir que os principais componentes da aplicação estejam funcionando conforme o esperado e identificar quaisquer discrepâncias.

#### Fase 2: Design de Testes do Formulário "Adicionar Carteira de Motorista"
**Definir Classes de Equivalência e Valores-Limite:**
- Analisar os campos do formulário ("Nome", "Sobrenome" e "Data de nascimento").
- Identificar classes de equivalência e definir os valores-limite para testes.
- Incluir cenários de teste positivos e negativos.
Escrever Casos de Teste:
- Documentar os casos de teste na aba específica do modelo, focando no campo "Nome".

**Detalhes**
- Abertura do Formulário:
- Inserir "East 2nd Street, 601" no campo "De".
- Inserir "1300 1st St" no campo "Para".
- Escolher o modo "Personal" e o transporte "Carsharing".
- Clicar em "Reservar" e depois em "Adicionar carteira de motorista".

#### Fase 3: Testes da Funcionalidade de Compartilhamento de Carros
**Testar em Ambientes Diferentes:**
- Realizar os testes no Google Chrome (800x600) e no Firefox (1920x1080).

**Preparar Documentação de Teste:**
- Criar checklists para o layout do formulário de reserva e para as janelas "Método de pagamento" e "Adicionar cartão".
- Preparar casos de teste para o botão "Reservar" e a função de locação de carro.

**Executar os Testes:**
- Verificar o layout e a funcionalidade de acordo com os requisitos e designs.

**Etapas e Detalhes**
- Checklist do Layout: Verificar a ortografia, disposição e aparência dos elementos.
- Funcionalidade das Janelas: Utilizar particionamento de classes de equivalência e análise de valores-limite.
- Casos de Teste para o Botão "Reservar": Focar nos cenários positivos e negativos.

**Obs:** Para realizar os testes é necessário ter acesso ao servidor.

---

### 📬 Contato

<div align="left">
  <a href="https://www.linkedin.com/in/bruno-souza-14b11916a/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  </a>
  <a href="bhenriquealves520@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail logo"  />
  </a>
</div>

###
# projeto-urban.routes
