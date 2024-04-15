
</head>
<hr>
<span class="span"># How To Use Redirect In Express</span>
<hr>


<br>

<h1 style='color:yellow'>redirect make window location in other url when open the website  page</h1>
<br>

<p>2- Set The Express Display Page</p>

```js
app.get('/',(req,res)=>[
    res.redirect('LinkHere')
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
 <video width="1000" height="540" controls>
  <source src="../videos/bandicam_2024-04-15_02-40-12-788(2).mp4" type="video/mp4">
  <source src="../videos/bandicam_2024-04-15_02-40-12-788(2).ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
