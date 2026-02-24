# 🍃 Spring Boot Repàs – GitHub Pages

Web de repàs per al mòdul de **Spring Boot**. Funciona 100% estàticament, sense backendni dependències externes.

## 📋 Contingut

| Pàgina | Descripció |
|---|---|
| `index.html` | Pàgina d'inici i navegació |
| `examenes.html` | 4 exàmens tipus test de 50 preguntes |
| `teoria.html` | Resums de tots els temes (12 temes) |
| `ejercicios.html` | Exercicis de reconeixement de codi |

## 🎮 Modes d'examen

- **💀 Supervivència**: Si falles una resposta, l'examen torna a zero. Has d'aconseguir les 50 correctes sense cap error.
- **📖 Pràctica**: Si falles, veus la resposta correcta i continues. Ideal per aprendre.

## 🚀 Desplegar a GitHub Pages

1. Crea un repositori a GitHub (e.g. `spring-repas`).
2. Puja tots els fitxers `.html` a la branca `main`.
3. Ves a **Settings → Pages → Source: Deploy from branch → main → / (root)**.
4. La web estarà disponible a `https://USERNAME.github.io/spring-repas/`

## 📚 Temes coberts

1. Introducció a Spring Boot
2. Estructura del projecte (Spring Initializr)
3. Arquitectura MVC
4. IoC i Injecció de Dependències (DI)
5. Entitats JPA (@Entity, @Table, relacions...)
6. Repositoris (JpaRepository, convencions de noms)
7. Serveis (@Service, @Transactional...)
8. Controladors (@RestController, HTTP methods...)
9. Patrons Builder i DTO
10. Spring Security (JDBC Auth, BCrypt)
11. Gestió d'Excepcions (@ExceptionHandler, @RestControllerAdvice)
12. *(Ampliació)* Upload de fitxers
