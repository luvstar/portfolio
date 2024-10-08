
# 1. 시간은 금! 생산 효율 개선을 위한 QC 자동화 프로그램

#### 프로젝트 개요 및 소개

- 프로젝트 사용 기술 : C, C++, Visual Studio
- 프로젝트 기간 : 2024.04 ~ 2024.05 [2개월]
- 프로젝트 인원 : 2인
- 프로젝트 발주 기관 : (주)커미조아
- 프로젝트 진행 기관 : (주)커미조아
- 프로젝트 진행 내용 : 제품 출고를 위해 필수 과정인 QC 과정을 기존에는 수작업으로 진행하고 있었지만 자동화 프로그램을 개발하여 생산효율 개선, QC 신뢰도 증가를 이루었습니다.
- 소스 코드 : 보안 규정으로 인한 비공개
#### 프로젝트 내 역할

- QC Program 개발
- 프로그램을 사용하기 쉽게 설명해놓은 MANUAL 작성

#### 프로젝트 성과

- 수작업으로 진행 시 제품 1개당 약 20~30분 정도 소요되던 시간을 자동화 프로그램을 통해 소요시간 5분 내외로  감소

#### 프로젝트 진행 중 발생한 문제와 TroubleShooting

- 최초 Release 프로그램은 QC 시간이 10분 정도로 목표에 부합하지 못하는 문제가 있었습니다. 프로그램 속도 개선은 쉽지 않은 영역인 만큼 가장 오래 걸리는 알고리즘인 Analog calibration을 병렬처리와 다중 Thread 사용, Calibration 알고리즘 자체의 수정을 통해 목표 시간인 5분 내외로 소요시간을 줄일 수 있었습니다.


# 2. 세계를 무대로 만들기 위한 CE 인증 프로그램

#### 프로젝트 개요 및 소개

- 프로젝트 사용 기술 : C, C++, Visual Studio
- 프로젝트 기간 : 2024.07 ~ 2024.08 [2개월]
- 프로젝트 인원 : 1인
- 프로젝트 발주 기관 : (주)커미조아
- 프로젝트 진행 기관 : (주)커미조아
- 프로젝트 진행 내용 : 유럽 진출을 위해 필수적인 CE 인증을 위해 제품의 에이징 테스트 및 신뢰도 검사가 가능한 프로그램 개발
- 소스 코드 : 보안 규정으로 인한 비공개
#### 프로젝트 내 역할

- CE인증 Program 개발 및 CE인증 대행 업체에 배포

#### 프로젝트 성과

- CE 인증 성공 및 해당 인증을 기반으로 유럽 진출 가능. CE 인증을 기반으로 이탈리아 거래처 확보.

#### 프로젝트 진행 중 어려웠던 점과 해결법

- 한번에 약 40개의 EtherCAT Slave를 제어할 수 있는 프로그램을 만들다 보니 코드의 분량을 줄이고 프로그램을 최적화 시키는 작업을 많이 고민했습니다. 코드 분량을 줄이기 객체화를 적극 사용하고 기존에 사용하던 Library를 참고하여 CE 인증에서 사용할 수 있는 새로운 전용 Library를 만들어 최적화를 진행하였습니다.