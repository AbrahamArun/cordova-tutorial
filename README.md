# cordova-tutorial
A quick intro into cordova

1. What is it?
  - [ ] Open source mobile development framework
  - [ ] Uses standard web technologies: HTML, CSS & Javascript
  - [ ] Relies on [standards-compliant API bindings](https://developer.mozilla.org/en-US/docs/Web/API) (https://developer.mozilla.org/en-US/docs/Web/API).
        - [ ] Example: [Geolocation](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/geolocation)
        - [ ] Example: [Accelerometer](https://developer.mozilla.org/en-US/docs/Web/API/DeviceAcceleration)

2. Why is it needed?
  - [ ] Painful to maintain platform specific code
  - [ ] Time consuming to write in native code

3. How does cordova work?
  - [ ] Wraps a Web View within native app and provides an interface between javascript and the native layer

4. How to get started?

  Pre-requisites
  - [ ] Basic HTML, CSS and Javscript knowledge
  - [ ] Install: [node](https://nodejs.org/en/), [cordova cli](https://cordova.apache.org/), platform sdk's (android, ios etc.), emulator/simulator

  Example Hello Worlld App:
  - [ ] `cordova create foo com.example.foo Foo`
  - [ ] `cordova platform add android --save`
  - [ ] `cordova build android`
  - [ ] `cordova run android`
  - [ ] Similarly above 3 steps for iOS
  - [ ] Example showing a basic UI element and interaction?
  - [ ] Directory structure? Open individual platform specific code to dive into the core implementation

5. Plugins?
  - [ ] https://cordova.apache.org/plugins/
      - [ ] `cordova plugin add cordova-plugin-x-toast`
      - [ ] `cordova prepare`
  - [ ] How to write a custom plugin?
  - [ ] Check an existing plugin code to understand: Example 1: https://github.com/EddyVerbruggen/Toast-PhoneGap-Plugin (Clone url git@github.com:EddyVerbruggen/Toast-PhoneGap-Plugin.git)

6. Distributions
  - [ ] [Phone Gap](http://phonegap.com/)
  - [ ] [Ionic](http://ionic.io/) - Has a lot of standard controls that mimics native controls and it comes with Angular

7. Advanced:
  - [ ] [Buid as a component within a larger, hybrid application that mixes the WebView with native application components](https://cordova.apache.org/docs/en/latest/guide/hybrid/webviews/index.html)
