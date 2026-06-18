<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=230&section=header&text=Jiwoo%20Park&fontSize=50&fontAlignY=35&desc=Computer%20Vision%20%7C%20AI%20Engineer&descSize=20&descAlignY=55&animation=fadeIn&fontColor=ffffff)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jiwoo1105)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:psskej00@gmail.com)

</div>

---

## 👋 About Me

**Computer Vision**과 **AI**를 연구하는 엔지니어입니다. 현재 **[AIV Lab](https://aivlab.pages.dev/)** 에서 **3D Pose Estimation**과 **Computer Vision** 연구를 수행하고 있으며, 영상 속 움직임과 상태를 **정량적인 데이터로 변환하여 분석**하는 문제에 관심을 가지고 있습니다.

특히 단순히 객체를 탐지하거나 자세를 추정하는 것을 넘어, 영상으로부터 **의미 있는 정보를 추출**하고 이를 실제 **의사결정에 활용할 수 있는 형태로 해석**하는 연구를 지향하고 있습니다.

이를 위해 **단일 카메라 기반 3D Human Pose Estimation**, 동작 분석, 객체 탐지 등 다양한 Computer Vision 문제를 다루고 있으며, **축구 드리블 동작 자동 평가 시스템**과 **YOLO 기반 객체 탐지 파이프라인** 구축 프로젝트를 수행한 경험이 있습니다.

또한 **Redis**와 **Kafka**를 활용한 대규모 티켓팅 시스템을 설계·개발하여 실제 **6,000명 이상의 사용자**가 이용한 서비스를 운영했습니다. AI 연구뿐 아니라 **실제 서비스 환경에서 안정적으로 동작하는 시스템**을 설계하고 구현하는 역량도 함께 갖추고 있습니다.

궁극적으로는 영상으로부터 얻은 정보를 **실제 가치 있는 의사결정으로 연결하는 AI 엔지니어**를 목표로 하며, Computer Vision 연구와 서비스 개발을 아우르는 문제 해결에 지속적으로 도전하고 있습니다.

<table>
<tr>
<td valign="top" width="50%">

### 🎓 Education
- **단국대학교 (Dankook University)**
- 소프트웨어학과 학사 과정
- 2021.03 ~ 현재

</td>
<td valign="top" width="50%">

### 🔬 Research
- **[AIV Lab](https://aivlab.pages.dev/)** — 학부 연구생
- Advisor: **[Boeun Kim](https://aivlab.pages.dev/faculty)**
- 2025.09 ~ 현재
- Area: **Computer Vision, AI, 3D Pose Estimation**

</td>
</tr>
</table>

---

## 🚀 Research Projects & Activities
- **다개체 상호작용 환경에서의 개인화된 관계적 모션 생성 연구** — NRF
    - 여러 사람이 상호작용하는 장면에서 개인별 특성을 반영한 모션 생성 연구
    - 한국연구재단(NRF) 지원 과제 참여
- **단안 영상 기반 축구 드리블 동작 분석 시스템**
    - Mediapipe, SAM2, Depth Anything V2 기반 자세 평가 파이프라인 개발
    - 공 터치 자동 감지 및 어깨/골반 회전각, 헤드업 각도 정량 분석

## 📂 Main Projects

| 프로젝트 | 기간 | 설명 | 기술 | 성과 / 링크 |
|---|---|---|---|---|
| **Dan Zzan (단짠)** | 2025.12 – 2026.05 | 총학생회와 협업하여 **실제 축제에서 운영**한 티켓팅·공연·부스·공지 통합 서비스 <br> **Redis + Lua Script 선착순 티켓팅**, **JWT 학번 인증** 개발 <br> ![대학최초](https://img.shields.io/badge/대학_최초_네이버_페이스사인_도입-04c75b?style=flat-square) | Spring Boot, Redis, Kafka, MySQL, React, TypeScript, NHN Cloud | **실 운영**: 동시접속 4,500명, 3,500장 1분 매진, 중복발급 ZERO <br> **부하 테스트**: k6 10,000VU 통과 <br> [GitHub](https://github.com/DKU-Dan-Zzan) |
| **넙치 질병 조기 탐지 시스템** | 2026.03 – 2026.06 | **YOLO26 Fine-tuning** 기반 3-Stage 파이프라인 (탐지→분류→병변) <br> 7종 질병 증상 자동 분류 + 위험도 알림 시스템 <br> AIHub 넙치 질병 데이터 **48,000장** 학습 | Python, YOLO26, PyTorch, OpenCV, Flutter, FastAPI | Det mAP50: 0.445, Cls Acc: 83.99% <br> 7클래스 증상 분류 + 질병 대응 가이드 자동 생성 <br> [GitHub](https://github.com/jiwoo1105/fish-disease-detection) |
| **축구 드리블 동작 분석** | 2025.11 – 2026.06 | **단안 카메라 영상** 기반 축구 드리블 자세 정량 평가 시스템 <br> **공 터치 자동 감지** 및 어깨/골반 회전각, 헤드업 각도 분석 | Python, Mediapipe, SAM2, YOLOv8, OpenCV | 단일 카메라 영상만으로 드리블 자세 정량 평가 자동화 <br> [GitHub](https://github.com/jiwoo1105/soccer_motion_analysis) |
| **KNOO-B** | 2025.05 – 2025.06 | **감정 분석 기반** 영화/도서 추천 서비스 <br> 감정 분석 API 연동 및 **유클리드 거리 기반 메타데이터 매칭** 시스템 개발 | Python, PySide2, Hugging Face, Matplotlib | 오픈소스SW개발 <br> [GitHub](https://github.com/jiwoo1105/DKU_Opensource_knoo-B) |

## 🛠 Skills
### AI / Vision
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-F04D2F?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### Development & Tools
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Collaboration
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

<div align="center">

![Jiwoo's GitHub stats](https://github-readme-stats.vercel.app/api?username=jiwoo1105&show_icons=true&theme=transparent&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jiwoo1105&layout=compact&theme=transparent&hide_border=true)

</div>
