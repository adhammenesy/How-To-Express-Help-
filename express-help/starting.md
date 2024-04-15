<hr>
<span class="span"># Your First App In Express</span>
<hr>

<p>1- Create App Varible</p>

```js
const app = require('express')();
```

<p>2- Set The Express Display Page</p>

```js
app.get('/',(req,res)=>[
    res.send('My First App In Express')
])
```

<p>3- Set App Listen Port</p>

```js
const port = '3000';
app.listen(port,()=> console.log('express started on port: ',port))
```

<br>
<hr>
<p style='color:white;font-size:25px'># Code Preview:</p>
<hr><br><br>
<p style='color:white;font-size:25px'># Code: </p>

```js
const app = require('express')();

app.get('/',(req,res)=> {
    res.send('My First App In Express')


    const port = '3000';
app.listen(port,()=> console.log('express started on port: ',port))
})
```

<br>

<p style='color:white;font-size:25px'># preview: <br> <img src="../image/hp6hl40i.bmp"></p>
