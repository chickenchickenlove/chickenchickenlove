# ⚡**TECH STACK**⚡
<div align="left">
  


## 👋 ChickenChickenLove 
  ```python
  # I like these sentences.
  Little more than before.
  If you are afraid of falling, there is no chance to fly.
  Show and prove.
  Never assume anything.
  ```

## Open Source Contribution
I have been consistently contributing to several opensource projects.

### Apache Kafka
- [KAFKA-19242: Fix commit bugs caused by race condition during rebalancing.](https://github.com/apache/kafka/pull/19631)
- More than [3 PRs](https://github.com/apache/kafka/pulls?q=is%3Apr+author%3Achickenchickenlove+is%3Aclosed) have been merged.
- More than [1 PRs](https://github.com/apache/kafka/pulls/chickenchickenlove) are in progress.
</br>

### Spring for Apache Kafka
- [GH-3276: Support async retry with @RetryableTopic](https://github.com/spring-projects/spring-kafka/pull/3523)
- [GH-3145: Add test for next generation consumer-group rebalance protocol](https://github.com/spring-projects/spring-kafka/pull/3237)
- [GH-3067: Spring Kafka support multiple headers with same key.](https://github.com/spring-projects/spring-kafka/pull/3874)
- [GH-3407: Support KafkaHeaders.DELIVERY_ATTEMPT for batch listeners](https://github.com/spring-projects/spring-kafka/pull/3539)
- [GH-3712: Make ContainerPausingBackOffHandler working in batch mode.](https://github.com/spring-projects/spring-kafka/pull/3885)
- [Events skipped in group rebalancing](https://github.com/spring-projects/spring-kafka/issues/3703)
- More than [20+ PRs](https://github.com/spring-projects/spring-kafka/pulls?q=is%3Apr+is%3Aclosed+author%3Achickenchickenlove) have been merged.
- More than [0 PRs](https://github.com/spring-projects/spring-kafka/pulls/chickenchickenlove) are in progress.
- More than [5 issues](https://github.com/spring-projects/spring-kafka/issues?q=is%3Aissue%20state%3Aclosed%20author%3Achickenchickenlove) have been issued.
</br>

### Armeria
- [Make AnnotatedService public](https://github.com/line/armeria/pull/5628)
- [Implement @Attribute Injection](https://github.com/line/armeria/pull/5547)
- [Support micrometer context-propagation](https://github.com/line/armeria/pull/5577)
- [Support nested context paths.](https://github.com/line/armeria/pull/5846)
- [Respect TTL of a DNS record for proxy config](https://github.com/line/armeria/pull/5960)
- [Make ClientRequestContext.authority() and host() return non-null ](https://github.com/line/armeria/pull/5969)
</br>

### etc
- `kiali.io/kiali` : [kiali documentation](https://github.com/kiali/kiali.io/pull/765)
- `micrometer-metrics/context-propagation` : [micrometer-metrics/context-propagation documentation](https://github.com/micrometer-metrics/context-propagation/pull/223)
- `reactor/reactor:core` : [wrapped with await().untilAsserted](https://github.com/reactor/reactor-core/pull/3779).
- `line/centraldogma` : [Add @ConsumseJson to contents API. ](https://github.com/line/centraldogma/pull/999)
- `line/centraldogma-python` : [Bug fix from get_files method. ](https://github.com/line/centraldogma-python/pull/58)
</br>

## Learn by implementing
- [Implement an HTTP/HTTP2 Server with a TCP Server](https://github.com/chickenchickenlove/implment-http-client/tree/main/http_2) 
- [Implement SWIM Protocol](https://github.com/chickenchickenlove/implement_membership_protocol/tree/main/swim-portocol-implementation)
- [Implement HyParView Protocol](https://github.com/chickenchickenlove/implement_membership_protocol/tree/main/hybrid-partial-view-protocol-implementation)
- [Implement Plumtree Protocol](https://github.com/chickenchickenlove/implement_membership_protocol/tree/main/hyparview_and_plumtree_implementation)
- [Implement RAFT Consensus algorithm](https://github.com/chickenchickenlove/implement_raft_consensus)

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
