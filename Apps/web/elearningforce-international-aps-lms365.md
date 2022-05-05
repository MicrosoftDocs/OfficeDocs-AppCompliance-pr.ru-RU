---
title: Сведения о приложении для LMS365
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Все доступные сведения о безопасности и соответствии для LMS365, его политики обработки данных, сведения Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224993"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>Сведения о приложении для LMS365 от ELEARNINGFORCE International Aps

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 23 июня 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые ELEARNINGFORCE International Aps в корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | LMS365 |
| ID | elearningforce.lms365_spfx |
| Название партнерской компании | ELEARNINGFORCE International Aps |
| URL-адрес веб-сайта партнера | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL-адрес политики конфиденциальности | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| URL-адрес условий использования | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена ELEARNINGFORCE International Aps о том, как это приложение собирает и хранит данные организации, а также контроль над данными, собираемые приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>| **Разрешение**  | **Тип разрешения (делегированное или приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для хранения?** | **Azure AD приложения** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | приложение | Нет | Позволяет приложению расширять участников группы AD, что необходимо для регистрации группы пользователей в курсах. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Делегированные | Нет | Разрешение запрашивается динамически во время настройки учетной записи электронной почты для уведомления. Позволяет приложению отправлять уведомления по электронной почте | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | приложение | Нет | Позволяет приложению получать SharePoint во время подготовки клиента. Домен используется для создания URL-адресов. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Делегированные | Нет | Позволяет приложению приглашать внешних пользователей от имени текущего пользователя, выполнив вход. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Делегированные | Нет | Войдите в систему и прочтите профиль пользователя. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Делегированные | Нет | Позволяет приложению считывать полный профиль текущего пользователя, выполнив вход. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | приложение | Позволяет приложению считывать полный профиль пользователя. Он&#8217;, необходимые для чтения пользователей&#8217; руководителей для создания отчетов иерархии. | Следующие персональные данные хранятся в выделенной базе данных для соответствующего клиента, используемого для работы информационной панели Learner Management &amp; Manager в приложении. Имя учетной записи, отображаемое имя пользователя, адрес электронной почты, отдел, должность, Office, страна, город, идентификатор руководителя или электронная почта | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| profile | Делегированные | Нет | Просмотр базового профиля пользователя. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, созданные на Microsoft 365, могут использовать дополнительные API Майкрософт, отличные от Microsoft Graph для сбора или обработки идентифицируемой информации организации (OII). Вывод списка всех API-интерфейсов Майкрософт, кроме Microsoft Graph, которые использует это приложение.

>| **API** |  **Собирается ли OII?** |  **Какие OII собираются?** | **Обоснование для сбора OII?** | **Хранится ли OII?** | **Обоснование для хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да, мы используем Аналитика или журналы Log Analytics, которые используются только для устранения неполадок и имеют политику хранения на 90 дней, по истечении которой удаляются все данные.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>LMS365 оснащен функцией очистки, которая удаляет все персональные данные из базы данных клиентов LMS365.

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения об удостоверении

Эти сведения предоставлены ELEARNINGFORCE International Aps о том, как это приложение обрабатывает проверку подлинности, авторизацию, рекомендации по регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Вы интегрируете с Microsoft Identify Platform (Azure AD)?  | Да |
| Вы просматривали и соблюдали все применимые рекомендации, описанные в платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (библиотека проверки подлинности Майкрософт) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Перечисление поддерживаемых типов политик | Платформы устройств, состояние устройства, клиентские приложения |
| Запрашивает ли ваше приложение минимальные разрешения для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мультитенантность? | Да |
| Имеет ли ваше приложение конфиденциальный клиент? | Нет |
| У вас есть все URI перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Разрешает ли модель разрешений выполнять вызовы только в том случае, если клиентское приложение получает соответствующее согласие? | Да |
| Использует ли ваше приложение API предварительной версии? | Нет |
| Использует ли ваше приложение нерекомендуемые API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
