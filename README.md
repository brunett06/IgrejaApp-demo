# ⛪ Igreja App: plataforma de gestão para igrejas

Plataforma SaaS **multi-tenant** para gestão de igrejas, com foco no **engajamento do membro pelo celular**: leitura da Bíblia, jornadas com pontos, oração e agenda. Para líderes e tesouraria, tem a gestão completa da igreja.

> 🔒 O código-fonte é privado. Este repositório mostra o sistema em funcionamento: **telas reais**, com dados de exemplo.

## 📱 Telas
<table>
<tr><td align="center"><img src="telas/dashboard.png" width="230" alt="Painel do membro"><br><sub>Painel do membro</sub></td><td align="center"><img src="telas/biblia.png" width="230" alt="Plano de leitura da Bíblia"><br><sub>Plano de leitura da Bíblia</sub></td><td align="center"><img src="telas/jornadas-ranking.png" width="230" alt="Ranking das jornadas"><br><sub>Ranking das jornadas</sub></td></tr>
<tr><td align="center"><img src="telas/pastoral-assistente.png" width="230" alt="Assistente com IA"><br><sub>Assistente com IA</sub></td><td align="center"><img src="telas/financeiro.png" width="230" alt="Financeiro"><br><sub>Financeiro</sub></td><td align="center"><img src="telas/kids.png" width="230" alt="Kids"><br><sub>Kids</sub></td></tr>
</table>

## Funcionalidades
- **Bíblia e plano de leitura:** capítulo do dia, sequência de dias seguidos e áudio do capítulo
- **Jornadas e gamificação:** trilhas, metas, pontos, conquistas e ranking mensal
- **Assistente com IA:** ajuda com versículos, mensagens e ideias para células, além de um quiz diário da Bíblia
- **Kids:** turmas por faixa etária e check-in por QR Code
- **Financeiro:** dízimos, ofertas, despesas, orçamento e patrimônio
- **Visitantes:** funil de acompanhamento, do primeiro contato até a decisão
- **Notificações:** no app e push no celular
- **Planos e assinatura:** Gratuito, Básico, Pro e Igreja Plena, com checkout pelo Stripe

## Em números
- Mais de **140 telas**
- **5 perfis de acesso** (membro, voluntário, líder, tesoureiro e administrador), além de um painel de super admin da plataforma
- Cada igreja tem seus dados isolados, com Row Level Security em todas as tabelas
- Auditoria de segurança concluída sem falhas críticas, com teste automatizado de isolamento entre igrejas
- API REST com chave de acesso para integrações

## Tecnologias
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)

## Como foi feito
Eu defini os requisitos, as regras de negócio e os perfis de acesso. O desenvolvimento foi assistido por IA (Claude Code), testando cada funcionalidade antes de avançar.

## Contato
Demonstração completa sob solicitação: [LinkedIn](https://linkedin.com/in/brunaaganett) · [Portfólio](https://brunaaganettportifolio.lovable.app) · brunacassiane6@hotmail.com
