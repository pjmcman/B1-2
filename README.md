📄 [과제 제출] AI 기반 브랜드 광고 제작 프로젝트

## 1. 브랜드 아이덴티티 및 캠페인 정의
> 선택한 브랜드의 정보와 기획 목적을 작성하는 공간입니다.

*   **브랜드명:** 온기로 (ONKIRO)
*   **타겟층:** 여행 일정을 주도적으로 계획하며, 과거에 대한 아련한 감수성과 90년대 노스텔지어(향수)를 그리워하는 30~40대 여성층
*   **톤앤매너:** Warm, Cozy, Aesthetic, Modern-Retro (따뜻함, 포근함, 감성적, 모던 레트로)
*   **USP (차별점):** 빈집이 가진 고유의 아날로그 역사와 90년대 감성을 그대로 살리되, 최신식 침대, 세련된 화장실, 현대적인 주방 시설을 완벽히 구축하여 '감성과 편리함'을 동시에 잡은 프리미엄 시골 공간 재생 플랫폼
*   **광고 목적:** 인지 (Brand Awareness) 및 브랜드 인상 각인 (Brand Awareness)
*   **핵심 메시지 (한 문장):** 
    > **"빛바랜 공간, 당신의 온기로 다시 이뻐지다."**

---

## 2. 멀티모달 파이프라인 및 도구 설계
> 미션에 사용한 도구들과 리스크 대응 도구를 작성하세요.

| 미디어 분류 | 선택한 주 도구 | 대체 도구 (Risk 대응) | 도구 선택 이유 및 목적 |
| :--- | :--- | :--- | :--- |
| **이미지 생성** | Gemini | Midjourney | 대화형 인터페이스로 기획 의도를 신속하게 구체화하고 베이스 이미지를 생성하기 위함. |
| **비디오 변환** | Flow | Kling | 이미지의 고유한 화풍과 구도를 깨뜨리지 않으면서, 자연스러운 모션을 부여하기 위함. |
| **오디오 생성** | Suno | Udio | 브랜드 감성에 맞는 고품질의 배경음악(BGM)을 텍스트 프롬프트로 빠르게 확보하기 위함. |
| **음성 합성 (TTS)** | ElevenLabs | Typecast | 기계음을 배제하고, 실제 성우 같이 자연스러운 톤과 감정이 실린 내레이션을 입히기 위함. |
| **통합 편집** | CapCut | Vrew | 생성된 영상·오디오 소스들을 한데 모아 컷 편집하고, 자막 및 오디오 싱크를 직관적으로 맞추기 위함. |

## 3. 상세 스토리보드 (Storyboard)
> 10초 이내 영상의 씬별 데이터를 누락 없이 채워주세요. (필요 시 씬 가감 가능)


### 🎬 씬 1 (Intro)
*   **씬 길이:** `3.5초`
*   **목표 메시지:** 오래도록 방치되어 온기가 사라진 시골 빈집의 쓸쓸함과 아련함 각인.
*   **화면 구성:** 
    *   **배경:** 톤 다운된 블루·그레이 파스텔톤의 흐린 하늘 아래, 낙엽과 거미줄이 정돈되지 않은 채 방치된 시골집 마당과 계단. 빛바랜 수국과 낡은 벤치 위 펼쳐진 책이 아련한 노스텔지어를 자극함.
    *   **피사체:** 대문 틈 사이로 슬픈 눈망울을 한 채 빼꼼 고개를 내밀고 있는 귀여운 강아지 캐릭터 '온이'.
    *   **레이아웃/텍스트:** 화면 우측 상단에 '온기로(ONKIRO)' 로고가 조화롭게 배치되어 있음. 화면 하단에 차분한 서체의 자막 삽입. (화면 자막: "기억 뒤편으로 사라지던 시골 집...")
*   **내레이션 / 카피:** "차가운 온기만 남은 채 멈춰있던 공간."
*   **사용 도구 및 목적:** 
    *   **이미지 생성:** Gemini (실제 빈집 사진 소스와 로고, 캐릭터 레이아웃을 조합하여 90년대 감성 레트로 애니메이션 스타일의 비주얼 확보)
    *   **비디오 변환:** Flux (Flow) (정지 이미지에 쓸쓸하게 흩날리는 낙엽, 바람에 흔들리는 꽃잎, 온이의 미세한 눈빡임 모션을 부여하여 생동감 연출)
