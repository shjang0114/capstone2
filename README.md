# MEMORI 
컴퓨터 부품 비교 및 구매 안내 서비스

## 목차
#### [▶ 팀프로젝트 개요](#팀프로젝트-개요)   
#### [▶ 팀프로젝트 상세](#팀프로젝트-상세)   
#### [▶ 팀프로젝트 결과](#팀프로젝트-결과)

## 팀프로젝트 개요
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
- HTML, CSS, JavaScript, Bootstrap, JAVA, H2 Database, Apache Tomcat, Naver Open API, Spring Boot

## 팀프로젝트 상세
**[ 주요 기능 ]**
- 메인 화면: 컴퓨터 본체 내부를 미니멀리즘 기준으로 구성. 부품별 주요 정보 안내.
- 부품 목록: 네이버 쇼핑 API를 활용. 부품별 상품 정보 확인 및 관심 목록 저장.
- 관심 목록: 부품 목록에서 저장한 관심 부품 확인 및 구매처로 이동.
- 커뮤니티 게시판: 이용자들 간에 컴퓨터 부품과 관련된 정보 공유 가능.

## 팀프로젝트 결과
### ※ 메인 페이지
|<img src="https://github.com/user-attachments/assets/00803690-8bff-467a-9e5e-0a7140b9d2f1" />|<img src="https://github.com/user-attachments/assets/2d432d97-74df-4aab-a494-8fb9b091d310" width="1150" />|<img src="https://github.com/user-attachments/assets/4539726d-1e41-415f-b66a-91ab2dd67d26" />|
|:---:|:---:|:---:|
| 메인 페이지 | 컴퓨터 본체 | 미니멀리즘 |

- 화면 중앙에 일반적인 컴퓨터 본체를 미니멀리즘으로 표현한 UI를 배치하였습니다.
- 전체적인 디자인은 피트 몬드리안의 '빨강, 파랑, 노랑의 구성 II'를 참고하였습니다.
- 내부의 복잡한 구조를 추상화하여 직관적으로 디자인하였습니다.
- 주요 부품 이외의 장치들은 남은 공간에 추가로 배치하였습니다.
- 각 목록에 마우스를 올려둘 시, 부품에 대한 정보를 확인할 수 있습니다.

### ※ 부품 목록
|<img src="https://github.com/user-attachments/assets/6642a0ca-7055-44a3-b98a-73709c2d28bb" />|<img src="https://github.com/user-attachments/assets/296e9128-e4d8-450c-a6e2-0571c9cff75c" />|
|:---:|:---:|
| 부품 목록 1 | 부품 목록 2 |

- 네이버 쇼핑 API를 활용하여 구현하였으며, 부품별 상품 정보를 확인할 수 있습니다.
- 상단 네비게이션 바를 통해, 현재 목록 외에 다른 부품 목록으로 이동할 수 있습니다.
- 우측의 관심 버튼을 클릭 시, 해당 부품을 관심 목록에 저장할 수 있습니다.

### ※ 관심 목록
|<img src="https://github.com/user-attachments/assets/0fac5665-f8b0-48b1-ba6d-af372d53137d" />|<img src="https://github.com/user-attachments/assets/9c0273de-28ed-463d-9073-c51ca3e52104" />|
|:---:|:---:|
| 관심 목록 | 구매 사이트 |

- 부품 목록 화면에서 저장한 부품들을 확인할 수 있습니다.
- 우측의 구매 버튼을 클릭 시, 해당 부품을 구매할 수 있는 사이트로 이동할 수 있습니다.
- 좌측 삭제 버튼을 통해 해당 부품을 목록에서 삭제할 수 있습니다.

### ※ 커뮤니티 게시판
|<img src="https://github.com/user-attachments/assets/760d1a1f-e132-4810-aeee-e002e88b08dd" />|<img src="https://github.com/user-attachments/assets/1c5788f9-a341-43fd-8cbf-c59415ab6c93" />|
|:---:|:---:|
| 게시판 목록 | 게시글 작성 |

- 게시글과 댓글을 작성할 수 있는 커뮤니티 게시판입니다.
- 사이트에서 제공하는 정보 이외에 사용자들 간에 컴퓨터와 관련된 정보를 공유할 수 있습니다.

### ※ 로그인 및 회원가입
|<img src="https://github.com/user-attachments/assets/c0a608e0-cfdf-447c-8f5c-2132657b8e9c" />|<img src="https://github.com/user-attachments/assets/25834ad4-92fb-41f4-91f7-3165f9043503" />|<img src="https://github.com/user-attachments/assets/7b20f035-73e3-4000-b6d6-be421e059cf5" />|
|:---:|:---:|:---:|
| 로그인 | 회원가입 | 마이페이지 |

- 로그인 및 회원가입 페이지입니다.
- 로그인 후 관심 목록 및 마이페이지 기능을 사용할 수 있습니다.
- 마이페이지를 통해 로그인한 계정의 비밀번호를 변경할 수 있습니다.

### ※ 고객센터
|<img src="https://github.com/user-attachments/assets/70b0c819-2929-4c08-a276-1e40e2f5632b" />|<img src="https://github.com/user-attachments/assets/ed45fa0a-ed94-4931-87bd-e410dbfbf62e" />|
|:---:|:---:|
| 이용 관련 설명 1 | 이용 관련 설명 2 |

- 고객센터 페이지입니다.
- 사이트 이용과 관련된 정보들을 확인할 수 있습니다.
