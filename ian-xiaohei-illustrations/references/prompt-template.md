# 이미지 생성 프롬프트 템플릿

각 이미지는 따로 생성한다. 본문 내용에 맞춰 변수를 바꾸고, 여러 장을 한 장에 합치지 않는다.

```text
Generate one standalone 16:9 horizontal Korean article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Korean annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
小黑, a small solid-black absurd creature with white dot eyes, tiny thin legs, blank serious expression, slightly uneven hand-drawn body shape. 小黑 must perform the core conceptual action, not decorate the scene. Make 小黑 serious, deadpan, and slightly bizarre, not cute.

Language rule:
All handwritten annotations, labels, and short phrases inside the image must be natural Korean. If the source content is Chinese, English, Japanese, or any other language, translate the image labels into Korean. No Chinese labels. No English explanatory labels, except unavoidable product names, code identifiers, or proper nouns.

Theme:
{본문 삽화 주제}

Structure type:
{구조 유형: Workflow / 시스템 일부 / 전후 비교 / 역할 상태 / 개념 은유 / 방법 분층 / 지도 경로 / 짧은 만화 컷}

Core idea:
{이 그림이 표현해야 할 핵심 의미}

Composition:
{구체적 화면: 小黑가 어디에서 무엇을 하는지, 주요 물건은 무엇인지, 정보나 흐름이 어떻게 움직이는지}

Suggested elements:
{요소1} / {요소2} / {요소3} / {요소4}

Korean handwritten labels only:
{한국어 라벨1} / {한국어 라벨2} / {한국어 라벨3} / {한국어 라벨4} / {선택 한국어 라벨5}

Color use:
Black for main line art and 小黑. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Korean labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 이미지 편집 프롬프트

좌상단 제목 제거:

```text
Edit the provided image. Remove only the handwritten title "{삭제할 문구}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects. Keep all remaining image text in Korean.
```

괴상함 강화:

```text
Regenerate this illustration with the same core meaning and simple layout, but make 小黑 more central to the conceptual action. 小黑 should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute. All labels and annotations must be natural Korean only.
```
