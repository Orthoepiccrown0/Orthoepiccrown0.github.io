# DirectStream SDK landing page

Jekyll publishes `index.html` at `/directStreamSDK/`. The page shares the
portfolio stylesheet; `style.css` adds product-specific layouts.

Assets are original, editable SVGs in `assets/`:

- `video-calls.svg`: paired video-call illustration, also used on the homepage.
- `call-flow.svg`: accessible default-provider architecture diagram, with a
  full-size link and a text explanation on the landing page.

Content was checked against the SDK README, `docs/ARCHITECTURE.md` and
`docs/CODECS.md` in https://github.com/Orthoepiccrown0/webrtc-android at the
revision recorded below. There are deliberately no setup tutorials or code
samples. Keep installation claims scoped to the SDK starter: host dependencies
and cloud-service configuration are still required. Codec availability depends
on both peers' bundled WebRTC capabilities, not the Android codec list alone.
Source revision: `7901a3b5cc107045594e3a087d0d4cd8e5043809`.
