# resource-management-project

Using JavaScript in 2024  
📌: KOSA 전자정부 표준 프레임워크 기반 공공프로젝트 개발 전문가 양성과정 - 자재/창고 재고 관리 시스템

[![Last Commit](https://img.shields.io/github/last-commit/221B0825/ResourceManagementProject)](https://github.com/221B0825/ResourceManagementProject/commits/main)

## 🚀 Introduction
KOSA 과정 중 팀원과 함께 진행한 자재/창고 재고 관리 프로젝트입니다. 여러 창고의 자재 입출고 현황을 관리하고, 창고별 적재율에 따른 상태(안전/중간/위험)를 시각화하며, 입출고 이력과 순위를 조회할 수 있는 관리자용 대시보드를 Vanilla JavaScript로 구현했습니다.

---

## ✨ Features

* 📦 **자재 관리 (Material)**
  자재 등록 및 정보 관리, 커스텀 슬라이더/숫자 입력을 통한 수량·비율 설정 (`pages/material`)

* 🏭 **창고 현황 관리 (Warehouse Status)**
  창고별 현재 적재량을 실시간 계산하여 적재율에 따라 안전/중간/위험 상태로 분류, 차트 및 테이블로 시각화 (`pages/warehouse/warehouseStatus`)

* ⚙️ **창고 설정 (Warehouse Setting)**
  신규 창고 등록 및 창고 정보(최대 적재량 등) 설정 (`pages/warehouse/warehouseSetting`)

* 📊 **재고 현황 & 관리 (Stock)**
  전체 재고 현황 조회 및 재고 관리 화면 제공 (`pages/stock/stockStatus`, `pages/stock/stockManagement`)

* 🔍 **자재 검색 (Retrieval)**
  조건에 맞는 자재 데이터를 검색하고 목록으로 조회 (`pages/retrieval`)

* 🏆 **입출고 순위 (Ranking)**
  자재별 입출고 데이터를 집계하여 순위 테이블로 표시 (`pages/ranking`)

* 🕓 **입출고 이력 (History)**
  일자별 입출고 이력 조회 및 순위 데이터 생성 (`pages/history`, `pages/stock/stockHistory`)

* 🗂️ **보관 현황 (Storage)**
  창고 내 보관 중인 자재 목록 및 입출고(`out.json`) 데이터 관리 (`pages/storage`)

* 🧩 **공통 컴포넌트**
  헤더/네비게이션 바를 별도 HTML로 분리 후 `fetch`로 동적 로드하여 재사용 (`components/`)

---

## 📂 Folder Structure

```plaintext
resource-management-project/
└── ResourceManagementProject/
    ├── src/
    │   └── test.java
    └── WebContent/
        ├── index.html
        ├── app.js
        ├── components/          # 공통 헤더/네비게이션 (동적 로드)
        ├── data/                 # 자재/창고 JSON 목업 데이터
        └── pages/
            ├── material/          # 자재 관리
            ├── warehouse/
            │   ├── warehouseStatus/   # 창고 적재 현황
            │   └── warehouseSetting/  # 창고 등록/설정
            ├── stock/
            │   ├── stockStatus/       # 재고 현황
            │   ├── stockManagement/   # 재고 관리
            │   └── stockHistory/      # 입출고 이력
            ├── retrieval/            # 자재 검색
            ├── ranking/               # 입출고 순위
            ├── history/                # 입출고 이력
            └── storage/                 # 보관 현황
```

---

## 🛠️ Built With

* **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS), Axios
* **IDE**: Eclipse (Dynamic Web Project)

---

## 👥 Team

* [221B0825](https://github.com/221B0825)
* [YoungJinKim](https://github.com/youngjin-korea)
* [Seong_gu](https://github.com/SG1515)

---

## 📧 Contact

* **Name**: Eunseo Yu
* **E-mail**: [eunseoyu0825@gmail.com](mailto:eunseoyu0825@gmail.com)
* **GitHub**: [221B0825](https://github.com/221B0825)
