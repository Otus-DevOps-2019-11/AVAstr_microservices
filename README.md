# AVAstr_microservices

## (Training Repository OTUS)
---
**<details><summary>15_Homework (Docker-2)</summary>**
**В рамках HW было изучено:**

  * Работа с **`Docker-2`**:
   * Сравнение выводов:
	* 1) docker run --rm -ti tehbilly/htop
	* 2) docker run --rm --pid host -ti tehbilly/htop

	* при первой команде выводятся процессы только внутри докера
	* при второй команде выводятся процессы и докера и хостовой машины

   * Создал docker-host
   * Создал свой образ
   * Развернул приложение в контейнере через GCP
   * Загрузил свой образ в Docker Hub и оттуда развернул свой образ, успешно
   * Возобновил работу travis CI для работы с новым репозиторием

</details>

**<details><summary>16_Homework (Docker-3)</summary>**
**В рамках HW было изучено:**

  * Работа с **`Docker-3`**:
   * Работа с докер-образом
   * Запуск приложения в докере
   * Разделение приложения на компоненты
   * Запуск и проверка приложения как микросервисное
   * Оптимизация размера образов (alpine)

</details>

**<details><summary>17_Homework (Docker-4)</summary>**
**В рамках HW было изучено:**

  * Работа с **`Docker-4`**:
   * Создал сетевые интерфейсы none/host/bridge
   * Приложение и базу разнес по разным сетям, а после настроил связь (front_net/back_net)
   * Просмотрел цепочку настрйоки изменения сетей в контейнерах и на хосте
   * Использовал docker-compose для работы с приложением
   * Использовал несколько переменных для работы ocker-compose через файл .env
   * docker-compose формирует имя для своих сущностей по принципу <Имя директории проекта>_<Имя сервиса>_<Порядковый номер>

</details>

**<details><summary>19_Homework (gitlab-ci-1)</summary>**
**В рамках HW было изучено:**

  * Работа с **`gitlab-ci-1`**:
   * Развернул Gitlab CI
   * Работал с репозиторием в gitlab
   * Настроил gitlab-runner
   * Создал несколько окружений для деплоя приложения
   * Описал пайплайн деплоя и теста приложения
   * Добавил приложение в сборку контейнера
   * Добавил информирование через slack для gitlab (https://devops-team-otus.slack.com/archives/CRY2WU88P)

</details>

**<details><summary>20_Homework (monitoring-1)</summary>**
**В рамках HW было изучено:**

  * Работа с **`monitoring-1`**:
   * Развернул Prometheus в докере
   * Настроил отслеживание сосотояния микросервисов
   * С помощью экспортера собрал метрики
   * Закончил работу с docker-host, удалил ВМ
   * DockerHub: https://hub.docker.com/r/avastr

</details>

**<details><summary>21_Homework (monitoring-2)</summary>**
**В рамках HW было изучено:**

  * Работа с **`monitoring-2`**:
   * На практике использовал мониторинг Docker-контейнеров
   * Собрал метрикив таких системах как grafana, cadvisor, prometheus, alertmanager
   * Настроил уведомление в slack от alertmanager
   * DockerHub: https://hub.docker.com/r/avastr

</details>

**<details><summary>23_Homework (logging-1)</summary>**
**В рамках HW было изучено:**

  * Работа с **`logging-1`**:
   * Произвел сбор логов elasticsearch, kibana, zipkin
   * Произвел визуализацию логов, упростил просмотр с помощью фильтров
   * Собрал структурированные логи
   * Провел трассировку через zipkin

</details>

**<details><summary>25_Homework (kubernetes-1)</summary>**
**В рамках HW было изучено:**

  * Работа с **`kubernetes-1`**:
   * Произвел создание кластера kubernetes по hard way manual
   * Проверил, что все прошло в штатном режиме, кластер создан, ошибок нет
   * Созданы необходимые файлы и проетстировано ДЗ
   * Кластер удален полностью

</details>

**<details><summary>26_Homework (kubernetes-2)</summary>**
**В рамках HW было изучено:**

  * Работа с **`kubernetes-2`**:
   * Развернул локальное окружения для рабоыт k8s
   * Развернул k8s в GKE
   * Запустил приложение reddit в k8s

</details>

**<details><summary>27_Homework (kubernetes-3)</summary>**
**В рамках HW было изучено:**

  * Работа с **`kubernetes-3`**:
   * Развернул и настроил Ingress Controller
   * Настроил шифрование TLS
   * Развернул балансировщик нагрузки
   * Создал сетевые правила для балансировщика
   * СОздал диски в GCP ля работы с базой данных

</details>
