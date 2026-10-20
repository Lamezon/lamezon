<div align="right">
  <a href="README.md">🇺🇸 English</a> | <strong>Português</strong>
</div>
<div align="center">

# Matheus Lamezon
### Software Engineer | Systems Architecture & AI-Augmented Development

<p>
  <a href="https://github.com/Lamezon">
    <img src="https://img.shields.io/badge/GitHub-Pro-0d1117?style=flat-square&logo=github&logoColor=white" alt="GitHub Pro" />
  </a>
  <img src="https://img.shields.io/badge/Focus-Backend_&_Architecture-1f2937?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Methodology-AI--Augmented_Engineering-4338ca?style=flat-square" alt="AI Augmented" />
  <img src="https://img.shields.io/badge/Location-Paran%C3%A1%2C_Brasil-374151?style=flat-square" alt="Location" />
</p>

<p align="center">
  Desenvolvedor de software focado em arquitetura backend, integração de dados relacionais e automação de processos corporativos críticos.
</p>

</div>

---

## 📌 Sobre Mim e Modelo Operacional

Atuo na interseção entre **engenharia de software tradicional** e **fluxos modernos orientados por inteligência artificial**. Minha experiência abrange regras de negócio de backoffice (faturamento, estoques, comissões de vendas e relatórios estruturados), modelagem relacional profunda e interoperabilidade entre sistemas.

### 🤖 Engenharia de Software Aumentada por IA (*Human-in-the-Loop*)
Minha abordagem não é a geração passiva de código, mas a **orquestração técnica e governança ativa**:
- **O papel da IA:** Aceleração na escrita de código estrutural (*scaffolding*), refatorações sintáticas, automação de testes e geração rápida de protótipos em velocidade multiplicada.
- **Meu papel técnico:** Definição da arquitetura do sistema, engenharia reversa conceitual, modelagem estrita de dados, análise de segurança e validação determinística de regras fiscais e contábeis.

> **🔒 Nota sobre Repositórios Corporativos:**  
> A maior parte do meu trabalho em produção — incluindo pipelines de migração de dados e ferramentas de engenharia reversa — reside em **repositórios privados sob acordos de confidencialidade (NDA)**. Por envolverem propriedade intelectual restrita e dados fiscais de clientes, o código-fonte permanece confidencial. Abaixo constam meus projetos públicos de referência e os estudos de caso arquiteturais que liderei.

---

## 🛠️ Stack & Tecnologias Verificadas

| Camada | Tecnologias |
| :--- | :--- |
| **Linguagens** | `PHP`, `Python`, `TypeScript`, `JavaScript (ES6+)`, `SQL`, `Java` |
| **Backend & Frameworks** | `Laravel Framework`, `REST APIs`, `mPDF`, `Breeze / Sanctum` |
| **Bancos de Dados & Dados** | `PostgreSQL`, `MySQL`, `SQLite`, `Sybase / ASA`, `Modelagem Relacional`, `ETL` |
| **Automação & Sistemas** | `Windows API (Win32 / MDI)`, `RPA Desktop`, `Engenharia Reversa de Binários` |
| **Frontend & Mobile** | `Tailwind CSS`, `HTML5 / CSS3`, `React Native (TypeScript)`, `Web UI / Canvas` |
| **Qualidade & DevOps** | `Git / GitHub`, `Docker`, `Suítes de Testes Automatizados (E2E)`, `Playwright` |

---

## 🌟 Portfólio de Projetos

### Projetos Públicos de Referência (Código Aberto)

#### 🧾 [Emissão de Fatura](https://github.com/Lamezon/Emissao-de-Fatura)
*Sistema web para gestão comercial, controle de clientes e faturamento automatizado.*
- **Problema:** Necessidade de centralizar faturamento e emitir documentos estruturados para impressão e auditoria sem quebras de layout.
- **Implementação:** Aplicação Laravel com controle de acesso, persistência relacional e renderização dinâmica de PDFs via `mPDF` e planilhas via `Excel`.
- **Tecnologias:** `PHP`, `Laravel`, `mPDF`, `Guzzle`, `MySQL/PostgreSQL`.
- **Estado:** Concluído / Funcional.

