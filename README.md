# Lit snippets

Lit snippets for Visual Studio Code.

## Screenshots

#### JavaScript

![Javascript Demo](https://github.com/litelement-dev/lit-snippets/raw/master/images/screenshot-js.gif)

#### TypeScript

![Typescript Demo](https://github.com/litelement-dev/lit-snippets/raw/master/images/screenshot-ts.gif)

## Features

-   Supports both JavaScript and TypeScript with Lit 3

## List

### Element and Its Property Snippets

| Trigger       | Snippet                                                      |
| ------------- | ------------------------------------------------------------ |
| litbase       | Create LitElement subclasss                                  |
| littemplate   | Create LitElement subclasss with styles and render fn        |
| litprop       | Generate property                                            |
| litquery      | Generate @query property                                     |
| litqueryall   | Generate @queryall property                                  |
| litrender     | Generate render function with lit-html                       |
| litstyles     | Generate `styles` static property                            |
| ctlittemplate | Create @conectate/ct-lit subclasss with styles and render fn |

### Event Related Snippets

| Trigger                             | Snippet                             |
| ----------------------------------- | ----------------------------------- |
| addeventlistener                    | Generate component's event listener |
| litfire \| fire \| litdispatchevent | Generate dispatch of the event      |

### Custom Element [Lifecycle Callback](https://developers.google.com/web/fundamentals/web-components/customelements#reactions) Snippets

| Trigger                  | Snippet                                                                                                                                                                    |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| connectedcallback        | Generate `connectedCallback()`                                                                                                                                             |
| disconnectedcallback     | Generate `disconnectedCallback()`                                                                                                                                          |
| adoptedcallback          | Generate `adoptedCallback()`                                                                                                                                               |
| attributechangedcallback | Generate `attributechangedCallback(_,_,_)`                                                                                                                                 |
| observedattributes       | Generate `static get observedAttributes()` see [Observing changes to attributes](https://developers.google.com/web/fundamentals/web-components/customelements#attrchanges) |

### Other Snippets

| Trigger   | Snippet              |
| --------- | -------------------- |
| importele | Import other element |

## Contact

Issues [issues](https://github.com/litelement-dev/lit-snippet/issues) or for any features, please tweet us [@herberthobregon](https://x.com/herberthobregon).

## License

Please read [License](https://github.com/litelement-dev/lit-snippet/blob/master/LICENSE.md) for more information
