# vuepress-plugin-greysite

## Install

```sh
yarn add -D vuepress-plugin-greysite
# OR npm install -D vuepress-plugin-greysite
```

## Use

```js
module.exports = {
  plugins: ['greysite']
}
```
## Config
```js
module.exports = {
  plugins: [
    ['greysite',{
      startDate: '2020-04-03 00:00:00',
      endDate: '2020-04-04 23:59:59'
    }]
  ]
}
```

## Option(required)

### startDate
- Type: `date`
- Default: `null`   
Set start date for mourning day.

### endDate
- Type: `date`
- Default: `null`    
Set end date for mourning day.