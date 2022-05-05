---
title: Сведения о приложении для StealthMail от Stealthmail Software Ltd
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для StealthMail, политики обработки данных, сведения Microsoft Cloud App Security каталога приложений, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a0a31e0eceafbaa4188587411503514692c4b743
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225573"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 31 марта 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Просмотр в Teams хранилище</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Stealthmail Software Ltd корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | StealthMail |
| ID | WA200001748 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Название партнерской компании | Stealthmail Software Ltd |
| URL-адрес веб-сайта партнера | [https://stealthmail.com](https://stealthmail.com) |
| URL-адрес страницы Teams приложения | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| URL-адрес политики конфиденциальности | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| URL-адрес условий использования | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Stealthmail Software Ltd о том, как это приложение собирает и сохраняет данные организации, а также контроль над данными, собираемые приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>| **Разрешение**  | **Тип разрешения (делегированное или приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для хранения?** | **Azure AD приложения** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | Делегированные | Приложение отправляет сообщение в канал со ссылкой на созданную защищенную электронную почту. | Ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| ChannelMessage.Send | Делегированные | Приложение отправляет сообщение в канал со ссылкой на созданную защищенную электронную почту. | Ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| Chat.ReadWrite | Делегированные | Приложение отправляет сообщение в чат со ссылкой на созданную защищенную электронную почту | Ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| GroupMember.Read.All | Делегированные | Приложение получает участников канала для создания безопасной электронной почты для них | Ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.Read.All | Делегированные | Приложение получает участников чата для создания безопасной электронной почты для них | Ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.ReadBasic.All | Делегированные | Приложение получает участников чата для создания безопасной электронной почты для них | Ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| email | Делегированные | Проверка подлинности пользователя | nothing store в базе данных | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |


#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бот или расширение для обмена сообщениями, оно может получить доступ к идентифицируемой информации конечного пользователя (EUII): список (имя, фамилия, отображаемое имя, адрес электронной почты) любого участника команды или чата, в который оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не выполняется.


#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии или журналах приложений не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>Мы не можем контролировать данные партнеров в их системах.

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения об удостоверении

Эти сведения предоставлены stealthmail Software Ltd о том, как это приложение обрабатывает проверку подлинности, авторизацию, рекомендации по регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Вы интегрируете с Microsoft Identify Platform (Azure AD)?  | Да |
| Вы просматривали и соблюдали все применимые рекомендации, описанные в платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (библиотека проверки подлинности Майкрософт) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение минимальные разрешения для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мультитенантность? | Да |
| Имеет ли ваше приложение конфиденциальный клиент? | Нет |
| У вас есть все URI перенаправления, зарегистрированные для вашего приложения? | Да |
| Что не следует использовать для вашего приложения? | — URI перенаправления с подстановочными знаками,<br/>— неявные Flow OAuth2, если только это не требуется для одностраничного приложения;<br/>— Поток учетных данных пароля владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Разрешает ли модель разрешений выполнять вызовы только в том случае, если клиентское приложение получает соответствующее согласие? | Да |
| Использует ли ваше приложение API предварительной версии? | Да |
| Использует ли ваше приложение нерекомендуемые API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
