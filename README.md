# 양자컴퓨팅 이론 및 실습 (12시간 집중 부트캠프) - Day 3

본 저장소는 **[양자컴퓨팅 이론 및 실습]** 4주(총 12시간) 집중 강좌 중 **3주차 (Day 3: Qiskit & Grover 탐색 알고리즘)** 공식 학생용 실습 및 배포 저장소입니다.  
강의 슬라이드, Day 3 렉처노트 및 실습 파일(Jupyter Notebook), 원클릭 구동 스크립트가 포함되어 있습니다.

- **강사**: 서상협 ((주)큐렌스 / QRens)
- **주제**: 3주차 - Qiskit & 양자 알고리즘 기초 (2-qubit Grover 탐색)
- **사전 요구사항**: 기본적인 파이썬 문법 이해 (파이썬이 설치되어 있지 않아도 아래 원클릭 실행기로 자동 세팅됩니다!)

---

## 📥 저장소 다운로드

### 방법 1. Git 사용 (추천)
```bash
git clone https://github.com/saibie/quantum-computing-bootcamp-2026-day3.git
cd quantum-computing-bootcamp-2026-day3
```

### 방법 2. ZIP 파일 다운로드
1. 페이지 우측 상단의 **`Code`** -> **`Download ZIP`** 클릭
2. 다운로드한 파일의 **압축을 해제**한 후 해당 폴더로 진입

---

## 🚀 3초 만에 실습 환경 시작하기

### 🪟 Windows 사용자
1. 폴더 내의 **`start_windows.bat`** 파일을 더블 클릭하여 실행합니다.
2. 검은색 터미널 창에서 자동 환경 구성 후 브라우저에 **Jupyter Lab**이 실행됩니다.

### 🍎 macOS 및 Linux 사용자
1. 터미널에서 아래 명령어 실행:
   ```bash
   chmod +x start_mac.sh
   ./start_mac.sh
   ```

---

## 📂 폴더 구조 안내

```text
├── docs/                               # 강의 교재 및 참고 문서 (PDF)
│   ├── day3_algorithms.pdf             # Day 3 강의 슬라이드 (양자 알고리즘과 Grover 탐색)
│   └── lecture_notes_day3.pdf          # Day 3 핵심 수식/원리 집중 렉처노트
│
├── hands_on/                           # 실습 코드
│   └── day3_qiskit_grover.ipynb        # [Day 3 실습] Phase Oracle, Diffusion, 2-qubit Grover 회로
│
├── start_windows.bat                   # Windows 원클릭 실습 실행기
├── start_mac.sh                        # Mac/Linux 원클릭 실습 실행기
├── pyproject.toml                      # 프로젝트 메타데이터 및 의존성 정의
└── uv.lock                             # 라이브러리 버전 고정 락파일
```

---

## 💡 Day 3 핵심 학습 내용
- **Session 1**: 비정렬 검색 한계($O(N)$ vs $O(\sqrt{N})$), Phase Oracle과 Diffusion 연산자, $4 \times 4$ 행렬 소거 증명
- **Session 2**: 2차원 부분공간 기하학적 회전($2\theta=60^\circ$), Qiskit Little-Endian 규칙, 2-qubit Grover 회로 조립 및 100% 검출 전수 검증

---

## 📬 문의 및 지원
- 저작권: 본 자료의 저작권은 **(주)큐렌스** 및 강사 **서상협**에게 있습니다. 교육 목적 외 무단 배포 및 상업적 이용을 금합니다.
