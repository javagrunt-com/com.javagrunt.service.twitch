# com.javagrunt.service.twitch
## Spring Boot Twitch4J Metrics Exporter Prometheus

![img](./index.png)

## Installation
Instructions on how to install and set up the project.

```bash
git clone https://github.com/javagrunt-com/com.javagrunt.service.twitch
cd com.javagrunt.service.twitch
```

## Usage

```bash
./mvnw spring-boot:test-run
```

## Getting a Twitch `User` access token

```bash
twitch token -u -s "user:read:email moderation:read channel:read:subscriptions"
```

## See Also

- [Blog](https://dashaun.com/posts/bootiful-twitch-metrics-for-prometheus/)
- [YouTube](https://youtu.be/TSmEx8taj2M?si=ieRu4CHgV8JdD9rT)