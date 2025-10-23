# Monitoria Busca Ativa e Desempenho Escolar

Sistema web para monitores registrarem horários de entrada/saída e faltas de alunos, com relatórios em PDF (diário, semanal, mensal).

## Estrutura do Projeto
- `index.html`: Página de login com autenticação.
- `main.html`: Registro de horários (nome do monitor, data, entrada, saída).
- `absences.html`: Registro de faltas (formulário manual com nome, série, data, motivo).
- `reports.html`: Relatórios em PDF (faltas e horários, em tabelas).
- `css/styles.css`: Estilização global.
- `js/auth.js`: Autenticação via mock API.
- `js/schedules.js`: Gerenciamento de horários.
- `js/absences.js`: Gerenciamento de faltas.
- `js/reports.js`: Geração de PDFs.
- `data/mock-api.json`: Simulação de web service.

## Credenciais de Login
- Luiz.silva / 2006
- Jota / 2024
- Manoel / 2025
- Andreia / 2026

## Como Executar Localmente
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seduc-monitoria.git
