# CNC Planner

Sistema de planejamento de produção CNC integrando solicitações de peças, agendamento semanal/mensal por turno e gestão de capacidade mensal por fábrica.

Single-file HTML app — funciona offline após primeira carga, dados persistidos em `localStorage`.

## Funcionalidades

- **Solicitações** — cadastro, aprovação para compra e checklist de materiais
- **Semanal** — visão por turno (T1/T2/T3) com Torno e Centro separados, capacidade por técnico (420min/turno)
- **Mensal** — calendário tradicional com drag/drop de OSs entre dias
- **Sites** — capacidade mensal por fábrica (Aguaí, Garanhuns, Igarassu, Indaiatuba, Pouso Alegre, Suape, Valinhos, Vinhedo)
- **Desenhos** — biblioteca de desenhos técnicos com tempos de torno/centro/programação editáveis
- **Análise por IA** — upload de PDF/imagem do desenho e roteamento automático na ROMI
- **Planejamento parcial** — divide OS em lotes (ex: 5 hoje + saldo no backlog)

## Como rodar

Abra o arquivo `CNC_Planner.html` em qualquer navegador moderno (Chrome, Edge, Firefox).

## Capacidades cadastradas

Atualmente: Abril, Maio e Junho de 2026.

## Stack

HTML/CSS/JS puro — zero dependências externas em runtime.
