---
title: Сведения о приложениях для SecretaryBot от MySecretary
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для SecretaryBot, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8d7e2fce37cf43fe52cb050e85aa9e4fd5e00802
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287377"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные MySecretary Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | SecretaryBot |
| Идентификатор | WA104381085 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | MySecretary |
| URL-адрес веб-сайта-партнера | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| URL-адрес страницы Teams приложения | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| URL-адрес политики конфиденциальности | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| URL-адрес терминов использования | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена MySecretary о том, как это приложение собирает и хранит организационные данные, а также о контроле, которое будет иметь организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | делегирована |  | Извлечение сведений о свободном времени пользователя и его коллег. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Calendars.ReadWrite | делегирована |  | Отправка запроса на собрание вместо пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.Read | делегирована | Хранить язык для показа правильного лангажа. Сохранение зоны времени для правильного вызова API Graph календаря | Извлечение параметров языка и часового пояса пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| People.Read | делегирована |  | Попробуйте найти коллег, которые имеют прочные отношения с пользователем. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | делегирована | Store username, city, country and langauge for user analytics. Хранение электронной почты для контакта с клиентом. Мы никогда не использовали адрес электронной почты, но можем использовать для поддержки. | Попробуйте найти страну пользователя и предпочтительный язык. Он используется для резервного копирования для mailboxSettings.Read. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| email | делегирована | описание выше. | Для хранения электронной почты. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | делегирована |  | Для проверки подлинности OpenID. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | делегирована | Сохранение OID для идентификации уникального идентификатора пользователя в системе удостоверений MS. | Получение имени пользователя и OID. Попробуйте использовать OID для подключения Outlook addin в будущем. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Используйте эту инфромацию, чтобы запланировать собрание группы | Нет |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Данные OII или EUII действительно отображаются в телеметрии или журналах.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы пока не предоставляем администрирование конечным пользователям, но если конечные пользователи просят удалить данные, мы можем следовать их запросу.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

