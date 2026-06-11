# B1-2 AI 기반 브랜드 광고 영상 제작 과제

## QUANTA — AI Investment Intelligence Platform

> **슬로건:** Beyond Data, Into Decisions.

---

## 1. 최종 결과물

| 산출물 | 내용 |
|---|---|
| 스토리보드 문서 | README.md (본 문서) |
| 광고 영상 파일 | [Quanta.mp4 - YouTube](https://youtu.be/Gu3XoUOpUKA) / 50.7초 / 1920x1080 / H.264 / AAC |
| 씬별 클립 | [GitHub - Videos/Clip](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |
| 씬별 이미지 | [GitHub - Images](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) |
| 오디오 | [GitHub - Audio](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Audio) |

---

## 2. 브랜드/캠페인 정의

### 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | QUANTA |
| 서비스 | AI Investment Intelligence Platform |
| 슬로건 | Beyond Data, Into Decisions. |
| 타겟 | 20~40대 개인 투자자 |
| 광고 목적 | 인지 (Awareness) |
| 핵심 메시지 | 복잡한 금융 데이터 속에서 AI가 핵심 투자 인사이트만 골라준다 |

### 브랜드 선정 배경

주식 투자에 관심을 갖게 되면서 실제로 시장 데이터를 직접 찾아보기 시작했는데, 뉴스, 지표, 차트, 공시 등 정보가 너무 방대하고 어디서부터 봐야 할지 감을 잡기 어려웠다. 이 경험에서 출발해 "AI가 이 복잡한 데이터를 대신 정리하고 핵심만 알려준다면 어떨까?"라는 아이디어로 QUANTA를 기획했다.

### 광고 기획 의도

개인 투자자들이 실제로 겪는 가장 큰 어려움은 정보 부족이 아니라 **정보 과잉**이다. 너무 많은 데이터 속에서 무엇이 중요한지 판단하기 어렵고, 그로 인해 결정을 미루거나 잘못된 판단을 내리게 된다. QUANTA는 이 문제를 AI로 해결하는 플랫폼으로, 단순한 데이터 제공이 아닌 **의사결정까지 이어지는 인텔리전스**를 제공한다는 점에서 차별화된다. 광고의 핵심 메시지는 **"혼란에서 명확함으로"** 이며, 씬1의 데이터 과부하 장면으로 공감대를 형성한 뒤 QUANTA AI가 개입하면서 점차 정리되고 인사이트가 도출되는 과정을 시각적으로 보여준다.

### USP

> 방대한 금융 데이터를 AI가 실시간으로 분석하여 핵심 투자 인사이트를 직관적으로 제공

### 타겟 설정 이유

20~40대 개인 투자자를 타겟으로 설정한 이유는 이 연령대가 투자에 가장 적극적으로 참여하면서도 전문적인 분석 도구 접근성이 낮은 계층이기 때문이다. 기관 투자자가 아닌 **개인이 AI 수준의 인사이트를 얻을 수 있다**는 메시지가 가장 강하게 전달될 수 있는 타겟이다.

### 톤앤매너

- Premium Fintech
- Cyberpunk Neon
- Futuristic AI Intelligence
- Dark Navy & Black
- Electric Blue Neon
- Purple Neon Accent
- Holographic Data Visualization
- Sophisticated & Trustworthy

---

## 3. 사용 도구 목록

| 도구 | 분류 | 사용 목적 | 선택 이유 |
|---|---|---|---|
| **Claude (Anthropic)** | 프롬프트 설계 AI | 씬 설계, 이미지/영상 프롬프트 작성, 브랜드 기획 | 구조적인 씬 설계와 일관된 프롬프트 체계 수립에 최적화 |
| **ChatGPT / DALL-E (OpenAI)** | 이미지 생성 AI | 씬별 레퍼런스 이미지 제작 | 텍스트 프롬프트 기반 고품질 광고 컨셉 이미지 생성 가능 |
| **Google Flow (Veo)** | 영상 생성 AI | 이미지 기반 씬 클립 영상 생성 및 클립 간 전환 연결 | Veo 엔진 기반 고화질 영상 생성, 캐릭터 일관성 유지 기능 제공 |
| **Suno** | 오디오 생성 AI | 광고 배경음악 제작 | 텍스트 프롬프트로 분위기에 맞는 Instrumental BGM 생성 가능 |
| **CapCut** | 영상 편집 | 씬 클립 연결 및 최종 편집, BGM 삽입 | 직관적 편집 환경, 전환 효과 및 색감 통일 작업 |

### 도구별 워크플로우

```
[Claude]
씬 설계 및 전체 프롬프트 체계 수립
        ↓
[ChatGPT / DALL-E]
씬별 레퍼런스 이미지 생성 (1scene1.png ~ 7scene7.png)
        ↓
[Google Flow / Veo]
이미지 기반 씬 클립 영상 생성
씬 간 전환 클립 생성 (클립1~7 연결 프롬프트 사용)
        ↓
[Suno]
광고 BGM 생성 (Digital Frontier)
        ↓
[CapCut]
씬 클립 순서 편집 + BGM 삽입 + 최종 출력
```

---

## 4. 초기 입력 프롬프트 (Claude → ChatGPT)

씬 설계를 위해 Claude에서 설계한 뒤 ChatGPT에 입력한 전체 프롬프트:

```
과제 요구사항 이미지를 기준으로 QUANTA 광고 프로젝트의 씬만 설계해주세요.
주제: QUANTA (AI Investment Intelligence Platform)

브랜드 정보:
- 브랜드명: QUANTA
- 서비스: AI Investment Intelligence Platform
- 슬로건: Beyond Data, Into Decisions.
- 타겟: 20~40대 개인 투자자

톤앤매너:
- Premium Fintech / Cyberpunk Neon / Futuristic AI Intelligence
- Dark Navy and Black / Electric Blue Neon / Purple Neon Accent
- Holographic Data Visualization / Sophisticated and Trustworthy

USP: 방대한 금융 데이터를 AI가 실시간으로 분석하여 핵심 투자 인사이트를 직관적으로 제공

제작 환경:
- 영상 생성: Veo / 광고 길이: 45~60초
- 동일 인물 유지 / 동일 환경 유지 / 동일 브랜드 컬러 유지

비주얼 스타일:
- Cyberpunk financial district / Neon reflections / Futuristic Seoul skyline
- Holographic stock charts / Floating market data / AI-driven analytics
- Ultra realistic / Photorealistic / HDR / Ray tracing / Global illumination

산출물: Character Bible, Environment Bible, Visual Style Bible,
Global Prompt Rule, Scene 1(수정 전), Scene 1(수정 후), Scene 2~6

주의사항:
- Scene 1 수정 전은 정보 과부하
- Scene 1 수정 후는 QUANTA가 데이터를 정리하기 시작하는 전환 장면
- 내레이션/자막/BGM 제외
- Scene 2부터 매 씬마다 카메라 앵글과 인물의 시선/자세를 반드시 변경할 것
- Scene 2: Close-up / Scene 3: Eye-level medium shot
- Scene 4: Low angle / Scene 5: Wide pull-back / Scene 6: Slow push-in
```

---

## 5. Character Bible

| 항목 | 내용 |
|---|---|
| 성별 | 남성 |
| 나이 | 32~35세 |
| 국적 | 한국인 |
| 외모 | 날카로운 이목구비, 지적이고 침착한 표정 |
| 헤어 | 단정하게 정돈된 검은 머리 |
| 의상 | 프리미엄 다크 네이비 테일러드 수트 + 블랙 터틀넥 |
| 성격 | 분석적, 이성적, 침착한 전문 투자자 |
| 비주얼 | 항상 블루 홀로그램 빛에 조명됨 |

---

## 6. Environment Bible

- **장소:** 미래형 서울 금융지구 펜트하우스 (단일 공간)
- 바닥부터 천장까지 유리벽 / 야간 서울 스카이라인
- 사이버펑크 분위기 / 부유하는 AI 금융 인터페이스
- 홀로그램 주식 차트 / 반사되는 블랙 마블 바닥
- 블루 네온 건축 요소 / 퍼플 앰비언트 하이라이트

---

## 7. Visual Style Bible

| 항목 | 내용 |
|---|---|
| Primary Color | Dark Navy, Deep Black |
| Secondary Color | Electric Blue Neon |
| Accent Color | Purple Neon |
| 렌더링 | Ultra realistic, Photorealistic, HDR, Ray tracing |
| 조명 | Cinematic depth of field, Volumetric lighting |
| 키워드 | Premium Fintech, AI Intelligence, Cyberpunk Corporate |

---

## 8. Global Prompt Rule

모든 씬에 공통 적용:

```
Same Korean male investor,
same futuristic Seoul financial penthouse,
same dark navy suit and black turtleneck,
same neon blue holographic ecosystem,
same nighttime environment, same lighting style,
no text, no subtitles, no logo overlay, no narration,
cinematic realism, ultra realistic, HDR, ray tracing,
consistent character continuity,
consistent environment continuity
```

---

## 9. 스토리보드

### 광고 전체 서사 구조 (기승전결)

```
[기] 씬1(전)  정보 과부하 — 문제 제시
      ↓
[승] 씬1(후)  AI 정리 시작 — 전환점
      ↓
     씬2      데이터 상호작용
      ↓
     씬3      심층 분석
      ↓
[전] 씬4      인사이트 발견 — 클라이맥스
      ↓
     씬5      도시 규모 확장
      ↓
[결] 씬6      명확한 의사결정 — 해결/제안
      ↓
     씬7      QUANTA 브랜드 각인
```

---

### Scene 1 (수정 전) — 정보 과부하

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 1 (수정 전) |
| 예상 길이 | 6~8초 |
| 목표 메시지 | 투자자가 방대한 데이터에 압도되는 상황 표현 |
| 화면 구성 | 인물 중앙, 데이터가 화면 전체를 뒤덮음, 차트가 충돌하며 겹침 |
| 카메라 워크 | Fast orbiting camera around character |
| Mood | Overwhelmed / Chaotic / Data Saturation |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (클립 생성) |
| 생성 파일명 | [1scene1.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test1.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
A Korean male investor standing inside a futuristic
Seoul financial penthouse at night, surrounded by
overwhelming holographic financial data, thousands
of floating stock charts, market indicators, breaking
financial signals, AI dashboards, information overload,
chaotic data streams crossing in every direction,
investor looking stressed and unable to focus,
cyberpunk financial district outside floor-to-ceiling
glass walls, electric blue neon reflections,
premium fintech atmosphere, ultra realistic,
photorealistic, HDR, ray tracing, volumetric lighting,
cinematic realism, high detail, dynamic floating
interfaces, futuristic AI analytics environment
```

**이미지 출력 결과:** 혼란스러운 데이터에 둘러싸여 머리를 짚고 있는 투자자 이미지 생성됨

**[Google Flow] 클립 생성 프롬프트:**

```
Cinematic transition clip starting with Korean male
investor standing overwhelmed by chaotic holographic
financial data exploding everywhere, stressed expression,
fast orbiting camera, red and blue neon chaos.
Gradually transition to same investor in same penthouse,
chaotic data suddenly freezing in midair,
AI neural pathways activating, data reorganizing
into elegant structured panels, investor becoming
calm and focused, electric blue neon intensifying.
Smooth cinematic dissolve transition between states.
No text, no subtitles, no narration,
ultra realistic, HDR, cinematic.
```

**클립 출력 결과:** 1scene1 시작 → 1scene2 종료로 자연스럽게 전환되는 클립 생성됨

---

### Scene 1 (수정 후) — AI 정리 시작

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 1 (수정 후) |
| 예상 길이 | 6~8초 |
| 목표 메시지 | QUANTA AI가 데이터를 정리하기 시작하는 전환 표현 |
| 화면 구성 | 데이터가 중앙으로 수렴, 블루 네온 흐름 생성, 인물 시선 고정 |
| 카메라 워크 | Slow forward dolly movement |
| Mood | Transformation / Control / Emerging Intelligence |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (클립 생성) |
| 생성 파일명 | [1scene2.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test2.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
Same Korean investor, same futuristic Seoul financial
penthouse, chaotic market data suddenly freezing in
midair, AI intelligence activating, fragmented financial
information reorganizing into elegant structured
holographic systems, blue neural pathways connecting
stock charts and market signals, information becoming
clean and understandable, investor becoming calm
and focused, sophisticated AI-powered financial
visualization, premium fintech aesthetic,
electric blue neon glow intensifying,
cinematic lighting, photorealistic, ultra realistic,
HDR, ray tracing, volumetric atmosphere
```

**이미지 출력 결과:** AI 코어를 향해 데이터가 수렴되고 투자자가 침착하게 바라보는 이미지 생성됨

**[Google Flow] 클립 생성 프롬프트:**

```
Cinematic transition clip starting with same Korean
male investor standing calmly, organized AI holographic
panels surrounding him, electric blue neural pathways
active, slow forward dolly camera.
Gradually transition to close-up of same investor's
hand reaching forward touching floating holographic
AI analytics panel, fingertip making contact with
electric blue interface, layered financial data
unfolding elegantly around touch point.
Smooth cinematic cut from medium shot to close-up.
No text, no subtitles, no narration,
ultra realistic, HDR, cinematic depth of field.
```

**클립 출력 결과:** 1scene2 시작 → 2scene2 종료로 자연스럽게 전환되는 클립 생성됨

---

### ✏️ 프롬프트 수정 전/후 비교 (과제 핵심 요건)

| 항목 | 수정 전 | 수정 후 |
|---|---|---|
| 데이터 상태 | chaotic, overwhelming, crossing in every direction | freezing, reorganizing, becoming clean |
| 인물 감정 | stressed, unable to focus | calm, focused |
| AI 역할 | 없음 | AI intelligence activating, neural pathways connecting |
| 카메라 | Fast orbiting | Slow forward dolly |

**수정 의도:** 정보 과부하라는 문제를 먼저 시각적으로 제시한 뒤, QUANTA의 핵심 가치인 데이터 정제와 AI 인텔리전스를 전환점으로 표현하기 위해 프롬프트의 감정어와 데이터 상태 묘사를 전면 교체했다.

**수정 결과:** 투자자의 표정이 혼란에서 집중으로 바뀌었고, 데이터 시각화가 폭발적 혼돈에서 정렬된 구조로 전환되어 QUANTA의 USP가 명확하게 표현됨.

---

### Scene 2 — 데이터 상호작용

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 2 |
| 예상 길이 | 7~8초 |
| 목표 메시지 | AI와 직접 상호작용하며 데이터를 탐색 |
| 화면 구성 | 손과 데이터 패널 중심, 얼굴 일부 포함, 인터페이스 디테일 강조 |
| 카메라 워크 | Close-up tracking movement following hand interaction |
| Mood | Engagement / Precision / Control |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (클립 생성) |
| 생성 파일명 | [2scene2.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test3.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
Close-up shot of the same Korean investor interacting
with a floating holographic financial panel,
hand reaching forward and touching transparent
AI-driven market analytics interface,
layered stock charts unfolding elegantly,
intelligent financial insights connecting through
electric blue neural networks,
futuristic Seoul skyline softly blurred in background,
premium fintech command center, cyberpunk atmosphere,
blue neon holograms, photorealistic, ultra realistic,
HDR, ray tracing, cinematic depth of field
```

**이미지 출력 결과:** 손가락으로 AI 패널을 터치하는 클로즈업 이미지 생성됨

**[Google Flow] 클립 생성 프롬프트:**

```
Cinematic transition clip starting with close-up
of same Korean investor's hand touching holographic
AI panel, electric blue interface reacting to touch,
financial data layers unfolding.
Gradually transition to same investor now seated
at glass desk, eye-level medium shot, leaning forward
analyzing structured AI investment intelligence panels,
calm focused expression, slow horizontal slide camera.
Smooth pull-back from close-up to medium seated shot.
No text, no subtitles, no narration,
ultra realistic, HDR, cinematic.
```

**클립 출력 결과:** 2scene2 시작 → 3scene3 종료로 자연스럽게 전환되는 클립 생성됨

---

### Scene 3 — 심층 분석

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 3 |
| 예상 길이 | 7~8초 |
| 목표 메시지 | AI 분석 결과를 깊이 검토하는 집중 상태 표현 |
| 화면 구성 | 인물 상반신 중심, 의자 착석, 데이터 네트워크가 배경 형성 |
| 카메라 워크 | Slow horizontal slide |
| Mood | Analytical / Focused / Strategic |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (클립 생성) |
| 생성 파일명 | [3scene3.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test4.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
Eye-level medium shot, same Korean investor seated
inside futuristic Seoul financial penthouse,
carefully analyzing structured AI-generated
investment intelligence, holographic market
prediction models floating around him,
interconnected financial variables visualized
through elegant electric blue data networks,
calm focused expression, premium fintech environment,
cyberpunk Seoul skyline, cinematic realism,
ultra realistic, photorealistic, HDR, ray tracing,
sophisticated financial intelligence interface
```

**이미지 출력 결과:** 유리 책상에 앉아 홀로그램 데이터를 분석하는 투자자 이미지 생성됨

**[Google Flow] 클립 생성 프롬프트:**

```
Cinematic transition clip starting with same Korean
investor seated analyzing holographic AI dashboards,
calm focused expression, eye-level medium shot.
Gradually transition to same investor rising from seat,
low angle upward cinematic shot, powerful AI investment
insight glowing above him, electric blue and purple
holographic energy aligning around single predictive
signal, investor looking upward with confidence.
Smooth camera movement from eye-level to low angle.
No text, no subtitles, no narration,
ultra realistic, HDR, cinematic.
```

**클립 출력 결과:** 3scene3 시작 → 4scene4 종료로 자연스럽게 전환되는 클립 생성됨

---

### Scene 4 — 인사이트 발견

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 4 |
| 예상 길이 | 7~8초 |
| 목표 메시지 | AI가 도출한 핵심 투자 기회를 발견하는 순간 |
| 화면 구성 | 인물이 크게 보임, 인사이트가 상단 중앙, 데이터가 주변에서 정렬 |
| 카메라 워크 | Low-angle upward crane movement |
| Mood | Discovery / Confidence / Breakthrough |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (클립 생성) |
| 생성 파일명 | [4scene4.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test5.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
Low angle cinematic shot, same Korean investor
standing confidently inside futuristic Seoul
financial penthouse, powerful AI investment insight
illuminating the environment, financial data streams
aligning around a single predictive signal,
electric blue and subtle purple holographic glow,
investor realizing a high-value opportunity,
premium fintech atmosphere, cyberpunk architecture,
cinematic lighting, ultra realistic, HDR,
ray tracing, photorealistic
```

**이미지 출력 결과:** 위를 바라보며 인사이트를 확인하는 자신감 있는 투자자 Low angle 이미지 생성됨

**[Google Flow] 클립 생성 프롬프트:**

```
Cinematic transition clip starting with same Korean
investor standing confidently, low angle shot,
powerful AI insight glowing above him.
Gradually transition to wide pull-back aerial shot
revealing entire futuristic Seoul financial district,
same investor visible inside penthouse command center,
massive AI-powered financial intelligence network
extending across skyscrapers.
Smooth dramatic pull-back from low angle to wide aerial.
No text, no subtitles, no narration,
ultra realistic, HDR, volumetric lighting, cinematic.
```

**클립 출력 결과:** 4scene4 시작 → 5scene5 종료로 자연스럽게 전환되는 클립 생성됨

---

### Scene 5 — 도시 규모 확장

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 5 |
| 예상 길이 | 8~10초 |
| 목표 메시지 | QUANTA의 분석이 개인을 넘어 시장 전체와 연결됨을 표현 |
| 화면 구성 | 도시 전경 강조, 인물은 중앙 하단, 데이터 네트워크가 도시 전체 연결 |
| 카메라 워크 | Wide pull-back aerial retreat |
| Mood | Scale / Connectivity / Intelligence |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (클립 생성) |
| 생성 파일명 | [5scene5.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test6.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
Wide pull-back shot revealing the entire futuristic
Seoul financial district, same investor standing
inside penthouse command center,
massive AI-powered financial intelligence network
extending across skyscrapers,
holographic market data integrated with
city infrastructure, electric blue neural pathways
connecting global financial information,
premium fintech ecosystem, cyberpunk skyline,
cinematic scale, ultra realistic, HDR,
ray tracing, volumetric lighting, photorealistic
```

**이미지 출력 결과:** 서울 금융지구 전체가 AI 데이터 네트워크로 연결된 Wide shot 이미지 생성됨

**[Google Flow] 클립 생성 프롬프트:**

```
Cinematic transition clip starting with wide aerial
shot of futuristic Seoul financial district,
investor silhouette visible inside penthouse.
Gradually transition to slow push-in toward same
investor now facing camera directly, medium close-up,
calm confident direct eye contact, perfectly organized
AI financial intelligence system operating behind him,
electric blue neon glow, subtle purple accents.
Smooth camera movement pulling in from wide to close-up.
No text, no subtitles, no narration,
ultra realistic, HDR, cinematic masterpiece.
```

**클립 출력 결과:** 5scene5 시작 → 6scene6 종료로 자연스럽게 전환되는 클립 생성됨

---

### Scene 6 — 명확한 의사결정

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 6 |
| 예상 길이 | 8~10초 |
| 목표 메시지 | QUANTA가 제공하는 명확한 의사결정의 가치 전달 |
| 화면 구성 | 정면 응시, 인물 중심, 정돈된 데이터 배경, 브랜드 세계관 완성 |
| 카메라 워크 | Slow push-in toward face |
| Mood | Clarity / Trust / Decision Intelligence |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (클립 생성) |
| 생성 파일명 | [6scene6.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test7.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
Slow push-in cinematic shot toward the same Korean
investor, direct eye contact with camera,
perfectly organized AI-powered financial intelligence
system operating behind him,
elegant holographic market analytics,
structured investment insights,
electric blue neon glow, subtle purple accents,
futuristic Seoul skyline at night,
premium fintech command center,
confidence, clarity, trust,
ultra realistic, photorealistic, HDR,
ray tracing, volumetric lighting, cinematic masterpiece,
no text overlay, no subtitles, no narration,
visual storytelling only
```

**이미지 출력 결과:** 카메라를 정면으로 응시하며 자신감 있게 서있는 투자자 이미지 생성됨

**[Google Flow] 클립 생성 프롬프트:**

```
Cinematic transition clip starting with same Korean
investor facing camera directly, calm confident
expression, organized AI panels behind him.
Gradually transition to premium brand end card,
holographic displays dissolving into thousands of
electric blue neon particles gathering in dark space,
particles elegantly forming QUANTA logo at screen center,
subtle purple neon accents flowing around logo edges.
Smooth cinematic fade from investor to brand logo.
No text overlay except QUANTA logo and tagline,
ultra realistic, HDR, cinematic masterpiece.
```

**클립 출력 결과:** 6scene6 시작 → 7scene7 종료로 자연스럽게 전환되는 클립 생성됨

---

### Scene 7 — QUANTA 브랜드 엔딩

| 항목 | 내용 |
|---|---|
| 씬 번호 | Scene 7 |
| 예상 길이 | 5초 |
| 목표 메시지 | 브랜드명 QUANTA를 강하게 각인 |
| 화면 구성 | 중앙에 QUANTA 로고, 하단에 슬로건, 어두운 배경에 블루 네온 입자 |
| 카메라 워크 | Slow cinematic push-in toward logo |
| Mood | Premium / Trustworthy / Innovative / Memorable |
| 화면 텍스트 | QUANTA / Beyond Data, Into Decisions. |
| 내레이션 | 없음 |
| 사용 도구 | Claude (프롬프트 설계) → ChatGPT DALL-E (이미지 생성) → Google Flow (단독 클립 생성) |
| 생성 파일명 | [7scene7.png](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Images) / [test8.mp4](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Videos/Clip) |

**[ChatGPT DALL-E] 이미지 생성 프롬프트:**

```
Premium fintech brand end card,
thousands of electric blue neon particles gathering
in a dark futuristic data space,
particles forming the QUANTA logo at the center,
elegant blue energy trails,
subtle purple neon accents flowing around logo edges,
futuristic Seoul financial skyline softly visible,
luxury AI investment technology branding,
clean composition, cinematic lighting,
volumetric glow, photorealistic, ultra realistic,
HDR, ray tracing, global illumination,
centered typography reading QUANTA,
smaller subtitle Beyond Data Into Decisions
```

**이미지 출력 결과:** QUANTA 로고와 슬로건이 블루 네온 입자로 형성되는 브랜드 엔딩 이미지 생성됨

**[Google Flow] 단독 클립 생성 프롬프트 (5초):**

```
Premium fintech brand end card, 5 seconds duration,
thousands of electric blue neon particles slowly
gathering in dark futuristic data space,
particles elegantly forming QUANTA logo at screen center,
subtle purple neon accents flowing around logo edges,
futuristic Seoul financial skyline softly visible,
slow cinematic push-in toward logo,
logo glowing brighter as it fully forms,
final frame completely still with QUANTA logo centered,
electric blue and purple neon glow, dark navy background,
no motion after logo forms,
centered text QUANTA and subtitle
Beyond Data Into Decisions below,
cinematic masterpiece, premium fintech aesthetic
```

**클립 출력 결과:** QUANTA 로고가 블루 네온 입자로 형성되는 5초 브랜드 엔딩 클립 생성됨

---

## 10. 오디오 제작 (Suno)

### 생성된 BGM 정보

| 항목 | 내용 |
|---|---|
| BGM 제목 | Digital Frontier |
| 생성 도구 | Suno v4.5 |
| 파일명 | [Digital Frontier.mp3](https://github.com/Xn0w/ia-codyssey/tree/main/B1/2/Audio) |

### Suno 입력 프롬프트

**Lyrics 칸:**
```
cinematic electronic, dark atmospheric,
cyberpunk ambient, epic orchestral,
no vocals, instrumental only
```

**Styles 칸:**
```
웅장한 음악, 고전 음악, 이교도, 슬픈 비트, 테크노 랩
```

### 음악 구조

| 구간 | 음악 흐름 | 대응 씬 |
|---|---|---|
| 0~10초 | 긴장감 있는 도입 | 씬1 수정 전 (혼돈) |
| 10~20초 | 전환, 상승 | 씬1 수정 후 ~ 씬2 |
| 20~40초 | 안정적 고조 | 씬3 ~ 씬5 |
| 40~55초 | 웅장한 클라이맥스 | 씬6 ~ 씬7 |

---

## 11. 최종 영상 스펙

| 항목 | 내용 | 과제 요건 | 충족 여부 |
|---|---|---|---|
| 파일명 | [Quanta.mp4](https://youtu.be/Gu3XoUOpUKA) | - | - |
| 길이 | 50.7초 | 30~60초 | ✅ |
| 해상도 | 1920x1080 | 1080p | ✅ |
| 프레임레이트 | 30fps | 24~30fps | ✅ |
| 비디오 코덱 | H.264 | H.264 | ✅ |
| 오디오 코덱 | AAC | AAC | ✅ |
| 시각 요소 | AI 생성 이미지/영상 | 필수 | ✅ |
| 청각 요소 | Digital Frontier BGM | 필수 | ✅ |

---

## 12. 서사 구조 요약

이 광고는 기승전결 구조를 따릅니다:

- **기 (문제 제시):** 씬1 수정 전 — 투자자가 데이터 과부하로 의사결정을 못하는 상황
- **승 (전환):** 씬1 수정 후 ~ 씬3 — QUANTA AI가 데이터를 정리하고 분석 시작
- **전 (클라이맥스):** 씬4 ~ 씬5 — 핵심 인사이트 발견 및 시장 전체와의 연결
- **결 (해결/제안):** 씬6 ~ 씬7 — 명확한 의사결정과 QUANTA 브랜드 각인

> 영상 마지막 5초 구간에 QUANTA 로고 + 슬로건 **"Beyond Data, Into Decisions."** 표시

---

*B1-2 과제 | AI 기반 브랜드 광고 영상 제작*
