## Changelog
----

## 54.1 (5.4.1)

### Fixes

- Fix the regression about icons not being replaced in tabs.
- Fix the regression about Java and Images icons getting the default icon instead of the PSI icons

## 54.0 (5.4.0)

### Features

- Refactor the project to use the `ProjectViewDecorators` instead of `FileIconProvider`, thus fixing the problems with plugins overriding icons provided by the plugin, as well as the icons not showing when using the Remote client.

### Additions:

- File Icons
  - Playwright
  - Gymfile, Matchfile, Pluginfile
  - Koka
- Folder Icons
  - fastlane

## 53.0 (5.3.0)

### Fixes

- Fix Kotlin PSI Icons not showing on the tabs
- Fix issue where adding associations would show up at the top of the list while scrolling down
- Fix issue where disabled associations would be enabled nonetheless
- Hollow Folders are now working in Rider!
- Folder Decorators and Custom Folder Icons are now working in Rider!

### Additions

- Many new UI Icons:
  - Resharper
  - Rider
  - Spring
  - Gateway
  - Space
  - Logos
- Files:
  - Qodana
  - Safari
  - JFormDesigner
  - nsriignore
  - retextignore
  - remarkignore
  - rehypeignore
  - boringignore
  - bazelignore
  - pubignore
  - Fitbit
  - Go-zero
  - Luau
  - Toit
  - Vanilla Extract
  - Changelog
  - CodeOwners
  - Bundle files in Java and Kotlin

### Other

- Reorganization of the whole project by modules: `common` and `Rider`
- Add linters
- Removed deprecated _Custom File Associations_ settings


## 52.0 (5.2.0)

### Additions

- Files: Add MobX and Mock
- Folders: Add objects

### Fixes

- Fix associations not being persisted

## 51.0 (5.1.0)

### Additions

- Add Preact association
- Add i18n language codes association (en.js, fr.yml, de.json...)
- More UI icons

### Fixes

- Remove the Binary File association to prevent the plugin to replace fallback icons with the binary file.

## 50.0 (5.0.0)

### Features

- New Settings page: **Associations Editor**. The Custom Associations page has been revamped with more features:
  - View all icon and folder associations from the settings page
  - Toggle, Add, Remove and Edit associations easily
  - Search by name and pattern
  - Tweak the associations priorities
  - Reset all custom associations at once
- Deprecation of the old _Custom Associations_ page. Please migrate your currently defined associations in the new page.

### Other

- More and more conversions to Kotlin
- Refactor xStream to use annotations
- Rename "_Custom Folder Color_" to "_Custom Themed Color_"

## 42.0 (4.4.0)

### Fixes

- add missing optional underscores for some folder associations
- fix composer, husky, maven folder icons
- change pm2 icon

### Additions

- _Files_:
  - coala, parcel, distignore
  - clio and stalebot
  - lolcode, nuxt, skript, textlint, grain
  - dockercompose, spectral, mdsvex
  - bundle.properties, mybatis
- *Folders*:
  - kotlin, java
  - perl, lua
  - input/output
  - connection, nuxt, quasar, scala, vuepress, article, base, cart, home, mobile, kivy, project
  - infra
  - stencil, scala, svelte, tech, terraform, venv

## 41.1 (4.3.1)

### Fixes

- Fix icons not showing because of duplicate attribute.

## 41.0 (4.3.0)

### Fixes

- Fix accent and tinted colors not being applied during theme switch
- First attempt on trying to fix the BaseConnection NPE

### Additions

- Gauge
- Go Template
- SemGrep
- NgRx Actions, Reducers, Selectors, State
- Coconut
- DenizenScript
- Fastlane
- Dune
- Forth
- FoxPro
- OPAM
- Percy
- SML
- Gleam
- Rust Folders
- Act
- ThunderClient
- Nest dto, schema, provider, strategy
- CAP
- Hasura config
- YueScript
- Eleventy
- dialogs, to, entities folder icons
- atoms, molecules, redux, organisms folder icons
- install.md files
- workflows/ci.yml github files
- png, jpg, gif, bmp, icon files
- funding
- artisan
- robots.txt
- pictures folder associations

## 40.0 (4.2.0)

### Features

- Add support for optional `.` and `_` prefix for folder icons
- Make all icons bigger with the _Bigger Icons_ setting
- Add action for _Bigger Icons_

