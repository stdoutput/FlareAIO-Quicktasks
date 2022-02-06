![](https://www.flarebots.com/images/logo.png)
# FlareAIO-Quicktasks
Quicktasks Documentation for FlareAIO 3.5.x

FlareAIO quicktask links should always point to the following host, port and path:  ```http://127.0.0.1:5559/quicktask```

In the querystring, you then specify the quicktask input as follows: ```?product=product1``` multiple inputs are also supported and a random input from the provided list will then be chosen in the bot. To submit multiple product inputs, format as follows: ```?product=product1,product2,...```

You can choose to start quicktasks via **URL**, **PID** or **SKU** - Find which stores support which input type [here](#sites)

# URL
This is pretty straight-forward. Just submit the product URL in the product parameter:
```http://127.0.0.1:5559/quicktask?product=https://www.footpatrol.fr/product/flarebots/455613_footpatrolfr/```

# PID
Use a PID (Product ID) - corresponding to a product on a website:
```http://127.0.0.1:5559/quicktask?product=455613_footpatrolfr```

# SKU
Use a SKU (Stock Keeping Unit) - usually corresponding to a specific size / variation of a product:
```http://127.0.0.1:5559/quicktask?product=16233377.0195243332015,16233377.0195243332008,16233377.0195243331995```

# Sites
- Aw-Lab
	- SKU
	- PID
- Courir
	- SKU 
	- PID
- Footasylum
	- PID
- Footlocker
	- SKU (Corresponding to a product here)
- Mesh Stores (Size?, TheHipStore, Footpatrol, JD Sports)
	- SKU
	- PID
- Solebox / Snipes / Onygo
	- SKU
	- PID
