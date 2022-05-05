---
title: Сведения о приложении для iGlobe CRM Office 365 для Microsoft 365
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии для iGlobe CRM Office 365 для Microsoft 365, политики обработки данных, сведения о каталоге приложений Microsoft Cloud App Security и сведения о безопасности и соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 020e2ce913d50c72c401b4d08bc7810173faaa28
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225031"
---
# <a name="application-information-for-iglobe-crm-office-365-for-microsoft-365"></a>Сведения о приложении для iGlobe CRM Office 365 для Microsoft 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 22 июня 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iglobecrmoffice365" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые iGlobe корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | iGlobe CRM Office 365 для Microsoft 365 |
| ID | 17859280.iglobecrmoffice365 |
| Название партнерской компании | iGlobe |
| URL-адрес веб-сайта партнера | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL-адрес политики конфиденциальности | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL-адрес условий использования | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена iGlobe о том, как это приложение собирает и сохраняет данные организации, а также контроль над данными, собираемые приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>| **Разрешение**  | **Тип разрешения (делегированное или приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для хранения?** | **Azure AD приложения** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Делегированные | Данные не хранятся в базах данных приложений. | Доступ к календарям пользователей при выполнении отчетов о собраниях из canlendar в iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | Делегированные | Directory.AccessAsUser.All | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | Делегированные | Данные не хранятся в базах данных приложений. | Проверьте наличие разрешений и получение сайтов и списков. Создание папок, получение файлов и сохранение файлов. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач Panner, чтение последних и общих файлов пользователей, получение SharePoint списков, библиотек и файлов. Сохранение файлов и данных в SharePoint списков. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | Делегированные | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач Panner, чтение последних и общих файлов пользователей, получение SharePoint списков, библиотек и файлов. Сохранение файлов в SharePoint списков. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач Panner, чтение последних и общих файлов пользователей, получение SharePoint списков, библиотек и файлов. Сохранение файлов в SharePoint списков. Интеграция с iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | Делегированные | Данные не хранятся в базах данных приложений. | Подключите eamil к iGlobe CRM и получите informatiopn от iGlobe к новому e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | Делегированные | Данные не хранятся в базах данных приложений. | Создание, изменение и удаление элементов и списков в iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | Делегированные | Данные не хранятся в базах данных приложений. | Чтение элементов в iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Изменение и удаление элементов и списков в iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | Делегированные | Данные не хранятся в базах данных приложений. | Создание задачи планировщика из iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | Делегированные | Данные не хранятся в базах данных приложений. | Получение сведений о iGlobe CRM для пользователя speficic | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, созданные на Microsoft 365, могут использовать дополнительные API Майкрософт, отличные от Microsoft Graph для сбора или обработки идентифицируемой информации организации (OII). Вывод списка всех API-интерфейсов Майкрософт, кроме Microsoft Graph, которые использует это приложение.

>| **API** |  **Собирается ли OII?** |  **Какие OII собираются?** | **Обоснование для сбора OII?** | **Хранится ли OII?** | **Обоснование для хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | Нет |  |  |  |  |
>| Exchange — Mail.Read.All | Нет |  |  |  |  |
>| Exchange — Contacts.Read | Нет |  |  |  |  |
>| Exchange — EWS. AccessAsUser.All | Нет |  |  |  |  |
>| Exchange — Tasks.ReadWrite | Нет |  |  |  |  |
>| SharePoint — AllSites.Manage | Нет |  |  |  |  |
>| SharePoint — AllSites.Read | Нет |  |  |  |  |
>| SharePoint -AllSites.Write | Нет |  |  |  |  |
>| SharePoint — MyFiles.Write | Нет |  |  |  |  |
>| SharePoint — Sites.Manage.All | Нет |  |  |  |  |
>| SharePoint — Sites.Read.All | Нет |  |  |  |  |
>| SharePoint — Sites.ReadWrite.All | Нет |  |  |  |  |
>| SharePoint — Sites.Search.All | Нет |  |  |  |  |
>| SharePoint — TermStore.Read.All | Нет |  |  |  |  |
>| SharePoint TermStore.ReadWrite.All | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>iGlobe собирает данные для эффективной работы и предоставляет лучшие возможности работы с нашими продуктами и службами. Для лицензирования: данные, собранные для администрирования вашей организации&#8217;учетной записи лицензирования, например при развертывании бесплатных надстроек, создании пробной подписки или приобретении подписки. Собираются следующие сведения. 
- Для финансовых целей: название и адрес компании
- Подписанные пользователи: имя пользователя и электронная почта

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>Все данные принадлежат клиенту. Данные приложения не сохраняются. Современная надстройка запускается в изолированном браузере, &#8220;вне процесса&#8221;. Он взаимодействует с данными пользователей с помощью службы Майкрософт. Надстройка может получать доступ только к данным, с которыми работает пользователь.

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения об удостоверении

Эта информация предоставлена iGlobe о том, как это приложение обрабатывает проверку подлинности, авторизацию, рекомендации по регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Вы интегрируете с Microsoft Identify Platform (Azure AD)?  | Да |
| Вы просматривали и соблюдали все применимые рекомендации, описанные в платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (библиотека проверки подлинности Майкрософт) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Перечисление поддерживаемых типов политик | Параметры безопасности по умолчанию и другие распространенные политики, такие как блокировка устаревшей проверки подлинности* Требовать многофакторную проверку подлинности для администраторов* Требовать многофакторную проверку подлинности для управления Azure* Требовать многофакторную проверку подлинности для всех пользователей* |
| Запрашивает ли ваше приложение минимальные разрешения для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мультитенантность? | Да |
| Имеет ли ваше приложение конфиденциальный клиент? | Да |
| У вас есть все URI перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли ваше приложение API предварительной версии? | Нет |
| Использует ли ваше приложение нерекомендуемые API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
