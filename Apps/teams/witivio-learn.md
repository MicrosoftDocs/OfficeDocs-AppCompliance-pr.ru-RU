---
title: Сведения о приложениях для получения с помощью Witivio
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Learn, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f931e75f0a5736ffa49c7366d9928db774c4bdbf
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59289230"
---
# <a name="learn"></a>Узнать

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 31 марта 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Witivio Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Узнать |
| Идентификатор | WA200001308 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Witivio |
| URL-адрес веб-сайта-партнера | [https://www.witivio.com](https://www.witivio.com) |
| URL-адрес политики конфиденциальности | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| URL-адрес терминов использования | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена Witivio о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | делегирована | Н/Д | Мы собираем upN и AAD ID для авторизации. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| User.ReadBasic.All | делегирована | Н/Д | Мы собираем upN и AAD ID для авторизации. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| openid | делегирована | Н/Д | Мы собираем upN и AAD ID для авторизации. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| profile | делегирована | Н/Д | Мы собираем upN и AAD ID для авторизации. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Мы используем реестр для: 1) авторизация (предоставление доступа к боту), 2) обнаружение первого имени для предоставления дружественного UX, 3) Для управления чатами для бизнес-администратора бота | N/A. Или боты только личные |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Телеметрия бота содержит диагностику upN и AAD ID fr.
Доступ к производственной телеметрии имеют только администраторы PROD/Run. Журналы хранятся в течение 90 дней и могут быть удалены по запросу на специальном портале support.witivio.com или по электронной почте dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Witivio использует только компоненты Azure, развернутые в регионе Северной Европы. Мы используем анализ приложений и Cosmos DB для анализа данных и хранения данных..
Witivio использует MFA для всех пользователей, включая администраторов. Администраторы имеют учетную запись пользователя (для рабочей станции) и привилегированную учетную запись для доступа к ressources Azure.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

