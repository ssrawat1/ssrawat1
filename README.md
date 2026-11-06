<h1 align="center">💫 Hi 👋, I'm Sanjay Singh Rawat</h1> 
<h3 align="center">Full-Stack Developer | MERN · Next.js · TypeScript · AWS</h3>
<p align="center"><i>I build the interface, the API and the deployment pipeline, and I make each one fast and secure.</i></p>

<br>

- 🔭 **Currently building:** Cloud Storage App v2, an improved version with AWS S3, CloudFront and Redis
- 💼 **Experience:** Frontend Developer Intern at National Fertilizers Limited (React, TypeScript, Tailwind CSS)
- 🌱 **Currently learning:** Advanced deployment and scaling with CI/CD and Nginx
- 🎯 **Looking for:** Full-Stack, Frontend and MERN Stack roles in a fast-moving product team
- 📫 **Reach me:** [ssr911999@gmail.com](mailto:ssr911999@gmail.com)

<br>

# 🛠️ Skills in Action

| Area | Technologies | Where I used them |
|------|--------------|-------------------|
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS | Shopee E-commerce, Cloud Storage, NFL internship |
| **Backend** | Node.js, Express, REST APIs, OAuth, RBAC | Cloud Storage, Shopee E-commerce, CI/CD Server |
| **Database & Caching** | MongoDB, Mongoose, Redis | Cloud Storage (Redis was 7x to 10x faster than MongoDB on reads) |
| **Cloud** | AWS S3, CloudFront | Cloud Storage (latency cut from 300ms to 100ms) |
| **Security** | Zod, DOMPurify, CSP, Helmet, Rate Limiting, HMAC-SHA256 | Shopee E-commerce, CI/CD Server |
| **DevOps** | GitHub Webhooks, Bash, PM2, SSH | CI/CD Server (deploy time cut from 15 minutes to under 60 seconds) |
| **Payments** | Razorpay | Cloud Storage |
| **Advanced TypeScript** | Conditional, mapped, recursive and template literal types | [Type Challenges](https://github.com/ssrawat1/type-challenges) (all Easy, 101 Medium solved) |

<br>

# 💻 Tech Stack

**Frontend**<br>
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![Redux](https://img.shields.io/badge/Redux-593d88?style=for-the-badge&logo=redux&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Backend & Database**<br>
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-404d59?style=for-the-badge&logo=express&logoColor=61DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

**Cloud & DevOps**<br>
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

<br>

# 🚀 Featured Projects

## ☁️ Cloud Storage Application

A cloud storage platform for secure file uploads and downloads, with premium storage plans.

🚧 **Status:** The live demo is offline because my AWS free tier ended. I am building an improved version (v2), and the full code is available below.

**Highlights**
- ⚡ Cut file delivery latency from **300ms to 100ms** (66% faster) using the CloudFront CDN
- 🧠 Benchmarked Redis against MongoDB: Redis gave **7x to 10x faster reads**, which shaped the caching strategy
- 🚀 Redis-backed session handling improved API responsiveness by **50%**
- 🔐 Role-based access control with Google and GitHub OAuth
- 💳 Razorpay billing for premium storage tiers

**Skills used in this project**

| Skill | How I used it |
|-------|---------------|
| **React** | Frontend for file uploads, retrievals and storage metrics |
| **Node.js + Express** | Modular REST APIs, including real-time storage metrics for active users |
| **MongoDB** | Database behind the APIs, benchmarked against Redis for read speed |
| **Redis** | Session handling and caching for high-frequency API calls |
| **AWS S3** | Secure file uploads and retrievals |
| **AWS CloudFront** | CDN delivery, latency from 300ms to 100ms |
| **OAuth + RBAC** | Google/GitHub login and role-based access control |
| **Razorpay** | Billing flows for premium storage tiers |

[🌐 Live Demo (currently offline)](https://safemystuff.store/) · [🔗 Frontend Code](https://github.com/ssrawat1/StorageApp-Frontend) · [🔗 Backend Code](https://github.com/ssrawat1/StorageApp-Backend)

---

## ⚙️ Custom CI/CD Server

A self-hosted deployment server that removes manual SSH deployments.

**Highlights**
- 🚀 Reduced deploy time from about **15 minutes to under 60 seconds** (93% faster)
- 🔒 Verifies every webhook with **HMAC-SHA256** to block spoofed pushes
- 🧭 Picks the right deploy script automatically for each repository, so one server handles many projects
- 📧 Sends color-coded HTML email reports of success or failure to the developer who pushed the commit

**Skills used in this project**

| Skill | How I used it |
|-------|---------------|
| **Node.js + Express** | Webhook server that receives and processes GitHub push events |
| **GitHub Webhooks** | Automatic deployment trigger on every push |
| **HMAC-SHA256** | Signature check on every incoming payload to block unauthorized requests |
| **Bash** | Deploy scripts (`deploy-frontend.sh`, `deploy-backend.sh`) chosen by repository |
| **SSH + PM2** | Server-side deployment and process management |
| **Email alerts** | HTML reports with filtered logs, branch, commit message and timestamp |

[🔗 Code](https://github.com/ssrawat1/Custom-CI-CD-Pipelines-Using-Node.js-GitHub-Webhook)

---

## 🛒 Shopee E-commerce Application

A full-stack shopping app with a focus on user experience and security.

**Highlights**
- 🛍️ Guest cart that merges automatically with the user's cart after login
- 🔎 Product search with live suggestions and keyword highlighting
- 🛡️ Secure APIs protected against common web vulnerabilities
- 📄 Client-side pagination and reusable UI components

**Skills used in this project**

| Skill | How I used it |
|-------|---------------|
| **Next.js** | Product listings, search, pagination and cart experience |
| **Tailwind CSS** | Responsive, modular UI components |
| **Node.js + Express** | Secure REST APIs |
| **MongoDB** | Data storage for the shopping app |
| **Rate limiting + throttling** | Protection against abuse and request floods |
| **Zod + DOMPurify** | Input validation and sanitization |
| **CSP + Helmet** | Secure HTTP headers and content policy |

[🌐 Live Demo](https://shopee.safemystuff.store/) · [🔗 Frontend Code](https://github.com/ssrawat1/shopping_app_frontend) · [🔗 Backend Code](https://github.com/ssrawat1/shopping_app_backend)

<br>

## 🧩 TypeScript Type-Level Programming

I went deep into TypeScript's type system by solving **all 101 Medium** and **100% of Easy** challenges from the well-known [type-challenges](https://github.com/type-challenges/type-challenges) repository. I wrote algorithms using nothing but recursive, conditional, and template literal types, typeof and keyof operators, mapped types, indexed access types.

[![Easy](https://img.shields.io/badge/Easy-100%25-brightgreen?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/ssrawat1/type-challenges/tree/main/easy)
[![Medium](https://img.shields.io/badge/Medium-101%20Solved-blue?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/ssrawat1/type-challenges/tree/main/medium)

📂 **[View all solutions →](https://github.com/ssrawat1/type-challenges)**

<br>

## 🧩 LeetCode Stats

[![LeetCode Stats](https://leetcard.jacoblin.cool/ssrawata1?theme=dark)](https://leetcode.com/ssrawata1/)

## 🔝 Top Contributed Repo

![](https://github-contributor-stats.vercel.app/api?username=ssrawat1&limit=5&theme=dark&combine_all_yearly_contributions=true)

<br>

# 🌐 Socials & Portfolio

[![Portfolio](https://img.shields.io/badge/Portfolio-%2300C7B7.svg?style=for-the-badge&logo=netlify&logoColor=white)](https://sanjaydevportfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanjay-singh-rawat-a39b11302)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ssr911999@gmail.com)

[![](https://visitcount.itsvg.in/api?id=ssrawat1&icon=0&color=0)](https://visitcount.itsvg.in)
