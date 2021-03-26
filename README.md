# Automated Web Browsing Examples

[epj@asc.upenn.edu](epj@asc.upenn.edu)

- *DRAFT 03/26/2021*

**THIS IS A DEMONSTRATION!!!** 🚀

## Running code in Anaconda

Please make sure you have **Anaconda** installed on your computer for test & dev automated web browsing!

- Download at https://www.anaconda.com/products/individual for your OS of choice.

### JupyterHub Notebooks:

Within the Anaconda suite, we will use **JupyterHub** to run Python code in notebooks!

- For more information on the Jupyter ecosystem, please visit https://jupyter.org/hub.

_________

## Selenium with Python

We will use the `selenium` python module to automate our web browsing

- For more info on *Selenium with Python*, please visit https://selenium-python.readthedocs.io/.
- The *pypi* for selenium with helpful instructions at https://pypi.org/project/selenium/.

### Installing Selenium
In your jupyter terminal, install the selenium module:
    
- *Please note: this repo does not describe virtual environment setup for installing selenium, though this is something to consider... More information [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)*

``` bash
pip install selenium --user
``` 
_________

## Downloading the WebDriver

To use Selenium for automating & deploying your code, you must download the corresponding **web driver** for your browser of choice... 

### Common drivers for automated web browsing:

*I use Firefox on MacOS for my test&dev environment!*

- **Firefox**:	https://github.com/mozilla/geckodriver/releases
- **Chrome**:   https://sites.google.com/a/chromium.org/chromedriver/downloads
- **Edge**:     https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
- **Safari**:	https://webkit.org/blog/6900/webdriver-support-in-safari-10/

_________

## Confirming your installation

Please navigate to the [examples](./examples) directory for sample code & notebooks on getting started with web browser automation... 
- Specifically, the notebook [getting_started.ipynb](./examples/getting_started.ipynb) is helpful to *confirm that installation* by running a quick firefox automation!

<img src="https://www.energy.gov/sites/prod/files/2020/08/f77/080720-np-selenium.gif" alt="selenium gif of mathematical rendering" width="250"/>


### Great, Selenium is working on my computer... Now what?

At this point, your are good to go with test & dev for web browsing... Use the **example** notebook for your own specific automated browsing need!

- More information on the Selenium please visit https://www.selenium.dev/

### Containerized Browser vs Local Browser... 

If you have selenium programs that you want to scale up &/or run faster, please consider using **Docker-Selenium** for a *containerized standalone browser* instead of the traditional *GUI application browser*... More info on getting started with this [here](https://github.com/SeleniumHQ/docker-selenium)

- Please also refer to the [docker](./docker) directory for examples on getting started...





