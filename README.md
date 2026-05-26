# CLEAR × TCE-ES · Teorias de Mudança Setoriais

> **Convênio nº 00017/2024-4C** · FGV CLEAR e Tribunal de Contas do Estado do Espírito Santo
> *Sistema de Monitoramento de Políticas Públicas Municipais*

Três teorias de mudança setoriais — **Saúde**, **Educação** e **Assistência Social** — desenvolvidas como infraestrutura compartilhada para os municípios capixabas. Cada teoria mapeia a cadeia causal que liga insumos a impactos, em cinco colunas: Insumos → Atividades → Produtos → Resultados → Impactos.

🔗 **Site:** https://caiodesouzacastro.github.io/clear-tdms-municipais/

## Sobre

Uma teoria da mudança torna explícita a hipótese causal por trás de uma política. Sem essa cadeia, o monitoramento vira coleta de números sem norte e a avaliação vira opinião. As três teorias aqui apresentadas oferecem um vocabulário comum para gestores, avaliadores e órgãos de controle pensarem políticas municipais como cadeias de efeito, não como ações isoladas.

| Setor | Insumos centrais | Impactos finais |
|---|---|---|
| **Saúde** | DATASUS, Plano Estadual de Saúde, orçamento, conselhos | Redução da mortalidade infantil, ampliação da expectativa de vida |
| **Educação** | FUNDEB, PNE, PNLD, Censo Escolar, conselhos | Aprendizagem, redução da evasão, equidade educacional |
| **Assistência Social** | SUAS, CadÚnico, NOB SUAS, IGD-M | Interrupção do ciclo intergeracional de pobreza |

Cada teoria é apresentada em duas versões:

- **Simplificada**: caixas organizadas em colunas, sem setas. Boa para leitura panorâmica.
- **Completa**: com setas explicitando as conexões causais entre caixas. Mais densa, indicada para uso técnico.

## Estrutura do repositório

```
clear-tdms-municipais/
├── index.html              ← portal com cards das 3 teorias
├── saude/index.html        ← visualizador da TdM de Saúde
├── educacao/index.html     ← visualizador da TdM de Educação
├── assistencia/index.html  ← visualizador da TdM de Assistência Social
├── assets/
│   ├── tdms/               ← JPGs e PDFs das teorias
│   ├── css/style.css       ← design system
│   └── js/viewer.js        ← zoom/pan inline
├── README.md
└── LICENSE
```

## Como rodar localmente

```bash
git clone https://github.com/caiodesouzacastro/clear-tdms-municipais.git
cd clear-tdms-municipais
python3 -m http.server 8000
# abra http://localhost:8000
```

Ou simplesmente abra `index.html` no navegador.

## Como publicar no GitHub Pages

1. Suba o repositório para o GitHub.
2. Settings → Pages → Source: `main` / `(root)`.
3. Aguarde alguns minutos e acesse `https://<usuario>.github.io/clear-tdms-municipais/`.

## Créditos

- **Conteúdo:** Equipe FGV CLEAR e parceiros do projeto de sistema de monitoramento municipal (TCE-ES).
- **Desenvolvimento web:** FGV CLEAR.
- **Convênio:** nº 00017/2024-4C, entre FGV CLEAR (FGV EESP) e TCE-ES.

## Licença

- **Código:** MIT — veja [LICENSE](LICENSE).
- **Conteúdo das teorias e textos editoriais:** CC BY 4.0 — atribuição obrigatória ao FGV CLEAR / TCE-ES.

---

*Para mais protótipos e bens públicos do FGV CLEAR:*
- [Painel CLEAR](https://caiodesouzacastro.github.io/painel-clear/)
- [Radar de Políticas Municipais](https://caiodesouzacastro.github.io/radar-politicas-municipais/)
- [CLEAR Lab Prototypes](https://caiodesouzacastro.github.io/clear-lab-prototypes/)
