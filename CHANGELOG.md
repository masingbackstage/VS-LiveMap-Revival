# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Features
- Run fullrender on colormap received ([143f26e](../../commit/143f26e))

### Fixes
- Use kebab case where appropriate ([49b445e](../../commit/49b445e))
- Don't throw exceptions when stopping ([143f26e](../../commit/143f26e))
- Resolve critical bugs and refactor magic numbers ([1f313d5](../../commit/1f313d5)) #37

### Performance
- Comprehensive performance optimizations ([a82c73b](../../commit/a82c73b)) #38

## [0.1.7] - 2026-01-02

### Features
- Better translation support ([c40fb92](../../commit/c40fb92)) #35

### Fixes
- Attempt to improve color accuracy ([29c260c](../../commit/29c260c)) #36
- Added using statement to SqliteCommand in ChunkLoader ([d7f1508](../../commit/d7f1508)) #34

### Chores
- Run ReSharper ([69af792](../../commit/69af792))
- Pre-emptive 0.1.6 bump ([a54daa6](../../commit/a54daa6))

## [0.1.6] - 2026-01-02

### Features
- Add renderer buttons ([a5e8f5c](../../commit/a5e8f5c)) #33
- Add code quality checks ([a426e66](../../commit/a426e66)) #32

### Fixes
- Chunk colormap on send ([f6530e8](../../commit/f6530e8)) #31
- Materialize map positions to avoid repeated DB queries ([4b16f7d](../../commit/4b16f7d)) #29

### Chores
- Pre-emptively bump version ([3a0f3cf](../../commit/3a0f3cf))

## [0.1.5] - 2026-01-02

### Features
- Add renderer buttons ([a5e8f5c](../../commit/a5e8f5c)) #33

### Chores
- Pre-emptive 0.1.6 bump ([a54daa6](../../commit/a54daa6))

## [0.1.4] - 2026-01-02

### Features
- Add code quality checks ([a426e66](../../commit/a426e66)) #32

### Fixes
- Chunk colormap on send ([f6530e8](../../commit/f6530e8)) #31
- Materialize map positions to avoid repeated DB queries ([4b16f7d](../../commit/4b16f7d)) #29

### Chores
- Pre-emptively bump version ([3a0f3cf](../../commit/3a0f3cf))

## [0.1.3] - 2026-01-01

### Fixes
- Queueing chunks up on load ([3c11d36](../../commit/3c11d36)) #28

## [0.1.2] - 2026-01-01

### Features
- Boilerplate test framework ([9813f3c](../../commit/9813f3c)) #25

### Fixes
- Update links ([f821477](../../commit/f821477)) #27

## [0.1.1] - 2026-01-01

### Refactor
- Swap to genHTTP ([a792160](../../commit/a792160)) #23

### Chores
- Add eslint ([924e916](../../commit/924e916)) #22
- Add code review reports ([61685f6](../../commit/61685f6))

## [0.1.0] - 2025-12-31

### Features
- Initial release of VS-LiveMap-Revival

### Fixes
- Tile rendering ([b8e8626](../../commit/b8e8626))
- Return sidebar ([0a2b56c](../../commit/0a2b56c))
- Download link ([8cd87fe](../../commit/8cd87fe))

### Chores
- Add more gitignores ([5582a95](../../commit/5582a95))
- Get running webserver ([7eb9311](../../commit/7eb9311))
- Update readme ([72d10b4](../../commit/72d10b4))
- Update demo map ([c009c52](../../commit/c009c52))
- Enable doc building ([ffe3eef](../../commit/ffe3eef))
- Allow manual dispatch ([4dc8d4a](../../commit/4dc8d4a))
- Upgrade doxygen ([73c5375](../../commit/73c5375))
- Update readme ([1fc2ff3](../../commit/1fc2ff3))

## [0.0.13] - 2024-12-24

### Fixes
- ArgumentOutOfRangeException with sepia colors ([5257dec](../../commit/5257dec))

## [0.0.12] - 2024-12-24

### Features
- Add friendly URLs setting to config file ([9a055c9](../../commit/9a055c9))

