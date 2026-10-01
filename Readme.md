# Mapa integrado das redes de Niterói

Mapa interativo com camadas independentes para equipamentos da Assistência Social e da Saúde municipal. Os tipos da Saúde podem ser ativados ou desativados sem alterar os filtros da Assistência Social.

## Estrutura do repositório

```text
.
├── dados/
│   ├── equipamentos_niteroi.csv
│   ├── equipamentos_saude_niteroi.csv
│   └── equipamentos_saude_niteroi.xlsx
├── index.html
└── Readme.md
```

O `index.html` carrega os dois CSVs pelos caminhos relativos `./dados/`. Mantenha esses nomes e caminhos ao enviar os arquivos ao GitHub Pages.

## Base da Saúde

A planilha reúne 103 registros identificados nas páginas oficiais da Secretaria Municipal de Saúde e em camadas do SIG Niterói. Há coordenadas validadas no SIG para 45 Módulos de Médico da Família, 11 UBS e 2 registros do SAMU. Os outros 44 registros permanecem na planilha sem ponto no mapa até que seu endereço seja confirmado ou geocodificado com segurança.

A rede municipal está separada de unidades estaduais, federais e da rede complementar. Os campos de origem, CNES, região de saúde e status de localização ajudam a revisar e atualizar os dados. Confira os endereços e horários com a unidade antes de usar a planilha como cadastro operacional.

## Fontes principais

- Secretaria Municipal de Saúde de Niterói: https://saude.niteroi.rj.gov.br/unidades-de-saude/
- Módulos do Médico de Família no SIG Niterói: https://sig.niteroi.rj.gov.br/server/rest/services/Hosted/NGP_SMS_FESAUDE_P_REDEPMF_PUBLICO/FeatureServer/10
- UBS no SIG Niterói: https://sig.niteroi.rj.gov.br/server/rest/services/Hosted/Unidades_B%C3%A1sicas_de_Sa%C3%BAde_(UBS)_visualiza%C3%A7%C3%A3o/FeatureServer/0
- SAMU no SIG Niterói: https://sig.niteroi.rj.gov.br/server/rest/services/Hosted/SAMU/FeatureServer/0
- Policlínicas: https://saude.niteroi.rj.gov.br/policlinicas/
- Hospitais: https://saude.niteroi.rj.gov.br/hospitais/
- Urgência e emergência: https://saude.niteroi.rj.gov.br/urgencia-e-emergencia/
- Rede de Atenção Psicossocial: https://saude.niteroi.rj.gov.br/rede-de-atencao-psicossocial/

Dados consultados em 1º de outubro de 2026.
