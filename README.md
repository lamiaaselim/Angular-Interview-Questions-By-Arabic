<a name="top"></a>

# Angular Interview Questions

> connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-elshahat-4017a1303) for more technical updates and content.

## Sources

This Repo is inspired by the following sources:

1. [angular.dev](https://angular.dev/)
2. [TekTutorialsHub-Logo](https://www.tektutorialshub.com/angular-tutorial/)
3. [Logo ConcretePage.com](https://www.concretepage.com/angular/)
4. [List of 300 Angular Interview Questions and answers](https://github.com/sudheerj/angular-interview-questions)

| No. | Questions                                                                                                                                                                             |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [What is Angular Framework?](#what-is-angular-framework)                                                                                                                              |
| 3   | [What is TypeScript?](#what-is-typescript)                                                                                                                                            |
| 4   | [Write a pictorial diagram of Angular architecture?](#write-a-pictorial-diagram-of-angular-architecture)                                                                              |
| 5   | [What are the key components of Angular?](#what-are-the-key-components-of-angular)                                                                                                    |
| 6   | [What are directives?](#what-are-directives)                                                                                                                                          |
| 7   | [What are components?](#what-are-components)                                                                                                                                          |
| 9   | [What is a template?](#what-is-a-template)                                                                                                                                            |
| 10  | [What is a module?](#what-is-a-module)                                                                                                                                                |
| 11  | [What are lifecycle hooks available?](#what-are-lifecycle-hooks-available)                                                                                                            |
| 12  | [What is a data binding?](#what-is-a-data-binding)                                                                                                                                    |
| 13  | [What is metadata?](#what-is-metadata)                                                                                                                                                |
| 14  | [What is Angular CLI?](#what-is-angular-cli)                                                                                                                                          |
| 15  | [What is the difference between constructor and ngOnInit?](#what-is-the-difference-between-constructor-and-ngoninit)                                                                  |
| 16  | [What is a service?](#what-is-a-service)                                                                                                                                              |
| 17  | [What is dependency injection in Angular?](#what-is-dependency-injection-in-angular)                                                                                                  |
| 18  | [What is the purpose of async pipe?](#what-is-the-purpose-of-async-pipe)                                                                                                              |
| 19  | [What is the purpose of \*ngFor directive?](#what-is-the-purpose-of-ngfor-directive)                                                                                                  |
| 20  | [What are pipes?](#what-are-pipes)                                                                                                                                                    |
| 21  | [What is a parameterized pipe?](#what-is-a-parameterized-pipe)                                                                                                                        |
| 22  | [How do you chain pipes?](#how-do-you-chain-pipes)                                                                                                                                    |
| 23  | [What is a custom pipe?](#what-is-a-custom-pipe)                                                                                                                                      |
| 24  | [What is the difference between pure and impure pipe?](#what-is-the-difference-between-pure-and-impure-pipe)                                                                          |
| 25  | [What is HttpClient and its benefits?](#what-is-httpclient-and-its-benefits)                                                                                                          |
| 26  | [What are dynamic components?](#what-are-dynamic-components)                                                                                                                          |
| 27  | [What are router events?](#what-are-router-events)                                                                                                                                    |
| 28  | [What is activated route?](#what-is-activated-route)                                                                                                                                  |
| 29  | [How do you define routes?](#how-do-you-define-routes)                                                                                                                                |
| 30  | [What is the purpose of Wildcard route?](#what-is-the-purpose-of-wildcard-route)                                                                                                      |
| 31  | [What is Angular Universal?](#what-is-angular-universal)                                                                                                                              |
| 32  | [What is ng-content?](#what-is-ng-content)                                                                                                                                            |
| 33  | [What is Angular Input and Output and EventEmitter?](#what-is-angular-input-and-output-and-eventemitter)                                                                              |
| 34  | [Template Reference Variable in Angular](#template-reference-variable-in-angular)                                                                                                     |
| 35  | [What is ng-container in Angular?](#what-is-ng-container-in-angular)                                                                                                                  |
| 36  | [How to use ng-template and TemplateRef in Angular?](#how-to-use-ng-template-and-templateref-in-angular)                                                                              |
| 37  | [How to Use ngTemplateOutlet in Angular?](#how-to-use-ngtemplateoutlet-in-angular)                                                                                                    |
| 38  | [What are Signals?](#what-are-signals)                                                                                                                                                |
| 39  | [Why Signal?](#why-signal)                                                                                                                                                            |
| 40  | [Angular Signals and Observables: How and When to Use Each](#angular-signals-and-observables-how-and-when-to-use-each)                                                                |
| 41  | [What is Effect in Signal?](#what-is-effect-in-signal)                                                                                                                                |
| 42  | [ElementRef in Angular](#elementref-in-angular)                                                                                                                                       |
| 43  | [What is Renderer2?](#what-is-renderer2)                                                                                                                                              |
| 44  | [How to Use @ViewChild and @ViewChildren](#how-to-use-viewchild-and-viewchildren)                                                                                                     |
| 45  | [ContentChild and ContentChildren in Angular](#contentchild-and-contentchildren-in-angular)                                                                                           |
| 46  | [What are decorators in angular?](#what-are-decorators-in-angular)                                                                                                                    |
| 47  | [AfterViewInit, AfterViewChecked, AfterContentInit and AfterContentChecked in Angular](#afterviewinit-afterviewchecked-aftercontentinit-and-aftercontentchecked-in-angular)           |
| 48  | [What is View Encapsulation in Angular?](#what-is-view-encapsulation-in-angular)                                                                                                      |
| 49  | [What are Host and hostContext in Angular?](#what-are-host-and-hostcontext-in-angular)                                                                                                |
| 50  | [Angular Change Detection How Does It Really Work?](#angular-change-detection-how-does-it-really-work)                                                                                |
| 51  | [A Change Detection and Zone.js and Zoneless and Local Change Detection and Signals Story](#a-change-detection-and-zone-js-and-zoneless-and-local-change-detection-and-signals-story) |
| 52  | [Angular Signals Component API input and output and model](#angular-signals-component-api-input-and-output-and-model)                                                                 |

# Angular Service Interview Questions

<a name="top2"></a>

> connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-elshahat-4017a1303) for more technical updates and content.

| No. | Questions                                                                                                                                    |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [What is an Angular Service?](#what-is-an-angular-service)                                                                                   |
| 2   | [What Angular Services are used for?](#what-angular-services-are-used-for)                                                                   |
| 3   | [Advantages of Angular Service](#advantages-of-angular-service)                                                                              |
| 4   | [Benefits of Dependency Injection](#benefits-of-dependency-injection)                                                                        |
| 5   | [The five main players in the Angular Dependency Injection Framework?](#the-five-main-players-in-the-angular-dependency-injection-framework) |
| 6   | [Service Scope in Angular](#service-scope-in-angular)                                                                                        |
| 7   | [What is Angular Injector?](#what-is-angular-injector)                                                                                       |
| 8   | [When is Angular Injector created?](#when-is-angular-injector-created)                                                                       |
| 9   | [Registering the service with an injector](#registering-the-service-with-an-injector)                                                        |
| 10  | [What are Angular Providers?](#what-are-angular-providers)                                                                                   |
| 11  | [Types of Providers in Angular?](#types-of-providers-in-angular)                                                                             |
| 12  | [How Dependency Injection and Resolution Work in Angular?](#how-dependency-injection-and-resolution-work-in-angular)                         |
| 13  | [Element Injector Tree in Angular](#element-injector-tree-in-angular)                                                                        |
| 14  | [ProvidedIn root, any, and platform in Angular](#providedin-root-any-and-platform-in-angular)                                                |
| 15  | [@Self, @SkipSelf, and @Optional Decorators in Angular?](#@self-@skipself-@and-optional-decorators-in-angular)                               |

<a name="top3"></a>

# Angular RxJS Interview Questions

> connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-elshahat-4017a1303) for more technical updates and content.

### Table of Contents

| No. | Questions                                                                                                                                                                                                                                                                                                        |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Explain RxJS Observable?](#explain-rxjs-observable)                                                                                                                                                                                                                                                             |
| 2   | [What are RxJS operators?](#what-are-rxjs-operators)                                                                                                                                                                                                                                                             |
| 3   | [What is Observable.pipe() and how to use it?](#what-is-observablepipe-and-how-to-use-it)                                                                                                                                                                                                                        |
| 4   | [What is the difference between RxJS of and from?](#what-is-the-difference-between-rxjs-of-and-from)                                                                                                                                                                                                             |
| 5   | [Explain RxJS map operator?](#explain-rxjs-map-operator)                                                                                                                                                                                                                                                         |
| 6   | [Explain RxJS switchMap operator?](#explain-rxjs-switchmap-operator)                                                                                                                                                                                                                                             |
| 7   | [Explain RxJS mergeMap operator?](#explain-rxjs-mergemap-operator)                                                                                                                                                                                                                                               |
| 8   | [Explain RxJS concatMap operator?](#explain-rxjs-concatmap-operator)                                                                                                                                                                                                                                             |
| 9   | [Explain RxJS exhaustMap operator?](#explain-rxjs-exhaustmap-operator)                                                                                                                                                                                                                                           |
| 10  | [How will you handle errors on observable using RxJS throwError?](#how-will-you-handle-errors-on-observable-using-rxjs-throwerror)                                                                                                                                                                               |
| 11  | [How will you handle errors on observable using RxJS catchError?](#how-will-you-handle-errors-on-observable-using-rxjs-catcherror)                                                                                                                                                                               |
| 12  | [Explain RxJS retry operator?](#explain-rxjs-retry-operator)                                                                                                                                                                                                                                                     |
| 13  | [Explain RxJS filter operator?](#explain-rxjs-filter-operator)                                                                                                                                                                                                                                                   |
| 14  | [Explain RxJS tap operator?](#explain-rxjs-tap-operator)                                                                                                                                                                                                                                                         |
| 15  | [Explain RxJS takeUntil operator?](#explain-rxjs-takeuntil-operator)                                                                                                                                                                                                                                             |
| 16  | [Explain RxJS debounceTime operator?](#explain-rxjs-debouncetime-operator)                                                                                                                                                                                                                                       |
| 17  | [Explain RxJS combineLatestWith operator?](#explain-rxjs-combinelatestwith-operator)                                                                                                                                                                                                                             |
| 18  | [Explain RxJS fromEvent operator?](#explain-rxjs-fromevent-operator)                                                                                                                                                                                                                                             |
| 19  | [What is the difference between Subject, BehaviorSubject, ReplaySubject, and AsyncSubject in RxJS? How do they differ in terms of behavior and use cases?](#what-is-the-difference-between-subject-behaviorsubject-replaysubject-and-asyncsubject-in-rxjs-how-do-they-differ-in-terms-of-behavior-and-use-cases) |
| 20  | [What are the best practices for managing Observable subscriptions in Angular and ensuring there are no memory leaks?](#what-are-the-best-practices-for-managing-observable-subscriptions-in-angular-and-ensuring-there-are-no-memory-leaks)                                                                     |
| 21  | [What are the differences between cold observable and hot observable?](#what-are-the-differences-between-cold-observable-and-hot-observable)                                                                                                                                                                     |
| 22  | [What are the differences between Observables and Promises?](#what-are-the-differences-between-observables-and-promises)                                                                                                                                                                                         |
| 23  | [What is a higher-order Observable?](#what-is-a-higher-order-observable)                                                                                                                                                                                                                                         |
| 24  | [How can you share a single Observable among multiple subscribers?](#how-can-you-share-a-single-observable-among-multiple-subscribers)                                                                                                                                                                           |

<a name="top5"></a>

# Angular Form Interview Questions

> connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-elshahat-4017a1303) for more technical updates and content.

### Table of Contents

| No. | Questions                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Describe the types of forms created in Angular application?](#describe-the-types-of-forms-created-in-angular-application)       |
| 2   | [How will you create reactive form in Angular?](#how-will-you-create-reactive-form-in-angular)                                   |
| 3   | [How will you create template-driven form in Angular?](#how-will-you-create-template-driven-form-in-angular)                     |
| 4   | [Explain FormControl?](#explain-formcontrol)                                                                                     |
| 5   | [Explain FormGroup?](#explain-formgroup)                                                                                         |
| 6   | [Explain FormArray?](#explain-formarray)                                                                                         |
| 7   | [Explain FormBuilder?](#explain-formbuilder)                                                                                     |
| 8   | [Explain FormRecord?](#explain-formrecord)                                                                                       |
| 9   | [How will you use valueChanges?](#how-will-you-use-valuechanges)                                                                 |
| 10  | [How will you use statusChanges?](#how-will-you-use-statuschanges)                                                               |
| 11  | [What is difference between setValue() and patchValue()?](#what-is-difference-between-setvalue-and-patchvalue)                   |
| 12  | [How will you add and remove controls on FormGroup dynamically?](#how-will-you-add-and-remove-controls-on-formgroup-dynamically) |
| 13  | [What is difference between (ngModelChange) and (change)?](#what-is-difference-between-ngmodelchange-and-change)                 |
| 14  | [How to add async validation in FormControl?](#how-to-add-async-validation-in-formcontrol)                                       |
| 15  | [How will you validate template-driven form?](#how-will-you-validate-template-driven-form)                                       |
| 16  | [How will you perform two-way binding using ngModel?](#how-will-you-perform-two-way-binding-using-ngmodel)                       |

<a name="top7"></a>

# Angular Route Guards

> connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-elshahat-4017a1303) for more technical updates and content.

| No. | Questions                                                         |
| --- | ----------------------------------------------------------------- |
| 1   | [Uses of Angular Route Guards](#uses-of-angular-route-guards)     |
| 2   | [Types of Route Guards](#types-of-route-guards)                   |
| 3   | [What is CanActivate Guard](#what-is-canactivate-guard)           |
| 4   | [What is CanActivateChild Guard](#what-is-canactivatechild-guard) |
| 5   | [What is CanDeactivate Guard](#what-is-candeactivate-guard)       |
| 6   | [How to Use Resolve Guard](#how-to-use-resolve-guard)             |
| 7   | [How to Use CanLoad Guard](#how-to-use-canload-guard)             |

<a name="top8"></a>

# HTTP

> connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-elshahat-4017a1303) for more technical updates and content.

| No. | Questions                                                             |
| --- | --------------------------------------------------------------------- |
| 1   | [What is Angular Http Interceptor](#what-is-angular-http-interceptor) |

<a name="top4"></a>

# Error Handling in Angular Applications

> connect with me on [LinkedIn](https://www.linkedin.com/in/mohamed-elshahat-4017a1303) for more technical updates and content.

| No. | Questions                                                                            |
| --- | ------------------------------------------------------------------------------------ |
| 1   | [Why Handle Errors?](#why-handle-errors)                                             |
| 2   | [What is HttpErrorResponse?](#what-is-httperrorresponse)                             |
| 3   | [How Can Catching Errors in HTTP Request?](#how-can-catching-errors-in-http-request) |

## What is Angular Framework?

[⬆️ Back to Top](#top)

<div dir="auto" align="right"> 
الـ Angular Framework هو منصة مفتوحة المصدر معتمدة على TypeScript، وبيستخدموها عشان يبنوا تطبيقات ويب، موبايل، وديسكتوب بكل سهولة. من أهم المميزات اللي بيوفرها الفريم وورك ده هي الـ declarative templates، ودي بتسهل الكتابة والتصميم. كمان فيه الـ dependency injection اللي بيخلي إعادة استخدام الكود والمرونة في الشغل أسهل. بالإضافة لكده، عندك أدوات شاملة من البداية للنهاية end to end tooling اللي بتسهل تطوير التطبيقات بشكل كبير.
</div>
<hr/>

## What is TypeScript?

[⬆️ Back to Top](#top)

<div dir="auto" align="right"> 
ال TypeScript هو نسخة محسنة من JavaScript عملتها مايكروسوفت، والمميز فيه إنه بيضيف أنواع متغيرة (types) إلزامية زي الـ string و number، وكمان بيدعم حاجات زي الـ classes، والـ async/await، وميزات تانية كتير. وبعدين بيتحول الكود المكتوب بـ TypeScript إلى كود عادي مكتوب بـ JavaScript اللي كل المتصفحات بتفهمه.
الـ Angular كله متبني الـ TypeScript كلغة رئيسية.

### مثال بسيط لاستخدام TypeScript

<div dir="auto" align="left">

```typescript
function greeter(person: string) {
  return "Hello, " + person;
}

let user = "mohamed";

document.body.innerHTML = greeter(user);
```

</div>

في المثال ده، الـ greeter function مش بتقبل غير المتغيرات اللي نوعها string بس كـ argument، وده مثال على قوة TypeScript في تحديد نوع المتغيرات.

</div>
<hr/>

## Write a pictorial diagram of Angular architecture?

[⬆️ Back to Top](#top)

The main building blocks of an Angular application are shown in the diagram below:-

![alt text](./images/architecture.png)

<hr/>

## What are the key components of Angular?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### المكونات الأساسية في Angular بتشمل الحاجات دي:

#### Component

ال(Components) في Angular زي الطوب اللي بتبني بيه التطبيق بتاعك، كل Component مسؤول عن جزء معين من الصفحة اللي بتظهر للمستخدم. يعني هو اللي بيقول الـ HTML يتعرض إزاي ويشتغل إزاي. زي مثلاً لو عندك صفحة تسجيل دخول، الComponent هو اللي هيتحكم في الشكل والأزرار وكل حاجة بتظهر في الجزء ده.

#### Modules

في Angular هي عبارة عن مجموعة من Components Angular الأساسية زي الـ Components، والـ Directives، والـ Services وغيرها. التطبيق بيتقسم لقطع منطقية، وكل قطعة بتتسمى "Module" وبتقوم بمهمة واحدة محددة.

#### Templates

ال(Templates) في Angular زي الرسمة اللي بتقول Component يعرض إيه بالظبط. يعني هي اللي بتحدد الشكل اللي المستخدم هيشوفه، زي الأزرار، النصوص، والصور. Template ده بيبقى مليان كود HTML، بس ممكن كمان يكون فيه حاجات ديناميكية بتتغير حسب اللي بيحصل في التطبيق. يعني باختصار، Template هو اللي بيرسم شكل الواجهة اللي هتشوفها قدامك.

#### Services

دي زي حاجات بتعملها مرة واحدة وتقدر تستخدمها في أي حتة في التطبيق بتاعك. يعني لو عندك شغلانة معينة وعايز تعملها في كذا مكان، مش هتعيد الكود كل مرة، بتعملها كـ "Service" وتستخدمها في أي حتة.

#### Metadata

دي زي شوية معلومات إضافية بتضيفها على الكلاس عشان تخليه يشتغل بشكل معين في Angular. يعني زي ما تكون بتدي توجيهات زيادة للكلاس ده، عشان Angular يفهمه بطريقة أحسن.

</div>

<hr/>

## What are directives?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الDirectives في Angular هي زي تعليمات بتضيف تصرفات أو سلوكيات جديدة لعناصر الـ DOM اللي موجودة في الصفحة، أو حتى لComponent موجود بالفعل.
<div dir="auto" align="left">

```typescript
import { Directive, ElementRef } from "@angular/core";

@Directive({ selector: "[myHighlight]" })
export class HighlightDirective {
  constructor(el: ElementRef) {
    el.nativeElement.style.backgroundColor = "yellow";
  }
}
```

</div>
الكود ده بيعمل Directive اسمه myHighlight، وكل اللي بيعمله إنه بيغير لون الخلفية لأي عنصر HTML للون الأصفر. يعني مثلاً لو عندك فقرة (paragraph) وعايز تديها خلفية صفراء، هتكتب كود بالشكل ده:

<div dir="auto" align="left">

```HTML
<p myHighlight>Highlight me!</p>
```

</div>

</div>
<hr/>

## What are components?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
في Angular، الـ Components تعتبر الوحدة الأساسية اللي بتستخدم عشان تبني واجهة المستخدم (UI). كل Component بيكون مسؤول عن جزء معين من الصفحة أو الواجهة. يعني مثلاً ممكن يكون عندك Component مسؤول عن عرض الـ header  وComponent تاني مسؤول عن عرض قائمة المنتجات، وهكذا.

الـ Components دي بتشتغل مع بعض وبتتجمع عشان تبني التطبيق كله، وعشان كده بنقول إنها بتكون شجرة من الـ Components، يعني كل Component ممكن يكون جواه Components تانية أصغر. زي ما يكون عندك صفحة فيها أجزاء مختلفة وكل جزء فيه تفاصيله الخاصة.

#### نيجي بقى للفرق بين الـ Component والـ Directive:

الComponent هو نوع من الـ Directives، بس الفرق الأساسي هو إن الـ Component لازم يكون ليه template، يعني لازم يعرض حاجة للمستخدم زي نصوص، صور، أزرار... إلخ.

في المقابل، الـ Directive العادي مش لازم يكون ليه template، وممكن يستخدم بس عشان يضيف أو يعدل سلوك عنصر HTML موجود. يعني بيغير في العنصر من غير ما يعرض محتوى جديد.

#### باختصار

الComponent بيكون ليه template وبيعرض حاجة للمستخدم.
كل تطبيق Angular بيتكون من مجموعة Components بتشتغل مع بعض زي شجرة.
الفرق الأساسي بين Component و Directive هو إن الأول بيعرض واجهة (UI) والثاني بس بيغير أو يضيف سلوك للعناصر اللي موجودة.

</div>
<hr/>

## What is a template?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ template في Angular هو ببساطة العرض اللي بيتشوف للمستخدم على هيئة HTML، وبتقدر تعرض فيه بيانات عن طريق ربط العناصر اللي في الـ HTML بالبيانات اللي جوا الـ Component. بمعنى تاني، الـ template هو المكان اللي بتعرض فيه البيانات اللي بيكون جوا الـ Component.

#### الـ template ممكن تخزنه في مكانين

##### Inline Template

يعني إنك تكتب كود الـ HTML مباشرة جوا الـ Component باستخدام الخاصية template. ده مناسب لو عندك HTML بسيط.

##### External Template

يعني إنك تخزن الـ template في ملف HTML منفصل وتربطه بالـ Component باستخدام templateUrl. ده بيكون مناسب لما يكون عندك HTML كبير أو معقد.

##### مثال على Inline Template

 <div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";

@Component({
  selector: "my-app",
  template: `
    <div>
      <h1>{{ title }}</h1>
      <div>Learn Angular</div>
    </div>
  `,
})
export class AppComponent {
  title: string = "Hello World";
}
```

</div>
في المثال ده، كل كود الـ HTML مكتوب مباشرة جوه الـ Component عن طريق الخاصية template. وهنا بيتم ربط المتغير title اللي جوا الـ Component بالـh1  عن طريق {{}}، وده اسمه interpolation.

##### مثال على External Template

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";

@Component({
  selector: "my-app",
  templateUrl: "app/app.component.html",
})
export class AppComponent {
  title: string = "Hello World";
}
```

</div>
في الحالة دي، كود الـ HTML بيكون موجود في ملف خارجي اسمه app.component.html، وبتربطه بالـ Component عن طريق templateUrl. وده مفيد لو عندك templates معقدة أو كبيرة عشان تبقى الصفحة أسهل في التنظيم والصيانة.
</div>
<hr/>

## What is a module?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ Modules في Angular بتعمل زي الحدود المنطقية في التطبيق بتاعك، وبتقسم التطبيق لأجزاء منفصلة عشان كل جزء يقوم بوظيفة معينة. الفكرة الأساسية هي إنك تقسم الكود لموديولات (Modules) عشان تبقى الأمور منظمة وسهلة في الإدارة.

خلينا ناخد مثال على الملف app.module.ts، اللي هو الموديول الرئيسي في التطبيق، وبيتم الإعلان عنه باستخدام @NgModule decorator

<div dir="auto" align="left">

```typescript
import { NgModule } from "@angular/core";
import { BrowserModule } from "@angular/platform-browser";
import { AppComponent } from "./app.component";

@NgModule({
  imports: [BrowserModule],
  declarations: [AppComponent],
  bootstrap: [AppComponent],
  providers: [],
})
export class AppModule {}
```

</div>
في المثال ده، عندنا الـ @NgModule اللي بيوفر شوية خيارات مهمة، وأهمها

##### imports

دي بتستخدم عشان تستورد موديولات تانية محتاجها في التطبيق. في المثال ده، بنستورد BrowserModule اللي بيكون مطلوب لأي تطبيق ويب في Angular.

##### declarations:

دي بتستخدم عشان تعلن عن الـ Components اللي موجودة في الموديول ده. هنا بنعلن عن AppComponent.

##### bootstrap

دي بتقول لـ Angular أي Component هو اللي هيبدأ تشغيل التطبيق. في الحالة دي، AppComponent هو اللي بيبدأ تشغيل التطبيق.

##### providers

بتستخدم عشان تحدد الحاجات اللي تقدر تعمل لها حقن (Injectable objects) في أجزاء مختلفة من التطبيق. يعني لو عندك (Services) معينة وعايز كل أجزاء التطبيق تقدر تستعملها، بتحطها في المكان ده. مثلاً، لو عندك Service بتجيب بيانات من سيرفر، بتقدر تحطها في الـ providers عشان أي Component في التطبيق يقدر يستخدمها من غير ما تضطر تعيد الكود في كل مكان.

الـ Modules بشكل عام بتساعد في تقسيم الوظائف بشكل منطقي في التطبيق وبتسهل تنظيم الكود وإعادة استخدامه.

</div>
<hr/>

## What are lifecycle hooks available?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ Lifecycle hooks في Angular هي مجموعة من المراحل أو العمليات اللي بيمر بيها الـ Component أو الـ Directive من لحظة إنشاؤه لحد ما يتم تدميره. 
Angular بيوفر مجموعة من الدوال اللي بتتفاعل مع كل مرحلة من مراحل الحياة دي.

![alt text](./images/lifecycle.png)

#### دي قائمة بأهم lifecycle hooks المتاحة في Angular:

##### ngOnChanges

بيتنفذ لما يحصل تغيير في قيمة أي خاصية مربوطة بالبيانات (data bound property). يعني كل ما تتغير بيانات الـ Component بيتنفذ الكود ده.

##### ngOnInit

بيتنفذ أول ما يتم تهيئة (initialize) الـ Component أو الـ Directive بعد ما Angular يعرض الخصائص اللي مربوطة بالبيانات لأول مرة.

##### ngDoCheck

بيتنفذ عشان يكتشف أي تغييرات Angular مش قادر يكتشفها لوحده، وبيخليك تعمل أي حاجات إضافية لو فيه تغييرات معينة محتاج تتعامل معاها يدوي.

##### ngAfterContentInit

بيتنفذ بعد ما Angular يعمل (project) للمحتوى الخارجي جوا الـ Component.

##### ngAfterContentChecked

بيتنفذ بعد ما Angular يتأكد من المحتوى اللي تم إسقاطه جوا الـ Component، يعني بيتشيك على المحتوى اللي جوا الـ Component بعد ما يتم عرضه.

##### ngAfterViewInit

بيتنفذ بعد ما Angular يهيئ (initialize) الـ Views الخاصة بالـ Component وأي Child Components (الأطفال اللي جواه).

##### ngAfterViewChecked

بيتنفذ بعد ما Angular يتأكد من الـ Views الخاصة بالـ Component وأي Child Components.

##### ngOnDestroy

ده بيكون المرحلة الأخيرة، بيتنفذ قبل ما Angular يدمر الـ Component أو الـ Directive. هنا بتعمل تنظيف (cleanup) لأي موارد أو اشتراكات (subscriptions) مستخدمة في الـ Component.

✨ باختصار، كل Lifecycle hook بيخليك تتحكم في سلوك الـ Component في مراحل معينة من حياته، زي لما يتغير، يتعرض، أو يتدمر.

</div>

<hr/>

## What is a data binding?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الData binding في Angular هو مفهوم أساسي بيسمح بتحديد طريقة التواصل بين الـ Component والـ DOM (واجهة المستخدم). الفكرة الرئيسية في الـ data binding هي إنك بتخلي التطبيق ديناميكي وتفاعلي من غير ما تقلق تسحب أو تدفع البيانات بشكل يدوي بين الـ Component والـ HTML.

#### فيه 4 أنواع للـ Data binding، وكل نوع بيسمح للبيانات تتحرك في اتجاه معين

##### من الـ Component للـ DOM (يعني من TS للview):

##### Interpolation

ده بيستخدم لما عايز تعرض قيمة متغير من الـ Component جوه الـ HTML. بتستخدم الأقواس المزدوجة {{ }} زي ما بنقول "خذ القيمة دي من الكود بتاعك وحطها هنا في للview".

<div dir="auto" align="left">

```HTML
<li>Name: {{ user.name }}</li>
<li>Address: {{ user.address }}</li>
```

</div>
هنا، user.name و user.address هما قيمتين موجودين في الـ Component، وبتظهر قيمهم للمستخدم جوا الـ HTML.

##### Property Binding

هنا، بتربط قيمة معينة من الـ Component بخاصية (property) من خصائص عنصر HTML. بتستخدم الأقواس المربعة [ ] حوالين الخاصية اللي عايز تتحكم فيها.

<div dir="auto" align="left">

```typescript
<input type="email" [value]="user.email">
```

</div>
في المثال ده، قيمة الinput value هتيجي من المتغير user.email اللي موجود في الـ Component.

##### من الـ DOM للـ Component (يعني من view للTS ):

##### Event Binding

ده لما عايز تربط حدث معين (زي click، أو keyup) بدالة أو وظيفة في الـ Component بتاعك. بتستخدم الأقواس العادية ( ) حوالين اسم الحدث.

<div dir="auto" align="left">

```HTML
<button (click)="logout()"></button>
```

</div>
هنا، لما المستخدم يضغط على الزرار ده، Angular هيستدعي دالة logout اللي موجودة في الـ Component.

##### (Two-way binding)

##### Two-way Data Binding

هنا بتربط البيانات بين الـ Component والـ DOM في الاتجاهين. يعني لو المستخدم غيّر حاجة في الواجهة، القيمة بتتحدث في الـ Component، ولو حصل العكس، القيمة اللي في الـ Component بتتغير في الواجهة. بتستخدم أقواس مربعة وعادية [( )] حوالين الـ ngModel.

<div dir="auto" align="left">

```HTML
<input type="email" [(ngModel)]="user.email">
```

</div>
هنا، ال input متصل بشكل مباشر مع المتغير user.email. يعني لو المستخدم كتب إيميل جديد في الinput قيمة user.email في الـ Component هتتحدث تلقائيًا. ولو حصل العكس، أي تغيير في user.email هيظهر مباشرة في الinput.

##### ✨ الخلاصة

-الInterpolation و Property Binding بيخلوا البيانات تمشي من الـ Component للـ DOM.
-الEvent Binding بيخلي البيانات تمشي من الـ DOM للـ Component.
-الTwo-way binding بيخلي البيانات تمشي في الاتجاهين، بين الـ Component والـ DOM في نفس الوقت.

</div>
<hr/>

## What is metadata?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ Metadata في Angular هي بيانات إضافية بتتحط فوق  (classes) أو  (properties) أو  (methods) أو  (parameters) عشان تتحكم في سلوكهم. الـ Metadata بتتمثل في حاجة اسمها Decorators، وهي بتخلي Angular يفهم إزاي يتعامل مع الكود اللي انت كتبته. خلينا نبسط الموضوع مع الأنواع المختلفة من الـ Decorators:

### Class decorators

بتستخدم لتزيين الكلاس كله، زي لما بنستخدم Component@ أو NgModule@. دي بتحول الكلاس إلى Component أو Module.

<div dir="auto" align="left">

```typescript
import { NgModule, Component } from "@angular/core";

@Component({
  selector: "my-component",
  template: "<div>Class decorator</div>",
})
export class MyComponent {
  constructor() {
    console.log("Hey I am a component!");
  }
}

@NgModule({
  imports: [],
  declarations: [],
})
export class MyModule {
  constructor() {
    console.log("Hey I am a module!");
  }
}
```

</div>

##### Component@

هنا بيحول الكلاس MyComponent إلى Component بواجهة HTML مرتبطة بيه.

##### NgModule@

بيحول الكلاس MyModule إلى Module عشان يقدر يشتغل في التطبيق.

### Property decorators

بتستخدم لتزيين الخصائص جوا الكلاس. أشهر الأمثلة هي Input@ و Output@ اللي بيتحكموا في تبادل البيانات بين الـ Components.

<div dir="auto" align="left">

```typescript
import { Component, Input } from "@angular/core";

@Component({
  selector: "my-component",
  template: "<div>Property decorator</div>",
})
export class MyComponent {
  @Input()
  title: string;
}
```

</div>

### Method decorators

بتستخدم لتزيين (methods) جوا الكلاس، زي HostListener@ اللي بيتفاعل مع أحداث معينة زي الـ click أو hover.

<div dir="auto" align="left">

```typescript
import { Component, HostListener } from "@angular/core";

@Component({
  selector: "my-component",
  template: "<div>Method decorator</div>",
})
export class MyComponent {
  @HostListener("click", ["$event"])
  onHostClick(event: Event) {}
}
```

</div>

### Parameter decorators

بتستخدم لتزيين Parameters اللي جوا الـ Constructor. زي Inject@ و Optional@ اللي بيتحكموا في كيفية حقن القيم أو الخدمات جوا الكلاس.

<div dir="auto" align="left">

```typescript
import { Component, Inject } from "@angular/core";
import { MyService } from "./my-service";

@Component({
  selector: "my-component",
  template: "<div>Parameter decorator</div>",
})
export class MyComponent {
  constructor(@Inject(MyService) myService) {
    console.log(myService); // بيتم حقن MyService
  }
}
```

</div>
</div>
<hr/>

## What is Angular CLI?

[⬆️ Back to Top](#top)

### Angular CLI (Command Line Interface)

Angular CLI is a command line interface to scaffold and build Angular apps using nodejs style (commonJs) modules. You need to install using the npm command,

```bash
npm install @angular/cli@latest
```

i. Creating New Project:

```bash
ng new
```

ii. Generating Components, Directives & Services:

```bash
ng generate/g
```

The different types of commands would be:

- ng generate class my-new-class: add a class to your application
- ng generate component my-new-component: add a component to your application
- ng generate directive my-new-directive: add a directive to your application
- ng generate enum my-new-enum: add an enum to your application
- ng generate module my-new-module: add a module to your application
- ng generate pipe my-new-pipe: add a pipe to your application
- ng generate service my-new-service: add a service to your application

iii. Running the Project:

```bash
ng serve
```

<hr/>

## What is the difference between constructor and ngOnInit?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### الـ Constructor

الـ constructor هو زي "function" اللي بتشتغل أول ما تعمل نسخة جديدة من (class) في TypeScript. يعني مثلاً لما تيجي تعمل Component جديد، أول حاجة بتحصل هي إن الـ constructor بيشتغل.

وظيفته الأساسية إنه يجهز المتغيرات بتاعت الكلاس ويظبط حاجة اسمها Dependency Injection، ودي اللي بتخلي Angular يقدر يحط الـ services اللي محتاجها الكلاس بسهولة.

المهم إنك تستخدم الـ constructor عشان تجهز الحاجات الأساسية بتاعت الكلاس بس، يعني متعملش فيه أي "شغل" تقيل زي استدعاء دوال أو التعامل مع بيانات أو حاجات معقدة. الأفضل إنك تسيب الحاجات دي للـ ngOnInit لأن ده بيكون وقت مناسب أكتر عشان تبدأ الشغل الفعلي.

باختصار، خلي الـ constructor لتهيئة الحاجات الأساسية، من غير ما تعمل فيه حاجات كتير.

### الـ ngOnInit

هو واحد من الـ lifecycle hooks اللي Angular بتشغله بعد ما تكون خلصت إنشاء الـ Component وعرضته قدام المستخدم. يعني ببساطة، بيشتغل بعد الـ constructor.

عادة بنستخدم الـ ngOnInit لما نكون عايزين نجهز أو نعمل تهيئة لحاجات معينة زي البيانات أو لو عايزين نجيب بيانات من API، أو حتى لو في حاجات مربوطة (bindings) محتاجين نشتغل عليها.

الـ ngOnInit بيكون أنسب مكان تبتدي فيه الشغل التقيل، زي استدعاء بيانات أو التعامل مع الحاجات اللي جاية من بره الـ Component، لأن في الوقت ده بيكون Angular ظبط كل الـ bindings واتأكد إن البيانات اللي جايالك من بره (زي المتغيرات اللي بتجي من الـ parent component) جاهزة.

</div>
<hr/>

## What is a service?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الService في Angular هي ببساطة كود بتكتبه لما يكون عندك وظيفة معينة أو شغل عايز تعمله في أكتر من مكان في التطبيق. الفكرة من الـ Service هي إنها تخليك تفصل المهام المشتركة أو المنطق اللي بتحتاجه في كذا Component في مكان واحد، وتقدر تستخدمه بسهولة في أماكن كتير، وده بيساعد في تنظيم الكود وتجنب التكرار.

<div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import { Http } from "@angular/http";

@Injectable({
  providedIn: "root",
})
export class RepoService {
  constructor(private http: Http) {}

  fetchAll() {
    return this.http.get("https://api.github.com/repositories");
  }
}
```

</div>

### HTML

<div dir="auto" align="left">

```typescript
import { Component, OnInit } from "@angular/core";
import { RepoService } from "./repo.service";

@Component({
  selector: "app-repo-list",
  template: `
    <ul>
      <li *ngFor="let repo of repos">{{ repo.name }}</li>
    </ul>
  `,
})
export class RepoListComponent implements OnInit {
  repos: any[] = [];

  constructor(private repoService: RepoService) {}

  ngOnInit() {
    this.repoService.fetchAll().subscribe((data) => {
      this.repos = data;
    });
  }
}
```

</div>
</div>
 <hr/>

## What is dependency injection in Angular?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الDependency Injection (DI) في Angular هو ببساطة طريقة ذكية بتخلي الكلاس (class) يطلب الحاجات اللي محتاجها من بره بدل ما هو ينشئها بنفسه. يعني لو في service أو حاجة معينة الكلاس محتاجها عشان يشتغل، Angular بتساعده ويجيبله الحاجات دي جاهزة من بره.

#### الفكرة باختصار

بدل ما الكلاس يبقى مسؤول عن إنشاء كل حاجة بنفسه ، Angular بتشوف هو محتاج إيه، وتقوم تروح تجيبها وتحطها له جاهزة، عن طريق حاجة اسمها الـ Injector.

#### ليه نستخدم Dependency Injection؟

تنظيم الكود: بيساعد إن الكلاس مايبقاش مضطر ينشئ الحاجات اللي محتاجها بنفسه، وده بيفصل بين منطق الكود والحاجات اللي بيحتاجها.

إعادة الاستخدام: لو عندك service بتعمل حاجة معينة، تقدر تستخدمها في أكتر من Component بسهولة.

تسهيل الاختبارات: لما تيجي تختبر الكود، تقدر تستبدل الـ service الأصلية بحاجة وهمية بسهولة وتعمل اختباراتك من غير مشاكل.

</div>
<hr/>

## What is the purpose of async pipe?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ Async Pipe في Angular بيساعدك في التعامل مع الـ Observable أو الـ Promise بشكل سهل وبدون ما تضطر تعمل subscribe بنفسك. يعني بدل ما تقعد تكتب كود عشان تراقب الـ Observable وتعمله unsubscribe لما الكومبوننت بتاعك يتدمر، الـ Async Pipe بيعمل كل ده لوحده.

تخيل إن عندك Observable بيرجع الوقت الحالي كل ثانيتين، وانت عايز تعرضه في الـ HTML بتاعك. باستخدام الـ Async Pipe، هتقدر تعمل ده من غير أي تعقيدات.

<div dir="auto" align="left">

```typescript
@Component({
  selector: "async-observable-pipe",
  template: `<div>
    <code>observable|async</code>: Time: {{ time$ | async }}
  </div>`,
})
export class AsyncObservablePipeComponent {
  time$: Observable<string>;
  constructor() {
    this.time$ = new Observable((observer) => {
      setInterval(() => {
        observer.next(new Date().toString());
      }, 2000);
    });
  }
}
```

</div>
للي بيحصل هنا إنك عملت Observable اسمه time$ بيبعت القيمة الجديدة (الوقت الحالي) كل ثانيتين. بعد كده في التمبليت (template)، استخدمت الـ Async Pipe بالطريقة دي: {{ time$ | async }}.

الـ Async Pipe بيقوم بالاشتراك في الـ Observable أو الـ Promise وبيجيب أحدث قيمة منه ويعرضها. كل ما الـ Observable يبعث قيمة جديدة، الـ Pipe بيحدث القيمة في الـ View تلقائي.

</div>
<hr/>

## What is the purpose of \*ngFor directive?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ *ngFor directive في Angular هدفها الرئيسي هو إنها تساعدك تعرض مجموعة عناصر في الـ template بناءً على البيانات اللي عندك في الـ component. بمعنى إنك لو عندك array مثلاً من البيانات، زي users، ممكن بسهولة تكرر عرض كل عنصر من العناصر دي جوه الـ template بتاعك.
<div dir="auto" align="left">

```HTML
<li *ngFor="let user of users">
  {{ user }}
</li>
```

</div>
</div>
<hr/>

## What are pipes?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الpipes في Angular هي عبارة عن functions بسيطة بتشتغل عشان تاخد بيانات كمدخلات وتحوّلها لصيغة أو شكل معين يكون مفيد أكتر للمستخدم. وده بيتم عن طريق استخدام حاجة اسمها "template expressions"، اللي بتبقى موجودة جوا الHTML بتاع الcomponent.

خلينا نوضح بمثال عشان الصورة تكون أوضح. لو عندك component معمول في Angular وعايز تعرض تاريخ ميلاد معين (birthday) بس في شكل يكون سهل للفهم أو "human-friendly"، هنا ممكن تستخدم حاجة اسمها "date pipe". الـpipe دي هتخلي التاريخ يظهر بطريقة متنسيقة زي ما المستخدم ممكن يتوقع.

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";

@Component({
  selector: "app-birthday",
  template: `<p>Birthday is {{ birthday | date }}</p>`,
})
export class BirthdayComponent {
  birthday = new Date(1987, 6, 18); // June 18, 1987
}
```

</div>
في الكود ده، انت عندك component اسمه BirthdayComponent وداخله birthday معمول على إنه object من نوع Date، بتحدده بتاريخ معين (18 يونيو 1987). بعد كده في الـHTML، استخدمت {{ birthday | date }} وده اللي بيسمى "pipe". الـ| هنا هي اللي بتحدد إنك بتستخدم pipe عشان تحول البيانات.

اللي بيحصل هو إن التاريخ اللي مخزن جوا الـbirthday هيظهر للمستخدم في شكل تاريخ مفهوم بسهولة، حسب الفورمات اللي Angular بيستخدمه افتراضيًا لعرض التواريخ.

<div dir="auto" align="left">

```HTML
Birthday is Jun 18, 1987
```

</div>
فالـpipes بتسهل عليك شغل كتير لو محتاج تعدل أو تنسق البيانات قبل عرضها للمستخدمين.
</div>
<hr/>

## What is a parameterized pipe?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ Parameterized Pipe في Angular ببساطة هو طريقة لتعديل الـ output بتاع الـ pipe باستخدام بارامترات إضافية. يعني تقدر تتحكم في النتيجة اللي هتطلع من الـ pipe عن طريق إضافة بارامترات بعد اسم الـ pipe باستخدام الـ colon " : ". لو الـ pipe بيقبل أكتر من باراميتر، بتفصل بينهم بـ colons تانية.

خلينا نوضح الموضوع بمثال بسيط زي اللي انت جبته عن عيد الميلاد. في الكود اللي انت كتبته، بنستخدم الـ date pipe عشان نعرض تاريخ معين لكن بالصيغة اللي احنا عايزنها (يوم/شهر/سنة).

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";

@Component({
  selector: "app-birthday",
  template: `<p>Birthday is {{ birthday | date : "dd/MM/yyyy" }}</p>`, // 18/06/1987
})
export class BirthdayComponent {
  birthday = new Date(1987, 6, 18);
}
```

</div>
هنا، الـ date pipe بيقبل باراميتر وهو الصيغة اللي انت عايز تعرض بيها التاريخ، واللي هنا عبارة عن 'dd/MM/yyyy'. الـ pipe هيقوم بتحويل التاريخ اللي موجود في birthday (اللي هو 18 يونيو 1987) للصيغة اللي انت عايزها، وهيطلعلك 18/06/1987.

لو الـ pipe بيقبل أكتر من باراميتر، هتفصلهم بنفس الطريقة عن طريق colons.

</div>
<hr/>

## How do you chain pipes?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
انت بتستخدم أكثر من pipe وبتسميها chaining pipes. يعني بتربط أكثر من pipe مع بعض عشان تنفذ مجموعة عمليات على القيمة.

الفكرة ببساطة انك بتبدأ من القيمة الأولانية وبتعديها على أول pipe، وبعد ما الـ pipe الأول يخلص، النتيجة بتاعت الـ pipe الأول بتروح للـ pipe اللي بعده، وهكذا لغاية ما يخلصوا كل الـ pipes اللي انت حاططهم.

في المثال بتاعك، انت عندك خاصية birthday اللي هي تاريخ الميلاد:

<div dir="auto" align="left">

```typescript
birthday = new Date(1987, 6, 18);
```

</div>
ده معناه ان عندك التاريخ 18 يوليو 1987 (شهر 6 هو يوليو عشان الـ JavaScript بتمشي بالأصفار).

اللي بيحصل هنا:
الdate pipe: بيحول قيمة التاريخ ويعرضها بشكل معين. انت استخدمت الفورمات 'fullDate'، فالتاريخ هيظهر كامل زي "Thursday, June 18, 1987".

الuppercase pipe: بياخد النتيجة اللي طلعت من الـ date pipe وبيحولها لحروف كبيرة، فالناتج النهائي هيكون: "THURSDAY, JUNE 18, 1987".

### طريقة الكتابة

<div dir="auto" align="left">

```HTML
<p>Birthday is {{ birthday | date:'fullDate' | uppercase }} </p>
```

</div>

</div>
<hr/>

## What is a custom pipe?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ "custom pipe" ببساطة هو أن انت تكتب حاجة بنفسك في Angular عشان تحوّل البيانات بشكل معين، غير الـ "built-in pipes" اللي Angular بتوفّرها زي الـ date أو uppercase وكده.

أول حاجة لازم تعملها لما تيجي تكتب "custom pipe" هي إنك تستخدم الـ @Pipe ديكوريتور اللي بتجيبها من الـ core Angular.

<div dir="auto" align="left">

```typescript
@Pipe({name: 'myCustomPipe'})
```

</div>
بعد كده بتكتب class وبتخلّيه implement للـ PipeTransform interface اللي فيه الميثود الأساسية اللي هي transform. الميثود دي بتاخد الـ value اللي عاوز تحولها، وكمان ممكن تاخد شوية parameters إضافية. وتبقى النتيجة هي القيمة الجديدة اللي متحوّلة.

#### مثلا، لو هنعمل pipe بيحوّل أي input لقيمته مضروبة في رقم معيّن

<div dir="auto" align="left">

```typescript
import { Pipe, PipeTransform } from "@angular/core";

@Pipe({ name: "multiply" })
export class MultiplyPipe implements PipeTransform {
  transform(value: number, multiplier: number): number {
    return value * multiplier;
  }
}
```

</div>
كده لو عندك template وعايز تستخدم الـ pipe ده، هتعمله زي ما بتعمل مع الـ built-in pipes:
<div dir="auto" align="left">

```HTML
{{ 5 | multiply: 2 }} // 10
```

</div>
النقطة اللي لازم تركز عليها إن اسم الـ pipe اللي بتكتبه في الـ @Pipe ديكوريتور هو اللي هتستخدمه في الـ template. والـ transform method دي هي اللي بتكتب فيها اللوجيك اللي عاوز تطبقه على البيانات.
</div>
<hr/>

## What is the difference between pure and impure pipe?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
طبعاً، الفرق بين الـ pure pipe والـ impure pipe في Angular بيكون في إزاي بيتعاملوا مع دورة التغيير (change detection)

### Pure Pipe

يتنفذ بس لما يكون في تغيير في القيمة أو في الـ parameters اللي اتبعتت للـ pipe.
يعني لو عندك قيمة primitive زي String أو Number أو Boolean، ولو اتغيرت القيمة دي، أو لو كان فيه تغيير في الـ object reference زي Date أو Array أو Function أو Object.
ده بيخلي الـ pure pipe أكتر كفاءة لأنها مش بتتنفذ كتير، وبتشتغل بس لما يكون في حاجة اتغيرت فعلاً.

### Impure Pipe

يتنفذ في كل دورة تغيير (change detection cycle) بغض النظر إذا كانت القيمة أو الـ parameters اتغيرت ولا لأ.
يعني ممكن الـ impure pipe يتنفذ كتير جداً، زي كل حركة مفتاح (keystroke) أو حركة ماوس (mouse-move).
ده ممكن يؤدي إلى أداء أبطأ لو استخدمته في أماكن كتير في التطبيق.

</div>
<hr/>

## What is HttpClient and its benefits?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الHttpClient هو واحد من الأدوات اللي بيوفرها Angular علشان تتعامل مع الـ backend services اللي بتشتغل بالـ HTTP. زمان كان الناس بتستخدم حاجات زي XMLHttpRequest أو fetch() API علشان يجيبوا البيانات من السيرفر، لكن دلوقتي Angular عامل لنا الموضوع أسهل شوية عن طريق الـ HttpClient اللي مبني أصلاً فوق الـ XMLHttpRequest. يعني، بيقدملك طريقة أبسط وأوضح علشان تشتغل مع الـ HTTP requests.

طيب، هو موجود فين؟ تقدر تضيفه في التطبيق بتاعك عن طريق تعمل import لل HttpClientModule من الباكدج اللي اسمها angular/common/http@ بالطريقة دي:

<div dir="auto" align="left">

```typescript
import { HttpClientModule } from "@angular/common/http";
```

</div>

### طيب إيه بقى فايدته؟

تقدر تختبر الكود بتاعك بسهولة لما تستخدمه في الـ HTTP requests.
تقدر تحدد أنواع البيانات اللي طالعين من وإلى الـ backend، وده بيخليك متأكد إنك شغال على البيانات الصح.
بيعمل intercept للrequest and response: يعني ممكن تتحكم في الطلبات اللي طالعة من التطبيق بتاعك أو الاستجابات اللي راجعة قبل ما توصل. ده بيساعد في حاجات زي إضافة headers أو التعامل مع الـ tokens.
بيدعم Observable APIs: لو متعود على الـ Observables في Angular، هتلاقي الـ HttpClient بيشتغل معاهم حلو جداً، وده بيخليك تستفيد من حاجات زي الـ RxJS.

</div>
<hr/>

## What are dynamic components?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ Dynamic Components هي components في Angular اللي مكانها مش بيتحدد في التطبيق وقت الـ Build، يعني مش بنستخدمها في أي Template ثابتة. الفكرة إنك بتعمل Instantiation للـ component دي وتضيفها في التطبيق وقت الـ Runtime. يعني بكل بساطة، بتحدد مكانها وطريقة عرضها وقت التشغيل مش وقت بناء التطبيق.

✨ مثال على كده، ممكن يكون عندك component مش عارف هيتعرض فين بالضبط، زي في Dialog، Popup، أو حتى جزء من الصفحة حسب تفاعل المستخدم أو رد من API. فبتستخدم الـ Dynamic Components عشان تضيف الـ component دي بشكل ديناميكي بناءً على اللي بيحصل في التطبيق وقت التشغيل.

ده بيكون مفيد جدًا لو عاوز تعمل تصميم مرن أو تعرض components معينة بناءً على ظروف أو اختيارات معينة للمستخدم.

</div>
<hr/>

## What are the various kinds of directives?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
في عالم الـ Angular مثلاً، بنلاقي ٣ أنواع رئيسية من الـ Directives

### Components directives

دي عبارة عن directives بس معاها template. يعني بتتعامل كأنها حتة UI كاملة، زي ما تكون واجهة المستخدم اللي انت بتعرضها. الكمبوننتس دي بتحتوي على html و logic بتاعها. يعني تقدر تعتبرها مزيج ما بين شكل الصفحة والسلوك اللي فيها.

### Structural directives

دي بتشتغل على الـ DOM. بتغير في الـ layout بتاع الصفحة، يعني تقدر تضيف أو تشيل عناصر من الصفحة نفسها. مثال على كده عندنا الـ *ngIf أو الـ *ngFor اللي بتخلينا نتحكم في إذا كان العنصر يتعرض أو يتخفى أو يتكرر بناءً على شروط معينة.

### Attribute directives

النوع ده بيغير في شكل العنصر أو في الـ behavior بتاعه، زي الـ ngClass أو الـ ngStyle. دي بتتحكم في الخصائص أو الـ styles بتاعت العنصر اللي موجود في الـ DOM من غير ما تشيله أو تضيف عناصر جديدة.

</div>
<hr/>

## What are router events?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ Router Events دي عبارة عن الأحداث اللي بتحصل لما الـ router في تطبيقك (زي في Angular مثلاً) بينقلك من صفحة للتانية.

يعني إيه؟ يعني لو إنت مثلاً فاتح صفحة "Home" وعايز تروح لصفحة "About"، الـ router ده هو اللي بيعمل التنقل ده. كل ما تتنقل من صفحة لصفحة، بيحصل شوية أحداث.

#### خلينا نبسطها أكتر:

١. NavigationStart: ده أول ما تبدأ تتحرك من صفحة للتانية، يعني كده بنقول إنك "بدأت التنقل".

٢. NavigationEnd: لما التنقل يخلص وتوصل للصفحة اللي رايح لها، الـ router بيقولك "التنقل خلص بنجاح".

٣. NavigationCancel: لو حصل حاجة وانت في النص، مثلاً أنت لغيت أو فيه مشكلة، يبقى كده التنقل "اتلغى".

٤. NavigationError: لو حصلت مشكلة وانت بتتنقل، زي مثلاً الصفحة مش موجودة أو السيرفر وقع، هنا بنقول "فيه خطأ".

٥. RoutesRecognized: هنا بقى الـ router بيقولك "أيوه أنا عرفت الصفحة اللي انت رايح لها ومستعد أروح لها".

✨الفكرة إنك ممكن تستفيد من الأحداث دي، زي إنك مثلاً تشغل loader (الحاجة اللي بتفضل تلف وانت مستني الصفحة تفتح) أول لما يبدأ التنقل، وبعد ما يخلص تخفيه. أو ممكن تعمل check لو فيه أخطاء في النص عشان تبلغ المستخدم إن في مشكلة.

يعني باختصار، الـ Router Events دي بتديك سيطرة على كل خطوة بتحصل وانت بتتنقل بين صفحات التطبيق.

</div>
<hr/>

## What is activated route?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الActivatedRoute في Angular زي اللي بيقولك إنت واقف فين في  (routes) بتاعت الأبليكيشن. يعني لو إنت فتحت صفحة معينة، هو اللي هيقولك كل التفاصيل بتاعت الصفحة دي، زي  (path) اللي إنت ماشي فيه، أو أي parameters اتحطت في ال URL، زي مثلا لو فتحت صفحة ب ID معين.
</div>
<hr/>

## How do you define routes?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
تعريف الـ Routes في Angular بيتم باستخدام الموديل RouterModule من خلال الطريقة RouterModule.forRoot. بتستخدم الطريقة دي عشان تحدد قائمة من المسارات اللي التطبيق بتاعك هيتعامل معاها. كل مسار (Route) بيبقى مرتبط بـ component معين، يعني لما المستخدم يدخل على المسار ده، الـ component المحدد بيتحمل ويظهر.
<div dir="auto" align="left">

```typescript
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

</div>
</div>
 <hr/>

## What is the purpose of Wildcard route?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الغرض من الـ Wildcard route هو التعامل مع أي روابط (URLs) غير معروفة أو غير معرفة مسبقًا في التطبيق. يعني لو المستخدم دخل على رابط مش موجود في قائمة الـ routes اللي أنت معرفها، بدل ما التطبيق يرمي خطأ أو يتعطل، يتم توجيه المستخدم لصفحة مخصصة زي "صفحة غير موجودة" (Page Not Found).
<div dir="auto" align="left">

```typescript
{ path: '**', component: PageNotFoundComponent }
```

</div>

### '\*\*' path

دي معناها إن أي رابط ما اتعرفش في باقي المسارات هيتم التقاطه من المسار ده. الـ \*\* هو رمز الـ wildcard اللي بيمسك أي URL ما ينطبقش عليه أي من المسارات اللي قبله.

### component

الPageNotFoundComponent: هنا بتحدد الـ component اللي هيتعرض لما المسار يتحقق. في الحالة دي، صفحة الخطأ أو الصفحة اللي بتقول إن الرابط مش موجود.
✨الخلاصة: الـ Wildcard route بيضمن إن التطبيق مش هيكراش بسبب روابط غير معروفة وبيسمحلك تعرض رسالة أو صفحة مخصصة بدل من حدوث خطأ.

</div>
<hr/>

## What is Angular Universal?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الAngular Universal ده ببساطة طريقة إنك تخلي تطبيق Angular بتاعك يشتغل بـ Server-Side Rendering (SSR)، يعني السيرفر هو اللي يولد الـ HTML بدل ما المتصفح يعمل كل حاجة. الطبيعي في تطبيقات Angular العادية إن كل حاجة بتتحمل في المتصفح (الـ HTML والـ JavaScript)، وده ممكن يخلي التحميل الأول للصفحة بطيء شوية خصوصًا على النت البطيء.

#### ليه بقى Angular Universal مهم؟

أداء أسرع: بدل ما المستخدم يقعد مستني لما الصفحة تتحمل بالكامل، السيرفر بيرسل له HTML جاهز أول ما يفتح التطبيق، فبيحس إن الصفحة ظهرت بسرعة.

تحسين الـ SEO: عشان محركات البحث زي جوجل تفهم محتويات الصفحات، لازم تلاقي HTML كامل أول ما تزور الصفحة. الـ SPA (Single Page Applications) زي Angular ممكن يكون عندها مشكلة في النقطة دي لأنها بتحتاج الجافاسكريبت يتنفذ الأول عشان يطلع المحتوى. لكن مع Angular Universal، الصفحة بتطلع بـ HTML جاهز، فمحركات البحث تقدر تقرأها وتحسن ترتيب الموقع.

تجربة أحسن على الشبكات البطيئة: المستخدمين اللي عندهم إنترنت بطيء هيتبسطوا إنهم يشوفوا الصفحة بسرعة من غير ما يقعدوا مستنيين تحميل كل حاجة.

</div>
<hr/>

## What is ng-content?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ ng-content في Angular بنستخدمه عشان نعمل حاجة اسمها content projection، وهي إننا نقدر نمرر HTML من الـ Parent Component للـ Child Component بحيث الـ Child Component يعرض المحتوى ده في مكان معين جوة UI بتاعته.

🔴 لو فكرت فيها، الـ Input@ بيسمح للـ Parent إنه يمرر بيانات للـ Child Component، بس لو حبينا نمرر حاجة زي HTML elements أو محتوى فيه CSS معين، الـ Input@ مش حينفع. وده هنا بييجي دور ng-content.

### مثال توضيحي بسيط

لو عندك Button Component بسيط، هيعرض زراير، وعايز مثلاً تخلي النص اللي جواه "Click Me"، تقدر تعمل كده بإنك تضيف <button>Click Me</button> جوة الكومبوننت.

لكن لو عايز تخلي الـ Parent هو اللي يقرر يكتب إيه جوة الزرار أو يضيف HTML مختلف، بنستخدم ng-content.

### إزاي نعمل ده؟

في المثال ده، بدل ما تحط "Click Me" جوة <button>Click Me</button>، هنحط <ng-content></ng-content> مكانه. وده معناه إن المحتوى اللي بين <app-fancybtn></app-fancybtn> في الـ Parent Component حيتعرض جوة الزرار.

<div dir="auto" align="left">

```typescript
@Component({
  selector: "app-fancybtn",
  template: `<button><ng-content></ng-content></button>`,
})
export class FancyBtnComponent {}
```

</div>
وفي الـ Parent Component هنكتب مثلاً:
<div dir="auto" align="left">

```HTML
<app-fancybtn>Click Me</app-fancybtn>
<app-fancybtn><b>Submit</b></app-fancybtn>

```

</div>
كده النص اللي بين app-fancybtn  هيظهر جوة الزرار في المكان اللي محطوط فيه ng-content. الجميل هنا إنك ممكن تمرر أي محتوى HTML وحيظهر.

### الـ Multiple Projections والـ select attribute

لو عندك كومبوننت زي Card Component وفيه أجزاء زي header وcontent وfooter، تقدر تدي لكل جزء ng-content خاص بيه باستخدام select attribute. بالشكل ده تقدر تمرر محتويات مختلفة للـ Parent والـ Child هيعرضهم في الأماكن الصح.

<div dir="auto" align="left">

```typescript
@Component({
  selector: "app-card",
  template: `
    <div class="card">
      <div class="header"><ng-content select="header"></ng-content></div>
      <div class="content"><ng-content select="content"></ng-content></div>
      <div class="footer"><ng-content select="footer"></ng-content></div>
    </div>
  `,
})
export class CardComponent {}
```

</div>
وفي الـ Parent

<div dir="auto" align="left">

```HTML
<app-card>
  <header><h1>Angular</h1></header>
  <content>One framework. Mobile & desktop.</content>
  <footer><b>Super-powered by Google</b></footer>
</app-card>
```

</div>

### ✨ ng-content without selector catches all

</div>
<hr/>

## what is Angular input and output and EventEmitter?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
أول حاجة، خلينا نبدأ بـ Input@
لو عندك Input@ في الـ child component، ده معناه إنك ممكن تستقبل بيانات من الـ parent component. يعني مثلا لو عندك component اسمه CustomerDetailComponent وعاوز تستقبل بيانات عميل معين من الـ parent component، هتعمل حاجة زي كده:

<div dir="auto" align="left">

```typescript
export class CustomerDetailComponent implements OnInit {
  @Input() customer: Customer;
}
```

</div>
هنا احنا عاملين Input@ فوق الخاصية customer. ده معناه إن الـ parent component هيقدر يبعت قيمة للخاصية دي، زي كده مثلا:

<div dir="auto" align="left">

```HTML
<app-customer-detail [customer]="selectedCustomer"></app-customer-detail>
```

</div>

### ثاني حاجة، الـ Output@ و EventEmitter

لما تيجي تتعامل مع Output@، ده معناه إنك بتبعت أحداث للـ parent component. يعني مثلا لو الـ child component عايز يقول للـ parent component إن العميل اتعدل، هنعمل كالتالي:

<div dir="auto" align="left">

```typescript
@Output() customerChange: EventEmitter<Customer> = new EventEmitter<Customer>();

update() {
  this.customerChange.emit(this.customer);
}
```

</div>
هنا إحنا بنستخدم Output@ فوق الخاصية customerChange اللي من نوع EventEmitter<Customer>. لما نعمل emit للحدث ده عن طريق update function، الـ parent component هيقدر يلتقط الحدث ده ويشوف القيمة اللي بعتها customer.

🔴 في الـ parent component، نقدر نسمع الحدث ده باستخدام كود زي ده

<div dir="auto" align="left">

```HTML
<app-customer-detail [customer]="selectedCustomer" (customerChange)="update($event)"></app-customer-detail>
```

</div> 
هنا في <app-customer-detail> إحنا بنحط customerChange بين أقواس دائرية عشان نقدر نمسك الحدث، وده هيشغل الـ update function اللي في الـ parent component لما يتغير الـ customer.

### ملاحظات إضافية على Input@ و Output@ في Angular

#### 1. إمكانية تمرير اسم اختياري مع Input@

Input@ بتسمح لك بإنك تحدد اسم اختياري، وده بيبقى مفيد لما تحب تسمي الخاصية حاجة في الكود واسم تاني للـ binding في الـ HTML.

<div dir="auto" align="left">

```typescript
@Input('customerData') customer: Customer;
```

</div>
✨ هنا بنستخدم customerData كاسم خاص بالـ binding في الـ Parent، لكن في الكود بنستخدم customer.

#### 2. التعامل مع تغييرات باستخدام Setter

تقدر تعمل setter للخاصية اللي عليها Input@ عشان تضيف أي منطق إضافي أو تتحكم في التغيير قبل ما يتم تعيين القيمة.

<div dir="auto" align="left">

```typescript
private _customerData: Customer;

@Input()
set customer(customer: Customer) {
  this._customerData = customer;
  console.log("Updated customer data:", this._customerData);
}

get customer(): Customer {
  return this._customerData;
}

```

</div>
هنا، كل مرة يتغير فيها customer، هنقدر نشغل كود معين أو نضيف منطق إضافي قبل ما نعطي القيمة للخاصية.

#### 3. الاشتراك في تغييرات Input@ باستخدام ngOnChanges

الAngular بيوفر ngOnChanges كـ lifecycle hook، وده بيسمح لنا نراقب أي تغيير في الخصائص اللي عليها Input@ في أي وقت.

<div dir="auto" align="left">

```typescript
import { OnChanges, SimpleChanges } from "@angular/core";

export class CustomerDetailComponent implements OnChanges {
  @Input() customer: Customer;

  ngOnChanges(changes: SimpleChanges) {
    if (changes["customer"]) {
      console.log("Customer changed:", changes["customer"].currentValue);
    }
  }
}
```

</div>
هنا ngOnChanges هيتم تنفيذه كل مرة يحصل فيها تغيير في الخاصية customer.

#### 4. الEventEmitters تعتبر Observable

الEventEmitters في Angular هي Observable زي RxJS Subjects، وده بيسمح باستخدام مشغلين RxJS عشان تتلاعب بالأحداث، مثلا تقدر تعمل debounceTime، filter، وغيره على الأحداث اللي بتنبعث.

#### 5. تمرير البيانات حسب المرجع (Pass by Reference)

لبيانات من نوع Object وArray بتنتقل حسب Reference يعني أي تغيير فيها بيعدل النسخة الأصلية. عشان كده لما تبعت بيانات من الـ Parent للـ Child، لو عدلتها في الـ Child، هتتغير تلقائيًا في الـ Parent.
البيانات من نوع Primitive زي number و string بتتنقل حسب القيمة، فالتغيير على القيمة مش بيأثر على النسخة الأصلية في الـ Parent.

</div>
<hr/>

## Template Reference Variable in Angular

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الTemplate Reference Variable هي متغيرات بننشئها في  (Template) عشان نقدر نوصل لأي عنصر HTML، أو  (Component)، أو  (Directive) في الTemplate

#### كيفية تعريف Template Reference Variable

نقدر نعرّفها باستخدام علامة # متبوعة باسم المتغير.

#### أمثلة

عنصر HTML

<div dir="auto" align="left">

```HTML
<input type="text" #firstName>
```

</div>
component or directive 
<div dir="auto" align="left">

```HTML
<app-customer #customerList="customer"></app-customer>
```

</div>

#### إظهار القيم باستخدام Template Reference Variables

في المثال ده، بنعرف متغيرات firstName# و#lastName

<div dir="auto" align="left">

```HTML
<h1>Welcome</h1>

<input type="text" #firstName placeholder="First Name" (keyup)="0">
<input type="text" #lastName placeholder="Last Name" (keyup)="0">

<b>Welcome {{ firstName.value }} {{ lastName.value }}</b>
```

</div>
1- عند الكتابة داخل   (input)، بيتم تفعيل الحدث keyup.
بسبب "0"=(keyup), الAngular بيقوم بتشغيل الChange Detection لتحديث القيم اللي في الTemplate.

2- Change Detection بيحدث (view) مباشرة ويعرض القيمة الجديدة اللي كتبتها في الinput

#### لماذا نحتاج "0"=(keyup)"؟

لو شيلنا (keyup) من الكود، ممكن ما يتم تحديث جملة الترحيب بالسرعة اللي بنتوقعها لأن Angular يعتمد على الكشف عن التغييرات فقط عند وقوع حدث غير متزامن أو عند أي حدث متعلق بالكشف عن التغييرات.

</div>
<hr/>

## What is ng-container in Angular?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ ng-container ده عبارة عن طريقة بنستخدمها في أنجولر عشان نعمل تقسيم أو جزء معين في  (template) من غير ما نضيف عنصر HTML فعلي في الصفحة. يعني الـ ng-container نفسه مش بيظهر في الكود النهائي للـ HTML، لكن المحتوى اللي جواه بيظهر.

### ليه بنستخدم ng-container؟

الميزة الرئيسية للـ ng-container إنه بيخلينا نضيف حاجات معينة زي شروط أو تكرارات (زي *ngIf أو *ngFor) من غير ما نضطر نضيف عنصر إضافي في DOM، واللي ممكن يكون ليه تأثير سلبي على الأداء، أو حتى يكون مزعج لو بتعدل في الـ CSS.

#### مثال بسيط

<div dir="auto" align="left">

```HTML
<h1> ng-Container</h1>
<p>Hello  world!</p>
<ng-container>
  المحتوى بتاع الكونتينر.
</ng-container>
```

</div>
الكود ده لما بيتحول لـ HTML النهائي هيكون كالتالي:
<div dir="auto" align="left">

```HTML
<h1> ng-Container</h1>
<p>Hello  world!</p>
المحتوى بتاع الكونتينر.
```

</div>
✨ زي ما انت شايف، الـ ng-container نفسه اختفى، لكن المحتوى اللي جواه ظهر في الصفحة.

### استخدامات ng-container

#### مثال مع ngFor و ngIf

تخيل إن عندك قائمة فيها مجموعة من العناصر وعايز تعرض بس العناصر النشطة (اللي Active)، فهتستخدم *ngFor عشان تعمل لوب على العناصر، و*ngIf عشان تتحقق إذا كان العنصر نشط ولا لأ.

لو استخدمت عنصر زي span مثلا عشان تحط الـ \*ngFor هتلاقي إنه بيضيف عنصر span جديد في DOM لكل عنصر، وده ممكن يخلي الكود أطول وممكن يأثر على الـ CSS.
لكن لو استخدمت ng-container، هتتجنب الحكاية دي

بدون ng-container

<div dir="auto" align="left">

```HTML
<ul>
  <span *ngFor="let item of items;">
    <li *ngIf="item.active">
      {{item.name}}
    </li>
  </span>
</ul>

```

</div>
باستخدام ng-container
<div dir="auto" align="left">

```HTML
<ul>
  <ng-container *ngFor="let item of items;">
    <li *ngIf="item.active">
      {{item.name}}
    </li>
  </ng-container>
</ul>
```

</div>
مثال تاني مع ngIf
لو عندك شرط *ngIf عشان تتحقق من وجود عنصر معين، مفيش داعي تستخدم div أو أي عنصر عشان تحط فيه الشرط ده؛ ممكن تستبدله بـ ng-container

بدون ng-container

<div dir="auto" align="left">

```HTML
<div *ngIf="items1">
  <div *ngFor="let item of items1;">
    {{item.name}}
  </div>
</div>
```

</div>
باستخدام ng-container

<div dir="auto" align="left">

```HTML
<ng-container *ngIf="items1">
  <div *ngFor="let item of items1;">
    {{item.name}}
  </div>
</ng-container>
```

</div>
</div>
<hr/>

## How to use ng-template and TemplateRef in Angular

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الـ ng-template ده عنصر في Angular بيستخدم عشان تحط فيه template معين، لكن من غير ما يتعرض في الصفحة (الـ DOM) بشكل مباشر. يعني هو كأنك بتجهز حاجة وتخليها جاهزة عالرف، ومش بتظهر غير لما تقوله يظهر.

### مثال بسيط

<div dir="auto" align="left">

```HTML

<h2>Defining a Template using ng-Template</h2>

<ng-template>
  <p> Say Hello</p>
</ng-template>
```

</div> 
مش هتلاقي "Say Hello" ظهرت في الصفحة. السبب إن الـ ng-template لوحده مش هيعرض أي حاجة، هو بس بيحطها على جنب لحد ما تيجي أنت تقوله يعرضها فين وإمتى.

### إزاي نعرض الـ template؟

#### فيه كذا طريقة علشان تعرض اللي جوه ng-template

ال ngTemplateOutlet: دي Directive بتخليك تعرض الـ template في مكان معين.

#### مثال باستخدام ngTemplateOutlet

الأول بنعمل الـ template ونحط عليه اسم علشان نقدر نرجعله:

<div dir="auto" align="left">

```HTML
<ng-template #sayHelloTemplate>
  <p>Say Hello/p>
</ng-template>
```

</div>
وبعدين في أي مكان عاوزين نعرض فيه الـ template ده، بنستخدم ng-container بالطريقة دي
<div dir="auto" align="left">

```HTML
<ng-container *ngTemplateOutlet="sayHelloTemplate">
This text is not displayed
</ng-container>
```

</div>
فالنتيجة اللي هتطلع هي
<div dir="auto" align="left">

```HTML
Say Hello
```

</div>
✨ يعني Angular بياخد اللي جوه sayHelloTemplate ويعرضه مكان الـ ng-container

### طب لو عاوز أتحكم فيه أكتر من TS؟

لو محتاج تتحكم في عرض الـ template من جوه TS؟ بتاع الـ Component، ممكن تستخدم حاجة اسمها TemplateRef و ViewContainerRef.

الTemplateRef: ده عبارة عن object بيحتوي على الـ template نفسه (اللي موجود جوه ng-template). بنستخدمه عشان نمسك الـ template ونتحكم فيه من الكود.

الViewContainerRef: ده عبارة عن مكان في الـ DOM (الصفحة) تقدر تعرض فيه الـ template في أي وقت. هو بيحدد المكان اللي الـ template هيظهر فيه، وده بيبقى مفيد لما تكون عاوز تضيف أو تحذف أجزاء من الـ DOM بشكل ديناميكي.

#### مثال باستخدام TemplateRef و ViewContainerRef

 <div dir="auto" align="left">

```typescript
@ViewChild('sayHelloTemplate', { read: TemplateRef }) sayHelloTemplate: TemplateRef<any>;
```

</div>
وبعدين ممكن تستخدمه في الكود علشان تعرضه كده
<div dir="auto" align="left">

```typescript
this.vref.createEmbeddedView(this.sayHelloTemplate);
```

</div>
<div dir="auto" align="left">

```typescript
import {
  Component,
  ViewChild,
  TemplateRef,
  ViewContainerRef,
  AfterViewInit,
} from "@angular/core";

@Component({
  selector: "app-root",
  templateUrl: "./app.component.html",
  styleUrls: ["./app.component.css"],
})
export class AppComponent implements AfterViewInit {
  @ViewChild("sayHelloTemplate", { read: TemplateRef })
  sayHelloTemplate: TemplateRef<any>;

  constructor(private vref: ViewContainerRef) {}

  ngAfterViewInit() {
    this.vref.createEmbeddedView(this.sayHelloTemplate);
  }
}
```

</div>

### ليه استخدمنا AfterViewInit؟

علشان نتاكد إن الـ template بقى جاهز واتحمل في الصفحة، لأن لو جربنا نستخدمه مباشرة في ngOnInit ممكن ميكنش اتحمل بالكامل.

## الng-template مع ngIf

لما تستخدم ngIf، الAngular بيحولها تلقائيًا لـ ng-template (behind the scenes). يعني بدل ما تكتب الكود بالشكل المعتاد

<div dir="auto" align="left">

```HTML
<div *ngIf="selected">
  <p>You are selected</p>
</div>
```

</div>
تقدر تكتبها باستخدام <ng-template> بالشكل ده:
<div dir="auto" align="left">

```HTML
<ng-template [ngIf]="selected">
  <div>
    <p>You are selected</p>
  </div>
</ng-template>
```

</div>

### طيب إيه اللي بيحصل هنا؟

الAngular لما بيشوف \*ngIf بيترجمها تلقائيًا لـ ng-template بحيث لما الشرط يكون true، يعرض اللي جواه، ولو الشرط false، مش هيعرض أي حاجة. فبكده ng-template بيدي مرونة أكبر للتحكم في أماكن العرض وشروطه.

### ليه ممكن تستخدم ng-template بشكل مباشر مع ngIf؟

في حالات ممكن تحتاج تتحكم في طريقة العرض بشكل أوسع من مجرد \*ngIf. مثلاً، لو عاوز تعمل أجزاء تانية تظهر لو الشرط كان false، زي استخدام الـ then و else.

#### مثال مع then و else

لو عندك سيناريو فيه محتوى عاوز تعرضه لما الشرط يكون true، ومحتوى تاني لما الشرط يكون false، تقدر تعملها كده

<div dir="auto" align="left">

```HTML
<div *ngIf="selected; then thenBlock else elseBlock"></div>

<ng-template #thenBlock>
  <p> You are selected</p>
</ng-template>

<ng-template #elseBlock>
  <p> You are selected </p>
</ng-template>
```

</div>
</div>
<hr/>

## How to Use ngTemplateOutlet in Angular?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
في Angular، الـ ngTemplateOutlet هو Directive بيستخدم لعرض Template معين في مكان محدد داخل الـ DOM باستخدام Reference للـ Template ده، وكمان ممكن تمرر معاه بيانات. دي أداة قوية بتسمحلك تستخدم نفس الـ Template أكتر من مرة في أماكن مختلفة وتتحكم في محتواه بناءً على اللي انت محتاجه.

### إزاي نستخدم ngTemplateOutlet

تحديد Template: بنبدأ بكتابة Template باستخدام ng-template، وده بيكون مجرد تصميم مش بيظهر لوحده. لازم نحدد Reference للـ Template ده زي #template1.

<div dir="auto" align="left">

```HTML
<ng-template #template1>
   <p> Template </p>
</ng-template>

```

</div> 
استخدام ngTemplateOutlet: عشان نعرض الـ Template ده في مكان معين، بنستخدم ngTemplateOutlet ونعينه للـ Reference اللي حددناه.
<div dir="auto" align="left">

```HTML
<ng-container *ngTemplateOutlet="template1"></ng-container>
```

</div>
تمرير بيانات للـ Template: ممكن نستخدم خاصية ngTemplateOutletContext عشان نمرر بيانات للـ Template كمان. يعني لو عندنا قيمة اسمها value، نقدر نمررها كالتالي:

<div dir="auto" align="left">

```HTML
<ng-template let-value="value" #messageTemplate>
   <p>القيمة اللي وصلت من الـ Parent هي {{value}}</p>
</ng-template>

<ng-container [ngTemplateOutlet]="messageTemplate" [ngTemplateOutletContext]="{value:'1000'}"></ng-container>
```

</div>

### استخدام $implicit

في Angular، استخدام implicit بيسمحلك تمرر قيمة افتراضية لأي متغير محلي (local variable) في ng-template من غير ما تعينها مباشرة للمتغير ده. ببساطة، لو عينت قيمة للـ implicit في ngTemplateOutletContext، المتغيرات اللي ملهاش قيمة صريحة هتاخد القيمة اللي عينتها لـ $implicit.

<div dir="auto" align="left">

```HTML
<ng-template let-name let-message="messageText" #welcomeTemplate>
  <p>hello {{name}}، {{message}}</p>
</ng-template>

<ng-container
    [ngTemplateOutlet]="welcomeTemplate"
    [ngTemplateOutletContext]="{$implicit: 'mohamed', messageText: 'welcome'}">
</ng-container>

<ng-container
    [ngTemplateOutlet]="welcomeTemplate"
    [ngTemplateOutletContext]="{$implicit: 'hassan', messageText: 'welcome'}">
</ng-container>

```

</div>
الlet-name: هنا إحنا بنعرّف متغير محلي اسمه name داخل الـ ng-template. المتغير ده هياخد قيمته من  implicit اللي بنحدده في كل مرة نستخدم فيها الـ Template.

let-message="messageText": هنا بنعرّف متغير محلي تاني اسمه message داخل نفس الـ Template، والمتغير ده هياخد قيمته من messageText اللي بنمرره في ngTemplateOutletContext.

</div>

## What are signals?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
خليني أقولك ببساطة: الـ"Signals" في Angular هي زي وعاء بيحتفظ بقيمة معينة (سواء رقم، نص، أو حتى بيانات معقدة)، والميزة الكبيرة فيها إنها بتقدر تبلغ أي "مستهلك"  لما القيمة دي تتغير.

فكرتها إنها بتسهّل متابعة أي تغييرات بتحصل على البيانات اللي بنعتمد عليها. يعني، لما مثلاً تبقى عندك واجهة بتظهر (Counter) بيزيد، ممكن تعمل الـ"counter" ده كـ"Signal". لما قيمة العداد تتغير، أي مكان بيستخدم القيمة دي هيعرف فوراً إن فيه تغيير حصل.

### دلوقتي عندنا نوعين من الـ"Signals"

##### الWritable Signal

النوع ده تقدر تغيره بنفسك. يعني تقدر تزود القيمة بتاعته، تنقصها، أو تعدلها بأي شكل.

<div dir="auto" align="left">

```typescript
const count = signal(0);
```

</div>

### ازاي نغير قيمة الـWritable Signal؟

#### تغيير مباشر باستخدام .()set

تقدر تستخدم ()set لو عايز تدي قيمة جديدة مباشرة للـ"signal"

<div dir="auto" align="left">

```typescript
count.set(3); // كده القيمة بقت 3
```

</div>

#### تحديث القيمة باستخدام ()update

تقدر كمان تستخدم ()update علشان تحسب قيمة جديدة بناءً على القيمة الحالية. زي إنك تزود القيمة بواحد:

<div dir="auto" align="left">

```typescript
count.update((value) => value + 1); // كده القيمة بتزيد 1
```

</div>

##### Read-only Signal

النوع ده بيكون للقراءة بس، مش هتقدر تعدل فيه مباشرة. وده بيبقى مفيد في الحالات اللي بتعتمد على حسابات من "signals" تانية، زي لما يبقى عندك مثلاً "double counter" اللي بيعتمد على قيمة "counter" تاني، فبيتحسب تلقائي.

✨ فالـ"Signals" دي بتبسط الموضوع لما يبقى عندك تطبيق معقد، لأن Angular بيتابع أي تحديثات بتحصل في "signals" تلقائياً ويرندر بس الأماكن اللي فعلاً اتغيرت، مش كل الصفحة.

### الComputed Signals

أما الـ"Computed Signals" فهي نوع تاني من "signals" لكن بتبقى للقراءة فقط (read-only)، لأنها بترتبط بقيم signals أخرى وبتحسب قيمة جديدة بناءً عليها. علشان تعمل "computed signal"، بتستخدم دالة ()computed وبتكتب طريقة الحساب بناءً على signals تانية.

<div dir="auto" align="left">

```typescript
const count = signal(0);
const doubleCount = computed(() => count() * 2);
```

</div>
✨ هنا، doubleCount بيحسب القيمة كضعف قيمة count، وبيحدث نفسه تلقائيًا لما count تتغير.

### مميزات الـComputed Signals

#### Lazy Evaluation

الـ"computed signals" بتحسب القيمة بس لما تحتاج تقراها لأول مرة. القيمة بعد كده بتبقى محفوظة (cached)، يعني لما تقراها تاني، Angular مش هيحسبها من الأول، إلا لو في حاجة اتغيرت.

#### Dynamic Dependencies

بتتابع بس الsignals اللي تم قراءتها أثناء الحساب. فلو مثلاً عندنا شرط بيحدد إذا كانت القراءة من count أو لأ، الـ"computed signal" هيتابع count بس في حالة تحقق الشرط، وإلا مش هيتابعها.

### 🔴 ملاحظة مهمة

الـ"computed signals" مش بتقبل التعديل المباشر باستخدام .()set أو .()update لأنها للقراءة بس، وده بيساعد في تأكيد إنه يتم تحديثها تلقائيًا بناءً على signals اللي بتعتمد عليها.

### ليه Signal مش زي المتغير العادي؟

لما بنعمل متغير عادي، لو غيرنا قيمته مش بيأثر في الواجهة مباشرة، وعلشان يحصل ده محتاجين نعمل "تحديث" يدوي. إنما مع الـSignal، لما بتغير القيمة بشكل صحيح، التغيير ده بينعكس تلقائي على الواجهة اللي بتعتمد على القيمة دي.

### الSignal لعدد (Number)

<div dir="auto" align="left">

```typescript
import { signal } from "@angular/core";

const numberSignal = signal(10); // هنا بنخزن قيمة 10 كعدد
```

</div>

🔴 لو حاولنا نغير القيمة كده:

<div dir="auto" align="left">

```typescript
❌
numberSignal = 20;
```

</div>
🤨 المشكلة هنا: إننا غيرنا refrence  بتاع Signal نفسه، لكن Angular مش هيعرف إنه في تغيير لأننا عدينا على الـ Signal مباشرة.

### ✅ الطريقة الصح:

بنستخدم ()set عشان نحدث القيمة:

<div dir="auto" align="left">

```typescript
numberSignal.set(20); // كده بنغير القيمة بطريقة صح
```

</div>
ليه ده صح؟ لأن ()set بتعرف الـ Angular إن في تغيير، فبيحدث أي حاجة بتستخدم القيمة دي تلقائي.

### الSignal ل (Object)

إزاي نعملها:

<div dir="auto" align="left">

```typescript
const userSignal = signal({ name: "Ali", age: 25 });
```

</div>

### ❌ إزاي نعدلها غلط

<div dir="auto" align="left">

```typescript
userSignal().name = "Ahmed";
```

</div>

### ✅ الطريقة الصح:

<div dir="auto" align="left">

```typescript
userSignal.set({ ...userSignal(), name: "Ahmed" });
```

</div>
ليه ده صح؟ هنا استخدمنا ..().userSignal عشان ناخد object القديم بالكامل، وبعدها غيرنا name بس، وبعدين رجعنا object الجديد للـ Signal. كده Angular يعرف إنه في تغيير.

### Signal لقائمة (Array)

إزاي نعملها:

<div dir="auto" align="left">

```typescript
const numbersArraySignal = signal([1, 2, 3]);
```

</div>

### ❌ إزاي نعدلها غلط

<div dir="auto" align="left">

```typescript
numbersArraySignal().push(4);
```

</div>

### ✅ الطريقة الصح:

<div dir="auto" align="left">

```typescript
numbersArraySignal.set([...numbersArraySignal(), 4]); // بنعيد تعيين الأراي كلها
```

</div>
أو نقدر نستخدم ()update:

<div dir="auto" align="left">

```typescript
numbersArraySignal.update((numbers) => [...numbers, 4]);
```

</div>

### Signal لقائمة من (Array of Objects)

إزاي نعملها:

<div dir="auto" align="left">

```typescript
const usersArraySignal = signal([
  { name: "Ali", age: 25 },
  { name: "Mona", age: 30 },
]);
```

</div>

### ❌ إزاي نعدلها غلط

<div dir="auto" align="left">

```typescript
//❌ ده غلط
usersArraySignal()[0].name = "Hassan"; // هنا بنغير الأراي مباشرة وده غلط
```

</div>

### ✅ الطريقة الصح:

<div dir="auto" align="left">

```typescript
usersArraySignal.update((users) =>
  users.map((user) =>
    user.name === "Ali" ? { ...user, name: "Hassan" } : user
  )
);
```

</div>
</div>

## Why Signal?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
الفكرة الأساسية
أولاً، في التطبيقات الكبيرة زي اللي بتعملها بـAngular، الموضوع بيكون مليان بيانات، والبيانات دي بتتغير كل شوية. لما تتغير بيانات معينة، عايزين نعرف إن الجزء ده من التطبيق يتحدث تلقائيًا من غير ما نرجع نرندر كل حاجة من أول وجديد. تقليديًا، الAngular بتعتمد على أدوات زي الـ"Observables" و"Subjects" علشان تتابع التغييرات وتحدث البيانات بشكل تلقائي، لكن الطريقة دي بتتطلب جهد شوية، وبالذات في الحالات اللي فيها حاجات بسيطة زي تغير قيمة عداد أو بيانات خفيفة.

### ليه Signals؟

الـ"Signals" بتقدم طريقة أبسط وأسرع للتعامل مع التغيرات في البيانات من غير ما تضطر تستخدم Observables وطرق معقدة. مثلاً لو عندك قيمة معينة عايزها تتغير وتؤثر على جزء معين في UI ممكن تحطها كـ"Signal". فلما القيمة دي تتغير، كل عنصر أو جزء بيعتمد عليها هيعرف بشكل تلقائي، وده من غير ما ترجع تشغل "change detection" لكل التطبيق.

### الـ"signals" ليها تأثير كبير على عملية change detection في Angular، وده لأنها بتساعد في تحسين الأداء وتبسيط عملية تحديث البيانات بشكل مباشر.

لما بنستخدم الـ"signals"، التحديث بيكون على مستوى كل جزء (أو "Component") بشكل مستقل، بمعنى إن أي جزء بيستخدم قيمة معينة من "signal" هيتم تحديثه بس لو حصل تغيير في القيمة دي، من غير ما يضطر Angular يشغل عملية change detection لكل التطبيق. فده بيوفر كفاءة أكبر في التطبيقات الكبيرة، ويقلل من كمية الأكواد المطلوبة للتحديث.

### التوافق مع "OnPush" Strategy

لو بتستخدم استراتيجية "OnPush" للتحديثات في Angular، فالـ"signals" بتتكامل معاها بشكل ممتاز، لأنها بتسمح بتحديث القيم اللي بتتأثر بشكل مباشر من غير ما يتم تحديث كل شيء. لما يكون عندك جزء معين بيعتمد على "signal"، و"OnPush" مفعل، الواجهة هتتحدث تلقائيًا لما تتغير قيمة الـ"signal" من غير تدخل أو إعادة حسابات غير ضرورية.

### تقليل الحمل على الذاكرة والبروسيسور

مع الـ"signals"، Angular مش بيحتاج يشغل كل الـ change detection cycles، لأن الـ"signal" بيبعت إشعار بإن التغيير حصل بس للأجزاء اللي بتعتمد على القيمة دي. فبكده بنقلل من الضغط على الذاكرة والبروسيسور، وده بيساعد في تحسين أداء التطبيق عمومًا.

### سهولة في التعامل مع التغيرات المتكررة

الـ"signals" بتتيح طريقة بسيطة للتعامل مع القيم اللي بتتغير بشكل متكرر، زي مثلاً counter أو حالة معينة. باستخدام signals، ممكن تتحكم في عملية التحديث من غير ما تحتاج تكتب أكواد إضافية لمتابعة التغييرات، وده بيسهل على المطورين التعامل مع الـUI بشكل ديناميكي وفعال.

### ✨ خلاصة

فايدة الـ"signals" الأساسية في الـchange detection هي إنها بتخلي التحديثات أكتر تركيزًا وأقل حملًا على النظام، وده بيحسن من استجابة التطبيق بشكل كبير وبيوفر وقت وجهد كبير على المطورين، خاصةً في التطبيقات اللي فيها بيانات كتير بتتحدث باستمرار.

</div>

## Angular signals and observables: How and when to use each

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### إيه هي مشكلة الـ Observables وليه ظهر الـ Signals؟

الـ Observables تعتبر أداة قوية في Angular بتخلينا نتحكم في البيانات المتغيرة على مدار الوقت، زي لما بيجيلك تحديثات لبيانات التطبيق من API أو WebSocket. يعني لو عندك حاجة بتتغير بانتظام (زي رقم بيزيد كل ثانية)، تقدر تستخدم Observable علشان تتابع التغييرات دي.

فكرة الـ Observable هي إنها بتطلع القيم الجديدة للبيانات وتبعت إشارات للتحديثات دي للتطبيق، وده بيحصل على مدار الوقت، مش مرة واحدة وخلاص. باستخدام الـ “async pipe” ممكن تخلي القيم تظهر في الـ UI مباشرةً. بس العيب إن استخدام الـ Observables أحياناً بيكون معقد، وخصوصًا لما بتجمع أكتر من مصدر للبيانات أو لما تستخدم عمليات معقدة كتير من RxJS، اللي ممكن تخلي الكود صعب يتفهم أو يتتبع، وممكن كمان يعمل مشاكل في الأداء والذاكرة لو مش متظبط صح.

### طيب.. إيه الجديد في الـ Signals؟

الـ Signals بقت جزء من Angular من أول الإصدار 16، وبتقدم طريقة جديدة وأبسط في التعامل مع البيانات المتغيرة. الفكرة ببساطة إنك بدل ما تستخدم Observable وتتعامل مع التعقيد بتاع RxJS، تقدر تستخدم Signal لتحديث البيانات. الميزة هنا إنها بتسمحلك تتابع التغيرات بطريقة أبسط وأكتر تحكم، وده بيفيد في حاجات كتير خاصة في التطبيقات الكبيرة اللي فيها تفاصيل كتير عايزة تحديث بانتظام من غير ما تعمل عبء كبير على الأداء.

### إمتى تستخدم الـ Signals ومتى تستخدم الـ Observables؟

#### 🔴 أولاً: امتى تستخدم الـ observables؟

الـ observables بتكون مناسبة جدًا في حالة البيانات اللي بتيجي على شكل تدفق مستمر زي الداتا اللي جايه من API، إشعارات الـ real-time، أو العمليات اللي بتم بشكل غير متزامن. يعني لو عندك service بتجيب بيانات كل شوية أو بتتغير كل شوية زي إشعارات أو حاجة بتتحدث بانتظام، فالأفضل هنا إنك تستخدم observable.

لازم تشترك subscribe في الـ observable عشان تاخد البيانات، ولما تخلص بتحتاج تعمل unsubscribe عشان تقفل الاتصال وتوفر موارد.
كمان في الـ observables تقدر تعمل حاجات زي التصفية، الترتيب، والتعديل باستخدام الـ pipe والـ operators، ودي بتساعدك تعمل معالجة للداتا اللي جاية بشكل مرن وسهل.

#### 🔴 ثانيًا: امتى تستخدم الـ signals؟

الـ signals في Angular بتكون أفضل في الجزء الخاص بالـ UI، يعني الجزء اللي بيتعامل مع UI أو components بشكل مباشر. لو عندك بيانات عايز تعرضها وتتغير بشكل ديناميكي مع كل تعديل، الـ signals هتكون مناسبة.

مش بتحتاج تعمل subscribe أو unsubscribe زي الـ observable؛ هنا بتستخدم set عشان تغير القيمة أو update عشان تحدث القيمة بناءً على الحالة الحالية.

كمان تقدر تستخدم حاجة اسمها computed signals اللي بتسمح لك تعمل إشارات جديدة بتعتمد على إشارات موجودة فعلاً، ودي مفيدة لما يكون عندك أكتر من عنصر بيعتمد على داتا واحدة.
استخدام الـ signals هيكون مناسب لو التصميم بتاع الـ template بيعتمد على تغيير لحظي، عشان تتأكد إن components بتتحدث مع كل تعديل في الداتا بدون لخبطة أو مشاكل.

</div>

## What is Effect in signal?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
ببساطة، الـEffects في Angular هي عبارة عن عمليات بتشتغل بشكل تلقائي كل مرة تحصل فيها أي تغييرات في قيمة معينة بنسميها Signal.

الفكرة هي إن الـEffect بيسجل قيمة الـSignal اللي بيتتبعها، ولما يحصل تغيير في قيمة الـSignal دي، الـEffect ده بيشتغل تاني ويعمل العمليات المطلوبة.

يعني مثلا لو عندك عداد وعايز تسجل القيمة كل مرة تتغير فيها، ممكن تستخدم الـEffect كالتالي

<div dir="auto" align="left">

```typescript
effect(() => {
  console.log(`The current count is ${count()}`);
});
```

</div>
هنا، كل مرة قيمة count تتغير، الـEffect هيشتغل وهيطبع القيمة الجديدة للعداد. الفايدة هنا إنك مش محتاج تكتب كود منفصل للتأكد إن القيمة اتغيرت، Angular بيقوم بالموضوع ده تلقائيًا نيابة عنك.

#### إيه هي حالات الاستخدام للـEffects؟

مش مطلوب إنك تستخدم الـEffects دايمًا، لكن فيه شوية حالات معينة ممكن تحتاج تستخدمها فيها:

##### Logging data being displayed and when it changes, either for analytics or as a debugging tool.

مثلا لو محتاج تسجل أي تغير بيحصل في الداتا اللي بتظهر للمستخدم، عشان التحليل أو التتبع.

##### Keeping data in sync with window.localStorage.

مزامنة البيانات مع localStorage: عشان البيانات تحفظ محليًا وتتحدث تلقائيًا.

##### Adding custom DOM behavior that can't be expressed with template syntax.

#### Injection context

في Angular، التعامل مع Injection Context أمر أساسي لإنشاء الـEffects بطريقة صحيحة، إذ تحتاج هذه البيئة (Injection Context) لتشغيل ()effect داخل سياق تقدر تستدعي فيه دوال inject، مثل الكومبوننت، (directives)، أو (services). فيما يلي طرق مختلفة لتنفيذ الـEffects ضمن Injection Context:

وبذلك يظل الـEffect يعمل فقط أثناء حاجة الكومبوننت له، ويتوقف تلقائيًا عندما يتم تدمير الكومبوننت.

تسجيل Effect داخل كود البناء (constructor)
أبسط طريقة هي تسجيل الـEffect داخل الـconstructor مباشرة في الكومبوننت أو الخدمة. مثلًا

باختصار، استخدام Injection Context يسهل إنشاء وإدارة الكائنات والخدمات بطريقة تجعل التطبيق مرنًا، مستقرًا، وقابلاً للصيانة

<div dir="auto" align="left">

```typescript
@Component({...})
export class EffectiveCounterComponent {
  readonly count = signal(0);

  constructor() {
    // Register a new effect.
    effect(() => {
      console.log(`The count is: ${this.count()}`);
    });
  }
}
```

</div>

##### ممكن كمان تسجل الـEffect كجزء مستقل في الكومبوننت وتدي له اسم يوضح وظيفته.

الطريقة دي بتساعد لو عايز تتابع أو توضح الهدف من الـEffect بشكل أوضح، وكمان بتخلي الكود منظم أكتر.

<div dir="auto" align="left">

```typescript
@Component({...})
export class EffectiveCounterComponent {
  readonly count = signal(0);
  private loggingEffect = effect(() => {
    console.log(`The count is: ${this.count()}`);
  });
}
```

</div>

##### إنشاء Effect خارج الـconstructor باستخدام Injector

في بعض الحالات، قد تحتاج إلى إنشاء Effect خارج الـconstructor، ويمكنك هنا تمرير Injector إلى effect كخيار (Option)

<div dir="auto" align="left">

```typescript
@Component({...})
export class EffectiveCounterComponent {
  readonly count = signal(0);
  constructor(private injector: Injector) {}
  initializeLogging(): void {
    effect(() => {
      console.log(`The count is: ${this.count()}`);
    }, {injector: this.injector});
  }
}
```

</div>

### Destroying effects

الـEffects في Angular بيتم تدميرها تلقائيًا لما ينتهي المكان اللي اتسجلت فيه (زي الكومبوننت أو service). يعني لو عندك Effect معمول في كومبوننت، هيتدمر بشكل تلقائي لما الكومبوننت نفسه يتدمر.
نفس الكلام بينطبق على التوجيهات (directives) و (services).

في نفس الوقت، كل Effect بيرجع حاجة اسمها EffectRef، ودي بتديك القدرة على تدمير الـEffect يدويًا لو احتجت كده.
عن طريق استدعاء ()destroy على الـEffectRef، تقدر تنهي الـEffect وقت ما تحب.

 <div dir="auto" align="left">

```typescript
@Component({...})
export class ExampleComponent {
  private count = signal(0);
  private effectRef = effect(() => {
    console.log(`The count is: ${this.count()}`);
  }, { manualCleanup: true });

  ngOnDestroy() {
    this.effectRef.destroy();
  }
}
```

</div>
 ✨في المثال ده، الـEffect مش هيتدمر تلقائيًا، وإنت مسؤول عن تدميره يدويًا في الدالة ngOnDestroy للتأكد إنه مش هيبقى شغال بعد انتهاء الكومبوننت.
</div>

## ElementRef in Angular

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### ما هو ElementRef؟

الElementRef هو Object بيتيح لنا الوصول المباشر للعنصر في الـDOM من داخل الكومبوننت أو الديركتيف.

غالبًا، في أغلب حالات الـAngular، بنعتمد على (Bindings) , (Directives) لتغيير الـDOM بشكل غير مباشر، لكن في حالات معينة، بنحتاج نوصل للعنصر نفسه عشان نعمل عمليات خاصة عليه، زي التفاعل مع مكتبات JavaScript خارجية أو إجراء تعديلات معينة على العنصر مباشرة.

### ليه نحتاج ElementRef؟

أحيانًا نحتاج نعدل حاجة محددة في العنصر مباشرة، مش كل حاجة بتكون ممكنة بالـAngular bindings. على سبيل المثال:

إضافة أو تعديل بعض الخصائص (CSS Styles) بشكل ديناميكي.

التعامل مع مكتبات JavaScript خارجية محتاجة الـDOM Element مباشرة.

تنفيذ تعديلات أو تنقلات مباشرة على العنصر مش ممكنة بسهولة بالـAngular.

### إزاي نستخدم ElementRef؟

##### أول خطوة: إنشاء Template Reference Variable

أول حاجة، عشان تقدر تستخدم ElementRef، لازم تنشئ حاجة اسمها Template Reference Variable في التيمبلت.

ده بيكون متغير بيشير للعنصر اللي عاوز توصله، وبتكتبه بالشكل ده في الـHTML بتاعك:

<div dir="auto" align="left">

```HTML
<div #hello>Hello Angular</div>
```

</div> 
هنا، hello# ده هو Template Reference Variable للعنصر div

. بيدينا زي اسم داخلي نقدر نوصل بيه للعنصر ده من كود الكومبوننت.

#### الخطوة الثانية: الوصول لـ ElementRef باستخدام ViewChild

عشان نستخدم hello جوه كود الكومبوننت، بنستعمل ViewChild@، وده بيسمح لـAngular إنه يححقن لنا refrence للعنصر في الكومبوننت بشكل مباشر.

<div dir="auto" align="left">

```typescript
import { Component, ElementRef, ViewChild } from "@angular/core";

@Component({
  selector: "app-root",
  template: `<div #hello>Hello Angular</div>`,
})
export class AppComponent {
  @ViewChild("hello", { static: false }) divHello: ElementRef;

  ngAfterViewInit() {
    console.log(this.divHello.nativeElement.innerText); // هيطبع 'Hello Angular'
  }
}
```

</div>

هنا، ViewChild@ بيعمل ربط بين المتغير divHello والـElementRef للعنصر اللي عليه الـTemplate Reference Variable hello.

##### nativeElement

بداخل ElementRef، عندنا خاصية nativeElement اللي بترجع العنصر نفسه من الـDOM، وبالتالي تقدر تتعامل مع العنصر مباشرة زي ما بتعمل في JavaScript العادي.

#### استخدام الـRead Token لما يكون في ديركتيف تاني على العنصر

أحيانًا بيكون في ديركتيفات على نفس العنصر زي ngModel. لو عاوز توصل للعنصر نفسه كـElementRef بدل ما توصل للديركتيف ngModel، هنا بييجي دور الـread token. ده بيساعدنا نحدد نوع المرجع اللي محتاجينه (سواء ElementRef أو ديركتيف زي NgModel).

#### مثال مع ngModel

مثلاً عندنا input عليه ngModel كالتالي:

<div dir="auto" align="left">

```HTML
<input #nameInput [(ngModel)]="name">
```

</div> 
في المثال ده، عاوزين نوصل للعنصر نفسه كـElementRef أو نوصل للـngModel لو محتاجين نشتغل بيه. نقدر نحدد ده باستخدام read بالشكل التالي:

<div dir="auto" align="left">

```typescript
import { Component, ElementRef, ViewChild } from "@angular/core";
import { NgModel } from "@angular/forms";

@Component({
  selector: "app-root",
  template: `<input #nameInput [(ngModel)]="name" />`,
})
export class AppComponent {
  name: string;

  // هنا بنطلب الـ ElementRef للعنصر input
  @ViewChild("nameInput", { static: false, read: ElementRef })
  elRef: ElementRef;

  // هنا بنطلب ngModel المرتبط بالعنصر
  @ViewChild("nameInput", { static: false, read: NgModel }) inRef: NgModel;

  ngAfterViewInit() {
    console.log(this.elRef.nativeElement); // بيرجع العنصر `<input>`
    console.log(this.inRef.model); // بيرجع القيمة المرتبطة بـ ngModel
  }
}
```

</div>

### ElementRef in Custom Directive

استخدام ElementRef في ديركتيف مخصص بيتيح لك تتعامل مع host element للديركتيف بشكل مباشر، زي ما بيظهر في مثال ttClass اللي عملنا فيه ديركتيف بيضيف كلاس معين للعنصر.

#### مثال: ديركتيف ttClass

في الكود اللي كتبناه، ttClass هو ديركتيف مخصص بيستخدم ElementRef للوصول للعنصر host element وإضافة كلاس معين عليه، زي كالتالي:

<div dir="auto" align="left">

```typescript
import { Directive, ElementRef, Input, OnInit } from "@angular/core";

@Directive({
  selector: "[ttClass]",
})
export class ttClassDirective implements OnInit {
  @Input() ttClass: string;

  constructor(private el: ElementRef) {}

  ngOnInit() {
    this.el.nativeElement.classList.add(this.ttClass);
  }
}
```

</div>

### استخدامه في HTML:

لما تستخدم الديركتيف ttClass، هتكتب زي كده في الـHTML:

<div dir="auto" align="left">

```HTML
<div ttClass="highlight">Hello World!</div>
```

</div>
الكود ده هيضيف الكلاس highlight للعنصر div.

### 🔴 ملاحظات مهمة عند استخدام ElementRef

الElementRef بيسمح لك تتعامل مع العناصر مباشرةً، لكن Angular بتحذر من الاعتماد عليه كتير لأنه بيخلي التطبيق مرتبط جدًا بطريقة عرض العناصر، وده ممكن يسبب مشاكل في بعض الحالات، زي لما تتعامل مع Web Workers أو Server-side rendering. Renderer2 يعتبر بديل آمن لأنه بيسمح لك تتعامل مع العناصر بطريقة بتشتغل في بيئات مختلفة بدون الاعتماد المباشر على DOM.

### حماية ضد XSS Injection Attacks

استخدام ElementRef بطريقة غير صحيحة ممكن يعرض التطبيق لمشاكل أمنية زي هجمات XSS (Cross-Site Scripting).

### بديل آمن: Renderer2

الRenderer2 هو API من Angular بيتيح لك التعامل مع الـDOM بشكل آمن ويتوافق مع بيئات مختلفة.

### ✨ الخلاصة

الElementRef مفيد في بعض الحالات لكنه يحتاج حذر لأنه مرتبط مباشرةً بالـDOM.

الRenderer2 هو الخيار الأفضل لو محتاج تضمن أمان أكتر في التعامل مع العناصر.

</div>

## What is Renderer2 ?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

الRenderer2 في Angular هو API بيتيح لك تتعامل مع عناصر الـ DOM بطريقة آمنة ومتوافقة مع بيئات مختلفة، وده بيكون أفضل من التعامل المباشر مع الـ DOM باستخدام ElementRef.

الRenderer2 بيستخدم في حالات زي إضافة أو إزالة كلاس، تغيير ستايلات CSS، التعامل مع الأحداث، وإضافة أو حذف عناصر في الـ DOM.

### ليه نستخدم Renderer2 بدل ElementRef؟

لو استخدمت ElementRef للتعامل مع الـ DOM مباشرة، هيشتغل في المتصفح (Browser) بس. لكن لو عاوز تشغل التطبيق بتاعك في بيئات تانية زي:

الWeb Workers (لتشغيل الكود بعيدًا عن الواجهة الأساسية).

الServer-Side Rendering (لتحميل التطبيق من السيرفر زي Angular Universal).

تطبيقات الموبايل وسطح المكتب.

✅ الـ Renderer2 بيخلي الكود متوافق ويشتغل في كل البيئات دي، لأنه بيعمل كـ "طبقة وسطية" بين كودك وعناصر الـ DOM.

### استخدامات Renderer2

1. تغيير الخصائص (Properties) والستايلات (Styles)
   بدل ما تستخدم ElementRef.nativeElement.style، تقدر تستخدم Renderer2 لإضافة أو إزالة ستايلات على العنصر. زي كده:

<div dir="auto" align="left">

```typescript
@ViewChild('myDiv') myDiv: ElementRef;

constructor(private renderer: Renderer2) {}

addStyle() {
  this.renderer.setStyle(this.myDiv.nativeElement, 'color', 'blue'); // يغير اللون للأزرق
}

removeStyle() {
  this.renderer.removeStyle(this.myDiv.nativeElement, 'color'); // يشيل اللون
}
```

</div>

### 2. إضافة أو إزالة كلاس

ممكن تضيف أو تشيل كلاس للعنصر زي addClass وremoveClass

<div dir="auto" align="left">

```typescript
addClass() {
  this.renderer.addClass(this.myDiv.nativeElement, 'highlight');
}

removeClass() {
  this.renderer.removeClass(this.myDiv.nativeElement, 'highlight');
}
```

</div>

### 3. التعامل مع events

ممكن كمان تستخدم Renderer2.listen عشان تتعامل مع الأحداث بطريقة آمنة ومتوافقة مع Angular

<div dir="auto" align="left">

```typescript
ngAfterViewInit() {
  this.clickListener = this.renderer.listen(this.myDiv.nativeElement, 'click', () => {
    console.log('Div clicked!');
  });
}

ngOnDestroy() {
  this.clickListener(); // تلغي الاشتراك في الحدث عشان ما يبقاش فيه تسريب للذاكرة
}
```

</div>

### 4. إنشاء عناصر جديدة وإضافتها

تقدر تنشئ عناصر جديدة وتضيفها للـ DOM باستخدام Renderer2

<div dir="auto" align="left">

```typescript
createElement() {
  const newDiv = this.renderer.createElement('div');
  const text = this.renderer.createText('Hello Angular');

  this.renderer.appendChild(newDiv, text); // تضيف النص للعنصر
  this.renderer.appendChild(this.myDiv.nativeElement, newDiv); // تضيف العنصر للـ DOM
}
```

</div>

</div>

## How to Use @ViewChild and @ViewChildren

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

ال@ViewChild بتستخدمها لو عايز تجيب عنصر معين من عناصر الـ DOM (زي زرار أو كومبوننت تاني) عشان تتعامل معاه من الكود، وبتديك أول عنصر يطابق الشرط اللي حطيته.

ال@ViewChildren بتديك كل العناصر اللي بتطابق الشرط اللي حطيته، وبتطلعهم في QueryList تقدر تلف عليها وتستخدم كل عنصر منها.

### إزاي تستخدم ViewChild@؟

<div dir="auto" align="left">

```typescript
@ViewChild(ChildComponent, { static: true }) child: ChildComponent;
```

</div>

### خليني أوضح أكتر النقطة دي:

```bash
@ViewChild(ChildComponent, { static: true })
```

هنا ChildComponent هو نوع أو كلاس العنصر اللي عايزين نجيبه (في الحالة دي، بنجيب عنصر معين اللي هو الكومبوننت ChildComponent).

🔴static: true و static: false
الخيار static بيحدد امتى Angular تجيب العنصر وتديك مرجع ليه. فيه حالتين هنا:

### static: true

لو حطينا static: true، ده معناه إن Angular هتجيب المرجع للعنصر قبل ما تعمل أول تغيير (Change Detection). بمعنى تاني، Angular هتجيب العنصر من الـ DOM في بداية تحميل الصفحة أو الكومبوننت، وده مفيد لو العنصر دايمًا بيبقى موجود في التيمبلت بتاعنا.

### static: false

لو حطينا static: false، ده معناه إن Angular هتستنى لحد ما تكمل أول Change Detection وتحدد العناصر اللي هتظهر حسب شروط معينة زي *ngIf أو *ngSwitch.

يعني لو العنصر بيظهر بناءً على شرط معين أو بيتم تحميله ديناميكيًا، لازم تستخدم static: false، عشان Angular تستنى لحد ما الشرط يتحقق أو العنصر يظهر في التيمبلت.

### مثال للتوضيح

لو عندنا عنصر بيتحكم في ظهوره شرط معين، زي \*ngIf، لازم نستخدم static: false عشان نضمن إن Angular هتنتظر لحد ما يتحقق الشرط ده ويظهر العنصر في التيمبلت.

<div dir="auto" align="left">

```HTML
<div *ngIf="showChildComponent">
  <child-component></child-component>
</div>
```

</div>

<div dir="auto" align="left">

```typescript
@ViewChild(ChildComponent, { static: false }) child: ChildComponent;
```

</div>
هنا، Angular هتستنى لحد ما يحصل تغيير (Change Detection) ويتحقق شرط *ngIf، وبعد كده هتجيب ChildComponent لما يكون موجود في التيمبلت.

### مثال بسيط

عندنا كومبوننت صغير اسمه ChildComponent فيه عداد، وفيه زراير لزيادته أو نقصانه:

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";

@Component({
  selector: "child-component",
  template: `<h2>Child Component</h2>
    <p>Current count: {{ count }}</p>`,
})
export class ChildComponent {
  count = 0;

  increment() {
    this.count++;
  }
  decrement() {
    this.count--;
  }
}
```

</div>
في الكومبوننت الأب (Parent Component)، عايزين نجيب الـ ChildComponent ونتحكم في العداد بتاعه. نستخدم ViewChild@ كالتالي:

<div dir="auto" align="left">

```typescript
import { Component, ViewChild } from "@angular/core";
import { ChildComponent } from "./child.component";

@Component({
  selector: "app-root",
  template: `
    <h1>Parent Component</h1>
    <button (click)="increment()">Increment</button>
    <button (click)="decrement()">Decrement</button>
    <child-component></child-component>
  `,
})
export class AppComponent {
  @ViewChild(ChildComponent, { static: true }) child: ChildComponent;

  increment() {
    this.child.increment();
  }

  decrement() {
    this.child.decrement();
  }
}
```

</div>
استخدام Template Reference Variable مع ViewChild@
بدل ما نحدد النوع بتاع الكومبوننت، ممكن نستخدم Template Reference Variable. 
يعني ندي اسم للعنصر في التيمبلت زي كده:

<div dir="auto" align="left">

```HTML
<child-component #childRef></child-component>
```

</div>
وبعدين نجيبه في الكود:
<div dir="auto" align="left">

```typescript
@ViewChild('childRef', { static: true }) child: ChildComponent;
```

</div>

### التعامل مع عناصر الـ HTML باستخدام ElementRef

لو عايز تجيب عنصر HTML زي p أو div، ممكن تستخدم ViewChild@ مع ElementRef.

### مثال:

<div dir="auto" align="left">

```HTML
<p #para>Some text</p>
```

</div>

<div dir="auto" align="left">

```typescript
import { Component, ElementRef, ViewChild, AfterViewInit } from "@angular/core";

@Component({
  selector: "htmlelement",
  template: `<p #para>Some text</p>`,
})
export class HTMLElementComponent implements AfterViewInit {
  @ViewChild("para", { static: false }) para: ElementRef;

  ngAfterViewInit() {
    console.log(this.para.nativeElement.innerHTML);
    this.para.nativeElement.innerHTML = "new text";
  }
}
```

</div>

### 🔴 لو عندك أكتر من عنصر بنفس النوع؟

لو عندك أكتر من عنصر زي ChildComponent في نفس التيمبلت، ViewChild@ هترجعلك أول واحد بس. لكن لو عايز كل العناصر، استخدم ViewChildren@

### مثال مع ViewChildren@

في المثال ده، عندنا أكتر من input:

<div dir="auto" align="left">

```HTML
<input name="firstName" [(ngModel)]="firstName">
<input name="middleName" [(ngModel)]="middleName">
<input name="lastName" [(ngModel)]="lastName">
```

</div>
نجيبهم باستخدام ViewChildren@ كالتالي:
<div dir="auto" align="left">

```typescript
import { Component, ViewChildren, QueryList, NgModel } from "@angular/core";

@Component({
  selector: "app-viewchildren-example",
  template: `
    <input name="firstName" [(ngModel)]="firstName" />
    <input name="middleName" [(ngModel)]="middleName" />
    <input name="lastName" [(ngModel)]="lastName" />
    <button (click)="show()">Show</button>
  `,
})
export class ViewChildrenExampleComponent {
  @ViewChildren(NgModel) modelRefList: QueryList<NgModel>;

  show() {
    this.modelRefList.forEach((element) => {
      console.log(element);
    });
  }
}
```

</div>
هنا ViewChildren@ بترجع كل input، وتقدر تلف عليهم باستخدام ()forEach

### 🔴 ملحوظلة

لما نستخدم ViewChild@ او ViewChildren@ في Angular، بنحتاج نستنى لحد ما العناصر في الـ DOM تكون اتعملها تحميل بالكامل قبل ما نقدر نستخدمها في الكود.

عشان كده، الـlifecycle hook المناسبة للتعامل مع ViewChild@ هي ngAfterViewInit مش ngOnInit.

</div>

## ContentChild and ContentChildren in Angular

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### إيه هما ContentChild و ContentChildren؟

الContentChild@ و `ContentChildren@` هما (Decorators) في Angular بنستخدمهم عشان نوصل لحاجة اسمها "Projected Content"، اللي هو المحتوى اللي بيجي للكومبوننت من كومبوننت الأب (Parent Component).

الProjected Content يعني محتوى جاي من الكومبوننت الأب عشان يتعرض في الكومبوننت الابن، وبنحدده عادةً باستخدام عنصر `ng-content` اللي بنضيفه في الكومبوننت الابن عشان يحجز مكان لعرض المحتوى اللي جاي من بره.

### الفرق بين `ViewChild@` و `ContentChild@`

🔴 الViewChild@ و ViewChildren@ بيقدروا يجيبوا أي عنصر موجود جوه الكومبوننت نفسه، سواء كان عنصر HTML، أو كومبوننت تاني، أو ديركتيف.

🔴 الContentChild@ و ContentChildren@ بقى بيستخدموا للوصول للمحتوى اللي جاي من الكومبوننت الأب عبر `ng-content`، يعني بيقدروا يجيبوا أي حاجة جاية من بره مش موجودة بشكل مباشر جوه الكومبوننت.

### إزاي بنستخدم ContentChild و ContentChildren؟

1. مثال بسيط على ContentChild
خلينا نقول عندنا كومبوننت (CardComponent) بيستخدم <ng-content> عشان ياخد محتوى من بره ويعرضه جواه.
مثلا الكارت فيه 3 أماكن: `header`, `content`, `وfooter`
<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";

@Component({
  selector: "card",
  template: `
    <div class="card">
      <ng-content select="header"></ng-content>
      <ng-content select="content"></ng-content>
      <ng-content select="footer"></ng-content>
    </div>
  `,
  styles: [
    `
      .card {
        min-width: 280px;
        margin: 5px;
        float: left;
      }
    `,
  ],
})
export class CardComponent {}
```

</div>

الكود ده هيحجز 3 أماكن في الكارت: واحد لـ header، والتاني لـ content، والتالت لـ footer

2. استخدام ContentChild للوصول للعنصر المرسل من الكومبوننت الأب
   دلوقتي لو عندنا في الكومبوننت الأب كذا كارت وعايزين نضيف لكل كارت محتوى مختلف، نكتب الكود بالشكل ده:

<div dir="auto" align="left">

```HTML
<card>
  <header><h1 #header>Angular</h1></header>
  <content>One framework. Mobile & desktop.</content>
  <footer><b>Super-powered by Google</b></footer>
</card>
```

</div>

في المثال ده، إحنا ضفنا header, content, وfooter لكارت واحد، وحددنا `<h1 #header>` اللي موجود في header.

دلوقتي عايزين نوصل للـ h1 اللي في header جوه CardComponent باستخدام ContentChild@

<div dir="auto" align="left">

```typescript
import {
  Component,
  ContentChild,
  ElementRef,
  AfterContentInit,
  Renderer2,
} from "@angular/core";

@Component({
  selector: "card",
  template: `
    <div class="card">
      <ng-content select="header"></ng-content>
      <ng-content select="content"></ng-content>
      <ng-content select="footer"></ng-content>
    </div>
  `,
})
export class CardComponent implements AfterContentInit {
  @ContentChild("header") cardContentHeader: ElementRef;

  constructor(private renderer: Renderer2) {}

  ngAfterContentInit() {
    this.renderer.setStyle(
      this.cardContentHeader.nativeElement,
      "font-size",
      "20px"
    );
  }
}
```

</div>

### 🔴 النقطة المهمة هنا

ال`ContentChild('header')@` بيجيب أول عنصر اسمه header موجود في الـ Projected Content.

الngAfterContentInit هو الـ lifecycle hook المناسب عشان نضمن إن Angular حملت المحتوى الخارجي.

### ContentChildren@ عشان تجيب أكتر من عنصر

لو عندنا كذا عنصر بنفس الاسم (مثلا كذا عنصر header)، ممكن نستخدم ContentChildren@ عشان نجيبهم كلهم في شكل قائمة (QueryList) ونقدر نلف عليهم ونتعامل مع كل عنصر فيهم.

<div dir="auto" align="left">

```typescript
@ContentChildren('header') headers: QueryList<ElementRef>;
```

</div>

### الفرق بين ContentChild و ContentChildren

ال@ContentChild بيجيب أول عنصر بس يطابق الاسم.

ال@ContentChildren بيجيب كل العناصر اللي ليها نفس الاسم في شكل قائمة (QueryList)، وتقدر تستخدم forEach عشان تتعامل مع كل عنصر لوحده.

### ✅ الفرق بين ViewChild@ و ContentChild@

| #             | ViewChild و ViewChildren              | ContentChild و ContentChildren                      |
| ------------- | ------------------------------------- | --------------------------------------------------- |
| **الاستخدام** | بيدور على العناصر جوه الكومبوننت نفسه | بيدور على المحتوى اللي جاي من بره                   |
| **التوقيت**   | بيشتغل بعد تحميل التيمبلت             | بيشتغل بعد تحميل المحتوى الخارجي (AfterContentInit) |

</div>

## What are decorators in angular ?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

الـ Decorators في Angular هي عبارة عن وظيفة أو دالة بتدي معلومات إضافية عن الكلاس (class) أو (method) أو (property) أو (parameter).

بتدي معلومات لـ Angular عشان تفهم الكود وتعرف إزاي تتعامل معاه. يعني، الديكوريتور بيزود الكلاس بمعلومات تخليه (Component)، أو (Directive)، أو (Service)... وهكذا.

### طيب بنستخدم الـ Decorators ليه في Angular؟

الAngular بتستخدم الـ Decorators عشان تضيف Metadata (معلومات إضافية) للكود اللي بنكتبه.

المعلومات دي بتساعد Angular تفهم إزاي تتعامل مع الكلاس أو الميثودات اللي جواه.

مثلا، لو عندك كلاس وعايز تخليه Component، بنستخدم ديكوريتور اسمه Component@، ولو عايز تعمل Service بنستخدم Injectable@ وهكذا.

### أنواع الديكوريتورز في Angular

الAngular عندها كذا نوع من الـ Decorators، وهنقسمهم لأربع أنواع رئيسية:

#### الClass Decorators: بتستخدم على الكلاسات (classes).

#### الProperty Decorators: بتستخدم على (properties).

#### الMethod Decorators: بتستخدم على (methods).

#### الParameter Decorators: بتستخدم على الباراميترز (parameters) بتاعة الـ Constructor.

### Class Decorators

#### @NgModule

#### @Component

#### @Injectable

#### @Directive

#### @Pipe

ديكوريتورز بتشتغل على الكلاسات، زي Component@ وDirective@ وInjectable@، ودي بتخلي Angular تتعامل مع الكلاس ده بطريقة معينة.

##### Component@

بنستخدمه عشان نقول لـ Angular إن الكلاس ده عبارة عن Component، وده بيخلي Angular تتعامل مع الكلاس ده ك component ممكن يتعرض في التيمبلت.

<div dir="auto" align="left">

```typescript
@Component({
  selector: "app-root",
  templateUrl: "./app.component.html",
})
export class AppComponent {}
```

</div>

##### Injectable@

ديكوريتور بيستخدم عشان نقول لـ Angular إن الكلاس ده محتاج يتعامل كـ Service. ده بيخلي Angular تعرف توفر الكلاس ده لما نحتاجه في component تاني عن طريق الـ Dependency Injection.

<div dir="auto" align="left">

```typescript
@Injectable({
  providedIn: "root",
})
export class MyService {}
```

</div>

### Property decorators

#### @Input

#### @Output

#### @HostBinding

#### @ContentChild

#### @ContentChildren

#### @ViewChild

#### @ViewChildren

<div dir="auto" align="left">

```typescript
export class ChildComponent {
  @Input() childProperty: string;
}
```

</div>

### Method decorators

#### @HostListener

<div dir="auto" align="left">

```typescript
@HostListener('click') onClick() {
  console.log(' cliked');
}
```

</div>

### Parameter decorators

#### @Inject

#### @Self

#### @SkipSelf

#### @Optional

#### @Host

<div dir="auto" align="left">

```typescript
constructor(@Inject(SomeToken) private myValue) {

}
```

</div>
</div>

## AfterViewInit, AfterViewChecked, AfterContentInit and AfterContentChecked in Angular

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### إيه الفرق بين Content و View في Angular؟

قبل ما نشرح الـ Hooks اللي بنستخدمهم، محتاجين نفهم حاجة مهمة، وهي الفرق بين Content و View:

الContent: ده المحتوى اللي بيوصل للكومبوننت كـ Projected Content، يعني محتوى بيجيله من الكومبوننت الأب عن طريق `<ng-content>`.

الView: دي التيمبلت (Template) أو UI بتاع الكومبوننت نفسه، اللي بنكتبه جواه.

### الAngular بيستخدم 4 Lifecycle Hooks للتعامل مع الـ Content والـ View:

فيه أربع Hooks مهمين في Angular بيساعدونا نتحكم في التوقيت اللي بنشتغل فيه مع المحتوى اللي جاي من بره (اللي هو الـ Content) والعرض بتاع الكومبوننت (اللي هو الـ View).

#### 1. AfterContentInit

ده Hook بيشتغل أول ما يتعمل تحميل كامل للمحتوى (Content) اللي جاي من الأب.

الAngular كمان بيحدّث الخصائص اللي بنزودها بديكوريتور ContentChild@ أو ContentChildren@ قبل ما تنادي Hook دي.

بتشتغل مرة واحدة بس.

#### 2. AfterContentChecked

ده Hook بيشتغل كل مرة يحصل Change Detection في التطبيق.

يعني إيه؟ يعني كل مرة Angular بتفحص إذا فيه تغيير حصل، بتشغل الـ Hook ده وتتأكد من أي تغييرات حصلت في المحتوى.

بـالمختصر، ده بيشوف إذا حصل أي تعديل على المحتوى وبيشتغل كل مرة Angular تعمل عملية فحص للتغييرات (حتى لو بسيط زي الضغط على زرار).

#### 3. AfterViewInit

ده Hook بيشتغل بعد ما ينتهي تحميل الـ View الخاص بالكومبوننت وأي Child Components جواه.

الAngular بيحدّث الخصائص اللي بنزودها بديكوريتور ViewChild@ أو ViewChildren@ قبل ما تنادي Hook دي.

بتشتغل مرة واحدة بس.

#### 4. AfterViewChecked

ده Hook بيشتغل كل مرة يحصل Change Detection ويتأكد من أي تغييرات في (View).

يعني بعد ما Angular تخلص فحص التغييرات، هتشغل الـ Hook ده عشان تشوف إذا اتعدل ولا لأ.

بـالمختصر، ده زيه زي AfterContentChecked لكن بيركز على العرض بدل المحتوى، وبيشتغل في كل عملية فحص تغييرات.

#### ❌ ليه ماينفعش نعدل Bindings في الـ Checked Hooks زي ngAfterViewChecked؟

في Angular، الـ Checked Hooks زي ngAfterViewChecked بتشتغل بعد كل دورة فحص تغييرات (Change Detection Cycle). يعني، كل مرة Angular تشوف إذا فيه حاجة اتغيرت في الكومبوننت أو في الـ View، بيتم استدعاء الـ Hook دي.

المشكلة في تعديل الـ Bindings في الـ Checked Hooks
لما تعمل تعديل على Binding (زي تعديل قيمة متغيرة بتظهر في التيمبلت) في ngAfterViewChecked، ده بيعمل مشكلة لإن Angular هتضطر تدخل في دورة فحص جديدة عشان تتأكد من التغييرات، وهكذا تفضل في حلقة مفرغة (Infinite Loop) من دورات الفحص.

###### 🔴 المشكلة الكبيرة هنا إنك ممكن تواجه خطأ اسمه: ExpressionChangedAfterItHasBeenCheckedError

الخطأ ده معناه إن فيه قيمة اتغيرت بعد ما Angular انتهت من الفحص، وده بيعمل تعارض في الـ Change Detection.

### ✅ الحل

لو عايز تقرأ قيمة viewChild.message وتعرضها في التيمبلت من غير مشاكل، اعمل التعديل في Hook زي ngAfterViewInit أو في أماكن تانية مش بتتكرر زي ngOnInit.

### Init Vs Checked Hooks

الInit Hooks (AfterContentInit وAfterViewInit): بتشتغل مرة واحدة بس بعد ما ينتهي تحميل المحتوى أو العرض لأول مرة.

الChecked Hooks (AfterContentChecked وAfterViewChecked): بتشتغل في كل دورة Change Detection.

#### 🔴 لما بقول إن الـ Hook "بتشتغل مرة واحدة بس"، أقصد إن الـ Hook دي بتشتغل أول ما يحصل تحميل للكومبوننت بس ومش بتكرر تاني.

### ليه بتشتغل مرة واحدة بس؟

الفكرة إن الـ Hooks دي متخصصة إنك تستخدمها لإعدادات مبدئية. مثلا لو عايز تعمل حاجة في الكومبوننت بعد ما يخلص تحميله مباشرةً، بس مش محتاج تعملها كل مرة يحصل فيها تغيير في التطبيق. عشان كده Angular بتشغل الـ Hooks دي مرة واحدة بس بعد أول تحميل للكومبوننت أو المحتوى.

### طيب إيه اللي بيشتغل أكتر من مرة؟

في المقابل، فيه Hooks زي AfterContentChecked و AfterViewChecked. دول بيشتغلوا كل مرة يحصل فيها Change Detection في التطبيق.

</div>

## What is View Encapsulation in Angular?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### يعني إيه View Encapsulation؟

الـ View Encapsulation في Angular بيساعدنا نتحكم في الاستايلات الخاصة بكل كومبوننت بحيث تكون معزولة وماتأثرش على باقي الكومبوننتات في التطبيق.

يعني لو عندك استايلات معينة في كومبوننت واحد، مش عايزينها تأثر على استايلات الكومبوننتات التانية.

### الAngular بيدعم 3 طرق أو استراتيجيات للتحكم في الاستايلات:

###### الViewEncapsulation.None: بدون عزل للاستايلات (يعني الاستايلات تكون global).

###### الViewEncapsulation.Emulated: عزل وهمي (Emulated Encapsulation).

###### الViewEncapsulation.ShadowDOM: عزل حقيقي باستخدام الـ Shadow DOM.

### ViewEncapsulation.None

يعني إيه ViewEncapsulation.None؟

لو استخدمت ViewEncapsulation.None، يبقى كده مفيش عزل. الاستايلات اللي بتعملها في الكومبوننت ده هتكون (Global)، يعني ممكن تأثر على كل العناصر في التطبيق.

<div dir="auto" align="left">

```typescript
import { Component, ViewEncapsulation } from "@angular/core";

@Component({
  selector: "app-none",
  template: `<p>I am not encapsulated and in blue (ViewEncapsulation.None)</p>`,
  styles: ["p { color:blue}"],
  encapsulation: ViewEncapsulation.None,
})
export class ViewNoneComponent {}
```

</div>

#### لو أضفنا الكومبوننت ده في التطبيق، الاستايل color: blue هيأثر على كل `<p>` في التطبيق، مش بس جوا الكومبوننت ده.

### 2. ViewEncapsulation.Emulated

يعني إيه ViewEncapsulation.Emulated؟

دي تعتبر الاستراتيجية الافتراضية في . Emulated Encapsulation يعني الAngular هتضيف حاجة زي أكواد HTML Attributes فريدة للكومبوننت والاستايلات الخاصة به، بحيث تضمن إن الاستايلات دي ماتأثرش على باقي الكومبوننتات.

يعني Angular بتضيف حاجات زي \_ngcontent لكل عنصر جوا الكومبوننت عشان تربط الاستايلات الخاصة بيه بيه بس، بحيث تضمن إن الاستايلات ماتخرجش لباقي التطبيق.

<div dir="auto" align="left">

```typescript
import { Component, ViewEncapsulation } from "@angular/core";

@Component({
  selector: "app-emulated",
  template: `<p>Using Emulator</p>`,
  styles: ["p { color:red}"],
  encapsulation: ViewEncapsulation.Emulated,
})
export class ViewEmulatedComponent {}
```

</div>

### إيه اللي بيحصل هنا؟

لما تفتح (Developer Tools)، هتلاقي Angular ضافت Attribute فريد زي `_ngcontent-c2` على عنصر `<p>` والاستايلات الخاصة به. ده بيخلي الاستايلات دي تنطبق بس على العناصر اللي جوا الكومبوننت ده، وماتأثرش على باقي التطبيق.

### ViewEncapsulation.ShadowDOM

يعني إيه ViewEncapsulation.ShadowDOM؟

الـ Shadow DOM هو جزء من Web Components وبيوفر عزل حقيقي للاستايلات.

لما تستخدمه، الاستايلات الخاصة بالكومبوننت ده مش هتخرج بره الكومبوننت، ومش هتأثر على أي عناصر تانية بره الكومبوننت.

ملاحظة: مش كل المتصفحات بتدعم الـ Shadow DOM، فالأفضل تشغل التطبيق على متصفح زي جوجل كروم.

<div dir="auto" align="left">

```typescript
import { Component, ViewEncapsulation } from "@angular/core";

@Component({
  selector: "app-shadowdom",
  template: `<p>
    I am encapsulated inside a Shadow DOM ViewEncapsulation.ShadowDom
  </p>`,
  styles: ["p { color:brown}"],
  encapsulation: ViewEncapsulation.ShadowDom,
})
export class ViewShadowdomComponent {}
```

</div>

### إيه اللي بيحصل هنا؟

الAngular بترندر الكومبوننت ده جوا عنصر اسمه shadow-root#.

العنصر ده بيعزل الاستايلات الخاصة بالكومبوننت عن باقي التطبيق، وده بيحقق عزل حقيقي.

### مزايا وعيوب Shadow DOM

مزايا: عزل حقيقي للاستايلات، وبكده تضمن إن الاستايلات ماتأثرش على أي حاجة بره الكومبوننت.

عيوب: مش كل المتصفحات بتدعمه، وبعض الاستايلات المشتركة بين الكومبوننتات ممكن ماتشتغلش زي ما تتوقع.

### 🚀 الخلاصة

الViewEncapsulation.None: استخدامه لما تكون عايز الاستايلات تأثر على التطبيق كله.

الViewEncapsulation.Emulated: الاختيار الافتراضي، بيعزل الاستايلات باستخدام ng-content.

الViewEncapsulation.ShadowDOM: بيعزل الاستايلات بشكل كامل لكن ممكن مايشتغلش على كل المتصفحات.

</div>

## What are Host and hostContext in angular?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

### أولاً: إيه هو host:؟

الhost هو CSS Selector بنستخدمه في Angular عشان نستهدف العنصر الأساسي بتاع الكومبوننت نفسه.

لما بتستخدمه، هو بيخليك تضيف استايلات على العنصر الرئيسي للكومبوننت من غير ما تتعرض للعناصر اللي جواه أو من غير ما تضطر تضيف كلاس معين عليه.

### ليه بنستخدم :host في Angular

كل كومبوننت بيبقى ليه استايلات خاصة بيه، ولو عايز تضيف استايل للعنصر الأساسي بتاع الكومبوننت من غير ما تأثر على باقي الكومبوننتات أو محتوى الصفحة، هنا :host بيبقى مفيد.

### مثال عملي:

خلينا نقول عندك كومبوننت اسمه app-card وعايز تخلي العنصر الأساسي يظهر بحدود (border) ولون خلفية (background color) محددين.

<div dir="auto" align="left">

```typescript
@Component({
  selector: "app-card",
  template: `
    <div class="content">
      <p>this is a content</p>
    </div>
  `,
  styles: [
    `
      :host {
        display: block;
        border: 2px solid #333;
        background-color: #f9f9f9;
        padding: 16px;
        border-radius: 8px;
      }
    `,
  ],
})
export class CardComponent {}
```

</div>

الـ :host هنا بيخلي الاستايلات تطبق على العنصر الأساسي بتاع app-card نفسه.

مش محتاج تضيف كلاس أو تعمل حاجة مخصوص للعنصر الرئيسي، لأن :host بيفهم لوحده إن ده هو العنصر الحاوي للكومبوننت، وبيطبق عليه الاستايلات مباشرة.

### ثانياً: إيه هو :host-context؟

الhost-context هو CSS Selector بيستخدم في Angular عشان تتحكم في الاستايلات بناءً على السياق الخارجي للكومبوننت. يعني بيشوف الكومبوننت موجود فين أو جواه إيه، ويطبق الاستايلات بناءً على ده.

تخيل :host-context زي شرط بيقول: "لو الكومبوننت موجود في سياق معين أو محاط بعنصر معين، يبقى طبق الاستايل ده".

### مثال

افترض إن عندك كومبوننت في Angular فيه عنصر `<input>`، وعايز هذا الكومبوننت يظهر بشكل مختلف بناءً على المكان اللي بيتواجد فيه. يعني مثلًا:

لو الكومبوننت ده موجود جوا Dropdown، عايز عرض الـ `<input>` يكون 50%.

لو الكومبوننت ده موجود جوا Table، عايز عرض الـ `<input>` يكون 100%.

### إزاي نستخدم :host-context في المثال بتاعنا؟

لو عندنا كومبوننت MyInputComponent اللي فيه `<input>`، عايزين نخليه يغير عرضه بناءً على المكان اللي هو فيه.

الكومبوننت MyInputComponent هيظهر في أماكن مختلفة، زي my-dropdown و my-table.

لو الكومبوننت ده جوه `<my-dropdown>`، العرض يكون 50%.
لو الكومبوننت ده جوه `<my-table>`، العرض يكون 100%.

<div dir="auto" align="left">

```CSS
:host-context(my-dropdown) input {
  width: 50%; /* العرض لما يكون جوا dropdown */
}

:host-context(my-table) input {
  width: 100%; /* العرض لما يكون جوا table */
}
```

</div>

ال:host-context(my-dropdown) input: ده بيقول إنه لو الكومبوننت MyInputComponent موجود جوا عنصر `<my-dropdown>`، يخلي عرض `<input>` في الكومبوننت ده 50%.

ال:host-context(my-table) input: ده بيقول إنه لو الكومبوننت MyInputComponent موجود جوا `<my-table>`، يخلي عرض `<input>` في الكومبوننت ده 100%.

دلوقتي لو حطيت MyInputComponent جوا <my-dropdown> أو <my-table>، هيتم تطبيق الاستايل اللي يناسب السياق بشكل تلقائي.

<div dir="auto" align="left">

```HTML
<my-dropdown>
  <my-input></my-input> <!-- العرض 50% هنا عشان موجود في dropdown -->
</my-dropdown>

<my-table>
  <my-input></my-input> <!-- العرض 100% هنا عشان موجود في table -->
</my-table>
```

</div>

### ليه host-context مفيد في الحالة دي؟

بدل ما تكتب كود إضافي في كل مكان أو تضيف كلاس جديد للتحكم في الاستايل، host-context بيسهل عليك التحكم في استايلات الكومبوننت بناءً على السياق الخارجي اللي الكومبوننت موجود فيه، من غير ما تعدل على الكومبوننت نفسه كل مرة.

</div>

## Angular Change Detection How Does It Really Work?

[⬆️ Back to Top](#top)

<div dir="auto" align="right">
في أنجولار، عندنا حاجة اسمها "Change Detection" ، اللي بتخلي أنجولار يقدر يعرف لو في أي بيانات اتغيرت في الكمبوننت، ويعيد تحديث UI أوتوماتيك عشان يظهر التغيير ده.

السؤال هنا، إزاي بيعمل كده بعد أحداث زي ضغطة زر، اللي ممكن تحصل في أي حتة في الصفحة؟

### change detection mechanism work

اللي بيحصل هو إن أنجولار بيبص على كل متغير مستخدم في الـHTML (الـTemplate)، زي لما تكتب `{{ user.name }}` أو تحط حاجة زي `[value]="counter"`، وبيقارن القيمة الحالية للمتغير ده بالقيمة اللي كانت موجودة قبل كده.

### الخطوات

1- أنجولار بيمر على كل متغير جوه الـTemplate عشان يشوف إذا حصل فيه تغيير ولا لأ.

2- بيقارن القيمة الجديدة بالقيمة القديمة. لو لقى إنهم مختلفين، بيقول "أيوة، حصل تغيير"، وبيخلي متغير داخلي اسمه isChanged يبقى true.

3- أنجولار بيستخدم دالة اسمها looseNotIdentical، ودي بتقارن بين القيم بطريقة مشابهة للمقارنة ===، لكنها بتتجنب مشاكل معينة زي NaN (عشان لو عندك NaN، جافاسكريبت بتتعامل معاه بشكل مختلف شوية).

4- لو isChanged بقت true، أنجولار بيروح يعمل تحديث للجزء ده في الواجهة عشان يظهر التغييرات.

![Angular component tree and its change detector (CD)](https://mokkapps.twic.pics/mokkapps.de/blog/the-last-guide-for-angular-change-detection-you-will-ever-need/cd-cycle_wfdcsk.gif)

الصورة بتوضح شجرة الكومبوننتات (Component Tree) في Angular، ولكل كومبوننت فيه (Change Detector) خاص بيه بيتعمل أثناء عملية تشغيل التطبيق لأول مرة

والchange detector بيعمل نفس الخطوات السابقة

### ننتقل لنقطة تانية وهي Zone.js

#### يعني إيه Zone.js؟

الZone.js هو مكتبة في Angular بتعمل حاجة زي "مراقبة" للعمليات غير المتزامنة، زي لما تعمل استدعاء API أو تعدادات زمنية (timers) زي setTimeout أو setInterval.

المكتبة دي بتسمح لـ Angular إنه "يتصنت" على العمليات دي، وده بيساعده إنه يقدر يكتشف التغييرات اللي بتحصل في البيانات بتاعت التطبيق لما أي من العمليات دي تتنفذ.

#### إيه فايدة المراحل في Zone.js؟

الـ Zone بتعدي بمراحل معينة علشان Angular يقدر يتحكم في متى يشغل آلية اكتشاف التغييرات:

1- المرحلة المستقرة (Stable): التطبيق بيكون شغال عادي من غير أي عمليات غير متزامنة شغالة، يعني التطبيق هادي.

2- المرحلة غير المستقرة (Unstable): لو حصلت عملية غير متزامنة (زي طلب HTTP أو حدث كليك على زر)، الـ Zone بتتحول لغير مستقرة، وبتبدأ تراقب العمليات دي لحد ما تخلص.

3- المرحلة المستقرة تاني: بعد ما تخلص العمليات دي، الـ Zone بترجع مستقره، ووقتها Angular بيبدأ عملية change detection علشان يحدث واجهة المستخدم لو في أي تغيير حصل.

اللي بيحصل إن Angular عامل منطقة خاصة بيه اسمها NgZone، ودي بتمثل المكان اللي Angular بيقدر يشغل فيه change detection على العمليات غير المتزامنة اللي بتحصل فيه. يعني مثلاً:

لما يحصل حدث في المتصفح زي ضغطة زر (click) أو كتابة حرف (keyup).
لما يستعمل setTimeout أو setInterval.
لما تعمل طلب HTTP عن طريق XMLHttpRequest.
أي حاجة بتحصل في NgZone دي هتشغل change detection وتخلي Angular يحدث UI لو حصل أي تغيير في البيانات.

### Change Detection Strategies

Angular provides two strategies to run change detections

#### 🔴 Default

#### 🔴 OnPush

بشكل افتراضي، Angular بيستخدم ChangeDetectionStrategy.Default، واللي معناها إن كل مرة يحصل حدث ممكن يؤثر على البيانات، زي حدث من المستخدم، أو مؤقت (timer)، أو طلب HTTP (XHR)، أو promise وغيره، Angular بيمر على كل الكومبوننتات في شجرة الكومبوننتات من فوق لتحت.

العملية دي بيسموها الفحص المتكرر (dirty checking)، وده لأنه Angular بيتأكد من كل كومبوننت من غير ما يفترض إن فيه علاقات معينة أو اعتماد على عناصر تانية جواه.

![Angular component tree and its change detector (CD)](https://mokkapps.twic.pics/mokkapps.de/blog/the-last-guide-for-angular-change-detection-you-will-ever-need/cd-cycle_wfdcsk.gif)

الطريقة دي محافظة أكتر، لأنها بتفحص كل الكومبوننتات وتفترض إنها ممكن تكون اتغيرت، لكن ده ممكن يأثر سلبًا على أداء التطبيق، خصوصًا في التطبيقات الكبيرة اللي فيها عدد كبير من الكومبوننتات. فحص كل الكومبوننتات كل مرة بيكون بطيء وممكن يقلل سرعة التطبيق مع زيادة الحجم والتعقيد.

### استراتيجية OnPush لاكتشاف التغييرات في Angular

علشان نستخدم استراتيجية ChangeDetectionStrategy.OnPush، ممكن نضيف خاصية changeDetection في الديكوريتور بتاع الكومبوننت بالشكل ده:

<div dir="auto" align="left">

```typescript
@Component({
    selector: 'hero-card',
    changeDetection: ChangeDetectionStrategy.OnPush,
    template: `...`
})
export class HeroCard {
    ...
}
```

</div>

![Angular component tree and its change detector (CD)](https://mokkapps.twic.pics/mokkapps.de/blog/the-last-guide-for-angular-change-detection-you-will-ever-need/cd-on-push-cycle_te8dai.gif)

### إيه اللي بتعمله استراتيجية OnPush؟

استراتيجية OnPush بتديك ميزة كبيرة في تحسين الأداء، لأنها بتقلل الفحوصات اللي Angular بيعملها. لما نستخدم OnPush، Angular مش هيفحص الكومبوننت ده ولا أي كومبوننت فرعي جواه إلا في حالات معينة، زي:

<div dir="auto" align="left">

### Using this strategy, Angular knows that the component only needs to be updated if:

- the input reference has changed
- the component or one of its children triggers an event handler
- change detection is triggered manually
- an observable linked to the template via the async pipe emits a new value

### Input Reference Changes

</div>

لما تستخدم استراتيجية OnPush في Angular، فآلية changeDetection بتشتغل بس لما يتغير refrence.

### يعني إيه "تغيير الrefrence "؟

#### في جافاسكريبت، عندنا نوعين من البيانات

ال(Primitive types): زي الأرقام (numbers)، النصوص (strings)، القيم المنطقية (booleans)، null، وundefined. لما تعدل قيمتها، بيعتبر ده تغيير، وده معناه إن changeDetection هيشتغل تلقائيًا.

ال(Objects) و (Arrays): هنا الموضوع مختلف. لو عدلت خاصية جوا object أو عنصر جوا array الrefrence بتاعهم مبيختلفش، يعني Angular مش هيشغل changeDetection لأن refrence ثابت.

علشان االchangeDetection يشتغل، لازم تبعت object جديد أو array جديدة بreference جديد.

### مثال توضيحي

تخيل عندك كومبوننت بياخد بيانات كـ Input@ بالطريقة دي

<div dir="auto" align="left">

```typescript
@Component({
  selector: "example-component",
  changeDetection: ChangeDetectionStrategy.OnPush,
  template: `...`,
})
export class ExampleComponent {
  @Input() data: any;
}
```

</div>

🔴 السيناريو الأول:

لو البيانات كانت رقم (مثلاً data = 5) وعدلتها إلى data = 6، الAngular هيلاحظ التغيير لأن Primitive types بيتغير بالقيمة، وchangeDetection هيشتغل.

🔴 السيناريو الثاني

تعديل object أو array

<div dir="auto" align="left">

```typescript
this.data = { name: "John" };
```

</div>
لو عدلت الobject نفسه:
<div dir="auto" align="left">

```typescript
this.data.name = "Doe";
```

</div>
في الحالة دي، الrefrence ثابت، فـ Angular مش هيشغل Change Detection، ومش هيلاحظ التغيير، لأنه object نفسه لسه بنفس الrefrence.

### إزاي تخلي Angular يلاحظ التغيير؟

لو عايز الـ Change Detector يشتغل، لازم تعمل Object أو Array جديد بrefrence جديد، كده Angular هيقدر يشغل الـ Change Detector ويلاحظ التغيير.

<div dir="auto" align="left">

```typescript
this.data = { ...this.data, name: "Doe" };
```

</div>
 ✅في الحالة دي، Angular هيلاحظ التغيير لأنك عملت object جديد وrefrence جديد.

### Event Handler Is Triggered

خد بالك ان في بعض الحالات زي setTimeout وPromise واشتراكات RxJS، التغييرات بتحصل بشكل "خارج" عن نطاق الكشف التقليدي. وبالتالي، الـOnPush مش بيكتشف التغييرات دي تلقائيًا.

لما بنستخدم setTimeout أو setInterval في الـcomponent، الكود بينفذ بعد وقت معين، لكن ده بيحصل "خارج" نطاق Angular change detection.

يعني Angular مش عارف إن فيه تغيير حصل ومش هيعرف يظهره مباشرة على الشاشة لأن OnPush مش بيشوف التغييرات دي.

#### طيب إيه الحل عشان نخلي التغييرات تظهر؟

استخدام `ChangeDetectorRef.markForCheck` اللي بيقول لـAngular يشوف التغييرات حتى لو جت من حاجات زي setTimeout أو Promise

#### مثال

  <div dir="auto" align="left">

```typescript
import {
  Component,
  ChangeDetectionStrategy,
  ChangeDetectorRef,
} from "@angular/core";

@Component({
  selector: "app-hero-card-on-push",
  template: `
    <div>
      <p>Age: {{ age }}</p>
      <button (click)="changeAge()">Change Age with setTimeout</button>
    </div>
  `,
  changeDetection: ChangeDetectionStrategy.OnPush,
})
export class HeroCardOnPushComponent {
  age = 25;

  constructor(private cdr: ChangeDetectorRef) {}

  changeAge() {
    setTimeout(() => {
      this.age = 30; // غيرنا العمر هنا
      this.cdr.markForCheck(); // بنستخدم markForCheck عشان نقول لـAngular يشوف التغيير
    }, 1000);
  }
}
```

</div>

بعد ما نغير age، بنستخدم `this.cdr.markForCheck` عشان نطلب من Angular إنه يعمل كشف عن التغييرات ويحدث الشاشة. بدون `markForCheck`، التغيير في age مش هيظهر لأننا بنستخدم OnPush.

#### ليه نستخدم markForCheck؟

الmarkForCheck بيقول لـAngular إن فيه تغيير حصل وبيحتاج يتشاف حتى لو كان جاي من setTimeout أو Promise أو حاجة تانية خارج نطاق الكشف التقليدي للتغييرات.

### Trigger Change Detection Manually

#### فهم طرق تشغيل الكشف عن التغييرات يدويًا في Angular

في Angular، فيه ٣ طرق أساسية ممكن تستخدمها عشان تشغل الكشف عن التغييرات يدويًا، وده مفيد لما تكون محتاج تحديث الـcomponent أو التطبيق في حالات خاصة، زي ما بيحصل في setTimeout أو Promise، اللي ما بيشغلوش الكشف عن التغييرات بشكل تلقائي

##### 🔴 ١- detectChanges

إيه اللي بيعمله؟
الdetectChanges بتشغل الكشف عن التغييرات للـcomponent الحالي وأي مكونات فرعية ليه.

فين ممكن تستخدمه؟
لما عايز تحدث الـcomponent الحالي فقط بعد ما يحصل تغيير معين من غير ما تعمل تحديث لكل التطبيق.

مثال عملي:

لو عندك component فيه قيمة age بتتغير بعد فترة باستخدام setTimeout، وعايز تشغل الكشف عن التغييرات يدويًا عشان تظهر القيمة الجديدة

<div dir="auto" align="left">

```typescript
import { ChangeDetectorRef } from '@angular/core';

constructor(private cdr: ChangeDetectorRef) {}

changeAge() {
  setTimeout(() => {
    this.age = 30;
    this.cdr.detectChanges();
  }, 1000);
}
```

</div>

##### 🔴 ٢. ApplicationRef.tick

إيه اللي بيعمله؟

الApplicationRef.tick بتشغل الكشف عن التغييرات على مستوى التطبيق بالكامل، يعني بتشيك على كل الـcomponents، وده بيكون تأثيره أوسع من detectChanges.

فين ممكن تستخدمه؟
لو حصل تغيير في جزء معين من التطبيق وعايز تشغل الكشف عن التغييرات في كل components بس نادرًا بنحتاجها لأن تأثيرها على الأداء كبير

##### 🔴 ٣. markForCheck

إيه اللي بيعمله؟

الmarkForCheck ما بيشغّلش الكشف عن التغييرات مباشرةً، لكنه بيوصّل للـOnPush components إنهم يتفحصوا في أقرب دورة كشف تغييرات.

فين ممكن تستخدمه؟
لو فيه تغييرات بتحصل خارج نطاق الكشف عن التغييرات، وعايز تأكد إن component هيعمل فحص ليها في الدورة الجاية.

![Angular component tree and its change detector (CD)](https://mokkapps.twic.pics/mokkapps.de/blog/the-last-guide-for-angular-change-detection-you-will-ever-need/change-detector-ref_j3gyml.jpg)

#### ✅ خلاصة استخدام كل طريقة:

##### الdetectChanges: لما تحتاج تحديث للـcomponent الحالي وcomponents الفرعية فقط.

##### الApplicationRef.tick: لو عايز تحديث لكل التطبيق مرة واحدة (بيستخدم في حالات نادرة).

##### الmarkForCheck: لما تحتاج تضمن تحديث الـcomponent في الدورة القادمة بدون ما تشغّل الكشف عن التغييرات في الحال.

### Async Pipe

الAsync Pipe هو Pipe جاهز في Angular بيقوم بالاشتراك في الـObservable أو Promise تلقائيًا، وبيرجع آخر قيمة تم إصدارها منه.

ده بيخليك تستفيد من التحديثات اللي بتحصل في البيانات بدون ما تحتاج تتعامل مع الاشتراكات subscribe بنفسك، وده بيسهل عليك كتابة كود أنظف وأكثر ترتيبًا

#### كيف يعمل Async Pipe داخليًا؟

الAsync Pipe بيستخدم markForCheck عشان يضمن إن التحديثات تظهر حتى لو الـcomponent بيستخدم استراتيجية OnPush.

في كل مرة الـObservable أو الـPromise يرجع قيمة جديدة، Async Pipe بيستخدم markForCheck عشان يخلي Angular يشوف التغييرات دي ويحدث الـcomponent

#### لماذا يفضل استخدام Async Pipe؟

التوافق مع الOnPush: متوافق تلقائيًا مع استراتيجية OnPush، مما يجعله مناسب جدًا لو انتقلنا لاستخدام OnPush في التطبيق.

إدارة الذاكرة: Async Pipe بيلغي الاشتراك تلقائيًا في الـObservable أو الـPromise لما يتم تدمير الـcomponent، وبالتالي بيقلل من مخاطر التسريبات (Memory Leaks).

بساطة الكود: Async Pipe بيقلل من الحاجة لكتابة كود معقد لعملية الاشتراك والإلغاء، مما يجعل الكود أنظف وأقل عرضة للأخطاء.

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";
import { Observable, of } from "rxjs";

@Component({
  selector: "app-user",
  templateUrl: "./user.component.html",
  changeDetection: ChangeDetectionStrategy.OnPush,
})
export class UserComponent {
  user$: Observable<{ name: string }> = of({ name: "John Doe" });
}
```

</div>
<div dir="auto" align="left">

```HTML
<div *ngIf="user$ | async as user">
  <p>{{ user.name }}</p>
</div>

```

</div>
</div>

## A Change Detection and Zone.js and Zoneless and Local Change Detection and Signals Story

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

الAngular هو إطار عمل بيشتغل بطريقة الـ component-driven، يعني كل حاجة في التطبيق مبنية على مكونات (components). وزي أي إطار عمل تاني، فكرته الأساسية إنه يعرض الداتا للمستخدم ويعمل تحديث للواجهة (view) لما الداتا تتغير.

فكرة كشف التغييرات (change detection) ببساطة هي عملية متابعة التغييرات اللي بتحصل في الداتا، ولما يحصل تغيير، يبتدي يعرضه للمستخدم في الواجهة. يعني لو مثلا عندك اسم بيظهر على الشاشة والمستخدم غيره، Angular بيعمل تحديث تلقائي للعرض عشان يظهر الاسم الجديد.

زمان، Angular كانت بتستخدم حاجة اسمها Zone.js عشان تتتبع التغييرات دي. Zone.js كان مسؤول عن متابعة كل الأحداث اللي بتحصل في التطبيق، زيcilke و (server responses)، ولما يحصل تغيير، بيبدأ عملية كشف التغييرات عشان يحدّث الواجهة.

دلوقتي، في توجه جديد اسمه زونليس (zoneless)، وده يعني إننا بنحاول نبعد عن استخدام Zone.js عشان نخلي الأداء أسرع ونقلل التعقيدات. الفكرة هنا إنك تتابع التغييرات بشكل محلي في كل component لوحده، وده اللي بيسموه الكشف المحلي للتغييرات (local change detection). يعني كل component يتابع الداتا بتاعته بس، من غير ما يدخل Zone.js في كل عملية.

وفي مفهوم جديد ظهر اسمه (signals)، وده عبارة عن طريقة ذكية عشان تعرف Angular إن في حاجة اتغيرت، من غير ما تتابع كل التفاصيل الصغيرة. يعني بدل ما التطبيق كله يبقى بيراقب الداتا طول الوقت، signals هتدي إشارة لما يحصل تغيير، وده يخلي الأداء أحسن والتحميل أسرع.

![A UserCard component that shows user data in the template](https://justangular.com/cd-article/user-card-change.webp)

A UserCard component that shows user data in the template

![Component structure](https://justangular.com/cd-article/component-structure.webp)

### مع الوقت، وإحنا بنبني components أكتر في التطبيق، بنبدأ نركبهم مع بعض ونعمل شجرة من (component tree) زي اللي موضحة في الرسم اللي فوق.

### طيب، إزاي Angular بتعرف إمتى تحدث الUI؟

إزاي بتعرف إن في داتا اتغيرت؟ وإزاي بتعرف إنها محتاجة تشغل كشف التغييرات (change detection)؟

### 🔴 Change detection with synchronous code

خلينا نبدأ بمثال بسيط. عندنا (component) فيه خاصية اسمها `name` ودالة اسمها `changeName`. لما ندوس على الزرار، بنادي دالة `changeName` اللي بتغير قيمة `name`

<div dir="auto" align="left">

```typescript
@Component({
  template: `
    <button (click)="changeName()">Change name</button>
    <p>{{ name }}</p>
  `,
})
export class AppComponent {
  name = "John";

  changeName() {
    this.name = "Jane";
  }
}
```

</div>

لما بندوس على الزرار، changeName بتشتغل وبتغير القيمة بتاعت name من "John" لـ "Jane". لأن Angular بتحاوط كل حاجة بآلية كشف التغييرات، فإحنا نقدر نفترض بأمان إنه بعد تغيير الاسم، Angular هتشغل كود عشان تحدث العرض وتخلي كل حاجة متزامنة (in sync).

مثال للكود اللي Angular ممكن تشغله وراء الكواليس:

تخيل إن Angular شغلت كود زي ده ورا الكواليس:

<div dir="auto" align="left">

```typescript
component.changeName();
angular.runChangeDetection();
```

</div>

ده شغال تمام في الحالة البسيطة دي، عشان كل التغييرات بتحصل في نفس اللحظة (synchronously)، وده بيخلي Angular تشغل كشف التغييرات بدون مشاكل.

لكن في أغلب الوقت، لما بنغير الداتا، الموضوع مش بيحصل بشكل متزامن. غالباً بنبعت طلب HTTP، أو بنعتمد على مؤقتات (timers)، أو بنستنى أحداث تانية تحصل قبل ما نحدث الداتا. وده هنا اللي بيسبب المشاكل!

### فين المشكلة؟

لما يكون التغيير مرتبط بأحداث غير متزامنة (async)، Angular مش هتقدر تعرف لوحدها إن في حاجة اتغيرت. عشان كده بتعتمد على Zone.js (لو مش شغالين بزونليس)، اللي بيراقب الأحداث زي طلبات HTTP أو مؤقتات، وبيخبر Angular لما يحصل تغيير في الداتا، عشان تشغل كشف التغييرات وتحدث العرض.

لكن استخدام الأحداث غير المتزامنة مع Angular بيخلي الأمور معقدة أكتر وبيحتاج انتباه، عشان نتأكد إن Angular دايماً في حالة تحديث (in sync) مع التغييرات.

### 🔴 Change detection with asynchronous code

في المثال ده، إحنا عاوزين نغير قيمة `name` بعد ثانية واحدة، وهنعمل ده باستخدام `setTimeout`.

<div dir="auto" align="left">

```typescript
@Component({
  template: `
    <button (click)="changeName()">Change name</button>
    <p>{{ name }}</p>
  `,
})
export class AppComponent {
  name = "John";

  changeName() {
    setTimeout(() => {
      this.name = "Jane";
    }, 1000);
  }
}
```

</div>

لما ندوس على الزرار، `changeName` بتتنادي وsetTimeout بيشتغل. `setTimeout` هتستنى ثانية، وبعدها هتنفذ اللي جواها عشان تغير قيمة `name` لـ "Jane".

خلينا نضيف نفس الكود اللي تخيلنا إنه شغال ورا الكواليس في Angular:

<div dir="auto" align="left">

```typescript
component.changeName();

angular.runChangeDetection();
```

</div>

### إيه المشكلة هنا؟

بسبب ترتيب الكود في stack، الـ callback بتاع setTimeout مش هيتنفذ غير بعد ما Angular تكون شغلت runChangeDetection. فبالتالي، Angular هتشغل كشف التغييرات، لكن name لسه ما اتغيرتش، وده هيخلي (view) ما يتحدثش، عشان كده مش هنشوف اسم "Jane" على الشاشة بعد ما نضغط الزرار. وده بيسبب مشكلة في التطبيق ⚠️.

### لكن في الواقع، Angular بتحل المشكلة

لو فاكرين، Angular بتستخدم Zone.js، اللي بيراقب كل الأحداث غير المتزامنة زي setTimeout. فلما setTimeout ينفذ بعد ثانية ويغير name، Zone.js هيلاحظ التغيير ويخطر Angular إنها تشغل runChangeDetection مرة تانية. وده هيخلي (view) يتحدث ويظهر القيمة الجديدة "Jane".

### 🔴 Zone.js to the rescue

#### إيه هي Zone.js وإزاي بتشتغل؟

الZone.js موجودة من أيام Angular 2.0، وهي مكتبة بتعمل حاجة اسمها "monkey patching" لمجموعة من واجهات المتصفح (browser APIs) وتسمح لنا ندخل في دورة حياة (lifecycle) الأحداث اللي بتحصل في المتصفح. طيب إيه معنى الكلام ده؟ ببساطة، ده معناه إننا نقدر نشغل كود معين قبل أو بعد أحداث معينة بتحصل في المتصفح.

خلينا نشوف مثال بسيط:

<div dir="auto" align="left">

```typescript
setTimeout(() => {
  console.log("Hello world");
}, 1000);
```

</div>
الكود ده هيطبع "Hello world" بعد ثانية. طيب، لو إحنا عاوزين نشغل كود معين قبل أو بعد ما setTimeout ينفذ، لأي أسباب تتعلق بالشغل مثلًا 😄؟ ده بيكون مهم لإطار عمل زي Angular، اللي ممكن يكون عاوز يشغل كود معين قبل أو بعد ما setTimeout ينفذ، عشان يتأكد إن كل التغييرات متزامنة مع كشف التغييرات (change detection).

هنا بتيجي Zone.js بدورها. بتسمح لنا نعمل "zone" (ودي حاجة Angular نفسها بتستخدمها) ونتدخل في دورة حياة الـ setTimeout.

مثال مع Zone.js
هنعمل زون جديدة ونضيف عمليات قبل وبعد تنفيذ setTimeout

<div dir="auto" align="left">

```typescript
const zone = Zone.current.fork({
  onInvokeTask: (delegate, current, target, task, applyThis, applyArgs) => {
    console.log("Before setTimeout"); // الكود ده هيشتغل قبل `setTimeout`
    delegate.invokeTask(target, task, applyThis, applyArgs); // هنا بيشغل `setTimeout`
    console.log("After setTimeout"); // الكود ده هيشتغل بعد `setTimeout`
  },
});
```

</div>

عشان نشغل `setTimeout` داخل الزون، محتاجين نستخدم `zone.run` زي كده:

<div dir="auto" align="left">

```typescript
zone.run(() => {
  setTimeout(() => {
    console.log("Hello world");
  }, 1000);
});
```

</div>

الناتج
لما نشغل الكود ده، هنشوف التالي في الـ console

```
Before setTimeout
Hello world
After setTimeout

```

### ازاي Zone.js بتعمل ده؟

اللي Zone.js بتعمله هو إنها بتعدل في الطريقة اللي المتصفح بيشغل بيها الـ APIs زي setTimeout وsetInterval وغيرها. ده بيسمح ل Angular إنها "ترصد" التغييرات اللي بتحصل في الـ components وتحدث UI بشكل متزامن مع الأحداث، وده بيضمن إن كل حاجة في التطبيق شغالة بتناغم وكفاءة.

### 🔴 Zone.js + Angular

الZone.js و Angular: إزاي Angular بتستخدم NgZone في التطبيقات
الAngular بتشغل Zone.js تلقائيًا في كل تطبيق، وبتعمل حاجة اسمها NgZone، وده نوع من الـ zones المخصصة اللي بتراقب التطبيق. NgZone فيها حاجة اسمها onMicrotaskEmpty، ودي عبارة عن Observable، يعني زي عداد بيتابع الأحداث اللي بتحصل في التطبيق. الـ Observable ده بيبعث قيمة لما مفيش أي مهام صغيرة (microtasks) فاضلة في الطابور. وده اللي Angular بتستخدمه عشان تعرف إن كل الكود غير المتزامن (asynchronous code) خلص، وتقدر تشغل كشف التغييرات (change detection) بأمان.

![NgZone wraps every angular application today](https://justangular.com/cd-article/ngzone-1.webp)

NgZone wraps every angular application today

### 🔴 Component Dirty Marking in Angular

في Angular، لما يحصل تغيير جوه (component)، بتقوم بتمييز component كـ "متسخ" (dirty)، وده معناه إن component محتاج يتحدث عشان يظهر التغييرات الجديدة. فكرة "تمييز component كـ dirty" بتساعد Angular إنها تحدد إيه اللي محتاج يتحدث بدل ما تحدث كل حاجة في التطبيق.

#### إيه الحاجات اللي بتخلي Angular تميّز component كـ dirty؟

1. الأحداث (Events زي click، mouseover، إلخ)
   كل مرة بندوس على زرار أو بنعمل حدث معين في (template) عنده مستمع (listener)، Angular بيلف الدالة المستجيبة (callback function) بدالة تانية اسمها wrapListenerIn_markDirtyAndPreventDefault. زي ما الاسم بيوضح 😅، الدالة دي بتعلّم Component كـ dirty.

2. تغييرات (Changed Inputs)
   أثناء تشغيل كشف التغييرات، Angular بتشيك إذا كان فيه تغيير حصل في قيمة (input value) الخاصة بcomponent. لو Inputs اتغير، Angular بتميّز component كـ dirty. وده بيخلي component يعرف إنه محتاج يتحدث.

3. الـ Output Emissions
   عشان تستمع للـ outputs في Angular، بنسجل حدث في template. وزي ما شفنا قبل كده، الـ callback بتتلف بدالة تانية، ولما يتم استدعاء الحدث، component بيتعلّم كـ dirty.

### وظيفة markViewDirty

هي المسؤولة عن تمييز (view) الحالي وكل الأجداد (ancestors) كـ dirty.

### إزاي markViewDirty بتشتغل؟

دي بتعمل تمييز للview الحالي، وكمان لكل Components اللي فوقه (الأجداد) كـ dirty. وده معناه إن لما يحصل تغيير، Angular بتعرف إنها مش بس محتاجة تحدث Component ده، لكن كمان كل الأجزاء اللي بتعتمد عليه.

![Dirty marking component and its ancestor up to the root](https://justangular.com/cd-article/dirty-marking.webp)

Dirty marking component and its ancestor up to the root

### كيف يعمل تحديث البيانات في Angular عند الضغط على الزر؟

لما ندوس على الزر، Angular بتستدعي callback اللي هي هنا `changeName`. وبما إن دي ملفوفة داخل دالة `wrapListenerIn_markDirtyAndPreventDefault`، فده بيخلي Angular تميّز الـ component كـ dirty.

زي ما قولنا قبل كده، Angular بتستخدم Zone.js وبتحاوط التطبيق كله بيه.

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/cd-change.webp)

Dirty marking component and its ancestor up to the root

### الخطوات وراء الكواليس

التمييز كـ Dirty: لما `wrapListenerIn_markDirtyAndPreventDefault` تشتغل، بتقوم بتمييز الـ component وكل الأجداد كـ dirty، وبكده Angular بتعرف إن في حاجة اتغيرت في الـ component أو الـ components اللي فوقه.

تنبيه Zone.js: بعد تمييز الـ components، `wrapListenerIn_markDirtyAndPreventDefault` بتشغل Zone.js.

الonMicrotaskEmpty: بما إن Angular بتراقب الـ observable onMicrotaskEmpty، وأي حدث (زي click) بيسجل listener مع Zone.js، فالـ zone هيعرف إن الـ listener خلص شغله ويقدر يبعث قيمة لـ onMicrotaskEmpty.

إطلاق الـ onMicrotaskEmpty: لما onMicrotaskEmpty يشتغل، ده بيقول لـ Angular إن كل المهام الصغيرة (microtasks) خلصت، وبالتالي الوقت مناسب لتشغيل change detection.

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/zone-notifying.webp)

### تحديث الـ Component Binding

أول ما Angular تشغل change detection، بتبدأ تراجع كل الـ components من فوق لتحت. يعني بتمر على كل الـ components (سواء كانت marked كـ dirty أو لا) وبتشيك على كل الـ bindings. لو الـ binding اتغير، بيتم تحديث الـ view.

لكن ليه Angular بتشيك على كل الـ components 🤔؟ ليه ما تراجعش الـ components اللي marked كـ dirty بس؟ 🤔

الإجابة هنا ليها علاقة بـ استراتيجية change detection

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/cd-binding-refresh.webp)

### 🔴 OnPush Change Detection

في Angular، فيه استراتيجية اسمها OnPush لـ change detection. لما نستخدم الاستراتيجية دي، Angular هتشغل change detection فقط على الـ component اللي متعلم كـ dirty.

<div dir="auto" align="left">

```typescript
@Component({
  // ...
  changeDetection: ChangeDetectionStrategy.OnPush,
})
export class UserCard {}
```

</div>

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/cd-onpush.webp)

### إزاي change detection بيشتغل مع OnPush؟

دلوقتي خلينا نشوف الرسوم التوضيحية عشان نفهم أكتر إزاي change detection بيشتغل لما نستخدم استراتيجية OnPush.

بعض الـ components هتكون معلمة كـ OnPush (وأي children ليها هيبقوا تلقائيًا كمان OnPush).

خلينا نعمل نفس الخطوة اللي فاتت، ندوس على زرار في الـ component ونغير قيمة `name`.

1. مرحلة Dirty Marking

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/cd-on-push-click.webp)

2. إشعار Zone.js بالـ Event
   بعدها، الـ event listener هيشعر Zone.js بالحدث.

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/on-push-zone-notify.webp)

3. انتظار انتهاء الكود غير المتزامن
   لما كل الكود غير المتزامن يخلص، onMicrotaskEmpty هتشتغل.

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/on-push-microtask-empty.webp)

4. تشغيل tick في Angular
   بعد كده، Angular هتشغل tick وتبدأ تمر على كل الـ components من فوق لتحت وتشيك عليهم.

لو الـ component حالته كانت:

لوOnPush + Non-Dirty -> تتجاهله
لوOnPush + Dirty -> تشيك الـ bindings -> تحدث الـ bindings -> تشيك الـ children

![ Dirty marking component and its ancestor up to the root
](https://justangular.com/cd-article/onpush-refresh.webp)

الفائدة من OnPush
باستخدام OnPush، Angular تقدر تتخطى أجزاء من الشجرة اللي مفيهاش أي تغييرات، وده بيقلل من تكلفة التحديث ويحسن أداء التطبيق.

### 🔴 OnPush + Observables + async pipe

في الAngular، observables بقت الأداة الأساسية لإدارة البيانات وتحديث الحالة (state changes). ولأن Angular بتدعم observables، هي بتوفر async pipe اللي بيعمل اشتراك (subscription) في الـ observable ويرجع آخر قيمة.

عشان Angular تعرف إن القيمة اتغيرت، `async pipe` بيستخدم `markForCheck` اللي جاية من كلاس `ChangeDetectorRef`.

### ازاي بيشتغل async pipe مع OnPush؟

الكود التالي بيوضح الأساس اللي async pipe بيشتغل عليه:

<div dir="auto" align="left">

```typescript
@Pipe()
export class AsyncPipe implements OnDestroy, PipeTransform {
  constructor(ref: ChangeDetectorRef) {}

  transform<T>(obj: Observable<T>): T | null {}

  private _updateLatestValue(async: any, value: Object): void {
    // code removed for brevity
    this._ref!.markForCheck();
  }
}
```

</div>

الasync pipe بيتابع الـ observable، وأول ما يحصل تغيير في القيمة، بيشغل markForCheck. الطريقة دي هي اللي بتعلّم الـ component كـ dirty، وده بيخلّي Angular تعرف إنه محتاج تحديث.

### ليه ده مهم؟

باستخدام async pipe مع الobservables، Angular بتقدر تتأكد من إن الـ component بيتحدث تلقائيًا لما البيانات تتغير، بدون الحاجة لاستخدام .subscribe بشكل مباشر في الكود. وبما إن markForCheck بيشتغل مع OnPush، Angular بتعرف إنها محتاجة تشيك فقط على الـ components اللي اتعلمت كـ dirty، وده بيخلي التحديثات أكتر كفاءة وأقل تكلفة.

![ Dirty marking component and its ancestor up to the root](https://justangular.com/cd-article/onpush-async-pipe.webp)

### 🔴 OnPush + Observables + Who is triggering zone.js?

في حالة إن البيانات اتغيرت بدون أي event مباشر (زي click أو mouseover)، غالبًا بيكون فيه حاجة شغالة في الخلفية زي setTimeout أو setInterval أو استدعاء HTTP بيحفز Zone.js.

<div dir="auto" align="left">

```typescript
@Component({
  selector: "todos",
  standalone: true,
  imports: [AsyncPipe, JsonPipe],
  template: `{{ todos$ | async | json }}`,
  changeDetection: ChangeDetectionStrategy.OnPush,
})
export class TodosComponent {
  private http = inject(HttpClient);
  private ngZone = inject(NgZone);

  todos$ = of([] as any[]);

  ngOnInit() {
    this.ngZone.runOutsideAngular(() => {
      setTimeout(() => {
        // هنا البيانات هتتحدث، لكن مفيش حاجة هتشغّل Zone.js
        this.todos$ = this.getTodos();
      });
    });
  }

  getTodos() {
    return this.http
      .get<any>("https://jsonplaceholder.typicode.com/todos/1")
      .pipe(shareReplay(1));
  }
}
```

</div>

### إيه اللي بيحصل هنا؟

في `ngOnInit`، استخدمنا `ngZone.runOutsideAngular`، وده API بيسمح لنا نشغّل حاجات خارج نطاق Angular zone.

استخدمنا setTimeout (عشان نتخطى أول عملية تكون شغالة وكمان عشان Angular بيشغّل change detection على الأقل مرة واحدة بشكل تلقائي)، وفي داخل setTimeout، أسندنا قيمة جديدة للـ observable (todos$).

بما إن setTimeout شغّال خارج نطاق Angular zone، كمان استدعاء الـ API هيشتغل خارج الـ zone عشان الكود كله جوه runOutsideAngular. وبكده، مفيش حاجة بتنبّه Zone.js إن فيه حاجة اتغيرت.

### النتيجة

لما تشغّل الكود ده في التطبيق، هتلاقي إن اللي بيظهر في المتصفح هو “[]” بس.

### Broken State 🧨!

ده وضع غير مثالي 😄، وبيفتح لنا تساؤل تاني: ازاي Angular تقدر تتعامل مع التغييرات اللي بتحصل خارج نطاق Zone.js، وخصوصًا مع استراتيجية OnPush؟

### الحل؟

في الحالة دي، نقدر نستخدم `ChangeDetectorRef` وندعي `markForCheck` بعد التحديث عشان نجبر Angular على تشغيل change detection على الـ component ده بالتحديد، وده هيضمن إن التحديثات بتظهر في العرض حتى لو التغييرات حصلت خارج Zone.js.

### 🔴 Why can’t we just run the change detection for the component that is marked as dirty?

#### ليه ما نقدرش نكتفي بتشغيل change detection للـ component اللي متعلم كـ dirty؟

ممكن نعمل كده باستخدام detectChanges في كلاس ChangeDetectorRef، لكن ليها مشاكلها. لأن detectChanges بيشغل change detection بشكل متزامن، وده ممكن يسبب مشاكل في الأداء. لأن كل حاجة هتتنفذ في نفس مهمة المتصفح (browser task)، وده ممكن يسبب "performance issues" في الـ main thread ويخلي الأداء متقطع (jank).

تخيل مثلاً إنك بتشيك على التغييرات في قائمة فيها 100 عنصر كل ثانية أو ثانيتين، ده هيكون عبء كبير على المتصفح

#### الفرق بين markForCheck و detectChanges (تشغيل متزامن vs تشغيل مؤجل)

الmarkForCheck: لما بنستخدم markForCheck، إحنا بس بنقول لـ Angular إن فيه component متعلم كـ dirty، لكن مفيش أي تحديث بيحصل في اللحظة دي. حتى لو دعينا markForCheck 1000 مرة، مش هيبقى فيه مشكلة، لأن التحديث الفعلي هيحصل في دورة الـ change detection التالية، وده بيوفر أداء أفضل.

الdetectChanges: لما نستخدم detectChanges، Angular بتعمل الشغل الحقيقي فورًا، زي إنها تراجع الـ bindings وتحدث العرض (view) لو في حاجة محتاجة تتحدث. وده ممكن يسبب ضغط على الأداء، وخصوصًا لو عندنا مكونات كتيرة أو
تحديثات متكررة.

#### ليه يفضل نستخدم markForCheck بدل detectChanges؟

الmarkForCheck بيسمح لـ Angular إنها تشتغل بكفاءة أعلى عن طريق تأجيل التحديثات لحد ما تكون جاهزة لتشغيل change detection بشكل مجمع (coalesced run) بدل ما يكون فيه تحديثات متزامنة (sync runs) لكل component منفصل. وده بيخلي أداء التطبيق سلس أكتر ويقلل الضغط على الـ main thread في المتصفح.

### Signals 🚦

الـ Signals في Angular جابت تحسينات كبيرة في تجربة المطورين. نقدر بسهولة نخلق ونعمل اشتقاق للـ state وكمان نشغل side effects لما الـ state يتغير باستخدام الـ effects. مش محتاجين نعمل اشتراك ولا إلغاء اشتراك فيها، ومش محتاجين نقلق من مشاكل الـ memory leaks 🧯.

<div dir="auto" align="left">

```typescript
const name = signal("John");
const upperCaseName = computed(() => name().toUpperCase());

effect(() => {
  console.log(name() + " " + upperCaseName());
});

setTimeout(() => {
  name("Jane");
}, 1000);

// Output:
// John JOHN
// Jane JANE
```

</div>
كمان بنقدر نستخدم الـ signals في الـ template زي ما بنستخدم الـ function calls العادية.

<div dir="auto" align="left">

```HTML
@Component({
  template: `
    <button (click)="name.set('Jane')">Change name</button>
    <p>{{ name() }}</p>
  `
})
export class AppComponent {
  name = signal('John');
}
```

</div>

### 🔴 Signals and Change Detection

في الإصدار الجديد من Angular v17، حصل تطوير في موضوع الـchange detection أو "كشف التغيرات" في الـtemplates، اللي بيخليها تستجيب لأي تحديثات في البيانات تلقائيًا بطريقة أسهل وأسرع.

#### 1. الـSignals بدل الـAsync Pipe

زمان كنا بنستخدم حاجة اسمها async pipe عشان نقدر نستجيب لتحديثات البيانات في الـtemplate. يعني لو في قيمة بتتغير، الـasync pipe كان بيخلي Angular يعرف إن في تحديث ويعمل markForCheck للـtemplate عشان يرندر التغييرات دي. بس دلوقتي مع الإصدار الجديد، Angular بقى بيفهم إن الإشارات (signals) اللي بنستدعيها في الـtemplate مش مجرد استدعاءات دوال، لأ بقى بيشوفها كحاجات تستاهل المتابعة. وبالتالي، لو استخدمنا signal، Angular أوتوماتيك هيسجل حاجة اسمها effect (أو consumer) عشان يرائب الـsignal دي ويعمل markForCheck كل ما يحصل أي تغيير في قيمتها.

![ Dirty marking component and its ancestor up to the root](https://justangular.com/cd-article/signals-data-in-template.webp)

#### فإيه الفايدة هنا؟

مش محتاجين الـasync pipe: دلوقتي بقى سهل تستدعي الـsignal في الـtemplate عادي من غير ما تضطر تستخدم async pipe.

أداء أسرع: الـsignals دلوقتي بتوفر أداء أفضل لإن الـchange detection بيحصل في الأماكن اللي محتاجينها بس.

### 🔴Improving “how” – signals

لما signal ياخد قيمة جديدة في الـ template بتاعة الـ component، اللي بيحصل إنه بيقول لـ reactive consumer (اللي هو الكود اللي بيتابع التغيرات) إنه فيه تغيير محتاج يتشاف. لكن هنا التركيز على حاجة معينة: اللي بيتم تعليمه كأنه "dirty" أو محتاج تحديث هو reactive consumer اللي متعلق بالـ component view مش component view نفسها. يعني مش الكومبوننت ككل اللي بيتعلم كأنه عايز يتحدث، زي اللي بيحصل في الحالة العادية لو كنت بتستخدم OnPush.

#### يعني إيه Reactive Consumer؟

ببساطة، reactive consumer هو كود أو جزء من البرنامج وظيفته إنه "يراقب" signals أو بيانات معينة عشان يشوف لو حصل عليها تغيير، ويقرر إزاي يتصرف بناءً على التغيير ده. يعني هو "المستهلك" للتحديثات اللي بتحصل على البيانات، وبيشتغل بطريقة reactive (تفاعلية).

#### مثال توضيحي

تخيل عندك تطبيق فيه قائمة مهام، وكل ما المستخدم يضيف مهمة جديدة أو يحذف مهمة، عايز القائمة تتحدث تلقائيًا. هنا، الـ reactive consumer بيكون الجزء من الكود اللي "منتظر" يشوف لو فيه تغيير في قائمة المهام عشان يظهرها أو يخفيها من الشاشة. لما يحصل تغيير (زي إضافة مهمة جديدة)، الـ reactive consumer يعرف إنه فيه حاجة جديدة وبيتعلم إنه "dirty" أو محتاج يتحدث عشان يعرض التغيير.

#### ليه بنحتاج الـ Reactive Consumer؟

الفكرة هنا إنك مش عايز التطبيق يعيد بناء كل الكومبوننت أو الـ UI من الأول في كل مرة يحصل فيها تغيير بسيط. بدل كده، بنستفيد من إن عندنا reactive consumers، بحيث يقدروا يتابعوا البيانات المطلوبة ويحدثوا بس الأجزاء المتأثرة. ده بيساعدنا نحسن الأداء، لأننا مش بنعيد بناء الكل، بس بنركز على اللي اتغير.

#### يعني إيه Component View؟

الComponent view هي الشكل أو (View) اللي بيظهر للمستخدم من component معين في Angular. كل component بيكون ليه "view" خاص بيه، وده اللي بيعرض واجهة المستخدم (UI) اللي مرتبطة بالكومبوننت ده.

#### علاقة Component View بـ Change Detection

الـ Component View هو الجزء اللي Angular بيعمل عليه "فحص للتغييرات" (change detection)، بحيث لما يحصل تغيير على البيانات اللي مرتبطة بالـ view، بيتم تحديثها على الشاشة للمستخدم بدون الحاجة لتحديث الكومبوننت بالكامل. الفكرة دي بتساعد في تحسين أداء التطبيق لأنك مش مضطر تعمل إعادة بناء لكل الكومبوننتات مرة واحدة، لكن بس الجزء اللي فعلاً حصل فيه تغيير.

![ Dirty marking component and its ancestor up to the root](https://wp.angular.love/wp-content/uploads/2024/10/one-path.gif)

#### قبل Angular 17

قبل إصدار Angular 17، لما الـ reactive consumer كان بيتعلم إنه "dirty"، ده كمان كان بيخلي الـ component view نفسها تتعلم كأنها محتاجة تحديث. وده بيخلي الطريقة شبيهة باللي بتعمله AsyncPipe: بيشوف لو فيه تحديث، ويعمل التحديث على مستوى الكومبوننت ككل.

بالتالي، لو عايز تطبق الاستراتيجية دي وتقلل الكشف على التغيرات (عشان تتحسن الكفاءة)، كنت هتستخدم OnPush على كل الـ components، بحيث الكشف على التغيرات يتم على مسار واحد بس، ومش بيشمل كل مكونات التطبيق مرة واحدة.

#### بعد Angular 17

مع إصدار Angular 17 والأحدث، الوضع اتغير شوية. لما الـ reactive consumer يتعلم كأنه "dirty"، ده مش بيأثر على component view نفسها. بدل من كده، فيه دالة جديدة اسمها markAncestorsForTraversal بتشتغل. الدالة دي بتعمل حاجة شبيهة، لكنها بتمشي من الـ component لغاية فوق عند كل الـ components الجدود (من الـ component الحالي لغاية الكومبوننت الرئيسية اللي فوق الكل).

لكن الفرق هنا إن الدالة دي مش بتعلمهم إنهم كلهم محتاجين تحديث، لا! هي بتعلم بس الجدود إن عندهم مكون فرعي (child component) محتاج تحديث. وبتديهم علامة اسمها HasChildViewsToRefresh كإشارة إنه فيه تغيير جاي من تحت، لكن مش بتعمل تحديث فعلي غير لما يوصل عند الـ component اللي فيه التغيير الفعلي.

![ Dirty marking component and its ancestor up to the root](https://wp.angular.love/wp-content/uploads/2024/10/mark-traversal.gif)

التقنية الجديدة للتأكد من التغيير (change detection) اتحدثت. دلوقتي لما العملية تبدأ والشجرة في الحالة دي، بيعدي على الـcomponents A وE من غير ما يعمل لهم change detection، وده لأنهم OnPush لكن مش dirty. بفضل الـHasChildViewsToRefresh flag، Angular بيكمل يزور النودز اللي معمول لها علامة بالـflag ده ويدور على الـcomponent اللي محتاج change detection (في مثالنا هنا هو اللي فيه reactive consumer ومتعلّم عليه إنه dirty). لما يوصل للـcomponent F، يلاقي إن الـreactive consumer بتاعه dirty، فـcomponent ده بس اللي بيحصل له change detection – وده component الوحيد!

حلو، صح؟ بدل ما يعمل change detection للمسار الكامل بتاع الـcomponents، دلوقتي بقى بيعمله component واحد بس. ده مثال مبسط لشجرة components، لكن المكاسب في الأداء في التطبيقات الفعلية أكبر بكتير.

النهج الجديد في الـchange detection، اللي بيخلي component واحد بس يحصل له change detection بفضل الـsignals، بيطلق عليه "شبه محلي" أو “global-local/glocal” change detection.

🔴 تحذيرات لكن في شوية تحذيرات لازم تاخد بالك منها. خلينا نبص على مثال، لما ضغط المستخدم على الزرار وتسبب في تغيير إشارة signal:

### الـglocal change detection caveat

![ Dirty marking component and its ancestor up to the root](https://wp.angular.love/wp-content/uploads/2024/10/caveat1.gif)

### فين المشكلة؟

المشكلة بتحصل لو التغيير جاي من حاجة معينة، زي لما المستخدم يدوس على زرار، وده بيعمل تغيير في البيانات. في الحالة دي، Angular بيطبّق القواعد القديمة وبيعتبر إن الوحدة نفسها وكل اللي فوقها في الشجرة dirty، وده بيرجعنا للطريقة التقليدية اللي بتفحص الوحدات كلها، حتى لو بس وحدة واحدة محتاجة تحديث.

### إيه اللي نتعلمه من ده؟

لو التغيير في البيانات جاي من حاجة زي setTimeout أو Observable، ساعتها Angular هيشتغل بالنظام الجديد ويفحص الوحدات اللي محتاجة فقط. لكن لو التغيير سببه حاجة زي ضغط زرار، النظام القديم بيشتغل وبيعمل فحص لكل الوحدات اللي فوق الوحدة دي.

### 🔴 تحذير تاني:

لو في وحدات مش بتستخدم نظام OnPush، فحتى مع النظام الجديد، الوحدات دي هيتعمل لها فحص كل مرة، لأنها مش متعلّم عليها بالنظام الجديد.

![ Dirty marking component and its ancestor up to the root](https://wp.angular.love/wp-content/uploads/2024/10/caveat2a.gif)

### إيه اللي بيحصل لو مفيش OnPush؟

لو عندنا شجرة فيها وحدات زي A، B، C، وD، وكلهم مش شغالين بـOnPush، والوحدة F فيها تغيير بسيط أو تحديث، اللي هيحصل هو إن مش بس الوحدة F اللي هيتعمل لها change detection، لكن كمان الوحدات اللي في الشجرة ABCD هيتعمل لها فحص كامل في نفس الوقت. السبب إن الوحدات اللي مش بتستخدم OnPush بتشتغل على النظام الافتراضي اللي بيفحصها كل مرة يحصل فيها أي تغيير في التطبيق، حتى لو مش محتاجة.

### ليه ده بيأثر علينا؟

ده بيأثر على كفاءة التطبيق، لأنه بيزود عدد الوحدات اللي بيتم فحصها مع كل تغيير، حتى لو التغيير حصل في جزء بعيد عنها. وبالتالي، وجود وحدات مش بتستخدم OnPush بيلغي جزء من الفائدة اللي بنحصل عليها من نظام الـsemi-local change detection، لأنه بيخلينا نفحص وحدات أكتر من اللي محتاجة فعلاً.

### 🔴 Zoneless Angular — Let’s remove zone.js from Angular

ليه نشيل Zone.js أصلاً؟ خلينا نفكر الأول ليه ممكن نحب نتخلص من Zone.js. فيه شوية أسباب:

تقليل حجم الـ bundle في البداية: بص كده على الـ outputs اللي قدامك (واحد Zone-full وواحد Zoneless). زي ما انت شايف، Zone.js حجمه حوالي 30kB خام، وبيقل لـ 10kB لما يتضغط. ده حجم مش قليل، خصوصاً إنه بيدخل ضمن الحاجات اللي لازم تتحمل قبل ما التطبيق يبدأ يشتغل.

![Zone-full vs Zoneless build output](https://wp.angular.love/wp-content/uploads/2024/10/build-output.png)

تجنب الـ change detection اللي ملهاش لازمة: Zone.js بيساعد في إن Angular يعمل change detection من خلال إنه بيبلغه لما أي عملية تخلص. لكن هو في الحقيقة مش بيعرف إذا كانت العمليات دي غيرت أي داتا ولا لأ. عشان كده، الفريم وورك بيبالغ شوية وبيعمل run "للاحتياط".

عايز أوضح حاجة – Zone.js كان أداة رهيبة (أو على الأقل كان كده لما بدأ) وساهم كتير في نجاح Angular من الأول. كان بيخلي التعامل مع الفريم وورك سهل حتى للمطورين المبتدئين – يركزوا بس على شغلهم، وكل حاجة تشتغل بطرق سحرية.

لكن، زي ما شوفنا، السحر ده له تكلفة. متأكد إن كتير من التطبيقات شغالة كويس جداً مع Zone.js. بس في حالات التطبيقات المعقدة اللي محتاجة أداء أعلى، أكيد البحث عن بدائل خطوة منطقية.

### 🔴Zoneless scheduler

الـ "Zoneless Scheduler" الجديد اللي تم تقديمه في الإصدار 17.1 بيغير طريقة عمل الـ "Zone.js" events وبيستنى لحد ما يجي له إشعار صريح من أجزاء تانية في الفريمورك عن أي تغييرات. التغيير ده مهم لأنه بدل ما يشغل عملية الـ "change detection" لما "أي عملية تحصل وخلاص"، النظام بقى يشغله "لما يوصل له إشعار أن فيه بيانات اتغيرت".

عشان يحقق ده، الجدول الجديد بيعرض طريقة خاصة اسمها "notify" وبتتدعي في الحالات دي:

لما "signal" اللي بيتقرا في الـ "template" يوصل له قيمة جديدة (بالتحديد، لما "markAncestorsForTraversal" تتدعي).

لما الـ "component" يتعلم أنه بقى "dirty" عن طريق "markViewDirty". ده ممكن يحصل بسبب وصول قيمة جديدة من "AsyncPipe"، أو "template-bound event"، أو عن طريق استدعاء "ComponentRef.setInput"، أو استدعاء "ChangeDetectorRef.

markForCheck" بشكل مباشر، أو حاجات تانية.

لما "afterRender hook" يتسجل، أو لما "view" يتضاف تاني للـ "change detection tree" أو يتشال من الـ "DOM". في الحالات دي، "notify" بتتدعي لكنها بس بتنفذ الـ "hooks" من غير ما تعمل "refresh" للـ "view".

ممكن تسأل لو "change detection" ممكن يشتغل كتير لو "signals" كتيرة اتغيرت في نفس الوقت أو لو حصلت "events" بسرعة ورا بعض. لكن التنفيذ بتاع الـ "scheduler" معمول عشان يتعامل مع ده بكفاءة. بيجمع الإشعارات على مدار فترة قصيرة وبيعمل "schedule" لتشغيل "change detection" مرة واحدة بدل ما يشغله كذا مرة. السلوك ده مبني على سباق بين "setTimeout" و "requestAnimationFrame"، بس مش هندخل في التفاصيل دي هنا. المهم إن "notify" دي بتتجمع، عشان تضمن أحسن أداء.

![Zone-full vs Zoneless build output](https://wp.angular.love/wp-content/uploads/2024/10/zoneless.gif)

</div>

## Angular Signals Component API input and output and model

[⬆️ Back to Top](#top)

<div dir="auto" align="right">

في أنجولار، بقت في طريقة جديدة لكتابة الcomponents والdirectives والpipes، والطريقة دي اسمها Signal Components، وهي أبسط وأقوى من الطريقة التقليدية.

الSignal Components هي بديل كامل للdecorators زي `Input` و `Output`. كمان بتوفر طريقة جديدة لعمل two-way binding (التواصل رايح جاي). والمفروض إن دي تبقى الطريقة المفضلة اللي تكتب بيها الcomponents الجديدة في أنجولار من دلوقتي، وبالمناسبة هي جاهزة للاستخدام حالياً.

الميزة الأساسية في Signal Components إنها مش محتاجة decorators، وكمان مفيش أغلب lifecycle hooks اللي متعودين عليها، لأنها متكاملة بشكل عميق مع الإشارات (signals).

لو عايز تستفيد من Signal Components، لازم تحدث لنسخة Angular 17.3 أو أعلى.

في الدليل ده، حاشرح إزاي تكتب components بطريقة Signal، وإزاي تستخدم الأدوات الأساسية زي input و output و model عشان تبني Signal Components في أنجولار.

<div dir="auto" align="left">

### Signal inputs with input()

</div>

الـinput() function بقت بديل للـInput() decorator، وده بيعتبر طريقة جديدة في Angular للتعامل مع الـinputs.

لكن مهم تعرف إن Input() decorator لسه شغال وهيفضل مدعوم لفترة جاية.

لما نستخدم input، القيمة اللي بنحطها للـinput property بتتحول لحاجة اسمها Signal. بمعنى إن الـSignal ده بيحتفظ دايمًا بأحدث قيمة متاحة للـinput اللي جاية من الجزء الأب أو الـparent.

مثال عملي: هنشوف إزاي نعمل input property اسمها book في BookComponent

<div dir="auto" align="left">

```typescript
import { Component, input } from "@angular/core";

@Component({...})
class BookComponent {
 book = input<Book>()
}
```

</div>

هنا استخدمنا input عشان نعمل input field اسمها book.

الفرق هنا إن input بيرجع قيمة نوعها `InputSignal<Book>` . وده معناه إن book مش مجرد object عادي زي الطريقة القديمة باستخدام @Input، لكنها بقت حاجة بتحافظ دايمًا على آخر قيمة جايه من الجزء الأب.

لكن بالرغم من استخدام الطريقة الجديدة، من ناحية الجزء الأب اللي بيبعت البيانات للـBookComponent، مفيش أي تغيير. تقدر تبعت بيانات بالطريقة المعتادة:

<div dir="auto" align="left">

```HTML
<book [book]="angularCoreDeepDiveBook" />
```

</div>
 <div dir="auto" align="left">

```typescript
angularCoreDeepDiveBook = {
  title: "Angular Core Deep Dive",
  synopsis: "A deep dive into Angular core concepts",
};
```

</div>
<div dir="auto" align="left">

### Reading input() values

</div>

من ناحية الـ Parent Component، كل حاجة بتفضل زي ما هي.

لكن بالنسبة للـ Component نفسه، إزاي نقدر نجيب قيمة الـ input؟

علشان نقرا القيمة، محتاجين نستدعي الـ Signal بتاع الـ book، زي أي Signal تاني في Angular:

<div dir="auto" align="left">

```typescript
book();
```

</div>

السطر ده لما نستدعيه، هيجيب لنا أحدث قيمة موجودة في book signal، اللي فيها قيمة angularBook object.

خلي بالك إن Signals دايمًا بيكون ليها قيمة، فـ ()book هترجع لنا يا إما undefined لو مفيش حاجة، أو قيمة book object.

دلوقتي هنعدل الـ Component بتاعنا علشان نعرض title وsynopsis بتوع الكتاب في template بتاعه:

<div dir="auto" align="left">

```typescript
import { Component, input } from "@angular/core";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book()?.title }}</b>
    <div>{{ book()?.synopsis }}</div>
  </div> `,
})
class BookComponent {
  book = input<Book>();
}
```

</div>

لاحظ إننا في template استدعينا الـ Signal بتاع ()book، وبعد كده دخلنا على الـ title وsynopsis properties.

استخدمنا ?. (الـ Optional Chaining) علشان لو الـ book ممكن يبقى undefined.

الكود ده شغال، لكن ممكن يبقى متعب شوية.

طب إيه اللي هيحصل لو إحنا متأكدين وضامنين إن قيمة book عمرها ما هتكون undefined؟

هنا بقى يظهر لنا الفرق بين نوعين من Signal Inputs اللي ممكن نستخدمهم في Angular:

#### Optional Inputs

#### Required Inputs

<div dir="auto" align="left">

### Optional signal inputs

</div>

بشكل افتراضي، inputs اللي بنعملها باستخدام ()input بتعتبر optional.

ده معناه إننا مش مضطرين نحدد قيمة للـ input لما نستخدم component ده من جوه parent component.

المثال اللي استخدمناه فوق مع BookComponent كان optional input.

وده معناه حاجتين مهمين:

أول حاجة، ممكن نستخدم BookComponent من غير ما نحدد قيمة للـ book input:

<div dir="auto" align="left">

```HTML
<book />
```

</div>

تاني حاجة، في الحالة دي، الـ book signal هيبقى قيمته undefined.

لو مش عايزين تبقى القيمة الافتراضية هي undefined، ممكن كمان نحدد قيمة مبدئية للـ optional input كالتالي:

<div dir="auto" align="left">

```typescript
const age = input<number>(0);
```

</div>

كده، القيمة المبدئية للـ age input signal هتبقى 0 بدل undefined.

<div dir="auto" align="left">

### Making an input to be required

</div>

في بعض الحالات، بنحتاج إن input properties تكون required بدل ما تبقى optional. وده بيكون مفيد لما نكون عايزين نضمن إن قيمة معينة هتكون موجودة دايمًا.

إزاي نعمل ده؟ ببساطة، بنستخدم input.required بالشكل ده:

<div dir="auto" align="left">

```typescript
import { Component, input } from "@angular/core";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book().title }}</b>
    <div>{{ book().synopsis }}</div>
  </div> `,
  styles: ``,
})
class BookComponent {
  book = input.required<Book>();
}
```

</div>

فيه شوية حاجات مهمة لما بنستخدم input.required

🔴 مش ممكن نحدد قيمة مبدئية للـ input signal. القيمة الأولية هتبقى هي القيمة اللي بنمررها للـ input من الـ parent component.

🔴 ماينفعش نهمل الـ book property في الـ parent component

<div dir="auto" align="left">

```HTML
<book />
```

</div>

لو عملنا كده، هيظهر خطأ في الـ compilation لأن الـ book input field مش optional دلوقتي!

علشان نحل المشكلة دي، لازم نمرر قيمة للـ book property لما نستخدم BookComponent:

<div dir="auto" align="left">

```HTML
<book [book]="angularBook" />
```

</div>
وبكده نكون غطينا أساسيات الفرق بين optional وrequired inputs.

<div dir="auto" align="left">

### Setting an input property alias

</div>

غالبًا، بنحب نخلي اسم input property هو نفسه اسم input signal.

لكن أحيانًا ممكن نحتاج ندي الـ input property اسم مختلف، وده نادرًا ما بيحصل، لكنه مفيد في بعض الحالات.

لو واجهت موقف زي ده، دي الطريقة اللي تقدر تعمل بيها input alias سواء للـ optional أو required inputs:

لعمل alias لـ optional input:

<div dir="auto" align="left">

```typescript
book = input<Book>(null, {
  alias: "bookInput",
});
```

</div>
لعمل alias لـ required input:

<div dir="auto" align="left">

```typescript
book = input.required<Book>({
  alias: "bookInput",
});
```

</div>

إزاي نستخدم الـ input alias في parent component:
لما نيجي نستخدم الـ alias في parent component، بيكون بالشكل ده:

<div dir="auto" align="left">

```HTML
<book [bookInput]="angularBook" />
```

</div>

### 🔴 ملاحظة:

لو حاولت تستخدم اسم الـ input property الأصلي بدل alias، زي كده:

<div dir="auto" align="left">

```HTML
<book [book]="angularBook" />
```

</div>

#### ❌ الكود مش هيشتغل، وهيطلع لك خطأ

<div dir="auto" align="left">

### Input value transformation: the transform function

</div>

في بعض الحالات النادرة، ممكن نحتاج نعدل قيمة الـ input قبل ما تتخزن في input signal.

بنعمل كده عن طريق استخدام input transform، اللي بيخلينا نغير البيانات اللي جاية من parent component قبل ما تتخزن.

دي الطريقة اللي نقدر نحدد بيها input transforms سواء للـ optional أو required inputs:

للـ optional input:

<div dir="auto" align="left">

```typescript
book = input(null, {
  transform: (value: Book | null) => {
    if (!value) return null;

    value.title += " :TRANSFORMED";

    return value;
  },
});
```

</div>

للـ required input:

<div dir="auto" align="left">

```typescript
book = input.required({
  transform: (value: Book | null) => {
    if (!value) return null;

    value.title += " :TRANSFORMED";

    return value;
  },
});
```

</div>

#### 🔴ملاحظة:

قيمة خاصية transform لازم تكون pure function، يعني دالة بتشتغل بدون side effects (تأثيرات جانبية).

في الدالة دي بنكتب منطق تحويل القيمة اللي محتاجينه، ومهم جدًا إننا نرجع قيمة من الدالة علشان الـ transform يشتغل صح.

<div dir="auto" align="left">

### Deriving values from signal inputs

</div>

بما إن input في الأساس هو مجرد signal، نقدر نعمل بيه كل اللي بنعمله مع أي signal تاني، وده بيشمل حساب derived signal منه.

إزاي نقدر نعمل derived signal من input signal باستخدام computed:

<div dir="auto" align="left">

```typescript
import { Component, input, computed } from "@angular/core";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book()?.title }}</b>
    <div>{{ book()?.synopsis }}</div>
    <div>{{ bookLength() }}</div>
  </div> `,
  styles: ``,
})
class BookComponent {
  book = input.required<Book>();

  bookLength = computed(() => this.book().title.length);
}
```

</div>

في الكود ده، bookLength هو derived signal ناتج من book signal.

بمعنى، في أي وقت تتغير فيه قيمة book input signal، الـ bookLength signal هيتم حسابه من جديد.

كمان ممكن نستخدم effect علشان نراقب أي تغييرات بتحصل في book signal لو حابين.

خلوا في بالكم، input signal هو مجرد read-only signal، يعني مفيش حاجة خاصة بيه، تقدروا تعملوا عليه كل العمليات اللي ممكن تعملوها مع أي signal تاني.

<div dir="auto" align="left">

### No more need for the OnChanges lifecycle hook

</div>

استخدام signal inputs بدلًا من Input() decorator بيدينا فائدة مخفية وهي تبسيط عملية متابعة التغييرات في الـ input بدون الحاجة لاستخدام OnChanges lifecycle hook.

خلينا نوضح ده بمثال:

الطريقة التقليدية باستخدام Input@ و OnChanges:
في الطريقة القديمة، لو عايزين نتابع تغييرات الـ input بنستخدم OnChanges بالشكل ده:

<div dir="auto" align="left">

```typescript
import { Component, Input, OnChanges, SimpleChanges } from "@angular/core";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book?.title }}</b>
    <div>{{ book?.synopsis }}</div>
  </div> `,
})
class BookComponent implements OnChanges {
  @Input() book: Book;

  ngOnChanges(changes: SimpleChanges) {
    if (changes["book"]) {
      console.log("Book changed: ", changes.book.currentValue);
    }
  }
}
```

</div>

الطريقة الجديدة باستخدام signals وeffect

دلوقتي، مع نظام signal-based الجديد، مابقيناش محتاجين OnChanges lifecycle hook. بدل كده، بنستخدم effect لمتابعة أي تغيير يحصل في input signal بشكل مباشر:

<div dir="auto" align="left">

```typescript
import { Component, input, effect } from "@angular/core";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book()?.title }}</b>
    <div>{{ book()?.synopsis }}</div>
  </div> `,
  styles: ``,
})
class BookComponent {
  book = input.required<Book>();

  constructor() {
    effect(() => {
      console.log("Book changed: ", this.book());
    });
  }
}
```

</div>

### الفكرة الأساسية:

بدون الحاجة لأي lifecycle hook خاص، مجرد استدعاء effect بيكون كافي علشان يتابع أي تغييرات تحصل في input signal.

<div dir="auto" align="left">

### Angular component outputs with output()

</div>

الـ output() API هو بديل مباشر للـ Output() decorator التقليدي في Angular.

رغم إن Output مش هيتم إيقافه، لكن استخدام output بيخلي كتابة الكود أكثر تناسقًا، خاصة لو كنا بنستخدم input، وبيقدم طريقة أكثر type-safe وأفضل تكاملًا مع RxJs مقارنة بالطريقة القديمة اللي بتستخدم EventEmitter.

إزاي نستخدم output لتحديد component output في Angular:

<div dir="auto" align="left">

```typescript
import { Component, output } from "@angular/core";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book()?.title }}</b>
    <div>{{ book()?.synopsis }}</div>
    <button (click)="onDelete()">Delete Book</button>
  </div>`,
})
class BookComponent {
  deleteBook = output<Book>();

  onDelete() {
    this.deleteBook.emit({
      title: "Angular Deep Dive",
      synopsis: "A deep dive into Angular core concepts",
    });
  }
}
```

</div>

من وجهة نظر parent component

بنفس طريقة event handling المعتادة، الـ parent component ممكن يستمع لحدث
deleteBook بالشكل ده:

<div dir="auto" align="left">

```HTML
<book (deleteBook)="deleteBookEvent($event)" />
```

</div>
وفي  deleteBookEvent، هنستقبل قيمة book اللي تم إرسالها ونقدر نستخدمها في الكود:
<div dir="auto" align="left">

```typescript
deleteBookEvent(book: Book) {
  console.log(book);
}
```

</div>

<div dir="auto" align="left">

### Setting an alias on an output()

</div>

زي ما قدرنا نحدد alias للـ signal inputs، كمان ممكن نحدد alias للـ output بالطريقة دي

<div dir="auto" align="left">

```typescript
deleteBook = output<Book>({
  alias: "deleteBookOutput",
});
```

</div>
إزاي parent component يستخدم الـ alias:
لما نحدد alias، الـ parent component هيستخدم الاسم الجديد deleteBookOutput للاستماع للحدث:
<div dir="auto" align="left">

```HTML
<book (deleteBookOutput)="deleteBookEvent($event)" />
```

</div>

<div dir="auto" align="left">

### output() RxJs Interoperability using outputFromObservable()

</div>

زي ما وضحنا، الـ ()output مش مبني على signals، لكنه أكتر type-safe من الـ Output@ التقليدي، وبيوفر تكامل أفضل مع RxJs.

واحدة من الميزات القوية هي إننا نقدر بسهولة نعمل output signal بيصدر القيم من Observable.

علشان نعمل ده، بنستخدم outputFromObservable، ودي الطريقة:

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";
import { outputFromObservable } from "@angular/core/rxjs-interop";
import { of } from "rxjs";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book()?.title }}</b>
    <div>{{ book()?.synopsis }}</div>
  </div>`,
})
class BookComponent {
  deleteBook = outputFromObservable<Book>(
    of({
      title: "Angular Core Deep Dive",
      synopsis: "A deep dive into the core features of Angular.",
    })
  );
}
```

</div>

🚀 الميزة هنا هي إننا نقدر نربط بين Observables وoutputs في Angular بشكل مباشر، وده بيسهل الشغل مع streams وتكامل RxJs، خصوصًا لو بنعتمد على reactive programming.

<div dir="auto" align="left">

### output() RxJs interoperability with outputToObservable()

</div>

زي ما قدرنا نحول Observable لـ output باستخدام outputFromObservable، ممكن كمان نحول output إلى Observable باستخدام outputToObservable.

دي الطريقة:

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";
import { output, outputToObservable } from "@angular/core/rxjs-interop";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <b>{{ book()?.title }}</b>
    <div>{{ book()?.synopsis }}</div>
    <button (click)="onDelete()">Delete Book</button>
  </div>`,
})
class BookComponent {
  deleteBook = output<Book>();

  deleteBookObservable$ = outputToObservable(this.deleteBook);

  constructor() {
    this.deleteBookObservable$.subscribe((book: Book) => {
      console.log("Book emitted: ", book);
    });
  }

  onDelete() {
    this.deleteBook.emit({
      title: "Angular Core Deep Dive",
      synopsis: "A deep dive into Angular core concepts",
    });
  }
}
```

</div>

استخدمنا outputToObservable لتحويل deleteBook output إلى Observable اسمه deleteBookObservable$.

دلوقتي أي قيمة بيصدرها deleteBook output، هيتم استقبالها برضه في deleteBookObservable$.

استخدمنا subscribe لمتابعة القيم الصادرة وطباعة أي book object جديد في الكونسول.

🚀 الميزة هنا هي إننا نقدر نشتغل مع outputs كـ Observables، وده بيسهل التكامل مع RxJs وreactive programming.

<div dir="auto" align="left">

### What is the model() API?

</div>

بالإضافة إلى `()input` و `()output`، أضافت Angular API جديدة اسمها `()model`، واللي بنستخدمها لإنشاء model inputs.

#### ما هو Model Input؟

الModel Input هو نوع خاص من inputs بيكون writeable، يعني قابل للقراءة والكتابة! وده معناه إننا بنقدر نعمل two-way data binding بين الـ parent component والـ child component.

ببساطة، بيسمح للـ parent component إنه يمرر بيانات للـ child component، وفي نفس الوقت، child component يقدر يرجع بيانات للـ parent component.

مثال على استخدام `()model`
خلينا نشوف مثال يوضح استخدام `()model` في two-way binding:

<div dir="auto" align="left">

```typescript
import { Component, model } from "@angular/core";

@Component({
  selector: "book",
  standalone: true,
  template: `<div class="book-card">
    <input [(ngModel)]="bookModel().title" />
    <div>{{ bookModel().synopsis }}</div>
    <button (click)="updateBook()">Update Book</button>
  </div>`,
})
class BookComponent {
  bookModel = model<Book>();

  updateBook() {
    const updatedBook = {
      ...this.bookModel(),
      title: "Updated Title",
    };
    this.bookModel.set(updatedBook); // Emit updated data to the parent
  }
}
```

</div>

الـ parent component ممكن يمرر قيمة للـ model باستخدام [(bookModel)] بالطريقة المعتادة.
child component يقدر يقرأ أو يعدل قيمة الـ model input، ولما يعمل تعديل باستخدام ()set, البيانات الجديدة بتترجع للـ parent component مباشرة.

من منظور parent component:

<div dir="auto" align="left">

```HTML
<book [(bookModel)]="parentBook"></book>
```

</div>
الـ parentBook هتتحدث تلقائيًا لما child component يغير قيمة الـ model.

<div dir="auto" align="left">

### When to use model()?

</div>

في بعض الحالات، مثلًا لو عندنا date picker component بيحتوي على قيمة رئيسية (زي قيمة date نفسها)، `()model`ممكن يكون مفيد جدًا. في المثال ده:

الparent component هيحدد initial value للتاريخ.

الchild component يقدر يرجع القيم المحدثة للـ parent لما المستخدم يغيرها.

✨ومع ذلك، في الغالب:

يفضل استخدام inputs وoutputs العادية لأنها أكثر وضوحًا وأسهل في الفهم.

ال`()model` لو تم استخدامها بدون سبب قوي، ممكن تؤدي لكتابة كود صعب الفهم وصعب تتبعه أثناء الـ debugging.

تخيل إنك بتستخدم model input عبر عدة مستويات من components متداخلة، هيبقى صعب تعرف مصدر قيمة معينة أثناء تتبع الأخطاء.

</div>

## What is an Angular Service

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
ببساطة كده، الـ Services في Angular هي طريقة بنستخدمها علشان نكتب كود نقدر نستخدمه أكتر من مرة في كذا Component. يعني بدل ما نكرر نفس الكود في كل Component، بنكتب الكود ده مرة واحدة في Service ونستدعيه في أي Component يحتاجه.

طيب، إزاي بنستدعي الـ Service؟ بنعمل حاجة اسمها Dependency Injection، وده معناه إننا بنضيف الـ Service للـ Component أو لـ Service تانية عن طريق الـ constructor. Angular بتسهل لنا القصة دي باستخدام حاجة اسمها Providers، اللي بنحطها في الـ Module بتاعنا علشان تقول لـ Angular إن الـ Service دي متاحة للاستخدام في كل الـ Components اللي محتاجاها.

✨ النقطة التانية المهمة هي إن Angular بيبني حاجة اسمها Injector Tree. الفكرة إن لما يكون عندك (Components) كتيرة في التطبيق، Angular بيعمل شجرة Injectors علشان يعرف يوزع الـ Services دي بناءً على احتياجات كل Component. الطريقة دي اسمها Hierarchical Pattern، واللي معناها إن الـ Injectors بتتبنى بشكل شجري، زي ما الـ Components بتتبنى على شكل شجرة.

بالتالي، لو Component معين محتاج Service معينة، Angular هيدور عليها في أقرب Injector ليه في الشجرة. لو ملقهاش، هيكمل يدور لحد ما يطلع لفوق في الشجرة ويلاقيها.

#### لخلاصة: الـ Services بتوفر كود reusable، وAngular بتستخدم Dependency Injection مع نظام شجري من الـ Providers علشان توزع الـ Services دي في التطبيق كله بطريقة ذكية ومرتبة.

</div>
<hr/>

## What Angular Services are used for

[⬆️ Back to Top](#top2)

##### 1- Features that are independent of components such a logging services

##### 2 -Share logic or data across components

##### 3- Encapsulate external interactions like data access

<hr/>

## Advantages of Angular Service

[⬆️ Back to Top](#top2)

##### 1- Services are easier to test.

##### 2- They are easier to Debug.

##### 3- We can reuse the service at many places.

<hr/>

## Benefits of Dependency Injection

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
بص، Dependency Injection هو أسلوب بنستخدمه عشان نخلي مكونات الـ Angular تشتغل مع بعضها بشكل مرن من غير ما تكون مرتبطة ببعضها بشكل مباشر. يعني إيه؟ يعني مثلاً عندنا مكون اسمه AppComponent وده محتاج يشتغل مع ProductService. في العادي، عشان الـ AppComponent يشتغل مع الـ ProductService، كان المفروض يبقى فاهم إزاي الـ ProductService بيتعمله إنشاء وبيشتغل، لكن هنا الفكرة في Dependency Injection إنه بيخلينا نمرر الـ ProductService للـ AppComponent من غير ما يبقى عارف تفاصيل إنشاؤه.

#### طيب إيه الفايدة؟

##### 1- Loosely Coupled (غير مرتبط بشكل مباشر)

يعني الـ AppComponent مش مرتبط بالـ ProductService اللي انت بتديله. عادي ممكن تديله BetterProductService أو MockProductService من غير ما يعرف الفرق. هو مش محتاج يعرف كل التفاصيل.

##### 2- Easier to Test (أسهل في الاختبار)

دلوقتي الاختبار بقى سهل. بما إن الـ AppComponent مش مرتبط بنوع معين من ProductService، فإنت ممكن تعمل mock للـ ProductService وتستخدمه في الاختبار من غير ما يبقى عندك مشاكل في الكود الأساسي.

##### 3- إعادة استخدام الكود

دلوقتي بقى عندك component ممكن تعيد استخدامه في أماكن تانية بسهولة، لأن طالما الخدمة اللي بتشتغل مع component بتلتزم بالـ interface اللي محتاجه، خلاص مفيش مشكلة.

</div>

<hr/>

## The five main players in the Angular Dependency Injection Framework?

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
ال Consumer

ده اللي هو الكلاس اللي محتاج الـ Dependency. يعني هو اللي عايز "الخدمة" أو "الـ Service" علشان يستخدمها في الكود بتاعه. وده ممكن يكون أي حاجة زي الـ Component أو الـ Directive أو حتى الـ Service تانية.

Dependency
الـ Dependency هو الحاجة اللي الـ Consumer محتاجها. يعني هي الـ Service اللي إحنا عايزين نحقنها في الـ Consumer

الInjection Token (DI Token)
ده حاجة زي "المفتاح" اللي بنستخدمه علشان نقول للـ Angular إحنا عايزين نحقن أي Dependency. كل Dependency لازم يبقى ليها حاجة بتحددها زي ID، علشان الـ Angular يعرف يلاقيها ويحقنها في الـ Consumer. يعني بنستخدم الـ DI Token علشان نسجل الـ Dependency بتاعتنا.

الProvider
ده الشخص اللي "بيوفر" الـ Dependencies. يعني عنده لستة بكل الـ Dependencies اللي بنستخدمها في الأبلكيشن بتاعنا، مع الـ Tokens بتاعتها. الـ Provider هو اللي بيستخدم الـ Token علشان يحدد الـ Dependency ويجهزها علشان الـ Consumer يقدر يستخدمها.

الInjector
ده هو المسؤول إنه يمسك الـ Providers ويشوف إيه الـ Dependency اللي الـ Consumer طالبها. بعد كده هو اللي بيعمل "إنشاء" للـ Dependency (يعني بيخلق instance منها) وبيحقنها في الـ Consumer. الـ Injector بيستخدم الـ DI Token علشان يدور على الـ Dependency ويحقنها في الكلاس اللي طالبها.

بمعنى تاني، لو انت في الـ Component بتاعك بتقول إنك محتاج "Service" معينة، الـ Injector بيدور في الـ Providers ويشوف الـ Service اللي انت طالبها ويبعتهالك.

</div>

## Service Scope in Angular

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
1- لما تيجي تعمل Service في الـAngular، لو وفرتها على مستوى الـ root module، ده معناه إن الـ service دي هتبقى متاحة في كل حتة في التطبيق. يعني أي component أو service تانية في التطبيق تقدر تستخدمها من غير مشاكل.

2- أما لو وفرت الـ service في مستوى الـ component نفسه، يبقى الـ service دي متاحة بس للـ component ده والـ child components اللي جواه. يعني لو في components برا مش هتقدر تستخدم الـ service دي.

3- لو وفرت الـ service دي في أي module تاني (غير الـ Lazy Loaded Module)، برضو هتبقى متاحة لكل التطبيق. يعني تقدر تستخدمها في أي حتة من المشروع بتاعك.

الLazy Loaded Module هو module بيتم تحميله بس لما يبقى محتاجه، مش بيتحمل مع بداية التطبيق. عشان كده، الـ services اللي بتتوفر في الـ Lazy Loaded Module بتكون محصورة (scoped) جوا الـ module ده بس.

يعني إيه الكلام ده؟ يعني لو أنت وفرت service معينة جوا Lazy Loaded Module، الـ service دي هتكون متاحة فقط للعناصر (components أو services) اللي موجودة جوا نفس الـ module ده. يعني لو في components أو services تانية موجودة في أجزاء تانية من التطبيق (مش موجودة جوه الـ Lazy Loaded Module) مش هتقدر تستخدم الـ service دي.

### مثال يوضح أكتر:

لو عندك تطبيق كبير فيه Modules كتير، وليكن مثلاً:
AdminModule
UserModule
لو عملت Lazy Loading للـ AdminModule ووفرت فيه service خاصة (مثلاً AdminService)، الخدمة دي هتبقى متاحة فقط في الـ AdminModule. لو حاولت تستخدمها في UserModule أو أي module تاني، مش هتشتغل ومش هتبقى متاحة هناك.

</div>
<hr/>

## What is Angular Injector?

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">

الـ Angular Injector هو اللي بيقوم بإنشاء الـ dependency (يعني أي حاجة محتاجها الكومبوننت أو الخدمة عشان تشتغل) ويحقنها في الكومبوننت أو الخدمة اللي طالبة الحاجة دي.

دلوقتي، عشان الـ Injector يعرف يجيب الـ dependency دي، بيشوف حاجة اسمها Injection Token. الـ Injection Token ده زي اسم أو علامة مميزة للـ dependency اللي انت طالبها. بعد كده، الـ Injector بيروح يبص في قائمة الـ Providers اللي هي المكان اللي بيحتفظ فيه Angular بطريقة إنشاء الـ dependency دي.

الـ Provider ده بيحتوي على معلومات عن إزاي نعمل instance (نسخة جديدة) من الـ dependency دي. فاللي بيحصل إن الـ Injector أول ما يلاقي الـ Provider المناسب، بيعمل نسخة من الـ dependency دي، وبعد كده يحقنها في الكومبوننت أو الخدمة اللي محتاجاها.

✨ الموضوع زي لما تكون بتطلب خدمة معينة (زي سباك أو كهربائي)، والـ Injector هو الشخص اللي بيوصل الخدمة دي ليك، بس هو لازم يروح يدور في دليل الخدمات (اللي هو الـ Providers) عشان يلاقي الشخص المناسب (الـ dependency) اللي هيعمل الخدمة المطلوبة.

</div>
<hr/>

## When is Angular Injector created?

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
ببساطة كده، لما بنقول إن Angular بيشتغل، بيبدأ بإنه يخلق حاجتين أساسيتين زي الشجر:
واحدة اسمها ModuleInjector tree للتعامل مع الـ Modules، وواحدة تانية اسمها ElementInjector tree للتعامل مع العناصر زي الـ Components والـ Directives.

### أول حاجة بتحصل عند الـ Bootstrap

لما البرنامج بيبدأ (الـ bootstrap)، Angular بيحمل أول حاجة Root Module اللي هي AppModule. الموديول ده بيبقى زي الأصل اللي كل حاجة بعد كده هتتحمل منه. مع تحميله، Angular بيخلق حاجة اسمها RootModule Injector. ده المسؤول عن البرنامج كله، وبنقول عليه الـ application-wide scope، يعني ينفع يستعمل أي حاجة في أي حتة في التطبيق.

### بعد كده بيجي دور الـ Components

لما Root Module يخلص تحميل، يروح يجيب الـ AppComponent اللي هو أهم Component في التطبيق لأنه الأب لكل الـ Components اللي بعد كده. مع كل Component بيتخلق Injector خاص بيه، فالـ AppComponent بيأخذ حاجة اسمها root Injector ودي اللي بتبقى جذر شجرة الـ ElementInjector tree اللي هي للشغل الخاص بالـ Components.

### إزاي بيتكون باقي الـ Injectors؟

كل Component تحت AppComponent بيبقى ليه أولاده من الـ Components، وكل واحد فيهم برضه بياخذ Injector خاص بيه. فكل ما التطبيق يكبر ويتفرع، الـ Injectors بتكبر وتتفرع بنفس الطريقة في شجرة موازية للـ Components tree، وده اللي بنسميه شجرة الـ ElementInjector.

#### باختصار، عندك شجرتين:

- الModuleInjector tree للتعامل مع الموديولز.
- الElementInjector tree اللي بتوازي شجرة الـ Components وبتبني Injectors ليهم.

✨ الموضوع ده بيساعد Angular إنه ينظم استدعاء الـ Dependencies بشكل سليم ويوفرها في الأماكن الصح.

</div>
<hr/>

## Registering the service with an injector

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
ببساطة كده، في Angular لما بتيجي تضيف Service في التطبيق، بيكون في حاجة اسمها Injector هو اللي بيقوم بعملية إدارة وإضافة الـ Service في المكان الصح في التطبيق. ده بيتم عن طريق حاجة اسمها Providers، ودي بتسجل الخدمات اللي انت عاوز تستخدمها.

### إزاي بتسجل الـ Service؟

لو سجلت الـ Service في الـ Module:

ده معناه إن الخدمة دي هتكون متاحة في كل مكان في التطبيق. يعني لو أنت ضفت الـ Service بتاعتك في الـ Providers بتاعة الـ NgModule@، هتكون متاحة في كل المكونات (components) وكل الحتت اللي في المشروع.

<div dir="auto" align="left">

```typescript
providers: [ProductService, LoggerService];
```

</div>
لو سجلت الـ Service في Component

في الحالة دي، الخدمة هتكون متاحة بس للمكون ده (Component) وأي مكونات (Components) بتكون جواه أو تابعاله. يعني هيكون ليها نطاق أصغر.

### استخدام providedIn مع الـ Injectable:

في طريقة تانية لتسجيل الـ Service وهي باستخدام الـ providedIn جوه الـ Injectable@. دي تعتبر طريقة مريحة لأنك بتسجل الـ Service بشكل مباشر في المكان اللي هي متعرفة فيه، وغالباً بنستخدم providedIn: 'root' علشان تكون الخدمة متاحة للتطبيق كله من غير ما نضيفها في الـ Module بشكل صريح.

<div dir="auto" align="left">

```typescript
@Injectable({
  providedIn: "root",
})
export class ProductService {}
```

</div>
 ✨ده معناه إن الـ ProductService متاحة للتطبيق كله من غير ما تضيفها في الـ Providers بتاعة الـ Module.

### وظيفية الـ Injectable

دي Decorator لازم تضيفها على أي خدمة علشان Angular يعرف إنه يقدر يعمل Inject للخدمة دي في (components) اللي محتاجاها. لما تستخدم Injectable@، Angular بيدير العملية دي ويقدر يجيب الخدمات اللي Component محتاجها ويضيفها أوتوماتيكي.

</div>

## What are Angular Providers?

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
الـ Angular Provider هو زي تعليمات أو وصفة بنقول فيها للـ Angular إزاي ينشئ  (Object) معين بناءً على حاجة اسمها Token. الفكرة كلها إن كل خدمة (Service) أو Dependency عايز تستدعيها في التطبيق بتحتاج تكون متسجلة في الـ Providers Array عشان الـ Angular يعرف يجيبها ويستخدمها لما تحتاجها في الكود.

### إزاي بنسجل الـ Providers؟

في طريقتين أساسيين علشان تسجل الخدمة في الـ Providers:

إنك تضيفها مباشرة في الـ Providers array سواء في NgModule@ لو عايزها على مستوى التطبيق كله، أو في Component@ أو Directive@ لو عايزها على مستوى مكون معين.

أو إنك تستخدم خاصية providedIn في الـ Injectable@ decorator. ودي طريقة تانية أسهل شوية لأنك بتقول للـ Angular إن الخدمة دي متاحة على مستوى التطبيق كله (Root) أو على مستوى موديول معين (Module).

### الفكرة بتمشي إزاي؟

لما الـ Angular بيشغل التطبيق، بيعمل حاجة اسمها Injector. الـ Injector ده مسؤول عن إنه يجيبلك الكائنات أو الـ dependencies اللي محتاجها الكود. فيه Root-level Injector بيبقى شغال على مستوى التطبيق كله، وبيبقى فيه Module-level Injector لو عندك Lazy Loaded Modules (ودي أجزاء من التطبيق بتتحمل بس لما تحتاجها).

</div>

## Types of Providers in Angular?

[⬆️ Back to Top](#top2)

### The Angular Dependency Injection provides several types of providers.

1- Class Provider : useClass
2- Value Provider: useValue
3- Factory Provider: useFactory
4- Aliased Class Provider: useExisting

<div dir="auto" align="right">

### 1- الClass Provider - useClass

يعني إيه؟: لما بنستخدم الـ useClass بنقول للـ Angular يعمل إنستنس جديدة (instance) من كلاس معين، وده زي ما بنستخدم الكلمة المفتاحية new لإنشاء كائن من الكلاس.
إزاي نستخدمها؟: لو عندك كلاس اسمه ProductService وعايز توفر إنستنس منه في التطبيق:

<div dir="auto" align="left">

```typescript
providers: [{ provide: ProductService, useClass: ProductService }];
```

</div>
في الكود ده، ProductService هو الـ token اللي بيستخدمه الـ Angular علشان يتعرف على الخدمة اللي محتاج يوفرها. والـ useClass بتخلي الـ Injector يعمل instance جديدة من ProductService.

### فايدتها إيه؟

فايدة الطريقة دي إنك تقدر بسهولة تبدل الكلاس الأصلي بكلاس تاني (مثلاً كلاس فيك للاختبارات). ده مفيد جدًا في unit testing لما مش عايز تتعامل مع البيانات أو العمليات الحقيقية، وبدلها بتستخدم بيانات وهمية.

<div dir="auto" align="left">

```typescript
providers: [{ provide: ProductService, useClass: FakeProductService }];
```

</div>

### 2 - الValue Provider - useValue

يعني إيه؟: هنا بنستخدم useValue عشان نوفر قيمة ثابتة مش خدمة أو كلاس، يعني مثلاً لو عايز توفر URL أو إعدادات عامة.

<div dir="auto" align="left">

```typescript
providers: [{ provide: "USE_FAKE", useValue: true }];
```

</div>
ولما تيجي تستدعيها في الـ Component
<div dir="auto" align="left">

```typescript
constructor(@Inject('USE_FAKE') public useFake: boolean) {}
```

</div>

### 3-الFactory Provider - useFactory

بنستخدم useFactory لما نحتاج نرجع قيمة أو object بعد تنفيذ function. يعني لو عايز ترجع قيمة بناءً على شرط معين.

<div dir="auto" align="left">

```typescript
providers: [{ provide: "GREETING", useFactory: () => "Hello World" }];
```

</div>
وتستدعيها بعدين:
<div dir="auto" align="left">

```typescript
constructor(@Inject('GREETING') public greetingFunc: any) {
  console.log(greetingFunc());
}
```

</div>
كرة الـ Factory إنك بتقدر تتحكم أكتر في اللي بيرجع من function بناءً على شروط معينة، ودي حاجة بنستخدمها كتير في حالة مثلاً الإعدادات اللي بتتغير حسب البيئة (production أو development).

### 4- الAliased Class Provider - useExisting

بنستخدم useExisting لما عايزين نوفر نفس الإنستنس بتاعت كلاس تاني، يعني بدل ما نعمل إنستنس جديدة، نستخدم إنستنس موجودة بالفعل.

<div dir="auto" align="left">

```typescript
providers: [{ provide: "ExistingService", useExisting: ProductService }];
```

</div>
كده بنستخدم نفس الإنستنس اللي اتعملت للـ ProductService تحت اسم جديد هو ExistingService.

✨ ببساطة، لما تيجي تستدعي الـ Service اللي استخدمت فيها useExisting، تقدر تستدعيها باستخدام الـ Token اللي حطيته في الـ provide.

<div dir="auto" align="left">

```typescript
constructor(@Inject('ExistingService') private productService: ProductService) {}
```

</div>
</div>

## How Dependency Injection and Resolution Work in Angular?

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
بص، في Angular بيشتغل بنظام حاجة اسمها Dependency Injection (DI)، واللي معناها باختصار إنك بدل ما تبني كل حاجة من الصفر في كل Component أو Service، Angular هو اللي بيوفر الحاجات اللي محتاجها (Dependencies) بشكل أوتوماتيكي عن طريق Injector.

### 1. Injector

الـ Injector ده هو المسئول إنه يجيب الـ Dependency اللي أي Component أو Service محتاجها. يعني لو عندك Service معينة وعايز تستخدمها في Component، مش هتعمل new بنفسك، لكن هتعتمد على الـ Injector إنه هو اللي يعملها لك.

### 2. Injector Tree (شجرة الـ Injectors)

في الحقيقة، Angular مش بيعمل Injector واحد بس. لأ، هو بيعمل Injector Tree (شجرتين في الحقيقة، واحدة للـ Modules وواحدة للـ Elements زي Components وDirectives).

- الModule Injector Tree: الشجرة دي خاصة بالـ Modules زي Root Module أو أي Lazy Loaded Module.
- الElement Injector Tree: دي خاصة بالـ Components والـ Directives اللي بتتعامل مع الـ DOM.

### 3. Module Injector Tree

الModule Injector بيتبني لما التطبيق بيبدأ، وبيحتوي على كل الـ Providers اللي أنت معرفها في الـ Module.
فيه طريقتين عشان تسجل الـ Providers على مستوى الـ Module
تحطهم في providers بتاع الـ NgModule@
تستخدم providedIn: 'root' في الـ Injectable@ عشان تعمل الـ Service متاحة في كل التطبيق.

### 4. Dependency Resolution

لما الـ Component يطلب Service معينة، Angular بيشوف الأول الـ Injector بتاع الـ Component نفسه، لو لقاها بيجبها، لو ملقهاش، بيطلع لفوق للـ Injectors الأعلى (زي بتاع الـ Module أو حتى الـ Root Injector) لحد ما يلاقي الـ Dependency المطلوبة. لو ملقهاش خالص، بيرجع Error.

### 5. Null Injector

في أعلى شجرة الـ Injectors، Angular بيعمل حاجة اسمها Null Injector، اللي دايماً بترمي Error لو حاولت تجيب منها حاجة مش موجودة، إلا لو كنت حاطط عليها الـ Optional@ عشان ماترميش Error.

### مثال على الـ Hierarchical Dependency Injection

مثال بسيط لو عندك Module معين بيستخدم Service، تقدر تحط الـ Service دي في providers بتاع الـ NgModul@، ساعتها الـ Injector اللي خاص بالـ Module ده بس هو اللي هيجيب الـ Service. ولو عايزها متاحة في كل التطبيق، تحط providedIn: 'root

![Hierarchical Dependency Injection](https://www.tektutorialshub.com/wp-content/uploads/2021/05/Module-Injector-Tree-Hierarchy-2.png)

</div>

## Element Injector Tree in Angular

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">

ببساطة، شجرة Element Injector في Angular بتُستخدم علشان توفر الـ services على مستوى العناصر زي Components و Directives. لما التطبيق بيبدأ، Angular بيبني شجرة Injectors دي بحيث كل عنصر في التطبيق سواء كان Component أو Directive يكون ليه Injector خاص بيه.

أول Injector بيتعمل هو بتاع Root Component، وده اللي بيبقى بمثابة الأب لكل العناصر اللي بعد كده. كل عنصر في التطبيق ممكن يبقى له عناصر تانية بداخله، وده بيخلق شجرة من العناصر وكل عنصر ليه Injector خاص بيه.

ببساطة، كل Injector في Angular بياخد الـ Providers من الـ Component@ أو Directive@ اللي بيكون مربوط بيه. بمعنى، لو عندك Component معين فيه قائمة من services أو dependencies محتاجة تكون متاحة، Angular بيستخدم الـ providers الموجودة في الـ Component@ علشان يوفرها للـ Injector.

لكن لو الـ Component@ أو Directive@ مش بيحتوي على أي Providers (يعني القائمة فاضية)، Angular بيعمل Injector، لكنه بيبقى فاضي، ومش بيحتوي على أي خدمات أو services متاحة للعنصر ده.

لما ينتهي عمر العنصر أو الـ component (يعني لما يتم إزالته من الـ DOM أو يخلص دورة حياته)، Angular بيتخلص من الـ Injector اللي مرتبط بيه علشان يحرر الذاكرة ويحسن الأداء.

### الهرمية بتاعة Element Injector Tree

لو عندك Component بيطلب Service معينة في الـ constructor، Angular بيبدأ يدور على الـ dependency دي في الـ Injector اللي خاص بالـ component نفسه. لو لقاها، بيحقنها جوه الـ Component. لو مش لقاها، بينادي على الأب بتاع الـ Component ويدور في الـ Injector بتاعه.

لو في النهاية مش لقى الـ dependency في شجرة الـ Element Injector كلها، يبدأ يدور في شجرة الـ Module Injector، والبحث يبدأ من الـ Root Module Injector (أو Lazy Loaded Module Injector لو بتستخدم lazy loading).

</div>

## ProvidedIn root, any, and platform in Angular

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">

### 1. ال providedIn: 'root'

لو عندك (Service) وعايزها تكون متاحة لكل التطبيق كله (بما في ذلك كل Components والكود اللي بتم تحميله سواء Lazy أو Eager)، تقدر تستخدم providedIn: 'root'. ده معناه إن Service دي هتكون singleton يعني موجودة بنسخة واحدة في كل التطبيق.
الفكرة هنا إن لو Service دي متمتش استخدامها في أي مكان في التطبيق، Angular هيشيلها من الملف النهائي عشان يحافظ على حجم التطبيق خفيف.

### 2- Lazy Loaded Service

لو عايز Service تكون متاحة بس في module معين ومش على مستوى التطبيق بالكامل، ممكن تضيفها في الـ providers بتاع الموديول ده فقط. في الحالة دي، Service هتكون singleton بس جوه الموديول ده، يعني مش هتتشارك مع باقي الموديولات أو التطبيق.

### ماذا يحدث لو استخدمت الطريقتين؟

لو قمت بتسجيل Service باستخدام الطريقتين (يعني حطيت providedIn: 'root' وفي نفس الوقت أضفتها في الـ providers لموديول معين):

هتكون singleton Service على مستوى التطبيق كله، ما عدا في الموديول اللي سجلتها فيه في الـ providers، لأنه هيكون عنده نسخة جديدة منفصلة عن باقي التطبيق. ده بيدي كل موديول القدرة إنه يستخدم نسخة خاصة بيه من Service من غير ما يشاركها مع موديولات تانية.

### 3. providedIn: 'any'

ده بقى مختلف شوية. لو عندك أكتر من lazy-loaded module وكل موديول محتاج نسخة خاصة بيه من الخدمة، تستخدم providedIn: 'any'. يعني كل lazy-loaded module هيكون عنده نسخة جديدة من الخدمة دي.
لكن eager-loaded modules (اللي بتتحمل في أول التطبيق) هيفضلوا يستخدموا النسخة اللي في Root Module Injector زي العادي.

### 4. providedIn: 'platform'

دي بقى للناس اللي بتعمل حاجات أكتر تعقيدًا. لما عندك أكتر من تطبيق Angular شغالين على نفس الصفحة، ومحتاج خدمة تكون مشتركة بينهم كلهم، تستخدم providedIn: 'platform'.
الـ Platform Injector هو الأب بتاع Root Module Injector، يعني أي خدمة بتتحط هنا تبقى متاحة لكل التطبيقات اللي شغالة في الصفحة.
مفيد جدًا لما تكون بتستخدم حاجة زي Angular Elements عشان تشارك نفس الخدمة بين العناصر المختلفة اللي شغالة على نفس الصفحة.

</div>

## @Self, @SkipSelf, and @Optional Decorators in Angular?

[⬆️ Back to Top](#top2)

<div dir="auto" align="right">
في Angular، فيه ديكوراتورز معينة زي Self@، SkipSelf@، و Optional@ بتتحكم في إزاي Angular بيدور على الdependencies اللي بيحتاجها عشان يعمل Dependency Injection.

### 1- Self@

الديكوراتور ده بيقول لـ Angular يدور على الـ dependency اللي انت محتاجها فقط في المكان اللي انت حقنت فيه الـ dependency. بمعنى إن لو فيه component أو service معين وحقنت فيه dependency وكنت مستخدم Self@، Angular مش هيبص في الأماكن الأعلى (الـ parent injectors) عشان يجيب الـ dependency دي، لو مش لقاها في المكان المحدد، هيطلع error.

##### مثال: لو انت بتقول لـ Angular: "ادور على الـ Service دي في نفس الـ component ده، ومش عايزك تبص في أي مكان تاني."

<div dir="auto" align="left">

```typescript
constructor(@Self() private myService: MyService) { }
```

</div>
✨ لو ما لاقاش الـ MyService في نفس المكان ده، هيحصل error.

### 2. SkipSelf@

الديكوراتور ده بيعمل العكس. هو بيقول لـ Angular "أنا عايز الـ dependency دي، بس متدورش عليها في نفس الـ injector اللي فيه الـ component ده، دور عليها في الـ parent injectors بس." يعني بيتخطى (skip) المكان الحالي ويروح يدور في الأماكن الأعلى (الـ parent injectors).

##### مثال: لو عايز تعتمد على service موجودة في مكان أعلى من الـ component اللي انت فيه، تقدر تستخدم SkipSelf@

<div dir="auto" align="left">

```typescript
constructor(@SkipSelf() private myService: MyService) { }
```

</div>
✨ هنا Angular هيبص في الـ parent injector ولو لقى الـ MyService هناك، هيحقنه، لو مش لاقيها في الـ parent برضه هيطلع error.

### 3.Optional@

الديكوراتور ده بيقول لـ Angular "لو لقيت الـ dependency اللي بطلبها، حقنها عادي، ولو ملقتهاش، متطلعش error." يعني ببساطة بـ Optional@، Angular بيعمل الموضوع ده اختياري، وبيسيب الـ dependency بـ null لو ملقهاش.

##### مثال: لو انت مش متأكد لو الـ MyService موجودة ولا لأ، بس مش عايز تطلع error لو مش موجودة، تقدر تستخدم Optional@

<div dir="auto" align="left">

```typescript
constructor(@Optional() private myService: MyService) { }
```

</div>
✨ في الحالة دي، لو Angular ملقاش الـ MyService، مش هيطلع error وهيخلي myService بـ null.

#### مثال توضيحي لكل الأنواع

<div dir="auto" align="left">

```typescript
constructor(
  @Self() private serviceA: ServiceA,  // لازم يلاقيها في نفس المكان
  @SkipSelf() private serviceB: ServiceB,  // متدورش عليها هنا، بس دور في اللي فوق
  @Optional() private serviceC: ServiceC  // لو ملقتهاش متطلعش error
) { }
```

</div>
</div>
<hr/>

## Explain RxJS Observable

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
  الـ Observable في RxJS هو طريقة لتبادل البيانات بين اللي بينتجها (الـ producer) واللي بيستخدمها (الـ consumer). تخيل إن فيه حد بيبعث لك بيانات، بس مش هتبعت لك غير لما تطلبها (ده نظام الـ pull)، أو ممكن البيانات تتبعت لك من غير ما تطلبها (ده نظام الـ push).

في الـ JavaScript العادي، أنت اللي بتطلب البيانات (ده زي الـ pull). لكن في الـ RxJS Observable، البيانات بتتبعت لك تلقائيًا أول ما تعمل subscribe للـ Observable (ده نظام الـ push).

في Angular، الـ Observable بتبدأ تشتغل لما تعملها subscribe، وبتقدر تعمل كده إما باستخدام subscribe مباشرةً أو باستخدام async pipe.

</div>

<hr/>

## What are RxJS operators?

[⬆️ Back to Top](#top3)

<div dir="auto" align='right'>
ببساطة RxJS operators هما functions بتساعدك في التعامل مع Observables وبتنقسم لنوعين:

### Pipeable Operators - 1

دي اللي بتشتغل مع Observable.pipe() وبتاخد observable كـ input وتطلع observable جديد. أمثلة عليها: map، switchMap، mergeMap، concatMap، takeUntil، retry، catchError، و throwError.

### Creation Operators - 2

دي اللي بنستخدمها كـ functions مستقلة عشان ننشئ observables. أمثلة عليها: of، from، interval، fromEvent، generate، و range.

</div>

<hr/>

## What is Observable.pipe() and how to use it?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
الـ pipe في RxJS هو اللي بنستخدمه عشان نمرر مجموعة من الـ pipeable operators، اللي بنقدر نستخدمها مع observables. يعني ببساطة، تقدر تحط أي عدد من العمليات (operators) جوه الـ pipe، وهيشتغلوا بالتسلسل. الفكرة إن الـ observable الأساسي بيتبعت لأول operator، والنتيجة بتاعت أول واحد بتتبعت للتاني، وهكذا.

<div dir="auto" align="left">

```typescript
of(101, 102)
  .pipe(
    delay(1000),
    map((num) => num * 2)
  )
  .subscribe((v) => console.log(v)); // 202, 204
```

</div>

في المثال ده، أول حاجة بنستخدم delay(1000) علشان نأخر التنفيذ ثانية (1000 ميلي ثانية).
بعد كده، بنستخدم map اللي بيضرب كل رقم في 2.
النتيجة هتكون: 202، 204 (يعني الأرقام اتضربت في 2 بعد التأخير).

الخلاصة:
الـ pipe بيسهل عليك تنفيذ عمليات متتابعة على البيانات اللي جاية من observable، وده بيديك تحكم أكبر في تعديل الداتا أو توقيتها أو التعامل مع الأخطاء.

</div>

<hr/>

## What is the difference between RxJS of and from?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
الفرق بين RxJS of و RxJS from ببساطة هو في نوع المدخلات اللي كل واحد فيهم بيتعامل معاها وطريقة تحويلهم لـ Observable

### of - 1

بتاخد مجموعة من القيم (زي "a" و "b" و "c") وتحولهم لـ observable sequence، يعني كل قيمة بتطلع لوحدها.

<div dir="auto" align="left">

```typescript
of("a", "b", "c").subscribe((e) => console.log(e));
```

</div>
في الحالة دي، كل حرف هيظهر في السطر على حدة.

### from - 2

بتاخد array أو حاجة شبهه (زي promise) وتحوّله لـ observable، يعني كل عنصر جوه الـ array بيتعامل معاه كجزء من الـ observable.

<div dir="auto" align="left">

```typescript
from(["a", "b", "c"]).subscribe((e) => console.log(e));
```

</div>
هنا، نفس القيم اللي كانت في الـ array (يعني "a", "b", "c") هتتعامل معاها كأن كل عنصر بيتطلع لوحده في الـ observable.

</div>

<hr/>

## Explain RxJS map operator?

[⬆️ Back to Top](#top3)

![ map ](https://rxjs.dev/assets/images/marble-diagrams/map.png)

<div dir="auto" align="right">
الـ map operator في RxJS ببساطة بيطبق function معينة على كل عنصر بيتم إصداره من الـ Observable. يعني كل عنصر بيعدي من المصدر، بيتم تطبيق الـ function عليه والنتيجة هي اللي بتطلع.

<div dir="auto" align="left">

```typescript
of(1, 2, 3, 4)
  .pipe(map((e) => e * e))
  .subscribe((output) => console.log(output));
```

</div>
في المثال ده:

عندنا observable بيرسل القيم (1, 2, 3, 4).
كل قيمة من القيم دي بتدخل في map، اللي بتضرب القيمة في نفسها (يعني بتربع القيمة).
بعد كده الـ observable الجديد اللي طالع بيرجع القيم: 1, 4, 9, 16.
يعني لما بنعمل subscribe على الـ observable الناتج، بنشوف القيم الجديدة اللي هي 1، 4، 9، و 16 في الـ console.

بكده تقدر تستخدم map علشان تعدل أو تعمل عمليات على البيانات اللي بتيجي من الـ observable الأصلي بطريقة بسيطة.

</div>

<hr/>

## Explain RxJS switchMap operator?

[⬆️ Back to Top](#top3)

![ switchMap ](https://rxjs.dev/assets/images/marble-diagrams/switchMap.png)

<div dir="auto" align="right">
الـ switchMap() بيحول observable لواحد تاني، وفي نفس الوقت بيكنسل الاشتراك اللي كان قبل كده. ده معناه إنه لو طلع observable جديد، الاشتراك القديم بيتلغي تلقائيًا. الميزة هنا إن الـ switchMap() بيحميك من تسريب الذاكرة وبيضمن إن آخر observable بس هو اللي شغال ومشترك فيه.

بس علشان كده، الـ switchMap() مش مناسب في السيناريوهات اللي محتاج فيها إن كل الاشتراكات تخلص للآخر، زي لما بتستخدمه مع طلبات HTTP اللي بتكتب في قاعدة البيانات زي (POST، PUT، PATCH، DELETE). في الحالات دي الأفضل إنك تستخدم mergeMap()، لأنه بيسمح لكل الاشتراكات تكمل بدون ما يوقف أي واحدة منهم.

### Some typical use cases for the switchMap() operator are

##### 1- Fetching Details from an API on a Routed Detail Screen

##### 2- Typeahead Search

## Detail screen with switchMap

<div dir="auto" align="left">

```typescript
@Component({
  selector: "my-car-brand-detail",
  standalone: true,
  imports: [CommonModule],
  providers: [CarBrandService],
  template: `
    Details:
    <ng-container *ngIf="carBrand$ | async as brand">
      <p>Brand ID:</p>
      <p>Brand Name:</p>
    </ng-container>
  `,
})
export class CarBrandDetailComponent {
  private readonly carBrandService = inject(CarBrandService);
  private readonly activatedRoute = inject(ActivatedRoute);

  // Listen for changes on the Router Params and map the params to an ID value
  private readonly id$ = this.activatedRoute.params.pipe(
    map((params) => params["id"])
  );

  // Every time the id$ changes, the carBand will be fetched
  public readonly carBrand$: Observable<CarBrand> = this.id$.pipe(
    switchMap(
      // SwitchMap returns an observable, in this case an Observable<CarBrand>
      (id) => this.carBrandService.getById(id)
    )
  );
}
```

</div>

## Typeahead with switchMap() and ReactiveForms

<div dir="auto" align="left">

```typescript
@Component({
  selector: "my-app",
  standalone: true,
  imports: [CommonModule, FormsModule, ReactiveFormsModule],
  providers: [CarService],
  template: `
    <input [formControl]="searchTermControl" type="text" />
    <ul>
      <li *ngFor="let brand of filteredCarBrands$ | async"></li>
    </ul>
  `,
})
export class AppComponent {
  private readonly carBrandService = inject(CarService);

  public readonly searchTermControl = new FormControl("");

  public readonly filteredCarBrands$: Observable<string[]> =
    // Every time the value changes of the fornControl this stream will be executed again
    this.searchTermControl.valueChanges.pipe(
      debounceTime(300), // Wait 300ms before searching
      switchMap((searchTerm) =>
        // Returns a list of Car Brands
        this.carBrandService.searchCarBrands(searchTerm)
      )
    );
}
```

</div>

## Typeahead search with switchMap() and BehaviorSubject

<div dir="auto" align="left">

```typescript
@Component({
  selector: "my-app",
  standalone: true,
  imports: [CommonModule, FormsModule],
  providers: [CarService],
  template: `
    <input
      [ngModel]="searchTerm$$.value"
      (ngModelChange)="searchTerm$$.next($event)"
      type="text"
    />
    <ul>
      <li *ngFor="let brand of filteredCarBrands$ | async"></li>
    </ul>
  `,
})
export class AppComponent {
  private readonly carBrandService = inject(CarService);

  public readonly searchTerm$$ = new BehaviorSubject("");
  private readonly searchTerm$ = this.searchTerm$$.asObservable();

  // Every time the searchTerm is changed then the carBrandService.searchCarBrands function is called
  public readonly filteredCarBrands$: Observable<string[]> =
    this.searchTerm$.pipe(
      debounceTime(300), // Wait 300ms before searching
      switchMap((searchTerm) =>
        // Returns a list of Car Brands
        this.carBrandService.searchCarBrands(searchTerm)
      )
    );
}
```

</div>

</div>

<hr/>

## Explain RxJS mergeMap operator?

[⬆️ Back to Top](#top3)

![ mergeMap ](https://rxjs.dev/assets/images/marble-diagrams/mergeMap.png)

<div dir="auto" align="right">
الـ mergeMap في RxJS هو operator بيستخدم في التعامل مع الـ observables، واللي بيعمله إنه بياخد كل element جاية من الـ observable الأولانية وبيعملها subscribe في observable تانية. يعني لو عندك observable بيطلع بيانات، لكل قيمة جاية ممكن تستدعي observable تانية، والـ mergeMap هيعمل merge لكل الـ observables اللي جوا بعض.

فايدته الأساسية إنه بيشتغل بشكل متوازي، يعني لو عندك مثلاً HTTP requests وكل واحدة محتاجة تطلع observable تانية عشان تعمل حاجة زي جلب بيانات، الـ mergeMap هيشغل كل الطلبات دي مع بعض من غير ما يستنى واحدة تخلص عشان يبدأ التانية.

### التعامل مع Multi HTTP requests

مثال على تنفيذ طلبات HTTP متعددة بشكل متوازي باستخدام mergeMap

<div dir="auto" align="left">

```typescript
import { fromEvent } from "rxjs";
import { mergeMap } from "rxjs/operators";
import { ajax } from "rxjs/ajax";

const button = document.getElementById("myButton");

fromEvent(button, "click")
  .pipe(mergeMap(() => ajax.getJSON("https://api.example.com/buttonData")))
  .subscribe((response) => {
    console.log("Button click data:", response);
  });
```

</div>

### ملحوظة

استخدم الmergeMap لو عند requests زي الPOST , DELETE الي لازم تكتمل بدون الغاء

</div>

<hr/>

## Explain RxJS concatMap operator?

[⬆️ Back to Top](#top3)

![ concatMap ](https://rxjs.dev/assets/images/marble-diagrams/concatMap.png)

<div dir="auto" align="right">
الـ concatMap في RxJS بيشتغل بطريقة مشابهة شوية لـ mergeMap، لكن الفرق الرئيسي بينهم هو في طريقة التعامل مع الـ observables اللي طالعة.

الـ concatMap بياخد كل قيمة جاية من الـ observable الأساسي وبيطلع منها observable جديد، بس هنا الـ observables اللي بيطلعها بتشتغل واحدة واحدة بالتتابع. يعني مش هيبدأ الـ observable التاني غير لما الأولاني يخلص. بمعنى آخر، هو بيعمل flattening للـ observables بس بشكل متسلسل بدل ما يكون كله شغال بالتوازي زي ما بيحصل في mergeMap.

<div dir="auto" align="left">

```typescript
of("Mohit", "Nilesh")
  .pipe(
    concatMap((se) =>
      of("Shree").pipe(
        delay(2000),
        map((e) => e + " " + se)
      )
    )
  )
  .subscribe((res) => console.log(res));
```

</div>

```typescript
 // the output.
(after 2 seconds)
Shree Mohit
(after 2 seconds)
Shree Nilesh
```

</div>

<hr/>

## Explain RxJS exhaustMap operator?

[⬆️ Back to Top](#top3)

![ exhaustMap ](https://rxjs.dev/assets/images/marble-diagrams/exhaustMap.png)

<div dir="auto" align="right">
ببساطة كده، exhaustMap بيشتغل بطريقة إنه مش بيهتم غير بالـobservable اللي شغال حاليًا. يعني لو حاجة جديدة جات (زي حدث أو كليك مثلاً) وهو لسه مشغول بحاجة تانية، مش هيبدأ الحاجة الجديدة غير لما يخلص اللي في إيده.

خلينا نقول إن عندك زرار في تطبيق بيفتح حاجة معينة، لو المستخدم ضغط بسرعة على الزرار أكتر من مرة، exhaustMap هيهتم بالضغطة الأولى بس، وهيتجاهل الباقي لحد ما الحاجة اللي بدأها أول مرة تخلص، وبعد كده يبدأ يستقبل حاجات جديدة.

ليه ده مفيد؟
لأنه بيساعد إنك تمنع طلبات كتير تشتغل في نفس الوقت، زي لما تضغط على زر تسجيل الدخول أكتر من مرة، ومش عايز تبعت بياناتك للسيرفر كل مرة غير لما الطلب الأولاني يخلص.

<div dir="auto" align="left">

```typescript
import { fromEvent } from "rxjs";
import { exhaustMap, interval, take } from "rxjs/operators";

const button = document.getElementById("myButton");
const clicks$ = fromEvent(button, "click");

clicks$
  .pipe(
    exhaustMap(() => {
      return interval(1000).pipe(take(3));
    })
  )
  .subscribe((val) => console.log(val));
```

</div>

هنا:

fromEvent بيتابع الكليكات اللي بتحصل على الزرار.
exhaustMap بيتأكد إن مفيش كليك جديد هيتم معالجته غير لما الطلب الحالي يخلص.
interval هنا مجرد مثال لعملية بتاخد شوية وقت (ممكن تعتبره طلب HTTP مثلاً).
كل ضغطة هتستنى لحد ما الكليك الأولاني يخلص قبل ما تقبل كليك جديد.

</div>

<hr/>

## How will you handle errors on observable using RxJS throwError?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
في RxJS، لو حصل خطأ أثناء تشغيل الـobservable، ممكن نستخدم throwError عشان نبعت الخطأ ده في الـstream ونتعامل معاه باستخدام الـcatchError أو الـretry operators.

<div dir="auto" align="left">

```typescript
import { of, throwError } from "rxjs";
import { catchError } from "rxjs/operators";

const myObservable = of("Data 1", "Data 2", "Data 3").pipe(
  throwError("Error occurred!"),
  catchError((error) => {
    return of("Default value");
  })
);

myObservable.subscribe(
  (data) => console.log("Data:", data),
  (error) => console.log("Error:", error),
  () => console.log("Complete")
);
```

</div>

throwError: لما يحصل خطأ، الـobservable هيعمل emit للخطأ ده.
catchError: بنستخدمه عشان نعمل handle للخطأ. في المثال ده، لو حصل خطأ، بنرجع observable تاني بقيمة بديلة (of('Default value')).
الـsubscribe: لو مفيش أخطاء، الـobserver هياخد الـdata اللي الـobservable بيعملها emit. ولو حصل خطأ هيتم الإمساك بيه في الـcatchError قبل ما يوصل للـsubscribe.

</div>

<hr/>

## Explain RxJS retry operator?

[⬆️ Back to Top](#top3)

![ retry ](https://rxjs.dev/assets/images/marble-diagrams/retry.png)

<div dir="auto" align="right">
في RxJS، الـretry هو operator بيُستخدم لما يحصل خطأ في الـobservable، ويسمح بإعادة محاولة تشغيل الـobservable تلقائيًا لعدد معين من المرات قبل ما يدي خطأ نهائي. الفكرة إنه لو عندك عملية ممكن تفشل (زي طلب HTTP)، الـretry بيساعد في إعادة المحاولة كذا مرة على أمل إن المشكلة تتحل، زي مشكلة مؤقتة في الشبكة.

### ازاي تستخدم retry

الـretry بياخد عدد من المرات اللي عايز تكرر فيها المحاولة لما يحصل خطأ. لو عدد المحاولات خلص ولسه فيه خطأ، الـobservable هيرجع خطأ عادي.

<div dir="auto" align="left">

```typescript
import { of, throwError } from "rxjs";
import { retry, catchError } from "rxjs/operators";

const myObservable = throwError("Error occurred!").pipe(
  retry(2),
  catchError((error) => {
    console.log("Failed after retries:", error);
    return of("Fallback value");
  })
);

myObservable.subscribe(
  (data) => console.log("Data:", data),
  (error) => console.log("Error:", error),
  () => console.log("Complete")
);
```

</div>

throwError: بنحاكي سيناريو إن الـobservable بيفشل وبيطلع خطأ.
retry(2): هنا بنقول للـobservable إنه يحاول مرتين لو حصل خطأ. يعني بعد أول خطأ، هيحاول مرة كمان، ولو فشل برضه، يحاول للمرة الأخيرة.
catchError: لو المحاولات كلها فشلت، بنمسك الخطأ ونتعامل معاه. في المثال، بنرجع قيمة افتراضية (Fallback value).
الـsubscribe: لو مفيش أخطاء، الـobservable هيعمل emit للـdata عادي، لكن لو كل المحاولات فشلت، هيوصل الخطأ للـcatchError وهنرجع القيمة البديلة.

سيناريوهات للاستخدام:
طلبات HTTP متكررة: ممكن تكون بتعمل طلب لـAPI وفيه مشاكل مؤقتة في الاتصال، زي انقطاع الشبكة. في الحالة دي، بدل ما الطلب يفشل مباشرة، ممكن تحاول كذا مرة باستخدام retry، وتدي فرصة إن المشكلة تتحل.

عمليات غير مستقرة: في عمليات زي الكتابة أو القراءة من قاعدة بيانات أو التعامل مع ملفات، ممكن يحصل فشل بسبب عوامل خارجية (زي مشكلة في التخزين المؤقت). باستخدام retry، تقدر تعيد المحاولة بدون الحاجة لتدخل المستخدم كل مرة.

<div dir="auto" align="left">

```typescript
import { ajax } from "rxjs/ajax";
import { catchError, retry } from "rxjs/operators";
import { of } from "rxjs";

// مثال لطلب HTTP
const apiCall$ = ajax.getJSON("https://api.example.com/data").pipe(
  // هنحاول إعادة المحاولة 3 مرات لو فشل
  retry(3),
  catchError((error) => {
    console.log("Request failed after retries:", error);
    return of({ error: "Failed to fetch data", data: [] });
  })
);

apiCall$.subscribe(
  (response) => console.log("API Response:", response),
  (error) => console.log("Error:", error),
  () => console.log("Complete")
);
```

</div>

retry(3): بنطلب من RxJS إعادة المحاولة 3 مرات لو حصل فشل في طلب الـAPI.
catchError: لو كل المحاولات فشلت، بنعمل catch للخطأ ونتعامل معاه، مثلاً نرجع بيانات افتراضية بدل ما نوقف التطبيق.
الـretry بيكون مفيد في الحالات اللي بتحصل فيها أخطاء غير متوقعة أو مؤقتة، وبيسمح للتطبيق يكون أكثر مرونة في التعامل مع الأخطاء بدون الحاجة لتدخل المستخدم في كل مرة

</div>

<hr/>

## Explain RxJS filter operator?

[⬆️ Back to Top](#top3)

![ filter ](https://rxjs.dev/assets/images/marble-diagrams/filter.png)

<div dir="auto" align="right">
في RxJS، الـfilter هو operator بنستخدمه عشان نعمل "فلترة" للـvalues اللي الـobservable بيعمل لها emit. بمعنى تاني، هو بيشغل callback function على كل قيمة، ولو الشرط اللي في الـcallback اتحقق، بيمرر القيمة دي، ولو لأ، بيتجاهلها.

### ازاي تستخدم filter

الـfilter بياخد كل قيمة جاية من الـobservable ويشوف لو القيمة دي بتوافق الشرط اللي في الـcallback.
لو القيمة مطابقة للشرط، بتكمل في الـobservable stream، ولو لأ، بتتفلتر وتتجاهل.

<div dir="auto" align="left">

```typescript
import { from } from "rxjs";
import { filter } from "rxjs/operators";

// observable بيمثل مجموعة من الأرقام
const numbers$ = from([1, 2, 3, 4, 5, 6, 7, 8, 9]);

// بنستخدم filter عشان نخلي بس الأرقام الزوجية تعدي
const evenNumbers$ = numbers$.pipe(
  filter((num) => num % 2 === 0) // هنا الشرط إن الرقم لازم يكون زوجي
);

evenNumbers$.subscribe(
  (value) => console.log("Even number:", value),
  (error) => console.log("Error:", error),
  () => console.log("Complete")
);
```

</div>

### الاستخدام

فلترة الأحداث: مثلاً، في حالة استماعك لأحداث معينة (زي ضغطات المستخدم على زر معين)، ممكن تستخدم filter عشان تتعامل بس مع نوع معين من الأحداث (زي لو المستخدم ضغط على زرار معين في الـUI).

طلبات الـHTTP: لو عندك استجابة API وبيجيلك فيها بيانات كتيرة، ممكن تستخدم filter عشان تمرر فقط القيم اللي تحقق شروط معينة (مثلاً، طلبات فيها status معين أو بيانات بنطاق معين).

<div dir="auto" align="left">

```typescript
import { fromEvent } from "rxjs";
import { filter } from "rxjs/operators";

const button = document.getElementById("myButton");
const clicks$ = fromEvent(button, "click");

// بنستخدم filter عشان نتعامل بس مع الكليكات اللي بتحصل في الجانب الأيسر من الشاشة
clicks$
  .pipe(filter((event: MouseEvent) => event.clientX < window.innerWidth / 2))
  .subscribe((event) => console.log("Clicked on the left side!", event));
```

</div>

fromEvent: بنعمل observable للضغطات على زرار معين.
filter: هنا بنفلتر الأحداث ونتعامل بس مع الضغطات اللي حصلت في النصف الأيسر من الشاشة (على أساس إن قيمة clientX أقل من نصف عرض الشاشة).

</div>

<hr/>

## Explain RxJS tap operator?

[⬆️ Back to Top](#top3)

![ tap ](https://rxjs.dev/assets/images/marble-diagrams/tap.png)

<div dir="auto" align="right">
في RxJS، الـtap هو operator بيُستخدم عشان تنفذ side effects على الـobservable، من غير ما تغير أو تعدل على الـvalues اللي بتخرج منه. هو بيكون مفيد لما تحتاج تطبع القيم في الـconsole، أو تعمل logging، أو أي عمليات أخرى أثناء مرور البيانات في الـstream، بس من غير ما تتدخل في البيانات نفسها.

### إزاي بيشتغل الـtap؟

الـtap بياخد function بتتنفذ لكل قيمة بتعدي في الـobservable.
القيم بتعدي بدون أي تعديل، فالـtap مش بيغير الـstream، لكنه بيسمح لك تعمل شيء إضافي أثناء مرور البيانات.

<div dir="auto" align="left">

```typescript
import { of } from "rxjs";
import { tap, map } from "rxjs/operators";

const numbers$ = of(1, 2, 3, 4, 5).pipe(
  tap((value) => console.log("Before map:", value)),
  map((value) => value * 10),
  tap((value) => console.log("After map:", value))
);

numbers$.subscribe(
  (value) => console.log("Final value:", value),
  (error) => console.log("Error:", error),
  () => console.log("Complete")
);
```

</div>

### فايدة الـtap

Logging: لو عايز تتابع القيم اللي بتعدي في الـobservable لأي سبب، زي الـdebugging.
Side effects: لو محتاج تعمل أي عملية أثناء مرور البيانات من غير ما تعدل على القيم. مثال على ده: تحديث UI، تسجيل أحداث، أو تعديل بيانات في مكان تاني بناءً على القيم اللي بتعدي.

</div>

<hr/>

## Explain RxJS takeUntil operator?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
في RxJS، الـtakeUntil هو operator بيستخدم عشان يوقف الـobservable عن إصدار القيم (emit) لما observable تاني يعمل emit. بمعنى تاني، الـtakeUntil بيمسك الـobservable الأصلي وبيخليه شغال لحد ما observable معين (اللي بنسميه notifier) يصدر قيمة، وبعدين يوقف الـobservable الأصلي عن العمل.

### إزاي بيشتغل الـtakeUntil؟

عندك observable رئيسي بيرسل قيم (مثلاً، تدفق للأرقام، أو استجابة لأحداث).
وعندك observable تاني بنسميه notifier، وده مجرد observable بيتراقب لحد ما بيرسل أي قيمة.
بمجرد ما الـnotifier بيرسل أول قيمة، الـobservable الرئيسي بيتوقف عن ارسال أي قيم جديدة.

### من اكتر استخدماته اننا بنستخدمه في الdestroy

<div dir="auto" align="left">

```typescript
import { Component, OnInit, OnDestroy } from "@angular/core";
import { Subject } from "rxjs";
import { takeUntil } from "rxjs/operators";

@Component({
  selector: "app-my-component",
  templateUrl: "./my-component.component.html",
  styleUrls: ["./my-component.component.css"],
})
export class MyComponent implements OnInit, OnDestroy {
  // الـnotifier اللي هيشغل takeUntil
  private componentDestroyed: Subject<void> = new Subject<void>();

  constructor() {}

  ngOnInit() {
    // Example: لو عندك Observable مثلاً بيسمع للأحداث أو بيطلب بيانات
    this.someObservable()
      .pipe(
        takeUntil(this.componentDestroyed) // هيوقف الـObservable لما الـcomponent يتدمر
      )
      .subscribe((data) => {
        console.log("Data received:", data);
      });
  }

  someObservable() {
    // ده الـObservable اللي هيشترك فيه الـcomponent (مجرد مثال)
    return of("Some data");
  }

  ngOnDestroy() {
    // هنا بنعمل emit للقيمة عشان نوقف الـObservables
    this.componentDestroyed.next();
    this.componentDestroyed.complete(); // عشان نضمن إن الـSubject مش هيستخدم تاني
  }
}
```

</div>

### ليه بنستخدم takeUntil بالطريقة دي؟

إدارة الاشتراكات: الـtakeUntil بيضمن إن أي اشتراكات للـobservables بتتوقف تلقائيًا لما الـcomponent يتدمر، وده بيساعد على عدم تسرب الذاكرة (memory leaks).

مرونة: الطريقة دي سهلة وبتشتغل مع أي observable في الـcomponent سواء كان HTTP request، أو WebSocket، أو أي نوع تاني من الـobservables.

باستخدام takeUntil مع الـSubject<void>، بتقدر تضمن إن أي اشتراكات بتتوقف بطريقة منظمة وفعالة لما الـcomponent يخرج من الـDOM.

</div>

<hr/>

## Explain RxJS debounceTime operator?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
هو واحد من أقوى الـoperators في RxJS وبيفيد بشكل كبير لما بنحتاج نتعامل مع سلسلة من القيم اللي بتتبع بعضها بسرعة، زي في حالة البحث اللحظي أو الحفظ التلقائي. الـdebounceTime بيسمح لنا نفلتر القيم اللي بتتبع بشكل سريع من الـobservable، ونحافظ بس على القيمة الأخيرة بعد فترة معينة من الزمن، وده مفيد لما ما نكونش محتاجين نتعامل مع كل قيمة بتطلع.

### إزاي بيشتغل الـdebounceTime

تأخير القيم: أول ما تيجي قيمة من الـobservable، الـdebounceTime بيبدأ يعد الزمن المحدد (مثلاً 300 مللي ثانية).
إعادة ضبط المؤقت: لو حصلت قيمة جديدة قبل ما الزمن المحدد ينتهي، المؤقت بيبدأ يعد من الأول تاني.
القيمة الأخيرة فقط: لما الزمن المحدد ينتهي ومافيش قيم جديدة جات، القيمة الأخيرة هي اللي بتعدي.

### Basic Usage

<div dir="auto" align="left">

```typescript
const result = fromEvent(document, "click").pipe(
  // Click event is delayed for 1000ms or 1s
  // It emits the most recent click event, even after burst clicking
  debounceTime(1000)
);

result.subscribe((value) => console.log(value));
```

</div>

### Real-time search with debounceTime

لما المستخدم يكتب في خانة البحث، بنقدر نستخدم debounceTime عشان نمنع إرسال طلب للسيرفر مع كل ضغطة على الكيبورد. بدال ما نبعت طلب بعد كل حرف، بنستنى فترة قصيرة قبل ما نبعته فعليًا.

<div dir="auto" align="left">

```typescript
@Component({
  ...
  template: `
  <input [formControl]="searchBar" type="text">
  `,
})
export class AppComponent {
  public readonly searchBar = new FormControl();

  public readonly searchResults$ = this.searchBar.valueChanges.pipe(
    debounceTime(1000), // Waits for 1000ms or 1s before emitting
    distinctUntilChanged() // doesn't emit if current value = previous value
  );

  constructor() {
    this.searchResults$.subscribe((query) => {
      console.log(query);
    });
  }
}
```

</div>

### Autosave with debounceTime

<div dir="auto" align="left">

```typescript
@Component({
  ...
  template: `
    <form [formGroup]="form" (ngSubmit)="save()">
        <input type="text" formControlName="firstName">
        <input type="text" formControlName="lastName">
        <button type="submit">Save</button>
    </form>
  `,
})
export class UserFormComponent implements OnInit {
  ...

  public readonly form = this.fb.group(...);

  ngOnInit() {
    this.form.valueChanges
      // Wait for 500ms after each keystroke before saving the user
      .pipe(debounceTime(500))
      .subscribe((user: User) => {
        this.userService.saveUser(user);
      });
  }

  ...
}
```

</div>

### Conclusion

الـdebounceTime هو واحد من أفضل الـoperators في RxJS لما بتتعامل مع سلاسل متتابعة من القيم بسرعة، وبيساعد في تحسين الأداء وتجربة المستخدم عن طريق تقليل الطلبات أو الاستجابات اللي ممكن تكون غير ضرورية.

</div>

<hr/>

## Explain RxJS combineLatestWith operator?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
الـcombineLatest هو operator بيجمع أكتر من observable في واحد، وبيعمل emit للقيم بتاعته كل ما واحد منهم يغير القيم بتاعته. ده بيخليه operator قوي جدًا، لكن فيه شوية حاجات لازم ناخد بالنا منها لما نستخدمه.

### إزاي الـcombineLatest بيشتغل:

الـcombineLatest بياخد array من الـobservables كمصدر، وبيطلع observable جديد بيحسب بناءً على أحدث القيم من كل observable مصدر. الموضوع باين إنه بسيط، لكن فيه شوية حاجات لازم نكون عارفينها:

كل الـobservables اللي في المصدر لازم يعملوا emit مرة على الأقل قبل ما الـcombineLatest يبدأ يطلع بيانات.
كل مرة observable من المصادر يعمل emit لقيمة جديدة، الـcombineLatest بيحسب القيمة من الأول. وده ممكن يخلي الـobservable يطلع بيانات كتير بسرعة، ودي حاجة لازم نخلي بالنا منها.
في أغلب الأوقات، هتحتاج تستخدم الـcombineLatest مع Observables طويلة المدى (long-lived observables).

### Usage

ممكن نعمل فلتر متعدد باستخدام combineLatest في Angular لما يكون عندنا أكتر من مصدر للفلترة، زي فلترة على اسم، تاريخ، وكاتيجوري مثلاً. باستخدام combineLatest، بنقدر ندمج الفلاتر دي كلها عشان نعمل الفلترة المطلوبة.

خلينا نشوف مثال عملي على عمل فلتر متعدد باستخدام combineLatest.

خطوات:
هنفترض إن عندنا Array من العناصر اللي محتاجين نفلترها.
هنستخدم أكتر من FormControl عشان نتحكم في الفلاتر.
هنستخدم combineLatest عشان ندمج القيم من كل فلتر ونعرض النتيجة النهائية.

<div dir="auto" align="left">

```typescript
import { Component, OnInit } from "@angular/core";
import { FormControl } from "@angular/forms";
import { combineLatest, of } from "rxjs";
import { map, startWith } from "rxjs/operators";

@Component({
  selector: "app-multi-filter",
  template: `
    <input [formControl]="nameFilter" placeholder="Filter by name" />
    <input [formControl]="categoryFilter" placeholder="Filter by category" />
    <input
      type="date"
      [formControl]="dateFilter"
      placeholder="Filter by date"
    />

    <ul>
      <li *ngFor="let item of filteredItems$ | async">
        {{ item.name }} - {{ item.category }} - {{ item.date }}
      </li>
    </ul>
  `,
})
export class MultiFilterComponent implements OnInit {
  // الفلاتر
  nameFilter = new FormControl("");
  categoryFilter = new FormControl("");
  dateFilter = new FormControl("");

  // قائمة العناصر اللي هنفلترها
  items = [
    { name: "Item 1", category: "A", date: "2023-01-01" },
    { name: "Item 2", category: "B", date: "2023-01-02" },
    { name: "Item 3", category: "A", date: "2023-01-03" },
    { name: "Item 4", category: "C", date: "2023-01-04" },
  ];

  // الـObservable اللي هيحتوي على العناصر المفلترة
  filteredItems$ = combineLatest([
    this.nameFilter.valueChanges.pipe(startWith("")),
    this.categoryFilter.valueChanges.pipe(startWith("")),
    this.dateFilter.valueChanges.pipe(startWith("")),
  ]).pipe(
    map(([name, category, date]) => {
      return this.items.filter(
        (item) =>
          item.name.toLowerCase().includes(name.toLowerCase()) &&
          item.category.toLowerCase().includes(category.toLowerCase()) &&
          item.date.includes(date)
      );
    })
  );

  ngOnInit() {}
}
```

</div>
</div>

<hr/>

## Explain RxJS fromEvent operator?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
في RxJS، الـfromEvent هو operator بنستخدمه عشان نعمل "observable" من الأحداث اللي بتحصل في الـDOM (أو أي مصدر أحداث تاني). بعبارة تانية، بنقدر نسمع لأي أحداث زي الكليكات، ضغطات الكيبورد، تحريك الماوس، وغيرها، ونتعامل معاها زي أي observable.

### إزاي بيشتغل الـfromEvent؟

بنمرر له العنصر اللي عايزين نسمع منه الأحداث (زي زرار أو صفحة كاملة).
بنحدد نوع الحدث اللي عايزين نسمعه (زي 'click'، 'keyup'، 'mousemove'، إلخ).
بعد كده بنستخدم الـobservable الناتج عشان نعمل اشتراك (subscription) ونتعامل مع الحدث.

<div dir="auto" align="left">

```typescript
import { fromEvent } from "rxjs";
import { filter } from "rxjs/operators";

const button = document.getElementById("myButton");

const clicks$ = fromEvent(button, "click").pipe(
  filter((event: MouseEvent) => event.clientX < window.innerWidth / 2) // نتعامل مع الكليكات في النصف الأيسر من الشاشة فقط
);

clicks$.subscribe((event) => {
  console.log("Clicked on the left side!", event);
});
```

</div>

</div>

<hr/>

## What is the difference between Subject, BehaviorSubject, ReplaySubject, and AsyncSubject in RxJS? How do they differ in terms of behavior and use cases?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
الفرق بين Subject و BehaviorSubject و ReplaySubject و AsyncSubject في RxJS
كل واحد من هذه الأنواع له سلوك خاص في التعامل مع observables والبيانات اللي يتم بثها للمشتركين (subscribers). خلينا نشرح كل واحد بالتفصيل، مع ذكر الفروق بينهم في السلوك والاستخدامات.

### 1. Subject

Subject هو observable عادي، لكن مع ميزات إضافية. يمكنه أن يستقبل بيانات ويصدرها، ويستطيع أكثر من subscriber الاشتراك فيه.
لا يحتفظ بأي بيانات سابقة: لو اشتركت في الـSubject بعد ما أرسل بيانات بالفعل، لن تتلقى البيانات السابقة، وستبدأ في تلقي القيم الجديدة فقط.

### السلوك:

أي مشترك جديد يبدأ في استقبال البيانات من اللحظة اللي اشترك فيها فقط، ولا يتلقى أي قيم سابقة.

### الاستخدامات:

مناسب للبث المباشر (real-time broadcasting) حيث لا نحتاج للاحتفاظ بالبيانات السابقة.

<div dir="auto" align="left">

```typescript
import { Subject } from "rxjs";

const subject = new Subject();

subject.subscribe((value) => console.log("Subscriber 1:", value));

subject.next(1); // Subscriber 1: 1
subject.next(2); // Subscriber 1: 2

subject.subscribe((value) => console.log("Subscriber 2:", value));

subject.next(3); // Subscriber 1: 3, Subscriber 2: 3
```

</div>

💡**Hint**: المشترك الأول يتلقى جميع القيم، لكن المشترك الثاني يتلقى فقط القيم الجديدة التي تم إرسالها بعد الاشتراك.

### 2. BehaviorSubject

BehaviorSubject هو نوع خاص من الـSubject يحتفظ دائمًا بآخر قيمة تم إصدارها.
عندما يشترك أي subscriber جديد، يستلم فورًا آخر قيمة تم بثها حتى لو تم الاشتراك بعد إرسال هذه القيمة.

### السلوك:

كل مشترك جديد يستلم آخر قيمة تم إصدارها، ثم يتلقى التحديثات الجديدة.

### الاستخدامات:

مفيد عندما تحتاج أن يحصل المشترك الجديد على آخر حالة أو آخر قيمة تم إصدارها بالفعل (مثل تحديث حالة المستخدم، أو تحميل بيانات التطبيق).

<div dir="auto" align="left">

```typescript
import { BehaviorSubject } from "rxjs";

const behaviorSubject = new BehaviorSubject(0); // القيمة الافتراضية هي 0

behaviorSubject.subscribe((value) => console.log("Subscriber 1:", value));

behaviorSubject.next(1); // Subscriber 1: 1
behaviorSubject.next(2); // Subscriber 1: 2

behaviorSubject.subscribe((value) => console.log("Subscriber 2:", value)); // Subscriber 2: 2

behaviorSubject.next(3); // Subscriber 1: 3, Subscriber 2: 3
```

</div>

💡**Hint** المشترك الثاني استلم القيمة الأخيرة (2) فور اشتراكه، ثم استلم القيمة الجديدة التي أرسلت بعد ذلك (3).

### 3. ReplaySubject

ReplaySubject هو نوع آخر من Subjects يمكنه أن يحتفظ بعدد معين من القيم السابقة (أو حتى كل القيم) ويعيد بثها لأي مشترك جديد عند الاشتراك.
يمكن تحديد عدد القيم التي يتم إعادة بثها للمشتركين الجدد، مثل آخر قيمة أو آخر قيمتين أو أكثر.

### السلوك:

أي مشترك جديد يتلقى عددًا معينًا من القيم السابقة (يمكن تحديد العدد)، ثم يبدأ في تلقي التحديثات الجديدة.

### الاستخدامات:

مفيد في التطبيقات التي تحتاج إلى إعادة تشغيل التاريخ (history replay) لمشتركين جدد، مثل تسجيل النشاطات أو الأحداث السابقة.

<div dir="auto" align="left">

```typescript
import { ReplaySubject } from "rxjs";

const replaySubject = new ReplaySubject(2); // يحتفظ بآخر قيمتين

replaySubject.next(1);
replaySubject.next(2);
replaySubject.next(3);

replaySubject.subscribe((value) => console.log("Subscriber 1:", value)); // Subscriber 1: 2, 3

replaySubject.next(4); // Subscriber 1: 4

replaySubject.subscribe((value) => console.log("Subscriber 2:", value)); // Subscriber 2: 3, 4
3;
```

</div>

💡 **Hint**: المشترك الأول استلم القيمتين الأخيرتين (2 و 3)، بينما المشترك الثاني استلم (3 و 4) لأنه اشترك بعد إرسال القيم.

### 4. AsyncSubject

AsyncSubject هو نوع من الـSubject لا يصدر أي قيم للمشتركين إلا بعد اكتمال الـobservable، وعندها يقوم بإرسال آخر قيمة فقط تم بثها قبل الاكتمال لجميع المشتركين.
لا يصدر أي شيء حتى يتم استدعاء complete

### السلوك:

المشتركين يستلمون آخر قيمة فقط عندما يتم استدعاء complete

### الاستخدامات:

يستخدم عندما تحتاج إلى إصدار آخر قيمة فقط عند انتهاء العمل، مثل استرجاع بيانات بعد إتمام عملية معقدة أو عند اكتمال عملية حسابية.

<div dir="auto" align="left">

```typescript
import { AsyncSubject } from "rxjs";

const asyncSubject = new AsyncSubject();

asyncSubject.subscribe((value) => console.log("Subscriber 1:", value));

asyncSubject.next(1);
asyncSubject.next(2);
asyncSubject.next(3);

asyncSubject.subscribe((value) => console.log("Subscriber 2:", value));

asyncSubject.next(4);
asyncSubject.complete(); // عند الاكتمال، يتم إرسال آخر قيمة

// Subscriber 1: 4
// Subscriber 2: 4
```

</div>

💡 **Hint** : هنا، المشتركين الاثنين استلموا فقط القيمة الأخيرة (4) بعد اكتمال الـobservable.

### متى تستخدم كل نوع؟

Subject: لما تكون مش محتاج تحتفظ بأي بيانات سابقة، وعايز تبث القيم الجديدة فقط للمشتركين الحاليين.
BehaviorSubject: لما تحتاج أن يحصل المشترك الجديد على آخر قيمة تم إصدارها، حتى لو اشترك بعد إرسالها (مثل حالة المستخدم أو حالة التطبيق).
ReplaySubject: لما تحتاج أن يحصل المشترك الجديد على عدد من القيم السابقة أو كل القيم التي تم إصدارها (مثل تسجيل الأحداث السابقة).
AsyncSubject: لما تحتاج أن يحصل المشترك على آخر قيمة فقط بعد اكتمال العمل (مثل نتائج عملية معقدة أو حسابية).

</div>
<hr/>

## What are the best practices for managing Observable subscriptions in Angular and ensuring there are no memory leaks?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">

### ليه manage subscriptions مهمة؟

في Angular، لما بتشتغل مع Observables زي HTTP requests أو حتى events زي كليك أو تغيير بيانات، لازم تتأكد إنك بتفصل (unsubscribe) عنهم لما ما تكونش محتاجهم، زي لما الـcomponent يتشال من الصفحة أو يتدمر. لو ما عملتش كده، ممكن يحصل تسرب في الذاكرة (memory leaks)، وده بيأثر على أداء التطبيق بتاعك مع الوقت.

## أفضل الطرق manage subscriptions

1. استخدام async pipe
   دي أسهل طريقة ومريحة جدًا، وبتستخدمها لما يكون عندك observable في (template) بتاعك، وعايز تشتغل معاه. async pipe بيعمل كل الشغل الصعب عنك. يعني بيشترك في الـobservable، ولما الـcomponent يتدمر أو يخرج من الشاشة، بيعمل unsubscribe تلقائيًا.

<div dir="auto" align="left">

```typescript
<div *ngIf="data$ | async as data">
  {{ data }}
</div>
```

</div>
هنا لما البيانات (data$) تتغير، الـasync pipe بيجيبها لك ويعرضها.
ولو الـcomponent اتشال أو المستخدم راح لشاشة تانية، الـasync pipe بيعمل unsubscribe تلقائي.
<hr/>

2. استخدام takeUntil مع Subject
الفكرة إنك تعمل Subject كإشارة (notifier) عشان تدي أمر لجميع الـobservables إنهم يوقفوا لما الـcomponent يتم تدميره. بتستخدم takeUntil كـ operator في الـ pipe عشان يتحقق من الـ Subject، وأول ما تبعتله إشعار (signal)، هو هيوقف كل الاشتراكات.
<div dir="auto" align="left">

```typescript
import { Subject } from "rxjs";
import { takeUntil } from "rxjs/operators";

export class MyComponent implements OnDestroy {
  private destroy$ = new Subject<void>();

  ngOnInit() {
    this.myObservable$
      .pipe(takeUntil(this.destroy$)) // هنا بنوقف الاشتراك لما الـdestroy$ تعمل emit
      .subscribe((data) => {
        console.log(data);
      });
  }

  ngOnDestroy() {
    this.destroy$.next(); // بنعمل إشعار إن الـcomponent اتدمر
    this.destroy$.complete(); // بننهي الـSubject تمامًا
  }
}
```

</div>

في المثال ده، بنستخدم destroy$ كإشارة لوقف الاشتراكات لما ngOnDestroy يتنفذ (الـcomponent يتشال).
كل الاشتراكات بتقف لما الـcomponent يتدمر، وده بيمنع تسرب الذاكرة.

<hr/>

3. التحديث الجديد في Angular 16: takeUntilDestroyed
   في Angular 16، ظهر شيء جديد اسمه takeUntilDestroyed وده بيسهل الموضوع أكتر. بدل ما تكتب كود كتير عشان تعمل takeUntil مع Subject، دلوقتي Angular وفرت لك حل جاهز.

### إزاي بنستخدمه؟

دلوقتي، مفيش داعي لإنك تعمل Subject بنفسك وتتحكم فيه. Angular هتتعامل مع الموضوع بشكل أوتوماتيكي.

<div dir="auto" align="left">

```typescript
import { takeUntilDestroyed } from "@angular/core/rxjs-interop";

export class MyComponent {
  ngOnInit() {
    this.myObservable$
      .pipe(takeUntilDestroyed(this)) // هنا بنمرر الـcomponent كـcontext
      .subscribe((data) => {
        console.log(data);
      });
  }
}
```

</div>

takeUntilDestroyed بيخليك تعمل نفس اللي كنا بنعمله مع takeUntil و Subject، بس بشكل أبسط وأسرع.
مش محتاج تعمل أي Subject، ومجرد ما الـcomponent يتدمر، Angular هتعمل unsubscribe تلقائي.

</div>

<hr/>

## what are the differences between cold observable and hot observable?

[⬆️ Back to Top](#top3)

<div dir="auto" align="right">
الفرق بين Hot Observables و Cold Observables ممكن يتلخص في طريقة تصرفهم مع المشتركين (subscribers) والبيانات اللي بيبعتوها.

### Cold Observables

الـ Cold Observable هو النوع اللي بيبدأ يشتغل لما حد يشترك فيه. يعني إيه؟ يعني مش بيبدأ يبعث بيانات أو يعمل أي حاجة إلا بعد ما أول مشترك يظهر.

💡 مثال بسيط:
لو عندك طلب HTTP (زي لما تطلب بيانات من سيرفر)، الطلب ده بيكون Cold Observable. ليه؟ لأنه هيبدأ يجيب البيانات ويشتغل بس لما المشترك الأول يشترك فيه.

كل مشترك جديد هيبدأ من الأول كأنه بيطلب نفس البيانات لأول مرة. يعني، لو فيه أكتر من مشترك، كل واحد هيعمل الطلب الخاص بيه.

<div dir="auto" align="left">

```typescript
const coldObservable = new Observable((observer) => {
  observer.next(Math.random());
});

coldObservable.subscribe((value) => console.log("Subscriber 1:", value));
coldObservable.subscribe((value) => console.log("Subscriber 2:", value));
```

</div>

في المثال ده، كل مشترك هيستقبل قيمة مختلفة لأن الـobservable هيشتغل من الأول مع كل اشتراك

### Hot Observables

الـ Hot Observable، على العكس، بيبدأ يبعث بيانات بمجرد ما يشتغل، حتى لو مفيش حد مشترك فيه. وده معناه إن أي مشترك جديد هيشترك في النص ويبدأ ياخد البيانات من اللحظة اللي هو اشترك فيها، مش من الأول.

💡 مثال بسيط:
لو عندك event زي حركة الماوس أو ضغطات زرار، ده يعتبر Hot Observable، لأنه بيبعت البيانات أول ما يحصل الحدث، بغض النظر لو كان فيه مشتركين ولا لأ.

كل مشترك جديد بيشترك بياخد البيانات من اللحظة اللي اشترك فيها. لو حاجة حصلت قبل كده، المشترك الجديد مش هيشوفها.

<div dir="auto" align="left">

```typescript
const hotObservable = new Subject();

hotObservable.subscribe((value) => console.log("Subscriber 1:", value));

hotObservable.next(Math.random());

hotObservable.subscribe((value) => console.log("Subscriber 2:", value));

hotObservable.next(Math.random());
```

</div>
</div>

</hr>

## What are the differences between Observables and Promises?

[⬆️ Back to Top](#top3)

<div dir="auto" align='right'>
الفرق بين الـ Observables والـ Promises يعتبر مهم جدًا لما تيجي تتعامل مع الكود الـ Asynchronous في JavaScript أو Angular.

### التشابهات بين Promise و Observable

- الاتنين بيشتغلوا مع العمليات Asynchronous (غير المتزامنة).
- الاتنين بيتحكموا في إمتى الكود اللي حاطه المستخدم هياخد القيمة.

### الفرق بينهم

#### 🏃‍♀️ التنفيذ (Execution)

##### Promise

بيتنفذ فورًا بمجرد ما يتكتب. يعني بمجرد ما تكتب الكود اللي بيعمل promise، هيتنفذ على طول حتى لو لسه ماعملتش then عليه. يعني الكود اللي جواه هيشتغل مباشرة.

##### Observable

بيشتغل بس لما تعمل subscribe، يعني مش هيبدأ يشتغل غير لما تطلبه. ده معناه إنك ممكن "تحضر" الـobservable لعملية async لكن ما تنفذوش غير لما تحتاجه.

#### 📦 القيم (Values)

##### Promise

بيطلع قيمة واحدة بس أو خطأ. يعني هو يا إما يرجعلك النتيجة أو يرمي خطأ لو حصل مشكلة.

##### Observable

ممكن يطلعلك أكتر من قيمة أو قيمة واحدة أو مفيش قيمة خالص. ده معناه إنه مناسب لحاجات زي الأحداث المتكررة (زي الضغط على زرار أكتر من مرة) أو التعامل مع event emitters في Angular.

**مثال**: لو عندك حاجة بتعمل استجابة للأحداث زي حركة الماوس أو كتابة المستخدم، الـobservable هو الحل الأمثل.

#### 🚧 الإلغاء (Cancellation)

##### Promise

مينفعش يتلغي. بمجرد ما يبدأ، بيكمل شغله حتى لو مش محتاجه. فيه بعض الطرق أو المكتبات اللي بتحاول تحايل على الموضوع، بس الـPromise في الأساس مش معمول للإلغاء.

##### Observable

معمول إنه يكون قابل للإلغاء، وده بيساعدك في إدارة الموارد بتاعتك بشكل أحسن. تقدر تلغي الاشتراك باستخدام unsubscribe أو من خلال الـoperators.

**في Angular**، ده بيساعدك تعمل حاجات زي الـ typeahead (بحث مباشر) وتمنع تسرب الذاكرة باستخدام takeUntil اللي بيوقف الـobservable لما الـcomponent يتشال.

#### ⚙️ (Operators)

##### Promise

مفيهوش operators، يعني مفيش طرق جاهزة للتعامل مع البيانات اللي بترجع من promise غير بإنك تستعمل then أو catch.

##### Observable

عنده أنواع كتير من الـ operators، زي التحويل، الفلترة، التعامل مع الأخطاء، والـoperators دي بتخليك تعمل حاجات معقدة بطرق بسيطة جدًا.

**مثال**: تقدر تعمل حاجات زي map لتحويل البيانات، أو debounceTime عشان تأخر تنفيذ الـobservable، أو catchError للتعامل مع الأخطاء.

#### الخلاصة

##### Promise

بيبدأ الشغل فورًا وبيطلعلك قيمة واحدة بس.
مش قابل للإلغاء، لكن Observable قابل للإلغاء.

##### Observable

بيبدأ بس لما تعمل اشتراك وممكن يطلعلك قيم متعددة.
عندها operators قوية جدًا بتخليك تتعامل مع البيانات بسهولة، وده بيفرق كتير في المشاريع الكبيرة.

</div>
<hr/>

## What is a higher-order Observable?

[⬆️ Back to Top](#top3)

<div dir="auto" align='right'>
الـ Higher-order Observable ببساطة هو Observable اللي بيطلع Observables تانية، بدل ما يطلع قيم عادية زي أرقام أو نصوص. يعني تقدر تقول إنه بيطلع Observable داخل Observable

### إمتى بنحتاج الـ Higher-order Observable؟

لما يكون عندك عمليات غير متزامنة كتيرة، زي إنك تعمل طلبات HTTP متتابعة أو تتعامل مع أحداث معينة بشكل مرتب، هنا بيجي دور الـ Higher-order Observable. هو بيساعدك على إنك "تسلسل" العمليات دي بشكل مرتب وفعال.

### إزاي بنتعامل مع الـ Higher-order Observable؟

عشان نتعامل مع الـ Higher-order Observables، بنستخدم Operators زي:
mergeMap
switchMap
concatMap

الـ Operators دي بتساعد على "flatten " أو "دمج" الـObservables اللي طالعين من الـ Higher-order Observable عشان يكون عندك Observable واحد في النهاية، وتقدر تشترك فيه بشكل عادي وتتعامل مع القيم اللي بتطلع منه.

### كل Operator بيشتغل إزاي؟

#### mergeMap

بيعمل flatten للـObservables اللي بتطلع من الـObservable الأصلي، ويشغلهم كلهم بالتوازي. يعني لو فيه أكتر من Observable طالع، كلهم هيشتغلوا في نفس الوقت.

#### switchMap

ده بيعمل flatten زي mergeMap، لكن الفرق إنه بيبدل الاشتراك لو فيه Observable جديد طلع. يعني لو فيه Observable جديد طلع، بيكنسل القديم ويشتغل على الجديد بس.

#### concatMap

ده بيشتغل زيهم بس بالتتابع. يعني كل Observable يخلص الأول قبل ما اللي بعده يبدأ، وده بيفيد لما يكون فيه ترتيب مهم لازم يتبع.

#### 💡 مثال

 <div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import { HttpClient } from "@angular/common/http";
import { Observable } from "rxjs";

@Injectable({
  providedIn: "root",
})
export class UserService {
  private apiUrl = "https://jsonplaceholder.typicode.com/users";

  constructor(private http: HttpClient) {}

  getUserById(id: number): Observable<any> {
    return this.http.get(`${this.apiUrl}/${id}`);
  }
}
```

</div>
 نعمل component فيه input عشان المستخدم يكتب ID، ونعمل اشتراك (subscribe) في القيمة:

 <div dir="auto" align="left">

```typescript
import { Component, OnInit } from "@angular/core";
import { FormControl } from "@angular/forms";
import { UserService } from "./user.service";
import { switchMap, debounceTime, distinctUntilChanged } from "rxjs/operators";

@Component({
  selector: "app-user-search",
  template: `
    <h2>Search for User</h2>
    <input
      type="number"
      [formControl]="userIdControl"
      placeholder="Enter User ID"
    />

    <div *ngIf="userData">
      <h3>User Details:</h3>
      <p>Name: {{ userData.name }}</p>
      <p>Email: {{ userData.email }}</p>
      <p>Address: {{ userData.address.street }}, {{ userData.address.city }}</p>
    </div>
  `,
})
export class UserSearchComponent implements OnInit {
  userIdControl = new FormControl();
  userData: any;

  constructor(private userService: UserService) {}

  ngOnInit() {
    // Listen for changes in the user ID input
    this.userIdControl.valueChanges
      .pipe(
        debounceTime(300), // Small delay to allow the user to finish typing
        distinctUntilChanged(), // Ensure the new value is different from the previous one
        switchMap((id: number) => this.userService.getUserById(id)) // Switch to a new request based on the new ID
      )
      .subscribe((data) => {
        this.userData = data; // Store the user data from the API response
      });
  }
}
```

</div>

</div>

<hr/>

## How can you share a single Observable among multiple subscribers?

[⬆️ Back to Top](#top3)

<div dir="auto" align='right'>
لما تيجي تشارك Observable واحد بين أكتر من مشترك (subscriber)، ممكن تستخدم share أو shareReplay. دول operators في RxJS بيساعدوك إنك تخلي الـObservable يتشارك بين المشتركين بدل ما كل واحد يعمل اشتراك منفصل ويبدأ العملية من الأول.

### إزاي الكلام ده بيفيدك؟

لما يكون عندك Observable بيعمل عملية معينة زي طلب HTTP، الطبيعي إن كل مشترك هيعمل طلب جديد، وده ممكن يكون مشكلة لو عندك مشتركين كتير، لأن كل واحد هيبدأ الطلب من الأول.

لكن لما تستخدم share، المشتركين كلهم هيشتركوا في نفس الـObservable اللي شغال بالفعل، فمش هيعملوا طلبات متكررة، هيستفيدوا من نفس النتيجة.

### طيب إيه الفرق بين share و shareReplay؟

### share

ده بيشترك في الـObservable الأصلي ويشترك فيه كل المشتركين، بس المشكلة إنه ما بيحتفظش بالقيم اللي طلعت. يعني لو واحد اشترك متأخر، مش هيشوف القيم اللي طلعت قبل ما يشترك.

### shareReplay

هنا بقى، ده بيشتغل زي share بس بميزة إضافية، إنه بيحتفظ بعدد معين من القيم اللي طلعت، عشان لو مشترك جديد اشترك متأخر، يقدر يشوف القيم اللي طلعت قبل كده. يعني بيعيد إرسال القيم للمشتركين الجدد.

#### 💡 مثال

 <div dir="auto" align="left">

```typescript
import { HttpClient } from "@angular/common/http";
import { Component, OnInit } from "@angular/core";
import { shareReplay } from "rxjs/operators";

@Component({
  selector: "app-user",
  template: `
    <h2>User Information</h2>
    <div *ngIf="userData">
      <p>Name: {{ userData.name }}</p>
      <p>Email: {{ userData.email }}</p>
    </div>
  `,
})
export class UserComponent implements OnInit {
  userData: any;

  constructor(private http: HttpClient) {}

  ngOnInit() {
    const userObservable = this.http
      .get("https://jsonplaceholder.typicode.com/users/1")
      .pipe(
        shareReplay(1) // Replay the last emitted value for any new subscribers
      );

    // First subscriber
    userObservable.subscribe((data) => {
      console.log("Subscriber 1 received data:", data);
      this.userData = data;
    });

    // Second subscriber
    userObservable.subscribe((data) => {
      console.log("Subscriber 2 received data:", data);
    });
  }
}
```

</div>
</div>
<hr/>

## Describe the types of forms created in Angular application?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
الإجابة: فيه نوعين أساسيين من الفورم في Angular

### Reactive Forms

وده معناه إنك بتتحكم في الفورم من خلال كود الـ TypeScript بدل الـ HTML.
الفورم دي مناسبة جدًا لو عايز تعمل فورم معقدة أو فيها عناصر كتير، وبتقدر تتحكم في التحقق من البيانات (validation) بشكل أدق.

#### الأنواع الرئيسية اللي بتستخدمها في النوع ده هي:

##### FormControl

ده بيعمل عنصر تحكم واحد في الفورم (زي input واحد).

##### FormGroup

ده بيجمع مجموعة من عناصر التحكم (مثلاً inputs متعددة).

##### FormArray

ده بيعمل لك عناصر تحكم ديناميكية يعني ممكن تزود أو تقلل منهم زي ما تحب.

##### FormBuilder

بيسهل عليك عملية إنشاء الـ FormControl وFormGroup وFormArray بطريقة أسرع وبكود أقل.

### Template-Driven Forms

النوع ده بيستخدم أكتر مع الفورم البسيطة زي فورم تسجيل دخول  
هنا التحكم في الفورم بيكون عن طريق الـ HTML باستخدام ديركتيفات (Directives)، وده أسهل لكن أقل تحكم مقارنة بالـ Reactive Forms.

### الأدوات الرئيسية اللي بنستخدمها هنا:

##### NgModel

بتتابع تغييرات القيم في عناصر الفورم زي الـ input وبتتعامل مع التحقق من المدخلات.

##### NgForm

دي بتربط نفسها بالفورم كله وبتتابع القيم الكلية وحالة التحقق للفورم كله.

##### NgModelGroup

دي بتتعامل مع جزء معين من الفورم وتتحقق من البيانات فيه بشكل منفصل عن باقي الفورم.

##### 💡 يعني ببساطة

لو الفورم بتاعتك بسيطة وعايز تعملها بسرعة، استخدم Template-Driven Forms.
لو الفورم معقدة وعايز تحكم أكتر في البيانات والتحقق منها، استخدم Reactive Forms.

</div>
<hr/>

## How will you create reactive form in Angular?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
أول حاجة، لازم تعمل import لـ ReactiveFormsModule. في ملف الـ TypeScript (TS)، بتعمل FormGroup باستخدام الميثود FormBuilder.group وتبدأ تجمّع شوية form controls. وكمان هتعمل function اللي هتشتغل لما الفورم يتعمله submit.

<div dir="auto" align="left">

```typescript
userForm = this.formBuilder.group({
   name: ['', Validators.required ],
   pwd: ['', Validators.required ],
});

onFormSubmit() {
   console.log(this.userForm.value);
}

```

</div>

في ملف الـ HTML، هتعمل form فيه form controls. اربط الـ FormGroup في الـ <form> باستخدام الـ directive formGroup. وكمان اربط كل form control باستخدام الـ directive formControlName.

<div dir="auto" align="left">

```HTML
<form [formGroup]="userForm" (ngSubmit)="onFormSubmit()">
   <p>Username: <input formControlName="empId"></p>
   <p>Password: <input type="password" formControlName="empId"></p>
   <button>Submit</button>
</form>

```

</div>
لما تدوس على الزرار (Submit)، الفورم هيعمل submit والـ function onFormSubmit هتشتغل علشان تعرض القيم بتاعت الفورم في الـ console.

</div>
<hr/>

## How will you create template-driven form in Angular?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
أول حاجة، لازم تعمل import لـ FormsModule. بتربط الـ ngForm في الـ <form> element. كل عناصر الفورم لازم تستخدم name و ngModel وأي validation attributes لو موجودة. في ملف الـ TypeScript (TS)، بتعمل method عشان تعمل submit للفورم وبتربط الميثود دي بالـ ngSubmit event.
<div dir="auto" align="left">

```HTML
<form #userForm="ngForm" (ngSubmit)="onFormSubmit(userForm)">
   <input name="username" ngModel required>
   <input type="password" name="pwd" ngModel required>
   <button>Submit</button>
</form>


```

</div>
<div dir="auto" align="left">

```typescript
onFormSubmit(form: NgForm) {
   console.log(form.value);
}
```

</div>
</div>
<hr/>

## Explain FormControl?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
ال FormControl في Angular بيُستخدم عشان تتحكم في الـ input أو أي عنصر معين في الـ forms. يعني ببساطة، بيكون مسؤول عن القيمة اللي المستخدم بيدخلها، وحالة الـ validation (يعني هل الإدخال صحيح ولا لأ)، وأي errors ممكن تحصل.

لما بتعمل form، بتحتاج تتابع البيانات اللي المستخدم بيدخلها وتتأكد إنها صح عن طريق الـ validation، زي مثلًا إنها تكون إيميل صحيح، أرقام معينة، أو حتى قيم مش فاضية. هنا بييجي دور الـ FormControl، اللي بيساعدك تتابع وتحكم في كل الحاجات دي.

<div dir="auto" align="left">

```typescript
const control = new FormControl("initial value", Validators.required);
```

</div>
في المثال ده، عملنا FormControl بالقيمة الافتراضية 'initial value'، وضفنا Validator بيقول إن الإدخال لازم يكون مطلوب (يعني ميكونش فاضي).

#### أهم خصائص FormControl

###### value

دي القيمة اللي المستخدم دخلها حاليًا.

###### valid

ده بيحدد إذا كان الإدخال صحيح ولا لأ.

###### invalid

ده بيحدد إذا كان في أخطاء ولا لأ.

###### pristine

لو المستخدم ما عدلش في الإدخال، بتبقى true.

###### dirty

لو المستخدم غيّر في الإدخال، بتبقى true.

</div>
<hr/>

## Explain FormGroup?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>

ال FormGroup في Angular بيُستخدم عشان يجمع مجموعة من الـ FormControls في نموذج واحد. يعني لو عندك فورم فيه أكتر من input (زي اسم، إيميل، وكلمة مرور)، تقدر تجمعهم كلهم في FormGroup عشان تتحكم فيهم كلهم مع بعض.

الفكرة ببساطة إنك بتتعامل مع الفورم ككل، بدل ما تتعامل مع كل (input) لوحده. بتقدر تتابع الـ validation والحالة بتاعة كل جوا المجموعة (group).

<div dir="auto" align="left">

```typescript
const form = new FormGroup({
  name: new FormControl(""),
  email: new FormControl(""),
  password: new FormControl(""),
});
```

</div>

### الخصائص المهمة بتاعة FormGroup

###### controls

دي بترجعلك كل الـ FormControls اللي جوه المجموعة.

###### value

بترجع القيم بتاعة كل الحقول في صورة object.

###### valid

لو كل الـ FormControls جوا المجموعة صالحة (valid)، بتكون true.

###### invalid

لو فيه أي input (input) في المجموعة مش صالح، بتكون true.

###### pristine

بتكون true لو مفيش أي تعديل حصل في أي input.

###### dirty

بتكون true لو حصل تعديل في أي input.

</div>
<hr/>

## Explain FormArray?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
ال FormArray في Angular بيُستخدم عشان تدير مجموعة من الـ FormControls أو الـ FormGroups جوا (form). الفكرة إنك تقدر تعمل array  من inputs اللي ممكن تضيفها أو تشيلها بشكل ديناميكي على حسب احتياجاتك.

يعني مثلًا لو عندك form فيه أكتر من input والـ input ده ممكن يتكرر زي مثلًا لما المستخدم يضيف أكتر من عنوان بريد إلكتروني أو أكتر من رقم تليفون، هنا بتستخدم FormArray عشان تقدر تضيف الـ inputs دي وتتحكم فيها.

<div dir="auto" align="left">

```typescript
const formArray = new FormArray([new FormControl(""), new FormControl("")]);
```

</div>

### التعامل مع FormArray

ممكن تضيف FormControl جديد في الـ array باستخدام push

<div dir="auto" align="left">

```typescript
formArray.push(new FormControl(""));
```

</div>
وممكن تشيل FormControl باستخدام removeAt
<div dir="auto" align="left">

```typescript
formArray.removeAt(0);
```

</div>
تقدر كمان تتعامل مع الـ FormArray زي ما بتتعامل مع الـ FormGroup أو الـ FormControl من ناحية التحقق (validation) والحالة (status) والقيم (values).

<div dir="auto" align="left">

```typescript
const formArray = new FormArray([
  new FormControl("", Validators.required),
  new FormControl("", Validators.email),
]);
```

</div>
</div>

## Explain FormRecord?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>

الـ FormRecord في Angular شبه الـ FormGroup، بس الفرق إنه بيتعامل مع مجموعة من الـ FormControl اللي كلهم من نفس نوع القيمة. يعني، الـ FormRecord بيتتبع القيمة وحالة الـ validity لمجموعة من الـ FormControl اللي ليهم نفس نوع البيانات.

الـ FormRecord مفيد جدًا لما تحب تبني form بشكل ديناميكي. تقدر تضيف form controls باستخدام addControl، وتشيلهم بـ removeControl، وهكذا.

<div dir="auto" align="left">

```typescript
@Component({
  selector: "my-app",
  standalone: true,
  imports: [CommonModule, ReactiveFormsModule],
  templateUrl: "./my.component.html",
})
export class MyComponent implements OnInit {
  userForm!: FormRecord;
  formData = [
    { title: "Name", key: "name" },
    { title: "City", key: "city" },
  ];
  ngOnInit() {
    this.userForm = new FormRecord<FormControl<string | null>>({});
    this.formData.forEach((data) =>
      this.userForm.addControl(data.key, new FormControl())
    );
  }
  onFormSubmit() {
    console.log(this.userForm.value);
  }
}
```

</div>

<div dir="auto" align="left">

```HTML
<form [formGroup]="userForm" (ngSubmit)="onFormSubmit()">
    <div *ngFor="let data of formData">
        {{data.title}}: <input [formControlName]="data.key"><br />
    </div>
    <button>Submit</button>
</form>

```

</div>
في الكود ده، إحنا بنستخدم FormRecord عشان ننشئ form ديناميكي. عندنا formData فيها الحقول اللي عايزينها في الـ form. في ngOnInit، بنعمل instance من الـ FormRecord وبنضيف الـ form controls باستخدام addControl.

لما المستخدم يضغط على زرار "Submit"، الـ onFormSubmit هتتنفذ وهتطبع قيم الـ form في الـ console.

بكده، تقدر تستخدم FormRecord عشان تبني forms ديناميكية بسهولة في Angular، وتتحكم في القيم والـ validation بتاعتها.

</div>
<hr/>

## How will you use valueChanges?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
الـ valueChanges ده Observable في Angular، بيعمل emit للقيمة بتاعة الـ form control أو الـ form group لما قيمتها بتتغير، سواء المستخدم غيرها أو برمجياً.

يعني لو المستخدم عدل في الـ input، الـ valueChanges هيشتغل وهيعمل subscribe لأي function انت محددها. وكمان لو انت برمجياً غيرت القيمة أو عملت enable/disable للـ control، برضه الـ valueChanges هيعمل emit.

تقدر تستخدمه مع FormControl، FormGroup، وFormArray.

<div dir="auto" align="left">

```typescript

studentForm = this.formBuilder.group({
  stdName: ['', [ Validators.required ]],
});

this.studentForm.get('stdName').valueChanges.subscribe(
  stdName => console.log(stdName);
);

this.studentForm.valueChanges.subscribe(student => {
  console.log(student.stdName);
});


```

</div>
في المثال ده، احنا عملنا subscribe للـ valueChanges بتاع الـ stdName control، فأي تغيير في القيمة هيطبع القيمة الجديدة في الـ console. وكمان عملنا subscribe للـ valueChanges بتاع الـ studentForm كله، فأي تغيير في أي control جوه الـ form هيطبع الـ student.stdName الجديدة.
</div>
<hr/>

## How will you use statusChanges?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
الـ statusChanges ده بيكون observable، يعني بيراقب أي تغيير في حالة الـ validation الخاصة بأي FormControl أو FormGroup أو FormArray. يعني كل ما يحصل إعادة حساب للـ validation، الـ statusChanges بيعمل emit بالقيمة الجديدة للحالة سواء كانت valid أو invalid.
<div dir="auto" align="left">

```typescript
studentForm = this.formBuilder.group({
  stdName: ['', [ Validators.required ]],
});
this.studentForm.get('stdName').statusChanges.subscribe(
  status => console.log(status);
);
this.studentForm.statusChanges.subscribe(status => {
	console.log(status);
});

```

</div>
هنا إحنا عاملين FormGroup اسمه studentForm وجواه FormControl اسمه stdName والـ validation بتاعه إنه required (يعني لازم المستخدم يدخل القيمة).

أول حاجة: بنستخدم statusChanges عشان نراقب حالة الـ stdName. لو حصل أي تغيير في الـ validation (يعني مثلاً المستخدم يدخل قيمة أو يسيبها فاضية)، هيتعمل emit للحالة سواء كانت valid أو invalid.

تاني حاجة: بنراقب حالة الـ FormGroup كله عن طريق الـ statusChanges بتاع الـ studentForm. وده بيعرض لنا حالة النموذج بالكامل.

يعني باختصار، الـ statusChanges ده بيساعدك تعرف إمتى الـ form أو الـ input بيغير حالته من صالح (valid) أو غير صالح (invalid) وتقدر تتصرف بناءً على الحالة دي.

</div>
<hr/>

## What is difference between setValue() and patchValue()?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
في Angular، الفرق بين setValue و patchValue بيظهر لما تيجي تتعامل مع الفورم وتحدث القيم اللي فيه.

setValue بيطلب منك تدي كل القيم لكل الـ controls اللي في الـ form أو الـ FormGroup. يعني لو الفورم بتاعك فيه 3 حقول، وانت استخدمت setValue، لازم تدي قيم للـ 3 حقول دول. لو نسيت أي حقل، هيطلعلك error.

patchValue بيبقى مرن أكتر. مش شرط تدي قيم لكل الـ controls. يعني ممكن تحدث جزء من الفورم بس من غير ما يحصل أي مشكلة. فلو الفورم فيه 3 حقول، وانت استخدمت patchValue لحقلين بس، الحقل التالت هيفضل زي ما هو من غير مشاكل.

<div dir="auto" align="left">

```typescript
form.setValue({
  name: "Abdelrahman",
  email: "abdelrahman@example.com",
  age: 30,
});

form.patchValue({
  name: "Abdelrahman",
  email: "abdelrahman@example.com",
});
```

</div>
في المثال الأول، لازم تدّي قيم لكل الـ inputs (name، email، و age)، لكن في المثال التاني، استخدمنا patchValue عشان نحدث بس الـ name والـ email من غير ما نضطر نحط قيمة للـ age.

باختصار:

setValue لازم تدي كل القيم لكل الـ inputs.
patchValue تقدر تدي قيم لجزء من الـ inputs بس.

</div>
<hr/>

## How will you add and remove controls on FormGroup dynamically?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
علشان تضيف وتزيل controls في FormGroup بشكل ديناميكي، بتستخدم الميثودز addControl وremoveControl.
<div dir="auto" align="left">

```typescript
addControl(name: string, control: AbstractControl)

```

</div>
<div dir="auto" align="left">

```typescript
this.customerForm.addControl(
  "city",
  this.formBuilder.control("", [Validators.required])
);
```

</div>
في المثال ده، بنضيف control اسمه 'city' للـ FormGroup بتاعنا.

<div dir="auto" align="left">

```typescript
removeControl(name: string)
```

</div>
<div dir="auto" align="left">

```typescript
this.customerForm.removeControl("city");
```

</div>
وده بيشيل الـ control اللي اسمه 'city' من الـ FormGroup.

#### 💡 مثال

هنفترض إن عندنا FormGroup اسمه customerForm، وعايزين نضيف حقل (control) اسمه "city" ونزيله بعد كده.

#### الخطوات:

أول حاجة هننشئ FormGroup.
هنستخدم addControl عشان نضيف الـ control.
بعد كده، لو عايزين نزيل الـ control، هنستخدم removeControl.

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";
import { FormBuilder, FormGroup, Validators } from "@angular/forms";

@Component({
  selector: "app-customer-form",
  templateUrl: "./customer-form.component.html",
})
export class CustomerFormComponent {
  customerForm: FormGroup;

  constructor(private formBuilder: FormBuilder) {
    this.customerForm = this.formBuilder.group({
      name: ["", Validators.required],
    });
  }

  addCityControl() {
    this.customerForm.addControl(
      "city",
      this.formBuilder.control("", [Validators.required])
    );
  }

  removeCityControl() {
    this.customerForm.removeControl("city");
  }
}
```

HTML

<div dir="auto" align="left">

```HTML
<form [formGroup]="customerForm">
  <label for="name">Name:</label>
  <input id="name" formControlName="name" />

  <div *ngIf="customerForm.get('city')">
    <label for="city">City:</label>
    <input id="city" formControlName="city" />
  </div>

  <button type="button" (click)="addCityControl()">Add City</button>
  <button type="button" (click)="removeCityControl()">Remove City</button>
</form>

```

</div>
</div>
عند الضغط على زرار "Add City"، بيتم إضافة حقل city.
عند الضغط على زرار "Remove City"، بيتم إزالة حقل city.
الطريقة دي بتخليك تتحكم في الحقول الديناميكية في النموذج بتاعك بكل سهولة.
</div>
<hr/>

## What is difference between (ngModelChange) and (change)?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
ببساطة، الفرق بين (ngModelChange) و (change) هو إن كل واحد منهم بيشتغل في مكان مختلف ولغرض مختلف:

الngModelChange ده بيشتغل مع حاجة اسمها ngModel، وده حاجة خاصة بـ Angular. يعني لو عندك input في النموذج بتاعك (form)، وعايز تتابع التغير اللي بيحصل في القيمة بتاعته بشكل مباشر، بتستخدم ngModelChange. كل ما القيمة تتغير جوه ngModel، الحدث ده بيشتغل وبيجيبلك القيمة الجديدة على طول باستخدام حاجة اسمها $event.

<div dir="auto" align="left">

```HTML
<input [(ngModel)]="name" (ngModelChange)="onNameChange($event)">
```

</div>
هنا كل ما المستخدم يغير الاسم في input ده، الحدث ngModelChange هيشتغل وهيجيبلك القيمة الجديدة اللي دخلها المستخدم.

الchange ده عبارة عن DOM event عادي خاص بـ HTML، وبيشتغل لما يحصل تغيير في القيمة بتاعت العنصر (زي input أو select)، لكنه بيتفاعل بس لما المستخدم يخلص التغيير (زي لما يكتب حاجة ويضغط Enter أو يطلع من input).

<div dir="auto" align="left">

```HTML
<input (change)="onInputChange($event)">
```

</div>
هنا change بيشتغل بس لما المستخدم يغير القيمة ويطلع من الـ input، وبيجيبلك القيمة من خلال event.target.value.

### الفرق الرئيسي

#### ngModelChange

بيراقب التغيير بشكل فوري جوه ngModel وبيجيبلك القيمة مباشرة من $event.

#### change

بيتفاعل مع التغيير في HTML elements العادية بعد ما المستخدم يخلص التغيير، وبتجيب القيمة باستخدام event.target.value.
يعني لو عايز تعرف التغيير أول ما يحصل في الـ input وتتحكم فيه، استخدم ngModelChange. لكن لو عايز تعرف التغيير بعد ما المستخدم يخلص تعديل القيمة، استخدم change.

</div>
<hr/>

## How to add async validation in FormControl?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
لو عايز تضيف async validation في FormControl، الموضوع بسيط

تقدر تمرر array من async validators كـ argument تالت في FormControl. مثال:

<div dir="auto" align="left">

```typescript
customerForm = this.formBuilder.group({
  customerName: ["", [Validators.required], [myCustomAsyncValidator()]],
});
```

</div>
الطريقة التانية، ممكن تمرر object كـ argument تاني يحتوي على خصائص زي validators و asyncValidators. مثال:

<div dir="auto" align="left">

```typescript
customerForm = this.formBuilder.group({
  customerName: [
    "",
    {
      validators: [Validators.required],
      asyncValidators: [myCustomAsyncValidator()],
    },
  ],
});
```

</div>

#### 💡 مثال

هديك مثال واقعي لموقف ممكن تستخدم فيه async validation في FormControl. خلينا نفترض إنك بتعمل form للمستخدم عشان يسجل بياناته، ومن ضمن البيانات دي اسم المستخدم (username)، ولازم تتأكد إن الاسم ده مش متسجل قبل كده في قاعدة البيانات (دي عملية بتحتاج تحقق من قاعدة البيانات، وبالتالي هتكون async).

#### create a service

<div dir="auto" align="left">

```typescript
@Injectable({ providedIn: "root" })
export class UserService {
  constructor(private http: HttpClient) {}

  checkUsername(username: string): Observable<boolean> {
    return this.http.get<boolean>(
      `/api/users/check-username?username=${username}`
    );
  }
}
```

</div>

#### UserFormComponent

<div dir="auto" align="left">

```typescript
export class UserFormComponent {
  constructor(
    private formBuilder: FormBuilder,
    private userService: UserService
  ) {}

  customerForm = this.formBuilder.group({
    username: ["", [Validators.required], [this.checkUsernameAvailability()]],
  });

  checkUsernameAvailability(): AsyncValidatorFn {
    return (control: AbstractControl): Observable<ValidationErrors | null> => {
      return this.userService.checkUsername(control.value).pipe(
        map((isAvailable) => {
          return isAvailable ? null : { usernameTaken: true };
        })
      );
    };
  }
}
```

</div>

#### template

<div dir="auto" align="left">

```HTML
<form [formGroup]="customerForm" (ngSubmit)="onSubmit()">
  <label for="username">Username</label>
  <input id="username" formControlName="username">

  <div *ngIf="customerForm.get('username').hasError('usernameTaken')">
    This username is already taken.
  </div>

  <button type="submit" [disabled]="customerForm.invalid">Submit</button>
</form>

```

</div>
دي ببساطة الطريقتين اللي تقدر تضيف بيهم async validation في FormControl في Angular.
</div>

<hr/>

## How will you validate template-driven form?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
عشان تعمل validation في الفورم اللي معمول بـ template-driven، بتحدد (validation attributes) في الـ form control، وبتستخدم   بـ # عشان تعرض رسائل الخطأ بناءً عليه.

<div dir="auto" align="left">

```HTML
<input name="uname" ngModel required maxlength="20" #usrname="ngModel">
<div *ngIf="usrname.errors?.['required']">
		Enter user name.
</div>
<div *ngIf="usrname.errors?.['maxlength']">
		Maxlength is 20.
</div>
{{usrname.status}}

```

</div>
</div>
<hr/>

## How will you perform two-way binding using ngModel?

[⬆️ Back to Top](#top5)

<div dir="auto" align='right'>
عشان تعمل two-way binding باستخدام ngModel، بتستخدم الأقواس المربعة والعادية مع بعض [()] حوالين الـ ngModel كده: [(ngModel)]. الطريقة دي بتسمح بإرسال البيانات من الـ component للـ view target، وفي نفس الوقت من الـ view target للـ component.
<div dir="auto" align="left">

```typescript
message = "Hello World!";
```

</div>

<div dir="auto" align="left">

```HTML
<input [(ngModel)]="message">

{{message}}

```

</div>
في المثال ده، أي تعديل على الإدخال اللي في الـ input هيتم تحديثه فورًا في المتغير message اللي في الـ component، والعكس صحيح. يعني أي تغيير في المتغير هيظهر برضه في الـ input.

</div>

## Uses of Angular Route Guards

[⬆️ Back to Top](#top7)

<div dir="auto" align="right">

#### To Confirm the navigational operation

لو عايز تسأل المستخدم "عايز تحفظ التعديلات قبل ما تسيب الصفحة؟

#### Allow access to certain parts of the application to specific users.

عايز تتحكم مين يدخل على أجزاء معينة في التطبيق (زي صفحات الأدمن مثلاً)

#### Validating the route parameters before navigating to the route

لو محتاج تتأكد من باراميتر معين (زي ID بتاع المستخدم مثلاً) قبل ما تروح لصفحة معينة

#### Fetching some data before you display the component.

لو عندك بيانات محتاج تجيبها من السيرفر قبل ما تعرض الكومبوننت،

</div>

## Types of Route Guards

[⬆️ Back to Top](#top7)

### The Angular Router supports fifth different guards, which you can use to protect the route.

#### 1- CanActivate

#### 2- CanDeactivate

#### 3- Resolve

#### 4- CanLoad

#### 5- CanActivateChild

## What is CanActivate Guard

[⬆️ Back to Top](#top7)

<div dir="auto" align="right">
الCanActivate Guard ده زي حارس بيمنع أو بيسمح للـ Route إنها تتفتح أو تتعرض للمستخدم بناءً على شرط معين. بنستخدمه لما نكون عايزين نتاكد من حاجة معينة قبل ما نخلي المستخدم يشوف الصفحة. يعني ممكن نقول للـ Guard ده “لو الشرط الفلاني موجود، اسمح للمستخدم يدخل”، ولو الشرط مش موجود، “امنع المستخدم”.

### أمتى بنستخدم CanActivate Guard؟

فيه أكتر من حالة ممكن تحتاج فيها CanActivate Guard

لو المستخدم مسجّل دخول: بنستخدمه عشان نتأكد إن المستخدم عامل تسجيل دخول في النظام. لو مش عامل تسجيل، نرجعه لصفحة تسجيل الدخول.

لو المستخدم ليه الصلاحية: بنشوف لو المستخدم عنده الصلاحية يدخل على صفحة معينة (زي صفحة الأدمن).

### إزاي نستخدم CanActivate Guard؟

عشان نستخدم CanActivate Guard، بنعمل Service في Angular.

### خطوات تنفيذه

إنشاء Service: بنعمل Service جديد في التطبيق يكون مسؤول عن الحماية دي.

ب Import CanActivate Interface: في الـ Service، بنستورد CanActivate Interface من @angular/router، ودي بتخلينا نحدد طريقة اسمها canActivate.

تنفيذ canActivate Method: الطريقة دي بتتأكد لو الشرط اتحقق وترجع true لو ممكن نكمل وندخل، أو false لو مش هينفع نكمل. كمان ممكن ترجع UrlTree (دي زي لينك) عشان تحول المستخدم على صفحة تانية لو الشرط مش موجود.

<div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import {
  Router,
  CanActivate,
  ActivatedRouteSnapshot,
  RouterStateSnapshot,
} from "@angular/router";

@Injectable()
export class AuthGuardService implements CanActivate {
  constructor(private _router: Router) {}

  canActivate(
    route: ActivatedRouteSnapshot,
    state: RouterStateSnapshot
  ): boolean {
    //check some condition
    if (someCondition) {
      alert("You are not allowed to view this page");
      //redirect to login/home page etc
      //return false to cancel the navigation
      return false;
    }
    return true;
  }
}
```

Update the route definition with the canActivate guard as shown below. You can apply more than one guard to a route and a route can have more than one guard

</div>

<div dir="auto" align="left">

```typescript
{ path: 'product', component: ProductComponent, canActivate : [AuthGuardService] },
```

</div>

</div>

## What is CanActivateChild Guard

[⬆️ Back to Top](#top7)

<div dir="auto" align="right">

### يعني إيه CanActivateChild Guard؟

الCanActivateChild Guard ده زي CanActivate Guard، بس الفرق إنه بيتطبق على الأب اللي جواه Routes الفكرة هنا إنك لما تحط CanActivateChild Guard على أي Route أب، كل ما المستخدم يحاول يدخل على واحدة من الصفحات الفرعية (الـ Children)، الـ Guard ده بيشتغل ويتأكد لو مسموح له يدخل ولا لأ.

### الفرق بين CanActivate و CanActivateChild

الCanActivate: بتحطه على أي Route (سواء Route عادي أو Parent) وبيتحكم في دخول المستخدم للـ Route دي كلها.

الCanActivateChild: بتحطه على الـ Parent Route وبيشتغل على كل الـ Child Routes اللي جواه. يعني بدل ما تحط Guard على كل Route فرعية، ممكن تحط CanActivateChild مرة واحدة على الـ Parent وهو هيعمل الحماية المطلوبة لكل اللي جواه.

### مثال لتوضيح الفرق

لو عندك مثلاً صفحة Products (اللي هي الـ Parent)، وعندك جواها كذا Route فرعي (زي عرض منتج معين، تعديل منتج، إضافة منتج)

باستخدام CanActivate، لو حطيت Guard على Products، ده هيمنع الدخول على الـ Parent والـ Children كلها في حالة إن المستخدم مش عامل تسجيل دخول.

باستخدام CanActivateChild، ممكن تسمح لكل الناس تشوف صفحة Products، بس تمنع الدخول للـ Routes الفرعية (زي التعديل والإضافة) وتخليها بس للأدمن.

### إزاي نستخدم CanActivateChild Guard؟

<div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import {
  Router,
  CanActivateChild,
  ActivatedRouteSnapshot,
  RouterStateSnapshot,
} from "@angular/router";

@Injectable()
export class AdminGuardService implements CanActivateChild {
  constructor(private _router: Router) {}

  canActivateChild(
    route: ActivatedRouteSnapshot,
    state: RouterStateSnapshot
  ): boolean {
    // بنفترض إن في شرط معين زي إن المستخدم يكون أدمن
    const isAdmin = false; // حط الشرط المناسب هنا
    if (!isAdmin) {
      alert("مش مسموح ليك تدخل هنا!");
      this._router.navigate(["/login"]); // يرجع المستخدم لصفحة تانية لو مش أدمن
      return false;
    }
    return true;
  }
}
```

</div>

<div dir="auto" align="left">

```typescript
{ path: 'product', component: ProductComponent, canActivate : [AuthGuardService] ,
      canActivateChild : [AuthGuardService],
      children: [
      {  path: 'view/:id', component: ProductViewComponent  },
      {  path: 'edit/:id', component: ProductEditComponent  },
      {  path: 'add', component: ProductAddComponent }
      ]
  }
```

</div>

### 🔴 ملخص سريع

CanActivate: يمنع أو يسمح بالوصول للـ Route ككل (الـ Parent والـ Children).

CanActivateChild: بيتحط على الـ Parent وبيشتغل على كل Child جواه، وبيمنع الوصول للـ Routes الفرعية بناءً على الشرط.

</div>

## What is CanDeactivate Guard

[⬆️ Back to Top](#top7)

<div dir="auto" align="right">

### يعني إيه CanDeactivate Guard؟

الCanDeactivate Guard ده بيشتغل لما المستخدم يحاول يسيب الصفحة أو الـ Component الحالية وعايز يروح لصفحة تانية.

الهدف الأساسي منه إنه يمنع المستخدم من الخروج لو عنده بيانات لسه متسجلتش، زي لما يكون كاتب بيانات في فورم بس لسه ما حفظهاش.

### أفضل حالة نستخدم فيها CanDeactivate Guard

مثلاً في حالات زي ملء بيانات في فورم: لو المستخدم كتب بيانات بس لسه ما ضغطش على "حفظ" وحاول يسيب الصفحة، CanDeactivate Guard يقدر يوقفه ويسأله "هل انت متأكد إنك عايز تخرج من غير ما تحفظ؟". لو وافق، ينقله للصفحة الجديدة، ولو رفض، يخليه يكمل في نفس الصفحة.

### إزاي نستخدم CanDeactivate Guard؟

عشان تفعّل CanDeactivate Guard، محتاج تعمل Service خاصة بيه.

خطوات التنفيذ:
إنشاء Service: بنعمل Service جديد، والـ Service ده بيستورد CanDeactivate Interface من angular/router@

تنفيذ canDeactivate Method: الطريقة canDeactivate بتاخد الكومبوننت الحالي كـ argument، وبتاخد كمان معلومات عن الـ Route الحالي والـ Route اللي المستخدم رايحله. بناءً على الشرط اللي تحدده، بتحدد لو ممكن نسيب الصفحة أو لأ.

### مثال عملي

أول حاجة، بنعمل الكومبوننت اللي عايزين نحميه، وليكن اسمه RegisterComponent. جواه بنعمل طريقة اسمها canExit، والطريقة دي بتتحقق لو فيه بيانات غير محفوظة وتسأل المستخدم لو عايز يخرج أو يكمل.

<div dir="auto" align="left">

```typescript
import { Component } from "@angular/core";

@Component({
  templateUrl: "register.component.html",
})
export class RegisterComponent {
  // الطريقة دي بتتحقق لو فيه بيانات غير محفوظة وتسأل المستخدم
  canExit(): boolean {
    if (confirm("هل تريد فعلاً الخروج بدون حفظ التعديلات؟")) {
      return true; // يسمح بالخروج
    } else {
      return false; // يخلّي المستخدم في الصفحة
    }
  }
}
```

</div>
تفعيل الـ CanDeactivate Guard في Service
بنعمل Service عشان يتحقق من canExit لما المستخدم يحاول يسيب الصفحة.
<div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import { CanDeactivate } from "@angular/router";
import { RegisterComponent } from "./register.component";

@Injectable({
  providedIn: "root",
})
export class CanDeactivateGuardService
  implements CanDeactivate<RegisterComponent>
{
  canDeactivate(component: RegisterComponent): boolean {
    return component.canExit(); // بيشغل canExit وبيتأكد لو المستخدم عايز يسيب الصفحة فعلاً
  }
}
```

</div>

### استخدام الـ Guard في الـ Routing

في ملف الـ Routing، بنضيف الـ Guard ده على الصفحة اللي عايزين نحميها، مثلاً على RegisterComponent

<div dir="auto" align="left">

```typescript
{ path: 'register', component: RegisterComponent, canDeactivate: [CanDeactivateGuardService] }
```

</div>

### 🔴 ملخص سريع

الCanDeactivate Guard بيمنع الخروج من الصفحة لو فيه بيانات غير محفوظة.

بيسأل المستخدم لو عايز يخرج بدون حفظ، ولو وافق، يكمل، ولو رفض، يفضل في نفس الصفحة.

بيساعدك تحمي بيانات المستخدم لو كان لسه ما حفظهاش قبل ما يخرج.

</div>

## How to Use Resolve Guard

[⬆️ Back to Top](#top7)

<div dir="auto" align="right">

### يعني إيه Resolve Guard؟

الResolve Guard في Angular بيعمل حاجة مهمة جداً وهي إنه يحمل البيانات من السيرفر قبل ما الصفحة تفتح أصلاً. بدل ما الكومبوننت يظهر فاضي وبعدين يستنى لحد ما البيانات توصله، Resolve Guard بيحمل البيانات الأول وبعدين يفتح الكومبوننت على طول والبيانات جاهزة.

### المشكلة اللي بيحلها Resolve Guard

عادةً في الكومبوننت العادية، لما بنستخدم ngOnInit لجلب البيانات، المستخدم ممكن يشوف صفحة فاضية لحد ما البيانات توصله. في الحالة دي، ممكن نستخدم loading spinner عشان نبين إن فيه حاجة بتحصل. لكن Resolve Guard بيخلّي البيانات موجودة من قبل ما الصفحة تفتح، فبيحسن التجربة ويخلي الصفحة تظهر كاملة للمستخدم.

### إزاي نستخدم Resolve Guard؟

إنشاء Service: بنعمل Service جديدة بتحمل البيانات المطلوبة. الـ Service دي هتطبق Resolve Interface

تنفيذ resolve method: جوه الـ Service، هنضيف method اسمها resolve بتجيب البيانات المطلوبة وترجعها. لازم ترجع Observable أو Promise عشان Angular تستنى البيانات دي قبل ما تفتح الكومبوننت.

### مثال عملي على الكود

<div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import {
  Resolve,
  ActivatedRouteSnapshot,
  RouterStateSnapshot,
} from "@angular/router";
import { ProductService } from "./product.service";
import { Observable } from "rxjs";

@Injectable({
  providedIn: "root",
})
export class ProductListResolveService implements Resolve<any> {
  constructor(private productService: ProductService) {}

  resolve(
    route: ActivatedRouteSnapshot,
    state: RouterStateSnapshot
  ): Observable<any> {
    return this.productService.getProducts();
  }
}
```

</div>

### إضافة الـ Resolve للـ Routing

عشان تفعّل الـ Resolve Guard ده، لازم تضيفه على Route بتاع الصفحة اللي عايز تفتحها بالبيانات الجاهزة.

<div dir="auto" align="left">

```typescript
{ path: 'product', component: ProductComponent, resolve: { products: ProductListResolveService } },
```

</div>
في الكود ده

الproducts هو اسم المتغير اللي هنستخدمه في الكومبوننت عشان نجيب البيانات.
ProductListResolveService هو الـ Service اللي جبنا منه البيانات.

### استخدام البيانات في الكومبوننت

جوه الكومبوننت، هنجيب البيانات الجاهزة من ActivatedRoute بدل ما نعمل طلب جديد.

<div dir="auto" align="left">

```typescript
import { Component, OnInit } from "@angular/core";
import { ActivatedRoute } from "@angular/router";

@Component({
  selector: "app-product",
  templateUrl: "./product.component.html",
})
export class ProductComponent implements OnInit {
  products: any;

  constructor(private route: ActivatedRoute) {}

  ngOnInit() {
    this.products = this.route.snapshot.data["products"]; // هنا بنجيب البيانات
  }
}
```

</div>

### ملاحظات إضافية

🔴 أولوية التنفيذ: Resolve Guard بيتنفذ بعد كل الـ Guards التانية.

🔴 إلغاء التنقل: لو الـ Resolver رجّع null أو حصل خطأ، Angular بتلغي التنقل ومش هتروح للـ Route.

🔴 استخدام أكتر من Resolver: تقدر تحط أكتر من Resolve على نفس الـ Route، يعني تقدر تجيب بيانات من مصادر مختلفة في نفس الوقت.

<div dir="auto" align="left">

```typescript
{ path: 'product', component: ProductComponent,
    resolve: {products: ProductListResolveService, , data:SomeOtherResolverService}  }
```

</div>
</div>

## How to use CanLoad Guard

[⬆️ Back to Top](#top7)

<div dir="auto" align="right">

### يعني إيه CanLoad Guard؟

الCanLoad Guard ده بيمنع تحميل الـ Lazy Loaded Modules لو المستخدم مالوش صلاحية.

بمعنى تاني، لو عندك Module مش عايز مستخدم معين يشوفه (زي صفحة الـ Admin)، الـ CanLoad بيمنع تحميل الـ Module ده بالكامل عشان المستخدم لا يقدر يشوف الصفحة ولا حتى يشوف كود الصفحة من المتصفح.

### الفرق بين CanActivate و CanLoad

الCanActivate: بيمنع المستخدم من الدخول للصفحة، لكن ما بيمنعش تحميل كود الصفحة، يعني ممكن المستخدم يشوف الكود من الـ Developer Tools.

الCanLoad: بيمنع تحميل كود الصفحة بالكامل. المستخدم مش هيشوف الكود ولا هيقدر يدخل على الصفحة.

### إزاي نستخدم CanLoad Guard؟

إنشاء Service جديدة: بنعمل Service بتطبق CanLoad Interface عشان نحدد الشروط اللي تمنع أو تسمح بالتحميل.

تنفيذ canLoad method: الطريقة دي بتتحقق من الـ Route اللي المستخدم عايز يدخل عليها، ولو الشروط متحققة بترجع true عشان يتم التحميل، أو false عشان تمنع التحميل.

#### مثال عملي

نبدأ بإنشاء Service جديدة، وليكن اسمها AuthGuardService، ونضيف فيها الشروط.

<div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import { CanLoad, Route, Router } from "@angular/router";

@Injectable()
export class AuthGuardService implements CanLoad {
  constructor(private router: Router) {}

  canLoad(route: Route): boolean {
    let url: string = route.path;
    console.log("Url:" + url);

    if (url === "admin") {
      // لو المستخدم حاول يدخل صفحة الأدمن
      alert("غير مسموح ليك تدخل الصفحة دي");
      return false; // تمنع تحميل الـ Module
    }
    return true; // تسمح بالتحميل للصفحات التانية
  }
}
```

</div>

### إضافة الـ CanLoad للـ Route

عشان تربط الـ Guard ده بالـ Routes، بتحط AuthGuardService في خاصية canLoad للـ Route اللي عايز تحميها.

<div dir="auto" align="left">

```typescript
const routes: Routes = [
  {
    path: "admin",
    loadChildren: "./admin/admin.module#AdminModule",
    canLoad: [AuthGuardService],
  },
  {
    path: "test",
    loadChildren: "./test/test.module#TestModule",
    canLoad: [AuthGuardService],
  },
];
```

</div>
تسجيل الـ Service في الـ AppModule
في الآخر، بنضيف الـ AuthGuardService في ملف AppModule كـ provider عشان Angular يقدر يستخدمه.

<div dir="auto" align="left">

```typescript
import { BrowserModule } from "@angular/platform-browser";
import { NgModule } from "@angular/core";
import { AppRoutingModule } from "./app-routing.module";
import { AppComponent } from "./app.component";
import { AuthGuardService } from "./auth-gaurd.service";

@NgModule({
  declarations: [AppComponent],
  imports: [BrowserModule, AppRoutingModule],
  providers: [AuthGuardService],
  bootstrap: [AppComponent],
})
export class AppModule {}
```

</div>
</div>

## What is angular Http interceptor

[⬆️ Back to Top](#top8)

<div dir="auto" align="right">

### يعني إيه Angular HTTP Interceptor؟

الHTTP Interceptor في Angular ده بيشتغل كوسيط ما بين التطبيق بتاعنا والسيرفر.

لما التطبيق يبعت طلب للسيرفر (زي GET أو POST)، الـ Interceptor بيقدر يمسك الطلب ده قبل ما يتبعت ويقدر يعدل عليه.

كمان لما السيرفر يرد علينا، الـ Interceptor يقدر يمسك الرد ويعدّل فيه لو محتاج.

### فوايد HTTP Interceptor

واحدة من أهم الفوايد هي إنك تقدر تضيف Authorization Header (زي توكن بتاع تسجيل الدخول) على كل طلب.

يعني بدل ما تحط التوكن بشكل يدوي في كل مكان، الـ Interceptor بيضيفه تلقائي لكل طلب، وده بيوفر مجهود ويقلل الأخطاء.

كمان تقدر تستخدمه عشان تمسك الأخطاء اللي بترجع من السيرفر، زي لو في مشكلة في الاتصال أو السيرفر رد بحاجة غلط. ممكن تخليه يسجل الأخطاء دي في اللوج أو يعرض للمستخدم رسالة.

### مثال على الاستخدامات

إضافة Headers: تقدر تضيف Headers مخصصة (زي Authorization) لكل طلب خارج.

التعامل مع الأخطاء: تقدر تمسك الأخطاء اللي بترجع من السيرفر وتتعامل معاها قبل ما توصل للتطبيق.

### إزاي نعمل Http Interceptor؟

إنشاء Service جديدة: الأول بنعمل Service جديدة، ودي لازم تطبّق HttpInterceptor Interface من Angular.

<div dir="auto" align="left">

```typescript
import { Injectable } from "@angular/core";
import {
  HttpInterceptor,
  HttpRequest,
  HttpHandler,
  HttpEvent,
} from "@angular/common/http";
import { Observable } from "rxjs";

@Injectable()
export class AppHttpInterceptor implements HttpInterceptor {
  intercept(
    req: HttpRequest<any>,
    next: HttpHandler
  ): Observable<HttpEvent<any>> {
    // هنا تقدر تعمل أي تعديل على الطلب
    console.log("Interceptor شغال!");

    // بترجع الطلب عشان يكمل ويعمله send
    return next.handle(req);
  }
}
```

</div>

الintercept هي الطريقة الأساسية اللي بتشتغل على كل طلب. بتاخد req اللي هو الطلب
الحالي وnext اللي هو المسؤول عن تمرير الطلب للخطوة اللي بعدها.

الnext.handle(req) بيكمل إرسال الطلب بعد التعديلات اللي انت عملتها.
تسجيل الـ Interceptor في الـ Root Module: عشان Angular تستخدم الـ Interceptor، لازم تضيفه في providers في AppModule وتستخدم الـ HTTP_INTERCEPTORS عشان تسجله كـ Multi Provider.

<div dir="auto" align="left">

```typescript
import { HTTP_INTERCEPTORS } from "@angular/common/http";

@NgModule({
  providers: [
    {
      provide: HTTP_INTERCEPTORS,
      useClass: AppHttpInterceptor,
      multi: true,
    },
  ],
})
export class AppModule {}
```

</div>

هنا بنضيف AppHttpInterceptor كـ provider في التطبيق، وmulti: true معناها إنه يقدر يستخدم أكتر من Interceptor في نفس الوقت لو عندك أكتر من واحد.

### Setting the new headers

#### ايه هي الفكرة الأساسية؟

لما بنبعت طلب HTTP من Angular للسيرفر (زي لما نجيب بيانات أو نبعت بيانات)، الطلب ده بيتبعت ومعاه Headers (زي بطاقة تعريف بتحط شوية معلومات عن الطلب، زي نوع البيانات اللي بنبعتها أو إن كان المستخدم مسجّل دخول).

فيه حالات بنحتاج نضيف أو نعدل أو حتى نحذف Headers قبل ما الطلب يتبعت للسيرفر.

هنا بنستخدم حاجة اسمها HTTP Interceptor، ودي بتخلينا "نعترض" الطلب ونعدل عليه قبل ما يتبعت.

 <div dir="auto" align="left">

```typescript
req = req.clone({
  headers: req.headers.set("Content-Type", "application/json"),
});
```

</div>

### ليه بنستخدم clone؟

في Angular، الطلبات (requests) والأجزاء بتاعتها زي الـ Headers بتكون ثابتة (Immutable)، يعني ماينفعش نعدل عليها مباشرةً. علشان كده، لما نحتاج نغير حاجة في الطلب، لازم نعمل نسخة (Clone) منه.

### ليه بنضيف Content-Type؟

لما نبعت بيانات للسيرفر، بنحط نوع البيانات اللي بنبعتها في الهيدر Content-Type. مثلاً لو البيانات بصيغة JSON، بنضيف الهيدر بالشكل ده

هنا set بتعمل نسخة جديدة من الهيدر وبتضيف Content-Type لو مش موجود أو بتعدله لو كان موجود.

### طيب لو عايز تضيف الهيدر بدون ما تغير الموجود؟

ممكن تستخدم append بدل set، ودي بتضيف Header جديد حتى لو كان نفس الهيدر موجود قبل كده:

<div dir="auto" align="left">

```typescript
req = req.clone({
  headers: req.headers.append("Content-Type", "application/json"),
});
```

</div>

### تأكد لو Header موجود قبل ما تضيفه

لو مش عايز تضيف نفس Header مرتين، ممكن تتأكد قبل بإستخدام:

<div dir="auto" align="left">

```typescript
if (!req.headers.has("Content-Type")) {
  req = req.clone({
    headers: req.headers.set("Content-Type", "application/json"),
  });
}
```

</div>

### إضافة Authorization Token

#### 🔴 ايه هو الـ Token؟

الـ Token هو زي كود سري بيستخدمه المستخدم لما يكون عامل تسجيل دخول.

بنضيفه في الهيدر Authorization عشان نقول للسيرفر "المستخدم ده معاه صلاحيات".

### إزاي تضيف التوكن للطلب؟

بنستخدم طريقة زي دي، نفترض إن التوكن متخزن في Service بتاعتك:

<div dir="auto" align="left">

```typescript
const token: string = authService.Token; // بنجيب التوكن من الـ Service
if (token) {
  req = req.clone({
    headers: req.headers.set("Authorization", "Bearer " + token),
  });
}
```

</div>

في الكود ده بنضيف "Bearer" قبل التوكن، وده أسلوب متعارف عليه في الـ Authorization Headers.

### Intercepting the Response

لما نبعت طلب للسيرفر، بنستنى رد (Response) يوصلنا.

الـ Interceptor بيخلينا "نعترض" الرد ده، نعدله أو نسجل أي حاجة محتاجينها قبل ما يوصل للتطبيق نفسه.

في الحالة دي، بنستخدم RxJS Operators زي map, tap catchError, و retry عشان نتحكم أكتر في الرد.

### تسجيل requests باستخدام tap

#### ليه بنستخدم tap؟

الtap بيخلينا نقدر نسجل أحداث معينة، زي الوقت اللي أخده الطلب عشان يخلص.

دي طريقة كويسة لو عايز تعرف الوقت اللي الطلب استغرقه، أو تسجل أي معلومات إضافية عن الطلب أو الرد.

### مثال عملي

في الكود ده، tap بيتنفذ مرتين: مرة لما الطلب يبعت، ومرة تانية لما الرد يوصل.

<div dir="auto" align="left">

```typescript
intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>> {
  req = req.clone({ headers: req.headers.append('Content-Type', 'application/json') });
  const started = Date.now();

  return next.handle(req).pipe(
    tap(event => {
      const elapsed = Date.now() - started;
      console.log(`Request for ${req.urlWithParams} took ${elapsed} ms.`);
      if (event instanceof HttpResponse) {
        console.log('Response Received');
      }
    })
  );
}
```

</div>

✨الكود ده بيحسب الزمن اللي أخده الطلب عشان يوصل الرد، وبيسجل رسالة لما الاستجابة توصل.

### تعديل الرد باستخدام map

#### ليه بنستخدم map؟

الmap بنستخدمه عشان نعدل محتوى الرد قبل ما يوصل للتطبيق. لو فيه بيانات محتاجين نغيرها أو نبدّلها، بنقدر نستخدم map عشان نعمل ده.

#### مثال عملي

في المثال ده، بنستخدم map عشان نغير محتوى الرد بالكامل، ونحط بيانات جديدة في (body) بتاع الرد:

<div dir="auto" align="left">

```typescript
intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>> {
  return next.handle(req).pipe(
    map(resp => {
      const myBody = [{ 'id': '1', 'name': 'TekTutorialsHub', 'html_url': 'www.tektutorialshub.com', 'description': 'description' }];
      if (resp instanceof HttpResponse) {
        resp = resp.clone<any>({ body: myBody });
        return resp;
      }
      return resp;
    })
  );
}
```

</div>

### التعامل مع الأخطاء باستخدام catchError

#### ليه بنستخدم catchError؟

الcatchError بنستخدمه عشان نمسك أي خطأ حصل أثناء الطلب ونتعامل معاه، زي مثلاً لو الطلب رجّع 401 Unauthorized، نعرف نوجّه المستخدم لصفحة تسجيل الدخول.

#### مثال عملي

في الكود ده، catchError بيمسك الأخطاء ويعرض التفاصيل الخاصة بيها، ولو كان الخطأ 401، ممكن نوجه المستخدم للصفحة المناسبة:

<div dir="auto" align="left">

```typescript
intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>> {
  const token: string = 'invalid token';
  req = req.clone({ headers: req.headers.set('Authorization', 'Bearer ' + token) });

  return next.handle(req).pipe(
    catchError(err => {
      console.error(err);
      if (err instanceof HttpErrorResponse) {
        console.log(err.status, err.statusText);
        if (err.status === 401) {
          // توجيه المستخدم لصفحة تسجيل الدخول
        }
      }
      return of(err); // بترجع الخطأ كـ Observable
    })
  );
}
```

</div>

### إلغاء الطلب باستخدام EMPTY

#### ليه ممكن نحتاج نلغي الrequest

لو المستخدم مش مسجّل دخول مثلاً، ممكن نلغي الطلب عشان ما يتبعتش للسيرفر، وده بنعمله بإرجاع EMPTY (اللي هو Observable فاضي).

<div dir="auto" align="left">

```typescript
import { EMPTY } from 'rxjs';

intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>> {
  if (NotLoggedIn) {
    return EMPTY; // الطلب مش هيتبعت
  }

  return next.handle(req);
}
```

</div>

</div>

## Why Handle Errors?

[⬆️ Back to Top](#top4)

<div dir="auto" align="right">

#### في Angular، التعامل مع errors جزء مهم من تصميم التطبيق لأن JavaScript ممكن ترمي errors في أي وقت يحصل فيه حاجة غلط. مثلاً

##### 1 - لو استخدمنا متغير مش موجود.

##### 2- لو القيمة اللي قدمناها خارج scope المسموح بيه.

##### 3- أو لو فيه مشكلة في الكود نفسه زي إن الكتابة غير صحيحة.

##### 4- أو لو القيمة مش من النوع اللي المفروض تكون عليه.

بجانب الحاجات دي، ممكن يحصل errors غير متوقعة زي انقطاع الاتصال، مفيش إنترنت، أو HTTP errors زي المستخدم غير مصرح له أو إن (Session) انتهت.

### التعامل مع HTTP Errors

الـ HTTP Errors بتحصل لما نبعت request باستخدام HttpClient في Angular. الـ errors دي ممكن تكون إما من السيرفر (زي مستخدم غير مسموح أو انتهاء الجلسة)، أو من عند العميل (زي فشل الاتصال). الفكرة إن HttpClient بيقدر يتعامل مع الـ HTTP responses، والـ errors بتتقسم لنوعين رئيسيين:

##### الErrors من السيرفر: زي ما يكون المستخدم غير مصرح له (401 Unauthorized) أو انتهت Session أو السيرفر واقع.

##### الErrors من العميل: زي حصول مشكلة في الاتصال بالشبكة أو عدم القدرة على ارسال الـ request بشكل صحيح.

### Client-Side Errors

الأخطاء اللي بتحصل في الكود مباشرة بتتسمى Client-Side Errors، ودي بيتم التعامل معاها عن طريق ErrorHandler وهو الـ default error handler اللي Angular بيستخدمه عشان يمسك أي exception غير متوقع.

### Global Error Handler

بشكل افتراضي، ErrorHandler في Angular بيمسك كل errors اللي بتحصل في التطبيق، لكن دوره بيقتصر على طباعتها في الـ console. لكن في التطبيقات الكبيرة، لازم يكون عندنا Global Error Handler مخصص عشان نقدر نعرض رسائل واضحة للمستخدم أو نبعت التقارير دي للسيرفر لمتابعة errors.

### خطوات عمل Global Error Handler

##### بنعمل سيرفس جديد بتimplements من ErrorHandler.

##### نستخدم الـ handleError

### مثال بسيط

<div dir="auto" align="left">

```typescript
import { ErrorHandler, Injectable } from "@angular/core";

@Injectable()
export class GlobalErrorHandlerService implements ErrorHandler {
  handleError(error) {
    console.error("An error occurred:", error.message);
    alert("An error occurred, please try again later!");
  }
}
```

</div>

### inject another service in Global Error Handler

ممكن تحتاج إنك تستخدم service زي Router عشان تعمل توجيه للمستخدم لصفحة مخصصة للخطأ. بس Angular بتعمل الـ Error Handler قبل ما باقي الـ services تبقى جاهزة، عشان كده بنستخدم حاجة اسمها Injector عشان نحقن الservice يدويًا.

<div dir="auto" align="left">

```typescript
import { ErrorHandler, Injectable, Injector } from "@angular/core";
import { Router } from "@angular/router";

@Injectable()
export class GlobalErrorHandlerService implements ErrorHandler {
  constructor(private injector: Injector) {}

  handleError(error) {
    let router = this.injector.get(Router);
    console.log("Navigating to error page");
    router.navigate(["/error"]);
  }
}
```

</div>
</div>
<hr/>

## What is HttpErrorResponse?

[⬆️ Back to Top](#top4)

<div dir="auto" align="right">
في Angular، التعامل مع HTTP Errors حاجة أساسية عشان تخلي التطبيق بتاعك أكتر استقرارًا. لما يحصل error أثناء عملية الـ HTTP، Angular بيغلف الـ error ده في object اسمه HttpErrorResponse، وبعد كده بيرجعه للتطبيق بتاعك.

ال object ده فيه معلومات مهمة عن الـ error زي سبب المشكلة والـ status code (زي 401 Unauthorized أو 404 Not Found). الـ HttpErrorResponse بيحتوي على الـ error اللي حصل سواء من السيرفر أو من الكود بتاع العميل.

</div>
<hr/>

## How Can Catching Errors in HTTP Request?

[⬆️ Back to Top](#top4)

<div dir="auto" align="right">

### في Angular، ممكن تمسك الـ HTTP errors في 3 أماكن مختلفة:

##### في الـ Component

##### في الـ Service

##### على المستوى العام باستخدام HTTP Interceptor

### التعامل مع Errors في الـ Component

أنت ممكن تمسك الـ HTTP errors في الكومبوننت بعد ما تعمل request. على سبيل المثال، لو أنت عامل GitHubService عشان تجيب البيانات من API زي الـ Repositories الخاصة بمستخدم، هتكتب subscribe للـ HTTP request في الكومبوننت عشان تتعامل مع الـ response والـ error.

#### في الكومبوننت، الـ subscribe بياخد 3 callbacks:

##### success: لما الـ request ينجح.

##### error: لو حصل error في الـ request.

##### completed: لما الـ observable ينتهي بدون مشاكل.

<div dir="auto" align="left">

```typescript
public getRepos() {
  this.loading = true;
  this.errorMessage = "";
  this.githubService.getRepos(this.userName)
    .subscribe(
      (response) => { // Next callback
        console.log('response received');
        this.repos = response;
      },
      (error) => { // Error callback
        console.error('error caught in component');
        this.errorMessage = error;
        this.loading = false;
      }
    );
}
```

</div>
✨ هنا لو حصل error زي URL غلط، الـ error هيتخزن في الـ errorMessage وتقدر تتعامل معاه في الـ UI، وتظهر رسالة للمستخدم.

### التعامل مع Errors في الـ Service

أنت كمان ممكن تمسك الـ HTTP errors في الـ service اللي بيعمل الـ request باستخدام الـ catchError من مكتبة RxJS.

<div dir="auto" align="left">

```typescript
getRepos(userName: string): Observable<any> {
  return this.http.get<repos[]>(this.baseURL + 'usersY/' + userName + '/repos')
    .pipe(
      catchError((err) => {
        console.log('error caught in service');
        console.error(err);
        return throwError(err); // رمي الـ error تاني عشان الكومبوننت يتعامل معاه
      })
    );
}

```

</div>
 ✨هنا بنمسك الـ error في الـ service نفسه، وممكن نعمل معاه حاجة زي طباعة رسالة أو إرسالها لملف لوج، وبعد كده بنرميه تاني عشان الكومبوننت يعرف يتعامل معاه.

### التعامل مع Errors على المستوى العام باستخدام Interceptor

لما تيجي تتعامل مع HTTP errors اللي بتحصل كتير (زي Unauthorized 401 أو Not Found 404)، مش منطقي إنك تمسك كل error في كل component أو service. هنا بييجي دور الـ HTTP Interceptor. الـ interceptor هو سيرفس بيشتغل في الخلفية وبيمسك كل request وresponse وبيعمل interception للـ errors عشان يتعامل معاها.

#### مثال لإنشاء HTTP Interceptor

 <div dir="auto" align="left">

```typescript
@Injectable()
export class GlobalHttpInterceptorService implements HttpInterceptor {
  constructor(public router: Router) {}

  intercept(
    req: HttpRequest<any>,
    next: HttpHandler
  ): Observable<HttpEvent<any>> {
    return next.handle(req).pipe(
      catchError((error) => {
        if (error instanceof HttpErrorResponse) {
          switch (error.status) {
            case 401:
              this.router.navigateByUrl("/login");
              break;
            case 403:
              this.router.navigateByUrl("/unauthorized");
              break;
          }
        }
        return throwError(error);
      })
    );
  }
}
```

</div>
لما السيرفر يبعت error response، بيبقى فيه HTTP Status Code بيوضح نوع الـ error، زي 401 (Unauthorized) أو 404 (Not Found). على حسب الكود ده، ممكن نعمل خطوات معينة:

Error 401 (Unauthorized): هنا ممكن نعمل redirect لصفحة تسجيل الدخول.
Error 403 (Forbidden): نقدر نوجه المستخدم لصفحة غير مصرح له بالدخول ليها.

#### 🧨 بعد كده لازم تسجل الـ Interceptor في الـ AppModule

<div dir="auto" align="left">

```typescript
providers: [
  {
    provide: HTTP_INTERCEPTORS,
    useClass: GlobalHttpInterceptorService,
    multi: true,
  },
];
```

</div>

#### 🚀 الـ Interceptor ده هيمسك كل الـ HTTP requests اللي بتمر في التطبيق، ويتعامل مع الأخطاء العامة زي الأخطاء اللي جاية من السيرفر أو مشاكل الشبكة.

</div>
