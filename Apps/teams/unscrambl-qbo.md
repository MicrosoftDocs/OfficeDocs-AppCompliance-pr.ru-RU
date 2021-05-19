---
title: Информация о применении для qbo от Unscrambl
ms.author: elmalova
author: elenamalova
ms.date: 02/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для qbo, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 245ab6925aa77a005194e1badf31b926280454a1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551079"
---
# <a name="qbo"></a>qbo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком на: 1 февраля 2021</p>

* <a href="https://teams.microsoft.com/l/app/834c6939-152c-450b-a305-c65b4dd5d1c7" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001708" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Unscrambl корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | qbo |
| ID | WA200001708 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Unscrambl |
| URL-адрес веб-сайта партнера | [https://qbo.ai](https://qbo.ai) |
| URL-адрес Teams страницы информации о приложениях | [https://qbo.ai](https://qbo.ai) |
| URL политики конфиденциальности | [https://qbo.ai/legal/](https://qbo.ai/legal/) |
| URL условий использования | [https://qbo.ai/legal/#service](https://qbo.ai/legal/#service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Unscrambl о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>Это приложение не использует Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на веб-Microsoft 365 могут использовать дополнительные API Майкрософт, кроме Microsoft Graph для сбора или обработки идентифицируемой организационной информации (OII). Перечислите все API Майкрософт, кроме Microsoft, Graph использует это приложение.

>| **API** |  **Собирается ли OII?** |  **Что такое OII?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Api-файлы Bot Framework | Да | Доменное имя, идентифицировано по электронной почте пользователя | Мы собираем электронную почту для отправки отчета, если этого пожелает пользователь. | Только по электронной почте | Хранится как часть профиля пользователя |

#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| У нас есть функция приложения, которая позволяет пользователю по электронной почте PDF докладов для себя. | адрес электронной почты; | У нас есть функциональность приложения, которая позволяет пользователю по электронной почте PDF отчетов для себя, это хранится как часть профиля пользователя. |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Эти данные хранятся в МариаДБ, размещенных в VM на Azure (юго-восточная Азия). Доступ к VM ограничен IP, пароль защищен, а доступ к DB также защищен паролем.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36419' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36419" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Идентификационная информация

Эта информация была предоставлена Unscrambl о том, как это приложение обрабатывает аутентификацию, авторизацию, лучшие практики регистрации приложений и другие критерии идентичности.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интегрируесь ли вы с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
