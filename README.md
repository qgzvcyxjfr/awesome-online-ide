<img width="128" height="128" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/codeschool.svg" align="right">

# Awesome Online IDE [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome online implementations of Integrated Development Environments (IDE)

An ([IDE](https://en.wikipedia.org/wiki/Integrated_development_environment)) is a software application that provides comprehensive facilities to computer programmers for software development. This typically includes a text editor, syntax highlighting, file explorer, debugger, version control, and build/run/deploy options. Another defining feature of an IDE is some form of intelligent code completion, sometimes called [intellisense](https://en.wikipedia.org/wiki/Intelligent_code_completion).
 
 An "Online IDE" has the features mentioned above but runs in a web browser instead of installing as a native application. An "Online IDE" can be made accessible in offline mode without an internet connection and still satisfy the above conditions.

## Contents

### Jump to

- [Full IDE](#full-ide)
- [Snippets](#snippets)
- [Web Snippets](#web-snippets)

### Legend

| Icon                                                                                                                | Meaning                                            |
| ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| <img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />       | Open source or source code available               |
| <img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />       | Docker image or other self-hosted option available |
| <img title="Sign Up Required" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/shopify.svg" /> | Sign-up required before usage                      |


## Full IDE

- [AWS Cloud9](https://aws.amazon.com/cloud9) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/c9/core) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/cloud9/workspace/) <img title="Sign Up Required" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/shopify.svg" /> - Run any language on a full VM complete with a terminal built on [Ace Editor](https://ace.c9.io)  [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/ajaxorg/ace).
- [CodeEnvy](https://codenvy.io) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/codenvy/codenvy) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/codenvy/codenvy) <img title="Sign Up Required" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/shopify.svg" /> - Run any language on a full VM complete with [Eclipse Che](https://www.eclipse.org/che/) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/eclipse/che) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/eclipse/che/).
- [CodeSandbox](https://codesandbox.io) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/CompuIves/codesandbox-client) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/codesandbox/client/) - Run JavaScript with starting templates for React, Vue, Angular, Preact and more with full intellisense, lint error checking and live collaborative editing.
- [Theia IDE](https://theia-ide.org) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/eclipse-theia/theia) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://github.com/eclipse-theia/theia-ide?tab=readme-ov-file#docker) - Run any language, supports VS Code Extensions, integrates flexible AI Support, based on the [Theia Platform](https://theia-ide.org/theia-platform/), integrates the [Monaco Editor](https://microsoft.github.io/monaco-editor/) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/Microsoft/monaco-editor).
- [Gitpod](https://gitpod.io) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/gitpod-io/gitpod) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://www.gitpod.io/self-hosted) <img title="Sign Up Required" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/shopify.svg" /> - Run any language on a full Linux VM complete with terminals, GitHub and Git integration, content assist, go-to-definition, linting, live collaboration, custom Docker workspaces, and integrated code review support.
- [Atheos](https://atheos.io) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/Atheos/Atheos) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/hlsiira/atheos) - Run most languages using a PHP/Browser based IDE with a terminal, git integration, and syntax highlighting.
- [Dockside](https://dockside.io) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/newsnowlabs/dockside) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/newsnowlabs/dockside) - Self host parallel access-controlled development containers complete with the Theia IDE and terminal, for developing in any language and multiple architectures, within choice of Docker runtimes; stage running code publicly or securely on own domains over HTTPS.

## Snippets

- [Glot](https://glot.io) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/prasmussen/glot-www) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/javierprovecho/glot-www/) - Run snippets from over 30 languages as docker containers including C#, Kotlin, Julia, Go, and Ruby.
- [Try It Online](https://tio.run) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/TryItOnline/tryitonline) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/tryitonline/tryitoffline/) - Run snippets from over 300 languages including esoteric code-golf languages.
- [Kotlin-Playgrounds](https://play.kotlinlang.org) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/JetBrains/kotlin-playground) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://github.com/JetBrains/kotlin-playground#installation) - Run Kotlin snippets with auto-completion, type checking and automatically translate Java to Kotlin code.

### Web Snippets

- [JS Bin](https://jsbin.com) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/jsbin/jsbin) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://hub.docker.com/r/euprogramador/jsbin/) - Run snippets in HTML/CSS/JS/TS, provides [Codecasting](https://remysharp.com/2013/11/14/what-is-codecasting/).
- [LiveCodes](https://livecodes.io) [<img title="Open Source" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/github.svg" />](https://github.com/live-codes/livecodes) [<img title="Self Hosted" width="16" src="https://cdn.jsdelivr.net/npm/simple-icons@1.2.7/icons/docker.svg" />](https://livecodes.io/docs/features/self-hosting) - Run snippets in 90+ languages/frameworks, including React, Vue, Svelte, Solid, Typescript, Python, Go, Ruby, PHP and many more. Runs client-side with no backend. Projects can be shared, exported, deployed and embedded. Free AI code assistant.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) and [code of conduct](code-of-conduct.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, styfle has waived all copyright and related or neighboring rights to this work.
