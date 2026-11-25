# Ktor

Example [Ktor](https://ktor.io/) app. Ktor is a Kotlin framework from JetBrains for building asynchronous servers and web applications.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | `java -jar build/libs/app.jar` |
| Application port | `4000` |
| Health check path | `/health` |

## <a name="dev"></a>Run locally

```bash
# run in development mode
./gradlew run

# build for production and run
./gradlew buildFatJar
java -jar build/libs/app.jar
```

Requires JDK 17 or later to run Gradle; Gradle will automatically download JDK 21 for the build if not present.
