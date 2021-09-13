---
title: Сведения о приложениях для выбора контента по officeatwork
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для выбора контента, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b7353f91abadea47e8b9147454697b66bcc7ddaa
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284897"
---
# <a name="content-chooser"></a>Выбор контента

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 июня 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.content-chooser" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые officeatwork Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Выбор контента |
| Идентификатор | officeatwork-ag.content-chooser |
| Имя компании-партнера | officeatwork |
| URL-адрес веб-сайта-партнера | [https://www.officeatwork.com](https://www.officeatwork.com) |
| URL-адрес политики конфиденциальности | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| URL-адрес терминов использования | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена officeatwork о том, как это приложение собирает и хранит организационные данные и контроль, который будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | делегирована | Данные не хранятся. | Избранное: возможность чтения и записи данных пользователям, OneDrive. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Files.ReadWrite.All | делегирована | Данные не хранятся. | OneDrive: возможность чтения и записи данных пользователям OneDrive. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Group.ReadWrite.All | делегирована | Данные не хранятся. | Teams: возможность чтения и записи данных в группу. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| GroupMember.Read.All | делегирована | Данные не хранятся. | SharePoint Поддержка групп безопасности: разрешить приложению перечислять группы, читать основные свойства групп и читать членство всех групп, к которые имеет доступ пользователь, входив в группу. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Sites.Read.All | делегирована | Данные не хранятся. | SharePoint Online: включить чтение данных из SharePoint Online. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| User.Read | делегирована | Данные не хранятся. | Sing-In: чтобы включить приложение Officeatwork для чтения основных свойств пользователя. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| User.Read.All | делегирована | Данные не хранятся. | Teams: выяснить, к каким группам относится пользователь. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| offline_access | делегирована | Данные не хранятся. | Sing-In: чтобы включить автоматическую регистрацию с помощью маркеров обновления, как и без, пользователям придется вручную включать каждый раз при запуске приложения officeatwork. Эта область требуется только для не-SSO с включенной хост-приложениями. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| openid | делегирована | Данные не хранятся. | Sing-In: чтобы пользователи могли войти в приложение officeatwork со своей организационной и/или учетной записью Майкрософт. | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| profile | делегирована | Данные не хранятся. | Sing-In: чтобы показать в приложении officeatwork пользователя, вписавшись в него. Это позволяет убедить пользователя в том, какая учетная запись использовалась для регистрации в приложении officeatwork. | edb24f8f-38af-4b3e-9475-0da243678d5a |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| REST API SharePoint | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да, события включают oid и tenantId и отправляются в Azure AppInsights. События автоматически удаляются через 90 дней. Если клиент хочет удалить эти данные, он может использовать ссылку, представленную в заявлении о конфиденциальности, чтобы инициировать удаление этих данных.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные параметров приложений (флаги функций, имя отображения организации, tenantId, список oids администраторов) хранятся в экземпляре Azure Cosmos DB (один файл на клиента). Файлы DB шифруются, доступ к ним ограничен для выбранных инженеров officeatwork и сотрудников службы поддержки. Клиент может получать доступ к данным параметров приложений Officeatwork и управлять ими с помощью веб-приложения Центра администрирования.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35751' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35751" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена officeatwork о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | Параметры безопасности по умолчанию |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Нет |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
