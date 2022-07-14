<p align="center">
  <a href="#">
    
  </a>
  <p align="center">
   <img width="150" height="150" src="" alt="Logo">
  </p>
  <h1 align="center"><b>Mirage Experience</b></h1>
  <p align="center">
  The new era of user experience and integrations
    <br />
    <a href=""><strong>mirageexperience »</strong></a>
    <br />
    <br />
    <b>Download for </b>
    macOS
    ·
    Windows
    ·
    Linux
    ·
    iOS
    ·
    Android
    <br />
    <i>~ Links will be added once a release is available. ~</i>
  </p>
</p>
Mirage is the first open source platform focused on the experience when consuming online courses in the world of digital marketing. (<a href="#what-is-a-vdfs">VDFS</a>) written in React. 
<br/>
<br/>

> NOTE: Mirage Experience is under active development, most of the listed features are still experimental and subject to change.

Deliver your content in an amazing way and provide the experience of a great platform.

For digital product creators who want to deliver a unique, personalized experience like no other.

## Monorepo structure:

### Apps:

- `mobile`: A [React Native](https://reactnative.dev/) app.
- `web`: A [React](https://reactjs.org) webapp.
- `landing`: A [React](https://reactjs.org) app using Vite SSR & Vite pages.

### Core:

- `core`: The [Rust](#) core, referred to internally as `sdcore`. Contains filesystem, database and networking logic. Can be deployed in a variety of host applications.

### Packages:

- `client`: A [TypeScript](#) client library to handle dataflow via RPC between UI and the Rust core.
- `ui`: A [React](<[#](https://reactjs.org)>) Shared component library.
- `interface`: The complete user interface in React (used by apps `desktop`, `web` and `landing`)
- `config`: `eslint` configurations (includes `eslint-config-next`, `eslint-config-prettier` and all `tsconfig.json` configs used throughout the monorepo.
- `macos`: A [Swift](#) Native binary for MacOS system extensions.
- `ios`: A [Swift](#) Native binary (planned).
- `windows`: A [C#](#) Native binary (planned).
- `android`: A [Kotlin](#) Native binary (planned).

