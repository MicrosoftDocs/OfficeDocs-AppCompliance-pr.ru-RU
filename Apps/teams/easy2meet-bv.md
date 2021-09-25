---
title: Сведения о приложениях для Easy2Meet от Easy2Meet B.V.
ms.author: elmalova
author: elenamalova
ms.date: 09/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для Easy2Meet, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 726f9ed549b3c200fda568f8b5d7a7f73c1a93ee
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785754"
---
# <a name="easy2meet"></a>Easy2Meet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 21 сентября 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/8dbb8c54-678e-4c02-bc35-0f393416e532" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003277" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Easy2Meet B.V. в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Easy2Meet |
| ID | WA200003277 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Easy2Meet B.V. |
| URL-адрес веб-сайта-партнера | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| URL-адрес страницы Teams приложения | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| URL-адрес политики конфиденциальности | [https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf](https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf) |
| URL-адрес терминов использования | [https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet...](https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet%20General%20Terms%20and%20Conditions%20Sept%202020%20EN.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены в Easy2Meet B.V. о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет иметь контроль над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | делегирована | Нам нужна информация о пользователях для управления пользователями и собраниями в Easy2Meet | Электронная почта и имя. Это необходимо для управления пользователями и собраниями. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| email | делегирована | Просмотр адресов электронной почты текущего пользователя. Нам нужны adres электронной почты для отправки приглашений на собрание | Электронная почта и имя. Это необходимо для управления пользователями и собраниями. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| openid | делегирована | мы не собираем данные здесь. Мы используем это для регистрации в пользователе | мы не собираем данные здесь. Мы используем это для регистрации в пользователе. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| profile | делегирована | Нам нужна информация о пользователях для управления пользователями и собраниями в Easy2Meet | Электронная почта и имя. Это необходимо для управления пользователями и собраниями. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint Online | Нет |  |  |  |  |
>| MS Exchange Online | Нет |  |  |  |  |

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

>аудит

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены в Easy2Meet B.V. о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

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
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
