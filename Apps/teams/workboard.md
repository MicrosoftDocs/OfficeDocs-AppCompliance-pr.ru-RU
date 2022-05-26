---
title: Сведения о приложении для workboard by Workboard
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Просмотрите все доступные сведения о безопасности и соответствии для Workboard, ее политики обработки данных, сведения Microsoft Cloud App Security каталога приложений, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ccf27f1fa0c6db96446fc0fa7afc686fe2a49e20
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/26/2022
ms.locfileid: "65688104"
---
# <a name="application-information-for-workboard"></a>Сведения о приложении для Workboard

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 4 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/28d0282b-3cd2-49f0-90bb-a016843750c6" target="_blank">Просмотр в Teams хранилище</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381599" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Workboard корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Workboard |
| ID | WA104381599 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Название партнерской компании | Workboard |
| URL-адрес веб-сайта партнера | [https://www.workboard.com](https://www.workboard.com) |
| URL-адрес страницы Teams приложения | [https://www.workboard.com/microsoft/](https://www.workboard.com/microsoft/) |
| URL-адрес политики конфиденциальности | [https://www.workboard.com/license/privacy-policy.html](https://www.workboard.com/license/privacy-policy.html) |
| URL-адрес условий использования | [https://www.workboard.com/license/terms_of_use_v1.php](https://www.workboard.com/license/terms_of_use_v1.php) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена рабочей областью о том, как это приложение собирает и сохраняет данные организации, а также о том, как ваша организация будет управлять данными, собранными приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>| **Разрешение**  | **Тип разрешения (делегированное или приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для хранения?** | **Azure AD приложения** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Делегированные | адрес электронной почты и идентификаторы пользователей.  Он используется для сопоставления пользователя с идентификатором пользователя WorkBoard. | WorkBoard хранит только удостоверение пользователя в своих базах данных. | [User.Read](/graph/permissions-reference#user-permissions) |


#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бот или расширение для обмена сообщениями, оно может получить доступ к идентифицируемой информации конечного пользователя (EUII): список (имя, фамилия, отображаемое имя, адрес электронной почты) любого участника команды или чата, в который оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование для доступа к EUII?**  | **Хранится ли EUII в базах данных?** | **Обоснование для хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Идентификатор пользователя используется для упреждающих уведомлений, отправляемых Teams WorkBord | Адрес и идентификатор электронной почты пользователя | Используется для сопоставления пользователя с идентификатором пользователя WorkBoard |


#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии или журналах приложений не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>WorkBoard не хранит данные организации в партнерских системах

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения об удостоверении

Эта информация предоставлена рабочей областью о том, как это приложение обрабатывает проверку подлинности, авторизацию, рекомендации по регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Вы интегрируете с Microsoft Identify Platform (Azure AD)?  | Да |
| Вы просматривали и соблюдали все применимые рекомендации, описанные в платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (библиотека проверки подлинности Майкрософт) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Перечисление поддерживаемых типов политик | WorkBoard реализовала собственные политики доступа, которые применяются в приложении.  Организация, команда и удостоверение пользователя используются для определения прав доступа. |
| Запрашивает ли ваше приложение минимальные разрешения для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мультитенантность? | Да |
| Имеет ли ваше приложение конфиденциальный клиент? | Нет |
| У вас есть все URI перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Разрешает ли модель разрешений выполнять вызовы только в том случае, если клиентское приложение получает соответствующее согласие? | Да |
| Использует ли ваше приложение API предварительной версии? | Нет |
| Использует ли ваше приложение нерекомендуемые API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
