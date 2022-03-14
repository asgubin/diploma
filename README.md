# <diploma> Приложение на Spring Boot
  Приложение для автоматизации оценки стоимости строительных конструкций, разработанных с использованием технологии информационного моделирования BIM, на примере трехмерной модели металлического каркаса здания. Модуль является web-интерфейсом для оценки стоимости элементов конструкции, выгруженных из базы данных 3D-модели Revit Autodesk во внешнюю БД с.
  
  После выгрузки элементов БД PostgreSQL состоит из 8 связанных между собой сущностей, включающие данные о элементах конструкции, симействах, материалах, уровнях, категориях, площадях и расценках (ФССЦм и ФЕР).
  
  Для ФССЦм и ФЕР реализована возможность добавления и удаления новых расценок.
  
  Для элементов конструкции реализована возможность привязки расценок из ФССЦм и ФЕР и изменение профиля металлопроката с автоматической оценкой стоимости.
  
## Используемые технологии
  Java 8
  Spring Boot, Spring MVC, Spring Data JPA
  PostgreSQL
  Thymeleaf
  JUnit 5, Mockito
