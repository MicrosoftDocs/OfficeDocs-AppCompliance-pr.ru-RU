---
title: Сведения о приложениях для TackleBox от Insiten
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для TackleBox, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f141d645dddf16f57f5ba8097cd1924f7e561462
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252519"
---
# <a name="tacklebox"></a>TackleBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 12 января 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/dc37dab6-b497-4259-9aad-e40bfa023796" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002310" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт insiten:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | TackleBox |
| ID | WA200002310 |
| Возможности | Вкладка, соединитель |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Insiten |
| URL-адрес веб-сайта-партнера | [https://tacklebox.app/](https://tacklebox.app/) |
| URL-адрес страницы Teams приложения | [https://tacklebox.app](https://tacklebox.app) |
| URL-адрес политики конфиденциальности | [https://tacklebox.app/privacy/](https://tacklebox.app/privacy/) |
| URL-адрес терминов использования | [https://tacklebox.app/terms/](https://tacklebox.app/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены insiten о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | делегирована | Позволяет пользователям просматривать OneDrive, папок и файлов; ссылки файлов на TackleBox; чтение Excel в автоматические диаграммы, графики, таблицы, области печати и названные диапазоны; создание и обновление PowerPoint с помощью этих Excel визуальных эффектов | Drive ID, Folder ID, File ID, View Link, Created By, Created Date, Modified By, Modified Date, Version ID, File Name | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| Sites.Read.All | делегирована | Разрешить пользователям просматривать и связывать Excel, расположенные в частных Teams каналах | Нет | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| User.Read | делегирована | Позволяет приложению считыть профиль вписаных пользователей и перенастраить их адрес электронной почты для уведомлений | Электронная почта | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| openid | делегирована | Позволяет пользователям войти в наше приложение с помощью Microsoft 365 учетной записи | ID клиента и объектный ID для пользователя | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| profile | делегирована | Позволяет приложению отображать базовый профиль пользователей (имя, имя пользователя) для фасилитации совместной работы | UPN, имя, фамилия | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Адреса электронной почты и имена учетных записей. Отключаемые учетные записи и связанные с ними сведения о пользователях будут отключены через 3 месяца.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Не применимо — все данные хранятся в Microsoft Azure

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена insiten о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
