# QuickApply
Free, offline-first job application PWA. No server, accounts or paid APIs.

## Publish on GitHub Pages
1. Create a public GitHub repository named `quickapply`.
2. Upload **the contents** of this folder to the repository root.
3. In Settings > Pages, choose Deploy from a branch, `main`, `/ (root)` and Save.
4. Open `https://YOUR_USERNAME.github.io/quickapply/` in Android Chrome.
5. Chrome menu > Add to Home screen / Install app.
6. Open it once online so its assets are cached for offline use.

## Usage
Save your PDF CV once. Type the recipient. Choose **Share CV** to open Android's share sheet (select Gmail if available). Some Android/Gmail versions may ignore shared subject or message. Alternatively use **Open email** to prefill subject and body, then attach your CV manually. **Copy message** provides a fallback.

## Privacy and limitations
CV is stored in browser IndexedDB; template is stored in localStorage. Neither is uploaded by this app. Clearing site data, uninstalling, or switching browsers may erase stored files. Web Share API requires HTTPS (GitHub Pages provides this). Gmail must still be online to send. Sharing a file does not guarantee Gmail receives the recipient, subject and body together. Review everything before sending. The app does not send email itself.
