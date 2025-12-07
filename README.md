# goopick-vault

Obsidian Vault 동기화 저장소

## 용도

- Obsidian 노트 자동 백업
- Obsidian Git 플러그인으로 자동 동기화

## 설정

### Obsidian Git 플러그인 설치
1. Obsidian → Settings → Community Plugins
2. "Obsidian Git" 검색 및 설치
3. 설정:
   - Auto pull interval: 5분
   - Auto push interval: 5분
   - Commit message: `vault backup: {{date}}`

## 구조

```
goopick-vault/
├── 00-Inbox/
├── 01-Projects/
├── 02-Areas/
├── 03-Resources/
└── 04-Archives/
```
