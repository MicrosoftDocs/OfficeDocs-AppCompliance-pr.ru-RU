---
title: Сведения о приложениях для HeyTaco! По HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 09/09/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствия требованиям для HeyTaco!, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 72a600a577b773f1e3de08c7ef10b15b8007d52b
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444878"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 ноября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные HeyTaco! в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | HeyTaco! |
| Идентификатор | WA200001346 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | HeyTaco! |
| URL-адрес веб-сайта-партнера | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL-адрес политики конфиденциальности | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL-адрес терминов использования | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена HeyTaco! о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет иметь контроль над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | делегирована | используется для совпадения пользователя для передачи данных из Slack в MS Teams | используется для совпадения пользователя для передачи данных из Slack в MS Team | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| openid | делегирована | используется для регистрации человека в HeyTaco! | используется для регистрации человека в HeyTaco! | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| profile | делегирована | используется для захвата имени пользователя, изображения профиля, смещения пояса времени, id клиента и id команды | используется для захвата имени пользователя, аватара, смещения пояса времени, id клиента и id команды | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Чтобы сообщить пользователю, от кого он получил тако. | Адрес электронной почты (для переноса тако с одной платформы на другую) Имя (для приветствия пользователя) Изображение профиля (для отображения на таблице лидеров) Timezone (для правильного отображения тако на странице действия) ID клиента (Для агрегации данных клиентом) Team ID (Для агрегации данных по команде)  |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>EUII и OII не подключены к любым журналам. Только типы ошибок и типы действий.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>HeyTaco! базы данных и резервные копии данных находятся в Веб-службах Amazon (AWS). 

Операции центра обработки данных Amazon аккредитованы в рамках ISO 27001, SOC 1 и SOC 2/SSAE 16/ISAE 3402 (ранее SAS 70 Type II), PCI Level 1, FISMA Moderate и Sarbanes-Oxley (SOX).

При отправке сведений через нашу службу ваша информация защищена и шифруется как в покое, так и в пути с помощью безопасных подключений. Мы реализуем различные меры безопасности для обеспечения безопасности ваших персональных данных.

Для защиты данных на наших серверах у нас есть управление привилегированным доступом.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

