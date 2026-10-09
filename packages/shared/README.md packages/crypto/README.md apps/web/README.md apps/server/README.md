# Telyragram

Приватный мессенджер. E2E-шифрование, realtime, минимализм.

## Стек
- Frontend: React + TypeScript + Vite + Tailwind
- Backend: Node.js + Express + Socket.IO
- DB: PostgreSQL + Prisma
- Realtime: Redis pub/sub
- Crypto: libsodium

## Запуск через GitHub Codespaces
1. Code → Codespaces → Create
2. В терминале Codespaces:
   ```bash
   pnpm install
   docker compose up -d
   pnpm dev
