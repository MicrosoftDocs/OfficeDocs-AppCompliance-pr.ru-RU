---
title: Сведения о приложениях для harmon.ie для Office по harmon.ie Корпорации
ms.author: elmalova
author: elenamalova
ms.date: 01/07/2021
ms.topic: article
ms.service: attestation
description: Все доступные сведения о безопасности и соответствия требованиям для harmon.ie для Office, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ddfc89a5291c0fb34c4198533ddf79154d4bc8bf
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095810"
---
# <a name="harmonie-for-office"></a>harmon.ie для Office

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 7 января 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381050" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией harmon.ie Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | harmon.ie для Office |
| Идентификатор | WA104381050 |
| Office 365 поддерживаемые клиенты | PowerPoint 2016 или позже Windows, Word 2016 или более поздней Windows, Excel в Интернете, Word в Интернете, PowerPoint в Интернете, Word 2016 или более поздней PowerPoint 2016 на Mac, PowerPoint 2016 или более поздней основе на Mac |
| Имя компании-партнера | harmon.ie Корпорация |
| URL-адрес веб-сайта-партнера | [https://harmon.ie/](https://harmon.ie/) |
| URL-адрес политики конфиденциальности | [https://harmon.ie/legal/privacy-policy](https://harmon.ie/legal/privacy-policy) |
| URL-адрес терминов использования | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836605/Product_42949673246/Asset_37060a29-311b-4239-be49-1758aebbeb1a/harmonieEULA.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены корпорацией harmon.ie о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | делегирована | Требуется harmon.ie для Outlook, чтобы разрешить пользователям войти и получить роль пользователя | нет | 170cef4c-862a-443c-b02a-c5ba04ecc7f3 |
>| Files.ReadWrite.All | делегирована | Требуется harmon.ie для Outlook, чтобы разрешить ему передавать вложения электронной почты из Outlook и &amp; сохранить его в SharePoint | нет | 170cef4c-862a-443c-b02a-c5ba04ecc7f3 |
>| Mail.ReadWrite | делегирована | Требуется harmon.ie для Outlook, чтобы разрешить ему передавать вложения электронной почты из Outlook и &amp; сохранить его в SharePoint | нет | 170cef4c-862a-443c-b02a-c5ba04ecc7f3 |
>| User.Read | делегирована | Требуется harmon.ie для Outlook для разрешения изображения профиля пользователей | нет | 170cef4c-862a-443c-b02a-c5ba04ecc7f3 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="add-in-data-access"></a>Доступ к данным надстройки

Список разрешений, необходимых этому приложению для доступа к данным организации, обоснования и цели этого разрешения (для чего приложение использует эти сведения?), и сохраняет ли приложение какую-либо из этих сведений в своих базах данных.

>| **Permission**  | **Описание** |
>|:----------------|:----------------|
>| Документ ReadWrite | Может читать и вносить изменения в документ |
>| Отправка данных | Может отправлять данные через Интернет |

#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Данные об использовании и обилие пользователей

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>-

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36360' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36360" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена корпорацией harmon.ie о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,
<br />
- OAuth2 Неявный Flow, если не требуется для SPA
<br />
- Поток учетных данных владельца ресурса (ROPC) | | Предоставляет ли ваше приложение какие-либо веб-API? | Да| | Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да| | Использует ли приложение API предварительного просмотра? | Нет | | Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
