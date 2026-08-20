# 박형주 포트폴리오

**사이트**: https://invastor.pro

클라우드/인프라 부트캠프(양주시 청년센터) 과정 중 진행한 프로젝트와 자격증 취득 현황을 정리한 개인 포트폴리오입니다.

---

## 담긴 내용

- **소개 / 강점**: 13년 임상 운영 경력을 바탕으로 한 교육 운영·조직 관리 역량
- **프로젝트**:
  - PI:VE — 소규모 팀 협업 플랫폼 (FastAPI 백엔드 개발)
  - 수업 링크 단축 서비스 — YOURLS 기반 Docker 배포, v1/v2 개선 과정
  - 인프라 제약을 우회한 자료 공유 서비스 — 네트워크 제약을 아키텍처 전환으로 해결한 트러블슈팅 사례
  - 3-Tier 보안 실습 랩
  - 배운 것을 남기는 습관 (learning-log 저장소 연동)
- **자격증**: NCP, 프로그래밍기능사, 리눅스마스터 2급, 네트워크관리사 2급 등

## 기술 스택

순수 HTML/CSS/JS로 작성된 정적 사이트. 별도 빌드 과정 없이 GitHub Pages로 바로 배포됩니다.

## 배포 구조

```
invastor.pro (가비아 DNS, A 레코드 → GitHub Pages)
    → 이 저장소의 index.html
```

## 로컬에서 확인하기

```bash
git clone https://github.com/pop2875/my_portfolio_26.git
cd my_portfolio_26
python3 -m http.server 8000
```
브라우저에서 `http://localhost:8000` 접속.

## 수정 후 배포

```bash
git add .
git commit -m "수정 내용"
git pull --rebase
git push
```
push 후 1~2분 뒤 https://invastor.pro 에 반영됩니다.
