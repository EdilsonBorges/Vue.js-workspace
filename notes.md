Progressive JavaScript framework
- focused on building user interfaces
- works in the 'view layer' only
- easily integraded into other projects/libs
- capable of powering adv SPAs
- uses virtual dom


Vue offers
- Reactive interfaces
- Declarative Rendering (dynamic variables)
- Data Binding (some like angular2, two-way data binding)
- Directives
- Template Logic
- Components & Nesting
- Event Handling
- Computed Properties
- CSS Transitions & Animation
- Custom Filters


Composing with Components
- The component system is another important concept in Vue, because it’s an abstraction that allows
us to build large-scale applications composed of small, self-contained, and often reusable components.

Directives
- Special attributes with the v- prefix that does something to the DOM
- Reactivley applies side effects to the DOM when the value of its expression changes
<element v-directiveld="[argument:] expression [| filters...]">
</element>
examples:
    <span>{{msg}}</span> // basic interpolation
    <span v-text="msg"></span> // using the v-text directive
    <span v-html="msg"></span> // parses html
    <span v-once="{{msg}}"></span> // one-time interpolation