# Sanam's Dessert Diary — GitHub Pages prototype

This is a static, browser-only prototype for Sanam's Dessert Diary. The uploaded bakery logo is embedded inside `index.html`, so no separate logo file is needed.

## Publish with GitHub Pages

1. Sign in at https://github.com/ and create a new repository named `sanams-dessert-diary`.
2. For a GitHub Free account, make the repository **Public** if you want to publish it with GitHub Pages.
3. On the repository page, choose **Add file → Upload files**.
4. Upload `index.html` and `.nojekyll` from this folder. You may also upload this README.
5. Commit the files to the `main` branch.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Select branch `main` and folder `/(root)`, then click **Save**.
9. Wait for the deployment. Under **Settings → Pages**, click **Visit site**. The public URL will usually look like `https://YOUR-USERNAME.github.io/sanams-dessert-diary/`.

Official guide: https://docs.github.com/en/pages/quickstart

## Important prototype limitations

- The site uses `localStorage` in the visitor's browser.
- Products, settings, and feedback are saved only in the browser where the changes are made.
- If the owner adds or changes a product in their own browser, those changes **will not automatically appear for other customers**.
- Each visitor's feedback is saved only in that visitor's browser; the owner cannot see feedback submitted from other devices.
- Browser storage has limited capacity, particularly for images.
- The Settings and Owner's Corner panels are **not protected by a secure login**. Do not treat them as a private admin system.
- GitHub Pages is static hosting and does not provide a database or server-side permissions.

Use this version for testing the layout and interactions. For a real bakery launch, add a cloud backend with authentication and database security rules before collecting orders or relying on shared product data.
