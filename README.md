# pibic-sage-processm
Estudo e execução do SAGE e do ProcessM - PIBIC UNICAP (Process Mining e Cibersegurança)

# PIBIC – Process Mining e Cibersegurança

Estudo e execução de ferramentas de análise de alertas de intrusão,
como parte da Iniciação Científica na UNICAP.

## 01 – SAGE
Notebook: `01_execucao_sage.ipynb`

O SAGE (IntruSion alert-driven Attack Graph Extractor) transforma alertas
de intrusão em grafos de ataque que mostram os caminhos seguidos pelos atacantes.

- Repositório original: https://github.com/tudelft-cda-lab/SAGE
- Dataset usado: CPTC-2018 (6 equipes atacantes)
- Ambiente: Google Colab (o SAGE e o FlexFringe são feitos para Linux)

### Observações da execução
- A versão atual do FlexFringe é incompatível com o SAGE.
  Foi usada a versão `1a87e3b` (2022), a mesma da versão Docker do SAGE.
- Limitação: alertas que não estão na tabela de assinaturas do SAGE
  são classificados como não maliciosos.

## 02 – ProcessM
Em andamento.

## Créditos
SAGE: Azqa Nadeem et al., TU Delft (licença MIT).
Este repositório contém apenas notebooks de estudo e execução.
