<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=32&pause=1000&color=00D2FF&center=true&vCenter=true&width=850&lines=Ruan+Pablo+%F0%9F%91%A8%F0%9F%8F%BD%E2%80%8D%F0%9F%92%BB;Engenharia+de+Software+%26+Backend+☕;Pós-graduando+em+Arquitetura+na+FIAP+🎓;Java+%E2%80%A2+Spring+%E2%80%A2+Microsserviços" alt="Typing SVG" />
</div>

### 🛰️ Vamos conversar?
<div align="center">
  <a href="https://www.linkedin.com/in/ruanpablo2/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin">
  </a>
  <a href="mailto:ruan.pablo2002@outlook.com.br">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</div>

---

## 👨‍💻 Sobre Mim
Sou desenvolvedor Back-end (Java/Spring) com foco em **Arquitetura de Software** e **Segurança da Informação**. 

Com 5 anos de vivência no mercado corporativo de seguros, desenvolvi uma visão estratégica de negócios: entendo que o código precisa não apenas funcionar, mas garantir disponibilidade, resiliência e resolver os problemas reais da operação. Minha transição para a engenharia de software é impulsionada por essa base, unindo o rigor técnico da segurança (DevSecOps, mitigação de vulnerabilidades e controle de acessos) com a criação de arquiteturas escaláveis.

Atualmente curso pós-graduação em **Arquitetura de Software pela FIAP**, focando em padrões de microsserviços, mensageria assíncrona e infraestrutura em nuvem para construir sistemas corporativos de alta performance.

---

## 🛠️ Stack Tecnológica

<table align="center">
  <tr>
    <td align="center" width="140"><b>Linguagens</b></td>
    <td align="center" width="140"><b>Frameworks & API</b></td>
    <td align="center" width="140"><b>Dados & Mensageria</b></td>
    <td align="center" width="140"><b>Cloud & DevOps</b></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=java,js,ts" alt="Linguagens" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=spring,angular,hibernate" alt="Frameworks" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=postgres,redis,rabbitmq" alt="DB e Mensageria" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=docker,git,githubactions,linux" alt="DevOps" />
    </td>
  </tr>
</table>

---

## 📁 Projetos em Destaque

<table align="center">
  <tr>
    <td colspan="2" align="center">
      <div align="center">
        <h3>🚛 FleetRisk (Ecossistema de Seguros)</h3>
        <img src="https://img.shields.io/badge/Status-Finalizado-blue?style=flat-square" />
      </div>
      <p align="center">
        <b>Modelo de Negócio:</b> Plataforma SaaS B2B para corretores de seguros, automatizando o fluxo de cotação de frotas desde o cálculo atuarial até a aprovação final.
        <br /><br />
        <b>Arquitetura & Engenharia:</b> Sistema construído em <b>Microsserviços</b>, garantindo alta disponibilidade e escalabilidade para o setor financeiro.
      </p>
      <div align="left" style="margin-left: 20px;">
        <ul>
          <li>🤖 <b>Integração IA Generativa:</b> Uso do Google Gemini AI (via RestClient) para gerar mensagens comerciais persuasivas de aprovação para o WhatsApp do cliente.</li>
          <li>⚡ <b>Real-Time & Mensageria:</b> WebSockets (STOMP/SockJS) para atualizações instantâneas de tela e <b>RabbitMQ</b> para desacoplar a geração pesada de apólices em PDF.</li>
          <li>☁️ <b>Infraestrutura:</b> Backend conteinerizado no <b>Oracle Cloud (OCI)</b> com banco PostgreSQL e cache em Redis. Frontend Angular hospedado na Vercel.</li>
        </ul>
      </div>
      <p align="center">🛠 <b>Stack:</b> Java 21, Spring Boot 3, Spring Security, Docker, RabbitMQ, PostgreSQL.</p>
      <div align="center">
        <a href="https://github.com/RuanPablo2/fleet-risk"><b>Ver Repositório</b></a> | 
        <a href="https://fleetrisk.vercel.app"><b>Em produção</b></a>
      </div>
      <br />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <div align="center">
        <h3>🎫 TicketFlow</h3>
        <img src="https://img.shields.io/badge/Status-Finalizado-blue?style=flat-square" />
      </div>
      <br />
      <b>Modelo de Negócio:</b> Help Desk Corporativo para otimização de SLA e gestão de incidentes.
      <br /><br />
      - 🛰️ <b>Event-Driven:</b> Notificações e fluxos de estado assíncronos via RabbitMQ.<br />
      - 🛡️ <b>API Gateway:</b> Roteamento centralizado e segurança RBAC baseada em perfis JWT.<br />
      - 🛠 <b>Stack:</b> Java 21, Spring Boot 3, Cloud Gateway.
      <br /><br />
      <div align="center">
        <a href="https://github.com/RuanPablo2/TicketFlow"><b>Ver Repositório</b></a> | 
        <a href="https://ticketflow-web.netlify.app"><b>Em produção</b></a>
      </div>
    </td>
    <td width="50%" valign="top">
      <div align="center">
        <h3>📈 BeanCounter API</h3>
        <img src="https://img.shields.io/badge/Status-Finalizado-blue?style=flat-square" />
      </div>
      <br />
      <b>Modelo de Negócio:</b> Gestão Financeira com governança rigorosa de acesso aos dados. 
      <br /><br />
      - 🔐 <b>Tenant Isolation:</b> Dados sensíveis isolados e protegidos por usuário (Segurança de Dados).<br />
      - 📊 <b>Dashboard:</b> Cálculo consolidado de saldo e fluxos mensais.<br />
      - 🛠 <b>Stack:</b> Java 17, Spring Boot, JWT, PostgreSQL.
      <br /><br />
      <div align="center">
        <a href="https://github.com/RuanPablo2/beancounter"><b>Ver Repositório</b></a> | 
        <a href="https://beancounter-ui.netlify.app/login"><b>Em produção</b></a>
      </div>
    </td>
  </tr>
</table>

---

## 📊 Atividade no GitHub
<div align="center">
  <img height="180em" src="https://github-stats-extended.vercel.app/api?username=RuanPablo2&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-stats-extended.vercel.app/api/top-langs/?username=RuanPablo2&layout=compact&langs_count=7&theme=tokyonight" />
</div>

---

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00D2FF&center=true&vCenter=true&width=435&lines=%E2%9C%A8+Obrigado+por+visitar+meu+perfil!" />
</div>
