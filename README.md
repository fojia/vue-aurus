**vue-aurus** provides components to build data visualization apps, it's built on top of d3

## Installation

````
npm i vue-aurus
````

## Usage

```vue
<template>
  <div id="app">
    <Sunburst :data="data" />
  </div>
</template>

<script>
import {Sunburst} from 'vue-aurus'

import chartData from '../data/data-sunburst.json';

export default {
    data(){
        return {
            data: chartData
        }    
    },
    components:{
        Sunburst
    }
}
</script>

```

## Implemented charts
* Sunburst
* Swarm
* Bar


## Input data

Full Datasets' examples are in the folder data/data-[chart name].json


