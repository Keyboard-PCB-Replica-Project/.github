## Keyboard PCB Replica Project
이 프로젝트는 시판 기판들을 복각하는 프로젝트에요.
작동하는 기판, 기판의 아웃라인, 혹은 단순한 사진이라도 업로드될 예정이랍니다.

소중한 키보드의 기판이 망가져서 더이상 사용할 수 없게 되거나,
조금 더 좋은 성능의 기판, 더 다양한 기능의 기판이 필요할 때
희망을 가지고 찾아볼 수 있는, 혹은 없더라도 요청해볼 수 있는 공간이 되었으면 합니다.

모든 기판은 오픈소스로 공개가 될 예정이지만, 프로젝트 주인 마음에 따라 오픈소스가 아닌 것들도 있을 수 있습니다!
물론 소스만 비공개고 파일은 전부 이용하실 수 있어요.

지금은 혼자서 시작하지만, 다른 분들도 언젠간 참여할 수 있는 공간이 되었으면 합니다.
각기 다른 스타일의 디자인과 각기 다른 MCU들, 또 서로 피드백을 주고받으며 발전하다 보면
멋진 공간이 될 수 있을 것 같습니다.

This project is dedicated to recreating and replicating commercially available keyboard PCBs.
We'll be uploading working PCBs, outlines, and even just reference photos — whatever we can gather.

Sometimes a beloved keyboard becomes unusable because its PCB is damaged beyond repair.
Sometimes we simply want a better-performing PCB, or one with more modern features.
This space is meant to be a hopeful archive — a place to search for what you need, or even what doesn’t exist yet.

All PCBs are intended to be released as open source.
However, in some cases, the availability may depend on the creator’s preferences — while the source code might not always be public, the design files will always be accessible for use.

While I’m starting this alone, I hope others will eventually join.
With diverse design styles, different MCUs, and shared feedback, I believe this space can grow into something truly special.

## Upload Format
업로드 포멧은 정확히 정해져있지는 않지만, 필수적인 포함 사항은 다음과 같아요 :

1. 기판의 거버(Gerber)와 POS,CPL 파일
이 프로젝트는 필요한 사람들이 기판을 직접 뽑아서 쓸 수 있게 하는 것이 궁극적인 목표이기 때문에, 설계 소스를 공유하지 않더라도 거버는 꼭 올라와 있어야 해요.

2. 기판의 실물 사진/설계 프로그램에서의 렌더링 사진
지금 찾아온 기판이 내가 원하는 기판이 맞는지 확인하려면 알아볼 수 있는 사진이 있어야겠죠? 안심하고 기판을 주문하려면, 확인할 수 있는 사진이나 그림이 있어야 할 거예요.

3. 펌웨어 및 VIA json 파일
기판을 직접 짜는 입장에서는 설계만 봐도 QMK로 펌웨어를 만들 수 있겠지만 그렇지 않은 경우도 많겠죠? 꼭 넣어줘야 해요.

4. 기판 검증 유무
꽤나 중요한 포인트예요. 설계가 언제든지 잘못될 수 있기 때문에, 이게 정상작동하는 기판이 맞는지, 이슈는 없는지, 아직 작동 확인을 못헀다든지 하는건 확인해줘야 해요.
신뢰도있는 프로젝트가 되려면 솔직하게 적어두는 것이 좋겠네요.

There isn’t a strict upload format, but the following items are considered essential:

1. Gerber, POS, and CPL files
Since the goal of this project is to allow anyone to manufacture and use the PCB themselves, it's absolutely necessary to include the production files — even if you choose not to share the full design sources.
At minimum, the Gerber files and pick-and-place (POS, CPL) files should be provided.

2. Photos or render images of the PCB
It’s important to visually confirm that the board matches what someone is looking for.
Whether it’s a real photo or a render from your design tool, please include at least one clear image.
This helps others feel confident before ordering or using the board.

3. Firmware and VIA .json files
While some users may be able to build firmware just by looking at the PCB design, many others can’t.
Please include any relevant QMK firmware and VIA .json files to make the board easy to use and set up.

4. Verification status
This is a very important part.
Designs can always have mistakes, so let others know the current status:

Is the board tested and working?

Are there known issues?

Has it not been tested yet?

Being transparent helps build trust and makes the project more reliable for everyone.

## Just a few words to end with:
이 프로젝트는 인원이 많으면 많을수록 좋은 프로젝트가 되겠지만, 결국 오픈소스에 무급으로 진행되기 때문에 많은 사람이 모이기 어려워요.

그렇기 때문에, 기판 작성을 취미로 가지고 있고, 가끔씩이라도 내 기판을 올려볼 생각이 있다 싶으신 분들이 계신다면 메일로 편하게 말씀 주세요.

언제나 누구든 환영합니다.

편하게 hjging826@gmail.com로 연락 주시면 됩니다. :)

This project would be even better with more people involved — but since it's open-source and entirely unpaid, it’s naturally difficult to gather a large number of contributors.

That said, if designing PCBs is something you enjoy as a hobby, and you’ve ever thought about sharing one of your own boards, even just once in a while — I’d love to hear from you.

Feel free to reach out by email at any time.

Everyone is always welcome, no matter your background or experience.

Feel free to reach out at hjging826@gmail.com — anytime.
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
