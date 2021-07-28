---
title: Сведения о приложениях для свободной руки от InVisionApp Inc.
ms.author: elmalova
author: elenamalova
ms.date: 05/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Freehand, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a3c92ee618693b4fed77026a47009b490845db60
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525563"
---
# <a name="freehand"></a>Freehand

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 6 мая 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/67cf2c5a-db0e-4256-a423-14010cbeafdd" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381362" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Корпорацией Майкрософт в InVisionApp Inc.:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Freehand |
| Идентификатор | WA104381362 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | InVisionApp Inc. |
| URL-адрес веб-сайта-партнера | [https://www.invisionapp.com](https://www.invisionapp.com) |
| URL-адрес страницы Teams приложения | [https://www.invisionapp.com/freehand](https://www.invisionapp.com/freehand) |
| URL-адрес политики конфиденциальности | [https://www.invisionapp.com/privacy](https://www.invisionapp.com/privacy) |
| URL-адрес терминов использования | [https://www.invisionapp.com/legal/terms-of-service](https://www.invisionapp.com/legal/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены inVisionApp Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://support.invisionapp.com/hc/en-us/articles/360002594732-Subprocessors-and-Subcontractors | https://support.invisionapp.com/hc/en-us/articles/360002594732-Subprocessors-and-Subcontractors | https://support.invisionapp.com/hc/en-us/articles/360002594732-Subprocessors-and-Subcontractors |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Журналы из систем и приложений собираются как в централизованную систему управления журналами, так и в SIEM с ограниченным доступом для изменения или удаления данных. SiEM также отслеживает вторжение, целостность, репутацию сети и сопоставляет эти сведения с событиями cloudtrail. За системой следит специальная группа безопасности, и оповещений настраивается на страницу инженера oncall 24/7. Журналы обеих систем поддерживаются в течение 1 года.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Сторонние оценки риска выполняются для поставщиков, которые обрабатывает персональные данные. Пункты были добавлены по контракту, чтобы включить &#8220;право на аудит&#8221; и проверка должной осмотрительности происходит ежегодно в зависимости от критических факторов и факторов риска. Юридически реализованы надстройки для защиты данных, которые должны быть добавлены по контракту, если это применимо, а также допустимые стандарты, соответствующие требованиям InVision. (Обратите внимание, что субпроцессоры не будут иметь доступ к данным проекта клиента в незашифрованном формате.)

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20788' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20788" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения были предоставлены inVisionApp Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Нет |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Нет |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/><br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
