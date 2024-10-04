# MEMORI 
컴퓨터 부품 비교 및 구매 안내 서비스

## 목차
#### ▶ 팀프로젝트 개요   
#### ▶ 팀프로젝트 상세   
#### ▶ 팀프로젝트 결과

## ▶ 팀프로젝트 개요
**[ 개발 기간 ]**   
- 2023.10.25 ~ 2023.11.30

**[ 개발 인원 ]**
- 총 7인 <팀장>

**[ 개발 동기 ]**
- PC의 필요성은 과거부터 꾸준히 증가하였으며, 현재 가정마다 PC는 필수적으로 보유하고 있는 편입니다.
- PC의 성능 요구사항은 계속 증가하는 추세이고, 이에 따라 PC 및 관련 부품 구매도 지속적으로 필요합니다.
- 기존 부품 사이트들은 구매가 필요한 소비자들에게 복잡하며 일정 수준의 사전 지식을 요구하고 있습니다.
- **따라서 보다 직관적인 인터페이스를 제공하고,**
- **구매에 도움을 줄 수 있는 정보들을 안내하여,**
- **소비자들이 접근하기 용이한 컴퓨터 부품 사이트를 구현하였습니다.**

**[ 맡은 역할 ]**
- 프로젝트 총괄, 데이터베이스 설계, 메인 페이지 및 관심 목록 설계 및 구현

**[ 개발 언어 및 도구 ]**
- HTML, CSS, JavaScript, Bootstrap, JAVA, H2 Database, Apache Tomcat, Spring Boot, IntelliJ IDEA

## ▶ 팀프로젝트 상세
- 메인 화면: 컴퓨터 본체 내부를 미니멀리즘 하에 직관적으로 구성. 부품별 주요 정보 안내 가능.
- 부품 목록: 네이버 쇼핑 API를 활용하여 부품별 상품 정보 확인 및 구매처로 이동 가능.
- 관심 목록: 관심있는 부품이 있는 경우 해당 부품을 관심 목록에 저장 가능.
- 커뮤니티 게시판: 이용자들 간에 컴퓨터 부품과 관련된 정보 공유 가능.

## ▶ 팀프로젝트 결과
### ※ 메인 페이지
<img src="https://github.com/user-attachments/assets/00803690-8bff-467a-9e5e-0a7140b9d2f1"  width="50%" />

- 화면 중앙 UI는 일반적인 컴퓨터 본체 내부의 복잡한 구조를 직관적으로 추상화 하여 디자인하였습니다.
- 남는 공간에는 본체 외의  부품 목록을 배치하였습니다.
- 또한 각 목록에 마우스를 올려두면 부품에 대한 정보들을 확인할 수 있게 구현하였습니다.

### ※ 부품 목록
<img src="https://github.com/user-attachments/assets/6642a0ca-7055-44a3-b98a-73709c2d28bb"  width="50%" />

- 네이버 쇼핑 API를 활용해 구현하였으며, 부품별 기본 정보들을 확인할 수 있습니다.
- 우측 관심 버튼을 클릭 시, 해당 부품을 관심 목록에 저장하여 확인할 수 있습니다.

### ※ 관심 목록
<img src="https://github.com/user-attachments/assets/0fac5665-f8b0-48b1-ba6d-af372d53137d"  width="48%" />
<img src="https://github.com/user-attachments/assets/9c0273de-28ed-463d-9073-c51ca3e52104"  width="48%" />

- 부품 목록 화면에서 저장한 부품들을 확인할 수 있습니다.
- 우측 구매 버튼을 클릭 시, 해당 부품을 구매할 수 있는 사이트로 이동할 수 있습니다.
- 또한 좌측 삭제 버튼을 통해 해당 부품을 목록에서 삭제할 수 있습니다.

### ※ 커뮤니티 게시판
<img src="https://github.com/user-attachments/assets/1c5788f9-a341-43fd-8cbf-c59415ab6c93"  width="48%" />
<img src="https://github.com/user-attachments/assets/760d1a1f-e132-4810-aeee-e002e88b08dd"  width="48%" />

- 게시글과 댓글을 작성할 수 있는 커뮤니티 게시판입니다.
- 사이트에서 제공하는 정보 이외에 사용자들 간에 컴퓨터와 관련된 정보를 공유할 수 있습니다.
