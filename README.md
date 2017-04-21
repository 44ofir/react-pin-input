# react-pin input

[![Build Status](https://travis-ci.org/arunghosh/react-pin-input.svg?branch=master)](https://travis-ci.org/arunghosh/react-pin-input)

**React component for PIN/MPIN like input**

![alt tag](https://github.com/arunghosh/react-pin-input/raw/master/docs/pin.png)


**Installation**
```
npm install react-pin-input
```


**Usage**

The component takes in the length of the PIN and two callback to notifiy change and completion. The ```index``` is the input which is currently in focus.

```javascript
<PinInput length={4} secret onChange={(value, index) => {}} onComplete={(value, index) => {}} />
```



**Configuration**

If you set the ```secret``` attibute, the input will be hidden as shown below.

![alt tag](https://github.com/arunghosh/react-pin-input/raw/master/docs/pin-secret.png)


Setting the ```focus``` attibute will set the default focus on the first input element.


### For developers

To make new build
```
npm run build
```

To run dev server
```
npm run dev
```

To run test
```
npm run test
```

