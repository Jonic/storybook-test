~/Code/storybook-test   main ✚  npx sb@next repro
╭──────────────────────────────────────────────────────────────────────────────╮
│                                                                              │
│   🤗 Welcome to sb repro! 🤗                                                 │
│                                                                              │
│   Create a new project to minimally reproduce Storybook issues.              │
│                                                                              │
│   1. select an environment that most closely matches your project setup.     │
│   2. select a location for the reproduction, outside of your project.        │
│                                                                              │
│   After the reproduction is ready, we'll guide you through the next steps.   │
│                                                                              │
╰──────────────────────────────────────────────────────────────────────────────╯
✔ 🌈 Select the repro framework › html
✔ 📝 Select the repro base template › html
✔ Enter the output directory … repro-output
🏃 Running html into /Users/jonic/Code/storybook-test/repro-output

🏃 Starting for html latest

{
  name: 'html',
  version: 'latest',
  appName: 'repro-output',
  creationPath: '/Users/jonic/Code/storybook-test',
  cwd: '/Users/jonic/Code/storybook-test/repro-output',
  e2e: false,
  pnp: false,
  framework: 'html',
  generator: 'mkdir {{appName}} && cd {{appName}} && touch yarn.lock && yarn init --yes',
  autoDetect: false
}

🏗 Bootstrapping html project (this might take a few minutes)
mkdir repro-output && cd repro-output && touch yarn.lock && yarn init --yes

🧶 Installing Yarn 2
yarn set version berry && yarn config set enableGlobalCache true && yarn config set nodeLinker node-modules

rm: no such file or directory: /Users/jonic/Code/storybook-test/repro-output/package-lock.json
🌍 Adding needed deps & installing all deps
yarn install
An error occurred while executing: `yarn install`
Command output was:
Usage Error: The nearest package directory (/Users/jonic/Code/storybook-test/repro-output) doesn't seem to be part of the project declared in /Users/jonic/Code/storybook-test.

- If the project directory is right, it might be that you forgot to list repro-output as a workspace.
- If it isn't, it's likely because you have a yarn.lock or package.json file there, confusing the project root detection.

$ yarn install [--json] [--immutable] [--immutable-cache] [--check-cache] [--inline-builds] [--skip-builds]


🚨 Dependencies installation failed
🚨 Failed to create repro
