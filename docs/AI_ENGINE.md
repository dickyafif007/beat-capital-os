# Beat Capital AI Engine

## Objective

The AI Engine is designed to assist users in making better investment decisions.

It does NOT execute trades.

Its responsibility is to analyze data, evaluate opportunities, calculate risk, and provide recommendations.

---

# AI Responsibilities

The AI should answer:

- Is this stock worth buying?
- Is now a good entry?
- Should I wait?
- Is the position becoming risky?
- Should I take profit?
- Should I cut loss?
- What is the confidence level?

---

# AI Inputs

The engine collects data from multiple sources.

## Market Data

- Price
- Volume
- Bid/Offer
- Foreign Flow

---

## Technical Data

- EMA
- SMA
- MACD
- RSI
- Bollinger Band
- VWAP

---

## Fundamental Data

- Revenue
- Net Profit
- ROE
- ROA
- DER
- PBV
- PER
- EPS Growth

---

## News

- Company News
- Sector News
- Macro Economy
- Global Events

---

## User Data

- Portfolio
- Watchlist
- Risk Profile
- Trading Journal
- Previous Decisions

---

# AI Analysis Pipeline

Step 1

Collect Data

↓

Step 2

Clean Data

↓

Step 3

Calculate Indicators

↓

Step 4

Fundamental Analysis

↓

Step 5

Technical Analysis

↓

Step 6

News Sentiment

↓

Step 7

Risk Analysis

↓

Step 8

Decision Score

↓

Step 9

Recommendation

---

# Recommendation Types

BUY

Strong opportunity.

WAIT

Potential opportunity.

HOLD

Maintain current position.

TAKE PROFIT

Target reached.

CUT LOSS

Risk becoming unacceptable.

AVOID

Poor quality stock.

---

# AI Confidence

Every recommendation includes confidence.

Example

Confidence

92%

Reason

- Trend Up
- Foreign Buy
- Strong Earnings
- High Volume

---

# Explainable AI

Every recommendation must include explanation.

Never output only:

BUY

Instead output:

BUY

Reason:

- Revenue increasing
- Technical breakout
- Strong accumulation
- Low downside risk

---

# Future Version

Future versions may include:

- Learning from user behavior
- Pattern recognition
- AI portfolio optimization
- AI market prediction
- Multi-agent collaboration
