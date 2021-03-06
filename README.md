# MasterFit.kr Web AppliCation

## CRM / CAD

[**MasterFit**](https://masterfit.kr/)은 대한민국 패션디자인 명장 이정구의 오랜 현장 경험치를 CAD화하여 제작된 맞춤 의류용 패턴 S/W입니다. [**MasterFit**](https://masterfit.kr/)의 지적 재산권은 이정구 명장, [**Goldfinger Ltd**](https://gftailor.co.kr/)에 있습니다.

****
# 1. 기능소개
## 1.1. CRM (고객 관리 프로그램)
### 1.1.1. 관리 대상 고객 데이터

    1. 맞춤 의복 주문 고객의 개인정보
    2. 고객의 치수
    3. 고객의 주문
    4. 고객의 주문에 적용된 의복 패턴
    5. 원단 업체
    6. 작업처
    7. 웹페이지 회원 정보

### 1.1.2 고객 데이터 간 연동
    고객의 주문 데이터에 패턴파일 정보와 치수 데이터를 저장하여 각 고객의 패턴 정보를 확인할 수 있습니다.
****
## 1.2. CAD
### 1.2.1. 패턴 생성 도구
    사용자가 직접 점과 선의 정보를 입력하여 원하는 의복의 패턴을 제작할 수 있는 툴을 제공합니다.
    DXF 파일로 변환 시 패턴 조각 별로 그룹을 지정할 수 있습니다.
    레이어를 설정하여 플로터 출력시 펜 지정이 가능합니다.
      
### 1.2.2. 고객 치수 패턴 적용
    만들어진 패턴 파일에 고객의 치수를 적용하여 브라우저에 출력합니다.
    치수가 적용된 패턴은 AWS S3 서버에 실시간으로 저장되어 조회 및 수정이 가능합니다.
### 1.2.3. 패턴 파일 변환
    생성된 패턴 파일은 각각 SVG, DXF 파일 포맷으로 변환이 가능합니다.
### 1.2.4. 플로터 출력
    치수가 적용된 패턴을 HPGL(Hewlett-Packard Graphics Language)로 변환하여 플로터로 출력할 수 있습니다. QT로 제작된 MasterFitFlotter 프로그램을 사용합니다.
    플로터의 펜 설정이 가능하여 패턴 조각이 커팅된 상태로 출력이 가능합니다.
### 1.2.5 점함수 기능 추가
    정교한 패턴 작성을 위한 점함수 기능 추가 완료.

---

![image1](https://user-images.githubusercontent.com/67298740/177034582-29c76945-1e08-438f-ad4b-4a2024c64281.jpg)  

![point_function_popup](https://user-images.githubusercontent.com/67298740/177034195-de51d3ae-21e2-4336-8e4f-bfd88362e887.png)  

![point_function](https://user-images.githubusercontent.com/67298740/177034203-579fec7f-a80a-4d31-b7bd-1afcb33cd66b.png)






