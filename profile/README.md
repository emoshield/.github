# emoshield
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=aws&logoColor=white"> <img src="https://img.shields.io/badge/terraform-232F3E?style=for-the-badge&logo=terraform&logoColor=white">

## 개요

![image](https://github.com/emoshield/.github/assets/33739448/aece9105-9f71-4886-be11-6b51e5a72be3)

감정노동자를 위한 Chat GPT활용 음성 필터링 서비스 emoshield입니다.  
[![emoshield](https://static.vecteezy.com/system/resources/previews/018/930/572/original/youtube-logo-youtube-icon-transparent-free-png.png){: width="20%" height="20%"}](https://youtu.be/_7KutXPRg-g)

### 배경

emoshield는 최근 감정노동자가 받는 심리적 스트레스의 심각성에 착안하여 이러한 문제를 해결하고자 시작된 프로젝트입니다.

![image](https://github.com/emoshield/.github/assets/33739448/fffcdcbf-4722-4891-bf69-06bc214303db)

감정노동자 중 상담사의 불안한 심리와 스트레스는 상담사 자신과 주변에 큰 영향을 끼칠 수 있습니다.

- **상담사**
    - 감정 노동으로 인해 상담사의 감정적 부조화를 가져오고 스트레스를 유발합니다 → **마음이 지치고 불안해짐**
- **고객**
    - 상담사의 불안한 정서가 그대로 입을 통해 고객과의 대화에 투영됩니다 → **고객 만족도 하락**
- **회사**
    - 상담사의 대응은 콜센터의 강담 품질과 직결되며 개인을 넘어 회사의 문제가 될 수 있습니다. → **장기적인 회사의 손해**

![image](https://github.com/emoshield/.github/assets/33739448/40f31f7c-7478-4ad9-a0bf-c4e2c7ae6a7d)

기존에도 상담사를 보호하기 위한 제도는 있지만 이러한 제도가 감정노동자를 보호하는데에 실효성이 있는지 검증되지 않고 있고 여러 요인을 고려했을 때 대처 매뉴얼을 통해 고객에게 강경 대응하는 것은 현실적으로 어렵다는 문제가 있었습니다.

### emoshield
💡 **감정노동자가 실제로 스트레스 받을 일 없이 통화를 할 수는 없을까?**  

이러한 문제점에서 착안하여 강한 감정의 전달에 방파제 역할을 해주는 서비스 **emoshield**를 만들게 되었습니다.

1. 고객의 두서없는 말, 욕설 등을 필터링하여 **상담원이 핵심 내용만 바로 파악**할 수 있다.
2. 텍스트로 추출한 문장에 있는 비속어의 **블러 처리 선택 기능**을 제공한다.
- **I.A**
    
    ![image](https://github.com/emoshield/.github/assets/33739448/236546dd-a2fd-41fa-af59-1b2ed2312444)

    

**고객 페이지**

![image](https://github.com/emoshield/.github/assets/33739448/c536c10c-ffd1-4c23-878a-0c2145b1ff9e)


- 카테고리 별 회사 목록 확인 및 연결 서비스
    - 고객은 추가적인 탐색 없이 한번에 원하는 회사에 대한 정보를 편리하게 얻을 수 있습니다.
- 즐겨 찾는 회사 등록 기능
    - 자주 상담하는 회사를 따로 모아 언제나 쉽고 편리하게 상담을 연결할 수 있습니다.
    - 카테고리 정렬을 통해 효율적인 문의 처리를 할 수 있습니다.

![image](https://github.com/emoshield/.github/assets/33739448/bec6ef5b-70b2-4f4e-a6f4-b73594e9cad8)


- 회사 선정 후 직접 바로 전화 연결 기능
    - 고객은 따로 전화 키패드 입력 없이 연결을 할 수 있습니다.

![image](https://github.com/emoshield/.github/assets/33739448/91851d5c-2b7f-4b27-80e8-54a49f7421ca)


- 불친절도에 따른 고객의 등급과 정보 확인 기능
    - 상담사는 상담을 하기 전 고객 정보를 미리 파악할 수 있고 고객의 성향, 과거의 기록에 따라 한 번에 어떤 성향의 고객인지 쉽게 파악이 가능합니다.

**상담원 페이지**

![image](https://github.com/emoshield/.github/assets/33739448/a3e78716-572d-4955-9df3-96c26951c837)

- 음성 사전 필터링 및 핵심 내용 요약 기능 제공
    - 고객이 음성 필터링 유/무를 선택하고 필터링 시 원본 음성에 대한 텍스트 블러처리가 됩니다.
    - 상담사가 고객의 부정적인 음성을 직접 마주하지 않고 핵심 내용만을 쉽게 파악할 수 있습니다.
    - 원본 내용을 파악하고 싶을 때는 상담원의 재량으로 블러를 해제할 수 있습니다.

### emoshield 개발 스택

- **ChatGPT 프롬프트**
    - ChatGPT API와 프롬프트 프로그래밍으로 문장에서 비속어를 파악하여 지우고 핵심 내용만을 제공하도록 학습
    
    ![image](https://github.com/emoshield/.github/assets/33739448/ac0458e1-6da9-450e-bd0a-8f78c1f3da87)

    
- **아키텍쳐**
    - WebRTC를 통한 실시간 음성 통화를 제공합니다.
    - STT API를 통해 음성을 텍스트로 변환하여 통화 내용을 실시간으로 필터링해 상담원에게 제공합니다.
    
    ![image](https://github.com/emoshield/.github/assets/33739448/44e275a3-d31b-448e-bb8a-aaca2d8135fd)

    ![image](https://github.com/emoshield/.github/assets/33739448/7c75b7dd-0254-44f8-90e8-44b858e6c042)
    
- **Infra**
    - AWS, 테라폼을 이용해 서비스를 배포했습니다.
    
    ![image](https://github.com/emoshield/.github/assets/33739448/44ad10e1-6f37-40b1-b77e-014f275b33ff)

    

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
