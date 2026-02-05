# LokSaarthi AI

An AI-powered community assistance platform that serves as a bridge between citizens and public systems in India.

## Overview

LokSaarthi AI improves access to information, public services, welfare schemes, education, healthcare, and employment opportunities through a single, easy-to-use interface that supports multiple languages and interaction modes.

## Key Features

- **Multi-language AI Assistant**: Conversational AI supporting 10+ regional Indian languages
- **Personalized Recommendations**: Smart matching of citizens to eligible government schemes
- **Application Assistance**: Step-by-step guidance for government scheme applications
- **Resource Mapping**: Location-based discovery of public services and facilities
- **Multi-platform Access**: Mobile app, web portal, WhatsApp, IVR, and SMS support
- **Offline Capability**: Works with poor connectivity and offline modes
- **Analytics Dashboard**: Insights for government officials and NGOs

## Architecture

The platform uses a microservices architecture with:
- **Backend**: Node.js/TypeScript for API services, Python/FastAPI for AI services
- **Database**: PostgreSQL with Redis caching
- **AI/ML**: OpenAI GPT-4/Claude with Indic NLP libraries
- **Frontend**: React Native (mobile), React.js (web)
- **Infrastructure**: Docker, Kubernetes, AWS/GCP

## Getting Started

### Prerequisites

- Node.js 18+
- Python 3.9+
- PostgreSQL 14+
- Redis 6+
- Docker & Docker Compose

### Development Setup

1. Clone the repository:
```bash
git clone https://github.com/vivekpunde05/Loksaarthi_AI.git
cd Loksaarthi_AI
```

2. Follow the implementation tasks in `.kiro/specs/loksaarthi-ai/tasks.md`

## Project Structure

```
├── .kiro/specs/loksaarthi-ai/    # Project specifications
│   ├── requirements.md           # Detailed requirements
│   ├── design.md                # Technical design document
│   └── tasks.md                 # Implementation task list
├── services/                    # Microservices (to be created)
│   ├── api-gateway/
│   ├── ai-assistant/
│   ├── recommendation-engine/
│   └── ...
├── mobile/                      # React Native mobile app
├── web/                        # React.js web portal
└── infrastructure/             # Docker, K8s configs
```

## Implementation Plan

The project follows a structured implementation approach:

1. **Infrastructure Setup** - Core foundations and database
2. **AI Services** - Conversational AI and language processing
3. **Core Services** - Recommendations, applications, resources
4. **Platform Interfaces** - Mobile, web, WhatsApp, IVR
5. **Integration & Testing** - End-to-end workflows

See `.kiro/specs/loksaarthi-ai/tasks.md` for detailed task breakdown.

## Contributing

1. Review the requirements and design documents in `.kiro/specs/loksaarthi-ai/`
2. Pick a task from `tasks.md`
3. Create a feature branch
4. Implement with comprehensive tests (unit + property-based)
5. Submit a pull request

## Testing Strategy

The project uses dual testing approach:
- **Unit Tests**: Specific examples and edge cases
- **Property-Based Tests**: Universal correctness properties using fast-check

## License

[Add your license here]

## Contact

[Add contact information]