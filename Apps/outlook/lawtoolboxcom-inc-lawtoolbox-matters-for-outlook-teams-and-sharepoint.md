---
title: Сведения о приложениях для LawToolBox важны для Outlook, Teams &amp; SharePoint по LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для LawToolBox Matters для Outlook, Teams SharePoint, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре &amp; CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 450fd7c5f0752d523fb94e59308f8f339c95fad8
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428676"
---
# <a name="lawtoolbox-matters-for-outlook-teams-amp-sharepoint"></a>LawToolBox имеет значение для Outlook, Teams &amp; SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 24 июня 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003103" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией LawToolBox.com Inc. в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | LawToolBox имеет значение для Outlook, Teams &amp; SharePoint |
| Идентификатор | WA200003103 |
| Office 365 поддерживаемые клиенты | Outlook 2013 или более поздней Windows, Outlook 2016 или более поздней Outlook в Интернете |
| Имя компании-партнера | LawToolBox.com Inc. |
| URL-адрес веб-сайта-партнера | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL-адрес политики конфиденциальности | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL-адрес терминов использования | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены LawToolBox.com Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | делегирована | это разрешение ограничивает доступ к контактам пользователей&#8217;, к которые они уже имеют доступ&#8211; мы используем это, чтобы позволить пользователям получать собственные данные календаря | [Необязательный] Чтение календаря пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | делегирована | это разрешение ограничивает доступ к контактам пользователей&#8217;, к которые они уже имеют доступ&#8211; мы используем это, чтобы позволить пользователям получать собственные данные календаря и записываться в календари | Создание приглашения календаря в календарь пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | делегирована | это разрешение ограничивает доступ к контактам пользователей&#8217;, к которые они уже имеют доступ&#8211; мы используем это, чтобы позволить пользователям получать собственные данные календаря | Создание приглашения календаря в общий календарь. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | делегирована | это разрешение ограничивает доступ к контактам&#8217;, к которые они уже имеют доступ.  Мы используем это разрешение, чтобы разрешить пользователю искать их контакты O365 и добавлять в LawToolBox &#8211; мы не добавляем автоматически никаких контактов (это может быть отменено, если вы не хотите, чтобы эта функция и контакты можно добавлять вручную. | [Необязательный] — чтение контактов пользователей и подключение пользователей из списка контактов к группе. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | делегирована | мы используем это разрешение, чтобы разрешить пользователю искать общие контакты O365 и добавлять в LawToolBox &#8211; мы не добавляем автоматически никаких контактов | [Необязательный] — чтение общих контактов пользователей для обслуживания списка контактов, соответствующих делу. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | делегирована | мы используем на портале администрирования для получения списка пользователей из клиента O365 для добавления в учетную запись | [Необязательный] Чтение сведений о группах и пользователях в качестве пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | делегирована | мы используем на портале администрирования для получения списка пользователей из клиента O365 для добавления в учетную запись | [Необязательный] Чтение сведений о группах и пользователях в качестве пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | делегирована | это позволяет надстройку читать и перечислять файлы пользователей, к которые пользователь уже имеет доступ. | [Необязательный] Ознакомьтесь с OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | делегирована | мы используем это разрешение для чтения и списка пользовательских файлов, к которые пользователь уже имеет доступ | [Необязательный]-Чтение OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | делегирована | мы читаем файлы из Teams, групп и OneDrive для собраний (если вы отзовете, это не позволит нашему надстройке перечислять файлы материи в наших приложениях) | [Необязательный]-Чтение и изменение файлов в OneDrive. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | делегирована | мы читаем файлы из Teams, групп и OneDrive для собраний (если вы отзовете, это не позволит LTB перечислять файлы материи в наших приложениях).  Пользователь может использовать надстройку только для чтения и списка пользовательских файлов, к которые пользователь уже имеет доступ | [Необязательный] Файл чтения и записи OneDrive, связанный с значением. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | делегирована | GroupID, GroupName, GroupEmail | Мы создаем группу для каждого вопроса, созданного в нашей системе. Это помогает пользователю сохранять сведения, связанные с вопросами, в Группу, что, в свою очередь, сохраняет их данные в собственном клиенте. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | делегирована | мы используем это разрешение для чтения писем PACER в надстройке outlook для автоматического открытия этого значения, а также для чтения контактов из электронной почты для добавления в нашу контактную систему  | [Необязательный] [InProgress] Чтение электронной почты пользователя для вопросов. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | делегирована | мы используем это разрешение для чтения писем PACER в надстройке outlook для автоматического открытия этого значения, а также для чтения контактов из электронной почты для добавления в нашу контактную систему  | [Необязательный] [InProgress] Чтение и написание электронной почты для пользователей. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | делегирована | мы используем это разрешение для чтения писем PACER в надстройке outlook для автоматического открытия этого значения, а также для чтения контактов из электронной почты для добавления в нашу контактную систему  | [Необязательный] [InProgress] Чтение и написание электронной почты для пользователей. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | делегирована | Мы используем эту отправку электронных писем в качестве пользователя, чтобы позволить пользователю отправлять отчеты только о данных, к которые у них уже есть доступ в нашей системе. | [Необязательный] [InProgress] Отправка крайних сроков по электронной почте в качестве пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | делегирована | это разрешение ограничивает доступ к задачам&#8217;, которые у них уже есть доступ к &#8211; мы используем это, чтобы позволить пользователям получать и обновлять свои собственные данные TASK.  | [Необязательный]-[InProgress] Читайте Сроки записи в качестве задачи для пользователей. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | делегирована | используется для добавления последних контактов в собрания или контакты | Чтение сведений пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | делегирована | используется для добавления последних контактов в собрания или контакты | Read/Write user's Information. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | делегирована | это необходимо для чтения API Teams, создания Teams, создания события календаря, создания каналов, Teams функции обмена файлами | Read/Write user's Information. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| email | делегирована | Электронная почта, UserID Office365, ObjectID, TenantID. | Ознакомьтесь с адресом электронной почты пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| profile | делегирована | это необходимо для проверки подлинности SSO — мы также используем это разрешение для получения изображений и имен, сохраненных на клиенте M365, чтобы отобразить их, чтобы пользователь знал, что они находятся в правильном ящике инструментов. | Чтение сведений о профиле пользователя. | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Сведения о пользователях электронной почты, userID, AccessToken, Groups в нашем журнале отладки

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы сохраняем записи о случаях, если не получим запрос на удаление данных.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена LawToolBox.com Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | Для более большого администратора управления можно реализовать разрешения приложений |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | ,<br/>- Неявные Flow OAuth2, если не требуется spa<br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
