## 목차 

1. 소개
2. 자습서
   1. 미리 해야할 일 
      1. 조직코드 부여
      2. 설정
         1. 사용자 관리
         2. 클라우드 계정 관리
         3. 스택 템플릿 관리
         4. 일반 설정
   2. 스택 관리 (클러스터 관리)
      1. 특장점
      2. 모니터링
   3. 앱 서빙 (배포)
      1. 특장점
   4. 대시보드
      1. Pod 재기동 수
      2. CPU, Traffic, Memory
      3. 자원 사용량
      4. 스택



## 컨텐츠 

1. 소개

   1. 왜 TKS Cloud Serive 를 사용해야 할까요?

        - 고객에게 이런 pain points 가 잇음 

        - TKS Cloud Service는 그 문제를 이렇게 멋지게 해결해 줌



2. 자습서  - TKS Cloud Serive 를 사용하는 방법을 알아볼까요?

   1. 미리 해야할 일

      1. 제일 먼저 SKT의 영업사원을 통해 조직코드를 받으실 수 있어요.
      2. 조직의 관리자는 우리 조직에 맞게 TKS Cloud Service를 설정할 수 있어요.

      - 조직의 동료들이 TKS Cloud Service를 사용할 수 있게 사용자를 추가해 주세요.
        - 관리자는 사용자를  추가하고, 관리할 수 있어요.
        - 사용자가 요청에 따라 비밀번호를 초기화 해주실 수 있어요.

      - 고객님의 AWS 계정을 제어할 수 있도록 클라우드 계정을 만들어 주세요.
        - 안심하셔도 괜찮아요. 고객님의 AWS Secret 은 Assume role만 생성하고 즉시 폐기할게요. 

      - 클러스터를 쉽게 관리할 수 있도록 스택템플릿을 사용할 수 있어요.
        - 계속 다양화 해 나갈게요.

      - 동료들과 TKS 팀이 관리자님에게 연락할 수 있도록 일반 정보를 입력해 주세요. 

        

   2. 스택(클러스터)을  생성해 볼까요?

      - 몇 가지 정보 입력만으로 쉽게 스택을 만들 수 있어요.

      - 만들어진 스택의 상태를 확인해 볼까요?

      - 문제가 생기면 시스템 경고를 통해 즉시 알려드릴게요.

        

   3. 앱을 배포해 볼까요?

      - 이렇게 저렇게 앱 서빙 메뉴를 사용해서 배포해 주세요.
        - 몇 가지 정보 입력만으로 쉽게 배포할 수 있어요.

      - 아쉽게도 지금은 Spring 과 Spring Boot 앱만 배포할 수 있어요.
        다른 유형의 앱을 배포하시려면 TKS 팀에 문의해주세요. 검토 후 빠르게 기능을 추가해드릴게요.

        

   4. 우리 조직의 사용량과 자원의 상태를 한 눈에 확인할 수 있어요

      - Pod 재기동 수

      - CPU, Traffic, Memory

      - 자원 사용량

      - 스택
