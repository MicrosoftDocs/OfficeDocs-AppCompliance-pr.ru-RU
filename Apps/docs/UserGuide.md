---
title: Руководство по пользователю
author: LGerrard
ms.author: legerrar
description: Руководство пользователя ISV для Microsoft 365 программы соответствия требованиям к приложениям
keywords: Руководство пользователя ISV для Microsoft 365 программы соответствия требованиям к приложениям
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 437fcbc56309ca14566dbb95f470097af82c26bf
ms.sourcegitcommit: bfabb191087786fae2b476e3f30861317886defa
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/29/2021
ms.locfileid: "53179088"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program"></a><span data-ttu-id="8acf2-104">Руководство для пользователей партнеров для Microsoft 365 программы соответствия требованиям приложений</span><span class="sxs-lookup"><span data-stu-id="8acf2-104">Partner's User Guide for Microsoft 365 App Compliance Program</span></span>

|<span data-ttu-id="8acf2-105">Этап</span><span class="sxs-lookup"><span data-stu-id="8acf2-105">Phase</span></span>|<span data-ttu-id="8acf2-106">Название</span><span class="sxs-lookup"><span data-stu-id="8acf2-106">Title</span></span>|
|---|---|
|<span data-ttu-id="8acf2-107">Этап 1</span><span class="sxs-lookup"><span data-stu-id="8acf2-107">Phase 1</span></span>| <span data-ttu-id="8acf2-108">Аттестация издателя</span><span class="sxs-lookup"><span data-stu-id="8acf2-108">Publisher Attestation</span></span>|
|<span data-ttu-id="8acf2-109">Этап 2</span><span class="sxs-lookup"><span data-stu-id="8acf2-109">Phase 2</span></span>| <span data-ttu-id="8acf2-110">Сертификация Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="8acf2-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="8acf2-111">1. Обзор</span><span class="sxs-lookup"><span data-stu-id="8acf2-111">1. Overview</span></span>
<span data-ttu-id="8acf2-112">Этот документ выступает в качестве пошагового руководства для наших партнеров, зарегистрированных в программе соответствия требованиям Microsoft 365 приложений, с целью пройти Publisher аттестацию и сертификацию на портале Центра партнеров.</span><span class="sxs-lookup"><span data-stu-id="8acf2-112">This document acts as a step-by-step user guide for our partners enrolled in the Microsoft 365 App Compliance Program aiming to undergo Publisher Attestation and Certification though Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="8acf2-113">2. Акронимы & определения</span><span class="sxs-lookup"><span data-stu-id="8acf2-113">2. Acronyms & Definitions</span></span>
| <span data-ttu-id="8acf2-114">Сокращение</span><span class="sxs-lookup"><span data-stu-id="8acf2-114">Acronym</span></span> |<span data-ttu-id="8acf2-115">Определение</span><span class="sxs-lookup"><span data-stu-id="8acf2-115">Definition</span></span> |
|---|----|
|<span data-ttu-id="8acf2-116">PC [(Центр партнеров)](https://partner.microsoft.com/)</span><span class="sxs-lookup"><span data-stu-id="8acf2-116">PC [(Partner Center)](https://partner.microsoft.com/)</span></span>|<span data-ttu-id="8acf2-117">Портал для всех партнеров Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="8acf2-117">A portal for all Microsoft Partners.</span></span> <span data-ttu-id="8acf2-118">Партнер входит в Центр партнеров и Self-Assessment вопросник.</span><span class="sxs-lookup"><span data-stu-id="8acf2-118">A Partner logs in to Partner Center and submits Self-Assessment Questionnaire.</span></span> <span data-ttu-id="8acf2-119">[Центр партнеров](https://partner.microsoft.com/dashboard/home) по Microsoft 365 соответствия требованиям к приложениям</span><span class="sxs-lookup"><span data-stu-id="8acf2-119">[Partner Center](https://partner.microsoft.com/dashboard/home) for Microsoft 365 App Compliance</span></span>|
|<span data-ttu-id="8acf2-120">Независимый поставщик программного обеспечения</span><span class="sxs-lookup"><span data-stu-id="8acf2-120">ISV</span></span>|<span data-ttu-id="8acf2-121">Независимый поставщик программного обеспечения.</span><span class="sxs-lookup"><span data-stu-id="8acf2-121">Independent Software Vendor.</span></span> <span data-ttu-id="8acf2-122">A.k.a.</span><span class="sxs-lookup"><span data-stu-id="8acf2-122">A.k.a.</span></span> <span data-ttu-id="8acf2-123">Партнер или разработчик</span><span class="sxs-lookup"><span data-stu-id="8acf2-123">Partner or Developer</span></span>|
|<span data-ttu-id="8acf2-124">Источник приложения</span><span class="sxs-lookup"><span data-stu-id="8acf2-124">App Source</span></span>| [<span data-ttu-id="8acf2-125">Каталог приложений</span><span class="sxs-lookup"><span data-stu-id="8acf2-125">Catalog of apps</span></span>](https://appsource.microsoft.com/)
||<span data-ttu-id="8acf2-126">Пример. [Теперь виртуальный агент](https://appsource.microsoft.com/product/office/WA104381816)</span><span class="sxs-lookup"><span data-stu-id="8acf2-126">Example: [Now virtual agent](https://appsource.microsoft.com/product/office/WA104381816)</span></span>|

## <a name="3---publisher-attestation-workflow"></a><span data-ttu-id="8acf2-127">3. Publisher процесса проверки</span><span class="sxs-lookup"><span data-stu-id="8acf2-127">3.   Publisher Attestation Workflow</span></span>

<span data-ttu-id="8acf2-128">Главная страница. Это посадочная страница после входа партнера в Центр партнеров.</span><span class="sxs-lookup"><span data-stu-id="8acf2-128">Home Page: This is the landing page once a partner logs in to Partner Center.</span></span>

![Домашний экран Центра партнеров](../media/UserGuidePhotos/01.png)

<span data-ttu-id="8acf2-130">**Шаг 1.**   Слева от страницы в панели навигации:</span><span class="sxs-lookup"><span data-stu-id="8acf2-130">**Step 1**   : On the left side of the page, in the navigation bar:</span></span>
1. <span data-ttu-id="8acf2-131">Выбор Office магазина</span><span class="sxs-lookup"><span data-stu-id="8acf2-131">Select Office store</span></span>
1. <span data-ttu-id="8acf2-132">Выбор обзоров</span><span class="sxs-lookup"><span data-stu-id="8acf2-132">Select Overview</span></span>

![Office Хранилище можно найти в левой навигации](../media/UserGuidePhotos/02.png)

<span data-ttu-id="8acf2-134">Выбрав "Обзор", партнер может увидеть список приложений, представленных через Центр партнеров и доступных для Microsoft 365 соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="8acf2-134">Upon selecting ‘Overview’, partner can see list of apps submitted through Partner Center and available for the Microsoft 365 Compliance program.</span></span>

<span data-ttu-id="8acf2-135">**Шаг 2.** Выберите приложение из списка, чтобы начать процесс Publisher проверки.</span><span class="sxs-lookup"><span data-stu-id="8acf2-135">**Step 2** : Select an app from the list to begin the Publisher Attestation process.</span></span>

![Выбор приложения, которое необходимо засвидетельстов](../media/UserGuidePhotos/03.png)

<span data-ttu-id="8acf2-137">При выборе приложения будет всплывающее другое панели навигации с параметром "Соответствие требованиям приложения".</span><span class="sxs-lookup"><span data-stu-id="8acf2-137">On selecting an app, another navigation bar will pop up with option ‘App Compliance.’</span></span>

<span data-ttu-id="8acf2-138">**Шаг 3.** Выберите "Соответствие требованиям приложения"</span><span class="sxs-lookup"><span data-stu-id="8acf2-138">**Step 3**: Select ‘App Compliance’</span></span>

![Выбор соответствия требованиям приложения](../media/UserGuidePhotos/04.png)

<span data-ttu-id="8acf2-140">**Шаг 4.** Заполните Self-Assessment для Publisher проверки</span><span class="sxs-lookup"><span data-stu-id="8acf2-140">**Step 4**: Fill out the Self-Assessment Questionnaire for Publisher Attestation</span></span>

![Аттестация издателя](../media/UserGuidePhotos/5.5.PNG)

<span data-ttu-id="8acf2-142">**Примечание:** Если вы возвращались к обновлению или повторной отправке приложения, нажмите кнопку "Выберите продукт", выберите приложение и нажмите кнопку "Клон".</span><span class="sxs-lookup"><span data-stu-id="8acf2-142">**Note:** If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone.’</span></span>

![Клонировать](../media/UserGuidePhotos/05.PNG)

<span data-ttu-id="8acf2-144">Вы также можете использовать функцию импорт и экспорт, чтобы завершить форму автономной работы и импортировать ее после завершения.</span><span class="sxs-lookup"><span data-stu-id="8acf2-144">You can also leverage the Import/Export feature to complete the form offline and import it once completed.</span></span>

![Функция экспорта импорта](../media/UserGuidePhotos/06.PNG)

<span data-ttu-id="8acf2-146">Вы также можете использовать функцию импорт и экспорт, чтобы завершить форму автономной работы и импортировать ее после завершения.</span><span class="sxs-lookup"><span data-stu-id="8acf2-146">You can also leverage the Import/Export feature to complete the form offline and import it once completed.</span></span> 

<span data-ttu-id="8acf2-147">**Шаг 5.** После завершения нажмите кнопку "Отправить", теперь оценка будет "рассмотрена".</span><span class="sxs-lookup"><span data-stu-id="8acf2-147">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘under review’.</span></span>

![Щелкните Sumbit](../media/UserGuidePhotos/07.png)

![В настоящее время продолжается проверка](../media/UserGuidePhotos/08.png)

### <a name="approvereject-scenarios"></a><span data-ttu-id="8acf2-150">Утверждение и отклонение сценариев:</span><span class="sxs-lookup"><span data-stu-id="8acf2-150">Approve/Reject Scenarios:</span></span>

<span data-ttu-id="8acf2-151">**Отклонение Publisher проверки**</span><span class="sxs-lookup"><span data-stu-id="8acf2-151">**A.Publisher Attestation Rejection**</span></span>

<span data-ttu-id="8acf2-152">В случае отказа на данном этапе партнер может:</span><span class="sxs-lookup"><span data-stu-id="8acf2-152">In case of rejection at this stage, an partner can:</span></span>
-   <span data-ttu-id="8acf2-153">Просмотр отчета о сбое.</span><span class="sxs-lookup"><span data-stu-id="8acf2-153">View failure report.</span></span>
    - <span data-ttu-id="8acf2-154">Партнер будет уведомлен по электронной почте, и он может просматривать отчет о сбое в Центре партнеров</span><span class="sxs-lookup"><span data-stu-id="8acf2-154">Partner will be notified via email, and they can view the failure report in Partner Center</span></span>
-   <span data-ttu-id="8acf2-155">Обновление и повторное Publisher аттестации ![ и повторное повторное тестирование](../media/UserGuidePhotos/09.png)</span><span class="sxs-lookup"><span data-stu-id="8acf2-155">Update and re-submit Publisher Attestation ![Update and resubmit assessment](../media/UserGuidePhotos/09.png)</span></span>

<span data-ttu-id="8acf2-156">**Повторное представление Publisher проверки**</span><span class="sxs-lookup"><span data-stu-id="8acf2-156">**B.Publisher Attestation Re-submission**</span></span>

![Повторное повторное повторное рассмотрение](../media/PA%20resubmission.png)

<span data-ttu-id="8acf2-158">**Утверждение Publisher проверки C.Publisher**</span><span class="sxs-lookup"><span data-stu-id="8acf2-158">**C.Publisher Attestation Approval**</span></span>

-   <span data-ttu-id="8acf2-159">После утверждения партнер может:</span><span class="sxs-lookup"><span data-stu-id="8acf2-159">Upon approval partner can:</span></span>
    - <span data-ttu-id="8acf2-160">Обновление и повторное тестирование</span><span class="sxs-lookup"><span data-stu-id="8acf2-160">Update and resubmit attestation</span></span>
    - <span data-ttu-id="8acf2-161">Просмотр и совместное Publisher проверки</span><span class="sxs-lookup"><span data-stu-id="8acf2-161">View and share completed Publisher Attestation</span></span>
    - <span data-ttu-id="8acf2-162">Запуск процесса сертификации M365</span><span class="sxs-lookup"><span data-stu-id="8acf2-162">Start M365 Certification Process</span></span>

![Обновление и повторное повторное обновление](../media/AttestApproval.PNG)

![<span data-ttu-id="8acf2-164">Просмотр завершенной проверки</span><span class="sxs-lookup"><span data-stu-id="8acf2-164">View completed attestation</span></span> ](../media/PA%20approval%202.png)

![Начало сертификации приложений M365](../media/PA%20approval%203.png)

<span data-ttu-id="8acf2-166">**Утверждение Publisher: пример ссылки в AppSource для заверенных приложений издателя**</span><span class="sxs-lookup"><span data-stu-id="8acf2-166">**Post Publisher Verification Approval: Example of link in AppSource for publisher attested apps**</span></span>

![Пример завершенной проверки](../media/Example%20to%20attested%20apps.png)

## <a name="4-microsoft-365-certification-workflow"></a><span data-ttu-id="8acf2-168">4. Microsoft 365 процесса сертификации</span><span class="sxs-lookup"><span data-stu-id="8acf2-168">4. Microsoft 365 Certification Workflow</span></span>

<span data-ttu-id="8acf2-169">Как только партнер нажимает кнопку "Отправить" и передает все документы и доказательства для проверки:</span><span class="sxs-lookup"><span data-stu-id="8acf2-169">Once partner clicks on ‘Submit’ and submits all documents and evidence for review:</span></span> 

### <a name="microsoft-365-certification---submitted"></a><span data-ttu-id="8acf2-170">Microsoft 365 Сертификация — отправка</span><span class="sxs-lookup"><span data-stu-id="8acf2-170">Microsoft 365 Certification - Submitted</span></span>

![Началась сертификация](../media/certification%201.png)

<span data-ttu-id="8acf2-172">**Microsoft 365 сертификации — отклонено**</span><span class="sxs-lookup"><span data-stu-id="8acf2-172">**Microsoft 365 certification - Rejected**</span></span>

![Отклоненная сертификация](../media/certification%20rejected.png)

<span data-ttu-id="8acf2-174">**Microsoft 365 Сертификация — утверждена**</span><span class="sxs-lookup"><span data-stu-id="8acf2-174">**Microsoft 365 Certification - Approved**</span></span>

![Сертификация утверждена](../media/certification%20approved.png)

<span data-ttu-id="8acf2-176">**Утверждение сертификации после публикации: пример значка Microsoft 365 сертификации в AppSource**</span><span class="sxs-lookup"><span data-stu-id="8acf2-176">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource**</span></span>

![Пример значка сертификации](../media/post%20certification%20badge.png)

## <a name="5-workflow-for-existing-isvs"></a><span data-ttu-id="8acf2-178">5. Рабочий процесс для существующих isVs</span><span class="sxs-lookup"><span data-stu-id="8acf2-178">5. Workflow for Existing ISVs</span></span>

<span data-ttu-id="8acf2-179">Если вы уже имеете isV и хотите обновить Publisher проверку.</span><span class="sxs-lookup"><span data-stu-id="8acf2-179">If you are an existing ISV and want to Update Publisher Attestation.</span></span>

<span data-ttu-id="8acf2-180">**Шаг 1.** Нажмите на ссылку "Обновление и повторное отправка Publisher проверки".</span><span class="sxs-lookup"><span data-stu-id="8acf2-180">**Step 1**: Click on ‘Update and re-submit your Publisher Attestation’ link.</span></span>

![<span data-ttu-id="8acf2-181">Обновление Publisher проверки</span><span class="sxs-lookup"><span data-stu-id="8acf2-181">Update Publisher Attestation</span></span> ](../media/existing%20isv%201.png)

<span data-ttu-id="8acf2-182">**Примечание.** Если вы возвращались к обновлению или повторной отправке приложения, нажмите кнопку "Выберите продукт", выберите приложение и нажмите кнопку "Импорт".</span><span class="sxs-lookup"><span data-stu-id="8acf2-182">**Note:**: If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Import’.</span></span>

![Тестирование импорта для другой интеграции](../media/M365%20App%20compliance.png)

![Нажмите кнопку Импорт](../media/M365%20App%20compliance1.png)

<span data-ttu-id="8acf2-185">**Шаг 2.** Внести обновления в форму и нажмите кнопку Сохранить/Отправить.</span><span class="sxs-lookup"><span data-stu-id="8acf2-185">**Step 2**: Make updates to your form and click Save/Submit.</span></span>

![Щелкните Сохранить или Отправить](../media/existing%20isv%202.png)

<span data-ttu-id="8acf2-187">После отправки оно будет рассмотрено.</span><span class="sxs-lookup"><span data-stu-id="8acf2-187">Once submitted, it will be under review.</span></span>

![Проверка на стадии рассмотрения](../media/existing%20isv%203.png)

## <a name="6---microsoft-365-publisher-attestation-and-certification-renewal-workflow"></a><span data-ttu-id="8acf2-189">6. Microsoft 365 Publisher процесса аттестации и обновления сертификации:</span><span class="sxs-lookup"><span data-stu-id="8acf2-189">6.   Microsoft 365 Publisher Attestation and Certification Renewal Workflow:</span></span>

<span data-ttu-id="8acf2-190">Microsoft 365 Программа соответствия требованиям приложений теперь предлагает ежегодный процесс обновления.</span><span class="sxs-lookup"><span data-stu-id="8acf2-190">Microsoft 365 App Compliance Program now offers an annual renewal process.</span></span> <span data-ttu-id="8acf2-191">В ходе этого процесса разработчики приложений могут обновить существующий Publisher аттестации и документы, необходимые для Microsoft 365 сертификации.</span><span class="sxs-lookup"><span data-stu-id="8acf2-191">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 

<span data-ttu-id="8acf2-192">**Преимущества:**</span><span class="sxs-lookup"><span data-stu-id="8acf2-192">**Benefits:**</span></span>

- <span data-ttu-id="8acf2-193">Сохраните значок сертификации в AppSource и Team Store, чтобы отличать приложение от других.</span><span class="sxs-lookup"><span data-stu-id="8acf2-193">Maintain your certification badge in AppSource and Team Store to differentiate your app from others.</span></span> 
- <span data-ttu-id="8acf2-194">Повышение доверия клиентов к использованию сертифицированного приложения.</span><span class="sxs-lookup"><span data-stu-id="8acf2-194">Increase customer confidence in using your certified app.</span></span> 
- <span data-ttu-id="8acf2-195">Помощь ИТ-администраторам в принятии обоснованных решений с помощью обновленных сведений о сертификации.</span><span class="sxs-lookup"><span data-stu-id="8acf2-195">Help IT admins make informed decisions with updated certification information.</span></span> 

<span data-ttu-id="8acf2-196">Новый процесс обновления доступен в [Центре партнеров для](https://partner.microsoft.com/en-us/dashboard/home) обеспечения бесперебойного работы.</span><span class="sxs-lookup"><span data-stu-id="8acf2-196">The new renewal process is available in [Partner Center](https://partner.microsoft.com/en-us/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="8acf2-197">Напоминание о возобновлении будет показано в Центре партнеров, начиная с 90 дней до истечения срока действия.</span><span class="sxs-lookup"><span data-stu-id="8acf2-197">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="8acf2-198">Периодические напоминания также будут отправляться по электронной почте за 90, 60 и 30 дней до истечения срока действия.</span><span class="sxs-lookup"><span data-stu-id="8acf2-198">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span>

<span data-ttu-id="8acf2-199">**Tier 1: Publisher проверки:**</span><span class="sxs-lookup"><span data-stu-id="8acf2-199">**Tier 1: Publisher Attestation Renewal:**</span></span> 

<span data-ttu-id="8acf2-200">Ответы на Publisher проверки приложения необходимо будет повторно повторно переподавлить на ежегодной основе.</span><span class="sxs-lookup"><span data-stu-id="8acf2-200">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="8acf2-201">Когда заверение близит к 1-летней отметке, будет отправлено напоминание по электронной почте, поощряющее повторное повторное тестирование.</span><span class="sxs-lookup"><span data-stu-id="8acf2-201">When the attestation nears 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 

<span data-ttu-id="8acf2-202">**Шаг 1.** **Выберите обновление** для обновления Publisher проверки.</span><span class="sxs-lookup"><span data-stu-id="8acf2-202">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span> 

![Microsoft 365Publisher процесса аттестации и обновления сертификации ](../media/AppComplianceExpirationNotice.png)

<span data-ttu-id="8acf2-204">**Шаг 2.** Просмотрите предыдущие ответы Publisher проверки и обновив при необходимости последнюю информацию.</span><span class="sxs-lookup"><span data-stu-id="8acf2-204">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> <span data-ttu-id="8acf2-205">Отправка Publisher для обновления при готовности.</span><span class="sxs-lookup"><span data-stu-id="8acf2-205">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="8acf2-206">Она будет рассмотрена аналитиком соответствия требованиям приложений M365.</span><span class="sxs-lookup"><span data-stu-id="8acf2-206">It will be reviewed by an M365 App Compliance Analyst.</span></span>

![Microsoft 365Publisher процесса аттестации и обновления сертификации ](../media/2.PNG)

<span data-ttu-id="8acf2-208">Publisher истек срок **проверки:** Сведения о приложении должны быть обновлены до истечения срока действия, чтобы сохранить страницу Publisher проверки в документы Майкрософт. Вовремяе обновление также обеспечит продолжение работы и значки для приложения в AppSource и Team Store.</span><span class="sxs-lookup"><span data-stu-id="8acf2-208">**Publisher Attestation Expired:** The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![Microsoft 365Publisher процесса аттестации и обновления сертификации ](../media/3.PNG)

<span data-ttu-id="8acf2-210">Примечание. По истечении срока действия Publisher обновления может быть запущен в любое время, нажав кнопку "Обновить".</span><span class="sxs-lookup"><span data-stu-id="8acf2-210">Note: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span> 

<span data-ttu-id="8acf2-211">**Tier 2: Microsoft 365 сертификации**</span><span class="sxs-lookup"><span data-stu-id="8acf2-211">**Tier 2: Microsoft 365 Certification Renewal**</span></span> 

<span data-ttu-id="8acf2-212">Сведения о сертификации приложения должны быть повторно перенаблюированы на ежегодной основе.</span><span class="sxs-lookup"><span data-stu-id="8acf2-212">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="8acf2-213">Для этого потребуется переоценка элементов управления в области текущей среды.</span><span class="sxs-lookup"><span data-stu-id="8acf2-213">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="8acf2-214">Когда сертификация близит к 1-летней отметке, будет отправлено уведомление по электронной почте с призывом к повторной отправке документов и доказательств.</span><span class="sxs-lookup"><span data-stu-id="8acf2-214">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span> 

<span data-ttu-id="8acf2-215">**Сценарии утверждения и отказа от сертификации:**</span><span class="sxs-lookup"><span data-stu-id="8acf2-215">**Certification Renewal Approve/Reject Scenarios:**</span></span>

<span data-ttu-id="8acf2-216">**Сценарий 1.**</span><span class="sxs-lookup"><span data-stu-id="8acf2-216">**Scenario 1:**</span></span> 

<span data-ttu-id="8acf2-217">Publisher Проверки завершены.</span><span class="sxs-lookup"><span data-stu-id="8acf2-217">Publisher Attestation  is complete.</span></span> <span data-ttu-id="8acf2-218">Обновление сертификации началось и находится в стадии рассмотрения.</span><span class="sxs-lookup"><span data-stu-id="8acf2-218">Certification renewal has started and under review.</span></span> 

![Microsoft 365Publisher процесса аттестации и обновления сертификации ](../media/4.PNG)

<span data-ttu-id="8acf2-220">**Сценарий 1A:**</span><span class="sxs-lookup"><span data-stu-id="8acf2-220">**Scenario 1A:**</span></span>

<span data-ttu-id="8acf2-221">Отказ от продления сертификации: сертификация может быть отклонена, если:</span><span class="sxs-lookup"><span data-stu-id="8acf2-221">Certification renewal rejection: Certification may be rejected if:</span></span> 

 - <span data-ttu-id="8acf2-222">Приложение не имеет необходимых инструментов, процессов или конфигураций на месте и не сможет реализовать необходимые изменения в окне сертификации.</span><span class="sxs-lookup"><span data-stu-id="8acf2-222">The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> 
 - <span data-ttu-id="8acf2-223">Приложение имеет непогашенные уязвимости и не может быть исправлено в окне сертификации.</span><span class="sxs-lookup"><span data-stu-id="8acf2-223">The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 

![Microsoft 365Publisher процесса аттестации и обновления сертификации ](../media/5.PNG)
    
<span data-ttu-id="8acf2-225">**Сценарий 1B:**</span><span class="sxs-lookup"><span data-stu-id="8acf2-225">**Scenario 1B:**</span></span> 

<span data-ttu-id="8acf2-226">Утверждено продление сертификации</span><span class="sxs-lookup"><span data-stu-id="8acf2-226">Certification renewal is approved</span></span>  

![Microsoft 365Publisher процесса аттестации и обновления сертификации ](../media/6.PNG)

<span data-ttu-id="8acf2-228">**Срок действия сертификации:**</span><span class="sxs-lookup"><span data-stu-id="8acf2-228">**Certification Expiration:**</span></span>

<span data-ttu-id="8acf2-229">Сведения о приложении необходимо обновлять до истечения срока действия, чтобы сохранить страницу сертификации приложения в документы Майкрософт. Вовремяе обновление также обеспечит продолжение работы и значки для приложения в AppSource и Team Store.</span><span class="sxs-lookup"><span data-stu-id="8acf2-229">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span> 

![Microsoft 365Publisher процесса аттестации и обновления сертификации ](../media/7.PNG)
    
<span data-ttu-id="8acf2-231">**Примечание.** По истечении срока действия Publisher проверки и сертификации можно начать в любое время, нажав кнопку "Обновить".</span><span class="sxs-lookup"><span data-stu-id="8acf2-231">**Note**: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 












