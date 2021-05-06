---
title: Сведения о приложениях для smartsheet от Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Smartsheet, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 063dd29aea9265d89eb3ba735a376c7b1f0b64e3
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251128"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Smartsheet Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Smartsheet |
| ID | WA104380975 |
| Возможности | Бот, вкладка |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Smartsheet |
| URL-адрес веб-сайта-партнера | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL-адрес страницы Teams приложения | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL-адрес политики конфиденциальности | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL-адрес терминов использования | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена smartsheet о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | делегирована | Нет. | Позволяет нашему приложению устанавливать приложения от имени пользователя. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | делегирована | tenantId для ирисовки информации, которая будет показываться в пользовательском интерфейсе. | Позволяет нам прочитать, какие приложения использует этот клиент, чтобы мы могли проверить, нужно ли нам установить приложение для них. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | делегирована | teamId/groupId для доставки сообщений. | Позволяет нашему приложению читать основные сведения о группе (или Teams группе), а также беседы. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | делегирована | teamId/groupId для доставки сообщений. | Позволяет нашему приложению запускать новые беседы в командах. Это разрешение также включает в себя область Read.All, но она нужна нам также по техническим причинам. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | делегирована | userId. | Позволяет нам читать основные сведения о пользователе во время процесса auth. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | делегирована | refreshToken. | Позволяет нашему приложению получать маркеры обновления и обновлять маркер auth от имени пользователя при использовании приложения. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API bot Framework | Да | Мы используем API Bot Framework для доставки сообщений в качестве приложения для приложения teams. Smartsheet хранит сведения userId, чтобы отслеживать, с кем разговаривает бот Smartsheet. |  | Нет |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet хранит сведения в зашифрованном состоянии в состоянии покоя в среде центра обработки данных производства, которая находится в Equinix, и в AWS S3, где мы храним вложения клиентов в частных зашифрованных ведрах. |  | API базы ботов используется для доставки сообщений в качестве приложения для приложения teams. Smartsheet хранит сведения userId, чтобы отслеживать, с кем разговаривает бот Smartsheet. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet использует его для отслеживания того, о чем говорит бот. Во время начального потока auth мы создадим запись бота для пользователя в системе уведомлений Smartsheet. | Для smartsheet для Teams бота мы храним электронную почту пользователей и userId из Teams, чтобы отслеживать, с кем говорит бот.  Smartsheet хранит tenantIds, чтобы помочь группам списков, в которые пользователь входит в каталог, и groupIds для доставки сообщений. |  |



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Нет

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Smartsheet шифрует все хранимые сведения о пользователях, и администраторы должны использовать 2FA. Smartsheet работает в качестве поставщика SaaS без просмотра, и по умолчанию мы не проверяем содержимое, которое клиенты выбирают для загрузки или входа на платформу.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

