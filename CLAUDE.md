# Prime Hall — Contexto do Projeto para o Squad Arsenal v3.4

## Identidade do Projeto

**Cliente:** Prime Hall  
**Segmento:** Casa de Festas / Eventos  
**Localização:** Barreiras, Bahia  
**Responsável (ADS Company):** Davidson Pereira  
**Status:** Início — fase de imersão e estratégia  

---

## Squad Ativo

**Plugin:** `squad-arsenal-aula1` (v3.4.0)  
**Entry point:** `@arsenal-chief`  
**Agentes disponíveis (16):** arsenal-chief, setup-guide, researcher, brand-architect, strategist, planner, immersion-architect, data-analyst, pitch-master, slide-master, copywriter, web-designer, designer, video-creator, traffic-manager, automation-manager  
**Tasks disponíveis (13):** setup-ferramentas, pesquisar-mercado, criar-briefing, criar-big-idea, criar-brandbook, criar-identidade-visual, criar-plano-implementacao, criar-copy, criar-pagina, criar-video, criar-campanha-meta-andromeda, criar-campanha-google-ads, criar-campanha-linkedin-ads  
**Skills arsenal (13):** meta-andromeda, google-ads-2026, linkedin-ads-2026, metricas-trafego-2026, ad-spend-calculator, ad-performance-report, keyword-research, customer-segmentation, ab-test-plan, conversion-funnel-analysis, data-dashboard-design, analytics-setup-guide, attribution-model  

---

## Produto / Serviço

- **O que é:** Casa de festas para eventos sociais e corporativos em Barreiras-BA
- **Dados adicionais:** A serem coletados na fase de imersão (briefing)

---

## Estrutura de Arquivos

```
PRIME HALL/
├── CLAUDE.md                           # Contexto do projeto
├── index.html                          # Hub principal (todas as entregas)
├── assets/                             # Logos e imagens
├── REFERENCIAS/                        # Materiais de referência
├── 01-ESTRATEGIA/
│   ├── 01-pesquisa-mercado/            # Pesquisa de mercado
│   └── 02-briefing/                    # Briefing completo
├── 02-IDENTIDADE-VISUAL/              # Paletas, brandbooks, logo
├── 03-FUNIL-VENDAS/                   # Páginas de captura, vendas, obrigado
├── 04-CONTEUDO-ORGANICO/              # Posts, stories, reels
└── 05-TRAFEGO-PAGO/                   # Campanhas Meta, Google, LinkedIn
```

---

## Fases do Projeto

- [ ] Setup de ferramentas → @setup-guide + task `setup-ferramentas`
- [ ] Pesquisa de mercado → @researcher + task `pesquisar-mercado`
- [ ] Briefing completo → @immersion-architect + task `criar-briefing`
- [ ] Big Idea da campanha → @strategist + task `criar-big-idea`
- [ ] Identidade visual (paletas + logo) → @brand-architect + task `criar-identidade-visual`
- [ ] Brandbook → @brand-architect + task `criar-brandbook`
- [ ] Plano de implementação → @planner + task `criar-plano-implementacao`
- [ ] Copy da campanha → @copywriter + task `criar-copy`
- [ ] Funil de vendas (páginas) → @web-designer + task `criar-pagina`
- [ ] Criativos (feed, stories, carrossel) → @designer
- [ ] Vídeos animados (reels, apresentações) → @video-creator + task `criar-video`
- [ ] Campanha Meta Andromeda → @traffic-manager + task `criar-campanha-meta-andromeda`
- [ ] Campanha Google Ads → @traffic-manager + task `criar-campanha-google-ads`
- [ ] Campanha LinkedIn Ads → @traffic-manager + task `criar-campanha-linkedin-ads`
- [ ] Dashboard de métricas → @data-analyst
- [ ] Automações e integrações → @automation-manager

---

## Regras do Projeto

1. Outputs HTML — nunca Markdown para entregas visuais
2. Sempre manter acentuação correta em português
3. Responsividade obrigatória: mobile-first, testar em 480px / 768px / 1024px / desktop
4. Tipografia e paleta a serem definidos na fase de identidade visual
5. Protocolo Anti-IA: nenhuma referência a IA nos outputs finais