## Pre-0.1.0 - Development History

### 2024-12-18
- Update to Vintage Story 1.20.0-rc.X ([a20bf47](../../commit/a20bf47))

### 2024-07-11
- Add wiki link for httpd access denied error ([72dbf23](../../commit/72dbf23))

### 2024-07-06
- Cleanup csproj ([3c33c6a](../../commit/3c33c6a))

### 2024-07-04
- Summer colors ([eb62919](../../commit/eb62919))

### 2024-06-21
- Stop trader markers from multiplying since they walk around ([dd33b22](../../commit/dd33b22))

### 2024-06-20
- Fix build ([636aa26](../../commit/636aa26))
- Change logger messages to debug level ([9226d11](../../commit/9226d11))

### 2024-06-16
- Include debug symbols in build ([a21f8fd](../../commit/a21f8fd))

### 2024-06-11
- Tweak cluster radius ([385a4bf](../../commit/385a4bf))
- Cluster markers ([4af5c26](../../commit/4af5c26))

### 2024-06-10
- Fix some stuffs ([9a6ae1f](../../commit/9a6ae1f))
- Make traders work finally ([120c5b7](../../commit/120c5b7))

### 2024-06-07
- Implement account entitlement colors ([476d1b3](../../commit/476d1b3))

### 2024-06-02
- Remove unnecessary annotations ([4786a1b](../../commit/4786a1b))
- Do not render incomplete chunks ([777b8d8](../../commit/777b8d8))

### 2024-06-01
- More work on structure layers ([7c2dbf2](../../commit/7c2dbf2))
- Some progress on config and structure layers ([0a0a5d5](../../commit/0a0a5d5))
- Cleanup chunkloader code ([3d10f2e](../../commit/3d10f2e))

### 2024-05-31
- Don't fade/blink tile images ([de6be86](../../commit/de6be86))
- Work on markers some more ([03efc40](../../commit/03efc40))

### 2024-05-30
- Default players and spawn marker layers to enabled true ([9b89fea](../../commit/9b89fea))
- Fix build ([050d977](../../commit/050d977))
- Add more player marker options ([74ea382](../../commit/74ea382))
- Only poll layers if previous poll is complete ([c2d13cf](../../commit/c2d13cf))

### 2024-05-28
- Fix ugly white borders on slow loading tiles ([baaf6e9](../../commit/baaf6e9))
- Configurable URL in command ([f73fa32](../../commit/f73fa32))
- Finish the apothemrender command ([f6f4fec](../../commit/f6f4fec))

### 2024-05-27
- Finish refactor ([633bc72](../../commit/633bc72))
- Move logo SVG into index.html ([7288f14](../../commit/7288f14))
- Fix logo spacing issue in sidebar ([6f4d0f3](../../commit/6f4d0f3))
- Remove all data files (part 2) ([f2e2950](../../commit/f2e2950))
- Remove all data files ([cac40c3](../../commit/cac40c3))
- Refactor ([4b0dd59](../../commit/4b0dd59))

### 2024-05-26
- Refactor ([4b0dd59](../../commit/4b0dd59))

### 2024-05-23
- Fail cleanly ([8608cf1](../../commit/8608cf1))
- Save config changes ([9bf616d](../../commit/9bf616d))

### 2024-05-21
- Cleanup client stuff to prepare for what's next ([6f63c4f](../../commit/6f63c4f))
- Cleanup some statics ([decb46d](../../commit/decb46d))
- Customizable logo stuff ([006550b](../../commit/006550b))
- Fix up the tasks/threads ([b93a340](../../commit/b93a340))

### 2024-05-19
- Yeah, that looks good ([c5a8ad7](../../commit/c5a8ad7))
- Add more opengraph images ([3e30a65](../../commit/3e30a65))

### 2024-05-13
- Some more progress ([245b04a](../../commit/245b04a))
- z-index ([d46e0be](../../commit/d46e0be))

### 2024-05-11
- More progress ([78f238a](../../commit/78f238a))

