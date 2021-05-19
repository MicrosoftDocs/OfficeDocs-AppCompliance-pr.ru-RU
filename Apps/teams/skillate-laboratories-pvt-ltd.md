---
title: Информация о применении для Skillate от Skillate Laboratories Pvt. Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Skillate, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений, а также информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 982f32da96968ac9426ef93a86741e037c0f1713
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553880"
---
# <a name="skillate"></a>Skillate

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 12 января 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/b24691df-ba35-42e7-bd57-a7c7e57e49d6" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002490" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация предоставлена Skillate Laboratories Pvt. Ооо для Microsoft:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Skillate |
| ID | WA200002490 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Skillate Laboratories Pvt. Ltd. |
| URL-адрес веб-сайта партнера | [https://skillate.com/](https://skillate.com/) |
| URL-адрес Teams страницы информации о приложениях | [https://www.skillate.com/features/intelligent-hiring/](https://www.skillate.com/features/intelligent-hiring/) |
| URL политики конфиденциальности | [https://www.skillate.com/privacy-policy](https://www.skillate.com/privacy-policy) |
| URL условий использования | [https://www.skillate.com/terms-and-conditions](https://www.skillate.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Skillate Laboratories Pvt. Ltd. о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Делегированные | Данные собираются для авторизации конечному пользователю На Skillate | Мы храним адрес электронной почты только для создания учетной записи пользователя в приложении Skillate | ed4df345-c860-4ffe-b614-0460d9106f0f |
>| openid | Делегированные | Мы используем API для регистрации пользователя в корпорации Майкрософт для навыков с помощью SSO | Мы храним имя и фамилию только конечного пользователя | ed4df345-c860-4ffe-b614-0460d9106f0f |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Мы используем адрес электронной почты только для разрешения пользователям использовать расширение обмена сообщениями | При создании учетной записи мы храним электронную почту, имя и фамилию. Однако во время использования приложения пользователь может добавлять больше переменных на основе входных данных клиентов | Мы храним только электронную почту, имя и фамилию конечного пользователя для авторизации и создания учетной записи.  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Неприменимо

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36380' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36380" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Идентификационная информация

Эта информация была предоставлена Skillate Laboratories Pvt. Ltd. о том, как это приложение обрабатывает аутентификацию, авторизацию, лучшие практики регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интегрируесь ли вы с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и соблюдали все применимые передовой опыт, изложенные в контрольном платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (Библиотека аутентификации Майкрософт) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политику условного доступа? | Нет |
| Запрашивает ли приложение наименьшее разрешение на привилегии для вашего сценария? | Да |
| Точно ли зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мульти-аренду? | Да |
| Есть ли у вашего приложения конфиденциальный клиент? | Нет |
| У вас есть все перенаправление идентификатора объединенных ресурсов (URI), зарегистрированного для вашего приложения? | Да |
| Что следует избегать использования приложения для вашего приложения? | - Wildcard перенаправить URIs,<br/>- OAuth2 Неявные Flow, если требуется для SPA<br/>- Ресурс Владелец пароль учетных данных (ROPC) поток |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API-версии предварительного просмотра? | Нет |
| Использует ли приложение увеные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
