# Kharcha

A daily college spending tracker that runs offline on your phone. All data stays on the phone.

## Put it online (one time, about 5 minutes)
1. On GitHub, create a new public repository named `kharcha`.
2. Click **Add file → Upload files**, drag in every file from this folder, then click **Commit changes**.
3. Go to **Settings → Pages**. Under *Branch*, pick `main` and `/ (root)`, then click **Save**.
4. Wait about a minute. Your app is live at `https://<your-username>.github.io/kharcha/`.

## Install on your Android phone
1. Open that link in **Chrome**.
2. Tap **⋮ → Add to Home screen → Install**.
3. Open Kharcha from the home screen. It now works with no internet.

## Using it
- **Add**: type the amount, pick a category, then tap Save. Use **Got back** when Anushka or a friend pays you back.
- **Your own categories**: tap **+ New** when adding an expense (e.g. Gym, Printouts). Remove them in Settings.
- **Quick add from the home screen**: long-press the Kharcha icon and pick **Add expense**.
- **Months**: use the arrows, or swipe left/right on the ring card.
- **Edit**: tap an entry. **Delete**: swipe it left (you can undo).
- **The ring** is your monthly pocket money. Tap **Pocket money ₹2,000** above it to change this month only (for example, +₹1,000 when you get extra). The white tick shows where you should be by today.
- **Haptics** can be switched off in Settings.
- **Settings (sliders icon)**: change the default pocket money for every month, and Export a backup now and then.

## Changing the app later
Edit `index.html`, then in `sw.js` change the version name (e.g. `kharcha-v3` to `kharcha-v4`) (and so on) so phones pick up the new version. Upload both files again.
