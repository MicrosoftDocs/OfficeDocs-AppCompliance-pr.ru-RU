---
title: Сведения о приложениях для dice disasterTech от DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для DICE DisasterTech, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9aceaf48c36012ad8c6eb062c1161746d55da6a
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281924"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 24 августа 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые службой DisasterTech Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | DisasterTech DICE |
| Идентификатор | WA200001909 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | DisasterTech |
| URL-адрес веб-сайта-партнера | [https://www.disastertech.com](https://www.disastertech.com) |
| URL-адрес политики конфиденциальности | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL-адрес терминов использования | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена disasterTech о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | делегирована | Адрес электронной почты пользователя, хранимый для установления прав доступа, а также имени пользователя для идентификации пользователей по имени | Позволяет пользователю войти в систему и предоставляет приложению доступ к его upN, чтобы включить бесшумный вход, а также Teams входа, а также установить имена пользователей и адреса электронной почты. | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| email | делегирована | Нет. | Требуется для Teams одноместных Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | делегирована | Нет. | Требуется для Teams одноместных Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| openid | делегирована | Нет. | Требуется для Teams одноместных Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| profile | делегирована | Нет. | Требуется для Teams одного входного знака. | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы храним имя пользователя, имя и фамилию в базе данных PostgreSQL, размещенной в Azure, чтобы позволить пользователям совместно работать в приложении. Элементы управления: прямой доступ к базе данных имеют только сотрудники службы аварийной техники. Когда пользователь удаляется из приложения, мы архивировать информацию. Пользователи имеют право удалять свои персональные данные из системы в любое время. Однако удаление таких сведений также запрещает их использование приложения.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные приложения хранятся в базе данных PostgreSQL в Azure, которая зашифрована в покое. Ни один пользователь не имеет прямого доступа к базе данных или интерфейсу API заднего конца. Все вызовы API защищены маркером доступа Active Directory.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

