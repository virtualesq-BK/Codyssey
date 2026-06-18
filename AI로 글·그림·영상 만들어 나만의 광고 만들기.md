# AI로 글·그림·영상 만들어 나만의 광고 만들기

## 스토리보드(기획) 문서 

### 브랜드 아이덴티티
- **브랜드명**: LEX-IN
- **브랜드 소개**: LEX-IN은 해외 계약서의 위험 조항을 AI가 자동으로 분석하고 위험도, 수정안, 법률 근거를 제공하는 AI 기반 글로벌 비즈니스 리스크 관리 플랫폼
- **타겟 고객**: 해외 진출 중소기업 대표, 스타트업 CEO, 해외영업 담당자, 수출입 기업 실무자, 글로벌 프로젝트 관리자 등
- **톤앤매너**: 전문가, 신뢰, 글로벌
- **USP**: "해외 계약의 위험을 AI가 체결 전에 발견합니다." 
- **캠페인 목표**: 브랜드 인지도 확보 
- **캠페인 핵심 메시지**: "해외 계약의 위험, 이제 AI가 먼저 찾아드립니다." 

---

## 사용 도구 목록

| 구분 | 도구 | 사용 목적 |
|------|------|----------|
| 이미지 생성 | gpt-image-2 | 광고 비주얼 생성 |
| 영상 생성 | sora-2 | 4초 광고 영상 생성 |
| 음성 생성 | tts-1 | 브랜드 내레이션 생성 |
| 편집 | CapCut 또는 Premiere | 영상 연결 및 자막 삽입 |

---

## 씬 구성 및 스토리보드

### SCENE 1
**씬 길이**: 4초

**목표 메시지**: 해외 계약에는 눈에 보이지 않는 위험이 존재한다.

**화면 구성**: 
- **구도**: 클로즈업
- **피사체**: 해외 공급계약서에 서명하려는 한국 기업 대표
- **배경**: 글로벌 비즈니스 회의실
- **연출**: 계약서 위에 붉은 경고 아이콘 등장, 특정 조항이 붉게 강조됨
- **텍스트**: "이 계약, 정말 안전할까요?"
- **내레이션**: "해외 계약에는 보이지 않는 위험이 숨어 있습니다."

**사용 도구**: 
- gpt-image-2 → 원본 비주얼 생성
- sora-2 → 카메라 이동 및 경고 효과 생성
- tts-1 → 내레이션 생성

**입력 프롬프트 [gpt-image-2]**:
```
A Korean business executive about to sign a multimillion-dollar international contract, 
modern global boardroom, subtle red warning indicators appearing on contract clauses, 
cinematic lighting, realistic legal business environment, premium commercial style
```

**출력 결과 요약**: 계약 체결 직전 위험 신호가 나타나는 장면 생성

**생성 파일명**: LEXIN_S01_Image.png, LEXIN_S01_Video.mp4

---

### SCENE 2
**씬 길이**: 4초

**목표 메시지**: LEX-IN이 위험을 찾아 안전한 계약을 돕는다. 

**화면 구성**: 
- **구도**: AI 분석 화면에서 시작, 카메라 줌아웃
- **피사체**: AI 분석 결과, 위험도 점수, 수정 권고안
- **배경**: 세계 지도, 글로벌 네트워크
- **연출**: 엔딩, LEX-IN 로고 등장, 슬로건 등장("계약의 위험을, 체결 전에."), CTA ("Upload. Analyze. Sign.")
- **내레이션**: "LEX-IN. 해외 계약의 위험을 체결 전에 찾아드립니다." 

**사용 도구**: 
- gpt-image-2 → SaaS UI 생성
- sora-2 → AI 분석 및 글로벌 네트워크 애니메이션
- tts-1 → 내레이션 생성

**입력 프롬프트 [gpt-image-2]**:
```
Futuristic AI legal risk analysis dashboard, international contract document, 
risk score visualization, professional legal technology SaaS interface, 
world map connections, corporate blue and white theme, premium startup commercial
```

**출력 결과 요약**: AI가 계약서를 분석하고 글로벌 플랫폼으로 연결되는 장면 생성

**생성 파일명**: LEXIN_S02_Image.png, LEXIN_S02_Video.mp4

---

## 프롬프트 수정 전/후 사례 (SCENE 2)

### 수정 전
```
AI legal dashboard
```

**문제점**: 
- 법률 SaaS 느낌 부족
- 계약 분석 서비스인지 불명확
- 브랜드 차별성이 드러나지 않음

### 수정 후
```
Futuristic AI legal risk analysis dashboard, international contract document, 
risk score visualization, professional legal technology SaaS interface, 
world map connections, corporate blue and white theme, premium startup commercial
```

**수정 이유**: 
- 위험도 점수 표현 추가
- 국제계약 맥락 강화
- 글로벌 플랫폼 이미지 강화
- SaaS 서비스 정체성 명확화 

**개선 결과**: 광고 시청자가 1초 이내에 "AI 계약 분석 서비스"라는 점을 이해할 수 있게 됨

---

## 최종 영상 구성

```
0~4초
문제 제시
"이 계약, 정말 안전할까요?"
       ↓
위험 조항 강조
       ↓
불안감 형성
—--------------------------------
4~8초
LEX-IN 등장
       ↓
AI 위험 분석
       ↓
글로벌 네트워크 시각화
       ↓
브랜드 로고
       ↓
"계약의 위험을, 체결 전에."
```

---

## 최종 산출물

| 항목 | 내용 |
|------|------|
| 스토리보드 | AI로 글·그림·영상 만들어 나만의 광고 만들기.pdf |
| 광고 영상 | LEXIN_BrandFilm_v1.mp4 |
| 영상 길이 | 8초 |
| 해상도 | 1920 × 1080 |
| 프레임 | 24fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |
| AI 생성 비율 | 100% (gpt-image-2 + sora-2 + tts-1 활용) |
