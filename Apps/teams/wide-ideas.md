---
title: Сведения о приложениях для широких идей с помощью широких идей
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Wide Ideas, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f1fc5d97736ba587595ef6c742b14ce75c0b1863
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550899"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 июня 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Корпорацией Майкрософт с помощью Wide Ideas:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Wide Ideas |
| ID | WA200000819 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Wide Ideas |
| URL-адрес веб-сайта-партнера | [https://getwideideas.com](https://getwideideas.com) |
| URL-адрес политики конфиденциальности | [https://getwideideas.com/privacy-policy](https://getwideideas.com/privacy-policy) |
| URL-адрес терминов использования | [https://getwideideas.com/terms](https://getwideideas.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены организацией Wide Ideas о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | приложение | Мы сэкономим ID группы и пользователи, к которым относятся группы | Позволяет приложению считыть данные в каталоге организации клиентов, например пользователей и групп.  | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| Group.ReadWrite.All | приложение | Мы экономим ID канала, который связан с группой. | Позволяет пользователю создавать группы, каналы и вкладки Microsoft Teams с клиентского портала. Это также позволяет пользователю синхронизировать существующие группы в Microsoft Teams в клиентский портал. | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| User.Read | делегирована | Мы экономим имя &amp; электронной почты | Позволяет пользователям войти и предоставить доступ к microsoft Graph от их имени | 77baef51-6387-4aff-9b3f-23e4654c30cd |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Почта Mailjet, которая используется для уведомлений электронной почты. |  | Недоступно |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Для создания пользователей в нашей задней части и получения разрешений на доступ к контенту, связанному с командой. | Мы храним: Имя - Чтобы показать имя пользователя, адрес электронной почты - Чтобы идентифицировать пользователя |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В журналах мы храним только IP-номер. 

Организация может отправить запрос нам как поставщику, если они хотят удалить какие-либо данные.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Хранение данных. Все данные клиента хранятся в Microsoft Azure службах. Для проверки подлинности пользователей через Azure AD требуется 2 фактора. Доступ на основе ролей (RBAC) на месте. Весь доступ к Microsoft Azure строго с помощью зашифрованных подключений. Все данные шифруются в покое. Все службы защищены лучшей практикой Центра безопасности Azure. 

У нас также есть политика доступа в соответствии с принципом наименьших привилегий. 


#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

