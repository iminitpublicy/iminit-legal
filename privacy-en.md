# Privacy Policy for the iminit Mobile Application

Last updated: October 1, 2026.

## 1. General information

This Privacy Policy explains what data is processed when you use the iminit mobile application, why it is processed, and which services are involved.

iminit is an IT interview preparation trainer for QA, Frontend, Backend, Data, and DevOps roles. Users answer interview questions, and an AI-based system evaluates answers for accuracy, completeness, and clarity and provides feedback. The app also includes timed mock interviews.

The personal data operator is Matvey Igorevich Kolmakov, an individual applying the Russian special tax regime for self-employed persons (Professional Income Tax).

Taxpayer Identification Number (INN): 440131020663.

Privacy contact: iminitapp@mail.ru.

## 2. Data we process

### 2.1. User text answers

When a user submits an answer for AI evaluation, the answer text is sent to the iminit backend hosted in Yandex Cloud and then to YandexGPT to generate scores and feedback.

The iminit backend does not store user answer text in its application database after the request is completed.

An answer may contain information voluntarily entered by the user. Users should not include names, contact details, identity documents, passwords, payment details, health information, or other information that is not necessary for interview preparation.

### 2.2. Technical data

To protect the service against abuse and excessive requests, the IP address associated with a network request may be processed.

When certain feedback features are used, technical information such as the Android platform, app interface language, and event timestamp may also be transmitted.

This information is not used to display advertising.

### 2.3. Voice input

Voice input is optional. Microphone access is requested only after the user actively starts dictation.

iminit uses the Android system speech-recognition service through expo-speech-recognition. Depending on the device and its settings, recognition may be performed locally on the device or through the system speech-recognition provider, which may be Google.

The iminit developer does not store the audio recording and does not receive the audio file on the iminit backend. Audio is not sent to YandexGPT.

After recognition, the application receives text. If the user submits that text for AI evaluation, it is processed as a regular text answer as described in Section 2.1.

Users may deny microphone access and type answers manually.

## 3. Data stored locally on the device

User progress, completed questions, scores, local usage limits, and mock interview history are stored locally on the user's device in the application's storage.

This data is not synchronized with an account because iminit does not use registration or authentication, and the full progress history is not transmitted to the server.

Mock interview history may include answers entered by the user. Such data remains on the device except for individual answers that the user submits for AI evaluation.

Local data that is not transmitted from the device is not received by the operator.

## 4. Feedback through Google services

### 4.1. Reporting an incorrect AI evaluation

If the user believes an AI evaluation is incorrect and voluntarily taps “Assessment wrong?”, the app sends information through Google Apps Script to Google Sheets so that the developer can review that specific case.

The information sent may include:

- the question identifier and question text;
- the user's answer text;
- the AI evaluation result and textual AI feedback;
- interface language;
- Android platform;
- submission timestamp.

This information is sent only after an explicit user action — tapping “Assessment wrong?” — and is used to review AI evaluation quality, identify errors, and improve the answer-evaluation feature.

Regular user answers are not automatically sent to Google Sheets. If the user does not use the “Assessment wrong?” feature, their answer text is not sent to Google as part of this feedback flow.

### 4.2. Interest in Pro

If the user taps “Want Pro”, “Notify me”, or a similar control related to the future Pro subscription, the app may send a service event through Google Apps Script to Google Sheets.

Such an event may include the event type and source, interface language, Android platform, timestamp, and, on certain screens, the question identifier.

The user's name, email address, phone number, and answer text are not sent as part of this event.

### 4.3. Bug reports

The “Report a bug” feature opens an external Google Forms page.

Information voluntarily entered by the user in that form is transmitted to Google Forms and may be stored in a linked Google Sheets spreadsheet so that the developer can process the report.

The exact information depends on the form fields and what the user chooses to submit. Users should not provide information that is not necessary to describe the issue.

## 5. Data the app does not automatically collect

iminit does not require registration or authentication.

The app does not automatically collect the user's name, email address, or phone number.

The app does not contain advertising SDKs or analytics SDKs such as Firebase Analytics or AppMetrica.

As of the date of this Policy, the app does not include payments or an active paid subscription.

## 6. Purposes of processing

Data is processed to:

- provide AI evaluation and feedback for text answers;
- operate mock interview features;
- provide optional speech recognition;
- protect the backend against abuse and excessive requests;
- review voluntarily submitted reports about incorrect AI evaluations, including the user's answer and the AI evaluation result;
- record voluntarily expressed interest in a future Pro subscription;
- process voluntarily submitted bug reports;
- maintain service security and stability.

## 7. Third-party services

The following services are used for certain iminit features:

- Yandex Cloud — backend hosting;
- YandexGPT — AI evaluation of text answers;
- Google Apps Script and Google Sheets — processing voluntary AI-evaluation reports and limited service feedback events;
- Google Forms — voluntary bug reports;
- Android system speech-recognition service — voice input processing; depending on the device, the provider may be Google.

The YandexGPT API key is stored only on the iminit backend and is not included in the mobile application.

iminit does not sell user data to advertising networks.

## 8. Data retention

Text answers submitted for AI evaluation are not stored in the iminit backend application database after completion of the AI request.

Technical data is processed to the extent necessary to protect the service and enforce request limits.

Service events, AI-evaluation reports, and other reports submitted through Google Apps Script, Google Sheets, or Google Forms may remain in those services until deleted by the developer, unless longer retention is required to review quality, process the report, or comply with applicable law.

Local progress and mock interview history remain on the user's device until deleted by the user, cleared through Android application settings, or removed together with the application.

## 9. Data deletion

Because iminit does not use user accounts, the developer does not maintain a unified server-side progress history for each user.

Local data can be deleted through the application where a relevant deletion function is available, by clearing the application's data in Android settings, or by uninstalling the application.

Text answers submitted for AI evaluation are not stored in the iminit backend database after processing is completed.

If the user submitted a report through Google Forms or used features that created records in Google Sheets, the user may request deletion of the relevant data by contacting iminitapp@mail.ru. Information sufficient to identify the specific report or event may be required.

If the relevant data can be reliably located and associated with the user's request, it will be deleted or its processing will be stopped where required by applicable Russian law.

## 10. User rights

Users may request information about the processing of personal data relating to them, request correction, blocking, or deletion of such data, and withdraw previously given consent to processing.

Requests should be sent to iminitapp@mail.ru.

Withdrawal of consent does not affect data that remains only on the user's device and has not been transmitted to the operator. Users may delete such data themselves.

## 11. Security

Data transfers between the application and the iminit backend, and between the backend and YandexGPT, use HTTPS.

The YandexGPT API key is kept on the server and is not stored in the mobile application.

The developer applies reasonable technical measures to restrict backend access and prevent abuse.

## 12. Possible future changes

A Pro subscription and additional paid features may be introduced in the future.

Before payment data or other new categories of data are processed, this Policy and the RuStore data-safety disclosures will be updated.

If the services used by the app, the categories of processed data, or the processing purposes change, an updated version of this Policy will be published before those changes take effect.

## 13. Contact

Personal data operator: Matvey Igorevich Kolmakov.

Status: individual applying the Russian special tax regime for self-employed persons (Professional Income Tax).

Taxpayer Identification Number (INN): 440131020663.

For privacy, data-processing, or deletion requests: iminitapp@mail.ru.
