# 말해봄 쇼케이스

말해봄 AI 면접 코칭 서비스의 홍보 및 프로젝트 소개를 위한 GitHub Pages 정적 사이트입니다.

- 서비스 소개: `/`
- 프로젝트 소개: `/project/`
- 실제 서비스: https://malhaebom.xyz
- 원본 프로젝트: https://github.com/aihuman-7th/proj2-3

## 로컬 미리보기

저장소 루트에서 실행:

~~~bash
python3 -m http.server 8081
~~~

- http://localhost:8081/
- http://localhost:8081/project/

## GitHub Pages 게시

GitHub 저장소 Settings > Pages > Build and deployment 에서
Deploy from a branch, main, / (root) 를 설정하고 저장하세요.

게시 후 예상 주소: https://nanocode00.github.io/malhaebom-showcase/

## 검증

~~~bash
python3 scripts/check_site.py
~~~

## 리소스

기존 말해봄 프로젝트의 로고, 파비콘, 마스코트, 배경,
데모 화면 4장을 최적화해 포함했습니다.

기획 목업과 실제 프론트엔드의 데모 화면은 구분됩니다.
데모 화면이 현재 운영 중인 화면과 동일하다는 보장은 없습니다.
운영 정책과 모델 성능은 docs/CONTENT_REVIEW.md에서 공개 전 확인해야 합니다.

서비스 연결 주소는 assets/site-config.js에서 변경할 수 있습니다.
정적 사이트에 비밀키를 넣지 마세요.
