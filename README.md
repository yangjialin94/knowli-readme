# Knowli

Knowli is a **cross-platform mobile learning app** that delivers bite-sized, AI-generated stories and surprising facts in under **30 seconds**. Designed for all age groups, Knowli makes idle moments productive — whether on a coffee break or waiting in line.

👉 This repository is **public for recruiters and collaborators to review the project’s scope and technology choices**. The source code remains private.

---

## ✨ Features

- **Daily Knowledge** – 3 free stories (“taps”) every day.  
- **Premium Tap Packs** – In-app purchases (5 taps for $0.99, 10 taps for $1.49).  
- **Subscriptions (roadmap)** – Monthly plan with up to 100 daily taps + history access.  
- **History** – Browse previously unlocked stories.  
- **Ads Integration** – Banner + interstitial ads (non-intrusive).  
- **Guest Mode** – Use immediately without sign-in.  
- **Sync & Auth** – Apple Sign-In (iOS), Google Sign-In (Android).  
- **Clean & Minimal UI** – Optimized for quick, distraction-free learning.  

---

## 🛠 Tech Stack

**Mobile App**  
- **Framework**: React Native (Expo)  
- **Language**: TypeScript  
- **UI**: Tailwind, Shadcn/UI components, Motion for animations  
- **Navigation**: Expo Router  
- **State Management**: React Context, Hooks  
- **In-App Purchases**: react-native-iap (StoreKit + Play Billing)  
- **Ads**: Google AdMob (banner, interstitial, planned rewarded ads)  
- **Auth**: Apple Sign-In, Google Sign-In  

**Backend & Infrastructure**  
- **Framework**: Node.js + Express  
- **ORM**: Prisma  
- **Database**: PostgreSQL (Render)  
- **Auth Validation**: Apple Sign-In token verification, JWTs  
- **Purchase Validation**: StoreKit receipt validation via backend endpoints  
- **Hosting**: Render  
- **Future Roadmap**: Subscription tiers, streaks & badges, themed weekly events  

---

## 🚀 Architecture Overview

- **Frontend** (React Native) calls backend APIs for authentication, purchases, and story history.  
- **Backend** manages users, tap counts, purchase validation, and ad configurations.  
- **AI Story Generation** – OpenAI API generates surprising, accessible stories on demand.  
- **Ads + IAP** – Monetization through Google AdMob & StoreKit/Play Billing.  

---

## 📸 Screenshots

<table>
  <tr>
    <td><img src="/screenshots/1.%20Sign%20In.png" width="220"/></td>
    <td><img src="/screenshots/2.%20Learn%20-%20Free.png" width="220"/></td>
    <td><img src="/screenshots/3.%20Learn%20-%20Purchased.png" width="220"/></td>
  </tr>
  <tr>
    <td><img src="/screenshots/4.Story.png" width="220"/></td>
    <td><img src="/screenshots/5.History.png" width="220"/></td>
    <td><img src="/screenshots/6.%20Profile.png" width="220"/></td>
  </tr>
</table>

---

## 📬 Contact

Interested in learning more about Minibunn Planner?  
- **Portfolio**: [jialinyang.com](https://www.jialinyang.com)
- **LinkedIn**: [linkedin.com/in/jialin-yang-jy](https://www.linkedin.com/in/jialin-yang-jy)
- **Email**: work@jialinyang.com

---

## ⚖️ License

This project is released under a Proprietary License.
-	Code is not open source and cannot be copied, modified, or redistributed.
-	This repository is for review purposes only.
