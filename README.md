# Pet Relive — AR dog prototype

A dog in augmented reality on your phone, in the browser. Place it on your real floor, throw a ball for fetch, and pet it.

- **Android (Chrome):** real WebXR AR. The dog is anchored to your floor and stays put as you walk around.
- **iPhone:** iOS browsers don't support WebXR AR, so the app uses camera mode: the dog is drawn over the live camera and follows the phone's orientation.
- **Meta Quest 3:** also works as mixed reality with hands or controllers.
- Upload a dog photo to color the simple dog, or load a realistic rigged dog (`.glb` / `.fbx`) with walk, run, idle and sit clips.

Built with Three.js loaded from a CDN. No build step: the whole app is `index.html`.

## Run it

1. Turn on GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root. (Free accounts need a public repo for Pages.)
2. Open `https://<your-user>.github.io/<repo>/` on your phone.
3. Tap **Start AR** (Android) or **Start camera mode** (iPhone).
