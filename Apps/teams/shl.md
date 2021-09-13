---
title: Сведения о приложениях для SHL по SHL
ms.author: elmalova
author: elenamalova
ms.date: 06/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствия требованиям для SHL, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5c5b98779e7c038d809a8ecaee60fee1cdf0ca71
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286137"
---
# <a name="shl"></a>SHL

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 25 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/0c52adc0-18a0-45ca-b6ee-154cf1ef87e2" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002887" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые службой SHL Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | SHL |
| Идентификатор | WA200002887 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | SHL |
| URL-адрес веб-сайта-партнера | [https://shl.com](https://shl.com) |
| URL-адрес страницы Teams приложения | [https://www.shl.com/en/about/](https://www.shl.com/en/about/) |
| URL-адрес политики конфиденциальности | [https://www.shl.com/en/privacy/administrator-data-protectio...](https://www.shl.com/en/privacy/administrator-data-protection-notice/) |
| URL-адрес терминов использования | [https://www.shl.com/en/terms-of-service/](https://www.shl.com/en/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена SHL о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | делегирована | Доступные общие слоты Calander | Н/Д | [afd2c390-8b78-40fa-913b-7fc5911e884a](https://docs.microsoft.com/microsoft-365-app-certification/azure/afd2c390-8b78-40fa-913b-7fc5911e884a) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Мы перекладываем данные в службы нашего собственного приложения (Talentcentral: https://talentcentral.eu.shl.com/admin) | EUII : Microsoft teams User name and teams user id | Имя пользователя из Teams приложения используется в другом приложении, которое вызывает сообщения электронной почты с именем пользователя в нем. и идентификатор пользователя, который мы сохраняем в качестве идентификатора и сопоставления его с&#8217;идентификатором пользователя. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Имя пользователя из Teams приложения используется в другом приложении, которое вызывает сообщения электронной почты с именем пользователя в нем. и идентификатор пользователя, который мы сохраняем в качестве идентификатора и сопоставления его с&#8217;идентификатором пользователя | Microsoft teams User name and teams user id | Имя пользователя из Teams приложения используется в другом приложении, которое вызывает сообщения электронной почты с именем пользователя в нем. и идентификатор пользователя, который мы сохраняем в качестве идентификатора и сопоставления его с&#8217;идентификатором пользователя |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы не контролируем данные, мы просто обработать данные.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена SHL о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
