## What's new in Angular 8?

# Angular Ivy: Next generation compilation and rendering pipeline (opt-in option in Angular 8)
- smaller build artifacts (lower load time)
- rebuild time is faster 
- better template checking
- for example, for Hello world app, in Angular 7, it generates 36Kb bundle, Ivy Minified is 7.3Kb and Ivy Compressed is 2.7Kb
- all of these are under the hood, from developers point of view, everything is the same

# Differential Loading
- when angular build, it generate 2 separate bundles, one for older browsers, one for modern browsers
- older browsers which doesn't support ES2015, will download larger bundle (ES5 bundles). Modern browsers will download ES2015 bundles which is smaller

## What's new in Angular 9?
- Typescript 3.7
  - Optional Chaining: https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-7.html
  - Nullish Coalescing: https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-7.html#nullish-coalescing
- Ivy become default, (you can opt out)

## What's new in Angular 10?
- not much...