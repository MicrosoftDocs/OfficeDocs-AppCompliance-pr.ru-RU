---
title: Сведения о приложениях для Waldo by Kickle
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Waldo, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 31c6c4b1240c9920a24f013c9d7ac6c61a30c90b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413751"
---
# <a name="waldo"></a>Waldo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 30 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/1d041f16-ab49-4627-bfda-6b60ad2cab6a" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003139" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Kickle Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Waldo |
| Идентификатор | WA200003139 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Kickle |
| URL-адрес веб-сайта-партнера | [https://hellowaldo.app](https://hellowaldo.app) |
| URL-адрес страницы Teams приложения | [https://hellowaldo.app/takeatour/](https://hellowaldo.app/takeatour/) |
| URL-адрес политики конфиденциальности | [https://hellowaldo.app/privacy-policy/](https://hellowaldo.app/privacy-policy/) |
| URL-адрес терминов использования | [https://hellowaldo.app/terms-and-conditions](https://hellowaldo.app/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена kickle о том, как это приложение собирает и хранит организационные данные и контроль, который будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | делегирована | Основываясь на истории чата, Waldo идентифицирует ваших коллег. Этот список используется после этого, чтобы показать состояние в представлении календаря. | Waldo сохраняет пользовательский id каждого коллеги. Эти ID используются для демонстрации списка коллег, с которые мы привыкли работать. | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.Read | делегирована | Это разрешение используется компонентом microsoft Graph набор средств | Недоступно | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| User.ReadBasic.All | делегирована | Это разрешение используется компонентом microsoft Graph набор средств | Недоступно | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| offline_access | делегирована | Используется приложением для выполнения фоновых задач от имени пользователя (обновление маркера для проверки подлинности) | Недоступно | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |
>| openid | делегирована | Необходимые для проверки подлинности | Недоступно | [c71a6f53-cf0c-426d-a826-cedae8b073f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/c71a6f53-cf0c-426d-a826-cedae8b073f7) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Организация может видеть администраторов Waldo, административных контактов и технических контактов по https://app.hellowaldo.app/admin-orga-contacts .  Организация может связаться с нами по hello@kickle.com, чтобы удалить персональные данные из нашего приложения. Это может ограничить предоставляемую услугу.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация была предоставлена Kickle о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Нет |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