### Fixes

- Fix Bigger Icons not being applied at start

### Other

- Convert more code to Kotlin
- Upgrade dependencies
- Add Urls to assocations (for the icon generator)

## 39.0 (4.1.0)

### Features

- Caught up with latest UI Icons, except <https://github.com/mallowigi/a-file-icon-idea/issues/212>

### Additions

- Caught up with **Atom File Icons** and **VSCode Icons** (non exhaustive list):
  - Tea
  - Telegram
  - Tex
  - Tfsignore
  - Table Of Contents
  - Template Toolkit
  - Subtitles
  - Terser
  - Thor
  - Tipe
  - Tla
  - Tmux
  - Truffle
  - TTCN
  - Twine
  - Txl
  - Typedoc
  - Typo3
  - Db2
  - Db3
  - Udf
  - SSH
  - Kdbx
  - Passwd
  - Sassrc
  - Kojo
  - Solidity
  - Cql
  - 4GL
  - Do
  - Ihlp
  - Sthlp
  - Mata
  - Matah
  - Stylelintignore
  - Nomad
  - Noon
  - Normalize
  - NSRI
  - Nu
  - Numpy
  - NXC
  - OpenOffice
  - OCaml
  - Finder
  - Oberon
  - Obj-J
  - Octave
  - Odin
  - Ooc
  - Opa
  - OpenCL
  - OpenGL
  - OpenPolicy
  - OpenScad
  - OpenVMS
  - OpenVPN
  - Org-mode
  - Oxygene
  - Oz
  - Progress
  - Sac
  - Sage
  - Sails
  - Saltstack
  - Sas
  - Scilab
  - Scilla
  - Scratch
  - Scrutinizer
  - Secret
  - Self
  - Sencha
  - Sentry
  - Serverless
  - ServiceFabric
  - Shadowcljs
  - Shen
  - Shipit
  - Shippable
  - Sigils
  - SketchMake
  - SketchUp
  - Skipper
  - Slash
  - SnapCraft
  - Snap.svg
  - Snort
  - Snyk
  - Solidarity
  - Sophia
  - Sorbet
  - Spacemacs
  - Sqf
  - Squarespace
  - Squirrel
  - Stan
  - Stdlib
  - Storyist
  - Stylable
  - StyledComponents
  - Stylish-haskell
  - Automator
  - Bitcoin
  - Bloc
  - Buildkite
  - Cnab
  - Cubit
  - Dub
  - Dvc
  - Macosx
  - Wine
  - ApiExtractor
  - Apollo
  - Binder
  - Bitcoin
  - BlitzBasic
  - Bors
  - Bosque
  - Calva
  - Casc
  - Codemeta
  - Commitizen
  - Dafny
  - TSS
  - JsonL
  - LdJSON
  - Deps
  - Pydeps
  - Cpc
  - Python Configs
  - Shell History
  - Son
  - Rdjson
  - Ston
  - Ejson
  - More Db Associations
  - Dependabot
  - Drawio
  - Dub
  - Fabfile
  - Fabric
  - Fauna
  - Figma
  - Fthtml
  - Gitpod
  - GoReleaser
  - Gql Codegen
  - Grapher
  - Hie
  - Arm
  - Avr
  - Bison
  - CkEditor
  - Hygen
  - Imgbot
  - Mixin
  - Photorec
  - Shellcheck
  - Windi.css
  - Jscpd
  - Kaitai
  - Kibo
  - Kusto
  - Lark
  - Latino
  - Lgtm
  - Lighthouse
  - Linqpad
  - Macaulay2
  - Mermaid
  - Metapost
  - Modernweb
  - Sourcemap
  - Neon
  - Nokogiri
  - Nwscript
  - Nx
  - Pytest
  - Readthedocs
  - Ftr
  - Omnigraffle
  - Ogone
  - Openexr
  - Openzfs
  - Rsync
  - Sandbox
  - Warcraft3
  - Winui
  - Wolfram
  - Qsharp
  - Xmake
  - Rescript
  - Stitches
  - Expo
  - Testcafe
  - Tilt
  - Ufo
  - Unicode
  - W3c
  - Yamllint
  - Yandex
  - Yvm
  - Vercel
  - Detekt
  - Al
  - Apex
  - Bats
  - Bicep
  - Cddl
  - Fork
  - AmigaOS
  - Codemirror
  - Cairo
  - Codeql
  - Confluence
  - Donejs
  - Dylan
  - Dal
  - Dojo
  - Dosbox
  - Drupal
  - Dustjs
  - Deno
  - Nest Land
  - E
  - Edge
  - Elastic
  - Fossil
  - Freedos
  - Fiddle
  - Freemat
  - Asar
  - Floobits
  - Freedesktop
  - Baboon
  - Tinymce
  - Gcode
  - Spray
  - Hosts
  - Hlsl
  - Hunspell
  - Hypr
  - Haxedevelop
  - Hugo
  - Icl
  - Informix
  - Janet
  - Zorinos
  - Xubuntu
  - Zquery
  - Webp
  - Wpml
  - Wxml
  - Wxs
  - Wxss
  - Vertex
  - Vmware
  - Volt
  - Vsix
  - Unlicense
  - Teal
  - Tera
  - Tox
  - Tuc
  - Sdlang
  - Slang
  - Slice
  - Spaceengine
  - Sparql
  - SSS
  - Reactos
  - Rehype
  - Remark
  - Retext
  - Rproj
  - Rust-toolchain
  - Pipeline
  - Pddl
  - Phpcs
  - Pipeline
  - Pkgsrc
  - Precision
  - Prometheus
  - Pytyped
  - Nodemon
  - Prisma
  - DragonFlyBSD
  - ElementaryOS
  - Manjaro
  - OpenBSD
  - Openhab
  - OpenIndiana
  - OpenSolaris
  - OpenStack
  - SmartOS
  - N64
  - Nearley
  - Nix
  - Stencil
  - Xliff
  - Svnignore
  - Magit
  - Manifest
  - Matlab
  - Mlang
  - Mojolicious
  - Mongo
  - Ms-dos
  - Mson
  - Libuv
  - License.bat
  - Kite
  - JSS
  - Jsp
  - JBuiler
  - Iodine
  - Jshintignore
  - Helix
  - Helixignore
  - Homeassistant
  - Horusec
  - Haxe Develop
  - Haxelib
  - Jekyll
  - Appsemble
  - Astro
  - Avif
  - Drools
  - Dvc
  - Glitter
  - Docz Config
  - Dojorc
  - Dox
  - Emakerfile
  - Flutter Lock
  - Flutter Pacakges
  - Angular Module
  - Angular Controller
  - Angular Container Ngrx
  - Angular Page Ionic
  - Angular App Routing
  - Angular Tailwind
  - Nest Adapter
  - Nest Controller
  - Nest Decorator
  - Nest Filter
  - Nest Gateway
  - Nest Interceptor
  - Nest Guard
  - Nest Middleware
  - Nest Service
  - Nest Pipe
  - Nest Module
  - Azure Pipelines
  - Blueprint
  - Cake
  - Composer,
  - GCloud
  - Haxelib
  - Husky
  - Mjml
  - Mongo
  - Next
  - Nuget
  - Platformio
  - Redis
  - Sso
  - Vs
  - Cmake
  - Dapr
  - Debian
  - Elastic
  - Electron
  - Abc
  - Astyle

