# LokSaarthi AI 🇮🇳

AI-powered community assistance platform bridging the digital divide between citizens and public services in India.

## 🌟 Overview

LokSaarthi AI provides multi-language, multi-modal access to government schemes, welfare programs, healthcare services, and employment opportunities through a unified interface.

## ✨ Key Features

- **🤖 AI Assistant**: 10+ regional languages, voice & text interaction across mobile, web, WhatsApp, IVR, SMS
- **🎯 Smart Recommendations**: AI-powered eligibility matching for schemes, jobs, scholarships, healthcare
- **📋 Application Assistance**: Step-by-step guidance, auto-fill forms, document management, real-time tracking
- **🗺️ Resource Mapping**: Location-based discovery of hospitals, government offices, NGOs, legal aid
- **📊 Analytics Dashboard**: Real-time insights for government officials with privacy-compliant reporting

## 🏗️ Tech Stack

**Backend**: Node.js/TypeScript, Python/FastAPI, PostgreSQL, Redis, Kafka, Elasticsearch  
**AI/ML**: OpenAI GPT-4, AI4Bharat IndicNLP, Google Cloud Speech APIs  
**Frontend**: React Native, React.js, WhatsApp Business API, Twilio Voice  
**Infrastructure**: AWS/GCP, Docker, Kubernetes

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/vivekpunde05/Loksaarthi_AI.git
cd Loksaarthi_AI

# Install dependencies
npm install
cd ai-services && pip install -r requirements.txt && cd ..

# Setup database
docker-compose up -d postgres redis
npm run db:migrate

# Configure environment
cp .env.example .env

# Start services
docker-compose up -d
npm run dev:api
npm run dev:ai
npm run dev:web
```

## 📋 Implementation Plan

**Phase 1**: Foundation - Core data models, AI services, recommendation engine  
**Phase 2**: Core Services - Application assistant, resource mapping, analytics, security  
**Phase 3**: User Interfaces - Mobile apps, web portal, WhatsApp, IVR integration

## 📚 Documentation

- [Requirements](.kiro/specs/loksaarthi-ai/requirements.md) - User stories and acceptance criteria
- [Design](.kiro/specs/loksaarthi-ai/design.md) - Architecture and correctness properties  
- [Tasks](.kiro/specs/loksaarthi-ai/tasks.md) - Implementation roadmap

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/name`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push branch (`git push origin feature/name`)
5. Open Pull Request

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

---

**Made with ❤️ for the people of India**