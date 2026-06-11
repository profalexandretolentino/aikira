# Aikira Project 🚀

**[EN]** A scalable educational platform built with modern engineering practices, focusing on AI and international career development.  
**[PT]** Uma plataforma educacional escalável construída com práticas modernas de engenharia, focada em IA e desenvolvimento de carreira internacional.  
**[JA]** 次世代(じせだい)教育(きょういく)学習(がくしゅう)基盤(きばん)「Aikira」— AIと次世代(じせだい)技術(ぎじゅつ)を融合(ゆうごう)させた国際的(こくさいてき)教育(きょういく)プラットフォーム。

---

## 🛠 Tech Stack
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-05998b?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007acc?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=for-the-badge&logo=docker&logoColor=white)

---

## 🏗 Architecture Overview
```mermaid
graph TD
    A[Client - Next.js] -->|HTTPS/REST| B[FastAPI Backend]
    B -->|Query| C[(PostgreSQL)]
    B -->|OpenAI| D[AI Services]
    subgraph "Monorepo (Turborepo)"
    A
    B
    end

🎯 Strategic Goals
Focus	Description
AI & Tech	Modern SaaS platform for technical education.
International	Positioning for Japan 🇯🇵 and USA 🇺🇸 markets.
Scalability	Evolving from MVP to enterprise-grade infrastructure.
🛠️ Tech Stack

    Frontend: Next.js + TypeScript

    Backend: FastAPI (Python)

    Database: PostgreSQL (Neon/Supabase)

    Infra: Docker, GitHub Actions, Vercel/Railway

📝 Roadmap (Tri-Lingual)
EN: Execution Strategy

    Phase 1 (Current): MVP focus, public construction, technical authority.

    Phase 2 (Future): AWS migration, enterprise branding, and global scale.

PT: Estratégia de Execução

    Fase 1 (Atual): Foco no MVP, construção em público, autoridade técnica.

    Fase 2 (Futuro): Migração para AWS, branding corporativo e escala global.

JA: 実行戦略 (実行じっこう戦略せんりゃく)

    第1フェーズ: MVP構築こうちく、公開こうかい開発かいはつ、技術的ぎじゅつてき権威けんいの確立かくりつ。

    第2フェーズ: AWSへの移行いこう、グローバルな事業じぎょう展開てんかい。

⚖️ Policy & Security

    License: MIT

    Security: Sensitive data (.env, secrets) are never committed. Use .env.example as a template.

    Visibility: Public repository for portfolio building and community growth.

🚀 Vision

Building an international technical asset that serves as a bridge for global engineering opportunities, focusing on sustainability, productivity, and modern architecture.
🎯 Strategic Goals
Focus	Description
AI & Tech	Modern SaaS platform for technical education.
International	Positioning for Japan 🇯🇵 and USA 🇺🇸 markets.
Scalability	Evolving from MVP to enterprise-grade infrastructure.
🛠️ Tech Stack

    Frontend: Next.js + TypeScript

    Backend: FastAPI (Python)

    Database: PostgreSQL (Neon/Supabase)

    Infra: Docker, GitHub Actions, Vercel/Railway

📝 Roadmap (Tri-Lingual)
EN: Execution Strategy

    Phase 1 (Current): MVP focus, public construction, technical authority.

    Phase 2 (Future): AWS migration, enterprise branding, and global scale.

PT: Estratégia de Execução

    Fase 1 (Atual): Foco no MVP, construção em público, autoridade técnica.

    Fase 2 (Futuro): Migração para AWS, branding corporativo e escala global.

JA: 実行戦略 (実行じっこう戦略せんりゃく)

    第1フェーズ: MVP構築こうちく、公開こうかい開発かいはつ、技術的ぎじゅつてき権威けんいの確立かくりつ。

    第2フェーズ: AWSへの移行いこう、グローバルな事業じぎょう展開てんかい。

⚖️ Policy & Security

    License: MIT

    Security: Sensitive data (.env, secrets) are never committed. Use .env.example as a template.

    Visibility: Public repository for portfolio building and community growth.

🚀 Vision

Building an international technical asset that serves as a bridge for global engineering opportunities, focusing on sustainability, productivity, and modern architecture.
