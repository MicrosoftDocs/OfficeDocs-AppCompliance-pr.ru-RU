---
title: Сведения о приложениях для FactSet в FactSet Research Systems Inc.
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для FactSet, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b869bbdddf3d7502aa9d174d5cb1a838f8ca7f8e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411033"
---
# <a name="factset"></a>FactSet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 сентября 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/95fb5da0-6ced-4247-9d62-294f8fcb75df" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002146" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт в корпорации Майкрософт в компании FactSet Research Systems Inc.:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | FactSet |
| Идентификатор | WA200002146 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | FactSet Research Systems Inc. |
| URL-адрес веб-сайта-партнера | [https://www.factset.com](https://www.factset.com) |
| URL-адрес политики конфиденциальности | [https://www.factset.com/privacy](https://www.factset.com/privacy) |
| URL-адрес терминов использования | [https://www.factset.com/hubfs/Misc/FactSet%20Teams%20Terms%...](https://www.factset.com/hubfs/Misc/FactSet%20Teams%20Terms%20of%20Use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены исследовательской организацией FactSet Research Systems Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | приложение | Имя и электронная почта для проверки и ведения журнала, Код беседы для упреждающего отправки сообщений | Имя и электронная почта для проверки и ведения журнала, Код беседы для упреждающего отправки сообщений | [95fb5da0-6ced-4247-9d62-294f8fcb75df](https://docs.microsoft.com/microsoft-365-app-certification/azure/95fb5da0-6ced-4247-9d62-294f8fcb75df) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Электронная почта и имя для проверки и ведения журнала, а также поддержки пользователей. | Электронная почта и имя | Электронная почта и имя для проверки и ведения журнала, а также поддержки пользователей. |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Идентификатор пользователя FactSet, электронная почта, имя, данные об использовании в журналах. Журналы имеют политику хранения в течение 30 дней,&#160;база данных хранится до тех пор, пока приложение не будет неустановлено.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Недоступно

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены исследовательскими системами FactSet Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

