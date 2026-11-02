# Shares launcher

A tiny page that gives the Share Recommender app its own iPhone home-screen icon. Streamlit
Community Cloud doesn't let an app set the home-screen icon, so this page carries the icon
and forwards to the app.

- `https://iancwy.github.io/shares/` forwards straight to the app (what the home-screen
  shortcut opens).
- `https://iancwy.github.io/shares/?setup` stays put and shows how to add it to the home
  screen. Open this one in Safari, then Share > Add to Home Screen.

It holds only the icon and a redirect: no code or data from the app. The app's address is
`APP_URL` in `index.html`. Hosted with GitHub Pages (Settings > Pages > Deploy from a branch,
`main`, `/ (root)`).
