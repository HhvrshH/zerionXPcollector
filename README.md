# Zerion XP Collector

Written by: @hvrsh (TG)

Channel: https://t.me/hashvers

---
**Automation of Interactions with Zerion wallet**

**Configuration upon launching `zerion.xml`:**

1. Use Finger Switcher - Should fingerprints be used?
   1. Finger Print Key - If enabled with **1**, a key is required to obtain fingerprints, which can be purchased here - https://fingerprints.bablosoft.com/
2. Threads - Number of concurrently running threads.
3. Sleep - Time between accounts in the thread.
4. Retries - how much retries will be on fails.
5. Clear DoneList - After successful completion or insufficient balance, private keys are recorded in the file `done_list.txt` so the software understands which accounts it has processed and which ones it hasn't. In case you interrupt its operation or a thread terminates with an error, if you need to rerun all wallets, select Yes.
7. Wallet shuffle - Should wallet shuffling be performed?

 **Files for Operation**

 `private.txt` - Specify private keys.

 `proxy.txt` - Proxies, selected line by line.

 `invites.txt` - You can add your own codes, or keep it empty. Script Will record invites from each acc to this file that use them in next registrations.