## 38.0 (4.0.0)

### Features

- New Setting: **Bigger Icons**
- Support for **Sync Settings** plugin. Now you can finally sync your settings between IDEs

### Additions

- Added many many more **UI Icons**:
  - Big Data Tools
  - UI Designer
  - Package Search
  - ColdFusion
  - Resharper/Rider
  - Ruby
  - Rust
  - Tailwind
  - Space
  - Swagger
  - Swift
  - Lombok
  - JavaEE
  - CodeWithMe
  - Chooser
  - Thumbnail Viewer
  - JetBrains Logos
  - Project Analysis
- New _file icons_:
  - CoffeelintIgnore
  - Csslint
  - htmlhint
  - jsbeautify
  - jscs
  - jshint
  - pythonconfig
  - yard
  - nant
  - nasm
  - ndepend
  - neko
  - neo4j
  - nessus
  - netlinx
  - netlogo
  - newrelic
  - nextflow
  - nextjs
  - nickle
  - nightwatch
  - nimble
  - nimrod
  - nit
  - nmap
  - nodemonignore
  - ninja
- New _folder icons_:
  - cypress

### Fixes

- Fix the fatal error when triggering the actions from the "Tools" menu

### Other

- Migrate to gradle.kts
- Rewrite changelog to suit the changelog standard (<https://keepachangelog.com/en/1.0.0/>)

## 37.0 (3.12.2)

### Other

- Support for 2021.2
- Java version update to 11
- Verification automated workflow with Github Actions
- Fix selected checkbox size

## 36.0 (3.12.1)

### Other

- Support for 2021.1

## 35.0 (3.12.0)

### Additions

- New **file icons**:
  - genstat
  - gentoo
  - gimp
  - gitcommit
  - gitmerge
  - glade
  - glide
  - gltf
  - gnome
  - golo
  - gauss
  - grammatical framework
  - glyphs
  - gn
  - gnuplot
  - gosu
  - gravit
  - greenkeeper
  - pointwise
  - snowpack

### Fixes

- Fix bundle size
- Fix bad associations

## 34.0 (3.11.0)

### Additions

- New **file icons**:
  - mapbox
  - markdownlint
  - materialize
  - mathjax
  - max
  - mdx
  - mediawiki
  - mercury
  - nano
  - nanoc
  - MS infopath
  - lync
  - visio
  - publisher
  - outlook
  - project
  - meson
  - metal
  - minecraft
  - minizinc
  - mirah
  - mirc
  - mkdocs
  - modelica
  - modernizr
  - modo
  - moho
  - modula2
  - modula3
  - moleculer
  - moment
  - monkey
  - reasonstudios
  - rebol
  - red2
  - redhat
  - reek
  - rneovate
  - requirejs
  - rexx
  - rhino3d
  - riemann
  - ring
  - riot2
  - robot2
  - rss
  - rstudio

## 33.0 (3.10.0)

### Fixes

- fix `init.py`

### Additions

- New **file icons**:
  - eclipselang
  - eagle
  - easybuild
  - ec
  - ecere
  - electron
  - email
  - emberscript
  - eq
  - esdoc
  - extjs

## 32.0 (3.9.0)

### Features

- Add the ability to disable associations

### Additions

- New **folder associations**:
  - ios
  - iosApp
  - androidApp
  - backend
  - desktop
  - buildSrc
  - repository
  - exception
  - usecase
- Add django associations and `eslintignore`

### Fixes

- Fix the bug with Edit/Clone associations

## 31.0 (3.8.0)

### Fixes

- Remove dependency to the Material Theme and add Javassist to fix the IconLoader issue.
- Fix possible NPE
- Recolored some icons

### Additions

- New **file icons**:
  - UIKit
  - Unibeautify
  - Uno
  - Urweb
  - Paket
  - Pan
  - Papyrus
  - Parrot
  - Pascal
  - Patreon
  - Pawn
  - PCD
  - Pegjs
  - Phoenix
  - Oracle
  - Phrase
  - Pickle
  - Pico8
  - Picolisp
  - Pike
  - Pinescript
  - Platform.IO
  - PM2
  - Pod
  - PgSQL
  - PogoScript
  - Pony
  - Povray
  - Powwerbuilder
  - Precommit
  - Propellet
  - PROS
  - Proselint
  - Pullapprove
  - Pure
  - PHP2
  - LabView
  - Lasso
  - Leaflet
  - Lean
  - Lefthook
  - Leiningen
  - Lekto
  - Lex
  - LFE
  - Lightwave
  - Lilypond
  - Link
  - Lime
  - Lisp
  - LLVM
  - LogTalk
  - Lolcode
  - LSL
  - Lua
  - Livescript
  - alexignore
  - boringignore
  - D3
  - darcsignore
  - darcs
  - deps
  - dockerignore
  - fossaignore
  - gitignore
  - helmignore
  - herokuignore
  - dashboard
  - dataweave
  - dbase
  - debian
  - devcontainer
  - devicetree
  - dhall
  - Dia
  - Digdag
  - DNS
  - Docbook
  - Doclets
  - Docpad
  - Docz
  - Dogescript
  - Dojo
  - Dosbox
  - Doxygen
  - Dragula
  - Drone
  - Dyalog
- Add `index.scss`, `index.css` and `index.html` to the index family
- Add more associations to markdown, manpage, manifest, maya, mercurial, mjml, mustache

## 30.0 (3.7.0)

### Additions

- New icons and folder associations: `public_html`, redis db
- New **UI Icons**: Checkboxes, Inlay icons, CodeWithMe, Emoji Picker, Tool Window Analyze...

### Fixes

- Pseudo-fix: Add leading slash relatively to new EAP refactor

## 29.0 (3.6.0)

### Additions

- Add new **UI icon sets**:
  - Spring
  - Kubernetes
  - Slim
  - Swagger
  - Sass
  - Swift
  - Rider
  - PostCSS
  - XSLT
- New **file icons**:
  - ngrx
  - RxJs
  - Protobuf
  - R
  - Swagger
  - Tapestry
- **New associations**:
  - command
  - console folders
  - public_html
  - entities
  - effects
  - stylelintrc

### Features

- Feature: **Hide Folders**
- Feature: Show Custom and Default file icons in the Commit Window and Panel
- Add more UI Icons

### Fixes

- Fix: regression issue with UI icons not disabling
- Fix: popup menus: restore active indicator

## 28.0 (3.5.1)

### Other

- Support for 2020.3
- Support for more UI icons

## 27.0 (3.5.0)

### Features

- Add new action: **Refresh Icons**. This will manually refresh all icons and reload the panes.
  - This should fix bugs such as <https://github.com/mallowigi/a-file-icon-idea/issues/93>
    and <https://github.com/mallowigi/a-file-icon-idea/issues/79>
- Reorganized icons: now icons belonging to the *Files* category and *PSI* category are separate from the rest of icons.
  As a result, toggling *UI Icons* should not affect *File Icons* and *PSI Icons* and vice-versa.
- Add icons to the **Atom Material Settings Toolbar Menu**.
- Add actions for switching between **Arrow Styles**

## 26.0 (3.4.0)

### Features

- New Option: "**Folder Color**" to customize Folder Colors from the current theme.
- Better detection of the current theme's accent color
- Add Checkboxes to **Accent Color** and **Folder Color** to allow customizing such colors instead of picking them from
  the theme

### Additions

- New **file icons**:
  - brew
  - harbour
  - holyc
  - hjson
  - hoplon
  - houndci
  - hp
  - hy
  - hyper, question

### Fixes

- Improve Hollow Folders opened files detection
- Put _Custom file associations_ under the "Atom File Icon Settings"

## 25.3 (3.3.3)

### Fixes

- Fixes many issues with custom associations

## 25.2 (3.3.2)

### Other

- Support for 2020.2 EAP

## 25.1 (3.3.1)

### Fixes

- Fix Psi Icons for PHP files

## 25.0 (3.3.0)

### Features

- The finally awaited **Custom Icon Associations** is here! This is an alpha version so it can contain bugs :)
  - Assign custom file associations and folder associations from the Settings
  - Preview Default File and Folder Associations from the Settings
  - Assign icons from your file system
  - **Important note**: most of the settings won't be applied to custom icons, so use them sparingly!

