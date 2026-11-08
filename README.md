# 교사 AI 실습실

클로드와 코덱스로 교실 업무를 처음부터 끝까지 맡기는 교사 연수용 정적 안내서입니다.

- 첫 화면: [index.html](index.html)
- [클로드 안내서](claude.html): Claude Code 데스크톱, 로컬 폴더 작업 기준
- [코덱스 안내서](codex.html): Codex 데스크톱, 로컬 폴더 작업 기준
- [가상 예시 자료](sample-materials.zip): 압축을 풀어 주제별 파일 사용
- [강사용 운영 메모](INSTRUCTOR.md)

## 강의 전체 순서

교사에게는 공개된 첫 화면 주소 하나를 안내합니다. 각 페이지 상단의 강의 순서와 하단의 이전·다음 링크로 이동합니다.

1. [코덱스와 클로드 설치하기](install.html) · [편집용 글](install.md)
2. [Aside 연결 맞추기](aside.html) · [편집용 글](aside.md)
3. [강의 시작 실습](basic.html): 설명해서 웹앱 만들기, 눌러 보기, 세 번 고치기
4. [기본실습](practice.html): 처음 만든 아홉 가지 교실 업무

코덱스와 클로드 코드 중 하나로 진행할 수 있습니다. 기존 basic.html, basic-claude.html, basic-codex.html, claude.html, codex.html 주소도 유지됩니다.

## 강의 시작 · 기본실습 1

[기본실습 첫 화면](basic.html)에서 시작합니다. 원본과 같은 19개 항목을 교사용으로 새로 썼습니다.

- [클로드 코드 기본실습](basic-claude.html) · [글 파일](basic-claude.md)
- [코덱스 기본실습](basic-codex.html) · [글 파일](basic-codex.md)
- [기본실습 가상 자료 6개](basic-samples.zip)

권장 흐름: 설명해 만들기 → 눌러 보기 → 세 번 고치기 → 짝 피드백 → 선택 공유.

## 주요 기능

9개 주제별 독립적인 전체 요청문 복사, 준비 자료 안내, 5단계 진행, 결과 점검, 인쇄 기능을 제공합니다.
모든 페이지는 별도 설치 없이 열리는 HTML 파일입니다. 외부 글꼴, 분석 코드, 학생 자료 업로드, 서버 저장 기능은 없습니다.
복사 기능을 사용할 수 없는 환경에는 수동 복사용 상자를 제공합니다.

## GitHub Pages 게시

공개 승인을 받은 뒤 이 폴더의 파일을 저장소 기본 브랜치의 최상위에 올립니다.
저장소 Settings → Pages → Build and deployment → Source에서 Deploy from a branch를 선택합니다.
Branch에서 기본 브랜치와 /(root)를 선택하고 Save합니다.
실제 화면에서 설정이 완료되고 공개 주소로 세 페이지가 열리는 것을 확인한 뒤 교사에게 링크를 배포합니다.
일반적인 주소 형식은 https://계정이름.github.io/저장소이름/ 이지만 설정과 게시가 끝나기 전에는 실제 링크로 안내하지 않습니다.
공개 저장소와 기본 Pages 게시를 사용하는 구성입니다. 별도 도메인과 유료 서비스는 필요하지 않습니다.

## 참고

[원본 실습 안내서](https://aiautomationstudy.github.io/study_exercises/3%EA%B8%B0/%EC%8B%A4%EC%8A%B5/3%EA%B8%B0_7%EC%A3%BC%EC%B0%A8_%EC%8B%A4%EC%8A%B5_%EC%82%AC%EB%9E%8C%EC%9D%B4%EB%A9%B4_3%EC%A3%BC_%EA%B1%B8%EB%A6%B4_%EC%9D%BC_%ED%86%B5%EC%A7%B8%EB%A1%9C_%EB%A7%A1%EA%B8%B0%EA%B8%B0.html)의 진행 구조를 참고했습니다. 본문의 문장과 교사용 요청문은 이 연수에 맞게 새로 작성했습니다.
주제 A~I는 강사가 제공한 이미지의 목록을 따릅니다. 원본과의 제휴나 공식 승인을 뜻하지 않습니다.

확인일: 2026-11-09. 앱의 화면과 권한, 모델, 요금제는 달라질 수 있으므로 강의 직전에 실제 계정으로 다시 확인하세요.
