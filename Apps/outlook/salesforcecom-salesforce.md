---
title: Сведения о приложениях для Salesforce salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Salesforce, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b15f111d61d974a71eade2e5a3322ea3ee3431ca
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429747"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 24 августа 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые salesforce.com Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Salesforce |
| Идентификатор | WA104379334 |
| Office 365 поддерживаемые клиенты | Outlook 2013 или более поздней Windows, Outlook 2016 или более поздней Outlook в Интернете |
| Имя компании-партнера | salesforce.com |
| URL-адрес веб-сайта-партнера | [https://www.salesforce.com](https://www.salesforce.com) |
| URL-адрес политики конфиденциальности | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| URL-адрес терминов использования | [https://www.salesforce.com/content/dam/web/en_us/www/docume...](https://www.salesforce.com/content/dam/web/en_us/www/documents/legal/Agreements/software-order-form-supplements/Salesforce_Outlook_TOU_Order_Form_Addendum.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены salesforce.com о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API JavaScript для Office | Да | Надстройка использует функции Office.js и EWS для копирования контента и вложений по электронной почте, Outlook пользователь решил войти в Salesforce. Аналогичные возможности используются в стороне календаря для входа встреч в Salesforce. | Надстройка использует функции Office.js и EWS для копирования контента и вложений по электронной почте, Outlook пользователь решил войти в Salesforce. Аналогичные возможности используются в стороне календаря для входа встреч в Salesforce. | Надстройка использует такие функции, как getUserIdentityTokenAsync для получения текущего Outlook пользователя, GetItem (.js и EWS) для получения и набора дополнительных свойств и содержимого текущего сообщения электронной почты при сохранении записей Salesforce, GetAttachment (EWS) для получения вложений из Exchange и добавления в сопряженную электронную почту Salesforce, UpdateItem (.js), GetFolder (.js) для получения папки черновиков,  CreateItem (.js), который используется для создания черновика сообщения. | Надстройка использует такие функции, как getUserIdentityTokenAsync для получения текущего Outlook пользователя, GetItem (.js и EWS) для получения и набора дополнительных свойств и содержимого текущего сообщения электронной почты при сохранении записей Salesforce, GetAttachment (EWS) для получения вложений из Exchange и добавления в сопряженную электронную почту Salesforce, UpdateItem (.js), GetFolder (.js) для получения папки черновиков,  CreateItem (.js), который используется для создания черновика сообщения. |
>| Веб-службы Exchange (EWS) | Да | Надстройка использует функции Office.js и EWS для копирования контента и вложений по электронной почте, Outlook пользователь решил войти в Salesforce. Аналогичные возможности используются в стороне календаря для входа встреч в Salesforce. | Надстройка использует функции Office.js и EWS для копирования контента и вложений по электронной почте, Outlook пользователь решил войти в Salesforce. Аналогичные возможности используются в стороне календаря для входа встреч в Salesforce. | Надстройка использует такие функции, как getUserIdentityTokenAsync для получения текущего Outlook пользователя, GetItem (.js и EWS) для получения и набора дополнительных свойств и содержимого текущего сообщения электронной почты при сохранении записей Salesforce, GetAttachment (EWS) для получения вложений из Exchange и добавления в сопряженную электронную почту Salesforce, UpdateItem (.js), GetFolder (.js) для получения папки черновиков,  CreateItem (.js), который используется для создания черновика сообщения. | Надстройка использует такие функции, как getUserIdentityTokenAsync для получения текущего Outlook пользователя, GetItem (.js и EWS) для получения и набора дополнительных свойств и содержимого текущего сообщения электронной почты при сохранении записей Salesforce, GetAttachment (EWS) для получения вложений из Exchange и добавления в сопряженную электронную почту Salesforce, UpdateItem (.js), GetFolder (.js) для получения папки черновиков,  CreateItem (.js), который используется для создания черновика сообщения. |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Нет

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Хранилище Salesforce описано в руководстве по безопасности по https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения были предоставлены salesforce.com о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