### Additions

- **New folder associations**:
  - widgets
  - elements
  - users
  - members
  - partners
  - friends
  - projects
  - ui
  - dev
  - staging
  - qa
  - prod
  - serializers
  - types
  - io
  - stdlib
  - deps
- **New file associations**:
  - `*_test.go`
  - `*_spec.go`
  - `Chart.yaml`
  - `values.yaml`
  - `helmfile.yaml`
  - scala test files
- Added `jsconfig` and `tsconfig`

### Fixes

- Fix issue with monospace colors not being persisted
- Changed color scheme of Kotlin PSI Icons, to differentiate with Java PSI Icons
- Now the _PSI Icons setting_ is dependent on the _UI Icons setting_, as this wouldn't work without it.
- And the _Hollow Folders Setting_ is dependent on the _Folder Decorations Setting_ as well.

### Other

- The project has been revamped to Kotlin! This is a huge step so please report any issues you can find :)

## 24.0 (3.2.0)

### Features

- Added accent color selection in the settings

### Additions

- new **UI/PSI icons**: `Scala, Ruby, Typescript`
- new _redux_ icons: `redux saga` and `redux epics`, tweaked other colors too
- new _test_ icons: ``test dart`, `test go`, `test haskell`, `test perl`, `test rust`
- switched typescript and tslint icons
- new **file icons**:
  - icomoon
  - idl
  - igor
  - imba
  - index
  - inform
  - ink
  - inkscape
  - inno
  - ioke
  - isabelle
  - jake
  - jasmine
  - jison
  - jolie
  - json5
  - jsonld
  - jsonnet
  - junos
- new/updated **folder icons**:
  - acre
  - agda
  - alacritty
  - app
  - appstore
  - arttext
  - atom
  - aurelia
  - bazaar
  - cabal
  - chef
  - client
  - cluster
  - container
  - content
  - controllers
  - coverage
  - cvs
  - messages,
  - viewmodel
  - deno
  - dependabot
  - devcontainer
  - dropbox
  - gitlab
  - istanbul
  - yarn
  - ruby
  - mercurial
  - meteor
  - svn
  - textmate
  - vagrant
  - vim
  - svg
  - firebase
  - xcassets
  - glyph

### Fixes

- Try to fix the weird border at start
- Fix wrong associations

## 23.0 (3.1.0)

### Additions

- **File icons**:
  - walt
  - watchman
  - wdl
  - webgl
  - owl
  - webvtt
  - wenyan
  - wget
  - wix
  - wordpress
  - workbox
  - wurst
  - x10
  - x11
  - xmos
  - xojo
  - xpages
  - xproc
  - xtend
  - yara
  - yorick
  - yui
  - yasm
  - zbrush
  - zeit
  - zenscript
  - zig
  - zilog
  - zimpl
  - zork
  - awk
  - bazaar
  - brewfile
  - hitachi
  - intel
  - vax
  - kerboscript
  - keybase
  - keynote
  - kicad
  - kitchenci
  - kml
  - knime
  - kotlin
  - knockout
  - krl
  - kubernetes
  - q
  - qasm
  - qlikview
  - qt
  - quasar
- New angular icon: `interceptor`
- New redux icons: `saga` and `selector`
- New pattern: `main.js` is now associated with nodejs
- Add `cron/scheduler` folder icons

## 22.0 (3.0.0)

### Other

- You can now preview icons at <https://github.com/mallowigi/a-file-icon-idea> !
- You can now get the list of available associations at <http://www.material-theme.com/docs/reference/associations/>
  and <http://www.material-theme.com/docs/reference/folder_associations/> !
- Extracted icons to its own repository so it can be used with multiple projects
- Optimized icons (reduce icons size, set colors in paths, etc)
  - Also the icons look much more like the Atom original plugin ones
- Added fileNames in associations, to be used with the examples generator
- Added colors in associations, for use with the font generator
- Update UI Icons with latest icons

### Additions

- **New/Updated UI Icons**:
  - Ant
  - Haml
  - Handlebars
  - DataGrip
  - JavaScript
  - Kotlin
  - DevKit
  - Dart
  - Docker
- **New icons**:
  - 4d
  - agda
  - alpine linux
  - analytica
  - adobe animate
  - ansible
  - antwar
  - aplus
  - buck
  - build boot
  - caddy
  - caffe
  - caffe2
  - cakefile
  - carthage
  - chai
  - chapel
  - chartjs
  - cheetah
  - chocolatey
  - cpp
  - csharp
  - cdf
  - chrome
  - chuck
  - circuit
  - cirru
  - clarion
  - clean
  - click
  - clips
  - closuretpl
  - cloudfoundry
  - cocoapods
  - codacy
  - codeclimate
  - cokekit
  - codeship
  - conan
  - conda
  - conll
  - coq
  - corel
  - coveralls
  - cp
  - cpan
  - credits
  - creole
  - crowdin
  - csound
  - cuneiform
  - curl
  - curry
  - cwl
  - collada
  - nvidia
  - fabric
  - factor
  - falcon
  - fancy
  - fantom
  - fexl
  - fbx
  - faust
  - fasta
  - finaldraft
  - firebase bolt
  - firefox
  - flask
  - flutter
  - flux
  - font bitmap
  - fontforge
  - fossa
  - fountain
  - fanca
  - frege
  - fuel ux
  - fusebox
  - futhark
  - JetBrains Theme Files
- *Update icon associations*:
  - actionscript
  - ansible
  - antlr
  - applescript
  - asciidoc
  - asm
  - atom
  - atoum
  - babel
  - backbone
  - behat
  - bison
  - bootstrap
  - bower
  - cabal
  - c
  - composer.lock
  - chef
  - credits
  - csharp
  - cypress
  - todo
  - finder
  - firebase
  - flash
  - fortran
  - gem
  - archives
  - audio
  - video

## 21.0 (2.10.1)

### Features

- Add new 2020.1 UI Icons

### Additions

- New **folder associations**: bin and units

### Fixes

- Fix issue with _Arrow Colors_ being black in Darcula
- Fix issue with _Plugins_ labels being black in Darcula

## 20.0 (2.10.0)

### Features

- Restore the **Accent Color** function to colorize icons with the Accent color (defined from Material Theme, or from
  the current active tab indicator color)

### Additions

- Add `bz2`, `xar`, `egg` and `sit` to "Archive" file association
- Add `sql/mysql/pgsql` folder

### Fixes

- Fix issue where arrows style were not persisted
- Fix Kotlin icons being unaffected by PSI File Icons setting
- Make Icon Settings "dumb aware" (not affected by the indexing process)

## 19.0 (2.9.0)

### Features

- New feature: **Arrows Style**
- New pattern: `angular controller`

### Fixes

- Fix issue with icons not being applied on start

### Other

- Add missing icons since Nov 2019

## 18.0 (2.8.1)

### Other

- Support for 2020.1

## 17.0 (2.8.0)

### Additions

- New **File Icons**:
  - 1c
  - 3dmodel
  - 3dsmax
  - abap
  - abif
  - acre
  - advpl
  - affectscript
  - affinity
  - alacritty
  - alex
  - alloy
  - ampl
  - amusewiki
  - angelscript
  - animestudio
  - ant
  - apache
  - apl
  - appcelerator
  - arc
  - archlinux
  - asymptote
  - atoum
  - ats
  - audacity
  - augeas
  - avro
  - backbone
  - bnf
  - bem
  - bibtext
  - biml
  - bintray
  - blender
  - bluespec
  - boo
  - bootstrap
  - brakeman
  - broccoli
  - brotli
  - browsersync
  - brunch
  - byond
  - gnu

### Features

- New Feature: **Hide File Icons**
- New Feature: **Hollow Directories**

## 16.0 (2.7.0)

### Additions

- New **file icons**:
  - Cargo
  - Codecov
  - codeowners
  - cypress
  - cython
  - gridsome
  - netlify
  - pnpm
  - posthtml
  - sapper
  - svelte-config
  - uml
  - v
  - vala
- New **folder icons**:
  - events
  - gulp
  - json
  - netlify
  - relay

### Other

- Sync with new UI Icons

## 15.0 (2.6.1)

### Other

- Support for 2019.3 EAP

## 14.0 (2.6.0)

### Additions

- New **File Icons**:
  - edge
  - autoit
  - azure
  - bithound
  - blink
  - bucklescript
  - buildkite
  - certificate
  - commitlint
  - credits
  - history
  - graphcoo
  - hel
  - istanbu
  - ke
  - kiv
  - li
  - livescrip
  - markoj
  - md
  - merli
  - min
  - moonscrip
  - mxm
  - nest
  - houdini
  - no
  - nunjuck
  - prism
  - processin
  - restq
  - sa
  - sequeliz
  - sw
  - unit
  - velocit
  - v
  - webassembl
  - webhin
  - wep
  - yang
- New **Folder Icons**:
  - ci
  - class
  - container
  - content
  - css
  - delta
  - dump
  - error
  - examples
  - flow
  - helper
  - modals
  - maps
  - pipe
  - prisma
  - private
  - stack
  - utils
  - vm

### Other

- Sync with Material Icons

## 13.0 (2.5.0)

### Additions

- New Icons and associations

### Other

- Sync with Material Icons

## 12.0 (2.4.0)

### Other

- Support for 2019.2
- Sync with Material Icons

## 11.0 (2.3.0)

### Features

- Add light equivalents of icons
- Update new icons: Resharper (Rider)
- Sync with Material Icons

### Fixes

- Fix errors

## 10.0 (2.2.0)

### Features

- New setting: **PSI Icons**. Replaces icons about program structure: classes, interfaces, methods, enums etc.
- Import last set of UI Icons from the Material Theme

### Other

- Update for 2019.1

## 9.0 (2.1.0)

### Features

- Add Monochrome Icons' tint color selection

### Additions

- New **folder icons**:
  - guard
  - providers
  - animations
  - grunt
  - icons
  - e2e
  - custom
  - rules
  - screens
  - storybook
  - stylus
  - syntax
  - security
  - meta-inf
  - fixtures
  - channels
  - concerns
  - support
  - features
  - fabricators
  - nyc
  - reviews
- New **file icons**:
  - ANTLR
  - brainfuck
  - cobol
  - delphi
  - eiffel
  - fortran
  - idris
  - io
  - j
  - lerna
  - postscript
  - prolog
  - racket
  - red
  - supercollider
  - scheme
  - terraform
  - test-react
  - turing
  - toml

### Fixes

- Fix UI Icons setting needing the IDE to be restarted
- Fix settings not being persisted
- Add more contrast to monochrome icons
- Fix some directories icons' contrast between the directory and the icon

## 8.0 (2.0.0)

### Features

- Atom File Icons has now the complete UI Icons feature, allowing you to replace IntelliJ icons with Material Icons
- New Option: **Monochrome Icons**

## 7.0 (1.6.1)

### Fixes

- Fix fatal error

## 6.0 (1.6.0)

### Additions

- New **file icons**:
  - Jenkins
  - Rspec
  - Rubocop
- New **folder icons**:
  - android
  - deploy
  - api
  - archives
  - config
  - constants
  - core
  - download
  - env
  - exclude
  - functions
  - generated
  - hooks
  - ios
  - include
  - jinja
  - job
  - keys
  - layouts
  - mailers
  - meta
  - middleware
  - notification
  - other
  - packages
  - posts
  - react
  - resourceIOS
  - routes
  - scripts
  - server
  - serverless
  - shared
  - sublime
  - tasks
  - themes
  - utils
  - upload
  - vendors
  - views
  - vue

## 5.0 (1.5.0)

### Additions

- New **file icons**:
  - Arduino
  - Assembly
  - Authors
  - Ballerina
  - Crystal
  - CSSMap
  - Dotjs
  - DTS
  - Favicon
  - Firebase
  - Flash
  - Gatsby
  - Gemfile
  - Po
  - JSMap
  - MJML
  - Nimble
  - Raml
  - Razor
  - Redux Actions/Stores/Reducers
  - Smarty
  - Solidity
  - Sonar
  - Stencil
  - Storybook
  - Wallaby
- New **folder icons**:
  - benchmarks
  - coverage
  - controllers
  - debug
  - excluded
  - expo
  - jinja
  - less
  - maven
  - messages
  - models
  - plugin
  - python
  - react
  - redux
  - routes
  - scripts
  - sublime
  - sync
  - tasks

## 4.0 (1.4.0)

### Other

- Convert icons to SVG
- Add more system UI icons

## 3.0 (1.3.0)

### Features

- Add **settings page** to control which components to enable or disable.
  - Components: **File Icons**, **Directory Icons** and **UI Icons** (experimental)

## 2.0 (1.2.0)

### Features

- Add **folder icons** feature
- Add more UI icons

## 1.2 (1.1.0)

### Features

- Add PHPStorm and PyCharm files and plugin support
- Add "nodes" icons for various file trees

### Additions

- New icons
  - Github Code of conduct, Github Contributing, Commit message convention, Github Template
  - README
  - Prefs
  - Atom files
  - Angular component, service, directive, guard, pipe, routing, resolver
  - Autohotkey
  - API Blueprint
  - Appveyor
  - Java Beans
  - Browserslist
  - Cabal
  - CNAME
  - Compass files
  - C++
  - Dockerignore
  - Doxygen
  - Dylib
  - Eslintignore
  - MAC OSX files
  - Flow Config
  - Ghostscript
  - Godot
  - Gradlew
  - H files
  - Adobe Indesign
  - Jekyll config.yml
  - jQuery
  - Makefile
  - Markdown
  - Manpage
  - Mathematica
  - Maven pom.xml
  - Maya
  - Mocha
  - Nib
  - NPM package.lock
  - NVM
  - OpenOffice
  - Objective C
  - Patch files
  - Phalcon
  - PostCSS Config
  - Prettier
  - Powershell
  - ReasonML
  - Restructured
  - Robot
  - RVM
  - Spring
  - Tern
  - Tomcat
  - Travis
  - VHDL
  - Webpack
  - XCode
  - Yarn files
  - Minified javascripts

### Fixes

- make it DumbAware

### Other

- Add markdown to html for changelog
- add gradle.properties for easy installing

## 1.0 (1.0.0)

### Other

- First commit, migrated from the Material Theme UI
