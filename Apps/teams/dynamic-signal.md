---
title: Сведения о приложениях для динамического сигнала динамическим сигналом
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям динамического сигнала, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 19f633362ac605ef5891b3d7e11f34a8ec04d74f
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281311"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые динамическим сигналом Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Dynamic Signal |
| Идентификатор | WA200000102 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Dynamic Signal |
| URL-адрес веб-сайта-партнера | [https://www.dynamicsignal.com](https://www.dynamicsignal.com) |
| URL-адрес страницы Teams приложения | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL-адрес политики конфиденциальности | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL-адрес терминов использования | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена Dynamic Signal о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | делегирована | Dynamic Signal синхронизирует пользователя с Azure AD на свою платформу, чтобы обеспечить упрощенную активацию и отключение пользователей в режиме реального времени. Данные хранятся в Dynamic Signal, чтобы пользователи использовали это приложение во время синхронизации. | Ознакомьтесь с разрешениями конкретного пользователя для синхронизации пользователей платформы Динамический сигнал с Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | делегирована | Dynamic Signal синхронизирует пользователя с Azure AD на свою платформу, чтобы обеспечить упрощенную активацию и отключение пользователей в режиме реального времени. Данные хранятся в Dynamic Signal, чтобы пользователи использовали это приложение во время синхронизации. | Ознакомьтесь с разрешениями конкретного пользователя для синхронизации пользователей платформы Динамический сигнал с Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | делегирована | Dynamic Signal синхронизирует пользователя с Azure AD на свою платформу, чтобы обеспечить упрощенную активацию и отключение пользователей в режиме реального времени. Данные хранятся в Dynamic Signal, чтобы пользователи использовали это приложение во время синхронизации. | Сохраните доступ к группам и группам клиента. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | делегирована | Dynamic Signal синхронизирует пользователя с Azure AD на свою платформу, чтобы обеспечить упрощенную активацию и отключение пользователей в режиме реального времени. Данные хранятся в Dynamic Signal, чтобы пользователи использовали это приложение во время синхронизации. | Проверка подлинности пользователей с помощью приложения динамического сигнала. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Openid sign in using openid directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams | Openid Разрешить независимую проверку подлинности. directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams Note: Dynamic Signal's application uses teams bot to apply groups and permissions created within Dynamic Signal to Teams so that a user that is active in Dynamic Signal will have access to the same groups and users that within Teams. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Приложение динамического сигнала и платформа используют пользовательские сведения для облегчения интеграции с Microsoft Teams. Эти сведения доступны пользователям с соответствующими разрешениями на платформе Динамический сигнал. Релевантные сведения : Имя, Имя отображения и Электронная почта. Эти сведения хранятся в журналах платформы Динамический сигнал в соответствии с политикой соответствующей организации с лицензией Динамический сигнал.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные PII, собираемые во время регистрации и хранимые в платформе Динамический сигнал, включают: имя, фамилию, электронную почту и идентификатор, а также настраиваемые поля, настраиваемые партнерами по бренду и/или агентствам. Когда участники используют Facebook или Twitter с помощью oAuth Registration, некоторые данные пользователей, представленные на платформе Динамический сигнал для предварительного заполнения данных. Эти данные включают имя, расположение и фотографию. Пользователи могут контролировать, какие сведения и данные представляются пользователям на био-страницах сообщества. Участники могут отказаться от загрузки личных или фирменных фотографий, подключения социальных учетных записей/каналов и использования/точек в программе, которая будет представлена на странице bio.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

