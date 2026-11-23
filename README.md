# Before the medicine request

Khaled Alrefai · Android · Istanbul · 23 November 2026

[Web edition](https://kaldx5.github.io/medico-amigo-qa-audit/) · [Illustrated PDF](field-notes.pdf)

## Sign-in across two visits

<table><tr><td align="center" width="33%"><a href="assets/review/first.png"><img src="assets/review/first.png" alt="First visit. I could not see a language switch." width="230"></a><br>First visit. I could not see a language switch.</td><td align="center" width="33%"><a href="assets/review/picker.png"><img src="assets/review/picker.png" alt="Google opened its account picker. I chose my account and returned to sign-in." width="230"></a><br>Google opened its account picker. I chose my account and returned to sign-in.</td><td align="center" width="33%"><a href="assets/review/language.png"><img src="assets/review/language.png" alt="After reopening. The EN / PT switch appeared." width="230"></a><br>After reopening. The EN / PT switch appeared.</td></tr></table>

I opened Médico Amigo to see how a patient requests medication. I reached the sign-in choices and the NIF verification flow. I do not have a Portuguese tax number of my own, so my review ends before the request.

## Choosing my Google account

I tapped Google, picked my account and found myself looking at the same two buttons again. I saw no message. Should I retry, or did I need a NIF anyway? One line explaining the next step would have helped.

## One step back

On the NIF entry screen I changed my mind and pressed Back to try Google. I ended up outside the app. I reopened it to get back to the two choices I had just seen.

## Finding English on my second visit

I could not see a language switch the first time. After I removed the app from recent apps and reopened it, EN / PT appeared. The NIF button wording changed too. I wanted that language choice before I had to interpret the first prompt.

## One change I would make

Show the NIF for review before requesting a code. I would give the patient a chance to correct a mistyped digit and make the effect of the next tap explicit.

![Observed Google sign-in and proposed code verification flows](report-preview.png)

### Reading the status bar

The clock and connection icons looked faint on my phone. Stronger contrast would make them easier to read at a glance.

![Status bar crop showing faint system icons](assets/review/contrast.png)

## Before sending a code

I liked that the field stopped at nine digits and gave feedback on invalid input. What surprised me was going from “Continuar” to a message saying a code had been sent. I had expected one more chance to review the digits. I stopped at that screen.

<table><tr><td align="center" width="33%"><a href="assets/review/validation.png"><img src="assets/review/validation.png" alt="The field rejected the all-zero entry." width="230"></a><br>The field rejected the all-zero entry.</td><td align="center" width="33%"><a href="assets/review/entry.png"><img src="assets/review/entry.png" alt="A validation message was also visible during my second entry." width="230"></a><br>A validation message was also visible during my second entry.</td><td align="center" width="33%"><a href="assets/review/code.png"><img src="assets/review/code.png" alt="Later I reached the code screen. The destination is covered." width="230"></a><br>Later I reached the code screen. The destination is covered.</td></tr></table>

### Where I stopped

With a demo profile I would change a medicine selection before confirming it and check how the app tells me when a clinician receives the request.
