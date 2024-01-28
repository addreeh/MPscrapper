# MPscrapper

A python web scraping script crafted to automate data extraction from the [MYPROTEIN](https://www.myprotein.com/) shopping cart. If you want to receive alerts, you can join this [Telegram channel](https://t.me/mpscrapper) where the price of the products is checked daily. This is what the alerts channel looks like.

![image](https://github.com/addreeh/MPscrapper/assets/74270582/f778fd12-43d4-4aa1-b812-ae4bc8c1e39f)



## Installation
To use the script you need to have installed Firefox and Python.
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.

```bash
pip install -r requirements.txt
```

This script is ready to work and store data in a MongoDB database. If you want to use the same system, you will need to install [MongoDB](https://www.mongodb.com/docs/manual/installation/). If you only want to display the current prices of the products, you can use NoDB script.

## Usage
The command to use Python will depend on the operating system; typically, in Ubuntu, *python3* is used, and in Windows, *python*. However, it will all depend on your Python installation on the system.

To run the script with the MongoDB database.
```bash
python3 mp.py
```

To run the script without the MongoDB database.
```bash
python3 mpNoDB.py
```

## Customize It
In the script, only one product is considered, which are the one added to the cart, the [IMPACT WHEY PROTEIN 2,5KG](https://www.myprotein.es/nutricion-deportiva/impact-whey-protein/10530943.html?variation=10530986). If you want the script to include more products, you will need to add them to your shopping cart and insert a new product into the script.

As you can see, each product must have specific information.
![image](https://github.com/addreeh/MPscrapper/assets/74270582/b90cd5fa-f0ec-45d3-96fe-045dcc17fcb9)

To obtain these data, you will need to access the browser's developer tool (F12).
![image](https://github.com/addreeh/MPscrapper/assets/74270582/8867a454-74e0-45b8-9e67-c4eab2e8ec27)

Once you have obtained the data, you simply need to insert a new product into the script.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
