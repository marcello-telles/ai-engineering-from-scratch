# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
Evoluir a triagem agêntica de cards da Engenharia de Integrações SAP (V360) para um funcionamento robusto: determinística (fluxo de controle em código, julgamento do LLM restrito e verificado, sem pular etapas obrigatórias), rodando na GCP sem depender da máquina local, com observabilidade e loop de evolução contínua. É o primeiro passo para ela virar a principal ferramenta de triagem de trabalho do time, evoluída por todos como automação do próprio trabalho.

O que construir até 27/11/2026: a triagem rodando na GCP nos horários (Cloud Run job), com trace e custo por card e por etapa, painel de saúde, contrato de saída validado por código e regressão automática a cada PR da skill.

Fonte do plano: nota `aprendizado/Plano de Estudos - Engenharia de IA para a Triagem.md` do segundo cérebro (`marcello-telles/second-brain`), que traz também as práticas (P1.1 a P4.4) com enunciado, objetivo e resultado esperado. **O tutor deve seguir a ordem do plano curado abaixo, e não a ordem por fase.**

## Placement
- Date: 2026-10-31
- Score: self-selected
- Entry point: Phase 14: Agent Engineering
- Pace: ~5h/week

Observação: o teste de nivelamento deu 6/10, mas foi descartado porque o Marcello não conhece ML e acertou parte das questões no chute. O plano é curado para a meta do mês, não para o currículo completo: as aulas vêm das fases 11, 13, 14, 15 e 17 e da trilha de certificação Claude. Fundamentos de ML (fases 1, 2, 3 e 7) ficam para depois de novembro.

## Path
| Phase | Name | Status | Est. hours |
|-------|------|--------|------------|
| 0 | Setup & Tooling | Skip | -- |
| 1 | Math Foundations | Skip | -- |
| 2 | ML Fundamentals | Skip | -- |
| 3 | Deep Learning Core | Skip | -- |
| 4 | Computer Vision | Skip | -- |
| 5 | NLP — Foundations to Advanced | Skip | -- |
| 6 | Speech & Audio | Skip | -- |
| 7 | Transformers Deep Dive | Skip | -- |
| 8 | Generative AI | Skip | -- |
| 9 | Reinforcement Learning | Skip | -- |
| 10 | LLMs from Scratch | Skip | -- |
| 11 | LLM Engineering | Do | 19 |
| 12 | Multimodal AI | Skip | -- |
| 13 | Tools & Protocols | Do | 76 |
| 14 | Agent Engineering | Do | 55 |
| 15 | Autonomous Systems | Do | 20 |
| 16 | Multi-Agent & Swarms | Skip | -- |
| 17 | Infrastructure & Production | Do | 34 |
| 18 | Ethics, Safety & Alignment | Skip | -- |
| 19 | Capstone Projects | Skip | -- |

As horas por fase vêm do ROADMAP.md e valem para a fase inteira. Dentro de cada fase marcada `Do`, só entram as aulas do plano curado abaixo.

### Ordem do plano curado

**Semana 1 (29/10 a 04/11): medir a instabilidade e tornar o contrato executável**
1. `phases/14-agent-engineering/12-anthropic-workflow-patterns`
2. `phases/11-llm-engineering/16-langgraph-state-machines`
3. `phases/14-agent-engineering/33-instructions-as-executable-constraints`
4. `phases/14-agent-engineering/38-verification-gates`
5. `phases/14-agent-engineering/26-failure-modes-agentic`
6. `certifications/claude/lessons/12-claude-agent-sdk-and-hooks`
7. `phases/11-llm-engineering/03-structured-outputs`

**Semana 2 (05/11 a 11/11): evals e o loop de melhoria**
8. `phases/11-llm-engineering/10-evaluation`
9. `phases/14-agent-engineering/30-eval-driven-agent-development`
10. `phases/14-agent-engineering/46-turn-feedback-into-system`
11. `phases/14-agent-engineering/54-build-the-feedback-ratchet`
12. `certifications/claude/lessons/14-evals-testing-debugging-and-observability`

**Semana 3 (12/11 a 18/11): observabilidade e infraestrutura na GCP**
13. `phases/14-agent-engineering/23-otel-genai-conventions`
14. `phases/13-tools-and-protocols/20-opentelemetry-genai`
15. `phases/17-infrastructure-and-production/13-llm-observability`
16. `phases/17-infrastructure-and-production/27-finops-llms`
17. `phases/15-autonomous-systems/13-cost-governors`
18. `phases/17-infrastructure-and-production/25-security-secrets-audit`

**Semana 4 (19/11 a 27/11): sombra na nuvem e entrega ao time**
19. `phases/17-infrastructure-and-production/20-shadow-canary-progressive`
20. `phases/17-infrastructure-and-production/23-sre-for-ai`
21. `phases/15-autonomous-systems/14-kill-switches-canaries`
22. `phases/14-agent-engineering/52-design-success-metrics`
23. `phases/14-agent-engineering/53-prototype-pilot-or-production`
24. `certifications/claude/lessons/19-claude-code-memory-rules-skills-and-ci`

**Dezembro (fase 3 da triagem: dividir por etapa, Agent SDK × ADK)**
25. `phases/14-agent-engineering/17-claude-agent-sdk`
26. `phases/15-autonomous-systems/12-durable-execution`
27. Projeto `projects/support-agent-with-google-adk`

Nas aulas cujo Build It só aponta para o `code/main.py`, sem passos: rodar o gabarito, escrever a própria versão em Node a partir das assinaturas e com exemplos da triagem, e só depois comparar.

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|

## Review queue
