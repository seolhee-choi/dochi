# 고슴도치 개발자의 일상

AI 도구를 활용해 제작한 개발자 일상 코미디 숏폼 애니메이션입니다.<br>
이유없이 그냥 한 번 제작해봤습니다.<br>
다음엔 더 나은 퀄리티로 도전해 볼 예정..<br>
![cute-love](./assets/cute-love.gif)

## 영상 보기

▶ [Vercel에서 영상 재생하기](https://dochi-five.vercel.app/)

## 제작 과정 (순서대로 작성함)

1. **Nano Banana**
   - 기준 캐릭터 이미지 제작
   - 캐릭터 디자인과 이미지 프롬프트 구성
<details>
<summary><strong>사용한 캐릭터 프롬프트 보기</strong></summary>

```text
A chubby, brown-furred hedgehog with a round face, shiny dark eyes, and slightly droopy ears. It wears glasses like a nerdy developer. The style is photorealistic, with soft fur texture and sharp details.
```

</details>

2. **Codex**
   - 장면별 영상 프롬프트 작성
   - 한국어 프롬프트 영문화 및 길이 최적화
   - 캐릭터와 배경의 일관성 보완

3. **미리캔버스**
   - 기준 캐릭터 이미지와 Codex 프롬프트로 장면별 영상 생성
<details>
<summary><strong>사용한 영상 프롬프트 보기</strong></summary>

```text
It's relatable developer-life comedy tone and Smooth camera movement, natural motion, and clean background details.
Maintain consistent character design throughout all scenes and short-form animation, around 3–5 seconds per scene.
Rich facial expressions and clear emotional acting.
A cute hedgehog developer sits at a cozy home-office desk and opens a laptop. On the desk are a coffee mug, a small keyboard, sticky notes, and a monitor. The hedgehog looks bright and confident, giving the feeling of “This bug will take only five minutes to fix.” Soft morning sunlight fills the room. The overall mood is warm, adorable, and slightly comedic. Medium shot, with a gentle slow zoom in.
The hedgehog developer stares at the code and suddenly widens its eyes. Several unexpected red error messages appear on the monitor. The hedgehog tilts its head in confusion, one paw on the keyboard and the other on its chin. 

The expression is adorably puzzled, with a slightly frozen smile and comedic awkward silence. Keep the same workspace. Use an over-the-shoulder style shot so both the monitor and facial reaction are visible.
The hedgehog developer is desperately debugging. The monitor is filled with browser tabs, official documentation, search results, and terminal windows. The hedgehog types rapidly, while sticky notes are covered with doodles and checkmarks. The expression is serious yet adorable, with a slightly anxious mood. The workspace feels busier now, and snack crumbs appear beside the coffee mug. The scene should feel like a fast-paced comedic montage, with quick pans or rapid cuts.
After struggling for a while, the hedgehog developer slumps in the chair. It looks at the monitor with a mix of frustration and confusion, as if thinking, “It definitely worked earlier...” The hedgehog nervously taps its little feet or holds its head in disbelief. Cute, exaggerated frustration is the key emotion. 

The lighting shifts slightly into an afternoon mood, and the desk is a bit messier now. Use a front-facing medium shot to emphasize the emotional reaction.
The hedgehog developer leans closer to the screen, then suddenly its eyes sparkle. It has discovered the cause: a tiny typo or one missing character in a line of code. The hedgehog opens its mouth slightly in a mix of shock and disbelief, then quickly fixes it on the keyboard. The scene should feel like a sudden bright realization, with a subtle sparkle effect. Alternate between the code detail and the hedgehog’s expression, creating a cute and playful twist.
The hedgehog developer presses Enter, and the program finally runs correctly. 

A successful result appears on the monitor, and the hedgehog throws both paws up in celebration. Its eyes sparkle, and its tiny body bounces with joy. The coffee mug, sticky notes, and monitor glow all contribute to a warm feeling of accomplishment. The mood is cute, satisfying, and triumphant. 
Use a slightly low-angle shot to make the hedgehog feel like a tiny hero.
It is now nighttime, and the hedgehog developer relaxes in a chair or on a small couch with a peaceful expression. Suddenly, a new error notification appears on the phone or laptop. The hedgehog’s smile freezes, and it slowly turns to look at the camera. The mood should feel like “Ah... here we go again,” creating a relatable comedy ending. The lighting is cozy and nighttime-soft, while the notification glows a bit dramatically. End the story in a cute, funny, and highly relatable way.
```

</details>

4. **Typecast**
   - 대사를 텍스트로 입력
   - 캐릭터별 AI 음성 생성 및 추출

5. **CapCut**
   - 장면 편집과 오디오 동기화
   - 자막, 전환 효과, 배경음악 적용

6. **Vercel**
   - 완성 영상 웹페이지 배포 및 공유 링크 생성

## 주요 콘셉트

- React + TypeScript 개발자의 버그 수정 과정
- 동일한 고슴도치 캐릭터와 작업 공간 유지
- 귀엽고 공감되는 개발자 일상 코미디
- 장면당 3–5초 분량의 숏폼 구성

## 사용 도구

| 작업 | 도구 |
|---|---|
| 캐릭터 제작 | Nano Banana |
| 프롬프트 작성·번역 | Codex |
| AI 영상 생성 | 미리캔버스 |
| AI 음성 생성 | Typecast |
| 영상 편집 | CapCut |
| 웹 배포 | Vercel |

## 제작자

- GitHub: [최설희](https://github.com/seolhee-choi)
