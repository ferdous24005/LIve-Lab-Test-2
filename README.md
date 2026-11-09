# Submission Checklist

## Checklist

- [x] Complete Java source code
- [x] Servlet/Spring implementation
- [x] JDBC database connectivity
- [x] Database SQL file
- [x] Four-question mathematical game
- [x] Score calculation (10 marks)
- [x] Top 10 leaderboard
- [x] Complete README.md
- [x] Application screenshots
- [x] GitHub repository subdirectory URL

## Details

| # | Item | Where to find it |
|---|------|------------------|
| 1 | Complete Java source code | `src/main/java/` |
| 2 | Servlet/Spring implementation | `src/main/java/.../controller/` |
| 3 | JDBC database connectivity | `src/main/java/.../util/DBConnection.java`, `.../dao/` |
| 4 | Database SQL file | `database/schema.sql` |
| 5 | Four-question mathematical game | Game page and servlet (4 questions per round) |
| 6 | Score calculation (10 marks) | Scoring logic in the service layer |
| 7 | Top 10 leaderboard | Leaderboard page, query ordered by score (limit 10) |
| 8 | Complete README.md | This file |
| 9 | Application screenshots | `screenshots/` |
| 10 | GitHub repository subdirectory URL | See below |

## Technology Stack

- Java, Jakarta Servlet, JSP
- JDBC with MySQL
- Apache Tomcat 10.1
- Maven
- HTML, CSS, JavaScript

## Setup

1. Install JDK, Maven, Apache Tomcat 10.1 and MySQL.
2. Run `database/schema.sql` in MySQL to create the database and tables.
3. Set the environment variables `DB_URL`, `DB_USER` and `DB_PASSWORD`.
4. Build with `mvn clean package`.
5. Copy the generated WAR file from `target/` into Tomcat's `webapps/` folder, or run it from IntelliJ IDEA.
6. Open `http://localhost:8080/` in a browser.

## How the Game Works

- The player answers **four** mathematical questions.
- The total score is out of **10 marks**.
- After finishing, the score is saved to the database.
- The **Top 10** scores are shown on the leaderboard.

## Screenshots

Add your screenshots to the `screenshots/` folder and link them here:

![Game page](screenshots/game.png)
![Result page](screenshots/result.png)
![Leaderboard](screenshots/leaderboard.png)

## GitHub Repository

Subdirectory URL: `https://github.com/<username>/<repository>/tree/main/<subdirectory>`
