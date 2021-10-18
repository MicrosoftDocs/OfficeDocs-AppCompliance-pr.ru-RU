---
title: Сведения о приложениях для ezTeam от EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для ezTeam, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8a058d3d4e8d96a0c915585e75b7c0e53c2f2341
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428806"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 24 февраля 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Корпорацией Майкрософт от EnterprizID Inc.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | ezTeam |
| Идентификатор | WA200002546 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | EnterprizID Inc |
| URL-адрес веб-сайта-партнера | [https://enterprizid.com](https://enterprizid.com) |
| URL-адрес страницы Teams приложения | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL-адрес политики конфиденциальности | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL-адрес терминов использования | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена организацией EnterprizID Inc о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | делегирована | Список приложений, доступных в Teams, чтобы мы могли показать его в Teams процессе создания запроса | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Application.Read.All | делегирована | Позволяет приложению читать приложения и субъекты-службы от имени вошедшего пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.AccessAsUser.All | делегирована | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | делегирована | Позволяет приложению читать данные в каталоге вашей организации, такие как сведения о пользователях, группах и приложениях. | Teams Сведения о владении и членстве  | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.Read.All | приложение | Позволяет приложению считывать данные в каталоге вашей организации, такие как группы, пользователи и приложения, в случаях, когда вход пользователя не предусмотрен. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | делегирована | Позволяет приложению читать и записывать данные в каталоге организации, такие как пользователи и группы | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Directory.ReadWrite.All | приложение | Позволяет приложению читать и записывать данные в каталоге вашей организации, например пользователей и группы, без вошедшего пользователя. Не позволяет удалять пользователей или группы. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Files.Read.All | приложение | Позволяет приложению считывать все файлы во всех семействах веб-сайтов без пользователя, выполнившего вход в систему. | Объем данных под управлением конечного пользователя в ГБ | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Create | приложение | Позволяет приложению создавать группы без подписанного пользователя. | Новые сведения о свойствах группы. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | делегирована | Приложение сможет выводить список групп, а также просматривать их свойства и все данные о членстве в группах от имени вошедшего пользователя. Используется для определения Teams  | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.Read.All | приложение | Позволяет приложению читать свойства и членство в группах, а также читать календарь и беседы для всех групп без подписывного пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | делегирована | Приложение сможет создавать группы, а также просматривать все их свойства и данные о членстве от имени вошедшего пользователя.  | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Group.ReadWrite.All | приложение | Позволяет приложению создавать группы, читать все свойства и членство группы, обновлять свойства и членство групп и удалять группы. Кроме того, приложение может читать и записывать групповой календарь и беседы.  | Последнее действие группы. | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.Read.All | приложение | Позволяет приложению считывать сведения об участии и основные свойства для всех групп без необходимости входа пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| GroupMember.ReadWrite.All | приложение | Позволяет приложению перечислять группы, читать основные свойства, читать и обновлять сведения об участии в группах, к которым у приложения есть доступ без необходимости входа пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| People.Read.All | приложение | Позволяет приложению читать забитый пользователем список соответствующих людей без подписаного пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | делегирована | Позволяет приложению читать все отчеты об использовании служб от имени вошедшего пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Reports.Read.All | приложение | Позволяет приложению читать все отчеты об использовании без вошедшего пользователя. | Последняя активность пользователя в группе | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| Sites.ReadWrite.All | приложение | Позволяет приложению создавать, считывать, изменять и удалять документы и элементы списков во всех семействах веб-сайтов без пользователя, выполнившего вход в систему. | Топ-10 сайтов по размеру для каждого пользователя | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read | делегирована | Пользователи смогут входить в приложение, а оно сможет просматривать профили вошедших пользователей. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| User.Read.All | приложение | Позволяет приложению читать профили пользователей без подписи пользователя. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| offline_access | делегирована | Позволяет приложению видеть и обновлять данные, к которые вы предоставили ему доступ, даже если пользователи в настоящее время не используют приложение.  | Уведомления бота | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| openid | делегирована | Пользователи смогут входить в приложение с помощью своей рабочей или учебной учетной записи, а приложение сможет просматривать основные данные профилей пользователей. | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |
>| profile | делегирована | Позволяет приложению видеть базовый профиль пользователей (имя, изображение, имя пользователя) | Недоступно | [2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Приветствие сообщений, утверждений и процессов проверки | Мы храним имя отображения удостоверений  | Наш инструмент позволяет конечным пользователям создавать запросы для различных элементов службы, и мы храним имя отображения запрашиваемого пользователя. Запрос будет следовать рабочего процесса утверждения, и нам нужно имя отображения утверждения, чтобы показать в подробностях запроса. Кроме того, в членах процесса сертификации группы мы перечисляем отображаемого имени участников. |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>EndUser и Organization Full Name. Политики хранения и удаления можно найти в разделе https://enterprizid.com/privacy-policy &quot; Хранение персональных &quot; данных

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы включили управление привилегированным доступом (PMA) в Azure, а удостоверения с привилегией подключаться к ресурсам используют 2FA для повышения безопасности. Мы используем Azure в качестве поставщика облачных партнеров и подвергаемся конфиденциальности и условиям использования Azure

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация была предоставлена EnterprizID Inc о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
