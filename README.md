# anova-react-guide
Just my compilation to start react js project

## Project creation
You can use either the ordinary create-react-app (https://reactjs.org/docs/installation.html) or my favourite, use the fork (https://github.com/kitze/custom-react-scripts). This way we can still use the ordinary create-react-app but we dont need to eject if we want to use several features such as:
1. Decorators
2. babel-preset-stage-0
3. Less
4. Sass
5. CSS modules
6. Sass modules
7. Less modules
8. Stylus modules
Read the article [here](https://medium.com/@kitze/configure-create-react-app-without-ejecting-d8450e96196a)

## Redux related library
In react, state management is important, thats why we use redux. These are the needed library for that:
1. [redux](https://github.com/reactjs/redux)
2. [react-redux](https://github.com/reactjs/react-redux)
3. [redux-promise](https://github.com/acdlite/redux-promise) 

## Form validation
Still research for this, but here are my list:
1. [Lesha react-validation](https://github.com/Lesha-spr/react-validation)
2. [formsy-react](https://github.com/christianalfoni/formsy-react)
3. [react-form-with-constraint](https://github.com/tkrotoff/react-form-with-constraints)
4. [vacuumlabs react-custom-validation](https://github.com/vacuumlabs/react-custom-validation)
5. article on [medium](https://medium.com/@rajaraodv/adding-a-robust-form-validation-to-react-redux-apps-616ca240c124)
6. article on [learnetto](https://learnetto.com/blog/how-to-do-simple-form-validation-in-reactjs)
7. the most used [redux-form](https://redux-form.com/7.1.2/examples/)

## Request or post to API
We can use the new fetch() method (https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch). But I think [axios](https://github.com/axios/axios) is doing nice job.

## Login and authentication
Read this nice [article](https://medium.com/the-many/adding-login-and-authentication-sections-to-your-react-or-react-native-app-7767fd251bd1) on how implement login and authentication, and it works with react-router.

## React routing
There's no doubt you need to have [react-router](https://github.com/ReactTraining/react-router) for your routing needs, it has routing support for react native as well. Read the article [here](https://medium.com/@pshrmn/a-simple-react-router-v4-tutorial-7f23ff27adf)

## UI purposes (CSS frameworks)
There are various css frameworks for React now, but I'm gonna stick with [bootstrap](http://getbootstrap.com/) for now. There are bootstrap react component now, you can get it [here](https://react-bootstrap.github.io/). 

If you're looking for bootstrap+ framework, check out [Shards](https://designrevision.com/demo/shards/). It already have more components such as datetimepicker, slider, etc.

But I also have compiled other CSS frameworks that commonly used now, some of it are listed from this [article](https://hackernoon.com/the-coolest-react-ui-frameworks-for-your-new-react-app-ad699fffd651):
1. [Material-UI](http://www.material-ui.com/)
2. [Semantic-UI React](https://react.semantic-ui.com/introduction)
3. [Ant-Design](https://ant.design/)

## Alert system
There are several alert system, one is [toastr](https://github.com/tomchentw/react-toastr) but my preference are [s-alert](https://github.com/juliancwirko/react-s-alert).

## Modal/Dialog/Confirm
Its a bit hard to find the suitable one for react, but i think [this](https://github.com/haradakunihiko/react-confirm) is good, it can handle custome dialog library with custom layout and also can handle complex input from the modal window.

## Grid
As for grids, we can use this [react-data-grid](https://github.com/adazzle/react-data-grid), this grid still not have pagination, for that purpose, use [react-paginate](https://www.npmjs.com/package/react-paginate)

## Code convention
I think the Airbnb code convention are nice to follow (https://github.com/airbnb/javascript/tree/master/react).

## Google maps component
Use [this](https://github.com/tomchentw/react-google-maps) component, its the most complete for now
