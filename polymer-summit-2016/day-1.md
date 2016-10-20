# Polymer Summit 2016 - Day 1

## Opening keynote - @taylorthesavage

- mobile: acceleration with web platform (PWA)
- **use the platform!**
  - vanilla/native API FTW
  - be selective with abstraction
- Web Components
  - first draft 22 May 2012 (v0)
  - now on v1, major browser vendors (almost) fully support this spec
- Polymer
  - 2014: Polymer 0.5
  - 2015: Polymer 1.0
  - 2016 adopters; Comcast, USA Today, ING, Coca Cola, EA, Predix (GE), **YouTube** (new)
  - pre release Polymer 2.0 (Web Components v1, ES6 classes, more Vanilla APIs, hybrid mode, **12kb**)
  - standards based, community driven
  - **beta.webcomponents.org** new components library (store like)!
  - Polymer has more HTML-CSS lines of code than any other framework.
  - Suggested components quality criteria:
    - Repo
    - I18n
    - A11y (accessible)
    - Tests
    - Demo
    - Blueprint/Mocks
    - Docs

## The Way of the Web @ ING - Ben Issa

- Size of a single page today is the same of **Doom** game
- iPhone 7 perform as 2013 MacBook Pro
- RDD resume driven development :D
- being a Web Developer not a framework developer
- Custom elements + domain based service
- Standards **are** the Web

## A Polymer Experience - Wendy Ginsberg

**Polymon**: PWA game in Polymer + Firebase

- Frictionless download
- Service worker (connectivity issue, cache)
- Native look and feel
- 200kb!

## Polymer 2.0: Under the Hood - Rob Dodson

- Polymer is an **opinionated usage** of Web Components.
- HTML tags are **instances** of classes. (```<input>``` -> HTMLInputElement).
- in **constructor()** you cant access the DOM.
- Manipulate DOM with native & Shadow DOM APIs.
- Dispatch an event for every state change.
- PolymerElement is a collection of mixins that extend the HTMLElement.
- You can extend single utility of Polymer not only whole library.
- Can **extend other Custom Elements**!
- No more mutation setters
- ```#usetheplatform``` :)

## Polymer 2.0 in 2.0 seconds: Upgrading Projects Large and Small - Peter Burns

- Minimally breaking
- ```<content>``` replaced by ```<slot>```
- Upgrader and linter tool, written in NodeJS
- Hybrid mode: use Polymer 1.0 and Polymer 2.0 components together.

## Polymer Butter and Firebase Jelly - Michael Bleigh

- Web push in Firebase as Cloud Messaging Service!
- Used by alibaba.com
- updated PolymerFire, Cloud Messaging integrated as component.
- send message to app wheter or not its open (based on service workers)
- ```#loosethebackend``` :)

## Data Flow in Polymer Elements and Apps - Gray Norton

- Every modern frontend framework approched the components model.

## Evolving chromestatus.com into a Lightning-Fast PWA - Eric Bidelman

- Chrome 52 settings page built in Polymer
- using async in link tags
- async load polyfills
- lazy load
- dom: 'shadow', lazyLoad: 'max', useNativeCSSProperties: true
- link rel preload as "html" or "script"
- poly-icon.appspot.com
- appmetric.js (NPM), bindable with Google Analytics

## Production-Ready Polymer Elements - A How-To-Guide - Daniel Freedman

- Polymer team uses Travis CI
- PRPL pattern:
  - Lazy load Polyfills.
  - Async HTML imports.
  - Link rel="preload".
  - h2 push manifest.
  - lazy-load non critical components.
  - appmetrics.js

## Codelab: Building an Image Carousel Element with Polymer 2.0 - Keanu Lee

https://codelabs.developers.google.com/codelabs/polymer-2-carousel/index.html

## Interacting with the Physical Web - Scott Jenson

- The Web needs a discovery sevice
- physicalweb.org

## Monster Apps - Chris Joel

- Media capture & streams API ```navigator.mediaDevices```
- ```canvas.drawImage()``` to get screenshot from a video element and downsample at the same time
- https://github.com/cdata/meat-scope-elements
- CommonWorker library to encode GIF
