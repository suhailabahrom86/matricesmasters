MATRICES MASTERS — Firebase cross-device sync package

1. Upload index.html and matrices-firebase-config.js to the ROOT of the GitHub repository.
2. In Firebase Console, open project explog-134ae -> Firestore Database -> Rules.
3. Replace/publish the rules using firestore-rules.txt.
4. Wait for GitHub Pages deployment, then hard refresh.
5. The app should show "Cloud Connected".
6. Submit one quiz attempt. Firestore Data should create chapter6Results automatically.
7. Open Teacher Dashboard on another device; the same participant should appear through onSnapshot().

Important:
- Collection used everywhere: chapter6Results
- Teacher access code remains in the app as configured.
- This package removes anonymous-auth dependency, so Firestore access is controlled by the published Firestore Rules.
