---
title: Сведения о приложениях для 365Projects по 365Apps
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для 365Projects, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 30670ebb5d80435dfbe77b3e735aeb72a695907c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430921"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 марта 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые 365Apps в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | 365Projects |
| Идентификатор | WA200002160 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | 365Apps |
| URL-адрес веб-сайта-партнера | [https://365apps.com.au](https://365apps.com.au) |
| URL-адрес страницы Teams приложения | [https://365projects.app](https://365projects.app) |
| URL-адрес политики конфиденциальности | [https://365projects.app/privacy](https://365projects.app/privacy) |
| URL-адрес терминов использования | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены 365Apps о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | делегирована | каналы в команде для связи проекта с каналом | каналы в команде для связи проекта с каналом | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.Read.All | делегирована | получите задачи планировщика и планировщика, будет лучше, если еще одна область наименьших привилегий позволит приложению получать пользовательские планы и задачи планов, но, к сожалению, нет областей, которые позволяют это | не хранить в DB | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Group.ReadWrite.All | приложение | Создание Teams  | не хранится в DB | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| People.Read | делегирована | имя пользователя, чтобы добавить их в качестве членов группы или назначить им задачи | Guid пользователя хранится в назначении задачи | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| Team.ReadBasic.All | делегирована | Присоединились к именам команд, чтобы связать проект с Teams каналом | Team Guid хранится в метаданных проекта, чтобы установить ссылку | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read | делегирована | получение сведений о пользователях, чтобы показать их в загонах  | электронная почта пользователя хранится в качестве владельца при первом предоставлении клиента | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |
>| User.Read.All | делегирована | чтение пользователей для обновления назначения задач | только guid пользователя не хранится личная идентифицированная информация не хранится в DB | [99a0a9b1-5d28-45df-9f99-792aa32795f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/99a0a9b1-5d28-45df-9f99-792aa32795f4) |


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

>Приложение не хранит пользовательские данные отдельно от Guid администратора приложения (первый пользователь использует приложение в клиенте) 

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены 365Apps о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | ,<br/>- Неявные Flow OAuth2, если не требуется spa<br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
