 # HEROTABLE MODULE ✅ HEROAPPS LLC DONE BY 👨‍💻 [KATHEESKUMAR](mailto:katheeskumar@outlook.com)

> **Initialize HeroTable On Document**

```html
<div id="exampleTable"></div>
```
> **Add HeroTable Vanila Javascript Module on document Bottom**

```html
<script src="hero-table.js"></script>
```
> **Configure Hero Table after inserting HeroTable Module**

```js
var table = new heroTable({
    element: "#exampleTable",
    title: "Example Table",
    data : [],
    url: "http://localhost/addrbook/users.json",
    search: true,
    sort: true,
    serverSide: false,
});
```

 -  `element` : Required `string` id or class attribute.

 -  `title` : Optional `string` for table title.

 -  `data` : Manualy put json data with key value. example data given on document bottom. 

 -  `url` : Enter url `string` format to expect returning output as json response.

 -  `search` : Enable or disbale table search use `true` or `false`

 -  `sort` : Sort column data acending and decending order use `true` or `false`

 -  `serverSide` : Required `true` or `false`, *if you enter `true` automatically disabling local search and sort.*


> **Sample Data for table rendering**

```json
[
    {
        "id": 1,
        "productName": "RICE",
        "productPrice": 15000,
        "date_create": "2019-06-13",
        "quantity": 200,
        "productCategory": "2",
        "action": "<button>Edit</button> <button>Delete</button>"
    },
    {
        "id": 2,
        "productName": "FISH",
        "productPrice": 9000,
        "date_create": "2020-06-13",
        "quantity": 765,
        "productCategory": "1",
        "action": "<button>Edit</button> <button>Delete</button>"
    },
    {
        "id": 3,
        "productName": "YAM",
        "productPrice": 200000,
        "date_create": "2021-06-13",
        "quantity": 210,
        "productCategory": "5",
        "action": "<button>Edit</button> <button>Delete</button>"
    }
]
```
