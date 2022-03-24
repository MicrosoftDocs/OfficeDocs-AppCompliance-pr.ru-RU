---
title: Сведения о приложениях для researcHR по KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для researcHR, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5def12e783d15c3cbcaf02ec128301dd9f75bd01
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753778"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 5 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией KBE&#26666;&#24335;&#20250;&#31038; Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | researcHR |
| ID | WA200002557 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | KBE&#26666;&#24335;&#20250;&#31038; |
| URL-адрес веб-сайта-партнера | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL-адрес страницы Teams приложения | [https://app.researchr.work](https://app.researchr.work) |
| URL-адрес политики конфиденциальности | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL-адрес терминов использования | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены KBE&#26666;&#24335;&#20250;&#31038; о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт](https://docs.microsoft.com/graph/permissions-reference), которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | приложение | Мы используем эту область, чтобы позволить нашему боту создать новый канал на Teams клиенте. См.: https://docs.microsoft.com/graph/api/channel-post | Мы не храним эти данные в нашей базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | приложение | Мы используем эту область для получения имен и ИД канала для отображения этих данных на нашем сайте. См.: https://docs.microsoft.com/graph/api/channel-list | Мы не храним эти данные в нашей базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | приложение | Мы используем эту область для получения имен и ИД канала для отображения этих данных на нашем сайте. См.: https://docs.microsoft.com/graph/api/channel-list | Мы не храним эти данные в нашей базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | приложение | Мы используем эту область, чтобы получить членов команды, чтобы пользователи могли видеть своих членов команды на нашем сайте. См.: https://docs.microsoft.com/graph/api/group-list-members | Мы не храним эти данные в базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | приложение | Мы используем эту область для получения каналов, присоединимых к пользователю, чтобы пользователи могли видеть их присоединились к группам на нашем сайте. См.: https://docs.microsoft.com/graph/api/user-list-joinedteams | Мы не храним эти данные в нашей базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | делегирована | Мы используем эту область, чтобы включить вход OAuth и собрать AAD пользователя, маркер доступа и маркер обновления. См.: https://docs.microsoft.com/graph/auth-v2-user | Мы храним в базе данных AAD, маркер доступа и маркер обновления, чтобы пользователь с помощью OAuth входил на наш веб-сайт. | [82df726e-0de2-46af-b4f1-0645fd95fc97].. /azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | делегирована | Мы используем эту область для получения маркера обновления, чтобы мы могли обновить маркер доступа для пользователей с строгим режимом без взаимодействия с пользователем. См.: https://docs.microsoft.com/azure/active-directory/develop/v2-permissions-and-consent#offline_access | Мы храним маркер обновления в базе данных, чтобы обновить маркер доступа без взаимодействия с пользователем. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


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

>Все данные в базе данных зашифрованы. Резервное копирование данных базы данных будет приниматься и храниться в течение определенного периода времени в соответствии с нашей внутренней операционной политикой. Если пользователь отменит эту службу, мы удалим сведения о пользователе без задержек, за исключением случаев, необходимых для выполнения обязательств по хранению, предусмотренных законом. Вот подробности. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены KBE&#26666;&#24335;&#20250;&#31038; о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
