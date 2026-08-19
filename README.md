<div align="center">
  <img src="assets/trayce-app-icon.png" width="108" alt="TRAYCE app icon" />
  <h1>TRAYCE</h1>
  <p><strong>Your day, on a plate.</strong></p>
  <p>Snap a meal to identify dishes and side dishes,<br />estimate calories and protein, and understand your daily nutrition.</p>
  <p>
    <img src="https://img.shields.io/badge/iOS-MVP-111111?style=flat-square&logo=apple&logoColor=white" alt="iOS MVP" />
    <img src="https://img.shields.io/badge/TestFlight-In%20Testing-0D96F6?style=flat-square&logo=appstore&logoColor=white" alt="TestFlight" />
    <img src="https://img.shields.io/badge/Market-South%20Korea-1A2B20?style=flat-square" alt="South Korea" />
  </p>
</div>

---

## Overview

TRAYCE is a lightweight nutrition journal designed to remove the friction from meal tracking. A user uploads a meal photo, and the app identifies Korean dishes and side dishes while estimating portion size, calories, protein, carbohydrates, and fat.

Instead of demanding precise manual logging, TRAYCE focuses on a simpler daily question: **What did I eat today, and what might be missing from my diet?**

## Product Preview

<div align="center">
  <img src="assets/trayce-login-mobile.png" width="300" alt="TRAYCE login screen" />
</div>

<br />

| Today | 3-Day Insight | Settings |
|:---:|:---:|:---:|
| <img src="assets/trayce-home.png" width="280" alt="TRAYCE today dashboard" /> | <img src="assets/trayce-report.png" width="280" alt="TRAYCE nutrition report" /> | <img src="assets/trayce-settings.png" width="280" alt="TRAYCE settings" /> |

## Key Features

- Photo-based recognition of meals and Korean side dishes
- Estimated calories and key nutrients for each identified food
- Daily intake compared with personal calorie and protein goals
- Three-day nutrition trends and potential nutrient gaps
- Small, actionable suggestions for the next meal
- A single daily nutrition summary notification
- Sign in with Apple, Google, or email
- In-app deletion of meal records and user accounts

## Product Decisions

### Reduce the cost of starting a food log

The camera is the primary action. Users can begin an analysis from the home screen without searching a food database or entering every ingredient manually.

### Design for the structure of Korean meals

TRAYCE considers rice, soup, a main dish, and multiple side dishes as one meal instead of assuming a single-plate format.

### Keep the product in the wellness category

Nutrition values are clearly presented as photo-based estimates. The product helps users understand everyday eating patterns and does not make diagnostic or treatment claims.

### Prefer a simple report over a dense dashboard

The interface prioritizes today's intake, a short three-day trend, and one realistic action for the next meal instead of overwhelming users with charts.

## Tech Overview

| Area | Technology |
|---|---|
| Mobile | React Native, Expo, TypeScript |
| Backend | Supabase Database, Auth, Storage, Edge Functions |
| AI | Vision-based meal recognition and structured nutrition estimation |
| Authentication | Sign in with Apple, Google, Email |
| Distribution | EAS Build, TestFlight |

## Status

- iOS MVP complete
- Tested on physical devices and through TestFlight
- Preparing the first App Store release
- The initial version is free with a monthly photo-analysis allowance

## Role

End-to-end product ownership across product strategy, UX/UI design, mobile development, backend integration, AI analysis workflow, and TestFlight distribution.

---

<div align="center">
  <sub>TRAYCE · 2026</sub>
</div>
