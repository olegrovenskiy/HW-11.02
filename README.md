# HW-11.02
# Домашнее задание к занятию "11.02 Микросервисы: принципы"

Предложите решение для обеспечения реализации API Gateway. Составьте сравнительную таблицу возможностей различных программных решений. На основе таблицы сделайте выбор решения.

Решение должно соответствовать следующим требованиям:

Маршрутизация запросов к нужному сервису на основе конфигурации
Возможность проверки аутентификационной информации в запросах
Обеспечение терминации HTTPS
Обоснуйте свой выбор.

https://geekflare.com/api-gateway/

https://medium.com/young-app-platform/top-10-api-gateways-for-api-management-to-try-in-2020-2488d03c0952

https://www.tecmint.com/open-source-api-gateways-and-management-tools/


|    |                      | Type           | Маршрутизация запросов к нужному сервису на основе конфигурации | Возможность проверки аутентификационной информации в запросах | Обеспечение терминации HTTPS | Дополнительный функционал                                                                                                                                                                                        | Core                                                | Примечание                       |
|----|----------------------|----------------|-----------------------------------------------------------------|---------------------------------------------------------------|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|----------------------------------|
| 1  | NGINX                | open source    | да                                                              | да                                                            | да                           | балансировка нагрузки                                                                                                                                                                                            |                                                     | хорошо зарекомендовавший продукт |
| 2  | HAProxy              | open source    | да                                                              | да                                                            | да                           | балансировка нагрузки                                                                                                                                                                                            |                                                     | хорошо зарекомендовавший продукт |
| 3  | Kong                 | open source    | да                                                              | да                                                            | да                           | Kong Enterprise gathers more tools around the gateway, such as dashboards or monitoring tools                                                                                                                    | Nginx, Cassandra/PostgreeSQL                        | since 2017                       |
| 4  | Gravitee             | open source    | да                                                              | да                                                            | да                           | One of the advantages of Gravitee is the dashboard: it is clear, easily understandable for a developer                                                                                                           | MongoDB                                             | since January 2015               |
| 5  | Tyk                  | open source    | да                                                              | да                                                            | да                           | strong point of the solution is the dashboard                                                                                                                                                                    | Redis and a MongoDB                                 | since 2014                       |
| 6  | Express Gateway      | open source    | да                                                              | да                                                            | да                           | monitoring, load balancing, caching, request shaping and management, and static response handling                                                                                                                | built on Express.js, a minimal and flexible Node.js | Jul 2016                         |
| 7  | Azure API Management | cloud services | да                                                              | да                                                            | да                           | Active Directory integration, Virtual Network support and a self-hosted gateway. The gateway tool also integrates with Azure services like Monitor for diagnostics and Logic Apps for workflow and orchestration |                                                     |                                  |
| 8  | Amazon API Gateway   | cloud services | да                                                              | да                                                            | да                           | focuses on features geared toward resiliency and lifecycle management                                                                                                                                            |                                                     |                                  |
| 9  | Oracle API Gateway   | cloud services | да                                                              | да                                                            | да                           | policy enforcement, metrics and logging                                                                                                                                                                          |                                                     |                                  |
| 10 | Sber API Gateway     | cloud services | да                                                              | да                                                            | да                           | Усовершенствованный мониторинг                                                                                                                                                                                   |                                                     |                                  |




AAA
