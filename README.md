<h2> It's me, Mário! <img src="https://media.giphy.com/media/LRaKL9P5ZEN8sSBaKE/giphy.gif" width="50"></h2>

<a href="https://www.linkedin.com/in/marioalvial/">
  <img align="left" alt="Mário's LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
<a href="https://medium.com/@msealvial/latest">
  <img align="left" alt="Mário's Medium" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/medium.svg" />
</a>

<br>
<br>

```kotlin
fun main() {
    val mario = Mario(
        pronous = setOf("he", "him"),
        goal = "impact people's lives through software",
        love = setOf("event-driven architecture", "DDD", "clean code"),
        programmingLanguages = setOf(
            ProgrammingLanguage(name = "Kotlin", level = Level.ADVANCED, experience = "Production experience"),
            ProgrammingLanguage(name = "Java", level = Level.ADVANCED, experience = "Production experience"),
            ProgrammingLanguage(name = "Ruby", level = Level.PROFICIENT, experience = "Production experience"),
            ProgrammingLanguage(name = "Elixir", level = Level.BASIC, experience = "Pet project"),
            ProgrammingLanguage(name = "TypeScript", level = Level.BASIC, experience = "Production experience")
        ),
        architecture = setOf(
            "microservices",
            "ports and adapters",
            "event-driven"
        ),
        tools = setOf("git, docker, circleci, kafka, intellij, gRPC..."),
        infrastructure = AWS(services = "ec2,ecs,rds,cloudwatch, s3, sqs, sns, cognito...")
    )

    mario.start()
}
```
