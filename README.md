# About

@ngx-tc/form-description is an Angular library that provides a UI component for displaying concise information about form fields. This library allows developers to easily add field descriptions to their forms, improving usability and accessibility for end-users. It is built on Angular and is designed to be lightweight, easy to use, and highly customizable.

## Usage

Install `@ngx-tc/form-description` in your project:

```
npm install @ngx-tc/form-description
```

Import `TcFormDescriptionModule` e.g. in your `app.module.ts`:
```typescript
import { TcFormDescriptionModule } from '@ngx-tc/form-description';

@NgModule({
  imports: [
    ...
    TcFormDescriptionModule
  ],
})
export class AppModule {}
```

Use the `tc-form-description` component in you app:
```html
<tc-form-description>
  Form control description
</tc-form-description>
```

## Demo
To view a working demo of the library in action, please follow the provided link. The demo will allow you to explore the various components and features included in this library and see how they can be used in your Angular applications.
[http://tc-library.type-code.pro/#/components/inputs](http://tc-library.type-code.pro/#/components/inputs)
