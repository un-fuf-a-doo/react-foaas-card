# react-foaas-card

[![Build Status](https://travis-ci.org/circa10a/react-foaas-card.svg?branch=master)](https://travis-ci.org/circa10a/react-foaas-card)

The most offensive of react components

[DEMO](https://circa10a.github.io/react-foaas/card/samples)

## Getting started

### install

```shell
npm install react-foaas-card
```

### component

```javascript
import FoaasCard from 'react-foaas-card';

<FoaasCard
    type="give"
    from="Some asshole"
/>
```

## Props

> For the `type` prop, refer to the [foaas documenation](https://foaas.com/) for supported methods

| prop | type | default | description | example |
|---|---|---|---|--|
| type | string | because | How to tell someone to fuck off| horse |
| from | string  | a react component | The subtitle, italized message | Kevin |
| classes | object | [link to source](https://github.com/circa10a/react-foaas-card/blob/master/src/index.js#L26-L39) | Classes object to configure material card styles |refer to [material ui card api](https://material-ui.com/api/card/) |
| raised | boolean | `true` | Provide shadowing to the card | `false` |
| darkMode | boolean | `false` | Invert text and background color | `true` |
| subtitleStyles | object | `{ fontWeight: 'lighter', fontStyle: 'italic' }` | Styles for subtitles | `{ color: 'red' }` |
| middleFinger | boolean | `true` | Provide a middle finger emoji | `false` |
| middleFingerStyles | object | `{ fontSize: '30px' }` | Styles for span containing middle finger emoji | `{ padding: '50px` } |