### 2024-05-09
- Fix player rotation ([23fc78a](../../commit/23fc78a))
- Colormap tweaks ([e422a1f](../../commit/e422a1f))

### 2024-05-08
- Fix players with non-alphanumeric UIDs ([d741f5d](../../commit/d741f5d))

### 2024-05-07
- Get rid of layers.png file ([87e2e82](../../commit/87e2e82))
- Push up progress ([55c8e36](../../commit/55c8e36))

### 2024-05-05
- Separate title and logo, and make logo a link ([a18db16](../../commit/a18db16))
- More progress ([3be520d](../../commit/3be520d))

### 2024-05-04
- Progress ([ed396dc](../../commit/ed396dc))
- Dark/light themed favicon.ico ([e61b9f2](../../commit/e61b9f2))
- Tweak friendly URL stuff ([ec02a3c](../../commit/ec02a3c))
- Share page title with sidebar logo ([eba4c64](../../commit/eba4c64))
- Tweak sidebar transitions timing ([8e21629](../../commit/8e21629))
- Push up some progress ([9569950](../../commit/9569950))

### 2024-05-03
- Fix index.html's meta tags ([419ff64](../../commit/419ff64))
- Allow logo.svg to be replaced ([2fab85d](../../commit/2fab85d))
- Push up some progress ([068f84e](../../commit/068f84e))

### 2024-05-02
- Rename medieval to sepia ([6efa02c](../../commit/6efa02c))
- Cleanup some stuff ([53634b8](../../commit/53634b8))
- Fix white lines in map on chunk slice edges ([a1d807e](../../commit/a1d807e))
- Fix config packet serialization ([1e3fc49](../../commit/1e3fc49))
- Push up progress ([ead11f4](../../commit/ead11f4))

### 2024-05-01
- Version bump ([1b20393](../../commit/1b20393))
- Refactor ([78553c8](../../commit/78553c8))
- Update meta card ([fcf97b4](../../commit/fcf97b4))
- Scan once, render twice ([c3c7865](../../commit/c3c7865))
- More progress ([c8165fc](../../commit/c8165fc))
- Push up progress ([a5f0e4d](../../commit/a5f0e4d))

### 2024-04-30
- Upload some progress ([ff212c5](../../commit/ff212c5))

### 2024-04-28
- Put comments on halfslider element ([c6644e3](../../commit/c6644e3))
- Move stuff around ([849e4ba](../../commit/849e4ba))
- More progress ([f9768f0](../../commit/f9768f0))
- Use more dependency injection ([2d847a9](../../commit/2d847a9))
- Push up some more progress ([4b5333b](../../commit/4b5333b))

### 2024-04-27
- Remove the rest of Lang so it compiles ([71a5581](../../commit/71a5581))
- Progress ([0f5a3f7](../../commit/0f5a3f7))
- Stop browsers from logging 404 errors in developer console ([30c9479](../../commit/30c9479))

### 2024-04-23
- Refactor namespaces - convention was too restricting ([2fcdf79](../../commit/2fcdf79))

### 2024-04-22
- Use only URLs nuget trusts for images ([a1458c7](../../commit/a1458c7))
- Update badges and have tokei ignore .conf files ([111d6e8](../../commit/111d6e8))
- Fix some badges in README.md ([0c7e47e](../../commit/0c7e47e))
- Work on README.md some more ([1504dd1](../../commit/1504dd1))

### 2024-04-21
- Version bump ([b0c2289](../../commit/b0c2289))
- Hide dependencies from nuget ([1490b83](../../commit/1490b83))
- Update modicon.png ([3603b67](../../commit/3603b67))
- Set version earlier in build process ([922e0ea](../../commit/922e0ea))
- Update README.md ([88c8d99](../../commit/88c8d99))
- Remove debug stuff ([0678bdd](../../commit/0678bdd))
- Fix version ([6c109ae](../../commit/6c109ae))
- Include version in filename ([c9d9de6](../../commit/c9d9de6))
- Progress ([1d7a09d](../../commit/1d7a09d))

