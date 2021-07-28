---
title: Сведения о приложениях для MIPA — ваш личный помощник по iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/05/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Вся доступная информация о безопасности и соответствии требованиям для MIPA — ваш личный помощник, политики обработки данных, сведения о каталоге Microsoft Cloud App Security, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7db3c4f2e43ab80a84cc1421bff8489b2e467732
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527025"
---
# <a name="mipa---your-own-personal-assistant"></a>MIPA — личный помощник

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 5 ноября 2020 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000062" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые iGlobe Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | MIPA — личный помощник |
| Идентификатор | WA200000062 |
| Office 365 поддерживаемые клиенты | Outlook 2013 или более поздней Windows, Outlook 2016 или более поздней Outlook в Интернете |
| Имя компании-партнера | iGlobe |
| URL-адрес веб-сайта-партнера | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL-адрес политики конфиденциальности | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL-адрес терминов использования | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена iGlobe о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Целые календера чтения и обновления | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Contacts.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Целые календера чтения и обновления | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Directory.AccessAsUser.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач panner. Чтобы проверить, у пользователя есть согласие и доступ к использованию API. | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Directory.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить задачу планирования Outlook To Do, помечайте и обновляйте их. Создание новой задачи планировщика. | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Files.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач panner, чтение последних и общих файлов пользователей, SharePoint список, библиотеки и файлы. Сохранение файлов для SharePoint списков. | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Group.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач panner, чтение последних и общих файлов пользователей, SharePoint список, библиотеки и файлы. Сохранение файлов для SharePoint списков. | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Group.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение, обновление, создание задач panner, чтение последних и общих файлов пользователей, SharePoint список, библиотеки и файлы. Сохранение файлов для SharePoint списков. Интеграция в iGlobe CRM Office 365 | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Mail.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление помеченной почты | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| MailboxSettings.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление целых календлеров, чтение и обновление почты с флагами, чтение и обновление Outlook To Do целых версий | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| Tasks.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление целых календера, чтение и обновление Outlook do Entreies | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.Read | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление целых календера, чтение и обновление Outlook do Entreies | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление целых календеров, чтение и обновление Outlook, чтение, обновление, создание задач panner | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.ReadBasic.All | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление целых календеров, чтение и обновление Outlook, чтение, обновление, создание задач panner | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| User.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление целых календера, чтение и обновление Outlook do Entreies | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| email | делегирована | Данные не хранятся в базах данных приложений. | Позволяет приложению читать основной адрес электронной почты пользователей (для SSO). | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| offline_access | делегирована | Данные не хранятся в базах данных приложений. | Позволяет приложению видеть и обновлять данные, к которые вы предоставили ему доступ, даже если пользователи в настоящее время не используют приложение. Это не дает приложению дополнительных разрешений (для SSO). | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| openid | делегирована | Данные не хранятся в базе данных приложений | Позволяет пользователям войти в приложение со своими учетными записями работы или школы и позволяет приложению видеть основные сведения о профиле пользователя (для SSO). | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |
>| profile | делегирована | Данные не хранятся в базах данных приложений. | Чтение и обновление целых календеров, чтение и обновление Outlook, чтение, обновление, создание задач panner | [e854ea05-68ab-4204-babe-db4a784fb4d16](https://docs.microsoft.com/microsoft-365-app-certification/azure/e854ea05-68ab-4204-babe-db4a784fb4d16) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - Calendars.ReadWrite.All | Нет |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Нет |  |  |  |  |
>| Exchange - Mail.Read | Нет |  |  |  |  |
>| Exchange - Mail.ReadWrite.All | Нет |  |  |  |  |
>| Exchange - MailboxSettings.Read | Нет |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Нет |  |  |  |  |
>| Exchange - Tasks.ReadWrite | Нет |  |  |  |  |
>| SharePoint - MyFiles.Read | Нет |  |  |  |  |
>| SharePoint - MyFiles.Write | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>iGlobe собирает данные для эффективной работы и предоставляет наилучшие сведения о наших продуктах и услугах. Для лицензирования. Данные, собранные для администрирования вашей&#8217;учетной записи лицензирования, например при развертывании бесплатных надстройок, создании пробной подписки или покупке подписки. Собираются следующие сведения. - Для финансовых целей: имя и адрес компании, подписав пользователей: имя пользователя и электронная почта

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

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Просмотр на новой вкладке</a>

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
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Нет |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
