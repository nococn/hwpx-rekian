# hwpx-rekian

`ai-public-peasant/hwpx-rekian`의 `hwpx/` 스킬을 독립 저장소로 분리했습니다.

- 원본: https://github.com/ai-public-peasant/hwpx-rekian
- 원본 커밋: `e151c968390e4dfc28f604934e3dfa72bf398951`
- 스킬 파일을 루트로 옮겼습니다. GitHub 웹 편집 과정에서 일부 텍스트 파일의 끝 줄바꿈만 정규화됐으며, 그 외 본문과 바이너리 파일은 원본과 같습니다. `SKILL.md`, 스크립트, 참고문서, 예시와 템플릿을 보존했습니다.
- 원본 크레딧과 설치 설명: [UPSTREAM_README.md](UPSTREAM_README.md)
- 핵심 XML 스크립트는 Python 및 lxml이 필요합니다. `from hwpx import HwpxDocument`를 쓰는 Python API 예제는 별도로 python-hwpx 패키지가 필요합니다. 자세한 환경과 사용법은 SKILL.md를 확인하세요.

## 라이선스 주의

이 커밋의 원본 저장소에는 LICENSE 파일이 없습니다. 원본 README는 하위 디렉터리의 라이선스를 확인하라고 안내하지만, 해당 스킬 디렉터리에도 라이선스 파일이 없습니다. 이 저장소는 새로운 라이선스를 부여하지 않습니다. 원본 저작자와 기여자 표기는 UPSTREAM_README.md에 보존했습니다.

## 확인 범위

분리 후 루트 SKILL.md와 파일 구성을 확인했고, 기본·공문·보고서·회의록 HWPX 생성 및 구조 검증을 통과했습니다. 실제 가져오기 화면과 한컴오피스에서의 문서 렌더링은 검증하지 않았습니다.
