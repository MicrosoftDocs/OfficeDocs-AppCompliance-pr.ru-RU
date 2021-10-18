---
title: Сведения о приложениях для timeghost по K&#246;llisch GmbH
ms.author: elmalova
author: elenamalova
ms.date: 07/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для timeghost, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9eb0acc888ccd96c0f0fbccd856792672e9ca10c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430057"
---
# <a name="timeghost"></a>timeghost

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 15 июля 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/e3956558-7399-4ec1-848a-c61a2aa95bc1" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001532" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые K&#246;llisch GmbH в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | timeghost |
| Идентификатор | WA200001532 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | K&#246;llisch GmbH |
| URL-адрес веб-сайта-партнера | [https://timeghost.io](https://timeghost.io) |
| URL-адрес страницы Teams приложения | [https://timeghost.io](https://timeghost.io) |
| URL-адрес политики конфиденциальности | [https://timeghost.io/privacy-policy/](https://timeghost.io/privacy-policy/) |
| URL-адрес терминов использования | [https://timeghost.io/terms-and-conditions/](https://timeghost.io/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены K&#246;llisch GmbH о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | делегирована | Titel, Startdatum, Enddatum, ID | Kalenderdaten werden beim Buchen eines Kalendereintrages auf ein Projekt gespeichert. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| People.Read | делегирована | E-Mail-Adresse | Die Daten werden gespeichert um weitere Team-Mitglieder hinzuzuf&#252;gen und die Avatare der Nutzer anzuzeigen. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| User.Read | делегирована | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| User.ReadBasic.All | делегирована | Um das Profilbild anzuzeigen. | Keine Daten werden gespeichert. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| openid | делегирована | Идентификатор  | Speicherung der ID des Users zur Zuordnung des Users. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |
>| profile | делегирована | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | [f6f894ce-5b44-4c9b-aff4-253d2fbe8a99](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6f894ce-5b44-4c9b-aff4-253d2fbe8a99) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Sentry.io, Chargebee | Vorname, Nachname, E-Mail-Adresse, Firmenname  | Zur Fehlerermittlung, Zahlungs&#252;bermittlung |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>E-Mail-Adresse, Пользовательский ID

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Аудит

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены K&#246;llisch GmbH о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
