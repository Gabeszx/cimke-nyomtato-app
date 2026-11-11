# Címke nyomtató – telepíthető app

Telepíthető (PWA) burok a [Címke nyomtató](https://github.com/Gabeszx/Cimke-nyomtato) Apps Script webapphoz.

**Telepítés:** https://gabeszx.github.io/cimke-nyomtato-app/ → Android Chrome: menü → *Alkalmazás telepítése*;
iPhone Safari: Megosztás → *Főképernyőhöz adás*; asztali Chrome/Edge: a címsor telepítés ikonja.

Az `index.html` iframe-ben az éles (`/exec`) telepítést tölti be; ha az éles telepítés azonosítója
változna, ott kell átírni. A manifest `id`-je (`/cimke-nyomtato-app/`) maradjon egyedi és változatlan,
különben a gabeszx.github.io alatti többi appal ütközik, vagy a már telepített példány árván marad.
