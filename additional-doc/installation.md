# Installation

To use `@dilhelh/ngx-remote-desktop` in your project install it via npm:

```
npm i @dilhelh/ngx-remote-desktop --save
```

We also require two peer dependencies:

```
npm i @langazov/guacamole-common-js --save
npm i screenfull --save
```

After installing, include `NgxRemoteDesktopModule` in your application module like this:

```typescript
import { NgModule } from '@angular/core';
import { BrowserModule } from '@angular/platform-browser';
import { NgxRemoteDesktopModule } from '@dilhelh/ngx-remote-desktop';
import { AppComponent } from './app.component';

@NgModule({
  declarations: [AppComponent],
  imports: [NgxRemoteDesktopModule, BrowserModule],
  bootstrap: [AppComponent]
})
export class AppModule { }
```