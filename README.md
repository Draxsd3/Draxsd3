<p align="center">
  <img src="assets/profile-header.svg" alt="Renan Ramos — criando produtos, automações e experiências digitais" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/renan-ramos">
    <img src="https://img.shields.io/badge/LinkedIn-conectar-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Draxsd3">
    <img src="https://img.shields.io/badge/GitHub-Draxsd3-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=Draxsd3&style=flat-square&color=7C3AED&label=visitas+ao+perfil" alt="Visitas ao perfil" />
</p>

## Olá, eu sou o Renan 👋

Sou desenvolvedor de software e gosto de transformar ideias em produtos digitais úteis. Entre uma interface, uma API e uma automação, meu objetivo é sempre o mesmo: **resolver problemas reais com experiências simples e tecnologia bem aplicada**.

Construo projetos full stack, exploro IA aplicada e automações, e desenvolvo produtos autorais pela **StreetLabs**.

<table>
  <tr>
    <td width="50%" valign="top">

### O que eu construo

- Aplicações web de ponta a ponta
- APIs, integrações e regras de negócio
- Automações que eliminam trabalho repetitivo
- Produtos digitais com intenção e utilidade

    </td>
    <td width="50%" valign="top">

### Meu jeito de trabalhar

- Começo pelo problema, não pela ferramenta
- Equilibro simplicidade e escala
- Valorizo detalhe, clareza e boa experiência
- Aprendo construindo e publico o que faz sentido

    </td>
  </tr>
</table>

## Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=laravel,php,nodejs,react,ts,js,mysql,mongodb,docker,git,linux&perline=11" alt="Laravel, PHP, Node.js, React, TypeScript, JavaScript, MySQL, MongoDB, Docker, Git e Linux" />
</p>

<p align="center">
  <code>Laravel</code> · <code>Node.js</code> · <code>React</code> · <code>TypeScript</code> · <code>MySQL</code> · <code>MongoDB</code> · <code>n8n</code> · <code>Docker</code>
</p>

## Projetos em destaque

<table>
  <tr>
    <td width="33%" valign="top">

### 🎓 [Gestão Escolar](https://github.com/Draxsd3/gestao-escolar-fullstack)

Uma plataforma acadêmica com múltiplos perfis, financeiro integrado, permissões e documentos.

`Laravel` `React` `Sanctum`

    </td>
    <td width="33%" valign="top">

### 📈 [CRM Full-Stack](https://github.com/Draxsd3/CRM-FullStack)

CRM para organizar leads e pipeline comercial, com autenticação por papel e consulta de CNPJ.

`Node.js` `Express` `React`

    </td>
    <td width="33%" valign="top">

### ✉️ [API Email](https://github.com/Draxsd3/api-email)

Uma API prática para conectar envio de e-mails a aplicações e automações.

`Node.js` `API`

    </td>
  </tr>
</table>

## Dev Quest 🎮

<p align="center">
  <img src="assets/dev-quest.svg" alt="Dev Quest: encontre o bug antes do deploy" width="100%" />
</p>

<details>
  <summary><b>🕹️ Jogar: qual é o bug?</b></summary>
  <br />

O código está quase pronto. Antes de liberar o deploy, encontre o detalhe que pode quebrar a missão:

```js
const deploy = async () => {
  const checks = await runChecks();

  if (checks.passed) {
    publish();
  }

  notifyTeam("Deploy concluído!");
};
```

<details>
  <summary>Ver resposta</summary>
  <br />

`publish()` não é aguardado. A mensagem pode ser enviada antes de o deploy terminar — ou até mesmo quando ele falhar. Uma versão mais segura seria:

```js
if (!checks.passed) throw new Error("Checks não passaram");
await publish();
notifyTeam("Deploy concluído!");
```
</details>
</details>

## Atividade

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Draxsd3&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=22D3EE&text_color=CBD5E1" alt="Estatísticas do GitHub" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Draxsd3&hide_border=true&background=0D1117&ring=A78BFA&fire=F59E0B&currStreakLabel=CBD5E1&sideLabels=CBD5E1&dates=64748B&sideNums=F8FAFC&currStreakNum=F8FAFC" alt="Sequência de contribuições" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Draxsd3&bg_color=0D1117&color=CBD5E1&line=A78BFA&point=22D3EE&area=true&hide_border=true" alt="Gráfico de atividade no GitHub" width="100%" />
</p>

---

<p align="center">
  <i>Construindo, aprendendo e colocando ideias no mundo — uma entrega por vez.</i><br /><br />
  <a href="https://www.linkedin.com/in/renan-ramos">Vamos conversar?</a>
</p>
