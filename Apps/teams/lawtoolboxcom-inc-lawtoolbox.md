---
title: Сведения о приложениях для LawToolBox LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для LawToolBox, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0bf192e58d66e43bfe64d237dffe4a8f2c33c8ce
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251298"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией LawToolBox.com Inc. в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | LawToolBox |
| ID | WA104381656 |
| Возможности | Бот, вкладка, расширение для обмена сообщениями |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | LawToolBox.com Inc. |
| URL-адрес веб-сайта-партнера | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL-адрес страницы Teams приложения | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL-адрес политики конфиденциальности | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL-адрес терминов использования | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены LawToolBox.com Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | делегирована |  | [Необязательный] Чтение календаря пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | делегирована |  | Создание приглашения календаря в календарь пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | делегирована |  | Создание приглашения календаря в общий календарь. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | делегирована |  | [Необязательный] — чтение контактов пользователей и подключение пользователей из списка контактов к группе. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | делегирована |  | [Необязательный] — чтение общих контактов пользователей для обслуживания списка контактов, соответствующих делу. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | делегирована |  | [Необязательный] Чтение сведений о группах и пользователях в качестве пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | делегирована |  | [Необязательный] Чтение сведений о группах и пользователях в качестве пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | делегирована |  | [Необязательный] Ознакомьтесь с OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | делегирована |  | [Необязательный]-Чтение OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | делегирована |  | [Необязательный]-Чтение и изменение файлов в OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | делегирована |  | [Необязательный] Файл чтения и записи OneDrive, связанный с значением. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | делегирована | GroupID, GroupName, GroupEmail | Мы создаем группу для каждого вопроса, созданного в нашей системе. Это помогает пользователю сохранять сведения, связанные с вопросами, в Группу, что, в свою очередь, сохраняет их данные в собственном клиенте. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | делегирована |  | [Необязательный] [InProgress] Чтение электронной почты пользователя для вопросов. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | делегирована |  | [Необязательный] [InProgress] Чтение и написание электронной почты для пользователей. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | делегирована |  | [Необязательный] [InProgress] Чтение и написание электронной почты для пользователей. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | делегирована |  | [Необязательный] [InProgress] Отправка крайних сроков по электронной почте в качестве пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | делегирована |  | [Необязательный]-[InProgress] Читайте Сроки записи в качестве задачи для пользователей. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | делегирована |  | Чтение сведений пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | делегирована |  | Read/Write user's Information. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | делегирована |  | Read/Write user's Information. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | делегирована | Электронная почта, UserID Office365, ObjectID, TenantID. | Ознакомьтесь с адресом электронной почты пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| profile | делегирована |  | Чтение сведений о профиле пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Определение вновь добавленного пользователя в команду и проверка потенциального свинца | Электронная почта, UserId |  |



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Сведения о пользователях электронной почты, userID, AccessToken, Groups в нашем журнале отладки

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы сохраняем записи о случаях, если не получим запрос на удаление данных.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

