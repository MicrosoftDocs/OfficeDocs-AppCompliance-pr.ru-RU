---
title: Информация о применении monday.com по monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям monday.com, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552930"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 28 сентября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная monday.com корпорацией Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | monday.com |
| ID | WA200001798 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | monday.com |
| URL-адрес веб-сайта партнера | [https://monday.com](https://monday.com) |
| URL политики конфиденциальности | [https://monday.com/privacy](https://monday.com/privacy) |
| URL условий использования | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена monday.com о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>| **Все неосуществимые службы Майкрософт OII передаются** |  **Какой OII передается?** | **Обоснование передачи OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com использует следующие суб-процессоры для выполнения своего сервиса:&#160;https://monday.com/terms/subprocessors |  | monday.com не использует API. Для выполнения наших услуг мы используем следующие фреймворки Майкрософт (как описано в нашем ответе выше): &#8216;бот-&#8217; &#8216;ботфрейм-разъем&#8217; &#8216;'micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>monday.com журналы приложений, которые содержат содержимое пользователей в течение ограниченного периода времени, чтобы позволить нашим сотрудникам R &amp; D устранения ошибок и проблем, о которых сообщает пользователь. В соответствии с нашей политикой хранения данных журналы безопасности, содержащие IP-адреса, сохраняются в течение более длительного периода времени.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>monday.com сервисе размещен на инфраструктуре AWS в Северной Вирджинии в нескольких зонах доступности, а сайт DR создан в другом регионе. Некоторые резервные данные хранятся на GCP (США, мульти-регион). Доступ к monday.com службе контролируется администраторами организации пользователей и достигается за счет использования следующих функций:
- Типы пользователей.
- Разрешения на уровне учетной записи
- Workspaces
- Типы доске
- Разрешения на уровне доски
- Разрешения на уровне столбца monday.com поддерживают следующие методы проверки подлинности:
- Учетные данные
- Google SSO (для Pro плана)
- Okta, OneLogin и пользовательские SAML 2.0 (для плана Enterprise) 2FA через SMS или через приложение аутентику может быть дополнительно включен администраторами учетной записи через панель администратора платформы.
Все данные в покое шифруются с помощью AES-256. Все данные, перегомняемые через открытые сети, шифруются с помощью TLS 1.3 (TLS 1.2 минимум).

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

