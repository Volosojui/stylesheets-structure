### Stylesheets Structure (POSTCSS/SCSS/SASS/LESS)

`*` - postcss|scss/sass|less

```
stylesheets/
|
|-- (postcss|scss/sass|less)/
|   |
|   |-- base/
|   |   |-- reset.*
|   |   |-- normalize.*
|   |   |-- grid.*
|   |   ...
|   |
|   |-- global/
|   |   |-- variables.*
|   |   |-- mixins.*
|   |   |-- placeholders.*
|   |   |-- helpers.*
|   |   |-- states.*
|   |   ...
|   |
|   |-- fonts/
|   |   |-- ptsans.*
|   |   |-- fonts.*
|   |   ...
|   |
|   |-- partials/
|   |   |-- foo/
|   |   |   |-- variables.*
|   |   |   |-- mixins.*
|   |   |   |-- placeholders.*
|   |   |   |-- foo.*
|   |   |
|   |   |-- bar/
|   |   |   |-- variables.*
|   |   |   |-- mixins.*
|   |   |   |-- placeholders.*
|   |   |   |-- bar.*
|   |   ...
|   |
|   |-- vendors/
|   |   |-- jquery-bootstrap-datepicker.*
|   |   ...
|   |
|   |-- pages/
|   |   |-- landing/
|   |   |   |-- ios/
|   |   |   |-- android/
|   |   ...
|   |
|   |-- bundle.*
|
|-- local.*
|-- production.*
```
