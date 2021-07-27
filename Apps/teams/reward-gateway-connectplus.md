---
title: Сведения о приложениях для Подключение+ по Шлюзу вознаграждения
ms.author: elmalova
author: elenamalova
ms.date: 05/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Подключение+, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 573f6bbf833f08720b6ace0fe6d1f0b92bcc4a53
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521182"
---
# <a name="connect"></a>Connect+

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 25 мая 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/feb4e7cc-eb28-483e-a1ac-31bfead47e92" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002611" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Шлюзом вознаграждения в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Connect+ |
| Идентификатор | WA200002611 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Reward Gateway |
| URL-адрес веб-сайта-партнера | [https://www.rewardgateway.com](https://www.rewardgateway.com) |
| URL-адрес страницы Teams приложения | [https://success.rewardgateway.com/hc/en-us/articles/3600158...](https://success.rewardgateway.com/hc/en-us/articles/360015834078-Installing-the-MS-Teams-Integration) |
| URL-адрес политики конфиденциальности | [https://policies.rewardgateway.net/ms-teams-connect-plus/pr...](https://policies.rewardgateway.net/ms-teams-connect-plus/privacy-policy/) |
| URL-адрес терминов использования | [https://policies.rewardgateway.net/ms-teams-connect-plus/te...](https://policies.rewardgateway.net/ms-teams-connect-plus/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена шлюзом Reward Gateway о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | делегирована | Данные не собираются | Мы храним aadObjectId каждого пользователя, чтобы иметь возможность отслеживать, что они вошли в наше приложение по крайней мере один раз | [5e4dadf5-9f90-449b-9e39-934fd10b7c23](https://docs.microsoft.com/microsoft-365-app-certification/azure/5e4dadf5-9f90-449b-9e39-934fd10b7c23) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы не контролируем данные в сторонних системах

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36074' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36074" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена шлюзом Reward Gateway о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
