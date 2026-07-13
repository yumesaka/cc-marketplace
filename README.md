# cc-marketplace

Claude Code 플러그인 마켓플레이스.

## 등록된 플러그인

| 플러그인 | 설명 | 버전 |
|----------|------|------|
| [code-reviewer](https://github.com/yumesaka/cc-plugins-sample) | 코드 리뷰어 에이전트 | 1.0.0 |
| vault-skills | Obsidian vault 전용 스킬 묶음 | 1.5.0 |
| github-topic-manager | GitHub repository topic rules manager | 1.0.0 |
| notion-habit | Notion habit tracker Daily Log 및 운동 기록 스킬 | 1.1.0 |

## 설치 방법

1. Claude Code `settings.json`에 마켓플레이스 등록:

```json
{
  "extraKnownMarketplaces": {
    "cc-marketplace": {
      "source": {
        "source": "github",
        "repo": "yumesaka/cc-marketplace"
      }
    }
  }
}
```

2. Claude Code에서 `/plugin` 명령으로 원하는 플러그인 설치
3. `/reload-plugins`으로 활성화
