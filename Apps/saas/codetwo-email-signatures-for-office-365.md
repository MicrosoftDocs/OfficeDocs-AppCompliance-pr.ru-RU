---
title: Сведения о приложениях для подписей электронной почты CodeTwo для Office 365 codeTwo
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для CodeTwo Email Signatures для Office 365, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3b6ab4d89a64aaec64dbb731a213fd203876476c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428181"
---
# <a name="codetwo-email-signatures-for-office-365"></a>Подписи электронной почты CodeTwo для Office 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 2 августа 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/web-apps/codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые CodeTwo в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Подписи электронной почты CodeTwo для Office 365 |
| Идентификатор | codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69 |
| Имя компании-партнера | CodeTwo |
| URL-адрес веб-сайта-партнера | [https://www.codetwo.com](https://www.codetwo.com) |
| URL-адрес политики конфиденциальности | [https://www.codetwo.com/regulations/privacy](https://www.codetwo.com/regulations/privacy) |
| URL-адрес терминов использования | [https://www.codetwo.com/license-agreement](https://www.codetwo.com/license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена codeTwo о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | делегирована | Позволяет пользователям войти в приложение и позволяет приложению считывать профиль пользователей, входив в приложение. Это также позволяет приложению считыть основные сведения об организации пользователей, вписав их. | Данные не хранятся. | [2a93620e-4345-4e3b-9bae-0195f08aab69](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a93620e-4345-4e3b-9bae-0195f08aab69) |
>| User.Read | делегирована | Позволяет пользователям входить в приложение, а приложению — просматривать профили вошедших пользователей. Кроме того, позволяет приложению считывать основные сведения о компании вошедших пользователей. | Данные не хранятся. | [7afd058a-f568-4496-96b1-28d06ab3500f](https://docs.microsoft.com/microsoft-365-app-certification/azure/7afd058a-f568-4496-96b1-28d06ab3500f) |
>| Directory.AccessAsUser.All | делегирована | Предоставляет приложению такой же доступ к информации в каталоге, как у вошедшего пользователя. | Данные не хранятся. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| Directory.Read.All | оба | Позволяет приложению читать данные в каталоге&#8217;организации, таких как пользователи, группы и приложения. | Данные не хранятся. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.ReadBasic.All | делегирована | Позволяет приложению просматривать базовый набор свойств профилей других пользователей организации от имени вошедшего пользователя. Это включает отображение имени, имени и фамилии, адреса электронной почты и фотографии. Сведения используются для автоматической персонализации подписей электронной почты для пользователей. | Данные не хранятся. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.Read | делегирована | Пользователи смогут входить в приложение, а оно сможет просматривать профили вошедших пользователей. Это также позволяет приложению считыть основные сведения о компании пользователей, подписав контракт. Используется для регистрации пользователя в службе CodeTwo. | Данные не хранятся. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| email | делегирована | Позволяет приложению считывать основные электронные адреса пользователей. Используется для регистрации пользователя в службе CodeTwo. | Данные не хранятся. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| offline_access | делегирована | Позволяет приложению видеть и обновлять данные, к которые вы предоставили ему доступ, даже если пользователи в настоящее время не используют приложение. Это не дает приложению дополнительных разрешений. | Данные не хранятся. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| openid | делегирована | Пользователи смогут входить в приложение с помощью своей рабочей или учебной учетной записи, а приложение сможет просматривать основные данные профилей пользователей. Используется для регистрации пользователя в службе CodeTwo. | Данные не хранятся. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| profile | делегирована | Позволяет приложению просматривать базовые профили пользователей (имя, аватар, имя пользователя). Используется для регистрации пользователя в службе CodeTwo. | Данные не хранятся. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Клиенты могут получать доступ к данным и настройкам служб контактной организации с &amp; помощью панели администрирования CodeTwo. Они также могут связаться с командой информационной безопасности CodeTwo с помощью выделенной формы (для осуществления любых прав, описанных в https://www.codetwo.com/form/security-officer/) CodeTwo Terms and Privacy ( т.е. доступа к данным, исправление данных, удаление и ограничение обработки, отзыв согласия и право возражать https://www.codetwo.com/regulations/privacy) против обработки.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена CodeTwo о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
