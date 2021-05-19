---
title: Информация о применении для StealthMail от Stealthmail Software Ltd
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для StealthMail, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4855cb478e8ba2e53b793a1d61f477de88b74058
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552740"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком на: 31 марта 2021</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Компанией Stealthmail Software Ltd корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | StealthMail |
| ID | WA200001748 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Stealthmail Software Ltd |
| URL-адрес веб-сайта партнера | [https://stealthmail.com](https://stealthmail.com) |
| URL-адрес Teams страницы информации о приложениях | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| URL политики конфиденциальности | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| URL условий использования | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Stealthmail Software Ltd о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ChannelMessage.Read.All | Делегированные | Приложение отправляет сообщение каналу со ссылкой на созданную безопасную электронную почту | ничто | 1ed0a549-c730-44c7-a984-a8c658fe9807 |
>| ChannelMessage.Send | Делегированные | Приложение отправляет сообщение каналу со ссылкой на созданную безопасную электронную почту | ничто | 1ed0a549-c730-44c7-a984-a8c658fe9807 |
>| Chat.ReadWrite | Делегированные | Приложение отправляет сообщение в чат со ссылкой на созданную безопасную электронную почту | ничто | 1ed0a549-c730-44c7-a984-a8c658fe9807 |
>| GroupMember.Read.All | Делегированные | Приложение получает канал членов сделать безопасную электронную почту для них | ничто | 1ed0a549-c730-44c7-a984-a8c658fe9807 |
>| User.Read.All | Делегированные | Приложение получает чат членов, чтобы сделать безопасную электронную почту для них | ничто | 1ed0a549-c730-44c7-a984-a8c658fe9807 |
>| User.ReadBasic.All | Делегированные | Приложение получает чат членов, чтобы сделать безопасную электронную почту для них | ничто | 1ed0a549-c730-44c7-a984-a8c658fe9807 |
>| email | Делегированные | Аутентичный пользователь | ничего не хранить в базе данных | 1ed0a549-c730-44c7-a984-a8c658fe9807 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Мы не контролируем данные партнера в их системах.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Идентификационная информация

Эта информация была предоставлена Stealthmail Software Ltd о том, как это приложение обрабатывает аутентификацию, авторизацию, лучшие практики регистрации приложений и другие критерии идентификации.

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
| Использует ли приложение API-версии предварительного просмотра? | Да |
| Использует ли приложение увеные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
