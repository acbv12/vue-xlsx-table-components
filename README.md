# vue-xlsx-table

> vue-xlsx-table-components
> 无需上传，查看xlsx或xls表格的组件，基于xlsx.js，在[vue-xlsx-table](https://github.com/GeoffZhu/vue-xlsx-table)基础上修改
# Install
```
npm install --save vue-xlsx-table-components
```
# Import
```
    import vueXlsxTable from 'vue-xlsx-table-components'
    components: {
        "vue-xlsx-table": vueXlsxTable
    }
```
# Usage
```
<vue-xlsx-table @on-select-file="handleSelectedFile" :readAsBS="true">上传Excel文件</vue-xlsx-table>
```
# Options
| Option           |  Default  | Description          |
| ---------------- |:---------:|:--------------------:|
| readAsBS         |   true    |read as binary string |

# Events
| Option           |   param   | Description                     |
| ---------------- |:---------:|:-------------------------------:|
| on-select-file   |   data    | called after excel analyzed     |


## demo Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
