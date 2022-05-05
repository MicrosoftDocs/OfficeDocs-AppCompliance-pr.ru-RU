---
title: Application Information for Guru by Guru Technologies
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии для Службы", ее политики обработки данных, сведения Microsoft Cloud App Security каталога приложений, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b623d0d92400219e5ad31d58ade4d98409aced98
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226563"
---
# <a name="guru"></a>Guru

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 1 марта 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/094bf90e-e413-4740-b2dc-68d624d0e40e" target="_blank">Просмотр в Teams хранилище</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001719" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые в корпорацию Майкрософт от Службы "Технологии Для Windows":

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Guru |
| ID | WA200001719 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Название партнерской компании | Guru Technologies |
| URL-адрес веб-сайта партнера | [https://www.getguru.com](https://www.getguru.com) |
| URL-адрес страницы Teams приложения | [https://www.getguru.com/integrations/microsoft-teams](https://www.getguru.com/integrations/microsoft-teams) |
| URL-адрес политики конфиденциальности | [https://www.getguru.com/privacy/](https://www.getguru.com/privacy/) |
| URL-адрес условий использования | [https://www.getguru.com/terms-of-service](https://www.getguru.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена ВИА "Технологии" о том, как это приложение собирает и хранит данные организации, а также о том, как ваша организация будет управлять данными, собранными приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>Это приложение не использует microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>| **Все сторонние службы Майкрософт OII передаются в** |  **Какой OII передается?** | **Обоснование для передачи OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Приложение конечного пользователя и внутренние базы данных Отеки | Когда пользователь или компания настраивает приложение «Teams» для приложения «Teams» , общие сведения, такие как имя пользователя, электронная почта и название компании, связанные с его профилем пользователя, записываются и доступны в приложении «Муайла» | Учитывая, что у пользователя должна быть учетная запись Teams и Учетная запись Для использования интеграции, мы отслеживаем и отслеживаем, какие пользователи обеспечивают интеграцию, чтобы обеспечить поддержку и управление для этих пользователей. |

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бот или расширение для обмена сообщениями, оно может получить доступ к идентифицируемой информации конечного пользователя (EUII): список (имя, фамилия, отображаемое имя, адрес электронной почты) любого участника команды или чата, в который оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не выполняется.


#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Когда пользователь или компания настраивает приложение «Teams» для приложения «Teams» , конечная информация, например имя пользователя, электронная почта и название компании, связанные с его профилем пользователя, записывает и получает доступ к ним. После завершения работы учетной записи данные сохраняются в течение 90 дней, а затем удаляются. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>Группа разработчиков Параметры позволяет администраторам в команде определять, какие группы и элементы управления доступом и ролем следует подготавливать для каждой коллекции, с возможностью добавлять, удалять и повторно назначать карточки альтернативным пользователям. Enterprise, которые развернули единый вход, также могут использовать консоль поставщика единого входа для подключения и отключения групп с помощью SCIM.

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения об удостоверении

Эта информация была предоставлена ВИА "Технологии" о том, как это приложение обрабатывает проверку подлинности, авторизацию, рекомендации по регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Вы интегрируете с Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
