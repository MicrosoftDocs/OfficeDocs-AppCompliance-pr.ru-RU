---
title: Сведения о приложениях для Sheetgo в SHEETGO EUROPE SL
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Sheetgo, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 77da98d015480716b848a47f4d6d04d35035f5fb
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526535"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 ноября 2020 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002128" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые SL SHEETGO EUROPE в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Sheetgo |
| Идентификатор | WA200002128 |
| Office 365 поддерживаемые клиенты | Excel 2016 или позже на Mac, Excel 2016 или более поздней Windows, Excel в Интернете |
| Имя компании-партнера | SHEETGO EUROPE SL |
| URL-адрес веб-сайта-партнера | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| URL-адрес политики конфиденциальности | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| URL-адрес терминов использования | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена SL SHEETGO EUROPE о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB: система записей и пользовательские данные для функционирования, Использование журналов систем записей Google BigQuery, Google Firestore: система, которая поддерживает и оркестрирует состояние наших микросервисов, Stripe: Платежная система |  | Эти приложения не используют дополнительные API Microsoft |



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Телеметрия/журналы включают адрес электронной почты пользователя только в качестве идентифицируемой информации для конечных пользователей. По запросу пользователя группа поддержки приложений выполняет внутреннюю автоматическую процедуру, которая размывает адреса электронной почты в телеметрии и журналах и делает данные пользователей более не идентифицируемыми.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>MongoDB: система записей и пользовательские данные для работы с Google BigQuery: журналы записей системы использования Google Firestore: система, которая поддерживает и оркестровает состояние наших микросервисов. Единственными критически важными данными, которые эта служба транзитирует, являются учетные данные пользователей, которые шифруются с помощью AES256 Stripe: Payment system.
 
Все данные в транзите используют HTTPS для безопасных подключений, а все конфиденциальные данные шифруются с помощью AES256

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

