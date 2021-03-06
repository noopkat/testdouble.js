# Change Log

## [v3.1.0](https://github.com/testdouble/testdouble.js/tree/v3.1.0) (2017-06-18)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v3.0.0...v3.1.0)

**Fixed bugs:**

- td.replace throws with objects created with Object.create [\#257](https://github.com/testdouble/testdouble.js/issues/257)
- getters are executed when using td.constructor\(\) [\#218](https://github.com/testdouble/testdouble.js/issues/218)

**Closed issues:**

- Verify that constructor is passed certain values [\#256](https://github.com/testdouble/testdouble.js/issues/256)
- Is there any sample code that mock aws sdk? [\#251](https://github.com/testdouble/testdouble.js/issues/251)
- Cannot use `td.object` with "callable objects" [\#232](https://github.com/testdouble/testdouble.js/issues/232)

**Merged pull requests:**

- Allow stubbing of custom instances & Object.create\(\) [\#264](https://github.com/testdouble/testdouble.js/pull/264) ([searls](https://github.com/searls))
- Enable tsc in ci pipeline take 2 [\#260](https://github.com/testdouble/testdouble.js/pull/260) ([duluca](https://github.com/duluca))
- TypeScript typing thenResolve takes variable args [\#258](https://github.com/testdouble/testdouble.js/pull/258) ([miyu](https://github.com/miyu))
- Test testdouble.js with testdouble.js! [\#255](https://github.com/testdouble/testdouble.js/pull/255) ([searls](https://github.com/searls))

## [v3.0.0](https://github.com/testdouble/testdouble.js/tree/v3.0.0) (2017-06-02)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.1.2...v3.0.0)

**Fixed bugs:**

- Figure out babel+instanceof+constructor problems with class extension  [\#241](https://github.com/testdouble/testdouble.js/issues/241)
- Mocking a Class [\#157](https://github.com/testdouble/testdouble.js/issues/157)

**Closed issues:**

- `td.verify` reporting after resolving promises [\#250](https://github.com/testdouble/testdouble.js/issues/250)
- Replacing dependency with td.replace\(path, replacement\) doesn't work [\#249](https://github.com/testdouble/testdouble.js/issues/249)
- Verify constructor [\#248](https://github.com/testdouble/testdouble.js/issues/248)
- td.replace \(\) breaks the cache in require [\#244](https://github.com/testdouble/testdouble.js/issues/244)
- Faking internal calls [\#243](https://github.com/testdouble/testdouble.js/issues/243)
- ECMAScript 2015 Classes with td.constructor\(\) [\#240](https://github.com/testdouble/testdouble.js/issues/240)
- TypeScript: Better Generic Support for td.object\(\) [\#236](https://github.com/testdouble/testdouble.js/issues/236)
- How to Replace Imported Constructor in Another File [\#235](https://github.com/testdouble/testdouble.js/issues/235)
- Mocha Spec Reporter [\#234](https://github.com/testdouble/testdouble.js/issues/234)
- TypeError: 'x' is not a function [\#233](https://github.com/testdouble/testdouble.js/issues/233)
- Inifinite recursion problem [\#231](https://github.com/testdouble/testdouble.js/issues/231)
- Invoke callback within object [\#230](https://github.com/testdouble/testdouble.js/issues/230)
- Testing Constructor invocations [\#229](https://github.com/testdouble/testdouble.js/issues/229)
- Stubbing chained API objects yields a warning [\#228](https://github.com/testdouble/testdouble.js/issues/228)

**Merged pull requests:**

- Stop extending types when replacing constructors [\#254](https://github.com/testdouble/testdouble.js/pull/254) ([searls](https://github.com/searls))
- Fix \#236; Add another overload and its test [\#237](https://github.com/testdouble/testdouble.js/pull/237) ([sgtoj](https://github.com/sgtoj))

## [v2.1.2](https://github.com/testdouble/testdouble.js/tree/v2.1.2) (2017-03-29)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.1.1...v2.1.2)

**Closed issues:**

- TypeError when used with node -r flag [\#226](https://github.com/testdouble/testdouble.js/issues/226)
- When replacing a node library calling it from other modules does not work as expected [\#225](https://github.com/testdouble/testdouble.js/issues/225)

## [v2.1.1](https://github.com/testdouble/testdouble.js/tree/v2.1.1) (2017-03-28)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.1.0...v2.1.1)

**Closed issues:**

- Add td.config\(\) to index.d.ts [\#222](https://github.com/testdouble/testdouble.js/issues/222)
- Mocking external dependencies in Express app [\#221](https://github.com/testdouble/testdouble.js/issues/221)

**Merged pull requests:**

- Add typings for config function [\#223](https://github.com/testdouble/testdouble.js/pull/223) ([lumaxis](https://github.com/lumaxis))

## [v2.1.0](https://github.com/testdouble/testdouble.js/tree/v2.1.0) (2017-03-25)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.0.5...v2.1.0)

**Closed issues:**

- Using td.replace\(\) with external modules [\#51](https://github.com/testdouble/testdouble.js/issues/51)

**Merged pull requests:**

- Add support for third party modules [\#220](https://github.com/testdouble/testdouble.js/pull/220) ([searls](https://github.com/searls))

## [v2.0.5](https://github.com/testdouble/testdouble.js/tree/v2.0.5) (2017-03-25)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.0.4...v2.0.5)

## [v2.0.4](https://github.com/testdouble/testdouble.js/tree/v2.0.4) (2017-03-23)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.0.3...v2.0.4)

**Closed issues:**

- `constructor\(someConstructorFunction\)` not referenced in associated example [\#213](https://github.com/testdouble/testdouble.js/issues/213)

**Merged pull requests:**

- Improve main build [\#212](https://github.com/testdouble/testdouble.js/pull/212) ([searls](https://github.com/searls))

## [v2.0.3](https://github.com/testdouble/testdouble.js/tree/v2.0.3) (2017-03-18)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.0.2...v2.0.3)

**Merged pull requests:**

- Rework test build [\#211](https://github.com/testdouble/testdouble.js/pull/211) ([searls](https://github.com/searls))

## [v2.0.2](https://github.com/testdouble/testdouble.js/tree/v2.0.2) (2017-03-17)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.0.1...v2.0.2)

**Closed issues:**

- Mocking a constructor function with no prototypes does not correctly mock static methods [\#208](https://github.com/testdouble/testdouble.js/issues/208)
- Test td.function\(\) after other td fuction\(\) [\#202](https://github.com/testdouble/testdouble.js/issues/202)
- How do I stub a function that being promisify'd by bluebird? [\#200](https://github.com/testdouble/testdouble.js/issues/200)

**Merged pull requests:**

- Preserve function context when calling thenDo [\#209](https://github.com/testdouble/testdouble.js/pull/209) ([connor4312](https://github.com/connor4312))
- Decaffeinate [\#206](https://github.com/testdouble/testdouble.js/pull/206) ([searls](https://github.com/searls))

## [v2.0.1](https://github.com/testdouble/testdouble.js/tree/v2.0.1) (2017-03-13)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v2.0.0...v2.0.1)

## [v2.0.0](https://github.com/testdouble/testdouble.js/tree/v2.0.0) (2017-03-13)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.11.2...v2.0.0)

**Closed issues:**

- How can I write a test for such situation? [\#199](https://github.com/testdouble/testdouble.js/issues/199)
- contains not working against IIFE objects [\#192](https://github.com/testdouble/testdouble.js/issues/192)
- td.verify not returning true when true [\#191](https://github.com/testdouble/testdouble.js/issues/191)
- Typing definition for td.object doesn't support constructors with arguments [\#184](https://github.com/testdouble/testdouble.js/issues/184)
- Replacing methods on `window.location` [\#183](https://github.com/testdouble/testdouble.js/issues/183)
- stub also verified warning when using ignoreExtraArgs [\#181](https://github.com/testdouble/testdouble.js/issues/181)
- \[BREAKING\] Return constructor for `td.replace\(\)` [\#166](https://github.com/testdouble/testdouble.js/issues/166)
- Allow matchers inside objects [\#160](https://github.com/testdouble/testdouble.js/issues/160)
- Support invoking callbacks with arbitrary timing [\#106](https://github.com/testdouble/testdouble.js/issues/106)

**Merged pull requests:**

- Async callbacks [\#205](https://github.com/testdouble/testdouble.js/pull/205) ([searls](https://github.com/searls))
- Create test double functions and copy/fake their properties [\#204](https://github.com/testdouble/testdouble.js/pull/204) ([searls](https://github.com/searls))
- Support deep matchers [\#203](https://github.com/testdouble/testdouble.js/pull/203) ([searls](https://github.com/searls))
- introduce td.constructor\(\) as top-level API sibling to td.object\(\) & td.function\(\) [\#201](https://github.com/testdouble/testdouble.js/pull/201) ([searls](https://github.com/searls))
- Allow Babel compilation [\#197](https://github.com/testdouble/testdouble.js/pull/197) ([searls](https://github.com/searls))
- Improves warning when verifying a stub [\#196](https://github.com/testdouble/testdouble.js/pull/196) ([samjonester](https://github.com/samjonester))
- Yarn [\#195](https://github.com/testdouble/testdouble.js/pull/195) ([searls](https://github.com/searls))
- Creates Better Verification Message [\#194](https://github.com/testdouble/testdouble.js/pull/194) ([samjonester](https://github.com/samjonester))
- Replace constructors with constructors [\#193](https://github.com/testdouble/testdouble.js/pull/193) ([searls](https://github.com/searls))

## [v1.11.2](https://github.com/testdouble/testdouble.js/tree/v1.11.2) (2017-02-28)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.11.1...v1.11.2)

**Closed issues:**

- Stubbing promises with thenResolve does not actually provide for anything in the callback [\#189](https://github.com/testdouble/testdouble.js/issues/189)
- sinon.sandbox analog? [\#188](https://github.com/testdouble/testdouble.js/issues/188)
- Shortcut for new stub returning args [\#187](https://github.com/testdouble/testdouble.js/issues/187)
-  Can't find variable: Proxy [\#186](https://github.com/testdouble/testdouble.js/issues/186)

**Merged pull requests:**

- Improve the error message when using Proxy incorrectly. [\#190](https://github.com/testdouble/testdouble.js/pull/190) ([Schoonology](https://github.com/Schoonology))

## [v1.11.1](https://github.com/testdouble/testdouble.js/tree/v1.11.1) (2017-01-27)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.11.0...v1.11.1)

**Closed issues:**

- Is it possible to `thenReturn` the receiver? [\#182](https://github.com/testdouble/testdouble.js/issues/182)
- Multiple stubbings with argThat causes unexpected behavior [\#180](https://github.com/testdouble/testdouble.js/issues/180)

**Merged pull requests:**

- Update type definition [\#185](https://github.com/testdouble/testdouble.js/pull/185) ([caseyhoward](https://github.com/caseyhoward))

## [v1.11.0](https://github.com/testdouble/testdouble.js/tree/v1.11.0) (2017-01-17)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.10.2...v1.11.0)

**Closed issues:**

- Having something like "verifyNoFurtherInvocations\(mock\)" would be nice \(feature request\) [\#176](https://github.com/testdouble/testdouble.js/issues/176)

**Merged pull requests:**

- feat: contains allows for regexps against strings [\#178](https://github.com/testdouble/testdouble.js/pull/178) ([JaKXz](https://github.com/JaKXz))

## [v1.10.2](https://github.com/testdouble/testdouble.js/tree/v1.10.2) (2016-12-31)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.10.1...v1.10.2)

**Closed issues:**

- Possible pollution issue \(2 tests work individually, but fails when run together\) [\#171](https://github.com/testdouble/testdouble.js/issues/171)
- td.verify and td.when redundency warning [\#170](https://github.com/testdouble/testdouble.js/issues/170)
- Does not work with jest [\#128](https://github.com/testdouble/testdouble.js/issues/128)

**Merged pull requests:**

- Captor typings [\#174](https://github.com/testdouble/testdouble.js/pull/174) ([danielmoore](https://github.com/danielmoore))
- Align TS replace\(\) signuatrue return with implementaiton [\#173](https://github.com/testdouble/testdouble.js/pull/173) ([danielmoore](https://github.com/danielmoore))

## [v1.10.1](https://github.com/testdouble/testdouble.js/tree/v1.10.1) (2016-12-20)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.10.0...v1.10.1)

**Implemented enhancements:**

- Make the `constructor` property of td.replaced\(\) instantiable types useful [\#121](https://github.com/testdouble/testdouble.js/issues/121)
- Improve output for `times` verification failures [\#85](https://github.com/testdouble/testdouble.js/issues/85)
- Allow argument matchers to enhance failure messages [\#59](https://github.com/testdouble/testdouble.js/issues/59)
- td.constructor\(\) feature for creating fake constructors [\#54](https://github.com/testdouble/testdouble.js/issues/54)

**Closed issues:**

- typings for typescript [\#167](https://github.com/testdouble/testdouble.js/issues/167)
- A little typo in Getting Started documentation [\#165](https://github.com/testdouble/testdouble.js/issues/165)
- Unable to stub static method on ES6 classes [\#164](https://github.com/testdouble/testdouble.js/issues/164)
- transcribe unusual spending kata from ES5 to ES6/babel  [\#163](https://github.com/testdouble/testdouble.js/issues/163)
- Classes with overridden methods not doubling properly since 1.10.0 [\#159](https://github.com/testdouble/testdouble.js/issues/159)
- `td.replace\(\)` doesn't work with `import`? [\#147](https://github.com/testdouble/testdouble.js/issues/147)
- Support multiple capture invocations [\#139](https://github.com/testdouble/testdouble.js/issues/139)
- Constructor replacements will fail instanceof checks [\#107](https://github.com/testdouble/testdouble.js/issues/107)

**Merged pull requests:**

- Typings for typescript [\#169](https://github.com/testdouble/testdouble.js/pull/169) ([mkusher](https://github.com/mkusher))

## [v1.10.0](https://github.com/testdouble/testdouble.js/tree/v1.10.0) (2016-12-11)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.9.1...v1.10.0)

**Implemented enhancements:**

- td.replace doesn't properly detect ES6 classes [\#119](https://github.com/testdouble/testdouble.js/issues/119)

**Closed issues:**

- Matcher for a specific position [\#156](https://github.com/testdouble/testdouble.js/issues/156)

**Merged pull requests:**

- Sort out replacement of especially 6+ Classes [\#158](https://github.com/testdouble/testdouble.js/pull/158) ([searls](https://github.com/searls))

## [v1.9.1](https://github.com/testdouble/testdouble.js/tree/v1.9.1) (2016-12-03)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.9.0...v1.9.1)

**Implemented enhancements:**

- td.replace for functions that have additional function properties [\#99](https://github.com/testdouble/testdouble.js/issues/99)

**Closed issues:**

- Is testdouble.js not compatible with PhantomJS? [\#154](https://github.com/testdouble/testdouble.js/issues/154)
- Model instance creation assistance [\#149](https://github.com/testdouble/testdouble.js/issues/149)
- Excessive warn "was both stubbed and verified" [\#148](https://github.com/testdouble/testdouble.js/issues/148)

**Merged pull requests:**

- Add failing test for resetting replaced modules. [\#215](https://github.com/testdouble/testdouble.js/pull/215) ([Schoonology](https://github.com/Schoonology))
- typo [\#152](https://github.com/testdouble/testdouble.js/pull/152) ([ghedamat](https://github.com/ghedamat))

## [v1.9.0](https://github.com/testdouble/testdouble.js/tree/v1.9.0) (2016-10-25)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.8.0...v1.9.0)

**Implemented enhancements:**

- Note when `ignoreExtraArgs` is used for a failed verification [\#60](https://github.com/testdouble/testdouble.js/issues/60)

**Closed issues:**

- td.replace multiple property names at once [\#146](https://github.com/testdouble/testdouble.js/issues/146)
- Consider ignoreExtraArgs method instead of parameter [\#143](https://github.com/testdouble/testdouble.js/issues/143)

**Merged pull requests:**

- Gives better hint when verification fails while ignoring extra args [\#150](https://github.com/testdouble/testdouble.js/pull/150) ([samjonester](https://github.com/samjonester))

## [v1.8.0](https://github.com/testdouble/testdouble.js/tree/v1.8.0) (2016-10-12)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.7.0...v1.8.0)

**Closed issues:**

- Feature request: Partial object matchers [\#141](https://github.com/testdouble/testdouble.js/issues/141)
- Drop CoffeeScript [\#140](https://github.com/testdouble/testdouble.js/issues/140)
- Question with verifications [\#138](https://github.com/testdouble/testdouble.js/issues/138)
- td.reset\(\) it´s working has expected? [\#133](https://github.com/testdouble/testdouble.js/issues/133)

**Merged pull requests:**

- Docs for multiple captor values.  [\#145](https://github.com/testdouble/testdouble.js/pull/145) ([marchaos](https://github.com/marchaos))
- Allow for multiple captor invocations [\#144](https://github.com/testdouble/testdouble.js/pull/144) ([marchaos](https://github.com/marchaos))
- Remove warning of implementations of ES2015 proxy [\#136](https://github.com/testdouble/testdouble.js/pull/136) ([mgryszko](https://github.com/mgryszko))
- Fix shorthand notation for stubbing [\#135](https://github.com/testdouble/testdouble.js/pull/135) ([mgryszko](https://github.com/mgryszko))

## [v1.7.0](https://github.com/testdouble/testdouble.js/tree/v1.7.0) (2016-09-18)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.6.2...v1.7.0)

**Merged pull requests:**

- Upgrade to lodash 4.15.0 [\#132](https://github.com/testdouble/testdouble.js/pull/132) ([searls](https://github.com/searls))

## [v1.6.2](https://github.com/testdouble/testdouble.js/tree/v1.6.2) (2016-09-18)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.6.1...v1.6.2)

**Closed issues:**

- Add support for concurrent test runners \(ava\)? [\#131](https://github.com/testdouble/testdouble.js/issues/131)
- Async use of verify results in timeout [\#129](https://github.com/testdouble/testdouble.js/issues/129)

**Merged pull requests:**

- Should methods on super types be stubbed in td.object? [\#130](https://github.com/testdouble/testdouble.js/pull/130) ([paultyng](https://github.com/paultyng))

## [v1.6.1](https://github.com/testdouble/testdouble.js/tree/v1.6.1) (2016-08-31)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.6.0...v1.6.1)

**Closed issues:**

- td.explain should indicate thenCallback / thenResolve / thenReject from thenReturn [\#126](https://github.com/testdouble/testdouble.js/issues/126)
- td.when and td.verify warning [\#125](https://github.com/testdouble/testdouble.js/issues/125)
- td.callback, when given a td.object, raises a TypeError [\#124](https://github.com/testdouble/testdouble.js/issues/124)
- not matcher and calling function multiple times [\#122](https://github.com/testdouble/testdouble.js/issues/122)
- Verify of a specific call when multiple calls happen [\#120](https://github.com/testdouble/testdouble.js/issues/120)

**Merged pull requests:**

- explain plan better in stubbing description [\#127](https://github.com/testdouble/testdouble.js/pull/127) ([Moeriki](https://github.com/Moeriki))
- Fix typo in plugin name [\#123](https://github.com/testdouble/testdouble.js/pull/123) ([hanneskaeufler](https://github.com/hanneskaeufler))

## [v1.6.0](https://github.com/testdouble/testdouble.js/tree/v1.6.0) (2016-07-14)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.5.0...v1.6.0)

**Closed issues:**

- Nested stubbing doesn't work [\#117](https://github.com/testdouble/testdouble.js/issues/117)

**Merged pull requests:**

- Allow nested stubbing configuration [\#118](https://github.com/testdouble/testdouble.js/pull/118) ([searls](https://github.com/searls))

## [v1.5.0](https://github.com/testdouble/testdouble.js/tree/v1.5.0) (2016-07-13)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.4.3...v1.5.0)

**Closed issues:**

- support promises resolve/reject [\#46](https://github.com/testdouble/testdouble.js/issues/46)

**Merged pull requests:**

- Use stringify-object now that my change is merged [\#116](https://github.com/testdouble/testdouble.js/pull/116) ([searls](https://github.com/searls))
- Promise stubbing sugar [\#115](https://github.com/testdouble/testdouble.js/pull/115) ([searls](https://github.com/searls))

## [v1.4.3](https://github.com/testdouble/testdouble.js/tree/v1.4.3) (2016-06-22)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.4.2...v1.4.3)

**Closed issues:**

- Build with Travis on Node 6.x [\#114](https://github.com/testdouble/testdouble.js/issues/114)
- Wrong test double name for proxies [\#112](https://github.com/testdouble/testdouble.js/issues/112)
- Improve error output message [\#111](https://github.com/testdouble/testdouble.js/issues/111)
- Flexible parameters [\#110](https://github.com/testdouble/testdouble.js/issues/110)
- How can I install and use this in an ember/ember-cli project? [\#105](https://github.com/testdouble/testdouble.js/issues/105)
- td.replace breaks subsequent require calls [\#103](https://github.com/testdouble/testdouble.js/issues/103)

**Merged pull requests:**

- Generate test double name for a Proxy test double [\#113](https://github.com/testdouble/testdouble.js/pull/113) ([mgryszko](https://github.com/mgryszko))

## [v1.4.2](https://github.com/testdouble/testdouble.js/tree/v1.4.2) (2016-04-29)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.4.1...v1.4.2)

**Closed issues:**

- matchers.contains\(number\) support [\#102](https://github.com/testdouble/testdouble.js/issues/102)

**Merged pull requests:**

- Fix contains\(\) behavior for arrays [\#104](https://github.com/testdouble/testdouble.js/pull/104) ([searls](https://github.com/searls))
- Add testdouble-timers as plugin to docs [\#101](https://github.com/testdouble/testdouble.js/pull/101) ([kuy](https://github.com/kuy))

## [v1.4.1](https://github.com/testdouble/testdouble.js/tree/v1.4.1) (2016-04-05)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.4.0...v1.4.1)

**Closed issues:**

- Changelog [\#97](https://github.com/testdouble/testdouble.js/issues/97)

**Merged pull requests:**

- Generate a changelog whenever we pubish [\#98](https://github.com/testdouble/testdouble.js/pull/98) ([searls](https://github.com/searls))

## [v1.4.0](https://github.com/testdouble/testdouble.js/tree/v1.4.0) (2016-04-03)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.3.1...v1.4.0)

**Closed issues:**

- Reserved word [\#82](https://github.com/testdouble/testdouble.js/issues/82)
- Warn when users verify an invocation they also stubbed [\#76](https://github.com/testdouble/testdouble.js/issues/76)
- Feature request: captors without verify [\#65](https://github.com/testdouble/testdouble.js/issues/65)

**Merged pull requests:**

- Warn verifications of exact stubbings [\#96](https://github.com/testdouble/testdouble.js/pull/96) ([searls](https://github.com/searls))
- Fixes \#82 [\#95](https://github.com/testdouble/testdouble.js/pull/95) ([searls](https://github.com/searls))

## [v1.3.1](https://github.com/testdouble/testdouble.js/tree/v1.3.1) (2016-04-03)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.3.0...v1.3.1)

**Closed issues:**

- Throws in node 0.10 [\#94](https://github.com/testdouble/testdouble.js/issues/94)
- td.replace\(\) property replacement warning & failure states [\#92](https://github.com/testdouble/testdouble.js/issues/92)
- give users a way to squelch individual warnings [\#90](https://github.com/testdouble/testdouble.js/issues/90)

## [v1.3.0](https://github.com/testdouble/testdouble.js/tree/v1.3.0) (2016-04-03)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.2.0...v1.3.0)

**Closed issues:**

- What's the best way to use testdouble.js with tape? [\#93](https://github.com/testdouble/testdouble.js/issues/93)
- help [\#91](https://github.com/testdouble/testdouble.js/issues/91)
- td.replace\(\) fails for method on prototype [\#86](https://github.com/testdouble/testdouble.js/issues/86)

**Merged pull requests:**

- README: Replace GIFs with code blocks [\#88](https://github.com/testdouble/testdouble.js/pull/88) ([Turbo87](https://github.com/Turbo87))
- replace: Use object\[property\] to check if property exists [\#87](https://github.com/testdouble/testdouble.js/pull/87) ([Turbo87](https://github.com/Turbo87))

## [v1.2.0](https://github.com/testdouble/testdouble.js/tree/v1.2.0) (2016-03-20)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.1.3...v1.2.0)

**Closed issues:**

- Print version in browserify build [\#23](https://github.com/testdouble/testdouble.js/issues/23)

**Merged pull requests:**

- Stringify objects better [\#84](https://github.com/testdouble/testdouble.js/pull/84) ([searls](https://github.com/searls))
- doc: thenDo and thenThrow are no longer unimplemented. [\#83](https://github.com/testdouble/testdouble.js/pull/83) ([verdammelt](https://github.com/verdammelt))
- Refactor time [\#81](https://github.com/testdouble/testdouble.js/pull/81) ([searls](https://github.com/searls))

## [v1.1.3](https://github.com/testdouble/testdouble.js/tree/v1.1.3) (2016-03-16)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.1.1...v1.1.3)

**Closed issues:**

- Quibble in the browser [\#77](https://github.com/testdouble/testdouble.js/issues/77)

**Merged pull requests:**

- Improve support for webpack users [\#80](https://github.com/testdouble/testdouble.js/pull/80) ([searls](https://github.com/searls))

## [v1.1.1](https://github.com/testdouble/testdouble.js/tree/v1.1.1) (2016-03-15)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.1.0...v1.1.1)

**Merged pull requests:**

- Add webpack specific metadata to package.json [\#79](https://github.com/testdouble/testdouble.js/pull/79) ([davemo](https://github.com/davemo))

## [v1.1.0](https://github.com/testdouble/testdouble.js/tree/v1.1.0) (2016-03-11)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v1.0.0...v1.1.0)

**Closed issues:**

- Add a property-namespacing-like replace strategy for browsers. [\#55](https://github.com/testdouble/testdouble.js/issues/55)

**Merged pull requests:**

- td.replace support for object properties \(incl. browsers\) [\#75](https://github.com/testdouble/testdouble.js/pull/75) ([searls](https://github.com/searls))
- td.explain tells you if you passed it a test double [\#74](https://github.com/testdouble/testdouble.js/pull/74) ([searls](https://github.com/searls))

## [v1.0.0](https://github.com/testdouble/testdouble.js/tree/v1.0.0) (2016-03-10)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.10.0...v1.0.0)

**Closed issues:**

- Document `thenDo` and `thenThrow` [\#64](https://github.com/testdouble/testdouble.js/issues/64)

**Merged pull requests:**

- Remove deprecated window.testdouble for 1.0.0 [\#73](https://github.com/testdouble/testdouble.js/pull/73) ([searls](https://github.com/searls))
- add some docs [\#72](https://github.com/testdouble/testdouble.js/pull/72) ([searls](https://github.com/searls))

## [v0.10.0](https://github.com/testdouble/testdouble.js/tree/v0.10.0) (2016-03-09)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.9.0...v0.10.0)

**Merged pull requests:**

- Change window.testdouble to window.td  [\#71](https://github.com/testdouble/testdouble.js/pull/71) ([searls](https://github.com/searls))

## [v0.9.0](https://github.com/testdouble/testdouble.js/tree/v0.9.0) (2016-03-09)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.8.0...v0.9.0)

**Implemented enhancements:**

- Stubbing callbacks [\#66](https://github.com/testdouble/testdouble.js/issues/66)

**Closed issues:**

- Getting testdouble.js to play nicely with Jasmine expectations? [\#41](https://github.com/testdouble/testdouble.js/issues/41)

**Merged pull requests:**

- Implement callback stubbing APIs [\#70](https://github.com/testdouble/testdouble.js/pull/70) ([searls](https://github.com/searls))
- fix typo [\#69](https://github.com/testdouble/testdouble.js/pull/69) ([jzinn](https://github.com/jzinn))
- Reference the completed testdouble-jasmine module [\#67](https://github.com/testdouble/testdouble.js/pull/67) ([BrianGenisio](https://github.com/BrianGenisio))

## [v0.8.0](https://github.com/testdouble/testdouble.js/tree/v0.8.0) (2016-02-06)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.7.3...v0.8.0)

**Closed issues:**

- Add `thenDo` [\#8](https://github.com/testdouble/testdouble.js/issues/8)
- Add `thenThrow` [\#7](https://github.com/testdouble/testdouble.js/issues/7)

## [v0.7.3](https://github.com/testdouble/testdouble.js/tree/v0.7.3) (2015-12-07)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.7.2...v0.7.3)

**Implemented enhancements:**

- td.matchers.contains does not work on sparse object trees [\#58](https://github.com/testdouble/testdouble.js/issues/58)

**Fixed bugs:**

- td.matchers.contains does not work on sparse object trees [\#58](https://github.com/testdouble/testdouble.js/issues/58)

**Merged pull requests:**

- Add headerify [\#62](https://github.com/testdouble/testdouble.js/pull/62) ([searls](https://github.com/searls))
- Rename src and scripts [\#61](https://github.com/testdouble/testdouble.js/pull/61) ([searls](https://github.com/searls))
- Better docs [\#49](https://github.com/testdouble/testdouble.js/pull/49) ([searls](https://github.com/searls))

## [v0.7.2](https://github.com/testdouble/testdouble.js/tree/v0.7.2) (2015-11-25)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.7.1...v0.7.2)

**Fixed bugs:**

- td.matchers.contains blows up on sparse matches [\#56](https://github.com/testdouble/testdouble.js/issues/56)

**Merged pull requests:**

- fixes \#56 [\#57](https://github.com/testdouble/testdouble.js/pull/57) ([searls](https://github.com/searls))
- Swap .replace with browser-specific function [\#52](https://github.com/testdouble/testdouble.js/pull/52) ([jasonkarns](https://github.com/jasonkarns))
- Use svg build badge [\#50](https://github.com/testdouble/testdouble.js/pull/50) ([hanneskaeufler](https://github.com/hanneskaeufler))

## [v0.7.1](https://github.com/testdouble/testdouble.js/tree/v0.7.1) (2015-11-12)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.7.0...v0.7.1)

## [v0.7.0](https://github.com/testdouble/testdouble.js/tree/v0.7.0) (2015-11-12)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.6.0...v0.7.0)

**Closed issues:**

- Is there a way to reset the state of a double? [\#43](https://github.com/testdouble/testdouble.js/issues/43)

**Merged pull requests:**

- Update README.md [\#45](https://github.com/testdouble/testdouble.js/pull/45) ([andrewvida](https://github.com/andrewvida))
- Adding reset\(\) to the Readme.md [\#44](https://github.com/testdouble/testdouble.js/pull/44) ([BrianGenisio](https://github.com/BrianGenisio))

## [v0.6.0](https://github.com/testdouble/testdouble.js/tree/v0.6.0) (2015-10-27)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.5.0...v0.6.0)

**Closed issues:**

- add ES2015 Proxy support  [\#39](https://github.com/testdouble/testdouble.js/issues/39)

**Merged pull requests:**

- Implement ES2015 proxy doubles [\#42](https://github.com/testdouble/testdouble.js/pull/42) ([searls](https://github.com/searls))

## [v0.5.0](https://github.com/testdouble/testdouble.js/tree/v0.5.0) (2015-10-25)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.4.0...v0.5.0)

**Closed issues:**

- Add verify times\(\) [\#5](https://github.com/testdouble/testdouble.js/issues/5)

**Merged pull requests:**

- Add a `times` option [\#40](https://github.com/testdouble/testdouble.js/pull/40) ([searls](https://github.com/searls))

## [v0.4.0](https://github.com/testdouble/testdouble.js/tree/v0.4.0) (2015-10-24)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.3.1...v0.4.0)

**Closed issues:**

- Allow when & verify to disregard arity [\#36](https://github.com/testdouble/testdouble.js/issues/36)
- implement argument captors [\#35](https://github.com/testdouble/testdouble.js/issues/35)

**Merged pull requests:**

- Add an option to ignore additional args [\#38](https://github.com/testdouble/testdouble.js/pull/38) ([searls](https://github.com/searls))
- Arg captors [\#37](https://github.com/testdouble/testdouble.js/pull/37) ([searls](https://github.com/searls))

## [v0.3.1](https://github.com/testdouble/testdouble.js/tree/v0.3.1) (2015-10-24)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.3.0...v0.3.1)

**Fixed bugs:**

- contains\(\) matcher doesn't seem to work on arrays [\#31](https://github.com/testdouble/testdouble.js/issues/31)

**Closed issues:**

- verify does not throw exception when too many arguments are passed [\#33](https://github.com/testdouble/testdouble.js/issues/33)
- Building CoffeeScript at runtime is slow. [\#29](https://github.com/testdouble/testdouble.js/issues/29)

**Merged pull requests:**

- Start checking arity on arg comparisons [\#34](https://github.com/testdouble/testdouble.js/pull/34) ([searls](https://github.com/searls))
- Compile coffeescript [\#30](https://github.com/testdouble/testdouble.js/pull/30) ([jasonkarns](https://github.com/jasonkarns))

## [v0.3.0](https://github.com/testdouble/testdouble.js/tree/v0.3.0) (2015-10-21)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.2.0...v0.3.0)

**Closed issues:**

- When stringifying args, use a testdouble's name if it has one [\#21](https://github.com/testdouble/testdouble.js/issues/21)

**Merged pull requests:**

- Clean up window/global management [\#28](https://github.com/testdouble/testdouble.js/pull/28) ([jasonkarns](https://github.com/jasonkarns))
- clean up package scripts \(primarily version\) [\#27](https://github.com/testdouble/testdouble.js/pull/27) ([jasonkarns](https://github.com/jasonkarns))
- don't watch generated files [\#26](https://github.com/testdouble/testdouble.js/pull/26) ([jasonkarns](https://github.com/jasonkarns))
- Export `version` property on base object [\#25](https://github.com/testdouble/testdouble.js/pull/25) ([jasonkarns](https://github.com/jasonkarns))
- Fixes \#21 [\#24](https://github.com/testdouble/testdouble.js/pull/24) ([searls](https://github.com/searls))

## [v0.2.0](https://github.com/testdouble/testdouble.js/tree/v0.2.0) (2015-09-13)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.1.0...v0.2.0)

**Closed issues:**

- Add a build task that distributes a web version / bower.json / etc [\#10](https://github.com/testdouble/testdouble.js/issues/10)

**Merged pull requests:**

- Browserify testing [\#22](https://github.com/testdouble/testdouble.js/pull/22) ([searls](https://github.com/searls))
- add some more syntax highlighting to README [\#20](https://github.com/testdouble/testdouble.js/pull/20) ([hanneskaeufler](https://github.com/hanneskaeufler))
- Configure Testem [\#19](https://github.com/testdouble/testdouble.js/pull/19) ([jasonkarns](https://github.com/jasonkarns))
- Browserify [\#13](https://github.com/testdouble/testdouble.js/pull/13) ([jasonkarns](https://github.com/jasonkarns))

## [v0.1.0](https://github.com/testdouble/testdouble.js/tree/v0.1.0) (2015-09-09)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/v0.0.5...v0.1.0)

**Closed issues:**

- name a test double with `create\("name"\)` [\#15](https://github.com/testdouble/testdouble.js/issues/15)
- Implement default matchers [\#9](https://github.com/testdouble/testdouble.js/issues/9)
- Add sequential stubbing [\#6](https://github.com/testdouble/testdouble.js/issues/6)
- Implement Prototype for create\(\) [\#2](https://github.com/testdouble/testdouble.js/issues/2)
- Implement argument matchers [\#1](https://github.com/testdouble/testdouble.js/issues/1)

**Merged pull requests:**

- Test prototype-based create\(\) [\#18](https://github.com/testdouble/testdouble.js/pull/18) ([searls](https://github.com/searls))
- Allow naming test doubles for better output [\#17](https://github.com/testdouble/testdouble.js/pull/17) ([searls](https://github.com/searls))
- sequential stubbing [\#16](https://github.com/testdouble/testdouble.js/pull/16) ([searls](https://github.com/searls))
- add more matchers [\#14](https://github.com/testdouble/testdouble.js/pull/14) ([searls](https://github.com/searls))

## [v0.0.5](https://github.com/testdouble/testdouble.js/tree/v0.0.5) (2015-09-08)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/0.0.4...v0.0.5)

**Closed issues:**

- Add `verify\(\)` [\#4](https://github.com/testdouble/testdouble.js/issues/4)

## [0.0.4](https://github.com/testdouble/testdouble.js/tree/0.0.4) (2015-09-08)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/0.0.3...0.0.4)

## [0.0.3](https://github.com/testdouble/testdouble.js/tree/0.0.3) (2015-09-08)
[Full Changelog](https://github.com/testdouble/testdouble.js/compare/0.0.2...0.0.3)

**Closed issues:**

- Add a `require\('testdouble'\).explain` function [\#12](https://github.com/testdouble/testdouble.js/issues/12)
- Ensure last stubbing wins [\#11](https://github.com/testdouble/testdouble.js/issues/11)

## [0.0.2](https://github.com/testdouble/testdouble.js/tree/0.0.2) (2015-09-07)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*