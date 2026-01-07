# Ahoj, já jsem [Krematos] 👋

Jsem vývojář, kterého baví  webové aplikace a jejich zabezpečení.

---

### 💻 Co používám

<details>
  <summary><strong>🚀 Tech Stack</strong></summary>
  <br>
  
  Jsem fanoušek moderních technologií. Aktuálně pracuji s:
  
  * **Jazyky:** Java, JavaScript
  * **Backend:** <img alt="Java" src="https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> <img alt="Spring Boot" src="https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" /> <img alt="PostgreSQL" src="https://img.shields.io/badge/-PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
   * **Frontend:** <img alt="html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" /> <img alt="Javascript" src="https://img.shields.io/badge/-javascript-f7df1c?style=flat-square&logo=javascript&logoColor=black" />
  <img alt="Bootstrap" src="https://img.shields.io/badge/-bootstrap-7953b3?style=flat-square&logo=javascript&logoColor=white" />  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />  <img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />

  * **Tools:**  <img alt="IntelliJ IDEA" src="https://img.shields.io/badge/-IntelliJ_IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white" /> <img alt="Docker" src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img alt="Postman" src="https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" /> <img alt="Maven" src="https://img.shields.io/badge/-Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white" /> <img alt="Google Gemini" src="https://img.shields.io/badge/-Gemini-8E75B2?style=flat-square&logo=google-gemini&logoColor=white" />

  
  > *"Rád se učím nové věci a experimentuji s open-source projekty. Momentálně se učím Springboot 4.0.0 a jeho nové vychytávky. Velmi rád poslouchám hudbu u vývoje, pokud jsi na tom podobně hit me up with your playlist. :D"*
  
</details>

## 🌟 Hlavní projekty

### 1. [Eshop](https://github.com/Krematos/E-shop2.0)
Ahoj! Vítejte v mém full-stack e-commerce projektu E-shop2.0. Tento projekt je kompletní online obchod, který demonstruje moderní webové vývojové praktiky. Backend je postavený na Spring Bootu s REST API, frontend na Reactu a vše je zabalené do Dockeru pro snadný deployment.

### [Demo](https://eshop-one-navy.vercel.app) - zde si můžete prohlédnout frontend, pokuď máte vercel účet
<details>
<summary><strong>Přihlašovací údaje</strong></summary>
  <br>
  demo@eshop.cz <br>
  demo123
</details>

#### ✨ Klíčové funkce
* 🔐 **Bezpečnost:** JWT autentizace, Role-based přístup (User/Admin), BCrypt šifrování.
* ⚡ **Výkon:** Caching přes Caffeine, asynchronní zpracování dat.
* 📧 **Notifikace:** Asynchronní odesílání e-mailů (Thymeleaf šablony).
* 🛒 **Správa:** Kompletní CRUD pro produkty a objednávky, správa uživatelů.
* 🎨 **Frontend:** Moderní UI v React 19 + TailwindCSS, plně responsivní.

#### 🛠️ Použité technologie

| Backend | Frontend | Data & Infra | Testování |
| :--- | :--- | :--- | :--- |
| ![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) | ![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) | ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white) |
| ![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | ![Mockito](https://img.shields.io/badge/Mockito-000000?style=flat-square&logo=mockito&logoColor=white) |
| ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring-security&logoColor=white) | ![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) | |
| ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white) | ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white) | | |

> **Další nástroje:** Lombok, MapStruct, Caffeine Cache


### 2. [Integrační Middleware](https://github.com/Krematos/ApiConnector)
je reaktivní aplikace postavená na Spring Boot 3.5.8 s využitím stacku WebFlux. Slouží jako prostředník mezi interními systémy a externími API, zajišťuje robustní komunikaci s automatickým retry mechanismem, fallback logikou přes RabbitMQ a auditním logováním do databáze.

* **Stack:** Java 21, Spring WebFlux, RabbitMQ, PostgreSQL (R2DBC), Docker.
* **Klíčové vlastnosti:**
    * ⚡ **Non-blocking I/O:** Zvládá vysokou zátěž s minimem vláken.
    * 🔄 **Smart Retry:** Exponenciální opakování při výpadku externí služby.
    * 📬 **Fallback:** Při selhání API odklání požadavky do RabbitMQ fronty pro pozdější zpracování.
    * 🔍 **Audit:** Kompletní logování životního cyklu transakce.

#### 🛠️ Použité technologie

| Core & Security | Data & Messaging | Infra & Monitoring | Testing & Tools |
| :--- | :--- | :--- | :--- |
| ![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL_15-316192?style=flat-square&logo=postgresql&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | ![Testcontainers](https://img.shields.io/badge/Testcontainers-9B4F96?style=flat-square&logo=testcontainers&logoColor=white) |
| ![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) | ![R2DBC](https://img.shields.io/badge/Spring_Data_R2DBC-6DB33F?style=flat-square&logo=spring&logoColor=white) | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) | ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white) |
| ![WebFlux](https://img.shields.io/badge/Spring_WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white) | ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) | ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) | ![Mockito](https://img.shields.io/badge/Mockito-000000?style=flat-square&logo=mockito&logoColor=white) |
| ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring-security&logoColor=white) | ![ShedLock](https://img.shields.io/badge/ShedLock-555555?style=flat-square&logo=lock&logoColor=white) | ![OpenAPI](https://img.shields.io/badge/Swagger_UI-85EA2D?style=flat-square&logo=swagger&logoColor=black) | ![Lombok](https://img.shields.io/badge/Lombok-BC0230?style=flat-square&logo=lombok&logoColor=white) |

> *"Demonstrace reaktivního programování a návrhových vzorů pro odolné distribuované systémy."*

### 3. [Kod pro Dobro](https://github.com/Krematos/KodProDobro) (ve vývoji)
je webová platforma navržená k propojení studentů informatiky a designu s českými neziskovými organizacemi. Cílem je umožnit studentům získat praxi na reálných projektech (Tech for Good) a zároveň pomoci neziskovému sektoru s digitalizací.

---

<details>
  <summary>📂 <strong>Zobrazit ostatní menší projekty</strong></summary>
  <br>
  
| Název Projektu | Popis | Technologie | Stav |
| :--- | :--- | :--- | :--- |
| **[Snake Game](https://github.com/Krematos/Snake)** | Hra had v konzoli - první pokus o hru | Java | Dokončeno |
| **[Web](https://github.com/Krematos/Potrub-Mont-e-web)** | Jednoduchý web | HTML, CSS, PHP | Dokončeno |
| **[E-shop web](https://github.com/Krematos/E-shop/)** | První pokus o E-shop, nakonec jsem tento frontend nepoužil | HTML, CSS | Dokončeno |
| **[Bednovač](https://github.com/Krematos/Bednovac)** | Applikace pro kamarády, přepočítává kurz na herní itemy | JavaFX | Dokončeno |
| **[Pojišťovna](https://github.com/Krematos/Pojistovna)** | První SpringBoot appka, výstup z rekvalifikace | Java, SpringBoot, MySQL | Dokončeno |
| **[DataImporter](https://github.com/Krematos/UniverzalniDataImporter)** | Import, validace a konverze CSV do JSON | Java | Dokončeno |
  
</details>

---

### 📫 Kontakt
Najdeš mě na [LinkedIn](https://www.linkedin.com/in/jan-macner/) nebo mi napiš e-mail JanMacnerDEV@gmail.com
