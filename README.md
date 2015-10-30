### Структура папок и файлов стилей (POSTCSS/SCSS/SASS/LESS)

`ext` - (postcss|scss/sass|less)

```
-- stylesheets
   -- postcss|scss/sass|less
      -- base
         -- reset.ext
         -- normalize.ext
         -- grid.ext
            ...
      -- global
         -- variables.ext
         -- mixins.ext
         -- placeholders.ext
         -- helpers.ext
         -- states.ext
            ...
      -- fonts
         -- ptsans.ext
         -- fonts.ext
         ...
      -- partials
         -- foo
            -- variables.ext
            -- mixins.ext
            -- placeholders.ext
            -- foo.ext
         -- bar
            -- variables.ext
            -- mixins.ext
            -- placeholders.ext
            -- bar.ext
            ...
      -- vendors
         -- jquery-bootstrap-datepicker.ext
            ...
      -- pages
         -- landing
            -- ios
            -- android
      -- bundle.ext
   -- local.ext
   -- production.ext
```
