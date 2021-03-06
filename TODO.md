## Roadmap: Summer of Cosmos

- [React Native integration](#react-native-integration)
- [Pluggable UI](#pluggable-ui)
- Explore: JSX fixtures
- UI control panel
- Redesign docs
- Create high-level examples (eg. Next.js, CRA, Gatsby)

## Pluggable UI

- [ ] Design plugin API

## React Native integration

- [x] RN server
  - [x] Extract non-webpack core from react-cosmos/server
  - [x] Create RN server cmd
  - [x] Create sockets server (forwarding messages between clients)
  - [x] Generate user modules file
  - [x] Update cosmos.modules file on fixture file changes
  - [x] Add loaderOpts to cosmos.modules
  - [ ] Onboarding
    - [ ] Generate Cosmos config
    - [ ] Add `cosmos.modules` to gitignore
    - [ ] Create new App file that forks between App.main and App.cosmos
    - [ ] Add package.json script
- [x] RN UI
  - [x] Add support for websocket communication (choose between sockets or postMessage)
  - [x] Ask loader for fixtures on load
  - [x] Create RN-specific onboarding screens
  - [ ] Test socket transport
  - [ ] Log using `debug` on the client
- [x] RN loader
  - [x] Extract non ReactDOM-specific core from react-cosmos-loader
  - [x] Create RN loader
  - [x] Test socket transport
  - [ ] Check if existing proxies are compatible
  - [x] Check if testing API is compatible
- [x] Create React Native App example
- [x] Add (experimental) README section
