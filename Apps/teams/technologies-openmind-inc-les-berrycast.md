---
title: Сведения о приложениях для Berrycast по технологиям Openmind Inc, Les
ms.author: elmalova
author: elenamalova
ms.date: 04/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Berrycast, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c3236368fbab418754e758f6009607335e593515
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283423"
---
# <a name="berrycast"></a>Berrycast

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 20 апреля 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/c7cde650-1e32-11eb-af14-639b3a7d6491" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002798" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией "Технологии Openmind Inc", les to Microsoft:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Berrycast |
| Идентификатор | WA200002798 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Technologies Openmind Inc, Les |
| URL-адрес веб-сайта-партнера | [https://www.berrycast.com](https://www.berrycast.com) |
| URL-адрес политики конфиденциальности | [https://www.berrycast.com/privacy-policy](https://www.berrycast.com/privacy-policy) |
| URL-адрес терминов использования | [https://www.berrycast.com/terms-of-use](https://www.berrycast.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены организацией Technologies Openmind Inc, Les о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| People.Read | делегирована | Для получения всех контактов пользователей | Сообщения электронной почты контактов, фистовое имя, фамилия и изображение хранятся для быстрого доступа к записям. | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| User.Read | делегирована | Определение пользователя с базовой информацией (имя и фамилия и изображение) | Отображение первого имени. последнее имя и изображение в приложении | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| email | делегирована | Определение пользователя | Определение пользователя для ведения журнала и отправка уведомления | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| offline_access | делегирована | Сохранение доступа к данным, к которым он был предоставлен | Недоступно | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| openid | делегирована | Определение пользователя | Определение пользователя для ведения журнала | 094f3986-3951-4f0c-88fa-514d117c8dd0 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, Intercom, MixPanel, Amplitude | электронная почта, уникальная идентификация пользователей, имя, имя последнего имени  | Обработка безопасного платежа, выполнение маркетинговой кампании, эффективное обслуживание клиентов и отслеживание аналитики пользователя для улучшения продукта |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Email, firstname, lastname and we remove all data if the user delete his account 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы удаляем все данные, связанные с пользователем, если он удаляет свою учетную запись.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены technologies Openmind Inc, Les о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Нет |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
