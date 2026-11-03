<!--
  Shashank Pandya — GitHub Profile README
  Save this as `shashankpandya/README.md` (your special profile repo).
-->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,15,18,22,25&height=200&section=header&text=Shashank%20Pandya&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Full-Stack%20Developer%20%C2%B7%20GenAI%20Engineer%20%C2%B7%20IIT%20Kharagpur&descSize=18&descAlignY=56&descColor=ffffff" width="100%" alt="Shashank Pandya" />

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=620&lines=Event-driven+backends+with+Node.js+%26+Python;Serverless+GenAI+on+AWS+Bedrock;Smart+contracts+in+Solidity;Codeforces+Specialist+%C2%B7+CodeChef+3%E2%98%85" alt="Typing SVG" />

</div>

<br/>

<div align="center">

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shashank-pandya-213366287/)
  [![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-shashankpandya.vercel.app/)
  [![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pandyashashank1@gmail.com)
  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shashankpandya)
  ![Profile Views](https://komarev.com/ghpvc/?username=shashankpandya&label=PROFILE+VIEWS&color=A78BFA&style=for-the-badge)

</div>

---

### Hi, I'm Shashank 👋

I'm a full-stack and GenAI engineer at **IIT Kharagpur**. My degree says *Civil Engineering*; my commit history says **event-driven backends, serverless GenAI on AWS, and Web3**. I build systems that hold up under real load, stay cheap to run, and stay readable for the next engineer, and I keep my fundamentals sharp through rated contests on Codeforces and CodeChef.

```ts
const shashank = {
  role:      "Full-Stack & GenAI Engineer",
  education: "B.Tech (Hons.) Civil Engineering · IIT Kharagpur · 2027",
  languages: ["Python", "TypeScript", "JavaScript", "C++", "Solidity"],
  interests: ["Serverless", "Event-driven systems", "RAG / Agentic AI", "Web3"],
} as const;
```

---
## <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/616df735-e8ca-432c-8c71-96073e3f6f7a" /> Featured Projects

### <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/d96a234f-4aa4-46f3-bd10-1d1f4cf8c60c" /> [Aira — AI Technical Interview Coach](https://github.com/shashankpandya/Aira)
> **Voice-first. Serverless. WhatsApp-native. Built for the AWS AI for Bharat Hackathon.**

Students in Tier-2/3 cities lack affordable, multilingual interview prep — existing tools are English-only, expensive, and need broadband. **Aira** fixes that.

A candidate sends a voice note in Hinglish/Hindi on WhatsApp → **Lambda A** ingests it, kicks off **Amazon Transcribe**, and shuts down. **EventBridge** wakes **Lambda B** when transcription finishes — it grades the answer with **AWS Bedrock (Claude 3) / Gemini**, generates the next adaptive question, and ships spoken feedback via **Amazon Polly**. All session state lives in **DynamoDB**. Zero app install, low bandwidth, ~$1.31/user/month.

**Stack:** `Python` `AWS Lambda` `Amazon Transcribe` `Amazon Polly` `EventBridge` `DynamoDB` `S3` `LangChain` `Bedrock` `WhatsApp Business API`

<p>
  <img src="https://img.shields.io/badge/Users-1,000%2B_concurrent-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Cost-~%241.31%2Fuser%2Fmonth-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Input-Hinglish%20%2B%20Hindi%20voice-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Architecture-Fully_decoupled_serverless-22C55E?style=flat-square" />
</p>

---

### <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/103e7f6e-9627-4f48-b832-dceefa91b59b" /> [Crypto Portfolio Tracker](https://github.com/shashankpandya/Crypto_Portfolio)
> **Privacy-first. Offline-capable. Your data never leaves your browser.**

Most crypto trackers force you through a third party that stores your financial data. Not this one.

A full-stack dashboard with a **React + Vite** frontend, **Node.js** backend, and **client-side IndexedDB** for offline-first persistence — no account, no cloud, no third-party access. **Hardhat**-based smart contracts handle on-chain holding verification, and **Chart.js** powers real-time visualisations.

**Stack:** `React` `Vite` `Node.js` `Solidity` `Hardhat` `Chart.js` `IndexedDB` `Web3.js`

<p>
  <img src="https://img.shields.io/badge/Storage-100%25_client--side-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Mode-Offline--first-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/On--chain-ERC--20_verified-22C55E?style=flat-square" />
</p>

---

### <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/b4d5e639-35f0-4b58-80af-6ff34552f550" /> [Megalith 2025 — College Fest Platform](https://github.com/1mansri/Megalith-2025)
> **One dashboard, 10 events, 500+ active users. Built by a 15-member web team.**

The official event-management platform for **IIT Kharagpur's largest technical fest**. Students register, join teams, sign up for workshops, pay via **Razorpay**, and get auto-generated certificates. Admins manage everything from a dedicated dashboard. Server-rendered with **Next.js** for snappy first-paint.

**Stack:** `Next.js` `TypeScript` `React` `Tailwind` `MongoDB` `Mongoose` `Razorpay` `Nodemailer`

<p>
  <img src="https://img.shields.io/badge/Events_managed-10-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Team_size-15-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Participation_growth-%2B25%25-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/My_role-Backend_%2B_admin_dashboard-22C55E?style=flat-square" />
</p>

---

### <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/2ef8a0a4-1562-4e49-9dd0-f990debf9888" /> [BuyChai — Decentralised Creator Support](https://github.com/shashankpandya/BuyChai)
> **No platform fees. No middlemen. Just ETH, direct from supporter to creator.**

A trustless alternative to "Buy Me a Coffee" — supporters send **ETH** straight to creators via a **Solidity** smart contract. The React frontend hooks into **MetaMask**; the contract enforces every business rule on-chain. **Zero platform fees**, deployed live on **Vercel**.

**Stack:** `Solidity` `Hardhat` `React` `Ethers.js` `Vercel`

<p>
  <img src="https://img.shields.io/badge/Fees-0%25_platform-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Logic-100%25_on--chain-22C55E?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Live_on_Vercel-22C55E?style=flat-square" />
</p>

</div>
<p align="right"><a href="https://github.com/shashankpandya?tab=repositories">See all repositories →</a></p>

---

## <img src="https://github.com/user-attachments/assets/9f9de277-b129-4031-8d1a-1ac731b1f3b7" width="24" height="24" alt="" /> Tech Stack

| Domain | Technologies |
|:--|:--|
| **Languages** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000" alt="JavaScript" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" /> <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=000" alt="C" /> <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" alt="Solidity" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" /> |
| **Frontend** | <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" /> <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" /> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" /> |
| **Backend** | <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" /> <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express.js" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" /> <img src="https://img.shields.io/badge/REST_APIs-02569B?style=flat-square&logo=openapiinitiative&logoColor=white" alt="REST APIs" /> |
| **Cloud & DevOps** | <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900" alt="AWS" /> <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=black" alt="AWS Lambda" /> <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white" alt="Amazon S3" /> <img src="https://img.shields.io/badge/EventBridge-FF4F8B?style=flat-square&logo=amazon-aws&logoColor=white" alt="EventBridge" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" /> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions" /> |
| **GenAI** | <img src="https://img.shields.io/badge/Amazon_Bedrock-8A2BE2?style=flat-square&logo=amazon-aws&logoColor=white" alt="Amazon Bedrock" /> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" /> <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=google-gemini&logoColor=white" alt="Google Gemini" /> <img src="https://img.shields.io/badge/RAG-0F766E?style=flat-square" alt="RAG" /> |
| **Web3** | <img src="https://img.shields.io/badge/Hardhat-FFF100?style=flat-square&logo=ethereum&logoColor=000" alt="Hardhat" /> <img src="https://img.shields.io/badge/Ethers.js-2535A0?style=flat-square&logo=ethereum&logoColor=white" alt="Ethers.js" /> <img src="https://img.shields.io/badge/Web3.js-F16822?style=flat-square&logo=web3dotjs&logoColor=white" alt="Web3.js" /> |
| **Databases** | <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" /> <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white" alt="DynamoDB" /> |

---

## <img src="https://github.com/user-attachments/assets/1b051e22-19b3-4b53-b99b-a5867fb4a028" width="24" height="24" alt="" /> Competitive Programming

| Platform | Result | Details |
|:--|:--|:--|
| **Codeforces** | Specialist | peak **1532**  |
| **CodeChef** | 3★ · peak **1709** | Top **1.5%** globally in Starters 191 |
| **CodeNite 2025** (IIT KGP) | Top **8.8%** | Out of 20,000+ participants |
| **Problem solving** | **450+** solved | Algorithmic problems across platforms |

---

## <img src="https://github.com/user-attachments/assets/a5721585-2abd-4880-9493-cbe177ab2663" width="24" height="24" alt="" /> Leadership & Community

- **Team Lead, Aira:** led a cross-functional team to architect and ship a scalable GenAI product for the AWS AI for Bharat Hackathon
- **Blockchain Head, KodeinKGP:** running the Web3 curriculum and hackathons for a 40+ member community, and writing beginner-friendly blockchain articles on Medium
- **Core Team, Megalith 2025:** coordinated a 15-member web team that delivered 10 events and drove 25% participation growth

## <img src="https://github.com/user-attachments/assets/7903724a-79e3-4d7c-be94-7f6b5d0a6fd6" width="24" height="24" alt="" /> Beyond the Code

🏀 **Gold**, Inter-Hall Basketball &nbsp;·&nbsp; 🎖️ **NCC** cadet &nbsp;·&nbsp; 🎨 **2nd place**, Inter-Hall Rangoli &nbsp;·&nbsp; 🤝 Mentor in student dev communities

---

## <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/be6dce27-bd22-4641-b7da-b96a7514ff4b" /> GitHub Analytics

  <div align="center">
  <img width="47%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=shashankpandya&theme=tokyonight&hide_border=true" alt="Top Languages by Repo" />
  <img width="47%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=shashankpandya&theme=tokyonight&hide_border=true" alt="Most Productive Time" />
</div>

<br/>

<div align="center">

### <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/84fa4ff1-9bc1-4257-a56d-fe8f01d0fad4" /> GitHub Achievements

[![Stars](https://img.shields.io/github/stars/shashankpandya?style=for-the-badge&logo=github&label=Total%20Stars%20Received&color=A78BFA)](https://github.com/shashankpandya?tab=repositories&sort=stargazers)
[![Followers](https://img.shields.io/github/followers/shashankpandya?style=for-the-badge&logo=github&label=Followers&color=A78BFA)](https://github.com/shashankpandya?tab=followers)
[![Pull Requests](https://img.shields.io/badge/-Pull%20Requests-181717?style=for-the-badge&logo=github)](https://github.com/shashankpandya?tab=overview&from=2024-01-01)
[![Issues](https://img.shields.io/badge/-Issues%20Opened-181717?style=for-the-badge&logo=github)](https://github.com/shashankpandya?tab=overview&from=2024-01-01)

</div>

---
<!--
<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Dev Quote" />
</div>
-->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shashankpandya/shashankpandya/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shashankpandya/shashankpandya/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/shashankpandya/shashankpandya/output/github-snake.svg" />
</picture>

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="mailto:pandyashashank1@gmail.com">
          <img src="https://github.com/user-attachments/assets/35b80a23-7f6a-4685-b70e-6d92820416f6" width="45"><br>Email
        </a>
      </td>
      <td align="center">
        <a href="https://www.linkedin.com/in/shashank-pandya-213366287/">
          <img src="https://github.com/user-attachments/assets/4bc78a71-60d6-45ad-b3d9-0195146888e8" width="45"><br>LinkedIn
        </a>
      </td>
      <td align="center">
        <a href="https://portfolio-shashankpandya.vercel.app/">
          <img src="https://github.com/user-attachments/assets/4fb1c0bc-1650-48ac-bec6-9d50b73d0316" width="45"><br>Portfolio
        </a>
      </td>
    </tr>
  </table>
</div>
<!--
---
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,15,18,22,25&height=120&section=footer" width="100%" alt="Footer wave"/>
</div>
-->
