
#### Diretivas Vue
  
  Todas contém o préfixo `v-`

+ v-if - Somente renderiza objeto se determinada expressão for verdadeira.
+ v-show - Renderiza o objeto mas denpendendo do valor da expressão o atributos 'display:none;' será adicionado na tag.
+ v-else - Negativa do IF
+ v-model - Dada uma determinada variável, configurar ou exibir seu valor.
+ v-bind ou apenas :atributo - Utilizado para modificar valores dos atributos de uma tag, exemplo: `v-bind:src` 
+ v-on ou @atributo - Vincular determinada ação para atributos ( methods)

```javascript
  var app = new Vue({
    el: 'id',
    data: {},
    filters: {
      toUpper(){
        return ...
      }
    },
    methods: {
      sayHello(){
        console.log("Olá (:");
      }
    }
  });
```
