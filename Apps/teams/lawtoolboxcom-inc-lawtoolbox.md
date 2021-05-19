---
title: Информация о применении для LawToolBox от LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для LawToolBox, политики обработки данных, Microsoft Cloud App Security каталога приложений и информации о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2e97d65822a5baeb0cd78101660084e4142e98ea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553010"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная LawToolBox.com Inc. корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | LawToolBox |
| ID | WA104381656 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | LawToolBox.com Inc. |
| URL-адрес веб-сайта партнера | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL-адрес Teams страницы информации о приложениях | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL политики конфиденциальности | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL условий использования | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена LawToolBox.com Inc. о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Делегированные |  | (По желанию) Читайте календарь пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | Делегированные |  | Для создания календаря приглашаем в календарь пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | Делегированные |  | Для создания календаря приглашаем в общий календарь. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | Делегированные |  | (Необязательно) - читать контакты пользователей и соединять пользователей из списка контактов в группу. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | Делегированные |  | (Необязательно) - читать пользователей общие контакты, чтобы служить список контактов, имеющих отношение к делу. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | Делегированные |  | (По желанию) Читайте информацию о группах и пользователях в качестве пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | Делегированные |  | (По желанию) Читайте информацию о группах и пользователях в качестве пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | Делегированные |  | (По желанию) Читайте отзывы пользователей OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | Делегированные |  | (Необязательно) - Прочитайте отзывы OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | Делегированные |  | «Необязательно» читать и изменять файлы в OneDrive. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | Делегированные |  | (По желанию) Читать/писать файл OneDrive связанный с материей. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | Делегированные | GroupID, GroupName, GroupEmail | Мы создаем группу для каждого вопроса, созданного в нашей системе. Это помогает пользователю хранит информацию, связанную с материей, в Группе, что, в свою очередь, сохраняет их данные в собственном арендаторе. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | Делегированные |  | (По желанию) (InProgress) Читайте электронную почту пользователя для вопросов. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | Делегированные |  | (По желанию) (InProgress) Читать/писать электронную почту для пользователей. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | Делегированные |  | (По желанию) (InProgress) Читать/писать электронную почту для пользователей. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | Делегированные |  | (По желанию) (InProgress) Отправить Сроки по электронной почте в качестве пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | Делегированные |  | «Необязательно» - «InProgress» Читать Написать сроки в качестве задачи для пользователей. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | Делегированные |  | Читайте информацию пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | Делегированные |  | Читать/писать информацию пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | Делегированные |  | Читать/писать информацию пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | Делегированные | Электронная почта, Office365 UserID, ObjectID, TenantID. | Прочитайте адрес электронной почты пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| profile | Делегированные |  | Читайте информацию о профиле пользователя. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Определить вновь добавленного пользователя в группу и проверить потенциальный зацеп | Электронная почта, UserId |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Электронная почта пользователя, UserID, AccessToken, информация групп в нашем журнале отладки

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Мы сохраняем записи о случаях, если не получим запрос на удаление данных.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

