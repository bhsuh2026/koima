# KOIMA 수입업체 정보시스템 — GitHub Pages 배포 패키지

## 구성 파일
- index.html        메인 허브 페이지 (첫 화면)
- asean.html        아세안 통합 허브
- search.html       통합 검색 시스템
- admin.html        관리자 콘솔
- vietnam.html ~ kazakhstan.html   국가별 디렉토리 11개

## 배포 방법 (GitHub Pages)
1. GitHub에서 새 저장소 생성
2. "Add file > Upload files" 로 이 폴더의 모든 .html 파일 업로드
3. Settings > Pages > Branch 를 main 으로 설정, 저장
4. 몇 분 후 https://(아이디).github.io/(저장소명)/ 으로 접속

index.html 이 있으므로 위 주소로 접속하면 메인 허브가 자동으로 표시됩니다.

## 데이터 갱신
관리자 콘솔(admin.html)에서 업체 정보를 수정한 뒤
data.json 을 내보내고, 빌드 스크립트로 디렉토리를 다시 생성하여
이 폴더의 파일들을 교체 후 재업로드하면 됩니다.

문의: seobh@koima.or.kr
