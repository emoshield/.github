# emoshield
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=aws&logoColor=white"> <img src="https://img.shields.io/badge/terraform-232F3E?style=for-the-badge&logo=terraform&logoColor=white">

## 개요

![image](https://github.com/emoshield/.github/assets/33739448/6e5b6c25-9beb-4fe8-aa1b-1b2301934b61)


감정노동자를 위한 Chat GPT활용 음성 필터링 서비스 emoshield입니다.

### 배경

emoshield는 최근 감정노동자가 받는 심리적 스트레스의 심각성에 착안하여 이러한 문제를 해결하고자 시작된 프로젝트입니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7d73e7b8-686e-4f30-8df1-d551f7b1e7e0/Untitled.png)

감정노동자 중 상담사의 불안한 심리와 스트레스는 상담사 자신과 주변에 큰 영향을 끼칠 수 있습니다.

- **상담사**
    - 감정 노동으로 인해 상담사의 감정적 부조화를 가져오고 스트레스를 유발합니다 → **마음이 지치고 불안해짐**
- **고객**
    - 상담사의 불안한 정서가 그대로 입을 통해 고객과의 대화에 투영됩니다 → **고객 만족도 하락**
- **회사**
    - 상담사의 대응은 콜센터의 강담 품질과 직결되며 개인을 넘어 회사의 문제가 될 수 있습니다. → **장기적인 회사의 손해**

![image](https://github.com/emoshield/.github/assets/33739448/fffcdcbf-4722-4891-bf69-06bc214303db)


기존에도 상담사를 보호하기 위한 제도는 있지만 이러한 제도가 감정노동자를 보호하는데에 실효성이 있는지 검증되지 않고 있고 여러 요인을 고려했을 때 대처 매뉴얼을 통해 고객에게 강경 대응하는 것은 현실적으로 어렵다는 문제가 있었습니다.

### emoshield

<aside>
💡 감정노동자가 실제로 스트레스 받을 일 없이 통화를 할 수는 없을까?

</aside>

이러한 문제점에서 착안하여 강한 감정의 전달에 방파제 역할을 해주는 서비스 **emoshield**를 만들게 되었습니다.

1. 고객의 두서없는 말, 욕설 등을 필터링하여 **상담원이 핵심 내용만 바로 파악**할 수 있다.
2. 텍스트로 추출한 문장에 있는 비속어의 **블러 처리 선택 기능**을 제공한다.
- **I.A**
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f9be6104-b9f5-456e-a8aa-1f7b6a12ddea/Untitled.png)
    

**고객 페이지**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5625e5a4-a8be-45e4-84fe-7d3bdfdf0afa/Untitled.png)

- 카테고리 별 회사 목록 확인 및 연결 서비스
    - 고객은 추가적인 탐색 없이 한번에 원하는 회사에 대한 정보를 편리하게 얻을 수 있습니다.
- 즐겨 찾는 회사 등록 기능
    - 자주 상담하는 회사를 따로 모아 언제나 쉽고 편리하게 상담을 연결할 수 있습니다.
    - 카테고리 정렬을 통해 효율적인 문의 처리를 할 수 있습니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d89f1ac6-0d99-4599-8dc1-de4379839ecc/Untitled.png)

- 회사 선정 후 직접 바로 전화 연결 기능
    - 고객은 따로 전화 키패드 입력 없이 연결을 할 수 있습니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/70b5783f-2460-4275-97a7-98b0f3f92cfa/Untitled.png)

- 불친절도에 따른 고객의 등급과 정보 확인 기능
    - 상담사는 상담을 하기 전 고객 정보를 미리 파악할 수 있고 고객의 성향, 과거의 기록에 따라 한 번에 어떤 성향의 고객인지 쉽게 파악이 가능합니다.

**상담원 페이지**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/06ce4176-2a66-46a7-9040-f0ee6d1eaa94/Untitled.png)

- 음성 사전 필터링 및 핵심 내용 요약 기능 제공
    - 고객이 음성 필터링 유/무를 선택하고 필터링 시 원본 음성에 대한 텍스트 블러처리가 됩니다.
    - 상담사가 고객의 부정적인 음성을 직접 마주하지 않고 핵심 내용만을 쉽게 파악할 수 있습니다.
    - 원본 내용을 파악하고 싶을 때는 상담원의 재량으로 블러를 해제할 수 있습니다.

### emoshield 개발 스택

- **ChatGPT 프롬프트**
    - ChatGPT API와 프롬프트 프로그래밍으로 문장에서 비속어를 파악하여 지우고 핵심 내용만을 제공하도록 학습
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b438c159-b927-433d-ae9c-6187b6f66ac3/Untitled.png)
    
- 아키텍쳐
    - WebRTC를 통한 실시간 음성 통화를 제공합니다.
    - STT API를 통해 음성을 텍스트로 변환하여 통화 내용을 실시간으로 필터링해 상담원에게 제공합니다.
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bcf1f426-f2cd-4e10-90f8-5b9452aa03a4/Untitled.png)
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2f2d180e-8777-4b37-8d33-90fe94296703/Untitled.png)
    
- **Infra**
    - AWS, 테라폼을 이용해 서비스를 배포했습니다.
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f35e995f-9b7d-4a04-a99e-07f76bad0af1/Untitled.png)
    

### 기대효과 및 결론

emoshield 서비스를 통해 감정노동자들의 감정노동 해소와 사회적 비용의 감소를 도모하고 있습니다.

- 감정노동 해소
    - 고객의 감정 대응에 대한 부분을 AI에게 위임하기 때문에 고객 민원 해소의 목적에만 집중이 가능합니다.
- 사회적 비용 감소
    - 감정노동자의 정신적 스트레스 처리를 도와 사회와 기업에서 상담원의 스트레스 처리를 위해 투자하는 사회적인 비용을 절감 가능합니다.
- 확장성
    - 기존 실시간 음성 통화 앱과 연동을 통해 더 신속한 음성 필터링 서비스
    - AI의 고객 모니터링을 이용한 업무 부담 감소 및 상담원 교육 비용 절감
    - AI의 상담원 모니터링을 이용한 직접적인 심리 치료 솔루션 제공

이를 통해 감정노동자의 스트레스를 해소하고 상담원 본인과 고객 더불어 사회의 긍정적인 영향을 주는 서비스, 감정 노동 방파제 emoshield 가 되었으면 좋겠습니다!
