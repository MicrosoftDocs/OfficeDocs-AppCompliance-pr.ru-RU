---
title: Сведения о приложениях для Office2SharePoint для Office iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Все доступные сведения о безопасности и соответствии требованиям для Office2SharePoint для Office, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 12b87e9addae70858503bb2d32def94cae657be2
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/27/2021
ms.locfileid: "58672766"
---
# <a name="office2sharepoint-for-office"></a>Office2SharePoint для Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 12 августа 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые iGlobe Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Office2SharePoint для Office |
| Идентификатор | WA104381787 |
| Office 365 поддерживаемые клиенты | Excel 2016 или позже на Mac, Excel 2016 или более поздней Windows, Excel в Интернете, Word 2016 или более поздней основе на Mac, Word в Интернете, Word 2016 или более поздней Windows, PowerPoint 2016 или более поздней PowerPoint в Интернете, PowerPoint 2016 или более поздней Windows |
| Имя компании-партнера | iGlobe |
| URL-адрес веб-сайта-партнера | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL-адрес политики конфиденциальности | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL-адрес терминов использования | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена iGlobe о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | делегирована | Данные не хранятся в базах данных приложений. | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Проверьте разрешение и получите сайты и списки. Создайте папки, получите файлы и сохраните файлы. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Проверьте разрешение и получите сайты и списки. Создайте папки, получите файлы и сохраните файлы. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить сайты группы пользователей. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить доступ к выбранной почте/s и получить вложения. От почты или добавить с сайта SharePoint групп на почту. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Mail.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить доступ к выбранной почте/s и получить вложения. От почты или добавить с сайта SharePoint групп на почту. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Manage.All | делегирована | Данные не хранятся в базах данных приложений. | Позволяет приложению создавать или удалять библиотеки документов и списки во всех коллекциях сайтов от имени подписанного пользователя. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы пользователи SharePoint сайте. Получите файлы и сохраните вложения из выбранной почты. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить SharePoint, библиотеки и файлы. Сохранение файлов для SharePoint списков. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| User.Read | делегирована | Данные не хранятся в базах данных приложений. | Чтобы пользователи SharePoint, OneDrive и групповых сайтов. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS. AccessAsUser.All | Нет |  |  |  |  |
>| Exchange - Mail.ReadWrite | Нет |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Нет |  |  |  |  |
>| SharePoint- AllSites.Manage | Нет |  |  |  |  |
>| SharePoint - AllSites.Write | Нет |  |  |  |  |
>| SharePoint - MyFiles.Write | Нет |  |  |  |  |
>| SharePoint - User.Read.All | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>iGlobe собирает данные для эффективной работы и предоставляет наилучшие сведения о наших продуктах и услугах. Для лицензирования. Данные, собранные для администрирования вашей&#8217;учетной записи лицензирования, например при развертывании бесплатных надстройок, создании пробной подписки или покупке подписки. Собираются следующие сведения. Для финансовых целей: имя и адрес подписанных пользователей компании: имя пользователя и электронная почта


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все данные приложения принадлежат клиенту и контролируются администратором клиента, как и все другие службы в Office 365. Данные приложения не хранятся в надстройке. Современная надстройка запускается в песочнице браузера, &#8220;из процесса&#8221;. Надстройка может получать доступ только к данным, с которыми работает пользователь. Он взаимодействует с данными пользователей с помощью службы Майкрософт.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена iGlobe о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
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