### 2024-04-20
- Cleanup JSON deserializing error handling ([892eeae](../../commit/892eeae))
- Save points as floored ints in JSON ([61fdeda](../../commit/61fdeda))
- Cleanup imports ([60fe799](../../commit/60fe799))
- Update README.md ([9f21065](../../commit/9f21065))
- Move doxygen to gh actions ([2396df9](../../commit/2396df9))
- Make Point a struct ([0fb728d](../../commit/0fb728d))
- Remove patronizing statement from docs ([fc56085](../../commit/fc56085))
- Color struct ([ccece58](../../commit/ccece58))
- Get rid of useless JsonSerializable interface ([ae90551](../../commit/ae90551))
- Rename doxygen config ([1a6b3f8](../../commit/1a6b3f8))
- Remove broken rules ([ab10b15](../../commit/ab10b15))
- More API stuffs ([27634b6](../../commit/27634b6))

### 2024-04-18
- C# Point API ([a64a6c7](../../commit/a64a6c7))
- Location to Point ([1d2616e](../../commit/1d2616e))

### 2024-04-17
- Progress ([e5e610b](../../commit/e5e610b))
- Time to upload some progress ([cb8baab](../../commit/cb8baab))

### 2024-04-16
- Fix double mousewheel zoom on Chrome-based browsers on Linux ([5d9ad23](../../commit/5d9ad23))
- PNG to SVG ([b029200](../../commit/b029200))
- Update README.md ([34e97a7](../../commit/34e97a7))

### 2024-04-15
- Progress ([325f970](../../commit/325f970))

### 2024-04-14
- Progress ([d099992](../../commit/d099992))

### 2024-04-13
- Fixup location stuff ([ad8cf51](../../commit/ad8cf51))
- Simplify regex and parse URL params better ([df48c29](../../commit/df48c29))
- Context menu progress ([bcb7078](../../commit/bcb7078))

### 2024-04-12
- Allow use of inline SVGs in marker icons ([8b689c1](../../commit/8b689c1))
- Stick to relative paths ([6064f50](../../commit/6064f50))
- Progress ([5ef6ee3](../../commit/5ef6ee3))

### 2024-04-11
- Handle point/latlng better ([254c959](../../commit/254c959))

### 2024-04-10
- Handle point/latlng better ([254c959](../../commit/254c959))
- .tokeignore ([c6eb4f8](../../commit/c6eb4f8))
- README badges ([2636eee](../../commit/2636eee))
- Default settings needed ([e797ed6](../../commit/e797ed6))
- Version bump ([4c05cd0](../../commit/4c05cd0))

### 2024-04-08
- More progress ([30f9c0d](../../commit/30f9c0d))
- More context menu work ([6df1772](../../commit/6df1772))

### 2024-04-07
- More work on context menu ([b347953](../../commit/b347953))

### 2024-04-05
- More progress ([e6beb26](../../commit/e6beb26))
- Do not refresh/reload page when clicking link button ([9dec907](../../commit/9dec907))
- Prevent click event propagation on custom control boxes ([5429a71](../../commit/5429a71))

### 2024-04-04
- Let to const ([6dab576](../../commit/6dab576))
- Add and cleanup the game's worldmap icons ([f3260f1](../../commit/f3260f1))
- Finish up the markers stuff ([9f99f2d](../../commit/9f99f2d))
- Cleanup ColorMapCommand for codefactor.io ([4b2d4bf](../../commit/4b2d4bf))
- A little cleaning up ([b58eb8c](../../commit/b58eb8c))

### 2024-04-03
- Move some images around ([0ea59fc](../../commit/0ea59fc))
- Make default layer interval 5 minutes ([0e2e991](../../commit/0e2e991))
- Add marker layer options ([e03e417](../../commit/e03e417))
- Remove left over debug message ([35c5c79](../../commit/35c5c79))
- Progress ([3c33788](../../commit/3c33788))
- More codefactor.io fixes ([bd2d69f](../../commit/bd2d69f))
- More easy fixes ([0220642](../../commit/0220642))
- Fix low hanging fruit for codefactor.io ([88797b2](../../commit/88797b2))
- Move some files around ([b2e5a50](../../commit/b2e5a50))
- Get markers working in the frontend ([13a5246](../../commit/13a5246))

