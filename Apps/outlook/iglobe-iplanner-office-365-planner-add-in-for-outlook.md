---
title: Сведения о приложениях для надстройки Office 365 планировщика для Outlook iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/28/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Все доступные сведения о безопасности и соответствии требованиям для надстройки Office 365 планировщика для Outlook, политики обработки данных, сведения о каталоге приложений Microsoft Cloud App Security и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity-certification
ms.openlocfilehash: 0dd9e0dfbff342238dd46dd9db8a9338158c7f2f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412128"
---
# <a name="iplanner-office-365-planner-add-in-for-outlook"></a>надстройка Office 365 планировщика для Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 28 августа 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380147" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые iGlobe Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | надстройка Office 365 планировщика для Outlook |
| Идентификатор | WA104380147 |
| Office 365 поддерживаемые клиенты | Outlook 2013 или более поздней Windows, Outlook 2016 или более поздней Outlook в Интернете |
| Имя компании-партнера | iGlobe |
| URL-адрес веб-сайта-партнера | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL-адрес политики конфиденциальности | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL-адрес терминов использования | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена iGlobe о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить задачу планировщика и добавить новые задачи, обновим ведро и линию плавания для конкретного пользователя | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Contacts.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | создание встречи в календаре пользователей в срок выполнения задач | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Directory.AccessAsUser.All | делегирована | Данные не хранятся в базах данных приложений. | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.Read | делегирована | Данные не хранятся в базах данных приложений. | Доступ к файлу в виде вложения и отправка файлов в задачу | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Получите тему почты из выбранной почты. Позволяет приложению получать сведения из выбранной электронной почты, что позволяет скопировать поле описания в описание задачи и сохранить вложения от почты или самой почты к задаче. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Group.Read.All | делегирована | Данные не хранятся в базах данных приложений. |  чтобы получить задачу планировщика и добавить новые задачи, обновив ведро и линию плавания для конкретного пользователя | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.Read | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить задачу планировщика и добавить новые задачи, обновим ведро и линию плавания для конкретного пользователя | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.ReadBasic.All | делегирована | Данные не хранятся в базах данных приложений. |  Проверьте разрешение и получите задачу планировщика и добавьте новые задачи, обновив ведро и линию плавания для конкретного пользователя. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| profile | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить задачу планировщика и добавить новые задачи, обновим ведро и линию плавания для конкретного пользователя | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS. AccessAsUser.All | Нет |  |  |  |  |
>| Exchange - Mail.Read.All | Нет |  |  |  |  |
>| SharePoint - AllSites.Manage | Нет |  |  |  |  |
>| SharePoint - AllSites.Read | Нет |  |  |  |  |
>| SharePoint - AllSites.Write | Нет |  |  |  |  |
>| SharePoint - MyFiles.Read | Нет |  |  |  |  |
>| SharePoint - MyFiles.Write | Нет |  |  |  |  |

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

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Просмотр на новой вкладке</a>

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

::: zone pivot="certification"

### <a name="certification-information"></a>Сведения о сертификации

| **Control** | **Microsoft 365 Результат сертификации** |
|:------------|:---------------------------------------|
| [**БЕЗОПАСНОСТЬ ПРИЛОЖЕНИЙ**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#application-security) | **Н/Д** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Тестирование на проникновение | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Обзор оценки уязвимости (тест DAST/SAST/Penetration) | Недоступно |
| [**ОПЕРАТИВНАЯ БЕЗОПАСНОСТЬ**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#operational-security) | **Н/Д** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Защита от вредоносных программ — антивирус | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Защита от вредоносных программ — управление приложениями | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Управление исправлениями — ранжирование рисков | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Управление исправлениями — исправление | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Сканирование уязвимостей | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Брандмауэр — брандмауэры (или эквивалентные технологии) | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Брандмауэр — брандмауэры веб-приложений (WAFs) (необязательный) | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Управление изменениями | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Безопасные разработки и развертывания программного обеспечения | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Управление учетной записью | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Обнаружение и предотвращение вторжений (необязательный) | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ведение журнала событий безопасности | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Проверка (ведение журнала данных) | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Оповещение о событиях безопасности | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Управление рисками информационной безопасности | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Реагирование на инциденты | Недоступно |
| [**КОНФИДЕНЦИАЛЬНОСТЬ ПРИ ОБРАБОТКЕ &amp; ДАННЫХ**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#data-handling-security-and-privacy) | **Н/Д** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Данные в транзите | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Данные в покое | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Хранение и удаление данных | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Управление доступом к данным | Недоступно |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GDPR | Н/Д |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
