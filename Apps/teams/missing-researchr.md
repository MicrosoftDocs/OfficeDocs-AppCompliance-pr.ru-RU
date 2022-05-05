---
title: Сведения о приложении для researcHR по KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии для researcHR, его политики обработки данных, сведения Microsoft Cloud App Security каталога приложений, а также сведения о безопасности и соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229013"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 5 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Просмотр в Teams хранилище</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые KBE&#26666;&#24335;&#20250;&#31038; корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | researcHR |
| ID | WA200002557 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Название партнерской компании | KBE&#26666;&#24335;&#20250;&#31038; |
| URL-адрес веб-сайта партнера | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL-адрес страницы Teams приложения | [https://app.researchr.work](https://app.researchr.work) |
| URL-адрес политики конфиденциальности | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL-адрес условий использования | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены KBE&#26666;&#24335;&#20250;&#31038; о том, как это приложение собирает и сохраняет данные организации, а также контроль над данными, собираемые приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>| **Разрешение**  | **Тип разрешения (делегированное или приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для хранения?** | **Azure AD приложения** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | приложение | Мы используем эту область, чтобы позволить боту создать новый канал на Teams клиенте. См.: /graph/api/channel-post | Мы не храним эти данные в базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | приложение | Мы используем эту область для получения идентификаторов каналов и имен для отображения этих данных на нашем веб-сайте. См. раздел /graph/api/channel-list | Мы не храним эти данные в базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | приложение | Мы используем эту область для получения идентификаторов каналов и имен для отображения этих данных на нашем веб-сайте. См. раздел /graph/api/channel-list | Мы не храним эти данные в базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | приложение | Мы используем эту область, чтобы получить участников команды, чтобы пользователи могли видеть своих участников команды на нашем веб-сайте. См. раздел /graph/api/group-list-members | Мы не храним эти данные в исходящих базах данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | приложение | Мы используем эту область для получения каналов, присоединенных к пользователю, чтобы пользователи могли видеть их присоединенные команды на нашем веб-сайте. См. раздел /graph/api/user-list-joinedteams | Мы не храним эти данные в базе данных. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | Делегированные | Эта область используется для включения имени входа OAuth и сбора идентификатора AAD, маркера доступа и маркера обновления пользователя. См. раздел /graph/auth-v2-user | Мы храним идентификатор AAD, маркер доступа и маркер обновления в нашей базе данных, чтобы пользователь может войти на наш веб-сайт с помощью OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97].. /azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | Делегированные | Мы используем эту область для получения маркера обновления, чтобы мы могли обновить маркер доступа пользователей, авторизаированных без взаимодействия с пользователем. См. раздел /azure/active-directory/develop/v2-permissions-and-consent#offline_access | Мы храним маркер обновления в базе данных, чтобы обновить маркер доступа без взаимодействия с пользователем. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бот или расширение для обмена сообщениями, оно может получить доступ к идентифицируемой информации конечного пользователя (EUII): список (имя, фамилия, отображаемое имя, адрес электронной почты) любого участника команды или чата, в который оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не выполняется.


#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии или журналах приложений не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>Все данные в базе данных шифруются. Резервные копии данных базы данных будут создаваться и храниться в течение определенного периода времени в соответствии с нашей внутренней операционной политикой. Если пользователь отменит эту службу, мы удалим сведения о пользователе без задержки, за исключением случаев, необходимых для выполнения обязательств по хранилищу, предусмотренных законом. Ниже приведены подробные сведения. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения об удостоверении

Эти сведения предоставлены KBE&#26666;&#24335;&#20250;&#31038; о том, как это приложение обрабатывает проверку подлинности, авторизацию, рекомендации по регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Вы интегрируете с Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
