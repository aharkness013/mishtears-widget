# MishTears 😭

A tiny Home Screen widget that shows how many days it's been since Mish last cried — with a button that resets it back to zero when it happens again. Everyone who sets this up sees the same live count.

## Install it (about 2 minutes)

1. Install **Scriptable** from the App Store — it's free.
2. Open Scriptable, tap the **+** in the top right, delete the placeholder code, and paste in everything from the [`Mishtears`](./Mishtears) file in this repo.
3. Tap the script's name at the top and rename it to `MishTears`.
4. Tap the ▶️ Play button to run it. A pop-up will ask for a **Firebase project ID** — this isn't written here on purpose, so ask the person who sent you this link for it directly, paste it in, and tap Save.
5. You should now see the day count and a red **"I cried today"** button.
6. Long-press your Home Screen → tap **+** in the corner → search for **Scriptable** → choose the small or medium size → add it.
7. Long-press the new widget → **Edit Widget** → set the script to `MishTears`.

Done — the widget refreshes roughly every 30 minutes on its own, and opening it always shows the live, up-to-date count.

## Please don't

- Don't post the project ID anywhere public (a comment here, a public chat, etc.) — anyone who has it can read *and reset* the counter, since there's no login on purpose to keep setup simple. Keep it inside the friend group.
- Don't fork or republish this repo with the ID filled in anywhere.

## Something not working?

- **Pop-up never appears / button does nothing**: make sure you pasted the *entire* file, and that Scriptable didn't silently fail to save it (reopen the script and check it's all there).
- **Widget stuck on "Tap to finish setup"**: tap it once — that opens the app and should show the project ID prompt if you haven't done that step yet.
- Anything else: ask whoever sent you this.
