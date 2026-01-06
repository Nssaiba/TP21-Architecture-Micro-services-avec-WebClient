# TP Architecture Microservices avec Eureka et WebClient

## 1. Eureka Server

### Dashboard Eureka
Les services **SERVICE-CLIENT** et **SERVICE-CAR** sont visibles sur le dashboard :

![Eureka Dashboard](https://github.com/user-attachments/assets/ba42f5bd-fe75-4531-9bc8-a3fb73267942)

---

## 2. Tests end-to-end (Scénario complet)

### 2.1 Créer un client
**Requête POST :**  http://localhost:8081/api/clients
<img width="1630" height="694" alt="C1PNG" src="https://github.com/user-attachments/assets/f0e68b88-f3da-406e-960d-85e972bc2af7" />

### 2.2 Lister les clients
**Requête GET :** http://localhost:8081/api/clients
<img width="1625" height="987" alt="C2PNG" src="https://github.com/user-attachments/assets/d0e40097-dc09-4f3c-8bad-b2aa2bcd02e8" />

### 2.3 Créer une voiture liée au client

<img width="1629" height="704" alt="C3PNG" src="https://github.com/user-attachments/assets/797b06f5-7c1a-45f3-a835-e0392e7f6a66" />

### 2.4 Lire les voitures enrichies
**Requête GET :** http://localhost:8082/api/cars

<img width="1920" height="1033" alt="C4PNG" src="https://github.com/user-attachments/assets/84597f4a-cbcb-4930-a82b-f61fa17beee3" />
