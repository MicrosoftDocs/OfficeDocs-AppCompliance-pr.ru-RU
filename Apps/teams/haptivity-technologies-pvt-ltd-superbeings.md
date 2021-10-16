---
title: Сведения о приложениях для SuperBeings от Haptivity Technologies Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для SuperBeings, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 22b42969049261c0456cd6ce842f64255b907423
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411657"
---
# <a name="superbeings"></a>SuperBeings

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 сентября 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/1e7931be-a76f-4b12-b1b3-8914c7860aec" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003246" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт по технологии Haptivity Pvt Ltd:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | SuperBeings |
| Идентификатор | WA200003246 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Haptivity Technologies Pvt Ltd |
| URL-адрес веб-сайта-партнера | [https://www.superbeings.ai](https://www.superbeings.ai) |
| URL-адрес страницы Teams приложения | [https://www.superbeings.ai](https://www.superbeings.ai) |
| URL-адрес политики конфиденциальности | [https://www.superbeings.ai/policy](https://www.superbeings.ai/policy) |
| URL-адрес терминов использования | [https://www.superbeings.ai/terms-of-use](https://www.superbeings.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Haptivity Technologies Pvt Ltd о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| https://api.botframework.com/.default | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://www.sendinblue.com | OII не передается, для служб электронной почты передаются только имя электронной почты и имя пользователя. | См. выше ответ. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Организации, которые зарегистрировались для использования электронной почты сотрудников службы, делятся с нами. Мы стараемся получать электронную почту от бота, чтобы синхронизировать правильные сведения для пользователя, а также лучше обслуживать пользователя. | Электронная почта | Id электронной почты используется для синхронизации данных из различных служб. То же самое относится и к нашему Teams боту. |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Имена и имена сотрудников организации и их имена можно найти в журналах. Журналы сохраняются в течение одного месяца, после чего они удаляются.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все наши партнеры соответствуют GDPR. Таким образом, мы можем попросить удалить или архивации и хранения данных для всех систем, которые SuperBeings использует или взаимодействует с.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация была предоставлена Haptivity Technologies Pvt Ltd о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

