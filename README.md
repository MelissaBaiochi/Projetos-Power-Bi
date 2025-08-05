#  Dashboard de Aferição de Insumos no Plantio

Este projeto de Business Intelligence tem como objetivo apresentar de forma visual e interativa os resultados de auditorias realizadas para aferição de insumos utilizados no plantio de cana-de-açucar. Foi desenvolvido um dashboard no Power BI que permite a análise de três tipos de insumos: **Adubos**, **Fungicidas** e **Inseticidas**.

##  Funcionalidades do Dashboard

###  Primeira Aba – Resultados da Auditoria

- **Segmentador "Apontamentos"**: permite ao usuário selecionar individualmente cada auditoria registrada, oferecendo uma visão detalhada de cada aferição realizada.
- **Filtros laterais**: seleção por fazenda, talhão, implemento utilizado, turno, auditor ou por data da auditoria.
- **Gráfico de dosagem por bico (esquerdo e direito)**:
  - Apresenta a **dose coletada** por bico.
  - Inclui linhas de **mínimo e máximo tolerado**, que se ajustam automaticamente conforme a dose recomendada:
    - **Máximo** = +10% da dose recomendada.
    - **Mínimo** = -10% da dose recomendada.
- **Cards de variação por lado avaliado**:
  - Apresentam a porcentagem de variação em relação à dose recomendada.
  - Mudam para **vermelho** caso a variação ultrapasse os 10%, alertando o usuário visualmente.
- **Tabela de observações**:
  - Lista os comentários feitos pelo auditor durante a auditoria.

###  Segunda Aba – Tabelas Resumo

- Contém 3 tabelas (uma para cada tipo de insumo):
  - **Adubos**
  - **Fungicidas**
  - **Inseticidas**
- Tabelas com todas as informações preenchidas nas fichas de auditoria.
- Facilmente exportável para Excel, caso o usuário deseje trabalhar os dados fora do Power BI.

##  Tecnologias Utilizadas

- [Power BI](https://powerbi.microsoft.com/)
- Microsoft Excel (como base de dados)
