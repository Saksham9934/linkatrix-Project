<div align="center">

# 🌾 LINKATRIX

### Smart Agriculture • Market Intelligence • Farmer Empowerment

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2EBD85&center=true&vCenter=true&width=750&lines=Smart+India+Hackathon+2026;Better+Information.+Better+Decisions.;Helping+Farmers+Sell+Smarter;Connecting+Farmers+with+Trusted+Buyers;Connect+%E2%80%A2+Understand+%E2%80%A2+Decide" alt="LINKATRIX Typing Banner" />

<p>
  <b>🌱 Better Information. Better Decisions. Better Income.</b>
</p>

<p>
  <img src="https://img.shields.io/badge/Smart%20India%20Hackathon-2026-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AgriTech-Farmer%20First-2EBD85?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Mobile%20First-Application-blue?style=for-the-badge" />
</p>

</div>

---

## 🌾 About LINKATRIX

**LINKATRIX** is an AgriTech platform developed for **Smart India Hackathon 2026** to help farmers make better selling and buying decisions using market intelligence, price trends, recommendations, buyer trust information, weather insights and agricultural knowledge.

The platform focuses on three important questions:

> **1. When should I sell?**
> Should I sell now or wait?

> **2. Whom should I trust?**
> Which buyer is reliable?

> **3. What is the real value of my crop?**
> What price should I expect in the market?

LINKATRIX brings these capabilities together into a simple, farmer-friendly mobile experience.

---

# ⚡ Animated Project Highlights

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=900&color=2EBD85&width=800&lines=%F0%9F%8C%BE+Farmer+First+Agriculture+Platform;%F0%9F%93%88+Real+Mandi+Price+Intelligence;%F0%9F%A4%96+Explainable+Sell%2FWait%2FCompare+Recommendations;%F0%9F%A4%9D+Trusted+Buyer+Discovery;%F0%9F%93%B1+Mobile+First+Experience;%F0%9F%8F%9B%EF%B8%8F+Government+Agmarknet+Data" />

---

# 🧑‍💻 Professional Introduction

LINKATRIX is designed as a **decision-support platform for farmers**, rather than simply another online crop marketplace.

The application combines:

* 📊 Market information
* 📈 Agricultural price trends
* 🤖 Explainable recommendations
* 🤝 Buyer trust scoring
* 🌦️ Weather information
* 📚 Agricultural knowledge
* 🌾 Crop listings
* 💰 Buyer offers

into one unified platform.

The goal is simple:

> **Give farmers better information so they can make better decisions and improve their income.**

---

# 🚀 Key Features

| Feature                        | Description                                           |
| ------------------------------ | ----------------------------------------------------- |
| 🔐 **Farmer / Buyer Login**    | Role-based application experience                     |
| 📍 **Location Setup**          | GPS or manual State / District / Mandi selection      |
| 🏠 **Farmer Home**             | Market insights and actionable information            |
| 📈 **Price Trend**             | 1D / 7D / 30D / 90D agricultural price visualization  |
| 🌾 **Add Crop**                | Create crop listings with quantity, quality and image |
| 🤖 **Recommendation Engine**   | SELL / WAIT / COMPARE recommendations                 |
| 💡 **Explainable AI-style UI** | Shows why a recommendation was generated              |
| 🤝 **Buyer Trust Score**       | 100-point buyer reliability indicator                 |
| 🛒 **Browse Listings**         | Buyers can discover farmer crop listings              |
| 💰 **Make Offer**              | Buyers can submit price and quantity offers           |
| 📋 **My Offers**               | Track buyer offer status                              |
| 📚 **Knowledge Hub**           | Agricultural learning resources                       |
| 🌦️ **Weather**                | Temperature and rainfall information                  |
| 🇮🇳 **Government Data**       | Agmarknet data through data.gov.in                    |
| 🌐 **Language Support**        | English / Hindi                                       |
| 🛡️ **Fallback Handling**      | Demo data when live API is unavailable                |

---

# 🧩 Core Decision System

```text
                 🌾 LINKATRIX
                       │
        ┌──────────────┼──────────────┐
        │              │              │
   📈 Market       🌦️ Weather     🤝 Buyer Data
   Information     Information      & Trust
        │              │              │
        └──────────────┼──────────────┘
                       ↓
              🧠 Decision Engine
                       │
          ┌────────────┼────────────┐
          ↓            ↓            ↓
       🟢 SELL      🟡 WAIT     🔵 COMPARE
```

