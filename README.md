<h2> It's me, Mário! <img src="https://media.giphy.com/media/LRaKL9P5ZEN8sSBaKE/giphy.gif" width="50"></h2>

<a href="https://www.linkedin.com/in/marioalvial/">
  <img align="left" alt="Mário's LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://medium.com/@msealvial/latest">
  <img align="left" alt="Mário's Medium" src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" />
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
