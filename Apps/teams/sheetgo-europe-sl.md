---
title: Application Information for Sheetgo by SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для Sheetgo, политики обработки данных, сведения Microsoft Cloud App Security каталога приложений, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9cbad6d4fcd5f6e081187af10c3c8a69de7122ba
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225313"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 ноября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Просмотр в Teams хранилище</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002067" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые SL SHEETGO EUROPE для Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Sheetgo |
| ID | WA200002067 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Название партнерской компании | SHEETGO EUROPE SL |
| URL-адрес веб-сайта партнера | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| URL-адрес политики конфиденциальности | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| URL-адрес условий использования | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены соглашением об уровне обслуживания SHEETGO EUROPE SL о том, как это приложение собирает и сохраняет данные организации, а также контроль над данными, собираемые приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>Это приложение не использует microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>| **Все сторонние службы Майкрософт OII передаются в** |  **Какой OII передается?** | **Обоснование для передачи OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB: запись системных и пользовательских данных для работы, Google BigQuery: запись использования системных журналов, Google Firestore: система, которая поддерживает и управляет состоянием наших микрослужб, Stripe: Платежная система |  | Эти приложения не используют дополнительные API Майкрософт |

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бот или расширение для обмена сообщениями, оно может получить доступ к идентифицируемой информации конечного пользователя (EUII): список (имя, фамилия, отображаемое имя, адрес электронной почты) любого участника команды или чата, в который оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не выполняется.


#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Данные телеметрии и журналы включают адрес электронной почты пользователя только в качестве идентифицируемой информации для конечного пользователя. По запросу пользователя группа поддержки приложений запускает внутреннюю автоматическую процедуру, которая размыкает адреса электронной почты по телеметрии или журналам и делает данные пользователя неопределяемыми.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>MongoDB: запись системных и пользовательских данных для работы Google BigQuery: запись системных журналов использования Google Firestore: система, которая поддерживает и управляет состоянием наших микрослужб. Единственными критически важными данными, передаваемыми этой службой, являются учетные данные пользователя, которые шифруются с помощью платежной системы AES256 Stripe: Payment system.
 
Все передаваемые данные используют ПРОТОКОЛ HTTPS для безопасных подключений, а все конфиденциальные данные шифруются с помощью AES256

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

