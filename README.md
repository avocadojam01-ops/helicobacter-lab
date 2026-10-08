# 위 속의 작은 세계

한국어 헬리코박터 인터랙티브 웹 교과서입니다. 8개 실험, 위·세균 도해, 검사 비교, 복약 달력, 제균 확인 날짜 계산기, 해설 퀴즈를 제공합니다.

## GitHub Pages

Settings → Pages → Build and deployment에서 Source를 **Deploy from a branch**, Branch를 **main**, 폴더를 **/(root)**로 선택하고 **Save**를 누르세요.

배포 주소: https://avocadojam01-ops.github.io/helicobacter-lab/

별도의 빌드 없이 index.html을 그대로 제공합니다. 외부 자산에 의존하지 않으며, 입력 내용은 서버에 전송하거나 저장하지 않습니다.

## 의학적 근거

- 한국 헬리코박터 진단·치료 지침, 2025 개정판
- ACG H. pylori 치료 지침, 2024
- 미국 국립암연구소 H. pylori 자료

교육용 콘텐츠이며 개인의 제균 성공률이나 암 위험을 예측하지 않습니다. 개별 치료는 담당 의사와 상의하세요.

Books (https://books.euiyun.com/)의 인터랙티브 교과서 표현 방식에서 영감을 받았으며, 도해·코드·문장은 새로 제작했습니다.

## 검증

JavaScript 구문 및 DOM 모형 기반 기능 검사(날짜 조건, 내성, 복약 표시, 위험 산술, 퀴즈 채점)를 통과했습니다. 브라우저 렌더링 검증은 완료하지 못했습니다.
