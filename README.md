## GorilaScraper
![peroncho](peracho.jpeg "Peron hizo google")

## Usage
Once you installed all the packages, run the script with `-h` argument to see how it works
```bash
$ python3 download_images.py -h
usage: download_images.py [-h] keyword

positional arguments:
  keyword     the keyword to search

optional arguments:
    -h, --help  show this help message and exit
```
Therefore, to search something, simply type
```bash
$ python3 download_images.py <your keyword>
```

## Installation
1- Instalar python requirements
```bash
pip install -r requirements.txt
```
2- Install ChromeDriver 
```bash
sudo apt-get install chromium-chromedriver
```
3- Add PATH variable to ChromeDriver
```bash
export PATH=$PATH:/usr/lib/chromium-browser/
```
