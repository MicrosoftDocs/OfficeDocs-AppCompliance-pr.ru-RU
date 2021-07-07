---
title: Сведения о приложениях для iGlobe CRM Office 365 для Microsoft 365 iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для iGlobe CRM Office 365 для Microsoft 365, политики обработки данных, сведения о каталоге Microsoft Cloud App Security и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: dd871a1c4b9e8ef8dd0628ff73a2737e1b94550f
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/02/2021
ms.locfileid: "53282738"
---
# <a name="iglobe-crm-office-365-for-microsoft-365"></a>cRM-Office 365 для Microsoft 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 22 июня 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iglobecrmoffice365" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые iGlobe Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | cRM-Office 365 для Microsoft 365 |
| Идентификатор | 17859280.iglobecrmoffice365 |
| Имя компании-партнера | iGlobe |
| URL-адрес веб-сайта-партнера | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL-адрес политики конфиденциальности | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL-адрес терминов использования | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена iGlobe о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Доступ к календарям пользователей при обмывке отчетов о собраниях из canlendar в iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | делегирована | Directory.AccessAsUser.All | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Проверьте разрешение и получите сайты и списки. Создайте папки, получите файлы и сохраните файлы. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач panner, чтение последних и общих файлов пользователей, SharePoint список, библиотеки и файлы. Сохранение файлов и данных для SharePoint списков. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач panner, чтение последних и общих файлов пользователей, SharePoint список, библиотеки и файлы. Сохранение файлов для SharePoint списков. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач panner, чтение последних и общих файлов пользователей, SharePoint список, библиотеки и файлы. Сохранение файлов для SharePoint списков. Интеграция в iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Svae eamil to iGlobe CRM and get informatiopn from iGlobe to a new e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | делегирована | Данные не хранятся в базах данных приложений. | Создание, редактирование и удаление элементов и списков в CRM iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение элементов в CRM iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Изменение и удаление элементов и списков в CRM iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Создание задачи планировщика из CRM iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить сведения о CRM iGlobe для speficic пользователя | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | Нет |  |  |  |  |
>| Exchange - Mail.Read.All | Нет |  |  |  |  |
>| Exchange - Contacts.Read | Нет |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Нет |  |  |  |  |
>| Exchange - Tasks.ReadWrite | Нет |  |  |  |  |
>| SharePoint - AllSites.Manage | Нет |  |  |  |  |
>| SharePoint - AllSites.Read | Нет |  |  |  |  |
>| SharePoint -AllSites.Write | Нет |  |  |  |  |
>| SharePoint - MyFiles.Write | Нет |  |  |  |  |
>| SharePoint - Sites.Manage.All | Нет |  |  |  |  |
>| SharePoint - Sites.Read.All | Нет |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | Нет |  |  |  |  |
>| SharePoint - Sites.Search.All | Нет |  |  |  |  |
>| SharePoint - TermStore.Read.All | Нет |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>iGlobe собирает данные для эффективной работы и предоставляет наилучшие сведения о наших продуктах и услугах. Для лицензирования. Данные, собранные для администрирования вашей&#8217;учетной записи лицензирования, например при развертывании бесплатных надстройок, создании пробной подписки или покупке подписки. Собираются следующие сведения. 
- Для финансовых целей: имя и адрес компании
- Подписанные пользователи: имя пользователя и электронная почта

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все данные принадлежат клиенту. Данные приложения не хранятся. Современная надстройка запускается в песочнице браузера, &#8220;из процесса&#8221;. Он взаимодействует с данными пользователей с помощью службы Майкрософт. Надстройка может получать доступ только к данным, с которыми работает пользователь.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена iGlobe о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | По умолчанию безопасности и любые другие распространенные политики, такие как проверка подлинности в режиме block legacy* Требуют MFA для администраторов* Требуют MFA для управления Azure* Требуют MFA для всех пользователей* |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
