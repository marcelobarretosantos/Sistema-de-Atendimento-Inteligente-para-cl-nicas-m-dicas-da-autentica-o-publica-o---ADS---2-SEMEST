# Sistema-de-Atendimento-Inteligente-para-cl-nicas-m-dicas-da-autentica-o-publica-o---ADS---2-SEMEST
aplicação web com Vue.js (frontend) e Node.js (backend), que implemente autenticação, integrações com APIs externas e recursos de gerenciamento de agendamentos

Sistema de Gestão Hospitalar - Clínica Médica MBS

Este projeto Full-stack foi desenvolvido como Trabalho Discente (TD) para a disciplina de **Programação Back-end III**. A aplicação simula o ambiente de uma clínica médica (MBS - Marcelo Barreto Santos), integrando agendamentos de pacientes com dados climáticos em tempo real.

Projeto
- Interface personalizada para a Clínica Médica MBS.
- **Fluxo de Sessão:** Sistema de Login e Logout funcional com persistência de dados.
- **Inteligência Climática:** Consulta automática à API OpenWeatherMap baseada na localização do paciente (ViaCEP).
- **Automação de Setup:** Script `.bat` exclusivo para instalação e inicialização rápida.

Tecnologias e Arquitetura
- **Frontend:** Vue.js 3 (Vite) + Axios.
- **Backend:** Node.js + Express.js + JSON Web Token (JWT).
- **Banco de Dados:** MongoDB Atlas (NoSQL Cloud).
- **APIs de Terceiros:** ViaCEP e OpenWeatherMap.

Como executar
1. Clone este repositório.
2. Na pasta `/backend`, configure o arquivo `.env` com sua `MONGO_URI` e `WEATHER_KEY`.
3. Execute o arquivo **`LIGAR_TUDO.bat`** na raiz do projeto. 
   - O script instalará as dependências e abrirá o Dashboard automaticamente em: `http://localhost:5173/dashboard`.

## Referências Bibliográficas (ABNT)

ALVES, William Pereira. **Node.js: Elaboração de APIs**. São Paulo: Érica, 2015.

FREITAS, Daniel; et al. **Programação Back-end III**. Porto Alegre: Sagah, 2021.

OLIVEIRA, Ricardo; ZANETTI, Humberto. **Desenvolvimento Web com Vue.js**. Rio de Janeiro: Brasport, 2020.
