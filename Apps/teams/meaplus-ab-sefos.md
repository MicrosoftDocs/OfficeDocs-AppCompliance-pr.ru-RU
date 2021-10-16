---
title: Сведения о приложениях для SEFOS от Meaplus AB
ms.author: elmalova
author: elenamalova
ms.date: 09/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для SEFOS, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 14da720eee4a70152a3239d43154f0b47b0c56ea
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414555"
---
# <a name="sefos"></a>SEFOS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 15 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/a9b13f17-540f-4b08-a48c-75051b68677e" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003219" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Корпорацией Майкрософт с помощью Meaplus AB:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | SEFOS |
| Идентификатор | WA200003219 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Meaplus AB |
| URL-адрес веб-сайта-партнера | [https://www.meaplus.com](https://www.meaplus.com) |
| URL-адрес страницы Teams приложения | [https://sefos.se/en/sefos-i-teams/](https://sefos.se/en/sefos-i-teams/) |
| URL-адрес политики конфиденциальности | [https://www.meaplus.com/privacy-policy/](https://www.meaplus.com/privacy-policy/) |
| URL-адрес терминов использования | [https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-...](https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-end_user_agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена ВБ Meaplus о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | Создание собрания от имени пользователя | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| Mail.Send | делегирована | Отправка приглашений на собрание | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| MailboxSettings.Read | делегирована | Сбор зоны времени для пользователя с проверкой подлинности | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| People.Read | делегирована | Поиск в adressbook пользователя с проверкой подлинности | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| User.Read | делегирована | Вход и чтение профиля пользователя | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| email | делегирована | Адрес электронной почты для идентификации пользователя в SEFOS. | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| openid | делегирована | Вход пользователя | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| profile | делегирована | Чтение профиля пользователя | Нет | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |


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

>Это распределенная система, в которой каждая организация контролирует собственные сведения в локальной установке. . 

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена ВБ Meaplus о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

