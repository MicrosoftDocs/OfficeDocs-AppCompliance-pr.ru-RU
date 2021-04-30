---
title: Сведения о приложениях для AVA от AvePoint, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
description: Все доступные сведения о безопасности и соответствия требованиям для AVA, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e5a5c364d2b49d598d6a5bd8c550b5aa8cc92913
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095541"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 марта 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные корпорацией Майкрософт AvePoint, Inc.:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | AVA |
| Идентификатор | WA104381883 |
| Возможности | Бот, вкладка |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | AvePoint, Inc. |
| URL-адрес веб-сайта-партнера | [https://www.avepoint.com](https://www.avepoint.com) |
| URL-адрес страницы Teams приложения | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| URL-адрес политики конфиденциальности | [https://www.avepoint.com/privacy-policy](https://www.avepoint.com/privacy-policy) |
| URL-адрес терминов использования | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены AvePoint, Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite.Shared | делегирована | Нет | Поиск электронной почты пользователя и перемещение электронной почты в указанную папку | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |
>| User.Read | делегирована |  Маркер доступа пользователя, используемый для поиска и восстановления данных пользователя | Позволяет пользователю войти и предоставить маркер доступа приложению | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |
>| User.ReadWrite | делегирована | DisplayName, UserPrincipalName, JobTitle, Organization, Country, MySiteUrl — записываю основные сведения пользователя, который использовал приложение | Получить основные сведения о профиле пользователя | 6f30434d-3cfa-4cf8-9810-6fcf79ae750a |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| REST API SharePoint | Да | Поиск файла в утилизации личного сайта пользователя и восстановление этих файлов. Требуется разрешение AllSites.Manage. |  | Нет |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да, в журналах появится имя электронной почты пользователя и его клиента. Журналы хранятся в защищенном расположении, и только уполномоченный персонал может получить доступ во время устранения неполадок. Журналы будут архивироваться через 60 дней для аудита безопасности и будут удалены через год.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные приложения хранятся в База данных SQL Azure и служба хранилища Azure. Шифрование SQL и служба хранилища Azure Azure.
Доступ к данным могут получить только уполномоченные администраторы. MFA требуется администраторам для входа в систему. Операции проверяются. Для ограничения доступа к данным также используется белый список IP.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

