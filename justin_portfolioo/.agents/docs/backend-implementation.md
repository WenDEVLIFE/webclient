# Backend Implementation Plan

## Stack
- **Language**: Java 21
- **Framework**: Spring Boot 3.x (or 4.x as per parent pom)
- **Engine**: Thymeleaf

## Routing (Controller)
- `PortfolioController`:
    - `@GetMapping("/")`: `index.html`
    - `@GetMapping("/about")`: `about.html`
    - `@GetMapping("/journey")`: `journey.html`
    - `@GetMapping("/skills")`: `skills.html`
    - `@GetMapping("/gallery")`: `gallery.html`

## Data Handling
- Simple model attributes to pass page-specific data if needed (e.g., lists of skills, gallery images).
