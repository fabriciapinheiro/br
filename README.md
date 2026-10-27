# Painel Brasil

Painel para celular com os principais indicadores do Brasil e de Piracicaba/SP, reunidos em 27/out/2026.

**Abas**
- **Panorama:** Selic, inflação, PIB, desemprego, dívida bruta, dólar e Ibovespa
- **Impacto social:** fome, insegurança alimentar, Mapa da Fome, pobreza, desigualdade e políticas públicas
- **Poder de compra:** salário mínimo, renda, cesta básica vs. salário mínimo, preços de alimentos, safra e agro
- **Amazônia e terras raras:** desmatamento, queimadas, estados, medidas em andamento e terras raras
- **Dívida pública:** trajetória, quem financia, indexadores e o que está sendo feito
- **Congresso:** PECs, orçamento, vetos e projetos
- **Plano do governo:** propostas 2027–2030 em kanban, com descrição de cada uma
- **Piracicaba** (no menu Local): indicadores da cidade agrupados por prefeito

Toque em um indicador para ver o que ele mede, quando é bom ou ruim, o impacto no dia a dia e o histórico agrupado por mandato.

## Como abrir
Abra `index.html` no navegador, ou ative o GitHub Pages (Settings → Pages → branch `main`, pasta raiz).

## Dados
- `data.js` contém todos os dados usados pela página; `data/*.json` traz os mesmos dados separados por tema.
- Fontes: IBGE, Banco Central, Tesouro Nacional, FAO/ONU, B3, Conab, Dieese, INPE, Caged, Inep, TCE-SP, Ipplap e Agência Senado.
- As etiquetas favorável/atenção/desfavorável, os textos de impacto e o status das propostas são análise, não classificação oficial.
- Algumas séries históricas foram compiladas a partir das bases oficiais e merecem conferência ano a ano.
