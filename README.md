# 🛠️ ManiToOne Admin Service (Refactoring)

> 기존 **ManiToOne** 프로젝트의 관리자(Admin) 기능을 분리하여 **Clean Code** 원칙을 적용하고, 최신 기술 스택으로 재구축한 리팩토링 프로젝트입니다.

## 📌 Project Overview
이 프로젝트는 기존 [ManiToOne(Original Repo)](https://github.com/kkb00714/ManiToOne) 프로젝트에서 **Admin(관리자)** 도메인만 분리하여 독립적인 서비스로 구축한 결과물입니다.
기존 코드의 복잡도를 낮추고 유지보수성을 높이기 위해 **전면적인 리팩토링**을 진행했습니다.

### 🎯 핵심 리팩토링 목표 (Key Objectives)
- **Architecture Separation:** 기존 프로젝트에 섞여 있던 사용자/관리자 로직을 완전히 분리
- **Clean Code & Refactoring:**
    - 불명확한 메서드명 및 변수명 개선 (Naming Convention)
    - 중복 코드 제거 및 객체 지향적 설계 적용
    - 가독성 향상을 위한 코드 구조 개선
- **Tech Stack Upgrade:**
    - Spring Boot 2.x? → **3.5.9** (Latest)
    - Java 8/11 → **Java 17 (LTS)**

<br>

## 🛠 Tech Stack

### Environment
| Category | Technology | Version |
| --- | --- | --- |
| **Language** | Java | **17 (LTS)** |
| **Framework** | Spring Boot | **3.5.9** |
| **Build Tool** | Gradle | Groovy |
| **Server** | Embedded Tomcat | - |

### Development
- **Template Engine:** Thymeleaf
- **IDE:** IntelliJ IDEA
- **VCS:** Git / GitHub

<br>

## 🚀 Getting Started

이 프로젝트는 **Java 17** 이상의 환경이 필요합니다.