Instead of only showing raw market data, LINKATRIX attempts to convert information into an understandable decision for the farmer.

---

# 📈 Price Intelligence

The **Price Trend** module provides an agricultural commodity price visualization similar to a stock-market chart.

### Supported time ranges

```text
1 Day     →     7 Days     →     30 Days     →     90 Days
```

Farmers can:

* Search for crops
* View price movements
* Compare market prices
* Analyze trends
* Inspect market information
* Understand minimum, maximum and modal prices

LINKATRIX uses a **custom SVG-based chart**, avoiding the need for an external charting library.

---

# 🏛️ Government Data Integration

LINKATRIX integrates government agricultural market information through:

**data.gov.in → Agmarknet REST API**

The application can display:

* 📍 Mandi information
* 📅 Actual market dates
* 💰 Minimum price
* 💰 Maximum price
* 📊 Modal price
* 📈 Market trends

### LIVE vs DEMO

🟢 **LIVE**
Data retrieved from the government API.

🟡 **DEMO**
Fallback/demo information used when live data cannot be retrieved.

This makes the prototype transparent during demonstrations.

---

# 🛡️ API Failure Handling

LINKATRIX is designed not to break when the government API becomes temporarily unavailable.

Possible causes include:

* Network problems
* API downtime
* CORS restrictions
* Missing API key
* Connectivity issues

The application can fall back to demo data.

```text
Government API
      │
      ├── ✅ Available
      │       ↓
      │    LIVE DATA
      │
      └── ❌ Unavailable
              ↓
          DEMO DATA
```

This allows the application to remain usable during demonstrations.

---

# 🌾 Farmer Flow

```text
Splash Screen
      ↓
Login / Register
      ↓
Select Farmer
      ↓
Location Setup
      ↓
Farmer Home
      ↓
┌─────────────┬─────────────┬──────────────┐
│             │             │              │
Price       Add Crop   Recommendation   Buyers
│             │             │              │
↓             ↓             ↓              ↓
Trend       Listing      SELL/WAIT/      Trust
Analysis                   COMPARE       Score
```

---

# 🤝 Buyer Flow

LINKATRIX also provides a dedicated buyer experience.

```text
Buyer Login
    ↓
Buyer Home
    ↓
Browse Listings
    ↓
Search / Filter
    ↓
View Crop Details
    ↓
Compare Listings
    ↓
Make Offer
    ↓
My Offers
    ↓
Track Status
```

Buyers can view:

* Farmer crop listings
* Crop details
* Quantity
* Quality
* Location
* Expected price
* Available offers

---

# 🧠 Recommendation Engine

LINKATRIX currently uses a **rule-based recommendation engine**.

Possible outputs:

### 🟢 SELL

Current market conditions may indicate a suitable selling opportunity.

### 🟡 WAIT

Price trends may indicate that waiting could provide a better opportunity.

### 🔵 COMPARE

The farmer may benefit from comparing prices across nearby markets.

The system also explains **why** a recommendation was generated instead of simply showing a result.

---

# 🤝 Buyer Trust Score

LINKATRIX introduces a **100-point Buyer Trust Score**.

Potential factors include:

* Transaction history
* Buyer activity
* Offer behavior
* Reliability indicators
* Platform interactions

Example:

```text
        BUYER TRUST SCORE

             92 / 100
        ██████████████████░░

     Transaction History
     Offer Reliability
     Buyer Activity
     Platform Behaviour
```

The purpose is to help farmers make more informed decisions when choosing buyers.

---

# 🛠️ Technology Stack

<div align="center">

### Frontend

<img src="https://skillicons.dev/icons?i=react,tailwind,html,css,js" />

### Backend

<img src="https://skillicons.dev/icons?i=nodejs,express,postgres" />

### Data & APIs

<img src="https://skillicons.dev/icons?i=postgres" />

**data.gov.in • Agmarknet REST API**

### Development Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode" />

</div>

---

# 🏗️ Architecture

```text
                    LINKATRIX
                        │
             ┌──────────┴──────────┐
             │                     │
          FARMER                 BUYER
             │                     │
             └──────────┬──────────┘
                        ↓
                Mobile Interface
                        ↓
                 React / UI Layer
                        ↓
                Application Logic
                        ↓
              ┌─────────┴─────────┐
              │                   │
        Government API        Backend Layer
        data.gov.in           Node / Express
              │                   │
              └─────────┬─────────┘
                        ↓
                   PostgreSQL
```

The current hackathon demonstration is packaged into a **single HTML file**, while a production-oriented backend architecture has also been prepared.

