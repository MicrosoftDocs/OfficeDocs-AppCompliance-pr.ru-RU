---
title: Сведения о приложениях для MailClark от MailClark
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для MailClark, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3e9c01b76c513fd0786b27a0447a70c1f9c9d7e0
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286382"
---
# <a name="mailclark"></a>MailClark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/64f174e8-7e14-4b48-871e-2fb7b17be302" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381679" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные MailClark корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | MailClark |
| Идентификатор | WA104381679 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | MailClark |
| URL-адрес веб-сайта-партнера | [https://mailclark.ai/microsoft-teams-integration](https://mailclark.ai/microsoft-teams-integration) |
| URL-адрес страницы Teams приложения | [https://mailclark.ai/support](https://mailclark.ai/support) |
| URL-адрес политики конфиденциальности | [https://mailclark.ai/privacy](https://mailclark.ai/privacy) |
| URL-адрес терминов использования | [https://mailclark.ai/tos](https://mailclark.ai/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена MailClark о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite | приложение |  | Читайте также: Подписаться на push-уведомления для входящих сообщений электронной почты. Write: Создание черновиков. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Send | приложение |  | Отправка черновиков. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | приложение | Сведения об учетной записи, например адрес электронной почты. | Определение учетной записи. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | приложение | Маркер обновления | Возобновление проверки подлинности до отключения учетной записи. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | приложение |  | Обязательное для проверки подлинности. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | приложение |  | Проверка подлинности пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Назначение людей для бесед | Имя, фамилия, имя отображения, адрес электронной почты |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>ID клиента, пользовательский ИД (адрес электронной почты)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>В рамках соответствия GDPR администраторы могут запрашивать удаления, доступ к данным и другие сведения (см. статью Legal).


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35675' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35675" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

