---
description: Setup and run the Soc Ops workspace locally in a dev container or local environment.
---

# Soc Ops Workspace Setup

## Development Checklist
- [ ] lint: run a supported code-style tool or verify formatting if available
- [ ] build: `cd socops && ./mvnw clean package`
- [ ] test: `cd socops && ./mvnw test`

## Quick Start

1. Open the workspace root.
2. Run the app from `socops/`:

```bash
cd socops
./mvnw spring-boot:run
```

3. Open the browser at `http://127.0.0.1:8080/`.

## Prerequisites

- Java 21 JDK on `PATH`
- Maven installed or use `./mvnw`
- Browser for previewing the app

## Notes

- App entrypoint: `socops/src/main/java/com/socops/SocOpsApplication.java`
- UI templates: `socops/src/main/resources/templates/`
- Styles: `socops/src/main/resources/static/css/app.css`
- Workshop content: `workshop/`
