# 🔎 GG // OSINT Intelligence Platform

![Status](https://img.shields.io/badge/STATUS-MVP%200.1-FB7185?style=for-the-badge&labelColor=111827)
[![Abrir interface](https://img.shields.io/badge/🌐%20ABRIR-INTERFACE-FB7185?style=for-the-badge&labelColor=111827)](https://geovanniandrade.github.io/GG-OSINT-Intelligence-Platform/)
[![Documentação](https://img.shields.io/badge/📘%20GUIA-DOCUMENTAÇÃO-FDA4AF?style=for-the-badge&labelColor=111827)](docs/methodology.md)

**Investigações OSINT guiadas com fontes públicas, grafo interativo, pesquisas direcionadas e relatórios.**

> **Cor do projeto:** vermelho claro / coral `#FB7185` · **Status:** protótipo educacional em desenvolvimento, não homologado para produção.

## 🎯 O que faz

- **Investigação técnica:** pesquisas orientadas para domínio, IP, URL e hash, com links para fontes públicas
- **Pesquisa de pessoas em fontes públicas:** consultas guiadas para Google, Instagram, LinkedIn e GitHub sem extração automatizada de dados
- **Grafo interativo:** nós clicáveis com detalhes e origem da informação; o grafo de demonstração é fictício
- **Relatório independente:** abre uma página de resumo e permite imprimir ou salvar como PDF
- **Demonstração segura:** usa nomes e endereços reservados para documentação

## 🚀 Como testar

1. Clique em **[Abrir interface web](https://geovanniandrade.github.io/GG-OSINT-Intelligence-Platform/)**.
2. Selecione **🧪 Exemplo fictício** para experimentar o grafo.
3. Clique nos nós para conferir detalhes.
4. Selecione **Abrir relatório → Salvar como PDF**.
5. Para uma pesquisa guiada, informe um indicador público e abra as fontes disponíveis.

## 🧭 Estrutura

| Caminho | Conteúdo |
|---|---|
| `index.html` | Dashboard e grafo interativo |
| `report.html` | Relatório em página separada |
| `examples/investigation-demo.json` | Exemplo fictício |
| `docs/methodology.md` | Metodologia, privacidade e fontes |
| `QUALITY.md` | Limitações e testes de aceite |

## ⚠️ Escopo e privacidade

**A versão 0.1 não utiliza APIs de terceiros, não realiza varredura ativa, não automatiza buscas ou downloads e não confirma associação entre entidades reais.** A pesquisa de pessoa abre consultas em mecanismos públicos, sem agregação de dados privados. Serviços externos recebem os termos consultados ao abrir os links. Não use a ferramenta para exposição indevida, perseguição ou coleta de dados confidenciais. Para uso empresarial, exige revisão e autorização.

**Próximos passos:** conectores de fontes públicas com controle de acesso e limites, importação de evidências com origem verificável, filtros no grafo e testes de segurança.

---

**GG // Security Applications** · Ferramentas defensivas, evidências verificáveis e documentação objetiva.
