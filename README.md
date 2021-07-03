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

- ត្រូវមានចំណេះដឹងទាក់ទងនឹង HTML និង CSS ខ្លះៗដើម្បីងាយស្រួលក្នុងការសិក្សាបន្ថែម!

#

## ចំណុចពិសេសរបស់ CSS Flexbox:

- **Flexbox** នៅក្នុង **CSS** គឺអាចធ្វើការបែងចែក _Container_ នៅក្នុង _Website_ របស់អ្នកឲ្យមានលក្ខណះស្តង់ដា រួមបញ្ចូលជាមួយនឹង _Properties_ ជាច្រើន ដែលផ្តល់ភាពងាយស្រួលដល់អ្នកនៅពេលដែលអ្នកត្រូវការ ហើយវាក៏ផ្នែកមួយដ៏សំខាន់ក្នុងការធ្វើ _Responsive_ ទៅលើ _Website_។

#

## អ្វីទៅជា CSS Flexbox?😯

- **Flexbox** នៅក្នុង **CSS** គឺប្រើសម្រាប់កំណត់ធាតុនីមួយៗឲ្យមានភាពស្រស់ស្អាតនិងងាយស្រួលក្នុងការកំណត់ទីតាំង។ នៅក្នុង **Flexbox** នេះគឺយើងមានរបស់ពីរដែលត្រូវសិក្សាគឺ _Parent Element_ និង _Child Element_។

  <u>**១.Parent Element:**</u>

  - នៅក្នុង **Parent Element** នេះគឺមាន _properties_ ជាច្រើនដែលយើងត្រូវសិក្សា ដែលមានដូចខាងក្រោម:

    - `flex-direction` : ប្រើសម្រាប់កំណត់ទិសដៅនៃធាតុដែលវាផ្ទុក។

    -	`flex-wrap` : ប្រើសម្រាប់កំណត់ថាតើធាតុដែលវាផ្ទុកគួរចុះបន្ទាត់ឬអត់ នៅពេលដល់កន្លែងទាល់។

    -	`flex-flow` : ប្រើសម្រាប់សរសេរតែក្នុងមួយ _property_ រវាង `flex-direction` និង `flex-wrap`។

    -	`justify-content` : ប្រើសម្រាប់តម្រៀបធាតុទៅតាមទិសដៅនៃទិសដៅគោល។

    -	`align-content` : ប្រើសម្រាប់តម្រៀបធាតុទៅតាមទិសដៅដែលកាត់ទិសដៅគោល`(សម្រាប់ច្រើនបន្ទាត់)` ។

    -	`place-content` : ប្រើសម្រាប់សរសេរតែក្នុងមួយ _properties_ រវាង `justify-content` និង `align-content` ។

    -	`align-items` : ប្រើសម្រាប់តម្រៀបទៅតាមទិសដៅដែលកាត់ទិសដៅគោល`(សម្រាប់មួយបន្ទាត់)` ។

  <u>**២.Child Element:**</u>

    - នៅក្នុង **Child Element** នេះគឺមាន _properties_ ជាច្រើនដែលយើងត្រូវសិក្សា ដែលមានដូចខាងក្រោម:

      -	`order` : ប្រើសម្រាប់កំណត់លំដាប់។

      -	`flex-grow` : ប្រើសម្រាប់ពង្រីកទំហំទៅឲ្យធាតុនូវទំហំដែលនៅសល់។

      -	`flex-shrink` : ប្រើសម្រាប់ពង្រួមធាតុ។

      -	`flex-basis` : ប្រើសម្រាប់កំណត់ទំហំទៅឲ្យធាតុ។

      -	`flex` : ប្រើសម្រាប់សរសេរតែក្នុងមួយ _properties_ រវាង `flex-grow`, `flex-shrink` និង `flex-basis` ។

      -	`align-self` : ប្រើសម្រាប់កំណត់តម្លៃដូច `align-items` ប៉ុន្តែសម្រាប់តែមួយធាតុបច្ចុប្បន្ននេះទេ។
