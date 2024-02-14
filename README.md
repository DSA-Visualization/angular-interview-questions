# Angular Interview Questions & Answers

> Click :star:if you like the project and follow [@Raj-rathod](https://github.com/raj-rathod) for technical updates. 

---

<p align="center">
  <a href="https://raj-rathod.github.io/DSA-visualisation-in-angular/">
    <img src="https://github.com/raj-rathod/DSA-visualisation-in-angular/blob/main/src/assets/icons/dsa-logo.png" alt="DSA Logo">
  </a>
</p>

---

### Table of Contents

| No. | Questions |
|---- | ---------
|1 | [What is Angular Framework?](#what-is-angular-framework)|
|2 | [What is the difference between AngularJS and Angular?](#what-is-the-difference-between-angularjs-and-angular)|
|3 | [What is TypeScript?](#what-is-typescript)|
|4 | [Write a pictorial diagram of Angular architecture?](#write-a-pictorial-diagram-of-angular-architecture)|
|5 | [What are the key components of Angular?](#what-are-the-key-components-of-angular)|
|6 | [What are directives?](#what-are-directives)|
|7 | [What are components?](#what-are-components)|
|8 | [What are the differences between Component and Directive?](#what-are-the-differences-between-component-and-directive)|
|9 | [What is a template?](#what-is-a-template)|
|10| [What is a module?](#what-is-a-module)|
|11| [What are lifecycle hooks available?](#what-are-lifecycle-hooks-available)|
|12| [What is a data binding?](#what-is-a-data-binding)|
|13| [What is metadata?](#what-is-metadata)|
|14| [What is Angular CLI?](#what-is-angular-cli)|
|15| [What is the difference between constructor and ngOnInit?](#what-is-the-difference-between-constructor-and-ngoninit)|
|16| [What is a service](#what-is-a-service)|
|17| [What is dependency injection in Angular?](#what-is-dependency-injection-in-angular)|
|18| [How is Dependency Hierarchy formed?](#how-is-dependency-hierarchy-formed)|
|19| [What is the purpose of async pipe?](#what-is-the-purpose-of-async-pipe)|
|20| [What is the option to choose between inline and external template file?](#what-is-the-option-to-choose-between-inline-and-external-template-file)|
|21| [What happens if you use script tag inside template?](#what-happens-if-you-use-script-tag-inside-template)|
|22| [What is interpolation?](#what-is-interpolation)|
|23| [What are template expressions?](#what-are-template-expressions)|
|24| [What are template statements?](#what-are-template-statements)|
|25| [How do you categorize data binding types?](#how-do-you-categorize-data-binding-types)|
|26| [What are pipes?](#what-are-pipes)|
|27| [What is a parameterized pipe?](#what-is-a-parameterized-pipe)|
|28| [How do you chain pipes?](#how-do-you-chain-pipes)|
|29| [What is a custom pipe?](#what-is-a-custom-pipe)|
|30| [What is the difference between pure and impure pipe?](#what-is-the-difference-between-pure-and-impure-pipe)|
|31| [What is a bootstrapping module?](#what-is-a-bootstrapping-module)|
|32| [What is HttpClient and its benefits?](#what-is-httpclient-and-its-benefits)|
|33| [Explain on how to use HttpClient with an example?](#explain-on-how-to-use-httpclient-with-an-example)|
|34| [How can you read full response?](#how-can-you-read-full-response)|
|35| [How do you perform Error handling?](#how-do-you-perform-error-handling)|
|36| [What is RxJS?](#what-is-rxjs)|
|37| [What is subscribing?](#what-is-subscribing)|
|38| [What is an observable?](#what-is-an-observable)|
|39| [What is an observer?](#what-is-an-observer)|
|40| [What is the difference between promise and observable?](#what-is-the-difference-between-promise-and-observable)|
|41| [What is multicasting?](#what-is-multicasting)|
|42| [How do you perform error handling in observables?](#how-do-you-perform-error-handling-in-observables)|
|43| [What is the shorthand notation for subscribe method?](#what-is-the-shorthand-notation-for-subscribe-method)|
|44| [What are the utility functions provided by RxJS?](#what-are-the-utility-functions-provided-by-rxjs)|
|45| [What are observable creation functions?](#what-are-observable-creation-functions)|
|46| [What will happen if you do not supply handler for the observer?](#what-will-happen-if-you-do-not-supply-handler-for-the-observer)|
|47| [What are Angular elements?](#what-are-angular-elements)|
|48| [What is the browser support of Angular Elements?](#what-is-the-browser-support-of-angular-elements)|
|49| [What are custom elements?](#what-are-custom-elements)|
|50| [Do I need to bootstrap custom elements?](#do-i-need-to-bootstrap-custom-elements)|
|51| [Explain how custom elements works internally?](#explain-how-custom-elements-works-internally)|
|52| [How to transfer components to custom elements?](#how-to-transfer-components-to-custom-elements)|
|53| [What are the mapping rules between Angular component and custom element?](#what-are-the-mapping-rules-between-angular-component-and-custom-element)|
|54| [How do you define typings for custom elements?](#how-do-you-define-typings-for-custom-elements)|
|55| [What are dynamic components?](#what-are-dynamic-components)|
|56| [What are the various kinds of directives?](#what-are-the-various-kinds-of-directives)|
|57| [How do you create directives using CLI?](#how-do-you-create-directives-using-cli)|
|58| [Give an example for attribute directives?](#give-an-example-for-attribute-directives)|
|59| [What is Angular Router?](#what-is-angular-router)|
|60| [What is the purpose of base href tag?](#what-is-the-purpose-of-base-href-tag)|
|61| [What are the router imports?](#what-are-the-router-imports)|
|62| [What is router outlet?](#what-is-router-outlet)|
|63| [What are router links?](#what-are-router-links)|
|64| [What are active router links?](#what-are-active-router-links)|
|65| [What is router state?](#what-is-router-state)|
|66| [What are router events?](#what-are-router-events)|
|67| [What is activated route?](#what-is-activated-route)|
|68| [How do you define routes?](#how-do-you-define-routes)|
|69| [What is the purpose of Wildcard route?](#what-is-the-purpose-of-wildcard-route)|
|70| [Do I need a Routing Module always?](#do-i-need-a-routing-module-always)|
|71| [What is Angular Universal?](#what-is-angular-universal)|
|72| [What are different types of compilation in Angular?](#what-are-different-types-of-compilation-in-angular)|
|73| [What is JIT?](#what-is-jit)|
|74| [What is AOT?](#what-is-aot)|
|75| [Why do we need compilation process?](#why-do-we-need-compilation-process)|
|76| [What are the advantages with AOT?](#what-are-the-advantages-with-aot)|
|77| [What is folding?](#what-is-folding)|
|78| [What are macros?](#what-are-macros)|
|79| [What is Non null type assertion operator?](#what-is-non-null-type-assertion-operator)|
|80| [What is type narrowing?](#what-is-type-narrowing)|
|81| [What is zone?](#what-is-zone)|
|82| [What is angular animation?](#what-is-angular-animation)|
|83| [What are the steps to use animation module?](#what-are-the-steps-to-use-animation-module)|
|84| [What is State function?](#what-is-state-function)|
|85| [What is Style function?](#what-is-style-function)|
|86| [What is the purpose of animate function?](#what-is-the-purpose-of-animate-function)|
|87| [What is transition function?](#what-is-transition-function)|
|88| [What is Angular Ivy?](#what-is-angular-ivy)|
|89| [What are the features included in ivy preview?](#what-are-the-features-included-in-ivy-preview)|
|90| [Can I use AOT compilation with Ivy?](#can-i-use-aot-compilation-with-ivy)|
|91| [What are the class decorators in Angular?](#what-are-the-class-decorators-in-angular)|
|92| [What are class field decorators?](#what-are-class-field-decorators)|
|93| [What is declarable in Angular?](#what-is-declarable-in-angular)|
|94| [What are the restrictions on declarable classes?](#what-are-the-restrictions-on-declarable-classes)|
|95| [What is a DI token?](#what-is-a-di-token)|
|96| [What is Angular DSL?](#what-is-angular-dsl)|
|97| [What is platform in Angular?](#what-is-platform-in-angular)|
|98| [What happens if I import the same module twice?](#what-happens-if-i-import-the-same-module-twice)|
|99| [How do you select an element with in a component template?](#how-do-you-select-an-element-with-in-a-component-template)|
|100| [How do you detect route change in Angular?](#how-do-you-detect-route-change-in-angular)|
|101| [What is lazy loading?](#what-is-lazy-loading)|
|102| [What is Angular Material?](#what-is-angular-material)|
|102| [How do you test Angular application using CLI?](#how-do-you-test-angular-application-using-cli)|
|104| [How to use polyfills in Angular application?](#how-to-use-polyfills-in-angular-application)|
|105| [What are the ways to trigger change detection in Angular?](#what-are-the-ways-to-trigger-change-detection-in-angular)|
|106| [What are the security principles in angular?](#what-are-the-security-principles-in-angular)|
|107| [What are the best practices for security in angular?](#what-are-the-best-practices-for-security-in-angular)|
|108| [What is Angular security model for preventing XSS attacks?](#what-is-angular-security-model-for-preventing-xss-attacks)|
|109| [What is the role of template compiler for prevention of XSS attacks?](#what-is-the-role-of-template-compiler-for-prevention-of-xss-attacks)|
|110| [What are the various security contexts in Angular?](#what-are-the-various-security-contexts-in-Angular)|
|111| [What is Sanitization? Is angular supports it?](#what-is-sanitization?Is-angular-supports-it)|
|112| [What is the purpose of innerHTML?](#what-is-the-purpose-of-innerhtml)|
|113| [What is the difference between interpolated content and innerHTML?](#what-is-the-difference-between-interpolated-content-and-innerhtml)|
|114| [How do you prevent automatic sanitization?](#how-do-you-prevent-automatic-sanitization)|
|115| [Is safe to use direct DOM API methods in terms of security?](#is-safe-to-use-direct-dom-api-methods-in-terms-of-security)|
|116| [What is DOM sanitizer?](#what-is-dom-sanitizer)|
|117| [How do you support server side XSS protection in Angular application?](#how-do-you-support-server-side-xss-protection-in-angular-application)
|118| [Is angular prevents http level vulnerabilities?](#is-angular-prevents-http-level-vulnerabilities)|
|119| [What are Http Interceptors?](#what-are-http-interceptors)|
|120| [What are the applications of HTTP interceptors?](#what-are-the-applications-of-http-interceptors)|
|121| [Is multiple interceptors supported in Angular?](#is-multiple-interceptors-supported-in-angular)|
|122| [How can I use interceptor for an entire application?](#how-can-i-use-interceptor-for-an-entire-application)|
|123| [How does Angular simplifies Internationalization?](#how-does-angular-simplifies-internationalization)|
|124| [How do you manually register locale data?](#how-do-you-manually-register-locale-data)|
|125| [What is the purpose of hidden property?](#what-is-the-purpose-of-hidden-property)|
|126| [What is the difference between ngIf and hidden property?](#what-is-the-difference-between-ngif-and-hidden-property)|
|127| [What is slice pipe?](#what-is-slice-pipe)|
|128| [What is index property in ngFor directive?](#what-is-index-property-in-ngfor-directive)|
|129| [What is the purpose of ngFor trackBy?](#what-is-the-purpose-of-ngfor-trackby)|
|130| [What is the purpose of ngSwitch directive?](#what-is-the-purpose-of-ngswitch-directive)|
|131| [Is it possible to do aliasing for inputs and outputs?](#is-it-possible-to-do-aliasing-for-inputs-and-outputs)|
|132| [What is safe navigation operator?](#what-is-safe-navigation-operator)|
|133| [What are the list of template expression operators?](#what-are-the-list-of-template-expression-operators)
|134| [What is the precedence between pipe and ternary operators?](#what-is-the-precedence-between-pipe-and-ternary-operators)
|135| [What is an entry component?](#what-is-an-entry-component)|
|136| [What is a bootstrapped component?](#what-is-a-bootstrapped-component)|
|137| [How do you manually bootstrap an application?](#how-do-you-manually-bootstrap-an-application)|
|138| [Is it necessary for bootstrapped component to be entry component?](#is-it-necessary-for-bootstrapped-component-to-be-entry-component)|
|139| [What is a routed entry component?](#what-is-a-routed-entry-component#)|
|140| [Why is not necessary to use entryComponents array every time?](#why-is-not-necessary-to-use-entrycomponents-array-every-time)|
|141| [Do I still need to use entryComponents array in Angular9?](do-i-still-need-to-use-entrycomponents-array-in-angular9#)|
|142| [Is it all components generated in production build?](#is-it-all-components-generated-in-production-build)|
|143| [What is Angular compiler?](#what-is-angular-compiler)|
|144| [What is the role of ngModule metadata in compilation process?](#what-is-the-role-of-ngmodule-metadata-in-compilation-process)|
|145| [How does angular finds components, directives and pipes?](#how-does-angular-finds-components-directives-and-pipes)|
|146| [What are feature modules?](#what-are-feature-modules)|
|147| [What are the imported modules in CLI generated feature modules?](#what-are-the-imported-modules-in-cli-generated-feature-modules)|
|148| [What are the possible errors with declarations?](#what-are-the-possible-errors-with-declarations)|
|149| [What are the steps to use declaration elements?](#what-are-the-steps-to-use-declaration-elements)|
|150| [What happens if browserModule used in feature module?](#what-happens-if-browsermodule-used-in-feature-module)|
|151| [What are the types of feature modules?](#what-are-the-types-of-feature-modules)|
|152| [What is a provider?](#what-is-a-provider)|
|153| [What is the recommendation for provider scope?](#what-is-the-recommendation-for-provider-scope#)|
|154| [How do you restrict provider scope to a module?](#how-do-you-restrict-provider-scope-to-a-module)|
|155| [How do you provide a singleton service?](#how-do-you-provide-a-singleton-service)|
|156| [What are the different ways to remove duplicate service registration?](#what-are-the-different-ways-to-remove-duplicate-service-registration)|
|157| [How does forRoot method helpful to avoid duplicate router instances?](#how-does-forroot-method-helpful-to-avoid-duplicate-router-instances)|
|158| [What is a shared module?](#what-is-a-shared-module)|
|159| [Can I share services using modules?](#can-i-share-services-using-modules)|
|160| [How do you get current direction for locales??](#how-do-you-get-current-direction-for-locales)|
|161| [What is ngcc?](#what-is-ngcc)|
|162| [What classes should not be added to declarations?](#what-classes-should-not-be-added-to-declarations)|
|163| [What is ngzone?](#what-is-ngzone)|
|164| [What is NoopZone?](#what-is-noopzone)|
|165| [How do you create displayBlock components?](#how-do-you-create-displayblock-components)|
|166| [What are the possible data change scenarios for change detection?](#what-are-the-possible-data-change-scenarios-for-change-detection)|
|167| [Which are the methods of NgZone used to control change detection?](#which-are-the-methods-of-ngzone-used-to-control-change-detection)|
|168| [How do you change the settings of zonejs?](#how-do-you-change-the-settings-of-zonejs)|
|169| [How do you trigger an animation?](#how-do-you-trigger-an-animation)|
|170| [How do you configure injectors with providers at different levels?](#how-do-you-configure-injectors-with-providers-at-different-levels)|
|171| [Is it mandatory to use injectable on every service class?](#is-it-mandatory-to-use-injectable-on-every-service-class)|
|172| [What is an optional dependency?](#what-is-an-optional-dependency)|
|173| [What are the types of injector hierarchies?](#what-are-the-types-of-injector-hierarchies)|
|174| [What are reactive forms?](#what-are-reactive-forms)|
|175| [What are dynamic forms?](#what-are-dynamic-forms)|
|176| [What are template driven forms?](#what-are-template-driven-forms)|
|177| [What are the differences between reactive forms and template driven forms?](#what-are-the-differences-between-reactive-forms-and-template-driven-forms)|
|178| [What is the purpose of FormBuilder?](#what-is-the-purpose-of-formbuilder)|
|179| [What are the state CSS classes provided by ngModel?](#what-are-the-state-css-classes-provided-by-ngmodel)|
|180| [How do you reset the form?](#how-do-you-reset-the-form)|
|181| [What are the types of validator functions?](#what-are-the-types-of-validator-functions)|
|182| [Can you give an example of built-in validators?](#can-you-give-an-example-of-built-in-validators)|
|183| [How do you optimize the performance of async validators?](#how-do-you-optimize-the-performance-of-async-validators)|
|184| [How to set ngFor and ngIf on the same element?](#how-to-set-ngfor-and-ngif-on-the-same-element)|
|185| [What is host property in css?](#what-is-host-property-in-css)|
|186| [How do you get the current route?](#how-do-you-get-the-current-route)|
|187| [What is Component Test Harnesses?](#what-is-component-test-harnesses)|
|189| [What is the benefit of Automatic Inlining of Fonts?](#what-is-the-benefit-of-automatic-inlining-of-fonts)|
|190| [What is content projection?](#what-is-content-projection)|
|191| [What is ng-content and its purpose?](#what-is-ng-content-and-its-purpose)|
|192| [What is standalone component?](#what-is-standalone-component)|
|193| [How to create a standalone component uing CLI command?](#how-to-create-a-standalone-component-uing-cli-command)
|194| [How to create a standalone component manually?](#how-to-create-a-standalone-component-manually)
|195| [What is hydration ?](#what-is-hydration)

1. ### What is Angular Framework?

    Angular is a **TypeScript-based open-source** front-end platform that makes it easy to build web, mobile and desktop applications. The major features of this framework include declarative templates, dependency injection, end to end tooling which ease application development.

  **[⬆ Back to Top](#table-of-contents)**

2. ### What is the difference between AngularJS and Angular?
    Angular is a completely revived component-based framework in which an application is a tree of individual components.

    Here are some of the major differences in tabular format:-

    | AngularJS | Angular |
    |---- | ---------
    | It is based on MVC architecture| This is based on Service/Controller|
    | It uses JavaScript to build the application| Uses TypeScript to build the application|
    | Based on controllers concept| This is a component based UI approach|
    | No support for mobile platforms| Fully supports mobile platforms|
    | Difficult to build SEO friendly application| Ease to build SEO friendly applications|

  **[⬆ Back to Top](#table-of-contents)**

3. ### What is TypeScript?
    TypeScript is a strongly typed superset of JavaScript created by Microsoft that adds optional types, classes, async/await and many other features, and compiles to plain JavaScript. Angular is written entirely in TypeScript as a primary language.
    You can install TypeScript globally as
    ```cmd
    npm install -g typescript
    ```
    Let's see a simple example of TypeScript usage:-
    ```typescript
    function greeter(person: string) {
        return "Hello, " + person;
    }

    let user = "Sudheer";

    document.body.innerHTML = greeter(user);
    ```
    The greeter method allows only string type as argument.

  **[⬆ Back to Top](#table-of-contents)**

4. ### Write a pictorial diagram of Angular architecture?
    The main building blocks of an Angular application are shown in the diagram below:-
    ![ScreenShot](images/architecture.png)

  **[⬆ Back to Top](#table-of-contents)**

5. ### What are the key components of Angular?
    Angular has the key components below,
    1. **Component:** These are the basic building blocks of an Angular application to control HTML views.
    2. **Modules:** An Angular module is a set of angular basic building blocks like components, directives, services etc. An application is divided into logical pieces and each piece of code is called as "module" which perform a single task.
    3. **Templates:** These represent the views of an Angular application.
    4. **Services:** Are used to create components which can be shared across the entire application.
    5. **Metadata:** This can be used to add more data to an Angular class.

  **[⬆ Back to Top](#table-of-contents)**

6. ### What are directives?
    Directives add behaviour to an existing DOM element or an existing component instance.
    ```typescript
    import { Directive, ElementRef, Input } from '@angular/core';

    @Directive({ selector: '[myHighlight]' })
    export class HighlightDirective {
        constructor(el: ElementRef) {
           el.nativeElement.style.backgroundColor = 'yellow';
        }
    }
    ```

    Now this directive extends HTML element behavior with a yellow background as below
    ```html
    <p myHighlight>Highlight me!</p>
    ```
  **[⬆ Back to Top](#table-of-contents)**

7. ### What are components?
    Components are the most basic UI building block of an Angular app, which form a tree of Angular components. These components are a subset of directives. Unlike directives, components always have a template, and only one component can be instantiated per element in a template.
    Let's see a simple example of Angular component
    ```typescript
    import { Component } from '@angular/core';

    @Component ({
       selector: 'my-app',
       template: ` <div>
          <h1>{{title}}</h1>
          <div>Learn Angular6 with examples</div>
       </div> `,
    })

    export class AppComponent {
       title: string = 'Welcome to Angular world';
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

8. ### What are the differences between Component and Directive?
    In a short note, A component(@component) is a directive-with-a-template.

    Some of the major differences are mentioned in a tabular form

    | Component | Directive |
    |---- | ---------
    | To register a component we use @Component meta-data annotation  | To register a directive we use @Directive meta-data annotation |
    | Components are typically used to create UI widgets| Directives are used to add behavior to an existing DOM element |
    | Component is used to break down the application into smaller components| Directive is used to design re-usable components|
    | Only one component can be present per DOM element | Many directives can be used per DOM element |
    | @View decorator or templateurl/template are mandatory | Directive doesn't use View|

  **[⬆ Back to Top](#table-of-contents)**

9. ### What is a template?
    A template is a HTML view where you can display data by binding controls to properties of an Angular component. You can store your component's template in one of two places. You can define it inline using the template property, or you can define the template in a separate HTML file and link to it in the component metadata using the @Component decorator's templateUrl property.

    **Using inline template with template syntax,**
    ```typescript
    import { Component } from '@angular/core';

    @Component ({
       selector: 'my-app',
       template: '
          <div>
             <h1>{{title}}</h1>
             <div>Learn Angular</div>
          </div>
       '
    })

    export class AppComponent {
       title: string = 'Hello World';
    }
    ```
    **Using separate template file such as app.component.html**
    ```typescript
    import { Component } from '@angular/core';

    @Component ({
       selector: 'my-app',
       templateUrl: 'app/app.component.html'
    })

    export class AppComponent {
       title: string = 'Hello World';
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

10. ### What is a module?

    Modules are logical boundaries in your application and the application is divided into separate modules to separate the functionality of your application.
    Lets take an example of **app.module.ts** root module declared with **@NgModule** decorator as below,
    ```typescript
    import { NgModule }      from '@angular/core';
    import { BrowserModule } from '@angular/platform-browser';
    import { AppComponent }  from './app.component';

    @NgModule ({
       imports:      [ BrowserModule ],
       declarations: [ AppComponent ],
       bootstrap:    [ AppComponent ],
       providers: []
    })
    export class AppModule { }
    ```
    The NgModule decorator has five important (among all) options:
    1. The imports option is used to import other dependent modules. The BrowserModule is required by default for any web based angular application.
    2. The declarations option is used to define components in the respective module.
    3. The bootstrap option tells Angular which Component to bootstrap in the application.
    4. The providers option is used to configure a set of injectable objects that are available in the injector of this module.
    5. The entryComponents option is a set of components dynamically loaded into the view.

  **[⬆ Back to Top](#table-of-contents)**

11. ### What are lifecycle hooks available?
    Angular application goes through an entire set of processes or has a lifecycle right from its initiation to the end of the application.
    The representation of lifecycle in pictorial representation as follows,

    ![ScreenShot](images/lifecycle.png)

    The description of each lifecycle method is as below,
    1. **ngOnChanges:** When the value of a data bound property changes, then this method is called.
    2. **ngOnInit:** This is called whenever the initialization of the directive/component after Angular first displays the data-bound properties happens.
    3. **ngDoCheck:** This is for the detection and to act on changes that Angular can't or won't detect on its own.
    4. **ngAfterContentInit:** This is called in response after Angular projects external content into the component's view.
    5. **ngAfterContentChecked:** This is called in response after Angular checks the content projected into the component.
    6. **ngAfterViewInit:** This is called in response after Angular initializes the component's views and child views.
    7. **ngAfterViewChecked:** This is called in response after Angular checks the component's views and child views.
    8. **ngOnDestroy:** This is the cleanup phase just before Angular destroys the directive/component.

  **[⬆ Back to Top](#table-of-contents)**

12. ### What is a data binding?
    Data binding is a core concept in Angular and allows to define communication between a component and the DOM, making it very easy to define interactive applications without worrying about pushing and pulling data. There are four forms of data binding(divided as 3 categories) which differ in the way the data is flowing.
    1. **From the Component to the DOM:**

        **Interpolation:** {{ value }}: Adds the value of a property from the component
        ```html
        <li>Name: {{ user.name }}</li>
        <li>Address: {{ user.address }}</li>
        ```
        **Property binding:** [property]=”value”: The value is passed from the component to the specified property or simple HTML attribute
        ```html
        <input type="email" [value]="user.email">
        ```
    2. **From the DOM to the Component:**
        **Event binding: (event)=”function”:** When a specific DOM event happens (eg.: click, change, keyup), call the specified method in the component
        ```html
        <button (click)="logout()"></button>
        ```
    3. **Two-way binding:**
        **Two-way data binding:** [(ngModel)]=”value”: Two-way data binding allows to have the data flow both ways. For example, in the below code snippet, both the email DOM input and component email property are in sync
        ```html
        <input type="email" [(ngModel)]="user.email">
        ```

  **[⬆ Back to Top](#table-of-contents)**

13. ### What is metadata?
    Metadata is used to decorate a class so that it can configure the expected behavior of the class. The metadata is represented by decorators
    1. **Class decorators**, e.g. @Component and @NgModule
        ```typescript
        import { NgModule, Component } from '@angular/core';

        @Component({
          selector: 'my-component',
          template: '<div>Class decorator</div>',
        })
        export class MyComponent {
          constructor() {
            console.log('Hey I am a component!');
          }
        }

        @NgModule({
          imports: [],
          declarations: [],
        })
        export class MyModule {
          constructor() {
            console.log('Hey I am a module!');
          }
        }
        ```
    2. **Property decorators** Used for properties inside classes, e.g. @Input and @Output
        ```typescript
        import { Component, Input } from '@angular/core';

        @Component({
            selector: 'my-component',
            template: '<div>Property decorator</div>'
        })

        export class MyComponent {
            @Input()
            title: string;
        }
        ```
    3. **Method decorators** Used for methods inside classes, e.g. @HostListener
        ```typescript
        import { Component, HostListener } from '@angular/core';

        @Component({
            selector: 'my-component',
            template: '<div>Method decorator</div>'
        })
        export class MyComponent {
            @HostListener('click', ['$event'])
            onHostClick(event: Event) {
                // clicked, `event` available
            }
        }
        ```
    4. **Parameter decorators** Used for parameters inside class constructors, e.g. @Inject, @Optional
        ```typescript
        import { Component, Inject } from '@angular/core';
        import { MyService } from './my-service';

        @Component({
            selector: 'my-component',
            template: '<div>Parameter decorator</div>'
        })
        export class MyComponent {
            constructor(@Inject(MyService) myService) {
                console.log(myService); // MyService
            }
        }
        ```
  **[⬆ Back to Top](#table-of-contents)**

14. ### What is angular CLI?
    Angular CLI(**Command Line Interface**) is a command line interface to scaffold and build angular apps using nodejs style (commonJs) modules.
    You need to install using below npm command,
    ```
    npm install @angular/cli@latest
    ```
    Below are the list of few commands, which will come handy while creating angular projects
    1. **Creating New Project:** ng new <project-name>

    2. **Generating Components, Directives & Services:** ng generate/g <feature-name>
        The different types of commands would be,
        * ng generate class my-new-class: add a class to your application
        * ng generate component my-new-component: add a component to your application
        * ng generate directive my-new-directive: add a directive to your application
        * ng generate enum my-new-enum: add an enum to your application
        * ng generate module my-new-module: add a module to your application
        * ng generate pipe my-new-pipe: add a pipe to your application
        * ng generate service my-new-service: add a service to your application

    3. **Running the Project:** ng serve

  **[⬆ Back to Top](#table-of-contents)**

15. ### What is the difference between constructor and ngOnInit?
    The **Constructor** is a default method of the class that is executed when the class is instantiated and ensures proper initialisation of fields in the class and its subclasses. Angular, or better Dependency Injector (DI), analyses the constructor parameters and when it creates a new instance by calling new MyClass() it tries to find providers that match the types of the constructor parameters, resolves them and passes them to the constructor.  
    **ngOnInit** is a life cycle hook called by Angular to indicate that Angular is done creating the component.  
    Mostly we use ngOnInit for all the initialization/declaration and avoid stuff to work in the constructor. The constructor should only be used to initialize class members but shouldn't do actual "work".
    So you should use constructor() to setup Dependency Injection and not much else. ngOnInit() is better place to "start" - it's where/when components' bindings are resolved.

    ```typescript
    export class App implements OnInit{
      constructor(private myService: MyService){
         //called first time before the ngOnInit()
      }

      ngOnInit(){
         //called after the constructor and called  after the first ngOnChanges()
         //e.g. http call...
      }
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

16. ### What is a service?
    A service is used when a common functionality needs to be provided to various modules. Services allow for greater separation of concerns for your application and better modularity by allowing you to extract common functionality out of components.

    Let's create a repoService which can be used across components,

    ```typescript
    import { Injectable } from '@angular/core';
    import { Http } from '@angular/http';

    @Injectable({ // The Injectable decorator is required for dependency injection to work
      // providedIn option registers the service with a specific NgModule
      providedIn: 'root',  // This declares the service with the root app (AppModule)
    })
    export class RepoService{
      constructor(private http: Http){
      }

      fetchAll(){
        return this.http.get('https://api.github.com/repositories');
      }
    }
    ```
    The above service uses Http service as a dependency.

  **[⬆ Back to Top](#table-of-contents)**

17. ### What is dependency injection in Angular?
    Dependency injection (DI), is an important application design pattern in which a class asks for dependencies from external sources rather than creating them itself. Angular comes with its own dependency injection framework for resolving dependencies( services or objects that a class needs to perform its function).So you can have your services depend on other services throughout your application.

  **[⬆ Back to Top](#table-of-contents)**

18. ### How is Dependency Hierarchy formed?
    Injectors in Angular have rules that can be leveraged to achieve the desired visibility of injectables in your applications. By understanding these rules, you can determine in which NgModule, Component, or Directive you should declare a provider.

    #### Angular has two injector hierarchies:
    ![Screenshot](/images/injector%20hierarchies.png)

    #### Module injector 
    When angular starts, it creates a root injector where the services will be registered, these are provided via injectable annotation. All services provided in the `ng-model` property are called providers (if those modules are not lazy-loaded).

    Angular recursively goes through all models which are being used in the application and creates instances for provided services in the root injector. If you provide some service in an eagerly-loaded model, the service will be added to the root injector, which makes it available across the whole application.

    #### Platform Module
    During application bootstrapping angular creates a few more injectors, above the root injector goes the platform injector, this one is created by the platform browser dynamic function inside the `main.ts` file, and it provides some platform-specific features like `DomSanitizer`. 

    #### NullInjector()
    At the very top, the next parent injector in the hierarchy is the `NullInjector()`.The responsibility of this injector is to throw the error if something tries to find dependencies there, unless you've used `@Optional()` because ultimately, everything ends at the `NullInjector()` and it returns an error or, in the case of `@Optional()`, `null`.

    ![Screenshot](images/hierarchy%20diagram.png)


    #### ElementInjector
    Angular creates `ElementInjector` hierarchies implicitly for each DOM element. `ElementInjector` injector is being created for any tag that matches the angular component, or any tag on which directive is applied, and you can configure it in component and directive annotations inside the provider's property, thus, it creates its own hierarchy likewise the upper one.

    ![Screenshot](images/element%20injector%20hieracrhy.png)

  **[⬆ Back to Top](#table-of-contents)**

19. ### What is the purpose of async pipe?
    The AsyncPipe subscribes to an observable or promise and returns the latest value it has emitted. When a new value is emitted, the pipe marks the component to be checked for changes.

    Let's take a time observable which continuously updates the view for every 2 seconds with the current time.
    ```typescript
    @Component({
      selector: 'async-observable-pipe',
      template: `<div><code>observable|async</code>:
           Time: {{ time | async }}</div>`
    })
    export class AsyncObservablePipeComponent {
      time: Observable<string>;
      constructor() {
        this.time = new Observable((observer) => {
          setInterval(() => {
            observer.next(new Date().toString());
          }, 2000);
        });
      }
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

20. ### What is the option to choose between inline and external template file?
    You can store your component's template in one of two places. You can define it inline using the **template** property, or you can define the template in a separate HTML file and link to it in the component metadata using the **@Component** decorator's **templateUrl** property.

    The choice between inline and separate HTML is a matter of taste, circumstances, and organization policy. But normally we use inline template for small portion of code and external template file for bigger views. By default, the Angular CLI generates components with a template file. But you can override that with the below command,
    ```
    ng generate component hero -it
    ```

  **[⬆ Back to Top](#table-of-contents)**


23. ### What happens if you use script tag inside template?

    Angular recognizes the value as unsafe and automatically sanitizes it, which removes the `script` tag but keeps safe content such as the text content of the `script` tag. This way it eliminates the risk of script injection attacks. If you still use it then it will be ignored and a warning appears in the browser console.

    Let's take an example of innerHtml property binding which causes XSS vulnerability,
    ```typescript
    export class InnerHtmlBindingComponent {
      // For example, a user/attacker-controlled value from a URL.
      htmlSnippet = 'Template <script>alert("0wned")</script> <b>Syntax</b>';
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

24. ### What is interpolation?

    Interpolation is a special syntax that Angular converts into property binding. It’s a convenient alternative to property binding. It is represented by double curly braces({{}}). The text between the braces is often the name of a component property. Angular replaces that name with the string value of the corresponding component property.

    Let's take an example,
    ```html
    <h3>
      {{title}}
      <img src="{{url}}" style="height:30px">
    </h3>
    ```
    In the example above, Angular evaluates the title and url properties and fills in the blanks, first displaying a bold application title and then a URL.

  **[⬆ Back to Top](#table-of-contents)**

25. ### What are template expressions?
    A template expression produces a value similar to any Javascript expression. Angular executes the expression and assigns it to a property of a binding target; the target might be an HTML element, a component, or a directive. In the property binding, a template expression appears in quotes to the right of the = symbol as in `[property]="expression"`.
    In interpolation syntax, the template expression is surrounded by double curly braces. For example, in the below interpolation, the template expression is `{{username}}`,

    ```html
    <h3>{{username}}, welcome to Angular</h3>
    ```

    The below javascript expressions are prohibited in template expression
    1. assignments (=, +=, -=, ...)
    2. new
    3. chaining expressions with ; or ,
    4. increment and decrement operators (++ and --)
    ----------------------------------

  **[⬆ Back to Top](#table-of-contents)**

26. ### What are template statements?
    A template statement responds to an event raised by a binding target such as an element, component, or directive. The template statements appear in quotes to the right of the = symbol like `(event)="statement"`.

    Let's take an example of button click event's statement

    ```html
    <button (click)="editProfile()">Edit Profile</button>
    ```
    In the above expression, editProfile is a template statement. The below JavaScript syntax expressions are not allowed.
    1. new
    2. increment and decrement operators, ++ and --
    3. operator assignment, such as += and -=
    4. the bitwise operators | and &
    5. the template expression operators
    --------------------------------------

  **[⬆ Back to Top](#table-of-contents)**

27. ### How do you categorize data binding types?

     Binding types can be grouped into three categories distinguished by the direction of data flow. They are listed as below,
     1. From the source-to-view
     2. From view-to-source
     3. View-to-source-to-view

     The possible binding syntax can be tabularized as below,

      | Data direction | Syntax | Type |
      |---- | --------- | ---- |
      | From the source-to-view(One-way)  | 1. {{expression}} 2. [target]="expression" 3. bind-target="expression" | Interpolation, Property, Attribute, Class, Style|
      | From view-to-source(One-way) | 1. (target)="statement" 2. on-target="statement" | Event |
      | View-to-source-to-view(Two-way)| 1. [(target)]="expression" 2. bindon-target="expression"| Two-way |

  **[⬆ Back to Top](#table-of-contents)**

28. ### What are pipes?
    Pipes are simple functions that use [template expressions](#what-are-template-expressions) to accept data as input and transform it into a desired output. For example, let us take a pipe to transform a component's birthday property into a human-friendly date using **date** pipe.

    ```javascript
    import { Component } from '@angular/core';

    @Component({
      selector: 'app-birthday',
      template: `<p>Birthday is {{ birthday | date }}</p>`
    })
    export class BirthdayComponent {
      birthday = new Date(1987, 6, 18); // June 18, 1987
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

29. ### What is a parameterized pipe?
    A pipe can accept any number of optional parameters to fine-tune its output. The parameterized pipe can be created by declaring the pipe name with a colon ( : ) and then the parameter value. If the pipe accepts multiple parameters, separate the values with colons. Let's take a birthday example with a particular format(dd/MM/yyyy):

    ```javascript
    import { Component } from '@angular/core';

        @Component({
          selector: 'app-birthday',
          template: `<p>Birthday is {{ birthday | date:'dd/MM/yyyy'}}</p>` // 18/06/1987
        })
        export class BirthdayComponent {
          birthday = new Date(1987, 6, 18);
        }
    ```
    **Note:** The parameter value can be any valid template expression, such as a string literal or a component property.

  **[⬆ Back to Top](#table-of-contents)**

30. ### How do you chain pipes?
    You can chain pipes together in potentially useful combinations as per the needs. Let's take a birthday property which uses date pipe(along with parameter) and uppercase pipes as below

    ```javascript
    import { Component } from '@angular/core';

            @Component({
              selector: 'app-birthday',
              template: `<p>Birthday is {{  birthday | date:'fullDate' | uppercase}} </p>` // THURSDAY, JUNE 18, 1987
            })
            export class BirthdayComponent {
              birthday = new Date(1987, 6, 18);
            }

    ```

  **[⬆ Back to Top](#table-of-contents)**

31. ### What is a custom pipe?
    Apart from built-in pipes, you can write your own custom pipe with the below key characteristics:
    1. A pipe is a class decorated with pipe metadata `@Pipe` decorator, which you import from the core Angular library
       For example,
        ```javascript
            @Pipe({name: 'myCustomPipe'})
        ```
    2. The pipe class implements the **PipeTransform** interface's transform method that accepts an input value followed by optional parameters and returns the transformed value.
       The structure of `PipeTransform` would be as below,
        ```javascript
        interface PipeTransform {
          transform(value: any, ...args: any[]): any
        }
        ```
    3. The `@Pipe` decorator allows you to define the pipe name that you'll use within template expressions. It must be a valid JavaScript identifier.
        ```javascript
        template: `{{someInputValue | myCustomPipe: someOtherValue}}`
        ```

  **[⬆ Back to Top](#table-of-contents)**

33. ### What is the difference between pure and impure pipe?
    A pure pipe is only called when Angular detects a change in the value or the parameters passed to a pipe. For example, any changes to a primitive input value (String, Number, Boolean, Symbol) or a changed object reference (Date, Array, Function, Object). An impure pipe is called for every change detection cycle no matter whether the value or parameters changes. i.e, An impure pipe is called often, as often as every keystroke or mouse-move.

  **[⬆ Back to Top](#table-of-contents)**

34. ### What is a bootstrapping module?
    Every application has at least one Angular module, the root module that you bootstrap to launch the application is called as bootstrapping module. It is commonly known as `AppModule`. The default structure of `AppModule` generated by AngularCLI would be as follows:
	
	```javascript
        import { BrowserModule } from '@angular/platform-browser';
        import { NgModule } from '@angular/core';
        import { FormsModule } from '@angular/forms';
        import { HttpClientModule } from '@angular/common/http';

        import { AppComponent } from './app.component';

        /* the AppModule class with the @NgModule decorator */
        @NgModule({
          declarations: [
            AppComponent
          ],
          imports: [
            BrowserModule,
            FormsModule,
            HttpClientModule
          ],
          providers: [],
          bootstrap: [AppComponent]
        })
        export class AppModule { }
	```

  **[⬆ Back to Top](#table-of-contents)**

36. ### What is HttpClient and its benefits?
    Most of the Front-end applications communicate with backend services over `HTTP` protocol using either `XMLHttpRequest` interface or the `fetch()` API. Angular provides a simplified client HTTP API known as `HttpClient` which is based on top of `XMLHttpRequest` interface. This client is available from `@angular/common/http` package.
    You can import in your root module as below:

    ```javascript
    import { HttpClientModule } from '@angular/common/http';
    ```

    The major advantages of HttpClient can be listed as below,
    1. Contains testability features
    2. Provides typed request and response objects
    3. Intercept request and response
    4. Supports Observalbe APIs
    5. Supports streamlined error handling

  **[⬆ Back to Top](#table-of-contents)**

37. ### Explain on how to use `HttpClient` with an example?
    Below are the steps need to be followed for the usage of `HttpClient`.
    1. Import `HttpClient` into root module:
        ```javascript
        import { HttpClientModule } from '@angular/common/http';
        @NgModule({
          imports: [
            BrowserModule,
            // import HttpClientModule after BrowserModule.
            HttpClientModule,
          ],
          ......
          })
         export class AppModule {}
        ```
    2. Inject the `HttpClient` into the application:
        Let's create a userProfileService(`userprofile.service.ts`) as an example. It also defines get method of `HttpClient`:
        ```javascript
        import { Injectable } from '@angular/core';
        import { HttpClient } from '@angular/common/http';

        const userProfileUrl: string = 'assets/data/profile.json';

        @Injectable()
        export class UserProfileService {
          constructor(private http: HttpClient) { }

          getUserProfile() {
            return this.http.get(this.userProfileUrl);
          }
        }
        ```
    3. Create a component for subscribing service:
        Let's create a component called UserProfileComponent(`userprofile.component.ts`), which injects `UserProfileService` and invokes the service method:
        ```javascript
        fetchUserProfile() {
          this.userProfileService.getUserProfile()
            .subscribe((data: User) => this.user = {
                id: data['userId'],
                name: data['firstName'],
                city:  data['city']
            });
        }
        ```
    Since the above service method returns an Observable which needs to be subscribed in the component.

  **[⬆ Back to Top](#table-of-contents)**

38. ### How can you read full response?
    The response body doesn't or may not return full response data because sometimes servers also return special headers or status code, which are important for the application workflow. In order to get the full response, you should use `observe` option from `HttpClient`:

    ```javascript
    getUserResponse(): Observable<HttpResponse<User>> {
      return this.http.get<User>(
        this.userUrl, { observe: 'response' });
    }
    ```
    Now `HttpClient.get()` method returns an Observable of typed `HttpResponse` rather than just the `JSON` data.

  **[⬆ Back to Top](#table-of-contents)**

39. ### How do you perform Error handling?
    If the request fails on the server or fails to reach the server due to network issues, then `HttpClient` will return an error object instead of a successful reponse. In this case, you need to handle in the component by passing `error` object as a second callback to `subscribe()` method.

    Let's see how it can be handled in the component with an example,
    ```javascript
    fetchUser() {
      this.userService.getProfile()
        .subscribe(
          (data: User) => this.userProfile = { ...data }, // success path
          error => this.error = error // error path
        );
    }
    ```
    It is always a good idea to give the user some meaningful feedback instead of displaying the raw error object returned from `HttpClient`.

  **[⬆ Back to Top](#table-of-contents)**

40. ### What is RxJS?
    RxJS is a library for composing asynchronous and callback-based code in a functional, reactive style using Observables. Many APIs such as  HttpClient produce and consume RxJS Observables and also uses operators for processing observables.

    For example, you can import observables and operators for using HttpClient as below,
    ```javascript
    import { Observable, throwError } from 'rxjs';
    import { catchError, retry } from 'rxjs/operators';
    ```

  **[⬆ Back to Top](#table-of-contents)**

41. ### What is subscribing?
    An Observable instance begins publishing values only when someone subscribes to it. So you need to subscribe by calling the `subscribe()` method of the instance, passing an observer object to receive the notifications.

    Let's take an example of creating and subscribing to a simple observable, with an observer that logs the received message to the console.
    ```javascript
    // Creates an observable sequence of 5 integers, starting from 1
    const source = range(1, 5);

    // Create observer object
    const myObserver = {
      next: x => console.log('Observer got a next value: ' + x),
      error: err => console.error('Observer got an error: ' + err),
      complete: () => console.log('Observer got a complete notification'),
    };

    // Execute with the observer object and Prints out each item
    source.subscribe(myObserver);
    // => Observer got a next value: 1
    // => Observer got a next value: 2
    // => Observer got a next value: 3
    // => Observer got a next value: 4
    // => Observer got a next value: 5
    // => Observer got a complete notification
    ```

  **[⬆ Back to Top](#table-of-contents)**

42. ### What is an observable?
    An Observable is a unique Object similar to a Promise that can help manage async code. Observables are not part of the JavaScript language so we need to rely on a popular Observable library called RxJS.
    The observables are created using new keyword.

    Let see the simple example of observable,
    ```javascript
    import { Observable } from 'rxjs';

    const observable = new Observable(observer => {
      setTimeout(() => {
        observer.next('Hello from a Observable!');
      }, 2000);
    });
    ```

  **[⬆ Back to Top](#table-of-contents)**

43. ### What is an observer?
    Observer is an interface for a consumer of push-based notifications delivered by an Observable. It has below structure,

    ```javascript
    interface Observer<T> {
      closed?: boolean;
      next: (value: T) => void;
      error: (err: any) => void;
      complete: () => void;
    }
    ```
    A handler that implements the Observer interface for receiving observable notifications will be passed as a parameter for observable as below,

    ```javascript
    myObservable.subscribe(myObserver);
    ```
    **Note:** If you don't supply a handler for a notification type, the observer ignores notifications of that type.

  **[⬆ Back to Top](#table-of-contents)**

44. ### What is the difference between promise and observable?
    Below are the list of differences between promise and observable:

       | Observable | Promise |
       |---- | --------- |
       | Declarative: Computation does not start until subscription, so they can run whenever you need the result | Executes immediately on creation|
       | Provides multiple values over time | Provides only one |
       | Subscribe method is used for error handling that facilitates centralized and predictable error handling | Push errors to the child promises |
       | Provides chaining and subscription to handle complex applications | Uses only `.then()` clause |

  **[⬆ Back to Top](#table-of-contents)**

45. ### What is multicasting?
    Multi-casting is the practice of broadcasting to a list of multiple subscribers in a single execution.

    Let's demonstrate the multi-casting feature:
    ```javascript
    var source = Rx.Observable.from([1, 2, 3]);
    var subject = new Rx.Subject();
    var multicasted = source.multicast(subject);

    // These are, under the hood, `subject.subscribe({...})`:
    multicasted.subscribe({
      next: (v) => console.log('observerA: ' + v)
    });
    multicasted.subscribe({
      next: (v) => console.log('observerB: ' + v)
    });

    // This is, under the hood, `s
    ```

  **[⬆ Back to Top](#table-of-contents)**

46. ### How do you perform error handling in observables?
    You can handle errors by specifying an **error callback** on the observer instead of relying on `try`/`catch`, which are ineffective in asynchronous environment.

    For example, you can define error callback as below,
    ```javascript
    myObservable.subscribe({
      next(num) { console.log('Next num: ' + num)},
      error(err) { console.log('Received an errror: ' + err)}
    });
    ```

  **[⬆ Back to Top](#table-of-contents)**

47. ### What is the shorthand notation for subscribe method?
    The `subscribe()` method can accept callback function definitions in line, for `next`, `error`, and `complete` handlers. It is known as shorthand notation or Subscribe method with positional arguments.

    For example, you can define subscribe method as below,
    ```javascript
    myObservable.subscribe(
      x => console.log('Observer got a next value: ' + x),
      err => console.error('Observer got an error: ' + err),
      () => console.log('Observer got a complete notification')
    );
    ```

  **[⬆ Back to Top](#table-of-contents)**

48. ### What are the utility functions provided by RxJS?
    The RxJS library also provides below utility functions for creating and working with observables.

    1. Converting existing code for async operations into observables
    2. Iterating through the values in a stream
    3. Mapping values to different types
    4. Filtering streams
    5. Composing multiple streams

  **[⬆ Back to Top](#table-of-contents)**

49. ### What are observable creation functions?
    RxJS provides creation functions for the process of creating observables from promises, events, timers and Ajax requests. Let us explain each of them with an example:
    1. Create an observable from a promise
        ```javascript
        import { from } from 'rxjs'; // from function
        const data = from(fetch('/api/endpoint')); //Created from Promise
        data.subscribe({
         next(response) { console.log(response); },
         error(err) { console.error('Error: ' + err); },
         complete() { console.log('Completed'); }
        });
        ```
    2. Create an observable that creates an AJAX request
        ```javascript
        import { ajax } from 'rxjs/ajax'; // ajax function
        const apiData = ajax('/api/data'); // Created from AJAX request
        // Subscribe to create the request
        apiData.subscribe(res => console.log(res.status, res.response));
        ```
    3. Create an observable from a counter
        ```javascript
        import { interval } from 'rxjs'; // interval function
        const secondsCounter = interval(1000); // Created from Counter value
        secondsCounter.subscribe(n =>
          console.log(`Counter value: ${n}`));
        ```
    4. Create an observable from an event
        ```javascript
        import { fromEvent } from 'rxjs';
        const el = document.getElementById('custom-element');
        const mouseMoves = fromEvent(el, 'mousemove');
        const subscription = mouseMoves.subscribe((e: MouseEvent) => {
          console.log(`Coordnitaes of mouse pointer: ${e.clientX} * ${e.clientY}`);
          });
        ```

  **[⬆ Back to Top](#table-of-contents)**

50. ### What will happen if you do not supply handler for the observer?
    Usually, an observer object can define any combination of `next`, `error`, and `complete` notification type handlers. If you don't supply a handler for a notification type, the observer just ignores notifications of that type.

  **[⬆ Back to Top](#table-of-contents)**

51. ### What are Angular elements?
    Angular elements are Angular components packaged as **custom elements** (a web standard for defining new HTML elements in a framework-agnostic way). Angular Elements host an Angular component, providing a bridge between the data and the logic defined in the component and the standard DOM APIs, thus, providing a way to use Angular components in `non-Angular environments`.

  **[⬆ Back to Top](#table-of-contents)**

52. ### What is the browser support of Angular Elements?
    Since Angular elements are packaged as custom elements the browser support of angular elements is same as custom elements support.

    This feature is is currently supported natively in a number of browsers and pending for other browsers.

    | Browser | Angular Element Support |
    |---- | --------- |
    | Chrome | Natively supported|
    | Opera | Natively supported |
    | Safari| Natively supported |
    | Firefox | Natively supported from 63 version onwards. You need to enable dom.webcomponents.enabled and dom.webcomponents.customelements.enabled in older browsers |
    | Edge| Currently it is in progress|

  **[⬆ Back to Top](#table-of-contents)**

53. ### What are custom elements?
    Custom elements (or Web Components) are a Web Platform feature which extends HTML by allowing you to define a tag whose content is created and controlled by JavaScript code. The browser maintains a `CustomElementRegistry` of defined custom elements, which maps an instantiable JavaScript class to an HTML tag. Currently this feature is supported by Chrome, Firefox, Opera, and Safari, and available in other browsers through polyfills.

  **[⬆ Back to Top](#table-of-contents)**

54. ### Do I need to bootstrap custom elements?
    No, custom elements bootstrap (or start) automatically when they are added to the DOM, and are automatically destroyed when removed from the DOM. Once a custom element is added to the DOM for any page, it looks and behaves like any other HTML element, and does not require any special knowledge of Angular.

  **[⬆ Back to Top](#table-of-contents)**

55. ### Explain how custom elements works internally?
    Below are the steps in an order about custom elements functionality,
    1. **App registers custom element with browser:** Use the `createCustomElement()` function to convert a component into a class that can be registered with the browser as a custom element.
    2. **App adds custom element to DOM:**  Add custom element just like a built-in HTML element directly into the DOM.
    3. **Browser instantiate component based class:** Browser creates an instance of the registered class and adds it to the DOM.
    4. **Instance provides content with data binding and change detection:** The content with in template is rendered using the component and DOM data.
    The flow chart of the custom elements functionality would be as follows,

    ![CustomElement](images/customElement.png)

  **[⬆ Back to Top](#table-of-contents)**

56. ### How to transfer components to custom elements?
    Transforming components to custom elements involves **two** major steps,
    1. **Build custom element class:** Angular provides the `createCustomElement()` function for converting an Angular component (along with its dependencies) to a custom element. The conversion process implements `NgElementConstructor` interface, and creates a constructor class which is used to produce a self-bootstrapping instance of Angular component.
    2. **Register element class with browser:** It uses `customElements.define()` JS function, to register the configured constructor and its associated custom-element tag with the browser's `CustomElementRegistry`. When the browser encounters the tag for the registered element, it uses the constructor to create a custom-element instance.

    The detailed structure would be as follows,
    ![CreateElement](images/createElement.png)

  **[⬆ Back to Top](#table-of-contents)**

57. ### What are the mapping rules between Angular component and custom element?
    The Component properties and logic maps directly into HTML attributes and the browser's event system. Let us describe them in two steps,
    1. The createCustomElement() API parses the component input properties with corresponding attributes for the custom element. For example, component @Input('myInputProp') converted as custom element attribute `my-input-prop`.
    2. The Component outputs are dispatched as HTML Custom Events, with the name of the custom event matching the output name. For example, component @Output() valueChanged = new EventEmitter() converted as custom element with dispatch event as "valueChanged".

  **[⬆ Back to Top](#table-of-contents)**

58. ### How do you define typings for custom elements?
    You can use the `NgElement` and `WithProperties` types exported from @angular/elements.

    Let's see how it can be applied by comparing with Angular component.
    1. The simple container with input property would be as below,
        ```javascript
        @Component(...)
        class MyContainer {
          @Input() message: string;
        }
        ```
    2. After applying types typescript validates input value and their types,
        ```javascirpt
        const container = document.createElement('my-container') as NgElement & WithProperties<{message: string}>;
        container.message = 'Welcome to Angular elements!';
        container.message = true;  // <-- ERROR: TypeScript knows this should be a string.
        container.greet = 'News';  // <-- ERROR: TypeScript knows there is no `greet` property on `container`.
        ```

  **[⬆ Back to Top](#table-of-contents)**

59. ### What are dynamic components?
    Dynamic components are the components in which the component's location in the application is not defined at build time i.e. they are not used in any angular template. Instead, the component is instantiated and placed in the application at runtime.

  **[⬆ Back to Top](#table-of-contents)**

60. ### What are the various kinds of directives?
    There are mainly three kinds of directives:
    1. **Components** — These are directives with a template.
    2. **Structural directives** — These directives change the DOM layout by adding and removing DOM elements.
    3. **Attribute directives** — These directives change the appearance or behavior of an element, component, or another directive.

  **[⬆ Back to Top](#table-of-contents)**

61. ### How do you create directives using CLI?
    You can use CLI command `ng generate directive` to create the directive class file. It creates the source file(`src/app/components/directivename.directive.ts`), the respective test file `.spec.ts` and declare the directive class file in root module.

  **[⬆ Back to Top](#table-of-contents)**

62. ### Give an example for attribute directives?
    Let's take simple highlighter behavior as a example directive for DOM element. You can create and apply the attribute directive using below step:

    1. Create HighlightDirective class with the file name `src/app/highlight.directive.ts`. In this file, we need to import **Directive** from core library to apply the metadata and **ElementRef** in the directive's constructor to inject a reference to the host DOM element ,
        ```javascript
        import { Directive, ElementRef } from '@angular/core';

        @Directive({
          selector: '[appHighlight]'
        })
        export class HighlightDirective {
            constructor(el: ElementRef) {
               el.nativeElement.style.backgroundColor = 'red';
            }
        }
        ```
    2. Apply the attribute directive as an attribute to the host element(for example, <p>)
        ```javascript
        <p appHighlight>Highlight me!</p>
        ```
    3. Run the application to see the highlight behavior on paragraph element
        ```javascript
        ng serve
        ```

  **[⬆ Back to Top](#table-of-contents)**

63. ### What is Angular Router?
    Angular Router is a mechanism in which navigation happens from one view to the next as users perform application tasks. It borrows the concepts or model of browser's application navigation. It enables developers to build Single Page Applications with multiple views and allow navigation between these views.

  **[⬆ Back to Top](#table-of-contents)**

64. ### What is the purpose of base href tag?
    The routing application should add <base> element to the index.html as the first child in the <head> tag in order to indicate how to compose navigation URLs. If app folder is the application root then you can set the href value as below

    ```html
    <base href="/">
    ```

  **[⬆ Back to Top](#table-of-contents)**

65. ### What are the router imports?
    The Angular Router which represents a particular component view for a given URL is not part of Angular Core. It is available in library named `@angular/router` to import required router components. For example, we import them in app module as below,

    ```javascript
    import { RouterModule, Routes } from '@angular/router';
    ```

  **[⬆ Back to Top](#table-of-contents)**

66. ### What is router outlet?
    The RouterOutlet is a directive from the router library and it  acts as a placeholder that marks the spot in the template where the router should display the components for that outlet. Router outlet is used like a component,

    ```html
    <router-outlet></router-outlet>
    <!-- Routed components go here -->
    ```

  **[⬆ Back to Top](#table-of-contents)**

67. ### What are router links?
    The RouterLink is a directive on the anchor tags give the router control over those elements. Since the navigation paths are fixed, you can assign string values to router-link directive as below,

    ```html
    <h1>Angular Router</h1>
    <nav>
      <a routerLink="/todosList" >List of todos</a>
      <a routerLink="/completed" >Completed todos</a>
    </nav>
    <router-outlet></router-outlet>
    ```

  **[⬆ Back to Top](#table-of-contents)**

68. ### What are active router links?
    RouterLinkActive is a directive that toggles css classes for active RouterLink bindings based on the current RouterState. i.e, The Router will add CSS classes when this link is active and remove when the link is inactive. For example, you can add them to RouterLinks as below.

    ```html
    <h1>Angular Router</h1>
    <nav>
      <a routerLink="/todosList" routerLinkActive="active">List of todos</a>
      <a routerLink="/completed" routerLinkActive="active">Completed todos</a>
    </nav>
    <router-outlet></router-outlet>
    ```

  **[⬆ Back to Top](#table-of-contents)**

69. ### What is router state?
    RouterState is a tree of activated routes. Every node in this tree knows about the "consumed" URL segments, the extracted parameters, and the resolved data. You can access the current RouterState from anywhere in the application using the `Router service` and the `routerState` property.

    ```javascript
    @Component({templateUrl:'template.html'})
    class MyComponent {
      constructor(router: Router) {
        const state: RouterState = router.routerState;
        const root: ActivatedRoute = state.root;
        const child = root.firstChild;
        const id: Observable<string> = child.params.map(p => p.id);
        //...
      }
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

70. ### What are router events?
    During each navigation, the Router emits navigation events through the Router.events property allowing you to track the lifecycle of the route.

    The sequence of router events is as below,

    1. NavigationStart,
    2. RouteConfigLoadStart,
    3. RouteConfigLoadEnd,
    4. RoutesRecognized,
    5. GuardsCheckStart,
    6. ChildActivationStart,
    7. ActivationStart,
    8. GuardsCheckEnd,
    9. ResolveStart,
    10. ResolveEnd,
    11. ActivationEnd
    12. ChildActivationEnd
    13. NavigationEnd,
    14. NavigationCancel,
    15. NavigationError
    16. Scroll

  **[⬆ Back to Top](#table-of-contents)**

71. ### What is activated route?
    ActivatedRoute contains the information about a route associated with a component loaded in an outlet. It can also be used to traverse the router state tree. The ActivatedRoute will be injected as a router service to access the information. In the below example, you can access route path and parameters,

    ```javascript
    @Component({...})
    class MyComponent {
      constructor(route: ActivatedRoute) {
        const id: Observable<string> = route.params.pipe(map(p => p.id));
        const url: Observable<string> = route.url.pipe(map(segments => segments.join('')));
        // route.data includes both `data` and `resolve`
        const user = route.data.pipe(map(d => d.user));
      }
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

72. ### How do you define routes?
     A router must be configured with a list of route definitions. You configures the router with routes via the `RouterModule.forRoot()` method, and adds the result to the AppModule's `imports` array.

    ```javascript
     const appRoutes: Routes = [
      { path: 'todo/:id',      component: TodoDetailComponent },
      {
        path: 'todos',
        component: TodosListComponent,
        data: { title: 'Todos List' }
      },
      { path: '',
        redirectTo: '/todos',
        pathMatch: 'full'
      },
      { path: '**', component: PageNotFoundComponent }
    ];

    @NgModule({
      imports: [
        RouterModule.forRoot(
          appRoutes,
          { enableTracing: true } // <-- debugging purposes only
        )
        // other imports here
      ],
      ...
    })
    export class AppModule { }
    ```

   **[⬆ Back to Top](#table-of-contents)**

73. ### What is the purpose of Wildcard route?
    If the URL doesn't match any predefined routes then it causes the router to throw an error and crash the app. In this case, you can use wildcard route. A wildcard route has a path consisting of two asterisks to match every URL.

    For example, you can define PageNotFoundComponent for wildcard route as below
    ```javascript
    { path: '**', component: PageNotFoundComponent }
    ```

  **[⬆ Back to Top](#table-of-contents)**

74. ### Do I need a Routing Module always?
    No, the Routing Module is a design choice. You can skip routing Module (for example, AppRoutingModule) when the configuration is simple and merge the routing configuration directly into the companion module (for example, AppModule). But it is recommended when the configuration is complex and includes specialized guard and resolver services.

  **[⬆ Back to Top](#table-of-contents)**

75. ### What is Angular Universal?
    Angular Universal is a server-side rendering module for Angular applications in various scenarios. This is a community driven project and available under @angular/platform-server package. Recently Angular Universal is integrated with Angular CLI.

  **[⬆ Back to Top](#table-of-contents)**

76. ### What are different types of compilation in Angular?
    Angular offers two ways to compile your application,
    1. Just-in-Time (JIT)
    2. Ahead-of-Time (AOT)

  **[⬆ Back to Top](#table-of-contents)**

77. ### What is JIT?
    Just-in-Time (JIT) is a type of compilation that compiles your app in the browser at runtime. JIT compilation was the default until Angular 8, now default is AOT. When you run the ng build (build only) or ng serve (build and serve locally) CLI commands, the type of compilation (JIT or AOT) depends on the value of the aot property in your build configuration specified in angular.json. By default, aot is set to true.

  **[⬆ Back to Top](#table-of-contents)**

78. ### What is AOT?
    Ahead-of-Time (AOT) is a type of compilation that compiles your app at build time. This is the default starting in Angular 9. When you run the ng build (build only) or ng serve (build and serve locally) CLI commands, the type of compilation (JIT or AOT) depends on the value of the aot property in your build configuration specified in angular.json. By default, aot is set to true.
    
    ```cmd
    ng build
    ng serve
    ```

  **[⬆ Back to Top](#table-of-contents)**

79. ### Why do we need compilation process?
    The Angular components and templates cannot be understood by the browser directly. Due to that Angular applications require a compilation process before they can run in a browser. For example, In AOT compilation, both Angular HTML and TypeScript code converted into efficient JavaScript code during the build phase before browser runs it.

  **[⬆ Back to Top](#table-of-contents)**

80. ### What are the advantages with AOT?
    Below are the list of AOT benefits,

    1. **Faster rendering:** The browser downloads a pre-compiled version of the application. So it can render the application immediately without compiling the app.
    2. **Fewer asynchronous requests:** It inlines external HTML templates and CSS style sheets within the application javascript which eliminates separate ajax requests.
    3. **Smaller Angular framework download size:** Doesn't require downloading the Angular compiler. Hence it dramatically reduces the application payload.
    4. **Detect template errors earlier:** Detects and reports template binding errors during the build step itself
    5. **Better security:** It compiles HTML templates and components into JavaScript.  So there won't be any injection attacks.

  **[⬆ Back to Top](#table-of-contents)**

87. ### What is folding?
    The compiler can only resolve references to exported symbols in the metadata. Where as some of the non-exported members are folded while generating the code. i.e Folding is a process in which the collector evaluate an expression during collection and record the result in the .metadata.json instead of the original expression.
    For example, the compiler couldn't refer selector reference because it is not exported

    ```javascript
    let selector = 'app-root';
    @Component({
      selector: selector
    })
    ```
    Will be folded into inline selector

    ```javascript
    @Component({
          selector: 'app-root'
        })
    ```
    Remember that the compiler can’t fold everything. For example, spread operator on arrays, objects created using new keywords and function calls.

  **[⬆ Back to Top](#table-of-contents)**

88. ### What are macros?
    The AOT compiler supports macros in the form of functions or static methods that return an expression in a `single return expression`.
    For example, let us take a below macro function,

    ```javascript
    export function wrapInArray<T>(value: T): T[] {
      return [value];
    }
    ```

    You can use it inside metadata as an expression,

    ```javascript
    @NgModule({
      declarations: wrapInArray(TypicalComponent)
    })
    export class TypicalModule {}
    ```

    The compiler treats the macro expression as it written directly

    ```javascript
    @NgModule({
      declarations: [TypicalComponent]
    })
    export class TypicalModule {}
    ```

  **[⬆ Back to Top](#table-of-contents)**

95. ### What is Non null type assertion operator?
    You can use the non-null type assertion operator to suppress the Object is possibly 'undefined' error. In the following example, the user and contact properties are always set together, implying that contact is always non-null if user is non-null. The error is suppressed in the example by using contact!.email.
    ```javascript
    @Component({
      selector: 'my-component',
      template: '<span *ngIf="user"> {{user.name}} contacted through {{contact!.email}} </span>'
    })
    class MyComponent {
      user?: User;
      contact?: Contact;

      setData(user: User, contact: Contact) {
        this.user = user;
        this.contact = contact;
      }
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

96. ### What is type narrowing?
    The expression used in an ngIf directive is used to narrow type unions in the Angular template compiler similar to if expression in typescript. So *ngIf allows the typeScript compiler to infer that the data used in the binding expression will never be undefined.
    ```javascript
    @Component({
      selector: 'my-component',
      template: '<span *ngIf="user"> {{user.contact.email}} </span>'
    })
    class MyComponent {
      user?: User;
    }
    ```

  **[⬆ Back to Top](#table-of-contents)**

98. ### What is zone?
    A Zone is an execution context that persists across async tasks. Angular relies on zone.js to run Angular's change detection processes when native JavaScript operations raise events

  **[⬆ Back to Top](#table-of-contents)**

99. ### What is the purpose of common module?
    The commonly-needed services, pipes, and directives provided by @angular/common module. Apart from these HttpClientModule is available under @angular/common/http.

  **[⬆ Back to Top](#table-of-contents)**


101. ### What is angular animation?
     Angular's animation system is built on CSS functionality in order to animate any property that the browser considers animatable. These properties includes positions, sizes, transforms, colors, borders etc. The Angular modules for animations are **@angular/animations** and **@angular/platform-browser** and these dependencies are automatically added to your project when you create a project using Angular CLI.

   **[⬆ Back to Top](#table-of-contents)**

102. ### What are the steps to use animation module?
     You need to follow below steps to implement animation in your angular project,

     1. **Enabling the animations module:** Import BrowserAnimationsModule to add animation capabilities into your Angular root application module(for example, src/app/app.module.ts).
         ```javascript
         import { NgModule } from '@angular/core';
         import { BrowserModule } from '@angular/platform-browser';
         import { BrowserAnimationsModule } from '@angular/platform-browser/animations';

         @NgModule({
           imports: [
             BrowserModule,
             BrowserAnimationsModule
           ],
           declarations: [ ],
           bootstrap: [ ]
         })
         export class AppModule { }
         ```
     2. **Importing animation functions into component files:** Import required animation functions from @angular/animations in component files(for example, src/app/app.component.ts).
         ```javascript
         import {
           trigger,
           state,
           style,
           animate,
           transition,
           // ...
         } from '@angular/animations';
         ```
     3. **Adding the animation metadata property:** add a metadata property called animations: within the @Component() decorator in component files(for example, src/app/app.component.ts)
         ```javascript
         @Component({
           selector: 'app-root',
           templateUrl: 'app.component.html',
           styleUrls: ['app.component.css'],
           animations: [
             // animation triggers go here
           ]
         })
         ```

   **[⬆ Back to Top](#table-of-contents)**

103. ### What is State function?
     Angular's state() function is used to define different states to call at the end of each transition. This function takes two arguments: a unique name like open or closed and a style() function.

     For example, you can write a open state function

     ```javascript
     state('open', style({
       height: '300px',
       opacity: 0.5,
       backgroundColor: 'blue'
     })),
     ```

   **[⬆ Back to Top](#table-of-contents)**

104. ### What is Style function?
     The style function is used to define a set of styles to associate with a given state name. You need to use it along with state() function to set CSS style attributes. For example, in the close state, the button has a height of 100 pixels, an opacity of 0.8, and a background color of green.

     ```javascript
     state('close', style({
       height: '100px',
       opacity: 0.8,
       backgroundColor: 'green'
     })),
     ```
     **Note:** The style attributes must be in camelCase.

   **[⬆ Back to Top](#table-of-contents)**

105. ### What is the purpose of animate function?
     Angular Animations are a powerful way to implement sophisticated and compelling animations for your Angular single page web application.

        ```javascript
        import { Component, OnInit, Input } from '@angular/core';
        import { trigger, state, style, animate, transition } from '@angular/animations';
    
        @Component({
        selector: 'app-animate',
        templateUrl: `<div [@changeState]="currentState" class="myblock mx-auto"></div>`,
        styleUrls: `.myblock {
            background-color: green;
            width: 300px;
            height: 250px;
            border-radius: 5px;
            margin: 5rem;
            }`,
        animations: [
            trigger('changeState', [
            state('state1', style({
                backgroundColor: 'green',
                transform: 'scale(1)'
            })),
            state('state2', style({
                backgroundColor: 'red',
                transform: 'scale(1.5)'
            })),
            transition('*=>state1', animate('300ms')),
            transition('*=>state2', animate('2000ms'))
            ])
        ]
        })
        export class AnimateComponent implements OnInit {
    
            @Input() currentState;
    
            constructor() { }
    
            ngOnInit() {
            }
        }
        ```

   **[⬆ Back to Top](#table-of-contents)**

106. ### What is transition function?
     The animation transition function is used to specify the changes that occur between one state and another over a period of time. It accepts two arguments: the first argument accepts an expression that defines the direction between two transition states, and the second argument accepts an animate() function.

     Let's take an example state transition from open to closed with an half second transition between states.

     ```javascript
     transition('open => closed', [
       animate('500ms')
     ]),
     ```

   **[⬆ Back to Top](#table-of-contents)**

 111. ### What is Angular Ivy?
      Angular Ivy is a new rendering engine for Angular. You can choose to opt in a preview version of Ivy from Angular version 8.

      1. You can enable ivy in a new project by using the --enable-ivy flag with the ng new command

          ```bash
          ng new ivy-demo-app --enable-ivy
          ```
      2. You can add it to an existing project by adding `enableIvy` option in the `angularCompilerOptions` in your project's `tsconfig.app.json`.

          ```javascript
          {
            "compilerOptions": { ... },
            "angularCompilerOptions": {
              "enableIvy": true
            }
          }
          ```

   **[⬆ Back to Top](#table-of-contents)**

 112. ### What are the features included in ivy preview?
      You can expect below features with Ivy preview,

      1. Generated code that is easier to read and debug at runtime
      2. Faster re-build time
      3. Improved payload size
      4. Improved template type checking

   **[⬆ Back to Top](#table-of-contents)**


 125. ### What are the class decorators in Angular?
      A class decorator is a decorator that appears immediately before a class definition, which declares the class to be of the given type, and provides metadata suitable to the type

      The following list of decorators comes under class decorators,

      1. @Component()
      2. @Directive()
      3. @Pipe()
      4. @Injectable()
      5. @NgModule()

   **[⬆ Back to Top](#table-of-contents)**

 126. ### What are class field decorators?
      The class field decorators are the statements declared immediately before a field in a class definition that defines the type of that field. Some of the examples are: @input and @output,

      ```javascript
      @Input() myProperty;
      @Output() myEvent = new EventEmitter();
      ```

   **[⬆ Back to Top](#table-of-contents)**

 127. ### What is declarable in Angular?
      Declarable is a class type that you can add to the declarations list of an NgModule. The class types such as components, directives, and pipes comes can be declared in the module. The structure of declarations would be,

      ```javascript
      declarations: [
        YourComponent,
        YourPipe,
        YourDirective
      ],
      ```

   **[⬆ Back to Top](#table-of-contents)**

 128. ### What are the restrictions on declarable classes?
      Below classes shouldn't be declared,

      1. A class that's already declared in another NgModule
      2. Ngmodule classes
      3. Service classes
      4. Helper classes

   **[⬆ Back to Top](#table-of-contents)**

 129. ### What is a DI token?
      A DI token is a lookup token associated with a dependency provider in dependency injection system. The injector maintains an internal token-provider map that it references when asked for a dependency and the DI token is the key to the map. Let's take example of DI Token usage,

      ```javascript
      const BASE_URL = new InjectionToken<string>('BaseUrl');
      const injector =
         Injector.create({providers: [{provide: BASE_URL, useValue: 'http://some-domain.com'}]});
      const url = injector.get(BASE_URL);
      ```

   **[⬆ Back to Top](#table-of-contents)**

 130. ### What is Angular DSL?
      A domain-specific language (DSL) is a computer language specialized to a particular application domain. Angular has its own Domain Specific Language (DSL) which allows us to write Angular specific html-like syntax on top of normal html. It has its own compiler that compiles this syntax to html that the browser can understand. This DSL is defined in NgModules such as animations, forms, and routing and navigation.

      Basically you will see 3 main syntax in Angular DSL.

      1. `()`: Used for Output and DOM events.
      2. `[]`: Used for Input and specific DOM element attributes.
      3. `*`: Structural directives(*ngFor or *ngIf) will affect/change the DOM structure.

   **[⬆ Back to Top](#table-of-contents)**

136. ### What is platform in Angular?
     A platform is the context in which an Angular application runs. The most common platform for Angular applications is a web browser, but it can also be an operating system for a mobile device, or a web server. The runtime-platform is provided by the @angular/platform-* packages and these packages allow applications that make use of `@angular/core` and `@angular/common` to execute in different environments.
     i.e, Angular can be used as platform-independent framework in different environments, For example,

     1. While running in the browser, it uses `platform-browser` package.
     2. When SSR(server-side rendering ) is used, it uses `platform-server` package for providing web server implementation.

   **[⬆ Back to Top](#table-of-contents)**

137. ### What happens if I import the same module twice?
     If multiple modules imports the same module then angular evaluates it only once (When it encounters the module first time). It follows this condition even the module appears at any level in a hierarchy of imported NgModules.

   **[⬆ Back to Top](#table-of-contents)**

138. ### How do you select an element with in a component template?
     You can use `@ViewChild` directive to access elements in the view directly. Let's take input element with a reference,

     ```html
     <input #uname>
     ```
     and define view child directive and access it in ngAfterViewInit lifecycle hook

     ```javascript
     @ViewChild('uname') input;

     ngAfterViewInit() {
       console.log(this.input.nativeElement.value);
     }
     ```

   **[⬆ Back to Top](#table-of-contents)**

139. ### How do you detect route change in Angular?
     In Angular7, you can subscribe to router to detect the changes. The subscription for router events would be as below,

     ```javascript
     this.router.events.subscribe((event: Event) => {})
     ```
     Let's take a simple component to detect router changes

     ```javascript
     import { Component } from '@angular/core';
     import { Router, Event, NavigationStart, NavigationEnd, NavigationError } from '@angular/router';

     @Component({
         selector: 'app-root',
         template: `<router-outlet></router-outlet>`
     })
     export class AppComponent {

         constructor(private router: Router) {

             this.router.events.subscribe((event: Event) => {
                 if (event instanceof NavigationStart) {
                     // Show loading indicator and perform an action
                 }

                 if (event instanceof NavigationEnd) {
                     // Hide loading indicator and perform an action
                 }

                 if (event instanceof NavigationError) {
                     // Hide loading indicator and perform an action
                     console.log(event.error); // It logs an error for debugging
                 }
             });
        }
     }
     ```

   **[⬆ Back to Top](#table-of-contents)**

143. ### What is lazy loading?
     Lazy loading is one of the most useful concepts of Angular Routing. It helps us to download the web pages in chunks instead of downloading everything in a big bundle. It is used for lazy loading by asynchronously loading the feature module for routing whenever required using the property `loadChildren`. Let's load both `Customer` and `Order` feature modules lazily as below,
     ```javascript
     const routes: Routes = [
       {
         path: 'customers',
         loadChildren: () => import('./customers/customers.module').then(module => module.CustomersModule)
       },
       {
         path: 'orders',
         loadChildren: () => import('./orders/orders.module').then(module => module.OrdersModule)
       },
       {
         path: '',
         redirectTo: '',
         pathMatch: 'full'
       }
     ];
     ```

     **[⬆ Back to Top](#table-of-contents)**

146. ### What is Angular Material?
     Angular Material is a collection of Material Design components for Angular framework following the Material Design spec. You can apply Material Design very easily using Angular Material. The installation can be done through npm or yarn,
     ```bash
     npm install --save @angular/material @angular/cdk @angular/animations
     (OR)
     yarn add @angular/material @angular/cdk @angular/animations
     ```
     It supports the most recent two versions of all major browsers. The latest version of Angular material is 8.1.1

     **[⬆ Back to Top](#table-of-contents)**

149. ### How do you test Angular application using CLI?
     Angular CLI downloads and install everything needed with the Jasmine Test framework. You just need to run `ng test` to see the test results. By default this command builds the app in watch mode, and launches the `Karma test runner`. The output of test results would be as below,
     ```bash
     10% building modules 1/1 modules 0 active
     ...INFO [karma]: Karma v1.7.1 server started at http://0.0.0.0:9876/
     ...INFO [launcher]: Launching browser Chrome ...
     ...INFO [launcher]: Starting browser Chrome
     ...INFO [Chrome ...]: Connected on socket ...
     Chrome ...: Executed 3 of 3 SUCCESS (0.135 secs / 0.205 secs)
     ```
     **Note:** A chrome browser also opens and displays the test output in the "Jasmine HTML Reporter".

     **[⬆ Back to Top](#table-of-contents)**

150. ### How to use polyfills in Angular application?
     The Angular CLI provides support for polyfills officially. When you create a new project with the ng new command, a `src/polyfills.ts` configuration file is created as part of your project folder. This file includes the mandatory and many of the optional polyfills as JavaScript import statements. Let's categorize the polyfills,

     1. **Mandatory polyfills:** These are installed automatically when you create your project with ng new command and the respective import statements enabled in 'src/polyfills.ts' file.
     2. **Optional polyfills:** You need to install its npm package and then create import statement in 'src/polyfills.ts' file.
        For example, first you need to install below npm package for adding web animations (optional) polyfill.
            ```bash
             npm install --save web-animations-js
            ```
        and create import statement in polyfill file.
            ```javascript
            import 'web-animations-js';
            ```

     **[⬆ Back to Top](#table-of-contents)**

151. ### What are the ways to trigger change detection in Angular?
     You can inject either ApplicationRef or NgZone, or ChangeDetectorRef into your component and apply below specific methods to trigger change detection in Angular. i.e, There are 3 possible ways,

     1. **ApplicationRef.tick():** Invoke this method to explicitly process change detection and its side-effects. It check the full component tree.
     2. **NgZone.run(callback):** It evaluate the callback function inside the Angular zone.
     3. **ChangeDetectorRef.detectChanges():** It detects only the components and it's children.

     **[⬆ Back to Top](#table-of-contents)**


153. ### What are the security principles in angular?
     Below are the list of security principles in angular,

		1.	You should avoid direct use of the DOM APIs.
		2.  You should enable Content Security Policy (CSP) and configure your web server to return appropriate CSP HTTP headers.
		3.  You should Use the offline template compiler.
		4.  You should Use Server Side XSS protection.
		5.  You should Use DOM Sanitizer.
		6.  You should Preventing CSRF or XSRF attacks. 

	 **[⬆ Back to Top](#table-of-contents)**

161. ### What are the best practices for security in angular?
     Below are the best practices of security in angular,

     1. Use the latest Angular library releases
     2. Don't modify your copy of Angular
     3. Avoid Angular APIs marked in the documentation as “Security Risk.”

     **[⬆ Back to Top](#table-of-contents)**

162. ### What is Angular security model for preventing XSS attacks?
     Angular treats all values as untrusted by default. i.e, Angular sanitizes and escapes untrusted values When a value is inserted into the DOM from a template, via property, attribute, style, class binding, or interpolation.

     **[⬆ Back to Top](#table-of-contents)**

163. ### What is the role of template compiler for prevention of XSS attacks?
     The offline template compiler prevents vulnerabilities caused by template injection, and greatly improves application performance. So it is recommended to use offline template compiler in production deployments without dynamically generating any template.

     **[⬆ Back to Top](#table-of-contents)**

164. ### What are the various security contexts in Angular?
     Angular defines the following security contexts for sanitization,

     1. **HTML:** It is used when interpreting a value as HTML such as binding to innerHtml.
     2. **Style:** It is used when binding CSS into the style property.
     3. **URL:** It is used for URL properties such as `<a href>`.
     4. **Resource URL:** It is a URL that will be loaded and executed as code such as `<script src>`.

     **[⬆ Back to Top](#table-of-contents)**

165. ### What is Sanitization? Is angular supports it?
     **Sanitization** is the inspection of an untrusted value, turning it into a value that's safe to insert into the DOM. Yes, Angular suppports sanitization. It sanitizes untrusted values for HTML, styles, and URLs but sanitizing resource URLs isn't possible because they contain arbitrary code.

     **[⬆ Back to Top](#table-of-contents)**

166. ### What is the purpose of innerHTML?
     The innerHtml is a property of HTML-Elements, which allows you to set it's html-content programmatically. Let's display the below html code snippet in a `<div>` tag as below using innerHTML binding,

     ```html
     <div [innerHTML]="htmlSnippet"></div>
     ```
     and define the htmlSnippet property from any component
     ```javascript
     export class myComponent {
       htmlSnippet: string = '<b>Hello World</b>, Angular';
     }
     ```
     Unfortunately this property could cause Cross Site Scripting (XSS) security bugs when improperly handled.

     **[⬆ Back to Top](#table-of-contents)**

167. ### What is the difference between interpolated content and innerHTML?
     The main difference between interpolated and innerHTML code is the behavior of code interpreted. Interpolated content is always escaped i.e,  HTML isn't interpreted and the browser displays angle brackets in the element's text content. Where as in innerHTML binding, the content is interpreted i.e, the browser will convert < and > characters as HTMLEntities. For example, the usage in template would be as below,

     ```html
     <p>Interpolated value:</p>
     <div >{{htmlSnippet}}</div>
     <p>Binding of innerHTML:</p>
     <div [innerHTML]="htmlSnippet"></div>
     ```
     and the property defined in a component.

     ```javascript
     export class InnerHtmlBindingComponent {
       htmlSnippet = 'Template <script>alert("XSS Attack")</script> <b>Code attached</b>';
     }
     ```
     Even though innerHTML binding create a chance of XSS attack, Angular recognizes the value as unsafe and automatically sanitizes it.

     **[⬆ Back to Top](#table-of-contents)**

168. ### How do you prevent automatic sanitization?
     Sometimes the applications genuinely need to include executable code such as displaying `<iframe>` from an URL. In this case, you need to prevent automatic sanitization in Angular by saying that you inspected a value, checked how it was generated, and made sure it will always be secure. Basically it involves 2 steps,

     1. Inject DomSanitizer: You can inject DomSanitizer in component as parameter in constructor
     2. Mark the trusted value by calling some of the below methods

         1. bypassSecurityTrustHtml
         2. bypassSecurityTrustScript
         3. bypassSecurityTrustStyle
         4. bypassSecurityTrustUrl
         5. bypassSecurityTrustResourceUrl

     For example,The  usage of dangerous url to trusted url would be as below,

     ```javascript
     constructor(private sanitizer: DomSanitizer) {
       this.dangerousUrl = 'javascript:alert("XSS attack")';
       this.trustedUrl = sanitizer.bypassSecurityTrustUrl(this.dangerousUrl);
     ```

     **[⬆ Back to Top](#table-of-contents)**

169. ### Is safe to use direct DOM API methods in terms of security?
     No,the built-in browser DOM APIs or methods don't automatically protect you from security vulnerabilities. In this case it is recommended to use Angular templates instead of directly interacting with DOM. If it is unavoidable then use the built-in Angular sanitization functions.

     **[⬆ Back to Top](#table-of-contents)**

170. ### What is DOM sanitizer?
     `DomSanitizer` is used to help preventing Cross Site Scripting Security bugs (XSS) by sanitizing values to be safe to use in the different DOM contexts.

     **[⬆ Back to Top](#table-of-contents)**

171. ### How do you support server side XSS protection in Angular application?
     The server-side XSS protection is supported in an angular application by using a templating language that automatically escapes values to prevent XSS vulnerabilities on the server. But don't use a templating language to generate Angular templates on the server side which creates a high risk of introducing template-injection vulnerabilities.

     **[⬆ Back to Top](#table-of-contents)**

172. ### Is angular prevents http level vulnerabilities?
     Angular has built-in support for preventing http level vulnerabilities such as as cross-site request forgery (CSRF or XSRF) and cross-site script inclusion (XSSI). Even though these vulnerabilities need to be mitigated on server-side, Angular provides helpers to make the integration easier on the client side.
     1. HttpClient supports a token mechanism used to prevent XSRF attacks
     2. HttpClient library recognizes the convention of prefixed JSON responses(which non-executable js code with ")]}',\\n" characters) and automatically strips the string ")]}',\\n" from all responses before further parsing

     **[⬆ Back to Top](#table-of-contents)**

173. ### What are Http Interceptors?
     Http Interceptors are part of @angular/common/http, which inspect and transform HTTP requests from your application to the server and vice-versa on HTTP responses. These interceptors can perform a variety of implicit tasks, from authentication to logging.

     The syntax of HttpInterceptor interface looks like as below,

     ```javascript
     interface HttpInterceptor {
       intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>>
     }
     ```
     You can use interceptors by declaring a service class that implements the intercept() method of the HttpInterceptor interface.

     ```javascript
     @Injectable()
     export class MyInterceptor implements HttpInterceptor {
         constructor() {}
         intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>> {
             ...
         }
     }
     ```
     After that you can use it in your module,

     ```javascript
     @NgModule({
         ...
         providers: [
             {
                 provide: HTTP_INTERCEPTORS,
                 useClass: MyInterceptor,
                 multi: true
             }
         ]
         ...
     })
     export class AppModule {}
     ```

     **[⬆ Back to Top](#table-of-contents)**

174. ### What are the applications of HTTP interceptors?
     The HTTP Interceptors can be used for different variety of tasks,

     1. Authentication
     2. Logging
     3. Caching
     4. Fake backend
     5. URL transformation
     6. Modifying headers

     **[⬆ Back to Top](#table-of-contents)**

175. ### Is multiple interceptors supported in Angular?
     Yes, Angular supports multiple interceptors at a time. You could define multiple interceptors in providers property:
     ```javascript
     providers: [
       { provide: HTTP_INTERCEPTORS, useClass: MyFirstInterceptor, multi: true },
       { provide: HTTP_INTERCEPTORS, useClass: MySecondInterceptor, multi: true }
     ],
     ```
     The interceptors will be called in the order in which they were provided. i.e, MyFirstInterceptor will be called first in the above interceptors configuration.

     **[⬆ Back to Top](#table-of-contents)**

176. ### How can I use interceptor for an entire application?
     You can use same instance of `HttpInterceptors` for the entire app by importing the `HttpClientModule` only in your AppModule, and add the interceptors to the root application injector.
     For example, let's define a class that is injectable in root application.
      ```javascript
      @Injectable()
      export class MyInterceptor implements HttpInterceptor {
        intercept(
          req: HttpRequest<any>,
          next: HttpHandler
        ): Observable<HttpEvent<any>> {

          return next.handle(req).do(event => {
            if (event instanceof HttpResponse) {
                 // Code goes here
            }
          });

        }
      }
      ```
     After that import HttpClientModule in AppModule
     ```javascript
     @NgModule({
       declarations: [AppComponent],
       imports: [BrowserModule, HttpClientModule],
       providers: [
         { provide: HTTP_INTERCEPTORS, useClass: MyInterceptor, multi: true }
       ],
       bootstrap: [AppComponent]
     })
     export class AppModule {}
     ```

     **[⬆ Back to Top](#table-of-contents)**

177. ### How does Angular simplifies Internationalization?

     Angular simplifies the below areas of internationalization,
     1. Displaying dates, number, percentages, and currencies in a local format.
     2. Preparing text in component templates for translation.
     3. Handling plural forms of words.
     4. Handling alternative text.

     **[⬆ Back to Top](#table-of-contents)**

178. ### How do you manually register locale data?
     By default, Angular only contains locale data for en-US which is English as spoken in the United States of America . But if you want to set to another locale, you must import locale data for that new locale. After that you can register using `registerLocaleData` method and the syntax of this method looks like below,
     ```javascript
     registerLocaleData(data: any, localeId?: any, extraData?: any): void
     ```
     For example, let us import German locale and register it in the application
     ```javascript
     import { registerLocaleData } from '@angular/common';
     import localeDe from '@angular/common/locales/de';

     registerLocaleData(localeDe, 'de');
     ```

     **[⬆ Back to Top](#table-of-contents)**


200. ### What is the purpose of hidden property?
     The hidden property is used  to show or hide the associated DOM element, based on an expression. It can be compared close to `ng-show` directive in AngularJS. Let's say you want to show user name based on the availability of user using `hidden` property.
     ```javascript
     <div [hidden]="!user.name">
       My name is: {{user.name}}
     </div>
     ```
     **[⬆ Back to Top](#table-of-contents)**

201. ### What is the difference between ngIf and hidden property?
     The main difference is that *ngIf will remove the element from the DOM, while [hidden] actually plays with the CSS style by setting `display:none`. Generally it is expensive to add and remove stuff from the DOM for frequent actions.

     **[⬆ Back to Top](#table-of-contents)**

202. ### What is slice pipe?
     The slice pipe is used to create a new Array or String containing a subset (slice) of the elements. The syntax looks like as below,
     ```javascript
     {{ value_expression | slice : start [ : end ] }}
     ```
     For example, you can provide 'hello' list based on a greeting array,
     ```javascript
     @Component({
       selector: 'list-pipe',
       template: `<ul>
         <li *ngFor="let i of greeting | slice:0:5">{{i}}</li>
       </ul>`
     })
     export class PipeListComponent {
       greeting: string[] = ['h', 'e', 'l', 'l', 'o', 'm','o', 'r', 'n', 'i', 'n', 'g'];
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

203. ### What is index property in ngFor directive?
     The index property of the NgFor directive is used to return the zero-based index of the item in each iteration. You can capture the index in a template input variable and use it in the template.

     For example, you can capture the index in a variable named indexVar and displays it with the todo's name using ngFor directive as below.
     ```javascript
     <div *ngFor="let todo of todos; let i=index">{{i + 1}} - {{todo.name}}</div>
     ```

     **[⬆ Back to Top](#table-of-contents)**

204. ### What is the purpose of ngFor trackBy?
     The main purpose of using *ngFor with trackBy option is performance optimization. Normally if you use NgFor with large data sets, a small change to one item by removing or adding an item, can trigger a cascade of DOM manipulations. In this case, Angular sees only a fresh list of new object references and to replace the old DOM elements with all new DOM elements. You can help Angular to track which items added or removed by providing a `trackBy` function which takes the index and the current item as arguments and needs to return the unique identifier for this item.

     For example, lets set trackBy to the trackByTodos() method
     ```javascript
     <div *ngFor="let todo of todos; trackBy: trackByTodos">
       ({{todo.id}}) {{todo.name}}
     </div>
     ```
     and define the trackByTodos method,
     ```javascript
     trackByTodos(index: number, item: Todo): number { return todo.id; }
     ```

     **[⬆ Back to Top](#table-of-contents)**

205. ### What is the purpose of ngSwitch directive?
     **NgSwitch** directive is similar to JavaScript switch statement which displays one element from among several possible elements, based on a switch condition. In this case only the selected element placed into the DOM. It has been used along with `NgSwitch`, `NgSwitchCase` and `NgSwitchDefault` directives.

     For example, let's display the browser details based on selected browser using ngSwitch directive.
     ```javascript
     <div [ngSwitch]="currentBrowser.name">
       <chrome-browser    *ngSwitchCase="'chrome'"    [item]="currentBrowser"></chrome-browser>
       <firefox-browser   *ngSwitchCase="'firefox'"     [item]="currentBrowser"></firefox-browser>
       <opera-browser     *ngSwitchCase="'opera'"  [item]="currentBrowser"></opera-browser>
       <safari-browser     *ngSwitchCase="'safari'"   [item]="currentBrowser"></safari-browser>
       <ie-browser  *ngSwitchDefault           [item]="currentItem"></ie-browser>
     </div>
     ```

     **[⬆ Back to Top](#table-of-contents)**

206. ### Is it possible to do aliasing for inputs and outputs?
     Yes, it is possible to do aliasing for inputs and outputs in two ways.
     1. **Aliasing in metadata:** The inputs and outputs in the metadata aliased using a colon-delimited (:) string with the directive property name on the left and the public alias on the right. i.e. It will be in the format of propertyName:alias.
         ```javascript
         inputs: ['input1: buyItem'],
         outputs: ['outputEvent1: completedEvent']
         ```
     2. **Aliasing with @Input()/@Output() decorator:** The alias can be specified for the property name by passing the alias name to the @Input()/@Output() decorator.i.e. It will be in the form of @Input(alias) or @Output(alias).
         ```javascript
         @Input('buyItem') input1: string;
         @Output('completedEvent') outputEvent1 = new EventEmitter<string>();
         ```

     **[⬆ Back to Top](#table-of-contents)**

207. ### What is safe navigation operator?
     The safe navigation operator(?)(or known as Elvis Operator) is used to guard against `null` and `undefined` values in property paths when you are not aware whether a path exists or not. i.e. It returns value of the object path if it exists, else it returns the null value.

     For example, you can access nested properties of a user profile easily without null reference errors as below,
     ```javascript
     <p>The user firstName is: {{user?.fullName.firstName}}</p>
     ```
     Using this safe navigation operator, Angular framework stops evaluating the expression when it hits the first null value and renders the view without any errors.

     **[⬆ Back to Top](#table-of-contents)**


211. ### What are the list of template expression operators?
     The Angular template expression language supports three special template expression operators.
     1. Pipe operator
     2. Safe navigation operator
     3. Non-null assertion operator

     **[⬆ Back to Top](#table-of-contents)**

212. ### What is the precedence between pipe and ternary operators?
     The pipe operator has a higher precedence than the ternary operator (?:). For example, the expression `first ? second : third | fourth` is parsed as `first ? second : (third | fourth)`.

     **[⬆ Back to Top](#table-of-contents)**

213. ### What is an entry component?
     An entry component is any component that Angular loads imperatively(i.e, not referencing it in the template) by type. Due to this behavior, they can’t be found by the Angular compiler during compilation. These components created dynamically with `ComponentFactoryResolver`.

     Basically, there are two main kinds of entry components which are following -
     1. The bootstrapped root component
     2. A component you specify in a route

     **[⬆ Back to Top](#table-of-contents)**
214. ### What is a bootstrapped component?
     A bootstrapped component is an entry component that Angular loads into the DOM during the bootstrap process or application launch time. Generally, this bootstrapped or root component is named as `AppComponent` in your root module using `bootstrap` property as below.
     ```js
     @NgModule({
       declarations: [
         AppComponent
       ],
       imports: [
         BrowserModule,
         FormsModule,
         HttpClientModule,
         AppRoutingModule
       ],
       providers: [],
       bootstrap: [AppComponent] // bootstrapped entry component need to be declared here
     })
     ```

     **[⬆ Back to Top](#table-of-contents)**
215. ### How do you manually bootstrap an application?
     You can use `ngDoBootstrap` hook for a manual bootstrapping of the application instead of using bootstrap array in `@NgModule` annotation. This hook is part of `DoBootstap` interface.
     ```js
     interface DoBootstrap {
       ngDoBootstrap(appRef: ApplicationRef): void
     }
     ```
     The module needs to be implement the above interface to use the hook for bootstrapping.
     ```js
     class AppModule implements DoBootstrap {
       ngDoBootstrap(appRef: ApplicationRef) {
         appRef.bootstrap(AppComponent); // bootstrapped entry component need to be passed
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

216. ### Is it necessary for bootstrapped component to be entry component?
     Yes, the bootstrapped component needs to be an entry component. This is because the bootstrapping process is an imperative process.

     **[⬆ Back to Top](#table-of-contents)**

217. ### What is a routed entry component?
     The components referenced in router configuration are called as routed entry components. This routed entry component defined in a route definition as below,
     ```js
     const routes: Routes = [
       {
         path: '',
         component: TodoListComponent // router entry component
       }
     ];
     ```
     Since router definition requires you to add the component in two places (router and entryComponents), these components are always entry components.

     **Note:** The compilers are smart enough to recognize a router definition and automatically add the router component into `entryComponents`.

     **[⬆ Back to Top](#table-of-contents)**

218. ### Why is not necessary to use entryComponents array every time?
     Most of the time, you don't need to explicity to set entry components in entryComponents array of ngModule decorator. Because angular adds components from both @NgModule.bootstrap and route definitions to entry components automatically.

     **[⬆ Back to Top](#table-of-contents)**

219. ### Do I still need to use entryComponents array in Angular9?
     No. In previous angular releases, the entryComponents array of ngModule decorator is used to tell the compiler which components would be created and inserted dynamically in the view. In Angular9, this is not required anymore with Ivy.

     **[⬆ Back to Top](#table-of-contents)**

220. ### Is it all components generated in production build?
     No, only the entry components and template components appears in production builds. If a component isn't an entry component and isn't found in a template, the tree shaker will throw it away. Due to this reason, make sure to add only true entry components to reduce the bundle size.

     **[⬆ Back to Top](#table-of-contents)**

221. ### What is Angular compiler?
     The Angular compiler is used to convert the application code into JavaScript code. It reads the template markup, combines it with the corresponding component class code, and emits component factories which creates JavaScript representation of the component along with elements of @Component metadata.

     **[⬆ Back to Top](#table-of-contents)**

222. ### What is the role of ngModule metadata in compilation process?
     The `@NgModule` metadata is used to tell the Angular compiler what components to be compiled for this module and how to link this module with other modules.

     **[⬆ Back to Top](#table-of-contents)**

223. ### How does angular finds components, directives and pipes?
     The Angular compiler finds a component or directive in a template when it can match the selector of that component or directive in that template. Whereas it finds a pipe if the pipe's name appears within the pipe syntax of the template HTML.

     **[⬆ Back to Top](#table-of-contents)**

225. ### What are feature modules?
     Feature modules are NgModules, which are used for the purpose of organizing code. The feature module can be created with Angular CLI using the below command in the root directory,
     ```javascript
     ng generate module MyCustomFeature //
     ```
     Angular CLI creates a folder called `my-custom-feature` with a file inside called `my-custom-feature.module.ts` with the following contents
     ```javascript
     import { NgModule } from '@angular/core';
     import { CommonModule } from '@angular/common';

     @NgModule({
       imports: [
         CommonModule
       ],
       declarations: []
     })
     export class MyCustomFeature { }
     ```

     **Note:**  The "Module" suffix shouldn't present in the name because the CLI appends it.

     **[⬆ Back to Top](#table-of-contents)**

226. ### What are the imported modules in CLI generated feature modules?
     In the CLI generated feature module, there are two JavaScript import statements at the top of the file
     1. **NgModule:** InOrder to use the `@NgModule` decorator
     2. **CommonModule:** It provides many common directives such as `ngIf` and `ngFor`.

     **[⬆ Back to Top](#table-of-contents)**

228. ### What are the possible errors with declarations?
     There are two common possible errors with declarations array,
     1. If you use a component without declaring it, Angular returns an error message.
     2. If you try to declare the same class in more than one module then compiler emits an error.

     **[⬆ Back to Top](#table-of-contents)**

229. ### What are the steps to use declaration elements?
     Below are the steps to be followed to use declaration elements.
     1. Create the element(component, directive and pipes) and export it from the file where you wrote it
     2. Import it into the appropriate module.
     3. Declare it in the @NgModule declarations array.


     **[⬆ Back to Top](#table-of-contents)**

230. ### What happens if browserModule used in feature module?
     If you do import `BrowserModule` into a lazy loaded feature module, Angular returns an error telling you to use `CommonModule` instead. Because BrowserModule’s providers are for the entire app so it should only be in the root module, not in feature module. Whereas Feature modules only need the common directives in CommonModule.

     ![ScreenShot](images/browser-module-error.gif)

     **[⬆ Back to Top](#table-of-contents)**

231. ### What are the types of feature modules?
     Below are the five categories of feature modules,
     1. **Domain:** Deliver a user experience dedicated to a particular application domain(For example, place an order, registration etc)
     2. **Routed:** These are domain feature modules whose top components are the targets of router navigation routes.
     3. **Routing:** It provides routing configuration for another module.
     4. **Service:** It provides utility services such as data access and messaging(For example, HttpClientModule)
     5. **Widget:** It makes components, directives, and pipes available to external modules(For example, third-party libraries such as Material UI)

     **[⬆ Back to Top](#table-of-contents)**

232. ### What is a provider?
     A provider is an instruction to the Dependency Injection system on how to obtain a value for a dependency(aka services created). The service can be provided using Angular CLI as below,
     ```javascript
     ng generate service my-service
     ```
     The created service by CLI would be as below,
     ```js
     import { Injectable } from '@angular/core';

     @Injectable({
       providedIn: 'root', //Angular provide the service in root injector
     })
     export class MyService {
     }
     ```
     **[⬆ Back to Top](#table-of-contents)**

233. ### What is the recommendation for provider scope?
     You should always provide your service in the root injector unless there is a case where you want the service to be available only if you import a particular @NgModule.

     **[⬆ Back to Top](#table-of-contents)**

234. ### How do you restrict provider scope to a module?
     It is possible to restrict service provider scope to a specific module instead making available to entire application. There are two possible ways to do it.
     1. **Using providedIn in service:**
         ```js
         import { Injectable } from '@angular/core';
         import { SomeModule } from './some.module';

         @Injectable({
           providedIn: SomeModule,
         })
         export class SomeService {
         }
         ```
     2. **Declare provider for the service in module:**
         ```js
         import { NgModule } from '@angular/core';

         import { SomeService } from './some.service';

         @NgModule({
           providers: [SomeService],
         })
         export class SomeModule {
         }
         ```

     **[⬆ Back to Top](#table-of-contents)**

235. ### How do you provide a singleton service?
     There are two possible ways to provide a singleton service.
     1. Set the providedIn property of the @Injectable() to "root". This is the preferred way(starting from Angular 6.0) of creating a singleton service since it makes your services tree-shakable.

         ```js
         import { Injectable } from '@angular/core';

         @Injectable({
           providedIn: 'root',
         })
         export class MyService {
         }
         ```
     2. Include the service in root module or in a module that is only imported by root module. It has been used to register services before Angular 6.0.

         ```js
         @NgModule({
           ...
           providers: [MyService],
           ...
         })
         ```

     **[⬆ Back to Top](#table-of-contents)**

236. ### What are the different ways to remove duplicate service registration?
     If a module defines provides and declarations then loading the module in multiple feature modules will duplicate the registration of the service. Below are the different ways to prevent this duplicate behavior.
     1. Use the providedIn syntax instead of registering the service in the module.
     2. Separate your services into their own module.
     3. Define forRoot() and forChild() methods in the module.

     **[⬆ Back to Top](#table-of-contents)**

237. ### How does forRoot method helpful to avoid duplicate router instances?
     If the `RouterModule` module didn’t have forRoot() static method then each feature module would instantiate a new Router instance, which leads to broken application due to duplicate instances. After using forRoot() method, the root application module imports `RouterModule.forRoot(...)` and gets a Router, and all feature modules import `RouterModule.forChild(...)` which does not instantiate another Router.

     **[⬆ Back to Top](#table-of-contents)**

238. ### What is a shared module?
     The Shared Module is the module in which you put commonly used directives, pipes, and components into one module that is shared(import it) throughout the application.

     For example, the below shared module imports CommonModule, FormsModule for common directives and components, pipes and directives based on the need,
     ```js
     import { CommonModule } from '@angular/common';
     import { NgModule } from '@angular/core';
     import { FormsModule } from '@angular/forms';
     import { UserComponent } from './user.component';
     import { NewUserDirective } from './new-user.directive';
     import { OrdersPipe } from './orders.pipe';

     @NgModule({
      imports:      [ CommonModule ],
      declarations: [ UserComponent, NewUserDirective, OrdersPipe ],
      exports:      [ UserComponent, NewUserDirective, OrdersPipe,
                      CommonModule, FormsModule ]
     })
     export class SharedModule { }
     ```

     **[⬆ Back to Top](#table-of-contents)**

239. ### Can I share services using modules?
     No, it is not recommended to share services by importing module. i.e Import modules when you want to use directives, pipes, and components only. The best approach to get a hold of shared services is through 'Angular dependency injection' because importing a module will result in a new service instance.

     **[⬆ Back to Top](#table-of-contents)**

240. ### How do you get current direction for locales?
     In Angular 9.1, the API method `getLocaleDirection` can be used to get the current direction in your app. This method is useful to support Right to Left locales for your Internationalization based applications.
     ```js
     import { getLocaleDirection, registerLocaleData } from '@angular/common';
     import { LOCALE_ID } from '@angular/core';
     import localeAr from '@angular/common/locales/ar';

       ...

       constructor(@Inject(LOCALE_ID) locale) {

         const directionForLocale = getLocaleDirection(locale); // Returns 'rtl' or 'ltr' based on the current locale
         registerLocaleData(localeAr, 'ar-ae');
         const direction = getLocaleDirection('ar-ae'); // Returns 'rtl'

         // Current direction is used to provide conditional logic here
       }
     ```

     **[⬆ Back to Top](#table-of-contents)**

241. ### What is ngcc?
     The ngcc(Angular Compatibility Compiler) is a tool which upgrades node_module compiled with non-ivy ngc into ivy compliant format. The `postinstall` script from package.json will make sure your node_modules will be compatible with the Ivy renderer.
     ```js
     "scripts": {
        "postinstall": "ngcc"
     }
     ```

     Whereas, Ivy compiler (ngtsc), which compiles Ivy-compatible code.

     **[⬆ Back to Top](#table-of-contents)**

242. ### What classes should not be added to declarations?
     The below class types shouldn't be added to declarations
     1. A class which is already declared in any another module.
     2. Directives imported from another module.
     3. Module classes.
     4. Service classes.
     5. Non-Angular classes and objects, such as strings, numbers, functions, entity models, configurations, business logic, and helper classes.

     **[⬆ Back to Top](#table-of-contents)**

243. ### What is NgZone?
     Angular provides a service called NgZone which creates a zone named `angular` to automatically trigger change detection when the following conditions are satisfied.
     1. When a sync or async function is executed.
     2. When there is no microTask scheduled.

     **[⬆ Back to Top](#table-of-contents)**

244. ### What is NoopZone?
     Zone is loaded/required by default in Angular applications and it helps Angular to know when to trigger the change detection. This way, it make sures developers focus on application development rather core part of Angular. You can also use Angular without Zone but the change detection need to be implemented on your own and `noop zone` need to be configured in bootstrap process.
     Let's follow the below two steps to remove zone.js,
     1. Remove the zone.js import from polyfills.ts.
         ```js
         /***************************************************************************************************
          * Zone JS is required by default for Angular itself.
          */
         // import 'zone.js/dist/zone';  // Included with Angular CLI.
         ```
     2. Bootstrap Angular with noop zone in src/main.ts.
         ```js
         platformBrowserDynamic().bootstrapModule(AppModule, {ngZone: 'noop'})
           .catch(err => console.error(err));
         ```
     **[⬆ Back to Top](#table-of-contents)**

245. ### How do you create displayBlock components?
     By default, Angular CLI creates components in an inline displayed mode(i.e, display:inline). But it is possible to create components with display: block style using `displayBlock` option,
     ```js
     ng generate component my-component --displayBlock
     ```
     (OR) the option can be turned on by default in Angular.json with `schematics.@schematics/angular:component.displayBlock` key value as true.

     **[⬆ Back to Top](#table-of-contents)**

246. ### What are the possible data update scenarios for change detection?
     The change detection works in the following scenarios where the data changes needs to update the application HTML.
     1. **Component initialization:** While bootstrapping the Angular application, Angular triggers the `ApplicationRef.tick()` to call change detection and View Rendering.
     2. **Event listener:**  The DOM event listener can update the data in an Angular component and trigger the change detection too.
         ```js
         @Component({
           selector: 'app-event-listener',
           template: `
             <button (click)="onClick()">Click</button>
             {{message}}`
         })
         export class EventListenerComponent {
           message = '';

           onClick() {
             this.message = 'data updated';
           }
         }
         ```
     3. **HTTP Data Request:** You can get data from a server through an HTTP request
         ```js
         data = 'default value';
         constructor(private httpClient: HttpClient) {}

           ngOnInit() {
             this.httpClient.get(this.serverUrl).subscribe(response => {
               this.data = response.data; // change detection will happen automatically
             });
           }
         ```
     4. **Macro tasks setTimeout() or setInterval():** You can update the data in the callback function of setTimeout or setInterval
         ```js
         data = 'default value';

           ngOnInit() {
             setTimeout(() => {
               this.data = 'data updated'; // Change detection will happen automatically
             });
           }
         ```
     5. **Micro tasks Promises:** You can update the data in the callback function of promise
         ```js
         data = 'initial value';

           ngOnInit() {
             Promise.resolve(1).then(v => {
               this.data = v; // Change detection will happen automatically
             });
           }
         ```
     6. **Async operations like Web sockets and Canvas:** The data can be updated asynchronously using WebSocket.onmessage() and Canvas.toBlob().

     **[⬆ Back to Top](#table-of-contents)**

247. ### What is a zone context?
      Execution Context is an abstract concept that holds information about the environment within the current code being executed. A zone provides an execution context that persists across asynchronous operations is called as zone context. For example, the zone context will be same in both outside and inside setTimeout callback function,
      ```js
      zone.run(() => {
        // outside zone
        expect(zoneThis).toBe(zone);
        setTimeout(function() {
          // the same outside zone exist here
          expect(zoneThis).toBe(zone);
        });
      });
      ```
      The current zone is retrieved through `Zone.current`.

     **[⬆ Back to Top](#table-of-contents)**

248. ### What are the lifecycle hooks of a zone?
     There are four lifecycle hooks for asynchronous operations from zone.js.
     1. **onScheduleTask:** This hook triggers when a new asynchronous task is scheduled. For example, when you call setTimeout()
         ```js
         onScheduleTask: function(delegate, curr, target, task) {
             console.log('new task is scheduled:', task.type, task.source);
             return delegate.scheduleTask(target, task);
           }
         ```
     2. **onInvokeTask:** This hook triggers when an asynchronous task is about to execute. For example, when the callback of setTimeout() is about to execute.
         ```js
         onInvokeTask: function(delegate, curr, target, task, applyThis, applyArgs) {
             console.log('task will be invoked:', task.type, task.source);
             return delegate.invokeTask(target, task, applyThis, applyArgs);
           }
         ```
     3. **onHasTask:** This hook triggers when the status of one kind of task inside a zone changes from stable(no tasks in the zone) to unstable(a new task is scheduled in the zone) or from unstable to stable.
         ```js
           onHasTask: function(delegate, curr, target, hasTaskState) {
             console.log('task state changed in the zone:', hasTaskState);
             return delegate.hasTask(target, hasTaskState);
           }
         ```
     4. **onInvoke:** This hook triggers when a synchronous function is going to execute in the zone.
         ```js
         onInvoke: function(delegate, curr, target, callback, applyThis, applyArgs) {
             console.log('the callback will be invoked:', callback);
             return delegate.invoke(target, callback, applyThis, applyArgs);
           }
         ```

     **[⬆ Back to Top](#table-of-contents)**

249. ### What are the methods of NgZone used to control change detection?
     NgZone service provides a `run()` method that allows you to execute a function inside the angular zone. This function is used to execute third party APIs which are not handled by Zone and trigger change detection automatically at the correct time.
     ```js
     export class AppComponent implements OnInit {
       constructor(private ngZone: NgZone) {}
       ngOnInit() {
         // use ngZone.run() to make the asynchronous operation in the angular zone
         this.ngZone.run(() => {
           someNewAsyncAPI(() => {
             // update the data of the component
           });
         });
       }
     }
     ```
     Whereas `runOutsideAngular()` method is used when you don't want to trigger change detection.
     ```js
     export class AppComponent implements OnInit {
       constructor(private ngZone: NgZone) {}
       ngOnInit() {
         // Use this method when you know no data will be updated
         this.ngZone.runOutsideAngular(() => {
           setTimeout(() => {
             // update component data and don't trigger change detection
           });
         });
       }
     }
     ```
     **[⬆ Back to Top](#table-of-contents)**

250. ### How do you change the settings of zonejs?
     You can change the settings of zone by configuring them in a separate file and import it just after zonejs import.
     For example, you can disable the requestAnimationFrame() monkey patch to prevent change detection for no data update as one setting and prevent DOM events(a mousemove or scroll event) to trigger change detection. Let's say the new file named zone-flags.js,
     ```js
     // disable patching requestAnimationFrame
     (window as any).__Zone_disable_requestAnimationFrame = true;

     // disable patching specified eventNames
     (window as any).__zone_symbol__UNPATCHED_EVENTS = ['scroll', 'mousemove'];
     ```
     The above configuration file can be imported in a polyfill.ts file as below,
     ```js
     /***************************************************************************************************
      * Zone JS is required by default for Angular.
      */
     import `./zone-flags`;
     import 'zone.js/dist/zone';  // Included with Angular CLI.
     ```
     **[⬆ Back to Top](#table-of-contents)**

251. ### How do you trigger an animation?
     Angular provides a `trigger()` function for animation in order to collect the states and transitions with a specific animation name, so that you can attach it to the triggering element in the HTML template. This function watch for changes and trigger initiates the actions when a change occurs.
     For example, let's create trigger named `upDown`, and attach it to the button element.
     ```js
     content_copy
     @Component({
       selector: 'app-up-down',
       animations: [
         trigger('upDown', [
           state('up', style({
             height: '200px',
             opacity: 1,
             backgroundColor: 'yellow'
           })),
           state('down', style({
             height: '100px',
             opacity: 0.5,
             backgroundColor: 'green'
           })),
           transition('up => down', [
             animate('1s')
           ]),
           transition('down => up', [
             animate('0.5s')
           ]),
         ]),
       ],
       templateUrl: 'up-down.component.html',
       styleUrls: ['up-down.component.css']
     })
     export class UpDownComponent {
       isUp = true;

       toggle() {
         this.isUp = !this.isUp;
       }

     ```

     **[⬆ Back to Top](#table-of-contents)**

252. ### How do you configure injectors with providers at different levels?
     You can configure injectors with providers at different levels of your application by setting a metadata value. The configuration can happen in one of three places,
     1. In the `@Injectable()` decorator for the service itself
     2. In the `@NgModule()` decorator for an NgModule
     3. In the `@Component()` decorator for a component

     **[⬆ Back to Top](#table-of-contents)**

253. ### Is it mandatory to use injectable on every service class?
     No. The `@Injectable()` decorator is not strictly required if the class has other Angular decorators on it or does not have any dependencies. But the important thing here is any class that is going to be injected with Angular is decorated.
     i.e, If we add the decorator, the metadata `design:paramtypes` is added, and the dependency injection can do it's job. That is the exact reason to add the @Injectable() decorator on a service if this service has some dependencies itself.
     For example, Let's see the different variations of AppService in a root component,
     1. The below AppService can be injected in AppComponent without any problems. This is because there are no dependency services inside AppService.
         ```js
         export class AppService {
           constructor() {
             console.log('A new app service');
           }
         }
         ```
     2. The below AppService with dummy decorator and httpService can be injected in AppComponent without any problems. This is because meta information is generated with dummy decorator.
         ```js
         function SomeDummyDecorator() {
           return (constructor: Function) => console.log(constructor);
         }

         @SomeDummyDecorator()
         export class AppService {
           constructor(http: HttpService) {
             console.log(http);
           }
         }
         ```
     and the generated javascript code of above service has meta information about HttpService,
         ```js
         var AppService = (function () {
             function AppService(http) {
                 console.log(http);
             }
             AppService = __decorate([
                 core_1.Injectable(),
                 __metadata('design:paramtypes', [http_service_1.HttpService])
             ], AppService);
             return AppService;
         }());
         exports.AppService = AppService;
         ```
     3. The below AppService with @injectable decorator and httpService can be injected in AppComponent without any problems. This is because meta information is generated with Injectable decorator.
         ```js
         @Injectable({
           providedIn: 'root',
         })
         export class AppService {
           constructor(http: HttpService) {
             console.log(http);
           }
         }
         ```
     **[⬆ Back to Top](#table-of-contents)**

254. ### What is an optional dependency?
     The optional dependency is a parameter decorator to be used on constructor parameters, which marks the parameter as being an optional dependency. Due to this, the DI framework provides null if the dependency is not found.
     For example, If you don't register a logger provider anywhere, the injector sets the value of logger(or logger service) to null in the below class.
     ```js
     import { Optional } from '@angular/core';

     constructor(@Optional() private logger?: Logger) {
       if (this.logger) {
         this.logger.log('This is an optional dependency message');
       } else {
         console.log('The logger is not registered');
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

255. ### What are the types of injector hierarchies?
     There are two types of injector hierarchies in Angular

     1. **ModuleInjector hierarchy:** It configure on a module level using an @NgModule() or @Injectable() annotation.
     2. **ElementInjector hierarchy:** It created implicitly at each DOM element. Also it is empty by default unless you configure it in the providers property on @Directive() or @Component().

     **[⬆ Back to Top](#table-of-contents)**

256. ### What are reactive forms?
     Reactive forms is a model-driven approach for creating forms in a reactive style(form inputs changes over time). These are built around observable streams, where form inputs and values are provided as streams of input values. Let's follow the below steps to create reactive forms,
     1. Register the reactive forms module which declares reactive-form directives in your app
         ```js
         import { ReactiveFormsModule } from '@angular/forms';

         @NgModule({
           imports: [
             // other imports ...
             ReactiveFormsModule
           ],
         })
         export class AppModule { }
         ```
     2. Create a new FormControl instance and save it in the component.
         ```js
         import { Component } from '@angular/core';
         import { FormControl } from '@angular/forms';

         @Component({
           selector: 'user-profile',
           styleUrls: ['./user-profile.component.css']
         })
         export class UserProfileComponent {
           userName = new FormControl('');
         }
         ```
     3. Register the FormControl in the template.
         ```js
         <label>
           User name:
           <input type="text" [formControl]="userName">
         </label>
         ```
     Finally, the component with reactive form control appears as below,
     ```js
     import { Component } from '@angular/core';
     import { FormControl } from '@angular/forms';
	
     @Component({
       selector: 'user-profile',
       styleUrls: ['./user-profile.component.css'],
       template: `
         <label>
           User name:
           <input type="text" [formControl]="userName">
         </label>
       `
     })
     export class UserProfileComponent {
       userName = new FormControl('');
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

257. ### What are dynamic forms?
     Dynamic forms is a pattern in which we build a form dynamically based on metadata that describes a business object model. You can create them based on reactive form API.
     **[⬆ Back to Top](#table-of-contents)**


258. ### What are template driven forms?
     Template driven forms are model-driven forms where you write the logic, validations, controls etc, in the template part of the code using directives. They are suitable for simple scenarios and uses two-way binding with [(ngModel)] syntax.
     For example, you can create register form easily by following the below simple steps,

     1. Import the FormsModule into the Application module's imports array
         ```js
            import { BrowserModule } from '@angular/platform-browser';
            import { NgModule } from '@angular/core';
            import {FormsModule} from '@angular/forms'
            import { RegisterComponent } from './app.component';
            @NgModule({
              declarations: [
                RegisterComponent,
              ],
              imports: [
                BrowserModule,
                FormsModule
              ],
              providers: [],
              bootstrap: [RegisterComponent]
            })
            export class AppModule { }
         ```
     2. Bind the form from template to the component using ngModel syntax
         ```html
         <input type="text" class="form-control" id="name"
           required
           [(ngModel)]="model.name" name="name">
         ```
     3.  Attach NgForm directive to the <form> tag in order to create FormControl instances and register them
         ```js
         <form #registerForm="ngForm">
         ```
     4. Apply the validation message for form controls
         ```html
         <label for="name">Name</label>
         <input type="text" class="form-control" id="name"
                required
                [(ngModel)]="model.name" name="name"
                #name="ngModel">
         <div [hidden]="name.valid || name.pristine"
              class="alert alert-danger">
           Please enter your name
         </div>
         ```
     5. Let's submit the form with ngSubmit directive and add type="submit" button at the bottom of the form to trigger form submit.
         ```html
         <form (ngSubmit)="onSubmit()" #heroForm="ngForm">
         // Form goes here
         <button type="submit" class="btn btn-success" [disabled]="!registerForm.form.valid">Submit</button>
         ```
     Finally, the completed template-driven registration form will be appeared as follow.
     ```html
     <div class="container">
       <h1>Registration Form</h1>
       <form (ngSubmit)="onSubmit()" #registerForm="ngForm">
         <div class="form-group">
           <label for="name">Name</label>
             <input type="text" class="form-control" id="name"
                    required
                    [(ngModel)]="model.name" name="name"
                    #name="ngModel">
             <div [hidden]="name.valid || name.pristine"
                  class="alert alert-danger">
               Please enter your name
             </div>
         </div>
         <button type="submit" class="btn btn-success" [disabled]="!registerForm.form.valid">Submit</button>
         </form>
     </div>
     ```

     **[⬆ Back to Top](#table-of-contents)**

259. ### What are the differences between reactive forms and template driven forms?
     Below are the main differences between reactive forms and template driven forms

     | Feature | Reactive | Template-Driven |
     |---- |---- | --------- |
     | Form model setup | Created(FormControl instance) in component explicitly | Created by directives  |
     | Data updates | Synchronous | Asynchronous |
     | Form custom validation | Defined as Functions | Defined as Directives |
     | Testing | No interaction with change detection cycle | Need knowledge of the change detection process |
     | Mutability | Immutable(by always returning new value for FormControl instance) | Mutable(Property always modified to new value) |
     | Scalability | More scalable using low-level APIs | Less scalable using due to abstraction on APIs|

     **[⬆ Back to Top](#table-of-contents)**


260. ### What are the different ways to group form controls?
     Reactive forms provide two ways of grouping multiple related controls.
     1. **FormGroup**: It defines a form with a fixed set of controls those can be managed together in an one object. It has same properties and methods similar to a FormControl instance.
        This FormGroup can be nested to create complex forms as below.
        ```js
        import { Component } from '@angular/core';
        import { FormGroup, FormControl } from '@angular/forms';

        @Component({
          selector: 'user-profile',
          templateUrl: './user-profile.component.html',
          styleUrls: ['./user-profile.component.css']
        })
        export class UserProfileComponent {
          userProfile = new FormGroup({
            firstName: new FormControl(''),
            lastName: new FormControl(''),
            address: new FormGroup({
                  street: new FormControl(''),
                  city: new FormControl(''),
                  state: new FormControl(''),
                  zip: new FormControl('')
                })
          });

          onSubmit() {
            // Store this.userProfile.value in DB
          }
        }
        ```
        ```html
        <form [formGroup]="userProfile" (ngSubmit)="onSubmit()">

          <label>
            First Name:
            <input type="text" formControlName="firstName">
          </label>

          <label>
            Last Name:
            <input type="text" formControlName="lastName">
          </label>

          <div formGroupName="address">
            <h3>Address</h3>

            <label>
              Street:
              <input type="text" formControlName="street">
            </label>

            <label>
              City:
              <input type="text" formControlName="city">
            </label>

            <label>
              State:
              <input type="text" formControlName="state">
            </label>

            <label>
              Zip Code:
              <input type="text" formControlName="zip">
            </label>
           </div>
            <button type="submit" [disabled]="!userProfile.valid">Submit</button>

        </form>
        ```
     2. **FormArray:** It defines a dynamic form in an array format, where you can add and remove controls at run time. This is useful for dynamic forms when you don’t know how many controls will be present within the group.
           ```js
            import { Component } from '@angular/core';
            import { FormArray, FormControl } from '@angular/forms';

            @Component({
              selector: 'order-form',
              templateUrl: './order-form.component.html',
              styleUrls: ['./order-form.component.css']
            })
            export class OrderFormComponent {
              constructor () {
                this.orderForm = new FormGroup({
                  firstName: new FormControl('John', Validators.minLength(3)),
                  lastName: new FormControl('Rodson'),
                  items: new FormArray([
                    new FormControl(null)
                  ])
                });
              }

              onSubmitForm () {
                // Save the items this.orderForm.value in DB
              }

              onAddItem () {
                this.orderForm.controls
                .items.push(new FormControl(null));
              }

              onRemoveItem (index) {
                this.orderForm.controls['items'].removeAt(index);
              }
            }
           ```
           ```html
           <form [formControlName]="orderForm" (ngSubmit)="onSubmit()">

             <label>
               First Name:
               <input type="text" formControlName="firstName">
             </label>

             <label>
               Last Name:
               <input type="text" formControlName="lastName">
             </label>

             <div>
             <p>Add items</p>
             <ul formArrayName="items">
               <li *ngFor="let item of orderForm.controls.items.controls; let i = index">
                 <input type="text" formControlName="{{i}}">
                 <button type="button" title="Remove Item" (click)="onRemoveItem(i)">Remove</button>
               </li>
             </ul>
             <button type="button" (click)="onAddItem">
               Add an item
             </button>
            </div>
           ```

     **[⬆ Back to Top](#table-of-contents)**

261. ### How do you update specific properties of a form model?
     You can use `patchValue()` method to update specific properties defined in the form model. For example,you can update the name and street of certain profile on click of the update button as shown below.
     ```js
     updateProfile() {
       this.userProfile.patchValue({
         firstName: 'John',
         address: {
           street: '98 Crescent Street'
         }
       });
     }
     ```
     ```html
       <button (click)="updateProfile()">Update Profile</button>
     ```

     You can also use `setValue` method to update properties.

     **Note:** Remember to update the properties against the exact model structure.

     **[⬆ Back to Top](#table-of-contents)**

262. ### What is the purpose of FormBuilder?
     FormBuilder is used as syntactic sugar for easily creating instances of a FormControl, FormGroup, or FormArray. This is helpful to reduce the amount of boilerplate needed to build complex reactive forms. It is available as an injectable helper class of the `@angular/forms` package.

     For example, the user profile component creation becomes easier as shown here.
     ```js
     export class UserProfileComponent {
       profileForm = this.formBuilder.group({
         firstName: [''],
         lastName: [''],
         address: this.formBuilder.group({
           street: [''],
           city: [''],
           state: [''],
           zip: ['']
         }),
       });
       constructor(private formBuilder: FormBuilder) { }
       }
     ```
     **[⬆ Back to Top](#table-of-contents)**

263. ### How do you verify the model changes in forms?
     You can add a getter property(let's say, diagnostic) inside component to return a JSON representation of the model during the development. This is useful to verify whether the values are really flowing from the input box to the model and vice versa or not.
     ```js
     export class UserProfileComponent {

       model = new User('John', 29, 'Writer');

       // TODO: Remove after the verification
       get diagnostic() { return JSON.stringify(this.model); }
     }
     ```
     and add `diagnostic` binding near the top of the form
     ```html
     {{diagnostic}}
     <div class="form-group">
       // FormControls goes here
     </div>
     ```

     **[⬆ Back to Top](#table-of-contents)**

264. ### What are the state CSS classes provided by ngModel?
     The ngModel directive updates the form control with special Angular CSS classes to reflect it's state. Let's find the list of classes in a tabular format,

     | Form control state | If true | If false |
     |---- | --------- | --- |
     | Visited | ng-touched | ng-untouched |
     | Value has changed | ng-dirty	 | ng-pristine |
     | Value is valid| 	ng-valid | ng-invalid |

     **[⬆ Back to Top](#table-of-contents)**

265. ### How do you reset the form?
     In a model-driven form, you can reset the form just by calling the function `reset()` on our form model.
     For example, you can reset the form model on submission as follows,
     ```js
     onSubmit() {
       if (this.myform.valid) {
         console.log("Form is submitted");
         // Perform business logic here
         this.myform.reset();
       }
     }
     ```
     Now, your form model resets the form back to its original pristine state.

     **[⬆ Back to Top](#table-of-contents)**

266. ### What are the types of validator functions?
     In reactive forms, the validators can be either synchronous or asynchronous functions,
     1. **Sync validators:** These are the synchronous functions which take a control instance and immediately return either a set of validation errors or null. Also, these functions passed as second argument while instantiating the form control. The main use cases are simple checks like whether a field is empty, whether it exceeds a maximum length etc.
     2. **Async validators:** These are the asynchronous functions which take a control instance and return a Promise or Observable that later emits a set of validation errors or null. Also, these functions passed as second argument while instantiating the form control. The main use cases are complex validations like hitting a server to check the availability of a username or email.

     The representation of these validators looks like below
     ```js
     this.myForm = formBuilder.group({
         firstName: ['value'],
         lastName: ['value', *Some Sync validation function*],
         email: ['value', *Some validation function*, *Some asynchronous validation function*]
     });
     ```

     **[⬆ Back to Top](#table-of-contents)**

267. ### Can you give an example of built-in validators?
     In reactive forms, you can use built-in validator like `required` and `minlength` on your input form controls. For example, the registration form can have these validators on name input field
     ```js
     this.registrationForm = new FormGroup({
         'name': new FormControl(this.hero.name, [
           Validators.required,
           Validators.minLength(4),
         ])
       });
     ```
     Whereas in template-driven forms, both `required` and `minlength` validators available as attributes.

     **[⬆ Back to Top](#table-of-contents)**

268. ### How do you optimize the performance of async validators?
     Since all validators run after every form value change, it creates a major impact on performance with async validators by hitting the external API on each keystroke. This situation can be avoided by delaying the form validity by changing the updateOn property from change (default) to submit or blur.
     The usage would be different based on form types,
     1. **Template-driven forms:** Set the property on `ngModelOptions` directive
         ```html
         <input [(ngModel)]="name" [ngModelOptions]="{updateOn: 'blur'}">
         ```
     2. **Reactive-forms:** Set the property on FormControl instance
         ```js
         name = new FormControl('', {updateOn: 'blur'});
         ```

     **[⬆ Back to Top](#table-of-contents)**

269. ### How to set ngFor and ngIf on the same element?
     Sometimes you may need to both ngFor and ngIf on the same element but unfortunately you are going to encounter below template error.
     ```cmd
      Template parse errors: Can't have multiple template bindings on one element.
     ```
      In this case, You need to use either ng-container or ng-template.
      Let's say if you try to loop over the items only when the items are available, the below code throws an error in the browser
      ```html
      <ul *ngIf="items" *ngFor="let item of items">
        <li></li>
      </ul>
      ```
      and it can be fixed by
      ```html
      <ng-container *ngIf="items">
        <ul *ngFor="let item of items">
          <li></li>
        </ul>
      </ng-container>
      ```

     **[⬆ Back to Top](#table-of-contents)**

270. ### What is host property in css?
     The `:host` pseudo-class selector is used to target styles in the element that hosts the component. Since the host element is in a parent component's template, you can't reach the host element from inside the component by other means.
     For example, you can create a border for parent element as below,
     ```js
     //Other styles for app.component.css
     //...
     :host {
       display: block;
       border: 1px solid black;
       padding: 20px;
     }
     ```
     **[⬆ Back to Top](#table-of-contents)**

271. ### How do you get the current route?
     In Angular, there is an `url` property of router package to get the current route. You need to follow the below few steps,

     1. Import Router from @angular/router
      ```js
        import { Router } from '@angular/router';
      ```
     2. Inject router inside constructor
      ```js
      constructor(private router: Router ) {

      }
      ```
     3. Access url parameter
      ```js
        console.log(this.router.url); //  /routename
      ```

      **[⬆ Back to Top](#table-of-contents)**

272. ### What is Component Test Harnesses?
     A component harness is a testing API around an Angular directive or component to make tests simpler by hiding implementation details from test suites. This can be shared between unit tests, integration tests, and end-to-end tests. The idea for component harnesses comes from the **PageObject** pattern commonly used for integration testing.

     **[⬆ Back to Top](#table-of-contents)**
     
273. ### What is the benefit of Automatic Inlining of Fonts?
     During compile time, Angular CLI will download and inline the fonts that your application is using. This performance update speed up the first contentful paint(FCP) and this feature is enabled by default in apps built with version 11.

     **[⬆ Back to Top](#table-of-contents)**

274. ### What is content projection?
     Content projection is a pattern in which you insert, or project, the content you want to use inside another component.

      **[⬆ Back to Top](#table-of-contents)**

275. ### What is ng-content and its purpose?
     The ng-content is used to insert the content dynamically inside the component that helps to increase component reusability. 

      **[⬆ Back to Top](#table-of-contents)**

276. ### What is standalone component?
      A standalone component is a type of component which is not part of any Angular module. It provides a simplified way to build Angular applications.

      **[⬆ Back to Top](#table-of-contents)**

278. ### How to create a standalone component uing CLI command?

      Generate standalone component using CLI command as shown below
      ```bash
      ng generate component component-name --standalone
      ```
      On running the command standalone component is created.
      Here is the list of file created.
      
      1. `component-name.component.ts`
      2. `component-name.component.css`
      3. `component-name.component.spec`
      4. `component-name.component.html`
      
      Next need to update `app.module.ts` as shown below.

      ```typescript
      import { NgModule } from '@angular/core';
      import { BrowserModule } from '@angular/platform-browser';
      import { ComponentNameComponent } from './component-name/component-name.component';

      @NgModule({
        imports: [
          BrowserModule,
          ComponentNameComponent
        ],
        declarations: [AppComponent],
        bootstrap: [AppComponent],
      })
      export class AppModule {}
      ```

      **[⬆ Back to Top](#table-of-contents)**

278. ### How to create a standalone component manually?
      To make existing component to standalone, then add `standalone: true` in `component-name.component.ts`
      as shown below

      ```typescript
      import { CommonModule } from '@angular/common';
      import { Component, OnInit } from '@angular/core';

      @Component({
        standalone: true,
        imports: [CommonModule],
        selector: 'app-standalone-component',
        templateUrl: './standalone-component.component.html',
        styleUrls: ['./standalone-component.component.css'],
      })
      export class ComponentNameComponent implements OnInit {
        constructor() {}

        ngOnInit() {}
      }
      ```
      Next need to update `app.module.ts` as shown below.

      ```typescript
      import { NgModule } from '@angular/core';
      import { BrowserModule } from '@angular/platform-browser';
      import { ComponentNameComponent } from './component-name/component-name.component';

      @NgModule({
        imports: [
          BrowserModule,
          ComponentNameComponent
        ],
        declarations: [AppComponent],
        bootstrap: [AppComponent],
      })
      export class AppModule {}
      ```
      
      **[⬆ Back to Top](#table-of-contents)**
278. ### What is hydration?
      Hydration is the process that restores the server side rendered application on the client. This includes things like reusing the server rendered DOM structures, persisting the application state, transferring application data that was retrieved already by the server, and other processes.

      To enable hydration, we have to enable server side rendering or Angular Universal. Once enabled, we can add the following piece of code in the root component.
        
      ```typescript
      import {
        bootstrapApplication,
        provideClientHydration,
      } from '@angular/platform-browser';

      bootstrapApplication(RootCmp, {
        providers: [provideClientHydration()]
      });
      ```
      Alternatively we can add `providers: [provideClientHydration()]` in the App Module
      ```typescript
      import {provideClientHydration} from '@angular/platform-browser';
      import {NgModule} from '@angular/core';
      ​
      @NgModule({
        declarations: [RootCmp],
        exports: [RootCmp],
        bootstrap: [RootCmp],
        providers: [provideClientHydration()],
      })
      export class AppModule {}
      ```
      
      **[⬆ Back to Top](#table-of-contents)**
      

## Connect with me ~Rajesh Rathore

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rajesh-rathore-0501/)
[![Website Badge](https://img.shields.io/badge/Website-3b5998?style=flat-square&logo=google-chrome&logoColor=white)](https://linktr.ee/rajesh_rathore)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-00acee?style=flat-square&logo=Twitter&logoColor=white)](https://twitter.com/Rajesh946055)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-e4405f?style=flat-square&logo=Instagram&logoColor=white)](https://www.instagram.com/raj_rathod1313/?hl=en)


***Do star, fork and share the repo to show your support, it would help others too!***   <br>
 <br>
 Let me know your views or any changes or improvements or contribute to make better for others 