#### 📈 [Humtech](https://github.com/Lamezon/humtech)
*Plataforma de gestão operacional, comissionamento e relatórios financeiros.*
- **Problema:** Gestão de vendas descentralizadas e cálculo complexo de comissões de equipe comercial.
- **Implementação:** Arquitetura MVC com controladores dedicados (`EarnController`, `SaleController`), autenticação segura via `Sanctum/Breeze` e banco PostgreSQL.
- **Tecnologias:** `PHP 7.4`, `Laravel 8`, `PostgreSQL 11`, `Breeze`.
- **Estado:** Concluído / Funcional.

#### 📦 [KubaSeller](https://github.com/Lamezon/KubaSeller)
*Módulo de controle de estoque e acompanhamento de vendedores.*
- **Problema:** Rastreabilidade de saídas de mercadorias e desempenho por representante.
- **Implementação:** Separação de escopo por vendedor (`SellerController`), relatórios analíticos de vendas e interface construída com utilitários Tailwind CSS.
- **Tecnologias:** `PHP`, `Laravel`, `Tailwind CSS`, `JavaScript`.
- **Estado:** Protótipo Funcional.

#### 📱 [PasswordApp](https://github.com/Lamezon/PasswordApp)
*Aplicativo móvel multiplataforma para geração e gerenciamento de credenciais.*
- **Implementação:** Construído com React Native e TypeScript estrito, com suporte a internacionalização (`i18n`) e arquitetura de componentes reutilizáveis.
- **Tecnologias:** `TypeScript`, `React Native`, `Ignite CLI`.
- **Estado:** Protótipo Funcional.

---

### Soluções Corporativas & Casos de Arquitetura `🔒 Privado / Enterprise`

#### 1. 🖨️ BGR Editor — Web Studio (Domínio Sistemas / Thomson Reuters)
*Estúdio Web WYSIWYG completo projetado para edição, conversão e compilação do formato binário proprietário `.bgr`.*
- **Engenharia Reversa:** Decodificação e compilação do binário criptografado (XOR + zlib + sintaxe PowerBuilder DataWindow release 11.5).
- **Motor Inteligente PDF → BGR:** Conversor que mapeia PDFs corporativos em relatórios de folha A4 com calibração geométrica milimétrica 1:1.
- **Confiabilidade:** Suíte com 87 testes automatizados cobrindo 15 setores do sistema para garantir zero falhas em produção.
- **Stack:** `Python`, `SQLite / Turso (libSQL)`, `ODBC Sybase ASA`, `Vanilla JS/CSS`.

#### 2. 🔄 Multi-ERP ETL & Migration Engine
*Motor de migração e normalização de dados conectando mais de 30 ERPs contábeis e fiscais do mercado brasileiro.*
- **Engenharia de Dados em Escala:** Dicionário e catálogo estruturado com mais de **5.100 tabelas mapeadas**.
- **Interoperabilidade:** Pipelines de extração e conversão entre bancos de dados heterogêneos (TOTVS Protheus, RM, Questor, Contmatic, Fortes, Senior Rubi, Domínio, etc.).
- **Garantia de Integridade:** Sanitização de inconsistências relacionais e tratamento estrito de integridade referencial.

#### 3. 🤖 DominioExplorer (RPA & Automação Windows Win32)
*Agente de automação para sistemas desktop legados sem APIs disponíveis.*
- Controle de janelas MDI e execução autônoma de fluxos contábeis e de folha via chamadas nativas da Windows API.

---

## 📊 Atividade no GitHub

<div align="center">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=Lamezon&show_icons=true&theme=tokyonight&hide_rank=true&include_all_commits=true" alt="Estatísticas do GitHub" />
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lamezon&layout=compact&theme=tokyonight&langs_count=6" alt="Linguagens mais utilizadas" />
</div>

---

## 📬 Contato Profissional

- **GitHub:** [@Lamezon](https://github.com/Lamezon)
- **Mensagens & Oportunidades:** Aberto a discussões técnicas, projetos de dados/integração e engenharia backend através do GitHub.
