# Test case for [Ionic Framework Issue #23516](https://github.com/ionic-team/ionic-framework/issues/23516#issuecomment-953657370)

Vite with `preact-ts` template + Ionic framework v6.0.0-rc.1

Instructions:
Open [src/app.tsx](./src/app.tsx) in VSCode

Se error for line 23 on Problems tab:

> 'IonApp' cannot be used as a JSX component.
> Its instance type 'IonApp' is not a valid JSX element.
> Type 'IonApp' is missing the following properties from type 'Component<any, any>': state, props, context, setState, forceUpdate

