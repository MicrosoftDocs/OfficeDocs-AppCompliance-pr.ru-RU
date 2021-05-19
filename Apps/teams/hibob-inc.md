---
title: Информация о применении для Hibob от Hibob Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Hibob, ее политики обработки данных, Microsoft Cloud App Security каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f2eae876022c6213b5f39532f44de4c127c3655e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553100"
---
# <a name="hibob"></a>Hibob

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/fdbe3361-c7dd-4ba5-b0b7-76a2002eb421" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000765" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Hibob Inc. корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Hibob |
| ID | WA200000765 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Hibob Inc. |
| URL-адрес веб-сайта партнера | [https://www.hibob.com/](https://www.hibob.com/) |
| URL политики конфиденциальности | [https://www.hibob.com/privacy-policy](https://www.hibob.com/privacy-policy) |
| URL условий использования | [https://www.hibob.com/terms-and-conditions](https://www.hibob.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Hibob Inc. о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Петух используется для соответствия пользователь Teams Боб пользователя в соответствии с электронной почтой. Соответствие используется для - идентификация, уведомления, ссылка на Teams профиль. | Используется и хранится только свойство UPN. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Мы ва-помоем идентификаторы разговоров и адреса электронной почты.
Логи очищаются через 30 дней.
Нет возможности удалять запрос на ответ журналов.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Наша платформа размещается в центрах обработки данных Amazon&#8217;, расположенных в Дублине и Франкфурте Доступ к платформе является ролевой, и устанавливается на основе необходимости знать / нужно делать, в соответствии с позицией сотрудника&#8217;.
Каждый пользователь имеет свои уникальные учетные данные, и мы применяем 2FA аутентификации на критических услуг.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29043' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29043" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

