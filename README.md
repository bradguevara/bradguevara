<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0414,50:5B2A6E,100:C026D3&height=160&section=header&text=Brad%20Guevara&fontSize=42&fontColor=E8E0F5&fontAlignY=35&desc=Software%20Engineer%20%C2%B7%20Distributed%20Systems%20%26%20Backend&descAlignY=55&descSize=18&animation=fadeIn" width="100%"/>

# Brad Guevara

**Software Engineer · CS Grad (May 2026) · Distributed Systems & Backend**

[![Certificate](https://img.shields.io/badge/Certificate-Data%20Intensive%20Computing-5EEAD4?style=for-the-badge&logo=apachespark&logoColor=black)](#-education)

[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bradrguevara@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bradguevara)
[![Portfolio](https://img.shields.io/badge/Portfolio-C026D3?style=for-the-badge&logo=githubpages&logoColor=white)](https://bradguevara.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-bradguevara-C026D3?style=for-the-badge&logo=github&logoColor=5EEAD4&labelColor=181717)](https://github.com/bradguevara)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/bguevarapinos/)

</div>

<p align="center">
I'm into distributed systems — the kind of stuff that happens behind the scenes when machines need to agree, find each other, or just not fall over. Routing tables, leader elections, failure detectors, that whole world.<br>
I just finished my CS degree at the University at Buffalo, along with a <strong>Certificate in Data Intensive Computing</strong>, where I got hands-on with Spark, Hadoop, and Google Cloud Dataproc for working with big datasets.<br>
Outside of class, I'm grinding LeetCode and working through NeetCode's roadmap to stay sharp on DSA.
</p>

---

## 🧩 Projects

### Raft Leader Election (Mar 2025)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Raft](https://img.shields.io/badge/Raft-Consensus-C026D3?style=flat-square)

- Tackled the leader election piece of Raft in Go — the part where nodes have to figure out who's in charge without a central authority.
- Used randomized election timeouts and heartbeats so the cluster notices when a leader goes down and quickly elects a new one.
- Made sure terms and votes were tracked correctly so you never end up with two leaders fighting for the same term.

### Distributed Hash Table (Feb 2025)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Kademlia](https://img.shields.io/badge/Kademlia-P2P-C026D3?style=flat-square)

- Built the routing table for a simplified Kademlia-style DHT — basically the part that lets nodes find each other in a peer-to-peer network without anyone keeping a master list.
- Used cryptographic hashing and Go interfaces so data could be addressed and located based on its content.
- Wired the routing table into a full DHT and tuned how lookups and messages travel across the network.

### Message Service & Failure Detector (Jan 2025)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TCP](https://img.shields.io/badge/TCP-Sockets-5EEAD4?style=flat-square) ![Protobuf](https://img.shields.io/badge/Protobuf-Serialization-5EEAD4?style=flat-square)

- Built a message-passing service in Go where multiple processes talk to each other over raw TCP sockets, with messages flowing through Go channels.
- Added a heartbeat-based failure detector so the system notices within half a second if a node goes down.
- Picked up Protobuf along the way for serializing messages, on top of a custom framing protocol I wrote to handle message boundaries over TCP.

### Stock Predictor App (Jun 2026)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini%20AI-4285F4?style=flat-square&logo=googlegemini&logoColor=white)

- Built a full-stack app that pulls real stock data from Yahoo Finance and Finnhub.
- Trained an XGBoost model on 11,000+ rows of historical data to predict next-day price movement.
- Hooked up Gemini to read news headlines and add a sentiment-based take alongside the model's prediction.

### Movie Rating & Review Platform (Fall 2025)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

- Worked with a team to build a full platform where people can rate, review, and discuss movies.
- Built out the React frontend with custom CSS — handling things like dynamic review feeds and responsive layouts.
- Wrote the PHP/MySQL backend powering reviews, auth, likes/dislikes, and watchlists.

### Video Platform — Backend (CSE312)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![WebSockets](https://img.shields.io/badge/WebSockets-5EEAD4?style=flat-square) ![JWT](https://img.shields.io/badge/JWT-Auth-5EEAD4?style=flat-square&logo=jsonwebtokens&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![OAuth](https://img.shields.io/badge/OAuth-GitHub%20Login-181717?style=flat-square&logo=github&logoColor=white)

- Built out the backend on top of a provided starter server — a good way to learn REST basics like GET, POST, PATCH, and DELETE while serving JSON.
- Set up JWT auth with cookie sessions, added two-factor authentication, and got "Login with GitHub" working via OAuth.
- Used FFmpeg to process video uploads, with everything stored and tracked in a database.
- Added WebSockets for live chat and peer-to-peer video calls.

---

## 💼 Experience

**Software Engineering Intern** — Citytech, Quito, Ecuador (Jun–Sep 2025)
- Helped out with small code updates and cleanup in the team's C/.NET testing environment, getting familiar with how everything fit together.
- Picked up the basics of REST APIs and SQL, and saw how the different layers of a .NET app connect in practice.
- Worked closely with senior developers, using diagrams and docs to get up to speed on the architecture and workflow.

---

## 🛠️ Skills

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**Tools & Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud%20Dataproc-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

---

## 🎓 Education

**B.S. Computer Science** — University at Buffalo (May 2026)
Coursework: Distributed Systems, System Programming, Data Models & Query Languages, Applied Probability Theory, Software Engineering Concepts, Data Intensive Computing

**Certificate in Data Intensive Computing** — University at Buffalo (May 2026)
Focus on large-scale data processing and distributed storage — Apache Spark, Hadoop, PySpark, MLlib, and Google Cloud Dataproc for building and tuning data pipelines over large datasets.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C026D3,50:5B2A6E,100:0A0414&height=100&section=footer" width="100%"/>
