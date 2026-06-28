<div align="center">

# EV3Team

### Patch Acquisition Game · 패치 획득 게임

**LEGO EV3 로봇 기반 최단경로 · 자유경로 패치 획득 게임 풀이**

<br>

![LEGO MINDSTORMS EV3](https://img.shields.io/badge/LEGO_MINDSTORMS_EV3-FFCB05?style=for-the-badge&logo=lego&logoColor=black)
![RobotC](https://img.shields.io/badge/RobotC-00599C?style=for-the-badge&logo=c&logoColor=white)

<sub>한양대학교 ERICA · 스마트융합공학부 스마트ICT융합전공 · 스마트센서와액츄에이터 기말 프로젝트</sub>

</div>

---

## 프로젝트 개요

> LEGO EV3 로봇으로 격자 구조의 맵에서 패치를 획득하며
> 최고 점수를 달성하는 것을 목표로 합니다.

두 가지 과제로 구성되며, 각각 **최단경로 알고리즘**과 **자유경로 최적화 전략**을 구현합니다.
컬러 센서로 패치를 인식하고, 자이로 센서 기반 포인트 턴으로 격자 위를 정밀 주행합니다.

---

## 과제 1 · 최단경로 패치 획득

**4×4 격자**에서 빨강·초록 패치가 임의 위치에 주어질 때, 출발점에서 도착점까지
모든 격자점을 탐색한 뒤 이동점으로 **최단경로 이동**하여 패치 위치를 출력하고,
이동점에서 출발점으로 복귀하며 패치를 획득해 최고 점수를 얻습니다.

| 채점 항목 | 점수 |
|:--|:--:|
| 빨간색 패치 | **+1** |
| 파란색 패치 | **−1** |

---

## 과제 2 · 자유경로 패치 획득

**5×4 격자**에서 모든 격자점을 탐색한 뒤, 이동점에서 출발점까지 **자유경로(상하좌우)** 로
이동하며 패치를 획득해 최고 점수를 얻습니다.

| 채점 항목 | 점수 |
|:--|:--:|
| 빨간색 패치 (처음 방문) | **+5** |
| 빨간색 패치 (재방문) | **−2** |
| 파란색 패치 (매 방문) | **−5** |
| 이동 패널티 (1칸당) | **−1** |

---

## 팀 구성

| 역할 | 이름 | 담당 업무 |
|:--:|:--:|:--|
| **PM** | 윤태웅 | 프로젝트 총괄 |
| **개발** | 박재형 | 주행 알고리즘 개발 |
| **개발** | 이현빈 | 주행 알고리즘 개발 |
| **발표** | 조민 | PPT 제작 · 발표 |
| **발표** | 전민석 | PPT 제작 · 발표 |

---

## 프로젝트 바로가기

<div align="center">

[![Repository](https://img.shields.io/badge/PatchAcquisitionGame-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EV3Team/PatchAcquisitionGame)
[![Web](https://img.shields.io/badge/프로젝트_웹페이지-Visit-2b5bfe?style=for-the-badge)](https://ev3team.github.io/PatchAcquisitionGame/)

</div>

> 과제별 풀이 코드(`solution.c`)와 발표 자료(PPT), 시연 영상은 저장소와 웹페이지에서 확인할 수 있습니다.

---

<div align="center">

**Contact** · 윤태웅 (PM) · [taewoong25@hanyang.ac.kr](mailto:taewoong25@hanyang.ac.kr)

<sub>© 2026 EV3Team · 한양대학교 ERICA</sub>

</div>
