🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# Soc Ops

**A social bingo experience for in-person meetup icebreakers.**

Discover people with shared stories, spark conversations, and race to five in a row.

> Built as an interactive workshop project that combines Spring Boot, templating, and collaborative game design.

---

## 🚀 What is Soc Ops?

Soc Ops is a lightweight social bingo web app designed for live events, team mixers, and classroom icebreakers. Players browse a bingo card full of prompt questions and mark matches with people around them.

### Why it stands out

- 🎲 Play a classic bingo game with social prompts
- 🧠 Ideal for workshops, networking, and team-building
- 💡 Built as a hands-on learning project for frontend + backend development
- 📁 Includes a step-by-step workshop guide for contributors

---

## ⭐ Highlights

- Simple Spring Boot web app with server-rendered templates
- Customizable bingo prompts and game board generation
- Workshop content for setup, UI design, quiz automation, and multi-agent development
- Local-first development with a Maven wrapper included

---

## 🧭 Quick start

```bash
cd socops
./mvnw spring-boot:run
```

Then open `http://localhost:8080` in your browser.

---

## 📚 Learn with the workshop

| Part | Topic |
|------|-------|
| [00](workshop/00-overview.md) | Overview & Checklist |
| [01](workshop/01-setup.md) | Setup & Context Engineering |
| [02](workshop/02-design.md) | Design-First Frontend |
| [03](workshop/03-quiz-master.md) | Custom Quiz Master |
| [04](workshop/04-multi-agent.md) | Multi-Agent Development |

> 📝 The full workshop is also available in the [`workshop/`](workshop/) folder.

---

## 🛠️ Development

### Prerequisites

- [Java 21 JDK](https://adoptium.net/) or higher
- [Apache Maven 3.9+](https://maven.apache.org/) (or use the included Maven Wrapper)

### Build

```bash
cd socops
./mvnw clean package
```

### Test

```bash
cd socops
./mvnw test
```

---

## 📦 Deployment

This repository is configured to deploy automatically to GitHub Pages on push to `main`.

---

## 💬 Need help?

If you want to extend the game or the workshop, start by reading `workshop/GUIDE.md` and open an issue if you want extra feature ideas.