### 2024-04-02
- Better variable names for file streams ([2a9337c](../../commit/2a9337c))
- Color micro optimization ([2dc1936](../../commit/2dc1936))
- Full PNG compression (we don't need quality) ([ec219be](../../commit/ec219be))
- Version bump ([bb20f80](../../commit/bb20f80))
- Remove livemap.admin privilege ([9ad5f06](../../commit/9ad5f06))
- Auto reload config ([a7697ca](../../commit/a7697ca))
- Tweak the zoom stuff ([8cf8ddf](../../commit/8cf8ddf))
- Version bump ([6435bb5](../../commit/6435bb5))

### 2024-04-01
- Process zoomed out tiles ([4433b6b](../../commit/4433b6b))
- Don't compile test tiles ([de9fe9e](../../commit/de9fe9e))
- Fix database reader ([7e30ace](../../commit/7e30ace))
- Fix logger crap ([d5e6063](../../commit/d5e6063))
- Cleanup stuff ([fd13b59](../../commit/fd13b59))
- Move logger and config stuff around ([ab97ba1](../../commit/ab97ba1))
- More progress ([192bb27](../../commit/192bb27))
- Add tile layers ([65a8b05](../../commit/65a8b05))
- Interrupt the render task ([7033f22](../../commit/7033f22))

### 2024-03-31
- More progress ([708c6d0](../../commit/708c6d0))
- Fix build ([477e3f7](../../commit/477e3f7))
- Progress ([6baefe2](../../commit/6baefe2))
- Switch to Jenkins ([eadb229](../../commit/eadb229))
- Work on actions ([c7bb07e](../../commit/c7bb07e))
- Progress ([008c4bf](../../commit/008c4bf))
- TypeScript ([34b049f](../../commit/34b049f))

### 2024-03-30
- Add leaflet extra files back ([f85d135](../../commit/f85d135))
- Progress ([ac99606](../../commit/ac99606))

### 2024-03-29
- Progress ([2200a0a](../../commit/2200a0a))

### 2024-03-15
- Add basic social media meta tags ([f980e57](../../commit/f980e57))
- Add funding.yml ([d024816](../../commit/d024816))

### 2024-03-14
- Ready for pre-alpha testing ([637bfbc](../../commit/637bfbc))
- Delete leaflet JS src files ([29a07f1](../../commit/29a07f1))
- It's almost usable now ([37d6091](../../commit/37d6091))

### 2024-03-13
- More progress ([5b0109a](../../commit/5b0109a))
- Even more ([593f7c6](../../commit/593f7c6))
- More progress ([64a6d4b](../../commit/64a6d4b))
- Progress ([3813749](../../commit/3813749))

### 2024-01-14
- Tidy up the project files ([a4699ef](../../commit/a4699ef))

### 2024-01-12
- Slight style change ([96d30e9](../../commit/96d30e9))

### 2024-01-11
- More progress ([52cb9ff](../../commit/52cb9ff))
- Fix a couple bugs ([eee569c](../../commit/eee569c))
- Progress ([78e038b](../../commit/78e038b))

### 2024-01-10
- Slight progress ([7b3991d](../../commit/7b3991d))
- More progress ([b92b1cc](../../commit/b92b1cc))
- Getting closer ([b2c33e1](../../commit/b2c33e1))

### 2024-01-09
- More progress ([b2a86c1](../../commit/b2a86c1))
- Remove unneeded code ([c517c2f](../../commit/c517c2f))
- Remove region class (replace with long index) ([a1b84db](../../commit/a1b84db))
- Move logger and lang to util ([70fe20f](../../commit/70fe20f))
- Even more progress ([728601b](../../commit/728601b))

### 2024-01-08
- Some progress ([b691b8e](../../commit/b691b8e))

### 2023-08-15
- Progress ([2d43894](../../commit/2d43894))

### 2023-08-14
- Get colormap from admin's client ([fb641e4](../../commit/fb641e4))
- Initial commit ([edaa5ae](../../commit/edaa5ae))
