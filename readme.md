# 12Flat Mobile App

## Libraries and packages

1.  [React Redux](https://github.com/reduxjs/redux) : Global State Management for React
2. [Redux Sauce](https://github.com/infinitered/reduxsauce): Helper library to reduce Redux related code and simplify reducers and action creators
3. [Redux Saga](https://github.com/redux-saga/redux-saga): To support asynchronous calls in redux (i.e. API calls)
4. [API Sauce](https://github.com/infinitered/apisauce): HTTP requests and API calls
5. [React Native Elements](https://react-native-training.github.io/react-native-elements) React Native UI Library
6. [React Navigation](https://reactnavigation.org): Routing and navigation


## Comments
* Navigation and Routing configuration for all interfaces (Customer, Restaurant, Driver, etc) can be found in [app/src/route](app/src/route) folder. 

* Theme and Colors are defined in [app/src/assets/theme](app/src/assets/theme) folder.

* Theme Object is available in all views prop:
    
    ` const {theme} = this.props; `
