# 상황판 그림·입체 파일

학급 주식 상황판(Apps Script)이 jsDelivr로 받아 쓰는 모양·그림 파일. 학생 자료는 없다.

| 파일 | 무엇 |
|---|---|
| r3d.json | 입체 마네킹(GLB)과 움직임 |
| r3f.json | 평면 「내 방」 판 조립식 윤곽·축 자료 |
| o/<꾸밈 id>.txt | 입체 옷·머리 부품 하나씩(GLB를 gzip+base64로) |
| acc/ | 입체 꾸밈 부품 GLB와 acc.json(나중에 더함) |
| bgm/ | 로블록스반 월드 배경 음악 mp3(OpenGameArt CC0, 출처 = CREDITS.md) |

주소는 브랜치 이름 말고 커밋 해시로 고정해서 쓴다: `https://cdn.jsdelivr.net/gh/<계정>/sbassets@<커밋해시>/r3d.json`
