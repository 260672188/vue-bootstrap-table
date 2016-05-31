---
title: data
weight: 1
---

```html
<div id="table">
    <bootstrap-table :options="options"></bootstrap-table>
</div>
```

```javascript
new Vue({
    el: '#table',
    components: {
        'bootstrap-table': BootstrapTable
    },
    data: {
        options: {
            columns: [
                {
                    title: 'Item ID',
                    field: 'id'
                },
                {
                    field: 'name',
                    title: 'Item Name'
                }, {
                    field: 'price',
                    title: 'Item Price'
                }
            ],
            data: [
                {
                    "id": 0,
                    "name": "Item 0",
                    "price": "$0"
                },
                {
                    "id": 1,
                    "name": "Item 1",
                    "price": "$1"
                },
                {
                    "id": 2,
                    "name": "Item 2",
                    "price": "$2"
                },
                {
                    "id": 3,
                    "name": "Item 3",
                    "price": "$3"
                },
                {
                    "id": 4,
                    "name": "Item 4",
                    "price": "$4"
                },
                {
                    "id": 5,
                    "name": "Item 5",
                    "price": "$5"
                },
                {
                    "id": 6,
                    "name": "Item 6",
                    "price": "$6"
                },
                {
                    "id": 7,
                    "name": "Item 7",
                    "price": "$7"
                },
                {
                    "id": 8,
                    "name": "Item 8",
                    "price": "$8"
                },
                {
                    "id": 9,
                    "name": "Item 9",
                    "price": "$9"
                }
            ]
        }
    }
});
```