# 💘 Witlv – A Dating App for People Who Are Tired of Dating Apps

Welcome to **Witlv**, a totally serious, fully-functional microservices-powered dating platform that was 80% built on sarcasm and 20% on Laravel.

This project will be a real working application, and a love letter to weird app ideas that should probably stay in your Notes app… but didn’t.

## 🎯 The Concept

**Witlv** explores two experimental approaches to modern dating that will be integrate on single application:

### 🧠 Idea 1: Quiz-Based Matching (for Sapiosexuals)

No profile pics. No bios. Just raw intellect.

Users answer **5 customizable questions**:
- Multiple Choice
- True or False
- Identification (yes, actual short answers)

Matches are made based on quiz compatibility, because clearly, **personality quizzes are a better predictor of love than selfies**.

> “Finally, a dating app where people judge you by your answers instead of your looks.”

---

### 📝 Idea 2: Post-Date Ratings & Reviews

After you match, chat, flirt, ghost, or full-send into heartbreak, you can leave a review.

Example ratings:
> J**n – ⭐⭐⭐⭐ <br>
Nice packaging. Late night calls all the time. Looks like it smells good.

> A******n – ⭐⭐ <br>
Beautiful but boring to talk to. Braces but smells like bad breath.

It’s like **Amazon** for relationships.  
Because **love is temporary, but public ratings are forever**.

## 🧱 Tech Stack

| Layer              | Tech                                |
|-------------------|-------------------------------------|
| Mobile App         | React Native (Expo)                 |
| Web Admin Panel    | Laravel + Inertia.js + React        |
| Auth Service       | Laravel API + Passport (OAuth2)     |
| User Service       | Laravel API (Microservice)          |
| Database           | PostgreSQL                          |
| Containerization   | Docker + Docker Compose             |
| CI/CD              | GitHub Actions                      |
| Deployment         | Laravel Cloud, EAS (Expo Application Services) |

---

## 🛠 Features (In Progress / MVP Goals)

### 📱 Client App
- [ ] Register / Login via OAuth2
- [ ] Setup profile and answer quiz
- [ ] See potential matches
- [ ] Swipe left/right
- [ ] Chat with matches
- [ ] Review your date like it’s a delivery service

### 🖥️ Admin Panel
- [ ] User management
- [ ] Review reports & disputes
- [ ] Payment dashboard (Gcash from Xendit or Paymongo idk.)
- [ ] App usage statistics

## 🧠 Why This Exists? (I honestly want to shapren my skills on CI/CD and Software Architecture and for fun 😂)

This is a **functioning microservices architecture** project built to showcase:
- API design and Laravel Passport auth flow
- Containerized services (Auth, User, Admin, Mobile)
- A React Native mobile app with secure auth and navigation
- A little ✨personality✨ because tech projects don’t have to be dry <i>**(Just literally dry texter, not Don't Repeat Yourself)**</i>

## 🧪 Fun, But Real

Witlv is designed for laughs, but it's also:
- I just want to flex this on my resume so I can have a experience on **Microservices Architecture**
- A testbed for building production-ready APIs and mobile clients
- A good excuse to build your own dating app so you never have to use the real ones again 😂


---
## 🤖 Author

Made by **Nathan** – who accidentally took a joke too far and now has a real app to show for it.

> ❝Swipe responsibly. Or don’t. I’m not your mom.❞
