---
title: Сведения о приложениях для виртуального слушания Casedoc по Casedoc
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для виртуального слуха Casedoc, политики обработки данных, сведения Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 49c51cff0f00b33f25b22eb73bde4382be10c6ba
ms.sourcegitcommit: b97ed9e84303967085e6f3f93c80f7b97110194c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/29/2021
ms.locfileid: "59992240"
---
# <a name="casedoc-virtual-hearing"></a>Виртуальный слух Casedoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 28 сентября 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/3e701664-cc46-49e4-b356-1a7ac6500998" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003164" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Casedoc Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Виртуальный слух Casedoc |
| ID | WA200003164 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Casedoc |
| URL-адрес веб-сайта-партнера | [https://www.casedoc.com](https://www.casedoc.com) |
| URL-адрес страницы Teams приложения | [https://casedoc.com/virtual-hearing-for-teams/](https://casedoc.com/virtual-hearing-for-teams/) |
| URL-адрес политики конфиденциальности | [https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Priv...](https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Privacy_Policy_2021.pdf) |
| URL-адрес терминов использования | [https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Cust...](https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Customer_Agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена Casedoc о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | делегирована | Приложение Lookup для добавления в вкладку "Собрание" | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Calendars.ReadWrite | приложение | Просмотр событий календаря пользователей списка, используемых для отображения списка собраний и данных из события в приложении. | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Directory.ReadWrite.All | приложение | Данные не собираются | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Files.ReadWrite.All | приложение | Файлы списков, загруженные приложением | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Group.ReadWrite.All | приложение | Данные не собираются | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| MailboxSettings.Read | приложение | Параметры электронной почты пользователей, часовой пояс. Используется для отображения правильного пояса времени для пользователя | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| OnlineMeetings.ReadWrite | делегирована | Считыв и храня данные собраний, они используются для отображения данных собраний в приложении | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadForUser | делегирована | Список приложения, установленного для пользователя, используется для добавления приложения на вкладку "Собрание". | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadWriteForUser | делегирована | Используется для добавления приложения на вкладку "Собрание". | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.Create | делегирована | Используется для добавления вкладки к собранию. | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.ReadWrite.All | делегирована | Используется для добавления вкладки к собранию. | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| User.Read.All | приложение | Используется для того, чтобы искать пользователей для собраний. | Данные не хранятся | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Журналы аудита, хранение в рамках политики ISMS, ISO 27001

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Недоступно

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена Casedoc о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/><br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Нет |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
