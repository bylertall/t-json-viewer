# 


# Angular 2 JSON Viewer Component `t-json-viewer` v1.2.0

Angular 2 component for objects debug. Collapsible JSON in HTML with syntax highlight like Chrome DevTools http://temich.in.ua/t-json-viewer/

## Install

```
npm install t-json-viewer --save
```
NPM Package: https://www.npmjs.com/package/t-json-viewer

## Usage

Import TJsonViewerModule to have access to following component
```js
import {TJsonViewerModule} from 't-json-viewer';

@NgModule({
    ...,
    imports: [
        ...,
        TJsonViewerModule,
        ...
    ],
    ...
})
export class AppModule { }
```

### Component

 Takes an input `[json]` that can be data bound to any object.

```js

@Component({
  ...,
  template: `
    <t-json-viewer [json]="asset"></t-json-viewer>
  `
  })
  export class MyComponent {
    ...
    ngOnInit() {
      this.asset = {};
      ...
    }
    ...
  }
```
## Examples
Example: [http://temich.in.ua/t-json-viewer/](http://temich.in.ua/t-json-viewer/)
Example source: [https://github.com/temich666/t-json-viewer-example](https://github.com/temich666/t-json-viewer-example)


### Outputs
![Angular 2 Pretty JSON with syntax highlight](http://temich.in.ua/-i/t-json-viewer.png)


