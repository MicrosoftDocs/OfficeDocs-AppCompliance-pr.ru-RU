---
title: Информация о приложениях для аналитики CloudExtend для NetSuite от Celigo CloudExtend
ms.author: elmalova
author: elenamalova
ms.date: 04/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для CloudExtend Analytics для NetSuite, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 12a973e35124a98ab2e284b40c536dabc8ae21a0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52549709"
---
# <a name="cloudextend-analytics-for-netsuite"></a>Аналитика CloudExtend для NetSuite

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 9 апреля 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002784" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Celigo CloudExtend корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Аналитика CloudExtend для NetSuite |
| ID | WA200002784 |
| Office 365 клиенты поддержали | Excel 2016 или позже на Mac, Excel 2016 или позже Windows, Excel в Интернете |
| Название компании-партнера | Селиго КлаудЭкстенд |
| URL-адрес веб-сайта партнера | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL политики конфиденциальности | [https://www.celigo.com/privacy](https://www.celigo.com/privacy) |
| URL условий использования | [https://www.cloudextend.io/agreements/ssa/2019-12](https://www.cloudextend.io/agreements/ssa/2019-12) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Celigo CloudExtend о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | оба | Читайте коллекцию сайтов, для которых пользователь имеет доступ, чтобы иметь возможность получать информацию о рабочей книге, совместно с помощью сайтов | хранить siteid для доступа к рабочей книге в автономном режиме. | 7040f194-bf08-400e-acb1-69df7939416a |
>| Files.ReadWrite.All | оба | Прочитайте содержимое рабочей книги, например таблицы и листы, и сможете писать содержимое этих таблиц | рабочая книга детали, как веб-адрес, идентификатор книги и расположение книги, чтобы получить доступ к ней в автономном режиме | 7040f194-bf08-400e-acb1-69df7939416a |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>| **Все неосуществимые службы Майкрософт OII передаются** |  **Какой OII передается?** | **Обоснование передачи OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Chargebee, NetSuite, Salesforce, Интерком, LogRocket, Amazon AWS | Название организации, номер учетной записи NetSuite, адреса электронной почты Домен org, контактная информация по выставлению счетов | Предоставление лицензий, проверка и выставление счетов поддержки клиентов, устранение неполадок и управление счетами |



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>адрес электронной почты, 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Недоступно

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/14008' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/14008" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Идентификационная информация

Эта информация была предоставлена Celigo CloudExtend о том, как это приложение обрабатывает аутентификацию, авторизацию, лучшие практики регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интегрируесь ли вы с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и соблюдали все применимые передовой опыт, изложенные в контрольном платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (Библиотека аутентификации Майкрософт) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политику условного доступа? | Нет |
| Запрашивает ли приложение наименьшее разрешение на привилегии для вашего сценария? | Да |
| Точно ли зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мульти-аренду? | Да |
| Есть ли у вашего приложения конфиденциальный клиент? | Нет |
| У вас есть все перенаправление идентификатора объединенных ресурсов (URI), зарегистрированного для вашего приложения? | Да |
| Что следует избегать использования приложения для вашего приложения? | - Wildcard перенаправить URIs,<br/>- OAuth2 Неявные Flow, если требуется для SPA<br/>- Ресурс Владелец пароль учетных данных (ROPC) поток |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли ваша модель разрешения вызовам преуспеть только в том случае, если клиентское приложение получает надлежащее согласие? | Да |
| Использует ли приложение API-версии предварительного просмотра? | Нет |
| Использует ли приложение увеные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
