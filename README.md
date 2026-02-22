# 🚗 Dashboard Corporativo Industrial — Projeto Conceitual

<div align="center">



**Autor: Alessandro Guimarães Pereira**

</div>

> ⚠️ **Todos os dados apresentados são fictícios.**A empresa "NovaDrive Industries", seus colaboradores, indicadores e valores financeiros são **inteiramente simulados** para fins de estudo e demonstração técnica. Este projeto não representa qualquer empresa, pessoa ou organização real.

* * *

## 📋 Sobre o Projeto

Projeto autoral desenvolvido com foco em:

* **Visualização de Dados** corporativos e industriais
* **UX/UI Executivo** — estrutura de painel para múltiplos perfis de usuário
* **Indicadores Industriais** — OEE, PPM, FPY, EBITDA, absenteísmo
* **Modelagem de KPIs** para diferentes áreas e níveis hierárquicos
* **Design System** customizado com tema dark industrial

O objetivo foi simular como um dashboard empresarial real seria estruturado, contemplando **todos os departamentos** de uma montadora — do chão de fábrica à diretoria executiva.

* * *

## 🗂️ Estrutura do Dashboard

6 painéis interativos navegáveis por abas:

| Painel | Conteúdo principal |
| --- | --- |
| 🏠 **Geral** | KPIs globais, organograma hierárquico completo, timeline de eventos, headcount por setor |
| 👥 **Pessoas & RH** | Contratações, diversidade, faixa etária, distribuição por cargo, tabela de funções |
| 🏭 **Produção** | OEE por linha, ordens de produção, indicadores de qualidade, histórico mensal |
| 💰 **Financeiro** | Receita, EBITDA, custos operacionais, contas a pagar, budget anual |
| 🚛 **Frota & Logística** | 284 veículos simulados, disponibilidade, KPIs de entrega, monitoramento |
| ⚙️ **Operacional** | SSMA, segurança do trabalho, manutenção, vendas por canal e modelo |

* * *

## 🏢 Hierarquia Organizacional Simulada

    CEO / Presidente
    ├── VP Operações
    ├── VP Financeiro
    ├── VP Pessoas & RH
    └── VP Engenharia
        ├── Diretores (6 áreas)
        │   └── Coordenadores → Supervisores
        │       ├── Operadores de Produção (N1 e N2)
        │       ├── Técnicos Especializados
        │       ├── Analistas (Jr / Pl / Sr)
        │       ├── Almoxarifes e Motoristas
        │       ├── Vigilantes Patrimoniais
        │       ├── Porteiros / Recepcionistas
        │       └── Serviços Gerais / Limpeza

* * *

## 🛠️ Tecnologias

| Tecnologia | Aplicação |
| --- | --- |
| **HTML5** | Estrutura semântica |
| **CSS3** | Design system completo, animações, responsividade |
| **JavaScript Vanilla** | Navegação por abas, relógio em tempo real, IntersectionObserver |
| **Google Fonts** | Bebas Neue · DM Sans · DM Mono |
| **CSS Custom Properties** | Tokens de design (cores, espaçamento, tipografia) |
| **CSS Grid & Flexbox** | Layouts responsivos e composição visual |

> Projeto desenvolvido **sem frameworks, sem bibliotecas externas de código** — apenas tecnologias nativas da web.

* * *

## 🚀 Como Executar

    # Clone o repositório
    git clone https://github.com/seu-usuario/novadrive-dashboard.git
    
    # Abra direto no navegador
    cd novadrive-dashboard
    # Duplo clique em novadrive_dashboard.html
    # — ou —
    python -m http.server 8080
    # Acesse: http://localhost:8080/novadrive_dashboard.html

> Requer conexão com internet para carregar as fontes via Google Fonts CDN. Funciona offline com fontes de sistema como fallback.

* * *

## 📁 Arquivos

    novadrive-dashboard/
    ├── novadrive_dashboard.html   # Aplicação completa (HTML + CSS + JS em arquivo único)
    └── README.md                  # Este arquivo

* * *

## ⚠️ Disclaimer Legal

> **Projeto Fictício para Portfólio Profissional.**
> 
> Este dashboard foi desenvolvido exclusivamente para fins educacionais e demonstração técnica. Todos os dados, nomes, indicadores, valores financeiros e estruturas organizacionais são **totalmente fictícios** e não representam qualquer empresa real, pessoa física ou jurídica. A empresa "NovaDrive Industries" não existe. Qualquer semelhança com situações ou entidades reais é mera coincidência. Projeto desenvolvido exclusivamente para fins educacionais, acadêmicos e de portfólio profissional, sem qualquer finalidade comercial.

* * *

<div align="center">

Desenvolvido por **Alessandro Guimarães Pereira**



</div>
