---
title: Сведения о приложениях для BlackBerry AtHoc по BlackBerry
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для BlackBerry AtHoc, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 38d1d54293b3f406a0a5c8028850dae27a9c9294
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284081"
---
# <a name="blackberry-athoc"></a>BlackBerry AtHoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003065" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые BlackBerry Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | BlackBerry AtHoc |
| Идентификатор | WA200003065 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | BlackBerry |
| URL-адрес веб-сайта-партнера | [https://www.blackberry.com](https://www.blackberry.com) |
| URL-адрес страницы Teams приложения | [https://www.blackberry.com/us/en/products/blackberry-athoc](https://www.blackberry.com/us/en/products/blackberry-athoc) |
| URL-адрес политики конфиденциальности | [https://www.blackberry.com/us/en/legal/privacy-policy](https://www.blackberry.com/us/en/legal/privacy-policy) |
| URL-адрес терминов использования | [https://www.athoc.com/pss/terms.html#](https://www.athoc.com/pss/terms.html#) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена BlackBerry о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | делегирована | Для отправки карты оповещения в группы мы&#8217;основные сведения пользователя, такие как имя principal и ссылку на общий канал teams (для которого подписан пользователь. | Мы не&#8217;хранить данные пользователей в базе данных, а в памяти Бота. Мы храним подписанный в основном имени пользователя, маркер AAD, маркер BlackBerry AtHoc, параметры BlackBerry AtHoc Server в памяти бота. Нужна информация для отправки запроса API в API Microsoft Graph и нашему серверу AtHoc BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Group.Read.All | делегирована | Для отправки карты оповещения в группы мы&#8217;основные сведения пользователя, такие как имя principal и ссылку на общий канал teams (для которого подписан пользователь. | Мы не&#8217;хранить данные пользователей в базе данных, а в памяти Бота. Мы храним подписанный в основном имени пользователя, маркер AAD, маркер BlackBerry AtHoc, параметры BlackBerry AtHoc Server в памяти бота. Нужна информация для отправки запроса API в API Microsoft Graph и нашему серверу AtHoc BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| User.Read | делегирована | Для отправки карты оповещения в группы мы&#8217;основные сведения пользователя, такие как имя principal и ссылку на общий канал teams (для которого подписан пользователь. | Мы не&#8217;хранить данные пользователей в базе данных, а в памяти Бота. Мы храним подписанный в основном имени пользователя, маркер AAD, маркер BlackBerry AtHoc, параметры BlackBerry AtHoc Server в памяти бота. Нужна информация для отправки запроса API в API Microsoft Graph и нашему серверу AtHoc BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| email | делегирована | Для отправки карты оповещения в группы мы&#8217;основные сведения пользователя, такие как имя principal и ссылку на общий канал teams (для которого подписан пользователь. | Мы не&#8217;хранить данные пользователей в базе данных, а в памяти Бота. Мы храним подписанный в основном имени пользователя, маркер AAD, маркер BlackBerry AtHoc, параметры BlackBerry AtHoc Server в памяти бота. Нужна информация для отправки запроса API в API Microsoft Graph и нашему серверу AtHoc BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| openid | делегирована | Для отправки карты оповещения в группы мы&#8217;основные сведения пользователя, такие как имя principal и ссылку на общий канал teams (для которого подписан пользователь. | Мы не&#8217;хранить данные пользователей в базе данных, а в памяти Бота. Мы храним подписанный в основном имени пользователя, маркер AAD, маркер BlackBerry AtHoc, параметры BlackBerry AtHoc Server в памяти бота. Нужна информация для отправки запроса API в API Microsoft Graph и нашему серверу AtHoc BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| profile | делегирована | Для отправки карты оповещения в группы мы&#8217;основные сведения пользователя, такие как имя principal и ссылку на общий канал teams (для которого подписан пользователь. | Мы не&#8217;хранить данные пользователей в базе данных, а в памяти Бота. Мы храним подписанный в основном имени пользователя, маркер AAD, маркер BlackBerry AtHoc, параметры BlackBerry AtHoc Server в памяти бота. Нужна информация для отправки запроса API в API Microsoft Graph и нашему серверу AtHoc BlackBerry. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |


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

>Н/Д

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация была предоставлена BlackBerry о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
