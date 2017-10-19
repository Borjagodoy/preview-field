[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

# \<preview-field\>

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="preview-field.html">
  </template>
</custom-element-demo>
```
-->
```html
 <preview-field
          metions
          hasthags
          text="Y, viéndole @donQuijote de aquella manera, con muestras de tanta tristeza, le dijo: 
          
          #Sábete, Sancho, que no es un hombre más que otro si no hace más que otro. Todas estas borrascas que nos suceden son señales de que presto ha de serenar el tiempo
          y han de sucedernos bien las cosas; porque no es posible que el mal ni el bien sean durables, y de aquí se sigue que, habiendo
          durado mucho el mal, el bien está ya cerca. Así que, no debes congojarte por las desgracias que a mí me suceden, pues a ti
          no te cabe parte dellas.

          Y, viéndole @donQuijote de aquella manera, con muestras de tanta tristeza, le dijo: 
          
          #Sábete, Sancho, que no es un hombre más que otro si no hace más que otro. Todas estas borrascas que nos suceden son señales de que presto
          ha de serenar el tiempo y han de sucedernos bien las cosas; porque no es posible que el mal ni el bien sean durables, y de
          aquí se sigue que, habiendo durado mucho el mal, el bien está ya cerca. Así que, no debes congojarte por las desgracias que
          a mí me suceden, pues a ti no

          https://google.com"
          ></preview-field>

```

### Properties

`<preview-field>` provides the following component properties:

Property | Description | Default
----------------|-------------|----------
`text` | Text to preview | 
`metions` | If true, @ mentieons will be links | `false`
`hashtags` | If true, # will be links  | `false`


### Styling

`<preview-field>` provides the following custom properties and mixins
for styling:

Custom property | Description | Default
----------------|-------------|----------
`--link-color` | Background color of the ripple | Based on the button's color
`--field-class` | Mixin applied to the preview field | `{}`
`--link-class` | Mixin applied to the links | `{}`
