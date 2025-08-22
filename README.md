# back-end
Core API for Zyto.

## Services
- `/plan` POST — create plan from NL prompt
- `/runs` CRUD — list/read runs
- `/events` WS — stream run events

## Dev
```bash
npm ci
cp .env.example .env
npm run dev
