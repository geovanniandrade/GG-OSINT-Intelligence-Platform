# Metodologia OSINT — GG

## Objetivo
Triagem e pesquisa **passiva** em fontes públicas para obter contexto técnico de domínios, IPs, URLs e arquivos. O modo de pessoas serve apenas para navegar por conteúdo publicamente indexado em contexto legítimo e proporcional.

## Fluxo
1. Definir objetivo e autorização.
2. Selecionar tipo de indicador e abrir fonte adequada.
3. Registrar URL, data, tipo de fonte e evidência obtida.
4. Confirmar os vínculos por evidência independente.
5. Classificar confiança (não verificado, parcialmente corroborado, corroborado).
6. Redigir relatório com limitações.

## Fontes e limites
- VirusTotal, AlienVault OTX e NVD: consultas guiadas, nenhuma API integrada.
- Google Dorks: consultas como `site:instagram.com "Nome Sobrenome"` e `site:linkedin.com/in/ "Nome Sobrenome"`, nunca equivalem a prova de identidade.
- Grafo atual: manual/demonstrativo. Não interpreta resultados externos nem os transforma automaticamente em nós.
- Não busque credenciais, endereços particulares ou informações sensíveis. Não tente contornar logins, bloqueios, rate limits ou privacidade.

## Fatos versus hipóteses
Compartilhar IP não prova mesma propriedade; nomes semelhantes não comprovam mesma pessoa; presença em base reputacional não implica malícia.

## Relatório
O relatório separa indicadores fornecidos de correlações realmente verificadas, informa fontes e incertezas e recomenda checagem humana.