*   **입력 프롬프트 (원문):** `An old, abandoned traditional Korean countryside house yard, lonely and melancholy atmosphere, dusty wooden porch, overcast foggy grey sky, subdues pastel tones, 90s vintage anime style, clean line art, Ghibli master piece tone, a cute sad puppy character looking out from behind the gate, onkiro logo on top right --ar 1:1` *(※ 현재 1:1 비율로 생성된 점을 고려하여 원문 기록)*
*   **출력 결과 요약 (한 줄):** 흐린 톤의 마당 배경과 대문 뒤 슬픈 표정의 캐릭터가 어우러져 타겟의 감수성을 자극하는 오프닝 컷 완성.
*   **결과 파일명 / 링크:** `scene01_abandoned_house.mp4`


### 🎬 씬 2 (Bridge / 반전)
*   **씬 길이:** `3.5초`
*   **목표 메시지:** 겉은 아날로그 감성이지만 속은 최고급으로 쾌적한 공간의 반전 매력 전달.
*   **화면 구성:** 
    *   **배경:**전통 시골집의 고유한 나무 서까래 구조는 그대로 보존되어 있으나, 내부는 최고급 호텔 수준으로 리모델링된 현대적이고 세련된 침실(또는 거실). 큰 창문을 통해 화사하고 따뜻한 오후의 햇살이 공간 전체를 아늑하게 감싸는 구도.
    *   **피사체:** 씬 1의 슬픈 모습과 대조적으로, 푹신하고 하얀 최신식 침대(또는 소파) 위에서 세상에서 가장 편안하고 행복한 표정으로 부드럽게 미소 지으며 엎드려 있는 강아지 캐릭터 '온이'.
    *   **레이아웃/텍스트:** 화면의 균형감을 깨지 않는 위치에 '온기로(ONKIRO)' 로고가 지속 노출됨. 화면 하단에 폰트 크기와 서체를 통일한 자막 삽입. (화면 자막: "...가장 현대적인 편리함으로 다시 태어나다.")
*   **내레이션 / 카피:** "익숙한 아늑함 속에 감춰진 완벽한 편안함."
*   **사용 도구 및 목적:** 
    *   **이미지 생성:** Gemini (새 대화 창에서 씬 1의 캐릭터 소스를 참조하여, 90년대 지브리풍 만화 화풍을 유지한 채 화사한 인테리어와 행복한 캐릭터 표정 생성)
    *   **비디오 변환:** Flux (Flow) (창문으로 들어오는 햇살의 미세한 먼지 입자 효과, 온이의 꼬리치기나 귀의 부드러운 움직임 모션을 추가하여 극적인 아늑함 연출)
