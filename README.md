# Hi there, I'm Shivani Senthilkumar 👋

### International Chess Player | Engineering Student | Learning to Build with Code

## 📖 About Me

- 🎓 **What I study:** Undergraduate student at St. Joseph's Engineering College.
- ♟️ **My story:** I started playing chess at the age of 5, and for almost twelve years it was the centre of my life. I have represented India at the international level on multiple occasions, in different countries, and won medals. I am also a National Chess Champion.
- 📚 **Academics:** Chess was my main focus through school, so I had about a year to explore academics seriously before college. I am still building my technical foundation, and I work on it every day.
- 🚀 **Where I'm heading:** I want to combine the thinking skills chess gave me with technology and engineering, with a focus on building user-friendly interfaces, the backend APIs that power them, and AI-driven cloud data tools.
- ⚡ **Fun fact:** I've spent most of my life solving problems under time pressure. Now I'm learning to solve them with code.

---

## ♟️ What Chess Taught Me

| Chess skill | How it helps me in tech |
|---|---|
| Logical thinking | Breaking a big problem into clear steps |
| Memory | Remembering patterns, syntax and concepts |
| Concentration | Staying focused on hard problems for long periods |
| Decision-making | Choosing the best approach under pressure |
| Patience | Debugging and learning from mistakes |
| Idea generation | Looking at a problem from different angles |

---

## 🛠 Tech Stack & Learning Path

| Domain | Tools & Technologies |
|---|---|
| **Languages** | C (currently learning) |
| **UI / UX** | Learning UI/UX design principles, user-friendly layouts, HTML & CSS basics |
| **Backend & APIs** | Exploring how REST APIs work and how a frontend talks to a backend |
| **Cloud & Data** | AWS storage concepts: S3 Standard, S3 Glacier Deep Archive, Redshift |
| **Hardware & IoT** | ESP32 / Arduino, BLE, sensor basics (building my first prototype) |
| **Tools** | Git, GitHub |

> I'm early in my journey. Everything above is something I'm actively learning, and this list will grow as I build more.

---

## 📌 Featured Projects

### ⚡ DataFetchronous AI (main project, in development)
An AI tool that fetches **ad hoc data** from cold storage quickly and cost-effectively.

**The problem:** Companies store frequently used data in **Amazon S3 Standard** (easy to retrieve, about $23 per TB/month) and rarely used, ad hoc data in **S3 Glacier Deep Archive** (about $1-4 per TB/month, roughly 95% cheaper). When an ad hoc request comes in, the challenge is turnaround time (TAT) and doing it without high cost.

**How it works:**
1. 📥 Receive the ad hoc data request
2. 🔎 Search Glacier to locate the requested data
3. 🧊 Retrieve the data from Glacier
4. 🪣 Push the retrieved data into an S3 bucket
5. 📤 Respond to the request so the data can be consumed
6. 🗑 Delete the ad hoc data from S3 to stop paying for it
7. 🔁 Automate the whole process for every future ad hoc request

**Impact:** Automating this flow could save up to **$20 per TB/month**. The engine can also take parameters for related purposes, then search Glacier and retrieve the matching data.

**Tech:** AWS (S3, S3 Glacier Deep Archive, Redshift context), AI-driven request handling, automation

---

### 🧪 Anti-Doping Sweat Biosensor Patch (hardware in progress)
A wearable, **tamper-evident patch** that monitors sweat biomarkers continuously, to fix the weak point in current doping tests: the human-handled blood/urine sample.

**The problem:** Current tests can be beaten by sample swapping, dilution, masking agents, catheterization and delayed collection. They also happen only at specific moments, not continuously.

**My solution:**
- 🚫 **No sample handoff:** sweat is analysed directly on the body, so there is no vial to swap or dilute
- ⏱ **Continuous monitoring:** abnormal spikes are flagged whenever they happen, not just on match day
- 🔒 **Tamper-evident hardware:** a breakaway seal or conductivity check flags removal and creates a gap alert
- ☁️ **Direct-to-cloud data:** removes the courier and lab chain-of-custody as a tampering point
- 💧 **Saltwater and dilution defence:** flow-rate sensing, skin temperature and conductance, and checking the Na⁺/K⁺/Cl⁻ ratio against lactate and cortisol, which only the body produces

**System architecture:**
1. Patch with a microfluidic channel and electrochemical sensor array
2. Microcontroller (ESP32 / Arduino Nano BLE) reads the sensor signal
3. Encrypted BLE transmission to a phone or base station
4. Cloud dashboard with real-time trends and anomaly detection (threshold-based ML model)
5. Tamper alert system

**What sweat sensing can do today:** cortisol, lactate, glucose, electrolytes and alcohol are well established. Some drug metabolites are in early-stage research. Steroids, EPO and growth hormone are not yet feasible through sweat, so this patch **supports** lab confirmation and does not replace it.

**Status:** 🔧 Building the hardware prototype. Release coming soon.

**Tech:** ESP32 / Arduino, BLE, electrochemical sensing, cloud dashboard, anomaly detection

---

## 🗺 Roadmap

- 🟩 **[done]** Created my GitHub profile and set up my profile README
- 🔵 **[in progress]** Learning C programming and building my first small programs
- 🔵 **[in progress]** Building DataFetchronous AI, my main project
- 🔵 **[in progress]** Building the hardware for my Anti-Doping Sweat Biosensor Patch
- 🎯 **[next]** Upload my C practice programs to a repository
- 🎯 **[next]** Learn HTML, CSS and JavaScript to build real user interfaces
- 🎯 **[next]** Learn how to build a simple backend with REST APIs
- 🚀 **[long-term]** Build full-stack projects that combine clean UI, solid backend logic and the problem-solving mindset I gained from chess

---

## 🏆 Achievements

- ♟️ **National Chess Champion**
- 🌍 Represented **India** at international events in multiple countries
- 🥇 **Medal winner** at the international level
- 🎓 Undergraduate student at **St. Joseph's Engineering College**

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ShivaniSenthilkumar2105&show_icons=true&theme=tokyonight" alt="GitHub stats" />
  <img height="170" src="https://streak-stats.demolab.com?user=ShivaniSenthilkumar2105&theme=tokyonight" alt="GitHub streak" />
</p>

---

## 📬 Connect With Me

- Happy to talk about chess, learning to code, and building student-friendly tech.
- Reach me on [LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN-ID) or at **YOUR-EMAIL@gmail.com**.

*Every move counts. Still learning, still improving.* ♟️
