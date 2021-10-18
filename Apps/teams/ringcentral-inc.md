---
title: Сведения о приложениях для RingCentral от RingCentral, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для RingCentral, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 823ebf982464166302bca0fcb7690f3b9b444a88
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429797"
---
# <a name="ringcentral"></a>RingCentral

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 18 мая 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/2f285d77-896a-4c5f-901e-0902316003b5" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000135" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт в компании RingCentral, Inc.:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | RingCentral |
| Идентификатор | WA200000135 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | RingCentral, Inc. |
| URL-адрес веб-сайта-партнера | [https://www.ringcentral.com](https://www.ringcentral.com) |
| URL-адрес страницы Teams приложения | [https://www.ringcentral.com/apps/ringcentral-for-microsoft-...](https://www.ringcentral.com/apps/ringcentral-for-microsoft-teams) |
| URL-адрес политики конфиденциальности | [https://www.ringcentral.com/legal/privacy-notice.html](https://www.ringcentral.com/legal/privacy-notice.html) |
| URL-адрес терминов использования | [https://www.ringcentral.com/legal/last-update-October-15-20...](https://www.ringcentral.com/legal/last-update-October-15-2019/eulatos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена RingCentral, Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована |  Позволяет приложению отправлять приглашения на собрания через календарь | Отсутствует | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| offline_access | делегирована |  Позволяет приложению получать и обновлять маркер oauth |  Маркер доступа, маркер обновления для доступа к API Graph MS | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read | делегирована |  Позволяет приложению читать базовый профиль пользователя&#8217;(электронная почта, имя), чтобы связаться со совпадениями в конце. И позволяет пользователю войти и связать свою учетную запись O365 с учетной записью RingCentral |  Электронная почта, имя, фамилия | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read.All | делегирована | Позволяет приложению считывать полный профиль пользователя с номерами телефонов, чтобы сделать телефонные звонки с помощью наших служб. | Отсутствует | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |


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

>Если мы используем другую организацию, мы по-прежнему контролируем ваши персональные данные. И у нас есть строгие элементы управления, чтобы убедиться, что&#8217;защищены. Наконец, в разделе выше описываются ситуации, в которых ваши персональные данные делятся с другими организациями, государственными органами и правоохранительными органами.  Когда мы делимся вашими сведениями с другими организациями,&#8217;мы убедимся, что&#8217;защищена, насколько это возможно.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация была предоставлена RingCentral, Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
