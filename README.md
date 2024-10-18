# ⚡**TECH STACK**⚡
<div align="left">
  


## 👋 ChickenChickenLove [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fchickenchickenlove&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
  ```python
  # I like these sentences.
  Little more than before.
  If you are afraid of falling, there is no chance to fly.
  Show and prove.
  Never assume anything.
  ```

## Skills

```java

/**
 * I have tried the above techniques more than once.
 * But it does not mean that i'm professional that techs.
 * But i always try to study to improve myself.
 * If i have free time to complain, i code instead.
 */

public class Me implements SmartLifecycle {

    private final Set<String> languages;
    private final Set<String> springEchoSystem;
    private final Set<String> display;
    private final Set<String> databases;
    private final Set<String> kafkaEchoSystem;
    private final Set<String> cloudFriendly;

    public Me(Set<String> languages,
              Set<String> springEchoSystem,
              Set<String> display,
              Set<String> databases,
              Set<String> kafkaEchoSystem,
              Set<String> cloudFriendly) {
        this.languages = languages;
        this.springEchoSystem = springEchoSystem;
        this.display = display;
        this.databases = databases;
        this.kafkaEchoSystem = kafkaEchoSystem;
        this.cloudFriendly = cloudFriendly;
    }

    @Override
    public void start() {
        System.out.println("Since 2022, i started to study to code. ");
    }

    @Override
    public void stop() {
        throw new NotImplementedException();
    }



    @Override
    public boolean isRunning() {
        return true;
    }

    @Override
    public String toString() {
        return "I'm not the person who is good at coding, " +
                "but i always try to be better man little more than before. " +
                "I'm interested in contributing to opensource to learn about " +
                "good architecture and code as well. ";
    }
}

@Configuration
public class ConfigurationForMe {

    @Bean
    public Me me() {
        final Set<String> languages = Set.of("Java", "Python", "erlang");
        final Set<String> springEcoSystem = Set.of("Spring Boot", "Spring MVC", "Spring Security", "Spring Batch", "Spring Data JPA");
        final Set<String> databases = Set.of("MySQL");
        final Set<String> display = Set.of("thymeleaf", "tailwind-css");
        final Set<String> kafkaEcoSystem = Set.of("Kafka", "kafka-connect", "schema-registry", "kafka-streams", "ksqlDB");
        final Set<String> cloudFriendly = Set.of("docker", "docker-compose", "kubernetes", "helm", "prometheus", "istio", "fluent-bit");

        return new Me(languages, 
                springEcoSystem,
                databases,
                display,
                kafkaEcoSystem,
                cloudFriendly);
    }
}
```

## 👋Problem Solving <img src="https://img.shields.io/badge/Python-black?style=for-the-badge&logo=Python&logoColor=#3776AB"/>

[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=chickenchickenlove)](https://solved.ac/chickenchickenlove)
<br/>
- I did problem solving at `sovled.ac`.
<br/>


## Docs Contribution
- `spring/spring-kafka` : [Fix ackDiscarded](https://github.com/spring-projects/spring-kafka/pull/3212) 
- `kiali.io/kiali` : [kiali documentation](https://github.com/kiali/kiali.io/pull/765)
- `micrometer-metrics/context-propagation` : [micrometer-metrics/context-propagation documentation](https://github.com/micrometer-metrics/context-propagation/pull/223)


## Code Contribution
- `apache/kafka` : [Unnecessary controller warning : "Loaded ZK migration state of NONE"](https://github.com/apache/kafka/pull/15926)
- `apache/kafka` : [KAFKA-15951: MissingSourceTopicException should include topic names](https://github.com/apache/kafka/pull/15573)
- `reactor/reactor:core` : [wrapped with await().untilAsserted](https://github.com/reactor/reactor-core/pull/3779).
- `spring/spring-kafka` : [Create topology before kafka streams start.](https://github.com/spring-projects/spring-kafka/pull/3172)
- `spring/spring-kafka` : [Receiving an empty list when using RecordFilterStrategy on batch messages](https://github.com/spring-projects/spring-kafka/pull/3216)
- `spring/spring-kafka` : [Add test for next generation consumer-group rebalance protocol](https://github.com/spring-projects/spring-kafka/pull/3237)
- `spring/spring-kafka` (-ing) : [Introduce Confluent ParallelConsumer to Spring Kafka](https://github.com/spring-projects/spring-kafka/pull/3161)
- `spring/spring-kafka` : [Internal Refactoring to improve code readability.](https://github.com/spring-projects/spring-kafka/pull/3422)
- `spring/spring-kafka` : [Removed dead code from test codes.](https://github.com/spring-projects/spring-kafka/pull/3545)
- `spring/spring-kafka` : [GH-3276: Support async retry with @RetryableTopic](https://github.com/spring-projects/spring-kafka/pull/3523)
- `spring/spring-kafka` : [GH-3407: Support KafkaHeaders.DELIVERY_ATTEMPT for batch listeners](https://github.com/spring-projects/spring-kafka/pull/3539)
- `spring/spring-kafka` : [No Issue : Refactor test codes and Remove useless full package name.](https://github.com/spring-projects/spring-kafka/pull/3551)
- `spring/spring-kafka` : [Fix flaky tests in async retry by using a latch instead of sleep.](https://github.com/spring-projects/spring-kafka/pull/3563)
- `line/armeria` : [Make AnnotatedService public](https://github.com/line/armeria/pull/5628)
- `line/armeria` : [Implement @Attribute Injection](https://github.com/line/armeria/pull/5547)
- `line/armeria`(-ing) : [Support micrometer context-propagation](https://github.com/line/armeria/pull/5577)
- `line/centraldogma` : [Add @ConsumseJson to contents API. ](https://github.com/line/centraldogma/pull/999)

## Issue Contribution
- `spring/spring-kafka`: [Improving Observability in Asynchronous Processing (CompletableFuture, Mono)](https://github.com/spring-projects/spring-kafka/issues/3528)

## Books and Lecture
- '23.12 ~ : Learn you some erlang (https://learnyousomeerlang.com)
- '23.11 ~ '23.12 : GOF Design Pattern (https://www.inflearn.com/course/%EB%94%94%EC%9E%90%EC%9D%B8-%ED%8C%A8%ED%84%B4)


<!--
**chickenchickenlove/chickenchickenlove** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