*   **입력 프롬프트 (원문):** `[Instruction: Create a new 16:9 widescreen image based on the attached character and logo sources.] - Scene Context: This is the second scene of the commercial, showing a dramatic contrast to the previous sad, abandoned house... Inside a cozy traditional Korean house. The old wooden ceiling beams (Seokgarae) are beautifully preserved, but the room is renovated into a premium, hyper-clean, and modern bedroom. A plush, high-end white king-sized bed with crisp linens is the main focus... The cute puppy character 'Oni' is now lying comfortably in the center of the soft white bed. Oni looks incredibly happy, cozy, and relaxed, with a soft and warm smile... 90s vintage nostalgic anime style, soft faded pastel tones, Studio Ghibli-inspired masterpiece vibe... --ar 16:9`
*   **출력 결과 요약 (한 줄):** ` 서까래의 고풍스러움과 고급 침실이 융합된 공간에서 캐릭터가 세상 편하게 힐링하는 압도적 퀄리티의 키 비주얼 완성.

*   **결과 파일명 / 링크:** `scene02_cozy_interior.mp4`

### 🎬 씬 3 (마지막 3~5초 브랜드 인지 필수)
*   **씬 길이:** `3.0초`
*   **목표 메시지:** 캐릭터 '온이'의 다정한 초대와 립싱크 대사를 통한 브랜드 인지 극대화 및 웹사이트 방문 유도.
*   **화면 구성:** 
    *   **전반부 (1.5초):** 화사하고 현대적인 온기로 숙소 내부를 배경으로, 강아지 캐릭터 '온이'가 정면을 바라보며 앞발을 들고 반갑게 환영 인사를 건넴. 온이 뒤편으로 '오신 것을 환영합니다 - Welcome -'이 적힌 아기자기한 이젤 표지판이 배치되어 환대의 분위기를 강조함. 온이가 입을 움직이며 직접 대사를 발화함.
    *   **후반부 (1.5초):** 온이의 초대가 끝나며 화면이 부드럽게 전환되고, 우측 벽면에 위치한 '온기로(ONKIRO)' 브랜드 로고가 점차 메인으로 강조됨. 화면 중앙 하단에 공식 웹사이트 링크와 검색창 자막이 서서히 떠오르며 종료됨. (화면 카피: "지금, 당신의 온기를 채워보세요. | www.ongiro.com")
*   **내레이션 / 대사 (캐릭터 발화):** "일상이 지칠때? 온기로 놀러 와!"
*   **사용 도구 및 목적:** 
    *   **이미지 생성:** Gemini (씬 2의 완성도 높은 인테리어 구도를 완벽히 계승하면서, 환영 포즈를 취한 온이와 웰컴 표지판 오브젝트를 조화롭게 구성한 엔딩 비주얼 확보)
    *   **비디오 변환/립싱크:** Flux (Flow) 또는 전용 AI 립싱크 툴 (ElevenLabs로 생성한 음성 싱크에 맞춰 온이의 입모양이 자연스럽게 움직이도록 구현하고, 엔딩 로고 부각을 위한 모션 그래픽 연출)
    *   **오디오 생성:** ElevenLabs (친근하고 다정한 목소리 톤으로 온이의 초대 대사를 인공지능 성우 합성음으로 제작)
*   **입력 프롬프트 (원문):** `[Instruction: Create a new image based on the attached character and logo sources, maintaining the exact same interior room from Scene 2.] - Scene Context: This is the final outro scene of the commercial where the character directly invites the viewers. - Background: The exact same beautifully renovated modern Korean traditional bedroom from Scene 2 with warm afternoon sunlight. On the left side, there is a small cute wooden easel sign that says "오신 것을 환영합니다 - Welcome -". - Subject (Character): The cute puppy character 'Oni' is standing in the foreground, looking directly at the camera with a bright, welcoming smile. One of its front paws is raised high in the air, waving to greet the viewers. Its mouth is slightly open as if speaking affectionately. - Art Style: 90s vintage nostalgic anime style, soft faded pastel tones, warm cinematic lighting, clean line art, Studio Ghibli-inspired vibe. - Layout: Ensure the center and bottom areas remain clean enough to superimpose website text later, and keep the 'ONKIRO' logo visible on the right wall.`
*   **출력 결과 요약 (한 줄):** 앞발을 들고 환영하는 캐릭터와 '오신 것을 환영합니다' 표지판이 어우러져 광고의 메시지와 미션을 완벽히 종결하는 엔딩 컷 완성.
*   **결과 파일명 / 링크:** `scene03_oni_welcome_invite.mp4`

---

## 4. 프롬프트 개선 로그 (Prompt Engineering Log)
> 최소 1개 이상의 씬에서 프롬프트 수정을 통해 한계를 극복한 과정을 기록하세요.

# 📝 스토리보드 프롬프트 수정 및 개선서

* **대상 씬 번호:** 씬2
* **수정 전 의도 및 프롬프트:**
  * **의도:** '온이' 캐릭터가 새롭게 단장한 숙소 집안으로 밝고 발랄하게 걸어 들어가며 "온기로로 놀러와"라고 초대하는 10초 분량의 애니메이션 씬 연출.
  * **수정 전 프롬프트:** `A cute golden retriever puppy wearing an orange scarf walking into a cozy renovated house, cheerful mood, animation style`
* **발생한 문제점:** *(캐릭터/화풍 불일치 등 기술적 한계)*
  * 씬1에서 씬2로 장면이 전환될 때, AI가 캐릭터의 이목구비나 비율, 주황색 스카프 착용 형태 및 애니메이션 화풍을 미세하게 변형시켜 캐릭터 일관성이 깨지는 현상 발생.
* **수정 후 프롬프트:**
  * `[Storyboard Asset: Oni_Welcoming] A cute golden retriever puppy walking into a cozy renovated stay, camera following behind, smooth camera pan, vibrant animation style --cw 100`
* **개선 근거 및 결과:** *(어떤 파라미터나 레퍼런스(cref, sref 등)를 고정하여 해결했는지 포함)*
  * **스토리보드 캐스팅(Cast) 지정:** 씬1의 기준 캐릭터인 '온이' 이미지 원본을 Flow의 **Character Asset(캐릭터 자산)**으로 등록 후, 씬2의 등장인물(Cast)로 고정 지정함.
  * **파라미터 및 캐릭터 참조(Character Reference) 적용:** 자산 연동을 통해 내부 캐릭터 가중치 파라미터(`--cw 100` / Character Weight)를 고정 적용하여, 장소가 바뀌거나 카메라 워킹(Pan/Follow)이 들어가도 캐릭터의 얼굴, 주황색 스카프, 3D 애니메이션 질감이 왜곡 없이 동일하게 유지되도록 개선함.
---

## 5. 최종 영상 파일 정보
> 제출하는 인코딩 스펙 및 리소스 관리 전략을 작성하세요.

* **최종 파일명:** `onkiropro.mp4` (또는 프로젝트 관리 기준에 맞춰 `onkiro_brand_ad_final.mp4`로 변경 가능)
* **영상 총 길이:** `10초` (타임라인 총 길이 10초 확인)
* **해상도 및 비율:** `1920x1080 (1080P), 16:9 와이드스크린`
* **프레임레이트:** `30fps`
* **비디오 / 오디오 코덱:** `H.264 / AAC`
* **크레딧 부족 시 대응 전략:** * *분량 조정 전략:* 한정된 무료 크레딧 환경을 고려하여 불필요하게 긴 롱테이크 연출을 지양하고, 광고 몰입도가 가장 높은 씬당 2~3초 내외의 '숏폼 타임라인(총 10초)' 전략을 수립하여 소모 크레딧을 최소화함.
    * *스타일 고정 전략:* 생성형 AI의 무작위 변형으로 인한 크레딧 낭비를 막기 위해, 초기 프롬프트 단계에서 `90s vintage anime art style`, `Studio Ghibli vibe`와 같은 핵심 스타일 키워드를 선제적으로 완전히 고정함. 
    * *비디오 렌더링 최적화:* 비디오 변환 툴(Flow)에서 발생할 수 있는 오류를 차단하기 위해 복잡한 영상 편집 용어 대신 `Slow and gentle camera pan`과 같은 직관적인 자연어 카메라 무빙 명령만을 사용하여 단 한 번의 시도로 실패 없이 안정적인 결과물을 도출해 냄.
 AI 영상 제작 및 스토리보드 리소스 최적화 가이드

## 1. 동일 스토리보드를 다른 도구로 제작할 때의 차이점

같은 스토리보드라도 어떤 AI 도구(예: Runway, Kling, Luma, Sora 등)를 사용하느냐에 따라 다음 4가지 관점에서 가장 큰 차이가 발생합니다.

| 구분 | 주요 차이점 및 원인 | 실무적 영향 |
| :--- | :--- | :--- |
| **품질 (Quality)** | 모델의 학습 데이터 및 물리 엔진 성능 차이 | 광원, 인물 표정, 질감, 물리적 움직임(유체, 파괴 등)의 자연스러움이 달라집니다. |
| **제어 (Control)** | 카메라 워킹, 피사체 고정, 프롬프트 반영력 | 원하는 구도나 피사체 일관성(Character Consistency)을 얼마나 정확히 유지할 수 있는지 결정됩니다. |
| **속도 (Speed)** | 서버 부하 및 프레임 생성 속도 | 씬 1개를 생성하는 데 수초에서 수분이 걸리며, 전체 제작 라이프사이클에 직접적인 영향을 줍니다. |
| **비용 (Cost)** | **‘생성 성공률’에 따른 실질 비용 차이** | 단순히 초당 크레딧 단가보다, **의도한 결과물이 나올 때까지 시도하는 횟수(Re-roll)**에 따라 실질 비용이 크게 갈립니다. |

> **핵심 요약:** 제어력이 떨어지는 도구를 쓰면 품질이 높아 보여도 실패율이 높아져 **실질 비용과 제작 시간이 급증**합니다. 따라서 스토리보드 구현 시에는 **"제어력이 높은 도구"**를 우선 선택하는 것이 비용 효율적입니다.

---

## 2. 영상 생성 크레딧 부족 시 대응 전략

크레딧이 부족할 때는 AI 생성 의존도를 낮추고 **생성 성공률을 높이는 정밀 타격 전략**으로 전환해야 합니다.

### ① 씬 구성 재설계
* **Static / Slow Pan 씬으로 변경:** AI는 복잡하고 격렬한 동작일수록 실패율이 높습니다. 움직임이 적은 컷으로 변경해 한 번에 성공시킵니다.
* **Image-to-Video (I2V) 적극 활용:** Text-to-Video는 결과 예측이 어렵습니다. 스틸 이미지를 먼저 완성해 고정한 뒤, 약간의 모션만 주면 크레딧 낭비를 크게 줄일 수 있습니다.

### ② 도구 선택 재조정
* **고비용 AI 생성:** 임팩트가 필요한 **핵심 클라이맥스 씬(2~3개)**에만 고성능 AI 도구의 크레딧을 할당합니다.
* **무료 스톡 푸티지 & 스틸컷 활용:** 배경이나 일반적인 연출은 Pexels, Unsplash 등의 무료 스톡 영상이나, 2D 스틸 이미지에 카메라 줌/팬 효과(2.5D 연출)를 주는 방식으로 대체합니다.

### ③ 편집 전략 전환
* **속도 조절 (Speed Ramping):** 잘 나온 2~3초짜리 AI 푸티지를 슬로 모션으로 늘리거나 루프(Loop) 처리하여 연출 분량을 확보합니다.
* **패스트 컷 & 타이포그래피:** 길게 이어지는 비주얼 대신 1초 안팎의 빠른 컷 전환, 강렬한 자막, 사운드 효과(SFX)를 결합하여 비주얼 생성 부담을 줄이면서도 리듬감을 유지합니다.

---

## 3. 60초 버전을 15초로 축소할 때의 전략

60초 영상이 **'서사(Story)'** 중심이라면, 15초 숏폼 영상은 **'임팩트(Impact)'** 중심으로 구조 자체를 바꿔야 합니다.

### ① 씬 유지 vs 삭제 기준

* **유지할 씬 (Keep):**
  1. **Hook (0~3초):** 시선을 즉시 사로잡는 강렬한 비주얼 또는 질문 씬.
  2. **Core Value (3~11초):** 제품/서비스가 제공하는 가장 강력한 핵심 해결책 1가지.
  3. **CTA / Logo (11~15초):** 브랜드 로고 및 최종 행동 유도 메시지.
* **삭제할 씬 (Delete):**
  * 도입부 상황 설명(Intro/Context) 및 배경 연출.
  * 복수의 서브 기능 설명이나 부연 예시 씬.
  * 씬과 씬 사이의 완충 역할을 하는 전환(Transition) 씬.

### ② 메시지 재구성 구조 비교

```text
[60초 구조: 서사형]
도입(10s) ──> 문제 심화(15s) ──> 해결책 등장(15s) ──> 상세 기능/후기(15s) ──> CTA(5s)

[15초 구조: 직진형]
Hook(3s) ──> 핵심 가치 단일 결론(8s) ──> CTA 및 브랜드(4s)
```

* **재구성 키포인트:** "왜 이 문제가 발생하는가?"라는 설명 단계를 과감히 생략하고, **"이걸 쓰면 결과가 이렇게 달라진다"**는 직관적인 전후(Before & After) 또는 결론 위주의 메시지로 단축 배치합니다.


## 🌟 [보너스 과제 확인용] (선택 사항)
> 수행한 보너스 미션이 있다면 체크(`[x]`)하고 내용을 간단히 적어주세요.

*   [ ] **보너스 1 – 립싱크(Lip-sync) 적용**
    *   *내용:* 
*   [ ] **보너스 2 – 동일 스토리보드, 다른 도구로 재제작**
    *   *내용:* 

*   [x]  **보너스 3 – 플랫폼별 화면 비율 버전 제작**
    *   *내용:* *(예: 16:9 버전 및 9:16 버전 동시 제출)*
    
















