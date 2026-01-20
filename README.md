# Test-Hardware-Ver-Manage
하드웨어 버전관리 테스트용 리파지토리
# Hardware Version Management Repository

## 📌 목적 (Purpose)
본 저장소는 하드웨어 개발 과정에서 발생하는 각종 설계 산출물에 대해  
체계적인 **버전 관리 및 변경 이력 추적**을 목적으로 운영한다.

설계 변경, 검증 결과, 4M 변경 사항 등을 시간 흐름에 따라 관리하여  
- 설계 의도 보존
- 변경 사유 명확화
- 재현성 및 추적성 확보
를 목표로 한다.

---

## 🧾 버전 관리 대상 (Version Controlled Items)

### 1️⃣ 설계 파일 (Design Files)
- 사양서&고객도면
- 회로도 (Schematic)
- PCB 설계 데이터 (CAD)
- BOM (Bill of Materials)
- Gerber / NC Drill
- Artwork 자료
- 회로물 관련 기구물 3D 모델 (STEP, IGES 등)

---

### 2️⃣ 검증 및 테스트 문서 (Test & Validation)
- 기능 시험 결과
- 광학 시험 결과
- 신뢰성 시험 자료
  - 온도 / 습도 / 진동
  - 수명 시험
- 전기적 특성 측정 데이터
- 시험 성적서 및 측정 로그

---

### 3️⃣ 변경 관리 문서 (Change Management)
- 4M 변경 문서
  - Man / Machine / Material / Method
- 설계 변경 이력
- 원인 분석 및 조치 내역
- 고객 요구사항 반영 내역

---

## 📁 저장소 구조 (Repository Structure)
/design
├─ schematic
├─ pcb
├─ bom
├─ gerber
├─ artwork
└─ 2d&3d_model

/test
├─ functional
├─ reliability
└─ measurement

/change_management
├─ 4M
├─ design_change
└─ issue_log

/docs
└─ reference

---

## 🔁 버전 관리 원칙 (Versioning Policy)
- 모든 변경 사항은 **Commit 단위로 기록**
- 변경 시 반드시 변경 사유를 Commit Message에 명시
- 주요 설계 변경 시 Tag 또는 Release로 버전 구분
  - 예: `HW_V1.0`, `HW_V1.1_ECO`

---

## 🚧 현재 상태 (Current Status)
- 하드웨어 설계 자료 정리 중
- 기존 산출물 GitHub 구조에 맞게 이관 중

---

## 📝 참고 사항 (Notes)
- 본 저장소는 내부 R&D 기준에 따른 하드웨어 형상 관리 목적의 저장소이다.
- 산출물은 개발 단계별로 순차 업데이트된다.

