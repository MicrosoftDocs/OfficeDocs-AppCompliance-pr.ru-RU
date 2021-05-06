---
title: Сведения о приложениях для Adobe Sign Add-In для Outlook Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Все доступные сведения о безопасности и соответствия требованиям для Adobe Sign Add-In для Outlook, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 530bd74a0c74561545c4e7076cec5f6bc0eb5aa4
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251808"
---
# <a name="adobe-sign-add-in-for-outlook"></a>Adobe Sign Add-In для Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381158" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные корпорацией Adobe Inc. корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Adobe Sign Add-In для Outlook |
| ID | WA104381158 |
| Office 365 поддерживаемые клиенты | Outlook 2013 или более поздней Windows, Outlook 2016 или более поздней Outlook в Интернете |
| Имя компании-партнера | Adobe Inc. |
| URL-адрес веб-сайта-партнера | [https://www.adobe.com/](https://www.adobe.com/) |
| URL-адрес политики конфиденциальности | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL-адрес терминов использования | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=ru](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена Компанией Adobe Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | приложение | Нам нужны данные из электронной почты, чтобы вытащить отчет Adobe Sign History and Audit Trail о каждой транзакции. https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | Чтобы заполнить присоединенный документ, отправитель и приемник электронной почты, а также содержимое сообщений из электронной почты в знак Adobe для отправки для подписи. Это необходимо для экономии времени пользователя, чтобы перепечатывать эти поля в Adobe Sign. После подписания соглашения мы автоматически сочиняем новое сообщение электронной почты для отправки электронной почты для информирования получателей о том, что транзакция сделана. |  |
>| People.Read | делегирована |  | Чтобы автозаполнеть адрес электронной почты в режиме Отправка для подписи, введя некоторые начальные буквы, не требуется вводить &quot; &quot; целые сообщения электронной почты. |  |
>| User.Read | делегирована |  | Чтение профиля пользователя и соответствие его профиля (в основном, электронной почты) нашей базе данных, чтобы они могли использовать Adobe Sign. |  |
>| offline_access | делегирована |  | Чтобы обновить маркер доступа, по истечении текущего срока действия. Например, когда пользователь находится в окне отправки подписи и оставляет его неактивным слишком долго, необходимо обновить новый маркер, когда пользователь &quot; &quot; активен. |  |
>| openid | делегирована | Электронная почта — уникальный идентификатор для пользователей в Adobe Sign. Мы храним ИД электронной почты, чтобы мы могли соедино все действия этого пользователя с его записью Adobe Sign.  | Для регистрации пользователя, чтобы убедиться в его согласии на разрешение на использование приложения Adobe Sign. |  |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="add-in-data-access"></a>Доступ к данным надстройки

Список разрешений, необходимых этому приложению для доступа к данным организации, обоснования и цели этого разрешения (для чего приложение использует эти сведения?), и сохраняет ли приложение какую-либо из этих сведений в своих базах данных.

>| **Permission**  | **Описание** |
>|:----------------|:----------------|
>| Почтовый ящик ReadWrite | Эта надстройка может читать или изменять содержимое любого элемента в почтовом ящике и создавать новые элементы. Он может получать доступ к личной информации ( например, к телу, субъекту, отправителю, получателям или вложениям) в любом сообщении или элементе календаря. Они могут отправлять эти данные сторонним службам. |
>| Отправка данных | Может отправлять данные через Интернет |

#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Нет. Мы не внося какие-либо EUII или OII в телеметрию или журналы. Этот процесс — это наши собственные обзоры безопасности, которые подтверждают, что мы этого не делаем.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>У нас нет взаимодействия администратора клиента в нашей системе для Microsoft Teams приложения.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

