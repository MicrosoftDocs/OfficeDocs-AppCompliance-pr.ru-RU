---
title: Application Information for Outreach Sales Engagement for Outlook by Outreach
ms.author: elmalova
author: elenamalova
ms.date: 06/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для участия в Outlook для Outlook, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 6a009dbc5c075f99bb71105834f3f5208ed91dea
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288278"
---
# <a name="outreach-sales-engagement-for-outlook"></a>Участие в информационно-пропагандистских продажах для Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 14 июня 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381052" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые информационно-разъяснительной службой Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Участие в информационно-пропагандистских продажах для Outlook |
| Идентификатор | WA104381052 |
| Office 365 поддерживаемые клиенты | Outlook 2013 или более поздней Windows, Outlook 2016 или более поздней Outlook в Интернете |
| Имя компании-партнера | Информационно-пропагандистская работа |
| URL-адрес веб-сайта-партнера | [https://www.outreach.io](https://www.outreach.io) |
| URL-адрес политики конфиденциальности | [https://www.outreach.io/legal/privacy-policy/](https://www.outreach.io/legal/privacy-policy/) |
| URL-адрес терминов использования | [https://www.outreach.io/terms](https://www.outreach.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены информационно-пропагандистской организацией о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook API надстройки , API EWS , O36 REST API | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Salesforce CRM | Интеграция информационно-пропагандистских служб с Salesforce позволяет обеспечить двунаправленную синхронизацию ограниченного наборов данных между обеими службами, к числу которые относятся; Имя организации, адрес электронной почты и имя пользователя. | Интеллектуальная двухнаправленная синхронизация аутрича обеспечивает полную верность между данными в обеих системах. Все действия, выполненные в информационно-пропагандистских &#8212;, электронных сообщениях и т.д&#8212; автоматически регистрируются в Salesforce и разрешения конфликтов обнаруживает и устраняет конфликты, чтобы сохранить данные нетронутыми. Он работает в выпусках Salesforce Aloha и Lightning. |



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Аутрич не применяет периоды хранения к данным&#8217;клиента. Аутрич работает как обработчик данных и поэтому никогда не вносит изменений&#8217;данных без их прямого разрешения. Все данные клиентов удаляются через 60 дней после окончания деловых отношений, как по нашим MSA и DPA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Информационно-пропагандистская работа по договорным и нормативным причинам также требует предоставления вовремя уведомления всем клиентам об использовании нового или изменения в подпроцессоре. Для большинства клиентов-аутричов это 30-дневный период. Однако у нас есть несколько клиентов с 60 и 90-дневными требованиями уведомления. Данные клиентов не могут передаваться до тех пор, пока всем клиентам не будет отправлено необходимое по закону уведомление о новой подпроцессе и не пройдет необходимый срок.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

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

Эти сведения предоставлены информационно-пропагандистской программой о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
