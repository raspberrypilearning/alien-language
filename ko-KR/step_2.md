## 사전 훈련 된 모델 사용

--- task ---
+ [machinelearningforkids.co.uk/scratch3으로 이동](https://machinelearningforkids.co.uk/scratch3/){: target = "_ blank"}
--- / task ---

**경고** 이 프로젝트의 이번 단계는 구글 크롬 웹브라우져를 사용해야 완료할 수 있습니다. 이 브라우져를 사용할 수 없는 경우 [단계 3: 새 프로젝트 만들기](https://projects.raspberrypi.org/en/projects/alien-language/3)로 건너 뛰십시오.

--- task ---
+ 그런 다음 **Speech to Text** 확장명을 로드하십시오. 왼쪽 하단에서 **확장** 단추를 클릭 한 다음 목록에서 **Speech to Text** 를 선택합니다. **참고 :** **Text to Speech** 확장이 아닌 **Speech to Text** 확장을 선택하십시오. ![확장 버튼을 가리키는 화살표](images/extensions-annotated.png)

+ **이벤트** 블록, **모션** 블록 및 새로운 **Speech to Text** 블록을 사용하여 다음 스크립트를 작성하십시오. ![추가 할 새로운 스크립트](images/S-to-T-blocks.png)

--- /task ---

--- task --- 이제 녹색 깃발을 클릭하여 코드를 실행하십시오. "왼쪽"또는 "오른쪽"이라고 말합니다. 스크래치 고양이는 당신이 말한 방향으로 움직여야 합니다. 음성을 사용하여 스크래치 고양이를 화면에서 앞뒤로 움직여보십시오. 차분하고 명확하게 말해보세요.

작동시키기가 어려울 수 있습니다. 작동하지 않으면 스크립트가 아래 스크립트처럼 보이도록 `말하기` 블록을 추가하여 사용자가 말하는 것을 보여줍니다. ![New scripts to see what the computer thinks you are saying](images/S-to-T-blocks-test.png) --- /task ---

이제 음성 인식을 사용하여 스크래치에서 캐릭터를 제어했습니다.

이 단계에서는 프로그램이 빠르게 작동하도록 하기 위해 이미 훈련 된 기계 학습 모델을 사용했습니다. 이것은 영어 사전에서 단어를 인식하도록 훈련 된 일반적인 기계 학습 모델입니다. 
