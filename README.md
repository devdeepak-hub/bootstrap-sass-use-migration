Migrated scss code of bootstrap to support latest sass feature *@use*. 

*Bootstrap doesn't support latest module system*

**USAGE**

Required partials
```scss
@use '~bootstrap-sass-use-migration/scss/variables';
@use '~bootstrap-sass-use-migration/scss/mixins';
```
**DO NOT USE FUNCTION PARTIAL**


For theming [load module with configuration](https://sass-lang.com/documentation/at-rules/use#configuration), All sass variables in bootstrap are supported.
```scss
@use '~bootstrap-sass-use-migration/scss/variable' with ($primary:red, $body-bg:yellow);
```

To add optional scss partials
```scss
@use '~bootstrap-sass-use-migration/scss/reboot';
@use '~bootstrap-sass-use-migration/scss/alert';
@use '~bootstrap-sass-use-migration/scss/vendor/rfs';
```






