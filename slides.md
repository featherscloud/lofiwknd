---
theme: ./theme
class: text-center
highlighter: shiki
lineNumbers: false
info: Vancouver DWeb Local First Weekend
transition: slide-left
title: DWeb Local First Weekend
background: /images/lofiwkndyvr.svg
---

---
class: text-2xl bg-white text-center text-gray-600
---

<h1 style="font-size: 3rem;">Where are we?</h1>

<img src="/images/z-space-logo.jpg" alt="Z-Space Logo" style="margin: 0 auto;" />

---
class: text-2xl bg-white text-center text-gray-600
---

<h1 style="font-size: 3rem;" class="pb-8">Who are we?</h1>

<img src="/images/sponsor-logos.png" alt="Z-Space Logo" style="margin: 0 auto;" />

---
class: text-2xl bg-gray-300 text-gray-600
---

<h1 style="font-size: 3rem">What's DWeb</h1>

<p>DWeb connects the people, projects and protocols essential to building a decentralized web. A web that is more private, reliable, secure and open. A web with many winners—returning to the original vision of the World Wide Web and internet.</p>

<img src="/images/dwebyvr-logo.svg" style="margin: 0 auto;" width="300" alt="Webassembly image" />

---
class: text-3xl bg-gray-300 text-gray-600
---

<h1 style="font-size: 3rem">DWeb principles</h1>

<ol class="pl-6">
  <li>Technology for Human Agency</li>
  <li>Distributed Benefits</li>
  <li>Mutual Respect</li>
  <li>Humanity</li>
  <li>Ecological Awareness</li>
</ol>

---
class: text-2xl bg-gray-300 text-gray-600
---

<h1 style="font-size: 3rem">What's local first software?</h1>

<ol class="pl-6">
  <li>No spinners: your work at your fingertips</li>
  <li>Your work is not trapped on one device</li>
  <li>The network is optional</li>
  <li>Seamless collaboration with your colleagues</li>
  <li>The Long Now</li>
  <li>Security and privacy by default</li>
  <li>You retain ultimate ownership and control</li>
</ol>

---
class: text-2xl bg-gray-300 text-gray-600
---

<h1 style="font-size: 3rem">Why local first?</h1>

<ul class="pl-6">
  <li>Fast</li>
  <li>100% uptime</li>
  <li>Works offline</li>
  <li>Easy to deploy</li>
  <li>Built in security</li>
  <li>Scalable</li>
  <li>Actually serverless</li>
</ul>

---
class: text-center
layout: cover
---

<img src="/images/logo-cloud.svg" class="invert w-1/2 mx-auto" alt="Feathers Cloud" />

---
class: text-center
layout: cover
---

# Hi, I'm David

### I make open source things at
### [feathers.cloud](https://feathers.cloud) and [feathersjs.com](https://feathersjs.com)

<img src="/images/spacebird.svg" class="w-50 mx-a mt-4" alt="Space bird!" />

---
class: text-4xl
layout: cover
---

# What do we need to build a webapp?

<ul class="list-none">
  <li><img alt="Identity" src="/images/icons/security.svg" class="w-15 inline" /> Identity</li>
  <li><img alt="Database" src="/images/database.svg" class="w-15 inline" /> Database</li>
  <li><img alt="Storage" src="/images/storage.svg" class="w-15 inline" /> Storage</li>
  <li><img alt="Compute" src="/images/compute.svg" class="w-15 inline" /> Compute</li>
</ul>

---
class: text-4xl
layout: cover
---

# The browser is a _universal_ application platform

<img alt="Universal" src="/images/universal.svg" class="mx-a w-70" />

---
class: text-xl
---

<img alt="Feathers Cloud logo" class="invert w-1/2 mx-auto" src="/images/logo-cloud.svg" />

<h1 class="text-center my-5">Auth</h1>

Feathers Cloud Auth connects traditional passwordless login mechanisms like Email, Passkey, Social, SMS or MFA with decentralised identities to create local-first applications and serverless APIs with JavaScript and TypeScript.

- [feathers.cloud](https://feathers.cloud)
- [dwebchat.feathers.cloud](https://dwebchat.feathers.cloud/)
- [github.com/featherscloud/chat](https://github.com/featherscloud/chat)

---
layout: two-cols
---

# Decentralized Identifiers

DIDs are identifiers that represent a user-owned digital identity.

It is usually derived from the public key where the private key is stored securely on a device, browser or hardware key.

```ts
import { createClient } from '@featherscloud/auth'

const auth = createClient({
  appId: '<app-DID-here>'
})

// Get the unique DID for this device (browser)
console.log(await auth.getDeviceId())

'did:key:z6MkjTgqoet6Li8NbvpryRpcwW23yZdu6FAjuGDgTyNbePKa'
```

::right::

<img alt="Devices" src="/images/icons/devices.svg" />

---
class: text-2xl
layout: two-cols
---

# Links!

- [dwebchat.feathers.cloud](https://dwebchat.feathers.cloud/)
- [dwebyvr.org](https://dwebyvr.org/)
- [getdweb.net](https://getdweb.net/)
- [z-space.ca](https://z-space.ca/)
- [www.inkandswitch.com](https://www.inkandswitch.com/)
- [hypha.coop](https://hypha.coop/)
- [feathers.cloud](https://feathers.cloud)

::right::

<QRCode page="1" size="400" />
