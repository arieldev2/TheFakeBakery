# The Fake Bakery
<img src="https://github.com/arieldev2/TheFakeBakery/blob/main/thefakebakery.jpg" />

<strong>Fake REST API for testing or prototyping. The Fake Bakery makes use of <a href="https://github.com/typicode/json-server">json-server</a>.</strong>

<h2>Data</h2>
<ul>
  <li>40 breads with images.</li>
  <li>2 Categories: Donut and milk bread.</li>
</ul> 

```bash
{
    "breads": [
      {
        "id": 1,
        "name": "Strawberry donut",
        "description": "Donut with strawberry glaze.",
        "price": 1.00,
        "category": "donut",
        "image": "http://localhost:3000/images/donut1.png"
      },
      {
        "id": 2,
        "name": "Strawberry yoghurt donut",
        "description": "Donut with strawberry yoghurt glaze.",
        "price": 1.00,
        "category": "donut",
        "image": "http://localhost:3000/images/donut2.png"
      }]
}
```

<h2>Installation</h2>
<p>Clone the repository and then run "npm install" inside the folder.</p>

```bash
npm install
```
<h2>Use</h2>

```bash
npx json-server --watch db.json
```

<h3>The server is running on <a href="http://localhost:3000/breads">http://localhost:3000/breads</a></h3>

<h2>Paginate</h2>

```bash
GET /breads?_page=5
GET /breads?_page=5&_limit=5
```




