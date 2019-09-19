# Valiantsin Varabiou

![PersonalImage](https://avatars2.githubusercontent.com/u/47920415)

### Contact Data
[GSM A1.BY](tel:+375447129525) | [Viber](viber://chat?number=375447129525) | [WhatsApp](https://api.whatsapp.com/send?phone=375447129525 ) | [Skype](skype:vorobiov.valentin) | [Main E-Mail](mailto:vxdator@gmail.com) | [EMail 2](mailto:vxdator@yandex.ru)


### Summary
**Goals**
* Professional growth;
* Mastering in JavaScript, both Core JS and frameworks, while working in a good stable company;
* Mastering in [Algorithms](https://vk.com/doc2036633_461668315?hash=3bbe2d53fdb5bac884&dl=973c79ffecb29ce1a0);
* Improving English language verbal skills through regular practice ( translating manuals, writing reviews, customers negotiating, and so on&hellip; );

### Skills
* Programming languages: JavaScript / TypeScript, some PHP ( Drupal 7.x ), basic Git Markdown
* Frameworks: [jQuery](https://api.jquery.com/) ( previously ), [Angular](https://angular.io/docs) 
* Methodologies: [BEM](https://en.bem.info/methodology/)
* Tools : [Git](https://git-scm.com/download/), [VSCode](https://code.visualstudio.com/download), [OSPanel](https://ospanel.io/download/)

### Latest Code Examples

**Vanilla JS**
<details>
<summary> Expand / Collapse </summary>
    <p>

  ```javascript

  function true_binary( n ){
      let max2Power = Math.floor( Math.log2( n ) );
      console.log( 'Maximum 2 power:' , max2Power ) ;
      let currRemnant = n; let currPower = max2Power;
      let currAdd ; 
      let arrTrueBinary = [];

      for( i=max2Power; i>=0 && currRemnant !== 0 ; i-- ){
        currPower = i;
        currAdd = Math.floor( Math.pow( 2, currPower ) ); 
        if( currRemnant > 0 ){
          currRemnant = currRemnant - currAdd;
          arrTrueBinary = [ ...arrTrueBinary, 1 ] ;
          } else {
          currRemnant = currRemnant + currAdd;
          arrTrueBinary = [ ...arrTrueBinary, -1 ];
        }
      }

    return arrTrueBinary;
  }

  ```

    </p>

</details>
<br />
<br />

**PHP** ( Drupal 7 Module )
<details>
<summary> Expand / Collapse </summary>
    <p>

  ```php

  function bs_phone_field_formatter_info() {
    return array(
      'bs_phone_formatter_tel' => array(
        'label' => t('Tel: Link'),
        'field types' => array( 'text' ),
        'settings' => array(
          'formatter' => 'phone_tel',
          'link_alt' => 'null',
          'link_title' => 'null',
          'use_fontawesome' => FALSE,
        )
      ),

      'bs_phone_formatter_viber' => array(
        'label' => t('Viber Link'),
        'field types' => array( 'text' ),
        'settings' => array(
          'formatter' => 'phone_viber',
          'link_alt' => 'null',
          'link_title' => 'null',
          'use_fontawesome' => FALSE,
        )
      ),

      'bs_phone_formatter_whatsapp' => array(
        'label' => t('WhatsApp Link'),
        'field types' => array( 'text' ),
        'settings' => array(
          'formatter' => 'phone_whatsapp',
          'link_alt' => 'null',
          'link_title' => 'null',
          'use_fontawesome' => FALSE,
        )
      ),

    );
  }

  ```

  </p>

</details>

<br />
<br />

**TypeScript** (Angular)
<details>
<summary> Expand / Collapse </summary>

<p>

  ```javascript

  public aclsInList( aCurrency : Currency ):boolean{
    let retRes: boolean = false;
      for ( let j:number =0; j<this.clsChartedCurrencies.length && retRes == false; j++){
        if(  this.clsChartedCurrencies[ j ].ccCurrency.cID == aCurrency.cID ){
          retRes = true;
        }
      }
    return retRes;
  }

  ```

</p>
</details>

<br />
<p>&nbsp;</p>


### Experience
* [Currency Exchange App (Angular) ](https://github.com/ValentinVorobiov/CurrencyExchange.git)
* [Yet Another Drupal 7.x site](https://stalgrad67.ru/)


### Education

* [CodeWars](https://www.codewars.com/users/QelDroma82) Kata's
* [(RU) HTMLAcademy](https://htmlacademy.ru/profile/id1188429)  HTML / CSS Free Blocks
* [Udemy](https://www.udemy.com/user/valiantsin-varabyou/) 
    * [HTML / CSS From Scratch Certificate](https://udemy-certificate.s3.amazonaws.com/image/UC-0TVCEGDX.jpg)
    * [Basics of HTML5 & CSS3](https://udemy-certificate.s3.amazonaws.com/image/UC-55EGZO6E.jpg)
* EPAM Front End October 2018 ( **FE 2018-2** )

### English Level
* Last Test Result: B2 on [EPAM Exam Lab](https://examinator.lab.epam.com)

