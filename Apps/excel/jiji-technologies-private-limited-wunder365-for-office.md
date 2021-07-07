---
title: Сведения о приложениях для Wunder365 для Office jiJi Technologies Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Wunder365 для Office, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 85e7b014e9bbc5754016bd83a7734ff2481aa8dc
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281691"
---
# <a name="wunder365-for-office"></a>Wunder365 для Office

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 15 декабря 2020 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001529" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт в компании JiJi Technologies Private Limited:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Wunder365 для Office |
| Идентификатор | WA200001529 |
| Office 365 поддерживаемые клиенты | Excel 2016 или позднее на Mac, Excel 2013 или более поздней Windows, Excel в Интернете, Word 2016 или более поздней основе на Mac, Word в Интернете, Word 2013 или более поздней Windows, OneNote в Интернете |
| Имя компании-партнера | JiJi Technologies Private Limited |
| URL-адрес веб-сайта-партнера | [https://www.jijitechnologies.com](https://www.jijitechnologies.com) |
| URL-адрес политики конфиденциальности | [https://www.wunder365.com/office-addin-privacy-policy](https://www.wunder365.com/office-addin-privacy-policy) |
| URL-адрес терминов использования | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена jiJi Technologies Private Limited о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | делегирована | Данные не хранятся. | Чтобы получить и обновить задачи планировщика, раздать обновления задач в канале команды | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Mail.Send | делегирована | Данные не хранятся. | Разрешить приложению отправлять уведомления электронной почты пользователям | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| offline_access | делегирована | Данные не хранятся. | Чтобы сохранить вход пользователя в систему. | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| openid | делегирована | Данные не хранятся. | Позволяет пользователям войти в систему с учетной записью организации | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| profile | делегирована | UPN, ID пользователя, email ID, Tenant ID для проверки лицензирования, бесплатная лицензия. | Позволяет пользователям войти в систему с учетной записью организации | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы внося в журнал Azure Application Аналитика. Мы внося в журнал id клиента и email-id пользователя, чтобы выявить проблемы и помочь клиентам решить проблемы.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все веб-приложения и служба хранилища находятся в подписке, не подключенной к нашей компании AAD, с помощью только администраторов, имеющих доступ к ресурсам. Для этих администраторов требуется 2FA. 


#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения были предоставлены jiJi Technologies Private Limited о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | Требование многофакторной проверки подлинности для пользователей с административными ролями, требование многофакторной проверки подлинности для задач управления Azure, блокировка входных входов для пользователей, пытающихся использовать устаревшие протоколы проверки подлинности, требование надежных местоположений для регистрации многофакторной проверки подлинности Azure AD, блокировка или предоставление доступа из определенных местоположений, блокировка рискованного поведения при входе |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
