# ឯកសារ CSS Flexbox ជាភាសាខ្មែរ

![css-flexbox thumbnail](/_thumbnail_doc/css-flexbox.jpg "CSS-Flexbox Tutorial")

#

## រៀនតាមរយះ Source Code នៅក្នុង Github Repository:

- **Source Code** គឺមានទៅតាម _folder_ ដូច្នេះអ្នកអាចរកនៅក្នុង _folder src / exercises_ បាន!

![github-repository thumbnail](/_thumbnail_doc/github-branches.JPG "Github Repository")

#

## ជំនួយបន្ថែម:

- ដើម្បីរៀនតាម _Tutorial_ មួយនេះឲ្យកាន់តែឆាប់យល់ ឆាប់ចាប់បាន អ្នកគួរមើលវីដេអូ **CSS Flexbox Crush Course** ខ្លះៗដែរ ដើម្បីជាជំនួយក្នុងការសិក្សាវាបន្ថែម។

> Flexbox CSS In 20 Minutes by Traversy Media

[![travery-flexbox-thumbnail](/_thumbnail_doc/traversy-flexbox.jpg)](https://www.youtube.com/watch?v=JJSoEo8JSnc "Flexbox CSS In 20 Minutes")

> Learn Flexbox In 20 Minutes | Learn HTML & CSS | Flexbox Tutorial by Dev Ed

[![deved-flexbox-thumbnail](/_thumbnail_doc/deved-flexbox.jpg)](https://www.youtube.com/watch?v=FTlczfR82mQ "Learn Flexbox In 20 Minutes | Learn HTML & CSS | Flexbox Tutorial")

> Flexbox in CSS | MengSreang Channel

[![mengsreang-flexbox-thumbnail](/_thumbnail_doc/mengsreang-flexbox.jpg)](https://youtu.be/svRsf1M2gGc "Flexbox in CSS | MengSreang Channel")

#

## តម្រូវការមុននឹងអាចសិក្សា CSS Flexbox:

- ត្រូវមានចំណេះដឹងទាក់ទងនឹង **HTML** និង **CSS** ខ្លះៗដើម្បីងាយស្រួលក្នុងការសិក្សាបន្ថែម!

#

## ចំណុចពិសេសរបស់ CSS Flexbox:

- **Flexbox** នៅក្នុង **CSS** គឺអាចធ្វើការបែងចែក _Container_ នៅក្នុង _Website_ របស់អ្នកឲ្យមានលក្ខណះស្តង់ដា រួមបញ្ចូលជាមួយនឹង _Properties_ ជាច្រើន ដែលផ្តល់ភាពងាយស្រួលដល់អ្នកនៅពេលដែលអ្នកត្រូវការ ហើយវាក៏ផ្នែកមួយដ៏សំខាន់ក្នុងការធ្វើ _Responsive_ ទៅលើ _Website_។

#

## អ្វីទៅជា CSS Flexbox?😯

- **Flexbox** នៅក្នុង **CSS** គឺប្រើសម្រាប់កំណត់ធាតុនីមួយៗឲ្យមានភាពស្រស់ស្អាតនិងងាយស្រួលក្នុងការកំណត់ទីតាំង។ នៅក្នុង **Flexbox** នេះគឺយើងមានរបស់ពីរដែលត្រូវសិក្សាគឺ _Parent Element_ និង _Child Element_។

  <u>**១.Parent Element:**</u>

  - នៅក្នុង **Parent Element** នេះគឺមាន _properties_ ជាច្រើនដែលយើងត្រូវសិក្សា ដែលមានដូចខាងក្រោម:

    - `flex-direction` : ប្រើសម្រាប់កំណត់ទិសដៅនៃធាតុដែលវាផ្ទុក។

    - `flex-wrap` : ប្រើសម្រាប់កំណត់ថាតើធាតុដែលវាផ្ទុកគួរចុះបន្ទាត់ឬអត់ នៅពេលដល់កន្លែងទាល់។

    - `flex-flow` : ប្រើសម្រាប់សរសេរតែក្នុងមួយ _property_ រវាង `flex-direction` និង `flex-wrap`។

    - `justify-content` : ប្រើសម្រាប់តម្រៀបធាតុទៅតាមទិសដៅនៃទិសដៅគោល។

    - `align-content` : ប្រើសម្រាប់តម្រៀបធាតុទៅតាមទិសដៅដែលកាត់ទិសដៅគោល`(សម្រាប់ច្រើនបន្ទាត់)` ។

    - `place-content` : ប្រើសម្រាប់សរសេរតែក្នុងមួយ _properties_ រវាង `justify-content` និង `align-content` ។

    - `align-items` : ប្រើសម្រាប់តម្រៀបទៅតាមទិសដៅដែលកាត់ទិសដៅគោល`(សម្រាប់មួយបន្ទាត់)` ។

  <u>**២.Child Element:**</u>

  - នៅក្នុង **Child Element** នេះគឺមាន _properties_ ជាច្រើនដែលយើងត្រូវសិក្សា ដែលមានដូចខាងក្រោម:

    - `order` : ប្រើសម្រាប់កំណត់លំដាប់។

    - `flex-grow` : ប្រើសម្រាប់ពង្រីកទំហំទៅឲ្យធាតុនូវទំហំដែលនៅសល់។

    - `flex-shrink` : ប្រើសម្រាប់ពង្រួមធាតុ។

    - `flex-basis` : ប្រើសម្រាប់កំណត់ទំហំទៅឲ្យធាតុ។

    - `flex` : ប្រើសម្រាប់សរសេរតែក្នុងមួយ _properties_ រវាង `flex-grow`, `flex-shrink` និង `flex-basis` ។

    - `align-self` : ប្រើសម្រាប់កំណត់តម្លៃដូច `align-items` ប៉ុន្តែសម្រាប់តែមួយធាតុបច្ចុប្បន្ននេះទេ។

## ឧទាហរណ៍:

- ខាងក្រោមនេះគឺជាឧទាហរណ៍ដែលមាន **Container** ដើម្បីក្តោបនូវ **Content** តូចៗ ហើយនៅក្នុង **Content** តូចៗនោះគឺមាន **Box** តូចៗចំនួនប្រាំបន្ថែមទៀត:

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__one">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.container{
    width: 100%;
    position: relative;
}

.content{
  width: 90%;
  height: 360px;
  margin: 30px auto;
  background-color: #6C3483;
  border-radius: 10px;
  border: 2px solid #F39C12;
  padding: 10px;
}

.content__one{

}

.box{
  margin: 10px;
  width: 45%;
  height: 45px;
  border-radius: 10px;
  border: 2px solid #dedede;
}

.box__one{
  background-color: #2ECC71;
}

.box__two{
  background-color: #E74C3C;
}

.box__three{
  background-color: #5499C7;
}

.box__four{
  background-color: #F5B041;
}

.box__five{
  background-color: #85929E;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentOne.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថា នៅក្នុង `class content__one` គឺមិនទាន់មានកំណត់ _style_ អ្វីចូលទៅក្នុងនឹងនោះទេ ដូច្នេះលទ្ធផលបង្ហាញចេញមកគឺ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានលក្ខណះធ្លាក់ចុះជាទម្រង់ជួរឈរ។

#

- ខាងក្រោមនេះគឺយើងប្រើ _flexbox_ នៅក្នុង `class content__two` ហើយដើម្បីអាចប្រើប្រាស់ _flexbox_ គឺយើងប្រើ _property_ `display` ហើយតម្លៃគឺ `flex` គឺមានលក្ខណះបែបនេះ `display: flex;`។

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__two">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__two{
  display: flex;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwo.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__two` គឺមានការកំណត់ _style_ ចំនួនមួយ​ _property_ គឺ `display: flex` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានលក្ខណះឡើងលើជាទម្រង់ជួរដេកវិញ។

#

- ខាងក្រោមនេះគឺយើងប្រើ _flexbox_ ដើម្បីកំណត់ទិសដៅទៅឲ្យ _boxes_ ទាំងអស់នៅក្នុង `class content__three` ហើយដើម្បីអាចកំណត់ទិសដៅបាន យើងអាចប្រើប្រាស់នូវ _property_ `flex-direction` ហើយតម្លៃជាច្រើនដែលមានដូច​ជា `column, row, column-reverse,​ និង​ row-reverse` ។

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__three">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__three{
  display: flex;
  flex-direction: column;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThree.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__three` គឺមានការកំណត់ _style_ ចំនួនមួយ​ _property_ បន្ថែមទៀតគឺ `flex-direction: column` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានទិសដៅជាលក្ខណះធ្លាក់ចុះជាទម្រង់ជួរឈរវិញ។

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__four">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__four{
  display: flex;
  flex-direction: row;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentFour.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__four` គឺមានការកំណត់ _style_ _property_ ដដែលតែមានការផ្លាស់ប្តូរតម្លៃគឺ `flex-direction: row` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានទិសដៅជាលក្ខណះឡើងលើជាទម្រង់ជួរដេកវិញ។

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__five">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__five{
  display: flex;
  flex-direction: column-reverse;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentFive.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__five` គឺមានការកំណត់ _style_ _property_ ដដែលតែមានការផ្លាស់ប្តូរតម្លៃគឺ `flex-direction: column-reverse` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានទិសដៅជាលក្ខណះធ្លាក់ចុះជាទម្រង់ជួរឈរបែបបញ្ច្រាស់ទៅវិញ។

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__six">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__six{
  display: flex;
  flex-direction: row-reverse;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentSix.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__six` គឺមានការកំណត់ _style_ _property_ ដដែលតែមានការផ្លាស់ប្តូរតម្លៃគឺ `flex-direction: row-reverse` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានទិសដៅជាលក្ខណះឡើងលើជាទម្រង់ជួរដេកបែបបញ្ច្រាស់ទៅវិញ។

#

- ខាងក្រោមនេះគឺយើងប្រើ _flexbox_ ដើម្បីកំណត់ការចុះបន្ទាត់របស់ _boxes_ ទាំងអស់នៅក្នុង `class content__seven` ហើយដើម្បីអាចកំណត់ការចុះបន្ទាត់បាន យើងអាចប្រើប្រាស់នូវ _property_ `flex-wrap` ហើយតម្លៃជាច្រើនដែលមានដូច​ជា `wrap, nowrap,  និង wrap-reverse` ។

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__seven">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__seven{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentSeven.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__seven` គឺមានការកំណត់ _style_ ចំនួនមួយ _property_ បន្ថែមទៀតគឺ `flex-wrap: wrap` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានលក្ខណះចុះបន្ទាត់។

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__eight">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__eight{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap-reverse;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentEight.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__eight` គឺមានការកំណត់ _style_ _property_ ដដែលតែមានការផ្លាស់ប្តូរតម្លៃគឺ `flex-wrap: wrap-reverse` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានលក្ខណះចុះបន្ទាត់បែបជាបញ្ច្រាស់ទៅវិញ។ 

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__nine">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__nine{
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentNine.JPG "CSS-Flexbox Exercise")

- ដោយយើងបានឃើញហើយថានៅក្នុង `class content__nine` គឺមានការកំណត់ _style_ _property_ ដដែលតែមានការផ្លាស់ប្តូរតម្លៃគឺ `flex-wrap: nowrap` ដូច្នេះ _boxes_ ទាំងអស់នៅក្នុង _content_ គឺមានលក្ខណះមិនចុះបន្ទាត់ទៅវិញ។ 

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__ten">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__ten{
  display: flex;
  flex-flow: row wrap;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__eleven">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__eleven{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentEleven.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twelve">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twelve{
  display: flex;
  flex-flow: row wrap;
  justify-content: flex-start;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwelve.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirteen">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirteen{
  display: flex;
  flex-flow: row wrap;
  justify-content: flex-end;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirteen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__fourteen">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__fourteen{
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentFourteen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__fifteen">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__fifteen{
  display: flex;
  flex-flow: row wrap;
  justify-content: space-around;
}

```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentFifteen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__sixteen">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__sixteen{
  display: flex;
  flex-flow: row wrap;
  justify-content: space-evenly;
}

```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentSixteen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__seventeen">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__seventeen{
  display: flex;
  flex-flow: row wrap;
  justify-content: stretch;
}

```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentSeventeen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__eighteenth">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__eighteenth{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-content: center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentEighteen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__nineteen">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__nineteen{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-content: flex-start;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentNineteen.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-content: flex-end;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwenty.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__one">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__one{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-content: space-between;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentyOne.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__two">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__two{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-content: space-around;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentyTwo.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__three">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__three{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-content: stretch;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentyThree.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__four">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__four{
  display: flex;
  flex-flow: row wrap;
  place-content: center center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentyFour.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__five">
    <div class="box box__one"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__five{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentyFive.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__six">
    <div class="box box__one"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__six{
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: flex-end;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentySix.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__seven">
    <div class="box box__one"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__seven{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: flex-start;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentySeven.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__eight">
    <div class="box box__one"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__eight{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: stretch;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentyEight.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__twenty__nine">
    <div class="box box__one"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__twenty__nine{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentTwentyNine.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirty.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__one">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__one{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtyOne.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__two">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__two{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-end;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtyTwo.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__three">
    <div class="box box__one">1</div>
    <div class="box box__two">2</div>
    <div class="box box__three">3</div>
    <div class="box box__four">4</div>
    <div class="box box__five">5</div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__three{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}

.content__thirty__three > .box{
  font-size: 24px;
  font-weight: 700;
  text-align: center;
  line-height: 45px;
  color: white;
}

.content__thirty__three > .box__one{
  order: 5;
}

.content__thirty__three > .box__two{
  order: 4;
}

.content__thirty__three > .box__three{
  order: 3;
}

.content__thirty__three > .box__four{
  order: 2;
}

.content__thirty__three > .box__five{
  order: 1;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtyThree.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__four">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__four{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}

.content__thirty__four > .box__one{
  flex-grow: 1;
}

.content__thirty__four > .box__four{
  flex-grow: 1;
}

.content__thirty__four > .box__five{
  flex-grow: 1;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtyFour.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__five">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__five{
  display: flex;
  flex-flow: row nowrap;
  justify-content: center;
  align-items: center;
}

.content__thirty__five > .box__one{
  flex-shrink: 0;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtyFive.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__six">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__six{
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}

.content__thirty__six > .box__two{
  flex-basis: 100px;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtySix.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__seven">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__seven{
  display: flex;
  flex-flow: row nowrap;
  justify-content: center;
  align-items: center;
}

.content__thirty__seven > .box__three{
  flex: 1 0 500px;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtySeven.JPG "CSS-Flexbox Exercise")

#

`src / exercises / index.html`

```js
<div class="container">
  <div class="content content__thirty__eight">
    <div class="box box__one"></div>
    <div class="box box__two"></div>
    <div class="box box__three"></div>
    <div class="box box__four"></div>
    <div class="box box__five"></div>
  </div>
</div>
```

`src / exercises / css / style.css`

```js
.content__thirty__eight{
  display: flex;
  flex-flow: row nowrap;
  justify-content: center;
  align-items: center;
}

.content__thirty__eight > .box__one{
  align-self: center;
}

.content__thirty__eight > .box__two{
  align-self: flex-start;
}

.content__thirty__eight > .box__three{
  align-self: flex-end;
}

.content__thirty__eight > .box__four{
  align-self: stretch;
}

.content__thirty__eight > .box__five{
  align-self: center;
}
```

> លទ្ធផល:

![css-flexbox thumbnail](/_thumbnail_doc/contentThirtyEight.JPG "CSS-Flexbox Exercise")
