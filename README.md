# Service Template

Стандартный шаблон проекта на SpringBoot

# Использованные технологии

* [Spring Boot](https://spring.io/projects/spring-boot) – как основной фрэймворк
* [PostgreSQL](https://www.postgresql.org/) – как основная реляционная база данных
* [Redis](https://redis.io/) – как кэш и очередь сообщений через pub/sub
* [testcontainers](https://testcontainers.com/) – для изолированного тестирования с базой данных
* [Liquibase](https://www.liquibase.org/) – для ведения миграций схемы БД
* [Gradle](https://gradle.org/) – как система сборки приложения
* [Lombok](https://projectlombok.org/) – для удобной работы с POJO классами
* [MapStruct](https://mapstruct.org/) – для удобного маппинга между POJO классами

(Сервис)[https://github.com/Dlakares/achievement_service/blob/medusa-master/src/main/java/faang/school/achievement/service/AchievementService.java] может отдать название достижения или увеличить его прогресс и создать ивент при достижении ачивки 

# Моя работа
(Общий интерфейс)[https://github.com/Dlakares/achievement_service/blob/medusa-master/src/main/java/faang/school/achievement/service/handler/EventHandler.java], (абстрактный класс)[https://github.com/Dlakares/achievement_service/blob/medusa-master/src/main/java/faang/school/achievement/service/handler/invitation/StageInvitationAchievement.java] для достижений определённого типа и (обработчик достижения)[https://github.com/Dlakares/achievement_service/blob/medusa-master/src/main/java/faang/school/achievement/service/handler/invitation/OrganizerAchievementHandler.java] работают в совокупности и предполагают просто добавление новых достижений и обновление функционала
