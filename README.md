<h1 align="center">João Victor</h1>

<p align="center">
  <em>Fullstack Developer · Interests in Network Systems & Offensive Security</em>
</p>

<p align="center">
  <a href="https://github.com/jtave111">
    <img src="https://komarev.com/ghpvc/?username=jtave111&style=flat-square&color=555" alt="Profile views"/>
  </a>
</p>

---

### 🇧🇷 Sobre

Desenvolvedor fullstack com experiência em construção de aplicações web completas, do backend ao frontend. Nas horas vagas, me aprofundo em programação de sistemas, protocolos de rede em baixo nível e segurança ofensiva/defensiva — áreas que estudo de forma séria e onde os projetos pessoais são o campo de prática.

### 🇺🇸 About

Fullstack developer with experience building end-to-end web applications, from backend APIs to frontend interfaces. Outside of that, I go deep into systems programming, low-level network protocols, and offensive/defensive security — areas I study seriously and where personal projects are the proving ground.

---

### 💻 Desenvolvimento · Development

No dia a dia, construo aplicações com foco em **APIs REST seguras**, **arquitetura de backend**, e **interfaces modernas**. Na stack de backend, o trabalho envolve modelagem de dados, autenticação stateless com JWT, controle de acesso baseado em roles e design de APIs que escalam. No frontend, o foco está em componentização, gerenciamento de estado e entrega de experiências rápidas e consistentes.

In day-to-day work, I build applications focused on **secure REST APIs**, **backend architecture**, and **modern interfaces**. On the backend side, the work involves data modeling, stateless JWT authentication, role-based access control, and scalable API design. On the frontend, the focus is on componentization, state management, and delivering fast, consistent experiences.

---

### 🔬 Interesse: Programação de Redes e Segurança · Interest: Network Programming & Security

Esta é a área onde o aprendizado vai fundo — não só como usuário de ferramentas, mas construindo as próprias.

This is the area where learning goes deep — not just as a tool user, but building the tools themselves.

**Programação de rede em baixo nível · Low-level network programming**

O interesse vai além das abstrações de alto nível: começa na camada de socket POSIX. Isso envolve construção de pacotes ICMP manualmente, varredura de portas via raw sockets TCP sem depender de bibliotecas como libpcap, e entendimento do comportamento real da pilha de rede — como o kernel lida com `CAP_NET_RAW`, o impacto do TTL em fingerprinting de sistema operacional, e a diferença entre conectar-se a uma porta e realmente enviar um SYN bruto. O build system de escolha para esses projetos é CMake, organizando alvos como bibliotecas estáticas independentes (`libping.a`) e executáveis que podem ter capabilities aplicadas (`setcap`) sem recompilar.

The interest goes beyond high-level abstractions: it starts at the POSIX socket layer. This involves crafting ICMP packets by hand, scanning ports via raw TCP sockets without relying on libraries like libpcap, and understanding the actual behavior of the network stack — how the kernel handles `CAP_NET_RAW`, the impact of TTL on OS fingerprinting, and the difference between connecting to a port and actually sending a raw SYN. The build system of choice for these projects is CMake, organizing targets as independent static libraries (`libping.a`) and executables that can have capabilities applied (`setcap`) without recompiling.

**Segurança ofensiva e defensiva · Offensive and defensive security**

O estudo é focado em como sistemas de Command & Control funcionam internamente: a orquestração de agents, o design de canais de comunicação assíncronos e cifrados, e a modelagem de dados de uma sessão de reconhecimento de rede (hosts descobertos → portas abertas → serviços → vulnerabilidades). Do lado defensivo, o interesse está em como plataformas SOC ingerem telemetria de endpoints, detectam desvios, e apresentam inteligência de vulnerabilidades de forma acionável — incluindo integração de LLMs locais para análise de CVEs.

The study is focused on how Command & Control systems work internally: agent orchestration, design of asynchronous encrypted communication channels, and data modeling for a network reconnaissance session (discovered hosts → open ports → services → vulnerabilities). On the defensive side, the interest lies in how SOC platforms ingest endpoint telemetry, detect anomalies, and present vulnerability intelligence in an actionable way — including local LLM integration for CVE analysis.

**Segurança em Java · Java Security**

Um ângulo específico de interesse é a implementação de segurança em aplicações Java: o funcionamento interno do filtro de segurança do Spring Security, autenticação stateless com JWT (construção, validação e gerenciamento de expiração), controle de acesso com RBAC (admin, operador), hash de senhas com BCrypt e a diferença de custo computacional entre fatores, e design de múltiplas camadas de autenticação — como combinar JWT Bearer para operadores humanos com API Keys para agents automatizados num mesmo sistema.

A specific angle of interest is implementing security in Java applications: the internals of the Spring Security filter chain, stateless authentication with JWT (building, validating, and managing expiration), access control with RBAC (admin, operator), password hashing with BCrypt and the computational cost difference between factors, and designing multiple authentication layers — like combining JWT Bearer for human operators with API Keys for automated agents in the same system.

---

### 🛠️ Stack

**Backend**

![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/-Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![C#](https://img.shields.io/badge/-C%23%20%2F%20.NET-512BD4?style=flat-square&logo=csharp&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Frontend**

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Banco de dados & Infra · Database & Infra**

![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CMake](https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

**Sistemas & Segurança · Systems & Security**

![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

---

### 📂 Projetos de interesse · Interest projects

Repositórios onde o estudo de segurança e sistemas toma forma prática:

Repositories where security and systems study takes practical shape:

| Projeto | Descrição | Stack |
|---|---|---|
| [Zombie-Keeper](https://github.com/jtave111/Zombie-Keeper) | Framework C2 full-stack: servidor C2 em Java, arsenal C++17 com raw sockets e dashboard Next.js | Java · Spring Security · C++17 · Raw Sockets · Next.js |
| [NetSentinel](https://github.com/jtave111/NetSentinel) | Plataforma SOC para patch management e detecção de CVEs com LLM local e agentes PowerShell | C# · .NET 10 · Next.js · PowerShell · Ollama |
| [SpiderNet](https://github.com/jtave111/SpiderNet) | Ferramenta de rede em C++ | C++ |

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jtave111&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="170"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=jtave111&theme=tokyonight&hide_border=true" height="170"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jtave111&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="170"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=jtave111&theme=tokyonight&no-frame=true&column=7&margin-w=10"/>
</p>
