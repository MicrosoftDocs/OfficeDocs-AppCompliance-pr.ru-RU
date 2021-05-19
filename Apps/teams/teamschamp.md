---
title: Информация о заявках для TeamsChamp по TeamsChamp
ms.author: elmalova
author: elenamalova
ms.date: 03/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для TeamsChamp, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d7e48aa2c60e33f22de04c103b7a8727d323b10a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551405"
---
# <a name="teamschamp"></a>TeamsChamp

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 10 марта 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/4fea4594-3f83-4e33-9929-9af6b78a7340" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001487" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная TeamsChamp корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | TeamsChamp |
| ID | WA200001487 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | TeamsChamp |
| URL-адрес веб-сайта партнера | [https://www.teamschamp.com/](https://www.teamschamp.com/) |
| URL-адрес Teams страницы информации о приложениях | [https://www.teamschamp.com](https://www.teamschamp.com) |
| URL политики конфиденциальности | [https://www.teamschamp.com/privacy-policy/](https://www.teamschamp.com/privacy-policy/) |
| URL условий использования | [https://www.teamschamp.com/terms/](https://www.teamschamp.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена TeamsChamp о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Делегированные | Войти в профиль пользователей и прочитать его | Нет данных, хранящихся в нашем bbdd | 79d7af39-4f57-4e95-adaf-ec8ff756d0df |
>| User.ReadBasic.All | Делегированные | Прочитайте основной профиль всех пользователей | Нет данных, хранящихся в нашем bbdd | 79d7af39-4f57-4e95-adaf-ec8ff756d0df |
>| profile | Делегированные | Просмотр базовых профилей пользователей | Нет данных, хранящихся в нашем bbdd | 79d7af39-4f57-4e95-adaf-ec8ff756d0df |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>| **Все неосуществимые службы Майкрософт OII передаются** |  **Какой OII передается?** | **Обоснование передачи OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Полосатые платежи | Имя comnpany, CIF/VAT ID, Фискальный адрес | Платежи |

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Личная информатория как полное имя, электронная почта

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>удаление, удержание, аудит, архивирование, все управления в центре stripe admin

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36549" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Идентификационная информация

Эта информация была предоставлена TeamsChamp о том, как это приложение обрабатывает аутентификацию, авторизацию, лучшие практики регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интегрируесь ли вы с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и соблюдали все применимые передовой опыт, изложенные в контрольном платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (Библиотека аутентификации Майкрософт) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политику условного доступа? | Нет |
| Запрашивает ли приложение наименьшее разрешение на привилегии для вашего сценария? | Да |
| Точно ли зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мульти-аренду? | Да |
| Есть ли у вашего приложения конфиденциальный клиент? | Да |
| У вас есть все перенаправление идентификатора объединенных ресурсов (URI), зарегистрированного для вашего приложения? | Да |
| Что следует избегать использования приложения для вашего приложения? | - Wildcard перенаправить URIs,<br/>- OAuth2 Неявные Flow, если требуется для SPA<br/>- Ресурс Владелец пароль учетных данных (ROPC) поток |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API-версии предварительного просмотра? | Нет |
| Использует ли приложение увеные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