---

# 📱 Single-File Mobile Demo

The current mobile prototype is available as:

```text
linkatrix-mobile.html
```

### Run locally

```text
Download linkatrix-mobile.html
          ↓
Double-click the file
          ↓
Open in Chrome / Edge
          ↓
Start LINKATRIX
```

### No installation required

The single-file prototype can be demonstrated without:

* npm installation
* Local server setup
* Database setup
* Backend configuration

This makes it convenient for hackathon demonstrations and quick testing.

---

# 🎨 Mobile-First Design

LINKATRIX was redesigned around a mobile-first experience.

### Design principles

* 🌱 Green agricultural branding
* 📱 Mobile-first interface
* 🧩 Rounded cards
* 🧭 Bottom navigation
* ➕ Large central Add Crop action
* 👨‍🌾 Farmer-friendly information
* 🎯 Simple decision-focused UI

### Farmer Navigation

```text
Home → Price → Add Crop → Buyers → Knowledge
```

### Buyer Navigation

```text
Home → Browse → Offers → Knowledge / Profile
```

---

# 📊 Project Evolution

LINKATRIX evolved through multiple stages.

### Phase 1 — Desktop Dashboard

The project initially included:

* Farmer Dashboard
* Buyer Dashboard
* Assisted Mode
* Admin Panel
* Express.js backend
* PostgreSQL database architecture

### Phase 2 — Mobile-First Pivot

The interface was redesigned as:

```text
linkatrix-mobile.html
```

with a simpler farmer-focused experience.

### Phase 3 — Buyer Marketplace

A dedicated buyer flow was introduced:

```text
Browse → View → Compare → Offer → Track
```

### Phase 4 — Government Data

Static market information was replaced/extended with:

```text
data.gov.in
      ↓
Agmarknet API
      ↓
LINKATRIX
      ↓
Real Mandi Information
```

---

# 🎯 Core Value Proposition

LINKATRIX combines:

**Market Information**

*

**Price Trends**

*

**Recommendations**

*

**Buyer Trust**

*

**Agricultural Knowledge**

into a single farmer-friendly platform.

> ### 🌾 Better Information. Better Decisions. Better Income.

---

# 🔮 Future Roadmap

### Phase 1 — Live Intelligence

* [ ] Real-time market updates
* [ ] Live weather integration
* [ ] More mandi coverage
* [ ] Advanced price analytics

### Phase 2 — AI / ML

* [ ] AI crop-quality analysis
* [ ] Crop disease detection
* [ ] Price prediction
* [ ] Personalized recommendations
* [ ] Intelligent farmer assistance

### Phase 3 — Production Backend

* [ ] Node.js / Express backend
* [ ] PostgreSQL database
* [ ] Secure authentication
* [ ] User profiles
* [ ] Crop listing management
* [ ] Offer management
* [ ] Transaction tracking

### Phase 4 — Full Marketplace

```text
Farmer
   ↓
Crop Listing
   ↓
Buyer Discovery
   ↓
Offers
   ↓
Negotiation
   ↓
Accepted Offer
   ↓
Transaction
```

---

# 🏆 Smart India Hackathon 2026

**LINKATRIX** is developed as an **AgriTech solution for Smart India Hackathon 2026**, with a focus on improving agricultural decision-making through accessible market intelligence and farmer-oriented digital tools.

---

# 📌 Project Status

| Module                | Status                   |
| --------------------- | ------------------------ |
| Farmer Experience     | ✅ Available              |
| Buyer Experience      | ✅ Available              |
| Price Trends          | ✅ Available              |
| SVG Charts            | ✅ Available              |
| Recommendation Engine | ✅ Available              |
| Buyer Trust Score     | ✅ Available              |
| Crop Listings         | ✅ Available              |
| Buyer Offers          | ✅ Available              |
| Government API        | ✅ Integrated             |
| API Fallback          | ✅ Implemented            |
| Hindi / English       | ✅ Available              |
| Production Backend    | 🚧 Architecture Prepared |
| Advanced AI / ML      | 🔮 Future Development    |

---

<div align="center">

# 🌾 LINKATRIX

### Connect • Understand • Decide

**Better Information. Better Decisions. Better Income.**

<br>

<img src="https://img.shields.io/badge/AgriTech-LINKATRIX-2EBD85?style=for-the-badge" />
<img src="https://img.shields.io/badge/SIH-2026-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Mobile--First-Ready-blue?style=for-the-badge" />

</div>
